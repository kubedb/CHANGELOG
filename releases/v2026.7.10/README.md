# KubeDB v2026.7.10 (2026-07-11)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.66.0](https://github.com/kubedb/apimachinery/releases/tag/v0.66.0)

- [e40ad552](https://github.com/kubedb/apimachinery/commit/e40ad5529) Modernize golangci-lint config (#1826)
- [e0b3004f](https://github.com/kubedb/apimachinery/commit/e0b3004fa) Update sidekick deps (#1827)
- [ca218a64](https://github.com/kubedb/apimachinery/commit/ca218a648) Update for release KubeStash@v2026.7.10 (#1825)
- [a9ed525b](https://github.com/kubedb/apimachinery/commit/a9ed525b6) run make fmt (#1823)
- [c85055d3](https://github.com/kubedb/apimachinery/commit/c85055d3a) ACL secret updation (#1822)
- [bad1baeb](https://github.com/kubedb/apimachinery/commit/bad1baeb0) Disallow InPlace vertical scaling mode for Neo4j (#1819)
- [9b75e234](https://github.com/kubedb/apimachinery/commit/9b75e2347) Fix Webhook for Virtual Secret (#1817)
- [5c452059](https://github.com/kubedb/apimachinery/commit/5c4520591) Don't allow updating version between distro (#1821)
- [fa18e712](https://github.com/kubedb/apimachinery/commit/fa18e712f) Restrict cross-baseOS version upgrades for Postgres (#1781)
- [0ea56fe9](https://github.com/kubedb/apimachinery/commit/0ea56fe94) Added app-binding in mssqlserver (#1820)
- [14397c47](https://github.com/kubedb/apimachinery/commit/14397c47b) fix etcd service name (#1818)
- [210cad0a](https://github.com/kubedb/apimachinery/commit/210cad0ad) Add Clickhouse Shard Scaling Support (#1784)
- [00be056e](https://github.com/kubedb/apimachinery/commit/00be056e2) Add ReconfigureTLS ops type and TLS spec to OracleOpsRequest (#1791)
- [21bd385d](https://github.com/kubedb/apimachinery/commit/21bd385dc) changed lederElection period (#1799)
- [233f90be](https://github.com/kubedb/apimachinery/commit/233f90be2) Add MongoDB distro option
- [75751efe](https://github.com/kubedb/apimachinery/commit/75751efe9) Add MilvusBind, QdrantBind, WeaviateBind wrappers (#1809)
- [cc1005a9](https://github.com/kubedb/apimachinery/commit/cc1005a99) Add VerticalScalingMode to all vertical scaling specs (#1808)
- [dd7736f0](https://github.com/kubedb/apimachinery/commit/dd7736f01) Add HanaDB volume permission option (#1802)
- [ac0d35e3](https://github.com/kubedb/apimachinery/commit/ac0d35e3d) Add PostgresSynchronousReplicationSpec for configurable sync replication (#1782)
- [c8af2eb6](https://github.com/kubedb/apimachinery/commit/c8af2eb6e) Fix Zookeeper Ops (#1788)
- [3e7d7558](https://github.com/kubedb/apimachinery/commit/3e7d75582) Set default container resizePolicy for all databases (#1789)
- [df643d84](https://github.com/kubedb/apimachinery/commit/df643d84b) Fix pgpool webhook build after ReconfigurationSpec embed change (#1816)
- [e14fe41d](https://github.com/kubedb/apimachinery/commit/e14fe41d9) Add Weaviate Monitoring Support (#1811)
- [d78e2c2e](https://github.com/kubedb/apimachinery/commit/d78e2c2e2) Improve Branch APIs and Status for human redable + fix duck typing ci (#1813)
- [779aee46](https://github.com/kubedb/apimachinery/commit/779aee469) Document make fmt requirement before opening PRs (#1814)
- [c3375004](https://github.com/kubedb/apimachinery/commit/c33750041) Register Migration and MigrationList to scheme
- [e0f21be8](https://github.com/kubedb/apimachinery/commit/e0f21be8f) Use db specific migration kind (#1812)
- [31ad8176](https://github.com/kubedb/apimachinery/commit/31ad81768) Add MSSQL Server migrator API types (#1742)
- [a5cc9682](https://github.com/kubedb/apimachinery/commit/a5cc9682d) courier: add Branch spec.target.issuerRef for branch TLS (#1810)
- [1476d578](https://github.com/kubedb/apimachinery/commit/1476d5788) Add courier.kubedb.com API group (rename migrator to courier) (#1807)
- [8cc4a11b](https://github.com/kubedb/apimachinery/commit/8cc4a11bd) Enable TLS in Backup Port (#1783)
- [79935675](https://github.com/kubedb/apimachinery/commit/799356756) changed lederElection period (#1785)
- [4cd0fc34](https://github.com/kubedb/apimachinery/commit/4cd0fc34c) Fix Cassandra VolumeExpansion Webhook (#1786)



## [kubedb/clickhouse](https://github.com/kubedb/clickhouse)

### [v0.21.0](https://github.com/kubedb/clickhouse/releases/tag/v0.21.0)

- [2a420dd6](https://github.com/kubedb/clickhouse/commit/2a420dd6) Prepare for release v0.21.0 (#125)
- [fbc3c3d6](https://github.com/kubedb/clickhouse/commit/fbc3c3d6) Modernize golangci-lint config (#124)
- [972ddd22](https://github.com/kubedb/clickhouse/commit/972ddd22) Add InPlace mode to vertical scaling (#122)
- [fccd8b2b](https://github.com/kubedb/clickhouse/commit/fccd8b2b) Add Shard Scaling Support (#119)
- [40de00ae](https://github.com/kubedb/clickhouse/commit/40de00ae) as (#123)
- [3b4ca7b6](https://github.com/kubedb/clickhouse/commit/3b4ca7b6) Add Archiver Support (#99)



## [kubedb/clickhouse-backup-plugin](https://github.com/kubedb/clickhouse-backup-plugin)

### [v0.3.0](https://github.com/kubedb/clickhouse-backup-plugin/releases/tag/v0.3.0)

- [46d0a5cf](https://github.com/kubedb/clickhouse-backup-plugin/commit/46d0a5cf) Prepare for release v0.3.0 (#30)
- [1b314899](https://github.com/kubedb/clickhouse-backup-plugin/commit/1b314899) Add golangci-lint config (#29)
- [e06cf170](https://github.com/kubedb/clickhouse-backup-plugin/commit/e06cf170) Add Incremental backup (#19)



## [kubedb/crd-manager](https://github.com/kubedb/crd-manager)

### [v0.21.0](https://github.com/kubedb/crd-manager/releases/tag/v0.21.0)

- [ef77e885](https://github.com/kubedb/crd-manager/commit/ef77e885) Prepare for release v0.21.0 (#148)
- [1257a1c4](https://github.com/kubedb/crd-manager/commit/1257a1c4) Rename migrator to courier CRDs (#147)
- [e3df0cbf](https://github.com/kubedb/crd-manager/commit/e3df0cbf) Modernize golangci-lint config (#146)



## [kubedb/dashboard-restic-plugin](https://github.com/kubedb/dashboard-restic-plugin)

### [v0.24.0](https://github.com/kubedb/dashboard-restic-plugin/releases/tag/v0.24.0)

- [2d5d0a3c](https://github.com/kubedb/dashboard-restic-plugin/commit/2d5d0a3c) Prepare for release v0.24.0 (#83)
- [3e204216](https://github.com/kubedb/dashboard-restic-plugin/commit/3e204216) Modernize golangci-lint config (#82)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.21.0](https://github.com/kubedb/db-client-go/releases/tag/v0.21.0)

- [bc3a25ce](https://github.com/kubedb/db-client-go/commit/bc3a25ce) Prepare for release v0.21.0 (#255)
- [fec3c231](https://github.com/kubedb/db-client-go/commit/fec3c231) Modernize golangci-lint config (#254)
- [a3da77c5](https://github.com/kubedb/db-client-go/commit/a3da77c5) add aerospike client (#251)
- [144cd45a](https://github.com/kubedb/db-client-go/commit/144cd45a) Add New function For Neo4j (#252)
- [4b2ca834](https://github.com/kubedb/db-client-go/commit/4b2ca834) Add Qdrant Recover Snapshot Reader Function (#253)



## [kubedb/db2](https://github.com/kubedb/db2)

### [v0.7.0](https://github.com/kubedb/db2/releases/tag/v0.7.0)

- [78ad3099](https://github.com/kubedb/db2/commit/78ad3099) Prepare for release v0.7.0 (#35)
- [538b3685](https://github.com/kubedb/db2/commit/538b3685) Modernize golangci-lint config (#34)



## [kubedb/db2-coordinator](https://github.com/kubedb/db2-coordinator)

### [v0.7.0](https://github.com/kubedb/db2-coordinator/releases/tag/v0.7.0)

- [3a80ff3](https://github.com/kubedb/db2-coordinator/commit/3a80ff3) Prepare for release v0.7.0 (#16)
- [5dc64ab](https://github.com/kubedb/db2-coordinator/commit/5dc64ab) Modernize golangci-lint config (#15)



## [kubedb/documentdb](https://github.com/kubedb/documentdb)

### [v0.3.0](https://github.com/kubedb/documentdb/releases/tag/v0.3.0)

- [ba6ac93b](https://github.com/kubedb/documentdb/commit/ba6ac93b) Prepare for release v0.3.0 (#39)
- [4fc3b678](https://github.com/kubedb/documentdb/commit/4fc3b678) Modernize golangci-lint config (#38)
- [bd9d564e](https://github.com/kubedb/documentdb/commit/bd9d564e) Run gofmt with updated golang-dev toolchain (#37)
- [86fce11f](https://github.com/kubedb/documentdb/commit/86fce11f) Add InPlace mode to vertical scaling (#36)
- [3f92d8c2](https://github.com/kubedb/documentdb/commit/3f92d8c2) updated documentdb deps (#34)
- [9d7aee2c](https://github.com/kubedb/documentdb/commit/9d7aee2c) fixed termination time & health check issue (#30)



## [kubedb/documentdb-coordinator](https://github.com/kubedb/documentdb-coordinator)

### [v0.2.0](https://github.com/kubedb/documentdb-coordinator/releases/tag/v0.2.0)

- [2d44eda](https://github.com/kubedb/documentdb-coordinator/commit/2d44eda) Prepare for release v0.2.0
- [dcfbce6](https://github.com/kubedb/documentdb-coordinator/commit/dcfbce6) Add golangci-lint config (#9)



## [kubedb/elasticsearch-restic-plugin](https://github.com/kubedb/elasticsearch-restic-plugin)

### [v0.29.0](https://github.com/kubedb/elasticsearch-restic-plugin/releases/tag/v0.29.0)

- [1b29f94d](https://github.com/kubedb/elasticsearch-restic-plugin/commit/1b29f94d) Prepare for release v0.29.0 (#106)
- [91b6fb9f](https://github.com/kubedb/elasticsearch-restic-plugin/commit/91b6fb9f) Modernize golangci-lint config (#105)



## [kubedb/hanadb](https://github.com/kubedb/hanadb)

### [v0.7.0](https://github.com/kubedb/hanadb/releases/tag/v0.7.0)

- [c293b3af](https://github.com/kubedb/hanadb/commit/c293b3af) Prepare for release v0.7.0 (#53)
- [5309a61e](https://github.com/kubedb/hanadb/commit/5309a61e) Modernize golangci-lint config (#52)
- [038da9ea](https://github.com/kubedb/hanadb/commit/038da9ea) Run gofmt with updated golang-dev toolchain (#51)
- [95713bbd](https://github.com/kubedb/hanadb/commit/95713bbd) Add InPlace mode to vertical scaling (#50)
- [fbc510b2](https://github.com/kubedb/hanadb/commit/fbc510b2) Add backup pause/resume support for ops requests (#48)



## [kubedb/ignite](https://github.com/kubedb/ignite)

### [v0.13.0](https://github.com/kubedb/ignite/releases/tag/v0.13.0)

- [cc26dcb4](https://github.com/kubedb/ignite/commit/cc26dcb4) Prepare for release v0.13.0 (#66)
- [7fc3f493](https://github.com/kubedb/ignite/commit/7fc3f493) Modernize golangci-lint config (#65)
- [eee09fbe](https://github.com/kubedb/ignite/commit/eee09fbe) Run gofmt with updated golang-dev toolchain (#64)
- [161f7c48](https://github.com/kubedb/ignite/commit/161f7c48) Add InPlace mode to vertical scaling (#63)



## [kubedb/kubedb-manifest-plugin](https://github.com/kubedb/kubedb-manifest-plugin)

### [v0.29.0](https://github.com/kubedb/kubedb-manifest-plugin/releases/tag/v0.29.0)

- [29af77f5](https://github.com/kubedb/kubedb-manifest-plugin/commit/29af77f5) Prepare for release v0.29.0 (#140)
- [42eaca97](https://github.com/kubedb/kubedb-manifest-plugin/commit/42eaca97) Modernize golangci-lint config (#139)
- [70ae44b0](https://github.com/kubedb/kubedb-manifest-plugin/commit/70ae44b0) Add ClickHouse Manifest (#129)



## [kubedb/kubedb-verifier](https://github.com/kubedb/kubedb-verifier)

### [v0.17.0](https://github.com/kubedb/kubedb-verifier/releases/tag/v0.17.0)

- [9ed0acba](https://github.com/kubedb/kubedb-verifier/commit/9ed0acba) Prepare for release v0.17.0 (#57)
- [11fc3fb9](https://github.com/kubedb/kubedb-verifier/commit/11fc3fb9) Modernize golangci-lint config (#56)



## [kubedb/memcached](https://github.com/kubedb/memcached)

### [v0.59.0](https://github.com/kubedb/memcached/releases/tag/v0.59.0)

- [d7c6e509](https://github.com/kubedb/memcached/commit/d7c6e5099) Prepare for release v0.59.0 (#549)
- [c678218d](https://github.com/kubedb/memcached/commit/c678218d3) Modernize golangci-lint config (#548)
- [7b058c67](https://github.com/kubedb/memcached/commit/7b058c67b) Run gofmt with updated golang-dev toolchain (#547)
- [732e96e8](https://github.com/kubedb/memcached/commit/732e96e85) Add InPlace mode to vertical scaling (#546)



## [kubedb/mongodb](https://github.com/kubedb/mongodb)

### [v0.59.0](https://github.com/kubedb/mongodb/releases/tag/v0.59.0)

- [2b61b507](https://github.com/kubedb/mongodb/commit/2b61b5070) Prepare for release v0.59.0
- [5612cb7a](https://github.com/kubedb/mongodb/commit/5612cb7a4) Modernize golangci-lint config (#776)
- [5e4ffce3](https://github.com/kubedb/mongodb/commit/5e4ffce33) Support InPlace mode for vertical scaling (#773)
- [0d548d47](https://github.com/kubedb/mongodb/commit/0d548d473) Skip duplicate --auth flag for mongodb-community-server images (#775)



## [kubedb/mssqlserver](https://github.com/kubedb/mssqlserver)

### [v0.21.0](https://github.com/kubedb/mssqlserver/releases/tag/v0.21.0)

- [b45fc246](https://github.com/kubedb/mssqlserver/commit/b45fc246) Prepare for release v0.21.0 (#152)
- [ce78720f](https://github.com/kubedb/mssqlserver/commit/ce78720f) Modernize golangci-lint config (#151)
- [ba6e13c6](https://github.com/kubedb/mssqlserver/commit/ba6e13c6) Run gofmt with updated golang-dev toolchain (#150)
- [c6a7e0bd](https://github.com/kubedb/mssqlserver/commit/c6a7e0bd) Add InPlace mode to vertical scaling (#149)
- [6af75d70](https://github.com/kubedb/mssqlserver/commit/6af75d70) Add backup pause/resume support for ops requests (#146)



## [kubedb/mssqlserver-walg-plugin](https://github.com/kubedb/mssqlserver-walg-plugin)

### [v0.20.0](https://github.com/kubedb/mssqlserver-walg-plugin/releases/tag/v0.20.0)

- [6ca5fb8](https://github.com/kubedb/mssqlserver-walg-plugin/commit/6ca5fb8) Prepare for release v0.20.0 (#66)
- [cf72afd](https://github.com/kubedb/mssqlserver-walg-plugin/commit/cf72afd) Modernize golangci-lint config (#65)



## [kubedb/mysql-archiver](https://github.com/kubedb/mysql-archiver)

### [v0.27.0](https://github.com/kubedb/mysql-archiver/releases/tag/v0.27.0)

- [0b5887b8](https://github.com/kubedb/mysql-archiver/commit/0b5887b8) Prepare for release v0.27.0 (#112)
- [633ec559](https://github.com/kubedb/mysql-archiver/commit/633ec559) Modernize golangci-lint config (#111)



## [kubedb/mysql-coordinator](https://github.com/kubedb/mysql-coordinator)

### [v0.44.0](https://github.com/kubedb/mysql-coordinator/releases/tag/v0.44.0)

- [a7f57425](https://github.com/kubedb/mysql-coordinator/commit/a7f57425) Prepare for release v0.44.0 (#188)
- [eb1460fa](https://github.com/kubedb/mysql-coordinator/commit/eb1460fa) Modernize golangci-lint config (#187)
- [db883280](https://github.com/kubedb/mysql-coordinator/commit/db883280) Add Virtual Secret (#182)



## [kubedb/mysql-restic-plugin](https://github.com/kubedb/mysql-restic-plugin)

### [v0.29.0](https://github.com/kubedb/mysql-restic-plugin/releases/tag/v0.29.0)

- [c13c0001](https://github.com/kubedb/mysql-restic-plugin/commit/c13c0001) Prepare for release v0.29.0 (#120)
- [a907f9a4](https://github.com/kubedb/mysql-restic-plugin/commit/a907f9a4) Modernize golangci-lint config (#119)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.44.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.44.0)

- [fa3f225](https://github.com/kubedb/mysql-router-init/commit/fa3f225) Prepare for release v0.44.0 (#67)
- [a848737](https://github.com/kubedb/mysql-router-init/commit/a848737) Modernize golangci-lint config (#66)



## [kubedb/neo4j](https://github.com/kubedb/neo4j)

### [v0.7.0](https://github.com/kubedb/neo4j/releases/tag/v0.7.0)

- [82145ee3](https://github.com/kubedb/neo4j/commit/82145ee3) Prepare for release v0.7.0 (#53)
- [75d9a446](https://github.com/kubedb/neo4j/commit/75d9a446) Modernize golangci-lint config (#52)
- [59d2adbc](https://github.com/kubedb/neo4j/commit/59d2adbc) Run gofmt with updated golang-dev toolchain (#51)
- [ce910cbd](https://github.com/kubedb/neo4j/commit/ce910cbd) Add InPlace mode to vertical scaling (#50)
- [a42ab5c8](https://github.com/kubedb/neo4j/commit/a42ab5c8) Add backup pause/resume support for ops requests (#47)
- [33b7be9b](https://github.com/kubedb/neo4j/commit/33b7be9b) Enable TLS in Backup Port (#46)



## [kubedb/oracle-coordinator](https://github.com/kubedb/oracle-coordinator)

### [v0.12.0](https://github.com/kubedb/oracle-coordinator/releases/tag/v0.12.0)

- [225c88c](https://github.com/kubedb/oracle-coordinator/commit/225c88c) Prepare for release v0.12.0 (#43)
- [9d5c3e0](https://github.com/kubedb/oracle-coordinator/commit/9d5c3e0) Modernize golangci-lint config (#42)



## [kubedb/pg-coordinator](https://github.com/kubedb/pg-coordinator)

### [v0.50.0](https://github.com/kubedb/pg-coordinator/releases/tag/v0.50.0)

- [eb30eb7a](https://github.com/kubedb/pg-coordinator/commit/eb30eb7a) Prepare for release v0.50.0 (#263)
- [440db3d9](https://github.com/kubedb/pg-coordinator/commit/440db3d9) Modernize golangci-lint config (#262)
- [d34653a1](https://github.com/kubedb/pg-coordinator/commit/d34653a1) Fix formatlsn8 to zero-pad LSN low word to 8 hex digits (#260)



## [kubedb/postgres-csi-snapshotter-plugin](https://github.com/kubedb/postgres-csi-snapshotter-plugin)

### [v0.27.0](https://github.com/kubedb/postgres-csi-snapshotter-plugin/releases/tag/v0.27.0)

- [5b3a81c2](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/5b3a81c2) Prepare for release v0.27.0
- [bab69004](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/bab69004) Modernize golangci-lint config (#93)



## [kubedb/qdrant](https://github.com/kubedb/qdrant)

### [v0.7.0](https://github.com/kubedb/qdrant/releases/tag/v0.7.0)

- [5ea7efa0](https://github.com/kubedb/qdrant/commit/5ea7efa0) Prepare for release v0.7.0 (#55)
- [8ed0db3f](https://github.com/kubedb/qdrant/commit/8ed0db3f) Modernize golangci-lint config (#54)
- [b955a139](https://github.com/kubedb/qdrant/commit/b955a139) Run gofmt with updated golang-dev toolchain (#53)
- [74e7dcd3](https://github.com/kubedb/qdrant/commit/74e7dcd3) Add InPlace mode to vertical scaling (#52)
- [3618bbdf](https://github.com/kubedb/qdrant/commit/3618bbdf) Add backup pause/resume support for ops requests (#50)



## [kubedb/rabbitmq](https://github.com/kubedb/rabbitmq)

### [v0.21.0](https://github.com/kubedb/rabbitmq/releases/tag/v0.21.0)

- [4827fb02](https://github.com/kubedb/rabbitmq/commit/4827fb02) Prepare for release v0.21.0 (#146)
- [eeedbe3b](https://github.com/kubedb/rabbitmq/commit/eeedbe3b) Modernize golangci-lint config (#145)
- [5d45e3ec](https://github.com/kubedb/rabbitmq/commit/5d45e3ec) Add backup pause/resume support for ops requests (#142)
- [7d8fc997](https://github.com/kubedb/rabbitmq/commit/7d8fc997) Support InPlace mode for vertical scaling (#144)



## [kubedb/redis-coordinator](https://github.com/kubedb/redis-coordinator)

### [v0.45.0](https://github.com/kubedb/redis-coordinator/releases/tag/v0.45.0)

- [f0b13174](https://github.com/kubedb/redis-coordinator/commit/f0b13174) Prepare for release v0.45.0 (#166)
- [7645c40a](https://github.com/kubedb/redis-coordinator/commit/7645c40a) Modernize golangci-lint config (#165)



## [kubedb/singlestore](https://github.com/kubedb/singlestore)

### [v0.21.0](https://github.com/kubedb/singlestore/releases/tag/v0.21.0)

- [f51c87f9](https://github.com/kubedb/singlestore/commit/f51c87f9) Prepare for release v0.21.0 (#139)
- [8d7aeb36](https://github.com/kubedb/singlestore/commit/8d7aeb36) Modernize golangci-lint config (#138)
- [daf2d45d](https://github.com/kubedb/singlestore/commit/daf2d45d) Run gofmt with updated golang-dev toolchain (#137)
- [ea9437b9](https://github.com/kubedb/singlestore/commit/ea9437b9) Merge pull request #135 from kubedb/inplace-vscale
- [5a7d19bf](https://github.com/kubedb/singlestore/commit/5a7d19bf) Merge branch 'master' into inplace-vscale
- [aa92b2d3](https://github.com/kubedb/singlestore/commit/aa92b2d3) fix build
- [6086ab90](https://github.com/kubedb/singlestore/commit/6086ab90) Add backup pause/resume support for ops requests (#134)
- [44b37bf1](https://github.com/kubedb/singlestore/commit/44b37bf1) Add InPlace mode to vertical scaling



## [kubedb/singlestore-restic-plugin](https://github.com/kubedb/singlestore-restic-plugin)

### [v0.24.0](https://github.com/kubedb/singlestore-restic-plugin/releases/tag/v0.24.0)

- [a6b971a3](https://github.com/kubedb/singlestore-restic-plugin/commit/a6b971a3) Prepare for release v0.24.0
- [1533cce0](https://github.com/kubedb/singlestore-restic-plugin/commit/1533cce0) Modernize golangci-lint config (#91)



## [kubedb/solr](https://github.com/kubedb/solr)

### [v0.21.0](https://github.com/kubedb/solr/releases/tag/v0.21.0)

- [0c84e83d](https://github.com/kubedb/solr/commit/0c84e83d) Prepare for release v0.21.0 (#145)
- [e3f0587d](https://github.com/kubedb/solr/commit/e3f0587d) Modernize golangci-lint config (#144)
- [824f8d6f](https://github.com/kubedb/solr/commit/824f8d6f) Run gofmt with updated golang-dev toolchain (#143)
- [1a81c48a](https://github.com/kubedb/solr/commit/1a81c48a) Add InPlace mode to vertical scaling (#142)
- [fd7d5de3](https://github.com/kubedb/solr/commit/fd7d5de3) Add backup pause/resume support for ops requests (#141)
- [b8e6684b](https://github.com/kubedb/solr/commit/b8e6684b) Add Solr Secret Fix (#139)



## [kubedb/weaviate](https://github.com/kubedb/weaviate)

### [v0.7.0](https://github.com/kubedb/weaviate/releases/tag/v0.7.0)

- [6e7f0a95](https://github.com/kubedb/weaviate/commit/6e7f0a95) Prepare for release v0.7.0 (#53)
- [0e405cbf](https://github.com/kubedb/weaviate/commit/0e405cbf) Add InPlace mode to vertical scaling (#50)
- [3d0642c6](https://github.com/kubedb/weaviate/commit/3d0642c6) Modernize golangci-lint config (#52)
- [f8e0e4a7](https://github.com/kubedb/weaviate/commit/f8e0e4a7) Add Weaviate Monitoring (#49)
- [c06bfe8b](https://github.com/kubedb/weaviate/commit/c06bfe8b) Fix Lint (#51)
- [4ef1154c](https://github.com/kubedb/weaviate/commit/4ef1154c) Add backup pause/resume support for ops requests (#47)
- [0eb4f587](https://github.com/kubedb/weaviate/commit/0eb4f587) Fix rotate_auth (#46)



