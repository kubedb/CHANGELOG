# KubeDB v2025.2.19 (2025-02-18)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.52.0](https://github.com/kubedb/apimachinery/releases/tag/v0.52.0)

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
- [d3ee4caa](https://github.com/kubedb/apimachinery/commit/d3ee4caa7) Update deps
- [f68a76c7](https://github.com/kubedb/apimachinery/commit/f68a76c7d) make fmt
- [1ba01a7d](https://github.com/kubedb/apimachinery/commit/1ba01a7de) Update deps
- [b05f9709](https://github.com/kubedb/apimachinery/commit/b05f97094) Add DisableSSLSessionResumption field in PostgresVersion CRD (#1390)
- [47fd90ca](https://github.com/kubedb/apimachinery/commit/47fd90caf) Update deps
- [f435670c](https://github.com/kubedb/apimachinery/commit/f435670c9) Add InitScript restore option into manifest restore (#1388)
- [e37dc985](https://github.com/kubedb/apimachinery/commit/e37dc985f) Set maxscale Field Optional (#1389)
- [e5366d52](https://github.com/kubedb/apimachinery/commit/e5366d526) Add Support for MariaDB Replication (#1383)
- [7ad43925](https://github.com/kubedb/apimachinery/commit/7ad439250) Add MS SQL Server Arbiter APIs (#1363)
- [affa6dc5](https://github.com/kubedb/apimachinery/commit/affa6dc53) Add RabbitMQ EnableAllFeatureFlags Constant (#1386)
- [7f9ee3e6](https://github.com/kubedb/apimachinery/commit/7f9ee3e6b) Add apis for archiver manifest recovery (#1387)
- [85c4437b](https://github.com/kubedb/apimachinery/commit/85c4437b1) Add Pgpool hba and pcp file name Constant (#1377)
- [2e163519](https://github.com/kubedb/apimachinery/commit/2e163519e) add reconfigure-tls for pgbouncer (#1384)
- [a7900520](https://github.com/kubedb/apimachinery/commit/a79005204) Add SchemaRegistry with RestProxy API (#1372)
- [bdae9dd4](https://github.com/kubedb/apimachinery/commit/bdae9dd4c) Move Redis mutator defaults to SetDefaults() (#1385)
- [ce659b3f](https://github.com/kubedb/apimachinery/commit/ce659b3fc) Add license restrictions (#1382)
- [051792b4](https://github.com/kubedb/apimachinery/commit/051792b4b) Implement DBBindInterface for generic bindings (#1381)
- [7dd4fbe3](https://github.com/kubedb/apimachinery/commit/7dd4fbe3f) Pass different ca for gateway & inCluster (#1380)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.7.0](https://github.com/kubedb/db-client-go/releases/tag/v0.7.0)

- [b3fa7654](https://github.com/kubedb/db-client-go/commit/b3fa7654) Prepare for release v0.7.0 (#163)
- [993a561c](https://github.com/kubedb/db-client-go/commit/993a561c) Add method to get shard information for ES (#160)
- [3fa565a9](https://github.com/kubedb/db-client-go/commit/3fa565a9) Use Go 1.24 (#162)
- [7deb14c1](https://github.com/kubedb/db-client-go/commit/7deb14c1) Prepare for release v0.7.0-rc.0 (#161)
- [4790577b](https://github.com/kubedb/db-client-go/commit/4790577b) cert remove from pgbouncer (#158)



## [kubedb/elasticsearch-restic-plugin](https://github.com/kubedb/elasticsearch-restic-plugin)

### [v0.15.0](https://github.com/kubedb/elasticsearch-restic-plugin/releases/tag/v0.15.0)

- [dd7dd4b8](https://github.com/kubedb/elasticsearch-restic-plugin/commit/dd7dd4b8) Prepare for release v0.15.0 (#59)
- [9e05f686](https://github.com/kubedb/elasticsearch-restic-plugin/commit/9e05f686) Use Go 1.24 (#58)
- [bbdc55c7](https://github.com/kubedb/elasticsearch-restic-plugin/commit/bbdc55c7) Disable image caching in setup-qemu action (#57)
- [6a087679](https://github.com/kubedb/elasticsearch-restic-plugin/commit/6a087679) Prepare for release v0.15.0-rc.0 (#56)
- [e06c0877](https://github.com/kubedb/elasticsearch-restic-plugin/commit/e06c0877) Add Stdin Backup Leaf Command Support (#54)



## [kubedb/mariadb-coordinator](https://github.com/kubedb/mariadb-coordinator)

### [v0.32.0](https://github.com/kubedb/mariadb-coordinator/releases/tag/v0.32.0)

- [24eeb621](https://github.com/kubedb/mariadb-coordinator/commit/24eeb621) Prepare for release v0.32.0 (#139)
- [a8c8f873](https://github.com/kubedb/mariadb-coordinator/commit/a8c8f873) Use Go 1.24 (#138)
- [ff0a938a](https://github.com/kubedb/mariadb-coordinator/commit/ff0a938a) Prepare for release v0.32.0-rc.0 (#137)
- [efb48fb1](https://github.com/kubedb/mariadb-coordinator/commit/efb48fb1) Disable image caching in setup-qemu action (#136)



## [kubedb/mongodb](https://github.com/kubedb/mongodb)

### [v0.45.0](https://github.com/kubedb/mongodb/releases/tag/v0.45.0)

- [7d7c2879](https://github.com/kubedb/mongodb/commit/7d7c28790) Prepare for release v0.45.0 (#689)
- [4009564e](https://github.com/kubedb/mongodb/commit/4009564ef) Test against k8s 1.32 (#688)
- [b0f42186](https://github.com/kubedb/mongodb/commit/b0f421864) Use Go 1.24 (#687)
- [f8093b11](https://github.com/kubedb/mongodb/commit/f8093b115) Create super user before oplog-restore (#686)
- [12d97bb1](https://github.com/kubedb/mongodb/commit/12d97bb19) Report namespace info with billing event (#685)
- [82d112ae](https://github.com/kubedb/mongodb/commit/82d112ae2) Show the reason for not satifying license restriction (#684)
- [03e6623d](https://github.com/kubedb/mongodb/commit/03e6623d6) Use testrig
- [5fb8819c](https://github.com/kubedb/mongodb/commit/5fb8819ca) Prepare for release v0.45.0-rc.0 (#683)
- [38062196](https://github.com/kubedb/mongodb/commit/380621967) Disable image caching in setup-qemu action (#682)
- [9d9dfdae](https://github.com/kubedb/mongodb/commit/9d9dfdaea) Enable license restriction and client billing (#681)
- [9d6457c8](https://github.com/kubedb/mongodb/commit/9d6457c82) Added archiver and init-script manifest restore support (#679)
- [d295e56a](https://github.com/kubedb/mongodb/commit/d295e56a9) remove `replicas >= 1` validation from replicaset (#677)



## [kubedb/mongodb-csi-snapshotter-plugin](https://github.com/kubedb/mongodb-csi-snapshotter-plugin)

### [v0.13.0](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/releases/tag/v0.13.0)

- [d5b6acb](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/d5b6acb) Prepare for release v0.13.0 (#47)
- [feff5cc](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/feff5cc) Use Go 1.24 (#46)
- [9871552](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/9871552) Prepare for release v0.13.0-rc.0 (#45)
- [92999f5](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/92999f5) Disable image caching in setup-qemu action (#44)



## [kubedb/mssqlserver-archiver](https://github.com/kubedb/mssqlserver-archiver)

### [v0.6.0](https://github.com/kubedb/mssqlserver-archiver/releases/tag/v0.6.0)

- [dc3364c](https://github.com/kubedb/mssqlserver-archiver/commit/dc3364c) Use Go 1.24 (#11)
- [cea73fd](https://github.com/kubedb/mssqlserver-archiver/commit/cea73fd) Disable image caching in setup-qemu action (#10)



## [kubedb/mssqlserver-walg-plugin](https://github.com/kubedb/mssqlserver-walg-plugin)

### [v0.6.0](https://github.com/kubedb/mssqlserver-walg-plugin/releases/tag/v0.6.0)

- [4b98360](https://github.com/kubedb/mssqlserver-walg-plugin/commit/4b98360) Prepare for release v0.6.0 (#20)
- [ca44e86](https://github.com/kubedb/mssqlserver-walg-plugin/commit/ca44e86) Use Go 1.24 (#19)
- [41265e0](https://github.com/kubedb/mssqlserver-walg-plugin/commit/41265e0) Prepare for release v0.6.0-rc.0 (#18)
- [cc57300](https://github.com/kubedb/mssqlserver-walg-plugin/commit/cc57300) Disable image caching in setup-qemu action (#17)



## [kubedb/mysql-csi-snapshotter-plugin](https://github.com/kubedb/mysql-csi-snapshotter-plugin)

### [v0.13.0](https://github.com/kubedb/mysql-csi-snapshotter-plugin/releases/tag/v0.13.0)

- [1511498](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/1511498) Prepare for release v0.13.0 (#43)
- [d1c7f1b](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/d1c7f1b) Use Go 1.24 (#42)
- [33f6918](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/33f6918) Prepare for release v0.13.0-rc.0 (#40)
- [9f91792](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/9f91792) Disable image caching in setup-qemu action (#41)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.30.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.30.0)

- [a41de94](https://github.com/kubedb/mysql-router-init/commit/a41de94) Use Go 1.24 (#51)
- [0ba8326](https://github.com/kubedb/mysql-router-init/commit/0ba8326) Disable image caching in setup-qemu action (#50)



## [kubedb/pg-coordinator](https://github.com/kubedb/pg-coordinator)

### [v0.36.0](https://github.com/kubedb/pg-coordinator/releases/tag/v0.36.0)

- [421d91d6](https://github.com/kubedb/pg-coordinator/commit/421d91d6) Prepare for release v0.36.0 (#192)
- [1488a1d9](https://github.com/kubedb/pg-coordinator/commit/1488a1d9) Fix a bug for force failover (#191)
- [b04c16fd](https://github.com/kubedb/pg-coordinator/commit/b04c16fd) Use Go 1.24 (#190)
- [35382941](https://github.com/kubedb/pg-coordinator/commit/35382941) Reduce API Server Load by Adding Wait Interval When DB Is In Not Ready State (#189)
- [0bc3ed8d](https://github.com/kubedb/pg-coordinator/commit/0bc3ed8d) Prepare for release v0.36.0-rc.0 (#187)
- [e5aabf68](https://github.com/kubedb/pg-coordinator/commit/e5aabf68) Disable image caching in setup-qemu action (#188)
- [a286040e](https://github.com/kubedb/pg-coordinator/commit/a286040e) Allow failover with data loss (#186)
- [8c0d12da](https://github.com/kubedb/pg-coordinator/commit/8c0d12da) Enhance Archive WAL Management and Improve Failover Stability (#184)



## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.52.0](https://github.com/kubedb/postgres/releases/tag/v0.52.0)

- [77658501](https://github.com/kubedb/postgres/commit/776585018) Prepare for release v0.52.0 (#796)
- [5a24b48e](https://github.com/kubedb/postgres/commit/5a24b48ed) Test against k8s 1.32 (#795)
- [ad5ada20](https://github.com/kubedb/postgres/commit/ad5ada201) Use Go 1.24 (#794)
- [9fd8f70a](https://github.com/kubedb/postgres/commit/9fd8f70ae) Report namespace info with billing event (#793)
- [f3158b9d](https://github.com/kubedb/postgres/commit/f3158b9de) update log (#792)
- [a2fe345e](https://github.com/kubedb/postgres/commit/a2fe345e3) Run e2e tests on testrig (#791)
- [18f17d97](https://github.com/kubedb/postgres/commit/18f17d974) Prepare for release v0.52.0-rc.0 (#790)
- [db644a80](https://github.com/kubedb/postgres/commit/db644a803) Disable image caching in setup-qemu action (#789)
- [6ad420f9](https://github.com/kubedb/postgres/commit/6ad420f93) Add client billing event support (#783)
- [e056f480](https://github.com/kubedb/postgres/commit/e056f4800) Added archiver and init-script manifest restore support (#787)
- [8ed11d08](https://github.com/kubedb/postgres/commit/8ed11d084) Archive mode related changes and add startTime-endTime in incremental snapshot (#784)
- [fe0e2ac0](https://github.com/kubedb/postgres/commit/fe0e2ac0e) Parse license restrictions
- [eaf5b26c](https://github.com/kubedb/postgres/commit/eaf5b26c0) Add license restrictions (#782)



## [kubedb/postgres-csi-snapshotter-plugin](https://github.com/kubedb/postgres-csi-snapshotter-plugin)

### [v0.13.0](https://github.com/kubedb/postgres-csi-snapshotter-plugin/releases/tag/v0.13.0)

- [63ba8c9](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/63ba8c9) Prepare for release v0.13.0 (#53)
- [c4b928f](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/c4b928f) Use Go 1.24 (#52)
- [bbe21c0](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/bbe21c0) Prepare for release v0.13.0-rc.0 (#51)
- [f088e55](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/f088e55) Disable image caching in setup-qemu action (#50)
- [3db1026](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/3db1026) Update volumeSnapshotTime when volumeSnapshot is ready to use and add support for standalone volume snapshot (#43)



## [kubedb/postgres-restic-plugin](https://github.com/kubedb/postgres-restic-plugin)

### [v0.15.0](https://github.com/kubedb/postgres-restic-plugin/releases/tag/v0.15.0)

- [4219198](https://github.com/kubedb/postgres-restic-plugin/commit/4219198) Prepare for release v0.15.0 (#67)
- [3773695](https://github.com/kubedb/postgres-restic-plugin/commit/3773695) Use Go 1.24 (#66)
- [91d569b](https://github.com/kubedb/postgres-restic-plugin/commit/91d569b) Prepare for release v0.15.0-rc.0 (#65)
- [87c8e45](https://github.com/kubedb/postgres-restic-plugin/commit/87c8e45) Disable image caching in setup-qemu action (#64)
- [b287099](https://github.com/kubedb/postgres-restic-plugin/commit/b287099) Add Stdin Backup Leaf Command support (#62)



## [kubedb/provider-aws](https://github.com/kubedb/provider-aws)

### [v0.14.0](https://github.com/kubedb/provider-aws/releases/tag/v0.14.0)




## [kubedb/provider-azure](https://github.com/kubedb/provider-azure)

### [v0.14.0](https://github.com/kubedb/provider-azure/releases/tag/v0.14.0)




## [kubedb/provider-gcp](https://github.com/kubedb/provider-gcp)

### [v0.14.0](https://github.com/kubedb/provider-gcp/releases/tag/v0.14.0)




