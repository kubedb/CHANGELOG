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



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.0.10](https://github.com/kubedb/db-client-go/releases/tag/v0.0.10)

- [902c39a0](https://github.com/kubedb/db-client-go/commit/902c39a0) Prepare for release v0.0.10 (#86)
- [377f8591](https://github.com/kubedb/db-client-go/commit/377f8591) Update deps
- [67567b71](https://github.com/kubedb/db-client-go/commit/67567b71) Update deps (#85)
- [4e2471e3](https://github.com/kubedb/db-client-go/commit/4e2471e3) Update deps (#84)



