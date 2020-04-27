

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
INFO [04-27|14:10:34.691] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.975ms   mgasps=0.000 number=72 hash=22693f…fa6c8c dirty=98.50KiB
INFO [04-27|14:10:38.149] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=73 hash=f60c5a…3e20e9 dirty=99.87KiB
INFO [04-27|14:10:41.735] Looking for peers                        peercount=1 tried=48 static=0
INFO [04-27|14:10:44.680] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=74 hash=70668a…d5a072 dirty=101.24KiB
INFO [04-27|14:10:45.022] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=75 hash=bcadd0…e1f781 dirty=102.60KiB
INFO [04-27|14:10:49.017] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=76 hash=bda8d8…8da8f1 dirty=103.97KiB
INFO [04-27|14:10:51.017] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.990ms   mgasps=0.000 number=77 hash=d850de…a99071 dirty=105.34KiB
INFO [04-27|14:10:51.736] Looking for peers                        peercount=1 tried=58 static=0
INFO [04-27|14:10:52.458] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=78 hash=738ef9…627705 dirty=106.71KiB
INFO [04-27|14:10:54.841] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=79 hash=8b04a0…761ecb dirty=108.08KiB
INFO [04-27|14:10:56.498] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=80 hash=a45d8f…bd0cd7 dirty=109.44KiB
INFO [04-27|14:11:02.341] Looking for peers                        peercount=1 tried=59 static=0
INFO [04-27|14:11:04.903] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=81 hash=08cf4b…967307 dirty=110.81KiB
INFO [04-27|14:11:07.913] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.988ms   mgasps=0.000 number=82 hash=f0cd6e…fb5b76 dirty=112.18KiB
INFO [04-27|14:11:12.342] Looking for peers                        peercount=1 tried=56 static=0
INFO [04-27|14:11:18.972] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.990ms   mgasps=0.000 number=83 hash=11a4e7…d70cf7 dirty=113.55KiB
INFO [04-27|14:11:22.343] Looking for peers                        peercount=1 tried=52 static=0
INFO [04-27|14:11:22.417] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=84 hash=9717c8…a1926b dirty=114.92KiB
INFO [04-27|14:11:28.389] Setting new local account                address=0xae3FE208e880ba04d75582FEf2781CDCa27Abe94
INFO [04-27|14:11:28.395] Submitted transaction                    fullhash=0x2c5394e295f2242689cdeeaea2a3ebb1faf65aae5c6d8766976c0b287fdd3aa1 recipient=0xF55D6A60f576C6c4b1Cd7432e65C06e37E82caC9
INFO [04-27|14:11:30.115] Imported new chain segment               blocks=1  txs=1 mgas=0.021 elapsed=11.968ms  mgasps=1.755 number=85 hash=1c9851…4c35b9 dirty=117.96KiB
INFO [04-27|14:11:32.458] Looking for peers                        peercount=1 tried=70 static=0
INFO [04-27|14:11:42.561] Looking for peers                        peercount=2 tried=56 static=0
INFO [04-27|14:11:52.678] Looking for peers                        peercount=1 tried=62 static=0
INFO [04-27|14:11:53.897] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=86 hash=a024f9…6dfec1 dirty=119.33KiB
INFO [04-27|14:11:59.523] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=87 hash=9da0e1…fac657 dirty=120.70KiB
INFO [04-27|14:12:02.774] Looking for peers                        peercount=2 tried=60 static=0
INFO [04-27|14:12:12.896] Looking for peers                        peercount=1 tried=52 static=0
INFO [04-27|14:12:16.313] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=88 hash=92351c…123af1 dirty=122.07KiB
INFO [04-27|14:12:23.012] Looking for peers                        peercount=1 tried=65 static=0
INFO [04-27|14:12:25.146] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=89 hash=71c90c…01a45a dirty=123.44KiB
INFO [04-27|14:12:25.453] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=90 hash=29007b…08caa9 dirty=124.80KiB
INFO [04-27|14:12:30.207] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.989ms   mgasps=0.000 number=91 hash=59137c…24173f dirty=126.17KiB
INFO [04-27|14:12:33.227] Looking for peers                        peercount=1 tried=54 static=0
INFO [04-27|14:12:33.628] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=92 hash=179b17…61881c dirty=127.54KiB
INFO [04-27|14:12:35.610] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.993ms   mgasps=0.000 number=93 hash=3dbb90…3ee622 dirty=128.91KiB
INFO [04-27|14:12:35.632] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=94 hash=c4bca5…c7f3d4 dirty=130.28KiB
INFO [04-27|14:12:43.229] Looking for peers                        peercount=1 tried=40 static=0
INFO [04-27|14:12:53.229] Looking for peers                        peercount=1 tried=46 static=0
INFO [04-27|14:12:56.984] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=95 hash=b9cd73…decef1 dirty=131.65KiB
INFO [04-27|14:13:02.193] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=96 hash=1a5d06…11af55 dirty=133.01KiB
INFO [04-27|14:13:03.229] Looking for peers                        peercount=1 tried=60 static=0
INFO [04-27|14:13:04.216] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.018ms   mgasps=0.000 number=97 hash=ac15bf…c32a2f dirty=134.38KiB
INFO [04-27|14:13:05.014] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.967ms   mgasps=0.000 number=98 hash=61b030…84e199 dirty=135.75KiB
INFO [04-27|14:13:12.990] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.988ms   mgasps=0.000 number=99 hash=62c59c…18b466 dirty=137.12KiB
INFO [04-27|14:13:13.230] Looking for peers                        peercount=1 tried=69 static=0
INFO [04-27|14:13:13.663] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=100 hash=191d44…c16cf9 dirty=138.49KiB
INFO [04-27|14:13:23.231] Looking for peers                        peercount=1 tried=53 static=0
INFO [04-27|14:13:24.418] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=101 hash=986d0a…7a7806 dirty=139.85KiB
INFO [04-27|14:13:25.440] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.980ms   mgasps=0.000 number=102 hash=4d4bd6…7b4dcf dirty=141.22KiB
INFO [04-27|14:13:33.250] Looking for peers                        peercount=1 tried=102 static=0
INFO [04-27|14:13:36.694] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=103 hash=9ba156…15d2e3 dirty=142.59KiB
INFO [04-27|14:13:43.294] Looking for peers                        peercount=2 tried=57  static=0
INFO [04-27|14:13:54.231] Looking for peers                        peercount=1 tried=103 static=0
INFO [04-27|14:13:55.711] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=104 hash=a0779b…20f464 dirty=143.96KiB
INFO [04-27|14:13:56.085] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.995ms   mgasps=0.000 number=105 hash=781393…073777 dirty=145.33KiB
INFO [04-27|14:13:58.127] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.002ms   mgasps=0.000 number=106 hash=499028…e4d6da dirty=146.70KiB
INFO [04-27|14:14:00.391] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.990ms   mgasps=0.000 number=107 hash=9ca084…9228c9 dirty=148.06KiB
INFO [04-27|14:14:01.586] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.964ms   mgasps=0.000 number=108 hash=d41857…d5ecf0 dirty=149.43KiB
INFO [04-27|14:14:04.231] Looking for peers                        peercount=1 tried=151 static=0
INFO [04-27|14:14:06.106] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.990ms   mgasps=0.000 number=109 hash=5a0aee…b274ed dirty=150.80KiB
INFO [04-27|14:14:14.035] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=110 hash=b5a88d…d4a24d dirty=152.17KiB
INFO [04-27|14:14:14.266] Looking for peers                        peercount=1 tried=76  static=0
INFO [04-27|14:14:19.069] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=111 hash=b9d620…593cd1 dirty=153.54KiB
INFO [04-27|14:14:21.917] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.958ms   mgasps=0.000 number=112 hash=514025…684a60 dirty=154.90KiB
INFO [04-27|14:14:24.270] Looking for peers                        peercount=1 tried=154 static=0
INFO [04-27|14:14:26.330] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=113 hash=150289…50bbd2 dirty=156.27KiB
INFO [04-27|14:14:34.277] Looking for peers                        peercount=2 tried=111 static=0
INFO [04-27|14:14:37.139] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.987ms   mgasps=0.000 number=114 hash=9a87c1…8640e9 dirty=157.64KiB
INFO [04-27|14:14:42.399] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=115 hash=d81e31…1aaf48 dirty=159.01KiB
INFO [04-27|14:14:43.760] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=4.018ms   mgasps=0.000 number=116 hash=8bd3b2…d9550a dirty=160.38KiB
INFO [04-27|14:14:44.771] Looking for peers                        peercount=1 tried=85  static=0
INFO [04-27|14:14:53.065] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=117 hash=b96d8e…81ba75 dirty=161.75KiB
INFO [04-27|14:14:54.825] Looking for peers                        peercount=1 tried=93  static=0
INFO [04-27|14:14:56.045] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=118 hash=f5d679…4eb272 dirty=163.11KiB
INFO [04-27|14:14:56.991] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=119 hash=a54986…930f94 dirty=164.48KiB
INFO [04-27|14:15:00.657] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=120 hash=11433b…d69a68 dirty=165.85KiB
INFO [04-27|14:15:05.176] Looking for peers                        peercount=1 tried=109 static=0
INFO [04-27|14:15:06.235] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=121 hash=990a3d…296a19 dirty=167.22KiB
INFO [04-27|14:15:07.048] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.979ms   mgasps=0.000 number=122 hash=d87b67…845d8c dirty=168.59KiB
INFO [04-27|14:15:15.559] Looking for peers                        peercount=1 tried=94  static=0
INFO [04-27|14:15:26.027] Looking for peers                        peercount=1 tried=86  static=0
INFO [04-27|14:15:32.509] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=123 hash=dc8f89…a05733 dirty=169.95KiB
INFO [04-27|14:15:36.047] Looking for peers                        peercount=1 tried=75  static=0
INFO [04-27|14:15:36.714] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.995ms   mgasps=0.000 number=124 hash=c912c1…d77789 dirty=171.32KiB
INFO [04-27|14:15:38.699] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=125 hash=6d821a…f85f83 dirty=172.69KiB
INFO [04-27|14:15:42.326] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.986ms   mgasps=0.000 number=126 hash=a2f807…43dff1 dirty=174.06KiB
INFO [04-27|14:15:46.186] Looking for peers                        peercount=1 tried=55  static=0
INFO [04-27|14:15:56.199] Looking for peers                        peercount=1 tried=99  static=0
INFO [04-27|14:15:57.687] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=127 hash=91f907…d6efb9 dirty=175.43KiB
INFO [04-27|14:15:59.059] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=128 hash=82ac15…bd501d dirty=176.79KiB
INFO [04-27|14:16:05.658] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=129 hash=7670b4…52d4eb dirty=176.80KiB
INFO [04-27|14:16:06.319] Looking for peers                        peercount=1 tried=80  static=0
INFO [04-27|14:16:16.384] Looking for peers                        peercount=1 tried=49  static=0
INFO [04-27|14:16:23.548] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=130 hash=bca096…c312e6 dirty=176.80KiB
INFO [04-27|14:16:25.761] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.985ms   mgasps=0.000 number=131 hash=65b97b…3ee2f7 dirty=176.80KiB
INFO [04-27|14:16:26.384] Looking for peers                        peercount=1 tried=62  static=0
INFO [04-27|14:16:31.367] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=132 hash=379eb0…da86e0 dirty=176.80KiB
INFO [04-27|14:16:31.825] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.953ms   mgasps=0.000 number=133 hash=81a809…19df75 dirty=176.80KiB
INFO [04-27|14:16:36.384] Looking for peers                        peercount=1 tried=58  static=0
INFO [04-27|14:16:46.160] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=134 hash=7011b9…67ebec dirty=176.80KiB
INFO [04-27|14:16:46.524] Looking for peers                        peercount=2 tried=53  static=0
INFO [04-27|14:16:55.743] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.990ms   mgasps=0.000 number=135 hash=624d0b…a3e522 dirty=176.80KiB
INFO [04-27|14:16:56.604] Looking for peers                        peercount=1 tried=56  static=0
INFO [04-27|14:16:59.505] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=136 hash=31d44d…548fa0 dirty=176.80KiB
INFO [04-27|14:17:03.759] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.979ms   mgasps=0.000 number=137 hash=8354ae…9c6a18 dirty=176.80KiB
INFO [04-27|14:17:06.718] Looking for peers                        peercount=1 tried=33  static=0
INFO [04-27|14:17:06.848] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.998ms   mgasps=0.000 number=138 hash=c7f625…41f5d6 dirty=176.80KiB
INFO [04-27|14:17:07.249] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=139 hash=a918b0…b35487 dirty=176.80KiB
INFO [04-27|14:17:07.784] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.001ms   mgasps=0.000 number=140 hash=f19d51…bf69bc dirty=176.80KiB
INFO [04-27|14:17:16.736] Looking for peers                        peercount=1 tried=61  static=0
INFO [04-27|14:17:22.808] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=141 hash=3d74c3…e26be1 dirty=176.80KiB
INFO [04-27|14:17:22.906] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=142 hash=2a8170…5de1af dirty=176.80KiB
INFO [04-27|14:17:27.011] Looking for peers                        peercount=1 tried=46  static=0
INFO [04-27|14:17:29.959] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.988ms   mgasps=0.000 number=143 hash=dc478e…ffc959 dirty=176.80KiB
INFO [04-27|14:17:30.181] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.033ms   mgasps=0.000 number=144 hash=ab7773…b2f0be dirty=176.80KiB
INFO [04-27|14:17:30.229] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.028ms   mgasps=0.000 number=145 hash=352055…ec88f2 dirty=176.80KiB
INFO [04-27|14:17:31.160] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=146 hash=faba2b…423b62 dirty=176.80KiB
INFO [04-27|14:17:31.600] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.006ms   mgasps=0.000 number=147 hash=d36aac…3b1490 dirty=176.80KiB
INFO [04-27|14:17:31.607] Mining too far in the future             wait=2s
INFO [04-27|14:17:33.798] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=148 hash=29b6be…62aa9e dirty=176.80KiB
INFO [04-27|14:17:36.730] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=149 hash=0a9c80…c3ebd8 dirty=176.80KiB
INFO [04-27|14:17:37.011] Looking for peers                        peercount=1 tried=50  static=0
INFO [04-27|14:17:40.206] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.961ms   mgasps=0.000 number=150 hash=aaeb56…58ebbc dirty=176.80KiB
INFO [04-27|14:17:44.732] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=151 hash=b06304…b146c9 dirty=176.80KiB
INFO [04-27|14:17:47.034] Looking for peers                        peercount=1 tried=59  static=0
INFO [04-27|14:17:51.110] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=4.017ms   mgasps=0.000 number=152 hash=cfdb6d…762fe0 dirty=176.80KiB
INFO [04-27|14:17:54.551] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=153 hash=7bdcc1…45dec6 dirty=176.80KiB
INFO [04-27|14:17:55.714] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.964ms   mgasps=0.000 number=154 hash=d2c6cf…37e8b4 dirty=176.80KiB
INFO [04-27|14:17:57.035] Looking for peers                        peercount=1 tried=47  static=0
INFO [04-27|14:17:59.490] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=155 hash=406d7d…076274 dirty=176.80KiB
INFO [04-27|14:18:00.658] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.991ms   mgasps=0.000 number=156 hash=bb921e…eb9f07 dirty=176.80KiB
INFO [04-27|14:18:02.707] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.006ms   mgasps=0.000 number=157 hash=a13567…9de892 dirty=176.80KiB
INFO [04-27|14:18:03.091] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=158 hash=020bef…59e332 dirty=176.80KiB
INFO [04-27|14:18:04.580] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=159 hash=9f7c92…7a1f22 dirty=176.80KiB
INFO [04-27|14:18:07.043] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.997ms   mgasps=0.000 number=160 hash=3ecfe0…679d81 dirty=176.80KiB
INFO [04-27|14:18:07.081] Looking for peers                        peercount=2 tried=63  static=0
INFO [04-27|14:18:08.827] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=161 hash=c1264a…5f0267 dirty=176.80KiB
INFO [04-27|14:18:14.297] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=162 hash=f0906a…31a5e2 dirty=176.80KiB
INFO [04-27|14:18:17.151] Looking for peers                        peercount=1 tried=149 static=0
INFO [04-27|14:18:25.028] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=163 hash=a7c7fb…e8ad35 dirty=176.80KiB
INFO [04-27|14:18:26.463] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=164 hash=824dca…81deab dirty=176.80KiB
INFO [04-27|14:18:27.369] Looking for peers                        peercount=1 tried=35  static=0
INFO [04-27|14:18:28.462] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=165 hash=fbc435…935c53 dirty=176.80KiB
INFO [04-27|14:18:32.729] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=166 hash=0b5d12…01b13a dirty=176.80KiB
INFO [04-27|14:18:34.604] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=167 hash=6ca37b…8561ea dirty=176.80KiB
INFO [04-27|14:18:37.506] Looking for peers                        peercount=1 tried=68  static=0
INFO [04-27|14:18:47.519] Looking for peers                        peercount=1 tried=44  static=0
INFO [04-27|14:18:57.632] Looking for peers                        peercount=2 tried=72  static=0
INFO [04-27|14:19:02.661] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=168 hash=1ebc4c…476db7 dirty=176.80KiB
INFO [04-27|14:19:04.926] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.990ms   mgasps=0.000 number=169 hash=9ca6d5…3a64ec dirty=176.80KiB
INFO [04-27|14:19:18.597] Looking for peers                        peercount=1 tried=172 static=0
INFO [04-27|14:19:25.722] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.026ms   mgasps=0.000 number=170 hash=1dea8d…d2dafc dirty=176.80KiB
INFO [04-27|14:19:28.630] Looking for peers                        peercount=1 tried=113 static=0
INFO [04-27|14:19:32.218] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=171 hash=ca6f14…750f0b dirty=176.80KiB
INFO [04-27|14:19:38.785] Looking for peers                        peercount=1 tried=154 static=0
INFO [04-27|14:19:46.551] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=172 hash=2a2f5e…6e2c37 dirty=176.80KiB
INFO [04-27|14:19:48.801] Looking for peers                        peercount=1 tried=64  static=0
INFO [04-27|14:19:50.199] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=173 hash=f46e09…98fcb7 dirty=176.80KiB
INFO [04-27|14:19:51.624] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.951ms   mgasps=0.000 number=174 hash=869577…f4865c dirty=176.80KiB
INFO [04-27|14:19:51.882] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=175 hash=252509…ee33e6 dirty=176.80KiB
INFO [04-27|14:19:56.414] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.035ms   mgasps=0.000 number=176 hash=e5e9e0…071d04 dirty=176.80KiB
INFO [04-27|14:19:59.054] Looking for peers                        peercount=1 tried=140 static=0
INFO [04-27|14:20:00.860] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.988ms   mgasps=0.000 number=177 hash=10e7f8…c4ebd9 dirty=176.80KiB
INFO [04-27|14:20:09.112] Looking for peers                        peercount=2 tried=101 static=0
INFO [04-27|14:20:18.899] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=178 hash=0b01d6…e52502 dirty=176.80KiB
INFO [04-27|14:20:19.123] Looking for peers                        peercount=1 tried=92  static=0
INFO [04-27|14:20:20.361] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=179 hash=4bad02…56b23e dirty=176.80KiB
INFO [04-27|14:20:23.328] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=180 hash=6ceb40…9c2f2a dirty=176.80KiB
INFO [04-27|14:20:29.160] Looking for peers                        peercount=1 tried=83  static=0
INFO [04-27|14:20:38.282] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.002ms   mgasps=0.000 number=181 hash=a46003…f26a26 dirty=176.80KiB
INFO [04-27|14:20:39.332] Looking for peers                        peercount=1 tried=94  static=0
INFO [04-27|14:20:49.566] Looking for peers                        peercount=1 tried=76  static=0
INFO [04-27|14:20:59.761] Looking for peers                        peercount=1 tried=63  static=0
INFO [04-27|14:21:03.680] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=182 hash=0c7aae…3ac19f dirty=176.80KiB
INFO [04-27|14:21:04.045] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=5.984ms   mgasps=0.000 number=183 hash=5a9ab0…661c6d dirty=176.80KiB
INFO [04-27|14:21:09.764] Looking for peers                        peercount=1 tried=12  static=0
INFO [04-27|14:21:14.472] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=184 hash=d08063…af4cf3 dirty=176.80KiB
INFO [04-27|14:21:19.283] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=185 hash=3ad891…546ac6 dirty=176.80KiB
INFO [04-27|14:21:20.095] Looking for peers                        peercount=1 tried=49  static=0
INFO [04-27|14:21:21.909] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=186 hash=363078…7f399e dirty=176.80KiB
INFO [04-27|14:21:24.073] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.989ms   mgasps=0.000 number=187 hash=4e4526…79f48e dirty=176.80KiB
INFO [04-27|14:21:26.645] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=5.986ms   mgasps=0.000 number=188 hash=bb1296…64abf5 dirty=176.80KiB
INFO [04-27|14:21:30.103] Looking for peers                        peercount=1 tried=98  static=0
INFO [04-27|14:21:31.167] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=189 hash=9a5636…08ce06 dirty=176.80KiB
INFO [04-27|14:21:34.893] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=190 hash=1db077…e60fc2 dirty=176.80KiB
INFO [04-27|14:21:40.680] Looking for peers                        peercount=1 tried=51  static=0
INFO [04-27|14:21:43.280] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=191 hash=f036db…79ef4d dirty=176.80KiB
INFO [04-27|14:21:50.771] Looking for peers                        peercount=1 tried=62  static=0
INFO [04-27|14:21:54.597] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=192 hash=21d1ac…7436b9 dirty=176.80KiB
INFO [04-27|14:21:59.238] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.000ms   mgasps=0.000 number=193 hash=a83dd3…fe9bf0 dirty=176.80KiB
INFO [04-27|14:22:00.971] Looking for peers                        peercount=1 tried=48  static=0
INFO [04-27|14:22:10.971] Looking for peers                        peercount=1 tried=75  static=0
INFO [04-27|14:22:11.215] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=5.989ms   mgasps=0.000 number=194 hash=b8a310…33086e dirty=176.80KiB
INFO [04-27|14:22:20.971] Looking for peers                        peercount=1 tried=62  static=0
INFO [04-27|14:22:27.229] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.021ms   mgasps=0.000 number=195 hash=699e47…0b87ca dirty=176.80KiB
INFO [04-27|14:22:28.021] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=196 hash=831d11…734eb0 dirty=176.80KiB
INFO [04-27|14:22:30.971] Looking for peers                        peercount=1 tried=53  static=0
INFO [04-27|14:22:36.108] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=197 hash=5fc893…f6510a dirty=176.80KiB
INFO [04-27|14:22:40.972] Looking for peers                        peercount=1 tried=49  static=0
INFO [04-27|14:22:50.086] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.976ms   mgasps=0.000 number=198 hash=f49009…8154d7 dirty=176.80KiB
INFO [04-27|14:22:50.972] Looking for peers                        peercount=1 tried=64  static=0
INFO [04-27|14:22:56.181] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.988ms   mgasps=0.000 number=199 hash=9d900e…3c9d2e dirty=176.80KiB
INFO [04-27|14:23:01.171] Looking for peers                        peercount=1 tried=71  static=0
INFO [04-27|14:23:03.032] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=200 hash=44b657…e16dbc dirty=176.80KiB
INFO [04-27|14:23:11.649] Looking for peers                        peercount=1 tried=111 static=0
INFO [04-27|14:23:17.419] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.027ms   mgasps=0.000 number=201 hash=feef59…ea4ba3 dirty=176.80KiB
INFO [04-27|14:23:21.649] Looking for peers                        peercount=1 tried=138 static=0
INFO [04-27|14:23:31.659] Looking for peers                        peercount=2 tried=127 static=0
INFO [04-27|14:23:32.439] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=202 hash=ad9ade…ee1c97 dirty=176.80KiB
INFO [04-27|14:23:41.051] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=203 hash=cee70f…2cc8a1 dirty=176.80KiB
INFO [04-27|14:23:41.503] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.998ms   mgasps=0.000 number=204 hash=f8f796…354822 dirty=176.80KiB
INFO [04-27|14:23:41.672] Looking for peers                        peercount=1 tried=104 static=0
INFO [04-27|14:23:46.604] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=205 hash=e20f4c…418da1 dirty=176.80KiB
INFO [04-27|14:23:49.551] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.995ms   mgasps=0.000 number=206 hash=5dbe96…890b82 dirty=176.80KiB
INFO [04-27|14:23:52.053] Looking for peers                        peercount=1 tried=108 static=0
INFO [04-27|14:23:55.704] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=207 hash=150665…fd8db4 dirty=176.80KiB
INFO [04-27|14:23:58.767] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=208 hash=76dde0…a0cc6f dirty=176.80KiB
INFO [04-27|14:24:02.081] Looking for peers                        peercount=1 tried=94  static=0
INFO [04-27|14:24:06.569] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=209 hash=6336c4…e1efb2 dirty=176.80KiB
INFO [04-27|14:24:12.393] Looking for peers                        peercount=1 tried=107 static=0
INFO [04-27|14:24:18.222] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=210 hash=2cdd54…706e71 dirty=176.80KiB
INFO [04-27|14:24:22.399] Looking for peers                        peercount=1 tried=69  static=0
INFO [04-27|14:24:23.438] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=211 hash=eaa548…bd9846 dirty=176.80KiB
INFO [04-27|14:24:31.722] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=212 hash=5edb3d…e70273 dirty=176.80KiB
INFO [04-27|14:24:42.447] Looking for peers                        peercount=1 tried=86  static=0
INFO [04-27|14:24:52.712] Looking for peers                        peercount=1 tried=90  static=0
INFO [04-27|14:25:02.727] Looking for peers                        peercount=1 tried=72  static=0
INFO [04-27|14:25:12.841] Looking for peers                        peercount=1 tried=74  static=0
INFO [04-27|14:25:19.096] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=213 hash=b97760…74eef0 dirty=176.80KiB
INFO [04-27|14:25:19.594] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=214 hash=d960a7…f97145 dirty=176.80KiB
INFO [04-27|14:25:22.943] Looking for peers                        peercount=1 tried=118 static=0
INFO [04-27|14:25:25.705] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=215 hash=ad6a0f…747dfd dirty=176.80KiB
INFO [04-27|14:25:26.250] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=216 hash=242b82…04f4f1 dirty=176.80KiB
INFO [04-27|14:25:32.947] Looking for peers                        peercount=1 tried=65  static=0
INFO [04-27|14:25:34.257] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=217 hash=1dcdba…ebc826 dirty=176.80KiB
INFO [04-27|14:25:38.864] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.979ms   mgasps=0.000 number=218 hash=e2976d…1c1821 dirty=176.80KiB
INFO [04-27|14:25:39.583] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.986ms   mgasps=0.000 number=219 hash=b6f544…600275 dirty=176.80KiB
INFO [04-27|14:25:43.013] Looking for peers                        peercount=2 tried=53  static=0
INFO [04-27|14:25:53.045] Looking for peers                        peercount=1 tried=89  static=0
INFO [04-27|14:25:54.852] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=220 hash=3a7929…2b0acc dirty=176.80KiB
INFO [04-27|14:25:57.020] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=221 hash=0cf843…ab7bbe dirty=176.80KiB
INFO [04-27|14:26:03.087] Looking for peers                        peercount=1 tried=70  static=0
INFO [04-27|14:26:04.094] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=222 hash=fd4db7…4a6f4d dirty=176.80KiB
INFO [04-27|14:26:05.453] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=223 hash=400043…427afb dirty=176.80KiB
INFO [04-27|14:26:09.601] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.959ms   mgasps=0.000 number=224 hash=a565ca…eacf12 dirty=176.80KiB
INFO [04-27|14:26:12.475] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=225 hash=3e9862…d8d32a dirty=176.80KiB
INFO [04-27|14:26:13.098] Looking for peers                        peercount=1 tried=63  static=0
INFO [04-27|14:26:14.233] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=226 hash=bda62d…38a017 dirty=176.80KiB
INFO [04-27|14:26:14.997] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=227 hash=bf7118…3ca6b6 dirty=176.80KiB
INFO [04-27|14:26:15.241] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=228 hash=e0aed6…99dc54 dirty=176.80KiB
INFO [04-27|14:26:18.832] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=229 hash=eb1c24…d427c9 dirty=176.80KiB
INFO [04-27|14:26:19.617] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=230 hash=ee50c9…2c4881 dirty=176.80KiB
INFO [04-27|14:26:22.169] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.985ms   mgasps=0.000 number=231 hash=d7d674…1dab67 dirty=176.80KiB
INFO [04-27|14:26:23.340] Looking for peers                        peercount=1 tried=33  static=0
INFO [04-27|14:26:33.341] Looking for peers                        peercount=1 tried=51  static=0
INFO [04-27|14:26:40.337] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.017ms   mgasps=0.000 number=232 hash=707765…1d400b dirty=176.80KiB
INFO [04-27|14:26:41.809] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.996ms   mgasps=0.000 number=233 hash=3c9a4c…72bf00 dirty=176.80KiB
INFO [04-27|14:26:43.341] Looking for peers                        peercount=1 tried=45  static=0
INFO [04-27|14:26:43.630] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.010ms   mgasps=0.000 number=234 hash=3bdc07…e7dffa dirty=176.80KiB
INFO [04-27|14:26:45.592] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.008ms   mgasps=0.000 number=235 hash=4f5e72…8ab61f dirty=176.80KiB
INFO [04-27|14:26:53.342] Looking for peers                        peercount=1 tried=62  static=0
INFO [04-27|14:26:55.273] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.000ms   mgasps=0.000 number=236 hash=f4850d…7f907a dirty=176.80KiB
INFO [04-27|14:27:03.386] Looking for peers                        peercount=1 tried=71  static=0
INFO [04-27|14:27:04.814] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=237 hash=4be71a…2046b7 dirty=176.80KiB
INFO [04-27|14:27:10.884] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=238 hash=689198…79dd1d dirty=176.80KiB
INFO [04-27|14:27:13.674] Looking for peers                        peercount=1 tried=46  static=0
INFO [04-27|14:27:17.365] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=239 hash=269029…0bd757 dirty=176.80KiB
INFO [04-27|14:27:20.821] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=240 hash=ba5338…9c2544 dirty=176.80KiB
INFO [04-27|14:27:23.731] Looking for peers                        peercount=1 tried=54  static=0
INFO [04-27|14:27:31.898] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.022ms   mgasps=0.000 number=241 hash=444261…45eb49 dirty=176.80KiB
INFO [04-27|14:27:32.028] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.958ms   mgasps=0.000 number=242 hash=7da092…8719f6 dirty=176.80KiB
INFO [04-27|14:27:33.798] Looking for peers                        peercount=2 tried=91  static=0
INFO [04-27|14:27:37.513] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=243 hash=19a9f5…cff6f0 dirty=176.80KiB
INFO [04-27|14:27:41.363] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.983ms   mgasps=0.000 number=244 hash=93564e…5212cb dirty=176.80KiB
INFO [04-27|14:27:42.952] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=245 hash=738796…5a19da dirty=176.80KiB
INFO [04-27|14:27:43.357] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.008ms   mgasps=0.000 number=246 hash=304371…e61185 dirty=176.80KiB
INFO [04-27|14:27:43.872] Looking for peers                        peercount=2 tried=119 static=0
INFO [04-27|14:27:50.114] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=247 hash=ad6c15…e3b1c3 dirty=176.80KiB
INFO [04-27|14:27:50.464] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=248 hash=2db5df…7a26c3 dirty=176.80KiB
INFO [04-27|14:27:51.858] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=249 hash=e42f09…eb2199 dirty=176.80KiB
INFO [04-27|14:27:54.421] Looking for peers                        peercount=1 tried=78  static=0
INFO [04-27|14:27:58.974] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=250 hash=305f1a…aea0a4 dirty=176.80KiB
INFO [04-27|14:28:04.481] Looking for peers                        peercount=1 tried=69  static=0
INFO [04-27|14:28:07.647] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=251 hash=8de52e…a36301 dirty=176.80KiB
INFO [04-27|14:28:14.496] Looking for peers                        peercount=1 tried=103 static=0
INFO [04-27|14:28:15.156] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=252 hash=84e1b3…bd4098 dirty=176.80KiB
INFO [04-27|14:28:19.196] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=253 hash=d962df…345d46 dirty=176.80KiB
INFO [04-27|14:28:20.674] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=254 hash=3da919…bf239d dirty=176.80KiB
INFO [04-27|14:28:24.546] Looking for peers                        peercount=1 tried=134 static=0
INFO [04-27|14:28:25.531] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=255 hash=97242a…b812bd dirty=176.80KiB
INFO [04-27|14:28:34.563] Looking for peers                        peercount=1 tried=81  static=0
INFO [04-27|14:28:40.508] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=256 hash=ebd24b…188f7b dirty=176.80KiB
INFO [04-27|14:28:41.999] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.021ms   mgasps=0.000 number=257 hash=c0ba21…3ba028 dirty=176.80KiB
INFO [04-27|14:28:44.657] Looking for peers                        peercount=2 tried=119 static=0
INFO [04-27|14:28:51.362] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.007ms   mgasps=0.000 number=258 hash=064c5b…7c0d2a dirty=176.80KiB
INFO [04-27|14:28:54.849] Looking for peers                        peercount=1 tried=123 static=0
INFO [04-27|14:28:57.475] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=259 hash=b654ee…ac31c7 dirty=176.80KiB
INFO [04-27|14:28:58.969] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=260 hash=e697a6…f58e1b dirty=176.80KiB
INFO [04-27|14:28:59.718] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=261 hash=1c33fb…539a5c dirty=176.80KiB
INFO [04-27|14:29:03.251] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=262 hash=ce027f…dbf7c6 dirty=176.80KiB
INFO [04-27|14:29:03.741] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=263 hash=b5b866…34584f dirty=176.80KiB
INFO [04-27|14:29:04.997] Looking for peers                        peercount=1 tried=134 static=0
INFO [04-27|14:29:08.008] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=264 hash=430f4e…aabfcc dirty=176.80KiB
INFO [04-27|14:29:15.014] Looking for peers                        peercount=2 tried=93  static=0
INFO [04-27|14:29:18.180] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=4.001ms   mgasps=0.000 number=265 hash=7cc7da…6884f2 dirty=176.80KiB
INFO [04-27|14:29:25.017] Looking for peers                        peercount=1 tried=99  static=0
INFO [04-27|14:29:30.220] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.989ms   mgasps=0.000 number=266 hash=8d1164…b44a3f dirty=176.80KiB
INFO [04-27|14:29:35.047] Looking for peers                        peercount=1 tried=129 static=0
INFO [04-27|14:29:39.431] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.998ms   mgasps=0.000 number=267 hash=779568…4429af dirty=176.80KiB
INFO [04-27|14:29:45.059] Looking for peers                        peercount=1 tried=99  static=0
INFO [04-27|14:29:49.460] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=268 hash=e4bfbf…1429a6 dirty=176.80KiB
INFO [04-27|14:29:56.089] Looking for peers                        peercount=1 tried=70  static=0
INFO [04-27|14:30:01.590] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=269 hash=a6ff78…4abaf1 dirty=176.80KiB
INFO [04-27|14:30:02.403] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.995ms   mgasps=0.000 number=270 hash=1ea78b…b019b2 dirty=176.80KiB
INFO [04-27|14:30:06.393] Looking for peers                        peercount=1 tried=22  static=0
INFO [04-27|14:30:11.871] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=271 hash=fbaebe…5d6c3f dirty=176.80KiB
INFO [04-27|14:30:13.532] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=272 hash=f195e0…b14d61 dirty=176.80KiB
INFO [04-27|14:30:15.504] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.995ms   mgasps=0.000 number=273 hash=ed4581…894cff dirty=176.80KiB
INFO [04-27|14:30:16.734] Looking for peers                        peercount=1 tried=37  static=0
INFO [04-27|14:30:20.127] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.978ms   mgasps=0.000 number=274 hash=76bb7c…f7ae0e dirty=176.80KiB
INFO [04-27|14:30:26.896] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=275 hash=a30d80…ea395c dirty=176.80KiB
INFO [04-27|14:30:27.048] Looking for peers                        peercount=2 tried=45  static=0
INFO [04-27|14:30:32.147] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=276 hash=2b3ef8…a54b37 dirty=176.80KiB
INFO [04-27|14:30:34.832] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=277 hash=87f2f5…a541b9 dirty=176.80KiB
INFO [04-27|14:30:37.148] Looking for peers                        peercount=2 tried=73  static=0
INFO [04-27|14:30:46.650] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.995ms   mgasps=0.000 number=278 hash=7c1d5b…9dfb51 dirty=176.80KiB
INFO [04-27|14:30:47.148] Looking for peers                        peercount=1 tried=63  static=0
INFO [04-27|14:30:49.812] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.983ms   mgasps=0.000 number=279 hash=92dcf5…892883 dirty=176.80KiB
INFO [04-27|14:30:56.727] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.986ms   mgasps=0.000 number=280 hash=8dbc52…329cf2 dirty=176.80KiB
INFO [04-27|14:30:57.149] Looking for peers                        peercount=1 tried=61  static=0
INFO [04-27|14:30:59.536] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=281 hash=85a813…99f676 dirty=176.80KiB
INFO [04-27|14:31:05.994] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=282 hash=89a560…5ed78d dirty=176.80KiB
INFO [04-27|14:31:07.307] Looking for peers                        peercount=1 tried=57  static=0
INFO [04-27|14:31:17.482] Looking for peers                        peercount=1 tried=48  static=0
INFO [04-27|14:31:18.624] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=283 hash=9d2153…9a0462 dirty=176.80KiB
INFO [04-27|14:31:22.231] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=284 hash=931713…38977a dirty=176.80KiB
INFO [04-27|14:31:27.506] Looking for peers                        peercount=1 tried=67  static=0
INFO [04-27|14:31:28.810] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.978ms   mgasps=0.000 number=285 hash=887bce…04974a dirty=176.80KiB
INFO [04-27|14:31:29.343] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.019ms   mgasps=0.000 number=286 hash=2f401d…8344f1 dirty=176.80KiB
INFO [04-27|14:31:37.102] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.965ms   mgasps=0.000 number=287 hash=3966aa…225ff7 dirty=176.80KiB
INFO [04-27|14:31:37.665] Looking for peers                        peercount=1 tried=68  static=0
INFO [04-27|14:31:43.304] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.995ms   mgasps=0.000 number=288 hash=37b2fe…49160f dirty=176.80KiB
INFO [04-27|14:31:47.725] Looking for peers                        peercount=1 tried=28  static=0
INFO [04-27|14:31:51.724] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.978ms   mgasps=0.000 number=289 hash=eb19eb…b5c8d2 dirty=176.80KiB
INFO [04-27|14:31:57.298] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.992ms   mgasps=0.000 number=290 hash=1ac3fe…ca0cf3 dirty=176.80KiB
INFO [04-27|14:31:57.791] Looking for peers                        peercount=1 tried=66  static=0
INFO [04-27|14:32:01.818] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=291 hash=5bfa99…8ef6cc dirty=176.80KiB
INFO [04-27|14:32:05.545] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=292 hash=73cf2f…8b3628 dirty=176.80KiB
INFO [04-27|14:32:07.791] Looking for peers                        peercount=1 tried=49  static=0
INFO [04-27|14:32:08.276] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=293 hash=a58e55…8bf409 dirty=176.80KiB
INFO [04-27|14:32:13.974] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.966ms   mgasps=0.000 number=294 hash=764b25…af8129 dirty=176.80KiB
INFO [04-27|14:32:18.029] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=295 hash=a0787a…4235b4 dirty=176.80KiB
INFO [04-27|14:32:20.161] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=296 hash=55d591…0e62f3 dirty=176.80KiB
INFO [04-27|14:32:25.246] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=297 hash=f669bf…bb9bd3 dirty=176.80KiB
INFO [04-27|14:32:25.903] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=298 hash=83d624…a752ef dirty=176.80KiB
INFO [04-27|14:32:27.889] Looking for peers                        peercount=1 tried=70  static=0
INFO [04-27|14:32:29.933] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=299 hash=5ee72f…e9164c dirty=176.80KiB
INFO [04-27|14:32:32.340] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.993ms   mgasps=0.000 number=300 hash=2bffd6…9c9539 dirty=176.80KiB
INFO [04-27|14:32:32.498] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.961ms   mgasps=0.000 number=301 hash=1f52f1…25a3ca dirty=176.80KiB
INFO [04-27|14:32:37.958] Looking for peers                        peercount=1 tried=113 static=0
INFO [04-27|14:32:42.545] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.023ms   mgasps=0.000 number=302 hash=ae6a0a…0b8129 dirty=176.80KiB
INFO [04-27|14:32:43.816] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.978ms   mgasps=0.000 number=303 hash=c9c3ff…d675f8 dirty=176.80KiB
INFO [04-27|14:32:47.981] Looking for peers                        peercount=2 tried=93  static=0
INFO [04-27|14:32:54.040] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=304 hash=bc3612…62acb6 dirty=176.80KiB
INFO [04-27|14:32:58.015] Looking for peers                        peercount=1 tried=132 static=0
INFO [04-27|14:32:58.116] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=305 hash=b0c029…b3ff10 dirty=176.80KiB
INFO [04-27|14:33:08.017] Looking for peers                        peercount=1 tried=82  static=0
INFO [04-27|14:33:08.569] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=306 hash=ce44c1…105de7 dirty=176.80KiB
INFO [04-27|14:33:18.029] Looking for peers                        peercount=2 tried=133 static=0
INFO [04-27|14:33:28.357] Looking for peers                        peercount=1 tried=82  static=0
INFO [04-27|14:33:38.414] Looking for peers                        peercount=2 tried=82  static=0
INFO [04-27|14:33:41.637] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.988ms   mgasps=0.000 number=307 hash=73581f…c09239 dirty=176.80KiB
INFO [04-27|14:33:45.011] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=308 hash=17fdec…6bd477 dirty=176.80KiB
INFO [04-27|14:33:48.442] Looking for peers                        peercount=1 tried=155 static=0
INFO [04-27|14:33:48.930] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=309 hash=0483e6…b631a8 dirty=176.80KiB
INFO [04-27|14:33:58.474] Looking for peers                        peercount=1 tried=132 static=0
INFO [04-27|14:34:03.140] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=310 hash=67035d…42efdf dirty=176.80KiB
INFO [04-27|14:34:07.791] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.973ms   mgasps=0.000 number=311 hash=f61479…545ebd dirty=176.80KiB
INFO [04-27|14:34:08.505] Looking for peers                        peercount=1 tried=84  static=0
INFO [04-27|14:34:11.731] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=312 hash=e29a84…08c07b dirty=176.80KiB
INFO [04-27|14:34:18.044] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=313 hash=949d8a…7bb218 dirty=176.80KiB
INFO [04-27|14:34:18.506] Looking for peers                        peercount=1 tried=99  static=0
INFO [04-27|14:34:19.550] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=314 hash=1a9150…fb590c dirty=176.80KiB
INFO [04-27|14:34:24.076] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=315 hash=7b072f…4b9532 dirty=176.80KiB
INFO [04-27|14:34:28.573] Looking for peers                        peercount=1 tried=107 static=0
INFO [04-27|14:34:30.935] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=316 hash=276c65…d04029 dirty=176.80KiB
INFO [04-27|14:34:31.505] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=317 hash=1c81b1…57cfce dirty=176.80KiB
INFO [04-27|14:34:36.556] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=318 hash=9699f8…28c329 dirty=176.80KiB
INFO [04-27|14:34:38.579] Looking for peers                        peercount=1 tried=67  static=0
INFO [04-27|14:34:40.263] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=319 hash=befbb3…3b4e17 dirty=176.80KiB
INFO [04-27|14:34:41.806] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=320 hash=82bff8…e609e2 dirty=176.80KiB
INFO [04-27|14:34:48.680] Looking for peers                        peercount=1 tried=64  static=0
INFO [04-27|14:34:50.594] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=321 hash=2f3441…4fd137 dirty=176.80KiB
INFO [04-27|14:34:51.250] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.002ms   mgasps=0.000 number=322 hash=d29a36…7e9dc8 dirty=176.80KiB
INFO [04-27|14:34:53.039] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=323 hash=99072b…8a609a dirty=176.80KiB
INFO [04-27|14:34:53.181] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=324 hash=06fe7e…b45d1a dirty=176.80KiB
INFO [04-27|14:34:58.680] Looking for peers                        peercount=2 tried=62  static=0
INFO [04-27|14:35:00.074] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=325 hash=c5804e…6af3ad dirty=176.80KiB
INFO [04-27|14:35:08.681] Looking for peers                        peercount=1 tried=54  static=0
INFO [04-27|14:35:10.338] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=326 hash=0e3179…4cf144 dirty=176.80KiB
INFO [04-27|14:35:19.015] Looking for peers                        peercount=1 tried=60  static=0
INFO [04-27|14:35:19.406] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.977ms   mgasps=0.000 number=327 hash=709602…2c0997 dirty=176.80KiB
INFO [04-27|14:35:19.421] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=328 hash=e64eb3…b5dc4e dirty=176.80KiB
INFO [04-27|14:35:24.117] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=329 hash=414bb3…231173 dirty=176.80KiB
INFO [04-27|14:35:24.319] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=330 hash=100025…64510b dirty=176.80KiB
INFO [04-27|14:35:25.947] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.980ms   mgasps=0.000 number=331 hash=f7d5d4…3cbde6 dirty=176.80KiB
INFO [04-27|14:35:29.123] Looking for peers                        peercount=1 tried=60  static=0
INFO [04-27|14:35:32.994] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=332 hash=69c8cf…974375 dirty=176.80KiB
INFO [04-27|14:35:39.248] Looking for peers                        peercount=1 tried=61  static=0
INFO [04-27|14:35:48.541] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=333 hash=66c4f5…3eada7 dirty=176.80KiB
INFO [04-27|14:35:49.347] Looking for peers                        peercount=1 tried=44  static=0
INFO [04-27|14:35:54.932] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.989ms   mgasps=0.000 number=334 hash=3c14fd…b31126 dirty=176.80KiB
INFO [04-27|14:35:59.390] Looking for peers                        peercount=1 tried=55  static=0
INFO [04-27|14:35:59.976] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=335 hash=4d73eb…bd1a17 dirty=176.80KiB
INFO [04-27|14:36:00.522] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=336 hash=b8f410…b5f911 dirty=176.80KiB
INFO [04-27|14:36:01.557] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=337 hash=3269f5…3a75ad dirty=176.80KiB
INFO [04-27|14:36:03.724] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=338 hash=c0c270…4ab0a2 dirty=176.80KiB
INFO [04-27|14:36:09.477] Looking for peers                        peercount=1 tried=64  static=0
INFO [04-27|14:36:17.482] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.965ms   mgasps=0.000 number=339 hash=0e1f04…778b30 dirty=176.80KiB
INFO [04-27|14:36:19.521] Looking for peers                        peercount=1 tried=50  static=0
INFO [04-27|14:36:23.078] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=340 hash=f588ec…db14e7 dirty=176.80KiB
INFO [04-27|14:36:28.325] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=341 hash=a99398…d1fb83 dirty=176.80KiB
INFO [04-27|14:36:29.521] Looking for peers                        peercount=2 tried=73  static=0
INFO [04-27|14:36:30.704] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=342 hash=7f8b87…e72158 dirty=176.80KiB
INFO [04-27|14:36:39.521] Looking for peers                        peercount=1 tried=93  static=0
INFO [04-27|14:36:48.091] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.989ms   mgasps=0.000 number=343 hash=bc6d99…c9cb09 dirty=176.80KiB
INFO [04-27|14:36:49.522] Looking for peers                        peercount=2 tried=96  static=0
INFO [04-27|14:36:58.586] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=344 hash=715ea0…53f84a dirty=176.80KiB
INFO [04-27|14:36:58.980] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=345 hash=94de31…10bff0 dirty=176.80KiB
INFO [04-27|14:36:59.701] Looking for peers                        peercount=2 tried=131 static=0
INFO [04-27|14:37:01.835] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=346 hash=eeadad…86e447 dirty=176.80KiB
INFO [04-27|14:37:02.938] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=347 hash=3fe648…95d713 dirty=176.80KiB
INFO [04-27|14:37:09.706] Looking for peers                        peercount=2 tried=47  static=0
INFO [04-27|14:37:12.720] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=348 hash=bc4ed0…c55744 dirty=176.80KiB
INFO [04-27|14:37:13.907] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.988ms   mgasps=0.000 number=349 hash=f0eaa4…234b60 dirty=176.80KiB
INFO [04-27|14:37:15.835] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=4.01ms    mgasps=0.000 number=350 hash=842ccf…fc5a1d dirty=176.80KiB
INFO [04-27|14:37:18.077] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=351 hash=67d451…27e183 dirty=176.80KiB
INFO [04-27|14:37:19.748] Looking for peers                        peercount=1 tried=105 static=0
INFO [04-27|14:37:21.094] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=352 hash=0b2623…290c17 dirty=176.80KiB
INFO [04-27|14:37:29.879] Looking for peers                        peercount=1 tried=147 static=0
INFO [04-27|14:37:35.319] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.993ms   mgasps=0.000 number=353 hash=224efd…d8b8a1 dirty=176.80KiB
INFO [04-27|14:37:39.915] Looking for peers                        peercount=1 tried=100 static=0
INFO [04-27|14:37:42.545] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=354 hash=47073b…9cfba0 dirty=176.80KiB
INFO [04-27|14:37:43.601] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=355 hash=f5ea6b…562d07 dirty=176.80KiB
INFO [04-27|14:37:46.176] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=356 hash=5f6656…0bd225 dirty=176.80KiB
INFO [04-27|14:37:49.926] Looking for peers                        peercount=2 tried=97  static=0
INFO [04-27|14:37:50.486] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=357 hash=710482…326764 dirty=176.80KiB
INFO [04-27|14:37:50.565] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.980ms   mgasps=0.000 number=358 hash=c7f8ff…0f92f9 dirty=176.80KiB
INFO [04-27|14:37:52.352] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=359 hash=ea1be3…24576f dirty=176.80KiB
INFO [04-27|14:37:59.097] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.003ms   mgasps=0.000 number=360 hash=e1e190…df782f dirty=176.80KiB
INFO [04-27|14:37:59.952] Looking for peers                        peercount=1 tried=90  static=0
INFO [04-27|14:38:01.802] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=361 hash=fad106…122fbd dirty=176.80KiB
INFO [04-27|14:38:09.961] Looking for peers                        peercount=1 tried=109 static=0
INFO [04-27|14:38:20.038] Looking for peers                        peercount=1 tried=134 static=0
INFO [04-27|14:38:25.043] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=362 hash=8b09cd…9c01f5 dirty=176.80KiB
INFO [04-27|14:38:30.214] Looking for peers                        peercount=2 tried=99  static=0
INFO [04-27|14:38:30.319] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.018ms   mgasps=0.000 number=363 hash=2a6942…cfe560 dirty=176.80KiB
INFO [04-27|14:38:30.582] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.981ms   mgasps=0.000 number=364 hash=f2e2fd…a34753 dirty=176.80KiB
INFO [04-27|14:38:36.165] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=365 hash=94a055…ec73ce dirty=176.80KiB
INFO [04-27|14:38:36.611] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=366 hash=7bb65c…b45e73 dirty=176.80KiB
INFO [04-27|14:38:40.300] Looking for peers                        peercount=1 tried=51  static=0
INFO [04-27|14:38:50.301] Looking for peers                        peercount=1 tried=111 static=0
INFO [04-27|14:38:51.621] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=367 hash=02efbe…c38380 dirty=176.80KiB
INFO [04-27|14:38:54.064] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.005ms   mgasps=0.000 number=368 hash=0fa1c2…8e73c2 dirty=176.80KiB
INFO [04-27|14:38:55.414] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=369 hash=0db686…b3fce9 dirty=176.80KiB
INFO [04-27|14:39:00.404] Looking for peers                        peercount=1 tried=93  static=0
INFO [04-27|14:39:10.406] Looking for peers                        peercount=1 tried=69  static=0
INFO [04-27|14:39:12.694] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=370 hash=70f8e4…2e2c59 dirty=176.80KiB
INFO [04-27|14:39:20.413] Looking for peers                        peercount=1 tried=82  static=0
INFO [04-27|14:39:22.695] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=371 hash=a8bb5c…8d8912 dirty=176.80KiB
INFO [04-27|14:39:25.641] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.973ms   mgasps=0.000 number=372 hash=4c162c…dafaab dirty=176.80KiB
INFO [04-27|14:39:30.738] Looking for peers                        peercount=1 tried=67  static=0
INFO [04-27|14:39:40.788] Looking for peers                        peercount=1 tried=51  static=0
INFO [04-27|14:39:43.593] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=373 hash=db553e…64c058 dirty=176.80KiB
INFO [04-27|14:39:45.003] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=374 hash=385ec4…179454 dirty=176.80KiB
INFO [04-27|14:39:46.594] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=375 hash=76edd9…3331c8 dirty=176.80KiB
INFO [04-27|14:39:50.924] Looking for peers                        peercount=1 tried=55  static=0
INFO [04-27|14:39:50.926] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=376 hash=40a2a2…56ee64 dirty=176.80KiB
INFO [04-27|14:39:52.990] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=377 hash=285ad9…661543 dirty=176.80KiB
INFO [04-27|14:39:55.534] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=378 hash=ffe309…08e15e dirty=176.80KiB
INFO [04-27|14:39:57.802] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=379 hash=f5cf2c…39bbba dirty=176.80KiB
INFO [04-27|14:40:00.925] Looking for peers                        peercount=2 tried=50  static=0
INFO [04-27|14:40:05.168] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.973ms   mgasps=0.000 number=380 hash=f77f17…0c4723 dirty=176.80KiB
INFO [04-27|14:40:06.942] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.008ms   mgasps=0.000 number=381 hash=5900aa…36619c dirty=176.80KiB
INFO [04-27|14:40:08.570] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=382 hash=36846f…eebdb4 dirty=176.80KiB
INFO [04-27|14:40:09.597] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.964ms   mgasps=0.000 number=383 hash=1b9c7d…679b1f dirty=176.80KiB
INFO [04-27|14:40:10.934] Looking for peers                        peercount=1 tried=65  static=0
INFO [04-27|14:40:13.597] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=384 hash=248d0e…3b5731 dirty=176.80KiB
INFO [04-27|14:40:13.619] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.018ms   mgasps=0.000 number=385 hash=6cddb3…9efd84 dirty=176.80KiB
INFO [04-27|14:40:20.551] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=386 hash=a1377e…17a454 dirty=176.80KiB
INFO [04-27|14:40:20.934] Looking for peers                        peercount=1 tried=51  static=0
INFO [04-27|14:40:31.006] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=387 hash=6ceb85…6a2f7c dirty=176.80KiB
INFO [04-27|14:40:31.270] Looking for peers                        peercount=1 tried=39  static=0
INFO [04-27|14:40:41.280] Looking for peers                        peercount=1 tried=65  static=0
INFO [04-27|14:40:45.998] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=388 hash=c99fa9…aaa4e5 dirty=176.80KiB
INFO [04-27|14:40:47.343] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=389 hash=cb37ca…15c80e dirty=176.80KiB
INFO [04-27|14:40:47.365] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=390 hash=6322d0…bc7647 dirty=176.80KiB
INFO [04-27|14:40:48.049] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.993ms   mgasps=0.000 number=391 hash=44288a…c8a684 dirty=176.80KiB
INFO [04-27|14:40:51.601] Looking for peers                        peercount=1 tried=56  static=0
INFO [04-27|14:40:52.167] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=392 hash=e0e16f…896f88 dirty=176.80KiB
INFO [04-27|14:41:01.602] Looking for peers                        peercount=1 tried=98  static=0
INFO [04-27|14:41:05.405] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=393 hash=685ef9…66e005 dirty=176.80KiB
INFO [04-27|14:41:06.379] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=394 hash=8d4204…b02988 dirty=176.80KiB
INFO [04-27|14:41:11.615] Looking for peers                        peercount=2 tried=131 static=0
INFO [04-27|14:41:21.669] Looking for peers                        peercount=1 tried=67  static=0
INFO [04-27|14:41:31.751] Looking for peers                        peercount=2 tried=144 static=0
INFO [04-27|14:41:35.056] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=395 hash=d13cfc…e5afa2 dirty=176.80KiB
INFO [04-27|14:41:38.759] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=396 hash=780799…503276 dirty=176.80KiB
INFO [04-27|14:41:41.810] Looking for peers                        peercount=1 tried=129 static=0
INFO [04-27|14:41:52.050] Looking for peers                        peercount=1 tried=103 static=0
INFO [04-27|14:41:52.390] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=397 hash=ae4162…c05fe9 dirty=176.80KiB
INFO [04-27|14:41:56.094] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.019ms   mgasps=0.000 number=398 hash=bd11d1…ff60f9 dirty=176.80KiB
INFO [04-27|14:41:58.300] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=399 hash=a82edf…e38451 dirty=176.80KiB
INFO [04-27|14:42:02.054] Looking for peers                        peercount=1 tried=93  static=0
INFO [04-27|14:42:05.394] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=400 hash=bb087d…b39762 dirty=176.80KiB
INFO [04-27|14:42:12.141] Looking for peers                        peercount=2 tried=88  static=0
INFO [04-27|14:42:15.767] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.989ms   mgasps=0.000 number=401 hash=ee9996…bd7873 dirty=176.80KiB
INFO [04-27|14:42:17.804] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.985ms   mgasps=0.000 number=402 hash=ff83de…ab2efd dirty=176.80KiB
INFO [04-27|14:42:22.116] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=403 hash=adec94…e2661d dirty=176.80KiB
INFO [04-27|14:42:22.239] Looking for peers                        peercount=1 tried=57  static=0
INFO [04-27|14:42:23.393] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=404 hash=9f1c0a…24b8c4 dirty=176.80KiB
INFO [04-27|14:42:28.240] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.995ms   mgasps=0.000 number=405 hash=37028a…fdf0b1 dirty=176.80KiB
INFO [04-27|14:42:32.284] Looking for peers                        peercount=1 tried=109 static=0
INFO [04-27|14:42:36.064] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.993ms   mgasps=0.000 number=406 hash=23aaa6…a04a6f dirty=176.80KiB
INFO [04-27|14:42:37.907] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=407 hash=cad6e4…2f7971 dirty=176.80KiB
INFO [04-27|14:42:39.463] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=408 hash=8dc4c4…aa72da dirty=176.80KiB
INFO [04-27|14:42:42.449] Looking for peers                        peercount=1 tried=123 static=0
INFO [04-27|14:42:44.221] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.985ms   mgasps=0.000 number=409 hash=5523a7…67575c dirty=176.80KiB
INFO [04-27|14:42:45.019] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=410 hash=a0e99d…1eb9ad dirty=176.80KiB
INFO [04-27|14:42:50.885] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=411 hash=c1a918…bc8645 dirty=176.80KiB
INFO [04-27|14:42:51.766] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.019ms   mgasps=0.000 number=412 hash=edf669…daeda2 dirty=176.80KiB
INFO [04-27|14:42:52.545] Looking for peers                        peercount=2 tried=84  static=0
INFO [04-27|14:42:54.868] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.985ms   mgasps=0.000 number=413 hash=a581f1…3430b1 dirty=176.80KiB
INFO [04-27|14:42:55.243] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.998ms   mgasps=0.000 number=414 hash=a9744f…97538a dirty=176.80KiB
INFO [04-27|14:42:57.550] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=415 hash=026321…06e46a dirty=176.80KiB
INFO [04-27|14:42:58.939] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=416 hash=201785…3cd62a dirty=176.80KiB
INFO [04-27|14:42:59.670] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.017ms   mgasps=0.000 number=417 hash=f55b62…9538bb dirty=176.80KiB
INFO [04-27|14:43:02.560] Looking for peers                        peercount=1 tried=73  static=0
INFO [04-27|14:43:07.753] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=418 hash=33d54e…242f55 dirty=176.80KiB
INFO [04-27|14:43:10.824] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=419 hash=cc9f70…73233a dirty=176.80KiB
INFO [04-27|14:43:12.562] Looking for peers                        peercount=1 tried=90  static=0
INFO [04-27|14:43:12.598] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=420 hash=e1c749…cbca59 dirty=176.80KiB
INFO [04-27|14:43:13.690] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=421 hash=deabf9…328cda dirty=176.80KiB
INFO [04-27|14:43:16.629] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=422 hash=096771…d7c112 dirty=176.80KiB
INFO [04-27|14:43:22.570] Looking for peers                        peercount=1 tried=102 static=0
INFO [04-27|14:43:24.021] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=423 hash=f3d039…88a038 dirty=176.80KiB
INFO [04-27|14:43:24.830] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.977ms   mgasps=0.000 number=424 hash=9c62b9…717ca4 dirty=176.80KiB
INFO [04-27|14:43:32.619] Looking for peers                        peercount=1 tried=66  static=0
INFO [04-27|14:43:36.757] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=425 hash=a70052…d93412 dirty=176.80KiB
INFO [04-27|14:43:42.704] Looking for peers                        peercount=1 tried=54  static=0
INFO [04-27|14:43:45.685] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=426 hash=d90755…e6588b dirty=176.80KiB
INFO [04-27|14:43:48.609] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=427 hash=a27bba…ea3a57 dirty=176.80KiB
INFO [04-27|14:43:48.714] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.994ms   mgasps=0.000 number=428 hash=6349c6…70d606 dirty=176.80KiB
INFO [04-27|14:43:52.704] Looking for peers                        peercount=1 tried=55  static=0
INFO [04-27|14:43:55.328] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=429 hash=89085d…0899bd dirty=176.80KiB
INFO [04-27|14:44:01.449] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=430 hash=011c23…338014 dirty=176.80KiB
INFO [04-27|14:44:02.901] Looking for peers                        peercount=1 tried=65  static=0
INFO [04-27|14:44:09.340] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=431 hash=4f5969…c336cc dirty=176.80KiB
INFO [04-27|14:44:12.920] Looking for peers                        peercount=2 tried=52  static=0
INFO [04-27|14:44:22.977] Looking for peers                        peercount=1 tried=60  static=0
INFO [04-27|14:44:23.834] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=432 hash=2223ae…a70766 dirty=176.80KiB
INFO [04-27|14:44:24.340] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=433 hash=e978ad…ae64fa dirty=176.80KiB
INFO [04-27|14:44:27.312] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=434 hash=a2fe68…f1497a dirty=176.80KiB
INFO [04-27|14:44:28.274] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=435 hash=18b5bb…70c367 dirty=176.80KiB
INFO [04-27|14:44:33.235] Looking for peers                        peercount=1 tried=64  static=0
INFO [04-27|14:44:34.483] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=4.007ms   mgasps=0.000 number=436 hash=0314fb…55563d dirty=176.80KiB
INFO [04-27|14:44:36.479] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.977ms   mgasps=0.000 number=437 hash=da33cd…fdc1dc dirty=176.80KiB
INFO [04-27|14:44:43.308] Looking for peers                        peercount=1 tried=46  static=0
INFO [04-27|14:44:47.498] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.965ms   mgasps=0.000 number=438 hash=a63730…403770 dirty=176.80KiB
INFO [04-27|14:44:53.310] Looking for peers                        peercount=2 tried=48  static=0
INFO [04-27|14:45:03.487] Looking for peers                        peercount=1 tried=70  static=0
INFO [04-27|14:45:10.633] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.017ms   mgasps=0.000 number=439 hash=6c0603…054c0b dirty=176.80KiB
INFO [04-27|14:45:13.352] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.972ms   mgasps=0.000 number=440 hash=6c479e…e02124 dirty=176.80KiB
INFO [04-27|14:45:13.468] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=441 hash=1e1b55…31fd0a dirty=176.80KiB
INFO [04-27|14:45:13.487] Looking for peers                        peercount=1 tried=53  static=0
INFO [04-27|14:45:23.644] Looking for peers                        peercount=1 tried=51  static=0
INFO [04-27|14:45:24.455] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.959ms   mgasps=0.000 number=442 hash=e1963e…6aa533 dirty=176.80KiB
INFO [04-27|14:45:28.268] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=443 hash=a548d0…e25f1b dirty=176.80KiB
INFO [04-27|14:45:28.521] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.963ms   mgasps=0.000 number=444 hash=bdf0a7…c29a3c dirty=176.80KiB
INFO [04-27|14:45:33.694] Looking for peers                        peercount=1 tried=121 static=0
INFO [04-27|14:45:34.310] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.934ms   mgasps=0.000 number=445 hash=ab5b66…d0fd99 dirty=176.80KiB
INFO [04-27|14:45:38.372] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.960ms   mgasps=0.000 number=446 hash=7324bd…27387f dirty=176.80KiB
INFO [04-27|14:45:43.213] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.957ms   mgasps=0.000 number=447 hash=03891f…b80e62 dirty=176.80KiB
INFO [04-27|14:45:43.820] Looking for peers                        peercount=1 tried=111 static=0
INFO [04-27|14:45:51.286] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.995ms   mgasps=0.000 number=448 hash=c8d83d…060e39 dirty=176.80KiB
INFO [04-27|14:45:53.874] Looking for peers                        peercount=1 tried=152 static=0
INFO [04-27|14:45:53.922] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=449 hash=a83a25…d77583 dirty=176.80KiB
INFO [04-27|14:45:57.626] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=450 hash=9d0656…caa6c2 dirty=176.80KiB
INFO [04-27|14:46:03.875] Looking for peers                        peercount=2 tried=113 static=0
INFO [04-27|14:46:04.950] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.964ms   mgasps=0.000 number=451 hash=766c85…04e60a dirty=176.80KiB
INFO [04-27|14:46:13.887] Looking for peers                        peercount=2 tried=89  static=0
INFO [04-27|14:46:14.543] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.996ms   mgasps=0.000 number=452 hash=917d4c…d64ed6 dirty=176.80KiB
INFO [04-27|14:46:19.830] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=453 hash=0dee95…f7dfef dirty=176.80KiB
INFO [04-27|14:46:23.914] Looking for peers                        peercount=1 tried=157 static=0
INFO [04-27|14:46:27.861] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=454 hash=de53ff…51c94f dirty=176.80KiB
INFO [04-27|14:46:33.919] Looking for peers                        peercount=2 tried=50  static=0
INFO [04-27|14:46:37.180] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=455 hash=668d4b…ec40e2 dirty=176.80KiB
INFO [04-27|14:46:39.050] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.968ms   mgasps=0.000 number=456 hash=2c1e7a…757cee dirty=176.80KiB
INFO [04-27|14:46:40.858] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=457 hash=ad3e37…37267f dirty=176.80KiB
INFO [04-27|14:46:41.359] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.990ms   mgasps=0.000 number=458 hash=1b102c…1b7c14 dirty=176.80KiB
INFO [04-27|14:46:44.019] Looking for peers                        peercount=2 tried=124 static=0
INFO [04-27|14:46:50.171] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=459 hash=668733…72f1ce dirty=176.80KiB
INFO [04-27|14:46:51.862] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=460 hash=562d9d…89e3a3 dirty=176.80KiB
INFO [04-27|14:46:52.547] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.988ms   mgasps=0.000 number=461 hash=795dc2…d5d9e3 dirty=176.80KiB
INFO [04-27|14:46:52.812] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=462 hash=a1782f…21d6e8 dirty=176.80KiB
INFO [04-27|14:46:54.038] Looking for peers                        peercount=1 tried=124 static=0
INFO [04-27|14:46:54.194] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.999ms   mgasps=0.000 number=463 hash=1610c5…8e63cc dirty=176.80KiB
INFO [04-27|14:47:02.248] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=464 hash=50258b…a2bff1 dirty=176.80KiB
INFO [04-27|14:47:04.508] Looking for peers                        peercount=1 tried=66  static=0
INFO [04-27|14:47:05.785] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.965ms   mgasps=0.000 number=465 hash=cfdc68…0cf0bd dirty=176.80KiB
INFO [04-27|14:47:14.561] Looking for peers                        peercount=1 tried=78  static=0
INFO [04-27|14:47:14.600] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.988ms   mgasps=0.000 number=466 hash=70189c…ea1a60 dirty=176.80KiB
INFO [04-27|14:47:15.129] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=467 hash=5cb516…2299c0 dirty=176.80KiB
INFO [04-27|14:47:16.800] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=468 hash=f502f0…84e93f dirty=176.80KiB
INFO [04-27|14:47:19.355] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=469 hash=39dcf7…274d26 dirty=176.80KiB
INFO [04-27|14:47:22.659] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.963ms   mgasps=0.000 number=470 hash=5dcca5…a1894e dirty=176.80KiB
INFO [04-27|14:47:24.104] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=471 hash=b5dc85…79e042 dirty=176.80KiB
INFO [04-27|14:47:24.589] Looking for peers                        peercount=1 tried=111 static=0
INFO [04-27|14:47:34.618] Looking for peers                        peercount=1 tried=89  static=0
INFO [04-27|14:47:44.771] Looking for peers                        peercount=1 tried=120 static=0
INFO [04-27|14:47:48.043] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=4.003ms   mgasps=0.000 number=472 hash=880a12…6eac18 dirty=176.80KiB
INFO [04-27|14:47:49.850] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=473 hash=036309…9f18cb dirty=176.80KiB
INFO [04-27|14:47:54.798] Looking for peers                        peercount=1 tried=83  static=0
INFO [04-27|14:47:57.706] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.966ms   mgasps=0.000 number=474 hash=fbdd5b…d1368b dirty=176.80KiB
INFO [04-27|14:47:58.530] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.009ms   mgasps=0.000 number=475 hash=85f60d…d8db3e dirty=176.80KiB
INFO [04-27|14:47:58.826] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=476 hash=a570fe…319fda dirty=176.80KiB
INFO [04-27|14:48:04.376] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.995ms   mgasps=0.000 number=477 hash=e1323d…a554ba dirty=176.80KiB
INFO [04-27|14:48:04.805] Looking for peers                        peercount=1 tried=96  static=0
INFO [04-27|14:48:14.805] Looking for peers                        peercount=1 tried=42  static=0
INFO [04-27|14:48:21.610] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=478 hash=304bda…828246 dirty=176.80KiB
INFO [04-27|14:48:24.864] Looking for peers                        peercount=2 tried=54  static=0
INFO [04-27|14:48:34.889] Looking for peers                        peercount=2 tried=48  static=0
INFO [04-27|14:48:38.801] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=479 hash=4ce67c…259afb dirty=176.80KiB
INFO [04-27|14:48:44.907] Looking for peers                        peercount=1 tried=31  static=0
INFO [04-27|14:48:45.076] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=480 hash=c8874b…ec22e6 dirty=176.80KiB
INFO [04-27|14:48:54.919] Looking for peers                        peercount=1 tried=81  static=0
INFO [04-27|14:49:04.920] Looking for peers                        peercount=1 tried=53  static=0
INFO [04-27|14:49:09.223] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=481 hash=b6590d…a2e091 dirty=176.80KiB
INFO [04-27|14:49:13.087] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.014ms   mgasps=0.000 number=482 hash=d8df27…ae3ada dirty=176.80KiB
INFO [04-27|14:49:15.022] Looking for peers                        peercount=1 tried=39  static=0
INFO [04-27|14:49:22.789] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=483 hash=31394c…c07f0a dirty=176.80KiB
INFO [04-27|14:49:24.979] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=484 hash=646328…16fd54 dirty=176.80KiB
INFO [04-27|14:49:25.097] Looking for peers                        peercount=1 tried=61  static=0
INFO [04-27|14:49:31.552] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=485 hash=8d66bd…ceed2f dirty=176.80KiB
INFO [04-27|14:49:35.098] Looking for peers                        peercount=2 tried=69  static=0
INFO [04-27|14:49:40.306] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.964ms   mgasps=0.000 number=486 hash=3c2290…f40b4a dirty=176.80KiB
INFO [04-27|14:49:42.561] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=487 hash=4f0d98…894287 dirty=176.80KiB
INFO [04-27|14:49:43.135] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.986ms   mgasps=0.000 number=488 hash=bca71f…df6705 dirty=176.80KiB
INFO [04-27|14:49:45.605] Looking for peers                        peercount=1 tried=54  static=0
INFO [04-27|14:49:50.445] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.990ms   mgasps=0.000 number=489 hash=021e72…bd7889 dirty=176.80KiB
INFO [04-27|14:49:55.606] Looking for peers                        peercount=1 tried=115 static=0
INFO [04-27|14:50:05.618] Looking for peers                        peercount=1 tried=60  static=0
INFO [04-27|14:50:12.042] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=490 hash=cc3565…913ffe dirty=176.80KiB
INFO [04-27|14:50:15.937] Looking for peers                        peercount=1 tried=138 static=0
INFO [04-27|14:50:16.703] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.025ms   mgasps=0.000 number=491 hash=c844fa…aadf8c dirty=176.80KiB
INFO [04-27|14:50:16.766] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.979ms   mgasps=0.000 number=492 hash=6701f9…08a494 dirty=176.80KiB
INFO [04-27|14:50:25.951] Looking for peers                        peercount=2 tried=131 static=0
INFO [04-27|14:50:36.076] Looking for peers                        peercount=1 tried=138 static=0
INFO [04-27|14:50:41.126] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=493 hash=ac2bc3…00001a dirty=176.80KiB
INFO [04-27|14:50:41.582] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=494 hash=5c0894…ca3347 dirty=176.80KiB
INFO [04-27|14:50:46.217] Looking for peers                        peercount=1 tried=64  static=0
INFO [04-27|14:50:56.284] Looking for peers                        peercount=1 tried=78  static=0
INFO [04-27|14:50:57.863] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=495 hash=bc8e4f…f20cbc dirty=176.80KiB
INFO [04-27|14:50:58.497] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=496 hash=ad6d6a…05a002 dirty=176.80KiB
INFO [04-27|14:51:00.349] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=497 hash=0b7aa7…738795 dirty=176.80KiB
INFO [04-27|14:51:00.792] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=498 hash=25c743…fc932d dirty=176.80KiB
INFO [04-27|14:51:03.489] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.974ms   mgasps=0.000 number=499 hash=5bd9c4…5e45f1 dirty=176.80KiB
INFO [04-27|14:51:06.902] Looking for peers                        peercount=1 tried=132 static=0
INFO [04-27|14:51:12.299] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=500 hash=9d7e9a…86d83a dirty=176.80KiB
INFO [04-27|14:51:15.177] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.019ms   mgasps=0.000 number=501 hash=5b2299…215086 dirty=176.80KiB
INFO [04-27|14:51:16.936] Looking for peers                        peercount=1 tried=104 static=0
INFO [04-27|14:51:19.782] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=502 hash=17adee…43f1dc dirty=176.80KiB
INFO [04-27|14:51:20.669] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.010ms   mgasps=0.000 number=503 hash=180ee3…6b7da7 dirty=176.80KiB
INFO [04-27|14:51:21.801] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.010ms   mgasps=0.000 number=504 hash=b7d24b…2cd09b dirty=176.80KiB
INFO [04-27|14:51:23.634] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.840ms   mgasps=0.000 number=505 hash=5cd8ea…c07c72 dirty=176.80KiB
INFO [04-27|14:51:27.010] Looking for peers                        peercount=1 tried=141 static=0
INFO [04-27|14:51:31.169] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=506 hash=b15f34…74c569 dirty=176.80KiB
INFO [04-27|14:51:35.224] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.959ms   mgasps=0.000 number=507 hash=36fb57…ca5eff dirty=176.80KiB
INFO [04-27|14:51:35.636] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=508 hash=688a8b…5a5e5c dirty=176.80KiB
INFO [04-27|14:51:37.044] Looking for peers                        peercount=1 tried=64  static=0
INFO [04-27|14:51:46.635] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=509 hash=bccf7f…013101 dirty=176.80KiB
INFO [04-27|14:51:47.113] Looking for peers                        peercount=1 tried=110 static=0
INFO [04-27|14:51:51.436] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.016ms   mgasps=0.000 number=510 hash=d6b37f…a29c92 dirty=176.80KiB
INFO [04-27|14:51:56.550] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.991ms   mgasps=0.000 number=511 hash=7f8ea7…dbee92 dirty=176.80KiB
INFO [04-27|14:51:57.133] Looking for peers                        peercount=1 tried=70  static=0
INFO [04-27|14:52:04.850] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.993ms   mgasps=0.000 number=512 hash=9afc3a…928400 dirty=176.80KiB
INFO [04-27|14:52:07.258] Looking for peers                        peercount=2 tried=96  static=0
INFO [04-27|14:52:17.407] Looking for peers                        peercount=1 tried=120 static=0
INFO [04-27|14:52:20.152] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=513 hash=46b7f3…d69e04 dirty=176.80KiB
INFO [04-27|14:52:20.309] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=514 hash=a1a42c…e9f178 dirty=176.80KiB
INFO [04-27|14:52:20.870] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=515 hash=e41cb3…ee50bd dirty=176.80KiB
INFO [04-27|14:52:20.875] Mining too far in the future             wait=2s
INFO [04-27|14:52:27.451] Looking for peers                        peercount=2 tried=60  static=0
INFO [04-27|14:52:34.655] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=516 hash=85abd4…61a114 dirty=176.80KiB
INFO [04-27|14:52:37.452] Looking for peers                        peercount=1 tried=68  static=0
INFO [04-27|14:52:38.174] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=517 hash=c0ccef…cf68cd dirty=176.80KiB
INFO [04-27|14:52:46.890] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=518 hash=b85f2a…078612 dirty=176.80KiB
INFO [04-27|14:52:47.452] Looking for peers                        peercount=1 tried=56  static=0
INFO [04-27|14:52:48.938] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=519 hash=5dcc61…7692ae dirty=176.80KiB
INFO [04-27|14:52:57.452] Looking for peers                        peercount=1 tried=58  static=0
INFO [04-27|14:52:57.760] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=520 hash=24385f…e26a83 dirty=176.80KiB
INFO [04-27|14:53:07.472] Looking for peers                        peercount=1 tried=60  static=0
INFO [04-27|14:53:12.369] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=521 hash=3d9054…96e064 dirty=176.80KiB
INFO [04-27|14:53:17.562] Looking for peers                        peercount=1 tried=65  static=0
INFO [04-27|14:53:19.276] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=522 hash=367448…d48c1c dirty=176.80KiB
INFO [04-27|14:53:19.455] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=523 hash=294f5c…0728c3 dirty=176.80KiB
INFO [04-27|14:53:25.764] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=524 hash=41d11d…178bd7 dirty=176.80KiB
INFO [04-27|14:53:27.589] Looking for peers                        peercount=1 tried=57  static=0
INFO [04-27|14:53:30.090] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.988ms   mgasps=0.000 number=525 hash=af6bdd…083138 dirty=176.80KiB
INFO [04-27|14:53:36.534] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=526 hash=8816db…a87776 dirty=176.80KiB
INFO [04-27|14:53:38.120] Looking for peers                        peercount=1 tried=47  static=0
INFO [04-27|14:53:45.592] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=527 hash=96ed2c…8f182b dirty=176.80KiB
INFO [04-27|14:53:48.128] Looking for peers                        peercount=1 tried=64  static=0
INFO [04-27|14:53:50.152] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=528 hash=99dff3…a9d78a dirty=176.80KiB
INFO [04-27|14:53:53.325] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=529 hash=ad7dbc…363ae1 dirty=176.80KiB
INFO [04-27|14:53:54.208] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.993ms   mgasps=0.000 number=530 hash=72b277…c506fc dirty=176.80KiB
INFO [04-27|14:53:58.128] Looking for peers                        peercount=2 tried=63  static=0
INFO [04-27|14:54:05.768] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.959ms   mgasps=0.000 number=531 hash=cff919…0ed72d dirty=176.80KiB
INFO [04-27|14:54:08.453] Looking for peers                        peercount=1 tried=27  static=0
INFO [04-27|14:54:16.723] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.986ms   mgasps=0.000 number=532 hash=9340bb…868f24 dirty=176.80KiB
INFO [04-27|14:54:18.462] Looking for peers                        peercount=1 tried=141 static=0
INFO [04-27|14:54:18.660] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.989ms   mgasps=0.000 number=533 hash=44c446…83f342 dirty=176.80KiB
INFO [04-27|14:54:21.798] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=534 hash=721de6…5afa1e dirty=176.80KiB
INFO [04-27|14:54:28.462] Looking for peers                        peercount=2 tried=151 static=0
INFO [04-27|14:54:33.960] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=535 hash=575a7b…0826f6 dirty=176.80KiB
INFO [04-27|14:54:36.936] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.006ms   mgasps=0.000 number=536 hash=be79c9…0cea66 dirty=176.80KiB
INFO [04-27|14:54:38.493] Looking for peers                        peercount=2 tried=66  static=0
INFO [04-27|14:54:45.525] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.978ms   mgasps=0.000 number=537 hash=eb47ad…0a4585 dirty=176.80KiB
INFO [04-27|14:54:48.520] Looking for peers                        peercount=1 tried=103 static=0
INFO [04-27|14:54:49.647] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.966ms   mgasps=0.000 number=538 hash=e748fe…05d1c7 dirty=176.80KiB
INFO [04-27|14:54:57.084] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=539 hash=670f64…c41f11 dirty=176.80KiB
INFO [04-27|14:54:58.585] Looking for peers                        peercount=1 tried=91  static=0
INFO [04-27|14:55:01.044] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=540 hash=285fee…1dffd6 dirty=176.80KiB
INFO [04-27|14:55:08.837] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.003ms   mgasps=0.000 number=541 hash=a33306…053f21 dirty=176.80KiB
INFO [04-27|14:55:08.915] Looking for peers                        peercount=1 tried=65  static=0
INFO [04-27|14:55:11.983] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.953ms   mgasps=0.000 number=542 hash=6e9fea…8786ac dirty=176.80KiB
INFO [04-27|14:55:18.930] Looking for peers                        peercount=1 tried=60  static=0
INFO [04-27|14:55:23.304] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=543 hash=554f2d…00f86f dirty=176.80KiB
INFO [04-27|14:55:23.802] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=544 hash=9ece00…507b65 dirty=176.80KiB
INFO [04-27|14:55:24.529] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=545 hash=b08b7a…2b6bb0 dirty=176.80KiB
INFO [04-27|14:55:29.654] Looking for peers                        peercount=1 tried=130 static=0
INFO [04-27|14:55:43.578] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=546 hash=6abffe…cb8735 dirty=176.80KiB
INFO [04-27|14:55:49.495] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=547 hash=a80f25…fdbdb4 dirty=176.80KiB
INFO [04-27|14:55:49.777] Looking for peers                        peercount=1 tried=51  static=0
INFO [04-27|14:55:49.943] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=548 hash=02511f…ec99fc dirty=176.80KiB
INFO [04-27|14:55:53.664] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.019ms   mgasps=0.000 number=549 hash=f9c43d…afbb3b dirty=176.80KiB
INFO [04-27|14:55:58.470] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=550 hash=20021b…014c5d dirty=176.80KiB
INFO [04-27|14:55:59.893] Looking for peers                        peercount=2 tried=120 static=0
INFO [04-27|14:56:04.695] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.984ms   mgasps=0.000 number=551 hash=86acba…9afb17 dirty=176.80KiB
INFO [04-27|14:56:09.920] Looking for peers                        peercount=2 tried=155 static=0
INFO [04-27|14:56:17.497] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=552 hash=f38425…d31cf3 dirty=176.80KiB
INFO [04-27|14:56:19.716] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=553 hash=0bc0b2…f20ccb dirty=176.80KiB
INFO [04-27|14:56:20.120] Looking for peers                        peercount=1 tried=21  static=0
INFO [04-27|14:56:25.411] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=554 hash=184dc4…4916cb dirty=176.80KiB
INFO [04-27|14:56:30.551] Looking for peers                        peercount=1 tried=14  static=0
INFO [04-27|14:56:34.955] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=555 hash=aeed2a…794bcc dirty=176.80KiB
INFO [04-27|14:56:35.143] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.978ms   mgasps=0.000 number=556 hash=14174c…ef45e5 dirty=176.80KiB
INFO [04-27|14:56:40.676] Looking for peers                        peercount=1 tried=29  static=0
INFO [04-27|14:56:42.550] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=557 hash=b9acbe…cc352d dirty=176.80KiB
INFO [04-27|14:56:48.631] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.022ms   mgasps=0.000 number=558 hash=d35a23…41daf0 dirty=176.80KiB
INFO [04-27|14:56:50.854] Looking for peers                        peercount=1 tried=19  static=0
INFO [04-27|14:56:58.520] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=559 hash=770001…985b24 dirty=176.80KiB
INFO [04-27|14:57:00.858] Looking for peers                        peercount=1 tried=22  static=0
INFO [04-27|14:57:11.011] Looking for peers                        peercount=2 tried=63  static=0
INFO [04-27|14:57:11.206] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=4.011ms   mgasps=0.000 number=560 hash=f06087…571a8a dirty=176.80KiB
INFO [04-27|14:57:15.209] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.995ms   mgasps=0.000 number=561 hash=72a74b…b2b7b2 dirty=176.80KiB
INFO [04-27|14:57:16.022] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.988ms   mgasps=0.000 number=562 hash=d508ed…78f676 dirty=176.80KiB
INFO [04-27|14:57:16.321] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=563 hash=cec6f2…20e454 dirty=176.80KiB
INFO [04-27|14:57:21.055] Looking for peers                        peercount=1 tried=25  static=0
INFO [04-27|14:57:31.158] Looking for peers                        peercount=1 tried=98  static=0
INFO [04-27|14:57:35.015] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.965ms   mgasps=0.000 number=564 hash=af182b…2b74b4 dirty=176.80KiB
INFO [04-27|14:57:41.193] Looking for peers                        peercount=1 tried=68  static=0
INFO [04-27|14:57:44.305] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.956ms   mgasps=0.000 number=565 hash=2913b6…1d682f dirty=176.80KiB
INFO [04-27|14:57:51.360] Looking for peers                        peercount=1 tried=61  static=0
INFO [04-27|14:57:54.132] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.994ms   mgasps=0.000 number=566 hash=56368e…2747db dirty=176.80KiB
INFO [04-27|14:57:57.276] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.991ms   mgasps=0.000 number=567 hash=464cad…24caa1 dirty=176.80KiB
INFO [04-27|14:58:01.413] Looking for peers                        peercount=2 tried=60  static=0
INFO [04-27|14:58:03.785] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.018ms   mgasps=0.000 number=568 hash=e3a2b5…f88ede dirty=176.80KiB
INFO [04-27|14:58:07.541] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.953ms   mgasps=0.000 number=569 hash=386446…15e21d dirty=176.80KiB
INFO [04-27|14:58:11.627] Looking for peers                        peercount=1 tried=36  static=0
INFO [04-27|14:58:13.392] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.001ms   mgasps=0.000 number=570 hash=6f6b7a…9ed470 dirty=176.80KiB
INFO [04-27|14:58:21.698] Looking for peers                        peercount=1 tried=61  static=0
INFO [04-27|14:58:31.947] Looking for peers                        peercount=1 tried=64  static=0
INFO [04-27|14:58:38.890] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.990ms   mgasps=0.000 number=571 hash=d83a31…4d8fff dirty=176.80KiB
INFO [04-27|14:58:40.708] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=572 hash=a8f119…8d07be dirty=176.80KiB
INFO [04-27|14:58:42.280] Looking for peers                        peercount=2 tried=52  static=0
INFO [04-27|14:58:52.280] Looking for peers                        peercount=2 tried=68  static=0
INFO [04-27|14:58:55.390] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=573 hash=628d7d…c1b016 dirty=176.80KiB
INFO [04-27|14:58:55.774] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.988ms   mgasps=0.000 number=574 hash=5785d4…07919a dirty=176.80KiB
INFO [04-27|14:59:01.435] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=575 hash=807334…16a130 dirty=176.80KiB
INFO [04-27|14:59:02.280] Looking for peers                        peercount=1 tried=62  static=0
INFO [04-27|14:59:08.049] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=576 hash=7819c3…084d70 dirty=176.80KiB
INFO [04-27|14:59:09.540] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.988ms   mgasps=0.000 number=577 hash=356185…f1cf05 dirty=176.80KiB
INFO [04-27|14:59:11.195] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.989ms   mgasps=0.000 number=578 hash=b2ca0f…926da3 dirty=176.80KiB
INFO [04-27|14:59:12.280] Looking for peers                        peercount=1 tried=59  static=0
INFO [04-27|14:59:14.161] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.979ms   mgasps=0.000 number=579 hash=00e7e9…2e0256 dirty=176.80KiB
INFO [04-27|14:59:14.754] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=580 hash=bbd07e…ba2e5c dirty=176.80KiB
INFO [04-27|14:59:22.359] Looking for peers                        peercount=1 tried=93  static=0
INFO [04-27|14:59:32.613] Looking for peers                        peercount=1 tried=52  static=0
INFO [04-27|14:59:40.267] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.992ms   mgasps=0.000 number=581 hash=d4ec9d…6e1a1e dirty=176.80KiB
INFO [04-27|14:59:42.671] Looking for peers                        peercount=1 tried=141 static=0
INFO [04-27|14:59:43.845] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=1.995ms   mgasps=0.000 number=582 hash=7b8b49…2e9ea9 dirty=176.80KiB
INFO [04-27|14:59:44.363] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.983ms   mgasps=0.000 number=583 hash=4652c4…9a4054 dirty=176.80KiB
INFO [04-27|14:59:52.726] Looking for peers                        peercount=2 tried=84  static=0
INFO [04-27|15:00:00.354] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=3.009ms   mgasps=0.000 number=584 hash=1a50c0…f00c48 dirty=176.80KiB
INFO [04-27|15:00:02.800] Looking for peers                        peercount=1 tried=109 static=0
INFO [04-27|15:00:08.741] Imported new chain segment               blocks=1  txs=0 mgas=0.000 elapsed=2.957ms   mgasps=0.000 number=585 hash=9b2c36…0761a3 dirty=176.80KiB
INFO [04-27|15:00:12.821] Looking for peers                        peercount=1 tried=138 static=0
INFO [04-27|15:00:23.038] Looking for peers                        peercount=1 tried=87  static=0
INFO [04-27|15:00:33.138] Looking for peers                        peercount=0 tried=86  static=0
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