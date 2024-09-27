# KubeDB v2024.9.30 (2024-09-27)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.48.0](https://github.com/kubedb/apimachinery/releases/tag/v0.48.0)

- [52824a32](https://github.com/kubedb/apimachinery/commit/52824a32c) Update deps
- [ce1269f7](https://github.com/kubedb/apimachinery/commit/ce1269f7a) Add DB Connection api for UI (#1300)
- [270c350d](https://github.com/kubedb/apimachinery/commit/270c350d4) Add support for NetworkPolicy (#1309)
- [1a812915](https://github.com/kubedb/apimachinery/commit/1a812915f) Update api to configure tls for solr (#1297)
- [83aa723b](https://github.com/kubedb/apimachinery/commit/83aa723b3) Fix DB's restoring phase for application-level restore (#1306)
- [706baeb4](https://github.com/kubedb/apimachinery/commit/706baeb42) Change default wal_keep_size for postgres (#1310)
- [42f85a6e](https://github.com/kubedb/apimachinery/commit/42f85a6e3) Add Support of Monitoring to ClickHouse (#1302)
- [027fb904](https://github.com/kubedb/apimachinery/commit/027fb9041) Add Support for ClickHouse Custom Config (#1299)
- [8657958f](https://github.com/kubedb/apimachinery/commit/8657958fe) Update Kibana API (#1301)
- [2c9d3953](https://github.com/kubedb/apimachinery/commit/2c9d3953d) Add ClickHouse Keeper Api (#1278)
- [9349421e](https://github.com/kubedb/apimachinery/commit/9349421ec) Add update constraints to Pgpool api (#1295)
- [1d90d680](https://github.com/kubedb/apimachinery/commit/1d90d680f) Add MS SQL Ops Requests APIs (#1198)
- [adf7fe76](https://github.com/kubedb/apimachinery/commit/adf7fe76c) Add Kafka Scram Constants (#1304)
- [88b051c9](https://github.com/kubedb/apimachinery/commit/88b051c92) Add init field in druid api for backup (#1305)
- [38154e49](https://github.com/kubedb/apimachinery/commit/38154e492) Reconfigure PGBouncer (#1291)
- [639cafff](https://github.com/kubedb/apimachinery/commit/639cafff0) Add ZooKeeper Ops Request (#1263)
- [f622d2d3](https://github.com/kubedb/apimachinery/commit/f622d2d3c) Add Cassandra Autoscaler Api (#1308)
- [5a256e68](https://github.com/kubedb/apimachinery/commit/5a256e688) Dont use kube-ui-server to detect rancher project namespaces (#1307)
- [c4598e14](https://github.com/kubedb/apimachinery/commit/c4598e143) Add Cassandra API (#1283)
- [e32b81a8](https://github.com/kubedb/apimachinery/commit/e32b81a82) Use KIND v0.24.0 (#1303)
- [9ed3d95a](https://github.com/kubedb/apimachinery/commit/9ed3d95a4) Add UpdateVersion API for pgbouncer (#1284)
- [f4c829bd](https://github.com/kubedb/apimachinery/commit/f4c829bda) Add updateConstraints in Memcached Api (#1298)
- [ecd23db4](https://github.com/kubedb/apimachinery/commit/ecd23db43) Update for release KubeStash@v2024.8.30 (#1296)
- [ceb03dd8](https://github.com/kubedb/apimachinery/commit/ceb03dd8b) Remove config secret check from Pgpool webhook (#1294)
- [eb51db0d](https://github.com/kubedb/apimachinery/commit/eb51db0d7) Update for release Stash@v2024.8.27 (#1293)
- [60f4751e](https://github.com/kubedb/apimachinery/commit/60f4751e3) Ignore Postgres reference when deleting Pgpool (#1292)
- [27985f4e](https://github.com/kubedb/apimachinery/commit/27985f4eb) Add monitoring defaults for mssqlserver (#1290)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.3.0](https://github.com/kubedb/db-client-go/releases/tag/v0.3.0)

- [c1fd8329](https://github.com/kubedb/db-client-go/commit/c1fd8329) Prepare for release v0.3.0 (#140)
- [5f1c5482](https://github.com/kubedb/db-client-go/commit/5f1c5482) Add tls for solr (#135)
- [2182ff59](https://github.com/kubedb/db-client-go/commit/2182ff59) Add DisableSecurity Support for ClickHouse (#137)
- [f15802ff](https://github.com/kubedb/db-client-go/commit/f15802ff) update zk client (#128)
- [51823940](https://github.com/kubedb/db-client-go/commit/51823940) Pass containerPort as parameter (#134)
- [e11cb0a2](https://github.com/kubedb/db-client-go/commit/e11cb0a2) Add Cassandra Client (#130)
- [392630ba](https://github.com/kubedb/db-client-go/commit/392630ba) Fix rabbitmq client builder for disable auth (#138)
- [2af340c4](https://github.com/kubedb/db-client-go/commit/2af340c4) Fix RabbitMQ HTTP client with TLS (#136)
- [b8c278df](https://github.com/kubedb/db-client-go/commit/b8c278df) Fix RabbitMQ client for default Vhost setup (#133)



## [kubedb/mongodb-restic-plugin](https://github.com/kubedb/mongodb-restic-plugin)

### [v0.11.0](https://github.com/kubedb/mongodb-restic-plugin/releases/tag/v0.11.0)

- [85fa28e](https://github.com/kubedb/mongodb-restic-plugin/commit/85fa28e) Prepare for release v0.11.0 (#66)
- [3bbb7ed](https://github.com/kubedb/mongodb-restic-plugin/commit/3bbb7ed) print mongodb output if get error (#64)
- [7cc56b2](https://github.com/kubedb/mongodb-restic-plugin/commit/7cc56b2) Update helper method and refactor code (#65)
- [5af3981](https://github.com/kubedb/mongodb-restic-plugin/commit/5af3981) Add timeout for backup and restore (#62)
- [fb269f3](https://github.com/kubedb/mongodb-restic-plugin/commit/fb269f3) Initialize the restic components only (#63)
- [2173316](https://github.com/kubedb/mongodb-restic-plugin/commit/2173316) Use restic 0.17.1 (#61)



## [kubedb/mssqlserver-archiver](https://github.com/kubedb/mssqlserver-archiver)

### [v0.2.0](https://github.com/kubedb/mssqlserver-archiver/releases/tag/v0.2.0)




## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.26.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.26.0)




## [kubedb/postgres-csi-snapshotter-plugin](https://github.com/kubedb/postgres-csi-snapshotter-plugin)

### [v0.9.0](https://github.com/kubedb/postgres-csi-snapshotter-plugin/releases/tag/v0.9.0)

- [0f4f483](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/0f4f483) Prepare for release v0.9.0 (#38)
- [1415a86](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/1415a86) Remove return error on backup fail (#37)



## [kubedb/provider-aws](https://github.com/kubedb/provider-aws)

### [v0.10.0](https://github.com/kubedb/provider-aws/releases/tag/v0.10.0)




## [kubedb/provider-azure](https://github.com/kubedb/provider-azure)

### [v0.10.0](https://github.com/kubedb/provider-azure/releases/tag/v0.10.0)




## [kubedb/provider-gcp](https://github.com/kubedb/provider-gcp)

### [v0.10.0](https://github.com/kubedb/provider-gcp/releases/tag/v0.10.0)




## [kubedb/zookeeper-restic-plugin](https://github.com/kubedb/zookeeper-restic-plugin)

### [v0.4.0](https://github.com/kubedb/zookeeper-restic-plugin/releases/tag/v0.4.0)

- [c64eefc](https://github.com/kubedb/zookeeper-restic-plugin/commit/c64eefc) Prepare for release v0.4.0 (#17)
- [db28c83](https://github.com/kubedb/zookeeper-restic-plugin/commit/db28c83) Update helper method and refactor code (#16)
- [175447e](https://github.com/kubedb/zookeeper-restic-plugin/commit/175447e) Add timeout for backup and restore (#15)



