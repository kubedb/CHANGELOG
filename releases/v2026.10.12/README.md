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



## [kubedb/cassandra](https://github.com/kubedb/cassandra)

### [v0.21.0](https://github.com/kubedb/cassandra/releases/tag/v0.21.0)

- [b480e473](https://github.com/kubedb/cassandra/commit/b480e473) Prepare for release v0.21.0 (#110)
- [b51261e2](https://github.com/kubedb/cassandra/commit/b51261e2) Use Go 1.27, k8s 1.37 & debian:13 (#109)
- [acbf46fe](https://github.com/kubedb/cassandra/commit/acbf46fe) Sync status.observedGeneration with metadata.generation on spec-only changes
- [25c0bf97](https://github.com/kubedb/cassandra/commit/25c0bf97) Sync Services with spec.serviceTemplates via shared helper (#108)
- [ed7f7fb9](https://github.com/kubedb/cassandra/commit/ed7f7fb9) Prepare for release v0.20.0-rc.2 (#107)
- [8103cfbf](https://github.com/kubedb/cassandra/commit/8103cfbf) Prepare for release v0.20.0-rc.1 (#106)
- [1f1cb82d](https://github.com/kubedb/cassandra/commit/1f1cb82d) Only watch virtual-secrets Secret when the CRD is installed (#105)
- [7638b232](https://github.com/kubedb/cassandra/commit/7638b232) Prepare for release v0.20.0-rc.0 (#104)
- [75d76a66](https://github.com/kubedb/cassandra/commit/75d76a66) Prepare for release v0.19.0-rc.0 (#103)
- [2c731155](https://github.com/kubedb/cassandra/commit/2c731155) Use shared pkg/controller/secret for auth & keystore-cred secrets (#102)
- [f57d0a7e](https://github.com/kubedb/cassandra/commit/f57d0a7e) Add virtual secret support (#83)
- [cf4a2ef4](https://github.com/kubedb/cassandra/commit/cf4a2ef4) Adopt shared monitor/appbinding packages from apimachinery (#101)
- [5b321447](https://github.com/kubedb/cassandra/commit/5b321447) Set default resource limits before patching petset in vertical scaling (#99)
- [ecb67ef2](https://github.com/kubedb/cassandra/commit/ecb67ef2) Move deletion logic to apimachinery (#100)
- [cd89e8bf](https://github.com/kubedb/cassandra/commit/cd89e8bf) Merge pull request #98 from kubedb/v2026.7.10-master



## [kubedb/cassandra-medusa-plugin](https://github.com/kubedb/cassandra-medusa-plugin)

### [v0.15.0](https://github.com/kubedb/cassandra-medusa-plugin/releases/tag/v0.15.0)

- [52ba8091](https://github.com/kubedb/cassandra-medusa-plugin/commit/52ba8091) Prepare for release v0.15.0 (#49)
- [59147c9b](https://github.com/kubedb/cassandra-medusa-plugin/commit/59147c9b) Use Go 1.27, k8s 1.37 & debian:13 (#48)
- [b3e1040f](https://github.com/kubedb/cassandra-medusa-plugin/commit/b3e1040f) Prepare for release v0.14.0-rc.2 (#47)
- [29d930ac](https://github.com/kubedb/cassandra-medusa-plugin/commit/29d930ac) Prepare for release v0.14.0-rc.1 (#46)
- [3caac86c](https://github.com/kubedb/cassandra-medusa-plugin/commit/3caac86c) Prepare for release v0.14.0-rc.0 (#45)
- [56fdcb76](https://github.com/kubedb/cassandra-medusa-plugin/commit/56fdcb76) Prepare for release v0.13.0-rc.0 (#44)



## [kubedb/cli](https://github.com/kubedb/cli)

### [v0.68.0](https://github.com/kubedb/cli/releases/tag/v0.68.0)

- [de11fae6](https://github.com/kubedb/cli/commit/de11fae6c) Prepare for release v0.68.0 (#846)
- [861102e4](https://github.com/kubedb/cli/commit/861102e41) Use Go 1.27, k8s 1.37 & debian:13 (#845)
- [a738b499](https://github.com/kubedb/cli/commit/a738b4993) Prepare for release v0.67.0-rc.2 (#842)
- [8deab935](https://github.com/kubedb/cli/commit/8deab9356) Prepare for release v0.67.0-rc.1 (#841)
- [ef5de5ad](https://github.com/kubedb/cli/commit/ef5de5ad6) Prepare for release v0.67.0-rc.0 (#840)
- [70addbc5](https://github.com/kubedb/cli/commit/70addbc5f) Prepare for release v0.66.0-rc.0 (#838)
- [0787f602](https://github.com/kubedb/cli/commit/0787f6025) Merge pull request #837 from kubedb/dcdr-cli
- [698c8c12](https://github.com/kubedb/cli/commit/698c8c12f) Merge pull request #832 from kubedb/fix/remote-config-strip-server-managed-fields
- [975c688a](https://github.com/kubedb/cli/commit/975c688a0) remote-config: issue client cert locally from a user-supplied CA
- [c8dc5838](https://github.com/kubedb/cli/commit/c8dc58389) add fix
- [da0a142b](https://github.com/kubedb/cli/commit/da0a142b2) dc-dr: satisfy errcheck and staticcheck
- [66e20969](https://github.com/kubedb/cli/commit/66e209690) remote-config: add --port / -d host:port and --replica-name
- [7fe9ed64](https://github.com/kubedb/cli/commit/7fe9ed640) Fix build: drop redeclared buffer in generateAuthSecret
- [75576974](https://github.com/kubedb/cli/commit/755769742) fix(remote-config): drop -s shorthand from --auth-secret flag
- [ddcf1e0e](https://github.com/kubedb/cli/commit/ddcf1e0e2) feat(remote-config): add -s/--auth-secret flag to override auth secret name
- [74f2e3c9](https://github.com/kubedb/cli/commit/74f2e3c9c) remove mysql changes
- [97976dbf](https://github.com/kubedb/cli/commit/97976dbfc) fix(remote-config): guard against nil Service and Secret pointers before dereference
- [8d4ff96c](https://github.com/kubedb/cli/commit/8d4ff96cc) refactor(remote-config): use DeepCopy instead of building AppBinding from scratch
- [4e401e5c](https://github.com/kubedb/cli/commit/4e401e5ce) fix(remote-config): build AppBinding from scratch to avoid 3-way merge corruption
- [09e3e396](https://github.com/kubedb/cli/commit/09e3e396d) fix(remote-config): strip server-managed metadata fields from generated YAML
- [36168ea0](https://github.com/kubedb/cli/commit/36168ea09) dc-dr: pin-standby timing caveat, hold refuses the post-failback rewind
- [fc6ee552](https://github.com/kubedb/cli/commit/fc6ee552d) dc-dr: pin-primary --remove --force clears a dead DC's stuck override-hold
- [f0e4a30c](https://github.com/kubedb/cli/commit/f0e4a30cd) dc-dr: kubectl-dba command group for cross data center DR day-2 operations



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



## [kubedb/db2](https://github.com/kubedb/db2)

### [v0.9.0](https://github.com/kubedb/db2/releases/tag/v0.9.0)

- [4b49dded](https://github.com/kubedb/db2/commit/4b49dded) Prepare for release v0.9.0 (#46)
- [4765d202](https://github.com/kubedb/db2/commit/4765d202) Use Go 1.27, k8s 1.37 & debian:13 (#45)
- [ac9db734](https://github.com/kubedb/db2/commit/ac9db734) Sync status.observedGeneration with metadata.generation on spec-only changes
- [e947a027](https://github.com/kubedb/db2/commit/e947a027) Sync Services with spec.serviceTemplates via shared helper (#44)
- [9bfbc770](https://github.com/kubedb/db2/commit/9bfbc770) exclude semiclone from password (#42)
- [c81c1cbd](https://github.com/kubedb/db2/commit/c81c1cbd) Prepare for release v0.8.0-rc.2 (#41)
- [b58a8323](https://github.com/kubedb/db2/commit/b58a8323) Prepare for release v0.8.0-rc.0 (#39)
- [be3f3b37](https://github.com/kubedb/db2/commit/be3f3b37) Prepare for release v0.7.0-rc.0 (#38)
- [ccf20e02](https://github.com/kubedb/db2/commit/ccf20e02) Migrate auth secret management to shared apimachinery secret package (#37)
- [4f924680](https://github.com/kubedb/db2/commit/4f924680) Add virtual secret support (#26)
- [87f6518b](https://github.com/kubedb/db2/commit/87f6518b) Move deletion logic to apimachinery (#36)



## [kubedb/db2-coordinator](https://github.com/kubedb/db2-coordinator)

### [v0.9.0](https://github.com/kubedb/db2-coordinator/releases/tag/v0.9.0)

- [da1ae0b](https://github.com/kubedb/db2-coordinator/commit/da1ae0b) Prepare for release v0.9.0 (#24)
- [5d9c739](https://github.com/kubedb/db2-coordinator/commit/5d9c739) Use Go 1.27, k8s 1.37 & debian:13 (#23)
- [5a5f946](https://github.com/kubedb/db2-coordinator/commit/5a5f946) Prepare for release v0.8.0-rc.2 (#20)
- [6f26b16](https://github.com/kubedb/db2-coordinator/commit/6f26b16) Prepare for release v0.8.0-rc.1 (#19)
- [938389f](https://github.com/kubedb/db2-coordinator/commit/938389f) Prepare for release v0.8.0-rc.0 (#18)
- [ac3486b](https://github.com/kubedb/db2-coordinator/commit/ac3486b) Prepare for release v0.7.0-rc.0 (#17)



## [kubedb/druid](https://github.com/kubedb/druid)

### [v0.23.0](https://github.com/kubedb/druid/releases/tag/v0.23.0)

- [c6aba64e](https://github.com/kubedb/druid/commit/c6aba64e) Prepare for release v0.23.0 (#159)
- [c90744b6](https://github.com/kubedb/druid/commit/c90744b6) Use Go 1.27, k8s 1.37 & debian:13 (#158)
- [06463290](https://github.com/kubedb/druid/commit/06463290) Sync status.observedGeneration with metadata.generation on spec-only changes
- [a4813609](https://github.com/kubedb/druid/commit/a4813609) Sync Services with spec.serviceTemplates via shared helper (#157)
- [a1b656c8](https://github.com/kubedb/druid/commit/a1b656c8) Prepare for release v0.22.0-rc.2 (#156)
- [4dfdca51](https://github.com/kubedb/druid/commit/4dfdca51) Fix AppBinding URL Scheme (#154)
- [b9ad65ca](https://github.com/kubedb/druid/commit/b9ad65ca) Prepare for release v0.22.0-rc.0 (#153)
- [14081e59](https://github.com/kubedb/druid/commit/14081e59) Prepare for release v0.21.0-rc.0 (#152)
- [91905bb4](https://github.com/kubedb/druid/commit/91905bb4) Migrate to shared auth-secret package (#151)
- [3d9469d6](https://github.com/kubedb/druid/commit/3d9469d6) Adopt shared monitor/appbinding packages from apimachinery (#150)
- [247bfac0](https://github.com/kubedb/druid/commit/247bfac0) Add virtual secret support (#133)
- [7abb51db](https://github.com/kubedb/druid/commit/7abb51db) Set default resource limits before patching petset in vertical scaling (#148)
- [0a1e5aac](https://github.com/kubedb/druid/commit/0a1e5aac) Move deletion logic to apimachinery (#149)



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



## [kubedb/elasticsearch-restic-plugin](https://github.com/kubedb/elasticsearch-restic-plugin)

### [v0.31.0](https://github.com/kubedb/elasticsearch-restic-plugin/releases/tag/v0.31.0)

- [05cf3e27](https://github.com/kubedb/elasticsearch-restic-plugin/commit/05cf3e27) Prepare for release v0.31.0 (#112)
- [74174804](https://github.com/kubedb/elasticsearch-restic-plugin/commit/74174804) Use Go 1.27, k8s 1.37 & debian:13 (#111)
- [e46b0c60](https://github.com/kubedb/elasticsearch-restic-plugin/commit/e46b0c60) Prepare for release v0.30.0-rc.2 (#110)
- [8b2a3fe9](https://github.com/kubedb/elasticsearch-restic-plugin/commit/8b2a3fe9) Prepare for release v0.30.0-rc.1 (#109)
- [a7ea7a14](https://github.com/kubedb/elasticsearch-restic-plugin/commit/a7ea7a14) Prepare for release v0.30.0-rc.0 (#108)
- [d3eaaafd](https://github.com/kubedb/elasticsearch-restic-plugin/commit/d3eaaafd) Prepare for release v0.29.0-rc.0 (#107)
- [542bd21b](https://github.com/kubedb/elasticsearch-restic-plugin/commit/542bd21b) Add Virtual Secret Support (#104)



## [kubedb/etcd-restic-plugin](https://github.com/kubedb/etcd-restic-plugin)

### [v0.2.0](https://github.com/kubedb/etcd-restic-plugin/releases/tag/v0.2.0)

- [679a2c0](https://github.com/kubedb/etcd-restic-plugin/commit/679a2c0) Prepare for release v0.2.0 (#4)
- [ff6dfe4](https://github.com/kubedb/etcd-restic-plugin/commit/ff6dfe4) Use Go 1.27, k8s 1.37 & debian:13 (#3)
- [00faabb](https://github.com/kubedb/etcd-restic-plugin/commit/00faabb) Prepare for release v0.1.0-rc.2 (#2)
- [ff35eda](https://github.com/kubedb/etcd-restic-plugin/commit/ff35eda) Update deps
- [f574749](https://github.com/kubedb/etcd-restic-plugin/commit/f574749) Fix snapshot integrity, restore idempotency and space accounting
- [54c8420](https://github.com/kubedb/etcd-restic-plugin/commit/54c8420) backup: check f.Close() error in sha256File
- [ecf9140](https://github.com/kubedb/etcd-restic-plugin/commit/ecf9140) Add missing .github CI workflow folder
- [974b15b](https://github.com/kubedb/etcd-restic-plugin/commit/974b15b) Add README



## [kubedb/gitops](https://github.com/kubedb/gitops)

### [v0.16.0](https://github.com/kubedb/gitops/releases/tag/v0.16.0)

- [bdcbacd2](https://github.com/kubedb/gitops/commit/bdcbacd2) Prepare for release v0.16.0 (#96)
- [a52129f3](https://github.com/kubedb/gitops/commit/a52129f3) Use Go 1.27, k8s 1.37 & debian:13 (#95)
- [0e39fe7e](https://github.com/kubedb/gitops/commit/0e39fe7e) Prepare for release v0.15.0-rc.2 (#93)
- [01a03f3e](https://github.com/kubedb/gitops/commit/01a03f3e) Prepare for release v0.15.0-rc.1 (#92)
- [6da96309](https://github.com/kubedb/gitops/commit/6da96309) Add Etcd GitOps support (#91)
- [a77ddade](https://github.com/kubedb/gitops/commit/a77ddade) Prepare for release v0.15.0-rc.0 (#90)
- [c0f20f15](https://github.com/kubedb/gitops/commit/c0f20f15) Prepare for release v0.14.0-rc.0 (#89)
- [492a5dda](https://github.com/kubedb/gitops/commit/492a5dda) [Solr] Fix Solr API (#88)
- [2aee9ab8](https://github.com/kubedb/gitops/commit/2aee9ab8) Add Virtual Secret Support (#86)



## [kubedb/hanadb](https://github.com/kubedb/hanadb)

### [v0.9.0](https://github.com/kubedb/hanadb/releases/tag/v0.9.0)

- [dfbf2a81](https://github.com/kubedb/hanadb/commit/dfbf2a81) Prepare for release v0.9.0 (#67)
- [3ebde9b8](https://github.com/kubedb/hanadb/commit/3ebde9b8) Use Go 1.27, k8s 1.37 & debian:13 (#66)
- [72bb1373](https://github.com/kubedb/hanadb/commit/72bb1373) Sync status.observedGeneration with metadata.generation on spec-only changes
- [036cd436](https://github.com/kubedb/hanadb/commit/036cd436) Sync Services with spec.serviceTemplates via shared helper (#65)
- [878f2041](https://github.com/kubedb/hanadb/commit/878f2041) Prepare for release v0.8.0-rc.2 (#62)
- [eea6e348](https://github.com/kubedb/hanadb/commit/eea6e348) Prepare for release v0.8.0-rc.1 (#61)
- [7cb78e06](https://github.com/kubedb/hanadb/commit/7cb78e06) Only watch virtual-secrets Secret when the CRD is installed (#60)
- [b678cf7a](https://github.com/kubedb/hanadb/commit/b678cf7a) Prepare for release v0.8.0-rc.0 (#59)
- [2791d997](https://github.com/kubedb/hanadb/commit/2791d997) Prepare for release v0.7.0-rc.0 (#58)
- [d3fdd8a8](https://github.com/kubedb/hanadb/commit/d3fdd8a8) Implement horizontal scaling, update version ops (#47)
- [e5bbe114](https://github.com/kubedb/hanadb/commit/e5bbe114) Fix HanaDB ops and volume permission handling (#49)
- [dba6048b](https://github.com/kubedb/hanadb/commit/dba6048b) Add virtual secret support (#40)
- [4b038da8](https://github.com/kubedb/hanadb/commit/4b038da8) Adopt shared apimachinery secret package for auth secret handling (#56)
- [25b8aa29](https://github.com/kubedb/hanadb/commit/25b8aa29) Adopt shared monitor/appbinding packages from apimachinery (#55)
- [916a4696](https://github.com/kubedb/hanadb/commit/916a4696) Move deletion logic to apimachinery (#54)



## [kubedb/hanadb-coordinator](https://github.com/kubedb/hanadb-coordinator)

### [v0.8.0](https://github.com/kubedb/hanadb-coordinator/releases/tag/v0.8.0)

- [c2d0ee94](https://github.com/kubedb/hanadb-coordinator/commit/c2d0ee94) Prepare for release v0.8.0 (#26)
- [ee198316](https://github.com/kubedb/hanadb-coordinator/commit/ee198316) Use Go 1.27, k8s 1.37 & debian:13 (#25)
- [83e3f954](https://github.com/kubedb/hanadb-coordinator/commit/83e3f954) Prepare for release v0.7.0-rc.2 (#24)
- [4946cd74](https://github.com/kubedb/hanadb-coordinator/commit/4946cd74) Prepare for release v0.7.0-rc.1 (#23)
- [008bb749](https://github.com/kubedb/hanadb-coordinator/commit/008bb749) Prepare for release v0.7.0-rc.0 (#22)
- [8185142d](https://github.com/kubedb/hanadb-coordinator/commit/8185142d) Prepare for release v0.6.0-rc.0 (#21)



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



## [kubedb/ignite](https://github.com/kubedb/ignite)

### [v0.15.0](https://github.com/kubedb/ignite/releases/tag/v0.15.0)

- [6977174d](https://github.com/kubedb/ignite/commit/6977174d) Prepare for release v0.15.0 (#79)
- [84b40223](https://github.com/kubedb/ignite/commit/84b40223) Use Go 1.27, k8s 1.37 & debian:13 (#78)
- [9de2974d](https://github.com/kubedb/ignite/commit/9de2974d) Sync status.observedGeneration with metadata.generation on spec-only changes
- [4f7db964](https://github.com/kubedb/ignite/commit/4f7db964) Sync Services with spec.serviceTemplates via shared helper (#77)
- [d8ffae05](https://github.com/kubedb/ignite/commit/d8ffae05) Prepare for release v0.14.0-rc.2 (#76)
- [da85f22f](https://github.com/kubedb/ignite/commit/da85f22f) Prepare for release v0.14.0-rc.1 (#75)
- [ff07bf28](https://github.com/kubedb/ignite/commit/ff07bf28) Add TLS Certs in AppBinding (#74)
- [059966b4](https://github.com/kubedb/ignite/commit/059966b4) Only watch virtual-secrets Secret when the CRD is installed (#73)
- [053b6b4c](https://github.com/kubedb/ignite/commit/053b6b4c) Prepare for release v0.14.0-rc.0 (#72)
- [9c019938](https://github.com/kubedb/ignite/commit/9c019938) Prepare for release v0.13.0-rc.0 (#71)
- [bf57aef8](https://github.com/kubedb/ignite/commit/bf57aef8) Migrate auth/keystore secret management to shared apimachinery pkg (#70)
- [5e7d5e13](https://github.com/kubedb/ignite/commit/5e7d5e13) Add virtual secret support (#55)
- [ea1d0e17](https://github.com/kubedb/ignite/commit/ea1d0e17) Use shared monitor and appbinding packages (#69)
- [140b6332](https://github.com/kubedb/ignite/commit/140b6332) Set default resource limits before patching petset in vertical scaling
- [d8aee1f0](https://github.com/kubedb/ignite/commit/d8aee1f0) Honor user-provided renewBefore in TLS certificate ops (#56)
- [8d071a7a](https://github.com/kubedb/ignite/commit/8d071a7a) Move deletion logic to apimachinery (#68)



## [kubedb/kafka](https://github.com/kubedb/kafka)

### [v0.39.0](https://github.com/kubedb/kafka/releases/tag/v0.39.0)

- [cba96e5e](https://github.com/kubedb/kafka/commit/cba96e5e) Prepare for release v0.39.0 (#224)
- [fc468a4a](https://github.com/kubedb/kafka/commit/fc468a4a) Use Go 1.27, k8s 1.37 & debian:13 (#223)
- [d92f14ba](https://github.com/kubedb/kafka/commit/d92f14ba) Sync status.observedGeneration with metadata.generation on spec-only changes
- [5624933b](https://github.com/kubedb/kafka/commit/5624933b) Sync Services with spec.serviceTemplates via shared helper (#222)
- [877b1bd2](https://github.com/kubedb/kafka/commit/877b1bd2) Prepare for release v0.38.0-rc.2 (#220)
- [ea87de4e](https://github.com/kubedb/kafka/commit/ea87de4e) Prepare for release v0.38.0-rc.1 (#219)
- [84c08626](https://github.com/kubedb/kafka/commit/84c08626) Prepare for release v0.38.0-rc.0 (#218)
- [28856e2e](https://github.com/kubedb/kafka/commit/28856e2e) Prepare for release v0.37.0-rc.0 (#217)
- [189fe261](https://github.com/kubedb/kafka/commit/189fe261) Migrate kafka-cluster and connect-cluster auth secrets to shared secret package (#216)
- [c5ad9ccc](https://github.com/kubedb/kafka/commit/c5ad9ccc) Use shared monitor and appbinding packages (#215)
- [c435a470](https://github.com/kubedb/kafka/commit/c435a470) Add virtual secret support (#197)
- [61481399](https://github.com/kubedb/kafka/commit/61481399) Set default resource limits before patching petset in vertical scaling
- [899e74ab](https://github.com/kubedb/kafka/commit/899e74ab) Move deletion logic to apimachinery (#214)
- [86fa0034](https://github.com/kubedb/kafka/commit/86fa0034) Merge pull request #212 from kubedb/v2026.7.10-master



## [kubedb/kubedb-manifest-plugin](https://github.com/kubedb/kubedb-manifest-plugin)

### [v0.31.0](https://github.com/kubedb/kubedb-manifest-plugin/releases/tag/v0.31.0)

- [1f555ce5](https://github.com/kubedb/kubedb-manifest-plugin/commit/1f555ce5) Prepare for release v0.31.0 (#148)
- [24a060da](https://github.com/kubedb/kubedb-manifest-plugin/commit/24a060da) Use Go 1.27, k8s 1.37 & debian:13 (#147)
- [453a17d9](https://github.com/kubedb/kubedb-manifest-plugin/commit/453a17d9) Support Milvus manifest backup and restore (#146)
- [5a757e23](https://github.com/kubedb/kubedb-manifest-plugin/commit/5a757e23) Add Neo4j Manifest Plugin (#138)
- [44572547](https://github.com/kubedb/kubedb-manifest-plugin/commit/44572547) Prepare for release v0.30.0-rc.2 (#144)
- [3d3ad890](https://github.com/kubedb/kubedb-manifest-plugin/commit/3d3ad890) Prepare for release v0.30.0-rc.1 (#143)
- [130ac489](https://github.com/kubedb/kubedb-manifest-plugin/commit/130ac489) Prepare for release v0.30.0-rc.0 (#142)
- [cd4c5601](https://github.com/kubedb/kubedb-manifest-plugin/commit/cd4c5601) Prepare for release v0.29.0-rc.0 (#141)
- [3fd5160f](https://github.com/kubedb/kubedb-manifest-plugin/commit/3fd5160f) Add Virtual Secret Support (#137)



## [kubedb/kubedb-verifier](https://github.com/kubedb/kubedb-verifier)

### [v0.19.0](https://github.com/kubedb/kubedb-verifier/releases/tag/v0.19.0)

- [8cc919c9](https://github.com/kubedb/kubedb-verifier/commit/8cc919c9) Prepare for release v0.19.0 (#63)
- [6c4f6891](https://github.com/kubedb/kubedb-verifier/commit/6c4f6891) Use Go 1.27, k8s 1.37 & debian:13 (#62)
- [8dd10355](https://github.com/kubedb/kubedb-verifier/commit/8dd10355) Prepare for release v0.18.0-rc.2 (#61)
- [2f4d0681](https://github.com/kubedb/kubedb-verifier/commit/2f4d0681) Prepare for release v0.18.0-rc.1 (#60)
- [0ee34ed3](https://github.com/kubedb/kubedb-verifier/commit/0ee34ed3) Prepare for release v0.18.0-rc.0 (#59)
- [76948c76](https://github.com/kubedb/kubedb-verifier/commit/76948c76) Prepare for release v0.17.0-rc.0 (#58)



## [kubedb/mariadb-archiver](https://github.com/kubedb/mariadb-archiver)

### [v0.28.0](https://github.com/kubedb/mariadb-archiver/releases/tag/v0.28.0)

- [ba53fe01](https://github.com/kubedb/mariadb-archiver/commit/ba53fe01) Prepare for release v0.28.0 (#106)
- [f58dd4e7](https://github.com/kubedb/mariadb-archiver/commit/f58dd4e7) Use Go 1.27, k8s 1.37 & debian:13 (#105)
- [e8899069](https://github.com/kubedb/mariadb-archiver/commit/e8899069) Prepare for release v0.27.0-rc.2 (#104)
- [0a816c0e](https://github.com/kubedb/mariadb-archiver/commit/0a816c0e) Prepare for release v0.27.0-rc.1 (#103)
- [2065feca](https://github.com/kubedb/mariadb-archiver/commit/2065feca) Prepare for release v0.27.0-rc.0 (#101)
- [97664701](https://github.com/kubedb/mariadb-archiver/commit/97664701) Prepare for release v0.26.0-rc.0 (#100)
- [e94155d5](https://github.com/kubedb/mariadb-archiver/commit/e94155d5) Merge pull request #99 from kubedb/v2026.7.10-master



## [kubedb/mariadb-coordinator](https://github.com/kubedb/mariadb-coordinator)

### [v0.48.0](https://github.com/kubedb/mariadb-coordinator/releases/tag/v0.48.0)

- [16f1a252](https://github.com/kubedb/mariadb-coordinator/commit/16f1a252) Prepare for release v0.48.0 (#192)
- [c9e0fcc5](https://github.com/kubedb/mariadb-coordinator/commit/c9e0fcc5) Use Go 1.27, k8s 1.37 & debian:13 (#191)
- [5e21bff3](https://github.com/kubedb/mariadb-coordinator/commit/5e21bff3) Prepare for release v0.47.0-rc.2 (#190)
- [989706c7](https://github.com/kubedb/mariadb-coordinator/commit/989706c7) Prepare for release v0.47.0-rc.1 (#189)
- [4cb4c9cc](https://github.com/kubedb/mariadb-coordinator/commit/4cb4c9cc) Prepare for release v0.47.0-rc.0 (#188)
- [4772461d](https://github.com/kubedb/mariadb-coordinator/commit/4772461d) Prepare for release v0.46.0-rc.0 (#187)



## [kubedb/mariadb-restic-plugin](https://github.com/kubedb/mariadb-restic-plugin)

### [v0.26.0](https://github.com/kubedb/mariadb-restic-plugin/releases/tag/v0.26.0)

- [18527210](https://github.com/kubedb/mariadb-restic-plugin/commit/18527210) Prepare for release v0.26.0 (#106)
- [1645bb03](https://github.com/kubedb/mariadb-restic-plugin/commit/1645bb03) Use Go 1.27, k8s 1.37 & debian:13 (#105)
- [356bcc77](https://github.com/kubedb/mariadb-restic-plugin/commit/356bcc77) Prepare for release v0.25.0-rc.2 (#104)
- [014243fd](https://github.com/kubedb/mariadb-restic-plugin/commit/014243fd) Prepare for release v0.25.0-rc.1 (#103)
- [de4e7af5](https://github.com/kubedb/mariadb-restic-plugin/commit/de4e7af5) Prepare for release v0.25.0-rc.0 (#102)
- [69621d76](https://github.com/kubedb/mariadb-restic-plugin/commit/69621d76) Prepare for release v0.24.0-rc.0 (#101)



## [kubedb/migrator](https://github.com/kubedb/migrator)

### [v0.8.0](https://github.com/kubedb/migrator/releases/tag/v0.8.0)

- [6404af2c](https://github.com/kubedb/migrator/commit/6404af2c) Prepare for release v0.8.0 (#56)
- [9c8f6b23](https://github.com/kubedb/migrator/commit/9c8f6b23) Use Go 1.27, k8s 1.37 & debian:13 (#55)
- [59559de1](https://github.com/kubedb/migrator/commit/59559de1) Feat/mssql database specific table selection & precheck (#52)
- [c6feaa68](https://github.com/kubedb/migrator/commit/c6feaa68) Prepare for release v0.7.0-rc.2 (#54)
- [5d3b4cca](https://github.com/kubedb/migrator/commit/5d3b4cca) Prepare for release v0.7.0-rc.1 (#53)
- [90f812e8](https://github.com/kubedb/migrator/commit/90f812e8) fixed patch issue
- [20d0ec20](https://github.com/kubedb/migrator/commit/20d0ec20) Fix MSSQL snapshot FK disable retries and CDC start LSN validation (#50)
- [72b69108](https://github.com/kubedb/migrator/commit/72b69108) Prepare for release v0.7.0-rc.0 (#49)
- [e9d330c6](https://github.com/kubedb/migrator/commit/e9d330c6) Prepare for release v0.6.0-rc.0 (#48)
- [9ccfbe83](https://github.com/kubedb/migrator/commit/9ccfbe83) Fix mssql snapshot tds eof retry (#47)
- [a5b1a307](https://github.com/kubedb/migrator/commit/a5b1a307) Update postgres sequence value when migration stops (#46)
- [91bfb3ac](https://github.com/kubedb/migrator/commit/91bfb3ac) Fixed release issue,waited for inital lsn for cdc
- [d9bf2272](https://github.com/kubedb/migrator/commit/d9bf2272) Add non root user in every docker file (#44)



## [kubedb/milvus](https://github.com/kubedb/milvus)

### [v0.9.0](https://github.com/kubedb/milvus/releases/tag/v0.9.0)

- [b98bb3bf](https://github.com/kubedb/milvus/commit/b98bb3bf) Prepare for release v0.9.0 (#74)
- [664160ec](https://github.com/kubedb/milvus/commit/664160ec) Use Go 1.27, k8s 1.37 & debian:13 (#73)
- [dd2f9900](https://github.com/kubedb/milvus/commit/dd2f9900) Add Milvus archiver: base backup, VolumeSnapshot backup and PITR (#71)
- [cea19ec9](https://github.com/kubedb/milvus/commit/cea19ec9) Sync status.observedGeneration with metadata.generation on spec-only changes
- [4bcef62e](https://github.com/kubedb/milvus/commit/4bcef62e) Sync Services with spec.serviceTemplates via shared helper (#72)
- [0da0d6ae](https://github.com/kubedb/milvus/commit/0da0d6ae) Replace official etcd-operator with KubeDB's own etcd operator for meta storage (#68)
- [c6a56b4e](https://github.com/kubedb/milvus/commit/c6a56b4e) Fail ops requests when pod/petset wait retries are exhausted (#67)
- [0e4f45cf](https://github.com/kubedb/milvus/commit/0e4f45cf) Add TLS Secret to AppBinding (#66)
- [c838b4d9](https://github.com/kubedb/milvus/commit/c838b4d9) Prepare for release v0.8.0-rc.2 (#65)
- [514250e6](https://github.com/kubedb/milvus/commit/514250e6) Prepare for release v0.8.0-rc.1 (#64)
- [4edc3864](https://github.com/kubedb/milvus/commit/4edc3864) Prepare for release v0.8.0-rc.0 (#63)
- [1b216221](https://github.com/kubedb/milvus/commit/1b216221) Prepare for release v0.7.0-rc.0 (#62)
- [4fe1caf8](https://github.com/kubedb/milvus/commit/4fe1caf8) Fix Milvus Minio Secret Bug (#61)
- [fb200646](https://github.com/kubedb/milvus/commit/fb200646) Migrate to shared apimachinery secret package (#60)
- [f57a329e](https://github.com/kubedb/milvus/commit/f57a329e) Use shared monitor and appbinding packages (#59)
- [c0190f3e](https://github.com/kubedb/milvus/commit/c0190f3e) Add virtual secret support (#38)
- [c7794778](https://github.com/kubedb/milvus/commit/c7794778) Set default resource limits before patching petset in vertical scaling
- [db076099](https://github.com/kubedb/milvus/commit/db076099) Move deletion logic to apimachinery (#57)



## [kubedb/mongodb](https://github.com/kubedb/mongodb)

### [v0.61.0](https://github.com/kubedb/mongodb/releases/tag/v0.61.0)

- [8831d659](https://github.com/kubedb/mongodb/commit/8831d659d) Prepare for release v0.61.0 (#790)
- [50371c68](https://github.com/kubedb/mongodb/commit/50371c68c) Use Go 1.27, k8s 1.37 & debian:13 (#789)
- [988213d8](https://github.com/kubedb/mongodb/commit/988213d80) Classify reconfigure parameters and apply the dynamic ones live (#787)
- [f1d3422e](https://github.com/kubedb/mongodb/commit/f1d3422e2) Sync status.observedGeneration with metadata.generation on spec-only changes
- [00e24642](https://github.com/kubedb/mongodb/commit/00e24642a) Add branched mode for KubeDB Courier Branch (#774)
- [96d78e8d](https://github.com/kubedb/mongodb/commit/96d78e8df) Sync primary Service with serviceTemplate via shared helper (#788)
- [46539ef2](https://github.com/kubedb/mongodb/commit/46539ef20) Prepare for release v0.60.0-rc.2 (#785)
- [2c3af67f](https://github.com/kubedb/mongodb/commit/2c3af67f2) Prepare for release v0.60.0-rc.1 (#784)
- [1a23d8c2](https://github.com/kubedb/mongodb/commit/1a23d8c2a) Prepare for release v0.60.0-rc.0 (#783)
- [2af7c3d8](https://github.com/kubedb/mongodb/commit/2af7c3d87) Prepare for release v0.59.0-rc.0 (#782)
- [a3753bec](https://github.com/kubedb/mongodb/commit/a3753bece) Use shared pkg/controller/secret for auth & keyfile secrets (#781)
- [620d2763](https://github.com/kubedb/mongodb/commit/620d27631) Adopt shared monitor/appbinding packages from apimachinery (#780)
- [59977bef](https://github.com/kubedb/mongodb/commit/59977bef8) Virtual Secret Ops Support (#779)
- [91595b9a](https://github.com/kubedb/mongodb/commit/91595b9ad) Use shared pkg/controller/deletion for termination and halt (#778)
- [14997977](https://github.com/kubedb/mongodb/commit/149979774) Merge pull request #777 from kubedb/v2026.7.10-master



## [kubedb/mongodb-csi-snapshotter-plugin](https://github.com/kubedb/mongodb-csi-snapshotter-plugin)

### [v0.29.0](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/releases/tag/v0.29.0)

- [235ac48a](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/235ac48a) Prepare for release v0.29.0 (#94)
- [7486f19d](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/7486f19d) Use Go 1.27, k8s 1.37 & debian:13 (#93)
- [23358801](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/23358801) Prepare for release v0.28.0-rc.2 (#92)
- [926b7b03](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/926b7b03) Prepare for release v0.28.0-rc.1 (#91)
- [1560789a](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/1560789a) Prepare for release v0.28.0-rc.0 (#90)
- [b2684818](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/b2684818) Prepare for release v0.27.0-rc.0 (#89)



## [kubedb/mongodb-restic-plugin](https://github.com/kubedb/mongodb-restic-plugin)

### [v0.31.0](https://github.com/kubedb/mongodb-restic-plugin/releases/tag/v0.31.0)

- [38e6b47d](https://github.com/kubedb/mongodb-restic-plugin/commit/38e6b47d) Prepare for release v0.31.0 (#141)
- [8e9c22aa](https://github.com/kubedb/mongodb-restic-plugin/commit/8e9c22aa) Use Go 1.27, k8s 1.37 & debian:13 (#140)
- [4966212d](https://github.com/kubedb/mongodb-restic-plugin/commit/4966212d) Prepare for release v0.30.0-rc.2 (#139)
- [aa7a7eb6](https://github.com/kubedb/mongodb-restic-plugin/commit/aa7a7eb6) Prepare for release v0.30.0-rc.1 (#138)
- [0a863335](https://github.com/kubedb/mongodb-restic-plugin/commit/0a863335) Prepare for release v0.30.0-rc.0 (#137)
- [ba50bd65](https://github.com/kubedb/mongodb-restic-plugin/commit/ba50bd65) Prepare for release v0.29.0-rc.0 (#136)
- [802a7051](https://github.com/kubedb/mongodb-restic-plugin/commit/802a7051) Add Virtual Secret Support (#133)



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



## [kubedb/mssqlserver](https://github.com/kubedb/mssqlserver)

### [v0.23.0](https://github.com/kubedb/mssqlserver/releases/tag/v0.23.0)

- [136c77cf](https://github.com/kubedb/mssqlserver/commit/136c77cf) Prepare for release v0.23.0 (#163)
- [d524f4a9](https://github.com/kubedb/mssqlserver/commit/d524f4a9) Use Go 1.27, k8s 1.37 & debian:13 (#162)
- [fa288a35](https://github.com/kubedb/mssqlserver/commit/fa288a35) Sync status.observedGeneration with metadata.generation on spec-only changes
- [cc1cb284](https://github.com/kubedb/mssqlserver/commit/cc1cb284) Sync Services with spec.serviceTemplates via shared helper (#161)
- [63ce4105](https://github.com/kubedb/mssqlserver/commit/63ce4105) Prepare for release v0.22.0-rc.2 (#159)
- [03752a06](https://github.com/kubedb/mssqlserver/commit/03752a06) Prepare for release v0.22.0-rc.1 (#158)
- [31242bf9](https://github.com/kubedb/mssqlserver/commit/31242bf9) Prepare for release v0.22.0-rc.0 (#157)
- [67038153](https://github.com/kubedb/mssqlserver/commit/67038153) Prepare for release v0.21.0-rc.0 (#156)
- [9ed3f569](https://github.com/kubedb/mssqlserver/commit/9ed3f569) feat: implement git-sync init container for MSSQLServer (#135)
- [d1ce9121](https://github.com/kubedb/mssqlserver/commit/d1ce9121) Add virtual secret support (#134)
- [d6073fd8](https://github.com/kubedb/mssqlserver/commit/d6073fd8) Migrate auth-secret and extra-secret handling to shared apimachinery pkg (#155)
- [f0233fe7](https://github.com/kubedb/mssqlserver/commit/f0233fe7) Use shared monitor and appbinding packages (#154)
- [ea93f18b](https://github.com/kubedb/mssqlserver/commit/ea93f18b) Honor user-provided renewBefore in TLS certificate ops (#136)
- [ddc48b66](https://github.com/kubedb/mssqlserver/commit/ddc48b66) Move deletion logic to apimachinery (#153)



## [kubedb/mssqlserver-walg-plugin](https://github.com/kubedb/mssqlserver-walg-plugin)

### [v0.22.0](https://github.com/kubedb/mssqlserver-walg-plugin/releases/tag/v0.22.0)

- [05422ba9](https://github.com/kubedb/mssqlserver-walg-plugin/commit/05422ba9) Prepare for release v0.22.0 (#72)
- [2146c995](https://github.com/kubedb/mssqlserver-walg-plugin/commit/2146c995) Use Go 1.27, k8s 1.37 & debian:13 (#71)
- [d7e11547](https://github.com/kubedb/mssqlserver-walg-plugin/commit/d7e11547) Prepare for release v0.21.0-rc.2 (#70)
- [9e36bfed](https://github.com/kubedb/mssqlserver-walg-plugin/commit/9e36bfed) Prepare for release v0.21.0-rc.1 (#69)
- [795d6e08](https://github.com/kubedb/mssqlserver-walg-plugin/commit/795d6e08) Prepare for release v0.21.0-rc.0 (#68)
- [4b43a1c5](https://github.com/kubedb/mssqlserver-walg-plugin/commit/4b43a1c5) Prepare for release v0.20.0-rc.0 (#67)
- [12f92505](https://github.com/kubedb/mssqlserver-walg-plugin/commit/12f92505) Integrate virtual secret (#64)



## [kubedb/mysql](https://github.com/kubedb/mysql)

### [v0.61.0](https://github.com/kubedb/mysql/releases/tag/v0.61.0)

- [e276628f](https://github.com/kubedb/mysql/commit/e276628f0) Prepare for release v0.61.0 (#784)
- [56250eba](https://github.com/kubedb/mysql/commit/56250eba1) Use Go 1.27, k8s 1.37 & debian:13 (#783)
- [d42a9385](https://github.com/kubedb/mysql/commit/d42a93853) Sync status.observedGeneration with metadata.generation on spec-only changes
- [6029a977](https://github.com/kubedb/mysql/commit/6029a9771) Sync Services with spec.serviceTemplates via shared helper (#782)
- [25ce8f92](https://github.com/kubedb/mysql/commit/25ce8f92d) Add branched mode for KubeDB Courier Branch (#765)
- [90cc7def](https://github.com/kubedb/mysql/commit/90cc7defb) Prepare for release v0.60.0-rc.2 (#780)
- [270d79ab](https://github.com/kubedb/mysql/commit/270d79ab7) Prepare for release v0.60.0-rc.1 (#779)
- [db444927](https://github.com/kubedb/mysql/commit/db4449279) Prepare for release v0.60.0-rc.0 (#778)
- [ffef9146](https://github.com/kubedb/mysql/commit/ffef91463) Prepare for release v0.59.0-rc.0 (#777)
- [b5175dc7](https://github.com/kubedb/mysql/commit/b5175dc75) Promote MySQL Standalone To Cluster (#774)
- [5ffb7469](https://github.com/kubedb/mysql/commit/5ffb7469d) My ops timeout (#775)
- [ef85ecc0](https://github.com/kubedb/mysql/commit/ef85ecc0d) Migrate auth secret management to shared apimachinery secret package (#773)
- [6c022f70](https://github.com/kubedb/mysql/commit/6c022f700) Adopt shared monitor/appbinding packages from apimachinery (#772)
- [38e268f5](https://github.com/kubedb/mysql/commit/38e268f51) Set default resource limits before patching petset in vertical scaling (#769)
- [134d1009](https://github.com/kubedb/mysql/commit/134d10092) cross rotate auth (#770)
- [b4564765](https://github.com/kubedb/mysql/commit/b4564765a) Move deletion logic to apimachinery (#771)



## [kubedb/mysql-archiver](https://github.com/kubedb/mysql-archiver)

### [v0.29.0](https://github.com/kubedb/mysql-archiver/releases/tag/v0.29.0)

- [74e43295](https://github.com/kubedb/mysql-archiver/commit/74e43295) Prepare for release v0.29.0 (#119)
- [a6964253](https://github.com/kubedb/mysql-archiver/commit/a6964253) Use Go 1.27, k8s 1.37 & debian:13 (#118)
- [82342bcb](https://github.com/kubedb/mysql-archiver/commit/82342bcb) Prepare for release v0.28.0-rc.2 (#117)
- [d4e1e633](https://github.com/kubedb/mysql-archiver/commit/d4e1e633) Prepare for release v0.28.0-rc.1 (#116)
- [e0da0940](https://github.com/kubedb/mysql-archiver/commit/e0da0940) Prepare for release v0.28.0-rc.0 (#115)
- [8d7d93e7](https://github.com/kubedb/mysql-archiver/commit/8d7d93e7) Prepare for release v0.27.0-rc.0 (#113)



## [kubedb/mysql-coordinator](https://github.com/kubedb/mysql-coordinator)

### [v0.46.0](https://github.com/kubedb/mysql-coordinator/releases/tag/v0.46.0)

- [6ad63b60](https://github.com/kubedb/mysql-coordinator/commit/6ad63b60) Prepare for release v0.46.0 (#195)
- [4d97a0b2](https://github.com/kubedb/mysql-coordinator/commit/4d97a0b2) Use Go 1.27, k8s 1.37 & debian:13 (#194)
- [fc1b0d2c](https://github.com/kubedb/mysql-coordinator/commit/fc1b0d2c) Prepare for release v0.45.0-rc.2 (#193)
- [9819d7b6](https://github.com/kubedb/mysql-coordinator/commit/9819d7b6) Prepare for release v0.45.0-rc.1 (#192)
- [cdf83626](https://github.com/kubedb/mysql-coordinator/commit/cdf83626) Prepare for release v0.45.0-rc.0 (#191)
- [c1cd7cf5](https://github.com/kubedb/mysql-coordinator/commit/c1cd7cf5) Prepare for release v0.44.0-rc.0 (#190)
- [54b35ec1](https://github.com/kubedb/mysql-coordinator/commit/54b35ec1) Fix Join Cluster (#189)



## [kubedb/mysql-csi-snapshotter-plugin](https://github.com/kubedb/mysql-csi-snapshotter-plugin)

### [v0.29.0](https://github.com/kubedb/mysql-csi-snapshotter-plugin/releases/tag/v0.29.0)

- [aefc5ec6](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/aefc5ec6) Prepare for release v0.29.0 (#91)
- [5d949fef](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/5d949fef) Use Go 1.27, k8s 1.37 & debian:13 (#90)
- [7f1d1457](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/7f1d1457) Prepare for release v0.28.0-rc.2 (#89)
- [a51d7fa0](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/a51d7fa0) Prepare for release v0.28.0-rc.1 (#88)
- [4f2b4470](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/4f2b4470) Prepare for release v0.28.0-rc.0 (#87)
- [72e86946](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/72e86946) Prepare for release v0.27.0-rc.0 (#85)



## [kubedb/mysql-restic-plugin](https://github.com/kubedb/mysql-restic-plugin)

### [v0.31.0](https://github.com/kubedb/mysql-restic-plugin/releases/tag/v0.31.0)

- [daf85b7d](https://github.com/kubedb/mysql-restic-plugin/commit/daf85b7d) Prepare for release v0.31.0 (#127)
- [cce19813](https://github.com/kubedb/mysql-restic-plugin/commit/cce19813) Use Go 1.27, k8s 1.37 & debian:13 (#126)
- [b5b9f288](https://github.com/kubedb/mysql-restic-plugin/commit/b5b9f288) Prepare for release v0.30.0-rc.2 (#125)
- [37e44fe1](https://github.com/kubedb/mysql-restic-plugin/commit/37e44fe1) Prepare for release v0.30.0-rc.1 (#124)
- [72b83af2](https://github.com/kubedb/mysql-restic-plugin/commit/72b83af2) Prepare for release v0.30.0-rc.0 (#123)
- [78d689a8](https://github.com/kubedb/mysql-restic-plugin/commit/78d689a8) Prepare for release v0.29.0-rc.0 (#122)
- [c863d090](https://github.com/kubedb/mysql-restic-plugin/commit/c863d090) Fix --ssl-ca being silently dropped from the client command (#121)
- [78790d48](https://github.com/kubedb/mysql-restic-plugin/commit/78790d48) Add Virtual Secret Support (#118)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.46.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.46.0)

- [4097a3d](https://github.com/kubedb/mysql-router-init/commit/4097a3d) Prepare for release v0.46.0 (#73)
- [9d83b4e](https://github.com/kubedb/mysql-router-init/commit/9d83b4e) Use Go 1.27, k8s 1.37 & debian:13 (#72)
- [2a6cad1](https://github.com/kubedb/mysql-router-init/commit/2a6cad1) Prepare for release v0.45.0-rc.2 (#71)
- [b195b0d](https://github.com/kubedb/mysql-router-init/commit/b195b0d) Prepare for release v0.45.0-rc.1 (#70)
- [f335f57](https://github.com/kubedb/mysql-router-init/commit/f335f57) Prepare for release v0.45.0-rc.0 (#69)
- [3d63a45](https://github.com/kubedb/mysql-router-init/commit/3d63a45) Prepare for release v0.44.0-rc.0 (#68)



## [kubedb/neo4j-backup-plugin](https://github.com/kubedb/neo4j-backup-plugin)

### [v0.4.0](https://github.com/kubedb/neo4j-backup-plugin/releases/tag/v0.4.0)

- [8034ffd](https://github.com/kubedb/neo4j-backup-plugin/commit/8034ffd) Prepare for release v0.4.0 (#17)
- [86ebbf5](https://github.com/kubedb/neo4j-backup-plugin/commit/86ebbf5) Use Go 1.27, k8s 1.37 & debian:13 (#16)
- [aadfc86](https://github.com/kubedb/neo4j-backup-plugin/commit/aadfc86) Add Differential Backup Command #5
- [648128c](https://github.com/kubedb/neo4j-backup-plugin/commit/648128c) Prepare for release v0.3.0-rc.2 (#15)
- [4a6ab67](https://github.com/kubedb/neo4j-backup-plugin/commit/4a6ab67) Prepare for release v0.3.0-rc.1 (#14)
- [bdc2c01](https://github.com/kubedb/neo4j-backup-plugin/commit/bdc2c01) Merge pull request #11 from kubedb/restore-composite-database
- [fcbba98](https://github.com/kubedb/neo4j-backup-plugin/commit/fcbba98) fix lint: drop always-constant param from containsNormalized
- [8052e8a](https://github.com/kubedb/neo4j-backup-plugin/commit/8052e8a) add support for standalone alias
- [2d5168d](https://github.com/kubedb/neo4j-backup-plugin/commit/2d5168d) move composite api into plugin
- [abe9dba](https://github.com/kubedb/neo4j-backup-plugin/commit/abe9dba) update deps
- [b08c7fb](https://github.com/kubedb/neo4j-backup-plugin/commit/b08c7fb) add semanticversion support
- [7d22077](https://github.com/kubedb/neo4j-backup-plugin/commit/7d22077) remove unused func
- [d5cfc76](https://github.com/kubedb/neo4j-backup-plugin/commit/d5cfc76) update deps
- [3cf87a3](https://github.com/kubedb/neo4j-backup-plugin/commit/3cf87a3) cleanup codebase
- [37536fd](https://github.com/kubedb/neo4j-backup-plugin/commit/37536fd) working phase
- [ff238b3](https://github.com/kubedb/neo4j-backup-plugin/commit/ff238b3) upload metadata to cloud
- [334ac63](https://github.com/kubedb/neo4j-backup-plugin/commit/334ac63) Prepare for release v0.3.0-rc.0 (#13)
- [2c124c5](https://github.com/kubedb/neo4j-backup-plugin/commit/2c124c5) working stage
- [c6a9b6a](https://github.com/kubedb/neo4j-backup-plugin/commit/c6a9b6a) Merge pull request #12 from kubedb/fix-restore-script-path
- [85fee4d](https://github.com/kubedb/neo4j-backup-plugin/commit/85fee4d) Fix restore script path file permission issue.
- [9791d29](https://github.com/kubedb/neo4j-backup-plugin/commit/9791d29) fix file permission issue
- [305803b](https://github.com/kubedb/neo4j-backup-plugin/commit/305803b) fix error strings should not be capitalized
- [ec3f548](https://github.com/kubedb/neo4j-backup-plugin/commit/ec3f548) Add Composite Database Support
- [b6daf30](https://github.com/kubedb/neo4j-backup-plugin/commit/b6daf30) Prepare for release v0.2.0-rc.0 (#10)



## [kubedb/oracle](https://github.com/kubedb/oracle)

### [v0.14.0](https://github.com/kubedb/oracle/releases/tag/v0.14.0)

- [b1b924bc](https://github.com/kubedb/oracle/commit/b1b924bc) Prepare for release v0.14.0 (#90)
- [0d5d2b5f](https://github.com/kubedb/oracle/commit/0d5d2b5f) Use Go 1.27, k8s 1.37 & debian:13 (#89)
- [218e4892](https://github.com/kubedb/oracle/commit/218e4892) Sync status.observedGeneration with metadata.generation on spec-only changes
- [e27ca150](https://github.com/kubedb/oracle/commit/e27ca150) Sync Services with spec.serviceTemplates via shared helper (#88)
- [d59bb265](https://github.com/kubedb/oracle/commit/d59bb265) Add SkipBackupPauseAnnotation (#86)
- [8fade5e6](https://github.com/kubedb/oracle/commit/8fade5e6) Prepare for release v0.13.0-rc.2 (#85)
- [43336e9a](https://github.com/kubedb/oracle/commit/43336e9a) Only watch virtual-secrets Secret when the CRD is installed (#83)
- [aa0ac08b](https://github.com/kubedb/oracle/commit/aa0ac08b) Prepare for release v0.13.0-rc.0 (#82)
- [c99cd856](https://github.com/kubedb/oracle/commit/c99cd856) Prepare for release v0.12.0-rc.0 (#81)
- [3a9a9961](https://github.com/kubedb/oracle/commit/3a9a9961) remove extra Error logs (#80)
- [42b512c6](https://github.com/kubedb/oracle/commit/42b512c6) Observer-image-pull-error-fix (#77)
- [84e43918](https://github.com/kubedb/oracle/commit/84e43918) Fix reconfigure wallet (#63)
- [b8b77661](https://github.com/kubedb/oracle/commit/b8b77661) solve multiple image pull secret, handle remove tls (#72)
- [f6bb8508](https://github.com/kubedb/oracle/commit/f6bb8508) Use shared pkg/controller/secret for auth secret (#76)
- [5ec9da67](https://github.com/kubedb/oracle/commit/5ec9da67) Add virtual secret support (#53)
- [5199a198](https://github.com/kubedb/oracle/commit/5199a198) Use shared monitor and appbinding packages (#75)
- [1b447602](https://github.com/kubedb/oracle/commit/1b447602) feat: implement git-sync init container for Oracle (#55)
- [ed013630](https://github.com/kubedb/oracle/commit/ed013630) Set default resource limits before patching petset in vertical scaling (#73)
- [b1819c65](https://github.com/kubedb/oracle/commit/b1819c65) Move deletion logic to apimachinery (#74)
- [d7753f7e](https://github.com/kubedb/oracle/commit/d7753f7e) Merge pull request #70 from kubedb/v2026.7.10-master



## [kubedb/oracle-coordinator](https://github.com/kubedb/oracle-coordinator)

### [v0.14.0](https://github.com/kubedb/oracle-coordinator/releases/tag/v0.14.0)

- [0b425099](https://github.com/kubedb/oracle-coordinator/commit/0b425099) Prepare for release v0.14.0 (#49)
- [e497cad3](https://github.com/kubedb/oracle-coordinator/commit/e497cad3) Use Go 1.27, k8s 1.37 & debian:13 (#48)
- [4a8e34fe](https://github.com/kubedb/oracle-coordinator/commit/4a8e34fe) Prepare for release v0.13.0-rc.2 (#47)
- [bc1a81aa](https://github.com/kubedb/oracle-coordinator/commit/bc1a81aa) Prepare for release v0.13.0-rc.1 (#46)
- [6121bc9f](https://github.com/kubedb/oracle-coordinator/commit/6121bc9f) Prepare for release v0.13.0-rc.0 (#45)
- [1cdbe950](https://github.com/kubedb/oracle-coordinator/commit/1cdbe950) Prepare for release v0.12.0-rc.0 (#44)



## [kubedb/percona-xtradb-coordinator](https://github.com/kubedb/percona-xtradb-coordinator)

### [v0.41.0](https://github.com/kubedb/percona-xtradb-coordinator/releases/tag/v0.41.0)

- [072770e4](https://github.com/kubedb/percona-xtradb-coordinator/commit/072770e4) Prepare for release v0.41.0 (#140)
- [335ed551](https://github.com/kubedb/percona-xtradb-coordinator/commit/335ed551) Prepare for release v0.41.0 (#139)
- [be5ec576](https://github.com/kubedb/percona-xtradb-coordinator/commit/be5ec576) Use Go 1.27, k8s 1.37 & debian:13 (#138)
- [aec6c642](https://github.com/kubedb/percona-xtradb-coordinator/commit/aec6c642) Prepare for release v0.40.0-rc.2 (#137)
- [4fe082df](https://github.com/kubedb/percona-xtradb-coordinator/commit/4fe082df) Prepare for release v0.40.0-rc.1 (#136)
- [1fbe6adf](https://github.com/kubedb/percona-xtradb-coordinator/commit/1fbe6adf) Prepare for release v0.40.0-rc.0 (#135)
- [62a3b59d](https://github.com/kubedb/percona-xtradb-coordinator/commit/62a3b59d) Prepare for release v0.39.0-rc.0 (#134)



## [kubedb/pg-coordinator](https://github.com/kubedb/pg-coordinator)

### [v0.52.0](https://github.com/kubedb/pg-coordinator/releases/tag/v0.52.0)

- [ab62b7c1](https://github.com/kubedb/pg-coordinator/commit/ab62b7c1) Prepare for release v0.52.0 (#284)
- [2c443f87](https://github.com/kubedb/pg-coordinator/commit/2c443f87) Use Go 1.27, k8s 1.37 & debian:13 (#283)
- [8a75c46e](https://github.com/kubedb/pg-coordinator/commit/8a75c46e) DC-DR: no false re-seeds, and write-lock a primary the fence refuses (#282)
- [72c38fbc](https://github.com/kubedb/pg-coordinator/commit/72c38fbc) grpc: consume the CoordinatorManager API from apimachinery (#275)
- [8374a3e7](https://github.com/kubedb/pg-coordinator/commit/8374a3e7) Dc dr review (#261)
- [95d49f96](https://github.com/kubedb/pg-coordinator/commit/95d49f96) Point a cascaded remote replica's coordinator at ordinal 0 (#278)
- [c4078ad7](https://github.com/kubedb/pg-coordinator/commit/c4078ad7) Prepare for release v0.51.0-rc.2 (#277)
- [afd510df](https://github.com/kubedb/pg-coordinator/commit/afd510df) Prepare for release v0.51.0-rc.1 (#276)
- [2fc1edae](https://github.com/kubedb/pg-coordinator/commit/2fc1edae) fix: keep pg_rewind's backup_label; re-seed when its checkpoint is un… (#274)
- [4943ae65](https://github.com/kubedb/pg-coordinator/commit/4943ae65) Prepare for release v0.51.0-rc.0 (#272)
- [dae2e9a7](https://github.com/kubedb/pg-coordinator/commit/dae2e9a7) Prepare for release v0.50.0-rc.0 (#269)
- [a83e4182](https://github.com/kubedb/pg-coordinator/commit/a83e4182) Serve remote replica DR metrics on the raft-metrics port (#268)
- [409a0f41](https://github.com/kubedb/pg-coordinator/commit/409a0f41) Add remote replica mode with pg_rewind and reinitialization support (#257)
- [9e889075](https://github.com/kubedb/pg-coordinator/commit/9e889075) Use pg_tde_rewind and pg_tde_basebackup when TDE is enabled (#264)



## [kubedb/pgpool](https://github.com/kubedb/pgpool)

### [v0.23.0](https://github.com/kubedb/pgpool/releases/tag/v0.23.0)

- [01736d7c](https://github.com/kubedb/pgpool/commit/01736d7c) Prepare for release v0.23.0 (#154)
- [dc861cc9](https://github.com/kubedb/pgpool/commit/dc861cc9) Use Go 1.27, k8s 1.37 & debian:13 (#153)
- [48ef577e](https://github.com/kubedb/pgpool/commit/48ef577e) Sync status.observedGeneration with metadata.generation on spec-only changes
- [53c1c526](https://github.com/kubedb/pgpool/commit/53c1c526) Apply primary serviceTemplate labels to Pgpool Service
- [ba649601](https://github.com/kubedb/pgpool/commit/ba649601) Sync Services with spec.serviceTemplates via shared helper (#152)
- [6924214d](https://github.com/kubedb/pgpool/commit/6924214d) Drop pgpool config validation (#150)
- [fd562a9b](https://github.com/kubedb/pgpool/commit/fd562a9b) fix sync-user auth (#149)
- [c3b78c01](https://github.com/kubedb/pgpool/commit/c3b78c01) sync users: pass credentials as arguments instead of shell text (#148)
- [31123988](https://github.com/kubedb/pgpool/commit/31123988) Fix backend connection budget: drop 2x cancel multiplier, make max_pool default per-child (#147)
- [ca61fed3](https://github.com/kubedb/pgpool/commit/ca61fed3) Prepare for release v0.22.0-rc.2 (#146)
- [8e775fe2](https://github.com/kubedb/pgpool/commit/8e775fe2) Prepare for release v0.22.0-rc.1 (#145)
- [6bf78777](https://github.com/kubedb/pgpool/commit/6bf78777) Prepare for release v0.22.0-rc.0 (#144)
- [9f165e26](https://github.com/kubedb/pgpool/commit/9f165e26) Prepare for release v0.21.0-rc.0 (#143)
- [ea823306](https://github.com/kubedb/pgpool/commit/ea823306) Dont validate pool config until the pg appbinding found (#142)
- [c5071c52](https://github.com/kubedb/pgpool/commit/c5071c52) Fix max_pool validation to check absolute minimum, not per-replica (#141)
- [70094e98](https://github.com/kubedb/pgpool/commit/70094e98) Reduce default max_pool from 15 to 4 (#140)
- [4aff494d](https://github.com/kubedb/pgpool/commit/4aff494d) Requeue if underlying postgres appbinding not found (#139)
- [955ad569](https://github.com/kubedb/pgpool/commit/955ad569) Use shared pkg/controller/secret for auth secret (#138)
- [009328ff](https://github.com/kubedb/pgpool/commit/009328ff) Use shared monitor and appbinding packages (#137)
- [a601d9d6](https://github.com/kubedb/pgpool/commit/a601d9d6) Virtual Secret Ops Support (#136)
- [0b8ea40b](https://github.com/kubedb/pgpool/commit/0b8ea40b) Honor user-provided renewBefore in TLS certificate ops (#121)
- [f9c951b8](https://github.com/kubedb/pgpool/commit/f9c951b8) Move deletion logic to apimachinery (#135)



## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.68.0](https://github.com/kubedb/postgres/releases/tag/v0.68.0)

- [7e1d77cf](https://github.com/kubedb/postgres/commit/7e1d77cf0) Prepare for release v0.68.0 (#945)
- [abc16435](https://github.com/kubedb/postgres/commit/abc16435c) Use Go 1.27, k8s 1.37 & debian:13 (#944)
- [43a09ae4](https://github.com/kubedb/postgres/commit/43a09ae41) Dc dr review (#916)
- [51aba9b2](https://github.com/kubedb/postgres/commit/51aba9b20) Sync status.observedGeneration with metadata.generation on spec-only changes (#941)
- [4659127e](https://github.com/kubedb/postgres/commit/4659127ee) Sync Services with spec.serviceTemplates via shared helper (#940)
- [bed2056e](https://github.com/kubedb/postgres/commit/bed2056e6) Give the archiver sidekicks the DB's custom config, license and pull secrets (#937)
- [03fb17fb](https://github.com/kubedb/postgres/commit/03fb17fbe) Guard against nil ResticStats.Summary and nil LogStats in snapshot status (#936)
- [fd3e3898](https://github.com/kubedb/postgres/commit/fd3e38987) Give the postgres container GOVERNING_SERVICE_DNS for remote replicas (#934)
- [69849fb1](https://github.com/kubedb/postgres/commit/69849fb1e) Generate rotated auth passwords with the same generator as provisioning (#933)
- [2ccb9242](https://github.com/kubedb/postgres/commit/2ccb92429) Prepare for release v0.67.0-rc.2 (#932)
- [7f83ef35](https://github.com/kubedb/postgres/commit/7f83ef35f) Prepare for release v0.67.0-rc.1 (#931)
- [52fab24a](https://github.com/kubedb/postgres/commit/52fab24ae) Project configSecret key user_hba.conf into the config volume (#929)
- [4dde82f7](https://github.com/kubedb/postgres/commit/4dde82f7d) Add Postgres license support for the AppsCode Enterprise distribution (#930)
- [42d19328](https://github.com/kubedb/postgres/commit/42d193289) Prepare for release v0.67.0-rc.0 (#927)
- [32b03ab1](https://github.com/kubedb/postgres/commit/32b03ab18) Generate auth-secret passwords with a symbol class (#925)
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

### [v0.29.0](https://github.com/kubedb/postgres-archiver/releases/tag/v0.29.0)

- [2512b94a](https://github.com/kubedb/postgres-archiver/commit/2512b94a) Prepare for release v0.29.0 (#126)
- [3494ed67](https://github.com/kubedb/postgres-archiver/commit/3494ed67) Use Go 1.27, k8s 1.37 & debian:13 (#125)
- [219d8596](https://github.com/kubedb/postgres-archiver/commit/219d8596) Add 16.9-stream9 archiver image for Postgres Enterprise (#123)
- [cfdfa2f9](https://github.com/kubedb/postgres-archiver/commit/cfdfa2f9) Fix UBI image build failure for 17.9-percona (#122)
- [61113d99](https://github.com/kubedb/postgres-archiver/commit/61113d99) Prepare for release v0.28.0-rc.2 (#120)
- [9de43b9a](https://github.com/kubedb/postgres-archiver/commit/9de43b9a) Prepare for release v0.28.0-rc.1 (#119)
- [33c25dd3](https://github.com/kubedb/postgres-archiver/commit/33c25dd3) Add 17.9-percona to the release build matrix (#118)
- [760aa637](https://github.com/kubedb/postgres-archiver/commit/760aa637) Prepare for release v0.28.0-rc.0 (#117)
- [9ee6f7aa](https://github.com/kubedb/postgres-archiver/commit/9ee6f7aa) Prepare for release v0.27.0-rc.0 (#116)
- [9b64fafc](https://github.com/kubedb/postgres-archiver/commit/9b64fafc) Build the postgres-archiver from the Percona image for 17.9-percona (pg_tde PITR) (#115)
- [4d647cb7](https://github.com/kubedb/postgres-archiver/commit/4d647cb7) Merge pull request #114 from kubedb/v2026.7.10-master



## [kubedb/postgres-csi-snapshotter-plugin](https://github.com/kubedb/postgres-csi-snapshotter-plugin)

### [v0.29.0](https://github.com/kubedb/postgres-csi-snapshotter-plugin/releases/tag/v0.29.0)

- [fcd6fb7a](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/fcd6fb7a) Prepare for release v0.29.0 (#101)
- [4ca3c448](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/4ca3c448) Use Go 1.27, k8s 1.37 & debian:13 (#100)
- [96c9afa4](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/96c9afa4) Prepare for release v0.28.0-rc.2 (#98)
- [a1b4e158](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/a1b4e158) Prepare for release v0.28.0-rc.0 (#96)
- [9c132102](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/9c132102) Prepare for release v0.27.0-rc.0 (#95)
- [683eca1a](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/683eca1a) Merge pull request #94 from kubedb/v2026.7.10-master



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



## [kubedb/qdrant](https://github.com/kubedb/qdrant)

### [v0.9.0](https://github.com/kubedb/qdrant/releases/tag/v0.9.0)

- [8f8732a5](https://github.com/kubedb/qdrant/commit/8f8732a5) Prepare for release v0.9.0 (#66)
- [02a5bf9d](https://github.com/kubedb/qdrant/commit/02a5bf9d) Use Go 1.27, k8s 1.37 & debian:13 (#65)
- [2c6f2c68](https://github.com/kubedb/qdrant/commit/2c6f2c68) Sync status.observedGeneration with metadata.generation on spec-only changes
- [74f3382b](https://github.com/kubedb/qdrant/commit/74f3382b) Sync Services with spec.serviceTemplates via shared helper (#64)
- [5ee354a3](https://github.com/kubedb/qdrant/commit/5ee354a3) Prepare for release v0.8.0-rc.2 (#63)
- [222d8df0](https://github.com/kubedb/qdrant/commit/222d8df0) Prepare for release v0.8.0-rc.1 (#62)
- [4a96ed61](https://github.com/kubedb/qdrant/commit/4a96ed61) Add JWT RBAC Granular Access Control (#61)
- [e1c81c10](https://github.com/kubedb/qdrant/commit/e1c81c10) Prepare for release v0.8.0-rc.0 (#60)
- [c53cd81b](https://github.com/kubedb/qdrant/commit/c53cd81b) Prepare for release v0.7.0-rc.0 (#59)
- [7fcc9d7d](https://github.com/kubedb/qdrant/commit/7fcc9d7d) Adopt shared monitor/appbinding packages (#58)
- [d6fa13f6](https://github.com/kubedb/qdrant/commit/d6fa13f6) Add virtual secret support (#42)
- [5adbcdf0](https://github.com/kubedb/qdrant/commit/5adbcdf0) Set default resource limits before patching petset in vertical scaling (#56)
- [984a3bd7](https://github.com/kubedb/qdrant/commit/984a3bd7) Move deletion logic to apimachinery (#57)



## [kubedb/qdrant-restic-plugin](https://github.com/kubedb/qdrant-restic-plugin)

### [v0.4.0](https://github.com/kubedb/qdrant-restic-plugin/releases/tag/v0.4.0)

- [19db20c](https://github.com/kubedb/qdrant-restic-plugin/commit/19db20c) Prepare for release v0.4.0 (#14)
- [b548cb1](https://github.com/kubedb/qdrant-restic-plugin/commit/b548cb1) Use Go 1.27, k8s 1.37 & debian:13 (#13)
- [099f838](https://github.com/kubedb/qdrant-restic-plugin/commit/099f838) fix restore stats (#9)
- [0bc1f5b](https://github.com/kubedb/qdrant-restic-plugin/commit/0bc1f5b) Prepare for release v0.3.0-rc.2 (#12)
- [0b2e713](https://github.com/kubedb/qdrant-restic-plugin/commit/0b2e713) Prepare for release v0.3.0-rc.1 (#11)
- [815a4cd](https://github.com/kubedb/qdrant-restic-plugin/commit/815a4cd) Replace hub command with gh command in script
- [7a4c0de](https://github.com/kubedb/qdrant-restic-plugin/commit/7a4c0de) Prepare for release v0.3.0-rc.0 (#10)
- [fb288cc](https://github.com/kubedb/qdrant-restic-plugin/commit/fb288cc) Prepare for release v0.2.0-rc.0 (#8)
- [34a99ba](https://github.com/kubedb/qdrant-restic-plugin/commit/34a99ba) Merge pull request #7 from kubedb/v2026.7.10-master



## [kubedb/rabbitmq](https://github.com/kubedb/rabbitmq)

### [v0.23.0](https://github.com/kubedb/rabbitmq/releases/tag/v0.23.0)

- [27282444](https://github.com/kubedb/rabbitmq/commit/27282444) Prepare for release v0.23.0 (#159)
- [21e71364](https://github.com/kubedb/rabbitmq/commit/21e71364) Use Go 1.27, k8s 1.37 & debian:13 (#158)
- [85bec1d8](https://github.com/kubedb/rabbitmq/commit/85bec1d8) Sync status.observedGeneration with metadata.generation on spec-only changes
- [5eee7c97](https://github.com/kubedb/rabbitmq/commit/5eee7c97) Sync Services with spec.serviceTemplates via shared helper (#157)
- [1874c2f9](https://github.com/kubedb/rabbitmq/commit/1874c2f9) Prepare for release v0.22.0-rc.2 (#156)
- [86a6bb4b](https://github.com/kubedb/rabbitmq/commit/86a6bb4b) Prepare for release v0.22.0-rc.1 (#155)
- [69b2974c](https://github.com/kubedb/rabbitmq/commit/69b2974c) Prepare for release v0.22.0-rc.0 (#154)
- [8d7aa943](https://github.com/kubedb/rabbitmq/commit/8d7aa943) Add Management AppBinding (#152)
- [68f62a51](https://github.com/kubedb/rabbitmq/commit/68f62a51) Prepare for release v0.21.0-rc.0 (#153)
- [e4fe45ba](https://github.com/kubedb/rabbitmq/commit/e4fe45ba) log fixed (#151)
- [39ce0108](https://github.com/kubedb/rabbitmq/commit/39ce0108) Use shared pkg/controller/secret for auth secret (#150)
- [f83d3abd](https://github.com/kubedb/rabbitmq/commit/f83d3abd) Use shared monitor and appbinding packages (#149)
- [ed7a49d4](https://github.com/kubedb/rabbitmq/commit/ed7a49d4) Add virtual secret support (#134)
- [7a7d559a](https://github.com/kubedb/rabbitmq/commit/7a7d559a) Set default resource limits before patching petset in vertical scaling
- [91a1006f](https://github.com/kubedb/rabbitmq/commit/91a1006f) Honor user-provided renewBefore in TLS certificate ops (#135)
- [a9bc44a5](https://github.com/kubedb/rabbitmq/commit/a9bc44a5) Move deletion logic to apimachinery (#148)



## [kubedb/redis](https://github.com/kubedb/redis)

### [v0.61.0](https://github.com/kubedb/redis/releases/tag/v0.61.0)

- [7f992dcd](https://github.com/kubedb/redis/commit/7f992dcd0) Prepare for release v0.61.0 (#682)
- [2d6793d3](https://github.com/kubedb/redis/commit/2d6793d31) Use Go 1.27, k8s 1.37 & debian:13 (#681)
- [a5d29444](https://github.com/kubedb/redis/commit/a5d294444) Switch master before restart (#680)
- [6f06f734](https://github.com/kubedb/redis/commit/6f06f7346) Add branched mode for KubeDB Courier Branch (#662)
- [6bff789e](https://github.com/kubedb/redis/commit/6bff789e0) Sync status.observedGeneration with metadata.generation on spec-only changes
- [b5e34eba](https://github.com/kubedb/redis/commit/b5e34eba8) Sync Services with spec.serviceTemplates via shared helper (#679)
- [03973ae7](https://github.com/kubedb/redis/commit/03973ae75) Support ip to ip conversion in announce ops request (#673)
- [8b388b37](https://github.com/kubedb/redis/commit/8b388b377) Prepare for release v0.60.0-rc.2 (#678)
- [282f64f7](https://github.com/kubedb/redis/commit/282f64f70) Prepare for release v0.60.0-rc.1 (#677)
- [b505761f](https://github.com/kubedb/redis/commit/b505761f9) Prepare for release v0.60.0-rc.0 (#676)
- [568642d9](https://github.com/kubedb/redis/commit/568642d99) Prepare for release v0.59.0-rc.0 (#675)
- [4479fd1b](https://github.com/kubedb/redis/commit/4479fd1b3) ACL Custom secret add (#668)
- [628b529d](https://github.com/kubedb/redis/commit/628b529db) Adopt shared secret package from apimachinery (#674)
- [cdf520da](https://github.com/kubedb/redis/commit/cdf520da5) Adopt shared monitor/appbinding packages from apimachinery (#672)
- [92957c09](https://github.com/kubedb/redis/commit/92957c097) Virtual Secret Ops Support (#670)
- [ce19a258](https://github.com/kubedb/redis/commit/ce19a2589) Set default resource limits before patching petset in vertical scaling
- [11ca8d63](https://github.com/kubedb/redis/commit/11ca8d636) Move deletion logic to apimachinery (#671)
- [bbf192dd](https://github.com/kubedb/redis/commit/bbf192ddb) Merge pull request #667 from kubedb/v2026.7.10-master



## [kubedb/redis-coordinator](https://github.com/kubedb/redis-coordinator)

### [v0.47.0](https://github.com/kubedb/redis-coordinator/releases/tag/v0.47.0)

- [3c23b356](https://github.com/kubedb/redis-coordinator/commit/3c23b356) Prepare for release v0.47.0 (#172)
- [39eb22c5](https://github.com/kubedb/redis-coordinator/commit/39eb22c5) Use Go 1.27, k8s 1.37 & debian:13 (#171)
- [ff09aab0](https://github.com/kubedb/redis-coordinator/commit/ff09aab0) Prepare for release v0.46.0-rc.2 (#170)
- [1492448b](https://github.com/kubedb/redis-coordinator/commit/1492448b) Prepare for release v0.46.0-rc.1 (#169)
- [c175fe00](https://github.com/kubedb/redis-coordinator/commit/c175fe00) Prepare for release v0.46.0-rc.0 (#168)
- [c88db39d](https://github.com/kubedb/redis-coordinator/commit/c88db39d) Prepare for release v0.45.0-rc.0 (#167)



## [kubedb/replication-mode-detector](https://github.com/kubedb/replication-mode-detector)

### [v0.55.0](https://github.com/kubedb/replication-mode-detector/releases/tag/v0.55.0)

- [fcad4c5e](https://github.com/kubedb/replication-mode-detector/commit/fcad4c5e) Prepare for release v0.55.0 (#334)
- [1e73fe3f](https://github.com/kubedb/replication-mode-detector/commit/1e73fe3f) Use Go 1.27, k8s 1.37 & debian:13 (#333)
- [a4317b50](https://github.com/kubedb/replication-mode-detector/commit/a4317b50) Prepare for release v0.54.0-rc.2 (#332)
- [ec8486cf](https://github.com/kubedb/replication-mode-detector/commit/ec8486cf) Prepare for release v0.54.0-rc.1 (#331)
- [637dd051](https://github.com/kubedb/replication-mode-detector/commit/637dd051) Prepare for release v0.54.0-rc.0 (#330)
- [2835220a](https://github.com/kubedb/replication-mode-detector/commit/2835220a) Prepare for release v0.53.0-rc.0 (#329)



## [kubedb/singlestore](https://github.com/kubedb/singlestore)

### [v0.23.0](https://github.com/kubedb/singlestore/releases/tag/v0.23.0)

- [d03ff036](https://github.com/kubedb/singlestore/commit/d03ff036) Prepare for release v0.23.0 (#150)
- [797a3f2f](https://github.com/kubedb/singlestore/commit/797a3f2f) Use Go 1.27, k8s 1.37 & debian:13 (#149)
- [8b33402b](https://github.com/kubedb/singlestore/commit/8b33402b) Sync status.observedGeneration with metadata.generation on spec-only changes
- [5947b4ce](https://github.com/kubedb/singlestore/commit/5947b4ce) Sync Services with spec.serviceTemplates via shared helper (#148)
- [e770aa63](https://github.com/kubedb/singlestore/commit/e770aa63) Prepare for release v0.22.0-rc.2 (#147)
- [894f6c05](https://github.com/kubedb/singlestore/commit/894f6c05) Prepare for release v0.22.0-rc.1 (#146)
- [72bc1182](https://github.com/kubedb/singlestore/commit/72bc1182) Only watch virtual-secrets Secret when the CRD is installed (#145)
- [6f9da672](https://github.com/kubedb/singlestore/commit/6f9da672) Prepare for release v0.22.0-rc.0 (#144)
- [1787b18b](https://github.com/kubedb/singlestore/commit/1787b18b) Prepare for release v0.21.0-rc.0 (#143)
- [d0ac823e](https://github.com/kubedb/singlestore/commit/d0ac823e) Use shared apimachinery secret package (#142)
- [264909c1](https://github.com/kubedb/singlestore/commit/264909c1) Use shared monitor and appbinding packages (#141)
- [7ff8879b](https://github.com/kubedb/singlestore/commit/7ff8879b) Add virtual secret support (#123)
- [ae4ba9ce](https://github.com/kubedb/singlestore/commit/ae4ba9ce) Move deletion logic to apimachinery (#140)



## [kubedb/singlestore-restic-plugin](https://github.com/kubedb/singlestore-restic-plugin)

### [v0.26.0](https://github.com/kubedb/singlestore-restic-plugin/releases/tag/v0.26.0)

- [58f32237](https://github.com/kubedb/singlestore-restic-plugin/commit/58f32237) Prepare for release v0.26.0 (#99)
- [4f62faae](https://github.com/kubedb/singlestore-restic-plugin/commit/4f62faae) Use Go 1.27, k8s 1.37 & debian:13 (#98)
- [f5db3d86](https://github.com/kubedb/singlestore-restic-plugin/commit/f5db3d86) Prepare for release v0.25.0-rc.2 (#97)
- [aca72da8](https://github.com/kubedb/singlestore-restic-plugin/commit/aca72da8) Prepare for release v0.25.0-rc.1 (#96)
- [914e097c](https://github.com/kubedb/singlestore-restic-plugin/commit/914e097c) Prepare for release v0.25.0-rc.0 (#95)
- [0e259058](https://github.com/kubedb/singlestore-restic-plugin/commit/0e259058) Prepare for release v0.24.0-rc.0 (#94)
- [67f1a95e](https://github.com/kubedb/singlestore-restic-plugin/commit/67f1a95e) Fix --ssl-ca being silently dropped from the client command (#93)
- [f50bc94f](https://github.com/kubedb/singlestore-restic-plugin/commit/f50bc94f) Add Virtual Secret Support (#90)
- [1fe1b17d](https://github.com/kubedb/singlestore-restic-plugin/commit/1fe1b17d) Merge pull request #92 from kubedb/v2026.7.10-master



## [kubedb/solr](https://github.com/kubedb/solr)

### [v0.23.0](https://github.com/kubedb/solr/releases/tag/v0.23.0)

- [fc4f6445](https://github.com/kubedb/solr/commit/fc4f6445) Prepare for release v0.23.0 (#162)
- [1517ce28](https://github.com/kubedb/solr/commit/1517ce28) Use Go 1.27, k8s 1.37 & debian:13 (#161)
- [db614a64](https://github.com/kubedb/solr/commit/db614a64) Sync status.observedGeneration with metadata.generation on spec-only changes
- [193876ae](https://github.com/kubedb/solr/commit/193876ae) Apply primary serviceTemplate labels to Solr Service
- [61f14f92](https://github.com/kubedb/solr/commit/61f14f92) Sync Services with spec.serviceTemplates via shared helper (#160)
- [e5fc736d](https://github.com/kubedb/solr/commit/e5fc736d) Add Backup Support for Multiple S3/GCS Backend (#157)
- [e416a480](https://github.com/kubedb/solr/commit/e416a480) Prepare for release v0.22.0-rc.2 (#159)
- [f6b10d41](https://github.com/kubedb/solr/commit/f6b10d41) Prepare for release v0.22.0-rc.1 (#158)
- [a49c4523](https://github.com/kubedb/solr/commit/a49c4523) Extend Reconfigure Ops for Backup Creds (#151)
- [df17e445](https://github.com/kubedb/solr/commit/df17e445) Prepare for release v0.22.0-rc.0 (#156)
- [25754c5f](https://github.com/kubedb/solr/commit/25754c5f) Prepare for release v0.21.0-rc.0 (#155)
- [0afd2d73](https://github.com/kubedb/solr/commit/0afd2d73) API fix [Unblock RC] (#154)
- [32dfb2d9](https://github.com/kubedb/solr/commit/32dfb2d9) Adopt shared secret package from apimachinery (#152)
- [22d3d42e](https://github.com/kubedb/solr/commit/22d3d42e) Adopt shared monitor/appbinding packages from apimachinery (#150)
- [dbaaa4f9](https://github.com/kubedb/solr/commit/dbaaa4f9) Add virtual secret support (#131)
- [5f23c1f2](https://github.com/kubedb/solr/commit/5f23c1f2) Set default resource limits before patching petset in vertical scaling (#147)
- [a0c4213c](https://github.com/kubedb/solr/commit/a0c4213c) Honor user-provided renewBefore in TLS certificate ops (#146)
- [cd576f42](https://github.com/kubedb/solr/commit/cd576f42) Move deletion logic to apimachinery (#148)



## [kubedb/tests](https://github.com/kubedb/tests)

### [v0.53.0](https://github.com/kubedb/tests/releases/tag/v0.53.0)

- [38fe361f](https://github.com/kubedb/tests/commit/38fe361f4) Prepare for release v0.53.0 (#558)
- [1c8ddbd4](https://github.com/kubedb/tests/commit/1c8ddbd46) Use Go 1.27, k8s 1.37 & debian:13 (#557)
- [fc7d163f](https://github.com/kubedb/tests/commit/fc7d163f0) Prepare for release v0.52.0-rc.2 (#555)
- [b5d2167e](https://github.com/kubedb/tests/commit/b5d2167e1) Prepare for release v0.52.0-rc.1 (#554)
- [f457453e](https://github.com/kubedb/tests/commit/f457453e8) Prepare for release v0.52.0-rc.0 (#552)
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

### [v0.9.0](https://github.com/kubedb/weaviate/releases/tag/v0.9.0)

- [91024bd2](https://github.com/kubedb/weaviate/commit/91024bd2) Prepare for release v0.9.0 (#65)
- [70769f06](https://github.com/kubedb/weaviate/commit/70769f06) Use Go 1.27, k8s 1.37 & debian:13 (#64)
- [7a9ade04](https://github.com/kubedb/weaviate/commit/7a9ade04) Sync status.observedGeneration with metadata.generation on spec-only changes
- [74aa21be](https://github.com/kubedb/weaviate/commit/74aa21be) Sync Services with spec.serviceTemplates via shared helper (#63)
- [bdd46c25](https://github.com/kubedb/weaviate/commit/bdd46c25) Prepare for release v0.8.0-rc.2 (#62)
- [876f7a88](https://github.com/kubedb/weaviate/commit/876f7a88) Prepare for release v0.8.0-rc.1 (#61)
- [d3cf3289](https://github.com/kubedb/weaviate/commit/d3cf3289) Prepare for release v0.8.0-rc.0 (#60)
- [d445e431](https://github.com/kubedb/weaviate/commit/d445e431) Prepare for release v0.7.0-rc.0 (#59)
- [c87d4ab5](https://github.com/kubedb/weaviate/commit/c87d4ab5) Add update-version ops (#56)
- [73297e3d](https://github.com/kubedb/weaviate/commit/73297e3d) Use shared monitor and appbinding packages (#57)
- [c0de6cde](https://github.com/kubedb/weaviate/commit/c0de6cde) Add virtual secret support (#36)
- [52ae615f](https://github.com/kubedb/weaviate/commit/52ae615f) Set default resource limits before patching petset in vertical scaling (#54)
- [47f19de7](https://github.com/kubedb/weaviate/commit/47f19de7) Move deletion logic to apimachinery (#55)



## [kubedb/zookeeper](https://github.com/kubedb/zookeeper)

### [v0.23.0](https://github.com/kubedb/zookeeper/releases/tag/v0.23.0)

- [04550f83](https://github.com/kubedb/zookeeper/commit/04550f83) Prepare for release v0.23.0 (#145)
- [aaeeb941](https://github.com/kubedb/zookeeper/commit/aaeeb941) Use Go 1.27, k8s 1.37 & debian:13 (#144)
- [d0e5cb33](https://github.com/kubedb/zookeeper/commit/d0e5cb33) Sync status.observedGeneration with metadata.generation on spec-only changes
- [c7045da6](https://github.com/kubedb/zookeeper/commit/c7045da6) Sync Services with spec.serviceTemplates via shared helper (#143)
- [4ef9e89a](https://github.com/kubedb/zookeeper/commit/4ef9e89a) Prepare for release v0.22.0-rc.2 (#142)
- [c588db00](https://github.com/kubedb/zookeeper/commit/c588db00) Prepare for release v0.22.0-rc.1 (#141)
- [b6b631e9](https://github.com/kubedb/zookeeper/commit/b6b631e9) Prepare for release v0.22.0-rc.0 (#140)
- [1b6e46fa](https://github.com/kubedb/zookeeper/commit/1b6e46fa) Prepare for release v0.21.0-rc.0 (#139)
- [fee971ca](https://github.com/kubedb/zookeeper/commit/fee971ca) Adopt shared secret package from apimachinery (#138)
- [6594c59e](https://github.com/kubedb/zookeeper/commit/6594c59e) Adopt shared monitor/appbinding packages from apimachinery (#137)
- [ef611f33](https://github.com/kubedb/zookeeper/commit/ef611f33) Add virtual secret support (#123)
- [76c37064](https://github.com/kubedb/zookeeper/commit/76c37064) Set default resource limits before patching petset in vertical scaling
- [d39eb3cd](https://github.com/kubedb/zookeeper/commit/d39eb3cd) Move deletion logic to apimachinery (#136)



## [kubedb/zookeeper-restic-plugin](https://github.com/kubedb/zookeeper-restic-plugin)

### [v0.23.0](https://github.com/kubedb/zookeeper-restic-plugin/releases/tag/v0.23.0)

- [133df217](https://github.com/kubedb/zookeeper-restic-plugin/commit/133df217) Prepare for release v0.23.0 (#83)
- [e742966f](https://github.com/kubedb/zookeeper-restic-plugin/commit/e742966f) Use Go 1.27, k8s 1.37 & debian:13 (#82)
- [48526261](https://github.com/kubedb/zookeeper-restic-plugin/commit/48526261) Prepare for release v0.22.0-rc.2 (#81)
- [4d6e385f](https://github.com/kubedb/zookeeper-restic-plugin/commit/4d6e385f) Prepare for release v0.22.0-rc.1 (#80)
- [a0e15552](https://github.com/kubedb/zookeeper-restic-plugin/commit/a0e15552) Prepare for release v0.22.0-rc.0 (#79)
- [c31c75e2](https://github.com/kubedb/zookeeper-restic-plugin/commit/c31c75e2) Prepare for release v0.21.0-rc.0 (#78)
- [9f1474e8](https://github.com/kubedb/zookeeper-restic-plugin/commit/9f1474e8) Add Virtual Secret Support (#75)
- [f9a0c8f0](https://github.com/kubedb/zookeeper-restic-plugin/commit/f9a0c8f0) Merge pull request #77 from kubedb/v2026.7.10-master



