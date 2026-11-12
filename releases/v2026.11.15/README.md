# KubeDB v2026.11.15 (2026-11-12)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.69.0](https://github.com/kubedb/apimachinery/releases/tag/v0.69.0)

- [cb8b0c69](https://github.com/kubedb/apimachinery/commit/cb8b0c69e) Cleanup deps
- [f42a5fad](https://github.com/kubedb/apimachinery/commit/f42a5fadb) Add Postgres MajorUpgradeInProgress raft key and conditions (#1954)
- [dbfac26f](https://github.com/kubedb/apimachinery/commit/dbfac26f5) Cache the OpenShift check per RESTMapper (#1956)
- [b89bffca](https://github.com/kubedb/apimachinery/commit/b89bffca5) OracleOSBWS Constants (#1953)
- [d24add47](https://github.com/kubedb/apimachinery/commit/d24add471) Default database UID/GID/fsGroup from OpenShift namespace SCC ranges (#1952)
- [30b10799](https://github.com/kubedb/apimachinery/commit/30b10799b) Add spec.objectStorage.tls to Milvus for a custom object storage CA (#1949)
- [0e4a9a41](https://github.com/kubedb/apimachinery/commit/0e4a9a412) Milvus: add spec.autoOps, GPU guard for UpdateVersion, StreamingNode storage default (#1947)
- [6cd3915e](https://github.com/kubedb/apimachinery/commit/6cd3915e3) Milvus webhook: allow the archiver on Milvus 3.x (#1945)
- [f07dcf5a](https://github.com/kubedb/apimachinery/commit/f07dcf5a4) Add Qdrant PITR Support (#1671)
- [bf4b2936](https://github.com/kubedb/apimachinery/commit/bf4b2936a) add mysql auto reconfigure feature (#1951)
- [c6b3e417](https://github.com/kubedb/apimachinery/commit/c6b3e4178) Restrict shared service aliases; add per-DB alias types and Kafka broker alias (#1931)
- [b537910b](https://github.com/kubedb/apimachinery/commit/b537910ba) [MySQL] Add Archiver Restore Ops (#1854)
- [b62975e8](https://github.com/kubedb/apimachinery/commit/b62975e85) Add Neo4j archiver CRD helper (#1927)
- [4606c7f8](https://github.com/kubedb/apimachinery/commit/4606c7f88) Add RecoverMember ops request type for Etcd (#1930)
- [9e71e6a1](https://github.com/kubedb/apimachinery/commit/9e71e6a1a) Accept a Milvus VerticalScaling that only targets node groups (#1929)
- [c5629ed3](https://github.com/kubedb/apimachinery/commit/c5629ed38) Milvus: external-etcd client auth/TLS, etcd root path, restricted SCC knob (#1928)
- [5af9abb5](https://github.com/kubedb/apimachinery/commit/5af9abb56) Fix lint issues



## [kubedb/crd-manager](https://github.com/kubedb/crd-manager)

### [v0.24.0](https://github.com/kubedb/crd-manager/releases/tag/v0.24.0)

- [c39f6de1](https://github.com/kubedb/crd-manager/commit/c39f6de1) Prepare for release v0.24.0 (#162)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.24.0](https://github.com/kubedb/db-client-go/releases/tag/v0.24.0)

- [dc07eaf4](https://github.com/kubedb/db-client-go/commit/dc07eaf4) Prepare for release v0.24.0 (#275)
- [ef134e34](https://github.com/kubedb/db-client-go/commit/ef134e34) postgres: bound GetPostgresXormClient's SELECT 1 by the caller context; close engine on failure (#269)
- [af39558a](https://github.com/kubedb/db-client-go/commit/af39558a) etcd: start clients on round_robin to stop canceled-dial warnings (#272)
- [a39d2ab9](https://github.com/kubedb/db-client-go/commit/a39d2ab9) etcd: dial learners anonymously, bound per-member Status probes (#267)



## [kubedb/mariadb](https://github.com/kubedb/mariadb)

### [v0.53.0](https://github.com/kubedb/mariadb/releases/tag/v0.53.0)

- [144cdc9c](https://github.com/kubedb/mariadb/commit/144cdc9c5) Prepare for release v0.53.0 (#439)
- [9c9a6613](https://github.com/kubedb/mariadb/commit/9c9a6613b) Default security IDs from the OpenShift namespace in the operator (#437)
- [782d4384](https://github.com/kubedb/mariadb/commit/782d43848) Allow skipping the primary service template for MaxScale or MariaDB (#438)
- [d07615c7](https://github.com/kubedb/mariadb/commit/d07615c7f) add mariadb auto reconfigure feature (#436)
- [b79ab6ad](https://github.com/kubedb/mariadb/commit/b79ab6adf) Default exporter resources in vertical scaling (#432)
- [09048e77](https://github.com/kubedb/mariadb/commit/09048e77b) Add the ArchiverRestore ops request and in-place restore path (#428)



## [kubedb/mssqlserver](https://github.com/kubedb/mssqlserver)

### [v0.24.0](https://github.com/kubedb/mssqlserver/releases/tag/v0.24.0)

- [2f8b8345](https://github.com/kubedb/mssqlserver/commit/2f8b8345) Prepare for release v0.24.0 (#166)
- [1bc17f10](https://github.com/kubedb/mssqlserver/commit/1bc17f10) Default security IDs from the OpenShift namespace in the operator (#164)
- [c847dd9b](https://github.com/kubedb/mssqlserver/commit/c847dd9b) Add branched mode for KubeDB Courier Branch (#148)



## [kubedb/percona-xtradb](https://github.com/kubedb/percona-xtradb)

### [v0.56.0](https://github.com/kubedb/percona-xtradb/releases/tag/v0.56.0)

- [7657afe3](https://github.com/kubedb/percona-xtradb/commit/7657afe33) Prepare for release v0.56.0 (#481)
- [2a83b5fc](https://github.com/kubedb/percona-xtradb/commit/2a83b5fc9) Default security IDs from the OpenShift namespace in the operator (#480)



