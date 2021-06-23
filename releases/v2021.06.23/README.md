# KubeDB v2021.06.23 (2021-06-23)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.19.0](https://github.com/kubedb/apimachinery/releases/tag/v0.19.0)

- [7cecea8e](https://github.com/kubedb/apimachinery/commit/7cecea8e) Add docs badge
- [c885fc2d](https://github.com/kubedb/apimachinery/commit/c885fc2d) Postgres DB Container's RunAsGroup As FSGroup (#769)
- [29cb0260](https://github.com/kubedb/apimachinery/commit/29cb0260) Add fixes to helper method (#768)
- [b20b40c2](https://github.com/kubedb/apimachinery/commit/b20b40c2) Use Stash v2021.06.23
- [e98fb31f](https://github.com/kubedb/apimachinery/commit/e98fb31f) Update audit event publisher (#767)
- [81e26637](https://github.com/kubedb/apimachinery/commit/81e26637) Add MariaDB Constants (#766)
- [532b6982](https://github.com/kubedb/apimachinery/commit/532b6982) Update Elasticsearch API to support various node roles including hot-warm-cold (#764)
- [a9979e15](https://github.com/kubedb/apimachinery/commit/a9979e15) Update for release Stash@v2021.6.18 (#765)
- [d20c46a2](https://github.com/kubedb/apimachinery/commit/d20c46a2) Fix locking in ResourceMapper
- [3a597982](https://github.com/kubedb/apimachinery/commit/3a597982) Send audit events if analytics enabled
- [27cc118e](https://github.com/kubedb/apimachinery/commit/27cc118e) Add auditor to shared Controller (#761)
- [eb13a94f](https://github.com/kubedb/apimachinery/commit/eb13a94f) Rename TimeoutSeconds to Timeout in MongoDBOpsRequest (#759)
- [29627ec6](https://github.com/kubedb/apimachinery/commit/29627ec6) Add timeout for each step of ES ops request (#742)
- [cc6b9690](https://github.com/kubedb/apimachinery/commit/cc6b9690) Add MariaDB OpsRequest Types (#743)
- [6fb2646e](https://github.com/kubedb/apimachinery/commit/6fb2646e) Update default resource limits for databases (#755)
- [161b3fe3](https://github.com/kubedb/apimachinery/commit/161b3fe3) Add UpdateMariaDBOpsRequestStatus function (#727)
- [98cd75f0](https://github.com/kubedb/apimachinery/commit/98cd75f0) Add Fields, Constant, Func  For Ops Request Postgres (#758)
- [722656b7](https://github.com/kubedb/apimachinery/commit/722656b7) Add Innodb Group Replication Mode (#750)
- [eb8e5883](https://github.com/kubedb/apimachinery/commit/eb8e5883) Replace go-bindata with //go:embed (#753)
- [df570f7b](https://github.com/kubedb/apimachinery/commit/df570f7b) Add HealthCheckInterval constant (#752)
- [e982e590](https://github.com/kubedb/apimachinery/commit/e982e590) Use kglog helper
- [e725873d](https://github.com/kubedb/apimachinery/commit/e725873d) Fix tests (#749)
- [11d1c306](https://github.com/kubedb/apimachinery/commit/11d1c306) Cleanup dependencies
- [7030bd8f](https://github.com/kubedb/apimachinery/commit/7030bd8f) Update crds
- [766fa11f](https://github.com/kubedb/apimachinery/commit/766fa11f) Update Kubernetes toolchain to v1.21.0 (#746)
- [12014667](https://github.com/kubedb/apimachinery/commit/12014667) Add Elasticsearch vertical scaling constants (#741)



## [kubedb/cli](https://github.com/kubedb/cli)

### [v0.19.0](https://github.com/kubedb/cli/releases/tag/v0.19.0)

- [2b394bba](https://github.com/kubedb/cli/commit/2b394bba) Prepare for release v0.19.0 (#610)
- [b367d2a5](https://github.com/kubedb/cli/commit/b367d2a5) Prepare for release v0.19.0-rc.0 (#609)
- [b9214d6a](https://github.com/kubedb/cli/commit/b9214d6a) Use Kubernetes 1.21.1 toolchain (#608)
- [36866cf5](https://github.com/kubedb/cli/commit/36866cf5) Use kglog helper
- [e4ee9973](https://github.com/kubedb/cli/commit/e4ee9973) Cleanup dependencies (#607)
- [07999fc2](https://github.com/kubedb/cli/commit/07999fc2) Use Kubernetes v1.21.0 toolchain (#606)
- [05e3b7e5](https://github.com/kubedb/cli/commit/05e3b7e5) Use Kubernetes v1.21.0 toolchain (#605)
- [44f4188e](https://github.com/kubedb/cli/commit/44f4188e) Use Kubernetes v1.21.0 toolchain (#604)
- [82cd8399](https://github.com/kubedb/cli/commit/82cd8399) Use Kubernetes v1.21.0 toolchain (#603)
- [998506cd](https://github.com/kubedb/cli/commit/998506cd) Use Kubernetes v1.21.0 toolchain (#602)
- [4ff64f94](https://github.com/kubedb/cli/commit/4ff64f94) Use Kubernetes v1.21.0 toolchain (#601)
- [19b257f1](https://github.com/kubedb/cli/commit/19b257f1) Update Kubernetes toolchain to v1.21.0 (#600)



## [kubedb/mariadb](https://github.com/kubedb/mariadb)

### [v0.3.0](https://github.com/kubedb/mariadb/releases/tag/v0.3.0)

- [189cc352](https://github.com/kubedb/mariadb/commit/189cc352) Prepare for release v0.3.0 (#78)
- [9b982f74](https://github.com/kubedb/mariadb/commit/9b982f74) Prepare for release v0.3.0-rc.0 (#77)
- [0ad0022c](https://github.com/kubedb/mariadb/commit/0ad0022c) Update audit lib (#75)
- [501a2e61](https://github.com/kubedb/mariadb/commit/501a2e61) Update custom config mount path for MariaDB Cluster (#59)
- [d00cf65b](https://github.com/kubedb/mariadb/commit/d00cf65b) Separate Reconcile functionality in a new function ReconcileNode (#68)
- [e9239d4f](https://github.com/kubedb/mariadb/commit/e9239d4f) Limit Go routines in Health Checker (#73)
- [d695adf1](https://github.com/kubedb/mariadb/commit/d695adf1) Send audit events if analytics enabled (#74)
- [070a0f79](https://github.com/kubedb/mariadb/commit/070a0f79) Create auditor if license file is provided (#72)
- [fc9046c3](https://github.com/kubedb/mariadb/commit/fc9046c3) Publish audit events (#71)
- [3a1f08a9](https://github.com/kubedb/mariadb/commit/3a1f08a9) Fix log level issue with klog for MariaDB (#70)
- [b6075e5d](https://github.com/kubedb/mariadb/commit/b6075e5d) Use kglog helper
- [f510e375](https://github.com/kubedb/mariadb/commit/f510e375) Use klog/v2
- [c009905e](https://github.com/kubedb/mariadb/commit/c009905e) Update Kubernetes toolchain to v1.21.0 (#66)



## [kubedb/tests](https://github.com/kubedb/tests)

### [v0.4.0](https://github.com/kubedb/tests/releases/tag/v0.4.0)

- [c6f1adc](https://github.com/kubedb/tests/commit/c6f1adc) Prepare for release v0.4.0 (#125)
- [b6b4be3](https://github.com/kubedb/tests/commit/b6b4be3) Prepare for release v0.4.0-rc.0 (#124)
- [62e6b50](https://github.com/kubedb/tests/commit/62e6b50) Fix locking in ResourceMapper (#123)
- [a855fab](https://github.com/kubedb/tests/commit/a855fab) Update dependencies (#122)
- [7d5b1a4](https://github.com/kubedb/tests/commit/7d5b1a4) Use kglog helper
- [a08eee4](https://github.com/kubedb/tests/commit/a08eee4) Use klog/v2
- [ed1afd4](https://github.com/kubedb/tests/commit/ed1afd4) Use Kubernetes v1.21.0 toolchain (#120)
- [ccb54f1](https://github.com/kubedb/tests/commit/ccb54f1) Use Kubernetes v1.21.0 toolchain (#119)
- [2a6f06d](https://github.com/kubedb/tests/commit/2a6f06d) Use Kubernetes v1.21.0 toolchain (#118)
- [7fb99f7](https://github.com/kubedb/tests/commit/7fb99f7) Use Kubernetes v1.21.0 toolchain (#117)
- [aaa0647](https://github.com/kubedb/tests/commit/aaa0647) Update Kubernetes toolchain to v1.21.0 (#116)
- [79d815d](https://github.com/kubedb/tests/commit/79d815d) Fix Elasticsearch status check while creating the client (#114)



