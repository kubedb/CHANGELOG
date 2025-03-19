# KubeDB v2025.3.19-rc.0 (2025-03-19)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.53.0-rc.0](https://github.com/kubedb/apimachinery/releases/tag/v0.53.0-rc.0)

- [c1c97c5d](https://github.com/kubedb/apimachinery/commit/c1c97c5d7) Update deps
- [e7fb1125](https://github.com/kubedb/apimachinery/commit/e7fb1125f) Move & convert oldDB validators to new-webhook signature (#1428)
- [d82a3f17](https://github.com/kubedb/apimachinery/commit/d82a3f17c) Register cassandra autoscaler types
- [4d0febcc](https://github.com/kubedb/apimachinery/commit/4d0febcc5) Rename SecretSource -> SecretStore
- [f80d5dc7](https://github.com/kubedb/apimachinery/commit/f80d5dc74) Move webhooks folder inside pkg
- [5e31d682](https://github.com/kubedb/apimachinery/commit/5e31d6825) update ferretdb autoscaler api (#1427)
- [5d295e37](https://github.com/kubedb/apimachinery/commit/5d295e374) Move & convert opsRequest validator files to new webhook style (#1425)
- [051711da](https://github.com/kubedb/apimachinery/commit/051711da2) Update deps
- [70c28b34](https://github.com/kubedb/apimachinery/commit/70c28b34c) Update autoscaler webhooks (#1424)
- [a9caf6ac](https://github.com/kubedb/apimachinery/commit/a9caf6acf) Update deps
- [999c0b80](https://github.com/kubedb/apimachinery/commit/999c0b803) Update deps
- [ee518661](https://github.com/kubedb/apimachinery/commit/ee5186618) Fix build (#1423)
- [28f8a1d6](https://github.com/kubedb/apimachinery/commit/28f8a1d6d) Add FerretDB replication support (#1420)
- [4fcb10d1](https://github.com/kubedb/apimachinery/commit/4fcb10d1c) Integrate virtual-secret in `authSecret` (#1414)
- [7b3b2d57](https://github.com/kubedb/apimachinery/commit/7b3b2d57a) Remove defaultclient from kafka api group (#1419)
- [3b730ac8](https://github.com/kubedb/apimachinery/commit/3b730ac81) Add Engine-type in Redis-Version to distinguish valkey version (#1410)
- [f5d0d929](https://github.com/kubedb/apimachinery/commit/f5d0d929f) Fix ChangeRequest Status type (#1411)
- [9493bd16](https://github.com/kubedb/apimachinery/commit/9493bd16d) Update schema manager to new webhook style (#1421)
- [dc851d6f](https://github.com/kubedb/apimachinery/commit/dc851d6fb) Increate MSSQL CPU Request (#1412)
- [38bb7a72](https://github.com/kubedb/apimachinery/commit/38bb7a72c) Add Operator Sharding Support (#1415)
- [5db581f5](https://github.com/kubedb/apimachinery/commit/5db581f54) Use k8s 1.32 client libs (#1405)
- [64f26616](https://github.com/kubedb/apimachinery/commit/64f266165) Set securityContext for exporter containers (#1418)
- [8673786a](https://github.com/kubedb/apimachinery/commit/8673786aa) Add IsCluster inside Replication (#1416)
- [d57315cd](https://github.com/kubedb/apimachinery/commit/d57315cdf) Add regex to kubedb object names (#1417)
- [c3871c5d](https://github.com/kubedb/apimachinery/commit/c3871c5de) Test against k8s 1.32 (#1409)
- [5065873e](https://github.com/kubedb/apimachinery/commit/5065873e2) Test against k8s 1.32 (#1407)
- [93b6bea8](https://github.com/kubedb/apimachinery/commit/93b6bea8a) Fix CI (#1408)
- [d685cb86](https://github.com/kubedb/apimachinery/commit/d685cb862) Add gitops apis (#1406)
- [a75252a4](https://github.com/kubedb/apimachinery/commit/a75252a4e) Add PostgresOpsRequest ReconnectStandby, ForceFailover, SetRaftKeyPair (#1404)
- [75a4e2b5](https://github.com/kubedb/apimachinery/commit/75a4e2b5a) Test against k8s 1.32 (#1403)
- [d38a170f](https://github.com/kubedb/apimachinery/commit/d38a170fe) Use Go 1.24 (#1401)
- [6d24fef2](https://github.com/kubedb/apimachinery/commit/6d24fef28) Use Go 1.24 (#1400)
- [bd6cc66b](https://github.com/kubedb/apimachinery/commit/bd6cc66bd) Defaulting DB namespace to init archiver fields (#1399)
- [39cd66e4](https://github.com/kubedb/apimachinery/commit/39cd66e47) Fix druid security context issue (#1396)
- [47139029](https://github.com/kubedb/apimachinery/commit/471390290) Defaulting internal zookeper (#1398)
- [2f6d49a9](https://github.com/kubedb/apimachinery/commit/2f6d49a92) security-context for pgbouncer (#1339)
- [60581b73](https://github.com/kubedb/apimachinery/commit/60581b73b) Update deps
- [b51e119e](https://github.com/kubedb/apimachinery/commit/b51e119e3) make some defaulting funcs public (#1395)
- [00ea2f07](https://github.com/kubedb/apimachinery/commit/00ea2f07f) Update for release KubeStash@v2025.2.10 (#1397)
- [023d2f62](https://github.com/kubedb/apimachinery/commit/023d2f628) Update security context defaulting for solr (#1394)
- [3a00131d](https://github.com/kubedb/apimachinery/commit/3a00131dd) Update Kafka Default Resource to Memory Intensive (#1393)
- [1b380ea0](https://github.com/kubedb/apimachinery/commit/1b380ea04) Seperate up the connectOptions for gw & inCluster (#1391)
- [7f58d039](https://github.com/kubedb/apimachinery/commit/7f58d0390) Return the reason for not allowing license restrictions (#1392)



## [kubedb/dashboard-restic-plugin](https://github.com/kubedb/dashboard-restic-plugin)

### [v0.11.0-rc.0](https://github.com/kubedb/dashboard-restic-plugin/releases/tag/v0.11.0-rc.0)

- [bdd5aa5](https://github.com/kubedb/dashboard-restic-plugin/commit/bdd5aa5) Prepare for release v0.11.0-rc.0 (#35)
- [cff8f60](https://github.com/kubedb/dashboard-restic-plugin/commit/cff8f60) Prepare for release v0.10.0 (#34)
- [d357bdc](https://github.com/kubedb/dashboard-restic-plugin/commit/d357bdc) Use Go 1.24 (#33)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.8.0-rc.0](https://github.com/kubedb/db-client-go/releases/tag/v0.8.0-rc.0)

- [2beb4691](https://github.com/kubedb/db-client-go/commit/2beb4691) Prepare for release v0.8.0-rc.0 (#167)
- [214a0339](https://github.com/kubedb/db-client-go/commit/214a0339) Remove decoding of data (#166)
- [0303ed1c](https://github.com/kubedb/db-client-go/commit/0303ed1c) Updates for integrating `Virtual-Secrets` (#165)
- [056c3ddf](https://github.com/kubedb/db-client-go/commit/056c3ddf) Fix TLS Handshake Issue for MySQL 5.7.x (#164)
- [b3fa7654](https://github.com/kubedb/db-client-go/commit/b3fa7654) Prepare for release v0.7.0 (#163)
- [993a561c](https://github.com/kubedb/db-client-go/commit/993a561c) Add method to get shard information for ES (#160)
- [3fa565a9](https://github.com/kubedb/db-client-go/commit/3fa565a9) Use Go 1.24 (#162)



## [kubedb/mongodb](https://github.com/kubedb/mongodb)

### [v0.46.0-rc.0](https://github.com/kubedb/mongodb/releases/tag/v0.46.0-rc.0)

- [d81d312a](https://github.com/kubedb/mongodb/commit/d81d312a8) Prepare for release v0.46.0-rc.0 (#697)
- [ce969181](https://github.com/kubedb/mongodb/commit/ce969181d) Restructure admission webhook (#696)
- [ce4b97c8](https://github.com/kubedb/mongodb/commit/ce4b97c87) Implement operator-sharding; Add IRSA annotation in sideick (#694)
- [68a81a75](https://github.com/kubedb/mongodb/commit/68a81a756) Update to k8s v32 (#692)
- [f9fe924e](https://github.com/kubedb/mongodb/commit/f9fe924e7) Merge pull request #690 from kubedb/mongo-ci-fix
- [77483bab](https://github.com/kubedb/mongodb/commit/77483bab5) change manual trigger, default case
- [ae1291b1](https://github.com/kubedb/mongodb/commit/ae1291b1b) add dropdown options to input sections
- [6a0a313a](https://github.com/kubedb/mongodb/commit/6a0a313a9) check after matrix profile remove
- [e80ca10f](https://github.com/kubedb/mongodb/commit/e80ca10f7) review changes done
- [3c14acc9](https://github.com/kubedb/mongodb/commit/3c14acc97) separate dynamic profiles
- [2aa206d8](https://github.com/kubedb/mongodb/commit/2aa206d8b) nhasdg
- [30555b40](https://github.com/kubedb/mongodb/commit/30555b400) fix checkout repo
- [0374303a](https://github.com/kubedb/mongodb/commit/0374303ae) checkout from test to working repo
- [47616663](https://github.com/kubedb/mongodb/commit/47616663a) add db_mode
- [5a261d5b](https://github.com/kubedb/mongodb/commit/5a261d5bf) wip
- [fad5ac51](https://github.com/kubedb/mongodb/commit/fad5ac51d) Set default resources on the walg container
- [5d6bedb4](https://github.com/kubedb/mongodb/commit/5d6bedb47) Install ace-user-roles; Run tests twice a week (#691)
- [7d7c2879](https://github.com/kubedb/mongodb/commit/7d7c28790) Prepare for release v0.45.0 (#689)
- [4009564e](https://github.com/kubedb/mongodb/commit/4009564ef) Test against k8s 1.32 (#688)
- [b0f42186](https://github.com/kubedb/mongodb/commit/b0f421864) Use Go 1.24 (#687)
- [f8093b11](https://github.com/kubedb/mongodb/commit/f8093b115) Create super user before oplog-restore (#686)
- [12d97bb1](https://github.com/kubedb/mongodb/commit/12d97bb19) Report namespace info with billing event (#685)
- [82d112ae](https://github.com/kubedb/mongodb/commit/82d112ae2) Show the reason for not satifying license restriction (#684)
- [03e6623d](https://github.com/kubedb/mongodb/commit/03e6623d6) Use testrig



## [kubedb/singlestore](https://github.com/kubedb/singlestore)

### [v0.8.0-rc.0](https://github.com/kubedb/singlestore/releases/tag/v0.8.0-rc.0)

- [78123100](https://github.com/kubedb/singlestore/commit/78123100) Prepare for release v0.8.0-rc.0 (#67)
- [4b4ca182](https://github.com/kubedb/singlestore/commit/4b4ca182) update deps (#66)
- [52126e70](https://github.com/kubedb/singlestore/commit/52126e70) Install ace-user-roles and Add Operator Sharding (#64)
- [9d9e89a6](https://github.com/kubedb/singlestore/commit/9d9e89a6) Update to k8s v1.32 (#65)
- [2781fd58](https://github.com/kubedb/singlestore/commit/2781fd58) Prepare for release v0.7.0 (#63)
- [e7c24277](https://github.com/kubedb/singlestore/commit/e7c24277) Test against k8s 1.32 (#62)
- [a043af3d](https://github.com/kubedb/singlestore/commit/a043af3d) Use Go 1.24 (#61)
- [d3c90016](https://github.com/kubedb/singlestore/commit/d3c90016) Report namespace info with billing event (#60)
- [25728a9e](https://github.com/kubedb/singlestore/commit/25728a9e) Update license log & e2e machine



## [kubedb/xtrabackup-restic-plugin](https://github.com/kubedb/xtrabackup-restic-plugin)

### [v0.2.0-rc.0](https://github.com/kubedb/xtrabackup-restic-plugin/releases/tag/v0.2.0-rc.0)




