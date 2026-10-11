# KubeDB v2026.10.12 (2026-10-11)


## [kubedb/aerospike](https://github.com/kubedb/aerospike)

### [v0.4.0](https://github.com/kubedb/aerospike/releases/tag/v0.4.0)

- [ffc3ab0d](https://github.com/kubedb/aerospike/commit/ffc3ab0d) Prepare for release v0.4.0 (#19)
- [9e951762](https://github.com/kubedb/aerospike/commit/9e951762) Use Go 1.27, k8s 1.37 & debian:13 (#18)
- [e9297592](https://github.com/kubedb/aerospike/commit/e9297592) Sync status.observedGeneration with metadata.generation on spec-only changes
- [29c6f649](https://github.com/kubedb/aerospike/commit/29c6f649) Update apimachinery (#17)
- [c834559b](https://github.com/kubedb/aerospike/commit/c834559b) Add network policy support with flavor selection (#16)
- [442d7867](https://github.com/kubedb/aerospike/commit/442d7867) Prepare for release v0.3.0-rc.2 (#15)
- [580212ae](https://github.com/kubedb/aerospike/commit/580212ae) Prepare for release v0.3.0-rc.1 (#14)
- [bd299458](https://github.com/kubedb/aerospike/commit/bd299458) Prepare for release v0.3.0-rc.0 (#13)
- [45481d49](https://github.com/kubedb/aerospike/commit/45481d49) Prepare for release v0.2.0-rc.0 (#12)
- [81fe47b5](https://github.com/kubedb/aerospike/commit/81fe47b5) Config merging (#11)
- [1c54e254](https://github.com/kubedb/aerospike/commit/1c54e254) Use shared appbinding helper and record event (#10)
- [22a19d44](https://github.com/kubedb/aerospike/commit/22a19d44) Add appbinding (#9)
- [408f2a83](https://github.com/kubedb/aerospike/commit/408f2a83) Fix Health check (#4)
- [1c47f5b1](https://github.com/kubedb/aerospike/commit/1c47f5b1) Move deletion logic to apimachinery (#8)
- [615dd307](https://github.com/kubedb/aerospike/commit/615dd307) Upgrade aerospike-client-go v6 -> v8 (#7)



## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.68.0](https://github.com/kubedb/apimachinery/releases/tag/v0.68.0)

- [936bc89c](https://github.com/kubedb/apimachinery/commit/936bc89c6) Update for release KubeStash@v2026.10.12 (#1926)
- [3f36c9ed](https://github.com/kubedb/apimachinery/commit/3f36c9ed7) Use Go 1.27, k8s 1.37 & debian:13 (#1925)
- [31f11301](https://github.com/kubedb/apimachinery/commit/31f11301d) Cleanup cves (#1924)
- [a060f480](https://github.com/kubedb/apimachinery/commit/a060f480f) make gen fmt
- [2fd5929c](https://github.com/kubedb/apimachinery/commit/2fd5929ce) Add per-CR Elasticsearch license activation support (#1912)
- [7c077193](https://github.com/kubedb/apimachinery/commit/7c0771936) Add db2 clustering & failover (#1917)
- [7d546f71](https://github.com/kubedb/apimachinery/commit/7d546f715) Add milvus basebackup and pitr (#1921)
- [39fb7184](https://github.com/kubedb/apimachinery/commit/39fb7184b) Add DefaultExporterResource (#1905)
- [d59357f7](https://github.com/kubedb/apimachinery/commit/d59357f74) documentdb base backup restore (#1906)
- [985ca990](https://github.com/kubedb/apimachinery/commit/985ca9902) Add Clickhouse PVC UID in Status (#1916)
- [5e3e2658](https://github.com/kubedb/apimachinery/commit/5e3e2658c) Classify reconfigure parameters as read-only, static or dynamic (#1909)
- [8a6bc178](https://github.com/kubedb/apimachinery/commit/8a6bc178d) grpc: add the Postgres CoordinatorManager API (#1879)
- [985699ba](https://github.com/kubedb/apimachinery/commit/985699ba7) Allow all KubeDB operator pods in Cilium healthcheck policy (#1923)
- [8558d60f](https://github.com/kubedb/apimachinery/commit/8558d60f1) Add AWS Aurora backend support to ProxySQL API (#1919)
- [b10f230e](https://github.com/kubedb/apimachinery/commit/b10f230ed) Warn on unsupported serviceTemplate aliases for Etcd (#1922)
- [2845df09](https://github.com/kubedb/apimachinery/commit/2845df094) Add shared ApplyServiceTemplate helper and serviceTemplate alias warnings (#1920)
- [8cea1803](https://github.com/kubedb/apimachinery/commit/8cea18036) Use et as etcd short code (#1918)
- [f04a6aad](https://github.com/kubedb/apimachinery/commit/f04a6aad0) Use standby svc alias everywhere; rr -> readreplica (#1904)
- [8e755745](https://github.com/kubedb/apimachinery/commit/8e755745d) Update audit package
- [bb1f2c70](https://github.com/kubedb/apimachinery/commit/bb1f2c702) Milvus: GPU support (Standalone + Distributed) and SR-IOV network field (#1898)
- [aed09b97](https://github.com/kubedb/apimachinery/commit/aed09b970) Fix oracle version validation (#1850)
- [d495a98c](https://github.com/kubedb/apimachinery/commit/d495a98c7) Redis Webhook fix (#1903)
- [95261874](https://github.com/kubedb/apimachinery/commit/952618743) docuomentdb base & logical backup (#1884)
- [9fb6af3d](https://github.com/kubedb/apimachinery/commit/9fb6af3db) Milvus: support TLS, password auth and encrypted storage for self-managed meta etcd (#1897)
- [bdfdbbc3](https://github.com/kubedb/apimachinery/commit/bdfdbbc35) Add Neo4j Archiver Api (#1806)
- [9694e2f8](https://github.com/kubedb/apimachinery/commit/9694e2f86) Add status.disasterRecovery to Postgres for cross-DC DR (#1858)
- [3c342fac](https://github.com/kubedb/apimachinery/commit/3c342fac2) db2,documentdb,cassandra,ui-server (#1901)
- [86f34c41](https://github.com/kubedb/apimachinery/commit/86f34c418) Add Solr Backup Credential Validation (#1902)
- [5c58b9ab](https://github.com/kubedb/apimachinery/commit/5c58b9ab3) Pin etcd server/pkg to v3.5.27 to fix raft build break (#1900)
- [4a577037](https://github.com/kubedb/apimachinery/commit/4a5770373) Reject a database create when another kubedb database in the namespace already has that name (#1894)
- [cd9e62f3](https://github.com/kubedb/apimachinery/commit/cd9e62f38) milvus ui server (#1896)
- [1260e1cf](https://github.com/kubedb/apimachinery/commit/1260e1cf9) Add Druid UI-Server Api (#1890)
- [e523ac4c](https://github.com/kubedb/apimachinery/commit/e523ac4c0) Singlestore ui-server api (#1888)
- [5fdf9eff](https://github.com/kubedb/apimachinery/commit/5fdf9eff2) PerconaXtradb ui-server api (#1887)
- [aedd4467](https://github.com/kubedb/apimachinery/commit/aedd4467f) Add Neo4jDatabase info (#1885)
- [d828306b](https://github.com/kubedb/apimachinery/commit/d828306bf) Add Neo4jBind wrapper for generic binding support (#1893)
- [65202d6b](https://github.com/kubedb/apimachinery/commit/65202d6ba) move OracleBackupWalletCreatedCondition const to apimachinery (#1859)
- [7642a350](https://github.com/kubedb/apimachinery/commit/7642a350b) add OsbwsPFilePath in const (#1895)
- [a5952a02](https://github.com/kubedb/apimachinery/commit/a5952a02b) Add Support for Multiple S3/GCS backupstorage (#1875)
- [46e4b822](https://github.com/kubedb/apimachinery/commit/46e4b8223) apis/ui/v1alpha1: restore DatabaseSummary's +genclient without ObjectMeta (#1889)
- [0fbe10cb](https://github.com/kubedb/apimachinery/commit/0fbe10cb4) apis/ui/v1alpha1: drop DatabaseSummary's metav1.ObjectMeta and +genclient (#1886)
- [ea09431b](https://github.com/kubedb/apimachinery/commit/ea09431bf) Migrate code generation to kube_codegen.sh (#1883)
- [16705ae9](https://github.com/kubedb/apimachinery/commit/16705ae9e) Feat/mssql database specific table selection (#1881)
- [f8e34443](https://github.com/kubedb/apimachinery/commit/f8e344437) Add PostgresCustomHBAFile constant for user-supplied pg_hba rules (#1869)
- [294da61f](https://github.com/kubedb/apimachinery/commit/294da61f9) Add Postgres license support for the AppsCode Enterprise distribution (#1880)
- [2f8c548f](https://github.com/kubedb/apimachinery/commit/2f8c548f0) Update ClickHouse Webhook (#1872)
- [c8efdca2](https://github.com/kubedb/apimachinery/commit/c8efdca29) Add Neo4jRemoteAliasKeystore Api (#1876)
- [c8162e96](https://github.com/kubedb/apimachinery/commit/c8162e962) Add Qdrant JWT Granular Access Control (#1878)
- [4d265c34](https://github.com/kubedb/apimachinery/commit/4d265c347) Let every MySQL topology reach its upgrade-version list (#1877)
- [b3365d4a](https://github.com/kubedb/apimachinery/commit/b3365d4a5) fixed fields for mssqlserver migration (#1874)
- [ee494fb1](https://github.com/kubedb/apimachinery/commit/ee494fb14) Add etcd database support (#1870)
- [016c41eb](https://github.com/kubedb/apimachinery/commit/016c41eb7) Support management AppBinding metadata (#1868)
- [66f5172f](https://github.com/kubedb/apimachinery/commit/66f5172fb) Use gomodules.xyz/password-generator for generated auth secret passwords (#1867)
- [4d379034](https://github.com/kubedb/apimachinery/commit/4d379034d) Add RabbitMQ connection helpers (#1861)
- [12679dc1](https://github.com/kubedb/apimachinery/commit/12679dc1c) Update virtual secrets to v0.2.0 (#1865)
- [c781d8f0](https://github.com/kubedb/apimachinery/commit/c781d8f04) Harden generated auth-secret passwords: crypto/rand + optional per-DB generator (#1863)
- [521b206a](https://github.com/kubedb/apimachinery/commit/521b206a0) Fix Neo4j ServiceMonitor Scheme (#1864)
- [fbf651ae](https://github.com/kubedb/apimachinery/commit/fbf651ae4) Skip kubedb db webhook defaulting/validation when deletionTimestamp is set (#1862)
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
- [fd1d8ae0](https://github.com/kubedb/apimachinery/commit/fd1d8ae01) Remove postgres-dependent validations from pgpool webhook
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

### [v0.23.0](https://github.com/kubedb/crd-manager/releases/tag/v0.23.0)




## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.23.0](https://github.com/kubedb/db-client-go/releases/tag/v0.23.0)

- [1fed96bf](https://github.com/kubedb/db-client-go/commit/1fed96bf) Prepare for release v0.23.0 (#271)
- [f53ad7e8](https://github.com/kubedb/db-client-go/commit/f53ad7e8) Use Go 1.27, k8s 1.37 & debian:13 (#270)
- [6e793845](https://github.com/kubedb/db-client-go/commit/6e793845) Add New Function for Composite Database (#266)
- [cfe9ea0b](https://github.com/kubedb/db-client-go/commit/cfe9ea0b) Prepare for release v0.22.0-rc.2 (#265)
- [0efc93cc](https://github.com/kubedb/db-client-go/commit/0efc93cc) Prepare for release v0.22.0-rc.1 (#264)
- [9793d3da](https://github.com/kubedb/db-client-go/commit/9793d3da) Fix ClickHouse Connection String (#262)
- [6769cb1c](https://github.com/kubedb/db-client-go/commit/6769cb1c) Neo4j Connectivity Check Against Systemdatabase (#263)
- [e048889a](https://github.com/kubedb/db-client-go/commit/e048889a) Add etcd client package (#261)
- [784f6a68](https://github.com/kubedb/db-client-go/commit/784f6a68) Prepare for release v0.22.0-rc.0 (#260)
- [7c17ffc1](https://github.com/kubedb/db-client-go/commit/7c17ffc1) Prepare for release v0.21.0-rc.0 (#259)
- [592d1ff9](https://github.com/kubedb/db-client-go/commit/592d1ff9) Update Solr Client (#256)
- [a5525a6e](https://github.com/kubedb/db-client-go/commit/a5525a6e) lower connect log visibility by changing klog V(3) to V(4) (#258)
- [55c58b66](https://github.com/kubedb/db-client-go/commit/55c58b66) Fix DNS issue for down scaling (#257)



## [kubedb/elasticsearch](https://github.com/kubedb/elasticsearch)

### [v0.68.0](https://github.com/kubedb/elasticsearch/releases/tag/v0.68.0)

- [ad2159a5](https://github.com/kubedb/elasticsearch/commit/ad2159a5b) Prepare for release v0.68.0 (#840)
- [24d22c87](https://github.com/kubedb/elasticsearch/commit/24d22c877) Use Go 1.27, k8s 1.37 & debian:13 (#839)
- [bc23a2c7](https://github.com/kubedb/elasticsearch/commit/bc23a2c79) Add Elasticsearch subscription license activation and sync (#837)
- [b1dab85b](https://github.com/kubedb/elasticsearch/commit/b1dab85b7) Add branched mode for KubeDB Courier Branch (#824)
- [b5b8ff16](https://github.com/kubedb/elasticsearch/commit/b5b8ff16f) Sync status.observedGeneration with metadata.generation on spec-only changes
- [4ae812e9](https://github.com/kubedb/elasticsearch/commit/4ae812e9e) Sync Services with spec.serviceTemplates via shared helper (#838)
- [8c06afa7](https://github.com/kubedb/elasticsearch/commit/8c06afa72) Add network policy flavor support (#836)
- [071452f9](https://github.com/kubedb/elasticsearch/commit/071452f95) Prepare for release v0.67.0-rc.2 (#835)
- [16244d23](https://github.com/kubedb/elasticsearch/commit/16244d23b) Prepare for release v0.67.0-rc.1 (#834)
- [566ae07c](https://github.com/kubedb/elasticsearch/commit/566ae07c7) Prepare for release v0.67.0-rc.0 (#833)
- [20095d87](https://github.com/kubedb/elasticsearch/commit/20095d87a) Prepare for release v0.66.0-rc.0 (#832)
- [32668c8f](https://github.com/kubedb/elasticsearch/commit/32668c8f3) Migrate auth secret handling to shared apimachinery secret package (#831)
- [ca2f2988](https://github.com/kubedb/elasticsearch/commit/ca2f2988d) Adopt shared monitor/appbinding packages from apimachinery (#830)
- [62ec1892](https://github.com/kubedb/elasticsearch/commit/62ec18929) Add virtual secret support (#813)
- [14fab5c7](https://github.com/kubedb/elasticsearch/commit/14fab5c77) Move deletion logic to apimachinery (#829)
- [50d3e6b3](https://github.com/kubedb/elasticsearch/commit/50d3e6b3e) Merge pull request #828 from kubedb/v2026.7.10-master



## [kubedb/hazelcast](https://github.com/kubedb/hazelcast)

### [v0.14.0](https://github.com/kubedb/hazelcast/releases/tag/v0.14.0)

- [19fd9477](https://github.com/kubedb/hazelcast/commit/19fd9477) Prepare for release v0.14.0 (#71)
- [4531ca4d](https://github.com/kubedb/hazelcast/commit/4531ca4d) Use Go 1.27, k8s 1.37 & debian:13 (#70)
- [70423d10](https://github.com/kubedb/hazelcast/commit/70423d10) Sync status.observedGeneration with metadata.generation on spec-only changes
- [a247d878](https://github.com/kubedb/hazelcast/commit/a247d878) Sync Services with spec.serviceTemplates via shared helper (#69)
- [a70a49bc](https://github.com/kubedb/hazelcast/commit/a70a49bc) Prepare for release v0.13.0-rc.2 (#68)
- [76480d46](https://github.com/kubedb/hazelcast/commit/76480d46) Prepare for release v0.13.0-rc.1 (#67)
- [654af89f](https://github.com/kubedb/hazelcast/commit/654af89f) Prepare for release v0.13.0-rc.0 (#66)
- [35ebce41](https://github.com/kubedb/hazelcast/commit/35ebce41) Prepare for release v0.12.0-rc.0 (#65)
- [ad3bf0c5](https://github.com/kubedb/hazelcast/commit/ad3bf0c5) Migrate auth-secret management to shared apimachinery secret package (#64)
- [e36af849](https://github.com/kubedb/hazelcast/commit/e36af849) Add virtual secret support (#47)
- [5b1409ef](https://github.com/kubedb/hazelcast/commit/5b1409ef) Add StorageMigration OpsRequest support for Hazelcast (#45)
- [a9a6cd5b](https://github.com/kubedb/hazelcast/commit/a9a6cd5b) Use shared monitor and appbinding packages (#63)
- [85d20938](https://github.com/kubedb/hazelcast/commit/85d20938) Set default resource limits before patching petset in vertical scaling
- [136b30e8](https://github.com/kubedb/hazelcast/commit/136b30e8) Move deletion logic to apimachinery (#62)



## [kubedb/mariadb-coordinator](https://github.com/kubedb/mariadb-coordinator)

### [v0.48.0](https://github.com/kubedb/mariadb-coordinator/releases/tag/v0.48.0)

- [16f1a252](https://github.com/kubedb/mariadb-coordinator/commit/16f1a252) Prepare for release v0.48.0 (#192)
- [c9e0fcc5](https://github.com/kubedb/mariadb-coordinator/commit/c9e0fcc5) Use Go 1.27, k8s 1.37 & debian:13 (#191)
- [5e21bff3](https://github.com/kubedb/mariadb-coordinator/commit/5e21bff3) Prepare for release v0.47.0-rc.2 (#190)
- [989706c7](https://github.com/kubedb/mariadb-coordinator/commit/989706c7) Prepare for release v0.47.0-rc.1 (#189)
- [4cb4c9cc](https://github.com/kubedb/mariadb-coordinator/commit/4cb4c9cc) Prepare for release v0.47.0-rc.0 (#188)
- [4772461d](https://github.com/kubedb/mariadb-coordinator/commit/4772461d) Prepare for release v0.46.0-rc.0 (#187)



## [kubedb/mssql-coordinator](https://github.com/kubedb/mssql-coordinator)

### [v0.23.0](https://github.com/kubedb/mssql-coordinator/releases/tag/v0.23.0)

- [b8c0b00e](https://github.com/kubedb/mssql-coordinator/commit/b8c0b00e) Prepare for release v0.23.0 (#86)
- [21f6a7a1](https://github.com/kubedb/mssql-coordinator/commit/21f6a7a1) Use Go 1.27, k8s 1.37 & debian:13 (#85)
- [5450a7f6](https://github.com/kubedb/mssql-coordinator/commit/5450a7f6) Fix Health Check for empty AG- #84 #84
- [e5df95bf](https://github.com/kubedb/mssql-coordinator/commit/e5df95bf) Prepare for release v0.22.0-rc.2 (#83)
- [7d190db9](https://github.com/kubedb/mssql-coordinator/commit/7d190db9) Prepare for release v0.22.0-rc.1 (#82)
- [11832898](https://github.com/kubedb/mssql-coordinator/commit/11832898) Prepare for release v0.22.0-rc.0 (#81)
- [ccd2c520](https://github.com/kubedb/mssql-coordinator/commit/ccd2c520) Prepare for release v0.21.0-rc.0 (#80)
- [872322d9](https://github.com/kubedb/mssql-coordinator/commit/872322d9) Add Virtual Secret (#77)



## [kubedb/percona-xtradb-coordinator](https://github.com/kubedb/percona-xtradb-coordinator)

### [v0.41.0](https://github.com/kubedb/percona-xtradb-coordinator/releases/tag/v0.41.0)

- [072770e4](https://github.com/kubedb/percona-xtradb-coordinator/commit/072770e4) Prepare for release v0.41.0 (#140)
- [335ed551](https://github.com/kubedb/percona-xtradb-coordinator/commit/335ed551) Prepare for release v0.41.0 (#139)
- [be5ec576](https://github.com/kubedb/percona-xtradb-coordinator/commit/be5ec576) Use Go 1.27, k8s 1.37 & debian:13 (#138)
- [aec6c642](https://github.com/kubedb/percona-xtradb-coordinator/commit/aec6c642) Prepare for release v0.40.0-rc.2 (#137)
- [4fe082df](https://github.com/kubedb/percona-xtradb-coordinator/commit/4fe082df) Prepare for release v0.40.0-rc.1 (#136)
- [1fbe6adf](https://github.com/kubedb/percona-xtradb-coordinator/commit/1fbe6adf) Prepare for release v0.40.0-rc.0 (#135)
- [62a3b59d](https://github.com/kubedb/percona-xtradb-coordinator/commit/62a3b59d) Prepare for release v0.39.0-rc.0 (#134)



## [kubedb/postgres-restic-plugin](https://github.com/kubedb/postgres-restic-plugin)

### [v0.31.0](https://github.com/kubedb/postgres-restic-plugin/releases/tag/v0.31.0)

- [a0b9aa65](https://github.com/kubedb/postgres-restic-plugin/commit/a0b9aa65) Prepare for release v0.31.0 (#132)
- [e1a46609](https://github.com/kubedb/postgres-restic-plugin/commit/e1a46609) Use Go 1.27, k8s 1.37 & debian:13 (#131)
- [314d9e84](https://github.com/kubedb/postgres-restic-plugin/commit/314d9e84) docuomentdb base-backup (#128)
- [30634501](https://github.com/kubedb/postgres-restic-plugin/commit/30634501) Guard against nil ResticStats.Summary in GetResticSnapshotID (#129)
- [36c1a6bb](https://github.com/kubedb/postgres-restic-plugin/commit/36c1a6bb) Allow backup when Postgres is in Critical phase (#127)
- [8a796277](https://github.com/kubedb/postgres-restic-plugin/commit/8a796277) Fix UBI image build failure for 17.9-percona (#126)
- [1685bd96](https://github.com/kubedb/postgres-restic-plugin/commit/1685bd96) Prepare for release v0.30.0-rc.2 (#125)
- [0837cdad](https://github.com/kubedb/postgres-restic-plugin/commit/0837cdad) Prepare for release v0.30.0-rc.1 (#124)
- [b546216f](https://github.com/kubedb/postgres-restic-plugin/commit/b546216f) Prepare for release v0.30.0-rc.0 (#123)
- [fb1c5cd1](https://github.com/kubedb/postgres-restic-plugin/commit/fb1c5cd1) Prepare for release v0.29.0-rc.0 (#122)
- [5620d3a1](https://github.com/kubedb/postgres-restic-plugin/commit/5620d3a1) Add Percona pg_tde physical backup support (17.9-percona) (#119)
- [c0ae4e7a](https://github.com/kubedb/postgres-restic-plugin/commit/c0ae4e7a) Add Virtual Secret Support (#116)



