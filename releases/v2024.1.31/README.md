# KubeDB v2024.1.31 (2024-02-01)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.41.0](https://github.com/kubedb/apimachinery/releases/tag/v0.41.0)

- [447a890a](https://github.com/kubedb/apimachinery/commit/447a890af) Update kubestash
- [a81b9dc2](https://github.com/kubedb/apimachinery/commit/a81b9dc28) Increase CPU resource for mongo versions >= 6 (#1140)
- [c711b3ab](https://github.com/kubedb/apimachinery/commit/c711b3abb) ferretdb apm fix (#1138)
- [02bd64df](https://github.com/kubedb/apimachinery/commit/02bd64dfa) Update security context based on version (#1137)
- [2a63b8b1](https://github.com/kubedb/apimachinery/commit/2a63b8b1a) Update deps
- [2293744e](https://github.com/kubedb/apimachinery/commit/2293744e3) Update deps
- [32a0f294](https://github.com/kubedb/apimachinery/commit/32a0f2944) Update deps
- [c389dcb1](https://github.com/kubedb/apimachinery/commit/c389dcb17) Add Singlestore Config Type (#1136)
- [ef7f62fb](https://github.com/kubedb/apimachinery/commit/ef7f62fbd) Defaulting RunAsGroup (#1134)
- [e08f63ba](https://github.com/kubedb/apimachinery/commit/e08f63ba0) Minox fixes in rlease (#1135)
- [760f1c55](https://github.com/kubedb/apimachinery/commit/760f1c554) Ferretdb webhook and apis updated (#1132)
- [958de8ec](https://github.com/kubedb/apimachinery/commit/958de8ec3) Fix spelling mistakes in dashboard. (#1133)
- [f614ab97](https://github.com/kubedb/apimachinery/commit/f614ab976) Fix release issues and add version 28.0.1 (#1131)
- [df53756a](https://github.com/kubedb/apimachinery/commit/df53756a3) Fix dashboard config merger command. (#1126)
- [4b8a46ab](https://github.com/kubedb/apimachinery/commit/4b8a46ab1) Add kafka connector webhook (#1128)
- [3e06dc03](https://github.com/kubedb/apimachinery/commit/3e06dc03a) Update Rabbitmq helpers and webhooks (#1130)
- [23153f41](https://github.com/kubedb/apimachinery/commit/23153f41f) Add ZooKeeper Standalone Mode (#1129)
- [650406ba](https://github.com/kubedb/apimachinery/commit/650406ba8) Remove replica condition for Pgpool (#1127)
- [dbd8e067](https://github.com/kubedb/apimachinery/commit/dbd8e0679) Update docker/docker
- [a28b2662](https://github.com/kubedb/apimachinery/commit/a28b2662e) Add validator to check negative number of replicas. (#1124)
- [cc189c3c](https://github.com/kubedb/apimachinery/commit/cc189c3c8) Add utilities to extract databaseInfo (#1123)
- [ceef191e](https://github.com/kubedb/apimachinery/commit/ceef191e0) Fix short name for FerretDBVersion
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
- [45cbf75e](https://github.com/kubedb/apimachinery/commit/45cbf75e3) Update deps
- [dc224c1a](https://github.com/kubedb/apimachinery/commit/dc224c1a1) Remove crd informer (#1102)
- [87c402a1](https://github.com/kubedb/apimachinery/commit/87c402a1a) Remove discovery.ResourceMapper (#1101)
- [a1d475ce](https://github.com/kubedb/apimachinery/commit/a1d475ceb) Replace deprecated PollImmediate (#1100)
- [75db4a37](https://github.com/kubedb/apimachinery/commit/75db4a378) Add ConfigureOpenAPI helper (#1099)
- [83be295b](https://github.com/kubedb/apimachinery/commit/83be295b0) update sidekick deps
- [032b2721](https://github.com/kubedb/apimachinery/commit/032b27211) Fix linter
- [389a934c](https://github.com/kubedb/apimachinery/commit/389a934c7) Use k8s 1.29 client libs (#1093)



## [kubedb/cli](https://github.com/kubedb/cli)

### [v0.41.0](https://github.com/kubedb/cli/releases/tag/v0.41.0)

- [8ff0608c](https://github.com/kubedb/cli/commit/8ff0608c) Prepare for release v0.41.0 (#755)
- [7aeaa861](https://github.com/kubedb/cli/commit/7aeaa861) Monitor CLI added for check-connection and aggregate all monitor CLI (#754)
- [a67dadc9](https://github.com/kubedb/cli/commit/a67dadc9) Prepare for release v0.41.0-rc.1 (#753)
- [d1b206ee](https://github.com/kubedb/cli/commit/d1b206ee) Update deps (#752)
- [50f15d19](https://github.com/kubedb/cli/commit/50f15d19) Update deps (#751)
- [64ad0b63](https://github.com/kubedb/cli/commit/64ad0b63) Prepare for release v0.41.0-rc.0 (#749)
- [d188eae6](https://github.com/kubedb/cli/commit/d188eae6) Grafana dashboard's metric checking CLI (#740)
- [234b7051](https://github.com/kubedb/cli/commit/234b7051) Prepare for release v0.41.0-beta.1 (#748)
- [1ebdd532](https://github.com/kubedb/cli/commit/1ebdd532) Update deps
- [c0165e83](https://github.com/kubedb/cli/commit/c0165e83) Prepare for release v0.41.0-beta.0 (#747)
- [d9c905e5](https://github.com/kubedb/cli/commit/d9c905e5) Update deps (#746)
- [bc415a1d](https://github.com/kubedb/cli/commit/bc415a1d) Update deps (#745)



## [kubedb/crd-manager](https://github.com/kubedb/crd-manager)

### [v0.0.4](https://github.com/kubedb/crd-manager/releases/tag/v0.0.4)

- [a45ec91](https://github.com/kubedb/crd-manager/commit/a45ec91) Prepare for release v0.0.4 (#13)
- [39cec60](https://github.com/kubedb/crd-manager/commit/39cec60) Fix deploy-to-kind make target



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.0.10](https://github.com/kubedb/db-client-go/releases/tag/v0.0.10)

- [902c39a0](https://github.com/kubedb/db-client-go/commit/902c39a0) Prepare for release v0.0.10 (#86)
- [377f8591](https://github.com/kubedb/db-client-go/commit/377f8591) Update deps
- [67567b71](https://github.com/kubedb/db-client-go/commit/67567b71) Update deps (#85)
- [4e2471e3](https://github.com/kubedb/db-client-go/commit/4e2471e3) Update deps (#84)



## [kubedb/druid](https://github.com/kubedb/druid)

### [v0.0.4](https://github.com/kubedb/druid/releases/tag/v0.0.4)

- [8d4fdb6](https://github.com/kubedb/druid/commit/8d4fdb6) Prepare for release v0.0.4 (#8)



## [kubedb/elasticsearch-restic-plugin](https://github.com/kubedb/elasticsearch-restic-plugin)

### [v0.4.0](https://github.com/kubedb/elasticsearch-restic-plugin/releases/tag/v0.4.0)

- [11a8a76](https://github.com/kubedb/elasticsearch-restic-plugin/commit/11a8a76) Prepare for release v0.4.0 (#19)
- [675caf7](https://github.com/kubedb/elasticsearch-restic-plugin/commit/675caf7) Prepare for release v0.4.0-rc.1 (#18)
- [18ea6da](https://github.com/kubedb/elasticsearch-restic-plugin/commit/18ea6da) Prepare for release v0.4.0-rc.0 (#17)
- [584dfd9](https://github.com/kubedb/elasticsearch-restic-plugin/commit/584dfd9) Prepare for release v0.4.0-beta.1 (#16)
- [5e9aef5](https://github.com/kubedb/elasticsearch-restic-plugin/commit/5e9aef5) Prepare for release v0.4.0-beta.0 (#15)
- [2fdcafa](https://github.com/kubedb/elasticsearch-restic-plugin/commit/2fdcafa) Use k8s 1.29 client libs (#14)



## [kubedb/kafka](https://github.com/kubedb/kafka)

### [v0.12.0](https://github.com/kubedb/kafka/releases/tag/v0.12.0)

- [8ffe42e6](https://github.com/kubedb/kafka/commit/8ffe42e6) Prepare for release v0.12.0 (#76)
- [511914c2](https://github.com/kubedb/kafka/commit/511914c2) Prepare for release v0.12.0-rc.1 (#75)
- [fb908cf2](https://github.com/kubedb/kafka/commit/fb908cf2) Update deps (#74)
- [cccaf86c](https://github.com/kubedb/kafka/commit/cccaf86c) Update deps (#73)
- [9d73e3ce](https://github.com/kubedb/kafka/commit/9d73e3ce) Prepare for release v0.12.0-rc.0 (#71)
- [c1d08f75](https://github.com/kubedb/kafka/commit/c1d08f75) Remove cassandra, clickhouse, etcd flags
- [e7283583](https://github.com/kubedb/kafka/commit/e7283583) Fix podtemplate containers reference isuue (#70)
- [6d04bf0f](https://github.com/kubedb/kafka/commit/6d04bf0f) Add termination policy for kafka and connect cluster (#69)
- [34f4967f](https://github.com/kubedb/kafka/commit/34f4967f) Prepare for release v0.12.0-beta.1 (#68)
- [7176931c](https://github.com/kubedb/kafka/commit/7176931c) Move Kafka Podtemplate to ofshoot-api v2 (#66)
- [9454adf6](https://github.com/kubedb/kafka/commit/9454adf6) Update ci & makefile for crd-manager (#67)
- [fda770d8](https://github.com/kubedb/kafka/commit/fda770d8) Add kafka connector controller (#65)
- [6ed0ccd4](https://github.com/kubedb/kafka/commit/6ed0ccd4) Add Kafka connect  controller (#44)
- [18e9a45c](https://github.com/kubedb/kafka/commit/18e9a45c) update deps (#64)
- [a7dfb409](https://github.com/kubedb/kafka/commit/a7dfb409) Update makefile for dynamic crd installer (#63)
- [f9350578](https://github.com/kubedb/kafka/commit/f9350578) Prepare for release v0.12.0-beta.0 (#62)
- [692f2bef](https://github.com/kubedb/kafka/commit/692f2bef) Dynamically start crd controller (#61)
- [a50dc8b4](https://github.com/kubedb/kafka/commit/a50dc8b4) Update deps (#60)
- [7ff28ed7](https://github.com/kubedb/kafka/commit/7ff28ed7) Update deps (#59)
- [16130571](https://github.com/kubedb/kafka/commit/16130571) Add openapi configuration for webhook server (#58)
- [cc465de9](https://github.com/kubedb/kafka/commit/cc465de9) Use k8s 1.29 client libs (#57)



## [kubedb/kubedb-manifest-plugin](https://github.com/kubedb/kubedb-manifest-plugin)

### [v0.4.0](https://github.com/kubedb/kubedb-manifest-plugin/releases/tag/v0.4.0)

- [7d51761](https://github.com/kubedb/kubedb-manifest-plugin/commit/7d51761) Prepare for release v0.4.0 (#40)
- [5daf9ce](https://github.com/kubedb/kubedb-manifest-plugin/commit/5daf9ce) Prepare for release v0.4.0-rc.1 (#39)
- [b7ec4a4](https://github.com/kubedb/kubedb-manifest-plugin/commit/b7ec4a4) Prepare for release v0.4.0-rc.0 (#38)
- [c77b4ae](https://github.com/kubedb/kubedb-manifest-plugin/commit/c77b4ae) Prepare for release v0.4.0-beta.1 (#37)
- [6a8a822](https://github.com/kubedb/kubedb-manifest-plugin/commit/6a8a822) Update component name (#35)
- [c315615](https://github.com/kubedb/kubedb-manifest-plugin/commit/c315615) Prepare for release v0.4.0-beta.0 (#36)
- [5ce328d](https://github.com/kubedb/kubedb-manifest-plugin/commit/5ce328d) Use k8s 1.29 client libs (#34)



## [kubedb/mariadb-coordinator](https://github.com/kubedb/mariadb-coordinator)

### [v0.21.0](https://github.com/kubedb/mariadb-coordinator/releases/tag/v0.21.0)

- [6e2b4dee](https://github.com/kubedb/mariadb-coordinator/commit/6e2b4dee) Prepare for release v0.21.0 (#107)
- [e0e9c489](https://github.com/kubedb/mariadb-coordinator/commit/e0e9c489) Fix MariaDB Health Check (#106)
- [4289bcd1](https://github.com/kubedb/mariadb-coordinator/commit/4289bcd1) Prepare for release v0.21.0-rc.1 (#105)
- [34f610f7](https://github.com/kubedb/mariadb-coordinator/commit/34f610f7) Update deps (#104)
- [13dbe3f7](https://github.com/kubedb/mariadb-coordinator/commit/13dbe3f7) Update deps (#103)
- [15a83758](https://github.com/kubedb/mariadb-coordinator/commit/15a83758) Prepare for release v0.21.0-rc.0 (#102)
- [1c30e710](https://github.com/kubedb/mariadb-coordinator/commit/1c30e710) Prepare for release v0.21.0-beta.1 (#101)
- [28677618](https://github.com/kubedb/mariadb-coordinator/commit/28677618) Prepare for release v0.21.0-beta.0 (#100)
- [655a2c66](https://github.com/kubedb/mariadb-coordinator/commit/655a2c66) Update deps (#99)
- [ef206cfe](https://github.com/kubedb/mariadb-coordinator/commit/ef206cfe) Update deps (#98)
- [ef72c98b](https://github.com/kubedb/mariadb-coordinator/commit/ef72c98b) Use k8s 1.29 client libs (#97)



## [kubedb/mongodb-csi-snapshotter-plugin](https://github.com/kubedb/mongodb-csi-snapshotter-plugin)

### [v0.2.0](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/releases/tag/v0.2.0)

- [06a2057](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/06a2057) Prepare for release v0.2.0 (#15)
- [5b28353](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/5b28353) Prepare for release v0.2.0-rc.1 (#14)
- [afd4fdb](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/afd4fdb) Prepare for release v0.2.0-rc.0 (#13)
- [5680265](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/5680265) Prepare for release v0.2.0-beta.1 (#12)
- [72693c8](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/72693c8) Fix component driver status (#11)
- [0ea73ee](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/0ea73ee) Update deps (#10)
- [ef74421](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/ef74421) Prepare for release v0.2.0-beta.0 (#9)
- [c2c9bd4](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/c2c9bd4) Use k8s 1.29 client libs (#8)



## [kubedb/mysql-archiver](https://github.com/kubedb/mysql-archiver)

### [v0.2.0](https://github.com/kubedb/mysql-archiver/releases/tag/v0.2.0)

- [ed748c7](https://github.com/kubedb/mysql-archiver/commit/ed748c7) Prepare for release v0.2.0 (#20)
- [4d1c341](https://github.com/kubedb/mysql-archiver/commit/4d1c341) Remove example files (#17)
- [9c0545e](https://github.com/kubedb/mysql-archiver/commit/9c0545e) Add azure, gcs support (#13)
- [d0fbef5](https://github.com/kubedb/mysql-archiver/commit/d0fbef5) Prepare for release v0.2.0-rc.1 (#19)
- [a6fdf50](https://github.com/kubedb/mysql-archiver/commit/a6fdf50) Prepare for release v0.2.0-rc.0 (#18)
- [718511e](https://github.com/kubedb/mysql-archiver/commit/718511e) Remove obsolete files (#16)
- [07fc1eb](https://github.com/kubedb/mysql-archiver/commit/07fc1eb) Fix mysql-community-common version in docker file
- [e5bdae3](https://github.com/kubedb/mysql-archiver/commit/e5bdae3) Prepare for release v0.2.0-beta.1 (#15)
- [7ef752c](https://github.com/kubedb/mysql-archiver/commit/7ef752c) Refactor + Cleanup wal-g example files (#14)
- [5857a8d](https://github.com/kubedb/mysql-archiver/commit/5857a8d) Don't use fail-fast
- [5833776](https://github.com/kubedb/mysql-archiver/commit/5833776) Prepare for release v0.2.0-beta.0 (#12)
- [f3e68b2](https://github.com/kubedb/mysql-archiver/commit/f3e68b2) Use k8s 1.29 client libs (#11)



## [kubedb/mysql-coordinator](https://github.com/kubedb/mysql-coordinator)

### [v0.19.0](https://github.com/kubedb/mysql-coordinator/releases/tag/v0.19.0)

- [ef84bd37](https://github.com/kubedb/mysql-coordinator/commit/ef84bd37) Prepare for release v0.19.0 (#103)
- [40a2b6eb](https://github.com/kubedb/mysql-coordinator/commit/40a2b6eb) Prepare for release v0.19.0-rc.1 (#102)
- [8b80958d](https://github.com/kubedb/mysql-coordinator/commit/8b80958d) Update deps (#101)
- [df438239](https://github.com/kubedb/mysql-coordinator/commit/df438239) Update deps (#100)
- [1bc71d04](https://github.com/kubedb/mysql-coordinator/commit/1bc71d04) Prepare for release v0.19.0-rc.0 (#99)
- [59a11671](https://github.com/kubedb/mysql-coordinator/commit/59a11671) Prepare for release v0.19.0-beta.1 (#98)
- [e0cc149f](https://github.com/kubedb/mysql-coordinator/commit/e0cc149f) Prepare for release v0.19.0-beta.0 (#97)
- [67aeb229](https://github.com/kubedb/mysql-coordinator/commit/67aeb229) Update deps (#96)
- [2fa4423f](https://github.com/kubedb/mysql-coordinator/commit/2fa4423f) Update deps (#95)
- [b0735769](https://github.com/kubedb/mysql-coordinator/commit/b0735769) Use k8s 1.29 client libs (#94)



## [kubedb/mysql-csi-snapshotter-plugin](https://github.com/kubedb/mysql-csi-snapshotter-plugin)

### [v0.2.0](https://github.com/kubedb/mysql-csi-snapshotter-plugin/releases/tag/v0.2.0)

- [61d40c2](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/61d40c2) Prepare for release v0.2.0 (#8)
- [ac60bf4](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/ac60bf4) Prepare for release v0.2.0-rc.1 (#7)
- [21e9470](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/21e9470) Prepare for release v0.2.0-rc.0 (#6)
- [d5771cf](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/d5771cf) Prepare for release v0.2.0-beta.1 (#5)
- [b4ffc6f](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/b4ffc6f) Fix component driver status & Update deps (#3)
- [d285eff](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/d285eff) Prepare for release v0.2.0-beta.0 (#4)
- [7a46441](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/7a46441) Use k8s 1.29 client libs (#2)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.19.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.19.0)

- [6a5deed](https://github.com/kubedb/mysql-router-init/commit/6a5deed) Update deps (#40)
- [0078f09](https://github.com/kubedb/mysql-router-init/commit/0078f09) Update deps (#39)
- [85f8c6f](https://github.com/kubedb/mysql-router-init/commit/85f8c6f) Update deps (#38)
- [7dd201c](https://github.com/kubedb/mysql-router-init/commit/7dd201c) Use k8s 1.29 client libs (#37)



## [kubedb/percona-xtradb](https://github.com/kubedb/percona-xtradb)

### [v0.28.0](https://github.com/kubedb/percona-xtradb/releases/tag/v0.28.0)

- [279330e0](https://github.com/kubedb/percona-xtradb/commit/279330e09) Prepare for release v0.28.0 (#354)
- [b567db53](https://github.com/kubedb/percona-xtradb/commit/b567db53a) Prepare for release v0.28.0-rc.1 (#353)
- [c0ddb330](https://github.com/kubedb/percona-xtradb/commit/c0ddb330b) Update deps (#352)
- [d461df3e](https://github.com/kubedb/percona-xtradb/commit/d461df3ed) Fix appbinding scheme (#349)
- [2752f7e3](https://github.com/kubedb/percona-xtradb/commit/2752f7e36) Update deps (#351)
- [80cd3a03](https://github.com/kubedb/percona-xtradb/commit/80cd3a030) Prepare for release v0.28.0-rc.0 (#350)
- [475a5e32](https://github.com/kubedb/percona-xtradb/commit/475a5e328) Prepare for release v0.28.0-beta.1 (#348)
- [4c1380ab](https://github.com/kubedb/percona-xtradb/commit/4c1380ab7) Incorporate with apimachinery package name change from `stash` to `restore` (#347)
- [0ceb3028](https://github.com/kubedb/percona-xtradb/commit/0ceb30284) Prepare for release v0.28.0-beta.0 (#346)
- [e7d35606](https://github.com/kubedb/percona-xtradb/commit/e7d356062) Dynamically start crd controller (#345)
- [5d07b565](https://github.com/kubedb/percona-xtradb/commit/5d07b5655) Update deps (#344)
- [1a639f84](https://github.com/kubedb/percona-xtradb/commit/1a639f840) Update deps (#343)
- [4f8b24ab](https://github.com/kubedb/percona-xtradb/commit/4f8b24aba) Update deps
- [e5254020](https://github.com/kubedb/percona-xtradb/commit/e52540202) Use k8s 1.29 client libs (#341)



## [kubedb/percona-xtradb-coordinator](https://github.com/kubedb/percona-xtradb-coordinator)

### [v0.14.0](https://github.com/kubedb/percona-xtradb-coordinator/releases/tag/v0.14.0)

- [6fd3b3cd](https://github.com/kubedb/percona-xtradb-coordinator/commit/6fd3b3cd) Prepare for release v0.14.0 (#63)
- [da619fa3](https://github.com/kubedb/percona-xtradb-coordinator/commit/da619fa3) Prepare for release v0.14.0-rc.1 (#62)
- [c39daf56](https://github.com/kubedb/percona-xtradb-coordinator/commit/c39daf56) Update deps (#61)
- [42dc1a95](https://github.com/kubedb/percona-xtradb-coordinator/commit/42dc1a95) Update deps (#60)
- [7581630e](https://github.com/kubedb/percona-xtradb-coordinator/commit/7581630e) Prepare for release v0.14.0-rc.0 (#59)
- [560bc5c3](https://github.com/kubedb/percona-xtradb-coordinator/commit/560bc5c3) Prepare for release v0.14.0-beta.1 (#58)
- [963756eb](https://github.com/kubedb/percona-xtradb-coordinator/commit/963756eb) Prepare for release v0.14.0-beta.0 (#57)
- [5489bb8c](https://github.com/kubedb/percona-xtradb-coordinator/commit/5489bb8c) Update deps (#56)
- [a8424e18](https://github.com/kubedb/percona-xtradb-coordinator/commit/a8424e18) Update deps (#55)
- [ee4add86](https://github.com/kubedb/percona-xtradb-coordinator/commit/ee4add86) Use k8s 1.29 client libs (#54)



## [kubedb/pg-coordinator](https://github.com/kubedb/pg-coordinator)

### [v0.25.0](https://github.com/kubedb/pg-coordinator/releases/tag/v0.25.0)

- [7e7d32d9](https://github.com/kubedb/pg-coordinator/commit/7e7d32d9) Prepare for release v0.25.0 (#154)
- [9a720273](https://github.com/kubedb/pg-coordinator/commit/9a720273) Prepare for release v0.25.0-rc.1 (#153)
- [f103f1fc](https://github.com/kubedb/pg-coordinator/commit/f103f1fc) Update deps (#152)
- [84b92d89](https://github.com/kubedb/pg-coordinator/commit/84b92d89) Update deps (#151)
- [41cc97b6](https://github.com/kubedb/pg-coordinator/commit/41cc97b6) Prepare for release v0.25.0-rc.0 (#150)
- [5298a177](https://github.com/kubedb/pg-coordinator/commit/5298a177) Fixed (#149)
- [bc296307](https://github.com/kubedb/pg-coordinator/commit/bc296307) Prepare for release v0.25.0-beta.1 (#148)
- [30973540](https://github.com/kubedb/pg-coordinator/commit/30973540) Prepare for release v0.25.0-beta.0 (#147)
- [7b84e198](https://github.com/kubedb/pg-coordinator/commit/7b84e198) Update deps (#146)
- [f1bfe818](https://github.com/kubedb/pg-coordinator/commit/f1bfe818) Update deps (#145)
- [1de05a6e](https://github.com/kubedb/pg-coordinator/commit/1de05a6e) Use k8s 1.29 client libs (#144)



## [kubedb/pgpool](https://github.com/kubedb/pgpool)

### [v0.0.4](https://github.com/kubedb/pgpool/releases/tag/v0.0.4)

- [b6546d3](https://github.com/kubedb/pgpool/commit/b6546d3) Prepare for release v0.0.4 (#12)
- [6f7ebca](https://github.com/kubedb/pgpool/commit/6f7ebca) Add daily to workflows (#10)
- [18c06cd](https://github.com/kubedb/pgpool/commit/18c06cd) Fix InitConfiguration issue (#9)



## [kubedb/postgres-archiver](https://github.com/kubedb/postgres-archiver)

### [v0.2.0](https://github.com/kubedb/postgres-archiver/releases/tag/v0.2.0)

- [a55baa8](https://github.com/kubedb/postgres-archiver/commit/a55baa8) Prepare for release v0.2.0 (#21)
- [8f66790](https://github.com/kubedb/postgres-archiver/commit/8f66790) Prepare for release v0.2.0-rc.1 (#20)
- [bff75cb](https://github.com/kubedb/postgres-archiver/commit/bff75cb) Prepare for release v0.2.0-rc.0 (#19)
- [bb8c342](https://github.com/kubedb/postgres-archiver/commit/bb8c342) Create directory for wal-backup (#18)
- [c4405c1](https://github.com/kubedb/postgres-archiver/commit/c4405c1) Prepare for release v0.2.0-beta.1 (#17)
- [c353dcd](https://github.com/kubedb/postgres-archiver/commit/c353dcd) Don't use fail-fast
- [a9cbe08](https://github.com/kubedb/postgres-archiver/commit/a9cbe08) Prepare for release v0.2.0-beta.0 (#16)
- [183e97c](https://github.com/kubedb/postgres-archiver/commit/183e97c) Use k8s 1.29 client libs (#15)



## [kubedb/postgres-csi-snapshotter-plugin](https://github.com/kubedb/postgres-csi-snapshotter-plugin)

### [v0.2.0](https://github.com/kubedb/postgres-csi-snapshotter-plugin/releases/tag/v0.2.0)

- [5e0031f](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/5e0031f) Prepare for release v0.2.0 (#18)
- [369c9a3](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/369c9a3) Prepare for release v0.2.0-rc.1 (#17)
- [87240d8](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/87240d8) Prepare for release v0.2.0-rc.0 (#16)
- [dc4f85e](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/dc4f85e) Prepare for release v0.2.0-beta.1 (#15)
- [098365a](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/098365a) Update README.md (#14)
- [5ef571f](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/5ef571f) Update deps (#13)
- [f0e546a](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/f0e546a) Prepare for release v0.2.0-beta.0 (#12)
- [aae7294](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/aae7294) Use k8s 1.29 client libs (#11)



## [kubedb/provider-aws](https://github.com/kubedb/provider-aws)

### [v0.3.0](https://github.com/kubedb/provider-aws/releases/tag/v0.3.0)




## [kubedb/provider-azure](https://github.com/kubedb/provider-azure)

### [v0.3.0](https://github.com/kubedb/provider-azure/releases/tag/v0.3.0)

- [ebba4fa](https://github.com/kubedb/provider-azure/commit/ebba4fa) Checkout fake release branch for release workflow



## [kubedb/provider-gcp](https://github.com/kubedb/provider-gcp)

### [v0.3.0](https://github.com/kubedb/provider-gcp/releases/tag/v0.3.0)

- [82f52c3](https://github.com/kubedb/provider-gcp/commit/82f52c3) Checkout fake release branch for release workflow



## [kubedb/redis-restic-plugin](https://github.com/kubedb/redis-restic-plugin)

### [v0.4.0](https://github.com/kubedb/redis-restic-plugin/releases/tag/v0.4.0)

- [5436cb6](https://github.com/kubedb/redis-restic-plugin/commit/5436cb6) Prepare for release v0.4.0 (#20)
- [67a8942](https://github.com/kubedb/redis-restic-plugin/commit/67a8942) Prepare for release v0.4.0-rc.1 (#19)
- [968da13](https://github.com/kubedb/redis-restic-plugin/commit/968da13) Prepare for release v0.4.0-rc.0 (#18)
- [fac6226](https://github.com/kubedb/redis-restic-plugin/commit/fac6226) Prepare for release v0.4.0-beta.1 (#17)
- [da2796a](https://github.com/kubedb/redis-restic-plugin/commit/da2796a) Prepare for release v0.4.0-beta.0 (#16)
- [0553c6f](https://github.com/kubedb/redis-restic-plugin/commit/0553c6f) Use k8s 1.29 client libs (#15)



## [kubedb/singlestore](https://github.com/kubedb/singlestore)

### [v0.0.4](https://github.com/kubedb/singlestore/releases/tag/v0.0.4)

- [e8cf66f](https://github.com/kubedb/singlestore/commit/e8cf66f) Prepare for release v0.0.4 (#11)



## [kubedb/solr](https://github.com/kubedb/solr)

### [v0.0.4](https://github.com/kubedb/solr/releases/tag/v0.0.4)

- [8be74c4](https://github.com/kubedb/solr/commit/8be74c4) Prepare for release v0.0.4 (#12)
- [0647ccf](https://github.com/kubedb/solr/commit/0647ccf) Remove overseer discovery service. (#10)
- [4901117](https://github.com/kubedb/solr/commit/4901117) Add daily yml. (#9)
- [3abb79b](https://github.com/kubedb/solr/commit/3abb79b) Add auth secret reference in appbinding. (#8)



## [kubedb/tests](https://github.com/kubedb/tests)

### [v0.26.0](https://github.com/kubedb/tests/releases/tag/v0.26.0)

- [16543a0f](https://github.com/kubedb/tests/commit/16543a0f) Prepare for release v0.26.0 (#304)
- [92607278](https://github.com/kubedb/tests/commit/92607278) Add dependencies flag (#301)
- [17bbf43c](https://github.com/kubedb/tests/commit/17bbf43c) Add Reconfigure with Vertical Scaling (#300)
- [f3e3fba1](https://github.com/kubedb/tests/commit/f3e3fba1) Add Singlestore Provisioning Test (#287)
- [5a527051](https://github.com/kubedb/tests/commit/5a527051) Prepare for release v0.26.0-rc.1 (#299)
- [03d71b6d](https://github.com/kubedb/tests/commit/03d71b6d) Update deps (#298)
- [2d928008](https://github.com/kubedb/tests/commit/2d928008) Update deps (#297)
- [1730fd31](https://github.com/kubedb/tests/commit/1730fd31) Prepare for release v0.26.0-rc.0 (#296)
- [d1805668](https://github.com/kubedb/tests/commit/d1805668) Add ZooKeeper Tests (#294)
- [4c27754c](https://github.com/kubedb/tests/commit/4c27754c) Fix kafka env-variable tests (#293)
- [3cfc1212](https://github.com/kubedb/tests/commit/3cfc1212) Prepare for release v0.26.0-beta.1 (#292)
- [b810e690](https://github.com/kubedb/tests/commit/b810e690) increase cpu limit for vertical scaling (#289)
- [c43985ba](https://github.com/kubedb/tests/commit/c43985ba) Change dashboard api group (#291)
- [1b96881e](https://github.com/kubedb/tests/commit/1b96881e) Fix error logging
- [33f78143](https://github.com/kubedb/tests/commit/33f78143) forceCleanup PVCs for mongo (#288)
- [0dcd3e38](https://github.com/kubedb/tests/commit/0dcd3e38) Add PostgreSQL logical replication tests  (#202)
- [2f403c85](https://github.com/kubedb/tests/commit/2f403c85) Find profiles in array, Don't match with string (#286)
- [5aca2293](https://github.com/kubedb/tests/commit/5aca2293) Give time to PDB status to be updated (#285)
- [5f3fabd7](https://github.com/kubedb/tests/commit/5f3fabd7) Prepare for release v0.26.0-beta.0 (#284)
- [27a24dff](https://github.com/kubedb/tests/commit/27a24dff) Update deps (#283)
- [b9021186](https://github.com/kubedb/tests/commit/b9021186) Update deps (#282)
- [589ca51c](https://github.com/kubedb/tests/commit/589ca51c) mongodb vertical scaling fix (#281)
- [feaa0f6a](https://github.com/kubedb/tests/commit/feaa0f6a) Add `--restricted` flag (#280)
- [2423ee38](https://github.com/kubedb/tests/commit/2423ee38) Fix linter errors
- [dcd64c7c](https://github.com/kubedb/tests/commit/dcd64c7c) Update lint command
- [c3ef1fa4](https://github.com/kubedb/tests/commit/c3ef1fa4) Use k8s 1.29 client libs (#279)



