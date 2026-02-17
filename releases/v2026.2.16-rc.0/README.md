# KubeDB v2026.2.16-rc.0 (2026-02-17)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.61.0-rc.0](https://github.com/kubedb/apimachinery/releases/tag/v0.61.0-rc.0)

- [78da1b2d](https://github.com/kubedb/apimachinery/commit/78da1b2d6) Redis Config Secret Conversion fix (#1595)
- [f1ac6610](https://github.com/kubedb/apimachinery/commit/f1ac6610d) Standardize migrator pkg (#1594)
- [8c54988a](https://github.com/kubedb/apimachinery/commit/8c54988a4) Report k8s distro and storage provisioners (#1593)
- [3ab9a8c4](https://github.com/kubedb/apimachinery/commit/3ab9a8c46) Fix CI (#1592)
- [46868bd0](https://github.com/kubedb/apimachinery/commit/46868bd03) Add Distributed Archiver Support for MariaDB (#1582)
- [d390f703](https://github.com/kubedb/apimachinery/commit/d390f7030) Add Migrator Operator APIs and Configs for CLI (#1588)
- [71146793](https://github.com/kubedb/apimachinery/commit/711467936) Add Qdrant Monitoring Support (#1550)
- [8591d06f](https://github.com/kubedb/apimachinery/commit/8591d06f2) Add read replica support for Postgres (#1580)
- [09750ca1](https://github.com/kubedb/apimachinery/commit/09750ca1e) Add Milvus Cluster Apis (#1551)
- [eec0c01f](https://github.com/kubedb/apimachinery/commit/eec0c01f2) Introduce log RetentionPeriod for log cleanup (#1537)
- [05e2788c](https://github.com/kubedb/apimachinery/commit/05e2788ca) Add Kafka Tiered Storage APIs (#1378)
- [719ce3b0](https://github.com/kubedb/apimachinery/commit/719ce3b05) Update license header (#1591)
- [04bd7de6](https://github.com/kubedb/apimachinery/commit/04bd7de62) Add Constant For Opensearch/Elasticsearch (#1578)
- [7eb9e9a4](https://github.com/kubedb/apimachinery/commit/7eb9e9a4c) Add tolerations to pvc-mounter pod for storageclass migration (#1589)
- [81a671f5](https://github.com/kubedb/apimachinery/commit/81a671f52) Add relabel config support to ServiceMonitor (#1584)



## [kubedb/crd-manager](https://github.com/kubedb/crd-manager)

### [v0.16.0-rc.0](https://github.com/kubedb/crd-manager/releases/tag/v0.16.0-rc.0)

- [2d2c0c9a](https://github.com/kubedb/crd-manager/commit/2d2c0c9a) Prepare for release v0.16.0-rc.0 (#110)
- [ef87879e](https://github.com/kubedb/crd-manager/commit/ef87879e) Update kafka crds (#108)
- [e9b0cd26](https://github.com/kubedb/crd-manager/commit/e9b0cd26) Prepare for release v0.15.0 (#107)
- [f16d4769](https://github.com/kubedb/crd-manager/commit/f16d4769) Add crd for cassandra, hazelcast, oracle (#106)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.16.0-rc.0](https://github.com/kubedb/db-client-go/releases/tag/v0.16.0-rc.0)

- [3cbe8746](https://github.com/kubedb/db-client-go/commit/3cbe8746) Prepare for release v0.16.0-rc.0 (#221)
- [496ef203](https://github.com/kubedb/db-client-go/commit/496ef203) Add Creating MariaDB Client without MariaDB Instance (#218)
- [2ecc2b55](https://github.com/kubedb/db-client-go/commit/2ecc2b55) Prepare for release v0.15.0 (#217)
- [9854141c](https://github.com/kubedb/db-client-go/commit/9854141c) fix opensearch-v3 health check issues (#216)
- [d08174b5](https://github.com/kubedb/db-client-go/commit/d08174b5) Add Qdrant TLS Support (#212)



## [kubedb/elasticsearch](https://github.com/kubedb/elasticsearch)

### [v0.61.0-rc.0](https://github.com/kubedb/elasticsearch/releases/tag/v0.61.0-rc.0)

- [ea0990c0](https://github.com/kubedb/elasticsearch/commit/ea0990c0f) Prepare for release v0.61.0-rc.0 (#790)
- [9d920917](https://github.com/kubedb/elasticsearch/commit/9d920917b) Remove init Container from Opensearch (#787)
- [06726a8c](https://github.com/kubedb/elasticsearch/commit/06726a8ce) Merge pull request #788 from kubedb/prll-ctrl
- [bf671dfe](https://github.com/kubedb/elasticsearch/commit/bf671dfe6) Prepare for release v0.60.0 (#786)
- [3d9d54ad](https://github.com/kubedb/elasticsearch/commit/3d9d54ad0) Fix Opensearch health check issue for v3.0 (#785)
- [10542dbb](https://github.com/kubedb/elasticsearch/commit/10542dbb0) Improve and generalize configure-reconfigure process (#782)



## [kubedb/kubedb-manifest-plugin](https://github.com/kubedb/kubedb-manifest-plugin)

### [v0.24.0-rc.0](https://github.com/kubedb/kubedb-manifest-plugin/releases/tag/v0.24.0-rc.0)

- [b3d1a34e](https://github.com/kubedb/kubedb-manifest-plugin/commit/b3d1a34e) Prepare for release v0.24.0-rc.0 (#116)
- [19fa3a25](https://github.com/kubedb/kubedb-manifest-plugin/commit/19fa3a25) Incorporate changes for restic standalone pkg (#115)
- [9aebbe1c](https://github.com/kubedb/kubedb-manifest-plugin/commit/9aebbe1c) Fix UBI image
- [39aabbc2](https://github.com/kubedb/kubedb-manifest-plugin/commit/39aabbc2) Prepare for release v0.23.0 (#113)
- [6ab7dfbc](https://github.com/kubedb/kubedb-manifest-plugin/commit/6ab7dfbc) Use forked kubestash/restic (#112)
- [839e93d7](https://github.com/kubedb/kubedb-manifest-plugin/commit/839e93d7) Use forked kubestash/restic (#111)



## [kubedb/mongodb-csi-snapshotter-plugin](https://github.com/kubedb/mongodb-csi-snapshotter-plugin)

### [v0.22.0-rc.0](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/releases/tag/v0.22.0-rc.0)

- [971d799d](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/971d799d) Prepare for release v0.22.0-rc.0 (#70)
- [e6fd5d5f](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/e6fd5d5f) Prepare for release v0.21.0 (#68)



## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.61.0-rc.0](https://github.com/kubedb/postgres/releases/tag/v0.61.0-rc.0)

- [e9c1b88f](https://github.com/kubedb/postgres/commit/e9c1b88f9) Prepare for release v0.61.0-rc.0 (#856)
- [2564a529](https://github.com/kubedb/postgres/commit/2564a529a) added permissions for binlog-cloeanup (#855)
- [c16dae52](https://github.com/kubedb/postgres/commit/c16dae527) Add Read Replica Support  (#854)
- [b44e0d83](https://github.com/kubedb/postgres/commit/b44e0d839) Add pod toleration during storageClass migration (#853)
- [acc6ee97](https://github.com/kubedb/postgres/commit/acc6ee979) Incorporate new snapshot naming in postgres archiver (#851)
- [dde64cf3](https://github.com/kubedb/postgres/commit/dde64cf30) Update parallel processing logic (#849)
- [5086c260](https://github.com/kubedb/postgres/commit/5086c260c) Update Arbiter error code (#848)
- [a313afc9](https://github.com/kubedb/postgres/commit/a313afc9e) Prepare for release v0.60.0 (#847)
- [4d86169d](https://github.com/kubedb/postgres/commit/4d86169d7) Add sharding facility for Postgres Ops-Requests (#843)



## [kubedb/postgres-archiver](https://github.com/kubedb/postgres-archiver)

### [v0.22.0-rc.0](https://github.com/kubedb/postgres-archiver/releases/tag/v0.22.0-rc.0)

- [6138276c](https://github.com/kubedb/postgres-archiver/commit/6138276c) Prepare for release v0.22.0-rc.0 (#85)
- [6f702e23](https://github.com/kubedb/postgres-archiver/commit/6f702e23) Test against k8s 1.35 (#84)
- [49c942eb](https://github.com/kubedb/postgres-archiver/commit/49c942eb) added wal-log clean feature (#83)
- [e92dc052](https://github.com/kubedb/postgres-archiver/commit/e92dc052) Fix ubi build (#81)
- [f45faf8c](https://github.com/kubedb/postgres-archiver/commit/f45faf8c) Prepare for release v0.21.0 (#80)
- [0c1f7850](https://github.com/kubedb/postgres-archiver/commit/0c1f7850) Fix redhat catalog submission (#78)



## [kubedb/redis-coordinator](https://github.com/kubedb/redis-coordinator)

### [v0.40.0-rc.0](https://github.com/kubedb/redis-coordinator/releases/tag/v0.40.0-rc.0)

- [e6f57560](https://github.com/kubedb/redis-coordinator/commit/e6f57560) Prepare for release v0.40.0-rc.0 (#146)
- [0a121386](https://github.com/kubedb/redis-coordinator/commit/0a121386) Prepare for release v0.39.0 (#144)



