# KubeDB v2024.1.19-beta.1 (2024-01-20)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.41.0-beta.1](https://github.com/kubedb/apimachinery/releases/tag/v0.41.0-beta.1)

- [ef49cbfa](https://github.com/kubedb/apimachinery/commit/ef49cbfa8) Update deps
- [f85d1410](https://github.com/kubedb/apimachinery/commit/f85d14100) Without non-root (#1122)
- [79fd675a](https://github.com/kubedb/apimachinery/commit/79fd675a0) Add `PausedBackups` field into `OpsRequestStatus` (#1114)
- [778a1af2](https://github.com/kubedb/apimachinery/commit/778a1af25) Add FerretDB Apis (#1119)
- [329083aa](https://github.com/kubedb/apimachinery/commit/329083aa6) Add missing entries while ignoring openapi schema (#1121)
- [0f8ac911](https://github.com/kubedb/apimachinery/commit/0f8ac9110) Fix API for new Databases (#1120)
- [b625c64c](https://github.com/kubedb/apimachinery/commit/b625c64c5) Fix issues with Pgpool HealthChecker field and version check in webhook (#1118)
- [e78c6ff7](https://github.com/kubedb/apimachinery/commit/e78c6ff74) Remove unnecessary apis for singlestore (#1117)
- [6e98cd41](https://github.com/kubedb/apimachinery/commit/6e98cd41c) Add Rabbitmq API (#1109)
- [e7a088fa](https://github.com/kubedb/apimachinery/commit/e7a088faf) Remove api call from Solr setDefaults. (#1116)
- [a73a825b](https://github.com/kubedb/apimachinery/commit/a73a825b7) Add Solr API (#1110)
- [9d687049](https://github.com/kubedb/apimachinery/commit/9d6870498) Pgpool Backend Set to Required (#1113)
- [72d44aef](https://github.com/kubedb/apimachinery/commit/72d44aef7) Fix ElasticsearchDashboard constants
- [0c40a769](https://github.com/kubedb/apimachinery/commit/0c40a7698) Change dashboard api group to elasticsearch (#1112)
- [85e4ae23](https://github.com/kubedb/apimachinery/commit/85e4ae232) Add ZooKeeper API (#1104)
- [ee446682](https://github.com/kubedb/apimachinery/commit/ee446682d) Add Pgpool apis (#1103)
- [4995ebf3](https://github.com/kubedb/apimachinery/commit/4995ebf3d) Add Druid API (#1111)
- [556a36df](https://github.com/kubedb/apimachinery/commit/556a36dfe) Add SingleStore APIS (#1108)
- [a72bb1ff](https://github.com/kubedb/apimachinery/commit/a72bb1ffc) Add runAsGroup field in mgVersion api (#1107)
- [1ee5ee41](https://github.com/kubedb/apimachinery/commit/1ee5ee41d) Add Kafka Connect Cluster and Connector APIs (#1066)
- [2fd99ee8](https://github.com/kubedb/apimachinery/commit/2fd99ee82) Fix replica count for arbiter & hidden node (#1106)
- [4e194f0a](https://github.com/kubedb/apimachinery/commit/4e194f0a2) Implement validator for autoscalers (#1105)
- [6a454592](https://github.com/kubedb/apimachinery/commit/6a4545928) Add kubestash controller for changing kubeDB phase (#1096)
- [44757753](https://github.com/kubedb/apimachinery/commit/447577539) Ignore validators.autoscaling.kubedb.com webhook handlers



## [kubedb/cli](https://github.com/kubedb/cli)

### [v0.41.0-beta.1](https://github.com/kubedb/cli/releases/tag/v0.41.0-beta.1)

- [234b7051](https://github.com/kubedb/cli/commit/234b7051) Prepare for release v0.41.0-beta.1 (#748)
- [1ebdd532](https://github.com/kubedb/cli/commit/1ebdd532) Update deps



## [kubedb/druid](https://github.com/kubedb/druid)

### [v0.0.1](https://github.com/kubedb/druid/releases/tag/v0.0.1)

- [46c4387](https://github.com/kubedb/druid/commit/46c4387) Prepare for release v0.0.1 (#2)
- [3a9e0dd](https://github.com/kubedb/druid/commit/3a9e0dd) Add Druid Controller (#1)



## [kubedb/elasticsearch](https://github.com/kubedb/elasticsearch)

### [v0.41.0-beta.1](https://github.com/kubedb/elasticsearch/releases/tag/v0.41.0-beta.1)

- [c410b39f](https://github.com/kubedb/elasticsearch/commit/c410b39f5) Prepare for release v0.41.0-beta.1 (#699)
- [3394f1d1](https://github.com/kubedb/elasticsearch/commit/3394f1d13) Use ptr.Deref(); Update deps
- [f00ee052](https://github.com/kubedb/elasticsearch/commit/f00ee052e) Update ci & makefile for crd-manager (#698)
- [e37e6d63](https://github.com/kubedb/elasticsearch/commit/e37e6d631) Add catalog client in scheme. (#697)
- [a46bfd41](https://github.com/kubedb/elasticsearch/commit/a46bfd41b) Add Support for DB phase change for restoring using KubeStash (#696)
- [9cbac2fc](https://github.com/kubedb/elasticsearch/commit/9cbac2fc4) Update makefile for dynamic crd installer (#695)



## [kubedb/elasticsearch-restic-plugin](https://github.com/kubedb/elasticsearch-restic-plugin)

### [v0.4.0-beta.1](https://github.com/kubedb/elasticsearch-restic-plugin/releases/tag/v0.4.0-beta.1)

- [584dfd9](https://github.com/kubedb/elasticsearch-restic-plugin/commit/584dfd9) Prepare for release v0.4.0-beta.1 (#16)



## [kubedb/ferretdb](https://github.com/kubedb/ferretdb)

### [v0.0.1](https://github.com/kubedb/ferretdb/releases/tag/v0.0.1)

- [68618ec](https://github.com/kubedb/ferretdb/commit/68618ec) Prepare for release v0.0.1 (#4)
- [9443437](https://github.com/kubedb/ferretdb/commit/9443437) Add github workflow files (#3)
- [0287771](https://github.com/kubedb/ferretdb/commit/0287771) Add FerretDB Controller (#2)



## [kubedb/kafka](https://github.com/kubedb/kafka)

### [v0.12.0-beta.1](https://github.com/kubedb/kafka/releases/tag/v0.12.0-beta.1)

- [34f4967f](https://github.com/kubedb/kafka/commit/34f4967f) Prepare for release v0.12.0-beta.1 (#68)
- [7176931c](https://github.com/kubedb/kafka/commit/7176931c) Move Kafka Podtemplate to ofshoot-api v2 (#66)
- [9454adf6](https://github.com/kubedb/kafka/commit/9454adf6) Update ci & makefile for crd-manager (#67)
- [fda770d8](https://github.com/kubedb/kafka/commit/fda770d8) Add kafka connector controller (#65)
- [6ed0ccd4](https://github.com/kubedb/kafka/commit/6ed0ccd4) Add Kafka connect  controller (#44)
- [18e9a45c](https://github.com/kubedb/kafka/commit/18e9a45c) update deps (#64)
- [a7dfb409](https://github.com/kubedb/kafka/commit/a7dfb409) Update makefile for dynamic crd installer (#63)



## [kubedb/kubedb-manifest-plugin](https://github.com/kubedb/kubedb-manifest-plugin)

### [v0.4.0-beta.1](https://github.com/kubedb/kubedb-manifest-plugin/releases/tag/v0.4.0-beta.1)

- [c77b4ae](https://github.com/kubedb/kubedb-manifest-plugin/commit/c77b4ae) Prepare for release v0.4.0-beta.1 (#37)
- [6a8a822](https://github.com/kubedb/kubedb-manifest-plugin/commit/6a8a822) Update component name (#35)



## [kubedb/mariadb-archiver](https://github.com/kubedb/mariadb-archiver)

### [v0.1.0-beta.1](https://github.com/kubedb/mariadb-archiver/releases/tag/v0.1.0-beta.1)

- [e8564fe](https://github.com/kubedb/mariadb-archiver/commit/e8564fe) Prepare for release v0.1.0-beta.1 (#5)
- [e5e8945](https://github.com/kubedb/mariadb-archiver/commit/e5e8945) Don't use fail-fast



## [kubedb/mariadb-coordinator](https://github.com/kubedb/mariadb-coordinator)

### [v0.21.0-beta.1](https://github.com/kubedb/mariadb-coordinator/releases/tag/v0.21.0-beta.1)

- [1c30e710](https://github.com/kubedb/mariadb-coordinator/commit/1c30e710) Prepare for release v0.21.0-beta.1 (#101)



## [kubedb/mariadb-csi-snapshotter-plugin](https://github.com/kubedb/mariadb-csi-snapshotter-plugin)

### [v0.1.0-beta.1](https://github.com/kubedb/mariadb-csi-snapshotter-plugin/releases/tag/v0.1.0-beta.1)

- [adac38d](https://github.com/kubedb/mariadb-csi-snapshotter-plugin/commit/adac38d) Prepare for release v0.1.0-beta.1 (#5)



## [kubedb/memcached](https://github.com/kubedb/memcached)

### [v0.34.0-beta.1](https://github.com/kubedb/memcached/releases/tag/v0.34.0-beta.1)

- [754ba398](https://github.com/kubedb/memcached/commit/754ba398) Prepare for release v0.34.0-beta.1 (#418)
- [abd9dbb6](https://github.com/kubedb/memcached/commit/abd9dbb6) Incorporate with apimachinery package name change from stash to restore (#417)



## [kubedb/mongodb-csi-snapshotter-plugin](https://github.com/kubedb/mongodb-csi-snapshotter-plugin)

### [v0.2.0-beta.1](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/releases/tag/v0.2.0-beta.1)

- [5680265](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/5680265) Prepare for release v0.2.0-beta.1 (#12)
- [72693c8](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/72693c8) Fix component driver status (#11)
- [0ea73ee](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/0ea73ee) Update deps (#10)



## [kubedb/mongodb-restic-plugin](https://github.com/kubedb/mongodb-restic-plugin)

### [v0.4.0-beta.1](https://github.com/kubedb/mongodb-restic-plugin/releases/tag/v0.4.0-beta.1)

- [6ae8ae2](https://github.com/kubedb/mongodb-restic-plugin/commit/6ae8ae2) Prepare for release v0.4.0-beta.1 (#23)
- [d8e1636](https://github.com/kubedb/mongodb-restic-plugin/commit/d8e1636) Reorder the execution of cleanup funcs (#22)



## [kubedb/mysql-archiver](https://github.com/kubedb/mysql-archiver)

### [v0.2.0-beta.1](https://github.com/kubedb/mysql-archiver/releases/tag/v0.2.0-beta.1)

- [e5bdae3](https://github.com/kubedb/mysql-archiver/commit/e5bdae3) Prepare for release v0.2.0-beta.1 (#15)
- [7ef752c](https://github.com/kubedb/mysql-archiver/commit/7ef752c) Refactor + Cleanup wal-g example files (#14)
- [5857a8d](https://github.com/kubedb/mysql-archiver/commit/5857a8d) Don't use fail-fast



## [kubedb/mysql-coordinator](https://github.com/kubedb/mysql-coordinator)

### [v0.19.0-beta.1](https://github.com/kubedb/mysql-coordinator/releases/tag/v0.19.0-beta.1)

- [59a11671](https://github.com/kubedb/mysql-coordinator/commit/59a11671) Prepare for release v0.19.0-beta.1 (#98)



## [kubedb/mysql-restic-plugin](https://github.com/kubedb/mysql-restic-plugin)

### [v0.4.0-beta.1](https://github.com/kubedb/mysql-restic-plugin/releases/tag/v0.4.0-beta.1)

- [105888a](https://github.com/kubedb/mysql-restic-plugin/commit/105888a) Prepare for release v0.4.0-beta.1 (#21)
- [b42d0cf](https://github.com/kubedb/mysql-restic-plugin/commit/b42d0cf) Removed `--all-databases` flag for restoring (#20)



## [kubedb/percona-xtradb](https://github.com/kubedb/percona-xtradb)

### [v0.28.0-beta.1](https://github.com/kubedb/percona-xtradb/releases/tag/v0.28.0-beta.1)

- [475a5e32](https://github.com/kubedb/percona-xtradb/commit/475a5e328) Prepare for release v0.28.0-beta.1 (#348)
- [4c1380ab](https://github.com/kubedb/percona-xtradb/commit/4c1380ab7) Incorporate with apimachinery package name change from `stash` to `restore` (#347)



## [kubedb/percona-xtradb-coordinator](https://github.com/kubedb/percona-xtradb-coordinator)

### [v0.14.0-beta.1](https://github.com/kubedb/percona-xtradb-coordinator/releases/tag/v0.14.0-beta.1)

- [560bc5c3](https://github.com/kubedb/percona-xtradb-coordinator/commit/560bc5c3) Prepare for release v0.14.0-beta.1 (#58)



## [kubedb/pgpool](https://github.com/kubedb/pgpool)

### [v0.0.1](https://github.com/kubedb/pgpool/releases/tag/v0.0.1)

- [dbb333b](https://github.com/kubedb/pgpool/commit/dbb333b) Prepare for release v0.0.1 (#3)
- [b9c96e2](https://github.com/kubedb/pgpool/commit/b9c96e2) Pgpool operator (#2)
- [7c878e7](https://github.com/kubedb/pgpool/commit/7c878e7) C1:bootstrap Initialization project and basic api design
- [c437da3](https://github.com/kubedb/pgpool/commit/c437da3) C1:bootstrap Initialization project and basic api design



## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.41.0-beta.1](https://github.com/kubedb/postgres/releases/tag/v0.41.0-beta.1)

- [72a1ee29](https://github.com/kubedb/postgres/commit/72a1ee294) Prepare for release v0.41.0-beta.1 (#708)
- [026598f4](https://github.com/kubedb/postgres/commit/026598f44) Prepare for release v0.41.0-beta.1 (#707)
- [8af305aa](https://github.com/kubedb/postgres/commit/8af305aa4) Use ptr.Deref(); Update deps
- [c7c0652d](https://github.com/kubedb/postgres/commit/c7c0652dc) Update ci & makefile for crd-manager (#706)
- [d468bdb3](https://github.com/kubedb/postgres/commit/d468bdb34) Fix wal backup directory (#705)
- [c6992bed](https://github.com/kubedb/postgres/commit/c6992bed8) Add Support for DB phase change for restoring using KubeStash (#704)



## [kubedb/postgres-archiver](https://github.com/kubedb/postgres-archiver)

### [v0.2.0-beta.1](https://github.com/kubedb/postgres-archiver/releases/tag/v0.2.0-beta.1)

- [c4405c1](https://github.com/kubedb/postgres-archiver/commit/c4405c1) Prepare for release v0.2.0-beta.1 (#17)



## [kubedb/postgres-csi-snapshotter-plugin](https://github.com/kubedb/postgres-csi-snapshotter-plugin)

### [v0.2.0-beta.1](https://github.com/kubedb/postgres-csi-snapshotter-plugin/releases/tag/v0.2.0-beta.1)

- [dc4f85e](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/dc4f85e) Prepare for release v0.2.0-beta.1 (#15)
- [098365a](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/098365a) Update README.md (#14)
- [5ef571f](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/5ef571f) Update deps (#13)



## [kubedb/postgres-restic-plugin](https://github.com/kubedb/postgres-restic-plugin)

### [v0.4.0-beta.1](https://github.com/kubedb/postgres-restic-plugin/releases/tag/v0.4.0-beta.1)

- [4ed2b4a](https://github.com/kubedb/postgres-restic-plugin/commit/4ed2b4a) Prepare for release v0.4.0-beta.1 (#14)



## [kubedb/rabbitmq](https://github.com/kubedb/rabbitmq)

### [v0.0.1](https://github.com/kubedb/rabbitmq/releases/tag/v0.0.1)

- [48d2ec95](https://github.com/kubedb/rabbitmq/commit/48d2ec95) Prepare for release v0.0.1 (#2)
- [d9dcec0f](https://github.com/kubedb/rabbitmq/commit/d9dcec0f) Add Rabbitmq controller (#1)
- [6844a9cf](https://github.com/kubedb/rabbitmq/commit/6844a9cf) Add Appscode Community license and release workflows



## [kubedb/redis](https://github.com/kubedb/redis)

### [v0.34.0-beta.1](https://github.com/kubedb/redis/releases/tag/v0.34.0-beta.1)

- [01290634](https://github.com/kubedb/redis/commit/01290634) Prepare for release v0.34.0-beta.1 (#517)
- [e51f93e1](https://github.com/kubedb/redis/commit/e51f93e1) Fix panic (#516)
- [dc75c163](https://github.com/kubedb/redis/commit/dc75c163) Update ci & makefile for crd-manager (#515)
- [09688f35](https://github.com/kubedb/redis/commit/09688f35) Add Support for DB phase change for restoring using KubeStash (#514)



## [kubedb/redis-coordinator](https://github.com/kubedb/redis-coordinator)

### [v0.20.0-beta.1](https://github.com/kubedb/redis-coordinator/releases/tag/v0.20.0-beta.1)

- [fd3b2112](https://github.com/kubedb/redis-coordinator/commit/fd3b2112) Prepare for release v0.20.0-beta.1 (#89)



## [kubedb/replication-mode-detector](https://github.com/kubedb/replication-mode-detector)

### [v0.28.0-beta.1](https://github.com/kubedb/replication-mode-detector/releases/tag/v0.28.0-beta.1)

- [f948a650](https://github.com/kubedb/replication-mode-detector/commit/f948a650) Prepare for release v0.28.0-beta.1 (#253)



## [kubedb/singlestore](https://github.com/kubedb/singlestore)

### [v0.0.1](https://github.com/kubedb/singlestore/releases/tag/v0.0.1)

- [8feeb79](https://github.com/kubedb/singlestore/commit/8feeb79) Prepare for release v0.0.1 (#5)
- [fb79ff9](https://github.com/kubedb/singlestore/commit/fb79ff9) Add Singlestore Operator (#4)



## [kubedb/solr](https://github.com/kubedb/solr)

### [v0.0.1](https://github.com/kubedb/solr/releases/tag/v0.0.1)

- [58fb5b4](https://github.com/kubedb/solr/commit/58fb5b4) Prepare for release v0.0.1 (#1)
- [6b7c3ef](https://github.com/kubedb/solr/commit/6b7c3ef) Add release workflows
- [9db6c84](https://github.com/kubedb/solr/commit/9db6c84) Disable ferret db in catalog helm command. (#5)
- [19553e7](https://github.com/kubedb/solr/commit/19553e7) Add solr operator. (#3)
- [ff4b9ae](https://github.com/kubedb/solr/commit/ff4b9ae) Reset master (#4)
- [7804b0a](https://github.com/kubedb/solr/commit/7804b0a) Add initial controller implementation (#2)



## [kubedb/tests](https://github.com/kubedb/tests)

### [v0.26.0-beta.1](https://github.com/kubedb/tests/releases/tag/v0.26.0-beta.1)

- [3cfc1212](https://github.com/kubedb/tests/commit/3cfc1212) Prepare for release v0.26.0-beta.1 (#292)
- [b810e690](https://github.com/kubedb/tests/commit/b810e690) increase cpu limit for vertical scaling (#289)
- [c43985ba](https://github.com/kubedb/tests/commit/c43985ba) Change dashboard api group (#291)
- [1b96881e](https://github.com/kubedb/tests/commit/1b96881e) Fix error logging
- [33f78143](https://github.com/kubedb/tests/commit/33f78143) forceCleanup PVCs for mongo (#288)
- [0dcd3e38](https://github.com/kubedb/tests/commit/0dcd3e38) Add PostgreSQL logical replication tests  (#202)
- [2f403c85](https://github.com/kubedb/tests/commit/2f403c85) Find profiles in array, Don't match with string (#286)
- [5aca2293](https://github.com/kubedb/tests/commit/5aca2293) Give time to PDB status to be updated (#285)



