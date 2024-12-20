# KubeDB v2024.12.18 (2024-12-20)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.50.0](https://github.com/kubedb/apimachinery/releases/tag/v0.50.0)

- [34e3d3f1](https://github.com/kubedb/apimachinery/commit/34e3d3f1f) Update deps
- [61e95e45](https://github.com/kubedb/apimachinery/commit/61e95e454) Add available database list in connection (#1371)
- [e9eda10c](https://github.com/kubedb/apimachinery/commit/e9eda10ca) Fix availabilityGroup panic; Set defults to logBackupOptions (#1370)
- [a471a5b0](https://github.com/kubedb/apimachinery/commit/a471a5b03) Update RabitMQ Constants (#1365)
- [e677abc2](https://github.com/kubedb/apimachinery/commit/e677abc2b) Add WAl backup failed and success history limit field (#1368)
- [d35054f5](https://github.com/kubedb/apimachinery/commit/d35054f53) Add opensearch rotateauth constants (#1369)
- [52bb8340](https://github.com/kubedb/apimachinery/commit/52bb83407) Fix RabbitMQ Default Authsecret name (#1367)
- [886ff390](https://github.com/kubedb/apimachinery/commit/886ff3903) Add kafka controller quorum constant (#1366)
- [f9bb8f9d](https://github.com/kubedb/apimachinery/commit/f9bb8f9d8) Update deps
- [90dd367e](https://github.com/kubedb/apimachinery/commit/90dd367e0) add remote to group replication ops request (#1359)
- [fb7e8ddf](https://github.com/kubedb/apimachinery/commit/fb7e8ddf6) Remove redundant database phase (#1358)
- [5c754b01](https://github.com/kubedb/apimachinery/commit/5c754b01e) Set Default Postgres StandbyMode (#1364)
- [97a0eb7c](https://github.com/kubedb/apimachinery/commit/97a0eb7c1) Add const for ES Master node shard allocation disabling (#1361)
- [9ab2b7bd](https://github.com/kubedb/apimachinery/commit/9ab2b7bdd) Add AutoOps for Kafka (#1362)
- [cac99cb9](https://github.com/kubedb/apimachinery/commit/cac99cb95) Update for release KubeStash@v2024.12.9 (#1360)
- [392b6fe3](https://github.com/kubedb/apimachinery/commit/392b6fe3e) Add ReplicationStrategy Default Value for MySQL (#1356)
- [2198d910](https://github.com/kubedb/apimachinery/commit/2198d9109) Add helpers to use different labels in sidekick (#1357)
- [cfbad6a2](https://github.com/kubedb/apimachinery/commit/cfbad6a2d) Add Memcahced Authentication Constant (#1355)
- [5c29840d](https://github.com/kubedb/apimachinery/commit/5c29840da) Add archiver contants (#1352)
- [d61bcdd7](https://github.com/kubedb/apimachinery/commit/d61bcdd70) Update deps
- [07482109](https://github.com/kubedb/apimachinery/commit/074821090) Update sidekick
- [1e6df971](https://github.com/kubedb/apimachinery/commit/1e6df9713) Rename auth-active-from annotation (#1354)
- [6ec77631](https://github.com/kubedb/apimachinery/commit/6ec77631d) Add ExtractDatabaseInfo Func for Cassandra (#1351)



## [kubedb/cli](https://github.com/kubedb/cli)

### [v0.50.0](https://github.com/kubedb/cli/releases/tag/v0.50.0)

- [f7e7b8fd](https://github.com/kubedb/cli/commit/f7e7b8fd) Prepare for release v0.50.0 (#782)



## [kubedb/dashboard-restic-plugin](https://github.com/kubedb/dashboard-restic-plugin)

### [v0.8.0](https://github.com/kubedb/dashboard-restic-plugin/releases/tag/v0.8.0)

- [cdd6918](https://github.com/kubedb/dashboard-restic-plugin/commit/cdd6918) Prepare for release v0.8.0 (#26)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.5.0](https://github.com/kubedb/db-client-go/releases/tag/v0.5.0)

- [d6abb5b9](https://github.com/kubedb/db-client-go/commit/d6abb5b9) Prepare for release v0.5.0 (#154)
- [61b1dcbb](https://github.com/kubedb/db-client-go/commit/61b1dcbb) Return amqp channel with RabbitMQ client (#153)



## [kubedb/druid](https://github.com/kubedb/druid)

### [v0.5.0](https://github.com/kubedb/druid/releases/tag/v0.5.0)

- [0504c4f6](https://github.com/kubedb/druid/commit/0504c4f6) Prepare for release v0.5.0 (#64)
- [498b668c](https://github.com/kubedb/druid/commit/498b668c) Use `DatabasePhase` instead of `DruidPhase` (#63)
- [678142c7](https://github.com/kubedb/druid/commit/678142c7) Update `AuthActiveFromAnnotation` const (#62)
- [039004a7](https://github.com/kubedb/druid/commit/039004a7) Fix Druid active-from Annotation check in Auth Secret (#61)



## [kubedb/elasticsearch](https://github.com/kubedb/elasticsearch)

### [v0.50.0](https://github.com/kubedb/elasticsearch/releases/tag/v0.50.0)

- [b616d048](https://github.com/kubedb/elasticsearch/commit/b616d0488) Prepare for release v0.50.0 (#744)
- [21a3fb0f](https://github.com/kubedb/elasticsearch/commit/21a3fb0ff) Add method to get internal config for opensearch (#743)
- [c1e9afd3](https://github.com/kubedb/elasticsearch/commit/c1e9afd34) Updated annotation name (#742)
- [f302a147](https://github.com/kubedb/elasticsearch/commit/f302a1479) Remove old statefulset (#741)



## [kubedb/elasticsearch-restic-plugin](https://github.com/kubedb/elasticsearch-restic-plugin)

### [v0.13.0](https://github.com/kubedb/elasticsearch-restic-plugin/releases/tag/v0.13.0)

- [7447e2da](https://github.com/kubedb/elasticsearch-restic-plugin/commit/7447e2da) Prepare for release v0.13.0 (#50)



## [kubedb/kafka](https://github.com/kubedb/kafka)

### [v0.21.0](https://github.com/kubedb/kafka/releases/tag/v0.21.0)

- [f07497c0](https://github.com/kubedb/kafka/commit/f07497c0) Prepare for release v0.21.0 (#126)
- [a4216f60](https://github.com/kubedb/kafka/commit/a4216f60) Fix .spec.authSecret Patch overriding user provided rotateAfter (#125)
- [d65a2fff](https://github.com/kubedb/kafka/commit/d65a2fff) Update configuration for new version and improve logs (#123)
- [f0762832](https://github.com/kubedb/kafka/commit/f0762832) Fix kafka connector deletion panic (#122)
- [01081fc9](https://github.com/kubedb/kafka/commit/01081fc9) Update auth active from annotations (#121)



## [kubedb/mariadb](https://github.com/kubedb/mariadb)

### [v0.34.0](https://github.com/kubedb/mariadb/releases/tag/v0.34.0)

- [b0d77276](https://github.com/kubedb/mariadb/commit/b0d77276d) Prepare for release v0.34.0 (#299)
- [6c3d91ef](https://github.com/kubedb/mariadb/commit/6c3d91efc) Stop checking archiver allowness if ref given (#298)
- [c8213ab5](https://github.com/kubedb/mariadb/commit/c8213ab58) Add Increamental Snapshot (#297)
- [d4e04a2a](https://github.com/kubedb/mariadb/commit/d4e04a2a2) Use different labels for sidekick (#293)
- [dbda72bb](https://github.com/kubedb/mariadb/commit/dbda72bb3) Add Support for Rotate Auth  (#292)



## [kubedb/mariadb-coordinator](https://github.com/kubedb/mariadb-coordinator)

### [v0.30.0](https://github.com/kubedb/mariadb-coordinator/releases/tag/v0.30.0)

- [449d50d8](https://github.com/kubedb/mariadb-coordinator/commit/449d50d8) Prepare for release v0.30.0 (#131)



## [kubedb/mongodb](https://github.com/kubedb/mongodb)

### [v0.43.0](https://github.com/kubedb/mongodb/releases/tag/v0.43.0)

- [2c7aeb18](https://github.com/kubedb/mongodb/commit/2c7aeb186) Prepare for release v0.43.0 (#673)
- [c7aa9063](https://github.com/kubedb/mongodb/commit/c7aa90638) update snapshot comps phase to succeed before database and arch deletion (#672)
- [e751b02a](https://github.com/kubedb/mongodb/commit/e751b02af) pass inc. snapshot limit as args to wal-g (#671)
- [9f301c9c](https://github.com/kubedb/mongodb/commit/9f301c9c7) fix auth secret panic in mongodb archiver manifest restore (#669)
- [44777c86](https://github.com/kubedb/mongodb/commit/44777c86a) Use different labels for sidekick (#668)
- [d69f0f40](https://github.com/kubedb/mongodb/commit/d69f0f405) update `AuthActiveFromAnnotation` const in secret (#667)



## [kubedb/mongodb-csi-snapshotter-plugin](https://github.com/kubedb/mongodb-csi-snapshotter-plugin)

### [v0.11.0](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/releases/tag/v0.11.0)

- [e46c5ae](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/e46c5ae) Prepare for release v0.11.0 (#40)



## [kubedb/mongodb-restic-plugin](https://github.com/kubedb/mongodb-restic-plugin)

### [v0.13.0](https://github.com/kubedb/mongodb-restic-plugin/releases/tag/v0.13.0)

- [1a813ed](https://github.com/kubedb/mongodb-restic-plugin/commit/1a813ed) Prepare for release v0.13.0 (#72)



## [kubedb/mssqlserver-archiver](https://github.com/kubedb/mssqlserver-archiver)

### [v0.4.0](https://github.com/kubedb/mssqlserver-archiver/releases/tag/v0.4.0)

- [a2ce047](https://github.com/kubedb/mssqlserver-archiver/commit/a2ce047) Update deps (#7)
- [503c917](https://github.com/kubedb/mssqlserver-archiver/commit/503c917) Update wal-g to v2024.12.18 (#6)
- [bc4c5a9](https://github.com/kubedb/mssqlserver-archiver/commit/bc4c5a9) Update log push start/end time in incremental snapshot (#5)



## [kubedb/mysql](https://github.com/kubedb/mysql)

### [v0.43.0](https://github.com/kubedb/mysql/releases/tag/v0.43.0)

- [f825bfbc](https://github.com/kubedb/mysql/commit/f825bfbc6) Prepare for release v0.43.0 (#657)
- [c5c16712](https://github.com/kubedb/mysql/commit/c5c167123) Stop checking archiver allowness if ref given
- [c5b77115](https://github.com/kubedb/mysql/commit/c5b771157) Add Increamental Snapshot (#656)
- [f0234d44](https://github.com/kubedb/mysql/commit/f0234d449) Update CI for Daily Test (#655)
- [9eceaab8](https://github.com/kubedb/mysql/commit/9eceaab8a) Set PITR_RESTORE env to InitContainer (#654)
- [7ed83cc1](https://github.com/kubedb/mysql/commit/7ed83cc11) Add XtraBackup Base Backup Support for Archiver (#647)
- [e2bb04af](https://github.com/kubedb/mysql/commit/e2bb04afd) Use different labels for sidekick (#652)



## [kubedb/mysql-coordinator](https://github.com/kubedb/mysql-coordinator)

### [v0.28.0](https://github.com/kubedb/mysql-coordinator/releases/tag/v0.28.0)

- [8fc7747b](https://github.com/kubedb/mysql-coordinator/commit/8fc7747b) Prepare for release v0.28.0 (#129)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.28.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.28.0)




## [kubedb/percona-xtradb](https://github.com/kubedb/percona-xtradb)

### [v0.37.0](https://github.com/kubedb/percona-xtradb/releases/tag/v0.37.0)

- [2eaf102a](https://github.com/kubedb/percona-xtradb/commit/2eaf102ae) Prepare for release v0.37.0 (#387)
- [1c679aac](https://github.com/kubedb/percona-xtradb/commit/1c679aac3) Add Support for Rotate Auth  (#385)



## [kubedb/pg-coordinator](https://github.com/kubedb/pg-coordinator)

### [v0.34.0](https://github.com/kubedb/pg-coordinator/releases/tag/v0.34.0)

- [c05b8ff9](https://github.com/kubedb/pg-coordinator/commit/c05b8ff9) Prepare for release v0.34.0 (#179)
- [04b387c5](https://github.com/kubedb/pg-coordinator/commit/04b387c5) Update LSN position in raft continuously  (#178)



## [kubedb/pgpool](https://github.com/kubedb/pgpool)

### [v0.5.0](https://github.com/kubedb/pgpool/releases/tag/v0.5.0)

- [258de2d9](https://github.com/kubedb/pgpool/commit/258de2d9) Prepare for release v0.5.0 (#54)



## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.50.0](https://github.com/kubedb/postgres/releases/tag/v0.50.0)

- [cdd642cf](https://github.com/kubedb/postgres/commit/cdd642cf1) Prepare for release v0.50.0 (#778)
- [213338de](https://github.com/kubedb/postgres/commit/213338dea) Add support for pitr restore to the latest point (#776)
- [d5b49d54](https://github.com/kubedb/postgres/commit/d5b49d544) Only use patch call when patching active from annotations (#777)
- [49471781](https://github.com/kubedb/postgres/commit/494717817) Add User in manifest restore (#774)
- [37a0cbba](https://github.com/kubedb/postgres/commit/37a0cbba6) Fix Daily (#769)
- [686c6240](https://github.com/kubedb/postgres/commit/686c62408) Use different labels for sidekick (#773)
- [3213e090](https://github.com/kubedb/postgres/commit/3213e0902) Update rotate auth annotation (#772)
- [99cb90f1](https://github.com/kubedb/postgres/commit/99cb90f17) Fix Archiver for Minio Backend (#771)



## [kubedb/provider-aws](https://github.com/kubedb/provider-aws)

### [v0.12.0](https://github.com/kubedb/provider-aws/releases/tag/v0.12.0)




## [kubedb/provider-gcp](https://github.com/kubedb/provider-gcp)

### [v0.12.0](https://github.com/kubedb/provider-gcp/releases/tag/v0.12.0)




## [kubedb/redis](https://github.com/kubedb/redis)

### [v0.43.0](https://github.com/kubedb/redis/releases/tag/v0.43.0)

- [e0e75e30](https://github.com/kubedb/redis/commit/e0e75e30a) Prepare for release v0.43.0 (#566)
- [157bd04a](https://github.com/kubedb/redis/commit/157bd04a7) Improve log (#562)



## [kubedb/redis-coordinator](https://github.com/kubedb/redis-coordinator)

### [v0.29.0](https://github.com/kubedb/redis-coordinator/releases/tag/v0.29.0)

- [f2264e1e](https://github.com/kubedb/redis-coordinator/commit/f2264e1e) Prepare for release v0.29.0 (#116)



## [kubedb/zookeeper-restic-plugin](https://github.com/kubedb/zookeeper-restic-plugin)

### [v0.6.0](https://github.com/kubedb/zookeeper-restic-plugin/releases/tag/v0.6.0)

- [9bed507](https://github.com/kubedb/zookeeper-restic-plugin/commit/9bed507) Prepare for release v0.6.0 (#22)



