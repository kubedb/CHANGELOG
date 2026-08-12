# KubeDB v2026.8.12-rc.0 (2026-08-12)


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



## [kubedb/documentdb](https://github.com/kubedb/documentdb)

### [v0.3.0-rc.0](https://github.com/kubedb/documentdb/releases/tag/v0.3.0-rc.0)

- [59ecdd3d](https://github.com/kubedb/documentdb/commit/59ecdd3d) Prepare for release v0.3.0-rc.0 (#46)
- [fa5afd65](https://github.com/kubedb/documentdb/commit/fa5afd65) Dcdb tls & reconfiguretls (#45)
- [0ed43723](https://github.com/kubedb/documentdb/commit/0ed43723) Add tuning config support to Reconfigure and VerticalScaling ops requests (#26)
- [efab7987](https://github.com/kubedb/documentdb/commit/efab7987) standalone-rotateauth (#43)
- [0d8d872b](https://github.com/kubedb/documentdb/commit/0d8d872b) Adopt shared apimachinery secret package for auth secret (#44)
- [7253e091](https://github.com/kubedb/documentdb/commit/7253e091) Adopt shared appbinding package from apimachinery (#42)
- [9876d3cc](https://github.com/kubedb/documentdb/commit/9876d3cc) Move deletion logic to apimachinery (#41)



## [kubedb/kafka](https://github.com/kubedb/kafka)

### [v0.37.0-rc.0](https://github.com/kubedb/kafka/releases/tag/v0.37.0-rc.0)

- [28856e2e](https://github.com/kubedb/kafka/commit/28856e2e) Prepare for release v0.37.0-rc.0 (#217)
- [189fe261](https://github.com/kubedb/kafka/commit/189fe261) Migrate kafka-cluster and connect-cluster auth secrets to shared secret package (#216)
- [c5ad9ccc](https://github.com/kubedb/kafka/commit/c5ad9ccc) Use shared monitor and appbinding packages (#215)
- [c435a470](https://github.com/kubedb/kafka/commit/c435a470) Add virtual secret support (#197)
- [61481399](https://github.com/kubedb/kafka/commit/61481399) Set default resource limits before patching petset in vertical scaling
- [899e74ab](https://github.com/kubedb/kafka/commit/899e74ab) Move deletion logic to apimachinery (#214)
- [86fa0034](https://github.com/kubedb/kafka/commit/86fa0034) Merge pull request #212 from kubedb/v2026.7.10-master



## [kubedb/mariadb-coordinator](https://github.com/kubedb/mariadb-coordinator)

### [v0.46.0-rc.0](https://github.com/kubedb/mariadb-coordinator/releases/tag/v0.46.0-rc.0)

- [4772461d](https://github.com/kubedb/mariadb-coordinator/commit/4772461d) Prepare for release v0.46.0-rc.0 (#187)



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



## [kubedb/mssqlserver-walg-plugin](https://github.com/kubedb/mssqlserver-walg-plugin)

### [v0.20.0-rc.0](https://github.com/kubedb/mssqlserver-walg-plugin/releases/tag/v0.20.0-rc.0)

- [4b43a1c5](https://github.com/kubedb/mssqlserver-walg-plugin/commit/4b43a1c5) Prepare for release v0.20.0-rc.0 (#67)
- [12f92505](https://github.com/kubedb/mssqlserver-walg-plugin/commit/12f92505) Integrate virtual secret (#64)



## [kubedb/percona-xtradb-coordinator](https://github.com/kubedb/percona-xtradb-coordinator)

### [v0.39.0-rc.0](https://github.com/kubedb/percona-xtradb-coordinator/releases/tag/v0.39.0-rc.0)

- [62a3b59d](https://github.com/kubedb/percona-xtradb-coordinator/commit/62a3b59d) Prepare for release v0.39.0-rc.0 (#134)



## [kubedb/singlestore-coordinator](https://github.com/kubedb/singlestore-coordinator)

### [v0.21.0-rc.0](https://github.com/kubedb/singlestore-coordinator/releases/tag/v0.21.0-rc.0)

- [072b894d](https://github.com/kubedb/singlestore-coordinator/commit/072b894d) Prepare for release v0.21.0-rc.0 (#79)



## [kubedb/singlestore-restic-plugin](https://github.com/kubedb/singlestore-restic-plugin)

### [v0.24.0-rc.0](https://github.com/kubedb/singlestore-restic-plugin/releases/tag/v0.24.0-rc.0)

- [0e259058](https://github.com/kubedb/singlestore-restic-plugin/commit/0e259058) Prepare for release v0.24.0-rc.0 (#94)
- [67f1a95e](https://github.com/kubedb/singlestore-restic-plugin/commit/67f1a95e) Fix --ssl-ca being silently dropped from the client command (#93)
- [f50bc94f](https://github.com/kubedb/singlestore-restic-plugin/commit/f50bc94f) Add Virtual Secret Support (#90)
- [1fe1b17d](https://github.com/kubedb/singlestore-restic-plugin/commit/1fe1b17d) Merge pull request #92 from kubedb/v2026.7.10-master



## [kubedb/weaviate](https://github.com/kubedb/weaviate)

### [v0.7.0-rc.0](https://github.com/kubedb/weaviate/releases/tag/v0.7.0-rc.0)

- [d445e431](https://github.com/kubedb/weaviate/commit/d445e431) Prepare for release v0.7.0-rc.0 (#59)
- [c87d4ab5](https://github.com/kubedb/weaviate/commit/c87d4ab5) Add update-version ops (#56)
- [73297e3d](https://github.com/kubedb/weaviate/commit/73297e3d) Use shared monitor and appbinding packages (#57)
- [c0de6cde](https://github.com/kubedb/weaviate/commit/c0de6cde) Add virtual secret support (#36)
- [52ae615f](https://github.com/kubedb/weaviate/commit/52ae615f) Set default resource limits before patching petset in vertical scaling (#54)
- [47f19de7](https://github.com/kubedb/weaviate/commit/47f19de7) Move deletion logic to apimachinery (#55)



