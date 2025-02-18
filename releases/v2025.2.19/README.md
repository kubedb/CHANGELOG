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



## [kubedb/postgres-csi-snapshotter-plugin](https://github.com/kubedb/postgres-csi-snapshotter-plugin)

### [v0.13.0](https://github.com/kubedb/postgres-csi-snapshotter-plugin/releases/tag/v0.13.0)

- [63ba8c9](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/63ba8c9) Prepare for release v0.13.0 (#53)
- [c4b928f](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/c4b928f) Use Go 1.24 (#52)
- [bbe21c0](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/bbe21c0) Prepare for release v0.13.0-rc.0 (#51)
- [f088e55](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/f088e55) Disable image caching in setup-qemu action (#50)
- [3db1026](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/3db1026) Update volumeSnapshotTime when volumeSnapshot is ready to use and add support for standalone volume snapshot (#43)



