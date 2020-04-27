
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
INFO [04-27|14:03:34.782] Looking for peers                        peercount=1 tried=57 static=0
INFO [04-27|14:03:41.459] Successfully sealed new block            number=7 sealhash=51cea6…859e4d hash=a77665…e994f4 elapsed=7.029s
INFO [04-27|14:03:41.459] Commit new mining work                   number=8 sealhash=bc6a74…a3cd45 uncles=0 txs=0 gas=0 fees=0 elapsed=0s
INFO [04-27|14:03:41.464] 🔨 mined potential block                  number=7 hash=a77665…e994f4
INFO [04-27|14:03:44.934] Looking for peers                        peercount=0 tried=49 static=0
INFO [04-27|14:03:45.746] Successfully sealed new block            number=8 sealhash=bc6a74…a3cd45 hash=7dc7b6…190ab5 elapsed=4.286s
INFO [04-27|14:03:45.746] 🔗 block reached canonical chain          number=1 hash=a23dfa…bfafe1
INFO [04-27|14:03:45.755] Commit new mining work                   number=9 sealhash=1ea65c…93b03b uncles=0 txs=0 gas=0 fees=0 elapsed=8.975ms
INFO [04-27|14:03:45.755] 🔨 mined potential block                  number=8 hash=7dc7b6…190ab5
INFO [04-27|14:03:49.077] Successfully sealed new block            number=9 sealhash=1ea65c…93b03b hash=92be40…549792 elapsed=3.331s
INFO [04-27|14:03:49.077] 🔗 block reached canonical chain          number=2 hash=4b2adc…649e09
INFO [04-27|14:03:49.086] 🔨 mined potential block                  number=9 hash=92be40…549792
INFO [04-27|14:03:49.086] Commit new mining work                   number=10 sealhash=8fc107…9cf24b uncles=0 txs=0 gas=0 fees=0 elapsed=8.942ms
INFO [04-27|14:03:54.961] Looking for peers                        peercount=0 tried=62 static=0
INFO [04-27|14:04:00.292] Successfully sealed new block            number=10 sealhash=8fc107…9cf24b hash=11a4f9…096bd5 elapsed=11.215s
INFO [04-27|14:04:00.293] 🔗 block reached canonical chain          number=3  hash=351c20…9cecd5
INFO [04-27|14:04:00.301] 🔨 mined potential block                  number=10 hash=11a4f9…096bd5
INFO [04-27|14:04:00.301] Commit new mining work                   number=11 sealhash=6bd7bf…7815b9 uncles=0 txs=0 gas=0 fees=0 elapsed=8.975ms
INFO [04-27|14:04:02.982] Successfully sealed new block            number=11 sealhash=6bd7bf…7815b9 hash=e19801…c87410 elapsed=2.688s
INFO [04-27|14:04:02.982] 🔗 block reached canonical chain          number=4  hash=f42991…281d88
INFO [04-27|14:04:02.991] 🔨 mined potential block                  number=11 hash=e19801…c87410
INFO [04-27|14:04:02.991] Commit new mining work                   number=12 sealhash=e1784d…0bc008 uncles=0 txs=0 gas=0 fees=0 elapsed=8.939ms
INFO [04-27|14:04:05.104] Looking for peers                        peercount=0 tried=55 static=0
INFO [04-27|14:04:15.111] Looking for peers                        peercount=0 tried=46 static=0
INFO [04-27|14:04:16.279] Successfully sealed new block            number=12 sealhash=e1784d…0bc008 hash=82826f…f4712c elapsed=13.297s
INFO [04-27|14:04:16.279] 🔗 block reached canonical chain          number=5  hash=f53783…b01ee8
INFO [04-27|14:04:16.287] Commit new mining work                   number=13 sealhash=5d7b38…bde186 uncles=0 txs=0 gas=0 fees=0 elapsed=7.978ms
INFO [04-27|14:04:16.287] 🔨 mined potential block                  number=12 hash=82826f…f4712c
INFO [04-27|14:04:25.444] Looking for peers                        peercount=0 tried=55 static=0
INFO [04-27|14:04:33.667] Successfully sealed new block            number=13 sealhash=5d7b38…bde186 hash=6140bb…54a3c1 elapsed=17.387s
INFO [04-27|14:04:33.667] 🔗 block reached canonical chain          number=6  hash=e5a0a6…59bef9
INFO [04-27|14:04:33.675] 🔨 mined potential block                  number=13 hash=6140bb…54a3c1
INFO [04-27|14:04:33.675] Commit new mining work                   number=14 sealhash=a7939a…aad155 uncles=0 txs=0 gas=0 fees=0 elapsed=7.938ms
INFO [04-27|14:04:35.445] Looking for peers                        peercount=0 tried=61 static=0
INFO [04-27|14:04:36.869] Successfully sealed new block            number=14 sealhash=a7939a…aad155 hash=df1a14…91c3d0 elapsed=3.202s
INFO [04-27|14:04:36.869] 🔗 block reached canonical chain          number=7  hash=a77665…e994f4
INFO [04-27|14:04:36.877] 🔨 mined potential block                  number=14 hash=df1a14…91c3d0
INFO [04-27|14:04:36.877] Commit new mining work                   number=15 sealhash=d33057…be1580 uncles=0 txs=0 gas=0 fees=0 elapsed=7.977ms
INFO [04-27|14:04:36.896] Successfully sealed new block            number=15 sealhash=d33057…be1580 hash=38ceb7…10b5d2 elapsed=26.927ms
INFO [04-27|14:04:36.896] 🔗 block reached canonical chain          number=8  hash=7dc7b6…190ab5
INFO [04-27|14:04:36.907] 🔨 mined potential block                  number=15 hash=38ceb7…10b5d2
INFO [04-27|14:04:36.907] Commit new mining work                   number=16 sealhash=33b40d…6972eb uncles=0 txs=0 gas=0 fees=0 elapsed=10.970ms
INFO [04-27|14:04:38.433] Successfully sealed new block            number=16 sealhash=33b40d…6972eb hash=4baef0…b1528c elapsed=1.536s
INFO [04-27|14:04:38.433] 🔗 block reached canonical chain          number=9  hash=92be40…549792
INFO [04-27|14:04:38.440] 🔨 mined potential block                  number=16 hash=4baef0…b1528c
INFO [04-27|14:04:38.440] Commit new mining work                   number=17 sealhash=d417f3…964782 uncles=0 txs=0 gas=0 fees=0 elapsed=6.973ms
INFO [04-27|14:04:45.524] Looking for peers                        peercount=0 tried=58 static=0
INFO [04-27|14:04:50.049] Successfully sealed new block            number=17 sealhash=d417f3…964782 hash=f065ff…771bc1 elapsed=11.615s
INFO [04-27|14:04:50.050] 🔗 block reached canonical chain          number=10 hash=11a4f9…096bd5
INFO [04-27|14:04:50.060] 🔨 mined potential block                  number=17 hash=f065ff…771bc1
INFO [04-27|14:04:50.060] Commit new mining work                   number=18 sealhash=88179b…aca583 uncles=0 txs=0 gas=0 fees=0 elapsed=10.971ms
INFO [04-27|14:04:53.421] Successfully sealed new block            number=18 sealhash=88179b…aca583 hash=6756c5…ee0061 elapsed=3.370s
INFO [04-27|14:04:53.421] 🔗 block reached canonical chain          number=11 hash=e19801…c87410
INFO [04-27|14:04:53.429] Commit new mining work                   number=19 sealhash=6be55e…0800cd uncles=0 txs=0 gas=0 fees=0 elapsed=7.978ms
INFO [04-27|14:04:53.429] 🔨 mined potential block                  number=18 hash=6756c5…ee0061
INFO [04-27|14:04:55.778] Looking for peers                        peercount=0 tried=37 static=0
INFO [04-27|14:05:04.889] Successfully sealed new block            number=19 sealhash=6be55e…0800cd hash=3b1738…95a3f3 elapsed=11.468s
INFO [04-27|14:05:04.889] 🔗 block reached canonical chain          number=12 hash=82826f…f4712c
INFO [04-27|14:05:04.897] Commit new mining work                   number=20 sealhash=d582af…588022 uncles=0 txs=0 gas=0 fees=0 elapsed=7.977ms
INFO [04-27|14:05:04.897] 🔨 mined potential block                  number=19 hash=3b1738…95a3f3
INFO [04-27|14:05:05.778] Looking for peers                        peercount=1 tried=84 static=0
INFO [04-27|14:05:15.811] Looking for peers                        peercount=0 tried=40 static=0
INFO [04-27|14:05:20.948] Successfully sealed new block            number=20 sealhash=d582af…588022 hash=e22ea4…f3cad4 elapsed=16.059s
INFO [04-27|14:05:20.948] 🔗 block reached canonical chain          number=13 hash=6140bb…54a3c1
INFO [04-27|14:05:20.956] Commit new mining work                   number=21 sealhash=346328…19aaff uncles=0 txs=0 gas=0 fees=0 elapsed=8.004ms
INFO [04-27|14:05:20.956] 🔨 mined potential block                  number=20 hash=e22ea4…f3cad4
INFO [04-27|14:05:23.042] Successfully sealed new block            number=21 sealhash=346328…19aaff hash=d819e7…3691c3 elapsed=2.093s
INFO [04-27|14:05:23.042] 🔗 block reached canonical chain          number=14 hash=df1a14…91c3d0
INFO [04-27|14:05:23.050] 🔨 mined potential block                  number=21 hash=d819e7…3691c3
INFO [04-27|14:05:23.050] Commit new mining work                   number=22 sealhash=3bf0c6…62d0db uncles=0 txs=0 gas=0 fees=0 elapsed=7.946ms
INFO [04-27|14:05:25.812] Looking for peers                        peercount=0 tried=54 static=0
INFO [04-27|14:05:26.175] Successfully sealed new block            number=22 sealhash=3bf0c6…62d0db hash=5498cd…b13cd3 elapsed=3.133s
INFO [04-27|14:05:26.175] 🔗 block reached canonical chain          number=15 hash=38ceb7…10b5d2
INFO [04-27|14:05:26.183] Commit new mining work                   number=23 sealhash=cbc929…cc8570 uncles=0 txs=0 gas=0 fees=0 elapsed=7.944ms
INFO [04-27|14:05:26.183] 🔨 mined potential block                  number=22 hash=5498cd…b13cd3
INFO [04-27|14:05:35.813] Looking for peers                        peercount=0 tried=72 static=0
INFO [04-27|14:05:45.832] Looking for peers                        peercount=0 tried=52 static=0
INFO [04-27|14:05:52.256] Successfully sealed new block            number=23 sealhash=cbc929…cc8570 hash=877c7e…c22366 elapsed=26.080s
INFO [04-27|14:05:52.256] 🔗 block reached canonical chain          number=16 hash=4baef0…b1528c
INFO [04-27|14:05:52.262] Commit new mining work                   number=24 sealhash=bf7375…141dae uncles=0 txs=0 gas=0 fees=0 elapsed=5.983ms
INFO [04-27|14:05:52.262] 🔨 mined potential block                  number=23 hash=877c7e…c22366
INFO [04-27|14:05:54.456] Successfully sealed new block            number=24 sealhash=bf7375…141dae hash=6cf647…9adcb7 elapsed=2.200s
INFO [04-27|14:05:54.456] 🔗 block reached canonical chain          number=17 hash=f065ff…771bc1
INFO [04-27|14:05:54.463] 🔨 mined potential block                  number=24 hash=6cf647…9adcb7
INFO [04-27|14:05:54.463] Commit new mining work                   number=25 sealhash=abbbcc…60368e uncles=0 txs=0 gas=0 fees=0 elapsed=6.948ms
INFO [04-27|14:05:55.866] Looking for peers                        peercount=0 tried=60 static=0
INFO [04-27|14:06:01.102] Successfully sealed new block            number=25 sealhash=abbbcc…60368e hash=8a6568…35eb40 elapsed=6.646s
INFO [04-27|14:06:01.102] 🔗 block reached canonical chain          number=18 hash=6756c5…ee0061
INFO [04-27|14:06:01.109] 🔨 mined potential block                  number=25 hash=8a6568…35eb40
INFO [04-27|14:06:01.109] Commit new mining work                   number=26 sealhash=67660e…b0ebc3 uncles=0 txs=0 gas=0 fees=0 elapsed=6.948ms
INFO [04-27|14:06:06.109] Looking for peers                        peercount=1 tried=57 static=0
INFO [04-27|14:06:08.083] Successfully sealed new block            number=26 sealhash=67660e…b0ebc3 hash=15b84a…790793 elapsed=6.981s
INFO [04-27|14:06:08.084] 🔗 block reached canonical chain          number=19 hash=3b1738…95a3f3
INFO [04-27|14:06:08.091] Commit new mining work                   number=27 sealhash=68ff3c…453d68 uncles=0 txs=0 gas=0 fees=0 elapsed=7.977ms
INFO [04-27|14:06:08.091] 🔨 mined potential block                  number=26 hash=15b84a…790793
INFO [04-27|14:06:08.807] Successfully sealed new block            number=27 sealhash=68ff3c…453d68 hash=8a4e34…80bd97 elapsed=723.065ms
INFO [04-27|14:06:08.807] 🔗 block reached canonical chain          number=20 hash=e22ea4…f3cad4
INFO [04-27|14:06:08.815] 🔨 mined potential block                  number=27 hash=8a4e34…80bd97
INFO [04-27|14:06:08.815] Commit new mining work                   number=28 sealhash=d173bd…e12aff uncles=0 txs=0 gas=0 fees=0 elapsed=7.978ms
INFO [04-27|14:06:09.492] Successfully sealed new block            number=28 sealhash=d173bd…e12aff hash=fe461c…0df352 elapsed=684.202ms
INFO [04-27|14:06:09.492] 🔗 block reached canonical chain          number=21 hash=d819e7…3691c3
INFO [04-27|14:06:09.497] Commit new mining work                   number=29 sealhash=839b80…c45a4b uncles=0 txs=0 gas=0 fees=0 elapsed=5.983ms
INFO [04-27|14:06:09.497] 🔨 mined potential block                  number=28 hash=fe461c…0df352
INFO [04-27|14:06:16.145] Looking for peers                        peercount=0 tried=41 static=0
INFO [04-27|14:06:18.187] Successfully sealed new block            number=29 sealhash=839b80…c45a4b hash=4530f8…737a4e elapsed=8.695s
INFO [04-27|14:06:18.187] 🔗 block reached canonical chain          number=22 hash=5498cd…b13cd3
INFO [04-27|14:06:18.194] Commit new mining work                   number=30 sealhash=ab3da2…2b962d uncles=0 txs=0 gas=0 fees=0 elapsed=7.011ms
INFO [04-27|14:06:18.194] 🔨 mined potential block                  number=29 hash=4530f8…737a4e
INFO [04-27|14:06:26.145] Looking for peers                        peercount=2 tried=61 static=0
INFO [04-27|14:06:27.976] Successfully sealed new block            number=30 sealhash=ab3da2…2b962d hash=75d5b7…6b48ad elapsed=9.788s
INFO [04-27|14:06:27.976] 🔗 block reached canonical chain          number=23 hash=877c7e…c22366
INFO [04-27|14:06:27.983] Commit new mining work                   number=31 sealhash=108024…3cf960 uncles=0 txs=0 gas=0 fees=0 elapsed=6.981ms
INFO [04-27|14:06:27.983] 🔨 mined potential block                  number=30 hash=75d5b7…6b48ad
INFO [04-27|14:06:30.124] Successfully sealed new block            number=31 sealhash=108024…3cf960 hash=957e82…c00586 elapsed=2.148s
INFO [04-27|14:06:30.124] 🔗 block reached canonical chain          number=24 hash=6cf647…9adcb7
INFO [04-27|14:06:30.133] 🔨 mined potential block                  number=31 hash=957e82…c00586
INFO [04-27|14:06:30.133] Commit new mining work                   number=32 sealhash=ea3986…968e75 uncles=0 txs=0 gas=0 fees=0 elapsed=8.937ms
INFO [04-27|14:06:30.907] Successfully sealed new block            number=32 sealhash=ea3986…968e75 hash=4db708…346229 elapsed=782.867ms
INFO [04-27|14:06:30.907] 🔗 block reached canonical chain          number=25 hash=8a6568…35eb40
INFO [04-27|14:06:30.914] 🔨 mined potential block                  number=32 hash=4db708…346229
INFO [04-27|14:06:30.914] Commit new mining work                   number=33 sealhash=100fd5…f05336 uncles=0 txs=0 gas=0 fees=0 elapsed=6.980ms
INFO [04-27|14:06:36.170] Looking for peers                        peercount=1 tried=60 static=0
INFO [04-27|14:06:38.074] Successfully sealed new block            number=33 sealhash=100fd5…f05336 hash=c60c63…8f9c22 elapsed=7.166s
INFO [04-27|14:06:38.074] 🔗 block reached canonical chain          number=26 hash=15b84a…790793
INFO [04-27|14:06:38.081] 🔨 mined potential block                  number=33 hash=c60c63…8f9c22
INFO [04-27|14:06:38.081] Commit new mining work                   number=34 sealhash=752470…5fc066 uncles=0 txs=0 gas=0 fees=0 elapsed=6.948ms
INFO [04-27|14:06:39.732] Successfully sealed new block            number=34 sealhash=752470…5fc066 hash=060432…93650f elapsed=1.657s
INFO [04-27|14:06:39.732] 🔗 block reached canonical chain          number=27 hash=8a4e34…80bd97
INFO [04-27|14:06:39.740] 🔨 mined potential block                  number=34 hash=060432…93650f
INFO [04-27|14:06:39.740] Commit new mining work                   number=35 sealhash=068f85…1584c3 uncles=0 txs=0 gas=0 fees=0 elapsed=7.978ms
INFO [04-27|14:06:46.479] Looking for peers                        peercount=1 tried=45 static=0
INFO [04-27|14:06:48.654] Successfully sealed new block            number=35 sealhash=068f85…1584c3 hash=e3d0d3…fd028b elapsed=8.922s
INFO [04-27|14:06:48.654] 🔗 block reached canonical chain          number=28 hash=fe461c…0df352
INFO [04-27|14:06:48.663] Commit new mining work                   number=36 sealhash=a1a6de…ed80b2 uncles=0 txs=0 gas=0 fees=0 elapsed=9.005ms
INFO [04-27|14:06:48.663] 🔨 mined potential block                  number=35 hash=e3d0d3…fd028b
INFO [04-27|14:06:48.917] Successfully sealed new block            number=36 sealhash=a1a6de…ed80b2 hash=031a90…07f869 elapsed=263.329ms
INFO [04-27|14:06:48.918] 🔗 block reached canonical chain          number=29 hash=4530f8…737a4e
INFO [04-27|14:06:48.926] 🔨 mined potential block                  number=36 hash=031a90…07f869
INFO [04-27|14:06:48.926] Commit new mining work                   number=37 sealhash=b6a337…0193a8 uncles=0 txs=0 gas=0 fees=0 elapsed=8.942ms
INFO [04-27|14:06:53.187] Successfully sealed new block            number=37 sealhash=b6a337…0193a8 hash=713214…dfd3c4 elapsed=4.268s
INFO [04-27|14:06:53.187] 🔗 block reached canonical chain          number=30 hash=75d5b7…6b48ad
INFO [04-27|14:06:53.197] 🔨 mined potential block                  number=37 hash=713214…dfd3c4
INFO [04-27|14:06:53.197] Commit new mining work                   number=38 sealhash=0c7e47…ab5e2c uncles=0 txs=0 gas=0 fees=0 elapsed=9.972ms
INFO [04-27|14:06:56.504] Looking for peers                        peercount=1 tried=65 static=0
INFO [04-27|14:07:05.039] Successfully sealed new block            number=38 sealhash=0c7e47…ab5e2c hash=4e5213…244353 elapsed=11.852s
INFO [04-27|14:07:05.039] 🔗 block reached canonical chain          number=31 hash=957e82…c00586
INFO [04-27|14:07:05.047] 🔨 mined potential block                  number=38 hash=4e5213…244353
INFO [04-27|14:07:05.047] Commit new mining work                   number=39 sealhash=26fafb…c43d8b uncles=0 txs=0 gas=0 fees=0 elapsed=7.979ms
INFO [04-27|14:07:06.521] Looking for peers                        peercount=1 tried=65 static=0
INFO [04-27|14:07:09.444] Successfully sealed new block            number=39 sealhash=26fafb…c43d8b hash=aa011e…74e99c elapsed=4.405s
INFO [04-27|14:07:09.445] 🔗 block reached canonical chain          number=32 hash=4db708…346229
INFO [04-27|14:07:09.454] 🔨 mined potential block                  number=39 hash=aa011e…74e99c
INFO [04-27|14:07:09.454] Commit new mining work                   number=40 sealhash=630649…1861a9 uncles=0 txs=0 gas=0 fees=0 elapsed=8.942ms
INFO [04-27|14:07:16.531] Looking for peers                        peercount=1 tried=54 static=0
INFO [04-27|14:07:19.985] Successfully sealed new block            number=40 sealhash=630649…1861a9 hash=2053bf…a5f509 elapsed=10.539s
INFO [04-27|14:07:19.985] 🔗 block reached canonical chain          number=33 hash=c60c63…8f9c22
INFO [04-27|14:07:19.993] 🔨 mined potential block                  number=40 hash=2053bf…a5f509
INFO [04-27|14:07:19.993] Commit new mining work                   number=41 sealhash=2fb7f0…939fd8 uncles=0 txs=0 gas=0 fees=0 elapsed=7.947ms
INFO [04-27|14:07:26.601] Looking for peers                        peercount=2 tried=61 static=0
INFO [04-27|14:07:27.195] Successfully sealed new block            number=41 sealhash=2fb7f0…939fd8 hash=88e19a…20035d elapsed=7.209s
INFO [04-27|14:07:27.195] 🔗 block reached canonical chain          number=34 hash=060432…93650f
INFO [04-27|14:07:27.205] 🔨 mined potential block                  number=41 hash=88e19a…20035d
INFO [04-27|14:07:27.205] Commit new mining work                   number=42 sealhash=ae48e4…562c9d uncles=0 txs=0 gas=0 fees=0 elapsed=9.972ms
INFO [04-27|14:07:31.117] Successfully sealed new block            number=42 sealhash=ae48e4…562c9d hash=28b84f…bcb9d4 elapsed=3.922s
INFO [04-27|14:07:31.118] 🔗 block reached canonical chain          number=35 hash=e3d0d3…fd028b
INFO [04-27|14:07:31.126] 🔨 mined potential block                  number=42 hash=28b84f…bcb9d4
INFO [04-27|14:07:31.126] Commit new mining work                   number=43 sealhash=cf84a3…70796f uncles=0 txs=0 gas=0 fees=0 elapsed=8.974ms
INFO [04-27|14:07:33.616] Successfully sealed new block            number=43 sealhash=cf84a3…70796f hash=c17ee5…c78d0e elapsed=2.497s
INFO [04-27|14:07:33.616] 🔗 block reached canonical chain          number=36 hash=031a90…07f869
INFO [04-27|14:07:33.633] 🔨 mined potential block                  number=43 hash=c17ee5…c78d0e
INFO [04-27|14:07:33.633] Commit new mining work                   number=44 sealhash=9e09b8…5cd69b uncles=0 txs=0 gas=0 fees=0 elapsed=16.921ms
INFO [04-27|14:07:36.693] Looking for peers                        peercount=1 tried=35 static=0
INFO [04-27|14:07:37.505] Successfully sealed new block            number=44 sealhash=9e09b8…5cd69b hash=c48d19…59e061 elapsed=3.889s
INFO [04-27|14:07:37.505] 🔗 block reached canonical chain          number=37 hash=713214…dfd3c4
INFO [04-27|14:07:37.513] Commit new mining work                   number=45 sealhash=9540ef…27a843 uncles=0 txs=0 gas=0 fees=0 elapsed=7.946ms
INFO [04-27|14:07:37.513] 🔨 mined potential block                  number=44 hash=c48d19…59e061
INFO [04-27|14:07:46.791] Looking for peers                        peercount=1 tried=62 static=0
INFO [04-27|14:07:50.196] Successfully sealed new block            number=45 sealhash=9540ef…27a843 hash=51abd7…d80c43 elapsed=12.691s
INFO [04-27|14:07:50.196] 🔗 block reached canonical chain          number=38 hash=4e5213…244353
INFO [04-27|14:07:50.206] 🔨 mined potential block                  number=45 hash=51abd7…d80c43
INFO [04-27|14:07:50.206] Commit new mining work                   number=46 sealhash=d8e472…307cc0 uncles=0 txs=0 gas=0 fees=0 elapsed=9.941ms
INFO [04-27|14:07:52.013] Successfully sealed new block            number=46 sealhash=d8e472…307cc0 hash=54a458…e7e6ba elapsed=1.816s
INFO [04-27|14:07:52.013] 🔗 block reached canonical chain          number=39 hash=aa011e…74e99c
INFO [04-27|14:07:52.023] 🔨 mined potential block                  number=46 hash=54a458…e7e6ba
INFO [04-27|14:07:52.023] Commit new mining work                   number=47 sealhash=3ed2ef…0a85bd uncles=0 txs=0 gas=0 fees=0 elapsed=10.935ms
INFO [04-27|14:07:55.275] Successfully sealed new block            number=47 sealhash=3ed2ef…0a85bd hash=d66382…c7e297 elapsed=3.262s
INFO [04-27|14:07:55.275] 🔗 block reached canonical chain          number=40 hash=2053bf…a5f509
INFO [04-27|14:07:55.284] 🔨 mined potential block                  number=47 hash=d66382…c7e297
INFO [04-27|14:07:55.284] Commit new mining work                   number=48 sealhash=558138…391450 uncles=0 txs=0 gas=0 fees=0 elapsed=8.942ms
INFO [04-27|14:07:56.892] Looking for peers                        peercount=1 tried=51 static=0
INFO [04-27|14:07:58.042] Successfully sealed new block            number=48 sealhash=558138…391450 hash=409bbc…a6fb98 elapsed=2.767s
INFO [04-27|14:07:58.043] 🔗 block reached canonical chain          number=41 hash=88e19a…20035d
INFO [04-27|14:07:58.053] 🔨 mined potential block                  number=48 hash=409bbc…a6fb98
INFO [04-27|14:07:58.053] Commit new mining work                   number=49 sealhash=29e87f…1065cd uncles=0 txs=0 gas=0 fees=0 elapsed=9.926ms
INFO [04-27|14:08:02.499] Successfully sealed new block            number=49 sealhash=29e87f…1065cd hash=23491a…33a812 elapsed=4.456s
INFO [04-27|14:08:02.499] 🔗 block reached canonical chain          number=42 hash=28b84f…bcb9d4
INFO [04-27|14:08:02.507] 🔨 mined potential block                  number=49 hash=23491a…33a812
INFO [04-27|14:08:02.507] Commit new mining work                   number=50 sealhash=49deef…54e36c uncles=0 txs=0 gas=0 fees=0 elapsed=7.944ms
INFO [04-27|14:08:02.651] Successfully sealed new block            number=50 sealhash=49deef…54e36c hash=7d9470…ff521a elapsed=151.594ms
INFO [04-27|14:08:02.652] 🔗 block reached canonical chain          number=43 hash=c17ee5…c78d0e
INFO [04-27|14:08:02.662] 🔨 mined potential block                  number=50 hash=7d9470…ff521a
INFO [04-27|14:08:02.662] Commit new mining work                   number=51 sealhash=e83ac4…25a103 uncles=0 txs=0 gas=0 fees=0 elapsed=10.937ms
INFO [04-27|14:08:05.010] Successfully sealed new block            number=51 sealhash=e83ac4…25a103 hash=8cbb89…310257 elapsed=2.357s
INFO [04-27|14:08:05.010] 🔗 block reached canonical chain          number=44 hash=c48d19…59e061
INFO [04-27|14:08:05.018] 🔨 mined potential block                  number=51 hash=8cbb89…310257
INFO [04-27|14:08:05.018] Commit new mining work                   number=52 sealhash=29b38b…6f62c8 uncles=0 txs=0 gas=0 fees=0 elapsed=7.942ms
INFO [04-27|14:08:06.897] Looking for peers                        peercount=1 tried=44 static=0
INFO [04-27|14:08:15.318] Successfully sealed new block            number=52 sealhash=29b38b…6f62c8 hash=806620…75d8e0 elapsed=10.308s
INFO [04-27|14:08:15.318] 🔗 block reached canonical chain          number=45 hash=51abd7…d80c43
INFO [04-27|14:08:15.328] Commit new mining work                   number=53 sealhash=ef2b3d…fa6914 uncles=0 txs=0 gas=0 fees=0 elapsed=9.938ms
INFO [04-27|14:08:15.328] 🔨 mined potential block                  number=52 hash=806620…75d8e0
INFO [04-27|14:08:15.997] Successfully sealed new block            number=53 sealhash=ef2b3d…fa6914 hash=4dbe90…6388d8 elapsed=679.181ms
INFO [04-27|14:08:15.997] 🔗 block reached canonical chain          number=46 hash=54a458…e7e6ba
INFO [04-27|14:08:16.007] 🔨 mined potential block                  number=53 hash=4dbe90…6388d8
INFO [04-27|14:08:16.007] Commit new mining work                   number=54 sealhash=c81397…81fcbd uncles=0 txs=0 gas=0 fees=0 elapsed=9.958ms
INFO [04-27|14:08:16.908] Looking for peers                        peercount=1 tried=83 static=0
INFO [04-27|14:08:21.931] Successfully sealed new block            number=54 sealhash=c81397…81fcbd hash=98158b…f34d0e elapsed=5.933s
INFO [04-27|14:08:21.931] 🔗 block reached canonical chain          number=47 hash=d66382…c7e297
INFO [04-27|14:08:21.940] 🔨 mined potential block                  number=54 hash=98158b…f34d0e
INFO [04-27|14:08:21.940] Commit new mining work                   number=55 sealhash=522e15…449f04 uncles=0 txs=0 gas=0 fees=0 elapsed=9.939ms
INFO [04-27|14:08:27.227] Looking for peers                        peercount=1 tried=52 static=0
INFO [04-27|14:08:37.571] Looking for peers                        peercount=2 tried=48 static=0
INFO [04-27|14:08:41.671] Successfully sealed new block            number=55 sealhash=522e15…449f04 hash=7f6143…6c061e elapsed=19.740s
INFO [04-27|14:08:41.671] 🔗 block reached canonical chain          number=48 hash=409bbc…a6fb98
INFO [04-27|14:08:41.679] 🔨 mined potential block                  number=55 hash=7f6143…6c061e
INFO [04-27|14:08:41.679] Commit new mining work                   number=56 sealhash=69ebcb…084ee6 uncles=0 txs=0 gas=0 fees=0 elapsed=7.938ms
INFO [04-27|14:08:47.662] Looking for peers                        peercount=1 tried=70 static=0
INFO [04-27|14:08:50.376] Successfully sealed new block            number=56 sealhash=69ebcb…084ee6 hash=01af2b…a57e1f elapsed=8.704s
INFO [04-27|14:08:50.376] 🔗 block reached canonical chain          number=49 hash=23491a…33a812
INFO [04-27|14:08:50.384] Commit new mining work                   number=57 sealhash=48183f…1a7cd2 uncles=0 txs=0 gas=0 fees=0 elapsed=7.945ms
INFO [04-27|14:08:50.384] 🔨 mined potential block                  number=56 hash=01af2b…a57e1f
INFO [04-27|14:08:56.912] Successfully sealed new block            number=57 sealhash=48183f…1a7cd2 hash=6ab55a…95de50 elapsed=6.536s
INFO [04-27|14:08:56.912] 🔗 block reached canonical chain          number=50 hash=7d9470…ff521a
INFO [04-27|14:08:56.921] 🔨 mined potential block                  number=57 hash=6ab55a…95de50
INFO [04-27|14:08:56.921] Commit new mining work                   number=58 sealhash=f40b2c…5a3bf2 uncles=0 txs=0 gas=0 fees=0 elapsed=8.940ms
INFO [04-27|14:08:57.719] Looking for peers                        peercount=2 tried=63 static=0
INFO [04-27|14:09:01.854] Successfully sealed new block            number=58 sealhash=f40b2c…5a3bf2 hash=795dfe…958700 elapsed=4.941s
INFO [04-27|14:09:01.854] 🔗 block reached canonical chain          number=51 hash=8cbb89…310257
INFO [04-27|14:09:01.861] Commit new mining work                   number=59 sealhash=fcf066…dd5b7e uncles=0 txs=0 gas=0 fees=0 elapsed=6.98ms
INFO [04-27|14:09:01.861] 🔨 mined potential block                  number=58 hash=795dfe…958700
INFO [04-27|14:09:03.151] Successfully sealed new block            number=59 sealhash=fcf066…dd5b7e hash=3fbb75…86a17f elapsed=1.296s
INFO [04-27|14:09:03.151] 🔗 block reached canonical chain          number=52 hash=806620…75d8e0
INFO [04-27|14:09:03.159] 🔨 mined potential block                  number=59 hash=3fbb75…86a17f
INFO [04-27|14:09:03.159] Commit new mining work                   number=60 sealhash=86e3f8…047875 uncles=0 txs=0 gas=0 fees=0 elapsed=7.977ms
INFO [04-27|14:09:07.900] Looking for peers                        peercount=1 tried=41 static=0
INFO [04-27|14:09:13.600] Successfully sealed new block            number=60 sealhash=86e3f8…047875 hash=785f2a…d76522 elapsed=10.449s
INFO [04-27|14:09:13.601] 🔗 block reached canonical chain          number=53 hash=4dbe90…6388d8
INFO [04-27|14:09:13.611] 🔨 mined potential block                  number=60 hash=785f2a…d76522
INFO [04-27|14:09:13.611] Commit new mining work                   number=61 sealhash=637a85…daf865 uncles=0 txs=0 gas=0 fees=0 elapsed=10.938ms
INFO [04-27|14:09:18.156] Looking for peers                        peercount=1 tried=50 static=0
INFO [04-27|14:09:22.321] Successfully sealed new block            number=61 sealhash=637a85…daf865 hash=bc95fa…2df067 elapsed=8.720s
INFO [04-27|14:09:22.321] 🔗 block reached canonical chain          number=54 hash=98158b…f34d0e
INFO [04-27|14:09:22.330] Commit new mining work                   number=62 sealhash=6eb9ad…04ce91 uncles=0 txs=0 gas=0 fees=0 elapsed=8.976ms
INFO [04-27|14:09:22.330] 🔨 mined potential block                  number=61 hash=bc95fa…2df067
INFO [04-27|14:09:28.231] Looking for peers                        peercount=1 tried=81 static=0
INFO [04-27|14:09:29.521] Successfully sealed new block            number=62 sealhash=6eb9ad…04ce91 hash=bc0417…f2545b elapsed=7.199s
INFO [04-27|14:09:29.522] 🔗 block reached canonical chain          number=55 hash=7f6143…6c061e
INFO [04-27|14:09:29.529] 🔨 mined potential block                  number=62 hash=bc0417…f2545b
INFO [04-27|14:09:29.529] Commit new mining work                   number=63 sealhash=0ca1e8…f37d8f uncles=0 txs=0 gas=0 fees=0 elapsed=7.947ms
INFO [04-27|14:09:35.434] Successfully sealed new block            number=63 sealhash=0ca1e8…f37d8f hash=a03851…d70153 elapsed=5.912s
INFO [04-27|14:09:35.434] 🔗 block reached canonical chain          number=56 hash=01af2b…a57e1f
INFO [04-27|14:09:35.442] Commit new mining work                   number=64 sealhash=d39b65…9d38a4 uncles=0 txs=0 gas=0 fees=0 elapsed=7.979ms
INFO [04-27|14:09:35.442] 🔨 mined potential block                  number=63 hash=a03851…d70153
INFO [04-27|14:09:38.234] Looking for peers                        peercount=1 tried=107 static=0
INFO [04-27|14:09:43.161] Successfully sealed new block            number=64 sealhash=d39b65…9d38a4 hash=1b2373…467d08 elapsed=7.726s
INFO [04-27|14:09:43.161] 🔗 block reached canonical chain          number=57 hash=6ab55a…95de50
INFO [04-27|14:09:43.169] 🔨 mined potential block                  number=64 hash=1b2373…467d08
INFO [04-27|14:09:43.169] Commit new mining work                   number=65 sealhash=85e382…58c046 uncles=0 txs=0 gas=0 fees=0 elapsed=7.945ms
INFO [04-27|14:09:48.294] Looking for peers                        peercount=1 tried=122 static=0
INFO [04-27|14:09:52.778] Successfully sealed new block            number=65 sealhash=85e382…58c046 hash=850077…03b2aa elapsed=9.617s
INFO [04-27|14:09:52.778] 🔗 block reached canonical chain          number=58 hash=795dfe…958700
INFO [04-27|14:09:52.787] 🔨 mined potential block                  number=65 hash=850077…03b2aa
INFO [04-27|14:09:52.787] Commit new mining work                   number=66 sealhash=357263…18e050 uncles=0 txs=0 gas=0 fees=0 elapsed=8.976ms
INFO [04-27|14:09:53.726] Successfully sealed new block            number=66 sealhash=357263…18e050 hash=c919d1…ad493a elapsed=948.463ms
INFO [04-27|14:09:53.726] 🔗 block reached canonical chain          number=59 hash=3fbb75…86a17f
INFO [04-27|14:09:53.734] 🔨 mined potential block                  number=66 hash=c919d1…ad493a
INFO [04-27|14:09:53.734] Commit new mining work                   number=67 sealhash=106793…d12d04 uncles=0 txs=0 gas=0 fees=0 elapsed=7.979ms
INFO [04-27|14:09:58.294] Looking for peers                        peercount=2 tried=111 static=0
INFO [04-27|14:09:59.908] Successfully sealed new block            number=67 sealhash=106793…d12d04 hash=728fcc…9d63cc elapsed=6.181s
INFO [04-27|14:09:59.908] 🔗 block reached canonical chain          number=60 hash=785f2a…d76522
INFO [04-27|14:09:59.915] Commit new mining work                   number=68 sealhash=843d31…50db1c uncles=0 txs=0 gas=0 fees=0 elapsed=6.979ms
INFO [04-27|14:09:59.915] 🔨 mined potential block                  number=67 hash=728fcc…9d63cc
INFO [04-27|14:10:03.696] Successfully sealed new block            number=68 sealhash=843d31…50db1c hash=4d6131…a7482f elapsed=3.787s
INFO [04-27|14:10:03.696] 🔗 block reached canonical chain          number=61 hash=bc95fa…2df067
INFO [04-27|14:10:03.705] Commit new mining work                   number=69 sealhash=d57771…94f39d uncles=0 txs=0 gas=0 fees=0 elapsed=8.939ms
INFO [04-27|14:10:03.705] 🔨 mined potential block                  number=68 hash=4d6131…a7482f
INFO [04-27|14:10:08.311] Looking for peers                        peercount=1 tried=91  static=0
INFO [04-27|14:10:15.978] Successfully sealed new block            number=69 sealhash=d57771…94f39d hash=191431…b45194 elapsed=12.282s
INFO [04-27|14:10:15.979] 🔗 block reached canonical chain          number=62 hash=bc0417…f2545b
INFO [04-27|14:10:15.990] Commit new mining work                   number=70 sealhash=d0f10c…9b9283 uncles=0 txs=0 gas=0 fees=0 elapsed=11.968ms
INFO [04-27|14:10:15.990] 🔨 mined potential block                  number=69 hash=191431…b45194
INFO [04-27|14:10:18.382] Looking for peers                        peercount=1 tried=67  static=0
INFO [04-27|14:10:18.802] Successfully sealed new block            number=70 sealhash=d0f10c…9b9283 hash=7a9434…c72d76 elapsed=2.823s
INFO [04-27|14:10:18.802] 🔗 block reached canonical chain          number=63 hash=a03851…d70153
INFO [04-27|14:10:18.810] 🔨 mined potential block                  number=70 hash=7a9434…c72d76
INFO [04-27|14:10:18.810] Commit new mining work                   number=71 sealhash=0b7479…ea0faf uncles=0 txs=0 gas=0 fees=0 elapsed=7.947ms
INFO [04-27|14:10:28.987] Looking for peers                        peercount=1 tried=163 static=0
INFO [04-27|14:10:33.752] Successfully sealed new block            number=71 sealhash=0b7479…ea0faf hash=726f03…f37f82 elapsed=14.950s
INFO [04-27|14:10:33.752] 🔗 block reached canonical chain          number=64 hash=1b2373…467d08
INFO [04-27|14:10:33.760] 🔨 mined potential block                  number=71 hash=726f03…f37f82
INFO [04-27|14:10:33.760] Commit new mining work                   number=72 sealhash=19f635…a49cc8 uncles=0 txs=0 gas=0 fees=0 elapsed=7.980ms
INFO [04-27|14:10:34.679] Successfully sealed new block            number=72 sealhash=19f635…a49cc8 hash=22693f…fa6c8c elapsed=926.523ms
INFO [04-27|14:10:34.679] 🔗 block reached canonical chain          number=65 hash=850077…03b2aa
INFO [04-27|14:10:34.688] 🔨 mined potential block                  number=72 hash=22693f…fa6c8c
INFO [04-27|14:10:34.688] Commit new mining work                   number=73 sealhash=e82e89…8d9a8f uncles=0 txs=0 gas=0 fees=0 elapsed=8.942ms
INFO [04-27|14:10:38.138] Successfully sealed new block            number=73 sealhash=e82e89…8d9a8f hash=f60c5a…3e20e9 elapsed=3.458s
INFO [04-27|14:10:38.139] 🔗 block reached canonical chain          number=66 hash=c919d1…ad493a
INFO [04-27|14:10:38.146] Commit new mining work                   number=74 sealhash=996b81…f68887 uncles=0 txs=0 gas=0 fees=0 elapsed=8.012ms
INFO [04-27|14:10:38.146] 🔨 mined potential block                  number=73 hash=f60c5a…3e20e9
INFO [04-27|14:10:39.078] Looking for peers                        peercount=1 tried=113 static=0
INFO [04-27|14:10:44.668] Successfully sealed new block            number=74 sealhash=996b81…f68887 hash=70668a…d5a072 elapsed=6.529s
INFO [04-27|14:10:44.669] 🔗 block reached canonical chain          number=67 hash=728fcc…9d63cc
INFO [04-27|14:10:44.677] 🔨 mined potential block                  number=74 hash=70668a…d5a072
INFO [04-27|14:10:44.677] Commit new mining work                   number=75 sealhash=245fe7…9a0d33 uncles=0 txs=0 gas=0 fees=0 elapsed=7.945ms
INFO [04-27|14:10:45.010] Successfully sealed new block            number=75 sealhash=245fe7…9a0d33 hash=bcadd0…e1f781 elapsed=341.054ms
INFO [04-27|14:10:45.010] 🔗 block reached canonical chain          number=68 hash=4d6131…a7482f
INFO [04-27|14:10:45.018] 🔨 mined potential block                  number=75 hash=bcadd0…e1f781
INFO [04-27|14:10:45.018] Commit new mining work                   number=76 sealhash=7eff0e…315e5b uncles=0 txs=0 gas=0 fees=0 elapsed=7.979ms
INFO [04-27|14:10:49.006] Successfully sealed new block            number=76 sealhash=7eff0e…315e5b hash=bda8d8…8da8f1 elapsed=3.995s
INFO [04-27|14:10:49.007] 🔗 block reached canonical chain          number=69 hash=191431…b45194
INFO [04-27|14:10:49.014] 🔨 mined potential block                  number=76 hash=bda8d8…8da8f1
INFO [04-27|14:10:49.014] Commit new mining work                   number=77 sealhash=7d8ae6…e1d7c6 uncles=0 txs=0 gas=0 fees=0 elapsed=7.944ms
INFO [04-27|14:10:49.131] Looking for peers                        peercount=1 tried=124 static=0
INFO [04-27|14:10:51.007] Successfully sealed new block            number=77 sealhash=7d8ae6…e1d7c6 hash=d850de…a99071 elapsed=2.000s
INFO [04-27|14:10:51.007] 🔗 block reached canonical chain          number=70 hash=7a9434…c72d76
INFO [04-27|14:10:51.016] Commit new mining work                   number=78 sealhash=7d0a17…2e4d68 uncles=0 txs=0 gas=0 fees=0 elapsed=8.940ms
INFO [04-27|14:10:51.016] 🔨 mined potential block                  number=77 hash=d850de…a99071
INFO [04-27|14:10:52.447] Successfully sealed new block            number=78 sealhash=7d0a17…2e4d68 hash=738ef9…627705 elapsed=1.439s
INFO [04-27|14:10:52.448] 🔗 block reached canonical chain          number=71 hash=726f03…f37f82
INFO [04-27|14:10:52.455] 🔨 mined potential block                  number=78 hash=738ef9…627705
INFO [04-27|14:10:52.455] Commit new mining work                   number=79 sealhash=5cb66b…c624a0 uncles=0 txs=0 gas=0 fees=0 elapsed=8.939ms
INFO [04-27|14:10:54.828] Successfully sealed new block            number=79 sealhash=5cb66b…c624a0 hash=8b04a0…761ecb elapsed=2.380s
INFO [04-27|14:10:54.828] 🔗 block reached canonical chain          number=72 hash=22693f…fa6c8c
INFO [04-27|14:10:54.838] 🔨 mined potential block                  number=79 hash=8b04a0…761ecb
INFO [04-27|14:10:54.838] Commit new mining work                   number=80 sealhash=4813a0…2b3079 uncles=0 txs=0 gas=0 fees=0 elapsed=9.972ms
INFO [04-27|14:10:56.485] Successfully sealed new block            number=80 sealhash=4813a0…2b3079 hash=a45d8f…bd0cd7 elapsed=1.656s
INFO [04-27|14:10:56.485] 🔗 block reached canonical chain          number=73 hash=f60c5a…3e20e9
INFO [04-27|14:10:56.495] 🔨 mined potential block                  number=80 hash=a45d8f…bd0cd7
INFO [04-27|14:10:56.496] Commit new mining work                   number=81 sealhash=4cf49c…eb98b9 uncles=0 txs=0 gas=0 fees=0 elapsed=10.936ms
INFO [04-27|14:10:59.161] Looking for peers                        peercount=1 tried=131 static=0
INFO [04-27|14:11:04.892] Successfully sealed new block            number=81 sealhash=4cf49c…eb98b9 hash=08cf4b…967307 elapsed=8.407s
INFO [04-27|14:11:04.892] 🔗 block reached canonical chain          number=74 hash=70668a…d5a072
INFO [04-27|14:11:04.900] Commit new mining work                   number=82 sealhash=bf917b…cc4146 uncles=0 txs=0 gas=0 fees=0 elapsed=7.978ms
INFO [04-27|14:11:04.900] 🔨 mined potential block                  number=81 hash=08cf4b…967307
INFO [04-27|14:11:07.899] Successfully sealed new block            number=82 sealhash=bf917b…cc4146 hash=f0cd6e…fb5b76 elapsed=3.006s
INFO [04-27|14:11:07.900] 🔗 block reached canonical chain          number=75 hash=bcadd0…e1f781
INFO [04-27|14:11:07.908] 🔨 mined potential block                  number=82 hash=f0cd6e…fb5b76
INFO [04-27|14:11:07.908] Commit new mining work                   number=83 sealhash=9ec589…8ce593 uncles=0 txs=0 gas=0 fees=0 elapsed=7.978ms
INFO [04-27|14:11:09.236] Looking for peers                        peercount=2 tried=94  static=0
INFO [04-27|14:11:18.960] Successfully sealed new block            number=83 sealhash=9ec589…8ce593 hash=11a4e7…d70cf7 elapsed=11.059s
INFO [04-27|14:11:18.960] 🔗 block reached canonical chain          number=76 hash=bda8d8…8da8f1
INFO [04-27|14:11:18.968] 🔨 mined potential block                  number=83 hash=11a4e7…d70cf7
INFO [04-27|14:11:18.968] Commit new mining work                   number=84 sealhash=1d8561…9cc3ef uncles=0 txs=0 gas=0 fees=0 elapsed=7.943ms
INFO [04-27|14:11:19.438] Looking for peers                        peercount=1 tried=66  static=0
INFO [04-27|14:11:22.405] Successfully sealed new block            number=84 sealhash=1d8561…9cc3ef hash=9717c8…a1926b elapsed=3.445s
INFO [04-27|14:11:22.405] 🔗 block reached canonical chain          number=77 hash=d850de…a99071
INFO [04-27|14:11:22.414] 🔨 mined potential block                  number=84 hash=9717c8…a1926b
INFO [04-27|14:11:22.414] Commit new mining work                   number=85 sealhash=99b80b…bf5241 uncles=0 txs=0 gas=0 fees=0 elapsed=8.974ms
INFO [04-27|14:11:28.420] Commit new mining work                   number=85 sealhash=73b241…3353f6 uncles=0 txs=1 gas=21000 fees=0.001071 elapsed=0s
INFO [04-27|14:11:29.445] Looking for peers                        peercount=1 tried=137 static=0
INFO [04-27|14:11:30.095] Successfully sealed new block            number=85 sealhash=73b241…3353f6 hash=1c9851…4c35b9 elapsed=1.674s
INFO [04-27|14:11:30.095] 🔗 block reached canonical chain          number=78 hash=738ef9…627705
INFO [04-27|14:11:30.104] 🔨 mined potential block                  number=85 hash=1c9851…4c35b9
INFO [04-27|14:11:30.104] Commit new mining work                   number=86 sealhash=9a3bd3…1b282f uncles=0 txs=0 gas=0     fees=0        elapsed=8.975ms
INFO [04-27|14:11:39.575] Looking for peers                        peercount=1 tried=83  static=0
INFO [04-27|14:11:49.649] Looking for peers                        peercount=2 tried=80  static=0
INFO [04-27|14:11:53.886] Successfully sealed new block            number=86 sealhash=9a3bd3…1b282f hash=a024f9…6dfec1 elapsed=23.791s
INFO [04-27|14:11:53.886] 🔗 block reached canonical chain          number=79 hash=8b04a0…761ecb
INFO [04-27|14:11:53.894] 🔨 mined potential block                  number=86 hash=a024f9…6dfec1
INFO [04-27|14:11:53.894] Commit new mining work                   number=87 sealhash=619d87…058d45 uncles=0 txs=0 gas=0     fees=0        elapsed=7.973ms
INFO [04-27|14:11:59.512] Successfully sealed new block            number=87 sealhash=619d87…058d45 hash=9da0e1…fac657 elapsed=5.625s
INFO [04-27|14:11:59.512] 🔗 block reached canonical chain          number=80 hash=a45d8f…bd0cd7
INFO [04-27|14:11:59.520] 🔨 mined potential block                  number=87 hash=9da0e1…fac657
INFO [04-27|14:11:59.520] Commit new mining work                   number=88 sealhash=c5e8a0…ca715b uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:11:59.650] Looking for peers                        peercount=1 tried=63  static=0
INFO [04-27|14:12:09.945] Looking for peers                        peercount=1 tried=72  static=0
INFO [04-27|14:12:16.302] Successfully sealed new block            number=88 sealhash=c5e8a0…ca715b hash=92351c…123af1 elapsed=16.790s
INFO [04-27|14:12:16.302] 🔗 block reached canonical chain          number=81 hash=08cf4b…967307
INFO [04-27|14:12:16.310] 🔨 mined potential block                  number=88 hash=92351c…123af1
INFO [04-27|14:12:16.310] Commit new mining work                   number=89 sealhash=f90b19…65bb8c uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:12:20.131] Looking for peers                        peercount=3 tried=80  static=0
INFO [04-27|14:12:25.133] Successfully sealed new block            number=89 sealhash=f90b19…65bb8c hash=71c90c…01a45a elapsed=8.830s
INFO [04-27|14:12:25.134] 🔗 block reached canonical chain          number=82 hash=f0cd6e…fb5b76
INFO [04-27|14:12:25.142] 🔨 mined potential block                  number=89 hash=71c90c…01a45a
INFO [04-27|14:12:25.142] Commit new mining work                   number=90 sealhash=0c24ea…a94a8d uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:12:25.442] Successfully sealed new block            number=90 sealhash=0c24ea…a94a8d hash=29007b…08caa9 elapsed=308.212ms
INFO [04-27|14:12:25.442] 🔗 block reached canonical chain          number=83 hash=11a4e7…d70cf7
INFO [04-27|14:12:25.450] Commit new mining work                   number=91 sealhash=dc08cd…39c9b2 uncles=0 txs=0 gas=0     fees=0        elapsed=7.941ms
INFO [04-27|14:12:25.450] 🔨 mined potential block                  number=90 hash=29007b…08caa9
INFO [04-27|14:12:30.196] Successfully sealed new block            number=91 sealhash=dc08cd…39c9b2 hash=59137c…24173f elapsed=4.753s
INFO [04-27|14:12:30.196] 🔗 block reached canonical chain          number=84 hash=9717c8…a1926b
INFO [04-27|14:12:30.205] Looking for peers                        peercount=1 tried=40  static=0
INFO [04-27|14:12:30.205] 🔨 mined potential block                  number=91 hash=59137c…24173f
INFO [04-27|14:12:30.205] Commit new mining work                   number=92 sealhash=666a07…46b502 uncles=0 txs=0 gas=0     fees=0        elapsed=8.977ms
INFO [04-27|14:12:33.616] Successfully sealed new block            number=92 sealhash=666a07…46b502 hash=179b17…61881c elapsed=3.420s
INFO [04-27|14:12:33.617] 🔗 block reached canonical chain          number=85 hash=1c9851…4c35b9
INFO [04-27|14:12:33.626] 🔨 mined potential block                  number=92 hash=179b17…61881c
INFO [04-27|14:12:33.626] Commit new mining work                   number=93 sealhash=81a4d4…1c58a2 uncles=0 txs=0 gas=0     fees=0        elapsed=9.931ms
INFO [04-27|14:12:35.599] Successfully sealed new block            number=93 sealhash=81a4d4…1c58a2 hash=3dbb90…3ee622 elapsed=1.981s
INFO [04-27|14:12:35.600] 🔗 block reached canonical chain          number=86 hash=a024f9…6dfec1
INFO [04-27|14:12:35.608] Commit new mining work                   number=94 sealhash=a59537…0251b3 uncles=0 txs=0 gas=0     fees=0        elapsed=8.954ms
INFO [04-27|14:12:35.608] 🔨 mined potential block                  number=93 hash=3dbb90…3ee622
INFO [04-27|14:12:35.619] Successfully sealed new block            number=94 sealhash=a59537…0251b3 hash=c4bca5…c7f3d4 elapsed=19.925ms
INFO [04-27|14:12:35.619] 🔗 block reached canonical chain          number=87 hash=9da0e1…fac657
INFO [04-27|14:12:35.629] 🔨 mined potential block                  number=94 hash=c4bca5…c7f3d4
INFO [04-27|14:12:35.629] Commit new mining work                   number=95 sealhash=5ca295…e4ff59 uncles=0 txs=0 gas=0     fees=0        elapsed=9.974ms
INFO [04-27|14:12:40.205] Looking for peers                        peercount=1 tried=47  static=0
INFO [04-27|14:12:50.249] Looking for peers                        peercount=2 tried=53  static=0
INFO [04-27|14:12:56.974] Successfully sealed new block            number=95 sealhash=5ca295…e4ff59 hash=b9cd73…decef1 elapsed=21.355s
INFO [04-27|14:12:56.974] 🔗 block reached canonical chain          number=88 hash=92351c…123af1
INFO [04-27|14:12:56.981] Commit new mining work                   number=96 sealhash=d75060…af959b uncles=0 txs=0 gas=0     fees=0        elapsed=6.947ms
INFO [04-27|14:12:56.981] 🔨 mined potential block                  number=95 hash=b9cd73…decef1
INFO [04-27|14:13:00.251] Looking for peers                        peercount=2 tried=39  static=0
INFO [04-27|14:13:02.182] Successfully sealed new block            number=96 sealhash=d75060…af959b hash=1a5d06…11af55 elapsed=5.208s
INFO [04-27|14:13:02.182] 🔗 block reached canonical chain          number=89 hash=71c90c…01a45a
INFO [04-27|14:13:02.189] 🔨 mined potential block                  number=96 hash=1a5d06…11af55
INFO [04-27|14:13:02.189] Commit new mining work                   number=97 sealhash=1501a7…1b6bae uncles=0 txs=0 gas=0     fees=0        elapsed=6.980ms
INFO [04-27|14:13:04.204] Successfully sealed new block            number=97 sealhash=1501a7…1b6bae hash=ac15bf…c32a2f elapsed=2.021s
INFO [04-27|14:13:04.204] 🔗 block reached canonical chain          number=90 hash=29007b…08caa9
INFO [04-27|14:13:04.212] 🔨 mined potential block                  number=97 hash=ac15bf…c32a2f
INFO [04-27|14:13:04.212] Commit new mining work                   number=98 sealhash=1039bb…53303e uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:13:05.003] Successfully sealed new block            number=98 sealhash=1039bb…53303e hash=61b030…84e199 elapsed=798.861ms
INFO [04-27|14:13:05.003] 🔗 block reached canonical chain          number=91 hash=59137c…24173f
INFO [04-27|14:13:05.011] Commit new mining work                   number=99 sealhash=eac24b…e778ec uncles=0 txs=0 gas=0     fees=0        elapsed=7.974ms
INFO [04-27|14:13:05.011] 🔨 mined potential block                  number=98 hash=61b030…84e199
INFO [04-27|14:13:10.384] Looking for peers                        peercount=1 tried=77  static=0
INFO [04-27|14:13:12.979] Successfully sealed new block            number=99 sealhash=eac24b…e778ec hash=62c59c…18b466 elapsed=7.976s
INFO [04-27|14:13:12.979] 🔗 block reached canonical chain          number=92 hash=179b17…61881c
INFO [04-27|14:13:12.986] 🔨 mined potential block                  number=99 hash=62c59c…18b466
INFO [04-27|14:13:12.986] Commit new mining work                   number=100 sealhash=f71f42…42bec5 uncles=0 txs=0 gas=0     fees=0        elapsed=6.941ms
INFO [04-27|14:13:13.651] Successfully sealed new block            number=100 sealhash=f71f42…42bec5 hash=191d44…c16cf9 elapsed=672.161ms
INFO [04-27|14:13:13.652] 🔗 block reached canonical chain          number=93  hash=3dbb90…3ee622
INFO [04-27|14:13:13.660] Commit new mining work                   number=101 sealhash=89c69f…93d6dd uncles=0 txs=0 gas=0     fees=0        elapsed=8.976ms
INFO [04-27|14:13:13.660] 🔨 mined potential block                  number=100 hash=191d44…c16cf9
INFO [04-27|14:13:20.474] Looking for peers                        peercount=1 tried=59  static=0
INFO [04-27|14:13:24.407] Successfully sealed new block            number=101 sealhash=89c69f…93d6dd hash=986d0a…7a7806 elapsed=10.754s
INFO [04-27|14:13:24.407] 🔗 block reached canonical chain          number=94  hash=c4bca5…c7f3d4
INFO [04-27|14:13:24.416] 🔨 mined potential block                  number=101 hash=986d0a…7a7806
INFO [04-27|14:13:24.416] Commit new mining work                   number=102 sealhash=596e77…1801af uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:13:25.429] Successfully sealed new block            number=102 sealhash=596e77…1801af hash=4d4bd6…7b4dcf elapsed=1.022s
INFO [04-27|14:13:25.429] 🔗 block reached canonical chain          number=95  hash=b9cd73…decef1
INFO [04-27|14:13:25.437] 🔨 mined potential block                  number=102 hash=4d4bd6…7b4dcf
INFO [04-27|14:13:25.437] Commit new mining work                   number=103 sealhash=919f72…9af8df uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:13:30.483] Looking for peers                        peercount=1 tried=41  static=0
INFO [04-27|14:13:36.682] Successfully sealed new block            number=103 sealhash=919f72…9af8df hash=9ba156…15d2e3 elapsed=11.253s
INFO [04-27|14:13:36.682] 🔗 block reached canonical chain          number=96  hash=1a5d06…11af55
INFO [04-27|14:13:36.690] 🔨 mined potential block                  number=103 hash=9ba156…15d2e3
INFO [04-27|14:13:36.690] Commit new mining work                   number=104 sealhash=c1e85e…47a53b uncles=0 txs=0 gas=0     fees=0        elapsed=7.946ms
INFO [04-27|14:13:40.719] Looking for peers                        peercount=1 tried=93  static=0
INFO [04-27|14:13:50.896] Looking for peers                        peercount=1 tried=108 static=0
INFO [04-27|14:13:55.700] Successfully sealed new block            number=104 sealhash=c1e85e…47a53b hash=a0779b…20f464 elapsed=19.018s
INFO [04-27|14:13:55.700] 🔗 block reached canonical chain          number=97  hash=ac15bf…c32a2f
INFO [04-27|14:13:55.708] 🔨 mined potential block                  number=104 hash=a0779b…20f464
INFO [04-27|14:13:55.708] Commit new mining work                   number=105 sealhash=158a00…ce1ff4 uncles=0 txs=0 gas=0     fees=0        elapsed=7.977ms
INFO [04-27|14:13:56.073] Successfully sealed new block            number=105 sealhash=158a00…ce1ff4 hash=781393…073777 elapsed=373.000ms
INFO [04-27|14:13:56.073] 🔗 block reached canonical chain          number=98  hash=61b030…84e199
INFO [04-27|14:13:56.082] Commit new mining work                   number=106 sealhash=b13bdd…a5e2c7 uncles=0 txs=0 gas=0     fees=0        elapsed=9.003ms
INFO [04-27|14:13:56.082] 🔨 mined potential block                  number=105 hash=781393…073777
INFO [04-27|14:13:58.116] Successfully sealed new block            number=106 sealhash=b13bdd…a5e2c7 hash=499028…e4d6da elapsed=2.042s
INFO [04-27|14:13:58.116] 🔗 block reached canonical chain          number=99  hash=62c59c…18b466
INFO [04-27|14:13:58.124] Commit new mining work                   number=107 sealhash=648984…1fc47a uncles=0 txs=0 gas=0     fees=0        elapsed=8.006ms
INFO [04-27|14:13:58.124] 🔨 mined potential block                  number=106 hash=499028…e4d6da
INFO [04-27|14:14:00.380] Successfully sealed new block            number=107 sealhash=648984…1fc47a hash=9ca084…9228c9 elapsed=2.263s
INFO [04-27|14:14:00.380] 🔗 block reached canonical chain          number=100 hash=191d44…c16cf9
INFO [04-27|14:14:00.388] 🔨 mined potential block                  number=107 hash=9ca084…9228c9
INFO [04-27|14:14:00.388] Commit new mining work                   number=108 sealhash=f6497e…e81a8d uncles=0 txs=0 gas=0     fees=0        elapsed=7.956ms
INFO [04-27|14:14:00.902] Looking for peers                        peercount=1 tried=107 static=0
INFO [04-27|14:14:01.575] Successfully sealed new block            number=108 sealhash=f6497e…e81a8d hash=d41857…d5ecf0 elapsed=1.195s
INFO [04-27|14:14:01.575] 🔗 block reached canonical chain          number=101 hash=986d0a…7a7806
INFO [04-27|14:14:01.583] 🔨 mined potential block                  number=108 hash=d41857…d5ecf0
INFO [04-27|14:14:01.583] Commit new mining work                   number=109 sealhash=f5e387…490850 uncles=0 txs=0 gas=0     fees=0        elapsed=7.971ms
INFO [04-27|14:14:06.093] Successfully sealed new block            number=109 sealhash=f5e387…490850 hash=5a0aee…b274ed elapsed=4.517s
INFO [04-27|14:14:06.093] 🔗 block reached canonical chain          number=102 hash=4d4bd6…7b4dcf
INFO [04-27|14:14:06.103] 🔨 mined potential block                  number=109 hash=5a0aee…b274ed
INFO [04-27|14:14:06.103] Commit new mining work                   number=110 sealhash=f10837…1d1fd8 uncles=0 txs=0 gas=0     fees=0        elapsed=9.974ms
INFO [04-27|14:14:14.024] Successfully sealed new block            number=110 sealhash=f10837…1d1fd8 hash=b5a88d…d4a24d elapsed=7.930s
INFO [04-27|14:14:14.024] 🔗 block reached canonical chain          number=103 hash=9ba156…15d2e3
INFO [04-27|14:14:14.032] 🔨 mined potential block                  number=110 hash=b5a88d…d4a24d
INFO [04-27|14:14:14.032] Commit new mining work                   number=111 sealhash=81bddf…006b23 uncles=0 txs=0 gas=0     fees=0        elapsed=7.973ms
INFO [04-27|14:14:19.058] Successfully sealed new block            number=111 sealhash=81bddf…006b23 hash=b9d620…593cd1 elapsed=5.033s
INFO [04-27|14:14:19.058] 🔗 block reached canonical chain          number=104 hash=a0779b…20f464
INFO [04-27|14:14:19.067] 🔨 mined potential block                  number=111 hash=b9d620…593cd1
INFO [04-27|14:14:19.067] Commit new mining work                   number=112 sealhash=d8c4e8…80780b uncles=0 txs=0 gas=0     fees=0        elapsed=8.976ms
INFO [04-27|14:14:21.139] Looking for peers                        peercount=1 tried=94  static=0
INFO [04-27|14:14:21.907] Successfully sealed new block            number=112 sealhash=d8c4e8…80780b hash=514025…684a60 elapsed=2.849s
INFO [04-27|14:14:21.907] 🔗 block reached canonical chain          number=105 hash=781393…073777
INFO [04-27|14:14:21.914] 🔨 mined potential block                  number=112 hash=514025…684a60
INFO [04-27|14:14:21.914] Commit new mining work                   number=113 sealhash=6073aa…c37a38 uncles=0 txs=0 gas=0     fees=0        elapsed=6.977ms
INFO [04-27|14:14:26.318] Successfully sealed new block            number=113 sealhash=6073aa…c37a38 hash=150289…50bbd2 elapsed=4.411s
INFO [04-27|14:14:26.319] 🔗 block reached canonical chain          number=106 hash=499028…e4d6da
INFO [04-27|14:14:26.327] 🔨 mined potential block                  number=113 hash=150289…50bbd2
INFO [04-27|14:14:26.327] Commit new mining work                   number=114 sealhash=d490df…9ecae9 uncles=0 txs=0 gas=0     fees=0        elapsed=8.941ms
INFO [04-27|14:14:31.477] Looking for peers                        peercount=1 tried=140 static=0
INFO [04-27|14:14:37.125] Successfully sealed new block            number=114 sealhash=d490df…9ecae9 hash=9a87c1…8640e9 elapsed=10.806s
INFO [04-27|14:14:37.125] 🔗 block reached canonical chain          number=107 hash=9ca084…9228c9
INFO [04-27|14:14:37.134] 🔨 mined potential block                  number=114 hash=9a87c1…8640e9
INFO [04-27|14:14:37.134] Commit new mining work                   number=115 sealhash=c05f5d…015084 uncles=0 txs=0 gas=0     fees=0        elapsed=8.976ms
INFO [04-27|14:14:41.525] Looking for peers                        peercount=2 tried=104 static=0
INFO [04-27|14:14:42.388] Successfully sealed new block            number=115 sealhash=c05f5d…015084 hash=d81e31…1aaf48 elapsed=5.262s
INFO [04-27|14:14:42.388] 🔗 block reached canonical chain          number=108 hash=d41857…d5ecf0
INFO [04-27|14:14:42.395] 🔨 mined potential block                  number=115 hash=d81e31…1aaf48
INFO [04-27|14:14:42.395] Commit new mining work                   number=116 sealhash=488f99…6d602e uncles=0 txs=0 gas=0     fees=0        elapsed=6.976ms
INFO [04-27|14:14:43.748] Successfully sealed new block            number=116 sealhash=488f99…6d602e hash=8bd3b2…d9550a elapsed=1.359s
INFO [04-27|14:14:43.748] 🔗 block reached canonical chain          number=109 hash=5a0aee…b274ed
INFO [04-27|14:14:43.757] 🔨 mined potential block                  number=116 hash=8bd3b2…d9550a
INFO [04-27|14:14:43.757] Commit new mining work                   number=117 sealhash=b2ec25…5dd1f3 uncles=0 txs=0 gas=0     fees=0        elapsed=8.940ms
INFO [04-27|14:14:51.665] Looking for peers                        peercount=1 tried=65  static=0
INFO [04-27|14:14:53.053] Successfully sealed new block            number=117 sealhash=b2ec25…5dd1f3 hash=b96d8e…81ba75 elapsed=9.305s
INFO [04-27|14:14:53.053] 🔗 block reached canonical chain          number=110 hash=b5a88d…d4a24d
INFO [04-27|14:14:53.062] 🔨 mined potential block                  number=117 hash=b96d8e…81ba75
INFO [04-27|14:14:53.062] Commit new mining work                   number=118 sealhash=06be38…52f7d0 uncles=0 txs=0 gas=0     fees=0        elapsed=8.940ms
INFO [04-27|14:14:56.032] Successfully sealed new block            number=118 sealhash=06be38…52f7d0 hash=f5d679…4eb272 elapsed=2.979s
INFO [04-27|14:14:56.032] 🔗 block reached canonical chain          number=111 hash=b9d620…593cd1
INFO [04-27|14:14:56.043] Commit new mining work                   number=119 sealhash=c9fccb…518735 uncles=0 txs=0 gas=0     fees=0        elapsed=10.938ms
INFO [04-27|14:14:56.043] 🔨 mined potential block                  number=118 hash=f5d679…4eb272
INFO [04-27|14:14:56.978] Successfully sealed new block            number=119 sealhash=c9fccb…518735 hash=a54986…930f94 elapsed=946.434ms
INFO [04-27|14:14:56.978] 🔗 block reached canonical chain          number=112 hash=514025…684a60
INFO [04-27|14:14:56.988] 🔨 mined potential block                  number=119 hash=a54986…930f94
INFO [04-27|14:14:56.988] Commit new mining work                   number=120 sealhash=c9be4c…0fe242 uncles=0 txs=0 gas=0     fees=0        elapsed=9.973ms
INFO [04-27|14:15:00.645] Successfully sealed new block            number=120 sealhash=c9be4c…0fe242 hash=11433b…d69a68 elapsed=3.667s
INFO [04-27|14:15:00.645] 🔗 block reached canonical chain          number=113 hash=150289…50bbd2
INFO [04-27|14:15:00.652] 🔨 mined potential block                  number=120 hash=11433b…d69a68
INFO [04-27|14:15:00.652] Commit new mining work                   number=121 sealhash=d0b8f4…33c158 uncles=0 txs=0 gas=0     fees=0        elapsed=7.014ms
INFO [04-27|14:15:01.711] Looking for peers                        peercount=1 tried=115 static=0
INFO [04-27|14:15:06.225] Successfully sealed new block            number=121 sealhash=d0b8f4…33c158 hash=990a3d…296a19 elapsed=5.579s
INFO [04-27|14:15:06.225] 🔗 block reached canonical chain          number=114 hash=9a87c1…8640e9
INFO [04-27|14:15:06.233] Commit new mining work                   number=122 sealhash=d120a4…d68c8a uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:15:06.233] 🔨 mined potential block                  number=121 hash=990a3d…296a19
INFO [04-27|14:15:07.037] Successfully sealed new block            number=122 sealhash=d120a4…d68c8a hash=d87b67…845d8c elapsed=812.825ms
INFO [04-27|14:15:07.037] 🔗 block reached canonical chain          number=115 hash=d81e31…1aaf48
INFO [04-27|14:15:07.045] 🔨 mined potential block                  number=122 hash=d87b67…845d8c
INFO [04-27|14:15:07.045] Commit new mining work                   number=123 sealhash=298430…4a6d33 uncles=0 txs=0 gas=0     fees=0        elapsed=7.958ms
INFO [04-27|14:15:11.846] Looking for peers                        peercount=1 tried=130 static=0
INFO [04-27|14:15:21.928] Looking for peers                        peercount=2 tried=124 static=0
INFO [04-27|14:15:32.011] Looking for peers                        peercount=1 tried=61  static=0
INFO [04-27|14:15:32.497] Successfully sealed new block            number=123 sealhash=298430…4a6d33 hash=dc8f89…a05733 elapsed=25.459s
INFO [04-27|14:15:32.497] 🔗 block reached canonical chain          number=116 hash=8bd3b2…d9550a
INFO [04-27|14:15:32.506] 🔨 mined potential block                  number=123 hash=dc8f89…a05733
INFO [04-27|14:15:32.506] Commit new mining work                   number=124 sealhash=e89d99…dd3ce9 uncles=0 txs=0 gas=0     fees=0        elapsed=8.940ms
INFO [04-27|14:15:36.702] Successfully sealed new block            number=124 sealhash=e89d99…dd3ce9 hash=c912c1…d77789 elapsed=4.204s
INFO [04-27|14:15:36.702] 🔗 block reached canonical chain          number=117 hash=b96d8e…81ba75
INFO [04-27|14:15:36.711] 🔨 mined potential block                  number=124 hash=c912c1…d77789
INFO [04-27|14:15:36.711] Commit new mining work                   number=125 sealhash=3e64b8…6f7eec uncles=0 txs=0 gas=0     fees=0        elapsed=8.970ms
INFO [04-27|14:15:38.687] Successfully sealed new block            number=125 sealhash=3e64b8…6f7eec hash=6d821a…f85f83 elapsed=1.984s
INFO [04-27|14:15:38.687] 🔗 block reached canonical chain          number=118 hash=f5d679…4eb272
INFO [04-27|14:15:38.697] Commit new mining work                   number=126 sealhash=319200…79d7f9 uncles=0 txs=0 gas=0     fees=0        elapsed=9.973ms
INFO [04-27|14:15:38.697] 🔨 mined potential block                  number=125 hash=6d821a…f85f83
INFO [04-27|14:15:42.038] Looking for peers                        peercount=2 tried=108 static=0
INFO [04-27|14:15:42.314] Successfully sealed new block            number=126 sealhash=319200…79d7f9 hash=a2f807…43dff1 elapsed=3.627s
INFO [04-27|14:15:42.315] 🔗 block reached canonical chain          number=119 hash=a54986…930f94
INFO [04-27|14:15:42.323] Commit new mining work                   number=127 sealhash=81b3e6…a33080 uncles=0 txs=0 gas=0     fees=0        elapsed=8.982ms
INFO [04-27|14:15:42.323] 🔨 mined potential block                  number=126 hash=a2f807…43dff1
INFO [04-27|14:15:52.039] Looking for peers                        peercount=3 tried=60  static=0
INFO [04-27|14:15:57.676] Successfully sealed new block            number=127 sealhash=81b3e6…a33080 hash=91f907…d6efb9 elapsed=15.360s
INFO [04-27|14:15:57.676] 🔗 block reached canonical chain          number=120 hash=11433b…d69a68
INFO [04-27|14:15:57.684] Commit new mining work                   number=128 sealhash=c60c55…b7fc51 uncles=0 txs=0 gas=0     fees=0        elapsed=7.941ms
INFO [04-27|14:15:57.684] 🔨 mined potential block                  number=127 hash=91f907…d6efb9
INFO [04-27|14:15:59.046] Successfully sealed new block            number=128 sealhash=c60c55…b7fc51 hash=82ac15…bd501d elapsed=1.370s
INFO [04-27|14:15:59.046] 🔗 block reached canonical chain          number=121 hash=990a3d…296a19
INFO [04-27|14:15:59.055] 🔨 mined potential block                  number=128 hash=82ac15…bd501d
INFO [04-27|14:15:59.055] Commit new mining work                   number=129 sealhash=9a274f…6bd49a uncles=0 txs=0 gas=0     fees=0        elapsed=8.939ms
INFO [04-27|14:16:02.072] Looking for peers                        peercount=1 tried=122 static=0
INFO [04-27|14:16:05.647] Successfully sealed new block            number=129 sealhash=9a274f…6bd49a hash=7670b4…52d4eb elapsed=6.600s
INFO [04-27|14:16:05.647] 🔗 block reached canonical chain          number=122 hash=d87b67…845d8c
INFO [04-27|14:16:05.656] 🔨 mined potential block                  number=129 hash=7670b4…52d4eb
INFO [04-27|14:16:05.656] Commit new mining work                   number=130 sealhash=a706e4…eeddd3 uncles=0 txs=0 gas=0     fees=0        elapsed=8.976ms
INFO [04-27|14:16:12.098] Looking for peers                        peercount=2 tried=56  static=0
INFO [04-27|14:16:22.102] Looking for peers                        peercount=1 tried=84  static=0
INFO [04-27|14:16:23.536] Successfully sealed new block            number=130 sealhash=a706e4…eeddd3 hash=bca096…c312e6 elapsed=17.889s
INFO [04-27|14:16:23.536] 🔗 block reached canonical chain          number=123 hash=dc8f89…a05733
INFO [04-27|14:16:23.545] 🔨 mined potential block                  number=130 hash=bca096…c312e6
INFO [04-27|14:16:23.545] Commit new mining work                   number=131 sealhash=4dfb2f…9efa52 uncles=0 txs=0 gas=0     fees=0        elapsed=8.976ms
INFO [04-27|14:16:25.750] Successfully sealed new block            number=131 sealhash=4dfb2f…9efa52 hash=65b97b…3ee2f7 elapsed=2.214s
INFO [04-27|14:16:25.750] 🔗 block reached canonical chain          number=124 hash=c912c1…d77789
INFO [04-27|14:16:25.757] 🔨 mined potential block                  number=131 hash=65b97b…3ee2f7
INFO [04-27|14:16:25.757] Commit new mining work                   number=132 sealhash=c8176b…87993c uncles=0 txs=0 gas=0     fees=0        elapsed=6.98ms
INFO [04-27|14:16:31.354] Successfully sealed new block            number=132 sealhash=c8176b…87993c hash=379eb0…da86e0 elapsed=5.604s
INFO [04-27|14:16:31.354] 🔗 block reached canonical chain          number=125 hash=6d821a…f85f83
INFO [04-27|14:16:31.365] Commit new mining work                   number=133 sealhash=b0562d…cfff58 uncles=0 txs=0 gas=0     fees=0        elapsed=10.936ms
INFO [04-27|14:16:31.365] 🔨 mined potential block                  number=132 hash=379eb0…da86e0
INFO [04-27|14:16:31.814] Successfully sealed new block            number=133 sealhash=b0562d…cfff58 hash=81a809…19df75 elapsed=459.770ms
INFO [04-27|14:16:31.814] 🔗 block reached canonical chain          number=126 hash=a2f807…43dff1
INFO [04-27|14:16:31.821] 🔨 mined potential block                  number=133 hash=81a809…19df75
INFO [04-27|14:16:31.821] Commit new mining work                   number=134 sealhash=61b3eb…6a0447 uncles=0 txs=0 gas=0     fees=0        elapsed=6.983ms
INFO [04-27|14:16:32.178] Looking for peers                        peercount=1 tried=36  static=0
INFO [04-27|14:16:42.261] Looking for peers                        peercount=3 tried=61  static=0
INFO [04-27|14:16:46.149] Successfully sealed new block            number=134 sealhash=61b3eb…6a0447 hash=7011b9…67ebec elapsed=14.335s
INFO [04-27|14:16:46.149] 🔗 block reached canonical chain          number=127 hash=91f907…d6efb9
INFO [04-27|14:16:46.157] 🔨 mined potential block                  number=134 hash=7011b9…67ebec
INFO [04-27|14:16:46.157] Commit new mining work                   number=135 sealhash=1ce94c…af424f uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:16:52.391] Looking for peers                        peercount=1 tried=56  static=0
INFO [04-27|14:16:55.731] Successfully sealed new block            number=135 sealhash=1ce94c…af424f hash=624d0b…a3e522 elapsed=9.581s
INFO [04-27|14:16:55.731] 🔗 block reached canonical chain          number=128 hash=82ac15…bd501d
INFO [04-27|14:16:55.739] 🔨 mined potential block                  number=135 hash=624d0b…a3e522
INFO [04-27|14:16:55.739] Commit new mining work                   number=136 sealhash=02e2a3…4dbc59 uncles=0 txs=0 gas=0     fees=0        elapsed=7.943ms
INFO [04-27|14:16:59.493] Successfully sealed new block            number=136 sealhash=02e2a3…4dbc59 hash=31d44d…548fa0 elapsed=3.761s
INFO [04-27|14:16:59.493] 🔗 block reached canonical chain          number=129 hash=7670b4…52d4eb
INFO [04-27|14:16:59.502] 🔨 mined potential block                  number=136 hash=31d44d…548fa0
INFO [04-27|14:16:59.502] Commit new mining work                   number=137 sealhash=156946…d0a2c0 uncles=0 txs=0 gas=0     fees=0        elapsed=8.941ms
INFO [04-27|14:17:02.392] Looking for peers                        peercount=2 tried=55  static=0
INFO [04-27|14:17:03.747] Successfully sealed new block            number=137 sealhash=156946…d0a2c0 hash=8354ae…9c6a18 elapsed=4.254s
INFO [04-27|14:17:03.748] 🔗 block reached canonical chain          number=130 hash=bca096…c312e6
INFO [04-27|14:17:03.756] Commit new mining work                   number=138 sealhash=31bf40…7eb853 uncles=0 txs=0 gas=0     fees=0        elapsed=8.973ms
INFO [04-27|14:17:03.757] 🔨 mined potential block                  number=137 hash=8354ae…9c6a18
INFO [04-27|14:17:06.837] Successfully sealed new block            number=138 sealhash=31bf40…7eb853 hash=c7f625…41f5d6 elapsed=3.088s
INFO [04-27|14:17:06.837] 🔗 block reached canonical chain          number=131 hash=65b97b…3ee2f7
INFO [04-27|14:17:06.846] 🔨 mined potential block                  number=138 hash=c7f625…41f5d6
INFO [04-27|14:17:06.846] Commit new mining work                   number=139 sealhash=ef7005…b8d9bd uncles=0 txs=0 gas=0     fees=0        elapsed=8.960ms
INFO [04-27|14:17:07.237] Successfully sealed new block            number=139 sealhash=ef7005…b8d9bd hash=a918b0…b35487 elapsed=399.897ms
INFO [04-27|14:17:07.237] 🔗 block reached canonical chain          number=132 hash=379eb0…da86e0
INFO [04-27|14:17:07.245] 🔨 mined potential block                  number=139 hash=a918b0…b35487
INFO [04-27|14:17:07.245] Commit new mining work                   number=140 sealhash=498a39…1e5c62 uncles=0 txs=0 gas=0     fees=0        elapsed=7.977ms
INFO [04-27|14:17:07.773] Successfully sealed new block            number=140 sealhash=498a39…1e5c62 hash=f19d51…bf69bc elapsed=535.630ms
INFO [04-27|14:17:07.773] 🔗 block reached canonical chain          number=133 hash=81a809…19df75
INFO [04-27|14:17:07.781] 🔨 mined potential block                  number=140 hash=f19d51…bf69bc
INFO [04-27|14:17:07.781] Commit new mining work                   number=141 sealhash=a9893f…85322a uncles=0 txs=0 gas=0     fees=0        elapsed=8.912ms
INFO [04-27|14:17:12.401] Looking for peers                        peercount=1 tried=56  static=0
INFO [04-27|14:17:22.401] Looking for peers                        peercount=1 tried=58  static=0
INFO [04-27|14:17:22.797] Successfully sealed new block            number=141 sealhash=a9893f…85322a hash=3d74c3…e26be1 elapsed=15.024s
INFO [04-27|14:17:22.797] 🔗 block reached canonical chain          number=134 hash=7011b9…67ebec
INFO [04-27|14:17:22.804] Commit new mining work                   number=142 sealhash=07b3d2…bf2374 uncles=0 txs=0 gas=0     fees=0        elapsed=6.936ms
INFO [04-27|14:17:22.804] 🔨 mined potential block                  number=141 hash=3d74c3…e26be1
INFO [04-27|14:17:22.895] Successfully sealed new block            number=142 sealhash=07b3d2…bf2374 hash=2a8170…5de1af elapsed=97.724ms
INFO [04-27|14:17:22.896] 🔗 block reached canonical chain          number=135 hash=624d0b…a3e522
INFO [04-27|14:17:22.903] 🔨 mined potential block                  number=142 hash=2a8170…5de1af
INFO [04-27|14:17:22.903] Commit new mining work                   number=143 sealhash=7a1937…0726da uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:17:29.946] Successfully sealed new block            number=143 sealhash=7a1937…0726da hash=dc478e…ffc959 elapsed=7.050s
INFO [04-27|14:17:29.946] 🔗 block reached canonical chain          number=136 hash=31d44d…548fa0
INFO [04-27|14:17:29.955] 🔨 mined potential block                  number=143 hash=dc478e…ffc959
INFO [04-27|14:17:29.955] Commit new mining work                   number=144 sealhash=a744e3…50ed43 uncles=0 txs=0 gas=0     fees=0        elapsed=8.942ms
INFO [04-27|14:17:30.171] Successfully sealed new block            number=144 sealhash=a744e3…50ed43 hash=ab7773…b2f0be elapsed=224.398ms
INFO [04-27|14:17:30.171] 🔗 block reached canonical chain          number=137 hash=8354ae…9c6a18
INFO [04-27|14:17:30.178] Commit new mining work                   number=145 sealhash=96cc4f…a04186 uncles=0 txs=0 gas=0     fees=0        elapsed=6.948ms
INFO [04-27|14:17:30.178] 🔨 mined potential block                  number=144 hash=ab7773…b2f0be
INFO [04-27|14:17:30.219] Successfully sealed new block            number=145 sealhash=96cc4f…a04186 hash=352055…ec88f2 elapsed=47.871ms
INFO [04-27|14:17:30.220] 🔗 block reached canonical chain          number=138 hash=c7f625…41f5d6
INFO [04-27|14:17:30.227] 🔨 mined potential block                  number=145 hash=352055…ec88f2
INFO [04-27|14:17:30.227] Commit new mining work                   number=146 sealhash=e570a9…927e79 uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:17:31.150] Successfully sealed new block            number=146 sealhash=e570a9…927e79 hash=faba2b…423b62 elapsed=930.497ms
INFO [04-27|14:17:31.150] 🔗 block reached canonical chain          number=139 hash=a918b0…b35487
INFO [04-27|14:17:31.158] 🔨 mined potential block                  number=146 hash=faba2b…423b62
INFO [04-27|14:17:31.158] Commit new mining work                   number=147 sealhash=092cfb…e88648 uncles=0 txs=0 gas=0     fees=0        elapsed=7.947ms
INFO [04-27|14:17:31.587] Successfully sealed new block            number=147 sealhash=092cfb…e88648 hash=d36aac…3b1490 elapsed=436.837ms
INFO [04-27|14:17:31.587] Mining too far in the future             wait=2s
INFO [04-27|14:17:31.593] 🔗 block reached canonical chain          number=140 hash=f19d51…bf69bc
INFO [04-27|14:17:31.600] 🔨 mined potential block                  number=147 hash=d36aac…3b1490
INFO [04-27|14:17:32.545] Looking for peers                        peercount=1 tried=65  static=0
INFO [04-27|14:17:33.597] Commit new mining work                   number=148 sealhash=c8cb04…6437fd uncles=0 txs=0 gas=0     fees=0        elapsed=2.009s
INFO [04-27|14:17:33.785] Successfully sealed new block            number=148 sealhash=c8cb04…6437fd hash=29b6be…62aa9e elapsed=188.361ms
INFO [04-27|14:17:33.785] 🔗 block reached canonical chain          number=141 hash=3d74c3…e26be1
INFO [04-27|14:17:33.795] Commit new mining work                   number=149 sealhash=bfbde2…26f99c uncles=0 txs=0 gas=0     fees=0        elapsed=9.930ms
INFO [04-27|14:17:33.795] 🔨 mined potential block                  number=148 hash=29b6be…62aa9e
INFO [04-27|14:17:36.718] Successfully sealed new block            number=149 sealhash=bfbde2…26f99c hash=0a9c80…c3ebd8 elapsed=2.933s
INFO [04-27|14:17:36.718] 🔗 block reached canonical chain          number=142 hash=2a8170…5de1af
INFO [04-27|14:17:36.727] 🔨 mined potential block                  number=149 hash=0a9c80…c3ebd8
INFO [04-27|14:17:36.727] Commit new mining work                   number=150 sealhash=6c6cbe…c630b8 uncles=0 txs=0 gas=0     fees=0        elapsed=8.945ms
INFO [04-27|14:17:40.194] Successfully sealed new block            number=150 sealhash=6c6cbe…c630b8 hash=aaeb56…58ebbc elapsed=3.475s
INFO [04-27|14:17:40.194] 🔗 block reached canonical chain          number=143 hash=dc478e…ffc959
INFO [04-27|14:17:40.203] 🔨 mined potential block                  number=150 hash=aaeb56…58ebbc
INFO [04-27|14:17:40.203] Commit new mining work                   number=151 sealhash=d5ff13…e5f3e8 uncles=0 txs=0 gas=0     fees=0        elapsed=8.973ms
INFO [04-27|14:17:42.758] Looking for peers                        peercount=1 tried=45  static=0
INFO [04-27|14:17:44.721] Successfully sealed new block            number=151 sealhash=d5ff13…e5f3e8 hash=b06304…b146c9 elapsed=4.526s
INFO [04-27|14:17:44.721] 🔗 block reached canonical chain          number=144 hash=ab7773…b2f0be
INFO [04-27|14:17:44.729] 🔨 mined potential block                  number=151 hash=b06304…b146c9
INFO [04-27|14:17:44.729] Commit new mining work                   number=152 sealhash=a63b23…3343bf uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:17:51.097] Successfully sealed new block            number=152 sealhash=a63b23…3343bf hash=cfdb6d…762fe0 elapsed=6.375s
INFO [04-27|14:17:51.097] 🔗 block reached canonical chain          number=145 hash=352055…ec88f2
INFO [04-27|14:17:51.106] 🔨 mined potential block                  number=152 hash=cfdb6d…762fe0
INFO [04-27|14:17:51.106] Commit new mining work                   number=153 sealhash=5e6243…9e335a uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:17:52.807] Looking for peers                        peercount=2 tried=46  static=0
INFO [04-27|14:17:54.540] Successfully sealed new block            number=153 sealhash=5e6243…9e335a hash=7bdcc1…45dec6 elapsed=3.442s
INFO [04-27|14:17:54.540] 🔗 block reached canonical chain          number=146 hash=faba2b…423b62
INFO [04-27|14:17:54.548] 🔨 mined potential block                  number=153 hash=7bdcc1…45dec6
INFO [04-27|14:17:54.548] Commit new mining work                   number=154 sealhash=5667ed…c5de8c uncles=0 txs=0 gas=0     fees=0        elapsed=7.977ms
INFO [04-27|14:17:55.703] Successfully sealed new block            number=154 sealhash=5667ed…c5de8c hash=d2c6cf…37e8b4 elapsed=1.163s
INFO [04-27|14:17:55.703] 🔗 block reached canonical chain          number=147 hash=d36aac…3b1490
INFO [04-27|14:17:55.713] 🔨 mined potential block                  number=154 hash=d2c6cf…37e8b4
INFO [04-27|14:17:55.713] Commit new mining work                   number=155 sealhash=c3f5e4…a610d1 uncles=0 txs=0 gas=0     fees=0        elapsed=9.959ms
INFO [04-27|14:17:59.479] Successfully sealed new block            number=155 sealhash=c3f5e4…a610d1 hash=406d7d…076274 elapsed=3.775s
INFO [04-27|14:17:59.479] 🔗 block reached canonical chain          number=148 hash=29b6be…62aa9e
INFO [04-27|14:17:59.488] 🔨 mined potential block                  number=155 hash=406d7d…076274
INFO [04-27|14:17:59.488] Commit new mining work                   number=156 sealhash=4a382a…d8c3c6 uncles=0 txs=0 gas=0     fees=0        elapsed=8.964ms
INFO [04-27|14:18:00.645] Successfully sealed new block            number=156 sealhash=4a382a…d8c3c6 hash=bb921e…eb9f07 elapsed=1.165s
INFO [04-27|14:18:00.645] 🔗 block reached canonical chain          number=149 hash=0a9c80…c3ebd8
INFO [04-27|14:18:00.654] 🔨 mined potential block                  number=156 hash=bb921e…eb9f07
INFO [04-27|14:18:00.654] Commit new mining work                   number=157 sealhash=338d9a…5f049f uncles=0 txs=0 gas=0     fees=0        elapsed=8.968ms
INFO [04-27|14:18:02.695] Successfully sealed new block            number=157 sealhash=338d9a…5f049f hash=a13567…9de892 elapsed=2.049s
INFO [04-27|14:18:02.695] 🔗 block reached canonical chain          number=150 hash=aaeb56…58ebbc
INFO [04-27|14:18:02.704] 🔨 mined potential block                  number=157 hash=a13567…9de892
INFO [04-27|14:18:02.704] Commit new mining work                   number=158 sealhash=bd6c28…82a73b uncles=0 txs=0 gas=0     fees=0        elapsed=8.958ms
INFO [04-27|14:18:03.030] Looking for peers                        peercount=1 tried=106 static=0
INFO [04-27|14:18:03.080] Successfully sealed new block            number=158 sealhash=bd6c28…82a73b hash=020bef…59e332 elapsed=384.935ms
INFO [04-27|14:18:03.080] 🔗 block reached canonical chain          number=151 hash=b06304…b146c9
INFO [04-27|14:18:03.089] 🔨 mined potential block                  number=158 hash=020bef…59e332
INFO [04-27|14:18:03.089] Commit new mining work                   number=159 sealhash=f4491c…89a414 uncles=0 txs=0 gas=0     fees=0        elapsed=8.976ms
INFO [04-27|14:18:04.569] Successfully sealed new block            number=159 sealhash=f4491c…89a414 hash=9f7c92…7a1f22 elapsed=1.489s
INFO [04-27|14:18:04.569] 🔗 block reached canonical chain          number=152 hash=cfdb6d…762fe0
INFO [04-27|14:18:04.577] 🔨 mined potential block                  number=159 hash=9f7c92…7a1f22
INFO [04-27|14:18:04.577] Commit new mining work                   number=160 sealhash=3b7b27…96acbf uncles=0 txs=0 gas=0     fees=0        elapsed=7.946ms
INFO [04-27|14:18:07.031] Successfully sealed new block            number=160 sealhash=3b7b27…96acbf hash=3ecfe0…679d81 elapsed=2.462s
INFO [04-27|14:18:07.031] 🔗 block reached canonical chain          number=153 hash=7bdcc1…45dec6
INFO [04-27|14:18:07.039] Commit new mining work                   number=161 sealhash=fbb7bd…6a2e98 uncles=0 txs=0 gas=0     fees=0        elapsed=7.946ms
INFO [04-27|14:18:07.039] 🔨 mined potential block                  number=160 hash=3ecfe0…679d81
INFO [04-27|14:18:08.815] Successfully sealed new block            number=161 sealhash=fbb7bd…6a2e98 hash=c1264a…5f0267 elapsed=1.784s
INFO [04-27|14:18:08.816] 🔗 block reached canonical chain          number=154 hash=d2c6cf…37e8b4
INFO [04-27|14:18:08.824] Commit new mining work                   number=162 sealhash=4e7a75…08053e uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:18:08.824] 🔨 mined potential block                  number=161 hash=c1264a…5f0267
INFO [04-27|14:18:13.282] Looking for peers                        peercount=2 tried=192 static=0
INFO [04-27|14:18:14.287] Successfully sealed new block            number=162 sealhash=4e7a75…08053e hash=f0906a…31a5e2 elapsed=5.470s
INFO [04-27|14:18:14.287] 🔗 block reached canonical chain          number=155 hash=406d7d…076274
INFO [04-27|14:18:14.295] 🔨 mined potential block                  number=162 hash=f0906a…31a5e2
INFO [04-27|14:18:14.295] Commit new mining work                   number=163 sealhash=53eea3…741e82 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:18:23.320] Looking for peers                        peercount=1 tried=88  static=0
INFO [04-27|14:18:25.016] Successfully sealed new block            number=163 sealhash=53eea3…741e82 hash=a7c7fb…e8ad35 elapsed=10.729s
INFO [04-27|14:18:25.016] 🔗 block reached canonical chain          number=156 hash=bb921e…eb9f07
INFO [04-27|14:18:25.024] 🔨 mined potential block                  number=163 hash=a7c7fb…e8ad35
INFO [04-27|14:18:25.024] Commit new mining work                   number=164 sealhash=792960…dffe12 uncles=0 txs=0 gas=0     fees=0        elapsed=7.977ms
INFO [04-27|14:18:26.452] Successfully sealed new block            number=164 sealhash=792960…dffe12 hash=824dca…81deab elapsed=1.436s
INFO [04-27|14:18:26.452] 🔗 block reached canonical chain          number=157 hash=a13567…9de892
INFO [04-27|14:18:26.460] Commit new mining work                   number=165 sealhash=7b0d54…fac947 uncles=0 txs=0 gas=0     fees=0        elapsed=7.943ms
INFO [04-27|14:18:26.460] 🔨 mined potential block                  number=164 hash=824dca…81deab
INFO [04-27|14:18:28.451] Successfully sealed new block            number=165 sealhash=7b0d54…fac947 hash=fbc435…935c53 elapsed=1.998s
INFO [04-27|14:18:28.451] 🔗 block reached canonical chain          number=158 hash=020bef…59e332
INFO [04-27|14:18:28.459] 🔨 mined potential block                  number=165 hash=fbc435…935c53
INFO [04-27|14:18:28.459] Commit new mining work                   number=166 sealhash=985ef8…88aa9c uncles=0 txs=0 gas=0     fees=0        elapsed=7.946ms
INFO [04-27|14:18:32.719] Successfully sealed new block            number=166 sealhash=985ef8…88aa9c hash=0b5d12…01b13a elapsed=4.268s
INFO [04-27|14:18:32.719] 🔗 block reached canonical chain          number=159 hash=9f7c92…7a1f22
INFO [04-27|14:18:32.727] 🔨 mined potential block                  number=166 hash=0b5d12…01b13a
INFO [04-27|14:18:32.727] Commit new mining work                   number=167 sealhash=4f4f92…46ebe7 uncles=0 txs=0 gas=0     fees=0        elapsed=7.980ms
INFO [04-27|14:18:33.453] Looking for peers                        peercount=1 tried=53  static=0
INFO [04-27|14:18:34.593] Successfully sealed new block            number=167 sealhash=4f4f92…46ebe7 hash=6ca37b…8561ea elapsed=1.873s
INFO [04-27|14:18:34.593] 🔗 block reached canonical chain          number=160 hash=3ecfe0…679d81
INFO [04-27|14:18:34.601] 🔨 mined potential block                  number=167 hash=6ca37b…8561ea
INFO [04-27|14:18:34.601] Commit new mining work                   number=168 sealhash=e01bb5…5e7093 uncles=0 txs=0 gas=0     fees=0        elapsed=7.977ms
INFO [04-27|14:18:43.482] Looking for peers                        peercount=1 tried=43  static=0
INFO [04-27|14:18:53.504] Looking for peers                        peercount=2 tried=94  static=0
INFO [04-27|14:19:02.649] Successfully sealed new block            number=168 sealhash=e01bb5…5e7093 hash=1ebc4c…476db7 elapsed=28.055s
INFO [04-27|14:19:02.650] 🔗 block reached canonical chain          number=161 hash=c1264a…5f0267
INFO [04-27|14:19:02.659] Commit new mining work                   number=169 sealhash=7aa357…033277 uncles=0 txs=0 gas=0     fees=0        elapsed=9.967ms
INFO [04-27|14:19:02.659] 🔨 mined potential block                  number=168 hash=1ebc4c…476db7
INFO [04-27|14:19:03.529] Looking for peers                        peercount=2 tried=50  static=0
INFO [04-27|14:19:04.914] Successfully sealed new block            number=169 sealhash=7aa357…033277 hash=9ca6d5…3a64ec elapsed=2.263s
INFO [04-27|14:19:04.915] 🔗 block reached canonical chain          number=162 hash=f0906a…31a5e2
INFO [04-27|14:19:04.923] 🔨 mined potential block                  number=169 hash=9ca6d5…3a64ec
INFO [04-27|14:19:04.923] Commit new mining work                   number=170 sealhash=112a57…bf3b1a uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:19:13.651] Looking for peers                        peercount=1 tried=109 static=0
INFO [04-27|14:19:23.807] Looking for peers                        peercount=2 tried=122 static=0
INFO [04-27|14:19:25.711] Successfully sealed new block            number=170 sealhash=112a57…bf3b1a hash=1dea8d…d2dafc elapsed=20.795s
INFO [04-27|14:19:25.711] 🔗 block reached canonical chain          number=163 hash=a7c7fb…e8ad35
INFO [04-27|14:19:25.718] 🔨 mined potential block                  number=170 hash=1dea8d…d2dafc
INFO [04-27|14:19:25.718] Commit new mining work                   number=171 sealhash=4d0c51…ceea7b uncles=0 txs=0 gas=0     fees=0        elapsed=7.008ms
INFO [04-27|14:19:32.206] Successfully sealed new block            number=171 sealhash=4d0c51…ceea7b hash=ca6f14…750f0b elapsed=6.495s
INFO [04-27|14:19:32.206] 🔗 block reached canonical chain          number=164 hash=824dca…81deab
INFO [04-27|14:19:32.216] Commit new mining work                   number=172 sealhash=522aaa…9b8269 uncles=0 txs=0 gas=0     fees=0        elapsed=9.970ms
INFO [04-27|14:19:32.216] 🔨 mined potential block                  number=171 hash=ca6f14…750f0b
INFO [04-27|14:19:33.917] Looking for peers                        peercount=2 tried=76  static=0
INFO [04-27|14:19:43.927] Looking for peers                        peercount=1 tried=76  static=0
INFO [04-27|14:19:46.539] Successfully sealed new block            number=172 sealhash=522aaa…9b8269 hash=2a2f5e…6e2c37 elapsed=14.332s
INFO [04-27|14:19:46.539] 🔗 block reached canonical chain          number=165 hash=fbc435…935c53
INFO [04-27|14:19:46.549] Commit new mining work                   number=173 sealhash=c4bcd8…b6c959 uncles=0 txs=0 gas=0     fees=0        elapsed=9.941ms
INFO [04-27|14:19:46.549] 🔨 mined potential block                  number=172 hash=2a2f5e…6e2c37
INFO [04-27|14:19:50.186] Successfully sealed new block            number=173 sealhash=c4bcd8…b6c959 hash=f46e09…98fcb7 elapsed=3.647s
INFO [04-27|14:19:50.187] 🔗 block reached canonical chain          number=166 hash=0b5d12…01b13a
INFO [04-27|14:19:50.197] 🔨 mined potential block                  number=173 hash=f46e09…98fcb7
INFO [04-27|14:19:50.197] Commit new mining work                   number=174 sealhash=fec1ca…7981da uncles=0 txs=0 gas=0     fees=0        elapsed=10.937ms
INFO [04-27|14:19:51.612] Successfully sealed new block            number=174 sealhash=fec1ca…7981da hash=869577…f4865c elapsed=1.424s
INFO [04-27|14:19:51.612] 🔗 block reached canonical chain          number=167 hash=6ca37b…8561ea
INFO [04-27|14:19:51.621] 🔨 mined potential block                  number=174 hash=869577…f4865c
INFO [04-27|14:19:51.621] Commit new mining work                   number=175 sealhash=aefc43…b8421a uncles=0 txs=0 gas=0     fees=0        elapsed=8.977ms
INFO [04-27|14:19:51.870] Successfully sealed new block            number=175 sealhash=aefc43…b8421a hash=252509…ee33e6 elapsed=258.272ms
INFO [04-27|14:19:51.870] 🔗 block reached canonical chain          number=168 hash=1ebc4c…476db7
INFO [04-27|14:19:51.880] 🔨 mined potential block                  number=175 hash=252509…ee33e6
INFO [04-27|14:19:51.880] Commit new mining work                   number=176 sealhash=6276d3…63ad60 uncles=0 txs=0 gas=0     fees=0        elapsed=9.972ms
INFO [04-27|14:19:53.985] Looking for peers                        peercount=1 tried=78  static=0
INFO [04-27|14:19:56.402] Successfully sealed new block            number=176 sealhash=6276d3…63ad60 hash=e5e9e0…071d04 elapsed=4.531s
INFO [04-27|14:19:56.402] 🔗 block reached canonical chain          number=169 hash=9ca6d5…3a64ec
INFO [04-27|14:19:56.410] 🔨 mined potential block                  number=176 hash=e5e9e0…071d04
INFO [04-27|14:19:56.410] Commit new mining work                   number=177 sealhash=d52c58…1dfcf1 uncles=0 txs=0 gas=0     fees=0        elapsed=7.938ms
INFO [04-27|14:20:00.847] Successfully sealed new block            number=177 sealhash=d52c58…1dfcf1 hash=10e7f8…c4ebd9 elapsed=4.445s
INFO [04-27|14:20:00.847] 🔗 block reached canonical chain          number=170 hash=1dea8d…d2dafc
INFO [04-27|14:20:00.856] 🔨 mined potential block                  number=177 hash=10e7f8…c4ebd9
INFO [04-27|14:20:00.856] Commit new mining work                   number=178 sealhash=b6b637…df0b5f uncles=0 txs=0 gas=0     fees=0        elapsed=8.977ms
INFO [04-27|14:20:04.100] Looking for peers                        peercount=1 tried=64  static=0
INFO [04-27|14:20:14.288] Looking for peers                        peercount=2 tried=83  static=0
INFO [04-27|14:20:18.889] Successfully sealed new block            number=178 sealhash=b6b637…df0b5f hash=0b01d6…e52502 elapsed=18.041s
INFO [04-27|14:20:18.889] 🔗 block reached canonical chain          number=171 hash=ca6f14…750f0b
INFO [04-27|14:20:18.897] Commit new mining work                   number=179 sealhash=f8a8e1…1ef864 uncles=0 txs=0 gas=0     fees=0        elapsed=8.009ms
INFO [04-27|14:20:18.897] 🔨 mined potential block                  number=178 hash=0b01d6…e52502
INFO [04-27|14:20:20.350] Successfully sealed new block            number=179 sealhash=f8a8e1…1ef864 hash=4bad02…56b23e elapsed=1.461s
INFO [04-27|14:20:20.350] 🔗 block reached canonical chain          number=172 hash=2a2f5e…6e2c37
INFO [04-27|14:20:20.358] 🔨 mined potential block                  number=179 hash=4bad02…56b23e
INFO [04-27|14:20:20.358] Commit new mining work                   number=180 sealhash=87b441…0b45f3 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:20:23.318] Successfully sealed new block            number=180 sealhash=87b441…0b45f3 hash=6ceb40…9c2f2a elapsed=2.968s
INFO [04-27|14:20:23.318] 🔗 block reached canonical chain          number=173 hash=f46e09…98fcb7
INFO [04-27|14:20:23.326] 🔨 mined potential block                  number=180 hash=6ceb40…9c2f2a
INFO [04-27|14:20:23.326] Commit new mining work                   number=181 sealhash=bef51e…4fc48b uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:20:24.338] Looking for peers                        peercount=1 tried=78  static=0
INFO [04-27|14:20:34.338] Looking for peers                        peercount=1 tried=76  static=0
INFO [04-27|14:20:38.270] Successfully sealed new block            number=181 sealhash=bef51e…4fc48b hash=a46003…f26a26 elapsed=14.952s
INFO [04-27|14:20:38.270] 🔗 block reached canonical chain          number=174 hash=869577…f4865c
INFO [04-27|14:20:38.279] 🔨 mined potential block                  number=181 hash=a46003…f26a26
INFO [04-27|14:20:38.279] Commit new mining work                   number=182 sealhash=06a450…76354c uncles=0 txs=0 gas=0     fees=0        elapsed=8.968ms
INFO [04-27|14:20:44.340] Looking for peers                        peercount=1 tried=63  static=0
INFO [04-27|14:20:54.452] Looking for peers                        peercount=1 tried=80  static=0
INFO [04-27|14:21:03.668] Successfully sealed new block            number=182 sealhash=06a450…76354c hash=0c7aae…3ac19f elapsed=25.397s
INFO [04-27|14:21:03.668] 🔗 block reached canonical chain          number=175 hash=252509…ee33e6
INFO [04-27|14:21:03.676] 🔨 mined potential block                  number=182 hash=0c7aae…3ac19f
INFO [04-27|14:21:03.676] Commit new mining work                   number=183 sealhash=d2d741…7b1be4 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:21:04.027] Successfully sealed new block            number=183 sealhash=d2d741…7b1be4 hash=5a9ab0…661c6d elapsed=359.040ms
INFO [04-27|14:21:04.027] 🔗 block reached canonical chain          number=176 hash=e5e9e0…071d04
INFO [04-27|14:21:04.042] 🔨 mined potential block                  number=183 hash=5a9ab0…661c6d
INFO [04-27|14:21:04.042] Commit new mining work                   number=184 sealhash=1e6e1c…732adb uncles=0 txs=0 gas=0     fees=0        elapsed=14.960ms
INFO [04-27|14:21:04.672] Looking for peers                        peercount=1 tried=18  static=0
INFO [04-27|14:21:14.460] Successfully sealed new block            number=184 sealhash=1e6e1c…732adb hash=d08063…af4cf3 elapsed=10.433s
INFO [04-27|14:21:14.460] 🔗 block reached canonical chain          number=177 hash=10e7f8…c4ebd9
INFO [04-27|14:21:14.469] 🔨 mined potential block                  number=184 hash=d08063…af4cf3
INFO [04-27|14:21:14.469] Commit new mining work                   number=185 sealhash=5d9bed…dab47c uncles=0 txs=0 gas=0     fees=0        elapsed=8.942ms
INFO [04-27|14:21:15.262] Looking for peers                        peercount=1 tried=32  static=0
INFO [04-27|14:21:19.272] Successfully sealed new block            number=185 sealhash=5d9bed…dab47c hash=3ad891…546ac6 elapsed=4.812s
INFO [04-27|14:21:19.272] 🔗 block reached canonical chain          number=178 hash=0b01d6…e52502
INFO [04-27|14:21:19.280] 🔨 mined potential block                  number=185 hash=3ad891…546ac6
INFO [04-27|14:21:19.280] Commit new mining work                   number=186 sealhash=42acda…5bdfb1 uncles=0 txs=0 gas=0     fees=0        elapsed=7.943ms
INFO [04-27|14:21:21.897] Successfully sealed new block            number=186 sealhash=42acda…5bdfb1 hash=363078…7f399e elapsed=2.624s
INFO [04-27|14:21:21.897] 🔗 block reached canonical chain          number=179 hash=4bad02…56b23e
INFO [04-27|14:21:21.906] Commit new mining work                   number=187 sealhash=9bb0b0…ab0d87 uncles=0 txs=0 gas=0     fees=0        elapsed=8.975ms
INFO [04-27|14:21:21.906] 🔨 mined potential block                  number=186 hash=363078…7f399e
INFO [04-27|14:21:24.062] Successfully sealed new block            number=187 sealhash=9bb0b0…ab0d87 hash=4e4526…79f48e elapsed=2.165s
INFO [04-27|14:21:24.062] 🔗 block reached canonical chain          number=180 hash=6ceb40…9c2f2a
INFO [04-27|14:21:24.070] 🔨 mined potential block                  number=187 hash=4e4526…79f48e
INFO [04-27|14:21:24.070] Commit new mining work                   number=188 sealhash=b21342…f6e32b uncles=0 txs=0 gas=0     fees=0        elapsed=7.980ms
INFO [04-27|14:21:25.290] Looking for peers                        peercount=2 tried=103 static=0
INFO [04-27|14:21:26.626] Successfully sealed new block            number=188 sealhash=b21342…f6e32b hash=bb1296…64abf5 elapsed=2.563s
INFO [04-27|14:21:26.626] 🔗 block reached canonical chain          number=181 hash=a46003…f26a26
INFO [04-27|14:21:26.640] 🔨 mined potential block                  number=188 hash=bb1296…64abf5
INFO [04-27|14:21:26.640] Commit new mining work                   number=189 sealhash=b8382e…e56b81 uncles=0 txs=0 gas=0     fees=0        elapsed=13.929ms
INFO [04-27|14:21:31.156] Successfully sealed new block            number=189 sealhash=b8382e…e56b81 hash=9a5636…08ce06 elapsed=4.530s
INFO [04-27|14:21:31.156] 🔗 block reached canonical chain          number=182 hash=0c7aae…3ac19f
INFO [04-27|14:21:31.164] 🔨 mined potential block                  number=189 hash=9a5636…08ce06
INFO [04-27|14:21:31.164] Commit new mining work                   number=190 sealhash=172f55…357b42 uncles=0 txs=0 gas=0     fees=0        elapsed=7.969ms
INFO [04-27|14:21:34.882] Successfully sealed new block            number=190 sealhash=172f55…357b42 hash=1db077…e60fc2 elapsed=3.725s
INFO [04-27|14:21:34.882] 🔗 block reached canonical chain          number=183 hash=5a9ab0…661c6d
INFO [04-27|14:21:34.892] 🔨 mined potential block                  number=190 hash=1db077…e60fc2
INFO [04-27|14:21:34.892] Commit new mining work                   number=191 sealhash=ef313a…ae1882 uncles=0 txs=0 gas=0     fees=0        elapsed=9.974ms
INFO [04-27|14:21:35.529] Looking for peers                        peercount=1 tried=31  static=0
INFO [04-27|14:21:43.268] Successfully sealed new block            number=191 sealhash=ef313a…ae1882 hash=f036db…79ef4d elapsed=8.385s
INFO [04-27|14:21:43.268] 🔗 block reached canonical chain          number=184 hash=d08063…af4cf3
INFO [04-27|14:21:43.276] 🔨 mined potential block                  number=191 hash=f036db…79ef4d
INFO [04-27|14:21:43.276] Commit new mining work                   number=192 sealhash=da40c4…f478e2 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:21:45.540] Looking for peers                        peercount=1 tried=89  static=0
INFO [04-27|14:21:54.585] Successfully sealed new block            number=192 sealhash=da40c4…f478e2 hash=21d1ac…7436b9 elapsed=11.316s
INFO [04-27|14:21:54.585] 🔗 block reached canonical chain          number=185 hash=3ad891…546ac6
INFO [04-27|14:21:54.595] 🔨 mined potential block                  number=192 hash=21d1ac…7436b9
INFO [04-27|14:21:54.595] Commit new mining work                   number=193 sealhash=eeeb23…047f00 uncles=0 txs=0 gas=0     fees=0        elapsed=9.973ms
INFO [04-27|14:21:55.794] Looking for peers                        peercount=1 tried=55  static=0
INFO [04-27|14:21:59.226] Successfully sealed new block            number=193 sealhash=eeeb23…047f00 hash=a83dd3…fe9bf0 elapsed=4.641s
INFO [04-27|14:21:59.226] 🔗 block reached canonical chain          number=186 hash=363078…7f399e
INFO [04-27|14:21:59.236] Commit new mining work                   number=194 sealhash=8b7a93…c617b1 uncles=0 txs=0 gas=0     fees=0        elapsed=9.973ms
INFO [04-27|14:21:59.236] 🔨 mined potential block                  number=193 hash=a83dd3…fe9bf0
INFO [04-27|14:22:06.118] Looking for peers                        peercount=1 tried=30  static=0
INFO [04-27|14:22:11.199] Successfully sealed new block            number=194 sealhash=8b7a93…c617b1 hash=b8a310…33086e elapsed=11.972s
INFO [04-27|14:22:11.200] 🔗 block reached canonical chain          number=187 hash=4e4526…79f48e
INFO [04-27|14:22:11.211] 🔨 mined potential block                  number=194 hash=b8a310…33086e
INFO [04-27|14:22:11.211] Commit new mining work                   number=195 sealhash=3b373f…8e9677 uncles=0 txs=0 gas=0     fees=0        elapsed=11.970ms
INFO [04-27|14:22:16.127] Looking for peers                        peercount=1 tried=62  static=0
INFO [04-27|14:22:26.127] Looking for peers                        peercount=1 tried=35  static=0
INFO [04-27|14:22:27.218] Successfully sealed new block            number=195 sealhash=3b373f…8e9677 hash=699e47…0b87ca elapsed=16.017s
INFO [04-27|14:22:27.218] 🔗 block reached canonical chain          number=188 hash=bb1296…64abf5
INFO [04-27|14:22:27.226] 🔨 mined potential block                  number=195 hash=699e47…0b87ca
INFO [04-27|14:22:27.226] Commit new mining work                   number=196 sealhash=81e9f9…02b712 uncles=0 txs=0 gas=0     fees=0        elapsed=7.946ms
INFO [04-27|14:22:28.009] Successfully sealed new block            number=196 sealhash=81e9f9…02b712 hash=831d11…734eb0 elapsed=791.883ms
INFO [04-27|14:22:28.010] 🔗 block reached canonical chain          number=189 hash=9a5636…08ce06
INFO [04-27|14:22:28.018] 🔨 mined potential block                  number=196 hash=831d11…734eb0
INFO [04-27|14:22:28.018] Commit new mining work                   number=197 sealhash=de35fb…6d63b4 uncles=0 txs=0 gas=0     fees=0        elapsed=8.938ms
INFO [04-27|14:22:36.097] Successfully sealed new block            number=197 sealhash=de35fb…6d63b4 hash=5fc893…f6510a elapsed=8.087s
INFO [04-27|14:22:36.097] 🔗 block reached canonical chain          number=190 hash=1db077…e60fc2
INFO [04-27|14:22:36.105] 🔨 mined potential block                  number=197 hash=5fc893…f6510a
INFO [04-27|14:22:36.105] Commit new mining work                   number=198 sealhash=5cc738…6be9b2 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:22:36.128] Looking for peers                        peercount=1 tried=85  static=0
INFO [04-27|14:22:46.196] Looking for peers                        peercount=1 tried=63  static=0
INFO [04-27|14:22:50.075] Successfully sealed new block            number=198 sealhash=5cc738…6be9b2 hash=f49009…8154d7 elapsed=13.978s
INFO [04-27|14:22:50.075] 🔗 block reached canonical chain          number=191 hash=f036db…79ef4d
INFO [04-27|14:22:50.083] Commit new mining work                   number=199 sealhash=d22ce8…965e13 uncles=0 txs=0 gas=0     fees=0        elapsed=7.959ms
INFO [04-27|14:22:50.083] 🔨 mined potential block                  number=198 hash=f49009…8154d7
INFO [04-27|14:22:56.170] Successfully sealed new block            number=199 sealhash=d22ce8…965e13 hash=9d900e…3c9d2e elapsed=6.094s
INFO [04-27|14:22:56.170] 🔗 block reached canonical chain          number=192 hash=21d1ac…7436b9
INFO [04-27|14:22:56.178] 🔨 mined potential block                  number=199 hash=9d900e…3c9d2e
INFO [04-27|14:22:56.179] Commit new mining work                   number=200 sealhash=52b8e4…60f40b uncles=0 txs=0 gas=0     fees=0        elapsed=8.944ms
INFO [04-27|14:22:56.197] Looking for peers                        peercount=1 tried=50  static=0
INFO [04-27|14:23:03.021] Successfully sealed new block            number=200 sealhash=52b8e4…60f40b hash=44b657…e16dbc elapsed=6.850s
INFO [04-27|14:23:03.021] 🔗 block reached canonical chain          number=193 hash=a83dd3…fe9bf0
INFO [04-27|14:23:03.029] 🔨 mined potential block                  number=200 hash=44b657…e16dbc
INFO [04-27|14:23:03.029] Commit new mining work                   number=201 sealhash=b30081…d487e5 uncles=0 txs=0 gas=0     fees=0        elapsed=7.977ms
INFO [04-27|14:23:16.391] Looking for peers                        peercount=1 tried=92  static=0
INFO [04-27|14:23:17.408] Successfully sealed new block            number=201 sealhash=b30081…d487e5 hash=feef59…ea4ba3 elapsed=14.387s
INFO [04-27|14:23:17.409] 🔗 block reached canonical chain          number=194 hash=b8a310…33086e
INFO [04-27|14:23:17.416] 🔨 mined potential block                  number=201 hash=feef59…ea4ba3
INFO [04-27|14:23:17.416] Commit new mining work                   number=202 sealhash=006b27…b244b1 uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:23:26.407] Looking for peers                        peercount=1 tried=41  static=0
INFO [04-27|14:23:32.427] Successfully sealed new block            number=202 sealhash=006b27…b244b1 hash=ad9ade…ee1c97 elapsed=15.017s
INFO [04-27|14:23:32.427] 🔗 block reached canonical chain          number=195 hash=699e47…0b87ca
INFO [04-27|14:23:32.435] 🔨 mined potential block                  number=202 hash=ad9ade…ee1c97
INFO [04-27|14:23:32.435] Commit new mining work                   number=203 sealhash=716e5f…3cc2f7 uncles=0 txs=0 gas=0     fees=0        elapsed=7.965ms
INFO [04-27|14:23:37.156] Looking for peers                        peercount=1 tried=208 static=0
INFO [04-27|14:23:41.039] Successfully sealed new block            number=203 sealhash=716e5f…3cc2f7 hash=cee70f…2cc8a1 elapsed=8.611s
INFO [04-27|14:23:41.040] 🔗 block reached canonical chain          number=196 hash=831d11…734eb0
INFO [04-27|14:23:41.048] Commit new mining work                   number=204 sealhash=facaea…1f524f uncles=0 txs=0 gas=0     fees=0        elapsed=8.976ms
INFO [04-27|14:23:41.048] 🔨 mined potential block                  number=203 hash=cee70f…2cc8a1
INFO [04-27|14:23:41.491] Successfully sealed new block            number=204 sealhash=facaea…1f524f hash=f8f796…354822 elapsed=450.760ms
INFO [04-27|14:23:41.491] 🔗 block reached canonical chain          number=197 hash=5fc893…f6510a
INFO [04-27|14:23:41.500] 🔨 mined potential block                  number=204 hash=f8f796…354822
INFO [04-27|14:23:41.500] Commit new mining work                   number=205 sealhash=dad1c9…80bd4c uncles=0 txs=0 gas=0     fees=0        elapsed=8.988ms
INFO [04-27|14:23:46.593] Successfully sealed new block            number=205 sealhash=dad1c9…80bd4c hash=e20f4c…418da1 elapsed=5.102s
INFO [04-27|14:23:46.594] 🔗 block reached canonical chain          number=198 hash=f49009…8154d7
INFO [04-27|14:23:46.602] 🔨 mined potential block                  number=205 hash=e20f4c…418da1
INFO [04-27|14:23:46.602] Commit new mining work                   number=206 sealhash=91d05b…7a122d uncles=0 txs=0 gas=0     fees=0        elapsed=8.976ms
INFO [04-27|14:23:47.205] Looking for peers                        peercount=1 tried=120 static=0
INFO [04-27|14:23:49.540] Successfully sealed new block            number=206 sealhash=91d05b…7a122d hash=5dbe96…890b82 elapsed=2.946s
INFO [04-27|14:23:49.541] 🔗 block reached canonical chain          number=199 hash=9d900e…3c9d2e
INFO [04-27|14:23:49.549] Commit new mining work                   number=207 sealhash=c1b536…b33d39 uncles=0 txs=0 gas=0     fees=0        elapsed=8.013ms
INFO [04-27|14:23:49.549] 🔨 mined potential block                  number=206 hash=5dbe96…890b82
INFO [04-27|14:23:55.692] Successfully sealed new block            number=207 sealhash=c1b536…b33d39 hash=150665…fd8db4 elapsed=6.150s
INFO [04-27|14:23:55.692] 🔗 block reached canonical chain          number=200 hash=44b657…e16dbc
INFO [04-27|14:23:55.702] Commit new mining work                   number=208 sealhash=6d8810…8a2271 uncles=0 txs=0 gas=0     fees=0        elapsed=9.973ms
INFO [04-27|14:23:55.702] 🔨 mined potential block                  number=207 hash=150665…fd8db4
INFO [04-27|14:23:57.205] Looking for peers                        peercount=1 tried=84  static=0
INFO [04-27|14:23:58.755] Successfully sealed new block            number=208 sealhash=6d8810…8a2271 hash=76dde0…a0cc6f elapsed=3.062s
INFO [04-27|14:23:58.755] 🔗 block reached canonical chain          number=201 hash=feef59…ea4ba3
INFO [04-27|14:23:58.763] Commit new mining work                   number=209 sealhash=f48723…c86af4 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:23:58.763] 🔨 mined potential block                  number=208 hash=76dde0…a0cc6f
INFO [04-27|14:24:06.559] Successfully sealed new block            number=209 sealhash=f48723…c86af4 hash=6336c4…e1efb2 elapsed=7.804s
INFO [04-27|14:24:06.559] 🔗 block reached canonical chain          number=202 hash=ad9ade…ee1c97
INFO [04-27|14:24:06.567] Commit new mining work                   number=210 sealhash=e34d8c…fb46d5 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:24:06.567] 🔨 mined potential block                  number=209 hash=6336c4…e1efb2
INFO [04-27|14:24:07.208] Looking for peers                        peercount=1 tried=107 static=0
INFO [04-27|14:24:17.223] Looking for peers                        peercount=1 tried=158 static=0
INFO [04-27|14:24:18.211] Successfully sealed new block            number=210 sealhash=e34d8c…fb46d5 hash=2cdd54…706e71 elapsed=11.651s
INFO [04-27|14:24:18.212] 🔗 block reached canonical chain          number=203 hash=cee70f…2cc8a1
INFO [04-27|14:24:18.220] 🔨 mined potential block                  number=210 hash=2cdd54…706e71
INFO [04-27|14:24:18.220] Commit new mining work                   number=211 sealhash=dc805b…9b7a4e uncles=0 txs=0 gas=0     fees=0        elapsed=7.975ms
INFO [04-27|14:24:23.428] Successfully sealed new block            number=211 sealhash=dc805b…9b7a4e hash=eaa548…bd9846 elapsed=5.216s
INFO [04-27|14:24:23.428] 🔗 block reached canonical chain          number=204 hash=f8f796…354822
INFO [04-27|14:24:23.436] 🔨 mined potential block                  number=211 hash=eaa548…bd9846
INFO [04-27|14:24:23.436] Commit new mining work                   number=212 sealhash=813665…158465 uncles=0 txs=0 gas=0     fees=0        elapsed=7.940ms
INFO [04-27|14:24:27.224] Looking for peers                        peercount=2 tried=131 static=0
INFO [04-27|14:24:31.713] Successfully sealed new block            number=212 sealhash=813665…158465 hash=5edb3d…e70273 elapsed=8.284s
INFO [04-27|14:24:31.713] 🔗 block reached canonical chain          number=205 hash=e20f4c…418da1
INFO [04-27|14:24:31.719] 🔨 mined potential block                  number=212 hash=5edb3d…e70273
INFO [04-27|14:24:31.719] Commit new mining work                   number=213 sealhash=08f144…4f9641 uncles=0 txs=0 gas=0     fees=0        elapsed=5.984ms
INFO [04-27|14:24:37.249] Looking for peers                        peercount=1 tried=96  static=0
INFO [04-27|14:24:47.256] Looking for peers                        peercount=1 tried=91  static=0
INFO [04-27|14:24:57.269] Looking for peers                        peercount=1 tried=148 static=0
INFO [04-27|14:25:07.287] Looking for peers                        peercount=1 tried=132 static=0
INFO [04-27|14:25:17.365] Looking for peers                        peercount=1 tried=30  static=0
INFO [04-27|14:25:19.083] Successfully sealed new block            number=213 sealhash=08f144…4f9641 hash=b97760…74eef0 elapsed=47.370s
INFO [04-27|14:25:19.084] 🔗 block reached canonical chain          number=206 hash=5dbe96…890b82
INFO [04-27|14:25:19.092] 🔨 mined potential block                  number=213 hash=b97760…74eef0
INFO [04-27|14:25:19.092] Commit new mining work                   number=214 sealhash=8b72e1…c16cd0 uncles=0 txs=0 gas=0     fees=0        elapsed=7.931ms
INFO [04-27|14:25:19.583] Successfully sealed new block            number=214 sealhash=8b72e1…c16cd0 hash=d960a7…f97145 elapsed=498.618ms
INFO [04-27|14:25:19.583] 🔗 block reached canonical chain          number=207 hash=150665…fd8db4
INFO [04-27|14:25:19.591] 🔨 mined potential block                  number=214 hash=d960a7…f97145
INFO [04-27|14:25:19.591] Commit new mining work                   number=215 sealhash=53cafb…e41479 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:25:25.694] Successfully sealed new block            number=215 sealhash=53cafb…e41479 hash=ad6a0f…747dfd elapsed=6.110s
INFO [04-27|14:25:25.694] 🔗 block reached canonical chain          number=208 hash=76dde0…a0cc6f
INFO [04-27|14:25:25.702] 🔨 mined potential block                  number=215 hash=ad6a0f…747dfd
INFO [04-27|14:25:25.702] Commit new mining work                   number=216 sealhash=efd9a0…d9ff0b uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:25:26.238] Successfully sealed new block            number=216 sealhash=efd9a0…d9ff0b hash=242b82…04f4f1 elapsed=544.545ms
INFO [04-27|14:25:26.238] 🔗 block reached canonical chain          number=209 hash=6336c4…e1efb2
INFO [04-27|14:25:26.247] 🔨 mined potential block                  number=216 hash=242b82…04f4f1
INFO [04-27|14:25:26.247] Commit new mining work                   number=217 sealhash=c7f40d…10a66d uncles=0 txs=0 gas=0     fees=0        elapsed=8.975ms
INFO [04-27|14:25:27.553] Looking for peers                        peercount=1 tried=92  static=0
INFO [04-27|14:25:34.244] Successfully sealed new block            number=217 sealhash=c7f40d…10a66d hash=1dcdba…ebc826 elapsed=8.005s
INFO [04-27|14:25:34.245] 🔗 block reached canonical chain          number=210 hash=2cdd54…706e71
INFO [04-27|14:25:34.254] 🔨 mined potential block                  number=217 hash=1dcdba…ebc826
INFO [04-27|14:25:34.254] Commit new mining work                   number=218 sealhash=dbc4f3…87f662 uncles=0 txs=0 gas=0     fees=0        elapsed=8.974ms
INFO [04-27|14:25:37.590] Looking for peers                        peercount=1 tried=80  static=0
INFO [04-27|14:25:38.854] Successfully sealed new block            number=218 sealhash=dbc4f3…87f662 hash=e2976d…1c1821 elapsed=4.609s
INFO [04-27|14:25:38.854] 🔗 block reached canonical chain          number=211 hash=eaa548…bd9846
INFO [04-27|14:25:38.861] Commit new mining work                   number=219 sealhash=01c836…1e606d uncles=0 txs=0 gas=0     fees=0        elapsed=6.948ms
INFO [04-27|14:25:38.861] 🔨 mined potential block                  number=218 hash=e2976d…1c1821
INFO [04-27|14:25:39.573] Successfully sealed new block            number=219 sealhash=01c836…1e606d hash=b6f544…600275 elapsed=719.076ms
INFO [04-27|14:25:39.573] 🔗 block reached canonical chain          number=212 hash=5edb3d…e70273
INFO [04-27|14:25:39.580] Commit new mining work                   number=220 sealhash=60a6db…b38cd6 uncles=0 txs=0 gas=0     fees=0        elapsed=6.948ms
INFO [04-27|14:25:39.580] 🔨 mined potential block                  number=219 hash=b6f544…600275
INFO [04-27|14:25:47.775] Looking for peers                        peercount=2 tried=61  static=0
INFO [04-27|14:25:54.840] Successfully sealed new block            number=220 sealhash=60a6db…b38cd6 hash=3a7929…2b0acc elapsed=15.266s
INFO [04-27|14:25:54.841] 🔗 block reached canonical chain          number=213 hash=b97760…74eef0
INFO [04-27|14:25:54.849] Commit new mining work                   number=221 sealhash=caa2c0…115a58 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:25:54.849] 🔨 mined potential block                  number=220 hash=3a7929…2b0acc
INFO [04-27|14:25:57.008] Successfully sealed new block            number=221 sealhash=caa2c0…115a58 hash=0cf843…ab7bbe elapsed=2.167s
INFO [04-27|14:25:57.009] 🔗 block reached canonical chain          number=214 hash=d960a7…f97145
INFO [04-27|14:25:57.017] 🔨 mined potential block                  number=221 hash=0cf843…ab7bbe
INFO [04-27|14:25:57.017] Commit new mining work                   number=222 sealhash=3beb72…c26256 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:25:57.974] Looking for peers                        peercount=1 tried=83  static=0
INFO [04-27|14:26:04.082] Successfully sealed new block            number=222 sealhash=3beb72…c26256 hash=fd4db7…4a6f4d elapsed=7.073s
INFO [04-27|14:26:04.082] 🔗 block reached canonical chain          number=215 hash=ad6a0f…747dfd
INFO [04-27|14:26:04.091] 🔨 mined potential block                  number=222 hash=fd4db7…4a6f4d
INFO [04-27|14:26:04.091] Commit new mining work                   number=223 sealhash=97163d…5f692d uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:26:05.443] Successfully sealed new block            number=223 sealhash=97163d…5f692d hash=400043…427afb elapsed=1.361s
INFO [04-27|14:26:05.443] 🔗 block reached canonical chain          number=216 hash=242b82…04f4f1
INFO [04-27|14:26:05.450] Commit new mining work                   number=224 sealhash=82924b…9eca67 uncles=0 txs=0 gas=0     fees=0        elapsed=6.980ms
INFO [04-27|14:26:05.450] 🔨 mined potential block                  number=223 hash=400043…427afb
INFO [04-27|14:26:08.020] Looking for peers                        peercount=3 tried=58  static=0
INFO [04-27|14:26:09.589] Successfully sealed new block            number=224 sealhash=82924b…9eca67 hash=a565ca…eacf12 elapsed=4.145s
INFO [04-27|14:26:09.589] 🔗 block reached canonical chain          number=217 hash=1dcdba…ebc826
INFO [04-27|14:26:09.597] Commit new mining work                   number=225 sealhash=6586d7…07704f uncles=0 txs=0 gas=0     fees=0        elapsed=7.972ms
INFO [04-27|14:26:09.597] 🔨 mined potential block                  number=224 hash=a565ca…eacf12
INFO [04-27|14:26:12.462] Successfully sealed new block            number=225 sealhash=6586d7…07704f hash=3e9862…d8d32a elapsed=2.873s
INFO [04-27|14:26:12.462] 🔗 block reached canonical chain          number=218 hash=e2976d…1c1821
INFO [04-27|14:26:12.473] Commit new mining work                   number=226 sealhash=6c178c…a4a38b uncles=0 txs=0 gas=0     fees=0        elapsed=10.971ms
INFO [04-27|14:26:12.473] 🔨 mined potential block                  number=225 hash=3e9862…d8d32a
INFO [04-27|14:26:14.222] Successfully sealed new block            number=226 sealhash=6c178c…a4a38b hash=bda62d…38a017 elapsed=1.759s
INFO [04-27|14:26:14.222] 🔗 block reached canonical chain          number=219 hash=b6f544…600275
INFO [04-27|14:26:14.230] 🔨 mined potential block                  number=226 hash=bda62d…38a017
INFO [04-27|14:26:14.230] Commit new mining work                   number=227 sealhash=d56d10…c142d8 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:26:14.984] Successfully sealed new block            number=227 sealhash=d56d10…c142d8 hash=bf7118…3ca6b6 elapsed=761.996ms
INFO [04-27|14:26:14.984] 🔗 block reached canonical chain          number=220 hash=3a7929…2b0acc
INFO [04-27|14:26:14.993] 🔨 mined potential block                  number=227 hash=bf7118…3ca6b6
INFO [04-27|14:26:14.993] Commit new mining work                   number=228 sealhash=831327…518d87 uncles=0 txs=0 gas=0     fees=0        elapsed=8.941ms
INFO [04-27|14:26:15.230] Successfully sealed new block            number=228 sealhash=831327…518d87 hash=e0aed6…99dc54 elapsed=246.342ms
INFO [04-27|14:26:15.230] 🔗 block reached canonical chain          number=221 hash=0cf843…ab7bbe
INFO [04-27|14:26:15.237] 🔨 mined potential block                  number=228 hash=e0aed6…99dc54
INFO [04-27|14:26:15.237] Commit new mining work                   number=229 sealhash=e6872d…1d5230 uncles=0 txs=0 gas=0     fees=0        elapsed=6.947ms
INFO [04-27|14:26:18.197] Looking for peers                        peercount=1 tried=51  static=0
INFO [04-27|14:26:18.819] Successfully sealed new block            number=229 sealhash=e6872d…1d5230 hash=eb1c24…d427c9 elapsed=3.589s
INFO [04-27|14:26:18.819] 🔗 block reached canonical chain          number=222 hash=fd4db7…4a6f4d
INFO [04-27|14:26:18.829] 🔨 mined potential block                  number=229 hash=eb1c24…d427c9
INFO [04-27|14:26:18.829] Commit new mining work                   number=230 sealhash=8f668d…d82d46 uncles=0 txs=0 gas=0     fees=0        elapsed=9.971ms
INFO [04-27|14:26:19.603] Successfully sealed new block            number=230 sealhash=8f668d…d82d46 hash=ee50c9…2c4881 elapsed=783.936ms
INFO [04-27|14:26:19.603] 🔗 block reached canonical chain          number=223 hash=400043…427afb
INFO [04-27|14:26:19.615] 🔨 mined potential block                  number=230 hash=ee50c9…2c4881
INFO [04-27|14:26:19.615] Commit new mining work                   number=231 sealhash=fbaffa…5393b8 uncles=0 txs=0 gas=0     fees=0        elapsed=11.934ms
INFO [04-27|14:26:22.156] Successfully sealed new block            number=231 sealhash=fbaffa…5393b8 hash=d7d674…1dab67 elapsed=2.552s
INFO [04-27|14:26:22.156] 🔗 block reached canonical chain          number=224 hash=a565ca…eacf12
INFO [04-27|14:26:22.165] 🔨 mined potential block                  number=231 hash=d7d674…1dab67
INFO [04-27|14:26:22.165] Commit new mining work                   number=232 sealhash=b9c332…33473f uncles=0 txs=0 gas=0     fees=0        elapsed=8.947ms
INFO [04-27|14:26:28.226] Looking for peers                        peercount=1 tried=74  static=0
INFO [04-27|14:26:38.260] Looking for peers                        peercount=1 tried=61  static=0
INFO [04-27|14:26:40.326] Successfully sealed new block            number=232 sealhash=b9c332…33473f hash=707765…1d400b elapsed=18.170s
INFO [04-27|14:26:40.326] 🔗 block reached canonical chain          number=225 hash=3e9862…d8d32a
INFO [04-27|14:26:40.335] 🔨 mined potential block                  number=232 hash=707765…1d400b
INFO [04-27|14:26:40.335] Commit new mining work                   number=233 sealhash=59afb4…8a9683 uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:26:41.798] Successfully sealed new block            number=233 sealhash=59afb4…8a9683 hash=3c9a4c…72bf00 elapsed=1.472s
INFO [04-27|14:26:41.798] 🔗 block reached canonical chain          number=226 hash=bda62d…38a017
INFO [04-27|14:26:41.806] Commit new mining work                   number=234 sealhash=0372a3…3c1c06 uncles=0 txs=0 gas=0     fees=0        elapsed=8.012ms
INFO [04-27|14:26:41.806] 🔨 mined potential block                  number=233 hash=3c9a4c…72bf00
INFO [04-27|14:26:43.619] Successfully sealed new block            number=234 sealhash=0372a3…3c1c06 hash=3bdc07…e7dffa elapsed=1.821s
INFO [04-27|14:26:43.619] 🔗 block reached canonical chain          number=227 hash=bf7118…3ca6b6
INFO [04-27|14:26:43.627] 🔨 mined potential block                  number=234 hash=3bdc07…e7dffa
INFO [04-27|14:26:43.627] Commit new mining work                   number=235 sealhash=084611…4e7e64 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:26:45.580] Successfully sealed new block            number=235 sealhash=084611…4e7e64 hash=4f5e72…8ab61f elapsed=1.960s
INFO [04-27|14:26:45.580] 🔗 block reached canonical chain          number=228 hash=e0aed6…99dc54
INFO [04-27|14:26:45.589] Commit new mining work                   number=236 sealhash=43d70c…4510b1 uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:26:45.589] 🔨 mined potential block                  number=235 hash=4f5e72…8ab61f
INFO [04-27|14:26:48.274] Looking for peers                        peercount=1 tried=49  static=0
INFO [04-27|14:26:55.262] Successfully sealed new block            number=236 sealhash=43d70c…4510b1 hash=f4850d…7f907a elapsed=9.682s
INFO [04-27|14:26:55.263] 🔗 block reached canonical chain          number=229 hash=eb1c24…d427c9
INFO [04-27|14:26:55.270] 🔨 mined potential block                  number=236 hash=f4850d…7f907a
INFO [04-27|14:26:55.270] Commit new mining work                   number=237 sealhash=ec5c20…83f087 uncles=0 txs=0 gas=0     fees=0        elapsed=7.024ms
INFO [04-27|14:26:58.274] Looking for peers                        peercount=1 tried=54  static=0
INFO [04-27|14:27:04.805] Successfully sealed new block            number=237 sealhash=ec5c20…83f087 hash=4be71a…2046b7 elapsed=9.541s
INFO [04-27|14:27:04.805] 🔗 block reached canonical chain          number=230 hash=ee50c9…2c4881
INFO [04-27|14:27:04.811] 🔨 mined potential block                  number=237 hash=4be71a…2046b7
INFO [04-27|14:27:04.811] Commit new mining work                   number=238 sealhash=876993…480514 uncles=0 txs=0 gas=0     fees=0        elapsed=6.947ms
INFO [04-27|14:27:08.274] Looking for peers                        peercount=1 tried=43  static=0
INFO [04-27|14:27:10.874] Successfully sealed new block            number=238 sealhash=876993…480514 hash=689198…79dd1d elapsed=6.069s
INFO [04-27|14:27:10.874] 🔗 block reached canonical chain          number=231 hash=d7d674…1dab67
INFO [04-27|14:27:10.881] Commit new mining work                   number=239 sealhash=097a79…d1ef6c uncles=0 txs=0 gas=0     fees=0        elapsed=6.982ms
INFO [04-27|14:27:10.881] 🔨 mined potential block                  number=238 hash=689198…79dd1d
INFO [04-27|14:27:17.355] Successfully sealed new block            number=239 sealhash=097a79…d1ef6c hash=269029…0bd757 elapsed=6.480s
INFO [04-27|14:27:17.355] 🔗 block reached canonical chain          number=232 hash=707765…1d400b
INFO [04-27|14:27:17.363] 🔨 mined potential block                  number=239 hash=269029…0bd757
INFO [04-27|14:27:17.363] Commit new mining work                   number=240 sealhash=146711…fb935c uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:27:18.275] Looking for peers                        peercount=1 tried=67  static=0
INFO [04-27|14:27:20.811] Successfully sealed new block            number=240 sealhash=146711…fb935c hash=ba5338…9c2544 elapsed=3.455s
INFO [04-27|14:27:20.811] 🔗 block reached canonical chain          number=233 hash=3c9a4c…72bf00
INFO [04-27|14:27:20.818] 🔨 mined potential block                  number=240 hash=ba5338…9c2544
INFO [04-27|14:27:20.818] Commit new mining work                   number=241 sealhash=a49ef5…698007 uncles=0 txs=0 gas=0     fees=0        elapsed=6.948ms
INFO [04-27|14:27:28.275] Looking for peers                        peercount=1 tried=50  static=0
INFO [04-27|14:27:31.887] Successfully sealed new block            number=241 sealhash=a49ef5…698007 hash=444261…45eb49 elapsed=11.076s
INFO [04-27|14:27:31.887] 🔗 block reached canonical chain          number=234 hash=3bdc07…e7dffa
INFO [04-27|14:27:31.895] 🔨 mined potential block                  number=241 hash=444261…45eb49
INFO [04-27|14:27:31.895] Commit new mining work                   number=242 sealhash=89e03e…7c5257 uncles=0 txs=0 gas=0     fees=0        elapsed=7.973ms
INFO [04-27|14:27:32.018] Successfully sealed new block            number=242 sealhash=89e03e…7c5257 hash=7da092…8719f6 elapsed=130.653ms
INFO [04-27|14:27:32.018] 🔗 block reached canonical chain          number=235 hash=4f5e72…8ab61f
INFO [04-27|14:27:32.025] 🔨 mined potential block                  number=242 hash=7da092…8719f6
INFO [04-27|14:27:32.025] Commit new mining work                   number=243 sealhash=38ce20…71a1c5 uncles=0 txs=0 gas=0     fees=0        elapsed=6.977ms
INFO [04-27|14:27:37.502] Successfully sealed new block            number=243 sealhash=38ce20…71a1c5 hash=19a9f5…cff6f0 elapsed=5.484s
INFO [04-27|14:27:37.502] 🔗 block reached canonical chain          number=236 hash=f4850d…7f907a
INFO [04-27|14:27:37.509] 🔨 mined potential block                  number=243 hash=19a9f5…cff6f0
INFO [04-27|14:27:37.509] Commit new mining work                   number=244 sealhash=06e69e…085f07 uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:27:38.622] Looking for peers                        peercount=1 tried=95  static=0
INFO [04-27|14:27:41.350] Successfully sealed new block            number=244 sealhash=06e69e…085f07 hash=93564e…5212cb elapsed=3.847s
INFO [04-27|14:27:41.351] 🔗 block reached canonical chain          number=237 hash=4be71a…2046b7
INFO [04-27|14:27:41.360] 🔨 mined potential block                  number=244 hash=93564e…5212cb
INFO [04-27|14:27:41.360] Commit new mining work                   number=245 sealhash=382207…75d80e uncles=0 txs=0 gas=0     fees=0        elapsed=8.976ms
INFO [04-27|14:27:42.941] Successfully sealed new block            number=245 sealhash=382207…75d80e hash=738796…5a19da elapsed=1.589s
INFO [04-27|14:27:42.941] 🔗 block reached canonical chain          number=238 hash=689198…79dd1d
INFO [04-27|14:27:42.948] Commit new mining work                   number=246 sealhash=45b380…8ec672 uncles=0 txs=0 gas=0     fees=0        elapsed=6.947ms
INFO [04-27|14:27:42.948] 🔨 mined potential block                  number=245 hash=738796…5a19da
INFO [04-27|14:27:43.345] Successfully sealed new block            number=246 sealhash=45b380…8ec672 hash=304371…e61185 elapsed=403.920ms
INFO [04-27|14:27:43.346] 🔗 block reached canonical chain          number=239 hash=269029…0bd757
INFO [04-27|14:27:43.353] 🔨 mined potential block                  number=246 hash=304371…e61185
INFO [04-27|14:27:43.353] Commit new mining work                   number=247 sealhash=44e2e1…19a09d uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:27:48.802] Looking for peers                        peercount=1 tried=97  static=0
INFO [04-27|14:27:50.103] Successfully sealed new block            number=247 sealhash=44e2e1…19a09d hash=ad6c15…e3b1c3 elapsed=6.757s
INFO [04-27|14:27:50.103] 🔗 block reached canonical chain          number=240 hash=ba5338…9c2544
INFO [04-27|14:27:50.112] 🔨 mined potential block                  number=247 hash=ad6c15…e3b1c3
INFO [04-27|14:27:50.112] Commit new mining work                   number=248 sealhash=39326e…855a8d uncles=0 txs=0 gas=0     fees=0        elapsed=8.975ms
INFO [04-27|14:27:50.451] Successfully sealed new block            number=248 sealhash=39326e…855a8d hash=2db5df…7a26c3 elapsed=348.102ms
INFO [04-27|14:27:50.451] 🔗 block reached canonical chain          number=241 hash=444261…45eb49
INFO [04-27|14:27:50.460] 🔨 mined potential block                  number=248 hash=2db5df…7a26c3
INFO [04-27|14:27:50.460] Commit new mining work                   number=249 sealhash=63de61…013fe2 uncles=0 txs=0 gas=0     fees=0        elapsed=8.942ms
INFO [04-27|14:27:51.848] Successfully sealed new block            number=249 sealhash=63de61…013fe2 hash=e42f09…eb2199 elapsed=1.397s
INFO [04-27|14:27:51.848] 🔗 block reached canonical chain          number=242 hash=7da092…8719f6
INFO [04-27|14:27:51.855] 🔨 mined potential block                  number=249 hash=e42f09…eb2199
INFO [04-27|14:27:51.855] Commit new mining work                   number=250 sealhash=c1bc71…4ff83e uncles=0 txs=0 gas=0     fees=0        elapsed=6.949ms
INFO [04-27|14:27:58.855] Looking for peers                        peercount=2 tried=128 static=0
INFO [04-27|14:27:58.963] Successfully sealed new block            number=250 sealhash=c1bc71…4ff83e hash=305f1a…aea0a4 elapsed=7.115s
INFO [04-27|14:27:58.963] 🔗 block reached canonical chain          number=243 hash=19a9f5…cff6f0
INFO [04-27|14:27:58.971] Commit new mining work                   number=251 sealhash=199d2c…09b6cb uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:27:58.971] 🔨 mined potential block                  number=250 hash=305f1a…aea0a4
INFO [04-27|14:28:07.637] Successfully sealed new block            number=251 sealhash=199d2c…09b6cb hash=8de52e…a36301 elapsed=8.673s
INFO [04-27|14:28:07.637] 🔗 block reached canonical chain          number=244 hash=93564e…5212cb
INFO [04-27|14:28:07.644] 🔨 mined potential block                  number=251 hash=8de52e…a36301
INFO [04-27|14:28:07.644] Commit new mining work                   number=252 sealhash=f0a55f…f78575 uncles=0 txs=0 gas=0     fees=0        elapsed=6.983ms
INFO [04-27|14:28:08.933] Looking for peers                        peercount=1 tried=72  static=0
INFO [04-27|14:28:15.145] Successfully sealed new block            number=252 sealhash=f0a55f…f78575 hash=84e1b3…bd4098 elapsed=7.507s
INFO [04-27|14:28:15.145] 🔗 block reached canonical chain          number=245 hash=738796…5a19da
INFO [04-27|14:28:15.153] 🔨 mined potential block                  number=252 hash=84e1b3…bd4098
INFO [04-27|14:28:15.153] Commit new mining work                   number=253 sealhash=4b6e76…ee8511 uncles=0 txs=0 gas=0     fees=0        elapsed=7.946ms
INFO [04-27|14:28:19.185] Successfully sealed new block            number=253 sealhash=4b6e76…ee8511 hash=d962df…345d46 elapsed=4.040s
INFO [04-27|14:28:19.185] 🔗 block reached canonical chain          number=246 hash=304371…e61185
INFO [04-27|14:28:19.193] 🔨 mined potential block                  number=253 hash=d962df…345d46
INFO [04-27|14:28:19.193] Commit new mining work                   number=254 sealhash=2c358b…847e75 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:28:19.221] Looking for peers                        peercount=1 tried=73  static=0
INFO [04-27|14:28:20.663] Successfully sealed new block            number=254 sealhash=2c358b…847e75 hash=3da919…bf239d elapsed=1.478s
INFO [04-27|14:28:20.663] 🔗 block reached canonical chain          number=247 hash=ad6c15…e3b1c3
INFO [04-27|14:28:20.671] 🔨 mined potential block                  number=254 hash=3da919…bf239d
INFO [04-27|14:28:20.671] Commit new mining work                   number=255 sealhash=e5e224…2a9b81 uncles=0 txs=0 gas=0     fees=0        elapsed=7.977ms
INFO [04-27|14:28:25.519] Successfully sealed new block            number=255 sealhash=e5e224…2a9b81 hash=97242a…b812bd elapsed=4.856s
INFO [04-27|14:28:25.520] 🔗 block reached canonical chain          number=248 hash=2db5df…7a26c3
INFO [04-27|14:28:25.527] 🔨 mined potential block                  number=255 hash=97242a…b812bd
INFO [04-27|14:28:25.527] Commit new mining work                   number=256 sealhash=9ae3a4…b0ee27 uncles=0 txs=0 gas=0     fees=0        elapsed=7.977ms
INFO [04-27|14:28:29.243] Looking for peers                        peercount=1 tried=154 static=0
INFO [04-27|14:28:40.496] Successfully sealed new block            number=256 sealhash=9ae3a4…b0ee27 hash=ebd24b…188f7b elapsed=14.976s
INFO [04-27|14:28:40.496] 🔗 block reached canonical chain          number=249 hash=e42f09…eb2199
INFO [04-27|14:28:40.505] 🔨 mined potential block                  number=256 hash=ebd24b…188f7b
INFO [04-27|14:28:40.505] Commit new mining work                   number=257 sealhash=92b65b…653a20 uncles=0 txs=0 gas=0     fees=0        elapsed=8.942ms
INFO [04-27|14:28:41.988] Successfully sealed new block            number=257 sealhash=92b65b…653a20 hash=c0ba21…3ba028 elapsed=1.492s
INFO [04-27|14:28:41.989] 🔗 block reached canonical chain          number=250 hash=305f1a…aea0a4
INFO [04-27|14:28:41.996] 🔨 mined potential block                  number=257 hash=c0ba21…3ba028
INFO [04-27|14:28:41.996] Commit new mining work                   number=258 sealhash=9fd73b…650fae uncles=0 txs=0 gas=0     fees=0        elapsed=6.973ms
INFO [04-27|14:28:49.306] Looking for peers                        peercount=2 tried=148 static=0
INFO [04-27|14:28:51.351] Successfully sealed new block            number=258 sealhash=9fd73b…650fae hash=064c5b…7c0d2a elapsed=9.361s
INFO [04-27|14:28:51.351] 🔗 block reached canonical chain          number=251 hash=8de52e…a36301
INFO [04-27|14:28:51.359] 🔨 mined potential block                  number=258 hash=064c5b…7c0d2a
INFO [04-27|14:28:51.359] Commit new mining work                   number=259 sealhash=ce1451…f4a976 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:28:57.465] Successfully sealed new block            number=259 sealhash=ce1451…f4a976 hash=b654ee…ac31c7 elapsed=6.113s
INFO [04-27|14:28:57.465] 🔗 block reached canonical chain          number=252 hash=84e1b3…bd4098
INFO [04-27|14:28:57.472] Commit new mining work                   number=260 sealhash=b07611…2f3b39 uncles=0 txs=0 gas=0     fees=0        elapsed=6.956ms
INFO [04-27|14:28:57.472] 🔨 mined potential block                  number=259 hash=b654ee…ac31c7
INFO [04-27|14:28:58.957] Successfully sealed new block            number=260 sealhash=b07611…2f3b39 hash=e697a6…f58e1b elapsed=1.491s
INFO [04-27|14:28:58.958] 🔗 block reached canonical chain          number=253 hash=d962df…345d46
INFO [04-27|14:28:58.966] 🔨 mined potential block                  number=260 hash=e697a6…f58e1b
INFO [04-27|14:28:58.966] Commit new mining work                   number=261 sealhash=9aee23…bbf92d uncles=0 txs=0 gas=0     fees=0        elapsed=7.977ms
INFO [04-27|14:28:59.324] Looking for peers                        peercount=1 tried=68  static=0
INFO [04-27|14:28:59.706] Successfully sealed new block            number=261 sealhash=9aee23…bbf92d hash=1c33fb…539a5c elapsed=748.031ms
INFO [04-27|14:28:59.706] 🔗 block reached canonical chain          number=254 hash=3da919…bf239d
INFO [04-27|14:28:59.716] Commit new mining work                   number=262 sealhash=5adf60…fcc6ac uncles=0 txs=0 gas=0     fees=0        elapsed=9.941ms
INFO [04-27|14:28:59.716] 🔨 mined potential block                  number=261 hash=1c33fb…539a5c
INFO [04-27|14:29:03.240] Successfully sealed new block            number=262 sealhash=5adf60…fcc6ac hash=ce027f…dbf7c6 elapsed=3.533s
INFO [04-27|14:29:03.240] 🔗 block reached canonical chain          number=255 hash=97242a…b812bd
INFO [04-27|14:29:03.248] 🔨 mined potential block                  number=262 hash=ce027f…dbf7c6
INFO [04-27|14:29:03.248] Commit new mining work                   number=263 sealhash=fe08f0…22d72a uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:29:03.730] Successfully sealed new block            number=263 sealhash=fe08f0…22d72a hash=b5b866…34584f elapsed=490.685ms
INFO [04-27|14:29:03.730] 🔗 block reached canonical chain          number=256 hash=ebd24b…188f7b
INFO [04-27|14:29:03.737] 🔨 mined potential block                  number=263 hash=b5b866…34584f
INFO [04-27|14:29:03.737] Commit new mining work                   number=264 sealhash=a0b5aa…3b6892 uncles=0 txs=0 gas=0     fees=0        elapsed=6.950ms
INFO [04-27|14:29:07.997] Successfully sealed new block            number=264 sealhash=a0b5aa…3b6892 hash=430f4e…aabfcc elapsed=4.266s
INFO [04-27|14:29:07.997] 🔗 block reached canonical chain          number=257 hash=c0ba21…3ba028
INFO [04-27|14:29:08.005] 🔨 mined potential block                  number=264 hash=430f4e…aabfcc
INFO [04-27|14:29:08.005] Commit new mining work                   number=265 sealhash=8af302…266dee uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:29:10.657] Looking for peers                        peercount=1 tried=106 static=0
INFO [04-27|14:29:18.168] Successfully sealed new block            number=265 sealhash=8af302…266dee hash=7cc7da…6884f2 elapsed=10.170s
INFO [04-27|14:29:18.168] 🔗 block reached canonical chain          number=258 hash=064c5b…7c0d2a
INFO [04-27|14:29:18.176] 🔨 mined potential block                  number=265 hash=7cc7da…6884f2
INFO [04-27|14:29:18.176] Commit new mining work                   number=266 sealhash=ec0ef4…b2d8d0 uncles=0 txs=0 gas=0     fees=0        elapsed=7.940ms
INFO [04-27|14:29:20.970] Looking for peers                        peercount=1 tried=133 static=0
INFO [04-27|14:29:30.210] Successfully sealed new block            number=266 sealhash=ec0ef4…b2d8d0 hash=8d1164…b44a3f elapsed=12.042s
INFO [04-27|14:29:30.210] 🔗 block reached canonical chain          number=259 hash=b654ee…ac31c7
INFO [04-27|14:29:30.217] 🔨 mined potential block                  number=266 hash=8d1164…b44a3f
INFO [04-27|14:29:30.217] Commit new mining work                   number=267 sealhash=a96b36…94d7b1 uncles=0 txs=0 gas=0     fees=0        elapsed=6.975ms
INFO [04-27|14:29:31.015] Looking for peers                        peercount=2 tried=66  static=0
INFO [04-27|14:29:39.419] Successfully sealed new block            number=267 sealhash=a96b36…94d7b1 hash=779568…4429af elapsed=9.208s
INFO [04-27|14:29:39.419] 🔗 block reached canonical chain          number=260 hash=e697a6…f58e1b
INFO [04-27|14:29:39.428] 🔨 mined potential block                  number=267 hash=779568…4429af
INFO [04-27|14:29:39.428] Commit new mining work                   number=268 sealhash=02d511…3e7a3d uncles=0 txs=0 gas=0     fees=0        elapsed=8.942ms
INFO [04-27|14:29:41.043] Looking for peers                        peercount=2 tried=60  static=0
INFO [04-27|14:29:49.447] Successfully sealed new block            number=268 sealhash=02d511…3e7a3d hash=e4bfbf…1429a6 elapsed=10.028s
INFO [04-27|14:29:49.447] 🔗 block reached canonical chain          number=261 hash=1c33fb…539a5c
INFO [04-27|14:29:49.457] 🔨 mined potential block                  number=268 hash=e4bfbf…1429a6
INFO [04-27|14:29:49.457] Commit new mining work                   number=269 sealhash=119729…8c1767 uncles=0 txs=0 gas=0     fees=0        elapsed=9.941ms
INFO [04-27|14:29:51.077] Looking for peers                        peercount=2 tried=108 static=0
INFO [04-27|14:30:01.360] Looking for peers                        peercount=1 tried=35  static=0
INFO [04-27|14:30:01.580] Successfully sealed new block            number=269 sealhash=119729…8c1767 hash=a6ff78…4abaf1 elapsed=12.132s
INFO [04-27|14:30:01.580] 🔗 block reached canonical chain          number=262 hash=ce027f…dbf7c6
INFO [04-27|14:30:01.587] Commit new mining work                   number=270 sealhash=cf22bb…b29812 uncles=0 txs=0 gas=0     fees=0        elapsed=6.980ms
INFO [04-27|14:30:01.587] 🔨 mined potential block                  number=269 hash=a6ff78…4abaf1
INFO [04-27|14:30:02.394] Successfully sealed new block            number=270 sealhash=cf22bb…b29812 hash=1ea78b…b019b2 elapsed=814.819ms
INFO [04-27|14:30:02.394] 🔗 block reached canonical chain          number=263 hash=b5b866…34584f
INFO [04-27|14:30:02.401] 🔨 mined potential block                  number=270 hash=1ea78b…b019b2
INFO [04-27|14:30:02.401] Commit new mining work                   number=271 sealhash=be6ea7…7890ba uncles=0 txs=0 gas=0     fees=0        elapsed=6.982ms
INFO [04-27|14:30:11.490] Looking for peers                        peercount=2 tried=33  static=0
INFO [04-27|14:30:11.861] Successfully sealed new block            number=271 sealhash=be6ea7…7890ba hash=fbaebe…5d6c3f elapsed=9.466s
INFO [04-27|14:30:11.861] 🔗 block reached canonical chain          number=264 hash=430f4e…aabfcc
INFO [04-27|14:30:11.868] 🔨 mined potential block                  number=271 hash=fbaebe…5d6c3f
INFO [04-27|14:30:11.868] Commit new mining work                   number=272 sealhash=a3aff7…0c71f0 uncles=0 txs=0 gas=0     fees=0        elapsed=6.948ms
INFO [04-27|14:30:13.521] Successfully sealed new block            number=272 sealhash=a3aff7…0c71f0 hash=f195e0…b14d61 elapsed=1.659s
INFO [04-27|14:30:13.521] 🔗 block reached canonical chain          number=265 hash=7cc7da…6884f2
INFO [04-27|14:30:13.529] 🔨 mined potential block                  number=272 hash=f195e0…b14d61
INFO [04-27|14:30:13.529] Commit new mining work                   number=273 sealhash=24999d…dbf331 uncles=0 txs=0 gas=0     fees=0        elapsed=7.972ms
INFO [04-27|14:30:15.495] Successfully sealed new block            number=273 sealhash=24999d…dbf331 hash=ed4581…894cff elapsed=1.974s
INFO [04-27|14:30:15.495] 🔗 block reached canonical chain          number=266 hash=8d1164…b44a3f
INFO [04-27|14:30:15.502] 🔨 mined potential block                  number=273 hash=ed4581…894cff
INFO [04-27|14:30:15.502] Commit new mining work                   number=274 sealhash=d7512d…ec6eb3 uncles=0 txs=0 gas=0     fees=0        elapsed=6.980ms
INFO [04-27|14:30:20.115] Successfully sealed new block            number=274 sealhash=d7512d…ec6eb3 hash=76bb7c…f7ae0e elapsed=4.619s
INFO [04-27|14:30:20.116] 🔗 block reached canonical chain          number=267 hash=779568…4429af
INFO [04-27|14:30:20.123] Commit new mining work                   number=275 sealhash=630829…37b2ab uncles=0 txs=0 gas=0     fees=0        elapsed=7.946ms
INFO [04-27|14:30:20.123] 🔨 mined potential block                  number=274 hash=76bb7c…f7ae0e
INFO [04-27|14:30:21.490] Looking for peers                        peercount=1 tried=63  static=0
INFO [04-27|14:30:26.887] Successfully sealed new block            number=275 sealhash=630829…37b2ab hash=a30d80…ea395c elapsed=6.770s
INFO [04-27|14:30:26.887] 🔗 block reached canonical chain          number=268 hash=e4bfbf…1429a6
INFO [04-27|14:30:26.893] 🔨 mined potential block                  number=275 hash=a30d80…ea395c
INFO [04-27|14:30:26.893] Commit new mining work                   number=276 sealhash=d4ec1c…d0aa75 uncles=0 txs=0 gas=0     fees=0        elapsed=5.984ms
INFO [04-27|14:30:31.510] Looking for peers                        peercount=1 tried=82  static=0
INFO [04-27|14:30:32.136] Successfully sealed new block            number=276 sealhash=d4ec1c…d0aa75 hash=2b3ef8…a54b37 elapsed=5.248s
INFO [04-27|14:30:32.136] 🔗 block reached canonical chain          number=269 hash=a6ff78…4abaf1
INFO [04-27|14:30:32.144] 🔨 mined potential block                  number=276 hash=2b3ef8…a54b37
INFO [04-27|14:30:32.144] Commit new mining work                   number=277 sealhash=23a1e3…5dd2e1 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:30:34.822] Successfully sealed new block            number=277 sealhash=23a1e3…5dd2e1 hash=87f2f5…a541b9 elapsed=2.685s
INFO [04-27|14:30:34.822] 🔗 block reached canonical chain          number=270 hash=1ea78b…b019b2
INFO [04-27|14:30:34.829] Commit new mining work                   number=278 sealhash=ca2350…f5b842 uncles=0 txs=0 gas=0     fees=0        elapsed=6.946ms
INFO [04-27|14:30:34.829] 🔨 mined potential block                  number=277 hash=87f2f5…a541b9
INFO [04-27|14:30:41.701] Looking for peers                        peercount=2 tried=65  static=0
INFO [04-27|14:30:46.639] Successfully sealed new block            number=278 sealhash=ca2350…f5b842 hash=7c1d5b…9dfb51 elapsed=11.817s
INFO [04-27|14:30:46.639] 🔗 block reached canonical chain          number=271 hash=fbaebe…5d6c3f
INFO [04-27|14:30:46.647] 🔨 mined potential block                  number=278 hash=7c1d5b…9dfb51
INFO [04-27|14:30:46.647] Commit new mining work                   number=279 sealhash=20d164…5e5233 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:30:49.801] Successfully sealed new block            number=279 sealhash=20d164…5e5233 hash=92dcf5…892883 elapsed=3.161s
INFO [04-27|14:30:49.801] 🔗 block reached canonical chain          number=272 hash=f195e0…b14d61
INFO [04-27|14:30:49.808] 🔨 mined potential block                  number=279 hash=92dcf5…892883
INFO [04-27|14:30:49.808] Commit new mining work                   number=280 sealhash=77c723…239691 uncles=0 txs=0 gas=0     fees=0        elapsed=6.947ms
INFO [04-27|14:30:51.778] Looking for peers                        peercount=2 tried=70  static=0
INFO [04-27|14:30:56.716] Successfully sealed new block            number=280 sealhash=77c723…239691 hash=8dbc52…329cf2 elapsed=6.915s
INFO [04-27|14:30:56.717] 🔗 block reached canonical chain          number=273 hash=ed4581…894cff
INFO [04-27|14:30:56.724] 🔨 mined potential block                  number=280 hash=8dbc52…329cf2
INFO [04-27|14:30:56.724] Commit new mining work                   number=281 sealhash=8c0117…55ce5c uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:30:59.525] Successfully sealed new block            number=281 sealhash=8c0117…55ce5c hash=85a813…99f676 elapsed=2.807s
INFO [04-27|14:30:59.525] 🔗 block reached canonical chain          number=274 hash=76bb7c…f7ae0e
INFO [04-27|14:30:59.533] 🔨 mined potential block                  number=281 hash=85a813…99f676
INFO [04-27|14:30:59.533] Commit new mining work                   number=282 sealhash=0c6e47…fee7e0 uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:31:01.779] Looking for peers                        peercount=3 tried=52  static=0
INFO [04-27|14:31:05.984] Successfully sealed new block            number=282 sealhash=0c6e47…fee7e0 hash=89a560…5ed78d elapsed=6.459s
INFO [04-27|14:31:05.984] 🔗 block reached canonical chain          number=275 hash=a30d80…ea395c
INFO [04-27|14:31:05.991] Commit new mining work                   number=283 sealhash=295ca5…f4f3b7 uncles=0 txs=0 gas=0     fees=0        elapsed=6.975ms
INFO [04-27|14:31:05.991] 🔨 mined potential block                  number=282 hash=89a560…5ed78d
INFO [04-27|14:31:11.851] Looking for peers                        peercount=1 tried=50  static=0
INFO [04-27|14:31:18.614] Successfully sealed new block            number=283 sealhash=295ca5…f4f3b7 hash=9d2153…9a0462 elapsed=12.629s
INFO [04-27|14:31:18.614] 🔗 block reached canonical chain          number=276 hash=2b3ef8…a54b37
INFO [04-27|14:31:18.622] 🔨 mined potential block                  number=283 hash=9d2153…9a0462
INFO [04-27|14:31:18.622] Commit new mining work                   number=284 sealhash=d9d5dc…f2d0a7 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:31:21.960] Looking for peers                        peercount=1 tried=56  static=0
INFO [04-27|14:31:22.219] Successfully sealed new block            number=284 sealhash=d9d5dc…f2d0a7 hash=931713…38977a elapsed=3.605s
INFO [04-27|14:31:22.220] 🔗 block reached canonical chain          number=277 hash=87f2f5…a541b9
INFO [04-27|14:31:22.227] 🔨 mined potential block                  number=284 hash=931713…38977a
INFO [04-27|14:31:22.227] Commit new mining work                   number=285 sealhash=54326a…77ca36 uncles=0 txs=0 gas=0     fees=0        elapsed=7.947ms
INFO [04-27|14:31:28.799] Successfully sealed new block            number=285 sealhash=54326a…77ca36 hash=887bce…04974a elapsed=6.579s
INFO [04-27|14:31:28.800] 🔗 block reached canonical chain          number=278 hash=7c1d5b…9dfb51
INFO [04-27|14:31:28.806] Commit new mining work                   number=286 sealhash=1a6e03…abc825 uncles=0 txs=0 gas=0     fees=0        elapsed=6.980ms
INFO [04-27|14:31:28.806] 🔨 mined potential block                  number=285 hash=887bce…04974a
INFO [04-27|14:31:29.332] Successfully sealed new block            number=286 sealhash=1a6e03…abc825 hash=2f401d…8344f1 elapsed=531.616ms
INFO [04-27|14:31:29.332] 🔗 block reached canonical chain          number=279 hash=92dcf5…892883
INFO [04-27|14:31:29.339] Commit new mining work                   number=287 sealhash=ed5c10…101f6f uncles=0 txs=0 gas=0     fees=0        elapsed=6.968ms
INFO [04-27|14:31:29.339] 🔨 mined potential block                  number=286 hash=2f401d…8344f1
INFO [04-27|14:31:31.961] Looking for peers                        peercount=2 tried=36  static=0
INFO [04-27|14:31:37.091] Successfully sealed new block            number=287 sealhash=ed5c10…101f6f hash=3966aa…225ff7 elapsed=7.759s
INFO [04-27|14:31:37.091] 🔗 block reached canonical chain          number=280 hash=8dbc52…329cf2
INFO [04-27|14:31:37.099] 🔨 mined potential block                  number=287 hash=3966aa…225ff7
INFO [04-27|14:31:37.099] Commit new mining work                   number=288 sealhash=7f6841…32303b uncles=0 txs=0 gas=0     fees=0        elapsed=7.971ms
INFO [04-27|14:31:42.293] Looking for peers                        peercount=2 tried=82  static=0
INFO [04-27|14:31:43.293] Successfully sealed new block            number=288 sealhash=7f6841…32303b hash=37b2fe…49160f elapsed=6.201s
INFO [04-27|14:31:43.294] 🔗 block reached canonical chain          number=281 hash=85a813…99f676
INFO [04-27|14:31:43.301] 🔨 mined potential block                  number=288 hash=37b2fe…49160f
INFO [04-27|14:31:43.301] Commit new mining work                   number=289 sealhash=5dbf48…7bcfc8 uncles=0 txs=0 gas=0     fees=0        elapsed=6.956ms
INFO [04-27|14:31:51.714] Successfully sealed new block            number=289 sealhash=5dbf48…7bcfc8 hash=eb19eb…b5c8d2 elapsed=8.420s
INFO [04-27|14:31:51.714] 🔗 block reached canonical chain          number=282 hash=89a560…5ed78d
INFO [04-27|14:31:51.722] 🔨 mined potential block                  number=289 hash=eb19eb…b5c8d2
INFO [04-27|14:31:51.722] Commit new mining work                   number=290 sealhash=04cd74…edc1a6 uncles=0 txs=0 gas=0     fees=0        elapsed=7.961ms
INFO [04-27|14:31:52.294] Looking for peers                        peercount=1 tried=45  static=0
INFO [04-27|14:31:57.288] Successfully sealed new block            number=290 sealhash=04cd74…edc1a6 hash=1ac3fe…ca0cf3 elapsed=5.574s
INFO [04-27|14:31:57.288] 🔗 block reached canonical chain          number=283 hash=9d2153…9a0462
INFO [04-27|14:31:57.296] 🔨 mined potential block                  number=290 hash=1ac3fe…ca0cf3
INFO [04-27|14:31:57.296] Commit new mining work                   number=291 sealhash=87d738…1655d3 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:32:01.808] Successfully sealed new block            number=291 sealhash=87d738…1655d3 hash=5bfa99…8ef6cc elapsed=4.519s
INFO [04-27|14:32:01.808] 🔗 block reached canonical chain          number=284 hash=931713…38977a
INFO [04-27|14:32:01.815] 🔨 mined potential block                  number=291 hash=5bfa99…8ef6cc
INFO [04-27|14:32:01.815] Commit new mining work                   number=292 sealhash=ce9bef…67d935 uncles=0 txs=0 gas=0     fees=0        elapsed=6.947ms
INFO [04-27|14:32:02.357] Looking for peers                        peercount=1 tried=59  static=0
INFO [04-27|14:32:05.533] Successfully sealed new block            number=292 sealhash=ce9bef…67d935 hash=73cf2f…8b3628 elapsed=3.725s
INFO [04-27|14:32:05.534] 🔗 block reached canonical chain          number=285 hash=887bce…04974a
INFO [04-27|14:32:05.542] 🔨 mined potential block                  number=292 hash=73cf2f…8b3628
INFO [04-27|14:32:05.542] Commit new mining work                   number=293 sealhash=b78221…0d8058 uncles=0 txs=0 gas=0     fees=0        elapsed=8.966ms
INFO [04-27|14:32:08.265] Successfully sealed new block            number=293 sealhash=b78221…0d8058 hash=a58e55…8bf409 elapsed=2.730s
INFO [04-27|14:32:08.265] 🔗 block reached canonical chain          number=286 hash=2f401d…8344f1
INFO [04-27|14:32:08.273] Commit new mining work                   number=294 sealhash=ff16ef…da9a07 uncles=0 txs=0 gas=0     fees=0        elapsed=7.948ms
INFO [04-27|14:32:08.273] 🔨 mined potential block                  number=293 hash=a58e55…8bf409
INFO [04-27|14:32:12.443] Looking for peers                        peercount=1 tried=56  static=0
INFO [04-27|14:32:13.963] Successfully sealed new block            number=294 sealhash=ff16ef…da9a07 hash=764b25…af8129 elapsed=5.697s
INFO [04-27|14:32:13.964] 🔗 block reached canonical chain          number=287 hash=3966aa…225ff7
INFO [04-27|14:32:13.971] 🔨 mined potential block                  number=294 hash=764b25…af8129
INFO [04-27|14:32:13.971] Commit new mining work                   number=295 sealhash=58c3af…3e4ca3 uncles=0 txs=0 gas=0     fees=0        elapsed=6.975ms
INFO [04-27|14:32:18.017] Successfully sealed new block            number=295 sealhash=58c3af…3e4ca3 hash=a0787a…4235b4 elapsed=4.053s
INFO [04-27|14:32:18.017] 🔗 block reached canonical chain          number=288 hash=37b2fe…49160f
INFO [04-27|14:32:18.025] 🔨 mined potential block                  number=295 hash=a0787a…4235b4
INFO [04-27|14:32:18.025] Commit new mining work                   number=296 sealhash=edb836…6107b1 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:32:20.149] Successfully sealed new block            number=296 sealhash=edb836…6107b1 hash=55d591…0e62f3 elapsed=2.132s
INFO [04-27|14:32:20.150] 🔗 block reached canonical chain          number=289 hash=eb19eb…b5c8d2
INFO [04-27|14:32:20.157] 🔨 mined potential block                  number=296 hash=55d591…0e62f3
INFO [04-27|14:32:20.157] Commit new mining work                   number=297 sealhash=731772…881aee uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:32:22.469] Looking for peers                        peercount=1 tried=39  static=0
INFO [04-27|14:32:25.234] Successfully sealed new block            number=297 sealhash=731772…881aee hash=f669bf…bb9bd3 elapsed=5.083s
INFO [04-27|14:32:25.234] 🔗 block reached canonical chain          number=290 hash=1ac3fe…ca0cf3
INFO [04-27|14:32:25.243] 🔨 mined potential block                  number=297 hash=f669bf…bb9bd3
INFO [04-27|14:32:25.243] Commit new mining work                   number=298 sealhash=fba699…ec5732 uncles=0 txs=0 gas=0     fees=0        elapsed=8.941ms
INFO [04-27|14:32:25.892] Successfully sealed new block            number=298 sealhash=fba699…ec5732 hash=83d624…a752ef elapsed=658.204ms
INFO [04-27|14:32:25.892] 🔗 block reached canonical chain          number=291 hash=5bfa99…8ef6cc
INFO [04-27|14:32:25.900] 🔨 mined potential block                  number=298 hash=83d624…a752ef
INFO [04-27|14:32:25.900] Commit new mining work                   number=299 sealhash=d56137…791b60 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:32:29.922] Successfully sealed new block            number=299 sealhash=d56137…791b60 hash=5ee72f…e9164c elapsed=4.030s
INFO [04-27|14:32:29.923] 🔗 block reached canonical chain          number=292 hash=73cf2f…8b3628
INFO [04-27|14:32:29.930] 🔨 mined potential block                  number=299 hash=5ee72f…e9164c
INFO [04-27|14:32:29.930] Commit new mining work                   number=300 sealhash=b82457…2e4f57 uncles=0 txs=0 gas=0     fees=0        elapsed=7.946ms
INFO [04-27|14:32:32.329] Successfully sealed new block            number=300 sealhash=b82457…2e4f57 hash=2bffd6…9c9539 elapsed=2.405s
INFO [04-27|14:32:32.330] 🔗 block reached canonical chain          number=293 hash=a58e55…8bf409
INFO [04-27|14:32:32.338] 🔨 mined potential block                  number=300 hash=2bffd6…9c9539
INFO [04-27|14:32:32.338] Commit new mining work                   number=301 sealhash=adc31b…cbb7cf uncles=0 txs=0 gas=0     fees=0        elapsed=8.971ms
INFO [04-27|14:32:32.487] Successfully sealed new block            number=301 sealhash=adc31b…cbb7cf hash=1f52f1…25a3ca elapsed=157.600ms
INFO [04-27|14:32:32.488] 🔗 block reached canonical chain          number=294 hash=764b25…af8129
INFO [04-27|14:32:32.495] 🔨 mined potential block                  number=301 hash=1f52f1…25a3ca
INFO [04-27|14:32:32.495] Commit new mining work                   number=302 sealhash=c12773…41e84e uncles=0 txs=0 gas=0     fees=0        elapsed=7.977ms
INFO [04-27|14:32:32.545] Looking for peers                        peercount=1 tried=179 static=0
INFO [04-27|14:32:42.534] Successfully sealed new block            number=302 sealhash=c12773…41e84e hash=ae6a0a…0b8129 elapsed=10.046s
INFO [04-27|14:32:42.534] 🔗 block reached canonical chain          number=295 hash=a0787a…4235b4
INFO [04-27|14:32:42.542] 🔨 mined potential block                  number=302 hash=ae6a0a…0b8129
INFO [04-27|14:32:42.542] Commit new mining work                   number=303 sealhash=0ceef5…eb92c3 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:32:42.689] Looking for peers                        peercount=1 tried=132 static=0
INFO [04-27|14:32:43.803] Successfully sealed new block            number=303 sealhash=0ceef5…eb92c3 hash=c9c3ff…d675f8 elapsed=1.268s
INFO [04-27|14:32:43.804] 🔗 block reached canonical chain          number=296 hash=55d591…0e62f3
INFO [04-27|14:32:43.813] 🔨 mined potential block                  number=303 hash=c9c3ff…d675f8
INFO [04-27|14:32:43.813] Commit new mining work                   number=304 sealhash=2f325a…a645e6 uncles=0 txs=0 gas=0     fees=0        elapsed=9.953ms
INFO [04-27|14:32:53.202] Looking for peers                        peercount=1 tried=115 static=0
INFO [04-27|14:32:54.028] Successfully sealed new block            number=304 sealhash=2f325a…a645e6 hash=bc3612…62acb6 elapsed=10.223s
INFO [04-27|14:32:54.028] 🔗 block reached canonical chain          number=297 hash=f669bf…bb9bd3
INFO [04-27|14:32:54.036] 🔨 mined potential block                  number=304 hash=bc3612…62acb6
INFO [04-27|14:32:54.036] Commit new mining work                   number=305 sealhash=ed864d…d6ce94 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:32:58.105] Successfully sealed new block            number=305 sealhash=ed864d…d6ce94 hash=b0c029…b3ff10 elapsed=4.077s
INFO [04-27|14:32:58.105] 🔗 block reached canonical chain          number=298 hash=83d624…a752ef
INFO [04-27|14:32:58.113] 🔨 mined potential block                  number=305 hash=b0c029…b3ff10
INFO [04-27|14:32:58.113] Commit new mining work                   number=306 sealhash=5ac0d8…1026df uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:33:03.380] Looking for peers                        peercount=2 tried=141 static=0
INFO [04-27|14:33:08.557] Successfully sealed new block            number=306 sealhash=5ac0d8…1026df hash=ce44c1…105de7 elapsed=10.452s
INFO [04-27|14:33:08.557] 🔗 block reached canonical chain          number=299 hash=5ee72f…e9164c
INFO [04-27|14:33:08.565] 🔨 mined potential block                  number=306 hash=ce44c1…105de7
INFO [04-27|14:33:08.565] Commit new mining work                   number=307 sealhash=50222d…98a53b uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:33:13.420] Looking for peers                        peercount=2 tried=155 static=0
INFO [04-27|14:33:23.474] Looking for peers                        peercount=1 tried=80  static=0
INFO [04-27|14:33:33.625] Looking for peers                        peercount=2 tried=95  static=0
INFO [04-27|14:33:41.626] Successfully sealed new block            number=307 sealhash=50222d…98a53b hash=73581f…c09239 elapsed=33.068s
INFO [04-27|14:33:41.626] 🔗 block reached canonical chain          number=300 hash=2bffd6…9c9539
INFO [04-27|14:33:41.634] 🔨 mined potential block                  number=307 hash=73581f…c09239
INFO [04-27|14:33:41.634] Commit new mining work                   number=308 sealhash=a2f484…d1bc1d uncles=0 txs=0 gas=0     fees=0        elapsed=7.946ms
INFO [04-27|14:33:43.807] Looking for peers                        peercount=1 tried=133 static=0
INFO [04-27|14:33:45.000] Successfully sealed new block            number=308 sealhash=a2f484…d1bc1d hash=17fdec…6bd477 elapsed=3.373s
INFO [04-27|14:33:45.000] 🔗 block reached canonical chain          number=301 hash=1f52f1…25a3ca
INFO [04-27|14:33:45.008] 🔨 mined potential block                  number=308 hash=17fdec…6bd477
INFO [04-27|14:33:45.008] Commit new mining work                   number=309 sealhash=94c513…b787cd uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:33:48.919] Successfully sealed new block            number=309 sealhash=94c513…b787cd hash=0483e6…b631a8 elapsed=3.919s
INFO [04-27|14:33:48.919] 🔗 block reached canonical chain          number=302 hash=ae6a0a…0b8129
INFO [04-27|14:33:48.926] 🔨 mined potential block                  number=309 hash=0483e6…b631a8
INFO [04-27|14:33:48.926] Commit new mining work                   number=310 sealhash=8c809a…ede03f uncles=0 txs=0 gas=0     fees=0        elapsed=6.980ms
INFO [04-27|14:33:54.257] Looking for peers                        peercount=1 tried=156 static=0
INFO [04-27|14:34:03.129] Successfully sealed new block            number=310 sealhash=8c809a…ede03f hash=67035d…42efdf elapsed=14.210s
INFO [04-27|14:34:03.129] 🔗 block reached canonical chain          number=303 hash=c9c3ff…d675f8
INFO [04-27|14:34:03.136] Commit new mining work                   number=311 sealhash=f1bef6…c97470 uncles=0 txs=0 gas=0     fees=0        elapsed=6.980ms
INFO [04-27|14:34:03.136] 🔨 mined potential block                  number=310 hash=67035d…42efdf
INFO [04-27|14:34:04.268] Looking for peers                        peercount=1 tried=87  static=0
INFO [04-27|14:34:07.779] Successfully sealed new block            number=311 sealhash=f1bef6…c97470 hash=f61479…545ebd elapsed=4.649s
INFO [04-27|14:34:07.779] 🔗 block reached canonical chain          number=304 hash=bc3612…62acb6
INFO [04-27|14:34:07.788] 🔨 mined potential block                  number=311 hash=f61479…545ebd
INFO [04-27|14:34:07.788] Commit new mining work                   number=312 sealhash=30bbb3…1be151 uncles=0 txs=0 gas=0     fees=0        elapsed=8.960ms
INFO [04-27|14:34:11.719] Successfully sealed new block            number=312 sealhash=30bbb3…1be151 hash=e29a84…08c07b elapsed=3.940s
INFO [04-27|14:34:11.719] 🔗 block reached canonical chain          number=305 hash=b0c029…b3ff10
INFO [04-27|14:34:11.728] Commit new mining work                   number=313 sealhash=98b091…0f8ec4 uncles=0 txs=0 gas=0     fees=0        elapsed=8.942ms
INFO [04-27|14:34:11.728] 🔨 mined potential block                  number=312 hash=e29a84…08c07b
INFO [04-27|14:34:14.343] Looking for peers                        peercount=2 tried=113 static=0
INFO [04-27|14:34:18.033] Successfully sealed new block            number=313 sealhash=98b091…0f8ec4 hash=949d8a…7bb218 elapsed=6.313s
INFO [04-27|14:34:18.033] 🔗 block reached canonical chain          number=306 hash=ce44c1…105de7
INFO [04-27|14:34:18.040] 🔨 mined potential block                  number=313 hash=949d8a…7bb218
INFO [04-27|14:34:18.040] Commit new mining work                   number=314 sealhash=2122d4…e35c18 uncles=0 txs=0 gas=0     fees=0        elapsed=6.948ms
INFO [04-27|14:34:19.541] Successfully sealed new block            number=314 sealhash=2122d4…e35c18 hash=1a9150…fb590c elapsed=1.507s
INFO [04-27|14:34:19.541] 🔗 block reached canonical chain          number=307 hash=73581f…c09239
INFO [04-27|14:34:19.547] 🔨 mined potential block                  number=314 hash=1a9150…fb590c
INFO [04-27|14:34:19.547] Commit new mining work                   number=315 sealhash=529b7a…34a72d uncles=0 txs=0 gas=0     fees=0        elapsed=5.984ms
INFO [04-27|14:34:24.067] Successfully sealed new block            number=315 sealhash=529b7a…34a72d hash=7b072f…4b9532 elapsed=4.526s
INFO [04-27|14:34:24.067] 🔗 block reached canonical chain          number=308 hash=17fdec…6bd477
INFO [04-27|14:34:24.073] 🔨 mined potential block                  number=315 hash=7b072f…4b9532
INFO [04-27|14:34:24.073] Commit new mining work                   number=316 sealhash=0a6a41…8f010b uncles=0 txs=0 gas=0     fees=0        elapsed=5.984ms
INFO [04-27|14:34:24.358] Looking for peers                        peercount=2 tried=50  static=0
INFO [04-27|14:34:30.926] Successfully sealed new block            number=316 sealhash=0a6a41…8f010b hash=276c65…d04029 elapsed=6.858s
INFO [04-27|14:34:30.926] 🔗 block reached canonical chain          number=309 hash=0483e6…b631a8
INFO [04-27|14:34:30.932] 🔨 mined potential block                  number=316 hash=276c65…d04029
INFO [04-27|14:34:30.932] Commit new mining work                   number=317 sealhash=2d31c7…8df1cb uncles=0 txs=0 gas=0     fees=0        elapsed=5.984ms
INFO [04-27|14:34:31.494] Successfully sealed new block            number=317 sealhash=2d31c7…8df1cb hash=1c81b1…57cfce elapsed=567.481ms
INFO [04-27|14:34:31.494] 🔗 block reached canonical chain          number=310 hash=67035d…42efdf
INFO [04-27|14:34:31.502] Commit new mining work                   number=318 sealhash=44f9a4…662dda uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:34:31.502] 🔨 mined potential block                  number=317 hash=1c81b1…57cfce
INFO [04-27|14:34:34.454] Looking for peers                        peercount=1 tried=97  static=0
INFO [04-27|14:34:36.545] Successfully sealed new block            number=318 sealhash=44f9a4…662dda hash=9699f8…28c329 elapsed=5.051s
INFO [04-27|14:34:36.545] 🔗 block reached canonical chain          number=311 hash=f61479…545ebd
INFO [04-27|14:34:36.553] 🔨 mined potential block                  number=318 hash=9699f8…28c329
INFO [04-27|14:34:36.553] Commit new mining work                   number=319 sealhash=d79d3a…6e1d89 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:34:40.252] Successfully sealed new block            number=319 sealhash=d79d3a…6e1d89 hash=befbb3…3b4e17 elapsed=3.707s
INFO [04-27|14:34:40.252] 🔗 block reached canonical chain          number=312 hash=e29a84…08c07b
INFO [04-27|14:34:40.260] 🔨 mined potential block                  number=319 hash=befbb3…3b4e17
INFO [04-27|14:34:40.260] Commit new mining work                   number=320 sealhash=a4b3a5…9fd823 uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:34:41.795] Successfully sealed new block            number=320 sealhash=a4b3a5…9fd823 hash=82bff8…e609e2 elapsed=1.542s
INFO [04-27|14:34:41.795] 🔗 block reached canonical chain          number=313 hash=949d8a…7bb218
INFO [04-27|14:34:41.803] 🔨 mined potential block                  number=320 hash=82bff8…e609e2
INFO [04-27|14:34:41.803] Commit new mining work                   number=321 sealhash=cf32ce…bd096b uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:34:44.480] Looking for peers                        peercount=1 tried=63  static=0
INFO [04-27|14:34:50.582] Successfully sealed new block            number=321 sealhash=cf32ce…bd096b hash=2f3441…4fd137 elapsed=8.786s
INFO [04-27|14:34:50.582] 🔗 block reached canonical chain          number=314 hash=1a9150…fb590c
INFO [04-27|14:34:50.590] 🔨 mined potential block                  number=321 hash=2f3441…4fd137
INFO [04-27|14:34:50.590] Commit new mining work                   number=322 sealhash=709282…d5af2a uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:34:51.239] Successfully sealed new block            number=322 sealhash=709282…d5af2a hash=d29a36…7e9dc8 elapsed=657.242ms
INFO [04-27|14:34:51.239] 🔗 block reached canonical chain          number=315 hash=7b072f…4b9532
INFO [04-27|14:34:51.246] 🔨 mined potential block                  number=322 hash=d29a36…7e9dc8
INFO [04-27|14:34:51.246] Commit new mining work                   number=323 sealhash=204751…4cea35 uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:34:53.027] Successfully sealed new block            number=323 sealhash=204751…4cea35 hash=99072b…8a609a elapsed=1.788s
INFO [04-27|14:34:53.028] 🔗 block reached canonical chain          number=316 hash=276c65…d04029
INFO [04-27|14:34:53.037] Commit new mining work                   number=324 sealhash=544759…556892 uncles=0 txs=0 gas=0     fees=0        elapsed=9.939ms
INFO [04-27|14:34:53.037] 🔨 mined potential block                  number=323 hash=99072b…8a609a
INFO [04-27|14:34:53.170] Successfully sealed new block            number=324 sealhash=544759…556892 hash=06fe7e…b45d1a elapsed=141.609ms
INFO [04-27|14:34:53.170] 🔗 block reached canonical chain          number=317 hash=1c81b1…57cfce
INFO [04-27|14:34:53.178] 🔨 mined potential block                  number=324 hash=06fe7e…b45d1a
INFO [04-27|14:34:53.178] Commit new mining work                   number=325 sealhash=40445c…e3cdb1 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:34:54.481] Looking for peers                        peercount=2 tried=60  static=0
INFO [04-27|14:35:00.063] Successfully sealed new block            number=325 sealhash=40445c…e3cdb1 hash=c5804e…6af3ad elapsed=6.893s
INFO [04-27|14:35:00.064] 🔗 block reached canonical chain          number=318 hash=9699f8…28c329
INFO [04-27|14:35:00.072] 🔨 mined potential block                  number=325 hash=c5804e…6af3ad
INFO [04-27|14:35:00.072] Commit new mining work                   number=326 sealhash=c20cb7…2cc462 uncles=0 txs=0 gas=0     fees=0        elapsed=8.942ms
INFO [04-27|14:35:04.539] Looking for peers                        peercount=1 tried=56  static=0
INFO [04-27|14:35:10.327] Successfully sealed new block            number=326 sealhash=c20cb7…2cc462 hash=0e3179…4cf144 elapsed=10.262s
INFO [04-27|14:35:10.327] 🔗 block reached canonical chain          number=319 hash=befbb3…3b4e17
INFO [04-27|14:35:10.334] 🔨 mined potential block                  number=326 hash=0e3179…4cf144
INFO [04-27|14:35:10.334] Commit new mining work                   number=327 sealhash=e523c5…f3128d uncles=0 txs=0 gas=0     fees=0        elapsed=6.983ms
INFO [04-27|14:35:14.733] Looking for peers                        peercount=1 tried=55  static=0
INFO [04-27|14:35:19.395] Successfully sealed new block            number=327 sealhash=e523c5…f3128d hash=709602…2c0997 elapsed=9.067s
INFO [04-27|14:35:19.395] 🔗 block reached canonical chain          number=320 hash=82bff8…e609e2
INFO [04-27|14:35:19.403] Commit new mining work                   number=328 sealhash=7bf97f…50fa3b uncles=0 txs=0 gas=0     fees=0        elapsed=7.958ms
INFO [04-27|14:35:19.403] 🔨 mined potential block                  number=327 hash=709602…2c0997
INFO [04-27|14:35:19.411] Successfully sealed new block            number=328 sealhash=7bf97f…50fa3b hash=e64eb3…b5dc4e elapsed=15.923ms
INFO [04-27|14:35:19.411] 🔗 block reached canonical chain          number=321 hash=2f3441…4fd137
INFO [04-27|14:35:19.418] 🔨 mined potential block                  number=328 hash=e64eb3…b5dc4e
INFO [04-27|14:35:19.418] Commit new mining work                   number=329 sealhash=055aae…bc415d uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:35:24.107] Successfully sealed new block            number=329 sealhash=055aae…bc415d hash=414bb3…231173 elapsed=4.696s
INFO [04-27|14:35:24.107] 🔗 block reached canonical chain          number=322 hash=d29a36…7e9dc8
INFO [04-27|14:35:24.114] 🔨 mined potential block                  number=329 hash=414bb3…231173
INFO [04-27|14:35:24.114] Commit new mining work                   number=330 sealhash=b6883d…064eb1 uncles=0 txs=0 gas=0     fees=0        elapsed=6.946ms
INFO [04-27|14:35:24.309] Successfully sealed new block            number=330 sealhash=b6883d…064eb1 hash=100025…64510b elapsed=201.460ms
INFO [04-27|14:35:24.309] 🔗 block reached canonical chain          number=323 hash=99072b…8a609a
INFO [04-27|14:35:24.316] 🔨 mined potential block                  number=330 hash=100025…64510b
INFO [04-27|14:35:24.316] Commit new mining work                   number=331 sealhash=b74015…a58da1 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:35:24.768] Looking for peers                        peercount=2 tried=58  static=0
INFO [04-27|14:35:25.933] Successfully sealed new block            number=331 sealhash=b74015…a58da1 hash=f7d5d4…3cbde6 elapsed=1.624s
INFO [04-27|14:35:25.934] 🔗 block reached canonical chain          number=324 hash=06fe7e…b45d1a
INFO [04-27|14:35:25.944] 🔨 mined potential block                  number=331 hash=f7d5d4…3cbde6
INFO [04-27|14:35:25.944] Commit new mining work                   number=332 sealhash=c55f55…35c617 uncles=0 txs=0 gas=0     fees=0        elapsed=10.981ms
INFO [04-27|14:35:32.984] Successfully sealed new block            number=332 sealhash=c55f55…35c617 hash=69c8cf…974375 elapsed=7.051s
INFO [04-27|14:35:32.984] 🔗 block reached canonical chain          number=325 hash=c5804e…6af3ad
INFO [04-27|14:35:32.991] 🔨 mined potential block                  number=332 hash=69c8cf…974375
INFO [04-27|14:35:32.991] Commit new mining work                   number=333 sealhash=de6daa…4095fc uncles=0 txs=0 gas=0     fees=0        elapsed=6.947ms
INFO [04-27|14:35:34.785] Looking for peers                        peercount=1 tried=40  static=0
INFO [04-27|14:35:44.821] Looking for peers                        peercount=1 tried=66  static=0
INFO [04-27|14:35:48.530] Successfully sealed new block            number=333 sealhash=de6daa…4095fc hash=66c4f5…3eada7 elapsed=15.545s
INFO [04-27|14:35:48.530] 🔗 block reached canonical chain          number=326 hash=0e3179…4cf144
INFO [04-27|14:35:48.538] Commit new mining work                   number=334 sealhash=256aaf…bb632a uncles=0 txs=0 gas=0     fees=0        elapsed=7.948ms
INFO [04-27|14:35:48.538] 🔨 mined potential block                  number=333 hash=66c4f5…3eada7
INFO [04-27|14:35:54.866] Looking for peers                        peercount=1 tried=57  static=0
INFO [04-27|14:35:54.920] Successfully sealed new block            number=334 sealhash=256aaf…bb632a hash=3c14fd…b31126 elapsed=6.389s
INFO [04-27|14:35:54.920] 🔗 block reached canonical chain          number=327 hash=709602…2c0997
INFO [04-27|14:35:54.928] 🔨 mined potential block                  number=334 hash=3c14fd…b31126
INFO [04-27|14:35:54.928] Commit new mining work                   number=335 sealhash=aad1ba…52acc3 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:35:59.965] Successfully sealed new block            number=335 sealhash=aad1ba…52acc3 hash=4d73eb…bd1a17 elapsed=5.045s
INFO [04-27|14:35:59.965] 🔗 block reached canonical chain          number=328 hash=e64eb3…b5dc4e
INFO [04-27|14:35:59.973] Commit new mining work                   number=336 sealhash=c30118…238ae2 uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:35:59.973] 🔨 mined potential block                  number=335 hash=4d73eb…bd1a17
INFO [04-27|14:36:00.511] Successfully sealed new block            number=336 sealhash=c30118…238ae2 hash=b8f410…b5f911 elapsed=545.504ms
INFO [04-27|14:36:00.511] 🔗 block reached canonical chain          number=329 hash=414bb3…231173
INFO [04-27|14:36:00.519] 🔨 mined potential block                  number=336 hash=b8f410…b5f911
INFO [04-27|14:36:00.519] Commit new mining work                   number=337 sealhash=e01210…a8a521 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:36:01.547] Successfully sealed new block            number=337 sealhash=e01210…a8a521 hash=3269f5…3a75ad elapsed=1.036s
INFO [04-27|14:36:01.547] 🔗 block reached canonical chain          number=330 hash=100025…64510b
INFO [04-27|14:36:01.555] Commit new mining work                   number=338 sealhash=d17d9f…cc1b95 uncles=0 txs=0 gas=0     fees=0        elapsed=7.974ms
INFO [04-27|14:36:01.555] 🔨 mined potential block                  number=337 hash=3269f5…3a75ad
INFO [04-27|14:36:03.713] Successfully sealed new block            number=338 sealhash=d17d9f…cc1b95 hash=c0c270…4ab0a2 elapsed=2.166s
INFO [04-27|14:36:03.713] 🔗 block reached canonical chain          number=331 hash=f7d5d4…3cbde6
INFO [04-27|14:36:03.721] 🔨 mined potential block                  number=338 hash=c0c270…4ab0a2
INFO [04-27|14:36:03.721] Commit new mining work                   number=339 sealhash=2e9413…2d25f8 uncles=0 txs=0 gas=0     fees=0        elapsed=7.948ms
INFO [04-27|14:36:05.007] Looking for peers                        peercount=1 tried=59  static=0
INFO [04-27|14:36:15.035] Looking for peers                        peercount=1 tried=56  static=0
INFO [04-27|14:36:17.470] Successfully sealed new block            number=339 sealhash=2e9413…2d25f8 hash=0e1f04…778b30 elapsed=13.757s
INFO [04-27|14:36:17.470] 🔗 block reached canonical chain          number=332 hash=69c8cf…974375
INFO [04-27|14:36:17.479] 🔨 mined potential block                  number=339 hash=0e1f04…778b30
INFO [04-27|14:36:17.479] Commit new mining work                   number=340 sealhash=f73207…f6fcb9 uncles=0 txs=0 gas=0     fees=0        elapsed=8.969ms
INFO [04-27|14:36:23.067] Successfully sealed new block            number=340 sealhash=f73207…f6fcb9 hash=f588ec…db14e7 elapsed=5.596s
INFO [04-27|14:36:23.067] 🔗 block reached canonical chain          number=333 hash=66c4f5…3eada7
INFO [04-27|14:36:23.074] 🔨 mined potential block                  number=340 hash=f588ec…db14e7
INFO [04-27|14:36:23.074] Commit new mining work                   number=341 sealhash=d76427…b083a3 uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:36:28.315] Successfully sealed new block            number=341 sealhash=d76427…b083a3 hash=a99398…d1fb83 elapsed=5.248s
INFO [04-27|14:36:28.315] 🔗 block reached canonical chain          number=334 hash=3c14fd…b31126
INFO [04-27|14:36:28.323] 🔨 mined potential block                  number=341 hash=a99398…d1fb83
INFO [04-27|14:36:28.323] Commit new mining work                   number=342 sealhash=8aca31…a5030a uncles=0 txs=0 gas=0     fees=0        elapsed=7.973ms
INFO [04-27|14:36:30.693] Successfully sealed new block            number=342 sealhash=8aca31…a5030a hash=7f8b87…e72158 elapsed=2.377s
INFO [04-27|14:36:30.693] 🔗 block reached canonical chain          number=335 hash=4d73eb…bd1a17
INFO [04-27|14:36:30.702] Commit new mining work                   number=343 sealhash=45f5a1…5b92d1 uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:36:30.702] 🔨 mined potential block                  number=342 hash=7f8b87…e72158
INFO [04-27|14:36:35.149] Looking for peers                        peercount=1 tried=118 static=0
INFO [04-27|14:36:45.154] Looking for peers                        peercount=1 tried=106 static=0
INFO [04-27|14:36:48.081] Successfully sealed new block            number=343 sealhash=45f5a1…5b92d1 hash=bc6d99…c9cb09 elapsed=17.388s
INFO [04-27|14:36:48.081] 🔗 block reached canonical chain          number=336 hash=b8f410…b5f911
INFO [04-27|14:36:48.088] Commit new mining work                   number=344 sealhash=fb3cd9…1c46d5 uncles=0 txs=0 gas=0     fees=0        elapsed=6.978ms
INFO [04-27|14:36:48.088] 🔨 mined potential block                  number=343 hash=bc6d99…c9cb09
INFO [04-27|14:36:55.290] Looking for peers                        peercount=2 tried=120 static=0
INFO [04-27|14:36:58.575] Successfully sealed new block            number=344 sealhash=fb3cd9…1c46d5 hash=715ea0…53f84a elapsed=10.493s
INFO [04-27|14:36:58.575] 🔗 block reached canonical chain          number=337 hash=3269f5…3a75ad
INFO [04-27|14:36:58.584] 🔨 mined potential block                  number=344 hash=715ea0…53f84a
INFO [04-27|14:36:58.584] Commit new mining work                   number=345 sealhash=7e902c…01f214 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:36:58.970] Successfully sealed new block            number=345 sealhash=7e902c…01f214 hash=94de31…10bff0 elapsed=394.947ms
INFO [04-27|14:36:58.970] 🔗 block reached canonical chain          number=338 hash=c0c270…4ab0a2
INFO [04-27|14:36:58.977] 🔨 mined potential block                  number=345 hash=94de31…10bff0
INFO [04-27|14:36:58.977] Commit new mining work                   number=346 sealhash=6899a3…51e141 uncles=0 txs=0 gas=0     fees=0        elapsed=6.971ms
INFO [04-27|14:37:01.824] Successfully sealed new block            number=346 sealhash=6899a3…51e141 hash=eeadad…86e447 elapsed=2.853s
INFO [04-27|14:37:01.824] 🔗 block reached canonical chain          number=339 hash=0e1f04…778b30
INFO [04-27|14:37:01.832] 🔨 mined potential block                  number=346 hash=eeadad…86e447
INFO [04-27|14:37:01.832] Commit new mining work                   number=347 sealhash=cc8b13…6a84ba uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:37:02.926] Successfully sealed new block            number=347 sealhash=cc8b13…6a84ba hash=3fe648…95d713 elapsed=1.102s
INFO [04-27|14:37:02.926] 🔗 block reached canonical chain          number=340 hash=f588ec…db14e7
INFO [04-27|14:37:02.935] 🔨 mined potential block                  number=347 hash=3fe648…95d713
INFO [04-27|14:37:02.935] Commit new mining work                   number=348 sealhash=bd248c…3104b4 uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:37:05.334] Looking for peers                        peercount=2 tried=96  static=0
INFO [04-27|14:37:12.708] Successfully sealed new block            number=348 sealhash=bd248c…3104b4 hash=bc4ed0…c55744 elapsed=9.781s
INFO [04-27|14:37:12.709] 🔗 block reached canonical chain          number=341 hash=a99398…d1fb83
INFO [04-27|14:37:12.716] 🔨 mined potential block                  number=348 hash=bc4ed0…c55744
INFO [04-27|14:37:12.716] Commit new mining work                   number=349 sealhash=9fd498…ac15e7 uncles=0 txs=0 gas=0     fees=0        elapsed=6.960ms
INFO [04-27|14:37:13.896] Successfully sealed new block            number=349 sealhash=9fd498…ac15e7 hash=f0eaa4…234b60 elapsed=1.187s
INFO [04-27|14:37:13.896] 🔗 block reached canonical chain          number=342 hash=7f8b87…e72158
INFO [04-27|14:37:13.904] 🔨 mined potential block                  number=349 hash=f0eaa4…234b60
INFO [04-27|14:37:13.904] Commit new mining work                   number=350 sealhash=e75359…314520 uncles=0 txs=0 gas=0     fees=0        elapsed=7.942ms
INFO [04-27|14:37:15.350] Looking for peers                        peercount=2 tried=124 static=0
INFO [04-27|14:37:15.823] Successfully sealed new block            number=350 sealhash=e75359…314520 hash=842ccf…fc5a1d elapsed=1.926s
INFO [04-27|14:37:15.824] 🔗 block reached canonical chain          number=343 hash=bc6d99…c9cb09
INFO [04-27|14:37:15.832] 🔨 mined potential block                  number=350 hash=842ccf…fc5a1d
INFO [04-27|14:37:15.832] Commit new mining work                   number=351 sealhash=f1ceb0…5d8851 uncles=0 txs=0 gas=0     fees=0        elapsed=8.962ms
INFO [04-27|14:37:18.066] Successfully sealed new block            number=351 sealhash=f1ceb0…5d8851 hash=67d451…27e183 elapsed=2.242s
INFO [04-27|14:37:18.066] 🔗 block reached canonical chain          number=344 hash=715ea0…53f84a
INFO [04-27|14:37:18.073] 🔨 mined potential block                  number=351 hash=67d451…27e183
INFO [04-27|14:37:18.073] Commit new mining work                   number=352 sealhash=eca75e…f3f3cf uncles=0 txs=0 gas=0     fees=0        elapsed=7.006ms
INFO [04-27|14:37:21.083] Successfully sealed new block            number=352 sealhash=eca75e…f3f3cf hash=0b2623…290c17 elapsed=3.016s
INFO [04-27|14:37:21.084] 🔗 block reached canonical chain          number=345 hash=94de31…10bff0
INFO [04-27|14:37:21.092] 🔨 mined potential block                  number=352 hash=0b2623…290c17
INFO [04-27|14:37:21.092] Commit new mining work                   number=353 sealhash=004041…502c6c uncles=0 txs=0 gas=0     fees=0        elapsed=8.941ms
INFO [04-27|14:37:25.370] Looking for peers                        peercount=1 tried=109 static=0
INFO [04-27|14:37:35.307] Successfully sealed new block            number=353 sealhash=004041…502c6c hash=224efd…d8b8a1 elapsed=14.223s
INFO [04-27|14:37:35.307] 🔗 block reached canonical chain          number=346 hash=eeadad…86e447
INFO [04-27|14:37:35.316] 🔨 mined potential block                  number=353 hash=224efd…d8b8a1
INFO [04-27|14:37:35.316] Commit new mining work                   number=354 sealhash=8ea516…cdf6ed uncles=0 txs=0 gas=0     fees=0        elapsed=8.938ms
INFO [04-27|14:37:35.408] Looking for peers                        peercount=1 tried=101 static=0
INFO [04-27|14:37:42.533] Successfully sealed new block            number=354 sealhash=8ea516…cdf6ed hash=47073b…9cfba0 elapsed=7.225s
INFO [04-27|14:37:42.533] 🔗 block reached canonical chain          number=347 hash=3fe648…95d713
INFO [04-27|14:37:42.541] 🔨 mined potential block                  number=354 hash=47073b…9cfba0
INFO [04-27|14:37:42.541] Commit new mining work                   number=355 sealhash=028ca1…aa1f61 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:37:43.590] Successfully sealed new block            number=355 sealhash=028ca1…aa1f61 hash=f5ea6b…562d07 elapsed=1.057s
INFO [04-27|14:37:43.591] 🔗 block reached canonical chain          number=348 hash=bc4ed0…c55744
INFO [04-27|14:37:43.598] 🔨 mined potential block                  number=355 hash=f5ea6b…562d07
INFO [04-27|14:37:43.598] Commit new mining work                   number=356 sealhash=d42258…f32363 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:37:45.478] Looking for peers                        peercount=1 tried=129 static=0
INFO [04-27|14:37:46.165] Successfully sealed new block            number=356 sealhash=d42258…f32363 hash=5f6656…0bd225 elapsed=2.574s
INFO [04-27|14:37:46.165] 🔗 block reached canonical chain          number=349 hash=f0eaa4…234b60
INFO [04-27|14:37:46.173] 🔨 mined potential block                  number=356 hash=5f6656…0bd225
INFO [04-27|14:37:46.173] Commit new mining work                   number=357 sealhash=a64676…75dd30 uncles=0 txs=0 gas=0     fees=0        elapsed=7.946ms
INFO [04-27|14:37:50.475] Successfully sealed new block            number=357 sealhash=a64676…75dd30 hash=710482…326764 elapsed=4.309s
INFO [04-27|14:37:50.475] 🔗 block reached canonical chain          number=350 hash=842ccf…fc5a1d
INFO [04-27|14:37:50.483] 🔨 mined potential block                  number=357 hash=710482…326764
INFO [04-27|14:37:50.483] Commit new mining work                   number=358 sealhash=44547a…63ec30 uncles=0 txs=0 gas=0     fees=0        elapsed=7.938ms
INFO [04-27|14:37:50.554] Successfully sealed new block            number=358 sealhash=44547a…63ec30 hash=c7f8ff…0f92f9 elapsed=79.781ms
INFO [04-27|14:37:50.554] 🔗 block reached canonical chain          number=351 hash=67d451…27e183
INFO [04-27|14:37:50.562] Commit new mining work                   number=359 sealhash=482b72…8470a8 uncles=0 txs=0 gas=0     fees=0        elapsed=7.955ms
INFO [04-27|14:37:50.562] 🔨 mined potential block                  number=358 hash=c7f8ff…0f92f9
INFO [04-27|14:37:52.340] Successfully sealed new block            number=359 sealhash=482b72…8470a8 hash=ea1be3…24576f elapsed=1.785s
INFO [04-27|14:37:52.341] 🔗 block reached canonical chain          number=352 hash=0b2623…290c17
INFO [04-27|14:37:52.348] 🔨 mined potential block                  number=359 hash=ea1be3…24576f
INFO [04-27|14:37:52.348] Commit new mining work                   number=360 sealhash=c0d9a8…dc7295 uncles=0 txs=0 gas=0     fees=0        elapsed=7.964ms
INFO [04-27|14:37:55.508] Looking for peers                        peercount=2 tried=97  static=0
INFO [04-27|14:37:59.085] Successfully sealed new block            number=360 sealhash=c0d9a8…dc7295 hash=e1e190…df782f elapsed=6.743s
INFO [04-27|14:37:59.085] 🔗 block reached canonical chain          number=353 hash=224efd…d8b8a1
INFO [04-27|14:37:59.093] 🔨 mined potential block                  number=360 hash=e1e190…df782f
INFO [04-27|14:37:59.093] Commit new mining work                   number=361 sealhash=13d45c…d80afd uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:38:01.791] Successfully sealed new block            number=361 sealhash=13d45c…d80afd hash=fad106…122fbd elapsed=2.706s
INFO [04-27|14:38:01.792] 🔗 block reached canonical chain          number=354 hash=47073b…9cfba0
INFO [04-27|14:38:01.800] 🔨 mined potential block                  number=361 hash=fad106…122fbd
INFO [04-27|14:38:01.800] Commit new mining work                   number=362 sealhash=e7086a…566ab2 uncles=0 txs=0 gas=0     fees=0        elapsed=7.941ms
INFO [04-27|14:38:05.592] Looking for peers                        peercount=1 tried=102 static=0
INFO [04-27|14:38:15.616] Looking for peers                        peercount=1 tried=120 static=0
INFO [04-27|14:38:25.032] Successfully sealed new block            number=362 sealhash=e7086a…566ab2 hash=8b09cd…9c01f5 elapsed=23.239s
INFO [04-27|14:38:25.032] 🔗 block reached canonical chain          number=355 hash=f5ea6b…562d07
INFO [04-27|14:38:25.040] 🔨 mined potential block                  number=362 hash=8b09cd…9c01f5
INFO [04-27|14:38:25.040] Commit new mining work                   number=363 sealhash=9c4d54…915813 uncles=0 txs=0 gas=0     fees=0        elapsed=7.946ms
INFO [04-27|14:38:25.679] Looking for peers                        peercount=1 tried=81  static=0
INFO [04-27|14:38:30.307] Successfully sealed new block            number=363 sealhash=9c4d54…915813 hash=2a6942…cfe560 elapsed=5.274s
INFO [04-27|14:38:30.308] 🔗 block reached canonical chain          number=356 hash=5f6656…0bd225
INFO [04-27|14:38:30.315] 🔨 mined potential block                  number=363 hash=2a6942…cfe560
INFO [04-27|14:38:30.315] Commit new mining work                   number=364 sealhash=76e434…f7c864 uncles=0 txs=0 gas=0     fees=0        elapsed=6.982ms
INFO [04-27|14:38:30.573] Successfully sealed new block            number=364 sealhash=76e434…f7c864 hash=f2e2fd…a34753 elapsed=264.299ms
INFO [04-27|14:38:30.573] 🔗 block reached canonical chain          number=357 hash=710482…326764
INFO [04-27|14:38:30.580] Commit new mining work                   number=365 sealhash=b5cfe9…560270 uncles=0 txs=0 gas=0     fees=0        elapsed=6.994ms
INFO [04-27|14:38:30.580] 🔨 mined potential block                  number=364 hash=f2e2fd…a34753
INFO [04-27|14:38:35.802] Looking for peers                        peercount=1 tried=93  static=0
INFO [04-27|14:38:36.154] Successfully sealed new block            number=365 sealhash=b5cfe9…560270 hash=94a055…ec73ce elapsed=5.581s
INFO [04-27|14:38:36.154] 🔗 block reached canonical chain          number=358 hash=c7f8ff…0f92f9
INFO [04-27|14:38:36.162] Commit new mining work                   number=366 sealhash=664c23…ff4452 uncles=0 txs=0 gas=0     fees=0        elapsed=7.946ms
INFO [04-27|14:38:36.162] 🔨 mined potential block                  number=365 hash=94a055…ec73ce
INFO [04-27|14:38:36.600] Successfully sealed new block            number=366 sealhash=664c23…ff4452 hash=7bb65c…b45e73 elapsed=446.805ms
INFO [04-27|14:38:36.600] 🔗 block reached canonical chain          number=359 hash=ea1be3…24576f
INFO [04-27|14:38:36.609] Commit new mining work                   number=367 sealhash=40660d…eebfc4 uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:38:36.609] 🔨 mined potential block                  number=366 hash=7bb65c…b45e73
INFO [04-27|14:38:45.894] Looking for peers                        peercount=1 tried=48  static=0
INFO [04-27|14:38:51.611] Successfully sealed new block            number=367 sealhash=40660d…eebfc4 hash=02efbe…c38380 elapsed=15.010s
INFO [04-27|14:38:51.611] 🔗 block reached canonical chain          number=360 hash=e1e190…df782f
INFO [04-27|14:38:51.618] Commit new mining work                   number=368 sealhash=a069ee…49722f uncles=0 txs=0 gas=0     fees=0        elapsed=6.974ms
INFO [04-27|14:38:51.618] 🔨 mined potential block                  number=367 hash=02efbe…c38380
INFO [04-27|14:38:54.053] Successfully sealed new block            number=368 sealhash=a069ee…49722f hash=0fa1c2…8e73c2 elapsed=2.441s
INFO [04-27|14:38:54.053] 🔗 block reached canonical chain          number=361 hash=fad106…122fbd
INFO [04-27|14:38:54.060] Commit new mining work                   number=369 sealhash=f3afb8…4a85ed uncles=0 txs=0 gas=0     fees=0        elapsed=6.947ms
INFO [04-27|14:38:54.060] 🔨 mined potential block                  number=368 hash=0fa1c2…8e73c2
INFO [04-27|14:38:55.404] Successfully sealed new block            number=369 sealhash=f3afb8…4a85ed hash=0db686…b3fce9 elapsed=1.351s
INFO [04-27|14:38:55.404] 🔗 block reached canonical chain          number=362 hash=8b09cd…9c01f5
INFO [04-27|14:38:55.411] 🔨 mined potential block                  number=369 hash=0db686…b3fce9
INFO [04-27|14:38:55.411] Commit new mining work                   number=370 sealhash=c8b0ed…46df62 uncles=0 txs=0 gas=0     fees=0        elapsed=6.947ms
INFO [04-27|14:38:55.989] Looking for peers                        peercount=1 tried=88  static=0
INFO [04-27|14:39:05.989] Looking for peers                        peercount=1 tried=64  static=0
INFO [04-27|14:39:12.683] Successfully sealed new block            number=370 sealhash=c8b0ed…46df62 hash=70f8e4…2e2c59 elapsed=17.278s
INFO [04-27|14:39:12.683] 🔗 block reached canonical chain          number=363 hash=2a6942…cfe560
INFO [04-27|14:39:12.691] 🔨 mined potential block                  number=370 hash=70f8e4…2e2c59
INFO [04-27|14:39:12.691] Commit new mining work                   number=371 sealhash=e478aa…340b61 uncles=0 txs=0 gas=0     fees=0        elapsed=7.977ms
INFO [04-27|14:39:17.137] Looking for peers                        peercount=1 tried=31  static=0
INFO [04-27|14:39:22.683] Successfully sealed new block            number=371 sealhash=e478aa…340b61 hash=a8bb5c…8d8912 elapsed=10.000s
INFO [04-27|14:39:22.683] 🔗 block reached canonical chain          number=364 hash=f2e2fd…a34753
INFO [04-27|14:39:22.691] 🔨 mined potential block                  number=371 hash=a8bb5c…8d8912
INFO [04-27|14:39:22.691] Commit new mining work                   number=372 sealhash=c40d57…272a2f uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:39:25.630] Successfully sealed new block            number=372 sealhash=c40d57…272a2f hash=4c162c…dafaab elapsed=2.947s
INFO [04-27|14:39:25.630] 🔗 block reached canonical chain          number=365 hash=94a055…ec73ce
INFO [04-27|14:39:25.637] 🔨 mined potential block                  number=372 hash=4c162c…dafaab
INFO [04-27|14:39:25.637] Commit new mining work                   number=373 sealhash=dd5403…e7c600 uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:39:27.227] Looking for peers                        peercount=1 tried=75  static=0
INFO [04-27|14:39:37.433] Looking for peers                        peercount=1 tried=60  static=0
INFO [04-27|14:39:43.581] Successfully sealed new block            number=373 sealhash=dd5403…e7c600 hash=db553e…64c058 elapsed=17.951s
INFO [04-27|14:39:43.582] 🔗 block reached canonical chain          number=366 hash=7bb65c…b45e73
INFO [04-27|14:39:43.590] 🔨 mined potential block                  number=373 hash=db553e…64c058
INFO [04-27|14:39:43.590] Commit new mining work                   number=374 sealhash=9b5dc6…4adf9b uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:39:44.992] Successfully sealed new block            number=374 sealhash=9b5dc6…4adf9b hash=385ec4…179454 elapsed=1.410s
INFO [04-27|14:39:44.993] 🔗 block reached canonical chain          number=367 hash=02efbe…c38380
INFO [04-27|14:39:45.000] 🔨 mined potential block                  number=374 hash=385ec4…179454
INFO [04-27|14:39:45.000] Commit new mining work                   number=375 sealhash=2bb3cc…7adbbc uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:39:46.582] Successfully sealed new block            number=375 sealhash=2bb3cc…7adbbc hash=76edd9…3331c8 elapsed=1.588s
INFO [04-27|14:39:46.583] 🔗 block reached canonical chain          number=368 hash=0fa1c2…8e73c2
INFO [04-27|14:39:46.591] Commit new mining work                   number=376 sealhash=418350…b8d401 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:39:46.591] 🔨 mined potential block                  number=375 hash=76edd9…3331c8
INFO [04-27|14:39:47.435] Looking for peers                        peercount=1 tried=44  static=0
INFO [04-27|14:39:50.915] Successfully sealed new block            number=376 sealhash=418350…b8d401 hash=40a2a2…56ee64 elapsed=4.331s
INFO [04-27|14:39:50.915] 🔗 block reached canonical chain          number=369 hash=0db686…b3fce9
INFO [04-27|14:39:50.923] 🔨 mined potential block                  number=376 hash=40a2a2…56ee64
INFO [04-27|14:39:50.923] Commit new mining work                   number=377 sealhash=6b846a…1fbf52 uncles=0 txs=0 gas=0     fees=0        elapsed=7.943ms
INFO [04-27|14:39:52.980] Successfully sealed new block            number=377 sealhash=6b846a…1fbf52 hash=285ad9…661543 elapsed=2.065s
INFO [04-27|14:39:52.980] 🔗 block reached canonical chain          number=370 hash=70f8e4…2e2c59
INFO [04-27|14:39:52.987] 🔨 mined potential block                  number=377 hash=285ad9…661543
INFO [04-27|14:39:52.987] Commit new mining work                   number=378 sealhash=73e7b2…cddc57 uncles=0 txs=0 gas=0     fees=0        elapsed=6.947ms
INFO [04-27|14:39:55.523] Successfully sealed new block            number=378 sealhash=73e7b2…cddc57 hash=ffe309…08e15e elapsed=2.543s
INFO [04-27|14:39:55.523] 🔗 block reached canonical chain          number=371 hash=a8bb5c…8d8912
INFO [04-27|14:39:55.531] 🔨 mined potential block                  number=378 hash=ffe309…08e15e
INFO [04-27|14:39:55.531] Commit new mining work                   number=379 sealhash=4d4721…e55cab uncles=0 txs=0 gas=0     fees=0        elapsed=7.972ms
INFO [04-27|14:39:57.449] Looking for peers                        peercount=1 tried=70  static=0
INFO [04-27|14:39:57.792] Successfully sealed new block            number=379 sealhash=4d4721…e55cab hash=f5cf2c…39bbba elapsed=2.268s
INFO [04-27|14:39:57.792] 🔗 block reached canonical chain          number=372 hash=4c162c…dafaab
INFO [04-27|14:39:57.799] Commit new mining work                   number=380 sealhash=dc6622…490adf uncles=0 txs=0 gas=0     fees=0        elapsed=6.971ms
INFO [04-27|14:39:57.799] 🔨 mined potential block                  number=379 hash=f5cf2c…39bbba
INFO [04-27|14:40:05.157] Successfully sealed new block            number=380 sealhash=dc6622…490adf hash=f77f17…0c4723 elapsed=7.364s
INFO [04-27|14:40:05.157] 🔗 block reached canonical chain          number=373 hash=db553e…64c058
INFO [04-27|14:40:05.165] 🔨 mined potential block                  number=380 hash=f77f17…0c4723
INFO [04-27|14:40:05.165] Commit new mining work                   number=381 sealhash=c4a72a…de2ec7 uncles=0 txs=0 gas=0     fees=0        elapsed=7.962ms
INFO [04-27|14:40:06.930] Successfully sealed new block            number=381 sealhash=c4a72a…de2ec7 hash=5900aa…36619c elapsed=1.773s
INFO [04-27|14:40:06.930] 🔗 block reached canonical chain          number=374 hash=385ec4…179454
INFO [04-27|14:40:06.939] Commit new mining work                   number=382 sealhash=ae0f94…a6094b uncles=0 txs=0 gas=0     fees=0        elapsed=8.942ms
INFO [04-27|14:40:06.939] 🔨 mined potential block                  number=381 hash=5900aa…36619c
INFO [04-27|14:40:07.451] Looking for peers                        peercount=1 tried=51  static=0
INFO [04-27|14:40:08.559] Successfully sealed new block            number=382 sealhash=ae0f94…a6094b hash=36846f…eebdb4 elapsed=1.629s
INFO [04-27|14:40:08.560] 🔗 block reached canonical chain          number=375 hash=76edd9…3331c8
INFO [04-27|14:40:08.568] 🔨 mined potential block                  number=382 hash=36846f…eebdb4
INFO [04-27|14:40:08.568] Commit new mining work                   number=383 sealhash=2a9dca…16188f uncles=0 txs=0 gas=0     fees=0        elapsed=8.989ms
INFO [04-27|14:40:09.587] Successfully sealed new block            number=383 sealhash=2a9dca…16188f hash=1b9c7d…679b1f elapsed=1.026s
INFO [04-27|14:40:09.587] 🔗 block reached canonical chain          number=376 hash=40a2a2…56ee64
INFO [04-27|14:40:09.594] 🔨 mined potential block                  number=383 hash=1b9c7d…679b1f
INFO [04-27|14:40:09.594] Commit new mining work                   number=384 sealhash=509490…278aa1 uncles=0 txs=0 gas=0     fees=0        elapsed=6.977ms
INFO [04-27|14:40:13.586] Successfully sealed new block            number=384 sealhash=509490…278aa1 hash=248d0e…3b5731 elapsed=3.999s
INFO [04-27|14:40:13.586] 🔗 block reached canonical chain          number=377 hash=285ad9…661543
INFO [04-27|14:40:13.595] 🔨 mined potential block                  number=384 hash=248d0e…3b5731
INFO [04-27|14:40:13.595] Commit new mining work                   number=385 sealhash=0f8905…027d82 uncles=0 txs=0 gas=0     fees=0        elapsed=8.942ms
INFO [04-27|14:40:13.609] Successfully sealed new block            number=385 sealhash=0f8905…027d82 hash=6cddb3…9efd84 elapsed=22.905ms
INFO [04-27|14:40:13.609] 🔗 block reached canonical chain          number=378 hash=ffe309…08e15e
INFO [04-27|14:40:13.617] 🔨 mined potential block                  number=385 hash=6cddb3…9efd84
INFO [04-27|14:40:13.617] Commit new mining work                   number=386 sealhash=588c06…da3ac5 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:40:17.519] Looking for peers                        peercount=1 tried=57  static=0
INFO [04-27|14:40:20.540] Successfully sealed new block            number=386 sealhash=588c06…da3ac5 hash=a1377e…17a454 elapsed=6.931s
INFO [04-27|14:40:20.541] 🔗 block reached canonical chain          number=379 hash=f5cf2c…39bbba
INFO [04-27|14:40:20.548] 🔨 mined potential block                  number=386 hash=a1377e…17a454
INFO [04-27|14:40:20.548] Commit new mining work                   number=387 sealhash=21beaf…506a25 uncles=0 txs=0 gas=0     fees=0        elapsed=6.941ms
INFO [04-27|14:40:27.547] Looking for peers                        peercount=2 tried=58  static=0
INFO [04-27|14:40:30.996] Successfully sealed new block            number=387 sealhash=21beaf…506a25 hash=6ceb85…6a2f7c elapsed=10.455s
INFO [04-27|14:40:30.996] 🔗 block reached canonical chain          number=380 hash=f77f17…0c4723
INFO [04-27|14:40:31.003] 🔨 mined potential block                  number=387 hash=6ceb85…6a2f7c
INFO [04-27|14:40:31.003] Commit new mining work                   number=388 sealhash=c0424a…3c481a uncles=0 txs=0 gas=0     fees=0        elapsed=6.947ms
INFO [04-27|14:40:37.715] Looking for peers                        peercount=1 tried=52  static=0
INFO [04-27|14:40:45.987] Successfully sealed new block            number=388 sealhash=c0424a…3c481a hash=c99fa9…aaa4e5 elapsed=14.990s
INFO [04-27|14:40:45.987] 🔗 block reached canonical chain          number=381 hash=5900aa…36619c
INFO [04-27|14:40:45.995] 🔨 mined potential block                  number=388 hash=c99fa9…aaa4e5
INFO [04-27|14:40:45.995] Commit new mining work                   number=389 sealhash=afdc4a…14a737 uncles=0 txs=0 gas=0     fees=0        elapsed=7.943ms
INFO [04-27|14:40:47.332] Successfully sealed new block            number=389 sealhash=afdc4a…14a737 hash=cb37ca…15c80e elapsed=1.344s
INFO [04-27|14:40:47.332] 🔗 block reached canonical chain          number=382 hash=36846f…eebdb4
INFO [04-27|14:40:47.340] 🔨 mined potential block                  number=389 hash=cb37ca…15c80e
INFO [04-27|14:40:47.340] Commit new mining work                   number=390 sealhash=737dc2…3eb7e5 uncles=0 txs=0 gas=0     fees=0        elapsed=7.958ms
INFO [04-27|14:40:47.354] Successfully sealed new block            number=390 sealhash=737dc2…3eb7e5 hash=6322d0…bc7647 elapsed=21.905ms
INFO [04-27|14:40:47.354] 🔗 block reached canonical chain          number=383 hash=1b9c7d…679b1f
INFO [04-27|14:40:47.362] Commit new mining work                   number=391 sealhash=775f00…c02152 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:40:47.362] 🔨 mined potential block                  number=390 hash=6322d0…bc7647
INFO [04-27|14:40:47.740] Looking for peers                        peercount=2 tried=98  static=0
INFO [04-27|14:40:48.039] Successfully sealed new block            number=391 sealhash=775f00…c02152 hash=44288a…c8a684 elapsed=685.203ms
INFO [04-27|14:40:48.039] 🔗 block reached canonical chain          number=384 hash=248d0e…3b5731
INFO [04-27|14:40:48.047] Commit new mining work                   number=392 sealhash=9269cb…a014fc uncles=0 txs=0 gas=0     fees=0        elapsed=7.942ms
INFO [04-27|14:40:48.047] 🔨 mined potential block                  number=391 hash=44288a…c8a684
INFO [04-27|14:40:52.155] Successfully sealed new block            number=392 sealhash=9269cb…a014fc hash=e0e16f…896f88 elapsed=4.115s
INFO [04-27|14:40:52.155] 🔗 block reached canonical chain          number=385 hash=6cddb3…9efd84
INFO [04-27|14:40:52.164] Commit new mining work                   number=393 sealhash=10da71…09a9e5 uncles=0 txs=0 gas=0     fees=0        elapsed=8.933ms
INFO [04-27|14:40:52.164] 🔨 mined potential block                  number=392 hash=e0e16f…896f88
INFO [04-27|14:40:57.771] Looking for peers                        peercount=2 tried=88  static=0
INFO [04-27|14:41:05.394] Successfully sealed new block            number=393 sealhash=10da71…09a9e5 hash=685ef9…66e005 elapsed=13.238s
INFO [04-27|14:41:05.395] 🔗 block reached canonical chain          number=386 hash=a1377e…17a454
INFO [04-27|14:41:05.402] 🔨 mined potential block                  number=393 hash=685ef9…66e005
INFO [04-27|14:41:05.402] Commit new mining work                   number=394 sealhash=702567…3007e6 uncles=0 txs=0 gas=0     fees=0        elapsed=6.980ms
INFO [04-27|14:41:06.367] Successfully sealed new block            number=394 sealhash=702567…3007e6 hash=8d4204…b02988 elapsed=972.432ms
INFO [04-27|14:41:06.368] 🔗 block reached canonical chain          number=387 hash=6ceb85…6a2f7c
INFO [04-27|14:41:06.376] 🔨 mined potential block                  number=394 hash=8d4204…b02988
INFO [04-27|14:41:06.376] Commit new mining work                   number=395 sealhash=09df56…f097c0 uncles=0 txs=0 gas=0     fees=0        elapsed=8.941ms
INFO [04-27|14:41:07.785] Looking for peers                        peercount=1 tried=174 static=0
INFO [04-27|14:41:17.887] Looking for peers                        peercount=1 tried=81  static=0
INFO [04-27|14:41:28.459] Looking for peers                        peercount=1 tried=130 static=0
INFO [04-27|14:41:35.044] Successfully sealed new block            number=395 sealhash=09df56…f097c0 hash=d13cfc…e5afa2 elapsed=28.676s
INFO [04-27|14:41:35.044] 🔗 block reached canonical chain          number=388 hash=c99fa9…aaa4e5
INFO [04-27|14:41:35.053] 🔨 mined potential block                  number=395 hash=d13cfc…e5afa2
INFO [04-27|14:41:35.053] Commit new mining work                   number=396 sealhash=6f68f8…4dcbd7 uncles=0 txs=0 gas=0     fees=0        elapsed=8.975ms
INFO [04-27|14:41:38.532] Looking for peers                        peercount=1 tried=94  static=0
INFO [04-27|14:41:38.748] Successfully sealed new block            number=396 sealhash=6f68f8…4dcbd7 hash=780799…503276 elapsed=3.703s
INFO [04-27|14:41:38.749] 🔗 block reached canonical chain          number=389 hash=cb37ca…15c80e
INFO [04-27|14:41:38.756] 🔨 mined potential block                  number=396 hash=780799…503276
INFO [04-27|14:41:38.756] Commit new mining work                   number=397 sealhash=410b9b…e8b99e uncles=0 txs=0 gas=0     fees=0        elapsed=8.941ms
INFO [04-27|14:41:48.534] Looking for peers                        peercount=1 tried=79  static=0
INFO [04-27|14:41:52.380] Successfully sealed new block            number=397 sealhash=410b9b…e8b99e hash=ae4162…c05fe9 elapsed=13.631s
INFO [04-27|14:41:52.380] 🔗 block reached canonical chain          number=390 hash=6322d0…bc7647
INFO [04-27|14:41:52.387] Commit new mining work                   number=398 sealhash=b8e0cc…5d276a uncles=0 txs=0 gas=0     fees=0        elapsed=6.946ms
INFO [04-27|14:41:52.387] 🔨 mined potential block                  number=397 hash=ae4162…c05fe9
INFO [04-27|14:41:56.084] Successfully sealed new block            number=398 sealhash=b8e0cc…5d276a hash=bd11d1…ff60f9 elapsed=3.704s
INFO [04-27|14:41:56.084] 🔗 block reached canonical chain          number=391 hash=44288a…c8a684
INFO [04-27|14:41:56.092] 🔨 mined potential block                  number=398 hash=bd11d1…ff60f9
INFO [04-27|14:41:56.092] Commit new mining work                   number=399 sealhash=0d1509…ee5b6c uncles=0 txs=0 gas=0     fees=0        elapsed=7.949ms
INFO [04-27|14:41:58.288] Successfully sealed new block            number=399 sealhash=0d1509…ee5b6c hash=a82edf…e38451 elapsed=2.204s
INFO [04-27|14:41:58.289] 🔗 block reached canonical chain          number=392 hash=e0e16f…896f88
INFO [04-27|14:41:58.296] 🔨 mined potential block                  number=399 hash=a82edf…e38451
INFO [04-27|14:41:58.296] Commit new mining work                   number=400 sealhash=ef7dc6…2f66ba uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:41:58.536] Looking for peers                        peercount=1 tried=106 static=0
INFO [04-27|14:42:05.384] Successfully sealed new block            number=400 sealhash=ef7dc6…2f66ba hash=bb087d…b39762 elapsed=7.095s
INFO [04-27|14:42:05.384] 🔗 block reached canonical chain          number=393 hash=685ef9…66e005
INFO [04-27|14:42:05.391] 🔨 mined potential block                  number=400 hash=bb087d…b39762
INFO [04-27|14:42:05.391] Commit new mining work                   number=401 sealhash=858f8e…8a2c68 uncles=0 txs=0 gas=0     fees=0        elapsed=6.946ms
INFO [04-27|14:42:08.642] Looking for peers                        peercount=1 tried=170 static=0
INFO [04-27|14:42:15.755] Successfully sealed new block            number=401 sealhash=858f8e…8a2c68 hash=ee9996…bd7873 elapsed=10.370s
INFO [04-27|14:42:15.756] 🔗 block reached canonical chain          number=394 hash=8d4204…b02988
INFO [04-27|14:42:15.764] 🔨 mined potential block                  number=401 hash=ee9996…bd7873
INFO [04-27|14:42:15.764] Commit new mining work                   number=402 sealhash=6cac3c…d72df8 uncles=0 txs=0 gas=0     fees=0        elapsed=8.946ms
INFO [04-27|14:42:17.792] Successfully sealed new block            number=402 sealhash=6cac3c…d72df8 hash=ff83de…ab2efd elapsed=2.036s
INFO [04-27|14:42:17.793] 🔗 block reached canonical chain          number=395 hash=d13cfc…e5afa2
INFO [04-27|14:42:17.800] 🔨 mined potential block                  number=402 hash=ff83de…ab2efd
INFO [04-27|14:42:17.800] Commit new mining work                   number=403 sealhash=f341d5…73c9cf uncles=0 txs=0 gas=0     fees=0        elapsed=7.948ms
INFO [04-27|14:42:19.007] Looking for peers                        peercount=1 tried=141 static=0
INFO [04-27|14:42:22.105] Successfully sealed new block            number=403 sealhash=f341d5…73c9cf hash=adec94…e2661d elapsed=4.311s
INFO [04-27|14:42:22.105] 🔗 block reached canonical chain          number=396 hash=780799…503276
INFO [04-27|14:42:22.113] Commit new mining work                   number=404 sealhash=9d1887…328b66 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:42:22.113] 🔨 mined potential block                  number=403 hash=adec94…e2661d
INFO [04-27|14:42:23.382] Successfully sealed new block            number=404 sealhash=9d1887…328b66 hash=9f1c0a…24b8c4 elapsed=1.277s
INFO [04-27|14:42:23.383] 🔗 block reached canonical chain          number=397 hash=ae4162…c05fe9
INFO [04-27|14:42:23.390] 🔨 mined potential block                  number=404 hash=9f1c0a…24b8c4
INFO [04-27|14:42:23.390] Commit new mining work                   number=405 sealhash=807dda…0db35f uncles=0 txs=0 gas=0     fees=0        elapsed=6.947ms
INFO [04-27|14:42:28.229] Successfully sealed new block            number=405 sealhash=807dda…0db35f hash=37028a…fdf0b1 elapsed=4.846s
INFO [04-27|14:42:28.229] 🔗 block reached canonical chain          number=398 hash=bd11d1…ff60f9
INFO [04-27|14:42:28.239] 🔨 mined potential block                  number=405 hash=37028a…fdf0b1
INFO [04-27|14:42:28.239] Commit new mining work                   number=406 sealhash=407615…0a5b81 uncles=0 txs=0 gas=0     fees=0        elapsed=9.939ms
INFO [04-27|14:42:29.098] Looking for peers                        peercount=1 tried=164 static=0
INFO [04-27|14:42:36.053] Successfully sealed new block            number=406 sealhash=407615…0a5b81 hash=23aaa6…a04a6f elapsed=7.824s
INFO [04-27|14:42:36.054] 🔗 block reached canonical chain          number=399 hash=a82edf…e38451
INFO [04-27|14:42:36.061] 🔨 mined potential block                  number=406 hash=23aaa6…a04a6f
INFO [04-27|14:42:36.061] Commit new mining work                   number=407 sealhash=c5f2cf…a43160 uncles=0 txs=0 gas=0     fees=0        elapsed=6.947ms
INFO [04-27|14:42:37.897] Successfully sealed new block            number=407 sealhash=c5f2cf…a43160 hash=cad6e4…2f7971 elapsed=1.842s
INFO [04-27|14:42:37.897] 🔗 block reached canonical chain          number=400 hash=bb087d…b39762
INFO [04-27|14:42:37.904] 🔨 mined potential block                  number=407 hash=cad6e4…2f7971
INFO [04-27|14:42:37.904] Commit new mining work                   number=408 sealhash=cfd85f…134a96 uncles=0 txs=0 gas=0     fees=0        elapsed=7.971ms
INFO [04-27|14:42:39.452] Successfully sealed new block            number=408 sealhash=cfd85f…134a96 hash=8dc4c4…aa72da elapsed=1.555s
INFO [04-27|14:42:39.452] 🔗 block reached canonical chain          number=401 hash=ee9996…bd7873
INFO [04-27|14:42:39.460] Commit new mining work                   number=409 sealhash=ff97ca…dcd402 uncles=0 txs=0 gas=0     fees=0        elapsed=7.972ms
INFO [04-27|14:42:39.460] 🔨 mined potential block                  number=408 hash=8dc4c4…aa72da
INFO [04-27|14:42:39.759] Looking for peers                        peercount=1 tried=152 static=0
INFO [04-27|14:42:44.209] Successfully sealed new block            number=409 sealhash=ff97ca…dcd402 hash=5523a7…67575c elapsed=4.756s
INFO [04-27|14:42:44.209] 🔗 block reached canonical chain          number=402 hash=ff83de…ab2efd
INFO [04-27|14:42:44.217] 🔨 mined potential block                  number=409 hash=5523a7…67575c
INFO [04-27|14:42:44.217] Commit new mining work                   number=410 sealhash=901d86…d96639 uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:42:45.008] Successfully sealed new block            number=410 sealhash=901d86…d96639 hash=a0e99d…1eb9ad elapsed=799.863ms
INFO [04-27|14:42:45.009] 🔗 block reached canonical chain          number=403 hash=adec94…e2661d
INFO [04-27|14:42:45.016] 🔨 mined potential block                  number=410 hash=a0e99d…1eb9ad
INFO [04-27|14:42:45.016] Commit new mining work                   number=411 sealhash=b703da…f7ea84 uncles=0 txs=0 gas=0     fees=0        elapsed=6.980ms
INFO [04-27|14:42:49.787] Looking for peers                        peercount=2 tried=49  static=0
INFO [04-27|14:42:50.874] Successfully sealed new block            number=411 sealhash=b703da…f7ea84 hash=c1a918…bc8645 elapsed=5.864s
INFO [04-27|14:42:50.875] 🔗 block reached canonical chain          number=404 hash=9f1c0a…24b8c4
INFO [04-27|14:42:50.882] 🔨 mined potential block                  number=411 hash=c1a918…bc8645
INFO [04-27|14:42:50.882] Commit new mining work                   number=412 sealhash=c3bd62…d5072e uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:42:51.755] Successfully sealed new block            number=412 sealhash=c3bd62…d5072e hash=edf669…daeda2 elapsed=880.679ms
INFO [04-27|14:42:51.755] 🔗 block reached canonical chain          number=405 hash=37028a…fdf0b1
INFO [04-27|14:42:51.762] Commit new mining work                   number=413 sealhash=633361…264d84 uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:42:51.762] 🔨 mined potential block                  number=412 hash=edf669…daeda2
INFO [04-27|14:42:54.856] Successfully sealed new block            number=413 sealhash=633361…264d84 hash=a581f1…3430b1 elapsed=3.100s
INFO [04-27|14:42:54.856] 🔗 block reached canonical chain          number=406 hash=23aaa6…a04a6f
INFO [04-27|14:42:54.865] 🔨 mined potential block                  number=413 hash=a581f1…3430b1
INFO [04-27|14:42:54.865] Commit new mining work                   number=414 sealhash=7fdc7a…a5755f uncles=0 txs=0 gas=0     fees=0        elapsed=8.967ms
INFO [04-27|14:42:55.231] Successfully sealed new block            number=414 sealhash=7fdc7a…a5755f hash=a9744f…97538a elapsed=374.996ms
INFO [04-27|14:42:55.232] 🔗 block reached canonical chain          number=407 hash=cad6e4…2f7971
INFO [04-27|14:42:55.240] 🔨 mined potential block                  number=414 hash=a9744f…97538a
INFO [04-27|14:42:55.240] Commit new mining work                   number=415 sealhash=b6d801…4e0214 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:42:57.538] Successfully sealed new block            number=415 sealhash=b6d801…4e0214 hash=026321…06e46a elapsed=2.305s
INFO [04-27|14:42:57.538] 🔗 block reached canonical chain          number=408 hash=8dc4c4…aa72da
INFO [04-27|14:42:57.547] Commit new mining work                   number=416 sealhash=9c1f3e…9f954f uncles=0 txs=0 gas=0     fees=0        elapsed=8.944ms
INFO [04-27|14:42:57.547] 🔨 mined potential block                  number=415 hash=026321…06e46a
INFO [04-27|14:42:58.927] Successfully sealed new block            number=416 sealhash=9c1f3e…9f954f hash=201785…3cd62a elapsed=1.389s
INFO [04-27|14:42:58.928] 🔗 block reached canonical chain          number=409 hash=5523a7…67575c
INFO [04-27|14:42:58.935] 🔨 mined potential block                  number=416 hash=201785…3cd62a
INFO [04-27|14:42:58.935] Commit new mining work                   number=417 sealhash=c4c32f…e1d5ce uncles=0 txs=0 gas=0     fees=0        elapsed=7.946ms
INFO [04-27|14:42:59.659] Successfully sealed new block            number=417 sealhash=c4c32f…e1d5ce hash=f55b62…9538bb elapsed=731.077ms
INFO [04-27|14:42:59.659] 🔗 block reached canonical chain          number=410 hash=a0e99d…1eb9ad
INFO [04-27|14:42:59.667] Commit new mining work                   number=418 sealhash=1b19d3…a7d932 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:42:59.667] 🔨 mined potential block                  number=417 hash=f55b62…9538bb
INFO [04-27|14:42:59.982] Looking for peers                        peercount=1 tried=111 static=0
INFO [04-27|14:43:07.742] Successfully sealed new block            number=418 sealhash=1b19d3…a7d932 hash=33d54e…242f55 elapsed=8.082s
INFO [04-27|14:43:07.742] 🔗 block reached canonical chain          number=411 hash=c1a918…bc8645
INFO [04-27|14:43:07.750] 🔨 mined potential block                  number=418 hash=33d54e…242f55
INFO [04-27|14:43:07.750] Commit new mining work                   number=419 sealhash=b9ee0e…e4c65c uncles=0 txs=0 gas=0     fees=0        elapsed=7.943ms
INFO [04-27|14:43:09.992] Looking for peers                        peercount=1 tried=81  static=0
INFO [04-27|14:43:10.812] Successfully sealed new block            number=419 sealhash=b9ee0e…e4c65c hash=cc9f70…73233a elapsed=3.069s
INFO [04-27|14:43:10.812] 🔗 block reached canonical chain          number=412 hash=edf669…daeda2
INFO [04-27|14:43:10.820] Commit new mining work                   number=420 sealhash=90e827…09b187 uncles=0 txs=0 gas=0     fees=0        elapsed=7.975ms
INFO [04-27|14:43:10.820] 🔨 mined potential block                  number=419 hash=cc9f70…73233a
INFO [04-27|14:43:12.586] Successfully sealed new block            number=420 sealhash=90e827…09b187 hash=e1c749…cbca59 elapsed=1.774s
INFO [04-27|14:43:12.587] 🔗 block reached canonical chain          number=413 hash=a581f1…3430b1
INFO [04-27|14:43:12.595] 🔨 mined potential block                  number=420 hash=e1c749…cbca59
INFO [04-27|14:43:12.595] Commit new mining work                   number=421 sealhash=f3d300…e073de uncles=0 txs=0 gas=0     fees=0        elapsed=8.968ms
INFO [04-27|14:43:13.680] Successfully sealed new block            number=421 sealhash=f3d300…e073de hash=deabf9…328cda elapsed=1.093s
INFO [04-27|14:43:13.680] 🔗 block reached canonical chain          number=414 hash=a9744f…97538a
INFO [04-27|14:43:13.687] 🔨 mined potential block                  number=421 hash=deabf9…328cda
INFO [04-27|14:43:13.687] Commit new mining work                   number=422 sealhash=07a6e0…dd3c91 uncles=0 txs=0 gas=0     fees=0        elapsed=6.947ms
INFO [04-27|14:43:16.619] Successfully sealed new block            number=422 sealhash=07a6e0…dd3c91 hash=096771…d7c112 elapsed=2.939s
INFO [04-27|14:43:16.619] 🔗 block reached canonical chain          number=415 hash=026321…06e46a
INFO [04-27|14:43:16.626] 🔨 mined potential block                  number=422 hash=096771…d7c112
INFO [04-27|14:43:16.626] Commit new mining work                   number=423 sealhash=011e0f…325ef2 uncles=0 txs=0 gas=0     fees=0        elapsed=6.980ms
INFO [04-27|14:43:20.037] Looking for peers                        peercount=1 tried=58  static=0
INFO [04-27|14:43:24.011] Successfully sealed new block            number=423 sealhash=011e0f…325ef2 hash=f3d039…88a038 elapsed=7.391s
INFO [04-27|14:43:24.011] 🔗 block reached canonical chain          number=416 hash=201785…3cd62a
INFO [04-27|14:43:24.019] 🔨 mined potential block                  number=423 hash=f3d039…88a038
INFO [04-27|14:43:24.019] Commit new mining work                   number=424 sealhash=755d6a…4d8f69 uncles=0 txs=0 gas=0     fees=0        elapsed=7.977ms
INFO [04-27|14:43:24.819] Successfully sealed new block            number=424 sealhash=755d6a…4d8f69 hash=9c62b9…717ca4 elapsed=808.869ms
INFO [04-27|14:43:24.819] 🔗 block reached canonical chain          number=417 hash=f55b62…9538bb
INFO [04-27|14:43:24.826] Commit new mining work                   number=425 sealhash=7f1e1b…1f9f0b uncles=0 txs=0 gas=0     fees=0        elapsed=6.947ms
INFO [04-27|14:43:24.826] 🔨 mined potential block                  number=424 hash=9c62b9…717ca4
INFO [04-27|14:43:30.037] Looking for peers                        peercount=1 tried=58  static=0
INFO [04-27|14:43:36.746] Successfully sealed new block            number=425 sealhash=7f1e1b…1f9f0b hash=a70052…d93412 elapsed=11.927s
INFO [04-27|14:43:36.746] 🔗 block reached canonical chain          number=418 hash=33d54e…242f55
INFO [04-27|14:43:36.753] 🔨 mined potential block                  number=425 hash=a70052…d93412
INFO [04-27|14:43:36.753] Commit new mining work                   number=426 sealhash=2d6942…47b083 uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:43:40.077] Looking for peers                        peercount=1 tried=66  static=0
INFO [04-27|14:43:45.674] Successfully sealed new block            number=426 sealhash=2d6942…47b083 hash=d90755…e6588b elapsed=8.927s
INFO [04-27|14:43:45.675] 🔗 block reached canonical chain          number=419 hash=cc9f70…73233a
INFO [04-27|14:43:45.682] Commit new mining work                   number=427 sealhash=43ce6c…2a37e6 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:43:45.682] 🔨 mined potential block                  number=426 hash=d90755…e6588b
INFO [04-27|14:43:48.598] Successfully sealed new block            number=427 sealhash=43ce6c…2a37e6 hash=a27bba…ea3a57 elapsed=2.923s
INFO [04-27|14:43:48.599] 🔗 block reached canonical chain          number=420 hash=e1c749…cbca59
INFO [04-27|14:43:48.606] Commit new mining work                   number=428 sealhash=56ae71…2a267e uncles=0 txs=0 gas=0     fees=0        elapsed=7.943ms
INFO [04-27|14:43:48.606] 🔨 mined potential block                  number=427 hash=a27bba…ea3a57
INFO [04-27|14:43:48.704] Successfully sealed new block            number=428 sealhash=56ae71…2a267e hash=6349c6…70d606 elapsed=104.708ms
INFO [04-27|14:43:48.704] 🔗 block reached canonical chain          number=421 hash=deabf9…328cda
INFO [04-27|14:43:48.711] Commit new mining work                   number=429 sealhash=68a8e4…30b5ac uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:43:48.711] 🔨 mined potential block                  number=428 hash=6349c6…70d606
INFO [04-27|14:43:50.102] Looking for peers                        peercount=1 tried=40  static=0
INFO [04-27|14:43:55.316] Successfully sealed new block            number=429 sealhash=68a8e4…30b5ac hash=89085d…0899bd elapsed=6.612s
INFO [04-27|14:43:55.316] 🔗 block reached canonical chain          number=422 hash=096771…d7c112
INFO [04-27|14:43:55.325] 🔨 mined potential block                  number=429 hash=89085d…0899bd
INFO [04-27|14:43:55.325] Commit new mining work                   number=430 sealhash=7c8a2a…7cfea1 uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:44:00.111] Looking for peers                        peercount=2 tried=47  static=0
INFO [04-27|14:44:01.436] Successfully sealed new block            number=430 sealhash=7c8a2a…7cfea1 hash=011c23…338014 elapsed=6.120s
INFO [04-27|14:44:01.436] 🔗 block reached canonical chain          number=423 hash=f3d039…88a038
INFO [04-27|14:44:01.446] 🔨 mined potential block                  number=430 hash=011c23…338014
INFO [04-27|14:44:01.446] Commit new mining work                   number=431 sealhash=a1b6c0…c9302b uncles=0 txs=0 gas=0     fees=0        elapsed=9.940ms
INFO [04-27|14:44:09.330] Successfully sealed new block            number=431 sealhash=a1b6c0…c9302b hash=4f5969…c336cc elapsed=7.893s
INFO [04-27|14:44:09.330] 🔗 block reached canonical chain          number=424 hash=9c62b9…717ca4
INFO [04-27|14:44:09.337] 🔨 mined potential block                  number=431 hash=4f5969…c336cc
INFO [04-27|14:44:09.337] Commit new mining work                   number=432 sealhash=334043…674c19 uncles=0 txs=0 gas=0     fees=0        elapsed=6.944ms
INFO [04-27|14:44:10.269] Looking for peers                        peercount=2 tried=55  static=0
INFO [04-27|14:44:20.306] Looking for peers                        peercount=2 tried=43  static=0
INFO [04-27|14:44:23.823] Successfully sealed new block            number=432 sealhash=334043…674c19 hash=2223ae…a70766 elapsed=14.492s
INFO [04-27|14:44:23.823] 🔗 block reached canonical chain          number=425 hash=a70052…d93412
INFO [04-27|14:44:23.831] Commit new mining work                   number=433 sealhash=7f44fc…b12484 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:44:23.831] 🔨 mined potential block                  number=432 hash=2223ae…a70766
INFO [04-27|14:44:24.330] Successfully sealed new block            number=433 sealhash=7f44fc…b12484 hash=e978ad…ae64fa elapsed=507.608ms
INFO [04-27|14:44:24.330] 🔗 block reached canonical chain          number=426 hash=d90755…e6588b
INFO [04-27|14:44:24.337] 🔨 mined potential block                  number=433 hash=e978ad…ae64fa
INFO [04-27|14:44:24.337] Commit new mining work                   number=434 sealhash=c7f1e0…6900d0 uncles=0 txs=0 gas=0     fees=0        elapsed=6.982ms
INFO [04-27|14:44:27.302] Successfully sealed new block            number=434 sealhash=c7f1e0…6900d0 hash=a2fe68…f1497a elapsed=2.972s
INFO [04-27|14:44:27.302] 🔗 block reached canonical chain          number=427 hash=a27bba…ea3a57
INFO [04-27|14:44:27.310] 🔨 mined potential block                  number=434 hash=a2fe68…f1497a
INFO [04-27|14:44:27.310] Commit new mining work                   number=435 sealhash=546e49…1fd818 uncles=0 txs=0 gas=0     fees=0        elapsed=7.943ms
INFO [04-27|14:44:28.261] Successfully sealed new block            number=435 sealhash=546e49…1fd818 hash=18b5bb…70c367 elapsed=958.436ms
INFO [04-27|14:44:28.261] 🔗 block reached canonical chain          number=428 hash=6349c6…70d606
INFO [04-27|14:44:28.271] 🔨 mined potential block                  number=435 hash=18b5bb…70c367
INFO [04-27|14:44:28.271] Commit new mining work                   number=436 sealhash=3a6a6d…ad79a0 uncles=0 txs=0 gas=0     fees=0        elapsed=9.937ms
INFO [04-27|14:44:30.410] Looking for peers                        peercount=1 tried=62  static=0
INFO [04-27|14:44:34.471] Successfully sealed new block            number=436 sealhash=3a6a6d…ad79a0 hash=0314fb…55563d elapsed=6.210s
INFO [04-27|14:44:34.471] 🔗 block reached canonical chain          number=429 hash=89085d…0899bd
INFO [04-27|14:44:34.480] 🔨 mined potential block                  number=436 hash=0314fb…55563d
INFO [04-27|14:44:34.480] Commit new mining work                   number=437 sealhash=c20cfc…73a5c1 uncles=0 txs=0 gas=0     fees=0        elapsed=8.940ms
INFO [04-27|14:44:36.469] Successfully sealed new block            number=437 sealhash=c20cfc…73a5c1 hash=da33cd…fdc1dc elapsed=1.997s
INFO [04-27|14:44:36.469] 🔗 block reached canonical chain          number=430 hash=011c23…338014
INFO [04-27|14:44:36.476] Commit new mining work                   number=438 sealhash=df0d17…6cd063 uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:44:36.476] 🔨 mined potential block                  number=437 hash=da33cd…fdc1dc
INFO [04-27|14:44:40.410] Looking for peers                        peercount=1 tried=66  static=0
INFO [04-27|14:44:47.486] Successfully sealed new block            number=438 sealhash=df0d17…6cd063 hash=a63730…403770 elapsed=11.017s
INFO [04-27|14:44:47.486] 🔗 block reached canonical chain          number=431 hash=4f5969…c336cc
INFO [04-27|14:44:47.495] 🔨 mined potential block                  number=438 hash=a63730…403770
INFO [04-27|14:44:47.495] Commit new mining work                   number=439 sealhash=134cee…89679f uncles=0 txs=0 gas=0     fees=0        elapsed=8.968ms
INFO [04-27|14:44:50.411] Looking for peers                        peercount=1 tried=43  static=0
INFO [04-27|14:45:00.474] Looking for peers                        peercount=1 tried=113 static=0
INFO [04-27|14:45:10.497] Looking for peers                        peercount=1 tried=79  static=0
INFO [04-27|14:45:10.623] Successfully sealed new block            number=439 sealhash=134cee…89679f hash=6c0603…054c0b elapsed=23.136s
INFO [04-27|14:45:10.623] 🔗 block reached canonical chain          number=432 hash=2223ae…a70766
INFO [04-27|14:45:10.629] 🔨 mined potential block                  number=439 hash=6c0603…054c0b
INFO [04-27|14:45:10.629] Commit new mining work                   number=440 sealhash=e1b500…e721e0 uncles=0 txs=0 gas=0     fees=0        elapsed=6.976ms
INFO [04-27|14:45:13.339] Successfully sealed new block            number=440 sealhash=e1b500…e721e0 hash=6c479e…e02124 elapsed=2.716s
INFO [04-27|14:45:13.340] 🔗 block reached canonical chain          number=433 hash=e978ad…ae64fa
INFO [04-27|14:45:13.349] 🔨 mined potential block                  number=440 hash=6c479e…e02124
INFO [04-27|14:45:13.349] Commit new mining work                   number=441 sealhash=bb3201…d067ab uncles=0 txs=0 gas=0     fees=0        elapsed=8.996ms
INFO [04-27|14:45:13.458] Successfully sealed new block            number=441 sealhash=bb3201…d067ab hash=1e1b55…31fd0a elapsed=117.719ms
INFO [04-27|14:45:13.459] 🔗 block reached canonical chain          number=434 hash=a2fe68…f1497a
INFO [04-27|14:45:13.466] Commit new mining work                   number=442 sealhash=63d8ff…420e5c uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:45:13.466] 🔨 mined potential block                  number=441 hash=1e1b55…31fd0a
INFO [04-27|14:45:20.739] Looking for peers                        peercount=1 tried=77  static=0
INFO [04-27|14:45:24.446] Successfully sealed new block            number=442 sealhash=63d8ff…420e5c hash=e1963e…6aa533 elapsed=10.986s
INFO [04-27|14:45:24.446] 🔗 block reached canonical chain          number=435 hash=18b5bb…70c367
INFO [04-27|14:45:24.453] 🔨 mined potential block                  number=442 hash=e1963e…6aa533
INFO [04-27|14:45:24.453] Commit new mining work                   number=443 sealhash=0e4255…7aa394 uncles=0 txs=0 gas=0     fees=0        elapsed=6.977ms
INFO [04-27|14:45:28.257] Successfully sealed new block            number=443 sealhash=0e4255…7aa394 hash=a548d0…e25f1b elapsed=3.811s
INFO [04-27|14:45:28.257] 🔗 block reached canonical chain          number=436 hash=0314fb…55563d
INFO [04-27|14:45:28.265] 🔨 mined potential block                  number=443 hash=a548d0…e25f1b
INFO [04-27|14:45:28.265] Commit new mining work                   number=444 sealhash=cdcc90…c84da1 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:45:28.510] Successfully sealed new block            number=444 sealhash=cdcc90…c84da1 hash=bdf0a7…c29a3c elapsed=252.324ms
INFO [04-27|14:45:28.510] 🔗 block reached canonical chain          number=437 hash=da33cd…fdc1dc
INFO [04-27|14:45:28.518] 🔨 mined potential block                  number=444 hash=bdf0a7…c29a3c
INFO [04-27|14:45:28.518] Commit new mining work                   number=445 sealhash=d4823d…fac934 uncles=0 txs=0 gas=0     fees=0        elapsed=7.975ms
INFO [04-27|14:45:30.744] Looking for peers                        peercount=2 tried=177 static=0
INFO [04-27|14:45:34.299] Successfully sealed new block            number=445 sealhash=d4823d…fac934 hash=ab5b66…d0fd99 elapsed=5.789s
INFO [04-27|14:45:34.299] 🔗 block reached canonical chain          number=438 hash=a63730…403770
INFO [04-27|14:45:34.308] Commit new mining work                   number=446 sealhash=0905f6…d197ef uncles=0 txs=0 gas=0     fees=0        elapsed=9.008ms
INFO [04-27|14:45:34.308] 🔨 mined potential block                  number=445 hash=ab5b66…d0fd99
INFO [04-27|14:45:38.361] Successfully sealed new block            number=446 sealhash=0905f6…d197ef hash=7324bd…27387f elapsed=4.062s
INFO [04-27|14:45:38.362] 🔗 block reached canonical chain          number=439 hash=6c0603…054c0b
INFO [04-27|14:45:38.369] 🔨 mined potential block                  number=446 hash=7324bd…27387f
INFO [04-27|14:45:38.369] Commit new mining work                   number=447 sealhash=2b8ea8…ae783e uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:45:40.776] Looking for peers                        peercount=1 tried=155 static=0
INFO [04-27|14:45:43.202] Successfully sealed new block            number=447 sealhash=2b8ea8…ae783e hash=03891f…b80e62 elapsed=4.841s
INFO [04-27|14:45:43.202] 🔗 block reached canonical chain          number=440 hash=6c479e…e02124
INFO [04-27|14:45:43.210] Commit new mining work                   number=448 sealhash=6ead55…3fb710 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:45:43.210] 🔨 mined potential block                  number=447 hash=03891f…b80e62
INFO [04-27|14:45:50.777] Looking for peers                        peercount=1 tried=157 static=0
INFO [04-27|14:45:51.275] Successfully sealed new block            number=448 sealhash=6ead55…3fb710 hash=c8d83d…060e39 elapsed=8.072s
INFO [04-27|14:45:51.276] 🔗 block reached canonical chain          number=441 hash=1e1b55…31fd0a
INFO [04-27|14:45:51.283] 🔨 mined potential block                  number=448 hash=c8d83d…060e39
INFO [04-27|14:45:51.283] Commit new mining work                   number=449 sealhash=9e69a9…4a22bb uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:45:53.912] Successfully sealed new block            number=449 sealhash=9e69a9…4a22bb hash=a83a25…d77583 elapsed=2.636s
INFO [04-27|14:45:53.912] 🔗 block reached canonical chain          number=442 hash=e1963e…6aa533
INFO [04-27|14:45:53.919] 🔨 mined potential block                  number=449 hash=a83a25…d77583
INFO [04-27|14:45:53.919] Commit new mining work                   number=450 sealhash=f7a78d…91948b uncles=0 txs=0 gas=0     fees=0        elapsed=6.948ms
INFO [04-27|14:45:57.614] Successfully sealed new block            number=450 sealhash=f7a78d…91948b hash=9d0656…caa6c2 elapsed=3.702s
INFO [04-27|14:45:57.615] 🔗 block reached canonical chain          number=443 hash=a548d0…e25f1b
INFO [04-27|14:45:57.624] 🔨 mined potential block                  number=450 hash=9d0656…caa6c2
INFO [04-27|14:45:57.624] Commit new mining work                   number=451 sealhash=6dd8b3…0c1266 uncles=0 txs=0 gas=0     fees=0        elapsed=9.940ms
INFO [04-27|14:46:00.788] Looking for peers                        peercount=1 tried=120 static=0
INFO [04-27|14:46:04.939] Successfully sealed new block            number=451 sealhash=6dd8b3…0c1266 hash=766c85…04e60a elapsed=7.324s
INFO [04-27|14:46:04.939] 🔗 block reached canonical chain          number=444 hash=bdf0a7…c29a3c
INFO [04-27|14:46:04.947] 🔨 mined potential block                  number=451 hash=766c85…04e60a
INFO [04-27|14:46:04.947] Commit new mining work                   number=452 sealhash=40b5e3…eeaf82 uncles=0 txs=0 gas=0     fees=0        elapsed=7.973ms
INFO [04-27|14:46:10.805] Looking for peers                        peercount=1 tried=107 static=0
INFO [04-27|14:46:14.532] Successfully sealed new block            number=452 sealhash=40b5e3…eeaf82 hash=917d4c…d64ed6 elapsed=9.592s
INFO [04-27|14:46:14.533] 🔗 block reached canonical chain          number=445 hash=ab5b66…d0fd99
INFO [04-27|14:46:14.540] Commit new mining work                   number=453 sealhash=200e0f…54c511 uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:46:14.540] 🔨 mined potential block                  number=452 hash=917d4c…d64ed6
INFO [04-27|14:46:19.819] Successfully sealed new block            number=453 sealhash=200e0f…54c511 hash=0dee95…f7dfef elapsed=5.285s
INFO [04-27|14:46:19.819] 🔗 block reached canonical chain          number=446 hash=7324bd…27387f
INFO [04-27|14:46:19.827] 🔨 mined potential block                  number=453 hash=0dee95…f7dfef
INFO [04-27|14:46:19.827] Commit new mining work                   number=454 sealhash=a690f7…e850b2 uncles=0 txs=0 gas=0     fees=0        elapsed=8.975ms
INFO [04-27|14:46:20.854] Looking for peers                        peercount=1 tried=101 static=0
INFO [04-27|14:46:27.851] Successfully sealed new block            number=454 sealhash=a690f7…e850b2 hash=de53ff…51c94f elapsed=8.032s
INFO [04-27|14:46:27.851] 🔗 block reached canonical chain          number=447 hash=03891f…b80e62
INFO [04-27|14:46:27.858] 🔨 mined potential block                  number=454 hash=de53ff…51c94f
INFO [04-27|14:46:27.858] Commit new mining work                   number=455 sealhash=a2cb88…6b1727 uncles=0 txs=0 gas=0     fees=0        elapsed=6.980ms
INFO [04-27|14:46:30.865] Looking for peers                        peercount=2 tried=133 static=0
INFO [04-27|14:46:37.167] Successfully sealed new block            number=455 sealhash=a2cb88…6b1727 hash=668d4b…ec40e2 elapsed=9.316s
INFO [04-27|14:46:37.167] 🔗 block reached canonical chain          number=448 hash=c8d83d…060e39
INFO [04-27|14:46:37.175] 🔨 mined potential block                  number=455 hash=668d4b…ec40e2
INFO [04-27|14:46:37.175] Commit new mining work                   number=456 sealhash=b6cc93…cbc0da uncles=0 txs=0 gas=0     fees=0        elapsed=7.976ms
INFO [04-27|14:46:39.039] Successfully sealed new block            number=456 sealhash=b6cc93…cbc0da hash=2c1e7a…757cee elapsed=1.872s
INFO [04-27|14:46:39.039] 🔗 block reached canonical chain          number=449 hash=a83a25…d77583
INFO [04-27|14:46:39.047] Commit new mining work                   number=457 sealhash=845595…434551 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:46:39.047] 🔨 mined potential block                  number=456 hash=2c1e7a…757cee
INFO [04-27|14:46:40.846] Successfully sealed new block            number=457 sealhash=845595…434551 hash=ad3e37…37267f elapsed=1.807s
INFO [04-27|14:46:40.846] 🔗 block reached canonical chain          number=450 hash=9d0656…caa6c2
INFO [04-27|14:46:40.854] 🔨 mined potential block                  number=457 hash=ad3e37…37267f
INFO [04-27|14:46:40.854] Commit new mining work                   number=458 sealhash=f0032b…2e1bb6 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:46:40.903] Looking for peers                        peercount=1 tried=77  static=0
INFO [04-27|14:46:41.347] Successfully sealed new block            number=458 sealhash=f0032b…2e1bb6 hash=1b102c…1b7c14 elapsed=500.693ms
INFO [04-27|14:46:41.348] 🔗 block reached canonical chain          number=451 hash=766c85…04e60a
INFO [04-27|14:46:41.355] 🔨 mined potential block                  number=458 hash=1b102c…1b7c14
INFO [04-27|14:46:41.355] Commit new mining work                   number=459 sealhash=64fdd4…cc71d7 uncles=0 txs=0 gas=0     fees=0        elapsed=7.972ms
INFO [04-27|14:46:50.160] Successfully sealed new block            number=459 sealhash=64fdd4…cc71d7 hash=668733…72f1ce elapsed=8.811s
INFO [04-27|14:46:50.160] 🔗 block reached canonical chain          number=452 hash=917d4c…d64ed6
INFO [04-27|14:46:50.169] 🔨 mined potential block                  number=459 hash=668733…72f1ce
INFO [04-27|14:46:50.169] Commit new mining work                   number=460 sealhash=c44f54…4aa64d uncles=0 txs=0 gas=0     fees=0        elapsed=9.941ms
INFO [04-27|14:46:51.039] Looking for peers                        peercount=1 tried=66  static=0
INFO [04-27|14:46:51.851] Successfully sealed new block            number=460 sealhash=c44f54…4aa64d hash=562d9d…89e3a3 elapsed=1.691s
INFO [04-27|14:46:51.851] 🔗 block reached canonical chain          number=453 hash=0dee95…f7dfef
INFO [04-27|14:46:51.859] Commit new mining work                   number=461 sealhash=5ae999…a75f3a uncles=0 txs=0 gas=0     fees=0        elapsed=7.923ms
INFO [04-27|14:46:51.859] 🔨 mined potential block                  number=460 hash=562d9d…89e3a3
INFO [04-27|14:46:52.536] Successfully sealed new block            number=461 sealhash=5ae999…a75f3a hash=795dc2…d5d9e3 elapsed=685.112ms
INFO [04-27|14:46:52.537] 🔗 block reached canonical chain          number=454 hash=de53ff…51c94f
INFO [04-27|14:46:52.544] 🔨 mined potential block                  number=461 hash=795dc2…d5d9e3
INFO [04-27|14:46:52.544] Commit new mining work                   number=462 sealhash=b5f6de…f425e2 uncles=0 txs=0 gas=0     fees=0        elapsed=6.980ms
INFO [04-27|14:46:52.801] Successfully sealed new block            number=462 sealhash=b5f6de…f425e2 hash=a1782f…21d6e8 elapsed=264.325ms
INFO [04-27|14:46:52.801] 🔗 block reached canonical chain          number=455 hash=668d4b…ec40e2
INFO [04-27|14:46:52.808] 🔨 mined potential block                  number=462 hash=a1782f…21d6e8
INFO [04-27|14:46:52.808] Commit new mining work                   number=463 sealhash=67eab5…a27ab1 uncles=0 txs=0 gas=0     fees=0        elapsed=6.949ms
INFO [04-27|14:46:54.184] Successfully sealed new block            number=463 sealhash=67eab5…a27ab1 hash=1610c5…8e63cc elapsed=1.382s
INFO [04-27|14:46:54.185] 🔗 block reached canonical chain          number=456 hash=2c1e7a…757cee
INFO [04-27|14:46:54.192] 🔨 mined potential block                  number=463 hash=1610c5…8e63cc
INFO [04-27|14:46:54.192] Commit new mining work                   number=464 sealhash=3a168f…87e37b uncles=0 txs=0 gas=0     fees=0        elapsed=6.976ms
INFO [04-27|14:47:01.237] Looking for peers                        peercount=2 tried=90  static=0
INFO [04-27|14:47:02.237] Successfully sealed new block            number=464 sealhash=3a168f…87e37b hash=50258b…a2bff1 elapsed=8.052s
INFO [04-27|14:47:02.237] 🔗 block reached canonical chain          number=457 hash=ad3e37…37267f
INFO [04-27|14:47:02.245] 🔨 mined potential block                  number=464 hash=50258b…a2bff1
INFO [04-27|14:47:02.245] Commit new mining work                   number=465 sealhash=0e4d28…3ca781 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:47:05.774] Successfully sealed new block            number=465 sealhash=0e4d28…3ca781 hash=cfdc68…0cf0bd elapsed=3.536s
INFO [04-27|14:47:05.774] 🔗 block reached canonical chain          number=458 hash=1b102c…1b7c14
INFO [04-27|14:47:05.782] 🔨 mined potential block                  number=465 hash=cfdc68…0cf0bd
INFO [04-27|14:47:05.782] Commit new mining work                   number=466 sealhash=dbe2a9…e96387 uncles=0 txs=0 gas=0     fees=0        elapsed=7.972ms
INFO [04-27|14:47:12.669] Looking for peers                        peercount=1 tried=73  static=0
INFO [04-27|14:47:14.588] Successfully sealed new block            number=466 sealhash=dbe2a9…e96387 hash=70189c…ea1a60 elapsed=8.814s
INFO [04-27|14:47:14.588] 🔗 block reached canonical chain          number=459 hash=668733…72f1ce
INFO [04-27|14:47:14.595] Commit new mining work                   number=467 sealhash=14adde…c1734b uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:47:14.595] 🔨 mined potential block                  number=466 hash=70189c…ea1a60
INFO [04-27|14:47:15.118] Successfully sealed new block            number=467 sealhash=14adde…c1734b hash=5cb516…2299c0 elapsed=529.617ms
INFO [04-27|14:47:15.118] 🔗 block reached canonical chain          number=460 hash=562d9d…89e3a3
INFO [04-27|14:47:15.126] 🔨 mined potential block                  number=467 hash=5cb516…2299c0
INFO [04-27|14:47:15.126] Commit new mining work                   number=468 sealhash=e0853e…291bd1 uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:47:16.790] Successfully sealed new block            number=468 sealhash=e0853e…291bd1 hash=f502f0…84e93f elapsed=1.672s
INFO [04-27|14:47:16.790] 🔗 block reached canonical chain          number=461 hash=795dc2…d5d9e3
INFO [04-27|14:47:16.797] 🔨 mined potential block                  number=468 hash=f502f0…84e93f
INFO [04-27|14:47:16.797] Commit new mining work                   number=469 sealhash=b9e719…f19ff1 uncles=0 txs=0 gas=0     fees=0        elapsed=6.948ms
INFO [04-27|14:47:19.344] Successfully sealed new block            number=469 sealhash=b9e719…f19ff1 hash=39dcf7…274d26 elapsed=2.554s
INFO [04-27|14:47:19.344] 🔗 block reached canonical chain          number=462 hash=a1782f…21d6e8
INFO [04-27|14:47:19.352] Commit new mining work                   number=470 sealhash=11e0a4…bdfe65 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:47:19.352] 🔨 mined potential block                  number=469 hash=39dcf7…274d26
INFO [04-27|14:47:22.647] Successfully sealed new block            number=470 sealhash=11e0a4…bdfe65 hash=5dcca5…a1894e elapsed=3.302s
INFO [04-27|14:47:22.647] 🔗 block reached canonical chain          number=463 hash=1610c5…8e63cc
INFO [04-27|14:47:22.656] 🔨 mined potential block                  number=470 hash=5dcca5…a1894e
INFO [04-27|14:47:22.656] Commit new mining work                   number=471 sealhash=75982c…33bffe uncles=0 txs=0 gas=0     fees=0        elapsed=8.970ms
INFO [04-27|14:47:22.733] Looking for peers                        peercount=1 tried=96  static=0
INFO [04-27|14:47:24.093] Successfully sealed new block            number=471 sealhash=75982c…33bffe hash=b5dc85…79e042 elapsed=1.446s
INFO [04-27|14:47:24.093] 🔗 block reached canonical chain          number=464 hash=50258b…a2bff1
INFO [04-27|14:47:24.101] 🔨 mined potential block                  number=471 hash=b5dc85…79e042
INFO [04-27|14:47:24.101] Commit new mining work                   number=472 sealhash=374164…9de320 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:47:32.737] Looking for peers                        peercount=1 tried=63  static=0
INFO [04-27|14:47:42.797] Looking for peers                        peercount=1 tried=51  static=0
INFO [04-27|14:47:48.030] Successfully sealed new block            number=472 sealhash=374164…9de320 hash=880a12…6eac18 elapsed=23.937s
INFO [04-27|14:47:48.030] 🔗 block reached canonical chain          number=465 hash=cfdc68…0cf0bd
INFO [04-27|14:47:48.039] 🔨 mined potential block                  number=472 hash=880a12…6eac18
INFO [04-27|14:47:48.039] Commit new mining work                   number=473 sealhash=acc559…4ea058 uncles=0 txs=0 gas=0     fees=0        elapsed=8.949ms
INFO [04-27|14:47:49.839] Successfully sealed new block            number=473 sealhash=acc559…4ea058 hash=036309…9f18cb elapsed=1.809s
INFO [04-27|14:47:49.839] 🔗 block reached canonical chain          number=466 hash=70189c…ea1a60
INFO [04-27|14:47:49.847] Commit new mining work                   number=474 sealhash=8207a7…fc6fa6 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:47:49.847] 🔨 mined potential block                  number=473 hash=036309…9f18cb
INFO [04-27|14:47:52.826] Looking for peers                        peercount=2 tried=81  static=0
INFO [04-27|14:47:57.696] Successfully sealed new block            number=474 sealhash=8207a7…fc6fa6 hash=fbdd5b…d1368b elapsed=7.857s
INFO [04-27|14:47:57.696] 🔗 block reached canonical chain          number=467 hash=5cb516…2299c0
INFO [04-27|14:47:57.703] 🔨 mined potential block                  number=474 hash=fbdd5b…d1368b
INFO [04-27|14:47:57.703] Commit new mining work                   number=475 sealhash=457f79…061e86 uncles=0 txs=0 gas=0     fees=0        elapsed=6.950ms
INFO [04-27|14:47:58.519] Successfully sealed new block            number=475 sealhash=457f79…061e86 hash=85f60d…d8db3e elapsed=822.768ms
INFO [04-27|14:47:58.519] 🔗 block reached canonical chain          number=468 hash=f502f0…84e93f
INFO [04-27|14:47:58.527] 🔨 mined potential block                  number=475 hash=85f60d…d8db3e
INFO [04-27|14:47:58.527] Commit new mining work                   number=476 sealhash=c64118…5cdf85 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:47:58.815] Successfully sealed new block            number=476 sealhash=c64118…5cdf85 hash=a570fe…319fda elapsed=296.207ms
INFO [04-27|14:47:58.815] 🔗 block reached canonical chain          number=469 hash=39dcf7…274d26
INFO [04-27|14:47:58.823] 🔨 mined potential block                  number=476 hash=a570fe…319fda
INFO [04-27|14:47:58.823] Commit new mining work                   number=477 sealhash=ebbca6…c745c6 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:48:02.930] Looking for peers                        peercount=1 tried=52  static=0
INFO [04-27|14:48:04.367] Successfully sealed new block            number=477 sealhash=ebbca6…c745c6 hash=e1323d…a554ba elapsed=5.552s
INFO [04-27|14:48:04.367] 🔗 block reached canonical chain          number=470 hash=5dcca5…a1894e
INFO [04-27|14:48:04.374] Commit new mining work                   number=478 sealhash=e7db2f…09d0da uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:48:04.375] 🔨 mined potential block                  number=477 hash=e1323d…a554ba
INFO [04-27|14:48:13.003] Looking for peers                        peercount=2 tried=58  static=0
INFO [04-27|14:48:21.596] Successfully sealed new block            number=478 sealhash=e7db2f…09d0da hash=304bda…828246 elapsed=17.228s
INFO [04-27|14:48:21.597] 🔗 block reached canonical chain          number=471 hash=b5dc85…79e042
INFO [04-27|14:48:21.606] 🔨 mined potential block                  number=478 hash=304bda…828246
INFO [04-27|14:48:21.606] Commit new mining work                   number=479 sealhash=45d48d…fe4430 uncles=0 txs=0 gas=0     fees=0        elapsed=8.942ms
INFO [04-27|14:48:23.066] Looking for peers                        peercount=2 tried=51  static=0
INFO [04-27|14:48:33.066] Looking for peers                        peercount=1 tried=48  static=0
INFO [04-27|14:48:38.790] Successfully sealed new block            number=479 sealhash=45d48d…fe4430 hash=4ce67c…259afb elapsed=17.193s
INFO [04-27|14:48:38.790] 🔗 block reached canonical chain          number=472 hash=880a12…6eac18
INFO [04-27|14:48:38.798] 🔨 mined potential block                  number=479 hash=4ce67c…259afb
INFO [04-27|14:48:38.798] Commit new mining work                   number=480 sealhash=efbd44…ccce0b uncles=0 txs=0 gas=0     fees=0        elapsed=7.946ms
INFO [04-27|14:48:43.209] Looking for peers                        peercount=1 tried=50  static=0
INFO [04-27|14:48:45.065] Successfully sealed new block            number=480 sealhash=efbd44…ccce0b hash=c8874b…ec22e6 elapsed=6.275s
INFO [04-27|14:48:45.065] 🔗 block reached canonical chain          number=473 hash=036309…9f18cb
INFO [04-27|14:48:45.073] 🔨 mined potential block                  number=480 hash=c8874b…ec22e6
INFO [04-27|14:48:45.073] Commit new mining work                   number=481 sealhash=0ca42f…8f5c41 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:48:53.279] Looking for peers                        peercount=2 tried=65  static=0
INFO [04-27|14:49:03.400] Looking for peers                        peercount=1 tried=40  static=0
INFO [04-27|14:49:09.212] Successfully sealed new block            number=481 sealhash=0ca42f…8f5c41 hash=b6590d…a2e091 elapsed=24.146s
INFO [04-27|14:49:09.213] 🔗 block reached canonical chain          number=474 hash=fbdd5b…d1368b
INFO [04-27|14:49:09.220] Commit new mining work                   number=482 sealhash=11550b…40402d uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:49:09.220] 🔨 mined potential block                  number=481 hash=b6590d…a2e091
INFO [04-27|14:49:13.076] Successfully sealed new block            number=482 sealhash=11550b…40402d hash=d8df27…ae3ada elapsed=3.863s
INFO [04-27|14:49:13.076] 🔗 block reached canonical chain          number=475 hash=85f60d…d8db3e
INFO [04-27|14:49:13.084] 🔨 mined potential block                  number=482 hash=d8df27…ae3ada
INFO [04-27|14:49:13.084] Commit new mining work                   number=483 sealhash=80807b…140bd6 uncles=0 txs=0 gas=0     fees=0        elapsed=7.955ms
INFO [04-27|14:49:13.400] Looking for peers                        peercount=1 tried=83  static=0
INFO [04-27|14:49:22.778] Successfully sealed new block            number=483 sealhash=80807b…140bd6 hash=31394c…c07f0a elapsed=9.702s
INFO [04-27|14:49:22.779] 🔗 block reached canonical chain          number=476 hash=a570fe…319fda
INFO [04-27|14:49:22.786] 🔨 mined potential block                  number=483 hash=31394c…c07f0a
INFO [04-27|14:49:22.786] Commit new mining work                   number=484 sealhash=fc6d23…c094f8 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:49:23.410] Looking for peers                        peercount=1 tried=70  static=0
INFO [04-27|14:49:24.967] Successfully sealed new block            number=484 sealhash=fc6d23…c094f8 hash=646328…16fd54 elapsed=2.188s
INFO [04-27|14:49:24.967] 🔗 block reached canonical chain          number=477 hash=e1323d…a554ba
INFO [04-27|14:49:24.976] Commit new mining work                   number=485 sealhash=1064c2…b51aa1 uncles=0 txs=0 gas=0     fees=0        elapsed=8.976ms
INFO [04-27|14:49:24.976] 🔨 mined potential block                  number=484 hash=646328…16fd54
INFO [04-27|14:49:31.541] Successfully sealed new block            number=485 sealhash=1064c2…b51aa1 hash=8d66bd…ceed2f elapsed=6.573s
INFO [04-27|14:49:31.541] 🔗 block reached canonical chain          number=478 hash=304bda…828246
INFO [04-27|14:49:31.549] Commit new mining work                   number=486 sealhash=219ca7…610a70 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:49:31.549] 🔨 mined potential block                  number=485 hash=8d66bd…ceed2f
INFO [04-27|14:49:33.735] Looking for peers                        peercount=1 tried=117 static=0
INFO [04-27|14:49:40.295] Successfully sealed new block            number=486 sealhash=219ca7…610a70 hash=3c2290…f40b4a elapsed=8.753s
INFO [04-27|14:49:40.295] 🔗 block reached canonical chain          number=479 hash=4ce67c…259afb
INFO [04-27|14:49:40.304] 🔨 mined potential block                  number=486 hash=3c2290…f40b4a
INFO [04-27|14:49:40.304] Commit new mining work                   number=487 sealhash=cef9bf…873707 uncles=0 txs=0 gas=0     fees=0        elapsed=8.968ms
INFO [04-27|14:49:42.548] Successfully sealed new block            number=487 sealhash=cef9bf…873707 hash=4f0d98…894287 elapsed=2.253s
INFO [04-27|14:49:42.548] 🔗 block reached canonical chain          number=480 hash=c8874b…ec22e6
INFO [04-27|14:49:42.557] 🔨 mined potential block                  number=487 hash=4f0d98…894287
INFO [04-27|14:49:42.557] Commit new mining work                   number=488 sealhash=332a32…ffd86e uncles=0 txs=0 gas=0     fees=0        elapsed=8.976ms
INFO [04-27|14:49:43.124] Successfully sealed new block            number=488 sealhash=332a32…ffd86e hash=bca71f…df6705 elapsed=575.493ms
INFO [04-27|14:49:43.125] 🔗 block reached canonical chain          number=481 hash=b6590d…a2e091
INFO [04-27|14:49:43.132] 🔨 mined potential block                  number=488 hash=bca71f…df6705
INFO [04-27|14:49:43.132] Commit new mining work                   number=489 sealhash=36ea82…2cea9f uncles=0 txs=0 gas=0     fees=0        elapsed=6.980ms
INFO [04-27|14:49:43.758] Looking for peers                        peercount=1 tried=104 static=0
INFO [04-27|14:49:50.432] Successfully sealed new block            number=489 sealhash=36ea82…2cea9f hash=021e72…bd7889 elapsed=7.307s
INFO [04-27|14:49:50.432] 🔗 block reached canonical chain          number=482 hash=d8df27…ae3ada
INFO [04-27|14:49:50.441] Commit new mining work                   number=490 sealhash=b0a5d8…cb1efe uncles=0 txs=0 gas=0     fees=0        elapsed=8.974ms
INFO [04-27|14:49:50.441] 🔨 mined potential block                  number=489 hash=021e72…bd7889
INFO [04-27|14:49:53.830] Looking for peers                        peercount=3 tried=90  static=0
INFO [04-27|14:50:03.903] Looking for peers                        peercount=1 tried=142 static=0
INFO [04-27|14:50:12.031] Successfully sealed new block            number=490 sealhash=b0a5d8…cb1efe hash=cc3565…913ffe elapsed=21.598s
INFO [04-27|14:50:12.031] 🔗 block reached canonical chain          number=483 hash=31394c…c07f0a
INFO [04-27|14:50:12.039] Commit new mining work                   number=491 sealhash=ec01a1…19d692 uncles=0 txs=0 gas=0     fees=0        elapsed=7.977ms
INFO [04-27|14:50:12.040] 🔨 mined potential block                  number=490 hash=cc3565…913ffe
INFO [04-27|14:50:13.904] Looking for peers                        peercount=1 tried=98  static=0
INFO [04-27|14:50:16.692] Successfully sealed new block            number=491 sealhash=ec01a1…19d692 hash=c844fa…aadf8c elapsed=4.661s
INFO [04-27|14:50:16.692] 🔗 block reached canonical chain          number=484 hash=646328…16fd54
INFO [04-27|14:50:16.700] 🔨 mined potential block                  number=491 hash=c844fa…aadf8c
INFO [04-27|14:50:16.700] Commit new mining work                   number=492 sealhash=49ec6a…461190 uncles=0 txs=0 gas=0     fees=0        elapsed=7.943ms
INFO [04-27|14:50:16.755] Successfully sealed new block            number=492 sealhash=49ec6a…461190 hash=6701f9…08a494 elapsed=62.828ms
INFO [04-27|14:50:16.755] 🔗 block reached canonical chain          number=485 hash=8d66bd…ceed2f
INFO [04-27|14:50:16.763] 🔨 mined potential block                  number=492 hash=6701f9…08a494
INFO [04-27|14:50:16.763] Commit new mining work                   number=493 sealhash=c4702e…53bee3 uncles=0 txs=0 gas=0     fees=0        elapsed=7.974ms
INFO [04-27|14:50:23.997] Looking for peers                        peercount=3 tried=124 static=0
INFO [04-27|14:50:34.033] Looking for peers                        peercount=2 tried=73  static=0
INFO [04-27|14:50:41.114] Successfully sealed new block            number=493 sealhash=c4702e…53bee3 hash=ac2bc3…00001a elapsed=24.358s
INFO [04-27|14:50:41.114] 🔗 block reached canonical chain          number=486 hash=3c2290…f40b4a
INFO [04-27|14:50:41.123] 🔨 mined potential block                  number=493 hash=ac2bc3…00001a
INFO [04-27|14:50:41.123] Commit new mining work                   number=494 sealhash=c756eb…ee5e27 uncles=0 txs=0 gas=0     fees=0        elapsed=8.944ms
INFO [04-27|14:50:41.571] Successfully sealed new block            number=494 sealhash=c756eb…ee5e27 hash=5c0894…ca3347 elapsed=456.747ms
INFO [04-27|14:50:41.572] 🔗 block reached canonical chain          number=487 hash=4f0d98…894287
INFO [04-27|14:50:41.579] 🔨 mined potential block                  number=494 hash=5c0894…ca3347
INFO [04-27|14:50:41.579] Commit new mining work                   number=495 sealhash=6ad39a…dde256 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:50:44.578] Looking for peers                        peercount=1 tried=76  static=0
INFO [04-27|14:50:54.638] Looking for peers                        peercount=2 tried=164 static=0
INFO [04-27|14:50:57.853] Successfully sealed new block            number=495 sealhash=6ad39a…dde256 hash=bc8e4f…f20cbc elapsed=16.281s
INFO [04-27|14:50:57.853] 🔗 block reached canonical chain          number=488 hash=bca71f…df6705
INFO [04-27|14:50:57.860] 🔨 mined potential block                  number=495 hash=bc8e4f…f20cbc
INFO [04-27|14:50:57.860] Commit new mining work                   number=496 sealhash=f2e6eb…80dd8f uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:50:58.486] Successfully sealed new block            number=496 sealhash=f2e6eb…80dd8f hash=ad6d6a…05a002 elapsed=632.343ms
INFO [04-27|14:50:58.486] 🔗 block reached canonical chain          number=489 hash=021e72…bd7889
INFO [04-27|14:50:58.494] 🔨 mined potential block                  number=496 hash=ad6d6a…05a002
INFO [04-27|14:50:58.494] Commit new mining work                   number=497 sealhash=926eba…b3691c uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:51:00.338] Successfully sealed new block            number=497 sealhash=926eba…b3691c hash=0b7aa7…738795 elapsed=1.852s
INFO [04-27|14:51:00.338] 🔗 block reached canonical chain          number=490 hash=cc3565…913ffe
INFO [04-27|14:51:00.347] 🔨 mined potential block                  number=497 hash=0b7aa7…738795
INFO [04-27|14:51:00.347] Commit new mining work                   number=498 sealhash=6e2fe1…77df3e uncles=0 txs=0 gas=0     fees=0        elapsed=8.945ms
INFO [04-27|14:51:00.780] Successfully sealed new block            number=498 sealhash=6e2fe1…77df3e hash=25c743…fc932d elapsed=442.781ms
INFO [04-27|14:51:00.780] 🔗 block reached canonical chain          number=491 hash=c844fa…aadf8c
INFO [04-27|14:51:00.788] Commit new mining work                   number=499 sealhash=70c43c…84dba2 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:51:00.788] 🔨 mined potential block                  number=498 hash=25c743…fc932d
INFO [04-27|14:51:03.477] Successfully sealed new block            number=499 sealhash=70c43c…84dba2 hash=5bd9c4…5e45f1 elapsed=2.696s
INFO [04-27|14:51:03.478] 🔗 block reached canonical chain          number=492 hash=6701f9…08a494
INFO [04-27|14:51:03.485] Commit new mining work                   number=500 sealhash=816cb6…9ac19f uncles=0 txs=0 gas=0     fees=0        elapsed=7.942ms
INFO [04-27|14:51:03.486] 🔨 mined potential block                  number=499 hash=5bd9c4…5e45f1
INFO [04-27|14:51:12.289] Successfully sealed new block            number=500 sealhash=816cb6…9ac19f hash=9d7e9a…86d83a elapsed=8.810s
INFO [04-27|14:51:12.289] 🔗 block reached canonical chain          number=493 hash=ac2bc3…00001a
INFO [04-27|14:51:12.296] 🔨 mined potential block                  number=500 hash=9d7e9a…86d83a
INFO [04-27|14:51:12.296] Commit new mining work                   number=501 sealhash=b51281…92b811 uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:51:14.681] Looking for peers                        peercount=2 tried=105 static=0
INFO [04-27|14:51:15.166] Successfully sealed new block            number=501 sealhash=b51281…92b811 hash=5b2299…215086 elapsed=2.877s
INFO [04-27|14:51:15.166] 🔗 block reached canonical chain          number=494 hash=5c0894…ca3347
INFO [04-27|14:51:15.174] Commit new mining work                   number=502 sealhash=a87b3c…52cf19 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:51:15.174] 🔨 mined potential block                  number=501 hash=5b2299…215086
INFO [04-27|14:51:19.770] Successfully sealed new block            number=502 sealhash=a87b3c…52cf19 hash=17adee…43f1dc elapsed=4.603s
INFO [04-27|14:51:19.770] 🔗 block reached canonical chain          number=495 hash=bc8e4f…f20cbc
INFO [04-27|14:51:19.779] 🔨 mined potential block                  number=502 hash=17adee…43f1dc
INFO [04-27|14:51:19.779] Commit new mining work                   number=503 sealhash=f44b07…f7d3ce uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:51:20.657] Successfully sealed new block            number=503 sealhash=f44b07…f7d3ce hash=180ee3…6b7da7 elapsed=887.592ms
INFO [04-27|14:51:20.657] 🔗 block reached canonical chain          number=496 hash=ad6d6a…05a002
INFO [04-27|14:51:20.665] 🔨 mined potential block                  number=503 hash=180ee3…6b7da7
INFO [04-27|14:51:20.665] Commit new mining work                   number=504 sealhash=c5e569…d38562 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:51:21.790] Successfully sealed new block            number=504 sealhash=c5e569…d38562 hash=b7d24b…2cd09b elapsed=1.133s
INFO [04-27|14:51:21.790] 🔗 block reached canonical chain          number=497 hash=0b7aa7…738795
INFO [04-27|14:51:21.798] 🔨 mined potential block                  number=504 hash=b7d24b…2cd09b
INFO [04-27|14:51:21.798] Commit new mining work                   number=505 sealhash=0a2d6d…1c4ba5 uncles=0 txs=0 gas=0     fees=0        elapsed=7.972ms
INFO [04-27|14:51:23.621] Successfully sealed new block            number=505 sealhash=0a2d6d…1c4ba5 hash=5cd8ea…c07c72 elapsed=1.831s
INFO [04-27|14:51:23.621] 🔗 block reached canonical chain          number=498 hash=25c743…fc932d
INFO [04-27|14:51:23.629] 🔨 mined potential block                  number=505 hash=5cd8ea…c07c72
INFO [04-27|14:51:23.629] Commit new mining work                   number=506 sealhash=154c6e…e8750b uncles=0 txs=0 gas=0     fees=0        elapsed=8.005ms
INFO [04-27|14:51:24.818] Looking for peers                        peercount=1 tried=105 static=0
INFO [04-27|14:51:31.159] Successfully sealed new block            number=506 sealhash=154c6e…e8750b hash=b15f34…74c569 elapsed=7.537s
INFO [04-27|14:51:31.159] 🔗 block reached canonical chain          number=499 hash=5bd9c4…5e45f1
INFO [04-27|14:51:31.167] Commit new mining work                   number=507 sealhash=4f9f22…cba4cb uncles=0 txs=0 gas=0     fees=0        elapsed=7.941ms
INFO [04-27|14:51:31.167] 🔨 mined potential block                  number=506 hash=b15f34…74c569
INFO [04-27|14:51:34.875] Looking for peers                        peercount=1 tried=98  static=0
INFO [04-27|14:51:35.213] Successfully sealed new block            number=507 sealhash=4f9f22…cba4cb hash=36fb57…ca5eff elapsed=4.053s
INFO [04-27|14:51:35.213] 🔗 block reached canonical chain          number=500 hash=9d7e9a…86d83a
INFO [04-27|14:51:35.221] Commit new mining work                   number=508 sealhash=c258cc…d275ea uncles=0 txs=0 gas=0     fees=0        elapsed=8.009ms
INFO [04-27|14:51:35.221] 🔨 mined potential block                  number=507 hash=36fb57…ca5eff
INFO [04-27|14:51:35.625] Successfully sealed new block            number=508 sealhash=c258cc…d275ea hash=688a8b…5a5e5c elapsed=412.930ms
INFO [04-27|14:51:35.625] 🔗 block reached canonical chain          number=501 hash=5b2299…215086
INFO [04-27|14:51:35.632] 🔨 mined potential block                  number=508 hash=688a8b…5a5e5c
INFO [04-27|14:51:35.632] Commit new mining work                   number=509 sealhash=63ae1d…c7d5d6 uncles=0 txs=0 gas=0     fees=0        elapsed=6.944ms
INFO [04-27|14:51:45.030] Looking for peers                        peercount=1 tried=51  static=0
INFO [04-27|14:51:46.625] Successfully sealed new block            number=509 sealhash=63ae1d…c7d5d6 hash=bccf7f…013101 elapsed=10.999s
INFO [04-27|14:51:46.625] 🔗 block reached canonical chain          number=502 hash=17adee…43f1dc
INFO [04-27|14:51:46.633] 🔨 mined potential block                  number=509 hash=bccf7f…013101
INFO [04-27|14:51:46.633] Commit new mining work                   number=510 sealhash=620193…c6b5dc uncles=0 txs=0 gas=0     fees=0        elapsed=7.943ms
INFO [04-27|14:51:51.425] Successfully sealed new block            number=510 sealhash=620193…c6b5dc hash=d6b37f…a29c92 elapsed=4.800s
INFO [04-27|14:51:51.425] 🔗 block reached canonical chain          number=503 hash=180ee3…6b7da7
INFO [04-27|14:51:51.433] Commit new mining work                   number=511 sealhash=43d39c…4b1cf7 uncles=0 txs=0 gas=0     fees=0        elapsed=7.952ms
INFO [04-27|14:51:51.433] 🔨 mined potential block                  number=510 hash=d6b37f…a29c92
INFO [04-27|14:51:55.143] Looking for peers                        peercount=2 tried=91  static=0
INFO [04-27|14:51:56.538] Successfully sealed new block            number=511 sealhash=43d39c…4b1cf7 hash=7f8ea7…dbee92 elapsed=5.112s
INFO [04-27|14:51:56.538] 🔗 block reached canonical chain          number=504 hash=b7d24b…2cd09b
INFO [04-27|14:51:56.545] 🔨 mined potential block                  number=511 hash=7f8ea7…dbee92
INFO [04-27|14:51:56.545] Commit new mining work                   number=512 sealhash=ad1c48…e725e9 uncles=0 txs=0 gas=0     fees=0        elapsed=7.943ms
INFO [04-27|14:52:04.839] Successfully sealed new block            number=512 sealhash=ad1c48…e725e9 hash=9afc3a…928400 elapsed=8.301s
INFO [04-27|14:52:04.840] 🔗 block reached canonical chain          number=505 hash=5cd8ea…c07c72
INFO [04-27|14:52:04.848] 🔨 mined potential block                  number=512 hash=9afc3a…928400
INFO [04-27|14:52:04.848] Commit new mining work                   number=513 sealhash=1b71fe…16f225 uncles=0 txs=0 gas=0     fees=0        elapsed=8.976ms
INFO [04-27|14:52:05.153] Looking for peers                        peercount=1 tried=65  static=0
INFO [04-27|14:52:15.210] Looking for peers                        peercount=1 tried=39  static=0
INFO [04-27|14:52:20.141] Successfully sealed new block            number=513 sealhash=1b71fe…16f225 hash=46b7f3…d69e04 elapsed=15.301s
INFO [04-27|14:52:20.141] 🔗 block reached canonical chain          number=506 hash=b15f34…74c569
INFO [04-27|14:52:20.149] 🔨 mined potential block                  number=513 hash=46b7f3…d69e04
INFO [04-27|14:52:20.149] Commit new mining work                   number=514 sealhash=439e0d…09bef0 uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:52:20.298] Successfully sealed new block            number=514 sealhash=439e0d…09bef0 hash=a1a42c…e9f178 elapsed=157.577ms
INFO [04-27|14:52:20.298] 🔗 block reached canonical chain          number=507 hash=36fb57…ca5eff
INFO [04-27|14:52:20.306] Commit new mining work                   number=515 sealhash=30b29b…bac787 uncles=0 txs=0 gas=0     fees=0        elapsed=7.946ms
INFO [04-27|14:52:20.306] 🔨 mined potential block                  number=514 hash=a1a42c…e9f178
INFO [04-27|14:52:20.859] Successfully sealed new block            number=515 sealhash=30b29b…bac787 hash=e41cb3…ee50bd elapsed=560.5ms
INFO [04-27|14:52:20.859] Mining too far in the future             wait=2s
INFO [04-27|14:52:20.864] 🔗 block reached canonical chain          number=508 hash=688a8b…5a5e5c
INFO [04-27|14:52:20.868] 🔨 mined potential block                  number=515 hash=e41cb3…ee50bd
INFO [04-27|14:52:22.866] Commit new mining work                   number=516 sealhash=7e7e20…cd88ea uncles=0 txs=0 gas=0     fees=0        elapsed=2.007s
INFO [04-27|14:52:25.264] Looking for peers                        peercount=1 tried=57  static=0
INFO [04-27|14:52:34.643] Successfully sealed new block            number=516 sealhash=7e7e20…cd88ea hash=85abd4…61a114 elapsed=11.777s
INFO [04-27|14:52:34.643] 🔗 block reached canonical chain          number=509 hash=bccf7f…013101
INFO [04-27|14:52:34.652] 🔨 mined potential block                  number=516 hash=85abd4…61a114
INFO [04-27|14:52:34.652] Commit new mining work                   number=517 sealhash=0976ae…9a635d uncles=0 txs=0 gas=0     fees=0        elapsed=8.939ms
INFO [04-27|14:52:35.486] Looking for peers                        peercount=1 tried=43  static=0
INFO [04-27|14:52:38.164] Successfully sealed new block            number=517 sealhash=0976ae…9a635d hash=c0ccef…cf68cd elapsed=3.520s
INFO [04-27|14:52:38.164] 🔗 block reached canonical chain          number=510 hash=d6b37f…a29c92
INFO [04-27|14:52:38.171] Commit new mining work                   number=518 sealhash=e2e9cc…3062ca uncles=0 txs=0 gas=0     fees=0        elapsed=6.979ms
INFO [04-27|14:52:38.171] 🔨 mined potential block                  number=517 hash=c0ccef…cf68cd
INFO [04-27|14:52:45.609] Looking for peers                        peercount=1 tried=70  static=0
INFO [04-27|14:52:46.878] Successfully sealed new block            number=518 sealhash=e2e9cc…3062ca hash=b85f2a…078612 elapsed=8.714s
INFO [04-27|14:52:46.878] 🔗 block reached canonical chain          number=511 hash=7f8ea7…dbee92
INFO [04-27|14:52:46.887] 🔨 mined potential block                  number=518 hash=b85f2a…078612
INFO [04-27|14:52:46.887] Commit new mining work                   number=519 sealhash=6bb949…d96b5b uncles=0 txs=0 gas=0     fees=0        elapsed=8.992ms
INFO [04-27|14:52:48.927] Successfully sealed new block            number=519 sealhash=6bb949…d96b5b hash=5dcc61…7692ae elapsed=2.048s
INFO [04-27|14:52:48.927] 🔗 block reached canonical chain          number=512 hash=9afc3a…928400
INFO [04-27|14:52:48.935] 🔨 mined potential block                  number=519 hash=5dcc61…7692ae
INFO [04-27|14:52:48.935] Commit new mining work                   number=520 sealhash=3951c6…de19e2 uncles=0 txs=0 gas=0     fees=0        elapsed=7.938ms
INFO [04-27|14:52:55.618] Looking for peers                        peercount=1 tried=58  static=0
INFO [04-27|14:52:57.749] Successfully sealed new block            number=520 sealhash=3951c6…de19e2 hash=24385f…e26a83 elapsed=8.822s
INFO [04-27|14:52:57.749] 🔗 block reached canonical chain          number=513 hash=46b7f3…d69e04
INFO [04-27|14:52:57.756] 🔨 mined potential block                  number=520 hash=24385f…e26a83
INFO [04-27|14:52:57.756] Commit new mining work                   number=521 sealhash=8608b0…6af218 uncles=0 txs=0 gas=0     fees=0        elapsed=6.948ms
INFO [04-27|14:53:05.618] Looking for peers                        peercount=1 tried=41  static=0
INFO [04-27|14:53:12.356] Successfully sealed new block            number=521 sealhash=8608b0…6af218 hash=3d9054…96e064 elapsed=14.606s
INFO [04-27|14:53:12.356] 🔗 block reached canonical chain          number=514 hash=a1a42c…e9f178
INFO [04-27|14:53:12.365] 🔨 mined potential block                  number=521 hash=3d9054…96e064
INFO [04-27|14:53:12.365] Commit new mining work                   number=522 sealhash=beb994…6c60b1 uncles=0 txs=0 gas=0     fees=0        elapsed=8.935ms
INFO [04-27|14:53:15.619] Looking for peers                        peercount=1 tried=58  static=0
INFO [04-27|14:53:19.266] Successfully sealed new block            number=522 sealhash=beb994…6c60b1 hash=367448…d48c1c elapsed=6.909s
INFO [04-27|14:53:19.266] 🔗 block reached canonical chain          number=515 hash=e41cb3…ee50bd
INFO [04-27|14:53:19.274] Commit new mining work                   number=523 sealhash=9ae23f…736ac6 uncles=0 txs=0 gas=0     fees=0        elapsed=7.943ms
INFO [04-27|14:53:19.274] 🔨 mined potential block                  number=522 hash=367448…d48c1c
INFO [04-27|14:53:19.444] Successfully sealed new block            number=523 sealhash=9ae23f…736ac6 hash=294f5c…0728c3 elapsed=178.596ms
INFO [04-27|14:53:19.444] 🔗 block reached canonical chain          number=516 hash=85abd4…61a114
INFO [04-27|14:53:19.453] 🔨 mined potential block                  number=523 hash=294f5c…0728c3
INFO [04-27|14:53:19.453] Commit new mining work                   number=524 sealhash=2e7ae5…94b360 uncles=0 txs=0 gas=0     fees=0        elapsed=8.976ms
INFO [04-27|14:53:25.619] Looking for peers                        peercount=1 tried=58  static=0
INFO [04-27|14:53:25.752] Successfully sealed new block            number=524 sealhash=2e7ae5…94b360 hash=41d11d…178bd7 elapsed=6.307s
INFO [04-27|14:53:25.753] 🔗 block reached canonical chain          number=517 hash=c0ccef…cf68cd
INFO [04-27|14:53:25.761] Commit new mining work                   number=525 sealhash=52b82e…f4cfb1 uncles=0 txs=0 gas=0     fees=0        elapsed=8.944ms
INFO [04-27|14:53:25.761] 🔨 mined potential block                  number=524 hash=41d11d…178bd7
INFO [04-27|14:53:30.079] Successfully sealed new block            number=525 sealhash=52b82e…f4cfb1 hash=af6bdd…083138 elapsed=4.326s
INFO [04-27|14:53:30.079] 🔗 block reached canonical chain          number=518 hash=b85f2a…078612
INFO [04-27|14:53:30.087] 🔨 mined potential block                  number=525 hash=af6bdd…083138
INFO [04-27|14:53:30.087] Commit new mining work                   number=526 sealhash=2eefc1…ca68f9 uncles=0 txs=0 gas=0     fees=0        elapsed=7.977ms
INFO [04-27|14:53:35.641] Looking for peers                        peercount=3 tried=55  static=0
INFO [04-27|14:53:36.522] Successfully sealed new block            number=526 sealhash=2eefc1…ca68f9 hash=8816db…a87776 elapsed=6.442s
INFO [04-27|14:53:36.523] 🔗 block reached canonical chain          number=519 hash=5dcc61…7692ae
INFO [04-27|14:53:36.531] 🔨 mined potential block                  number=526 hash=8816db…a87776
INFO [04-27|14:53:36.531] Commit new mining work                   number=527 sealhash=211020…560a35 uncles=0 txs=0 gas=0     fees=0        elapsed=7.965ms
INFO [04-27|14:53:45.581] Successfully sealed new block            number=527 sealhash=211020…560a35 hash=96ed2c…8f182b elapsed=9.057s
INFO [04-27|14:53:45.582] 🔗 block reached canonical chain          number=520 hash=24385f…e26a83
INFO [04-27|14:53:45.589] Commit new mining work                   number=528 sealhash=707095…414de6 uncles=0 txs=0 gas=0     fees=0        elapsed=7.972ms
INFO [04-27|14:53:45.589] 🔨 mined potential block                  number=527 hash=96ed2c…8f182b
INFO [04-27|14:53:45.679] Looking for peers                        peercount=1 tried=105 static=0
INFO [04-27|14:53:50.142] Successfully sealed new block            number=528 sealhash=707095…414de6 hash=99dff3…a9d78a elapsed=4.559s
INFO [04-27|14:53:50.142] 🔗 block reached canonical chain          number=521 hash=3d9054…96e064
INFO [04-27|14:53:50.150] 🔨 mined potential block                  number=528 hash=99dff3…a9d78a
INFO [04-27|14:53:50.150] Commit new mining work                   number=529 sealhash=414e96…1a0009 uncles=0 txs=0 gas=0     fees=0        elapsed=7.979ms
INFO [04-27|14:53:53.314] Successfully sealed new block            number=529 sealhash=414e96…1a0009 hash=ad7dbc…363ae1 elapsed=3.172s
INFO [04-27|14:53:53.314] 🔗 block reached canonical chain          number=522 hash=367448…d48c1c
INFO [04-27|14:53:53.322] 🔨 mined potential block                  number=529 hash=ad7dbc…363ae1
INFO [04-27|14:53:53.322] Commit new mining work                   number=530 sealhash=c94f69…0b0b64 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:53:54.198] Successfully sealed new block            number=530 sealhash=c94f69…0b0b64 hash=72b277…c506fc elapsed=883.602ms
INFO [04-27|14:53:54.198] 🔗 block reached canonical chain          number=523 hash=294f5c…0728c3
INFO [04-27|14:53:54.205] Commit new mining work                   number=531 sealhash=3e8292…9b70cd uncles=0 txs=0 gas=0     fees=0        elapsed=6.981ms
INFO [04-27|14:53:54.205] 🔨 mined potential block                  number=530 hash=72b277…c506fc
INFO [04-27|14:53:55.742] Looking for peers                        peercount=1 tried=76  static=0
INFO [04-27|14:54:05.749] Looking for peers                        peercount=1 tried=125 static=0
INFO [04-27|14:54:05.757] Successfully sealed new block            number=531 sealhash=3e8292…9b70cd hash=cff919…0ed72d elapsed=11.559s
INFO [04-27|14:54:05.757] 🔗 block reached canonical chain          number=524 hash=41d11d…178bd7
INFO [04-27|14:54:05.765] 🔨 mined potential block                  number=531 hash=cff919…0ed72d
INFO [04-27|14:54:05.765] Commit new mining work                   number=532 sealhash=2ade52…edfaab uncles=0 txs=0 gas=0     fees=0        elapsed=7.974ms
INFO [04-27|14:54:15.780] Looking for peers                        peercount=3 tried=98  static=0
INFO [04-27|14:54:16.712] Successfully sealed new block            number=532 sealhash=2ade52…edfaab hash=9340bb…868f24 elapsed=10.954s
INFO [04-27|14:54:16.712] 🔗 block reached canonical chain          number=525 hash=af6bdd…083138
INFO [04-27|14:54:16.720] Commit new mining work                   number=533 sealhash=bfb09e…1aa0ac uncles=0 txs=0 gas=0     fees=0        elapsed=8.011ms
INFO [04-27|14:54:16.720] 🔨 mined potential block                  number=532 hash=9340bb…868f24
INFO [04-27|14:54:18.648] Successfully sealed new block            number=533 sealhash=bfb09e…1aa0ac hash=44c446…83f342 elapsed=1.935s
INFO [04-27|14:54:18.648] 🔗 block reached canonical chain          number=526 hash=8816db…a87776
INFO [04-27|14:54:18.659] 🔨 mined potential block                  number=533 hash=44c446…83f342
INFO [04-27|14:54:18.659] Commit new mining work                   number=534 sealhash=676097…30e775 uncles=0 txs=0 gas=0     fees=0        elapsed=11.000ms
INFO [04-27|14:54:21.788] Successfully sealed new block            number=534 sealhash=676097…30e775 hash=721de6…5afa1e elapsed=3.140s
INFO [04-27|14:54:21.788] 🔗 block reached canonical chain          number=527 hash=96ed2c…8f182b
INFO [04-27|14:54:21.796] Commit new mining work                   number=535 sealhash=658681…35e59c uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:54:21.796] 🔨 mined potential block                  number=534 hash=721de6…5afa1e
INFO [04-27|14:54:25.815] Looking for peers                        peercount=2 tried=129 static=0
INFO [04-27|14:54:33.948] Successfully sealed new block            number=535 sealhash=658681…35e59c hash=575a7b…0826f6 elapsed=12.159s
INFO [04-27|14:54:33.948] 🔗 block reached canonical chain          number=528 hash=99dff3…a9d78a
INFO [04-27|14:54:33.956] 🔨 mined potential block                  number=535 hash=575a7b…0826f6
INFO [04-27|14:54:33.956] Commit new mining work                   number=536 sealhash=9927da…62d328 uncles=0 txs=0 gas=0     fees=0        elapsed=7.977ms
INFO [04-27|14:54:35.864] Looking for peers                        peercount=2 tried=77  static=0
INFO [04-27|14:54:36.926] Successfully sealed new block            number=536 sealhash=9927da…62d328 hash=be79c9…0cea66 elapsed=2.978s
INFO [04-27|14:54:36.926] 🔗 block reached canonical chain          number=529 hash=ad7dbc…363ae1
INFO [04-27|14:54:36.933] 🔨 mined potential block                  number=536 hash=be79c9…0cea66
INFO [04-27|14:54:36.933] Commit new mining work                   number=537 sealhash=246254…d7b502 uncles=0 txs=0 gas=0     fees=0        elapsed=6.980ms
INFO [04-27|14:54:45.513] Successfully sealed new block            number=537 sealhash=246254…d7b502 hash=eb47ad…0a4585 elapsed=8.586s
INFO [04-27|14:54:45.514] 🔗 block reached canonical chain          number=530 hash=72b277…c506fc
INFO [04-27|14:54:45.522] 🔨 mined potential block                  number=537 hash=eb47ad…0a4585
INFO [04-27|14:54:45.522] Commit new mining work                   number=538 sealhash=251f85…3e2428 uncles=0 txs=0 gas=0     fees=0        elapsed=8.990ms
INFO [04-27|14:54:46.074] Looking for peers                        peercount=1 tried=107 static=0
INFO [04-27|14:54:49.635] Successfully sealed new block            number=538 sealhash=251f85…3e2428 hash=e748fe…05d1c7 elapsed=4.121s
INFO [04-27|14:54:49.635] 🔗 block reached canonical chain          number=531 hash=cff919…0ed72d
INFO [04-27|14:54:49.643] 🔨 mined potential block                  number=538 hash=e748fe…05d1c7
INFO [04-27|14:54:49.643] Commit new mining work                   number=539 sealhash=b574bb…3aa027 uncles=0 txs=0 gas=0     fees=0        elapsed=8.005ms
INFO [04-27|14:54:56.174] Looking for peers                        peercount=1 tried=131 static=0
INFO [04-27|14:54:57.072] Successfully sealed new block            number=539 sealhash=b574bb…3aa027 hash=670f64…c41f11 elapsed=7.437s
INFO [04-27|14:54:57.072] 🔗 block reached canonical chain          number=532 hash=9340bb…868f24
INFO [04-27|14:54:57.080] 🔨 mined potential block                  number=539 hash=670f64…c41f11
INFO [04-27|14:54:57.080] Commit new mining work                   number=540 sealhash=a3c619…9620eb uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:55:01.032] Successfully sealed new block            number=540 sealhash=a3c619…9620eb hash=285fee…1dffd6 elapsed=3.960s
INFO [04-27|14:55:01.032] 🔗 block reached canonical chain          number=533 hash=44c446…83f342
INFO [04-27|14:55:01.040] 🔨 mined potential block                  number=540 hash=285fee…1dffd6
INFO [04-27|14:55:01.040] Commit new mining work                   number=541 sealhash=9d6245…0c431e uncles=0 txs=0 gas=0     fees=0        elapsed=7.942ms
INFO [04-27|14:55:06.187] Looking for peers                        peercount=1 tried=35  static=0
INFO [04-27|14:55:08.826] Successfully sealed new block            number=541 sealhash=9d6245…0c431e hash=a33306…053f21 elapsed=7.793s
INFO [04-27|14:55:08.826] 🔗 block reached canonical chain          number=534 hash=721de6…5afa1e
INFO [04-27|14:55:08.834] Commit new mining work                   number=542 sealhash=ef2d81…b3c47a uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:55:08.834] 🔨 mined potential block                  number=541 hash=a33306…053f21
INFO [04-27|14:55:11.972] Successfully sealed new block            number=542 sealhash=ef2d81…b3c47a hash=6e9fea…8786ac elapsed=3.146s
INFO [04-27|14:55:11.973] 🔗 block reached canonical chain          number=535 hash=575a7b…0826f6
INFO [04-27|14:55:11.980] 🔨 mined potential block                  number=542 hash=6e9fea…8786ac
INFO [04-27|14:55:11.980] Commit new mining work                   number=543 sealhash=c5a70e…434c14 uncles=0 txs=0 gas=0     fees=0        elapsed=6.994ms
INFO [04-27|14:55:16.353] Looking for peers                        peercount=2 tried=55  static=0
INFO [04-27|14:55:23.293] Successfully sealed new block            number=543 sealhash=c5a70e…434c14 hash=554f2d…00f86f elapsed=11.319s
INFO [04-27|14:55:23.293] 🔗 block reached canonical chain          number=536 hash=be79c9…0cea66
INFO [04-27|14:55:23.300] 🔨 mined potential block                  number=543 hash=554f2d…00f86f
INFO [04-27|14:55:23.300] Commit new mining work                   number=544 sealhash=5702dc…51d589 uncles=0 txs=0 gas=0     fees=0        elapsed=6.943ms
INFO [04-27|14:55:23.790] Successfully sealed new block            number=544 sealhash=5702dc…51d589 hash=9ece00…507b65 elapsed=496.631ms
INFO [04-27|14:55:23.790] 🔗 block reached canonical chain          number=537 hash=eb47ad…0a4585
INFO [04-27|14:55:23.799] 🔨 mined potential block                  number=544 hash=9ece00…507b65
INFO [04-27|14:55:23.799] Commit new mining work                   number=545 sealhash=2723b5…a7d7a4 uncles=0 txs=0 gas=0     fees=0        elapsed=8.976ms
INFO [04-27|14:55:24.519] Successfully sealed new block            number=545 sealhash=2723b5…a7d7a4 hash=b08b7a…2b6bb0 elapsed=729.056ms
INFO [04-27|14:55:24.519] 🔗 block reached canonical chain          number=538 hash=e748fe…05d1c7
INFO [04-27|14:55:24.527] 🔨 mined potential block                  number=545 hash=b08b7a…2b6bb0
INFO [04-27|14:55:24.527] Commit new mining work                   number=546 sealhash=11db5e…5d75f7 uncles=0 txs=0 gas=0     fees=0        elapsed=7.972ms
INFO [04-27|14:55:26.509] Looking for peers                        peercount=1 tried=108 static=0
INFO [04-27|14:55:36.516] Looking for peers                        peercount=1 tried=101 static=0
INFO [04-27|14:55:43.569] Successfully sealed new block            number=546 sealhash=11db5e…5d75f7 hash=6abffe…cb8735 elapsed=19.050s
INFO [04-27|14:55:43.569] 🔗 block reached canonical chain          number=539 hash=670f64…c41f11
INFO [04-27|14:55:43.576] 🔨 mined potential block                  number=546 hash=6abffe…cb8735
INFO [04-27|14:55:43.576] Commit new mining work                   number=547 sealhash=7757c4…f0e9af uncles=0 txs=0 gas=0     fees=0        elapsed=6.944ms
INFO [04-27|14:55:46.721] Looking for peers                        peercount=1 tried=69  static=0
INFO [04-27|14:55:49.485] Successfully sealed new block            number=547 sealhash=7757c4…f0e9af hash=a80f25…fdbdb4 elapsed=5.916s
INFO [04-27|14:55:49.485] 🔗 block reached canonical chain          number=540 hash=285fee…1dffd6
INFO [04-27|14:55:49.493] Commit new mining work                   number=548 sealhash=5a95db…db5762 uncles=0 txs=0 gas=0     fees=0        elapsed=7.943ms
INFO [04-27|14:55:49.493] 🔨 mined potential block                  number=547 hash=a80f25…fdbdb4
INFO [04-27|14:55:49.932] Successfully sealed new block            number=548 sealhash=5a95db…db5762 hash=02511f…ec99fc elapsed=446.804ms
INFO [04-27|14:55:49.932] 🔗 block reached canonical chain          number=541 hash=a33306…053f21
INFO [04-27|14:55:49.941] 🔨 mined potential block                  number=548 hash=02511f…ec99fc
INFO [04-27|14:55:49.941] Commit new mining work                   number=549 sealhash=992c87…19c55a uncles=0 txs=0 gas=0     fees=0        elapsed=8.969ms
INFO [04-27|14:55:53.652] Successfully sealed new block            number=549 sealhash=992c87…19c55a hash=f9c43d…afbb3b elapsed=3.720s
INFO [04-27|14:55:53.653] 🔗 block reached canonical chain          number=542 hash=6e9fea…8786ac
INFO [04-27|14:55:53.660] Commit new mining work                   number=550 sealhash=f083c8…ea2911 uncles=0 txs=0 gas=0     fees=0        elapsed=7.972ms
INFO [04-27|14:55:53.660] 🔨 mined potential block                  number=549 hash=f9c43d…afbb3b
INFO [04-27|14:55:56.789] Looking for peers                        peercount=1 tried=142 static=0
INFO [04-27|14:55:58.459] Successfully sealed new block            number=550 sealhash=f083c8…ea2911 hash=20021b…014c5d elapsed=4.806s
INFO [04-27|14:55:58.459] 🔗 block reached canonical chain          number=543 hash=554f2d…00f86f
INFO [04-27|14:55:58.467] 🔨 mined potential block                  number=550 hash=20021b…014c5d
INFO [04-27|14:55:58.467] Commit new mining work                   number=551 sealhash=22dedc…ab0d48 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:56:04.685] Successfully sealed new block            number=551 sealhash=22dedc…ab0d48 hash=86acba…9afb17 elapsed=6.226s
INFO [04-27|14:56:04.685] 🔗 block reached canonical chain          number=544 hash=9ece00…507b65
INFO [04-27|14:56:04.692] 🔨 mined potential block                  number=551 hash=86acba…9afb17
INFO [04-27|14:56:04.692] Commit new mining work                   number=552 sealhash=8828d5…e8ce81 uncles=0 txs=0 gas=0     fees=0        elapsed=6.982ms
INFO [04-27|14:56:06.871] Looking for peers                        peercount=1 tried=93  static=0
INFO [04-27|14:56:17.486] Successfully sealed new block            number=552 sealhash=8828d5…e8ce81 hash=f38425…d31cf3 elapsed=12.800s
INFO [04-27|14:56:17.486] 🔗 block reached canonical chain          number=545 hash=b08b7a…2b6bb0
INFO [04-27|14:56:17.493] Commit new mining work                   number=553 sealhash=5344ff…a6d4f2 uncles=0 txs=0 gas=0     fees=0        elapsed=6.976ms
INFO [04-27|14:56:17.493] 🔨 mined potential block                  number=552 hash=f38425…d31cf3
INFO [04-27|14:56:17.656] Looking for peers                        peercount=1 tried=32  static=0
INFO [04-27|14:56:19.705] Successfully sealed new block            number=553 sealhash=5344ff…a6d4f2 hash=0bc0b2…f20ccb elapsed=2.219s
INFO [04-27|14:56:19.705] 🔗 block reached canonical chain          number=546 hash=6abffe…cb8735
INFO [04-27|14:56:19.712] 🔨 mined potential block                  number=553 hash=0bc0b2…f20ccb
INFO [04-27|14:56:19.712] Commit new mining work                   number=554 sealhash=beceb3…07823d uncles=0 txs=0 gas=0     fees=0        elapsed=6.974ms
INFO [04-27|14:56:25.400] Successfully sealed new block            number=554 sealhash=beceb3…07823d hash=184dc4…4916cb elapsed=5.694s
INFO [04-27|14:56:25.400] 🔗 block reached canonical chain          number=547 hash=a80f25…fdbdb4
INFO [04-27|14:56:25.408] Commit new mining work                   number=555 sealhash=fead05…b0a8e8 uncles=0 txs=0 gas=0     fees=0        elapsed=7.972ms
INFO [04-27|14:56:25.408] 🔨 mined potential block                  number=554 hash=184dc4…4916cb
INFO [04-27|14:56:27.726] Looking for peers                        peercount=1 tried=30  static=0
INFO [04-27|14:56:34.944] Successfully sealed new block            number=555 sealhash=fead05…b0a8e8 hash=aeed2a…794bcc elapsed=9.543s
INFO [04-27|14:56:34.944] 🔗 block reached canonical chain          number=548 hash=02511f…ec99fc
INFO [04-27|14:56:34.953] 🔨 mined potential block                  number=555 hash=aeed2a…794bcc
INFO [04-27|14:56:34.953] Commit new mining work                   number=556 sealhash=d34bd0…5cd215 uncles=0 txs=0 gas=0     fees=0        elapsed=8.94ms
INFO [04-27|14:56:35.132] Successfully sealed new block            number=556 sealhash=d34bd0…5cd215 hash=14174c…ef45e5 elapsed=188.498ms
INFO [04-27|14:56:35.132] 🔗 block reached canonical chain          number=549 hash=f9c43d…afbb3b
INFO [04-27|14:56:35.140] Commit new mining work                   number=557 sealhash=e97073…abd5df uncles=0 txs=0 gas=0     fees=0        elapsed=7.955ms
INFO [04-27|14:56:35.140] 🔨 mined potential block                  number=556 hash=14174c…ef45e5
INFO [04-27|14:56:37.747] Looking for peers                        peercount=1 tried=16  static=0
INFO [04-27|14:56:42.540] Successfully sealed new block            number=557 sealhash=e97073…abd5df hash=b9acbe…cc352d elapsed=7.407s
INFO [04-27|14:56:42.540] 🔗 block reached canonical chain          number=550 hash=20021b…014c5d
INFO [04-27|14:56:42.547] 🔨 mined potential block                  number=557 hash=b9acbe…cc352d
INFO [04-27|14:56:42.547] Commit new mining work                   number=558 sealhash=687531…4b7a5d uncles=0 txs=0 gas=0     fees=0        elapsed=6.980ms
INFO [04-27|14:56:48.081] Looking for peers                        peercount=1 tried=19  static=0
INFO [04-27|14:56:48.621] Successfully sealed new block            number=558 sealhash=687531…4b7a5d hash=d35a23…41daf0 elapsed=6.081s
INFO [04-27|14:56:48.621] 🔗 block reached canonical chain          number=551 hash=86acba…9afb17
INFO [04-27|14:56:48.628] 🔨 mined potential block                  number=558 hash=d35a23…41daf0
INFO [04-27|14:56:48.628] Commit new mining work                   number=559 sealhash=00477f…40c44e uncles=0 txs=0 gas=0     fees=0        elapsed=6.973ms
INFO [04-27|14:56:58.085] Looking for peers                        peercount=1 tried=29  static=0
INFO [04-27|14:56:58.508] Successfully sealed new block            number=559 sealhash=00477f…40c44e hash=770001…985b24 elapsed=9.886s
INFO [04-27|14:56:58.508] 🔗 block reached canonical chain          number=552 hash=f38425…d31cf3
INFO [04-27|14:56:58.517] 🔨 mined potential block                  number=559 hash=770001…985b24
INFO [04-27|14:56:58.517] Commit new mining work                   number=560 sealhash=7ccbaf…847438 uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:57:08.381] Looking for peers                        peercount=1 tried=44  static=0
INFO [04-27|14:57:11.193] Successfully sealed new block            number=560 sealhash=7ccbaf…847438 hash=f06087…571a8a elapsed=12.685s
INFO [04-27|14:57:11.193] 🔗 block reached canonical chain          number=553 hash=0bc0b2…f20ccb
INFO [04-27|14:57:11.201] 🔨 mined potential block                  number=560 hash=f06087…571a8a
INFO [04-27|14:57:11.201] Commit new mining work                   number=561 sealhash=dffdf2…e2e6de uncles=0 txs=0 gas=0     fees=0        elapsed=7.972ms
INFO [04-27|14:57:15.197] Successfully sealed new block            number=561 sealhash=dffdf2…e2e6de hash=72a74b…b2b7b2 elapsed=4.004s
INFO [04-27|14:57:15.197] 🔗 block reached canonical chain          number=554 hash=184dc4…4916cb
INFO [04-27|14:57:15.207] Commit new mining work                   number=562 sealhash=8625cd…6fc54b uncles=0 txs=0 gas=0     fees=0        elapsed=9.937ms
INFO [04-27|14:57:15.207] 🔨 mined potential block                  number=561 hash=72a74b…b2b7b2
INFO [04-27|14:57:16.007] Successfully sealed new block            number=562 sealhash=8625cd…6fc54b hash=d508ed…78f676 elapsed=809.799ms
INFO [04-27|14:57:16.008] 🔗 block reached canonical chain          number=555 hash=aeed2a…794bcc
INFO [04-27|14:57:16.021] Commit new mining work                   number=563 sealhash=536b75…084be1 uncles=0 txs=0 gas=0     fees=0        elapsed=12.962ms
INFO [04-27|14:57:16.021] 🔨 mined potential block                  number=562 hash=d508ed…78f676
INFO [04-27|14:57:16.310] Successfully sealed new block            number=563 sealhash=536b75…084be1 hash=cec6f2…20e454 elapsed=302.189ms
INFO [04-27|14:57:16.310] 🔗 block reached canonical chain          number=556 hash=14174c…ef45e5
INFO [04-27|14:57:16.318] 🔨 mined potential block                  number=563 hash=cec6f2…20e454
INFO [04-27|14:57:16.318] Commit new mining work                   number=564 sealhash=7d3277…48f25d uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:57:18.404] Looking for peers                        peercount=2 tried=35  static=0
INFO [04-27|14:57:28.416] Looking for peers                        peercount=2 tried=78  static=0
INFO [04-27|14:57:35.002] Successfully sealed new block            number=564 sealhash=7d3277…48f25d hash=af182b…2b74b4 elapsed=18.691s
INFO [04-27|14:57:35.003] 🔗 block reached canonical chain          number=557 hash=b9acbe…cc352d
INFO [04-27|14:57:35.012] 🔨 mined potential block                  number=564 hash=af182b…2b74b4
INFO [04-27|14:57:35.012] Commit new mining work                   number=565 sealhash=93a458…86fb08 uncles=0 txs=0 gas=0     fees=0        elapsed=10.964ms
INFO [04-27|14:57:38.441] Looking for peers                        peercount=1 tried=65  static=0
INFO [04-27|14:57:44.291] Successfully sealed new block            number=565 sealhash=93a458…86fb08 hash=2913b6…1d682f elapsed=9.288s
INFO [04-27|14:57:44.292] 🔗 block reached canonical chain          number=558 hash=d35a23…41daf0
INFO [04-27|14:57:44.301] 🔨 mined potential block                  number=565 hash=2913b6…1d682f
INFO [04-27|14:57:44.301] Commit new mining work                   number=566 sealhash=531089…086539 uncles=0 txs=0 gas=0     fees=0        elapsed=9.975ms
INFO [04-27|14:57:48.442] Looking for peers                        peercount=1 tried=67  static=0
INFO [04-27|14:57:54.121] Successfully sealed new block            number=566 sealhash=531089…086539 hash=56368e…2747db elapsed=9.829s
INFO [04-27|14:57:54.121] 🔗 block reached canonical chain          number=559 hash=770001…985b24
INFO [04-27|14:57:54.129] Commit new mining work                   number=567 sealhash=100004…a4f72a uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|14:57:54.129] 🔨 mined potential block                  number=566 hash=56368e…2747db
INFO [04-27|14:57:57.265] Successfully sealed new block            number=567 sealhash=100004…a4f72a hash=464cad…24caa1 elapsed=3.143s
INFO [04-27|14:57:57.265] 🔗 block reached canonical chain          number=560 hash=f06087…571a8a
INFO [04-27|14:57:57.273] 🔨 mined potential block                  number=567 hash=464cad…24caa1
INFO [04-27|14:57:57.273] Commit new mining work                   number=568 sealhash=37562a…a549b6 uncles=0 txs=0 gas=0     fees=0        elapsed=7.942ms
INFO [04-27|14:57:58.494] Looking for peers                        peercount=1 tried=57  static=0
INFO [04-27|14:58:03.773] Successfully sealed new block            number=568 sealhash=37562a…a549b6 hash=e3a2b5…f88ede elapsed=6.507s
INFO [04-27|14:58:03.773] 🔗 block reached canonical chain          number=561 hash=72a74b…b2b7b2
INFO [04-27|14:58:03.781] 🔨 mined potential block                  number=568 hash=e3a2b5…f88ede
INFO [04-27|14:58:03.781] Commit new mining work                   number=569 sealhash=0c54ee…e47138 uncles=0 txs=0 gas=0     fees=0        elapsed=7.971ms
INFO [04-27|14:58:07.531] Successfully sealed new block            number=569 sealhash=0c54ee…e47138 hash=386446…15e21d elapsed=3.757s
INFO [04-27|14:58:07.531] 🔗 block reached canonical chain          number=562 hash=d508ed…78f676
INFO [04-27|14:58:07.540] Commit new mining work                   number=570 sealhash=2ca996…32e44f uncles=0 txs=0 gas=0     fees=0        elapsed=8.943ms
INFO [04-27|14:58:07.541] 🔨 mined potential block                  number=569 hash=386446…15e21d
INFO [04-27|14:58:08.494] Looking for peers                        peercount=1 tried=60  static=0
INFO [04-27|14:58:13.379] Successfully sealed new block            number=570 sealhash=2ca996…32e44f hash=6f6b7a…9ed470 elapsed=5.848s
INFO [04-27|14:58:13.380] 🔗 block reached canonical chain          number=563 hash=cec6f2…20e454
INFO [04-27|14:58:13.391] 🔨 mined potential block                  number=570 hash=6f6b7a…9ed470
INFO [04-27|14:58:13.391] Commit new mining work                   number=571 sealhash=39fc61…3286f5 uncles=0 txs=0 gas=0     fees=0        elapsed=10.944ms
INFO [04-27|14:58:18.503] Looking for peers                        peercount=1 tried=44  static=0
INFO [04-27|14:58:28.692] Looking for peers                        peercount=1 tried=69  static=0
INFO [04-27|14:58:38.747] Looking for peers                        peercount=1 tried=58  static=0
INFO [04-27|14:58:38.879] Successfully sealed new block            number=571 sealhash=39fc61…3286f5 hash=d83a31…4d8fff elapsed=25.498s
INFO [04-27|14:58:38.880] 🔗 block reached canonical chain          number=564 hash=af182b…2b74b4
INFO [04-27|14:58:38.888] Commit new mining work                   number=572 sealhash=d2ba20…e6382f uncles=0 txs=0 gas=0     fees=0        elapsed=8.939ms
INFO [04-27|14:58:38.888] 🔨 mined potential block                  number=571 hash=d83a31…4d8fff
INFO [04-27|14:58:40.697] Successfully sealed new block            number=572 sealhash=d2ba20…e6382f hash=a8f119…8d07be elapsed=1.817s
INFO [04-27|14:58:40.698] 🔗 block reached canonical chain          number=565 hash=2913b6…1d682f
INFO [04-27|14:58:40.706] 🔨 mined potential block                  number=572 hash=a8f119…8d07be
INFO [04-27|14:58:40.706] Commit new mining work                   number=573 sealhash=5d4ab0…2924a7 uncles=0 txs=0 gas=0     fees=0        elapsed=8.977ms
INFO [04-27|14:58:48.827] Looking for peers                        peercount=1 tried=57  static=0
INFO [04-27|14:58:55.378] Successfully sealed new block            number=573 sealhash=5d4ab0…2924a7 hash=628d7d…c1b016 elapsed=14.679s
INFO [04-27|14:58:55.378] 🔗 block reached canonical chain          number=566 hash=56368e…2747db
INFO [04-27|14:58:55.387] 🔨 mined potential block                  number=573 hash=628d7d…c1b016
INFO [04-27|14:58:55.387] Commit new mining work                   number=574 sealhash=521632…cb020c uncles=0 txs=0 gas=0     fees=0        elapsed=8.941ms
INFO [04-27|14:58:55.763] Successfully sealed new block            number=574 sealhash=521632…cb020c hash=5785d4…07919a elapsed=384.935ms
INFO [04-27|14:58:55.763] 🔗 block reached canonical chain          number=567 hash=464cad…24caa1
INFO [04-27|14:58:55.772] 🔨 mined potential block                  number=574 hash=5785d4…07919a
INFO [04-27|14:58:55.772] Commit new mining work                   number=575 sealhash=509283…c7a719 uncles=0 txs=0 gas=0     fees=0        elapsed=9.973ms
INFO [04-27|14:58:58.827] Looking for peers                        peercount=1 tried=93  static=0
INFO [04-27|14:59:01.423] Successfully sealed new block            number=575 sealhash=509283…c7a719 hash=807334…16a130 elapsed=5.660s
INFO [04-27|14:59:01.424] 🔗 block reached canonical chain          number=568 hash=e3a2b5…f88ede
INFO [04-27|14:59:01.431] Commit new mining work                   number=576 sealhash=e61ebb…f75fd7 uncles=0 txs=0 gas=0     fees=0        elapsed=7.944ms
INFO [04-27|14:59:01.431] 🔨 mined potential block                  number=575 hash=807334…16a130
INFO [04-27|14:59:08.036] Successfully sealed new block            number=576 sealhash=e61ebb…f75fd7 hash=7819c3…084d70 elapsed=6.611s
INFO [04-27|14:59:08.036] 🔗 block reached canonical chain          number=569 hash=386446…15e21d
INFO [04-27|14:59:08.046] 🔨 mined potential block                  number=576 hash=7819c3…084d70
INFO [04-27|14:59:08.046] Commit new mining work                   number=577 sealhash=4bf28e…5afb6c uncles=0 txs=0 gas=0     fees=0        elapsed=9.937ms
INFO [04-27|14:59:08.836] Looking for peers                        peercount=1 tried=148 static=0
INFO [04-27|14:59:09.527] Successfully sealed new block            number=577 sealhash=4bf28e…5afb6c hash=356185…f1cf05 elapsed=1.490s
INFO [04-27|14:59:09.527] 🔗 block reached canonical chain          number=570 hash=6f6b7a…9ed470
INFO [04-27|14:59:09.537] 🔨 mined potential block                  number=577 hash=356185…f1cf05
INFO [04-27|14:59:09.537] Commit new mining work                   number=578 sealhash=20c59a…5908a7 uncles=0 txs=0 gas=0     fees=0        elapsed=9.964ms
INFO [04-27|14:59:11.181] Successfully sealed new block            number=578 sealhash=20c59a…5908a7 hash=b2ca0f…926da3 elapsed=1.654s
INFO [04-27|14:59:11.181] 🔗 block reached canonical chain          number=571 hash=d83a31…4d8fff
INFO [04-27|14:59:11.190] 🔨 mined potential block                  number=578 hash=b2ca0f…926da3
INFO [04-27|14:59:11.190] Commit new mining work                   number=579 sealhash=7fde9c…3315bf uncles=0 txs=0 gas=0     fees=0        elapsed=8.977ms
INFO [04-27|14:59:14.149] Successfully sealed new block            number=579 sealhash=7fde9c…3315bf hash=00e7e9…2e0256 elapsed=2.968s
INFO [04-27|14:59:14.149] 🔗 block reached canonical chain          number=572 hash=a8f119…8d07be
INFO [04-27|14:59:14.158] 🔨 mined potential block                  number=579 hash=00e7e9…2e0256
INFO [04-27|14:59:14.158] Commit new mining work                   number=580 sealhash=0f920b…f30bb7 uncles=0 txs=0 gas=0     fees=0        elapsed=8.981ms
INFO [04-27|14:59:14.741] Successfully sealed new block            number=580 sealhash=0f920b…f30bb7 hash=bbd07e…ba2e5c elapsed=591.417ms
INFO [04-27|14:59:14.741] 🔗 block reached canonical chain          number=573 hash=628d7d…c1b016
INFO [04-27|14:59:14.752] 🔨 mined potential block                  number=580 hash=bbd07e…ba2e5c
INFO [04-27|14:59:14.752] Commit new mining work                   number=581 sealhash=d840a2…2fef95 uncles=0 txs=0 gas=0     fees=0        elapsed=10.936ms
INFO [04-27|14:59:18.964] Looking for peers                        peercount=3 tried=75  static=0
INFO [04-27|14:59:29.104] Looking for peers                        peercount=2 tried=134 static=0
INFO [04-27|14:59:39.141] Looking for peers                        peercount=1 tried=106 static=0
INFO [04-27|14:59:40.256] Successfully sealed new block            number=581 sealhash=d840a2…2fef95 hash=d4ec9d…6e1a1e elapsed=25.514s
INFO [04-27|14:59:40.257] 🔗 block reached canonical chain          number=574 hash=5785d4…07919a
INFO [04-27|14:59:40.264] Commit new mining work                   number=582 sealhash=fdbb90…cee0c0 uncles=0 txs=0 gas=0     fees=0        elapsed=7.978ms
INFO [04-27|14:59:40.264] 🔨 mined potential block                  number=581 hash=d4ec9d…6e1a1e
INFO [04-27|14:59:43.833] Successfully sealed new block            number=582 sealhash=fdbb90…cee0c0 hash=7b8b49…2e9ea9 elapsed=3.576s
INFO [04-27|14:59:43.834] 🔗 block reached canonical chain          number=575 hash=807334…16a130
INFO [04-27|14:59:43.842] 🔨 mined potential block                  number=582 hash=7b8b49…2e9ea9
INFO [04-27|14:59:43.842] Commit new mining work                   number=583 sealhash=87e739…335373 uncles=0 txs=0 gas=0     fees=0        elapsed=8.953ms
INFO [04-27|14:59:44.352] Successfully sealed new block            number=583 sealhash=87e739…335373 hash=4652c4…9a4054 elapsed=517.616ms
INFO [04-27|14:59:44.352] 🔗 block reached canonical chain          number=576 hash=7819c3…084d70
INFO [04-27|14:59:44.360] 🔨 mined potential block                  number=583 hash=4652c4…9a4054
INFO [04-27|14:59:44.360] Commit new mining work                   number=584 sealhash=ca3a54…acb804 uncles=0 txs=0 gas=0     fees=0        elapsed=7.981ms
INFO [04-27|14:59:49.148] Looking for peers                        peercount=2 tried=72  static=0
INFO [04-27|14:59:59.171] Looking for peers                        peercount=2 tried=176 static=0
INFO [04-27|15:00:00.342] Successfully sealed new block            number=584 sealhash=ca3a54…acb804 hash=1a50c0…f00c48 elapsed=15.990s
INFO [04-27|15:00:00.343] 🔗 block reached canonical chain          number=577 hash=356185…f1cf05
INFO [04-27|15:00:00.350] 🔨 mined potential block                  number=584 hash=1a50c0…f00c48
INFO [04-27|15:00:00.350] Commit new mining work                   number=585 sealhash=ea34e8…a735c7 uncles=0 txs=0 gas=0     fees=0        elapsed=7.945ms
INFO [04-27|15:00:08.730] Successfully sealed new block            number=585 sealhash=ea34e8…a735c7 hash=9b2c36…0761a3 elapsed=8.387s
INFO [04-27|15:00:08.731] 🔗 block reached canonical chain          number=578 hash=b2ca0f…926da3
INFO [04-27|15:00:08.739] 🔨 mined potential block                  number=585 hash=9b2c36…0761a3
INFO [04-27|15:00:08.739] Commit new mining work                   number=586 sealhash=4cc1da…170461 uncles=0 txs=0 gas=0     fees=0        elapsed=8.976ms
INFO [04-27|15:00:09.215] Looking for peers                        peercount=1 tried=112 static=0
INFO [04-27|15:00:17.889] Got interrupt, shutting down...
INFO [04-27|15:00:17.893] IPC endpoint closed                      url=\\\\.\\pipe\\geth.ipc
INFO [04-27|15:00:17.897] Ethereum protocol stopped
INFO [04-27|15:00:17.900] Transaction pool stopped
INFO [04-27|15:00:17.902] Writing cached state to disk             block=585 hash=9b2c36…0761a3 root=c0b254…b92809
INFO [04-27|15:00:17.906] Persisted trie from memory database      nodes=8 size=2.30KiB time=0s gcnodes=1371 gcsize=496.71KiB gctime=1.9947ms livenodes=382 livesize=138.04KiB
INFO [04-27|15:00:17.911] Writing cached state to disk             block=584 hash=1a50c0…f00c48 root=f23bf2…563f94
INFO [04-27|15:00:17.914] Persisted trie from memory database      nodes=3 size=1.09KiB time=0s gcnodes=0    gcsize=0.00B     gctime=0s       livenodes=379 livesize=136.95KiB
INFO [04-27|15:00:17.920] Writing cached state to disk             block=458 hash=1b102c…1b7c14 root=8ff094…dbde8c
INFO [04-27|15:00:17.925] Persisted trie from memory database      nodes=3 size=1.09KiB time=0s gcnodes=0    gcsize=0.00B     gctime=0s       livenodes=376 livesize=135.86KiB
INFO [04-27|15:00:17.931] Blockchain stopped

19293@DESKTOP-IJUOLJJ MINGW64 ~/Blockchain-Tools
$