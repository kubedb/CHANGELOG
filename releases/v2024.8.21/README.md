# KubeDB v2024.8.21 (2024-08-21)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.47.0](https://github.com/kubedb/apimachinery/releases/tag/v0.47.0)

- [30dcf8b2](https://github.com/kubedb/apimachinery/commit/30dcf8b2c) Update deps
- [b9b12692](https://github.com/kubedb/apimachinery/commit/b9b126925) Update deps
- [dd5bdc21](https://github.com/kubedb/apimachinery/commit/dd5bdc219) Use Go 1.23 (#1286)
- [9206f6ff](https://github.com/kubedb/apimachinery/commit/9206f6ff7) Fix clustermetadata helper
- [5928a28c](https://github.com/kubedb/apimachinery/commit/5928a28c9) Update for release KubeStash@v2024.8.14 (#1289)
- [4b2e4872](https://github.com/kubedb/apimachinery/commit/4b2e48726) Add Halted API Field in ProxySQL and Pgbouncher (#1288)
- [f7813626](https://github.com/kubedb/apimachinery/commit/f78136264) SingleStore Ops-Request API (#1287)
- [b7bee768](https://github.com/kubedb/apimachinery/commit/b7bee7681) Test against k8s 1.31 (#1285)
- [92ab030c](https://github.com/kubedb/apimachinery/commit/92ab030c5) Add DisabledProtocols API for RabbitMQ (#1282)
- [83f69191](https://github.com/kubedb/apimachinery/commit/83f69191f) Add constants for RM additional plugins (#1280)
- [beb194a1](https://github.com/kubedb/apimachinery/commit/beb194a15) Add Kafka `halted` field & some ops helpers (#1279)
- [7334833b](https://github.com/kubedb/apimachinery/commit/7334833b5) Set the catagories correctly (#1277)
- [ddbf74f3](https://github.com/kubedb/apimachinery/commit/ddbf74f33) Add missing opsRequests (#1276)
- [6402035d](https://github.com/kubedb/apimachinery/commit/6402035de) Fix petset patch issue (#1275)
- [0f09eede](https://github.com/kubedb/apimachinery/commit/0f09eedec) Add DefaultUserCredSecretName utility for mssql
- [527c5936](https://github.com/kubedb/apimachinery/commit/527c59365) Add MSSQLServer Archiver Backup and Restore API (#1265)
- [6779210b](https://github.com/kubedb/apimachinery/commit/6779210b4) Fix build error (#1274)
- [1d9ee37f](https://github.com/kubedb/apimachinery/commit/1d9ee37f6) Add Solr ops for vertical scaling and volume expansion (#1261)
- [45c637cc](https://github.com/kubedb/apimachinery/commit/45c637cc8) Add helpers to get the archiver with maximum priority (#1266)
- [9cb2a307](https://github.com/kubedb/apimachinery/commit/9cb2a3076) Update deps
- [739f7f6f](https://github.com/kubedb/apimachinery/commit/739f7f6f1) Add MSSQL Server Monitoring APIs (#1271)
- [3f96b907](https://github.com/kubedb/apimachinery/commit/3f96b9077) Add ExtractDatabaseInfo Func for ClickHouse (#1270)
- [6d44bfc1](https://github.com/kubedb/apimachinery/commit/6d44bfc1c) Upsert config-merger initContainer via ES defaults (#1259)
- [67d23948](https://github.com/kubedb/apimachinery/commit/67d239489) Add FerretDBOpsManager (#1267)
- [08af58b8](https://github.com/kubedb/apimachinery/commit/08af58b87) pgbouncerAutoScalerSpec Update and Scheme Register (#1268)
- [c57d4c2b](https://github.com/kubedb/apimachinery/commit/c57d4c2bc) Keep the druid dependency references if given (#1272)
- [88b60875](https://github.com/kubedb/apimachinery/commit/88b60875b) Add Kafka RestProxy APIs (#1262)
- [4af05fd8](https://github.com/kubedb/apimachinery/commit/4af05fd8b) Add types for all autoscaler CRDs (#1264)
- [bf2f0aeb](https://github.com/kubedb/apimachinery/commit/bf2f0aeb4) Update Memcached Scaling APIs (#1260)
- [7b594eb1](https://github.com/kubedb/apimachinery/commit/7b594eb14) Use DeletionPolicy in etcd (#1258)
- [84475028](https://github.com/kubedb/apimachinery/commit/844750289) Skip RedisClusterSpec conversion for sentinel and standalone mode (#1257)
- [c028472b](https://github.com/kubedb/apimachinery/commit/c028472b9) Update deps
- [d3914aa5](https://github.com/kubedb/apimachinery/commit/d3914aa5e) Update deps
- [79ca732b](https://github.com/kubedb/apimachinery/commit/79ca732bd) Update Redis Ops Master -> Shards (#1255)
- [0fdb8074](https://github.com/kubedb/apimachinery/commit/0fdb8074c) Add UI chart info & remove status.gateway from db (#1256)
- [88ec29e7](https://github.com/kubedb/apimachinery/commit/88ec29e74) Set the default resources correctly (#1253)
- [cea4a328](https://github.com/kubedb/apimachinery/commit/cea4a328b) update scaling field for pgbouncer ops-request (#1244)
- [9809d94e](https://github.com/kubedb/apimachinery/commit/9809d94ee) Add API for Solr Restart OpsRequest (#1247)
- [abc86bb9](https://github.com/kubedb/apimachinery/commit/abc86bb90) Fix druid by adding Postgres as metadata storage type (#1252)
- [f8063159](https://github.com/kubedb/apimachinery/commit/f8063159a) Rename Master -> Shards in Redis (#1249)
- [5760b1e2](https://github.com/kubedb/apimachinery/commit/5760b1e2e) Fix phase tests and  use ensure container utilities (#1250)
- [d03a54a6](https://github.com/kubedb/apimachinery/commit/d03a54a6c) Report control plane and worker node stats
- [2e35ad03](https://github.com/kubedb/apimachinery/commit/2e35ad031) Use v1 api for schema-manager phase calulation (#1248)
- [41c7c89a](https://github.com/kubedb/apimachinery/commit/41c7c89a5) Correctly package up the solr constants (#1246)
- [1302836d](https://github.com/kubedb/apimachinery/commit/1302836dc) Update deps
- [01fcb668](https://github.com/kubedb/apimachinery/commit/01fcb6683) Introduce v1 api (#1236)
- [42019af5](https://github.com/kubedb/apimachinery/commit/42019af5f) Update for release KubeStash@v2024.7.1 (#1245)
- [519c2389](https://github.com/kubedb/apimachinery/commit/519c2389b) Fix druid defaulter (#1243)
- [735c4683](https://github.com/kubedb/apimachinery/commit/735c4683a) Update Druid API for internally managed metadatastore and zookeeper (#1238)
- [b4f0c7ae](https://github.com/kubedb/apimachinery/commit/b4f0c7ae5) Add AppBinding PostgresRef in FerretDB API (#1239)
- [b88f519b](https://github.com/kubedb/apimachinery/commit/b88f519ba) Add Pgpool ops-request api(Horizontal Scaling) (#1241)
- [7a9cbb53](https://github.com/kubedb/apimachinery/commit/7a9cbb53c) auth_mode changes (#1235)
- [d9228be3](https://github.com/kubedb/apimachinery/commit/d9228be31) Make package path match package name
- [dd0bd4e6](https://github.com/kubedb/apimachinery/commit/dd0bd4e6f) Move feature gates from crd-manager (#1240)
- [c1a2e274](https://github.com/kubedb/apimachinery/commit/c1a2e2745) Reset RabbitMQ default healthcker periodSecond (#1237)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.2.0](https://github.com/kubedb/db-client-go/releases/tag/v0.2.0)

- [ccd70e6f](https://github.com/kubedb/db-client-go/commit/ccd70e6f) Prepare for release v0.2.0 (#132)
- [2088c88e](https://github.com/kubedb/db-client-go/commit/2088c88e) Use Go 1.23 (#129)
- [b4a5b756](https://github.com/kubedb/db-client-go/commit/b4a5b756) Prepare for release v0.2.0-rc.3 (#131)
- [f17f15a5](https://github.com/kubedb/db-client-go/commit/f17f15a5) Update log verbosity level (#127)
- [99d096fb](https://github.com/kubedb/db-client-go/commit/99d096fb) Prepare for release v0.2.0-rc.2 (#126)
- [49bebb7e](https://github.com/kubedb/db-client-go/commit/49bebb7e) Add Kafka RestProxy (#123)
- [495ccff1](https://github.com/kubedb/db-client-go/commit/495ccff1) Add solr client. (#106)
- [01231603](https://github.com/kubedb/db-client-go/commit/01231603) Add method to set database for redis client (#125)
- [877df856](https://github.com/kubedb/db-client-go/commit/877df856) Add ZooKeeper Client (#124)
- [48d0e46f](https://github.com/kubedb/db-client-go/commit/48d0e46f) Add druid client (#122)
- [57a5122f](https://github.com/kubedb/db-client-go/commit/57a5122f) Prepare for release v0.2.0-rc.1 (#121)
- [01905848](https://github.com/kubedb/db-client-go/commit/01905848) Prepare for release v0.2.0-rc.0 (#120)
- [3b94bb3e](https://github.com/kubedb/db-client-go/commit/3b94bb3e) Add v1 api to db clients (#119)



## [kubedb/kubedb-manifest-plugin](https://github.com/kubedb/kubedb-manifest-plugin)

### [v0.10.0](https://github.com/kubedb/kubedb-manifest-plugin/releases/tag/v0.10.0)

- [13a03d8](https://github.com/kubedb/kubedb-manifest-plugin/commit/13a03d8) Prepare for release v0.10.0 (#64)
- [41f4e91](https://github.com/kubedb/kubedb-manifest-plugin/commit/41f4e91) Use Go 1.23 (#62)
- [281d889](https://github.com/kubedb/kubedb-manifest-plugin/commit/281d889) Prepare for release v0.10.0-rc.3 (#63)
- [5053a2b](https://github.com/kubedb/kubedb-manifest-plugin/commit/5053a2b) Implement MSSQLServer manifest backup and restore (#59)
- [8b1207d](https://github.com/kubedb/kubedb-manifest-plugin/commit/8b1207d) Prepare for release v0.10.0-rc.2 (#60)
- [599fa89](https://github.com/kubedb/kubedb-manifest-plugin/commit/599fa89) Prepare for release v0.10.0-rc.1 (#58)
- [7a27d11](https://github.com/kubedb/kubedb-manifest-plugin/commit/7a27d11) Prepare for release v0.10.0-rc.0 (#57)



## [kubedb/mariadb-restic-plugin](https://github.com/kubedb/mariadb-restic-plugin)

### [v0.5.0](https://github.com/kubedb/mariadb-restic-plugin/releases/tag/v0.5.0)

- [e2b6c70](https://github.com/kubedb/mariadb-restic-plugin/commit/e2b6c70) Prepare for release v0.5.0 (#22)
- [6caca1c](https://github.com/kubedb/mariadb-restic-plugin/commit/6caca1c) Use Go 1.23 (#20)
- [21c1331](https://github.com/kubedb/mariadb-restic-plugin/commit/21c1331) Prepare for release v0.5.0-rc.3 (#21)
- [4d22fb4](https://github.com/kubedb/mariadb-restic-plugin/commit/4d22fb4) Wait for ready condition instead Provisioned condition (#19)
- [73a3ff8](https://github.com/kubedb/mariadb-restic-plugin/commit/73a3ff8) Prepare for release v0.5.0-rc.2 (#18)
- [7af0211](https://github.com/kubedb/mariadb-restic-plugin/commit/7af0211) Prepare for release v0.5.0-rc.1 (#17)
- [cb733d7](https://github.com/kubedb/mariadb-restic-plugin/commit/cb733d7) Prepare for release v0.5.0-rc.0 (#16)
- [0703bcd](https://github.com/kubedb/mariadb-restic-plugin/commit/0703bcd) Use v1 api (#15)



## [kubedb/mssqlserver-archiver](https://github.com/kubedb/mssqlserver-archiver)

### [v0.1.0](https://github.com/kubedb/mssqlserver-archiver/releases/tag/v0.1.0)

- [7c04349](https://github.com/kubedb/mssqlserver-archiver/commit/7c04349) Use Go 1.23 (#3)
- [7c867e6](https://github.com/kubedb/mssqlserver-archiver/commit/7c867e6) Prepare for release v0.1.0-rc.3 (#2)



## [kubedb/mysql-archiver](https://github.com/kubedb/mysql-archiver)

### [v0.8.0](https://github.com/kubedb/mysql-archiver/releases/tag/v0.8.0)

- [2ac416d3](https://github.com/kubedb/mysql-archiver/commit/2ac416d3) Prepare for release v0.8.0 (#40)
- [aad5ec96](https://github.com/kubedb/mysql-archiver/commit/aad5ec96) Use Go 1.23 (#38)
- [2d439cb5](https://github.com/kubedb/mysql-archiver/commit/2d439cb5) Prepare for release v0.8.0-rc.3 (#39)
- [a54178b9](https://github.com/kubedb/mysql-archiver/commit/a54178b9) Prepare for release v0.8.0-rc.2 (#37)
- [f7adcd27](https://github.com/kubedb/mysql-archiver/commit/f7adcd27) Prepare for release v0.8.0-rc.1 (#36)
- [b2e2904b](https://github.com/kubedb/mysql-archiver/commit/b2e2904b) Prepare for release v0.8.0-rc.0 (#35)
- [3d92a58f](https://github.com/kubedb/mysql-archiver/commit/3d92a58f) Use v1 api (#34)



## [kubedb/mysql-csi-snapshotter-plugin](https://github.com/kubedb/mysql-csi-snapshotter-plugin)

### [v0.8.0](https://github.com/kubedb/mysql-csi-snapshotter-plugin/releases/tag/v0.8.0)

- [305d265](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/305d265) Prepare for release v0.8.0 (#27)
- [4c7c011](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/4c7c011) Use Go 1.23 (#25)
- [6136a15](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/6136a15) Prepare for release v0.8.0-rc.3 (#26)
- [1b66901](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/1b66901) Prepare for release v0.8.0-rc.2 (#24)
- [d289a41](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/d289a41) Prepare for release v0.8.0-rc.1 (#23)
- [10e977c](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/10e977c) Prepare for release v0.8.0-rc.0 (#22)
- [94ec3c9](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/94ec3c9) Use v1 api (#21)



## [kubedb/mysql-restic-plugin](https://github.com/kubedb/mysql-restic-plugin)

### [v0.10.0](https://github.com/kubedb/mysql-restic-plugin/releases/tag/v0.10.0)

- [2ceada6](https://github.com/kubedb/mysql-restic-plugin/commit/2ceada6) Prepare for release v0.10.0 (#53)
- [105ac83](https://github.com/kubedb/mysql-restic-plugin/commit/105ac83) Fixed `WaitForDBReady` check method for `waitForInitialRestore` (#52)
- [4546c98](https://github.com/kubedb/mysql-restic-plugin/commit/4546c98) Use Go 1.23 (#49)
- [cddbf96](https://github.com/kubedb/mysql-restic-plugin/commit/cddbf96) Remove Provision condition and Add Ready condition (#48)
- [79412f1](https://github.com/kubedb/mysql-restic-plugin/commit/79412f1) Prepare for release v0.10.0-rc.3 (#50)
- [4c64334](https://github.com/kubedb/mysql-restic-plugin/commit/4c64334) Prepare for release v0.10.0-rc.2 (#47)
- [ab39345](https://github.com/kubedb/mysql-restic-plugin/commit/ab39345) Prepare for release v0.10.0-rc.1 (#46)
- [83efb51](https://github.com/kubedb/mysql-restic-plugin/commit/83efb51) Prepare for release v0.10.0-rc.0 (#45)
- [fdfd535](https://github.com/kubedb/mysql-restic-plugin/commit/fdfd535) Update API and Skip mysql.user Table (#44)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.25.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.25.0)

- [e87d6c6](https://github.com/kubedb/mysql-router-init/commit/e87d6c6) Use Go 1.23 (#46)



## [kubedb/percona-xtradb-coordinator](https://github.com/kubedb/percona-xtradb-coordinator)

### [v0.20.0](https://github.com/kubedb/percona-xtradb-coordinator/releases/tag/v0.20.0)

- [2d9941e4](https://github.com/kubedb/percona-xtradb-coordinator/commit/2d9941e4) Prepare for release v0.20.0 (#80)
- [93829115](https://github.com/kubedb/percona-xtradb-coordinator/commit/93829115) Use Go 1.23 (#78)
- [c15480fc](https://github.com/kubedb/percona-xtradb-coordinator/commit/c15480fc) Prepare for release v0.20.0-rc.3 (#79)
- [b43e1a42](https://github.com/kubedb/percona-xtradb-coordinator/commit/b43e1a42) Prepare for release v0.20.0-rc.2 (#77)
- [fc57007d](https://github.com/kubedb/percona-xtradb-coordinator/commit/fc57007d) Prepare for release v0.20.0-rc.1 (#76)
- [67e20d0d](https://github.com/kubedb/percona-xtradb-coordinator/commit/67e20d0d) Prepare for release v0.20.0-rc.0 (#75)
- [6b8544b7](https://github.com/kubedb/percona-xtradb-coordinator/commit/6b8544b7) Use v1 api (#74)



## [kubedb/postgres-archiver](https://github.com/kubedb/postgres-archiver)

### [v0.8.0](https://github.com/kubedb/postgres-archiver/releases/tag/v0.8.0)

- [ae2c0be3](https://github.com/kubedb/postgres-archiver/commit/ae2c0be3) Prepare for release v0.8.0 (#38)
- [ab30358f](https://github.com/kubedb/postgres-archiver/commit/ab30358f) Use Go 1.23 (#36)
- [60125c8e](https://github.com/kubedb/postgres-archiver/commit/60125c8e) Prepare for release v0.8.0-rc.3 (#37)
- [0949ab0c](https://github.com/kubedb/postgres-archiver/commit/0949ab0c) Prepare for release v0.8.0-rc.2 (#35)
- [5a8c6ec9](https://github.com/kubedb/postgres-archiver/commit/5a8c6ec9) Prepare for release v0.8.0-rc.1 (#34)
- [78bba5ae](https://github.com/kubedb/postgres-archiver/commit/78bba5ae) Prepare for release v0.8.0-rc.0 (#33)
- [6d9a8d20](https://github.com/kubedb/postgres-archiver/commit/6d9a8d20) Use v1 api (#32)



## [kubedb/postgres-csi-snapshotter-plugin](https://github.com/kubedb/postgres-csi-snapshotter-plugin)

### [v0.8.0](https://github.com/kubedb/postgres-csi-snapshotter-plugin/releases/tag/v0.8.0)

- [aa34bec](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/aa34bec) Prepare for release v0.8.0 (#36)
- [5dd5f10](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/5dd5f10) Use Go 1.23 (#34)
- [68f40d9](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/68f40d9) Prepare for release v0.8.0-rc.3 (#35)
- [744dd4a](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/744dd4a) Prepare for release v0.8.0-rc.2 (#33)
- [624c851](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/624c851) Prepare for release v0.8.0-rc.1 (#32)
- [5167fac](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/5167fac) Prepare for release v0.8.0-rc.0 (#31)
- [9cbbfce](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/9cbbfce) Use v1 api (#30)



## [kubedb/provider-aws](https://github.com/kubedb/provider-aws)

### [v0.9.0](https://github.com/kubedb/provider-aws/releases/tag/v0.9.0)




## [kubedb/provider-azure](https://github.com/kubedb/provider-azure)

### [v0.9.0](https://github.com/kubedb/provider-azure/releases/tag/v0.9.0)




## [kubedb/provider-gcp](https://github.com/kubedb/provider-gcp)

### [v0.9.0](https://github.com/kubedb/provider-gcp/releases/tag/v0.9.0)




## [kubedb/redis-coordinator](https://github.com/kubedb/redis-coordinator)

### [v0.26.0](https://github.com/kubedb/redis-coordinator/releases/tag/v0.26.0)

- [036f0ed3](https://github.com/kubedb/redis-coordinator/commit/036f0ed3) Prepare for release v0.26.0 (#111)
- [1dd607c8](https://github.com/kubedb/redis-coordinator/commit/1dd607c8) Use Go 1.23 (#109)
- [de860a65](https://github.com/kubedb/redis-coordinator/commit/de860a65) Prepare for release v0.26.0-rc.3 (#110)
- [3a92ab81](https://github.com/kubedb/redis-coordinator/commit/3a92ab81) Prepare for release v0.26.0-rc.2 (#108)
- [d15ce249](https://github.com/kubedb/redis-coordinator/commit/d15ce249) Prepare for release v0.26.0-rc.1 (#107)
- [e206e7ac](https://github.com/kubedb/redis-coordinator/commit/e206e7ac) Prepare for release v0.26.0-rc.0 (#106)
- [65403ff6](https://github.com/kubedb/redis-coordinator/commit/65403ff6) Use v1 api (#105)



## [kubedb/replication-mode-detector](https://github.com/kubedb/replication-mode-detector)

### [v0.34.0](https://github.com/kubedb/replication-mode-detector/releases/tag/v0.34.0)

- [85af53fb](https://github.com/kubedb/replication-mode-detector/commit/85af53fb) Prepare for release v0.34.0 (#277)
- [8a2afb28](https://github.com/kubedb/replication-mode-detector/commit/8a2afb28) Use Go 1.23 (#275)
- [fcc68baf](https://github.com/kubedb/replication-mode-detector/commit/fcc68baf) Prepare for release v0.34.0-rc.3 (#276)
- [77ca2092](https://github.com/kubedb/replication-mode-detector/commit/77ca2092) Prepare for release v0.34.0-rc.2 (#274)
- [c0197572](https://github.com/kubedb/replication-mode-detector/commit/c0197572) Prepare for release v0.34.0-rc.1 (#273)
- [aa1d5719](https://github.com/kubedb/replication-mode-detector/commit/aa1d5719) Prepare for release v0.34.0-rc.0 (#272)
- [915f548e](https://github.com/kubedb/replication-mode-detector/commit/915f548e) Use v1 api (#271)



## [kubedb/singlestore-coordinator](https://github.com/kubedb/singlestore-coordinator)

### [v0.2.0](https://github.com/kubedb/singlestore-coordinator/releases/tag/v0.2.0)

- [e431786](https://github.com/kubedb/singlestore-coordinator/commit/e431786) Prepare for release v0.2.0 (#26)
- [2eb12f2](https://github.com/kubedb/singlestore-coordinator/commit/2eb12f2) Use Go 1.23 (#24)
- [379e303](https://github.com/kubedb/singlestore-coordinator/commit/379e303) Prepare for release v0.2.0-rc.3 (#25)
- [33a157b](https://github.com/kubedb/singlestore-coordinator/commit/33a157b) Prepare for release v0.2.0-rc.2 (#23)
- [e0bc384](https://github.com/kubedb/singlestore-coordinator/commit/e0bc384) Prepare for release v0.2.0-rc.1 (#22)
- [06e4926](https://github.com/kubedb/singlestore-coordinator/commit/06e4926) Prepare for release v0.2.0-rc.0 (#21)
- [458fa6a](https://github.com/kubedb/singlestore-coordinator/commit/458fa6a) Update constants to use kubedb package (#20)



## [kubedb/tests](https://github.com/kubedb/tests)

### [v0.32.0](https://github.com/kubedb/tests/releases/tag/v0.32.0)

- [fb607c82](https://github.com/kubedb/tests/commit/fb607c82) Prepare for release v0.32.0 (#356)
- [b7edced0](https://github.com/kubedb/tests/commit/b7edced0) Add missing Autoscaler tests for Redis (#338)
- [dd13814b](https://github.com/kubedb/tests/commit/dd13814b) Fix Postgres Reconfigure test cases (#351)
- [34213383](https://github.com/kubedb/tests/commit/34213383) Use Go 1.23 (#347)
- [5c37c7ac](https://github.com/kubedb/tests/commit/5c37c7ac) set podTemplate for Arbiter and Hidden correctly (#352)
- [0f1153f5](https://github.com/kubedb/tests/commit/0f1153f5) Add Redis Exporter test (#348)
- [6ff529ee](https://github.com/kubedb/tests/commit/6ff529ee) Unfocus Redis Horizontal Scling Test (#350)
- [5f5d899c](https://github.com/kubedb/tests/commit/5f5d899c) Prepare for release v0.32.0-rc.3 (#349)
- [746fba1f](https://github.com/kubedb/tests/commit/746fba1f) Add Memcached e2e Tests (#346)
- [7647c955](https://github.com/kubedb/tests/commit/7647c955) Fix Redis Tests (#345)
- [cd54a2b7](https://github.com/kubedb/tests/commit/cd54a2b7) Add Redis Initialization Script (#342)
- [b279ee9f](https://github.com/kubedb/tests/commit/b279ee9f) Prepare for release v0.32.0-rc.2 (#343)
- [92599f33](https://github.com/kubedb/tests/commit/92599f33) Add Druid Tests (#306)
- [d4762475](https://github.com/kubedb/tests/commit/d4762475) Fix ES env variable tests for V1 api changes (#336)
- [1d5a9926](https://github.com/kubedb/tests/commit/1d5a9926) Add Resource for PerconaXtraDB, MariaDB when creating object (#334)
- [43aa9e97](https://github.com/kubedb/tests/commit/43aa9e97) Fix ES test for V1 changes (#335)
- [8b29ad4f](https://github.com/kubedb/tests/commit/8b29ad4f) Prepare for release v0.32.0-rc.1 (#332)
- [522ce4dd](https://github.com/kubedb/tests/commit/522ce4dd) Add api V1 support for e2e test cases (#330)
- [074319cb](https://github.com/kubedb/tests/commit/074319cb) Kubestash test (#328)
- [3d86cc15](https://github.com/kubedb/tests/commit/3d86cc15) Add MS SQL Server Provisioning Tests  (#321)
- [ac5c8e4a](https://github.com/kubedb/tests/commit/ac5c8e4a) Add FerretDB test (#323)
- [3b09f127](https://github.com/kubedb/tests/commit/3b09f127) Reprovision test (#311)
- [cbb366d5](https://github.com/kubedb/tests/commit/cbb366d5) Update SingleStore Tests Regarding API Changes (#327)
- [7568498c](https://github.com/kubedb/tests/commit/7568498c) Fix Pgpool sync users test (#326)



## [kubedb/zookeeper-restic-plugin](https://github.com/kubedb/zookeeper-restic-plugin)

### [v0.3.0](https://github.com/kubedb/zookeeper-restic-plugin/releases/tag/v0.3.0)

- [fcd21a9](https://github.com/kubedb/zookeeper-restic-plugin/commit/fcd21a9) Prepare for release v0.3.0 (#14)
- [9cb3a5c](https://github.com/kubedb/zookeeper-restic-plugin/commit/9cb3a5c) Use Go 1.23 (#12)
- [0ef0eb0](https://github.com/kubedb/zookeeper-restic-plugin/commit/0ef0eb0) Prepare for release v0.3.0-rc.3 (#13)
- [0f2644b](https://github.com/kubedb/zookeeper-restic-plugin/commit/0f2644b) Prepare for release v0.3.0-rc.2 (#11)
- [6333dd9](https://github.com/kubedb/zookeeper-restic-plugin/commit/6333dd9) Prepare for release v0.3.0-rc.1 (#10)
- [3235ccf](https://github.com/kubedb/zookeeper-restic-plugin/commit/3235ccf) Prepare for release v0.3.0-rc.0 (#9)



