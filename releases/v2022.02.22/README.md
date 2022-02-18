# KubeDB v2022.02.22 (2022-02-18)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.25.0](https://github.com/kubedb/apimachinery/releases/tag/v0.25.0)

- [4ed35401](https://github.com/kubedb/apimachinery/commit/4ed35401) Add Elasticsearch dashboard helper methods and constants (#860)
- [8c9cb4b7](https://github.com/kubedb/apimachinery/commit/8c9cb4b7) fix mysqldatabase validator webhook (#870)
- [6be2000e](https://github.com/kubedb/apimachinery/commit/6be2000e) Add Schema Manager for Postgres (#854)
- [fa5b5267](https://github.com/kubedb/apimachinery/commit/fa5b5267) Add helper method for MySQL (#871)
- [161fcef7](https://github.com/kubedb/apimachinery/commit/161fcef7) Remove RedisDatabase crd (#869)
- [f7217890](https://github.com/kubedb/apimachinery/commit/f7217890) Use admission/v1 api types (#868)
- [02c89901](https://github.com/kubedb/apimachinery/commit/02c89901) Cancel concurrent CI runs for same pr/commit (#867)
- [c6db524e](https://github.com/kubedb/apimachinery/commit/c6db524e) Cancel concurrent CI runs for same pr/commit (#866)
- [f1d3fa44](https://github.com/kubedb/apimachinery/commit/f1d3fa44) Remove Enable***Webhook fields from common Config (#865)
- [f0d84187](https://github.com/kubedb/apimachinery/commit/f0d84187) Add ES constants: ElasticsearchJavaOptsEnv (#864)
- [90877a3d](https://github.com/kubedb/apimachinery/commit/90877a3d) Add disableAuth Support in Redis (#863)
- [da0fea34](https://github.com/kubedb/apimachinery/commit/da0fea34) Add support to configure JVM heap in term of percentage (#861)
- [5d665ff1](https://github.com/kubedb/apimachinery/commit/5d665ff1) Add doubleOptIn helpers; Change 'Successful' to 'Current' (#856)
- [1ff8a60c](https://github.com/kubedb/apimachinery/commit/1ff8a60c) Fix dashboard api and webhook helper function (#852)
- [fdad1ab2](https://github.com/kubedb/apimachinery/commit/fdad1ab2) Convert configmap for redis
- [b2887180](https://github.com/kubedb/apimachinery/commit/b2887180) Update repository config (#855)
- [713bb229](https://github.com/kubedb/apimachinery/commit/713bb229) Make dashboard & dashboardInitContainer fields optional (#853)
- [fc35bc33](https://github.com/kubedb/apimachinery/commit/fc35bc33) Add Constants for MariaDB ApplyConfig OpsReq (#851)
- [18a94e28](https://github.com/kubedb/apimachinery/commit/18a94e28) Update constants for Elasticsearch horizontal scaling (#849)
- [c327bc75](https://github.com/kubedb/apimachinery/commit/c327bc75) Add helper method for Mysql Read Replica (#848)
- [967a2137](https://github.com/kubedb/apimachinery/commit/967a2137) Add common condition-related constants & GetPhase function (#845)
- [e6e6d092](https://github.com/kubedb/apimachinery/commit/e6e6d092) Add dashboard image in ElasticsearchVersion (#824)
- [13b91fde](https://github.com/kubedb/apimachinery/commit/13b91fde) Add helper method for  MySQL Read Replica (#847)
- [dfb7dd5c](https://github.com/kubedb/apimachinery/commit/dfb7dd5c) Add `ApplyConfig` on MariaDB Reconfigure Ops Request (#846)
- [449b6d64](https://github.com/kubedb/apimachinery/commit/449b6d64) Use lower case letters
- [ee91f91a](https://github.com/kubedb/apimachinery/commit/ee91f91a) Fix typo in package name (#844)
- [8a260d9a](https://github.com/kubedb/apimachinery/commit/8a260d9a) Add Config Generator for Reconfigure (#835)
- [55f68a75](https://github.com/kubedb/apimachinery/commit/55f68a75) Add support for MySQL Read Only Replica (#827)
- [c2d563c4](https://github.com/kubedb/apimachinery/commit/c2d563c4) Fix linter error
- [de55a914](https://github.com/kubedb/apimachinery/commit/de55a914) Add Timeout on MySQLOpsRequestSpec (#825)
- [6894aa4d](https://github.com/kubedb/apimachinery/commit/6894aa4d) Update Volume Expansion Mode Name in Storage Autoscaler (#843)
- [4834d9c2](https://github.com/kubedb/apimachinery/commit/4834d9c2) Add dashboard and schema-manager apis (#841)
- [1bfbd8a8](https://github.com/kubedb/apimachinery/commit/1bfbd8a8) Add VolumeExpansion Mode in PostgresOpsRequest (#842)
- [9831faf3](https://github.com/kubedb/apimachinery/commit/9831faf3) Add UpdateVersion ops request type (#838)
- [113972a8](https://github.com/kubedb/apimachinery/commit/113972a8) Add EnforceFsGroup field in Postgres Spec (#839)
- [ff687f61](https://github.com/kubedb/apimachinery/commit/ff687f61) Add Changes for MariaDB Offline Volume Expansion and MariaDB AutoScaler (#834)
- [e438a2d8](https://github.com/kubedb/apimachinery/commit/e438a2d8) Fix spelling
- [a90c72c7](https://github.com/kubedb/apimachinery/commit/a90c72c7) Rename ***Overview api types to ***Insight (#840)
- [f3a216bf](https://github.com/kubedb/apimachinery/commit/f3a216bf) Add support of offline volume expansion for Elasticsearch (#826)
- [77708728](https://github.com/kubedb/apimachinery/commit/77708728) Update repository config (#837)
- [de96ed84](https://github.com/kubedb/apimachinery/commit/de96ed84) Add mongodb reprovision ops request (#829)
- [d35fa391](https://github.com/kubedb/apimachinery/commit/d35fa391) Add EphemerStorage in MongoDB (#828)
- [24b06131](https://github.com/kubedb/apimachinery/commit/24b06131) Add constant for mongodb `configuration.js` (#830)



## [kubedb/cli](https://github.com/kubedb/cli)

### [v0.25.0](https://github.com/kubedb/cli/releases/tag/v0.25.0)

- [d22f9b86](https://github.com/kubedb/cli/commit/d22f9b86) Prepare for release v0.25.0 (#654)
- [829e5d49](https://github.com/kubedb/cli/commit/829e5d49) Cancel concurrent CI runs for same pr/commit (#653)
- [2366e0fc](https://github.com/kubedb/cli/commit/2366e0fc) Update dependencies (#652)
- [3a4e8d6a](https://github.com/kubedb/cli/commit/3a4e8d6a) Cancel concurrent CI runs for same pr/commit (#651)
- [21d910b6](https://github.com/kubedb/cli/commit/21d910b6) Use GO 1.17 module format (#650)
- [3972a064](https://github.com/kubedb/cli/commit/3972a064) Use stash.appscode.dev/apimachinery@v0.18.0 (#649)
- [287d32bc](https://github.com/kubedb/cli/commit/287d32bc) Update SiteInfo (#648)
- [7aacbc4e](https://github.com/kubedb/cli/commit/7aacbc4e) Publish GenericResource (#647)
- [926af73f](https://github.com/kubedb/cli/commit/926af73f) Release cli for darwin/arm64 (#646)
- [f575f520](https://github.com/kubedb/cli/commit/f575f520) Recover from panic in reconcilers (#645)
- [5ebd64b6](https://github.com/kubedb/cli/commit/5ebd64b6) Update for release Stash@v2021.11.24 (#644)



## [kubedb/mongodb](https://github.com/kubedb/mongodb)

### [v0.18.0](https://github.com/kubedb/mongodb/releases/tag/v0.18.0)

- [7a354d6c](https://github.com/kubedb/mongodb/commit/7a354d6c) Prepare for release v0.18.0 (#462)
- [46b5f2a7](https://github.com/kubedb/mongodb/commit/46b5f2a7) Add suffix to webhook resource (#461)
- [8db1061d](https://github.com/kubedb/mongodb/commit/8db1061d) Allow partially installing webhook server (#460)
- [d21b4c46](https://github.com/kubedb/mongodb/commit/d21b4c46) Fix AdmissionReview api version (#458)
- [85ae88c1](https://github.com/kubedb/mongodb/commit/85ae88c1) Fix commands (#456)
- [e528b327](https://github.com/kubedb/mongodb/commit/e528b327) Cancel concurrent CI runs for same pr/commit (#455)
- [111d3d88](https://github.com/kubedb/mongodb/commit/111d3d88) Update dependencies (#454)
- [417ca61e](https://github.com/kubedb/mongodb/commit/417ca61e) Cancel concurrent CI runs for same pr/commit (#453)
- [2aacc8b2](https://github.com/kubedb/mongodb/commit/2aacc8b2) Introduce separate commands for operator and webhook (#452)
- [aaa48967](https://github.com/kubedb/mongodb/commit/aaa48967) Use stash.appscode.dev/apimachinery@v0.18.0 (#451)
- [b4f039b7](https://github.com/kubedb/mongodb/commit/b4f039b7) Update UID generation for GenericResource (#450)
- [537f1d2a](https://github.com/kubedb/mongodb/commit/537f1d2a) Fix shard health check (#448)
- [787cd3b0](https://github.com/kubedb/mongodb/commit/787cd3b0) Update SiteInfo (#447)
- [2d7b4b0e](https://github.com/kubedb/mongodb/commit/2d7b4b0e) Generate GenericResource
- [7df41e17](https://github.com/kubedb/mongodb/commit/7df41e17) Publish GenericResource (#446)
- [4eaa7aa2](https://github.com/kubedb/mongodb/commit/4eaa7aa2) Add configuration for ephemeral storage (#442)
- [28c8967d](https://github.com/kubedb/mongodb/commit/28c8967d) Add read/write health check (#443)
- [921451d7](https://github.com/kubedb/mongodb/commit/921451d7) Add support to apply `configuration.js` (#445)
- [027e307a](https://github.com/kubedb/mongodb/commit/027e307a) Update Reconcile method (#444)
- [9d609162](https://github.com/kubedb/mongodb/commit/9d609162) Recover from panic in reconcilers (#441)



## [kubedb/mysql](https://github.com/kubedb/mysql)

### [v0.18.0](https://github.com/kubedb/mysql/releases/tag/v0.18.0)

- [12b89a3e](https://github.com/kubedb/mysql/commit/12b89a3e) Prepare for release v0.18.0 (#455)
- [03df7640](https://github.com/kubedb/mysql/commit/03df7640) Add Support for MySQL Read Replica (#439)
- [abfa3adc](https://github.com/kubedb/mysql/commit/abfa3adc) Use component specific webhook install command
- [f42185e5](https://github.com/kubedb/mysql/commit/f42185e5) Add suffix to webhook resource (#454)
- [b8c47c15](https://github.com/kubedb/mysql/commit/b8c47c15) Fix AdmissionReview api version (#453)
- [e987420a](https://github.com/kubedb/mysql/commit/e987420a) Fix commands (#451)
- [db3a06de](https://github.com/kubedb/mysql/commit/db3a06de) Cancel concurrent CI runs for same pr/commit (#450)
- [4a4f156e](https://github.com/kubedb/mysql/commit/4a4f156e) Update dependencies (#449)
- [b7209b20](https://github.com/kubedb/mysql/commit/b7209b20) Cancel concurrent CI runs for same pr/commit (#448)
- [f6214514](https://github.com/kubedb/mysql/commit/f6214514) Introduce separate commands for operator and webhook (#447)
- [97ba973b](https://github.com/kubedb/mysql/commit/97ba973b) Use stash.appscode.dev/apimachinery@v0.18.0 (#446)
- [668f50ff](https://github.com/kubedb/mysql/commit/668f50ff) Update UID generation for GenericResource (#445)
- [ac411e95](https://github.com/kubedb/mysql/commit/ac411e95) Remove coordinator container for stand alone instance. (#443)
- [99441193](https://github.com/kubedb/mysql/commit/99441193) Update SiteInfo (#444)
- [a248a8e2](https://github.com/kubedb/mysql/commit/a248a8e2) Generate GenericResource
- [1e7e681b](https://github.com/kubedb/mysql/commit/1e7e681b) Publish GenericResource (#442)
- [2cca63b8](https://github.com/kubedb/mysql/commit/2cca63b8) Rename MySQLClusterModeGroupReplication to MySQLModeGroupReplication (#441)
- [a25b9a4c](https://github.com/kubedb/mysql/commit/a25b9a4c) Pass --set-gtid-purged=off to stash for innodb cluster. (#437)
- [e2533c3a](https://github.com/kubedb/mysql/commit/e2533c3a) Recover from panic in reconcilers (#436)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.3.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.3.0)

- [32d8ac8](https://github.com/kubedb/mysql-router-init/commit/32d8ac8) Cancel concurrent CI runs for same pr/commit (#16)
- [c01384d](https://github.com/kubedb/mysql-router-init/commit/c01384d) Cancel concurrent CI runs for same pr/commit (#15)
- [febef73](https://github.com/kubedb/mysql-router-init/commit/febef73) Publish GenericResource (#14)



## [kubedb/percona-xtradb](https://github.com/kubedb/percona-xtradb)

### [v0.12.0](https://github.com/kubedb/percona-xtradb/releases/tag/v0.12.0)

- [d01b2914](https://github.com/kubedb/percona-xtradb/commit/d01b2914) Prepare for release v0.12.0 (#249)
- [6f821254](https://github.com/kubedb/percona-xtradb/commit/6f821254) Add suffix to webhook resource (#248)
- [0be0d287](https://github.com/kubedb/percona-xtradb/commit/0be0d287) Allow partially installing webhook server (#247)
- [a867d68c](https://github.com/kubedb/percona-xtradb/commit/a867d68c) Fix AdmissionReview api version (#246)
- [15c1e045](https://github.com/kubedb/percona-xtradb/commit/15c1e045) Fix commands (#244)
- [3c12213b](https://github.com/kubedb/percona-xtradb/commit/3c12213b) Cancel concurrent CI runs for same pr/commit (#243)
- [1458bd2b](https://github.com/kubedb/percona-xtradb/commit/1458bd2b) Update dependencies (#242)
- [675cd747](https://github.com/kubedb/percona-xtradb/commit/675cd747) Cancel concurrent CI runs for same pr/commit (#241)
- [3c5f5df0](https://github.com/kubedb/percona-xtradb/commit/3c5f5df0) Introduce separate commands for operator and webhook (#240)
- [cb4dd867](https://github.com/kubedb/percona-xtradb/commit/cb4dd867) Use stash.appscode.dev/apimachinery@v0.18.0 (#239)
- [b8bd01a9](https://github.com/kubedb/percona-xtradb/commit/b8bd01a9) Update UID generation for GenericResource (#238)
- [e6b35455](https://github.com/kubedb/percona-xtradb/commit/e6b35455) Update SiteInfo (#236)
- [473b9ba6](https://github.com/kubedb/percona-xtradb/commit/473b9ba6) Generate GenericResource
- [28321621](https://github.com/kubedb/percona-xtradb/commit/28321621) Publish GenericResource (#235)
- [94984a32](https://github.com/kubedb/percona-xtradb/commit/94984a32) Recover from panic in reconcilers (#234)



## [kubedb/replication-mode-detector](https://github.com/kubedb/replication-mode-detector)

### [v0.12.0](https://github.com/kubedb/replication-mode-detector/releases/tag/v0.12.0)

- [86ec5d2a](https://github.com/kubedb/replication-mode-detector/commit/86ec5d2a) Prepare for release v0.12.0 (#184)
- [21cf5fe5](https://github.com/kubedb/replication-mode-detector/commit/21cf5fe5) Cancel concurrent CI runs for same pr/commit (#183)
- [c8a693ba](https://github.com/kubedb/replication-mode-detector/commit/c8a693ba) Update dependencies (#182)
- [31268557](https://github.com/kubedb/replication-mode-detector/commit/31268557) Cancel concurrent CI runs for same pr/commit (#181)
- [c471f782](https://github.com/kubedb/replication-mode-detector/commit/c471f782) Update SiteInfo (#180)
- [301a0b0c](https://github.com/kubedb/replication-mode-detector/commit/301a0b0c) Publish GenericResource (#179)
- [157723f2](https://github.com/kubedb/replication-mode-detector/commit/157723f2) Recover from panic in reconcilers (#178)



