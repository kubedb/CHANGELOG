# KubeDB v2023.12.11 (2023-12-08)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.38.0](https://github.com/kubedb/apimachinery/releases/tag/v0.38.0)

- [566c617f](https://github.com/kubedb/apimachinery/commit/566c617f) Update kafka webhook mutating verb (#1084)
- [c6ac8def](https://github.com/kubedb/apimachinery/commit/c6ac8def) Add IPS_LOCK and SYS_RESOURCE (#1083)
- [96238937](https://github.com/kubedb/apimachinery/commit/96238937) Add Postgres arbiter spec (#1082)
- [24013ada](https://github.com/kubedb/apimachinery/commit/24013ada) Fix update-crds wf
- [de0bb4e2](https://github.com/kubedb/apimachinery/commit/de0bb4e2) Update kubestash apimachienry
- [545731a9](https://github.com/kubedb/apimachinery/commit/545731a9) Add default KubeBuilder client (#1081)
- [f260aa8e](https://github.com/kubedb/apimachinery/commit/f260aa8e) Add SecurityContext field in catalogs; Set default accordingly (#1080)
- [e070a3ae](https://github.com/kubedb/apimachinery/commit/e070a3ae) Do not default the seccompProfile (#1079)
- [29c96031](https://github.com/kubedb/apimachinery/commit/29c96031) Set Default Security Context for MariaDB (#1077)
- [fc35d376](https://github.com/kubedb/apimachinery/commit/fc35d376) Set default SecurityContext for mysql (#1070)
- [ee71aca0](https://github.com/kubedb/apimachinery/commit/ee71aca0) Update dependencies
- [93b5ba51](https://github.com/kubedb/apimachinery/commit/93b5ba51) add encriptSecret to postgresAchiver (#1078)
- [2b06b6e5](https://github.com/kubedb/apimachinery/commit/2b06b6e5) Add mongodb & postgres archiver (#1016)
- [47793c9a](https://github.com/kubedb/apimachinery/commit/47793c9a) Set default  SecurityContext for Elasticsearch. (#1072)
- [90567b46](https://github.com/kubedb/apimachinery/commit/90567b46) Set default SecurityContext for Kafka (#1068)
- [449a4e00](https://github.com/kubedb/apimachinery/commit/449a4e00) Remove redundant helper functions for Kafka and Update constants (#1074)
- [b28463f4](https://github.com/kubedb/apimachinery/commit/b28463f4) Set fsGroup to 999 to avoid mountedPath's files permission issue in different storageClass (#1075)
- [8e497b92](https://github.com/kubedb/apimachinery/commit/8e497b92) Set Default Security Context for Redis (#1073)
- [88ab93c7](https://github.com/kubedb/apimachinery/commit/88ab93c7) Set default SecurityContext for mongodb (#1067)
- [e7ac5d2e](https://github.com/kubedb/apimachinery/commit/e7ac5d2e) Set default for security Context for postgres (#1069)
- [f5de4a28](https://github.com/kubedb/apimachinery/commit/f5de4a28) Add support for init with git-sync; Add const (#1065)



## [kubedb/cli](https://github.com/kubedb/cli)

### [v0.38.0](https://github.com/kubedb/cli/releases/tag/v0.38.0)

- [8c968939](https://github.com/kubedb/cli/commit/8c968939) Prepare for release v0.38.0 (#739)
- [a99b2857](https://github.com/kubedb/cli/commit/a99b2857) Prepare for release v0.38.0-rc.1 (#738)
- [3a4dcc47](https://github.com/kubedb/cli/commit/3a4dcc47) Prepare for release v0.38.0-rc.0 (#737)



## [kubedb/elasticsearch](https://github.com/kubedb/elasticsearch)

### [v0.38.0](https://github.com/kubedb/elasticsearch/releases/tag/v0.38.0)

- [da1e77ef](https://github.com/kubedb/elasticsearch/commit/da1e77ef4) Prepare for release v0.38.0 (#681)
- [aec25e8a](https://github.com/kubedb/elasticsearch/commit/aec25e8a9) Add new version in elasticsearch yaml. (#679)
- [bd0fd357](https://github.com/kubedb/elasticsearch/commit/bd0fd357e) Prepare for release v0.38.0-rc.1 (#680)
- [6b2943f1](https://github.com/kubedb/elasticsearch/commit/6b2943f19) Prepare for release v0.38.0-rc.0 (#678)
- [7f1a37e1](https://github.com/kubedb/elasticsearch/commit/7f1a37e1a) Add prepare cluster installer before test runner (#677)
- [1d49f16d](https://github.com/kubedb/elasticsearch/commit/1d49f16d2) Remove `init-sysctl` container and add default containerSecurityContext (#676)
- [4bb15e48](https://github.com/kubedb/elasticsearch/commit/4bb15e48b) Update daily-opensearch workflow to provision v1.3.13



## [kubedb/elasticsearch-restic-plugin](https://github.com/kubedb/elasticsearch-restic-plugin)

### [v0.1.0](https://github.com/kubedb/elasticsearch-restic-plugin/releases/tag/v0.1.0)

- [1d1abdd](https://github.com/kubedb/elasticsearch-restic-plugin/commit/1d1abdd) Prepare for release v0.1.0 (#10)
- [f6a9e4c](https://github.com/kubedb/elasticsearch-restic-plugin/commit/f6a9e4c) Prepare for release v0.1.0-rc.1 (#9)
- [eb95c84](https://github.com/kubedb/elasticsearch-restic-plugin/commit/eb95c84) Prepare for release v0.1.0-rc.0 (#8)
- [fe82e1b](https://github.com/kubedb/elasticsearch-restic-plugin/commit/fe82e1b) Update component name (#7)
- [c155643](https://github.com/kubedb/elasticsearch-restic-plugin/commit/c155643) Update snapshot time (#6)
- [7093d5a](https://github.com/kubedb/elasticsearch-restic-plugin/commit/7093d5a) Move to kubedb org
- [a3a079e](https://github.com/kubedb/elasticsearch-restic-plugin/commit/a3a079e) Update deps (#5)
- [7a0fd38](https://github.com/kubedb/elasticsearch-restic-plugin/commit/7a0fd38) Refactor (#4)
- [b262635](https://github.com/kubedb/elasticsearch-restic-plugin/commit/b262635) Add support for backup and restore (#1)
- [50bde7e](https://github.com/kubedb/elasticsearch-restic-plugin/commit/50bde7e) Fix build
- [b9686b7](https://github.com/kubedb/elasticsearch-restic-plugin/commit/b9686b7) Prepare for release v0.1.0-rc.0 (#3)
- [ba0c0ed](https://github.com/kubedb/elasticsearch-restic-plugin/commit/ba0c0ed) Fix binary name
- [b0aa991](https://github.com/kubedb/elasticsearch-restic-plugin/commit/b0aa991) Use firecracker runner
- [a621400](https://github.com/kubedb/elasticsearch-restic-plugin/commit/a621400) Use Go 1.21 and restic 0.16.0
- [f08e4e8](https://github.com/kubedb/elasticsearch-restic-plugin/commit/f08e4e8) Use github runner to push docker image



## [kubedb/kafka](https://github.com/kubedb/kafka)

### [v0.9.0](https://github.com/kubedb/kafka/releases/tag/v0.9.0)

- [9c62eb1](https://github.com/kubedb/kafka/commit/9c62eb1) Prepare for release v0.9.0 (#52)
- [8ddb2b8](https://github.com/kubedb/kafka/commit/8ddb2b8) Remove hardcoded fsgroup from statefulset (#51)
- [0516c18](https://github.com/kubedb/kafka/commit/0516c18) Prepare for release v0.9.0-rc.1 (#50)
- [6554778](https://github.com/kubedb/kafka/commit/6554778) Set default KubeBuilder client (#49)
- [0770fff](https://github.com/kubedb/kafka/commit/0770fff) Prepare for release v0.9.0-rc.0 (#48)
- [ee3dcf5](https://github.com/kubedb/kafka/commit/ee3dcf5) Add condition for ssl.properties file (#47)
- [4bd632b](https://github.com/kubedb/kafka/commit/4bd632b) Reconfigure kafka for updated config properties (#45)
- [cc9795b](https://github.com/kubedb/kafka/commit/cc9795b) Upsert Init Containers with Kafka podtemplate.spec and update default test-profile (#43)
- [76e743c](https://github.com/kubedb/kafka/commit/76e743c) Update daily e2e tests yml (#42)



## [kubedb/kubedb-manifest-plugin](https://github.com/kubedb/kubedb-manifest-plugin)

### [v0.1.0](https://github.com/kubedb/kubedb-manifest-plugin/releases/tag/v0.1.0)

- [2dd0a52](https://github.com/kubedb/kubedb-manifest-plugin/commit/2dd0a52) Prepare for release v0.1.0 (#30)
- [4bd44b8](https://github.com/kubedb/kubedb-manifest-plugin/commit/4bd44b8) Prepare for release v0.1.0-rc.1 (#29)
- [bef777c](https://github.com/kubedb/kubedb-manifest-plugin/commit/bef777c) Prepare for release v0.1.0-rc.0 (#28)
- [46ad967](https://github.com/kubedb/kubedb-manifest-plugin/commit/46ad967) Remove redundancy (#27)
- [4eaf765](https://github.com/kubedb/kubedb-manifest-plugin/commit/4eaf765) Update snapshot time (#26)
- [e8ace42](https://github.com/kubedb/kubedb-manifest-plugin/commit/e8ace42) Fix plugin binary name
- [d4e3c34](https://github.com/kubedb/kubedb-manifest-plugin/commit/d4e3c34) Move to kubedb org
- [15770b2](https://github.com/kubedb/kubedb-manifest-plugin/commit/15770b2) Update deps (#25)
- [f50a3af](https://github.com/kubedb/kubedb-manifest-plugin/commit/f50a3af) Fix directory cleanup (#24)
- [d41eba7](https://github.com/kubedb/kubedb-manifest-plugin/commit/d41eba7) Refactor
- [0e154e7](https://github.com/kubedb/kubedb-manifest-plugin/commit/0e154e7) Fix release workflow
- [35c6b95](https://github.com/kubedb/kubedb-manifest-plugin/commit/35c6b95) Prepare for release v0.2.0-rc.0 (#22)
- [da97d9a](https://github.com/kubedb/kubedb-manifest-plugin/commit/da97d9a) Use gh runner token to publish image
- [592c51f](https://github.com/kubedb/kubedb-manifest-plugin/commit/592c51f) Use firecracker runner
- [008042d](https://github.com/kubedb/kubedb-manifest-plugin/commit/008042d) Use Go 1.21
- [985bcab](https://github.com/kubedb/kubedb-manifest-plugin/commit/985bcab) Set snapshot time after snapshot completed (#21)
- [6a8c682](https://github.com/kubedb/kubedb-manifest-plugin/commit/6a8c682) Refactor code (#20)
- [bcb944d](https://github.com/kubedb/kubedb-manifest-plugin/commit/bcb944d) Remove manifest option flags (#19)
- [5a47722](https://github.com/kubedb/kubedb-manifest-plugin/commit/5a47722) Fix secret restore issue (#18)
- [3ced8b7](https://github.com/kubedb/kubedb-manifest-plugin/commit/3ced8b7) Update `kmodules.xyz/client-go` version to `v0.25.27` (#17)
- [2ee1314](https://github.com/kubedb/kubedb-manifest-plugin/commit/2ee1314) Update Readme (#16)
- [42d0e52](https://github.com/kubedb/kubedb-manifest-plugin/commit/42d0e52) Set initial component status prior to backup and restore (#15)
- [31a64d6](https://github.com/kubedb/kubedb-manifest-plugin/commit/31a64d6) Remove redundant flags (#14)
- [a804ba8](https://github.com/kubedb/kubedb-manifest-plugin/commit/a804ba8) Pass Snapshot name for restore
- [99ca49f](https://github.com/kubedb/kubedb-manifest-plugin/commit/99ca49f) Set snapshot time, integrity and size (#12)
- [384bbb6](https://github.com/kubedb/kubedb-manifest-plugin/commit/384bbb6) Set backup error in component status + Refactor codebase (#11)
- [513eef5](https://github.com/kubedb/kubedb-manifest-plugin/commit/513eef5) Update for snapshot and restoresession API changes (#10)
- [4fb8f52](https://github.com/kubedb/kubedb-manifest-plugin/commit/4fb8f52) Add options for issuerref (#9)
- [2931d9e](https://github.com/kubedb/kubedb-manifest-plugin/commit/2931d9e) Update restic modules (#7)
- [3422ddf](https://github.com/kubedb/kubedb-manifest-plugin/commit/3422ddf) Fix bugs + Sync with updated snapshot api (#6)
- [b1a69b5](https://github.com/kubedb/kubedb-manifest-plugin/commit/b1a69b5) Prepare for release v0.1.0 (#5)
- [5344e9f](https://github.com/kubedb/kubedb-manifest-plugin/commit/5344e9f) Update modules (#4)
- [14b2797](https://github.com/kubedb/kubedb-manifest-plugin/commit/14b2797) Add CI badge
- [969eeda](https://github.com/kubedb/kubedb-manifest-plugin/commit/969eeda) Organize code structure (#3)
- [9fc3cbe](https://github.com/kubedb/kubedb-manifest-plugin/commit/9fc3cbe) Postgres manifest (#2)
- [8e2a56f](https://github.com/kubedb/kubedb-manifest-plugin/commit/8e2a56f) Merge pull request #1 from kubestash/mongodb-manifest
- [e80c1d0](https://github.com/kubedb/kubedb-manifest-plugin/commit/e80c1d0) update flag names.
- [80d3908](https://github.com/kubedb/kubedb-manifest-plugin/commit/80d3908) Add options for changing name in the restored files.
- [e7da42d](https://github.com/kubedb/kubedb-manifest-plugin/commit/e7da42d) Fix error.
- [70a0267](https://github.com/kubedb/kubedb-manifest-plugin/commit/70a0267) Sync with updated snapshot api
- [9d747d8](https://github.com/kubedb/kubedb-manifest-plugin/commit/9d747d8) Merge branch 'mongodb-manifest' of github.com:stashed/kubedb-manifest into mongodb-manifest
- [90e00e3](https://github.com/kubedb/kubedb-manifest-plugin/commit/90e00e3) Fix bugs.
- [9c3fc1e](https://github.com/kubedb/kubedb-manifest-plugin/commit/9c3fc1e) Sync with updated snapshot api
- [c321013](https://github.com/kubedb/kubedb-manifest-plugin/commit/c321013) update component path.
- [7f4bd17](https://github.com/kubedb/kubedb-manifest-plugin/commit/7f4bd17) Refactor.
- [2b61ff0](https://github.com/kubedb/kubedb-manifest-plugin/commit/2b61ff0) Specify component directory
- [6264cdf](https://github.com/kubedb/kubedb-manifest-plugin/commit/6264cdf) Support restoring particular mongo component.
- [0008570](https://github.com/kubedb/kubedb-manifest-plugin/commit/0008570) Fix restore component phase updating.
- [8bd4c95](https://github.com/kubedb/kubedb-manifest-plugin/commit/8bd4c95) Fix restore manifests.
- [7eda9f9](https://github.com/kubedb/kubedb-manifest-plugin/commit/7eda9f9) Update Snapshot phase calculation.
- [a2b52d2](https://github.com/kubedb/kubedb-manifest-plugin/commit/a2b52d2) Add core to runtime scheme.
- [9bd6bd5](https://github.com/kubedb/kubedb-manifest-plugin/commit/9bd6bd5) Fix bugs.
- [9e08774](https://github.com/kubedb/kubedb-manifest-plugin/commit/9e08774) Fix build
- [01225c6](https://github.com/kubedb/kubedb-manifest-plugin/commit/01225c6) Update module path
- [45d0e45](https://github.com/kubedb/kubedb-manifest-plugin/commit/45d0e45) updated flags.
- [fb0282f](https://github.com/kubedb/kubedb-manifest-plugin/commit/fb0282f) update docker file.
- [ad4c004](https://github.com/kubedb/kubedb-manifest-plugin/commit/ad4c004) refactor.
- [8f71d3a](https://github.com/kubedb/kubedb-manifest-plugin/commit/8f71d3a) Fix build
- [115ef23](https://github.com/kubedb/kubedb-manifest-plugin/commit/115ef23) update makefile.
- [a274690](https://github.com/kubedb/kubedb-manifest-plugin/commit/a274690) update backup and restore.
- [cff449f](https://github.com/kubedb/kubedb-manifest-plugin/commit/cff449f) Use yaml pkg from k8s.io.
- [dcbb399](https://github.com/kubedb/kubedb-manifest-plugin/commit/dcbb399) Use restic package from KubeStash.
- [596a498](https://github.com/kubedb/kubedb-manifest-plugin/commit/596a498) fix restore implementation.
- [6ebc19b](https://github.com/kubedb/kubedb-manifest-plugin/commit/6ebc19b) Implement restore.
- [3e8a869](https://github.com/kubedb/kubedb-manifest-plugin/commit/3e8a869) Start implementing restore.
- [e841113](https://github.com/kubedb/kubedb-manifest-plugin/commit/e841113) Add backup methods for mongodb.
- [b5961f7](https://github.com/kubedb/kubedb-manifest-plugin/commit/b5961f7) Continue implementing backup.
- [d943f6a](https://github.com/kubedb/kubedb-manifest-plugin/commit/d943f6a) Implement manifest backup for MongoDB.
- [e644c67](https://github.com/kubedb/kubedb-manifest-plugin/commit/e644c67) Implement kubedb-manifest plugin to MongoDB manifests.



## [kubedb/mariadb](https://github.com/kubedb/mariadb)

### [v0.22.0](https://github.com/kubedb/mariadb/releases/tag/v0.22.0)

- [b6995945](https://github.com/kubedb/mariadb/commit/b6995945) Prepare for release v0.22.0 (#237)
- [25018ad7](https://github.com/kubedb/mariadb/commit/25018ad7) Fix Statefulset Security Context Assign (#236)
- [9c157c66](https://github.com/kubedb/mariadb/commit/9c157c66) Prepare for release v0.22.0-rc.1 (#235)
- [1d0c2579](https://github.com/kubedb/mariadb/commit/1d0c2579) Pass version in SetDefaults func (#234)
- [e360fd82](https://github.com/kubedb/mariadb/commit/e360fd82) Prepare for release v0.22.0-rc.0 (#233)
- [3956f18c](https://github.com/kubedb/mariadb/commit/3956f18c) Set Default Security Context for MariaDB (#232)



## [kubedb/mariadb-archiver](https://github.com/kubedb/mariadb-archiver)

### [v0.1.0](https://github.com/kubedb/mariadb-archiver/releases/tag/v0.1.0)

- [a014ffc](https://github.com/kubedb/mariadb-archiver/commit/a014ffc) Prepare for release v0.1.0 (#5)
- [a2afbc9](https://github.com/kubedb/mariadb-archiver/commit/a2afbc9) Prepare for release v0.1.0-rc.1 (#4)
- [65fd6bf](https://github.com/kubedb/mariadb-archiver/commit/65fd6bf) Prepare for release v0.1.0-rc.0 (#3)



## [kubedb/mariadb-coordinator](https://github.com/kubedb/mariadb-coordinator)

### [v0.18.0](https://github.com/kubedb/mariadb-coordinator/releases/tag/v0.18.0)

- [ec9782e7](https://github.com/kubedb/mariadb-coordinator/commit/ec9782e7) Prepare for release v0.18.0 (#94)
- [118bcda4](https://github.com/kubedb/mariadb-coordinator/commit/118bcda4) Prepare for release v0.18.0-rc.1 (#93)
- [bf515bfa](https://github.com/kubedb/mariadb-coordinator/commit/bf515bfa) Prepare for release v0.18.0-rc.0 (#92)



## [kubedb/memcached](https://github.com/kubedb/memcached)

### [v0.31.0](https://github.com/kubedb/memcached/releases/tag/v0.31.0)

- [da52b0a5](https://github.com/kubedb/memcached/commit/da52b0a5) Prepare for release v0.31.0 (#407)
- [fab2a879](https://github.com/kubedb/memcached/commit/fab2a879) Prepare for release v0.31.0-rc.1 (#406)
- [e44be0a6](https://github.com/kubedb/memcached/commit/e44be0a6) Prepare for release v0.31.0-rc.0 (#405)



## [kubedb/mongodb-csi-snapshotter-plugin](https://github.com/kubedb/mongodb-csi-snapshotter-plugin)

### [v0.1.0](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/releases/tag/v0.1.0)




## [kubedb/mysql](https://github.com/kubedb/mysql)

### [v0.31.0](https://github.com/kubedb/mysql/releases/tag/v0.31.0)

- [9094f699](https://github.com/kubedb/mysql/commit/9094f699) Prepare for release v0.31.0 (#576)
- [fd0ebe09](https://github.com/kubedb/mysql/commit/fd0ebe09) Fix Statefulset Security Context Assign (#575)
- [79cb58c1](https://github.com/kubedb/mysql/commit/79cb58c1) Prepare for release v0.31.0-rc.1 (#574)
- [e5b37c00](https://github.com/kubedb/mysql/commit/e5b37c00) Pass version in SetDefaults func (#573)
- [3c005b51](https://github.com/kubedb/mysql/commit/3c005b51) Prepare for release v0.31.0-rc.0 (#572)
- [bcdfaf4a](https://github.com/kubedb/mysql/commit/bcdfaf4a) Set Default Security Context for MySQL (#571)
- [9009bcac](https://github.com/kubedb/mysql/commit/9009bcac) Add git sync constants from apimachinery (#570)



## [kubedb/mysql-archiver](https://github.com/kubedb/mysql-archiver)

### [v0.1.0](https://github.com/kubedb/mysql-archiver/releases/tag/v0.1.0)

- [721eaa8](https://github.com/kubedb/mysql-archiver/commit/721eaa8) Prepare for release v0.1.0 (#4)
- [8c65d14](https://github.com/kubedb/mysql-archiver/commit/8c65d14) Prepare for release v0.1.0-rc.1 (#3)
- [f79286a](https://github.com/kubedb/mysql-archiver/commit/f79286a) Prepare for release v0.1.0-rc.0 (#2)
- [dcd2e30](https://github.com/kubedb/mysql-archiver/commit/dcd2e30) Fix wal-g binary



## [kubedb/mysql-coordinator](https://github.com/kubedb/mysql-coordinator)

### [v0.16.0](https://github.com/kubedb/mysql-coordinator/releases/tag/v0.16.0)

- [c93152ea](https://github.com/kubedb/mysql-coordinator/commit/c93152ea) Prepare for release v0.16.0 (#91)
- [63cb0a33](https://github.com/kubedb/mysql-coordinator/commit/63cb0a33) Prepare for release v0.16.0-rc.1 (#90)
- [b5e481fc](https://github.com/kubedb/mysql-coordinator/commit/b5e481fc) Prepare for release v0.16.0-rc.0 (#89)



## [kubedb/mysql-restic-plugin](https://github.com/kubedb/mysql-restic-plugin)

### [v0.1.0](https://github.com/kubedb/mysql-restic-plugin/releases/tag/v0.1.0)

- [9ed9b45](https://github.com/kubedb/mysql-restic-plugin/commit/9ed9b45) Prepare for release v0.1.0 (#14)
- [f77476b](https://github.com/kubedb/mysql-restic-plugin/commit/f77476b) Prepare for release v0.1.0-rc.1 (#13)
- [81ceb55](https://github.com/kubedb/mysql-restic-plugin/commit/81ceb55) Add `databases` flag (#12)
- [b255e47](https://github.com/kubedb/mysql-restic-plugin/commit/b255e47) Prepare for release v0.1.0-rc.0 (#11)
- [9a17360](https://github.com/kubedb/mysql-restic-plugin/commit/9a17360) Set DB version from env if empty (#10)
- [c67ba7c](https://github.com/kubedb/mysql-restic-plugin/commit/c67ba7c) Update snapshot time (#9)
- [abef89e](https://github.com/kubedb/mysql-restic-plugin/commit/abef89e) Fix binary name
- [db1bbbf](https://github.com/kubedb/mysql-restic-plugin/commit/db1bbbf) Move to kubedb org
- [746d13e](https://github.com/kubedb/mysql-restic-plugin/commit/746d13e) Update deps (#8)
- [569533a](https://github.com/kubedb/mysql-restic-plugin/commit/569533a) Add version flag + Refactor (#6)
- [f0abd94](https://github.com/kubedb/mysql-restic-plugin/commit/f0abd94) Prepare for release v0.1.0-rc.0 (#7)
- [01bff62](https://github.com/kubedb/mysql-restic-plugin/commit/01bff62) Remove arm64 image support
- [277fda8](https://github.com/kubedb/mysql-restic-plugin/commit/277fda8) Build docker images for each db version (#5)
- [94f000d](https://github.com/kubedb/mysql-restic-plugin/commit/94f000d) Use Go 1.21
- [2e4f30d](https://github.com/kubedb/mysql-restic-plugin/commit/2e4f30d) Update Readme (#4)
- [272c8f9](https://github.com/kubedb/mysql-restic-plugin/commit/272c8f9) Add support for mysql backup and restore (#1)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.16.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.16.0)




## [kubedb/percona-xtradb](https://github.com/kubedb/percona-xtradb)

### [v0.25.0](https://github.com/kubedb/percona-xtradb/releases/tag/v0.25.0)

- [2780eea8](https://github.com/kubedb/percona-xtradb/commit/2780eea8) Prepare for release v0.25.0 (#335)
- [3a15a15e](https://github.com/kubedb/percona-xtradb/commit/3a15a15e) Fix Statefulset Security Context Assign (#334)
- [bad0b334](https://github.com/kubedb/percona-xtradb/commit/bad0b334) Prepare for release v0.25.0-rc.1 (#333)
- [b8447936](https://github.com/kubedb/percona-xtradb/commit/b8447936) Pass version in SetDefaults func (#332)
- [d374a542](https://github.com/kubedb/percona-xtradb/commit/d374a542) Prepare for release v0.25.0-rc.0 (#331)



## [kubedb/percona-xtradb-coordinator](https://github.com/kubedb/percona-xtradb-coordinator)

### [v0.11.0](https://github.com/kubedb/percona-xtradb-coordinator/releases/tag/v0.11.0)

- [44e0fea](https://github.com/kubedb/percona-xtradb-coordinator/commit/44e0fea) Prepare for release v0.11.0 (#51)
- [7a66da3](https://github.com/kubedb/percona-xtradb-coordinator/commit/7a66da3) Prepare for release v0.11.0-rc.1 (#50)
- [69e7d1e](https://github.com/kubedb/percona-xtradb-coordinator/commit/69e7d1e) Prepare for release v0.11.0-rc.0 (#49)



## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.38.0](https://github.com/kubedb/postgres/releases/tag/v0.38.0)

- [8fe3fe0e](https://github.com/kubedb/postgres/commit/8fe3fe0e1) Prepare for release v0.38.0 (#687)
- [7a853e00](https://github.com/kubedb/postgres/commit/7a853e001) Add postgres arbiter custom size limit (#686)
- [0e493a1c](https://github.com/kubedb/postgres/commit/0e493a1cd) Prepare for release v0.38.0-rc.1 (#685)
- [8738ad73](https://github.com/kubedb/postgres/commit/8738ad73e) Prepare for release v0.38.0-rc.0 (#684)
- [adb69b02](https://github.com/kubedb/postgres/commit/adb69b02e) Implement PostgreSQL archiver (#628)
- [668e15dd](https://github.com/kubedb/postgres/commit/668e15dd4) Remove test directory (#683)
- [d857c354](https://github.com/kubedb/postgres/commit/d857c354a) added postgres arbiter support (#677)
- [8fc98e8e](https://github.com/kubedb/postgres/commit/8fc98e8ed) Fixed a bug for init container (#681)
- [a2b408ff](https://github.com/kubedb/postgres/commit/a2b408ffb) Bugfix for security context (#680)
- [fb14015e](https://github.com/kubedb/postgres/commit/fb14015e9) added nightly yml for postgres (#679)



## [kubedb/postgres-archiver](https://github.com/kubedb/postgres-archiver)

### [v0.1.0](https://github.com/kubedb/postgres-archiver/releases/tag/v0.1.0)




## [kubedb/postgres-csi-snapshotter-plugin](https://github.com/kubedb/postgres-csi-snapshotter-plugin)

### [v0.1.0](https://github.com/kubedb/postgres-csi-snapshotter-plugin/releases/tag/v0.1.0)

- [31f5fc5](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/31f5fc5) Prepare for release v0.1.0 (#8)
- [57a7bdf](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/57a7bdf) Prepare for release v0.1.0-rc.1 (#7)
- [02a45da](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/02a45da) Prepare for release v0.1.0-rc.0 (#6)
- [1a6457c](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/1a6457c) Update flags and deps + Refactor (#5)
- [f32b56b](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/f32b56b) Delete .idea folder
- [e7f8135](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/e7f8135) clean up (#4)
- [06e7e70](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/06e7e70) clean up (#3)



## [kubedb/postgres-restic-plugin](https://github.com/kubedb/postgres-restic-plugin)

### [v0.1.0](https://github.com/kubedb/postgres-restic-plugin/releases/tag/v0.1.0)

- [d5524a7](https://github.com/kubedb/postgres-restic-plugin/commit/d5524a7) Prepare for release v0.1.0 (#7)
- [584bbad](https://github.com/kubedb/postgres-restic-plugin/commit/584bbad) Prepare for release v0.1.0-rc.1 (#6)
- [da1ecd7](https://github.com/kubedb/postgres-restic-plugin/commit/da1ecd7) Refactor (#5)
- [8208814](https://github.com/kubedb/postgres-restic-plugin/commit/8208814) Prepare for release v0.1.0-rc.0 (#4)
- [a56fcfa](https://github.com/kubedb/postgres-restic-plugin/commit/a56fcfa) Move to kubedb org (#3)
- [e8928c7](https://github.com/kubedb/postgres-restic-plugin/commit/e8928c7) Added postgres addon for kubestash (#2)
- [7c55105](https://github.com/kubedb/postgres-restic-plugin/commit/7c55105) Prepare for release v0.1.0-rc.0 (#1)
- [19eff67](https://github.com/kubedb/postgres-restic-plugin/commit/19eff67) Use gh runner token to publish docker image
- [6a71410](https://github.com/kubedb/postgres-restic-plugin/commit/6a71410) Use firecracker runner
- [e278d71](https://github.com/kubedb/postgres-restic-plugin/commit/e278d71) Use Go 1.21
- [4899879](https://github.com/kubedb/postgres-restic-plugin/commit/4899879) Update readme + cleanup



## [kubedb/redis](https://github.com/kubedb/redis)

### [v0.31.0](https://github.com/kubedb/redis/releases/tag/v0.31.0)

- [de7b9f50](https://github.com/kubedb/redis/commit/de7b9f50) Prepare for release v0.31.0 (#500)
- [ffe5982e](https://github.com/kubedb/redis/commit/ffe5982e) Fix DB update from version for RedisSentinel (#499)
- [9f4f26ac](https://github.com/kubedb/redis/commit/9f4f26ac) Fix Statefulset Security Context Assign (#498)
- [a3d4b7b8](https://github.com/kubedb/redis/commit/a3d4b7b8) Prepare for release v0.31.0-rc.1 (#497)
- [bb101b6a](https://github.com/kubedb/redis/commit/bb101b6a) Pass version in SetDefaults func (#496)
- [966f14ca](https://github.com/kubedb/redis/commit/966f14ca) Prepare for release v0.31.0-rc.0 (#495)
- [b72d8319](https://github.com/kubedb/redis/commit/b72d8319) Run Redis and RedisSentinel as non root (#494)



## [kubedb/redis-coordinator](https://github.com/kubedb/redis-coordinator)

### [v0.17.0](https://github.com/kubedb/redis-coordinator/releases/tag/v0.17.0)

- [34f65113](https://github.com/kubedb/redis-coordinator/commit/34f65113) Prepare for release v0.17.0 (#82)
- [7e5fbf31](https://github.com/kubedb/redis-coordinator/commit/7e5fbf31) Prepare for release v0.17.0-rc.1 (#81)
- [9f724e43](https://github.com/kubedb/redis-coordinator/commit/9f724e43) Prepare for release v0.17.0-rc.0 (#80)



## [kubedb/replication-mode-detector](https://github.com/kubedb/replication-mode-detector)

### [v0.25.0](https://github.com/kubedb/replication-mode-detector/releases/tag/v0.25.0)

- [5189e007](https://github.com/kubedb/replication-mode-detector/commit/5189e007) Prepare for release v0.25.0 (#246)
- [758906fe](https://github.com/kubedb/replication-mode-detector/commit/758906fe) Prepare for release v0.25.0-rc.1 (#245)
- [77886a28](https://github.com/kubedb/replication-mode-detector/commit/77886a28) Prepare for release v0.25.0-rc.0 (#244)


