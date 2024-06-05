# KubeDB v2024.6.4 (2024-06-05)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.46.0](https://github.com/kubedb/apimachinery/releases/tag/v0.46.0)

- [acca053a](https://github.com/kubedb/apimachinery/commit/acca053ab) Update kubestash api
- [f64ef778](https://github.com/kubedb/apimachinery/commit/f64ef7785) Add pod placement policy to v1 pod template spec (#1233)
- [7cb05566](https://github.com/kubedb/apimachinery/commit/7cb055661) Use k8s client libs 1.30.1 (#1232)
- [faac2b8d](https://github.com/kubedb/apimachinery/commit/faac2b8dc) Use DeletionPolicy instead of TerminationPolicy in new dbs (#1231)
- [e387d0c6](https://github.com/kubedb/apimachinery/commit/e387d0c63) Use PodPlacementPolicy from v2 podTemplate (#1230)
- [74e7190f](https://github.com/kubedb/apimachinery/commit/74e7190f0) Set TLS Defaults for Microsoft SQL Server (#1226)
- [f50d9c10](https://github.com/kubedb/apimachinery/commit/f50d9c109) Refactor Clickhouse Webhook (#1228)
- [04949036](https://github.com/kubedb/apimachinery/commit/049490369) Add TLS constants and defaults for RabbitMQ (#1227)
- [d5eb1d50](https://github.com/kubedb/apimachinery/commit/d5eb1d507) Add Druid autoscaler API (#1219)
- [8f7ef3c8](https://github.com/kubedb/apimachinery/commit/8f7ef3c81) Add Druid ops-request API (#1208)
- [a0277a77](https://github.com/kubedb/apimachinery/commit/a0277a77e) Add Pgpool Autoscaler API (#1223)
- [b0c77ebe](https://github.com/kubedb/apimachinery/commit/b0c77ebe1) Add Pgpool OpsRequest API (#1209)
- [0d84725c](https://github.com/kubedb/apimachinery/commit/0d84725c8) Add RabbitMQ OpsRequests (#1225)
- [31cc9434](https://github.com/kubedb/apimachinery/commit/31cc9434f) pgbouncer reload config based on label (#1224)
- [b3797f47](https://github.com/kubedb/apimachinery/commit/b3797f47c) Add ClickHouse API (#1212)
- [46e50802](https://github.com/kubedb/apimachinery/commit/46e50802d) Add Kafka Schema Registry APIs (#1217)
- [5e6b27ed](https://github.com/kubedb/apimachinery/commit/5e6b27ed3) Add MSSQL Server TLS related APIs and helpers (#1218)
- [e1111569](https://github.com/kubedb/apimachinery/commit/e11115697) Add SingleStore AutoScaler API (#1213)
- [85c1f2a6](https://github.com/kubedb/apimachinery/commit/85c1f2a6a) Add SingleStore Ops-Request API (#1211)
- [2c4d34e0](https://github.com/kubedb/apimachinery/commit/2c4d34e07) Updated Memcached API (#1214)
- [2321968d](https://github.com/kubedb/apimachinery/commit/2321968de) Update druid API for simplifying YAML (#1222)
- [dfb99f1a](https://github.com/kubedb/apimachinery/commit/dfb99f1ab) Set default scalingRules (#1220)
- [0744dd0c](https://github.com/kubedb/apimachinery/commit/0744dd0c9) Allow only one database for pgbouncer connection pooling (#1210)
- [08fb210b](https://github.com/kubedb/apimachinery/commit/08fb210be) Fix error check for ferretdb webhook (#1221)
- [4274e807](https://github.com/kubedb/apimachinery/commit/4274e8077) Update auditor library (#1216)
- [7fb9b8c9](https://github.com/kubedb/apimachinery/commit/7fb9b8c98) Extract databaseInfo from mssql (#1203)
- [945f983c](https://github.com/kubedb/apimachinery/commit/945f983c3) Add `syncUsers` field to pgbouncer api (#1206)
- [bf3d0581](https://github.com/kubedb/apimachinery/commit/bf3d0581d) Update kmodules/client-go deps
- [a74eb3db](https://github.com/kubedb/apimachinery/commit/a74eb3db5) Update ZooKeeper CRD (#1207)
- [bcfb3b3d](https://github.com/kubedb/apimachinery/commit/bcfb3b3da) Add Security Context (#1204)
- [62470fd4](https://github.com/kubedb/apimachinery/commit/62470fd41) Add Pgpool AppBinding (#1205)



## [kubedb/clickhouse](https://github.com/kubedb/clickhouse)

### [v0.1.0](https://github.com/kubedb/clickhouse/releases/tag/v0.1.0)

- [4065f54](https://github.com/kubedb/clickhouse/commit/4065f54) Prepare for release v0.1.0 (#2)
- [7e3dd87](https://github.com/kubedb/clickhouse/commit/7e3dd87) Add Support for Provisioning (#1)
- [5d37918](https://github.com/kubedb/clickhouse/commit/5d37918) Add ClickHouseVersion API
- [d5c86a3](https://github.com/kubedb/clickhouse/commit/d5c86a3) Add License
- [edd9534](https://github.com/kubedb/clickhouse/commit/edd9534) Add API and controller Skeleton



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.1.0](https://github.com/kubedb/db-client-go/releases/tag/v0.1.0)

- [19480f10](https://github.com/kubedb/db-client-go/commit/19480f10) Prepare for release v0.1.0 (#115)
- [1942b7bd](https://github.com/kubedb/db-client-go/commit/1942b7bd) client for health check & multiple user reload for pgBouncer (#107)
- [277b3fb6](https://github.com/kubedb/db-client-go/commit/277b3fb6) Use k8s 1.30 client libs (#114)
- [78f5e4c4](https://github.com/kubedb/db-client-go/commit/78f5e4c4) Update rabbitmq client methods (#113)
- [8beb95c5](https://github.com/kubedb/db-client-go/commit/8beb95c5) Update apimachinery module
- [f25da8ec](https://github.com/kubedb/db-client-go/commit/f25da8ec) Add ClickHouse DB Client (#112)
- [8c9132a7](https://github.com/kubedb/db-client-go/commit/8c9132a7) Add RabbitMQ PubSub methods (#105)
- [ed82b008](https://github.com/kubedb/db-client-go/commit/ed82b008) Add Kafka Schema Registry Client (#110)
- [9c578aba](https://github.com/kubedb/db-client-go/commit/9c578aba) Add MSSQL Server TLS  config  (#111)
- [94f6f276](https://github.com/kubedb/db-client-go/commit/94f6f276) Update auditor library (#109)



## [kubedb/elasticsearch-restic-plugin](https://github.com/kubedb/elasticsearch-restic-plugin)

### [v0.9.0](https://github.com/kubedb/elasticsearch-restic-plugin/releases/tag/v0.9.0)

- [adc1b75](https://github.com/kubedb/elasticsearch-restic-plugin/commit/adc1b75) Prepare for release v0.9.0 (#33)
- [6d90baf](https://github.com/kubedb/elasticsearch-restic-plugin/commit/6d90baf) Use k8s 1.30 client libs (#32)
- [0f59810](https://github.com/kubedb/elasticsearch-restic-plugin/commit/0f59810) Update auditor library (#31)



## [kubedb/kubedb-manifest-plugin](https://github.com/kubedb/kubedb-manifest-plugin)

### [v0.9.0](https://github.com/kubedb/kubedb-manifest-plugin/releases/tag/v0.9.0)

- [473e302](https://github.com/kubedb/kubedb-manifest-plugin/commit/473e302) Prepare for release v0.9.0 (#56)
- [a85da9a](https://github.com/kubedb/kubedb-manifest-plugin/commit/a85da9a) Fix nil pointer ref for manifest options (#55)
- [ad0bee2](https://github.com/kubedb/kubedb-manifest-plugin/commit/ad0bee2) Add default namespace for restore (#54)
- [9a503e1](https://github.com/kubedb/kubedb-manifest-plugin/commit/9a503e1) Add Support for Cross Namespace Restore (#45)
- [e02604f](https://github.com/kubedb/kubedb-manifest-plugin/commit/e02604f) Use k8s 1.30 client libs (#53)
- [93633f3](https://github.com/kubedb/kubedb-manifest-plugin/commit/93633f3) Update auditor library (#52)



## [kubedb/mariadb-csi-snapshotter-plugin](https://github.com/kubedb/mariadb-csi-snapshotter-plugin)

### [v0.6.0](https://github.com/kubedb/mariadb-csi-snapshotter-plugin/releases/tag/v0.6.0)

- [24bc92e](https://github.com/kubedb/mariadb-csi-snapshotter-plugin/commit/24bc92e) Prepare for release v0.6.0 (#22)
- [7e532d3](https://github.com/kubedb/mariadb-csi-snapshotter-plugin/commit/7e532d3) Use k8s 1.30 client libs (#21)
- [57e689b](https://github.com/kubedb/mariadb-csi-snapshotter-plugin/commit/57e689b) Update auditor library (#20)



## [kubedb/mariadb-restic-plugin](https://github.com/kubedb/mariadb-restic-plugin)

### [v0.4.0](https://github.com/kubedb/mariadb-restic-plugin/releases/tag/v0.4.0)

- [bf9cc17](https://github.com/kubedb/mariadb-restic-plugin/commit/bf9cc17) Prepare for release v0.4.0 (#14)
- [cdb7954](https://github.com/kubedb/mariadb-restic-plugin/commit/cdb7954) Update target name and namespace ref for restore (#13)
- [52f4777](https://github.com/kubedb/mariadb-restic-plugin/commit/52f4777) Use k8s 1.30 client libs (#12)
- [813f1c1](https://github.com/kubedb/mariadb-restic-plugin/commit/813f1c1) Wait for db provisioned (#10)
- [e5d053a](https://github.com/kubedb/mariadb-restic-plugin/commit/e5d053a) Update auditor library (#11)



## [kubedb/mysql](https://github.com/kubedb/mysql)

### [v0.39.0](https://github.com/kubedb/mysql/releases/tag/v0.39.0)

- [9fb15d4d](https://github.com/kubedb/mysql/commit/9fb15d4dd) Prepare for release v0.39.0 (#626)
- [b8591a75](https://github.com/kubedb/mysql/commit/b8591a757) Use k8s 1.30 client libs (#625)
- [11d498b8](https://github.com/kubedb/mysql/commit/11d498b82) Update auditor library (#624)
- [297e6f89](https://github.com/kubedb/mysql/commit/297e6f899) Refactor ENV and Func Name



## [kubedb/mysql-archiver](https://github.com/kubedb/mysql-archiver)

### [v0.7.0](https://github.com/kubedb/mysql-archiver/releases/tag/v0.7.0)

- [9aec804](https://github.com/kubedb/mysql-archiver/commit/9aec804) Prepare for release v0.7.0 (#33)
- [da8412e](https://github.com/kubedb/mysql-archiver/commit/da8412e) Use k8s 1.30 client libs (#32)
- [5a5c184](https://github.com/kubedb/mysql-archiver/commit/5a5c184) Update auditor library (#31)
- [bd8ed03](https://github.com/kubedb/mysql-archiver/commit/bd8ed03) Refactor ENV and Func Name
- [2817c31](https://github.com/kubedb/mysql-archiver/commit/2817c31) Refactor ENV and func



## [kubedb/mysql-restic-plugin](https://github.com/kubedb/mysql-restic-plugin)

### [v0.9.0](https://github.com/kubedb/mysql-restic-plugin/releases/tag/v0.9.0)

- [dd3c711](https://github.com/kubedb/mysql-restic-plugin/commit/dd3c711) Prepare for release v0.9.0 (#42)
- [7adcbdb](https://github.com/kubedb/mysql-restic-plugin/commit/7adcbdb) Update target name and namespace ref for restore (#41)
- [7f6a752](https://github.com/kubedb/mysql-restic-plugin/commit/7f6a752) Use k8s 1.30 client libs (#40)
- [5ef953f](https://github.com/kubedb/mysql-restic-plugin/commit/5ef953f) Update auditor library (#39)
- [e108ece](https://github.com/kubedb/mysql-restic-plugin/commit/e108ece) Wait for db provisioned (#38)



## [kubedb/pgpool](https://github.com/kubedb/pgpool)

### [v0.1.0](https://github.com/kubedb/pgpool/releases/tag/v0.1.0)

- [3979efd1](https://github.com/kubedb/pgpool/commit/3979efd1) Prepare for release v0.1.0 (#33)
- [7f032308](https://github.com/kubedb/pgpool/commit/7f032308) Use k8s 1.30 client libs (#32)
- [7dc03c00](https://github.com/kubedb/pgpool/commit/7dc03c00) Update deletion and pod placement policy (#31)
- [cc425633](https://github.com/kubedb/pgpool/commit/cc425633) Add pcp port and pdb (#30)
- [f4d0c0f9](https://github.com/kubedb/pgpool/commit/f4d0c0f9) Update auditor library (#29)



## [kubedb/postgres-csi-snapshotter-plugin](https://github.com/kubedb/postgres-csi-snapshotter-plugin)

### [v0.7.0](https://github.com/kubedb/postgres-csi-snapshotter-plugin/releases/tag/v0.7.0)

- [1246683](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/1246683) Prepare for release v0.7.0 (#29)
- [bc60a8e](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/bc60a8e) Use k8s 1.30 client libs (#28)
- [56106ab](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/56106ab) Update auditor library (#27)



## [kubedb/provider-aws](https://github.com/kubedb/provider-aws)

### [v0.8.0](https://github.com/kubedb/provider-aws/releases/tag/v0.8.0)




## [kubedb/provider-gcp](https://github.com/kubedb/provider-gcp)

### [v0.8.0](https://github.com/kubedb/provider-gcp/releases/tag/v0.8.0)




## [kubedb/rabbitmq](https://github.com/kubedb/rabbitmq)

### [v0.1.0](https://github.com/kubedb/rabbitmq/releases/tag/v0.1.0)

- [e5b4e89](https://github.com/kubedb/rabbitmq/commit/e5b4e89) Prepare for release v0.1.0 (#32)
- [ec07f9e](https://github.com/kubedb/rabbitmq/commit/ec07f9e) Use k8s 1.30 client libs (#31)
- [2a564ae](https://github.com/kubedb/rabbitmq/commit/2a564ae) Use DeletionPolicy instead of TerminationPolicy
- [e9ff804](https://github.com/kubedb/rabbitmq/commit/e9ff804) Use PodPlacementPolicy from v2 podTemplate
- [979f9c0](https://github.com/kubedb/rabbitmq/commit/979f9c0) Add support for TLS (#30)
- [4d5b3b2](https://github.com/kubedb/rabbitmq/commit/4d5b3b2) Update auditor library (#29)



## [kubedb/redis-coordinator](https://github.com/kubedb/redis-coordinator)

### [v0.25.0](https://github.com/kubedb/redis-coordinator/releases/tag/v0.25.0)

- [0afe9b48](https://github.com/kubedb/redis-coordinator/commit/0afe9b48) Prepare for release v0.25.0 (#104)
- [519a3d70](https://github.com/kubedb/redis-coordinator/commit/519a3d70) Use k8s 1.30 client libs (#103)
- [585fd8e8](https://github.com/kubedb/redis-coordinator/commit/585fd8e8) Update auditor library (#102)



## [kubedb/solr](https://github.com/kubedb/solr)

### [v0.1.0](https://github.com/kubedb/solr/releases/tag/v0.1.0)

- [de0665a](https://github.com/kubedb/solr/commit/de0665a) Prepare for release v0.1.0 (#32)
- [4a87cd1](https://github.com/kubedb/solr/commit/4a87cd1) Use podPlacementPolicy from v2 template and use deletionPolicy instead of terminationPolicy. (#30)
- [bd23006](https://github.com/kubedb/solr/commit/bd23006) Add petset to run tests. (#29)
- [11e98aa](https://github.com/kubedb/solr/commit/11e98aa) Update auditor library (#28)
- [f2854c4](https://github.com/kubedb/solr/commit/f2854c4) Use version specific bootstrap configurations (#27)



## [kubedb/tests](https://github.com/kubedb/tests)

### [v0.31.0](https://github.com/kubedb/tests/releases/tag/v0.31.0)

- [c6f2e4d4](https://github.com/kubedb/tests/commit/c6f2e4d4) Prepare for release v0.31.0 (#325)
- [5eb32303](https://github.com/kubedb/tests/commit/5eb32303) Use k8s 1.30 client libs (#324)
- [ff5cbff3](https://github.com/kubedb/tests/commit/ff5cbff3) Add solr tests. (#305)
- [5f3a802e](https://github.com/kubedb/tests/commit/5f3a802e) Update auditor library (#322)



## [kubedb/zookeeper](https://github.com/kubedb/zookeeper)

### [v0.1.0](https://github.com/kubedb/zookeeper/releases/tag/v0.1.0)

- [0f0958b2](https://github.com/kubedb/zookeeper/commit/0f0958b2) Prepare for release v0.1.0 (#28)
- [a0c3a9c3](https://github.com/kubedb/zookeeper/commit/a0c3a9c3) Use k8s 1.30 client libs (#27)
- [41f23f5e](https://github.com/kubedb/zookeeper/commit/41f23f5e) Update PodPlacementPolicy (#26)
- [0b3c259f](https://github.com/kubedb/zookeeper/commit/0b3c259f) Add support for PodDisruptionBudget (#25)
- [4139742c](https://github.com/kubedb/zookeeper/commit/4139742c) Update auditor library (#24)



