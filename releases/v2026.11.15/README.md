# KubeDB v2026.11.15 (2026-11-12)


## [kubedb/aerospike](https://github.com/kubedb/aerospike)

### [v0.5.0](https://github.com/kubedb/aerospike/releases/tag/v0.5.0)

- [1dc8cfc7](https://github.com/kubedb/aerospike/commit/1dc8cfc7) Prepare for release v0.5.0 (#20)



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



## [kubedb/cassandra-medusa-plugin](https://github.com/kubedb/cassandra-medusa-plugin)

### [v0.16.0](https://github.com/kubedb/cassandra-medusa-plugin/releases/tag/v0.16.0)

- [c000e161](https://github.com/kubedb/cassandra-medusa-plugin/commit/c000e161) Prepare for release v0.16.0 (#50)



## [kubedb/crd-manager](https://github.com/kubedb/crd-manager)

### [v0.24.0](https://github.com/kubedb/crd-manager/releases/tag/v0.24.0)

- [c39f6de1](https://github.com/kubedb/crd-manager/commit/c39f6de1) Prepare for release v0.24.0 (#162)



## [kubedb/dashboard-restic-plugin](https://github.com/kubedb/dashboard-restic-plugin)

### [v0.27.0](https://github.com/kubedb/dashboard-restic-plugin/releases/tag/v0.27.0)

- [3b2b41a0](https://github.com/kubedb/dashboard-restic-plugin/commit/3b2b41a0) Prepare for release v0.27.0 (#90)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.24.0](https://github.com/kubedb/db-client-go/releases/tag/v0.24.0)

- [dc07eaf4](https://github.com/kubedb/db-client-go/commit/dc07eaf4) Prepare for release v0.24.0 (#275)
- [ef134e34](https://github.com/kubedb/db-client-go/commit/ef134e34) postgres: bound GetPostgresXormClient's SELECT 1 by the caller context; close engine on failure (#269)
- [af39558a](https://github.com/kubedb/db-client-go/commit/af39558a) etcd: start clients on round_robin to stop canceled-dial warnings (#272)
- [a39d2ab9](https://github.com/kubedb/db-client-go/commit/a39d2ab9) etcd: dial learners anonymously, bound per-member Status probes (#267)



## [kubedb/druid](https://github.com/kubedb/druid)

### [v0.24.0](https://github.com/kubedb/druid/releases/tag/v0.24.0)

- [376b2284](https://github.com/kubedb/druid/commit/376b2284) Prepare for release v0.24.0 (#161)
- [414c272b](https://github.com/kubedb/druid/commit/414c272b) Default security IDs from the OpenShift namespace in the operator (#160)



## [kubedb/hanadb](https://github.com/kubedb/hanadb)

### [v0.10.0](https://github.com/kubedb/hanadb/releases/tag/v0.10.0)

- [c3db55db](https://github.com/kubedb/hanadb/commit/c3db55db) Prepare for release v0.10.0 (#69)
- [9a1e05cf](https://github.com/kubedb/hanadb/commit/9a1e05cf) Default security IDs from the OpenShift namespace in the operator (#68)



## [kubedb/hanadb-coordinator](https://github.com/kubedb/hanadb-coordinator)

### [v0.9.0](https://github.com/kubedb/hanadb-coordinator/releases/tag/v0.9.0)

- [6697127d](https://github.com/kubedb/hanadb-coordinator/commit/6697127d) Prepare for release v0.9.0 (#27)



## [kubedb/ignite](https://github.com/kubedb/ignite)

### [v0.16.0](https://github.com/kubedb/ignite/releases/tag/v0.16.0)

- [1f1b5b19](https://github.com/kubedb/ignite/commit/1f1b5b19) Prepare for release v0.16.0 (#81)
- [6f153323](https://github.com/kubedb/ignite/commit/6f153323) Default security IDs from the OpenShift namespace in the operator (#80)



## [kubedb/mariadb](https://github.com/kubedb/mariadb)

### [v0.53.0](https://github.com/kubedb/mariadb/releases/tag/v0.53.0)

- [144cdc9c](https://github.com/kubedb/mariadb/commit/144cdc9c5) Prepare for release v0.53.0 (#439)
- [9c9a6613](https://github.com/kubedb/mariadb/commit/9c9a6613b) Default security IDs from the OpenShift namespace in the operator (#437)
- [782d4384](https://github.com/kubedb/mariadb/commit/782d43848) Allow skipping the primary service template for MaxScale or MariaDB (#438)
- [d07615c7](https://github.com/kubedb/mariadb/commit/d07615c7f) add mariadb auto reconfigure feature (#436)
- [b79ab6ad](https://github.com/kubedb/mariadb/commit/b79ab6adf) Default exporter resources in vertical scaling (#432)
- [09048e77](https://github.com/kubedb/mariadb/commit/09048e77b) Add the ArchiverRestore ops request and in-place restore path (#428)



## [kubedb/memcached](https://github.com/kubedb/memcached)

### [v0.63.0](https://github.com/kubedb/memcached/releases/tag/v0.63.0)

- [2a4bfd1c](https://github.com/kubedb/memcached/commit/2a4bfd1cc) Prepare for release v0.63.0 (#562)
- [59c850d7](https://github.com/kubedb/memcached/commit/59c850d77) Default security IDs from the OpenShift namespace in the operator (#561)



## [kubedb/milvus](https://github.com/kubedb/milvus)

### [v0.10.0](https://github.com/kubedb/milvus/releases/tag/v0.10.0)

- [6b48c2ae](https://github.com/kubedb/milvus/commit/6b48c2ae) Prepare for release v0.10.0 (#90)
- [55162b5d](https://github.com/kubedb/milvus/commit/55162b5d) Default security IDs from the OpenShift namespace in the operator (#89)
- [da38092c](https://github.com/kubedb/milvus/commit/da38092c) Fix RotateAuth lockout, false InPlace successes, and Halt/WipeOut of the meta etcd (#82)
- [1b21b402](https://github.com/kubedb/milvus/commit/1b21b402) Mark the Milvus incremental snapshot Succeeded when the archiver is removed (#83)
- [f0dbd153](https://github.com/kubedb/milvus/commit/f0dbd153) Add spec.objectStorage.tls for an object storage with a private CA (#87)
- [00955f64](https://github.com/kubedb/milvus/commit/00955f64) Stop a new Milvus on a used object storage path (#86)
- [64c0b3ff](https://github.com/kubedb/milvus/commit/64c0b3ff) Propagate podTemplate securityContext to existing PetSets (#88)
- [42c05e0f](https://github.com/kubedb/milvus/commit/42c05e0f) Start meta etcd clients on round_robin (#81)



## [kubedb/mongodb](https://github.com/kubedb/mongodb)

### [v0.62.0](https://github.com/kubedb/mongodb/releases/tag/v0.62.0)

- [e0cfa3f0](https://github.com/kubedb/mongodb/commit/e0cfa3f04) Prepare for release v0.62.0 (#793)
- [65aea857](https://github.com/kubedb/mongodb/commit/65aea8572) Default security IDs from the OpenShift namespace in the operator (#792)
- [8dd3669c](https://github.com/kubedb/mongodb/commit/8dd3669cc) Apply document-valued setParameter entries as one parameter on Reconfigure (#791)



## [kubedb/mongodb-restic-plugin](https://github.com/kubedb/mongodb-restic-plugin)

### [v0.32.0](https://github.com/kubedb/mongodb-restic-plugin/releases/tag/v0.32.0)

- [555bceeb](https://github.com/kubedb/mongodb-restic-plugin/commit/555bceeb) Prepare for release v0.32.0 (#142)



## [kubedb/mssqlserver](https://github.com/kubedb/mssqlserver)

### [v0.24.0](https://github.com/kubedb/mssqlserver/releases/tag/v0.24.0)

- [2f8b8345](https://github.com/kubedb/mssqlserver/commit/2f8b8345) Prepare for release v0.24.0 (#166)
- [1bc17f10](https://github.com/kubedb/mssqlserver/commit/1bc17f10) Default security IDs from the OpenShift namespace in the operator (#164)
- [c847dd9b](https://github.com/kubedb/mssqlserver/commit/c847dd9b) Add branched mode for KubeDB Courier Branch (#148)



## [kubedb/mssqlserver-archiver](https://github.com/kubedb/mssqlserver-archiver)

### [v0.23.0](https://github.com/kubedb/mssqlserver-archiver/releases/tag/v0.23.0)

- [770a6a3](https://github.com/kubedb/mssqlserver-archiver/commit/770a6a3) Prepare for release v0.23.0 (#40)



## [kubedb/mssqlserver-walg-plugin](https://github.com/kubedb/mssqlserver-walg-plugin)

### [v0.23.0](https://github.com/kubedb/mssqlserver-walg-plugin/releases/tag/v0.23.0)

- [6e60a28b](https://github.com/kubedb/mssqlserver-walg-plugin/commit/6e60a28b) Prepare for release v0.23.0 (#73)



## [kubedb/mysql](https://github.com/kubedb/mysql)

### [v0.62.0](https://github.com/kubedb/mysql/releases/tag/v0.62.0)

- [63743fc3](https://github.com/kubedb/mysql/commit/63743fc33) Prepare for release v0.62.0 (#789)
- [2746998f](https://github.com/kubedb/mysql/commit/2746998fc) Default security IDs from the OpenShift namespace in the operator (#788)
- [465cc44a](https://github.com/kubedb/mysql/commit/465cc44a5) add mysql auto reconfigure feature (#787)
- [3ba4b7b6](https://github.com/kubedb/mysql/commit/3ba4b7b6a) Fix Enterprise Reconfig (#785)
- [f12272b9](https://github.com/kubedb/mysql/commit/f12272b95) Add Archiver Restore Ops (#776)



## [kubedb/mysql-archiver](https://github.com/kubedb/mysql-archiver)

### [v0.30.0](https://github.com/kubedb/mysql-archiver/releases/tag/v0.30.0)

- [28e3e4fe](https://github.com/kubedb/mysql-archiver/commit/28e3e4fe) Prepare for release v0.30.0 (#120)
- [507e6e59](https://github.com/kubedb/mysql-archiver/commit/507e6e59) Rotate the binlog on an interval so there is something to archive (#114)



## [kubedb/mysql-coordinator](https://github.com/kubedb/mysql-coordinator)

### [v0.47.0](https://github.com/kubedb/mysql-coordinator/releases/tag/v0.47.0)

- [04085d70](https://github.com/kubedb/mysql-coordinator/commit/04085d70) Prepare for release v0.47.0 (#197)



## [kubedb/mysql-csi-snapshotter-plugin](https://github.com/kubedb/mysql-csi-snapshotter-plugin)

### [v0.30.0](https://github.com/kubedb/mysql-csi-snapshotter-plugin/releases/tag/v0.30.0)

- [189d70ba](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/189d70ba) Prepare for release v0.30.0 (#92)



## [kubedb/mysql-restic-plugin](https://github.com/kubedb/mysql-restic-plugin)

### [v0.32.0](https://github.com/kubedb/mysql-restic-plugin/releases/tag/v0.32.0)

- [44527f7f](https://github.com/kubedb/mysql-restic-plugin/commit/44527f7f) Prepare for release v0.32.0 (#128)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.47.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.47.0)

- [9f4eae9](https://github.com/kubedb/mysql-router-init/commit/9f4eae9) Prepare for release v0.47.0 (#74)



## [kubedb/oracle-backup-plugin](https://github.com/kubedb/oracle-backup-plugin)

### [v0.3.0](https://github.com/kubedb/oracle-backup-plugin/releases/tag/v0.3.0)

- [8c66b47](https://github.com/kubedb/oracle-backup-plugin/commit/8c66b47) Prepare for release v0.3.0 (#12)
- [04745c2](https://github.com/kubedb/oracle-backup-plugin/commit/04745c2) Remove oracle restore flags (#4)
- [8452de4](https://github.com/kubedb/oracle-backup-plugin/commit/8452de4) add minio support (#6)



## [kubedb/percona-xtradb](https://github.com/kubedb/percona-xtradb)

### [v0.56.0](https://github.com/kubedb/percona-xtradb/releases/tag/v0.56.0)

- [7657afe3](https://github.com/kubedb/percona-xtradb/commit/7657afe33) Prepare for release v0.56.0 (#481)
- [2a83b5fc](https://github.com/kubedb/percona-xtradb/commit/2a83b5fc9) Default security IDs from the OpenShift namespace in the operator (#480)



## [kubedb/percona-xtradb-coordinator](https://github.com/kubedb/percona-xtradb-coordinator)

### [v0.42.0](https://github.com/kubedb/percona-xtradb-coordinator/releases/tag/v0.42.0)

- [ebe7cc57](https://github.com/kubedb/percona-xtradb-coordinator/commit/ebe7cc57) Prepare for release v0.42.0 (#141)



## [kubedb/pg-coordinator](https://github.com/kubedb/pg-coordinator)

### [v0.53.0](https://github.com/kubedb/pg-coordinator/releases/tag/v0.53.0)




## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.69.0](https://github.com/kubedb/postgres/releases/tag/v0.69.0)

- [d0e732d0](https://github.com/kubedb/postgres/commit/d0e732d01) Prepare for release v0.69.0 (#968)
- [d73b5f62](https://github.com/kubedb/postgres/commit/d73b5f62d) Find run.sh pid via /proc on RHEL-family images (#935)
- [f5f92e6c](https://github.com/kubedb/postgres/commit/f5f92e6cd) Ignore Issuer events that arrive before the Postgres watchers are initialised (#963)
- [23dc1723](https://github.com/kubedb/postgres/commit/23dc1723f) Default Postgres UID/GID/fsGroup from OpenShift namespace SCC ranges (#961)
- [15f12a76](https://github.com/kubedb/postgres/commit/15f12a760) Set a MajorUpgradeInProgress raft key for the length of a major upgrade (#964)
- [af89100a](https://github.com/kubedb/postgres/commit/af89100a4) Reconfigure: make restart: auto decide, verify reloads through PostgreSQL (#901)
- [f22cdc67](https://github.com/kubedb/postgres/commit/f22cdc67c) Opt-in service account token hardening and coordinator API token/TLS (#955)



## [kubedb/qdrant](https://github.com/kubedb/qdrant)

### [v0.10.0](https://github.com/kubedb/qdrant/releases/tag/v0.10.0)

- [f30d7f24](https://github.com/kubedb/qdrant/commit/f30d7f24) Prepare for release v0.10.0 (#67)



## [kubedb/rabbitmq](https://github.com/kubedb/rabbitmq)

### [v0.24.0](https://github.com/kubedb/rabbitmq/releases/tag/v0.24.0)

- [3b13c743](https://github.com/kubedb/rabbitmq/commit/3b13c743) Prepare for release v0.24.0 (#160)



## [kubedb/redis](https://github.com/kubedb/redis)

### [v0.62.0](https://github.com/kubedb/redis/releases/tag/v0.62.0)

- [a8b092f4](https://github.com/kubedb/redis/commit/a8b092f4a) Prepare for release v0.62.0 (#686)
- [fdc22f84](https://github.com/kubedb/redis/commit/fdc22f84d) Default security IDs from the OpenShift namespace in the operator (#685)



## [kubedb/singlestore-coordinator](https://github.com/kubedb/singlestore-coordinator)

### [v0.24.0](https://github.com/kubedb/singlestore-coordinator/releases/tag/v0.24.0)

- [eeefe830](https://github.com/kubedb/singlestore-coordinator/commit/eeefe830) Prepare for release v0.24.0 (#85)



## [kubedb/singlestore-restic-plugin](https://github.com/kubedb/singlestore-restic-plugin)

### [v0.27.0](https://github.com/kubedb/singlestore-restic-plugin/releases/tag/v0.27.0)

- [8937fd4a](https://github.com/kubedb/singlestore-restic-plugin/commit/8937fd4a) Prepare for release v0.27.0 (#100)



## [kubedb/solr](https://github.com/kubedb/solr)

### [v0.24.0](https://github.com/kubedb/solr/releases/tag/v0.24.0)

- [b6a0132d](https://github.com/kubedb/solr/commit/b6a0132d) Prepare for release v0.24.0 (#163)



## [kubedb/weaviate](https://github.com/kubedb/weaviate)

### [v0.10.0](https://github.com/kubedb/weaviate/releases/tag/v0.10.0)

- [d7b47bad](https://github.com/kubedb/weaviate/commit/d7b47bad) Prepare for release v0.10.0 (#66)



