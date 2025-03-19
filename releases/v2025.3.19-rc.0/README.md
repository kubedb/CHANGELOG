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



## [kubedb/cassandra](https://github.com/kubedb/cassandra)

### [v0.6.0-rc.0](https://github.com/kubedb/cassandra/releases/tag/v0.6.0-rc.0)

- [47f7e4fe](https://github.com/kubedb/cassandra/commit/47f7e4fe) Prepare for release v0.6.0-rc.0 (#29)
- [458feaa9](https://github.com/kubedb/cassandra/commit/458feaa9) Update webhook path (#28)
- [b592f3d3](https://github.com/kubedb/cassandra/commit/b592f3d3) Install ace-user-roles and Add Operator Sharding (#25)
- [a931ee8b](https://github.com/kubedb/cassandra/commit/a931ee8b) Update to k8s v1.32 (#27)
- [f8c20588](https://github.com/kubedb/cassandra/commit/f8c20588) Prepare for release v0.5.0 (#24)
- [d8682ce7](https://github.com/kubedb/cassandra/commit/d8682ce7) Test against k8s 1.32 (#23)
- [1683194c](https://github.com/kubedb/cassandra/commit/1683194c) Use Go 1.24 (#22)
- [5a9efd1a](https://github.com/kubedb/cassandra/commit/5a9efd1a) Merge pull request #21 from kubedb/ns
- [89c1e37c](https://github.com/kubedb/cassandra/commit/89c1e37c) Report namespace info with billing event
- [5d389517](https://github.com/kubedb/cassandra/commit/5d389517) Update license log & e2e machine



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



## [kubedb/druid](https://github.com/kubedb/druid)

### [v0.8.0-rc.0](https://github.com/kubedb/druid/releases/tag/v0.8.0-rc.0)

- [bb2ae901](https://github.com/kubedb/druid/commit/bb2ae901) Prepare for release v0.8.0-rc.0 (#79)
- [eb2421c5](https://github.com/kubedb/druid/commit/eb2421c5) Update webhook path (#78)
- [2a8160d1](https://github.com/kubedb/druid/commit/2a8160d1) Add Operator Sharding Support (#77)
- [1408db1d](https://github.com/kubedb/druid/commit/1408db1d) Fix webhook call
- [f6b65aeb](https://github.com/kubedb/druid/commit/f6b65aeb) Setup new webhook style; Update to k8s v1.32 (#76)
- [8dc34f78](https://github.com/kubedb/druid/commit/8dc34f78) Prepare for release v0.7.0 (#75)
- [507e27de](https://github.com/kubedb/druid/commit/507e27de) Test against k8s 1.32 (#74)
- [ec664f20](https://github.com/kubedb/druid/commit/ec664f20) Use Go 1.24 (#73)
- [bf3ae1d8](https://github.com/kubedb/druid/commit/bf3ae1d8) Fix druid security context issue (#71)
- [88e4905c](https://github.com/kubedb/druid/commit/88e4905c) Report namespace info with billing event (#72)
- [4f4062b6](https://github.com/kubedb/druid/commit/4f4062b6) Update license log & e2e machine



## [kubedb/elasticsearch](https://github.com/kubedb/elasticsearch)

### [v0.53.0-rc.0](https://github.com/kubedb/elasticsearch/releases/tag/v0.53.0-rc.0)

- [0884a60d](https://github.com/kubedb/elasticsearch/commit/0884a60de) Prepare for release v0.53.0-rc.0 (#760)
- [3790689f](https://github.com/kubedb/elasticsearch/commit/3790689f4) Restructure elasticsearch webhook (#759)
- [bc877df4](https://github.com/kubedb/elasticsearch/commit/bc877df46) Add operator sharding for Elasticsearch (#758)
- [b8937d5b](https://github.com/kubedb/elasticsearch/commit/b8937d5b2) Webhook changes for k8s 1.32 (#757)
- [01aa7b63](https://github.com/kubedb/elasticsearch/commit/01aa7b63f) Prepare for release v0.52.0 (#756)
- [0ce1d5a2](https://github.com/kubedb/elasticsearch/commit/0ce1d5a23) Test against k8s 1.32 (#755)
- [a5a3c257](https://github.com/kubedb/elasticsearch/commit/a5a3c2576) Use Go 1.24 (#754)
- [2600d5bd](https://github.com/kubedb/elasticsearch/commit/2600d5bd5) Report namespace info with billing event (#753)
- [19980821](https://github.com/kubedb/elasticsearch/commit/19980821a) Update license restriction log (#752)
- [19ea3a94](https://github.com/kubedb/elasticsearch/commit/19ea3a942) Use testrig



## [kubedb/ferretdb](https://github.com/kubedb/ferretdb)

### [v0.8.0-rc.0](https://github.com/kubedb/ferretdb/releases/tag/v0.8.0-rc.0)

- [178a987c](https://github.com/kubedb/ferretdb/commit/178a987c) Prepare for release v0.8.0-rc.0 (#68)
- [aa8bb0a9](https://github.com/kubedb/ferretdb/commit/aa8bb0a9) Fix backend init scripts and labels-selectors (#67)
- [9a5064dc](https://github.com/kubedb/ferretdb/commit/9a5064dc) Add FerretDB replication support (#66)
- [6b72cb54](https://github.com/kubedb/ferretdb/commit/6b72cb54) Fix security context for backend pg and add operator sharding (#60)
- [cfd63de6](https://github.com/kubedb/ferretdb/commit/cfd63de6) Setup new webhook style; Update to k8s v1.32 (#65)
- [175f1523](https://github.com/kubedb/ferretdb/commit/175f1523) Prepare for release v0.7.0 (#64)
- [15975b72](https://github.com/kubedb/ferretdb/commit/15975b72) Test against k8s 1.32 (#63)
- [4e2c27ee](https://github.com/kubedb/ferretdb/commit/4e2c27ee) Use Go 1.24 (#62)
- [2b50a0d6](https://github.com/kubedb/ferretdb/commit/2b50a0d6) Report namespace info with billing event (#61)
- [98674271](https://github.com/kubedb/ferretdb/commit/98674271) Update license log & e2e machine



## [kubedb/gitops](https://github.com/kubedb/gitops)

### [v0.1.0-rc.0](https://github.com/kubedb/gitops/releases/tag/v0.1.0-rc.0)

- [643d32d5](https://github.com/kubedb/gitops/commit/643d32d5) Prepare for release v0.1.0-rc.0 (#8)
- [79c495f8](https://github.com/kubedb/gitops/commit/79c495f8) Add Initial Setup for Dbs (#6)
- [466aad87](https://github.com/kubedb/gitops/commit/466aad87) Use firecracker runners for ci
- [741059fa](https://github.com/kubedb/gitops/commit/741059fa) Add license header



## [kubedb/kubedb-verifier](https://github.com/kubedb/kubedb-verifier)

### [v0.4.0-rc.0](https://github.com/kubedb/kubedb-verifier/releases/tag/v0.4.0-rc.0)

- [8b3a5e6](https://github.com/kubedb/kubedb-verifier/commit/8b3a5e6) Prepare for release v0.4.0-rc.0 (#15)
- [1033b54](https://github.com/kubedb/kubedb-verifier/commit/1033b54) Prepare for release v0.3.0 (#14)
- [7a08962](https://github.com/kubedb/kubedb-verifier/commit/7a08962) Use Go 1.24 (#13)
- [1e55a38](https://github.com/kubedb/kubedb-verifier/commit/1e55a38) Disable image caching in setup-qemu action (#12)



## [kubedb/mariadb-archiver](https://github.com/kubedb/mariadb-archiver)

### [v0.13.0-rc.0](https://github.com/kubedb/mariadb-archiver/releases/tag/v0.13.0-rc.0)

- [a7e37d89](https://github.com/kubedb/mariadb-archiver/commit/a7e37d89) Prepare for release v0.13.0-rc.0 (#45)
- [70edd7d5](https://github.com/kubedb/mariadb-archiver/commit/70edd7d5) Prepare for release v0.12.0 (#44)
- [fabf49b0](https://github.com/kubedb/mariadb-archiver/commit/fabf49b0) Use Go 1.24 (#43)



## [kubedb/memcached](https://github.com/kubedb/memcached)

### [v0.46.0-rc.0](https://github.com/kubedb/memcached/releases/tag/v0.46.0-rc.0)

- [b5ddb698](https://github.com/kubedb/memcached/commit/b5ddb698e) Prepare for release v0.46.0-rc.0 (#493)
- [816d7472](https://github.com/kubedb/memcached/commit/816d7472e) Restructure admission webhook (#492)
- [5ee33f9c](https://github.com/kubedb/memcached/commit/5ee33f9c3) Add operator sharding support; Update ci & makefile (#490)
- [93a42e71](https://github.com/kubedb/memcached/commit/93a42e718) Update to k8s v32 (#491)
- [d0bf662b](https://github.com/kubedb/memcached/commit/d0bf662b4) Prepare for release v0.45.0 (#489)
- [dc8343bc](https://github.com/kubedb/memcached/commit/dc8343bce) Test against k8s 1.32 (#488)
- [27399464](https://github.com/kubedb/memcached/commit/273994640) Use Go 1.24 (#487)
- [5757ac2c](https://github.com/kubedb/memcached/commit/5757ac2ca) Report namespace info with billing event (#486)
- [ae26c91e](https://github.com/kubedb/memcached/commit/ae26c91e7) Run e2e Tests on testrig & show the reason for not satisfying license restriction (#485)



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



## [kubedb/mssql-coordinator](https://github.com/kubedb/mssql-coordinator)

### [v0.8.0-rc.0](https://github.com/kubedb/mssql-coordinator/releases/tag/v0.8.0-rc.0)

- [cbb75c6a](https://github.com/kubedb/mssql-coordinator/commit/cbb75c6a) Prepare for release v0.8.0-rc.0 (#32)
- [1d9c6500](https://github.com/kubedb/mssql-coordinator/commit/1d9c6500) Prepare for release v0.7.0 (#31)
- [374ddac6](https://github.com/kubedb/mssql-coordinator/commit/374ddac6) Use Go 1.24 (#30)



## [kubedb/mssqlserver-walg-plugin](https://github.com/kubedb/mssqlserver-walg-plugin)

### [v0.7.0-rc.0](https://github.com/kubedb/mssqlserver-walg-plugin/releases/tag/v0.7.0-rc.0)

- [2d7f303](https://github.com/kubedb/mssqlserver-walg-plugin/commit/2d7f303) Prepare for release v0.7.0-rc.0 (#21)
- [4b98360](https://github.com/kubedb/mssqlserver-walg-plugin/commit/4b98360) Prepare for release v0.6.0 (#20)
- [ca44e86](https://github.com/kubedb/mssqlserver-walg-plugin/commit/ca44e86) Use Go 1.24 (#19)



## [kubedb/mysql](https://github.com/kubedb/mysql)

### [v0.46.0-rc.0](https://github.com/kubedb/mysql/releases/tag/v0.46.0-rc.0)

- [aa15539f](https://github.com/kubedb/mysql/commit/aa15539f5) Prepare for release v0.46.0-rc.0 (#677)
- [7e9aa056](https://github.com/kubedb/mysql/commit/7e9aa0564) Restructure admission webhook (#676)
- [04e0c7f0](https://github.com/kubedb/mysql/commit/04e0c7f07) Install ace-user-roles; Run tests twice a week (#674)
- [d107c361](https://github.com/kubedb/mysql/commit/d107c3614) Update to k8s v32 (#675)
- [8f36148e](https://github.com/kubedb/mysql/commit/8f36148eb) Lower Sidekick Default Resource (#673)
- [7cb70170](https://github.com/kubedb/mysql/commit/7cb701700) Prepare for release v0.45.0 (#672)
- [78f18ebc](https://github.com/kubedb/mysql/commit/78f18ebc2) Test against k8s 1.32 (#671)
- [7b8439cf](https://github.com/kubedb/mysql/commit/7b8439cf1) Use Go 1.24 (#670)
- [c7c9ffec](https://github.com/kubedb/mysql/commit/c7c9ffec3) Report namespace info with billing event (#669)
- [1db63846](https://github.com/kubedb/mysql/commit/1db638462) Show the reason for not satifying license restriction (#668)
- [8c49a6ea](https://github.com/kubedb/mysql/commit/8c49a6eae) Use testrig
- [2cd44d41](https://github.com/kubedb/mysql/commit/2cd44d411) Fix license restriction (#667)



## [kubedb/mysql-coordinator](https://github.com/kubedb/mysql-coordinator)

### [v0.31.0-rc.0](https://github.com/kubedb/mysql-coordinator/releases/tag/v0.31.0-rc.0)

- [8750fb07](https://github.com/kubedb/mysql-coordinator/commit/8750fb07) Prepare for release v0.31.0-rc.0 (#138)
- [026cf350](https://github.com/kubedb/mysql-coordinator/commit/026cf350) Fix TLS Handshake Issue for MySQL 5.7.x (#137)
- [f00b8511](https://github.com/kubedb/mysql-coordinator/commit/f00b8511) Prepare for release v0.30.0 (#136)
- [1611bdf9](https://github.com/kubedb/mysql-coordinator/commit/1611bdf9) Use Go 1.24 (#135)



## [kubedb/pgpool](https://github.com/kubedb/pgpool)

### [v0.8.0-rc.0](https://github.com/kubedb/pgpool/releases/tag/v0.8.0-rc.0)

- [f6639b78](https://github.com/kubedb/pgpool/commit/f6639b78) Prepare for release v0.8.0-rc.0 (#70)
- [683a8a1f](https://github.com/kubedb/pgpool/commit/683a8a1f) update webhook path (#69)
- [f8a989de](https://github.com/kubedb/pgpool/commit/f8a989de) Implement operator-sharding; Install ace-user-roles (#67)
- [6aee4ccc](https://github.com/kubedb/pgpool/commit/6aee4ccc) Setup new webhook style; Update to k8s v1.32 (#68)
- [8eb95eaf](https://github.com/kubedb/pgpool/commit/8eb95eaf) Prepare for release v0.7.0 (#66)
- [845d2edf](https://github.com/kubedb/pgpool/commit/845d2edf) Test against k8s 1.32 (#65)
- [f04be287](https://github.com/kubedb/pgpool/commit/f04be287) Use Go 1.24 (#64)
- [4c2e65b2](https://github.com/kubedb/pgpool/commit/4c2e65b2) Pgpool get fixed & Report namespace info with billing event (#63)
- [56d97ff5](https://github.com/kubedb/pgpool/commit/56d97ff5) Run e2e tests on testrig & Show the reason for not satifying license restriction (#62)



## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.53.0-rc.0](https://github.com/kubedb/postgres/releases/tag/v0.53.0-rc.0)

- [d794ce54](https://github.com/kubedb/postgres/commit/d794ce54c) Prepare for release v0.53.0-rc.0 (#805)
- [4c1923e2](https://github.com/kubedb/postgres/commit/4c1923e25) Refactor Postgres Webhook (#804)
- [4d1e1989](https://github.com/kubedb/postgres/commit/4d1e19894) Integrate virtual-secret in postgres (#799)
- [e22f77c4](https://github.com/kubedb/postgres/commit/e22f77c42) Update IRSA annotations (#802)
- [bc42a794](https://github.com/kubedb/postgres/commit/bc42a7947) Update Postgres With ShardConfiguration Related Changes (#800)
- [aca0e41e](https://github.com/kubedb/postgres/commit/aca0e41e7) support for kubernetes v1.32.x (#801)
- [3bdacec0](https://github.com/kubedb/postgres/commit/3bdacec07) Run Provisioner Tests On Monday + Friday, Fix Makefile (#797)
- [a9165b82](https://github.com/kubedb/postgres/commit/a9165b828) Lower Sidekick Default Resource (#798)
- [77658501](https://github.com/kubedb/postgres/commit/776585018) Prepare for release v0.52.0 (#796)
- [5a24b48e](https://github.com/kubedb/postgres/commit/5a24b48ed) Test against k8s 1.32 (#795)
- [ad5ada20](https://github.com/kubedb/postgres/commit/ad5ada201) Use Go 1.24 (#794)
- [9fd8f70a](https://github.com/kubedb/postgres/commit/9fd8f70ae) Report namespace info with billing event (#793)
- [f3158b9d](https://github.com/kubedb/postgres/commit/f3158b9de) update log (#792)
- [a2fe345e](https://github.com/kubedb/postgres/commit/a2fe345e3) Run e2e tests on testrig (#791)



## [kubedb/redis](https://github.com/kubedb/redis)

### [v0.46.0-rc.0](https://github.com/kubedb/redis/releases/tag/v0.46.0-rc.0)

- [abbcc896](https://github.com/kubedb/redis/commit/abbcc8962) Prepare for release v0.46.0-rc.0 (#588)
- [7f66d703](https://github.com/kubedb/redis/commit/7f66d703b) Restructure admission webhook (#587)
- [5bcfeff7](https://github.com/kubedb/redis/commit/5bcfeff71) Add Operator Sharding Support (#586)
- [03f9ebd5](https://github.com/kubedb/redis/commit/03f9ebd54) Update to k8s v32 (#585)
- [b5a67c90](https://github.com/kubedb/redis/commit/b5a67c907) Install ace-user-roles; Run tests twice a week (#583)
- [1bd0ce8e](https://github.com/kubedb/redis/commit/1bd0ce8ed) Prepare for release v0.45.0 (#582)
- [6bceb509](https://github.com/kubedb/redis/commit/6bceb5097) Test against k8s 1.32 (#581)
- [d09543ec](https://github.com/kubedb/redis/commit/d09543ec0) Use Go 1.24 (#580)
- [69b304d7](https://github.com/kubedb/redis/commit/69b304d7a) Fix and Improve Cluster Health Check + Add Cluster Pod Role Label (#578)
- [029f1ade](https://github.com/kubedb/redis/commit/029f1ade0) Report namespace info with billing event (#579)
- [50b6b3b8](https://github.com/kubedb/redis/commit/50b6b3b84) Run e2e tests on testrig & Show the reason for not satifying license (#577)



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



## [kubedb/singlestore-restic-plugin](https://github.com/kubedb/singlestore-restic-plugin)

### [v0.11.0-rc.0](https://github.com/kubedb/singlestore-restic-plugin/releases/tag/v0.11.0-rc.0)

- [e939734](https://github.com/kubedb/singlestore-restic-plugin/commit/e939734) Prepare for release v0.11.0-rc.0 (#39)
- [b3b6b4b](https://github.com/kubedb/singlestore-restic-plugin/commit/b3b6b4b) Prepare for release v0.10.0 (#38)
- [4cc4d3d](https://github.com/kubedb/singlestore-restic-plugin/commit/4cc4d3d) Use Go 1.24 (#37)



## [kubedb/solr](https://github.com/kubedb/solr)

### [v0.8.0-rc.0](https://github.com/kubedb/solr/releases/tag/v0.8.0-rc.0)

- [a2a12869](https://github.com/kubedb/solr/commit/a2a12869) Prepare for release v0.8.0-rc.0 (#78)
- [a68d5e84](https://github.com/kubedb/solr/commit/a68d5e84) Fix dependency for webhook (#77)
- [2322338c](https://github.com/kubedb/solr/commit/2322338c) Add operator sharding support for solr (#76)
- [792ceb13](https://github.com/kubedb/solr/commit/792ceb13) Webhook changes for k8s 1.32 (#75)
- [3cd88780](https://github.com/kubedb/solr/commit/3cd88780) Prepare for release v0.7.0 (#74)
- [9ae38877](https://github.com/kubedb/solr/commit/9ae38877) Test against k8s 1.32 (#73)
- [7db0eee6](https://github.com/kubedb/solr/commit/7db0eee6) Use Go 1.24 (#72)
- [bd805cac](https://github.com/kubedb/solr/commit/bd805cac) Configure internal zookeeper (#71)
- [32d513cd](https://github.com/kubedb/solr/commit/32d513cd) Update petset defaulter for security context (#70)
- [b405f209](https://github.com/kubedb/solr/commit/b405f209) Update workflow and license restriction log (#69)



## [kubedb/xtrabackup-restic-plugin](https://github.com/kubedb/xtrabackup-restic-plugin)

### [v0.2.0-rc.0](https://github.com/kubedb/xtrabackup-restic-plugin/releases/tag/v0.2.0-rc.0)




## [kubedb/zookeeper-restic-plugin](https://github.com/kubedb/zookeeper-restic-plugin)

### [v0.9.0-rc.0](https://github.com/kubedb/zookeeper-restic-plugin/releases/tag/v0.9.0-rc.0)

- [deb7075](https://github.com/kubedb/zookeeper-restic-plugin/commit/deb7075) Prepare for release v0.9.0-rc.0 (#31)
- [e9459f4](https://github.com/kubedb/zookeeper-restic-plugin/commit/e9459f4) Prepare for release v0.8.0 (#30)
- [739367c](https://github.com/kubedb/zookeeper-restic-plugin/commit/739367c) Use Go 1.24 (#29)



