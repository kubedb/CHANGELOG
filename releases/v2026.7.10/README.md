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



## [kubedb/crd-manager](https://github.com/kubedb/crd-manager)

### [v0.21.0](https://github.com/kubedb/crd-manager/releases/tag/v0.21.0)

- [ef77e885](https://github.com/kubedb/crd-manager/commit/ef77e885) Prepare for release v0.21.0 (#148)
- [1257a1c4](https://github.com/kubedb/crd-manager/commit/1257a1c4) Rename migrator to courier CRDs (#147)
- [e3df0cbf](https://github.com/kubedb/crd-manager/commit/e3df0cbf) Modernize golangci-lint config (#146)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.21.0](https://github.com/kubedb/db-client-go/releases/tag/v0.21.0)

- [bc3a25ce](https://github.com/kubedb/db-client-go/commit/bc3a25ce) Prepare for release v0.21.0 (#255)
- [fec3c231](https://github.com/kubedb/db-client-go/commit/fec3c231) Modernize golangci-lint config (#254)
- [a3da77c5](https://github.com/kubedb/db-client-go/commit/a3da77c5) add aerospike client (#251)
- [144cd45a](https://github.com/kubedb/db-client-go/commit/144cd45a) Add New function For Neo4j (#252)
- [4b2ca834](https://github.com/kubedb/db-client-go/commit/4b2ca834) Add Qdrant Recover Snapshot Reader Function (#253)



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



## [kubedb/mysql-restic-plugin](https://github.com/kubedb/mysql-restic-plugin)

### [v0.29.0](https://github.com/kubedb/mysql-restic-plugin/releases/tag/v0.29.0)

- [c13c0001](https://github.com/kubedb/mysql-restic-plugin/commit/c13c0001) Prepare for release v0.29.0 (#120)
- [a907f9a4](https://github.com/kubedb/mysql-restic-plugin/commit/a907f9a4) Modernize golangci-lint config (#119)



## [kubedb/rabbitmq](https://github.com/kubedb/rabbitmq)

### [v0.21.0](https://github.com/kubedb/rabbitmq/releases/tag/v0.21.0)

- [4827fb02](https://github.com/kubedb/rabbitmq/commit/4827fb02) Prepare for release v0.21.0 (#146)
- [eeedbe3b](https://github.com/kubedb/rabbitmq/commit/eeedbe3b) Modernize golangci-lint config (#145)
- [5d45e3ec](https://github.com/kubedb/rabbitmq/commit/5d45e3ec) Add backup pause/resume support for ops requests (#142)
- [7d8fc997](https://github.com/kubedb/rabbitmq/commit/7d8fc997) Support InPlace mode for vertical scaling (#144)



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



