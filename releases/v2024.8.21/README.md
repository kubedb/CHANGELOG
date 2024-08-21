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



## [kubedb/crd-manager](https://github.com/kubedb/crd-manager)

### [v0.2.0](https://github.com/kubedb/crd-manager/releases/tag/v0.2.0)

- [e0532ce0](https://github.com/kubedb/crd-manager/commit/e0532ce0) Prepare for release v0.2.0 (#46)
- [224e4f86](https://github.com/kubedb/crd-manager/commit/224e4f86) Use Go 1.23 (#42)
- [4fd0fdd5](https://github.com/kubedb/crd-manager/commit/4fd0fdd5) Prepare for release v0.2.0-rc.3 (#44)
- [2820d09e](https://github.com/kubedb/crd-manager/commit/2820d09e) Add MSSQLServer archiver crd (#43)
- [6a17ac75](https://github.com/kubedb/crd-manager/commit/6a17ac75) Prepare for release v0.2.0-rc.2 (#40)
- [2772153d](https://github.com/kubedb/crd-manager/commit/2772153d) Scale Down Provisioner if Older (#38)
- [f5470e5b](https://github.com/kubedb/crd-manager/commit/f5470e5b) Add Kafka RestProxy CRD (#37)
- [da1fedc4](https://github.com/kubedb/crd-manager/commit/da1fedc4) Add ferretdb ops-manager CRD (#39)
- [d7f0c41b](https://github.com/kubedb/crd-manager/commit/d7f0c41b) Install autoscaler CRDs (#36)
- [abdfe6d4](https://github.com/kubedb/crd-manager/commit/abdfe6d4) Prepare for release v0.2.0-rc.1 (#35)
- [8392c6cd](https://github.com/kubedb/crd-manager/commit/8392c6cd) Prepare for release v0.2.0-rc.0 (#34)
- [a4f9e562](https://github.com/kubedb/crd-manager/commit/a4f9e562) Preserve crd conversion config on update (#31)
- [5c05c9ba](https://github.com/kubedb/crd-manager/commit/5c05c9ba) Move features to apimachinery



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



## [kubedb/elasticsearch](https://github.com/kubedb/elasticsearch)

### [v0.47.0](https://github.com/kubedb/elasticsearch/releases/tag/v0.47.0)

- [720429d4](https://github.com/kubedb/elasticsearch/commit/720429d49) Prepare for release v0.47.0 (#732)
- [5725fedd](https://github.com/kubedb/elasticsearch/commit/5725feddb) Use Go 1.23 (#730)
- [6e5a7875](https://github.com/kubedb/elasticsearch/commit/6e5a78758) Prepare for release v0.47.0-rc.3 (#731)
- [14079024](https://github.com/kubedb/elasticsearch/commit/140790248) Refactor Elasticsearch webhook server (#729)
- [fd8abfca](https://github.com/kubedb/elasticsearch/commit/fd8abfca3) Prepare for release v0.47.0-rc.2 (#728)
- [be009364](https://github.com/kubedb/elasticsearch/commit/be009364b) Fix PodTemplate assignment to config-merger initContainer (#727)
- [28668a0c](https://github.com/kubedb/elasticsearch/commit/28668a0c3) Revert "Fix podTemplate assignment for init container"
- [9b7e0aa0](https://github.com/kubedb/elasticsearch/commit/9b7e0aa0c) Fix podTemplate assignment for init container
- [1f8f6a49](https://github.com/kubedb/elasticsearch/commit/1f8f6a495) Prepare for release v0.47.0-rc.1 (#726)
- [66d09cc2](https://github.com/kubedb/elasticsearch/commit/66d09cc27) Fix error handling for validators (#725)
- [f3bd7f56](https://github.com/kubedb/elasticsearch/commit/f3bd7f56f) Prepare for release v0.47.0-rc.0 (#724)
- [05142253](https://github.com/kubedb/elasticsearch/commit/051422532) Use v1 api (#723)



## [kubedb/ferretdb](https://github.com/kubedb/ferretdb)

### [v0.2.0](https://github.com/kubedb/ferretdb/releases/tag/v0.2.0)

- [86949d6c](https://github.com/kubedb/ferretdb/commit/86949d6c) Prepare for release v0.2.0 (#42)
- [a6955947](https://github.com/kubedb/ferretdb/commit/a6955947) Use Go 1.23 (#40)
- [7c5d6d1c](https://github.com/kubedb/ferretdb/commit/7c5d6d1c) Prepare for release v0.2.0-rc.3 (#41)
- [b6223cab](https://github.com/kubedb/ferretdb/commit/b6223cab) Test against k8s 1.31 (#39)
- [933d5b0d](https://github.com/kubedb/ferretdb/commit/933d5b0d) update server (#37)
- [a587c29d](https://github.com/kubedb/ferretdb/commit/a587c29d) pass context properly (#38)
- [0a38354a](https://github.com/kubedb/ferretdb/commit/0a38354a) Prepare for release v0.2.0-rc.2 (#36)
- [0d005f64](https://github.com/kubedb/ferretdb/commit/0d005f64) Make some changes for ops manager (#35)
- [fcc68498](https://github.com/kubedb/ferretdb/commit/fcc68498) Prepare for release v0.2.0-rc.1 (#34)
- [e8dfe581](https://github.com/kubedb/ferretdb/commit/e8dfe581) make client funcs accessible (#33)
- [c9abee71](https://github.com/kubedb/ferretdb/commit/c9abee71) Prepare for release v0.2.0-rc.0 (#32)
- [0c36fb43](https://github.com/kubedb/ferretdb/commit/0c36fb43) Fix apimachinery constants (#31)
- [0afda2a8](https://github.com/kubedb/ferretdb/commit/0afda2a8) Add e2e ci (#25)
- [652e0d81](https://github.com/kubedb/ferretdb/commit/652e0d81) Fix Backend TLS connection (#30)



## [kubedb/kafka](https://github.com/kubedb/kafka)

### [v0.18.0](https://github.com/kubedb/kafka/releases/tag/v0.18.0)

- [81d379d0](https://github.com/kubedb/kafka/commit/81d379d0) Prepare for release v0.18.0 (#105)
- [db65ea0d](https://github.com/kubedb/kafka/commit/db65ea0d) Use Go 1.23 (#103)
- [61da1711](https://github.com/kubedb/kafka/commit/61da1711) Prepare for release v0.18.0-rc.3 (#104)
- [0d676702](https://github.com/kubedb/kafka/commit/0d676702) Test against k8s 1.31 (#102)
- [f826ea35](https://github.com/kubedb/kafka/commit/f826ea35) Update ReadinessGate Conditions and remove unncessary logs (#101)
- [98b8a404](https://github.com/kubedb/kafka/commit/98b8a404) Prepare for release v0.18.0-rc.2 (#100)
- [ced0da95](https://github.com/kubedb/kafka/commit/ced0da95) Add Kafka RestProxy (#99)
- [b2cc90d4](https://github.com/kubedb/kafka/commit/b2cc90d4) Prepare for release v0.18.0-rc.1 (#98)
- [7a56e529](https://github.com/kubedb/kafka/commit/7a56e529) Install petset kafka daily (#97)
- [c3f92486](https://github.com/kubedb/kafka/commit/c3f92486) Prepare for release v0.18.0-rc.0 (#96)
- [19b65b86](https://github.com/kubedb/kafka/commit/19b65b86) Update Statefulset with PetSet and apiversion (#95)



## [kubedb/kubedb-manifest-plugin](https://github.com/kubedb/kubedb-manifest-plugin)

### [v0.10.0](https://github.com/kubedb/kubedb-manifest-plugin/releases/tag/v0.10.0)

- [13a03d8](https://github.com/kubedb/kubedb-manifest-plugin/commit/13a03d8) Prepare for release v0.10.0 (#64)
- [41f4e91](https://github.com/kubedb/kubedb-manifest-plugin/commit/41f4e91) Use Go 1.23 (#62)
- [281d889](https://github.com/kubedb/kubedb-manifest-plugin/commit/281d889) Prepare for release v0.10.0-rc.3 (#63)
- [5053a2b](https://github.com/kubedb/kubedb-manifest-plugin/commit/5053a2b) Implement MSSQLServer manifest backup and restore (#59)
- [8b1207d](https://github.com/kubedb/kubedb-manifest-plugin/commit/8b1207d) Prepare for release v0.10.0-rc.2 (#60)
- [599fa89](https://github.com/kubedb/kubedb-manifest-plugin/commit/599fa89) Prepare for release v0.10.0-rc.1 (#58)
- [7a27d11](https://github.com/kubedb/kubedb-manifest-plugin/commit/7a27d11) Prepare for release v0.10.0-rc.0 (#57)



## [kubedb/mariadb](https://github.com/kubedb/mariadb)

### [v0.31.0](https://github.com/kubedb/mariadb/releases/tag/v0.31.0)

- [691ffd6c](https://github.com/kubedb/mariadb/commit/691ffd6cd) Prepare for release v0.31.0 (#281)
- [d48899e7](https://github.com/kubedb/mariadb/commit/d48899e79) Use Go 1.23 (#279)
- [211fad73](https://github.com/kubedb/mariadb/commit/211fad731) Prepare for release v0.31.0-rc.3 (#280)
- [00d8723b](https://github.com/kubedb/mariadb/commit/00d8723bf) Test against k8s 1.31 (#278)
- [c21a2238](https://github.com/kubedb/mariadb/commit/c21a22387) Mongodb Alike Archiver related changes, refactor webhook (#277)
- [86038a20](https://github.com/kubedb/mariadb/commit/86038a201) Prepare for release v0.31.0-rc.2 (#276)
- [d66565b2](https://github.com/kubedb/mariadb/commit/d66565b29) Fix Archiver BackupConfig Not Ready Issue (#275)
- [c16d25c7](https://github.com/kubedb/mariadb/commit/c16d25c72) Prepare for release v0.31.0-rc.1 (#274)
- [823748e1](https://github.com/kubedb/mariadb/commit/823748e1a) Fix Env Validation (#273)
- [63504dc0](https://github.com/kubedb/mariadb/commit/63504dc0d) Prepare for release v0.31.0-rc.0 (#272)
- [1bf03c34](https://github.com/kubedb/mariadb/commit/1bf03c34d) Use v1 api (#271)



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



## [kubedb/memcached](https://github.com/kubedb/memcached)

### [v0.40.0](https://github.com/kubedb/memcached/releases/tag/v0.40.0)

- [00f29772](https://github.com/kubedb/memcached/commit/00f297726) Prepare for release v0.40.0 (#463)
- [f698842e](https://github.com/kubedb/memcached/commit/f698842e1) Use Go 1.23 (#460)
- [1a3ed68b](https://github.com/kubedb/memcached/commit/1a3ed68b8) Prepare for release v0.40.0-rc.3 (#462)
- [93626b1a](https://github.com/kubedb/memcached/commit/93626b1ab) Fix DeletionPolicy Halt (#461)
- [7ddfc3eb](https://github.com/kubedb/memcached/commit/7ddfc3eb1) Test against k8s 1.31 (#459)
- [c5a4d6a8](https://github.com/kubedb/memcached/commit/c5a4d6a85) Refactor Memcached Webhook Server (#458)
- [f2ab956b](https://github.com/kubedb/memcached/commit/f2ab956b4) Prepare for release v0.40.0-rc.2 (#457)
- [8a4aaac1](https://github.com/kubedb/memcached/commit/8a4aaac1d) Add Reconciler (#456)
- [7ee57761](https://github.com/kubedb/memcached/commit/7ee577616) Add Rule and Petset Watcher (#455)
- [028b7d98](https://github.com/kubedb/memcached/commit/028b7d98d) Prepare for release v0.40.0-rc.1 (#453)
- [ba86e1ca](https://github.com/kubedb/memcached/commit/ba86e1ca6) Update Validator (#452)
- [aa177b55](https://github.com/kubedb/memcached/commit/aa177b551) Fix Webhook Provisioner Restart Issue (#451)
- [2190a3c8](https://github.com/kubedb/memcached/commit/2190a3c8f) Prepare for release v0.40.0-rc.0 (#450)
- [cf78ad00](https://github.com/kubedb/memcached/commit/cf78ad006) Use v1 api (#449)



## [kubedb/mssqlserver-archiver](https://github.com/kubedb/mssqlserver-archiver)

### [v0.1.0](https://github.com/kubedb/mssqlserver-archiver/releases/tag/v0.1.0)

- [7c04349](https://github.com/kubedb/mssqlserver-archiver/commit/7c04349) Use Go 1.23 (#3)
- [7c867e6](https://github.com/kubedb/mssqlserver-archiver/commit/7c867e6) Prepare for release v0.1.0-rc.3 (#2)



## [kubedb/mssqlserver-walg-plugin](https://github.com/kubedb/mssqlserver-walg-plugin)

### [v0.1.0](https://github.com/kubedb/mssqlserver-walg-plugin/releases/tag/v0.1.0)

- [2f8ad13](https://github.com/kubedb/mssqlserver-walg-plugin/commit/2f8ad13) Prepare for release v0.1.0 (#5)
- [23da1d4](https://github.com/kubedb/mssqlserver-walg-plugin/commit/23da1d4) Use Go 1.23 (#3)
- [47b5046](https://github.com/kubedb/mssqlserver-walg-plugin/commit/47b5046) Prepare for release v0.1.0-rc.3 (#4)



## [kubedb/mysql](https://github.com/kubedb/mysql)

### [v0.40.0](https://github.com/kubedb/mysql/releases/tag/v0.40.0)

- [e4002e3c](https://github.com/kubedb/mysql/commit/e4002e3ca) Prepare for release v0.40.0 (#637)
- [fec33196](https://github.com/kubedb/mysql/commit/fec331965) Use Go 1.23 (#635)
- [715b4713](https://github.com/kubedb/mysql/commit/715b4713d) Prepare for release v0.40.0-rc.3 (#636)
- [46d5c62c](https://github.com/kubedb/mysql/commit/46d5c62ce) Test against k8s 1.31 (#634)
- [42a90ae7](https://github.com/kubedb/mysql/commit/42a90ae77) Refactor MySQL Webhook Server (#633)
- [b2cc7f23](https://github.com/kubedb/mysql/commit/b2cc7f236) Prepare for release v0.40.0-rc.2 (#632)
- [9801f22d](https://github.com/kubedb/mysql/commit/9801f22db) Prepare for release v0.40.0-rc.1 (#631)
- [695750a5](https://github.com/kubedb/mysql/commit/695750a55) fix validator for MySQL (#630)
- [3ca73ddd](https://github.com/kubedb/mysql/commit/3ca73ddda) Prepare for release v0.40.0-rc.0 (#629)
- [54cb812e](https://github.com/kubedb/mysql/commit/54cb812ec) Add PetSet and move on V1 API (#628)



## [kubedb/mysql-archiver](https://github.com/kubedb/mysql-archiver)

### [v0.8.0](https://github.com/kubedb/mysql-archiver/releases/tag/v0.8.0)

- [2ac416d3](https://github.com/kubedb/mysql-archiver/commit/2ac416d3) Prepare for release v0.8.0 (#40)
- [aad5ec96](https://github.com/kubedb/mysql-archiver/commit/aad5ec96) Use Go 1.23 (#38)
- [2d439cb5](https://github.com/kubedb/mysql-archiver/commit/2d439cb5) Prepare for release v0.8.0-rc.3 (#39)
- [a54178b9](https://github.com/kubedb/mysql-archiver/commit/a54178b9) Prepare for release v0.8.0-rc.2 (#37)
- [f7adcd27](https://github.com/kubedb/mysql-archiver/commit/f7adcd27) Prepare for release v0.8.0-rc.1 (#36)
- [b2e2904b](https://github.com/kubedb/mysql-archiver/commit/b2e2904b) Prepare for release v0.8.0-rc.0 (#35)
- [3d92a58f](https://github.com/kubedb/mysql-archiver/commit/3d92a58f) Use v1 api (#34)



## [kubedb/mysql-coordinator](https://github.com/kubedb/mysql-coordinator)

### [v0.25.0](https://github.com/kubedb/mysql-coordinator/releases/tag/v0.25.0)

- [6e595bee](https://github.com/kubedb/mysql-coordinator/commit/6e595bee) Prepare for release v0.25.0 (#122)
- [97ada282](https://github.com/kubedb/mysql-coordinator/commit/97ada282) Use Go 1.23 (#120)
- [486d06e4](https://github.com/kubedb/mysql-coordinator/commit/486d06e4) Prepare for release v0.25.0-rc.3 (#121)
- [cbae32d4](https://github.com/kubedb/mysql-coordinator/commit/cbae32d4) Prepare for release v0.25.0-rc.2 (#119)
- [7565022c](https://github.com/kubedb/mysql-coordinator/commit/7565022c) Prepare for release v0.25.0-rc.1 (#118)
- [e15adb2d](https://github.com/kubedb/mysql-coordinator/commit/e15adb2d) Update StatefulSet to PetSet (#117)
- [b8c377fd](https://github.com/kubedb/mysql-coordinator/commit/b8c377fd) Prepare for release v0.25.0-rc.0 (#116)
- [f29b8f56](https://github.com/kubedb/mysql-coordinator/commit/f29b8f56) Update constants to use kubedb package (#115)



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




## [kubedb/rabbitmq](https://github.com/kubedb/rabbitmq)

### [v0.2.0](https://github.com/kubedb/rabbitmq/releases/tag/v0.2.0)

- [683f8eb4](https://github.com/kubedb/rabbitmq/commit/683f8eb4) Prepare for release v0.2.0 (#43)
- [0d2360c8](https://github.com/kubedb/rabbitmq/commit/0d2360c8) Use Go 1.23 (#41)
- [9e2d1b30](https://github.com/kubedb/rabbitmq/commit/9e2d1b30) Prepare for release v0.2.0-rc.3 (#42)
- [ea18918d](https://github.com/kubedb/rabbitmq/commit/ea18918d) Update configurations and ports for DisableProtocol Support (#40)
- [a8f7d00d](https://github.com/kubedb/rabbitmq/commit/a8f7d00d) Add protocol plugins configurations and refactor webhook server (#39)
- [d0e559c6](https://github.com/kubedb/rabbitmq/commit/d0e559c6) Fix petset patch issue (#38)
- [6e8ac555](https://github.com/kubedb/rabbitmq/commit/6e8ac555) Prepare for release v0.2.0-rc.2 (#37)
- [8b6b97bb](https://github.com/kubedb/rabbitmq/commit/8b6b97bb) Prepare for release v0.2.0-rc.1 (#36)
- [ad06e69b](https://github.com/kubedb/rabbitmq/commit/ad06e69b) Prepare for release v0.2.0-rc.0 (#35)
- [4d025872](https://github.com/kubedb/rabbitmq/commit/4d025872) Update constants to use kubedb package (#34)



## [kubedb/redis](https://github.com/kubedb/redis)

### [v0.40.0](https://github.com/kubedb/redis/releases/tag/v0.40.0)

- [847f59c5](https://github.com/kubedb/redis/commit/847f59c57) Prepare for release v0.40.0 (#556)
- [a2cb2a09](https://github.com/kubedb/redis/commit/a2cb2a098) Use Go 1.23 (#554)
- [8e1b8b60](https://github.com/kubedb/redis/commit/8e1b8b600) Prepare for release v0.40.0-rc.3 (#555)
- [19c330c7](https://github.com/kubedb/redis/commit/19c330c78) Test against k8s 1.31 (#553)
- [e28ec45c](https://github.com/kubedb/redis/commit/e28ec45ca) Update Redis Webhook Server (#551)
- [89ab2ee1](https://github.com/kubedb/redis/commit/89ab2ee14) Remove Redis Petset Extra Enque (#552)
- [0dd62824](https://github.com/kubedb/redis/commit/0dd628243) Fix webhook crash issue for sentinel (#550)
- [7e9c8648](https://github.com/kubedb/redis/commit/7e9c8648c) Prepare for release v0.40.0-rc.2 (#549)
- [38b4b380](https://github.com/kubedb/redis/commit/38b4b3807) Update deps (#547)
- [9cb53e47](https://github.com/kubedb/redis/commit/9cb53e470) Prepare for release v0.40.0-rc.1 (#546)
- [8af74f1a](https://github.com/kubedb/redis/commit/8af74f1a0) Update master -> shards and replica count for cluster (#545)
- [824f81d9](https://github.com/kubedb/redis/commit/824f81d9b) Prepare for release v0.40.0-rc.0 (#544)
- [5fadc940](https://github.com/kubedb/redis/commit/5fadc9404) Use v1 api (#542)



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



## [kubedb/singlestore-restic-plugin](https://github.com/kubedb/singlestore-restic-plugin)

### [v0.5.0](https://github.com/kubedb/singlestore-restic-plugin/releases/tag/v0.5.0)

- [4146dcd](https://github.com/kubedb/singlestore-restic-plugin/commit/4146dcd) Prepare for release v0.5.0 (#22)
- [d01b066](https://github.com/kubedb/singlestore-restic-plugin/commit/d01b066) Use Go 1.23 (#20)
- [b811edc](https://github.com/kubedb/singlestore-restic-plugin/commit/b811edc) Remove provision condition and add ready condition (#19)
- [99b5c46](https://github.com/kubedb/singlestore-restic-plugin/commit/99b5c46) Prepare for release v0.5.0-rc.3 (#21)
- [1a8b875](https://github.com/kubedb/singlestore-restic-plugin/commit/1a8b875) Prepare for release v0.5.0-rc.2 (#18)
- [9bf8b9c](https://github.com/kubedb/singlestore-restic-plugin/commit/9bf8b9c) Prepare for release v0.5.0-rc.1 (#17)
- [efca7ae](https://github.com/kubedb/singlestore-restic-plugin/commit/efca7ae) Prepare for release v0.5.0-rc.0 (#16)
- [ae76f5a](https://github.com/kubedb/singlestore-restic-plugin/commit/ae76f5a) Update constants to use kubedb package (#15)



## [kubedb/solr](https://github.com/kubedb/solr)

### [v0.2.0](https://github.com/kubedb/solr/releases/tag/v0.2.0)

- [e1ba977a](https://github.com/kubedb/solr/commit/e1ba977a) Prepare for release v0.2.0 (#46)
- [ef089cf4](https://github.com/kubedb/solr/commit/ef089cf4) Use Go 1.23 (#43)
- [5dcbfa1d](https://github.com/kubedb/solr/commit/5dcbfa1d) Prepare for release v0.2.0-rc.3 (#45)
- [02eccb48](https://github.com/kubedb/solr/commit/02eccb48) Improve logs (#44)
- [82a533c8](https://github.com/kubedb/solr/commit/82a533c8) Test against k8s 1.31 (#42)
- [4e1ff74a](https://github.com/kubedb/solr/commit/4e1ff74a) Fix chroot issue to configure multiple solr cluster refering single zk (#41)
- [86526192](https://github.com/kubedb/solr/commit/86526192) Fix petset patch issue (#40)
- [a7534064](https://github.com/kubedb/solr/commit/a7534064) Prepare for release v0.2.0-rc.2 (#39)
- [1dd26676](https://github.com/kubedb/solr/commit/1dd26676) Changes related to ops manager (#38)
- [4d896266](https://github.com/kubedb/solr/commit/4d896266) Prepare for release v0.2.0-rc.1 (#37)
- [d8f02861](https://github.com/kubedb/solr/commit/d8f02861) fix constants (#36)
- [38d0c569](https://github.com/kubedb/solr/commit/38d0c569) Prepare for release v0.2.0-rc.0 (#35)
- [ca47b7be](https://github.com/kubedb/solr/commit/ca47b7be) Update constants to use kubedb package (#34)



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



## [kubedb/zookeeper](https://github.com/kubedb/zookeeper)

### [v0.2.0](https://github.com/kubedb/zookeeper/releases/tag/v0.2.0)

- [c07151b1](https://github.com/kubedb/zookeeper/commit/c07151b1) Prepare for release v0.2.0 (#38)
- [edbbf11e](https://github.com/kubedb/zookeeper/commit/edbbf11e) Use Go 1.23 (#35)
- [3c7a8b4d](https://github.com/kubedb/zookeeper/commit/3c7a8b4d) Prepare for release v0.2.0-rc.3 (#37)
- [6d9f2a50](https://github.com/kubedb/zookeeper/commit/6d9f2a50) Improve logging and fix manager (#36)
- [1051b1db](https://github.com/kubedb/zookeeper/commit/1051b1db) Prepare for release v0.2.0-rc.2 (#34)
- [2f695af7](https://github.com/kubedb/zookeeper/commit/2f695af7) Add ZooKeeper Client (#33)
- [68219ffe](https://github.com/kubedb/zookeeper/commit/68219ffe) Prepare for release v0.2.0-rc.1 (#31)
- [75a1fa49](https://github.com/kubedb/zookeeper/commit/75a1fa49) Prepare for release v0.2.0-rc.0 (#30)
- [bc8d242d](https://github.com/kubedb/zookeeper/commit/bc8d242d) Update constants to use kubedb package (#29)



## [kubedb/zookeeper-restic-plugin](https://github.com/kubedb/zookeeper-restic-plugin)

### [v0.3.0](https://github.com/kubedb/zookeeper-restic-plugin/releases/tag/v0.3.0)

- [fcd21a9](https://github.com/kubedb/zookeeper-restic-plugin/commit/fcd21a9) Prepare for release v0.3.0 (#14)
- [9cb3a5c](https://github.com/kubedb/zookeeper-restic-plugin/commit/9cb3a5c) Use Go 1.23 (#12)
- [0ef0eb0](https://github.com/kubedb/zookeeper-restic-plugin/commit/0ef0eb0) Prepare for release v0.3.0-rc.3 (#13)
- [0f2644b](https://github.com/kubedb/zookeeper-restic-plugin/commit/0f2644b) Prepare for release v0.3.0-rc.2 (#11)
- [6333dd9](https://github.com/kubedb/zookeeper-restic-plugin/commit/6333dd9) Prepare for release v0.3.0-rc.1 (#10)
- [3235ccf](https://github.com/kubedb/zookeeper-restic-plugin/commit/3235ccf) Prepare for release v0.3.0-rc.0 (#9)



