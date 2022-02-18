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



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.3.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.3.0)

- [32d8ac8](https://github.com/kubedb/mysql-router-init/commit/32d8ac8) Cancel concurrent CI runs for same pr/commit (#16)
- [c01384d](https://github.com/kubedb/mysql-router-init/commit/c01384d) Cancel concurrent CI runs for same pr/commit (#15)
- [febef73](https://github.com/kubedb/mysql-router-init/commit/febef73) Publish GenericResource (#14)



