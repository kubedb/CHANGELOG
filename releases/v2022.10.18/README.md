# KubeDB v2022.10.18 (2022-10-15)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.29.0](https://github.com/kubedb/apimachinery/releases/tag/v0.29.0)

- [daeafa99](https://github.com/kubedb/apimachinery/commit/daeafa99) Update crds properly
- [fc357a90](https://github.com/kubedb/apimachinery/commit/fc357a90) Make exporter optional in ProxySQL catalog (#992)
- [7d01a527](https://github.com/kubedb/apimachinery/commit/7d01a527) Add conditions for postgres logical replication. (#990)
- [197a2568](https://github.com/kubedb/apimachinery/commit/197a2568) Remove storage autoscaler from Sentinel spec (#991)
- [2dae1fa1](https://github.com/kubedb/apimachinery/commit/2dae1fa1) Add GetSystemUserSecret Heplers on PerconaXtraDB (#989)
- [35e1d5e5](https://github.com/kubedb/apimachinery/commit/35e1d5e5) Make OpsRequestType specific to databases (#988)
- [e7310243](https://github.com/kubedb/apimachinery/commit/e7310243) Add Redis Sentinel Ops Requests APIs (#958)
- [b937b3dc](https://github.com/kubedb/apimachinery/commit/b937b3dc) Update digest.go
- [1b1732a9](https://github.com/kubedb/apimachinery/commit/1b1732a9) Change ProxySQL backend to a local obj ref (#987)
- [31c66a34](https://github.com/kubedb/apimachinery/commit/31c66a34) Include Arbiter & hidden nodes in MongoAutoscaler (#979)
- [3c2f4a7a](https://github.com/kubedb/apimachinery/commit/3c2f4a7a) Add autoscaler types for Postgres (#969)
- [9f60ebbe](https://github.com/kubedb/apimachinery/commit/9f60ebbe) Add GetAuthSecretName() helper (#986)
- [b48d0118](https://github.com/kubedb/apimachinery/commit/b48d0118) Ignore TLS certificate validation when using private domains (#984)
- [11a09d52](https://github.com/kubedb/apimachinery/commit/11a09d52) Use stash.appscode.dev/apimachinery@v0.23.0 (#983)
- [cb611290](https://github.com/kubedb/apimachinery/commit/cb611290) Remove duplicate short name from redis sentinel (#982)
- [f5eabfc2](https://github.com/kubedb/apimachinery/commit/f5eabfc2) Fix typo 'SuccessfullyRestatedStatefulSet' (#980)
- [4f6d7eac](https://github.com/kubedb/apimachinery/commit/4f6d7eac) Test against Kubernetes 1.25.0 (#981)
- [c0388bc2](https://github.com/kubedb/apimachinery/commit/c0388bc2) Use authSecret.externallyManaged field (#978)
- [7f39736a](https://github.com/kubedb/apimachinery/commit/7f39736a) Remove default values from authSecret (#977)
- [2d9abdb4](https://github.com/kubedb/apimachinery/commit/2d9abdb4) Support different types of secrets and password rotation (#976)
- [f01cf5b9](https://github.com/kubedb/apimachinery/commit/f01cf5b9) Using opsRequestOpts for elastic,maria & percona (#970)
- [e26f6417](https://github.com/kubedb/apimachinery/commit/e26f6417) Fix typos of Postgres Logical Replication CRDs. (#974)
- [d43f454e](https://github.com/kubedb/apimachinery/commit/d43f454e) Check for PDB version only once (#975)
- [fb5283cd](https://github.com/kubedb/apimachinery/commit/fb5283cd) Handle status conversion for PDB (#973)
- [7263b503](https://github.com/kubedb/apimachinery/commit/7263b503) Update kutil
- [5c643b97](https://github.com/kubedb/apimachinery/commit/5c643b97) Use Go 1.19
- [a0b96812](https://github.com/kubedb/apimachinery/commit/a0b96812) Fix mergo dependency
- [b7b93597](https://github.com/kubedb/apimachinery/commit/b7b93597) Use k8s 1.25.1 libs (#971)
- [c1f407b0](https://github.com/kubedb/apimachinery/commit/c1f407b0) Add MySQLAutoscaler support (#968)
- [693f5243](https://github.com/kubedb/apimachinery/commit/693f5243) Add MongoDB HiddenNode support (#956)
- [0b3be441](https://github.com/kubedb/apimachinery/commit/0b3be441) Add Postgres Publisher & Subscriber CRDs (#967)
- [71947dec](https://github.com/kubedb/apimachinery/commit/71947dec) Update README.md
- [818f48fa](https://github.com/kubedb/apimachinery/commit/818f48fa) Add redis-sentinel autoscaler types (#965)
- [011938c4](https://github.com/kubedb/apimachinery/commit/011938c4) Add PerconaXtraDB OpsReq and Autoscaler APIs (#953)
- [b57e7099](https://github.com/kubedb/apimachinery/commit/b57e7099) Add RedisAutoscaler support (#963)
- [2ccea895](https://github.com/kubedb/apimachinery/commit/2ccea895) Remove `DisableScaleDown` field from autoscaler (#966)
- [02b47709](https://github.com/kubedb/apimachinery/commit/02b47709) Support PDB v1 or v1beta1 api based on k8s version (#964)
- [e2d0bb4f](https://github.com/kubedb/apimachinery/commit/e2d0bb4f) Stop using removed apis in Kubernetes 1.25 (#962)
- [722a1bc1](https://github.com/kubedb/apimachinery/commit/722a1bc1) Use health checker types from kmodules (#961)



## [kubedb/mongodb](https://github.com/kubedb/mongodb)

### [v0.22.0](https://github.com/kubedb/mongodb/releases/tag/v0.22.0)

- [fe689daa](https://github.com/kubedb/mongodb/commit/fe689daa) Prepare for release v0.22.0 (#519)
- [e6ce6f0e](https://github.com/kubedb/mongodb/commit/e6ce6f0e) Use password-generator@v0.2.9 (#518)
- [b9e03cc5](https://github.com/kubedb/mongodb/commit/b9e03cc5) Prepare for release v0.22.0-rc.0 (#517)
- [2f0c8b65](https://github.com/kubedb/mongodb/commit/2f0c8b65) Set TLSSecret name (#516)
- [ffb021ea](https://github.com/kubedb/mongodb/commit/ffb021ea) Configure AppRef in appbinding (#515)
- [2c9eb87b](https://github.com/kubedb/mongodb/commit/2c9eb87b) Add support for externally-managed authSecret (#514)
- [f4789ab7](https://github.com/kubedb/mongodb/commit/f4789ab7) Test against Kubernetes 1.25.0 (#513)
- [9ad4c219](https://github.com/kubedb/mongodb/commit/9ad4c219) Change operator name in event (#511)
- [dbb7ff10](https://github.com/kubedb/mongodb/commit/dbb7ff10) Check for PDB version only once (#510)
- [79d53b0a](https://github.com/kubedb/mongodb/commit/79d53b0a) Handle status conversion for CronJob/VolumeSnapshot (#509)
- [37521202](https://github.com/kubedb/mongodb/commit/37521202) Use Go 1.19 (#508)
- [d1a2d55a](https://github.com/kubedb/mongodb/commit/d1a2d55a) Use k8s 1.25.1 libs (#507)
- [43399906](https://github.com/kubedb/mongodb/commit/43399906) Add support for Hidden node (#503)
- [91acbffc](https://github.com/kubedb/mongodb/commit/91acbffc) Update README.md
- [b053290c](https://github.com/kubedb/mongodb/commit/b053290c) Stop using removed apis in Kubernetes 1.25 (#506)
- [79b99580](https://github.com/kubedb/mongodb/commit/79b99580) Use health checker types from kmodules (#505)
- [ff39883d](https://github.com/kubedb/mongodb/commit/ff39883d) Fix health check issue (#504)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.7.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.7.0)

- [e5eba9e](https://github.com/kubedb/mysql-router-init/commit/e5eba9e) Test against Kubernetes 1.25.0 (#26)
- [f0bdfdd](https://github.com/kubedb/mysql-router-init/commit/f0bdfdd) Use Go 1.19 (#25)
- [5631a3c](https://github.com/kubedb/mysql-router-init/commit/5631a3c) Use k8s 1.25.1 libs (#24)



## [kubedb/percona-xtradb-coordinator](https://github.com/kubedb/percona-xtradb-coordinator)

### [v0.2.0](https://github.com/kubedb/percona-xtradb-coordinator/releases/tag/v0.2.0)

- [9a28a21](https://github.com/kubedb/percona-xtradb-coordinator/commit/9a28a21) Prepare for release v0.2.0 (#20)
- [cf6c54c](https://github.com/kubedb/percona-xtradb-coordinator/commit/cf6c54c) Prepare for release v0.2.0-rc.0 (#19)
- [a71e01d](https://github.com/kubedb/percona-xtradb-coordinator/commit/a71e01d) Update dependencies (#18)
- [0b51751](https://github.com/kubedb/percona-xtradb-coordinator/commit/0b51751) Test against Kubernetes 1.25.0 (#17)
- [1f2b1a5](https://github.com/kubedb/percona-xtradb-coordinator/commit/1f2b1a5) Check for PDB version only once (#15)
- [03125ba](https://github.com/kubedb/percona-xtradb-coordinator/commit/03125ba) Handle status conversion for CronJob/VolumeSnapshot (#14)
- [06a2634](https://github.com/kubedb/percona-xtradb-coordinator/commit/06a2634) Use Go 1.19 (#13)
- [1a8a90b](https://github.com/kubedb/percona-xtradb-coordinator/commit/1a8a90b) Use k8s 1.25.1 libs (#12)
- [f33c751](https://github.com/kubedb/percona-xtradb-coordinator/commit/f33c751) Stop using removed apis in Kubernetes 1.25 (#11)
- [91495bf](https://github.com/kubedb/percona-xtradb-coordinator/commit/91495bf) Use health checker types from kmodules (#10)
- [290e281](https://github.com/kubedb/percona-xtradb-coordinator/commit/290e281) Prepare for release v0.1.0-rc.1 (#9)
- [c57449c](https://github.com/kubedb/percona-xtradb-coordinator/commit/c57449c) Update health checker (#8)
- [adad8b5](https://github.com/kubedb/percona-xtradb-coordinator/commit/adad8b5) Acquire license from license-proxyserver if available (#7)



## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.29.0](https://github.com/kubedb/postgres/releases/tag/v0.29.0)

- [08afda20](https://github.com/kubedb/postgres/commit/08afda20) Prepare for release v0.29.0 (#607)
- [ad39a6cf](https://github.com/kubedb/postgres/commit/ad39a6cf) Update password generator hash (#606)
- [cd547a68](https://github.com/kubedb/postgres/commit/cd547a68) Prepare for release v0.29.0-rc.0 (#605)
- [9d98af14](https://github.com/kubedb/postgres/commit/9d98af14) Fix TlsSecret for AppBinding (#604)
- [7d73ce99](https://github.com/kubedb/postgres/commit/7d73ce99) Update dependencies (#603)
- [d8515a3f](https://github.com/kubedb/postgres/commit/d8515a3f) Configure appRef in AppBinding (#602)
- [69458e25](https://github.com/kubedb/postgres/commit/69458e25) Check auth secrets labels if key exists (#601)
- [3dd3563b](https://github.com/kubedb/postgres/commit/3dd3563b) Simplify ensureAuthSecret (#600)
- [67f3db64](https://github.com/kubedb/postgres/commit/67f3db64) Relax Postgres key detection for a secret (#599)
- [acdd2cda](https://github.com/kubedb/postgres/commit/acdd2cda) Add support for Externally Managed secret (#597)
- [5121a362](https://github.com/kubedb/postgres/commit/5121a362) Test against Kubernetes 1.25.0 (#598)
- [bfa46b08](https://github.com/kubedb/postgres/commit/bfa46b08) Check for PDB version only once (#594)
- [150fcf2c](https://github.com/kubedb/postgres/commit/150fcf2c) Handle status conversion for CronJob/VolumeSnapshot (#593)
- [86ff76e1](https://github.com/kubedb/postgres/commit/86ff76e1) Use Go 1.19 (#592)
- [7732e22b](https://github.com/kubedb/postgres/commit/7732e22b) Use k8s 1.25.1 libs (#591)
- [b4c7f426](https://github.com/kubedb/postgres/commit/b4c7f426) Update README.md
- [68b06e68](https://github.com/kubedb/postgres/commit/68b06e68) Stop using removed apis in Kubernetes 1.25 (#590)
- [51f600b9](https://github.com/kubedb/postgres/commit/51f600b9) Use health checker types from kmodules (#589)
- [2e45ad1b](https://github.com/kubedb/postgres/commit/2e45ad1b) Fix health check issue (#588)



## [kubedb/tests](https://github.com/kubedb/tests)

### [v0.14.0](https://github.com/kubedb/tests/releases/tag/v0.14.0)

- [1737b25f](https://github.com/kubedb/tests/commit/1737b25f) Prepare for release v0.14.0 (#203)
- [f272557a](https://github.com/kubedb/tests/commit/f272557a) Add MongoDB arbiter-related tests (#172)
- [e7c55a30](https://github.com/kubedb/tests/commit/e7c55a30) Use password-generator@v0.2.9 (#201)
- [a2d4d3ac](https://github.com/kubedb/tests/commit/a2d4d3ac) Prepare for release v0.14.0-rc.0 (#200)
- [03a028e7](https://github.com/kubedb/tests/commit/03a028e7) Update dependencies (#197)
- [b34253e7](https://github.com/kubedb/tests/commit/b34253e7) Test against Kubernetes 1.25.0 (#196)
- [b2c48e72](https://github.com/kubedb/tests/commit/b2c48e72) Check for PDB version only once (#194)
- [bd0b7f66](https://github.com/kubedb/tests/commit/bd0b7f66) Handle status conversion for CronJob/VolumeSnapshot (#193)
- [8e5103d0](https://github.com/kubedb/tests/commit/8e5103d0) Use Go 1.19 (#192)
- [096cfbf6](https://github.com/kubedb/tests/commit/096cfbf6) Use k8s 1.25.1 libs (#191)
- [6c45ea94](https://github.com/kubedb/tests/commit/6c45ea94) Migrate to GinkgoV2 (#188)
- [f89ab1c1](https://github.com/kubedb/tests/commit/f89ab1c1) Stop using removed apis in Kubernetes 1.25 (#190)
- [17954e8b](https://github.com/kubedb/tests/commit/17954e8b) Use health checker types from kmodules (#189)


