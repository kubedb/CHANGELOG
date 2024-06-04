# KubeDB v2024.6.4 (2024-06-04)


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



