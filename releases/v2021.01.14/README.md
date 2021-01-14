# KubeDB v2021.01.14 (2021-01-14)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.16.0](https://github.com/kubedb/apimachinery/releases/tag/v0.16.0)

- [d516b399](https://github.com/kubedb/apimachinery/commit/d516b399) Keep resource request & limit is in sync  (#685)
- [8766c8b9](https://github.com/kubedb/apimachinery/commit/8766c8b9) Remove readiness and liveness prove from MySQL helper (#686)
- [06de1945](https://github.com/kubedb/apimachinery/commit/06de1945) Use suffix instead of prefix for ES pods (#684)
- [a76dc4cc](https://github.com/kubedb/apimachinery/commit/a76dc4cc) Move all MongoDB constants (#683)
- [7a3dd5ee](https://github.com/kubedb/apimachinery/commit/7a3dd5ee) Set default affinity rules for MySQL and Postgres (#680)
- [45768d13](https://github.com/kubedb/apimachinery/commit/45768d13) Make sysctl initContainer optional (#682)
- [91826678](https://github.com/kubedb/apimachinery/commit/91826678) Use kubedb.com prefix for ES node roles (#678)
- [31ec37c3](https://github.com/kubedb/apimachinery/commit/31ec37c3) Add MySQL OpsRequest constants (#681)
- [2bfc35e9](https://github.com/kubedb/apimachinery/commit/2bfc35e9) Add Hosts helper for MySQL (#679)
- [e4cb7ef9](https://github.com/kubedb/apimachinery/commit/e4cb7ef9) MySQL primary service dns helper (#677)
- [2469f17e](https://github.com/kubedb/apimachinery/commit/2469f17e) Add constants for Elasticsearch TLS reconfiguration (#672)
- [2c61fb41](https://github.com/kubedb/apimachinery/commit/2c61fb41) Add MongoDB constants (#676)
- [31584e58](https://github.com/kubedb/apimachinery/commit/31584e58) Add DB constants and tls-reconfigure checker func (#657)
- [4d67bea1](https://github.com/kubedb/apimachinery/commit/4d67bea1) Add MongoDB & Elasticsearch Autoscaler CRDs (#659)
- [fb88afcf](https://github.com/kubedb/apimachinery/commit/fb88afcf) Update Kubernetes v1.18.9 dependencies (#675)
- [56a61c7f](https://github.com/kubedb/apimachinery/commit/56a61c7f) Change default resource limits to 1Gi ram and 500m cpu (#674)
- [a36050ca](https://github.com/kubedb/apimachinery/commit/a36050ca) Invoke update handler on labels or annotations change
- [37c68bd0](https://github.com/kubedb/apimachinery/commit/37c68bd0) Change offshoot selector labels to standard k8s app labels (#673)
- [83fb66c2](https://github.com/kubedb/apimachinery/commit/83fb66c2) Add redis constants and an address function (#663)
- [2c0e6319](https://github.com/kubedb/apimachinery/commit/2c0e6319) Add support for Elasticsearch volume expansion (#666)
- [d16f40aa](https://github.com/kubedb/apimachinery/commit/d16f40aa) Add changes to Elasticsearch vertical scaling spec (#662)
- [938147c4](https://github.com/kubedb/apimachinery/commit/938147c4) Add Elasticsearch scaling constants (#658)
- [b1641bdf](https://github.com/kubedb/apimachinery/commit/b1641bdf) Update for release Stash@v2020.12.17 (#671)
- [d37718a2](https://github.com/kubedb/apimachinery/commit/d37718a2) Remove doNotPause logic from namespace validator (#669)



## [kubedb/cli](https://github.com/kubedb/cli)

### [v0.16.0](https://github.com/kubedb/cli/releases/tag/v0.16.0)

- [82be6c3c](https://github.com/kubedb/cli/commit/82be6c3c) Prepare for release v0.16.0 (#578)
- [4e216d5b](https://github.com/kubedb/cli/commit/4e216d5b) Update KubeDB api (#577)
- [d49954d2](https://github.com/kubedb/cli/commit/d49954d2) Update KubeDB api (#576)
- [2a3bc5a8](https://github.com/kubedb/cli/commit/2a3bc5a8) Prepare for release v0.16.0-rc.0 (#575)
- [500b142a](https://github.com/kubedb/cli/commit/500b142a) Update KubeDB api (#574)
- [8208fcf1](https://github.com/kubedb/cli/commit/8208fcf1) Update KubeDB api (#573)
- [59ac94e7](https://github.com/kubedb/cli/commit/59ac94e7) Update Kubernetes v1.18.9 dependencies (#572)
- [1ebd0633](https://github.com/kubedb/cli/commit/1ebd0633) Update KubeDB api (#571)
- [0ccba4d1](https://github.com/kubedb/cli/commit/0ccba4d1) Update KubeDB api (#570)
- [770f94be](https://github.com/kubedb/cli/commit/770f94be) Update KubeDB api (#569)
- [fbdcce08](https://github.com/kubedb/cli/commit/fbdcce08) Update KubeDB api (#568)
- [93b038e9](https://github.com/kubedb/cli/commit/93b038e9) Update KubeDB api (#567)
- [ef758783](https://github.com/kubedb/cli/commit/ef758783) Update for release Stash@v2020.12.17 (#566)
- [07fa4a7e](https://github.com/kubedb/cli/commit/07fa4a7e) Update KubeDB api (#565)



## [kubedb/mongodb](https://github.com/kubedb/mongodb)

### [v0.9.0](https://github.com/kubedb/mongodb/releases/tag/v0.9.0)

- [59e808c4](https://github.com/kubedb/mongodb/commit/59e808c4) Prepare for release v0.9.0 (#354)
- [2d5c1629](https://github.com/kubedb/mongodb/commit/2d5c1629) Use constants from apimachinery (#352)
- [55ef5143](https://github.com/kubedb/mongodb/commit/55ef5143) Add inMemory Validator (#353)
- [3fb3258a](https://github.com/kubedb/mongodb/commit/3fb3258a) Update condition to not panic on invalid TLS configuration (#351)
- [1e9bb613](https://github.com/kubedb/mongodb/commit/1e9bb613) Update KubeDB api (#350)
- [f23949c6](https://github.com/kubedb/mongodb/commit/f23949c6) Update KubeDB api (#349)
- [ee410983](https://github.com/kubedb/mongodb/commit/ee410983) Prepare for release v0.9.0-rc.0 (#348)
- [b39b664b](https://github.com/kubedb/mongodb/commit/b39b664b) Update KubeDB api (#347)
- [84e007fe](https://github.com/kubedb/mongodb/commit/84e007fe) Update KubeDB api (#346)
- [e8aa1f8a](https://github.com/kubedb/mongodb/commit/e8aa1f8a) Close connections when operation completes (#338)
- [1ec2a2c7](https://github.com/kubedb/mongodb/commit/1ec2a2c7) Update Kubernetes v1.18.9 dependencies (#345)
- [7306fb26](https://github.com/kubedb/mongodb/commit/7306fb26) Update KubeDB api (#344)
- [efa62a85](https://github.com/kubedb/mongodb/commit/efa62a85) Fix annotations passing to AppBinding (#342)
- [9d88e69e](https://github.com/kubedb/mongodb/commit/9d88e69e) Remove `inMemory` setting from Config Server (#343)
- [32b96d12](https://github.com/kubedb/mongodb/commit/32b96d12) Change offshoot selector labels to standard k8s app labels (#341)
- [67fcdbf4](https://github.com/kubedb/mongodb/commit/67fcdbf4) Update KubeDB api (#340)
- [cf2c0778](https://github.com/kubedb/mongodb/commit/cf2c0778) Update KubeDB api (#339)
- [232a4a00](https://github.com/kubedb/mongodb/commit/232a4a00) Update KubeDB api (#337)
- [0a1307e7](https://github.com/kubedb/mongodb/commit/0a1307e7) Update for release Stash@v2020.12.17 (#336)
- [89b4e4fc](https://github.com/kubedb/mongodb/commit/89b4e4fc) Update KubeDB api (#335)



## [kubedb/mysql](https://github.com/kubedb/mysql)

### [v0.9.0](https://github.com/kubedb/mysql/releases/tag/v0.9.0)

- [e5e3a121](https://github.com/kubedb/mysql/commit/e5e3a121) Prepare for release v0.9.0 (#343)
- [192c6b83](https://github.com/kubedb/mysql/commit/192c6b83) Update health checker for cluster readiness check (#342)
- [2948601f](https://github.com/kubedb/mysql/commit/2948601f) Fix unit test failed for adding affinity rules to DB (#341)
- [de8198ce](https://github.com/kubedb/mysql/commit/de8198ce) Add Affinity rules to DB (#340)
- [1877e10f](https://github.com/kubedb/mysql/commit/1877e10f) Update KubeDB api (#339)
- [c7a40574](https://github.com/kubedb/mysql/commit/c7a40574) Pass --db-kind to replication mode detector (#338)
- [ad9d9879](https://github.com/kubedb/mysql/commit/ad9d9879) Prepare for release v0.9.0-rc.0 (#337)
- [a9e9d1f7](https://github.com/kubedb/mysql/commit/a9e9d1f7) Fix args for TLS (#336)
- [9dd89572](https://github.com/kubedb/mysql/commit/9dd89572) Update KubeDB api (#335)
- [29ff2c57](https://github.com/kubedb/mysql/commit/29ff2c57) Fixes DB Health Checker and StatefulSet Patch (#322)
- [47470895](https://github.com/kubedb/mysql/commit/47470895) Remove unnecessary StatefulSet waitloop (#331)
- [3aec8f59](https://github.com/kubedb/mysql/commit/3aec8f59) Update Kubernetes v1.18.9 dependencies (#334)
- [c1ca980d](https://github.com/kubedb/mysql/commit/c1ca980d) Update KubeDB api (#333)
- [96f4b59c](https://github.com/kubedb/mysql/commit/96f4b59c) Fix annotations passing to AppBinding (#332)
- [76f371a2](https://github.com/kubedb/mysql/commit/76f371a2) Change offshoot selector labels to standard k8s app labels (#329)
- [aa3d6b6f](https://github.com/kubedb/mysql/commit/aa3d6b6f) Delete tests moved to tests repo (#330)
- [6c544d2c](https://github.com/kubedb/mysql/commit/6c544d2c) Update KubeDB api (#328)
- [fe03a36c](https://github.com/kubedb/mysql/commit/fe03a36c) Update KubeDB api (#327)
- [29fd7474](https://github.com/kubedb/mysql/commit/29fd7474) Use basic-auth secret type for auth secret (#326)
- [90457549](https://github.com/kubedb/mysql/commit/90457549) Update KubeDB api (#325)
- [1487f15e](https://github.com/kubedb/mysql/commit/1487f15e) Update for release Stash@v2020.12.17 (#324)
- [2d7fa549](https://github.com/kubedb/mysql/commit/2d7fa549) Update KubeDB api (#323)



## [kubedb/pg-leader-election](https://github.com/kubedb/pg-leader-election)

### [v0.4.0](https://github.com/kubedb/pg-leader-election/releases/tag/v0.4.0)

- [31050c1](https://github.com/kubedb/pg-leader-election/commit/31050c1) Update KubeDB api (#44)
- [dc786b7](https://github.com/kubedb/pg-leader-election/commit/dc786b7) Update KubeDB api (#43)



## [kubedb/replication-mode-detector](https://github.com/kubedb/replication-mode-detector)

### [v0.3.0](https://github.com/kubedb/replication-mode-detector/releases/tag/v0.3.0)

- [f7b0e81](https://github.com/kubedb/replication-mode-detector/commit/f7b0e81) Prepare for release v0.3.0 (#118)
- [26111c6](https://github.com/kubedb/replication-mode-detector/commit/26111c6) Update KubeDB api (#117)
- [f5825e2](https://github.com/kubedb/replication-mode-detector/commit/f5825e2) Update KubeDB api (#116)
- [179e153](https://github.com/kubedb/replication-mode-detector/commit/179e153) Prepare for release v0.3.0-rc.0 (#115)
- [d47023b](https://github.com/kubedb/replication-mode-detector/commit/d47023b) Update KubeDB api (#114)
- [3e5db31](https://github.com/kubedb/replication-mode-detector/commit/3e5db31) Update KubeDB api (#113)
- [987f068](https://github.com/kubedb/replication-mode-detector/commit/987f068) Change offshoot selector labels to standard k8s app labels (#110)
- [21fc76f](https://github.com/kubedb/replication-mode-detector/commit/21fc76f) Update Kubernetes v1.18.9 dependencies (#112)
- [db85cbd](https://github.com/kubedb/replication-mode-detector/commit/db85cbd) Close database connection when operation completes (#107)
- [740d1d8](https://github.com/kubedb/replication-mode-detector/commit/740d1d8) Update Kubernetes v1.18.9 dependencies (#111)
- [6f228a5](https://github.com/kubedb/replication-mode-detector/commit/6f228a5) Update KubeDB api (#109)
- [256ea7a](https://github.com/kubedb/replication-mode-detector/commit/256ea7a) Update KubeDB api (#108)
- [7a9acc0](https://github.com/kubedb/replication-mode-detector/commit/7a9acc0) Update KubeDB api (#106)
- [21a18c2](https://github.com/kubedb/replication-mode-detector/commit/21a18c2) Update KubeDB api (#105)



