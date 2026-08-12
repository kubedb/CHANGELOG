# KubeDB v2026.8.12-rc.0 (2026-08-12)


## [kubedb/aerospike](https://github.com/kubedb/aerospike)

### [v0.2.0-rc.0](https://github.com/kubedb/aerospike/releases/tag/v0.2.0-rc.0)

- [45481d49](https://github.com/kubedb/aerospike/commit/45481d49) Prepare for release v0.2.0-rc.0 (#12)
- [81fe47b5](https://github.com/kubedb/aerospike/commit/81fe47b5) Config merging (#11)
- [1c54e254](https://github.com/kubedb/aerospike/commit/1c54e254) Use shared appbinding helper and record event (#10)
- [22a19d44](https://github.com/kubedb/aerospike/commit/22a19d44) Add appbinding (#9)
- [408f2a83](https://github.com/kubedb/aerospike/commit/408f2a83) Fix Health check (#4)
- [1c47f5b1](https://github.com/kubedb/aerospike/commit/1c47f5b1) Move deletion logic to apimachinery (#8)
- [615dd307](https://github.com/kubedb/aerospike/commit/615dd307) Upgrade aerospike-client-go v6 -> v8 (#7)



## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.66.0-rc.0](https://github.com/kubedb/apimachinery/releases/tag/v0.66.0-rc.0)

- [e5b9582c](https://github.com/kubedb/apimachinery/commit/e5b9582cc) Merge branch 'master' into release-0.66
- [24131c2c](https://github.com/kubedb/apimachinery/commit/24131c2c1) Update for release KubeStash@v2026.8.12-rc.0 (#1860)
- [93c13782](https://github.com/kubedb/apimachinery/commit/93c137821) documentdb mututaltls-ops (#1857)
- [58cafb3b](https://github.com/kubedb/apimachinery/commit/58cafb3ba) Patch spec.authSecret without clobbering the caller's DB object (#1853)
- [69764282](https://github.com/kubedb/apimachinery/commit/697642824) Documentdb tls & reconfiguretls (#1851)
- [b9e9a762](https://github.com/kubedb/apimachinery/commit/b9e9a7629) Bump grpc and related dependencies (#1856)
- [58ee3014](https://github.com/kubedb/apimachinery/commit/58ee30148) Add ClickHouse Keeper Ops-Req (#1835)
- [afd2eb59](https://github.com/kubedb/apimachinery/commit/afd2eb590) Extend Solr Reconfigure Ops for Backup (#1841)
- [02fbd4e5](https://github.com/kubedb/apimachinery/commit/02fbd4e5f) Add HanaDB horizontal scaling and update version ops api (#1803)
- [87057a23](https://github.com/kubedb/apimachinery/commit/87057a239) prevent Neo4j cross-scheme version upgrades (#1852)
- [69a6f213](https://github.com/kubedb/apimachinery/commit/69a6f2135) Improve Branch status information and create generic branch annotations (#1840)
- [e7db6932](https://github.com/kubedb/apimachinery/commit/e7db69325) Make ui.kubedb.com DatabaseConfiguration namespaced and get/list-able (#1849)
- [45019453](https://github.com/kubedb/apimachinery/commit/450194532) Add Milvus Minio Port Constants (#1845)
- [4aac2b8c](https://github.com/kubedb/apimachinery/commit/4aac2b8c4) add reconfigureSpec.WalletConfigSecret check in webhook (#1848)
- [99e5f4bb](https://github.com/kubedb/apimachinery/commit/99e5f4bb5) [MySQL] Topology Mode Change (#1844)
- [c1c4d426](https://github.com/kubedb/apimachinery/commit/c1c4d4268) Fix druid svcNames & ports for gateway (#1843)
- [9bfcfcf9](https://github.com/kubedb/apimachinery/commit/9bfcfcf94) Add Postgres Transparent Data Encryption (pg_tde) API (#1831)
- [1a21cba4](https://github.com/kubedb/apimachinery/commit/1a21cba4a) Make MongoDB probes tolerate mongosh stdout warnings (#1846)
- [243e61d2](https://github.com/kubedb/apimachinery/commit/243e61d23) Remove postgres-dependent validations from pgpool webhook
- [fd1d8ae0](https://github.com/kubedb/apimachinery/commit/fd1d8ae01) Remove postgres-dependent validations from pgpool webhook
- [58b803eb](https://github.com/kubedb/apimachinery/commit/58b803ebe) Remove pg-validation from pgpool
- [104ef573](https://github.com/kubedb/apimachinery/commit/104ef5739) Remove pg-validation from pgpool
- [4a5dafc7](https://github.com/kubedb/apimachinery/commit/4a5dafc75) Added SkipBackupPauseAnnotation constant (#1842)
- [b0a89cbd](https://github.com/kubedb/apimachinery/commit/b0a89cbd0) Add shared pkg/controller/secret auth-secret orchestrator (#1839)
- [7cbfa8c7](https://github.com/kubedb/apimachinery/commit/7cbfa8c75) Add weaviate update version ops api (#1837)
- [62501c6a](https://github.com/kubedb/apimachinery/commit/62501c6a8) Elasticsearch Virtual Secret Fix (#1815)
- [da69e33e](https://github.com/kubedb/apimachinery/commit/da69e33e3) Add shared monitor & appbinding packages (#1834)
- [861df689](https://github.com/kubedb/apimachinery/commit/861df6898) deletion: preserve-on-halt annotation, DoNotTerminate safety net, finalizer NotFound handling (#1833)
- [21556766](https://github.com/kubedb/apimachinery/commit/21556766c) Add default RunAsGroup to container security context (#1829)
- [90d0d0c4](https://github.com/kubedb/apimachinery/commit/90d0d0c4f) Add Virtual Secret Schema (#1828)
- [e5417274](https://github.com/kubedb/apimachinery/commit/e5417274b) Add shared pkg/controllers/deletion and normalize DB accessors (#1830)



## [kubedb/cassandra](https://github.com/kubedb/cassandra)

### [v0.19.0-rc.0](https://github.com/kubedb/cassandra/releases/tag/v0.19.0-rc.0)

- [75d76a66](https://github.com/kubedb/cassandra/commit/75d76a66) Prepare for release v0.19.0-rc.0 (#103)
- [2c731155](https://github.com/kubedb/cassandra/commit/2c731155) Use shared pkg/controller/secret for auth & keystore-cred secrets (#102)
- [f57d0a7e](https://github.com/kubedb/cassandra/commit/f57d0a7e) Add virtual secret support (#83)
- [cf4a2ef4](https://github.com/kubedb/cassandra/commit/cf4a2ef4) Adopt shared monitor/appbinding packages from apimachinery (#101)
- [5b321447](https://github.com/kubedb/cassandra/commit/5b321447) Set default resource limits before patching petset in vertical scaling (#99)
- [ecb67ef2](https://github.com/kubedb/cassandra/commit/ecb67ef2) Move deletion logic to apimachinery (#100)
- [cd89e8bf](https://github.com/kubedb/cassandra/commit/cd89e8bf) Merge pull request #98 from kubedb/v2026.7.10-master



## [kubedb/clickhouse](https://github.com/kubedb/clickhouse)

### [v0.21.0-rc.0](https://github.com/kubedb/clickhouse/releases/tag/v0.21.0-rc.0)

- [cf0be0bd](https://github.com/kubedb/clickhouse/commit/cf0be0bd) Prepare for release v0.21.0-rc.0 (#133)
- [1d1d2efc](https://github.com/kubedb/clickhouse/commit/1d1d2efc) Migrate auth-secret and internal-token management to shared secret package (#130)
- [361d2755](https://github.com/kubedb/clickhouse/commit/361d2755) Adopt shared monitor/appbinding packages from apimachinery (#129)
- [51d6f1c3](https://github.com/kubedb/clickhouse/commit/51d6f1c3) Add virtual secret support (#108)
- [68fd5fea](https://github.com/kubedb/clickhouse/commit/68fd5fea) Set default resource limits before patching petset in vertical scaling (#126)
- [b845cd26](https://github.com/kubedb/clickhouse/commit/b845cd26) Move deletion logic to apimachinery (#127)



## [kubedb/crd-manager](https://github.com/kubedb/crd-manager)

### [v0.21.0-rc.0](https://github.com/kubedb/crd-manager/releases/tag/v0.21.0-rc.0)

- [6ba7e0f6](https://github.com/kubedb/crd-manager/commit/6ba7e0f6) Prepare for release v0.21.0-rc.0 (#149)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.21.0-rc.0](https://github.com/kubedb/db-client-go/releases/tag/v0.21.0-rc.0)

- [7c17ffc1](https://github.com/kubedb/db-client-go/commit/7c17ffc1) Prepare for release v0.21.0-rc.0 (#259)
- [592d1ff9](https://github.com/kubedb/db-client-go/commit/592d1ff9) Update Solr Client (#256)
- [a5525a6e](https://github.com/kubedb/db-client-go/commit/a5525a6e) lower connect log visibility by changing klog V(3) to V(4) (#258)
- [55c58b66](https://github.com/kubedb/db-client-go/commit/55c58b66) Fix DNS issue for down scaling (#257)



## [kubedb/db2](https://github.com/kubedb/db2)

### [v0.7.0-rc.0](https://github.com/kubedb/db2/releases/tag/v0.7.0-rc.0)

- [be3f3b37](https://github.com/kubedb/db2/commit/be3f3b37) Prepare for release v0.7.0-rc.0 (#38)
- [ccf20e02](https://github.com/kubedb/db2/commit/ccf20e02) Migrate auth secret management to shared apimachinery secret package (#37)
- [4f924680](https://github.com/kubedb/db2/commit/4f924680) Add virtual secret support (#26)
- [87f6518b](https://github.com/kubedb/db2/commit/87f6518b) Move deletion logic to apimachinery (#36)



## [kubedb/documentdb](https://github.com/kubedb/documentdb)

### [v0.3.0-rc.0](https://github.com/kubedb/documentdb/releases/tag/v0.3.0-rc.0)

- [59ecdd3d](https://github.com/kubedb/documentdb/commit/59ecdd3d) Prepare for release v0.3.0-rc.0 (#46)
- [fa5afd65](https://github.com/kubedb/documentdb/commit/fa5afd65) Dcdb tls & reconfiguretls (#45)
- [0ed43723](https://github.com/kubedb/documentdb/commit/0ed43723) Add tuning config support to Reconfigure and VerticalScaling ops requests (#26)
- [efab7987](https://github.com/kubedb/documentdb/commit/efab7987) standalone-rotateauth (#43)
- [0d8d872b](https://github.com/kubedb/documentdb/commit/0d8d872b) Adopt shared apimachinery secret package for auth secret (#44)
- [7253e091](https://github.com/kubedb/documentdb/commit/7253e091) Adopt shared appbinding package from apimachinery (#42)
- [9876d3cc](https://github.com/kubedb/documentdb/commit/9876d3cc) Move deletion logic to apimachinery (#41)



## [kubedb/documentdb-coordinator](https://github.com/kubedb/documentdb-coordinator)

### [v0.2.0-rc.0](https://github.com/kubedb/documentdb-coordinator/releases/tag/v0.2.0-rc.0)

- [d78d225](https://github.com/kubedb/documentdb-coordinator/commit/d78d225) Prepare for release v0.2.0-rc.0 (#11)
- [1a762f1](https://github.com/kubedb/documentdb-coordinator/commit/1a762f1) Merge pull request #10 from kubedb/v2026.7.10-master



## [kubedb/elasticsearch](https://github.com/kubedb/elasticsearch)

### [v0.66.0-rc.0](https://github.com/kubedb/elasticsearch/releases/tag/v0.66.0-rc.0)

- [20095d87](https://github.com/kubedb/elasticsearch/commit/20095d87a) Prepare for release v0.66.0-rc.0 (#832)
- [32668c8f](https://github.com/kubedb/elasticsearch/commit/32668c8f3) Migrate auth secret handling to shared apimachinery secret package (#831)
- [ca2f2988](https://github.com/kubedb/elasticsearch/commit/ca2f2988d) Adopt shared monitor/appbinding packages from apimachinery (#830)
- [62ec1892](https://github.com/kubedb/elasticsearch/commit/62ec18929) Add virtual secret support (#813)
- [14fab5c7](https://github.com/kubedb/elasticsearch/commit/14fab5c77) Move deletion logic to apimachinery (#829)
- [50d3e6b3](https://github.com/kubedb/elasticsearch/commit/50d3e6b3e) Merge pull request #828 from kubedb/v2026.7.10-master



## [kubedb/gitops](https://github.com/kubedb/gitops)

### [v0.14.0-rc.0](https://github.com/kubedb/gitops/releases/tag/v0.14.0-rc.0)

- [c0f20f15](https://github.com/kubedb/gitops/commit/c0f20f15) Prepare for release v0.14.0-rc.0 (#89)
- [492a5dda](https://github.com/kubedb/gitops/commit/492a5dda) [Solr] Fix Solr API (#88)
- [2aee9ab8](https://github.com/kubedb/gitops/commit/2aee9ab8) Add Virtual Secret Support (#86)



## [kubedb/hanadb](https://github.com/kubedb/hanadb)

### [v0.7.0-rc.0](https://github.com/kubedb/hanadb/releases/tag/v0.7.0-rc.0)

- [2791d997](https://github.com/kubedb/hanadb/commit/2791d997) Prepare for release v0.7.0-rc.0 (#58)
- [d3fdd8a8](https://github.com/kubedb/hanadb/commit/d3fdd8a8) Implement horizontal scaling, update version ops (#47)
- [e5bbe114](https://github.com/kubedb/hanadb/commit/e5bbe114) Fix HanaDB ops and volume permission handling (#49)
- [dba6048b](https://github.com/kubedb/hanadb/commit/dba6048b) Add virtual secret support (#40)
- [4b038da8](https://github.com/kubedb/hanadb/commit/4b038da8) Adopt shared apimachinery secret package for auth secret handling (#56)
- [25b8aa29](https://github.com/kubedb/hanadb/commit/25b8aa29) Adopt shared monitor/appbinding packages from apimachinery (#55)
- [916a4696](https://github.com/kubedb/hanadb/commit/916a4696) Move deletion logic to apimachinery (#54)



## [kubedb/hanadb-coordinator](https://github.com/kubedb/hanadb-coordinator)

### [v0.6.0-rc.0](https://github.com/kubedb/hanadb-coordinator/releases/tag/v0.6.0-rc.0)

- [8185142d](https://github.com/kubedb/hanadb-coordinator/commit/8185142d) Prepare for release v0.6.0-rc.0 (#21)



## [kubedb/hazelcast](https://github.com/kubedb/hazelcast)

### [v0.12.0-rc.0](https://github.com/kubedb/hazelcast/releases/tag/v0.12.0-rc.0)

- [35ebce41](https://github.com/kubedb/hazelcast/commit/35ebce41) Prepare for release v0.12.0-rc.0 (#65)
- [ad3bf0c5](https://github.com/kubedb/hazelcast/commit/ad3bf0c5) Migrate auth-secret management to shared apimachinery secret package (#64)
- [e36af849](https://github.com/kubedb/hazelcast/commit/e36af849) Add virtual secret support (#47)
- [5b1409ef](https://github.com/kubedb/hazelcast/commit/5b1409ef) Add StorageMigration OpsRequest support for Hazelcast (#45)
- [a9a6cd5b](https://github.com/kubedb/hazelcast/commit/a9a6cd5b) Use shared monitor and appbinding packages (#63)
- [85d20938](https://github.com/kubedb/hazelcast/commit/85d20938) Set default resource limits before patching petset in vertical scaling
- [136b30e8](https://github.com/kubedb/hazelcast/commit/136b30e8) Move deletion logic to apimachinery (#62)



## [kubedb/kafka](https://github.com/kubedb/kafka)

### [v0.37.0-rc.0](https://github.com/kubedb/kafka/releases/tag/v0.37.0-rc.0)

- [28856e2e](https://github.com/kubedb/kafka/commit/28856e2e) Prepare for release v0.37.0-rc.0 (#217)
- [189fe261](https://github.com/kubedb/kafka/commit/189fe261) Migrate kafka-cluster and connect-cluster auth secrets to shared secret package (#216)
- [c5ad9ccc](https://github.com/kubedb/kafka/commit/c5ad9ccc) Use shared monitor and appbinding packages (#215)
- [c435a470](https://github.com/kubedb/kafka/commit/c435a470) Add virtual secret support (#197)
- [61481399](https://github.com/kubedb/kafka/commit/61481399) Set default resource limits before patching petset in vertical scaling
- [899e74ab](https://github.com/kubedb/kafka/commit/899e74ab) Move deletion logic to apimachinery (#214)
- [86fa0034](https://github.com/kubedb/kafka/commit/86fa0034) Merge pull request #212 from kubedb/v2026.7.10-master



## [kubedb/kubedb-manifest-plugin](https://github.com/kubedb/kubedb-manifest-plugin)

### [v0.29.0-rc.0](https://github.com/kubedb/kubedb-manifest-plugin/releases/tag/v0.29.0-rc.0)

- [cd4c5601](https://github.com/kubedb/kubedb-manifest-plugin/commit/cd4c5601) Prepare for release v0.29.0-rc.0 (#141)
- [3fd5160f](https://github.com/kubedb/kubedb-manifest-plugin/commit/3fd5160f) Add Virtual Secret Support (#137)



## [kubedb/kubedb-verifier](https://github.com/kubedb/kubedb-verifier)

### [v0.17.0-rc.0](https://github.com/kubedb/kubedb-verifier/releases/tag/v0.17.0-rc.0)

- [76948c76](https://github.com/kubedb/kubedb-verifier/commit/76948c76) Prepare for release v0.17.0-rc.0 (#58)



## [kubedb/mariadb](https://github.com/kubedb/mariadb)

### [v0.50.0-rc.0](https://github.com/kubedb/mariadb/releases/tag/v0.50.0-rc.0)

- [9e28da96](https://github.com/kubedb/mariadb/commit/9e28da965) Prepare for release v0.50.0-rc.0 (#426)
- [b2d3e8c5](https://github.com/kubedb/mariadb/commit/b2d3e8c51) Fail the OpsRequest when a step exceeds its timeout (#425)
- [e5a2ea1e](https://github.com/kubedb/mariadb/commit/e5a2ea1ea) Migrate auth-secret handling to shared apimachinery secret package (#424)
- [9f0384d0](https://github.com/kubedb/mariadb/commit/9f0384d04) Adopt shared monitor/appbinding packages from apimachinery (#423)
- [b50b19c8](https://github.com/kubedb/mariadb/commit/b50b19c8a) Add virtual secret support (#403)
- [ae727436](https://github.com/kubedb/mariadb/commit/ae727436b) Set default resource limits before patching petset in vertical scaling (#421)
- [43aaf0a2](https://github.com/kubedb/mariadb/commit/43aaf0a21) Move deletion logic to apimachinery (#422)
- [d47908bb](https://github.com/kubedb/mariadb/commit/d47908bb4) Merge pull request #420 from kubedb/v2026.7.10-master



## [kubedb/mariadb-coordinator](https://github.com/kubedb/mariadb-coordinator)

### [v0.46.0-rc.0](https://github.com/kubedb/mariadb-coordinator/releases/tag/v0.46.0-rc.0)

- [4772461d](https://github.com/kubedb/mariadb-coordinator/commit/4772461d) Prepare for release v0.46.0-rc.0 (#187)



## [kubedb/mariadb-restic-plugin](https://github.com/kubedb/mariadb-restic-plugin)

### [v0.24.0-rc.0](https://github.com/kubedb/mariadb-restic-plugin/releases/tag/v0.24.0-rc.0)

- [69621d76](https://github.com/kubedb/mariadb-restic-plugin/commit/69621d76) Prepare for release v0.24.0-rc.0 (#101)
- [c3998c88](https://github.com/kubedb/mariadb-restic-plugin/commit/c3998c88) FIx 10.6.16 backup tls issue (#100)
- [f3f205c1](https://github.com/kubedb/mariadb-restic-plugin/commit/f3f205c1) Add Virtual Secret Support (#97)



## [kubedb/migrator](https://github.com/kubedb/migrator)

### [v0.6.0-rc.0](https://github.com/kubedb/migrator/releases/tag/v0.6.0-rc.0)

- [e9d330c6](https://github.com/kubedb/migrator/commit/e9d330c6) Prepare for release v0.6.0-rc.0 (#48)
- [9ccfbe83](https://github.com/kubedb/migrator/commit/9ccfbe83) Fix mssql snapshot tds eof retry (#47)
- [a5b1a307](https://github.com/kubedb/migrator/commit/a5b1a307) Update postgres sequence value when migration stops (#46)
- [91bfb3ac](https://github.com/kubedb/migrator/commit/91bfb3ac) Fixed release issue,waited for inital lsn for cdc
- [d9bf2272](https://github.com/kubedb/migrator/commit/d9bf2272) Add non root user in every docker file (#44)



## [kubedb/mongodb](https://github.com/kubedb/mongodb)

### [v0.59.0-rc.0](https://github.com/kubedb/mongodb/releases/tag/v0.59.0-rc.0)

- [2af7c3d8](https://github.com/kubedb/mongodb/commit/2af7c3d87) Prepare for release v0.59.0-rc.0 (#782)
- [a3753bec](https://github.com/kubedb/mongodb/commit/a3753bece) Use shared pkg/controller/secret for auth & keyfile secrets (#781)
- [620d2763](https://github.com/kubedb/mongodb/commit/620d27631) Adopt shared monitor/appbinding packages from apimachinery (#780)
- [59977bef](https://github.com/kubedb/mongodb/commit/59977bef8) Virtual Secret Ops Support (#779)
- [91595b9a](https://github.com/kubedb/mongodb/commit/91595b9ad) Use shared pkg/controller/deletion for termination and halt (#778)
- [14997977](https://github.com/kubedb/mongodb/commit/149979774) Merge pull request #777 from kubedb/v2026.7.10-master



## [kubedb/mongodb-csi-snapshotter-plugin](https://github.com/kubedb/mongodb-csi-snapshotter-plugin)

### [v0.27.0-rc.0](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/releases/tag/v0.27.0-rc.0)

- [b2684818](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/b2684818) Prepare for release v0.27.0-rc.0 (#89)



## [kubedb/mongodb-restic-plugin](https://github.com/kubedb/mongodb-restic-plugin)

### [v0.29.0-rc.0](https://github.com/kubedb/mongodb-restic-plugin/releases/tag/v0.29.0-rc.0)

- [ba50bd65](https://github.com/kubedb/mongodb-restic-plugin/commit/ba50bd65) Prepare for release v0.29.0-rc.0 (#136)
- [802a7051](https://github.com/kubedb/mongodb-restic-plugin/commit/802a7051) Add Virtual Secret Support (#133)



## [kubedb/mssqlserver-archiver](https://github.com/kubedb/mssqlserver-archiver)

### [v0.20.0-rc.0](https://github.com/kubedb/mssqlserver-archiver/releases/tag/v0.20.0-rc.0)

- [5fc9453](https://github.com/kubedb/mssqlserver-archiver/commit/5fc9453) Prepare for release v0.20.0-rc.0 (#34)



## [kubedb/mssqlserver-walg-plugin](https://github.com/kubedb/mssqlserver-walg-plugin)

### [v0.20.0-rc.0](https://github.com/kubedb/mssqlserver-walg-plugin/releases/tag/v0.20.0-rc.0)

- [4b43a1c5](https://github.com/kubedb/mssqlserver-walg-plugin/commit/4b43a1c5) Prepare for release v0.20.0-rc.0 (#67)
- [12f92505](https://github.com/kubedb/mssqlserver-walg-plugin/commit/12f92505) Integrate virtual secret (#64)



## [kubedb/mysql-coordinator](https://github.com/kubedb/mysql-coordinator)

### [v0.44.0-rc.0](https://github.com/kubedb/mysql-coordinator/releases/tag/v0.44.0-rc.0)

- [c1cd7cf5](https://github.com/kubedb/mysql-coordinator/commit/c1cd7cf5) Prepare for release v0.44.0-rc.0 (#190)
- [54b35ec1](https://github.com/kubedb/mysql-coordinator/commit/54b35ec1) Fix Join Cluster (#189)



## [kubedb/mysql-restic-plugin](https://github.com/kubedb/mysql-restic-plugin)

### [v0.29.0-rc.0](https://github.com/kubedb/mysql-restic-plugin/releases/tag/v0.29.0-rc.0)

- [78d689a8](https://github.com/kubedb/mysql-restic-plugin/commit/78d689a8) Prepare for release v0.29.0-rc.0 (#122)
- [c863d090](https://github.com/kubedb/mysql-restic-plugin/commit/c863d090) Fix --ssl-ca being silently dropped from the client command (#121)
- [78790d48](https://github.com/kubedb/mysql-restic-plugin/commit/78790d48) Add Virtual Secret Support (#118)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.44.0-rc.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.44.0-rc.0)

- [3d63a45](https://github.com/kubedb/mysql-router-init/commit/3d63a45) Prepare for release v0.44.0-rc.0 (#68)



## [kubedb/neo4j](https://github.com/kubedb/neo4j)

### [v0.7.0-rc.0](https://github.com/kubedb/neo4j/releases/tag/v0.7.0-rc.0)

- [6652df10](https://github.com/kubedb/neo4j/commit/6652df10) Merge commit '372d285b4261d4b760062334d8eda695b773296e' into release-0.7
- [372d285b](https://github.com/kubedb/neo4j/commit/372d285b) Prepare for release v0.7.0-rc.0 (#60)
- [4071b5f9](https://github.com/kubedb/neo4j/commit/4071b5f9) Retag v0.7.0 for reconfigureTLS fix (#59)
- [b77228b2](https://github.com/kubedb/neo4j/commit/b77228b2) Add Neo4j SemVer Support (#58)
- [68bf9055](https://github.com/kubedb/neo4j/commit/68bf9055) Use shared pkg/controller/secret for auth secret (#57)
- [d7e6539c](https://github.com/kubedb/neo4j/commit/d7e6539c) Use shared monitor and appbinding packages (#56)
- [ad9c2b06](https://github.com/kubedb/neo4j/commit/ad9c2b06) Add virtual secret support (#35)
- [3c7142e1](https://github.com/kubedb/neo4j/commit/3c7142e1) Set default resource limits before patching petset in vertical scaling (#54)
- [d670768b](https://github.com/kubedb/neo4j/commit/d670768b) Move deletion logic to apimachinery (#55)



## [kubedb/neo4j-backup-plugin](https://github.com/kubedb/neo4j-backup-plugin)

### [v0.2.0-rc.0](https://github.com/kubedb/neo4j-backup-plugin/releases/tag/v0.2.0-rc.0)

- [b6daf30](https://github.com/kubedb/neo4j-backup-plugin/commit/b6daf30) Prepare for release v0.2.0-rc.0 (#10)



## [kubedb/percona-xtradb](https://github.com/kubedb/percona-xtradb)

### [v0.53.0-rc.0](https://github.com/kubedb/percona-xtradb/releases/tag/v0.53.0-rc.0)

- [c9b14d9d](https://github.com/kubedb/percona-xtradb/commit/c9b14d9d7) Prepare for release v0.53.0-rc.0 (#472)
- [421e4a5c](https://github.com/kubedb/percona-xtradb/commit/421e4a5c9) Migrate auth-secret management to shared kubedb.dev/apimachinery secret package (#471)
- [454eeb0b](https://github.com/kubedb/percona-xtradb/commit/454eeb0b2) Use shared monitor and appbinding packages (#470)
- [ee188463](https://github.com/kubedb/percona-xtradb/commit/ee1884631) Add virtual secret support (#455)
- [bb4bf36d](https://github.com/kubedb/percona-xtradb/commit/bb4bf36de) Set default resource limits before patching petset in vertical scaling (#468)
- [f42d4b38](https://github.com/kubedb/percona-xtradb/commit/f42d4b388) Move deletion logic to apimachinery (#469)



## [kubedb/percona-xtradb-coordinator](https://github.com/kubedb/percona-xtradb-coordinator)

### [v0.39.0-rc.0](https://github.com/kubedb/percona-xtradb-coordinator/releases/tag/v0.39.0-rc.0)

- [62a3b59d](https://github.com/kubedb/percona-xtradb-coordinator/commit/62a3b59d) Prepare for release v0.39.0-rc.0 (#134)



## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.66.0-rc.0](https://github.com/kubedb/postgres/releases/tag/v0.66.0-rc.0)

- [5da0b6b8](https://github.com/kubedb/postgres/commit/5da0b6b89) Prepare for release v0.66.0-rc.0 (#924)
- [0558f966](https://github.com/kubedb/postgres/commit/0558f966d) Wire pg_tde Transparent Data Encryption into Postgres (#917)
- [e777c0a3](https://github.com/kubedb/postgres/commit/e777c0a3a) Add branched mode for KubeDB Courier Branch (kubedb.com/branched-from) (#912)
- [cfa2def6](https://github.com/kubedb/postgres/commit/cfa2def6a) Add pg-coordinator support for remote replica pg_rewind and reinitialization (#908)
- [4ee8265d](https://github.com/kubedb/postgres/commit/4ee8265df) Adopt shared monitor/appbinding packages from apimachinery (#920)
- [fb27a495](https://github.com/kubedb/postgres/commit/fb27a4957) Migrate auth secret management to shared apimachinery secret package (#921)
- [0e5a1ff5](https://github.com/kubedb/postgres/commit/0e5a1ff5e) Virtual Secret Ops Support (#918)
- [6fc4c37a](https://github.com/kubedb/postgres/commit/6fc4c37ac) feat: implement git-sync init container for Postgres (#892)
- [2d465d86](https://github.com/kubedb/postgres/commit/2d465d864) Move deletion logic to apimachinery (#919)
- [eda65ceb](https://github.com/kubedb/postgres/commit/eda65ceb5) Merge pull request #915 from kubedb/v2026.7.10-master



## [kubedb/postgres-archiver](https://github.com/kubedb/postgres-archiver)

### [v0.27.0-rc.0](https://github.com/kubedb/postgres-archiver/releases/tag/v0.27.0-rc.0)

- [9ee6f7aa](https://github.com/kubedb/postgres-archiver/commit/9ee6f7aa) Prepare for release v0.27.0-rc.0 (#116)
- [9b64fafc](https://github.com/kubedb/postgres-archiver/commit/9b64fafc) Build the postgres-archiver from the Percona image for 17.9-percona (pg_tde PITR) (#115)
- [4d647cb7](https://github.com/kubedb/postgres-archiver/commit/4d647cb7) Merge pull request #114 from kubedb/v2026.7.10-master



## [kubedb/postgres-restic-plugin](https://github.com/kubedb/postgres-restic-plugin)

### [v0.29.0-rc.0](https://github.com/kubedb/postgres-restic-plugin/releases/tag/v0.29.0-rc.0)

- [fb1c5cd1](https://github.com/kubedb/postgres-restic-plugin/commit/fb1c5cd1) Prepare for release v0.29.0-rc.0 (#122)
- [5620d3a1](https://github.com/kubedb/postgres-restic-plugin/commit/5620d3a1) Add Percona pg_tde physical backup support (17.9-percona) (#119)
- [c0ae4e7a](https://github.com/kubedb/postgres-restic-plugin/commit/c0ae4e7a) Add Virtual Secret Support (#116)



## [kubedb/qdrant](https://github.com/kubedb/qdrant)

### [v0.7.0-rc.0](https://github.com/kubedb/qdrant/releases/tag/v0.7.0-rc.0)

- [c53cd81b](https://github.com/kubedb/qdrant/commit/c53cd81b) Prepare for release v0.7.0-rc.0 (#59)
- [7fcc9d7d](https://github.com/kubedb/qdrant/commit/7fcc9d7d) Adopt shared monitor/appbinding packages (#58)
- [d6fa13f6](https://github.com/kubedb/qdrant/commit/d6fa13f6) Add virtual secret support (#42)
- [5adbcdf0](https://github.com/kubedb/qdrant/commit/5adbcdf0) Set default resource limits before patching petset in vertical scaling (#56)
- [984a3bd7](https://github.com/kubedb/qdrant/commit/984a3bd7) Move deletion logic to apimachinery (#57)



## [kubedb/redis](https://github.com/kubedb/redis)

### [v0.59.0-rc.0](https://github.com/kubedb/redis/releases/tag/v0.59.0-rc.0)

- [568642d9](https://github.com/kubedb/redis/commit/568642d99) Prepare for release v0.59.0-rc.0 (#675)
- [4479fd1b](https://github.com/kubedb/redis/commit/4479fd1b3) ACL Custom secret add (#668)
- [628b529d](https://github.com/kubedb/redis/commit/628b529db) Adopt shared secret package from apimachinery (#674)
- [cdf520da](https://github.com/kubedb/redis/commit/cdf520da5) Adopt shared monitor/appbinding packages from apimachinery (#672)
- [92957c09](https://github.com/kubedb/redis/commit/92957c097) Virtual Secret Ops Support (#670)
- [ce19a258](https://github.com/kubedb/redis/commit/ce19a2589) Set default resource limits before patching petset in vertical scaling
- [11ca8d63](https://github.com/kubedb/redis/commit/11ca8d636) Move deletion logic to apimachinery (#671)
- [bbf192dd](https://github.com/kubedb/redis/commit/bbf192ddb) Merge pull request #667 from kubedb/v2026.7.10-master



## [kubedb/redis-coordinator](https://github.com/kubedb/redis-coordinator)

### [v0.45.0-rc.0](https://github.com/kubedb/redis-coordinator/releases/tag/v0.45.0-rc.0)

- [c88db39d](https://github.com/kubedb/redis-coordinator/commit/c88db39d) Prepare for release v0.45.0-rc.0 (#167)



## [kubedb/redis-restic-plugin](https://github.com/kubedb/redis-restic-plugin)

### [v0.29.0-rc.0](https://github.com/kubedb/redis-restic-plugin/releases/tag/v0.29.0-rc.0)

- [ab2ff427](https://github.com/kubedb/redis-restic-plugin/commit/ab2ff427) Prepare for release v0.29.0-rc.0 (#114)
- [9490bd22](https://github.com/kubedb/redis-restic-plugin/commit/9490bd22) Add Virtual Secret Support (#111)



## [kubedb/replication-mode-detector](https://github.com/kubedb/replication-mode-detector)

### [v0.53.0-rc.0](https://github.com/kubedb/replication-mode-detector/releases/tag/v0.53.0-rc.0)

- [2835220a](https://github.com/kubedb/replication-mode-detector/commit/2835220a) Prepare for release v0.53.0-rc.0 (#329)



## [kubedb/singlestore](https://github.com/kubedb/singlestore)

### [v0.21.0-rc.0](https://github.com/kubedb/singlestore/releases/tag/v0.21.0-rc.0)

- [1787b18b](https://github.com/kubedb/singlestore/commit/1787b18b) Prepare for release v0.21.0-rc.0 (#143)
- [d0ac823e](https://github.com/kubedb/singlestore/commit/d0ac823e) Use shared apimachinery secret package (#142)
- [264909c1](https://github.com/kubedb/singlestore/commit/264909c1) Use shared monitor and appbinding packages (#141)
- [7ff8879b](https://github.com/kubedb/singlestore/commit/7ff8879b) Add virtual secret support (#123)
- [ae4ba9ce](https://github.com/kubedb/singlestore/commit/ae4ba9ce) Move deletion logic to apimachinery (#140)



## [kubedb/singlestore-coordinator](https://github.com/kubedb/singlestore-coordinator)

### [v0.21.0-rc.0](https://github.com/kubedb/singlestore-coordinator/releases/tag/v0.21.0-rc.0)

- [072b894d](https://github.com/kubedb/singlestore-coordinator/commit/072b894d) Prepare for release v0.21.0-rc.0 (#79)



## [kubedb/singlestore-restic-plugin](https://github.com/kubedb/singlestore-restic-plugin)

### [v0.24.0-rc.0](https://github.com/kubedb/singlestore-restic-plugin/releases/tag/v0.24.0-rc.0)

- [0e259058](https://github.com/kubedb/singlestore-restic-plugin/commit/0e259058) Prepare for release v0.24.0-rc.0 (#94)
- [67f1a95e](https://github.com/kubedb/singlestore-restic-plugin/commit/67f1a95e) Fix --ssl-ca being silently dropped from the client command (#93)
- [f50bc94f](https://github.com/kubedb/singlestore-restic-plugin/commit/f50bc94f) Add Virtual Secret Support (#90)
- [1fe1b17d](https://github.com/kubedb/singlestore-restic-plugin/commit/1fe1b17d) Merge pull request #92 from kubedb/v2026.7.10-master



## [kubedb/solr](https://github.com/kubedb/solr)

### [v0.21.0-rc.0](https://github.com/kubedb/solr/releases/tag/v0.21.0-rc.0)

- [25754c5f](https://github.com/kubedb/solr/commit/25754c5f) Prepare for release v0.21.0-rc.0 (#155)
- [0afd2d73](https://github.com/kubedb/solr/commit/0afd2d73) API fix [Unblock RC] (#154)
- [32dfb2d9](https://github.com/kubedb/solr/commit/32dfb2d9) Adopt shared secret package from apimachinery (#152)
- [22d3d42e](https://github.com/kubedb/solr/commit/22d3d42e) Adopt shared monitor/appbinding packages from apimachinery (#150)
- [dbaaa4f9](https://github.com/kubedb/solr/commit/dbaaa4f9) Add virtual secret support (#131)
- [5f23c1f2](https://github.com/kubedb/solr/commit/5f23c1f2) Set default resource limits before patching petset in vertical scaling (#147)
- [a0c4213c](https://github.com/kubedb/solr/commit/a0c4213c) Honor user-provided renewBefore in TLS certificate ops (#146)
- [cd576f42](https://github.com/kubedb/solr/commit/cd576f42) Move deletion logic to apimachinery (#148)



## [kubedb/tests](https://github.com/kubedb/tests)

### [v0.51.0-rc.0](https://github.com/kubedb/tests/releases/tag/v0.51.0-rc.0)

- [852fc45f](https://github.com/kubedb/tests/commit/852fc45fe) Prepare for release v0.51.0-rc.0 (#551)
- [ea820e35](https://github.com/kubedb/tests/commit/ea820e351) Add Postgres pg_tde (TDE) e2e coverage behind --enable-tde (#549)
- [3cfb92a9](https://github.com/kubedb/tests/commit/3cfb92a90) Add MongoDB Archiver CI (#463)
- [9a67cef0](https://github.com/kubedb/tests/commit/9a67cef0d) Add E2E tests for Milvus (#530)
- [3c251405](https://github.com/kubedb/tests/commit/3c2514059) Add E2E tests for Weaviate (#534)
- [3c6be199](https://github.com/kubedb/tests/commit/3c6be199c) Add E2E tests for SAP HANA (#527)
- [298da3c2](https://github.com/kubedb/tests/commit/298da3c29) Add E2E tests for Ignite (#529)
- [3953e608](https://github.com/kubedb/tests/commit/3953e6082) MSSQL Secondary Access Mode (#483)
- [c9d5734e](https://github.com/kubedb/tests/commit/c9d5734e8) Add E2E tests for DB2 (#526)
- [07c4c77c](https://github.com/kubedb/tests/commit/07c4c77c7) Add E2E tests for Hazelcast (#528)
- [e8ef8cb2](https://github.com/kubedb/tests/commit/e8ef8cb25) Add Common changes (kubestash), Neo4j Disable Security (#548)



## [kubedb/weaviate](https://github.com/kubedb/weaviate)

### [v0.7.0-rc.0](https://github.com/kubedb/weaviate/releases/tag/v0.7.0-rc.0)

- [d445e431](https://github.com/kubedb/weaviate/commit/d445e431) Prepare for release v0.7.0-rc.0 (#59)
- [c87d4ab5](https://github.com/kubedb/weaviate/commit/c87d4ab5) Add update-version ops (#56)
- [73297e3d](https://github.com/kubedb/weaviate/commit/73297e3d) Use shared monitor and appbinding packages (#57)
- [c0de6cde](https://github.com/kubedb/weaviate/commit/c0de6cde) Add virtual secret support (#36)
- [52ae615f](https://github.com/kubedb/weaviate/commit/52ae615f) Set default resource limits before patching petset in vertical scaling (#54)
- [47f19de7](https://github.com/kubedb/weaviate/commit/47f19de7) Move deletion logic to apimachinery (#55)



## [kubedb/xtrabackup-restic-plugin](https://github.com/kubedb/xtrabackup-restic-plugin)

### [v0.14.0-rc.0](https://github.com/kubedb/xtrabackup-restic-plugin/releases/tag/v0.14.0-rc.0)

- [0ea98fb8](https://github.com/kubedb/xtrabackup-restic-plugin/commit/0ea98fb8) Prepare for release v0.14.0-rc.0 (#62)
- [f0b1e934](https://github.com/kubedb/xtrabackup-restic-plugin/commit/f0b1e934) Add Virtual Secret Support (#59)



## [kubedb/zookeeper](https://github.com/kubedb/zookeeper)

### [v0.21.0-rc.0](https://github.com/kubedb/zookeeper/releases/tag/v0.21.0-rc.0)

- [1b6e46fa](https://github.com/kubedb/zookeeper/commit/1b6e46fa) Prepare for release v0.21.0-rc.0 (#139)
- [fee971ca](https://github.com/kubedb/zookeeper/commit/fee971ca) Adopt shared secret package from apimachinery (#138)
- [6594c59e](https://github.com/kubedb/zookeeper/commit/6594c59e) Adopt shared monitor/appbinding packages from apimachinery (#137)
- [ef611f33](https://github.com/kubedb/zookeeper/commit/ef611f33) Add virtual secret support (#123)
- [76c37064](https://github.com/kubedb/zookeeper/commit/76c37064) Set default resource limits before patching petset in vertical scaling
- [d39eb3cd](https://github.com/kubedb/zookeeper/commit/d39eb3cd) Move deletion logic to apimachinery (#136)



## [kubedb/zookeeper-restic-plugin](https://github.com/kubedb/zookeeper-restic-plugin)

### [v0.21.0-rc.0](https://github.com/kubedb/zookeeper-restic-plugin/releases/tag/v0.21.0-rc.0)

- [c31c75e2](https://github.com/kubedb/zookeeper-restic-plugin/commit/c31c75e2) Prepare for release v0.21.0-rc.0 (#78)
- [9f1474e8](https://github.com/kubedb/zookeeper-restic-plugin/commit/9f1474e8) Add Virtual Secret Support (#75)
- [f9a0c8f0](https://github.com/kubedb/zookeeper-restic-plugin/commit/f9a0c8f0) Merge pull request #77 from kubedb/v2026.7.10-master



