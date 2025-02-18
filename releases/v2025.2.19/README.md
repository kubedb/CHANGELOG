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



## [kubedb/cli](https://github.com/kubedb/cli)

### [v0.52.0](https://github.com/kubedb/cli/releases/tag/v0.52.0)

- [9b59b8bc](https://github.com/kubedb/cli/commit/9b59b8bc) Prepare for release v0.52.0 (#791)
- [71231655](https://github.com/kubedb/cli/commit/71231655) Use Go 1.24 (#790)
- [6682c895](https://github.com/kubedb/cli/commit/6682c895) Prepare for release v0.52.0-rc.0 (#789)
- [ae68ef49](https://github.com/kubedb/cli/commit/ae68ef49) Disable image caching in setup-qemu action (#788)



## [kubedb/clickhouse](https://github.com/kubedb/clickhouse)

### [v0.7.0](https://github.com/kubedb/clickhouse/releases/tag/v0.7.0)

- [d05435b4](https://github.com/kubedb/clickhouse/commit/d05435b4) Prepare for release v0.7.0 (#38)
- [e58da497](https://github.com/kubedb/clickhouse/commit/e58da497) Test against k8s 1.32 (#37)
- [add88aa4](https://github.com/kubedb/clickhouse/commit/add88aa4) Use Go 1.24 (#36)
- [11003b23](https://github.com/kubedb/clickhouse/commit/11003b23) Report namespace info with billing event (#35)
- [5f69479d](https://github.com/kubedb/clickhouse/commit/5f69479d) Show the reason for not satifying license restriction (#34)
- [3d058bb1](https://github.com/kubedb/clickhouse/commit/3d058bb1) Add license restriction (#33)
- [14822270](https://github.com/kubedb/clickhouse/commit/14822270) Fix lister creation for client billing
- [4ead52f5](https://github.com/kubedb/clickhouse/commit/4ead52f5) Prepare for release v0.7.0-rc.0 (#31)
- [62144b2f](https://github.com/kubedb/clickhouse/commit/62144b2f) Disable image caching in setup-qemu action (#32)
- [60c715bf](https://github.com/kubedb/clickhouse/commit/60c715bf) Add client billing event support (#30)



## [kubedb/crd-manager](https://github.com/kubedb/crd-manager)

### [v0.7.0](https://github.com/kubedb/crd-manager/releases/tag/v0.7.0)

- [665eda53](https://github.com/kubedb/crd-manager/commit/665eda53) Prepare for release v0.7.0 (#66)
- [66947bf4](https://github.com/kubedb/crd-manager/commit/66947bf4) Use Go 1.24 (#65)
- [b31b8762](https://github.com/kubedb/crd-manager/commit/b31b8762) Delete only the self-CRDs for depandants (#64)
- [14ffaaf3](https://github.com/kubedb/crd-manager/commit/14ffaaf3) Implement safe-deletion for CRDs (#63)
- [39b99af6](https://github.com/kubedb/crd-manager/commit/39b99af6) Disable image caching in setup-qemu action (#62)
- [07576a67](https://github.com/kubedb/crd-manager/commit/07576a67) Prepare for release v0.7.0-rc.0 (#61)



## [kubedb/dashboard-restic-plugin](https://github.com/kubedb/dashboard-restic-plugin)

### [v0.10.0](https://github.com/kubedb/dashboard-restic-plugin/releases/tag/v0.10.0)

- [cff8f60](https://github.com/kubedb/dashboard-restic-plugin/commit/cff8f60) Prepare for release v0.10.0 (#34)
- [d357bdc](https://github.com/kubedb/dashboard-restic-plugin/commit/d357bdc) Use Go 1.24 (#33)
- [3c2aa0a](https://github.com/kubedb/dashboard-restic-plugin/commit/3c2aa0a) Prepare for release v0.10.0-rc.0 (#32)
- [3a34720](https://github.com/kubedb/dashboard-restic-plugin/commit/3a34720) Disable image caching in setup-qemu action (#31)
- [f189381](https://github.com/kubedb/dashboard-restic-plugin/commit/f189381) Incorporate with go-sh leaf command execution (#29)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.7.0](https://github.com/kubedb/db-client-go/releases/tag/v0.7.0)

- [b3fa7654](https://github.com/kubedb/db-client-go/commit/b3fa7654) Prepare for release v0.7.0 (#163)
- [993a561c](https://github.com/kubedb/db-client-go/commit/993a561c) Add method to get shard information for ES (#160)
- [3fa565a9](https://github.com/kubedb/db-client-go/commit/3fa565a9) Use Go 1.24 (#162)
- [7deb14c1](https://github.com/kubedb/db-client-go/commit/7deb14c1) Prepare for release v0.7.0-rc.0 (#161)
- [4790577b](https://github.com/kubedb/db-client-go/commit/4790577b) cert remove from pgbouncer (#158)



## [kubedb/elasticsearch](https://github.com/kubedb/elasticsearch)

### [v0.52.0](https://github.com/kubedb/elasticsearch/releases/tag/v0.52.0)

- [01aa7b63](https://github.com/kubedb/elasticsearch/commit/01aa7b63f) Prepare for release v0.52.0 (#756)
- [0ce1d5a2](https://github.com/kubedb/elasticsearch/commit/0ce1d5a23) Test against k8s 1.32 (#755)
- [a5a3c257](https://github.com/kubedb/elasticsearch/commit/a5a3c2576) Use Go 1.24 (#754)
- [2600d5bd](https://github.com/kubedb/elasticsearch/commit/2600d5bd5) Report namespace info with billing event (#753)
- [19980821](https://github.com/kubedb/elasticsearch/commit/19980821a) Update license restriction log (#752)
- [19ea3a94](https://github.com/kubedb/elasticsearch/commit/19ea3a942) Use testrig
- [a60b0c13](https://github.com/kubedb/elasticsearch/commit/a60b0c134) Update reconcile method (#751)
- [7be7d728](https://github.com/kubedb/elasticsearch/commit/7be7d7282) Prepare for release v0.52.0-rc.0 (#749)
- [953e8b52](https://github.com/kubedb/elasticsearch/commit/953e8b529) Add restriction for client billing (#750)
- [c22f6099](https://github.com/kubedb/elasticsearch/commit/c22f60990) Disable image caching in setup-qemu action (#748)
- [39d72828](https://github.com/kubedb/elasticsearch/commit/39d728289) Add client billing event support (#747)



## [kubedb/elasticsearch-restic-plugin](https://github.com/kubedb/elasticsearch-restic-plugin)

### [v0.15.0](https://github.com/kubedb/elasticsearch-restic-plugin/releases/tag/v0.15.0)

- [dd7dd4b8](https://github.com/kubedb/elasticsearch-restic-plugin/commit/dd7dd4b8) Prepare for release v0.15.0 (#59)
- [9e05f686](https://github.com/kubedb/elasticsearch-restic-plugin/commit/9e05f686) Use Go 1.24 (#58)
- [bbdc55c7](https://github.com/kubedb/elasticsearch-restic-plugin/commit/bbdc55c7) Disable image caching in setup-qemu action (#57)
- [6a087679](https://github.com/kubedb/elasticsearch-restic-plugin/commit/6a087679) Prepare for release v0.15.0-rc.0 (#56)
- [e06c0877](https://github.com/kubedb/elasticsearch-restic-plugin/commit/e06c0877) Add Stdin Backup Leaf Command Support (#54)



## [kubedb/kubedb-manifest-plugin](https://github.com/kubedb/kubedb-manifest-plugin)

### [v0.15.0](https://github.com/kubedb/kubedb-manifest-plugin/releases/tag/v0.15.0)

- [01b12a7](https://github.com/kubedb/kubedb-manifest-plugin/commit/01b12a7) Prepare for release v0.15.0 (#90)
- [891e1ea](https://github.com/kubedb/kubedb-manifest-plugin/commit/891e1ea) Use Go 1.24 (#89)
- [f85c4ee](https://github.com/kubedb/kubedb-manifest-plugin/commit/f85c4ee) Prepare for release v0.15.0-rc.0 (#88)
- [155aea8](https://github.com/kubedb/kubedb-manifest-plugin/commit/155aea8) Disable image caching in setup-qemu action (#87)
- [1c168b9](https://github.com/kubedb/kubedb-manifest-plugin/commit/1c168b9) Archiver and InitScript support added for backup and restore (#84)
- [e64809f](https://github.com/kubedb/kubedb-manifest-plugin/commit/e64809f) Incorporate with `go-sh` leaf command execution (#85)



## [kubedb/kubedb-verifier](https://github.com/kubedb/kubedb-verifier)

### [v0.3.0](https://github.com/kubedb/kubedb-verifier/releases/tag/v0.3.0)

- [1033b54](https://github.com/kubedb/kubedb-verifier/commit/1033b54) Prepare for release v0.3.0 (#14)
- [7a08962](https://github.com/kubedb/kubedb-verifier/commit/7a08962) Use Go 1.24 (#13)
- [1e55a38](https://github.com/kubedb/kubedb-verifier/commit/1e55a38) Disable image caching in setup-qemu action (#12)
- [3648382](https://github.com/kubedb/kubedb-verifier/commit/3648382) Prepare for release v0.3.0-rc.0 (#11)



## [kubedb/mariadb](https://github.com/kubedb/mariadb)

### [v0.36.0](https://github.com/kubedb/mariadb/releases/tag/v0.36.0)

- [5aae329e](https://github.com/kubedb/mariadb/commit/5aae329ea) Prepare for release v0.36.0 (#314)
- [2102f599](https://github.com/kubedb/mariadb/commit/2102f5992) Test against k8s 1.32 (#313)
- [c48e29b6](https://github.com/kubedb/mariadb/commit/c48e29b67) Use Go 1.24 (#312)
- [c2df3bc9](https://github.com/kubedb/mariadb/commit/c2df3bc9b) Report namespace info with billing event (#311)
- [d72a123c](https://github.com/kubedb/mariadb/commit/d72a123ca) Show the reason for not satifying license restriction (#310)
- [d586b568](https://github.com/kubedb/mariadb/commit/d586b5689) Use testrig
- [b4aa7696](https://github.com/kubedb/mariadb/commit/b4aa76961) Prepare for release v0.36.0-rc.0 (#308)
- [35f8872b](https://github.com/kubedb/mariadb/commit/35f8872bb) Disable image caching in setup-qemu action (#309)
- [1ae948a1](https://github.com/kubedb/mariadb/commit/1ae948a15) Add client billing event support (#306)
- [163d01c1](https://github.com/kubedb/mariadb/commit/163d01c11) Added archiver and init-script manifest restore support (#305)
- [c32d1af6](https://github.com/kubedb/mariadb/commit/c32d1af68) Fix AuthSecret Check (#296)



## [kubedb/mariadb-coordinator](https://github.com/kubedb/mariadb-coordinator)

### [v0.32.0](https://github.com/kubedb/mariadb-coordinator/releases/tag/v0.32.0)

- [24eeb621](https://github.com/kubedb/mariadb-coordinator/commit/24eeb621) Prepare for release v0.32.0 (#139)
- [a8c8f873](https://github.com/kubedb/mariadb-coordinator/commit/a8c8f873) Use Go 1.24 (#138)
- [ff0a938a](https://github.com/kubedb/mariadb-coordinator/commit/ff0a938a) Prepare for release v0.32.0-rc.0 (#137)
- [efb48fb1](https://github.com/kubedb/mariadb-coordinator/commit/efb48fb1) Disable image caching in setup-qemu action (#136)



## [kubedb/memcached](https://github.com/kubedb/memcached)

### [v0.45.0](https://github.com/kubedb/memcached/releases/tag/v0.45.0)

- [d0bf662b](https://github.com/kubedb/memcached/commit/d0bf662b4) Prepare for release v0.45.0 (#489)
- [dc8343bc](https://github.com/kubedb/memcached/commit/dc8343bce) Test against k8s 1.32 (#488)
- [27399464](https://github.com/kubedb/memcached/commit/273994640) Use Go 1.24 (#487)
- [5757ac2c](https://github.com/kubedb/memcached/commit/5757ac2ca) Report namespace info with billing event (#486)
- [ae26c91e](https://github.com/kubedb/memcached/commit/ae26c91e7) Run e2e Tests on testrig & show the reason for not satisfying license restriction (#485)
- [761e9c14](https://github.com/kubedb/memcached/commit/761e9c145) Fix License Restriction Checking (#484)
- [1d14d49c](https://github.com/kubedb/memcached/commit/1d14d49c6) Prepare for release v0.45.0-rc.0 (#482)
- [1d3054df](https://github.com/kubedb/memcached/commit/1d3054dfa) Disable image caching in setup-qemu action (#483)
- [90fd0801](https://github.com/kubedb/memcached/commit/90fd08014) Add client billing event support (#480)
- [2e569244](https://github.com/kubedb/memcached/commit/2e5692449) Fix memcached config secret issue (#479)



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



## [kubedb/mongodb-restic-plugin](https://github.com/kubedb/mongodb-restic-plugin)

### [v0.15.0](https://github.com/kubedb/mongodb-restic-plugin/releases/tag/v0.15.0)

- [9afda5c](https://github.com/kubedb/mongodb-restic-plugin/commit/9afda5c) Prepare for release v0.15.0 (#80)
- [6f5b57b](https://github.com/kubedb/mongodb-restic-plugin/commit/6f5b57b) Use Go 1.24 (#79)
- [c06b10a](https://github.com/kubedb/mongodb-restic-plugin/commit/c06b10a) Prepare for release v0.15.0-rc.0 (#78)
- [c1892f4](https://github.com/kubedb/mongodb-restic-plugin/commit/c1892f4) Disable image caching in setup-qemu action (#77)
- [c37543b](https://github.com/kubedb/mongodb-restic-plugin/commit/c37543b) Add Stdin Backup Leaf Command support (#75)



## [kubedb/mssql-coordinator](https://github.com/kubedb/mssql-coordinator)

### [v0.7.0](https://github.com/kubedb/mssql-coordinator/releases/tag/v0.7.0)

- [1d9c6500](https://github.com/kubedb/mssql-coordinator/commit/1d9c6500) Prepare for release v0.7.0 (#31)
- [374ddac6](https://github.com/kubedb/mssql-coordinator/commit/374ddac6) Use Go 1.24 (#30)
- [f5dd10a7](https://github.com/kubedb/mssql-coordinator/commit/f5dd10a7) Prepare for release v0.7.0-rc.0 (#29)
- [c570b028](https://github.com/kubedb/mssql-coordinator/commit/c570b028) Disable image caching in setup-qemu action (#28)
- [e285bb2c](https://github.com/kubedb/mssql-coordinator/commit/e285bb2c) Add Arbiter node support (#24)



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



## [kubedb/mysql-archiver](https://github.com/kubedb/mysql-archiver)

### [v0.13.0](https://github.com/kubedb/mysql-archiver/releases/tag/v0.13.0)

- [39107a7b](https://github.com/kubedb/mysql-archiver/commit/39107a7b) Prepare for release v0.13.0 (#55)
- [ef00cd3b](https://github.com/kubedb/mysql-archiver/commit/ef00cd3b) Use Go 1.24 (#54)
- [11c6e83c](https://github.com/kubedb/mysql-archiver/commit/11c6e83c) Prepare for release v0.13.0-rc.0 (#52)
- [364b3500](https://github.com/kubedb/mysql-archiver/commit/364b3500) Disable image caching in setup-qemu action (#53)
- [f7833baf](https://github.com/kubedb/mysql-archiver/commit/f7833baf) Update Inc Snapshot status (#49)



## [kubedb/mysql-coordinator](https://github.com/kubedb/mysql-coordinator)

### [v0.30.0](https://github.com/kubedb/mysql-coordinator/releases/tag/v0.30.0)

- [f00b8511](https://github.com/kubedb/mysql-coordinator/commit/f00b8511) Prepare for release v0.30.0 (#136)
- [1611bdf9](https://github.com/kubedb/mysql-coordinator/commit/1611bdf9) Use Go 1.24 (#135)
- [40e90068](https://github.com/kubedb/mysql-coordinator/commit/40e90068) Prepare for release v0.30.0-rc.0 (#133)
- [6b61ec27](https://github.com/kubedb/mysql-coordinator/commit/6b61ec27) Disable image caching in setup-qemu action (#134)



## [kubedb/mysql-csi-snapshotter-plugin](https://github.com/kubedb/mysql-csi-snapshotter-plugin)

### [v0.13.0](https://github.com/kubedb/mysql-csi-snapshotter-plugin/releases/tag/v0.13.0)

- [1511498](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/1511498) Prepare for release v0.13.0 (#43)
- [d1c7f1b](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/d1c7f1b) Use Go 1.24 (#42)
- [33f6918](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/33f6918) Prepare for release v0.13.0-rc.0 (#40)
- [9f91792](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/9f91792) Disable image caching in setup-qemu action (#41)



## [kubedb/mysql-restic-plugin](https://github.com/kubedb/mysql-restic-plugin)

### [v0.15.0](https://github.com/kubedb/mysql-restic-plugin/releases/tag/v0.15.0)

- [a19fa28](https://github.com/kubedb/mysql-restic-plugin/commit/a19fa28) Prepare for release v0.15.0 (#70)
- [78dcba1](https://github.com/kubedb/mysql-restic-plugin/commit/78dcba1) Use Go 1.24 (#69)
- [8acee3b](https://github.com/kubedb/mysql-restic-plugin/commit/8acee3b) Prepare for release v0.15.0-rc.0 (#67)
- [b2144fb](https://github.com/kubedb/mysql-restic-plugin/commit/b2144fb) Disable image caching in setup-qemu action (#68)
- [6830436](https://github.com/kubedb/mysql-restic-plugin/commit/6830436) Add Stdin Backup Leaf Command support (#61)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.30.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.30.0)

- [a41de94](https://github.com/kubedb/mysql-router-init/commit/a41de94) Use Go 1.24 (#51)
- [0ba8326](https://github.com/kubedb/mysql-router-init/commit/0ba8326) Disable image caching in setup-qemu action (#50)



## [kubedb/percona-xtradb-coordinator](https://github.com/kubedb/percona-xtradb-coordinator)

### [v0.25.0](https://github.com/kubedb/percona-xtradb-coordinator/releases/tag/v0.25.0)

- [5dfc6dd5](https://github.com/kubedb/percona-xtradb-coordinator/commit/5dfc6dd5) Prepare for release v0.25.0 (#92)
- [52e1530a](https://github.com/kubedb/percona-xtradb-coordinator/commit/52e1530a) Use Go 1.24 (#91)
- [3e09a9ad](https://github.com/kubedb/percona-xtradb-coordinator/commit/3e09a9ad) Prepare for release v0.25.0-rc.0 (#89)
- [4013787c](https://github.com/kubedb/percona-xtradb-coordinator/commit/4013787c) Disable image caching in setup-qemu action (#90)



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



## [kubedb/postgres-archiver](https://github.com/kubedb/postgres-archiver)

### [v0.13.0](https://github.com/kubedb/postgres-archiver/releases/tag/v0.13.0)

- [c40544c2](https://github.com/kubedb/postgres-archiver/commit/c40544c2) Prepare for release v0.13.0 (#57)
- [4cc8a8e7](https://github.com/kubedb/postgres-archiver/commit/4cc8a8e7) Use Go 1.24 (#56)
- [b7bee766](https://github.com/kubedb/postgres-archiver/commit/b7bee766) Prepare for release v0.13.0-rc.0 (#55)
- [7b34eeba](https://github.com/kubedb/postgres-archiver/commit/7b34eeba) Disable image caching in setup-qemu action (#54)
- [47ea5469](https://github.com/kubedb/postgres-archiver/commit/47ea5469) Update Logstats, update wal archive support for standby (#52)



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




## [kubedb/redis-coordinator](https://github.com/kubedb/redis-coordinator)

### [v0.31.0](https://github.com/kubedb/redis-coordinator/releases/tag/v0.31.0)

- [ad30d0f4](https://github.com/kubedb/redis-coordinator/commit/ad30d0f4) Prepare for release v0.31.0 (#123)
- [ba9e3036](https://github.com/kubedb/redis-coordinator/commit/ba9e3036) Use Go 1.24 (#122)
- [e56c4c25](https://github.com/kubedb/redis-coordinator/commit/e56c4c25) Prepare for release v0.31.0-rc.0 (#121)
- [2539e4b4](https://github.com/kubedb/redis-coordinator/commit/2539e4b4) Disable image caching in setup-qemu action (#120)



## [kubedb/redis-restic-plugin](https://github.com/kubedb/redis-restic-plugin)

### [v0.15.0](https://github.com/kubedb/redis-restic-plugin/releases/tag/v0.15.0)

- [84059cf](https://github.com/kubedb/redis-restic-plugin/commit/84059cf) Prepare for release v0.15.0 (#62)
- [1ef930f](https://github.com/kubedb/redis-restic-plugin/commit/1ef930f) Use Go 1.24 (#61)
- [cd65bb3](https://github.com/kubedb/redis-restic-plugin/commit/cd65bb3) Prepare for release v0.15.0-rc.0 (#60)
- [a1e6dfa](https://github.com/kubedb/redis-restic-plugin/commit/a1e6dfa) Disable image caching in setup-qemu action (#59)
- [7cacd68](https://github.com/kubedb/redis-restic-plugin/commit/7cacd68) Add Stdin Backup Leaf Command support (#57)



## [kubedb/replication-mode-detector](https://github.com/kubedb/replication-mode-detector)

### [v0.39.0](https://github.com/kubedb/replication-mode-detector/releases/tag/v0.39.0)

- [feb3420a](https://github.com/kubedb/replication-mode-detector/commit/feb3420a) Prepare for release v0.39.0 (#289)
- [b42c020d](https://github.com/kubedb/replication-mode-detector/commit/b42c020d) Use Go 1.24 (#288)
- [43e19c32](https://github.com/kubedb/replication-mode-detector/commit/43e19c32) Prepare for release v0.39.0-rc.0 (#286)
- [fce9f58c](https://github.com/kubedb/replication-mode-detector/commit/fce9f58c) Disable image caching in setup-qemu action (#287)



## [kubedb/singlestore](https://github.com/kubedb/singlestore)

### [v0.7.0](https://github.com/kubedb/singlestore/releases/tag/v0.7.0)

- [2781fd58](https://github.com/kubedb/singlestore/commit/2781fd58) Prepare for release v0.7.0 (#63)
- [e7c24277](https://github.com/kubedb/singlestore/commit/e7c24277) Test against k8s 1.32 (#62)
- [a043af3d](https://github.com/kubedb/singlestore/commit/a043af3d) Use Go 1.24 (#61)
- [d3c90016](https://github.com/kubedb/singlestore/commit/d3c90016) Report namespace info with billing event (#60)
- [25728a9e](https://github.com/kubedb/singlestore/commit/25728a9e) Update license log & e2e machine
- [cf355d20](https://github.com/kubedb/singlestore/commit/cf355d20) fix license restriction checking (#59)
- [c22e7c86](https://github.com/kubedb/singlestore/commit/c22e7c86) Prepare for release v0.7.0-rc.0 (#58)
- [ebb993be](https://github.com/kubedb/singlestore/commit/ebb993be) Disable image caching in setup-qemu action (#57)



## [kubedb/singlestore-coordinator](https://github.com/kubedb/singlestore-coordinator)

### [v0.7.0](https://github.com/kubedb/singlestore-coordinator/releases/tag/v0.7.0)

- [3383f6e](https://github.com/kubedb/singlestore-coordinator/commit/3383f6e) Prepare for release v0.7.0 (#38)
- [3fe4c70](https://github.com/kubedb/singlestore-coordinator/commit/3fe4c70) Use Go 1.24 (#37)
- [3ab10f5](https://github.com/kubedb/singlestore-coordinator/commit/3ab10f5) Prepare for release v0.7.0-rc.0 (#36)
- [f7271dd](https://github.com/kubedb/singlestore-coordinator/commit/f7271dd) Disable image caching in setup-qemu action (#35)



## [kubedb/singlestore-restic-plugin](https://github.com/kubedb/singlestore-restic-plugin)

### [v0.10.0](https://github.com/kubedb/singlestore-restic-plugin/releases/tag/v0.10.0)

- [b3b6b4b](https://github.com/kubedb/singlestore-restic-plugin/commit/b3b6b4b) Prepare for release v0.10.0 (#38)
- [4cc4d3d](https://github.com/kubedb/singlestore-restic-plugin/commit/4cc4d3d) Use Go 1.24 (#37)
- [1b36229](https://github.com/kubedb/singlestore-restic-plugin/commit/1b36229) Prepare for release v0.10.0-rc.0 (#36)
- [4c9a228](https://github.com/kubedb/singlestore-restic-plugin/commit/4c9a228) Disable image caching in setup-qemu action (#35)
- [98dfeae](https://github.com/kubedb/singlestore-restic-plugin/commit/98dfeae) Add Stdin Backup Leaf Command support (#33)



## [kubedb/zookeeper](https://github.com/kubedb/zookeeper)

### [v0.7.0](https://github.com/kubedb/zookeeper/releases/tag/v0.7.0)

- [a3a96c3b](https://github.com/kubedb/zookeeper/commit/a3a96c3b) Prepare for release v0.7.0 (#64)
- [432282ec](https://github.com/kubedb/zookeeper/commit/432282ec) Test against k8s 1.32 (#63)
- [575e88a7](https://github.com/kubedb/zookeeper/commit/575e88a7) Use Go 1.24 (#62)
- [0a05aa4a](https://github.com/kubedb/zookeeper/commit/0a05aa4a) Report namespace info with billing event (#61)
- [0c0110cf](https://github.com/kubedb/zookeeper/commit/0c0110cf) Show the reason for not satifying license restriction (#60)
- [96dc0790](https://github.com/kubedb/zookeeper/commit/96dc0790) Add license restriction (#59)
- [ace3a6dd](https://github.com/kubedb/zookeeper/commit/ace3a6dd) Prepare for release v0.7.0-rc.0 (#57)
- [89699f8d](https://github.com/kubedb/zookeeper/commit/89699f8d) Disable image caching in setup-qemu action (#56)
- [9a81250c](https://github.com/kubedb/zookeeper/commit/9a81250c) Add client billing event support (#55)



## [kubedb/zookeeper-restic-plugin](https://github.com/kubedb/zookeeper-restic-plugin)

### [v0.8.0](https://github.com/kubedb/zookeeper-restic-plugin/releases/tag/v0.8.0)

- [e9459f4](https://github.com/kubedb/zookeeper-restic-plugin/commit/e9459f4) Prepare for release v0.8.0 (#30)
- [739367c](https://github.com/kubedb/zookeeper-restic-plugin/commit/739367c) Use Go 1.24 (#29)
- [52085d1](https://github.com/kubedb/zookeeper-restic-plugin/commit/52085d1) Prepare for release v0.8.0-rc.0 (#27)
- [7323969](https://github.com/kubedb/zookeeper-restic-plugin/commit/7323969) Disable image caching in setup-qemu action (#28)
- [096f163](https://github.com/kubedb/zookeeper-restic-plugin/commit/096f163) Add Stdin Backup Leaf Command support (#25)



