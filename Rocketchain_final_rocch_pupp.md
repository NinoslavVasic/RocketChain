# RocketChain 

# Proof of Authority and Proof of Work Development Chain


# Simplified manual how to create local blockchain 
## Create local network and Genesis Block using `puppeth`


19293@DESKTOP-IJUOLJJ MINGW64 ~/Blockchain-Tools
$ ./puppeth
+-----------------------------------------------------------+
| Welcome to puppeth, your Ethereum private network manager |
|                                                           |
| This tool lets you create a new Ethereum network down to  |
| the genesis block, bootnodes, miners and ethstats servers |
| without the hassle that it would normally entail.         |
|                                                           |
| Puppeth uses SSH to dial in to remote servers, and builds |
| its network components out of Docker containers using the |
| docker-compose toolset.                                   |
+-----------------------------------------------------------+

Please specify a network name to administer (no spaces, hyphens or capital letters please)
> rocketchain

Sweet, you can set this via --network=rocketchain next time!

[32mINFO [0m[04-27|13:51:42.893] Administering Ethereum network           [32mname[0m=rocketchain
[32mINFO [0m[04-27|13:51:42.896] No remote machines to gather stats from

## New genesis configuration

What would you like to do? (default = stats)
 1. Show network stats
 2. Configure new genesis
 3. Track new remote server
 4. Deploy network components
> 2

What would you like to do? (default = create)
 1. Create new genesis from scratch
 2. Import already existing genesis
> 1

Which consensus engine to use? (default = clique)
 1. Ethash - proof-of-work
 2. Clique - proof-of-authority
> 1

Which accounts should be pre-funded? (advisable at least one)
> 0xae3FE208e880ba04d75582FEf2781CDCa27Abe94
> 0x

Should the precompile-addresses (0x1 .. 0xff) be pre-funded with 1 wei? (advisable yes)
>

Specify your chain/network ID if you want an explicit one (default = random)
> 333
[32mINFO [0m[04-27|13:53:34.044] Configured new genesis block

## Generate and export json files into specific folder.   NOTE: only rocketchain.json is needed in further development

What would you like to do? (default = stats)
 1. Show network stats
 2. Manage existing genesis
 3. Track new remote server
 4. Deploy network components
> 2

 1. Modify existing configurations
 2. Export genesis configurations
 3. Remove genesis configuration
> 2

Which folder to save the genesis specs into? (default = current)
  Will create rocketchain.json, rocketchain-aleth.json, rocketchain-harmony.json, rocketchain-parity.json
>
[32mINFO [0m[04-27|13:55:11.194] Saved native genesis chain spec          [32mpath[0m=rocketchain.json
[32mINFO [0m[04-27|13:55:11.198] Saved genesis chain spec                 [32mclient[0m=aleth [32mpath[0m=rocketchain-aleth.json
[32mINFO [0m[04-27|13:55:11.208] Saved genesis chain spec                 [32mclient[0m=parity [32mpath[0m=rocketchain-parity.json
[32mINFO [0m[04-27|13:55:11.210] Saved genesis chain spec                 [32mclient[0m=harmony [32mpath[0m=rocketchain-harmony.json

## Using `geth` create 2 virtual nodes on rocketchain network   
## node1
19293@DESKTOP-IJUOLJJ MINGW64 ~/Blockchain-Tools
$ ./geth account new --datadir node1
INFO [04-27|13:56:16.367] Maximum peer count                       ETH=50 LES=0 total=50
Your new account is locked with a password. Please give a password. Do not forget this password. 
Password:
Repeat password:
## NOTE:  One can choose password and save it in notes for further use.
Your new key was generated

Public address of the key:   0xba51af165c60A32B3d23Df9B332b4A86cED4A1B9
Path of the secret key file: node1\keystore\UTC--2020-04-27T17-56-28.577384300Z--ba51af165c60a32b3d23df9b332b4a86ced4a1b9

- You can share your public address with anyone. Others need it to interact with you.
- You must NEVER share the secret key with anyone! The key controls access to your funds!
- You must BACKUP your key file! Without the key, it's impossible to access account funds!
- You must REMEMBER your password! Without the password, it's impossible to decrypt the key!

## NOTE:  node2

19293@DESKTOP-IJUOLJJ MINGW64 ~/Blockchain-Tools
$ ./geth account new --datadir node2
INFO [04-27|13:58:16.348] Maximum peer count                       ETH=50 LES=0 total=50
Your new account is locked with a password. Please give a password. Do not forget this password.
Password:
Repeat password:
## NOTE:  One can choose password and save it in notes for further use.
Your new key was generated

Public address of the key:   0x5ED637Ae71E68446B8389A2A93c682B7F068b5EF
Path of the secret key file: node2\keystore\UTC--2020-04-27T17-58-28.331921500Z--5ed637ae71e68446b8389a2a93c682b7f068b5ef

- You can share your public address with anyone. Others need it to interact with you.
- You must NEVER share the secret key with anyone! The key controls access to your funds!
- You must BACKUP your key file! Without the key, it's impossible to access account funds!
- You must REMEMBER your password! Without the password, it's impossible to decrypt the key!


## Initialize and tell the nodes to use `rocketchain` genesis block!
## NOTE: At this point rocketchain.json file should be used to initialize node1 and node2


19293@DESKTOP-IJUOLJJ MINGW64 ~/Blockchain-Tools
$ ./geth init rocketchain.json --datadir node1
INFO [04-27|14:00:46.011] Maximum peer count                       ETH=50 LES=0 total=50
INFO [04-27|14:00:46.067] Allocated cache and file handles         database=C:\\Users\\19293\\Blockchain-Tools\\node1\\geth\\chaindata cache=16.00MiB handles=16
INFO [04-27|14:00:46.078] Writing custom genesis block
INFO [04-27|14:00:46.085] Persisted trie from memory database      nodes=355 size=50.43KiB time=997.3µs gcnodes=0 gcsize=0.00B gctime=0s livenodes=1 livesize=0.00B
INFO [04-27|14:00:46.091] Successfully wrote genesis state         database=chaindata hash=ecc69d…c2a6e7
INFO [04-27|14:00:46.095] Allocated cache and file handles         database=C:\\Users\\19293\\Blockchain-Tools\\node1\\geth\\lightchaindata cache=16.00MiB handles=16
INFO [04-27|14:00:46.104] Writing custom genesis block
INFO [04-27|14:00:46.110] Persisted trie from memory database      nodes=355 size=50.43KiB time=997.1µs gcnodes=0 gcsize=0.00B gctime=0s livenodes=1 livesize=0.00B
INFO [04-27|14:00:46.115] Successfully wrote genesis state         database=lightchaindata hash=ecc69d…c2a6e7

19293@DESKTOP-IJUOLJJ MINGW64 ~/Blockchain-Tools
$ ./geth init rocketchain.json --datadir node2
INFO [04-27|14:01:30.806] Maximum peer count                       ETH=50 LES=0 total=50
INFO [04-27|14:01:30.861] Allocated cache and file handles         database=C:\\Users\\19293\\Blockchain-Tools\\node2\\geth\\chaindata cache=16.00MiB handles=16
INFO [04-27|14:01:30.872] Writing custom genesis block
INFO [04-27|14:01:30.879] Persisted trie from memory database      nodes=355 size=50.43KiB time=1.9941ms gcnodes=0 gcsize=0.00B gctime=0s livenodes=1 livesize=0.00B
INFO [04-27|14:01:30.885] Successfully wrote genesis state         database=chaindata hash=ecc69d…c2a6e7
INFO [04-27|14:01:30.891] Allocated cache and file handles         database=C:\\Users\\19293\\Blockchain-Tools\\node2\\geth\\lightchaindata cache=16.00MiB handles=16
INFO [04-27|14:01:30.901] Writing custom genesis block
INFO [04-27|14:01:30.906] Persisted trie from memory database      nodes=355 size=50.43KiB time=997.1µs  gcnodes=0 gcsize=0.00B gctime=0s livenodes=1 livesize=0.00B
INFO [04-27|14:01:30.912] Successfully wrote genesis state         database=lightchaindata hash=ecc69d…c2a6e7
______________________________________________________________________________________________________________________________________________________________________
## Open separate GitBash to start 'rocketchain' mining node1

# NOTE: IT IS IMPORTANT TO CONECT NODES  by entering enode of the node1 when running node2 mining

19293@DESKTOP-IJUOLJJ MINGW64 ~/Blockchain-Tools
$ ./geth --datadir node1 --mine --minerthreads 1
INFO [04-27|14:02:23.751] Starting Geth on Ethereum mainnet...
INFO [04-27|14:02:23.755] Bumping default cache on mainnet         provided=1024 updated=4096
INFO [04-27|14:02:23.758] Maximum peer count                       ETH=50 LES=0 total=50
INFO [04-27|14:02:23.816] Starting peer-to-peer node               instance=Geth/v1.9.13-stable-cbc4ac26/windows-amd64/go1.14.2
INFO [04-27|14:02:23.820] Allocated trie memory caches             clean=614.00MiB dirty=1024.00MiB
INFO [04-27|14:02:23.823] Allocated cache and file handles         database=C:\\Users\\19293\\Blockchain-Tools\\node1\\geth\\chaindata cache=2.00GiB handles=8192
INFO [04-27|14:02:23.864] Opened ancient database                  database=C:\\Users\\19293\\Blockchain-Tools\\node1\\geth\\chaindata\\ancient
INFO [04-27|14:02:23.869] Initialised chain configuration          config="{ChainID: 333 Homestead: 0 DAO: <nil> DAOSupport: false EIP150: 0 EIP155: 0 EIP158: 0 Byzantium: 0 Constantinople: 0 Petersburg: 0 Istanbul: 0, Muir Glacier: <nil>, Engine: ethash}"
INFO [04-27|14:02:23.875] Disk storage enabled for ethash caches   dir=C:\\Users\\19293\\Blockchain-Tools\\node1\\geth\\ethash count=3
INFO [04-27|14:02:23.879] Disk storage enabled for ethash DAGs     dir=C:\\Users\\19293\\AppData\\Local\\Ethash count=2
INFO [04-27|14:02:23.882] Initialising Ethereum protocol           versions="[65 64 63]" network=1 dbversion=<nil>
WARN [04-27|14:02:23.885] Upgrade blockchain database version      from=<nil> to=7
INFO [04-27|14:02:23.888] Loaded most recent local header          number=0 hash=ecc69d…c2a6e7 td=524288 age=10m13s
INFO [04-27|14:02:23.891] Loaded most recent local full block      number=0 hash=ecc69d…c2a6e7 td=524288 age=10m13s
INFO [04-27|14:02:23.894] Loaded most recent local fast block      number=0 hash=ecc69d…c2a6e7 td=524288 age=10m13s
INFO [04-27|14:02:23.899] Regenerated local transaction journal    transactions=0 accounts=0
INFO [04-27|14:02:23.921] Allocated fast sync bloom                size=1.60GiB
INFO [04-27|14:02:23.927] Initialized fast sync bloom              items=355 errorrate=0.000 elapsed=2.992ms
INFO [04-27|14:02:23.934] New local node record                    seq=1 id=33ae5cdc354273e9 ip=127.0.0.1 udp=30303 tcp=30303
INFO [04-27|14:02:23.940] Started P2P networking                   self=enode://3f060a6fbff80b74b272af852cab3b405bef60c2d0009bdb0281155335fe65708d73486fba2ae9e6951bec3ed22ddf358e6f011b2abdf24b93dfff8549beae73@127.0.0.1:30303
INFO [04-27|14:02:23.942] IPC endpoint opened                      url=\\\\.\\pipe\\geth.ipc
INFO [04-27|14:02:23.953] Transaction pool price threshold updated price=1000000000
INFO [04-27|14:02:23.955] Updated mining threads                   threads=1
INFO [04-27|14:02:23.958] Transaction pool price threshold updated price=1000000000
INFO [04-27|14:02:23.960] Etherbase automatically configured       address=0xba51af165c60A32B3d23Df9B332b4A86cED4A1B9
INFO [04-27|14:02:23.963] Commit new mining work                   number=1 sealhash=791643…4fe502 uncles=0 txs=0 gas=0 fees=0 elapsed=0s
INFO [04-27|14:02:27.434] New local node record                    seq=2 id=33ae5cdc354273e9 ip=24.102.91.205 udp=30303 tcp=30303
INFO [04-27|14:02:32.537] Successfully sealed new block            number=1 sealhash=791643…4fe502 hash=a23dfa…bfafe1 elapsed=8.573s
INFO [04-27|14:02:32.537] Commit new mining work                   number=2 sealhash=d94147…31702d uncles=0 txs=0 gas=0 fees=0 elapsed=0s
INFO [04-27|14:02:33.713] 🔨 mined potential block                  number=1 hash=a23dfa…bfafe1
INFO [04-27|14:02:34.015] Looking for peers                        peercount=0 tried=42 static=0
INFO [04-27|14:02:39.067] Successfully sealed new block            number=2 sealhash=d94147…31702d hash=4b2adc…649e09 elapsed=6.530s
INFO [04-27|14:02:39.073] 🔨 mined potential block                  number=2 hash=4b2adc…649e09
INFO [04-27|14:02:39.068] Commit new mining work                   number=3 sealhash=e1998d…9ea604 uncles=0 txs=0 gas=0 fees=0 elapsed=0s
INFO [04-27|14:02:43.013] Successfully sealed new block            number=3 sealhash=e1998d…9ea604 hash=351c20…9cecd5 elapsed=3.944s
INFO [04-27|14:02:43.013] Commit new mining work                   number=4 sealhash=eed156…e025c0 uncles=0 txs=0 gas=0 fees=0 elapsed=0s
INFO [04-27|14:02:43.018] 🔨 mined potential block                  number=3 hash=351c20…9cecd5
INFO [04-27|14:02:44.204] Looking for peers                        peercount=0 tried=49 static=0
INFO [04-27|14:02:54.284] Looking for peers                        peercount=0 tried=50 static=0
INFO [04-27|14:03:04.445] Looking for peers                        peercount=0 tried=55 static=0
INFO [04-27|14:03:14.768] Looking for peers                        peercount=0 tried=49 static=0
INFO [04-27|14:03:24.777] Looking for peers                        peercount=1 tried=58 static=0
INFO [04-27|14:03:25.528] Successfully sealed new block            number=4 sealhash=eed156…e025c0 hash=f42991…281d88 elapsed=42.515s
INFO [04-27|14:03:25.529] Commit new mining work                   number=5 sealhash=69619e…b63163 uncles=0 txs=0 gas=0 fees=0 elapsed=0s
INFO [04-27|14:03:25.534] 🔨 mined potential block                  number=4 hash=f42991…281d88
INFO [04-27|14:03:29.216] Successfully sealed new block            number=5 sealhash=69619e…b63163 hash=f53783…b01ee8 elapsed=3.687s
INFO [04-27|14:03:29.220] 🔨 mined potential block                  number=5 hash=f53783…b01ee8
INFO [04-27|14:03:29.216] Commit new mining work                   number=6 sealhash=2bdf2d…871aad uncles=0 txs=0 gas=0 fees=0 elapsed=0s
INFO [04-27|14:03:34.430] Successfully sealed new block            number=6 sealhash=2bdf2d…871aad hash=e5a0a6…59bef9 elapsed=5.214s
INFO [04-27|14:03:34.435] 🔨 mined potential block                  number=6 hash=e5a0a6…59bef9
INFO [04-27|14:03:34.431] Commit new mining work                   number=7 sealhash=51cea6…859e4d uncles=0 txs=0 gas=0 fees=0 elapsed=997.4µs

## Open separate GitBash to start 'rocketchain' mining node2

# NOTE: IT IS IMPORTANT TO CONECT NODES  by entering enode of the node1 when running node2 mining

19293@DESKTOP-IJUOLJJ MINGW64 ~/Blockchain-Tools
$ ./geth --datadir node2 --port 30304 --rpc --bootnodes "enode://3f060a6fbff80b74b272af852cab3b405bef60c2d0009bdb028115 5335fe65708d73486fba2ae9e6951bec3ed22ddf358e6f011b2abdf24b93dfff8549beae73@127.0.0.1:30303" --ipcdisable
INFO [04-27|14:06:29.259] Starting Geth on Ethereum mainnet...
INFO [04-27|14:06:29.261] Bumping default cache on mainnet         provided=1024 updated=4096
INFO [04-27|14:06:29.265] Maximum peer count                       ETH=50 LES=0 total=50
INFO [04-27|14:06:29.321] Starting peer-to-peer node               instance=Geth/v1.9.13-stable-cbc4ac26/windows-amd64/go1.14.2
INFO [04-27|14:06:29.325] Allocated trie memory caches             clean=614.00MiB dirty=1024.00MiB
INFO [04-27|14:06:29.327] Allocated cache and file handles         database=C:\\Users\\19293\\Blockchain-Tools\\node2\\geth\\chaindata cache=2.00GiB handles=8192
INFO [04-27|14:06:29.369] Opened ancient database                  database=C:\\Users\\19293\\Blockchain-Tools\\node2\\geth\\chaindata\\ancient
INFO [04-27|14:06:29.375] Initialised chain configuration          config="{ChainID: 333 Homestead: 0 DAO: <nil> DAOSupport: false EIP150: 0 EIP155: 0 EIP158: 0 Byzantium: 0 Constantinople: 0 Petersburg: 0 Istanbul: 0, Muir Glacier: <nil>, Engine: ethash}"
INFO [04-27|14:06:29.382] Disk storage enabled for ethash caches   dir=C:\\Users\\19293\\Blockchain-Tools\\node2\\geth\\ethash count=3
INFO [04-27|14:06:29.388] Disk storage enabled for ethash DAGs     dir=C:\\Users\\19293\\AppData\\Local\\Ethash count=2
INFO [04-27|14:06:29.393] Initialising Ethereum protocol           versions="[65 64 63]" network=1 dbversion=<nil>
WARN [04-27|14:06:29.396] Upgrade blockchain database version      from=<nil> to=7
INFO [04-27|14:06:29.400] Loaded most recent local header          number=0 hash=ecc69d…c2a6e7 td=524288 age=14m19s
INFO [04-27|14:06:29.404] Loaded most recent local full block      number=0 hash=ecc69d…c2a6e7 td=524288 age=14m19s
INFO [04-27|14:06:29.408] Loaded most recent local fast block      number=0 hash=ecc69d…c2a6e7 td=524288 age=14m19s
INFO [04-27|14:06:29.413] Regenerated local transaction journal    transactions=0 accounts=0
INFO [04-27|14:06:29.435] Allocated fast sync bloom                size=1.60GiB
INFO [04-27|14:06:29.441] Initialized fast sync bloom              items=355 errorrate=0.000 elapsed=1.995ms
INFO [04-27|14:06:29.448] New local node record                    seq=1 id=92a0a6af1bd98c5b ip=127.0.0.1 udp=30304 tcp=30304
INFO [04-27|14:06:29.454] Started P2P networking                   self=enode://d264dc2b9ebb7cc034d5570e4286b242f120ff2f6545ae365019812e0b3f68a8529ffd329e96e7fe9ea2a7cef11ba88a4590b82231f56dff671e1e9b86bc5306@127.0.0.1:30304
INFO [04-27|14:06:29.455] HTTP endpoint opened                     url=http://127.0.0.1:8545/ cors= vhosts=localhost
INFO [04-27|14:06:36.993] New local node record                    seq=2 id=92a0a6af1bd98c5b ip=127.0.0.1 udp=30304 tcp=30304
INFO [04-27|14:06:38.538] New local node record                    seq=3 id=92a0a6af1bd98c5b ip=24.102.91.205 udp=30304 tcp=30304
INFO [04-27|14:06:39.454] Block synchronisation started
INFO [04-27|14:06:39.460] Imported new state entries               count=3 elapsed=0s      processed=3 pending=0 retry=0 duplicate=0 unexpected=0
INFO [04-27|14:06:39.704] Looking for peers                        peercount=2 tried=47 static=0
INFO [04-27|14:06:40.004] Imported new block headers               count=33 elapsed=544.544ms number=33 hash=c60c63…8f9c22
INFO [04-27|14:06:40.016] Imported new chain segment               blocks=33 txs=0 mgas=0.000 elapsed=4.986ms   mgasps=0.000 number=33 hash=c60c63…8f9c22 dirty=45.14KiB
INFO [04-27|14:06:40.076] Fast sync complete, auto disabling
INFO [04-27|14:06:49.713] Looking for peers                        peercount=1 tried=51 static=0
INFO [04-27|14:06:50.094] Deallocated fast sync bloom              items=358 errorrate=0.000
INFO [04-27|14:06:50.109] Imported new chain segment               blocks=3  txs=0 mgas=0.000 elapsed=2.959ms   mgasps=0.000 number=36 hash=031a90…07f869 dirty=49.25KiB   ignored=1
INFO [04-27|14:06:53.201] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=37 hash=713214…dfd3c4 dirty=50.61KiB
INFO [04-27|14:06:59.782] Looking for peers                        peercount=1 tried=52 static=0
INFO [04-27|14:07:05.050] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=38 hash=4e5213…244353 dirty=51.98KiB
INFO [04-27|14:07:09.457] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=39 hash=aa011e…74e99c dirty=53.35KiB
INFO [04-27|14:07:09.782] Looking for peers                        peercount=1 tried=40 static=0
INFO [04-27|14:07:19.783] Looking for peers                        peercount=1 tried=56 static=0
INFO [04-27|14:07:19.996] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=40 hash=2053bf…a5f509 dirty=54.72KiB
INFO [04-27|14:07:27.207] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.995ms   mgasps=0.000 number=41 hash=88e19a…20035d dirty=56.09KiB
INFO [04-27|14:07:29.783] Looking for peers                        peercount=1 tried=61 static=0
INFO [04-27|14:07:31.129] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=42 hash=28b84f…bcb9d4 dirty=57.45KiB
INFO [04-27|14:07:33.627] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=43 hash=c17ee5…c78d0e dirty=58.82KiB
INFO [04-27|14:07:37.516] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=44 hash=c48d19…59e061 dirty=60.19KiB
INFO [04-27|14:07:39.783] Looking for peers                        peercount=1 tried=61 static=0
INFO [04-27|14:07:49.823] Looking for peers                        peercount=1 tried=45 static=0
INFO [04-27|14:07:50.209] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.990ms   mgasps=0.000 number=45 hash=51abd7…d80c43 dirty=61.56KiB
INFO [04-27|14:07:52.025] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=46 hash=54a458…e7e6ba dirty=62.93KiB
INFO [04-27|14:07:55.288] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.988ms   mgasps=0.000 number=47 hash=d66382…c7e297 dirty=64.29KiB
INFO [04-27|14:07:58.055] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=48 hash=409bbc…a6fb98 dirty=65.66KiB
INFO [04-27|14:07:59.831] Looking for peers                        peercount=1 tried=60 static=0
INFO [04-27|14:08:02.511] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.992ms   mgasps=0.000 number=49 hash=23491a…33a812 dirty=67.03KiB
INFO [04-27|14:08:02.665] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=50 hash=7d9470…ff521a dirty=68.40KiB
INFO [04-27|14:08:05.021] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=51 hash=8cbb89…310257 dirty=69.77KiB
INFO [04-27|14:08:10.026] Looking for peers                        peercount=1 tried=51 static=0
INFO [04-27|14:08:15.331] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.99ms    mgasps=0.000 number=52 hash=806620…75d8e0 dirty=71.14KiB
INFO [04-27|14:08:16.010] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.973ms   mgasps=0.000 number=53 hash=4dbe90…6388d8 dirty=72.50KiB
INFO [04-27|14:08:20.115] Looking for peers                        peercount=1 tried=56 static=0
INFO [04-27|14:08:21.943] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=54 hash=98158b…f34d0e dirty=73.87KiB
INFO [04-27|14:08:30.285] Looking for peers                        peercount=1 tried=53 static=0
INFO [04-27|14:08:40.361] Looking for peers                        peercount=1 tried=65 static=0
INFO [04-27|14:08:41.682] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=55 hash=7f6143…6c061e dirty=75.24KiB
INFO [04-27|14:08:50.388] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=56 hash=01af2b…a57e1f dirty=76.61KiB
INFO [04-27|14:08:50.449] Looking for peers                        peercount=1 tried=44 static=0
INFO [04-27|14:08:56.924] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=57 hash=6ab55a…95de50 dirty=77.98KiB
INFO [04-27|14:09:00.449] Looking for peers                        peercount=1 tried=38 static=0
INFO [04-27|14:09:01.865] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.984ms   mgasps=0.000 number=58 hash=795dfe…958700 dirty=79.34KiB
INFO [04-27|14:09:03.162] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=59 hash=3fbb75…86a17f dirty=80.71KiB
INFO [04-27|14:09:10.449] Looking for peers                        peercount=1 tried=67 static=0
INFO [04-27|14:09:13.614] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=60 hash=785f2a…d76522 dirty=82.08KiB
INFO [04-27|14:09:20.449] Looking for peers                        peercount=1 tried=55 static=0
INFO [04-27|14:09:22.333] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.960ms   mgasps=0.000 number=61 hash=bc95fa…2df067 dirty=83.45KiB
INFO [04-27|14:09:29.532] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=62 hash=bc0417…f2545b dirty=84.82KiB
INFO [04-27|14:09:30.782] Looking for peers                        peercount=1 tried=58 static=0
INFO [04-27|14:09:35.445] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=63 hash=a03851…d70153 dirty=86.19KiB
INFO [04-27|14:09:40.782] Looking for peers                        peercount=1 tried=50 static=0
INFO [04-27|14:09:43.174] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=5.021ms   mgasps=0.000 number=64 hash=1b2373…467d08 dirty=87.55KiB
INFO [04-27|14:09:50.783] Looking for peers                        peercount=2 tried=51 static=0
INFO [04-27|14:09:52.790] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=65 hash=850077…03b2aa dirty=88.92KiB
INFO [04-27|14:09:53.737] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=66 hash=c919d1…ad493a dirty=90.29KiB
INFO [04-27|14:09:59.919] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=67 hash=728fcc…9d63cc dirty=91.66KiB
INFO [04-27|14:10:01.116] Looking for peers                        peercount=1 tried=45 static=0
INFO [04-27|14:10:03.708] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=68 hash=4d6131…a7482f dirty=93.03KiB
INFO [04-27|14:10:11.117] Looking for peers                        peercount=1 tried=39 static=0
INFO [04-27|14:10:15.991] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.988ms   mgasps=0.000 number=69 hash=191431…b45194 dirty=94.39KiB
INFO [04-27|14:10:18.813] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=70 hash=7a9434…c72d76 dirty=95.76KiB
INFO [04-27|14:10:21.228] Looking for peers                        peercount=1 tried=62 static=0
INFO [04-27|14:10:31.402] Looking for peers                        peercount=1 tried=57 static=0
INFO [04-27|14:10:33.763] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.957ms   mgasps=0.000 number=71 hash=726f03…f37f82 dirty=97.13KiB

INFO [04-27|15:00:37.078] Got interrupt, shutting down...
INFO [04-27|15:00:37.083] HTTP endpoint closed                     url=http://127.0.0.1:8545/
INFO [04-27|15:00:37.244] Ethereum protocol stopped
INFO [04-27|15:00:37.250] Transaction pool stopped
INFO [04-27|15:00:37.251] Writing cached state to disk             block=585 hash=9b2c36…0761a3 root=c0b254…b92809
INFO [04-27|15:00:37.255] Persisted trie from memory database      nodes=8 size=2.30KiB time=0s gcnodes=1371 gcsize=496.71KiB gctime=4.9973ms livenodes=382 livesize=138.04KiB
INFO [04-27|15:00:37.260] Writing cached state to disk             block=584 hash=1a50c0…f00c48 root=f23bf2…563f94
INFO [04-27|15:00:37.264] Persisted trie from memory database      nodes=3 size=1.09KiB time=0s gcnodes=0    gcsize=0.00B     gctime=0s       livenodes=379 livesize=136.95KiB
INFO [04-27|15:00:37.268] Writing cached state to disk             block=458 hash=1b102c…1b7c14 root=8ff094…dbde8c
INFO [04-27|15:00:37.272] Persisted trie from memory database      nodes=3 size=1.09KiB time=0s gcnodes=0    gcsize=0.00B     gctime=0s       livenodes=376 livesize=135.86KiB
INFO [04-27|15:00:37.278] Blockchain stopped

19293@DESKTOP-IJUOLJJ MINGW64 ~/Blockchain-Tools
$