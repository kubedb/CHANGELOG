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



## [kubedb/crd-manager](https://github.com/kubedb/crd-manager)

### [v0.21.0-rc.0](https://github.com/kubedb/crd-manager/releases/tag/v0.21.0-rc.0)

- [6ba7e0f6](https://github.com/kubedb/crd-manager/commit/6ba7e0f6) Prepare for release v0.21.0-rc.0 (#149)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.21.0-rc.0](https://github.com/kubedb/db-client-go/releases/tag/v0.21.0-rc.0)

- [7c17ffc1](https://github.com/kubedb/db-client-go/commit/7c17ffc1) Prepare for release v0.21.0-rc.0 (#259)
- [592d1ff9](https://github.com/kubedb/db-client-go/commit/592d1ff9) Update Solr Client (#256)
- [a5525a6e](https://github.com/kubedb/db-client-go/commit/a5525a6e) lower connect log visibility by changing klog V(3) to V(4) (#258)
- [55c58b66](https://github.com/kubedb/db-client-go/commit/55c58b66) Fix DNS issue for down scaling (#257)



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



## [kubedb/percona-xtradb-coordinator](https://github.com/kubedb/percona-xtradb-coordinator)

### [v0.39.0-rc.0](https://github.com/kubedb/percona-xtradb-coordinator/releases/tag/v0.39.0-rc.0)

- [62a3b59d](https://github.com/kubedb/percona-xtradb-coordinator/commit/62a3b59d) Prepare for release v0.39.0-rc.0 (#134)



## [kubedb/singlestore-restic-plugin](https://github.com/kubedb/singlestore-restic-plugin)

### [v0.24.0-rc.0](https://github.com/kubedb/singlestore-restic-plugin/releases/tag/v0.24.0-rc.0)

- [0e259058](https://github.com/kubedb/singlestore-restic-plugin/commit/0e259058) Prepare for release v0.24.0-rc.0 (#94)
- [67f1a95e](https://github.com/kubedb/singlestore-restic-plugin/commit/67f1a95e) Fix --ssl-ca being silently dropped from the client command (#93)
- [f50bc94f](https://github.com/kubedb/singlestore-restic-plugin/commit/f50bc94f) Add Virtual Secret Support (#90)
- [1fe1b17d](https://github.com/kubedb/singlestore-restic-plugin/commit/1fe1b17d) Merge pull request #92 from kubedb/v2026.7.10-master



