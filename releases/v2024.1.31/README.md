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



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.0.10](https://github.com/kubedb/db-client-go/releases/tag/v0.0.10)

- [902c39a0](https://github.com/kubedb/db-client-go/commit/902c39a0) Prepare for release v0.0.10 (#86)
- [377f8591](https://github.com/kubedb/db-client-go/commit/377f8591) Update deps
- [67567b71](https://github.com/kubedb/db-client-go/commit/67567b71) Update deps (#85)
- [4e2471e3](https://github.com/kubedb/db-client-go/commit/4e2471e3) Update deps (#84)



## [kubedb/elasticsearch-restic-plugin](https://github.com/kubedb/elasticsearch-restic-plugin)

### [v0.4.0](https://github.com/kubedb/elasticsearch-restic-plugin/releases/tag/v0.4.0)

- [11a8a76](https://github.com/kubedb/elasticsearch-restic-plugin/commit/11a8a76) Prepare for release v0.4.0 (#19)
- [675caf7](https://github.com/kubedb/elasticsearch-restic-plugin/commit/675caf7) Prepare for release v0.4.0-rc.1 (#18)
- [18ea6da](https://github.com/kubedb/elasticsearch-restic-plugin/commit/18ea6da) Prepare for release v0.4.0-rc.0 (#17)
- [584dfd9](https://github.com/kubedb/elasticsearch-restic-plugin/commit/584dfd9) Prepare for release v0.4.0-beta.1 (#16)
- [5e9aef5](https://github.com/kubedb/elasticsearch-restic-plugin/commit/5e9aef5) Prepare for release v0.4.0-beta.0 (#15)
- [2fdcafa](https://github.com/kubedb/elasticsearch-restic-plugin/commit/2fdcafa) Use k8s 1.29 client libs (#14)



## [kubedb/kubedb-manifest-plugin](https://github.com/kubedb/kubedb-manifest-plugin)

### [v0.4.0](https://github.com/kubedb/kubedb-manifest-plugin/releases/tag/v0.4.0)

- [7d51761](https://github.com/kubedb/kubedb-manifest-plugin/commit/7d51761) Prepare for release v0.4.0 (#40)
- [5daf9ce](https://github.com/kubedb/kubedb-manifest-plugin/commit/5daf9ce) Prepare for release v0.4.0-rc.1 (#39)
- [b7ec4a4](https://github.com/kubedb/kubedb-manifest-plugin/commit/b7ec4a4) Prepare for release v0.4.0-rc.0 (#38)
- [c77b4ae](https://github.com/kubedb/kubedb-manifest-plugin/commit/c77b4ae) Prepare for release v0.4.0-beta.1 (#37)
- [6a8a822](https://github.com/kubedb/kubedb-manifest-plugin/commit/6a8a822) Update component name (#35)
- [c315615](https://github.com/kubedb/kubedb-manifest-plugin/commit/c315615) Prepare for release v0.4.0-beta.0 (#36)
- [5ce328d](https://github.com/kubedb/kubedb-manifest-plugin/commit/5ce328d) Use k8s 1.29 client libs (#34)



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



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.19.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.19.0)

- [6a5deed](https://github.com/kubedb/mysql-router-init/commit/6a5deed) Update deps (#40)
- [0078f09](https://github.com/kubedb/mysql-router-init/commit/0078f09) Update deps (#39)
- [85f8c6f](https://github.com/kubedb/mysql-router-init/commit/85f8c6f) Update deps (#38)
- [7dd201c](https://github.com/kubedb/mysql-router-init/commit/7dd201c) Use k8s 1.29 client libs (#37)



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



## [kubedb/provider-aws](https://github.com/kubedb/provider-aws)

### [v0.3.0](https://github.com/kubedb/provider-aws/releases/tag/v0.3.0)




## [kubedb/provider-azure](https://github.com/kubedb/provider-azure)

### [v0.3.0](https://github.com/kubedb/provider-azure/releases/tag/v0.3.0)

- [ebba4fa](https://github.com/kubedb/provider-azure/commit/ebba4fa) Checkout fake release branch for release workflow



## [kubedb/provider-gcp](https://github.com/kubedb/provider-gcp)

### [v0.3.0](https://github.com/kubedb/provider-gcp/releases/tag/v0.3.0)

- [82f52c3](https://github.com/kubedb/provider-gcp/commit/82f52c3) Checkout fake release branch for release workflow



