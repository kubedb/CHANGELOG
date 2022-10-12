# KubeDB v2022.10.12-rc.0 (2022-10-12)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.29.0-rc.0](https://github.com/kubedb/apimachinery/releases/tag/v0.29.0-rc.0)

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



## [kubedb/cli](https://github.com/kubedb/cli)

### [v0.29.0-rc.0](https://github.com/kubedb/cli/releases/tag/v0.29.0-rc.0)

- [8033e31b](https://github.com/kubedb/cli/commit/8033e31b) Prepare for release v0.29.0-rc.0 (#684)
- [b021f761](https://github.com/kubedb/cli/commit/b021f761) Update dependencies (#683)
- [792efd14](https://github.com/kubedb/cli/commit/792efd14) Support externally managed secrets (#681)
- [7ec2adbc](https://github.com/kubedb/cli/commit/7ec2adbc) Test against Kubernetes 1.25.0 (#682)
- [fc9b63c7](https://github.com/kubedb/cli/commit/fc9b63c7) Check for PDB version only once (#680)
- [81199060](https://github.com/kubedb/cli/commit/81199060) Handle status conversion for CronJob/VolumeSnapshot (#679)
- [17c6e94d](https://github.com/kubedb/cli/commit/17c6e94d) Use Go 1.19 (#678)
- [31c24f80](https://github.com/kubedb/cli/commit/31c24f80) Use k8s 1.25.1 libs (#677)
- [68e9ada6](https://github.com/kubedb/cli/commit/68e9ada6) Update README.md
- [4202bc84](https://github.com/kubedb/cli/commit/4202bc84) Stop using removed apis in Kubernetes 1.25 (#676)
- [eb922b19](https://github.com/kubedb/cli/commit/eb922b19) Use health checker types from kmodules (#675)



## [kubedb/elasticsearch](https://github.com/kubedb/elasticsearch)

### [v0.29.0-rc.0](https://github.com/kubedb/elasticsearch/releases/tag/v0.29.0-rc.0)

- [1e715c1a](https://github.com/kubedb/elasticsearch/commit/1e715c1a9) Prepare for release v0.29.0-rc.0 (#611)
- [4ab0de97](https://github.com/kubedb/elasticsearch/commit/4ab0de973) Update dependencies (#610)
- [1803a407](https://github.com/kubedb/elasticsearch/commit/1803a4078) Add support for Externally Managed secret (#609)
- [c2fb96e2](https://github.com/kubedb/elasticsearch/commit/c2fb96e2b) Test against Kubernetes 1.25.0 (#608)
- [96bbc6a8](https://github.com/kubedb/elasticsearch/commit/96bbc6a85) Check for PDB version only once (#606)
- [38099062](https://github.com/kubedb/elasticsearch/commit/380990623) Handle status conversion for CronJob/VolumeSnapshot (#605)
- [6e86f853](https://github.com/kubedb/elasticsearch/commit/6e86f853a) Use Go 1.19 (#604)
- [838ab6ae](https://github.com/kubedb/elasticsearch/commit/838ab6aec) Use k8s 1.25.1 libs (#603)
- [ce6877b5](https://github.com/kubedb/elasticsearch/commit/ce6877b58) Update README.md
- [297c6004](https://github.com/kubedb/elasticsearch/commit/297c60040) Stop using removed apis in Kubernetes 1.25 (#602)
- [7f9ef6bf](https://github.com/kubedb/elasticsearch/commit/7f9ef6bf1) Use health checker types from kmodules (#601)
- [baf9b9c1](https://github.com/kubedb/elasticsearch/commit/baf9b9c1b) Fix ClientCreated counter increment issue in healthchecker (#600)



## [kubedb/mariadb](https://github.com/kubedb/mariadb)

### [v0.13.0-rc.0](https://github.com/kubedb/mariadb/releases/tag/v0.13.0-rc.0)

- [b13d62cf](https://github.com/kubedb/mariadb/commit/b13d62cf) Prepare for release v0.13.0-rc.0 (#179)
- [5a8b0877](https://github.com/kubedb/mariadb/commit/5a8b0877) Add TLS Secret on Appbinding (#178)
- [a7f976f6](https://github.com/kubedb/mariadb/commit/a7f976f6) Add AppRef on AppBinding and Add Exporter Config Secret (#177)
- [a3d17697](https://github.com/kubedb/mariadb/commit/a3d17697) Update dependencies (#176)
- [8c666da8](https://github.com/kubedb/mariadb/commit/8c666da8) Add Externally Manage Secret Support (#175)
- [b14391f2](https://github.com/kubedb/mariadb/commit/b14391f2) Test against Kubernetes 1.25.0 (#174)
- [a07bbf68](https://github.com/kubedb/mariadb/commit/a07bbf68) Check for PDB version only once (#172)
- [8a316b93](https://github.com/kubedb/mariadb/commit/8a316b93) Handle status conversion for CronJob/VolumeSnapshot (#171)
- [56b6cd33](https://github.com/kubedb/mariadb/commit/56b6cd33) Use Go 1.19 (#170)
- [c666db48](https://github.com/kubedb/mariadb/commit/c666db48) Use k8s 1.25.1 libs (#169)
- [665d7f2a](https://github.com/kubedb/mariadb/commit/665d7f2a) Fix health check issue (#166)
- [c089e057](https://github.com/kubedb/mariadb/commit/c089e057) Update README.md
- [c0efefeb](https://github.com/kubedb/mariadb/commit/c0efefeb) Stop using removed apis in Kubernetes 1.25 (#168)
- [e3ef008e](https://github.com/kubedb/mariadb/commit/e3ef008e) Use health checker types from kmodules (#167)



## [kubedb/mongodb](https://github.com/kubedb/mongodb)

### [v0.22.0-rc.0](https://github.com/kubedb/mongodb/releases/tag/v0.22.0-rc.0)

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



## [kubedb/mysql](https://github.com/kubedb/mysql)

### [v0.22.0-rc.0](https://github.com/kubedb/mysql/releases/tag/v0.22.0-rc.0)

- [8386ed4c](https://github.com/kubedb/mysql/commit/8386ed4c) Prepare for release v0.22.0-rc.0 (#504)
- [8d58bbd8](https://github.com/kubedb/mysql/commit/8d58bbd8) Add cluster role for watching mysqlversion in coordinator (#503)
- [53b207b3](https://github.com/kubedb/mysql/commit/53b207b3) Add TLS Secret Name in appbinding (#501)
- [541e9f5e](https://github.com/kubedb/mysql/commit/541e9f5e) Update dependencies (#502)
- [e51a494c](https://github.com/kubedb/mysql/commit/e51a494c) Fix innodb router issues (#500)
- [c4f78c1f](https://github.com/kubedb/mysql/commit/c4f78c1f) Wait for externaly managed auth secret (#499)
- [90f337a2](https://github.com/kubedb/mysql/commit/90f337a2) Test against Kubernetes 1.25.0 (#498)
- [af6d6654](https://github.com/kubedb/mysql/commit/af6d6654) Check for PDB version only once (#496)
- [27611133](https://github.com/kubedb/mysql/commit/27611133) Handle status conversion for CronJob/VolumeSnapshot (#495)
- [a662b10d](https://github.com/kubedb/mysql/commit/a662b10d) Use Go 1.19 (#494)
- [07ce8211](https://github.com/kubedb/mysql/commit/07ce8211) Use k8s 1.25.1 libs (#493)
- [fac38c31](https://github.com/kubedb/mysql/commit/fac38c31) Update README.md
- [9676f388](https://github.com/kubedb/mysql/commit/9676f388) Stop using removed apis in Kubernetes 1.25 (#492)
- [db176142](https://github.com/kubedb/mysql/commit/db176142) Use health checker types from kmodules (#491)
- [3c9835b0](https://github.com/kubedb/mysql/commit/3c9835b0) Fix health check issue (#489)



## [kubedb/mysql-coordinator](https://github.com/kubedb/mysql-coordinator)

### [v0.7.0-rc.0](https://github.com/kubedb/mysql-coordinator/releases/tag/v0.7.0-rc.0)

- [b1d9ecf](https://github.com/kubedb/mysql-coordinator/commit/b1d9ecf) Prepare for release v0.7.0-rc.0 (#58)
- [88d01ef](https://github.com/kubedb/mysql-coordinator/commit/88d01ef) Update dependencies (#56)
- [cbb3504](https://github.com/kubedb/mysql-coordinator/commit/cbb3504) fix group_replication extra transcions jonning issue (#49)
- [8939e89](https://github.com/kubedb/mysql-coordinator/commit/8939e89) Test against Kubernetes 1.25.0 (#55)
- [0ba243d](https://github.com/kubedb/mysql-coordinator/commit/0ba243d) Check for PDB version only once (#53)
- [dac7227](https://github.com/kubedb/mysql-coordinator/commit/dac7227) Handle status conversion for CronJob/VolumeSnapshot (#52)
- [100f268](https://github.com/kubedb/mysql-coordinator/commit/100f268) Use Go 1.19 (#51)
- [07fc1af](https://github.com/kubedb/mysql-coordinator/commit/07fc1af) Use k8s 1.25.1 libs (#50)
- [71fe729](https://github.com/kubedb/mysql-coordinator/commit/71fe729) Stop using removed apis in Kubernetes 1.25 (#48)
- [f968206](https://github.com/kubedb/mysql-coordinator/commit/f968206) Use health checker types from kmodules (#47)
- [fa7ad1c](https://github.com/kubedb/mysql-coordinator/commit/fa7ad1c) Prepare for release v0.6.0-rc.1 (#46)
- [2c3615b](https://github.com/kubedb/mysql-coordinator/commit/2c3615b) update labels (#45)
- [38a4f88](https://github.com/kubedb/mysql-coordinator/commit/38a4f88) Update health checker (#43)
- [7c79e5f](https://github.com/kubedb/mysql-coordinator/commit/7c79e5f) Prepare for release v0.6.0-rc.0 (#42)
- [2eb313d](https://github.com/kubedb/mysql-coordinator/commit/2eb313d) Acquire license from license-proxyserver if available (#40)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.7.0-rc.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.7.0-rc.0)

- [e5eba9e](https://github.com/kubedb/mysql-router-init/commit/e5eba9e) Test against Kubernetes 1.25.0 (#26)
- [f0bdfdd](https://github.com/kubedb/mysql-router-init/commit/f0bdfdd) Use Go 1.19 (#25)
- [5631a3c](https://github.com/kubedb/mysql-router-init/commit/5631a3c) Use k8s 1.25.1 libs (#24)



## [kubedb/percona-xtradb](https://github.com/kubedb/percona-xtradb)

### [v0.16.0-rc.0](https://github.com/kubedb/percona-xtradb/releases/tag/v0.16.0-rc.0)

- [030e063d](https://github.com/kubedb/percona-xtradb/commit/030e063d) Prepare for release v0.16.0-rc.0 (#282)
- [47345de1](https://github.com/kubedb/percona-xtradb/commit/47345de1) Add TLS Secret on AppBinding (#281)
- [0aa33548](https://github.com/kubedb/percona-xtradb/commit/0aa33548) Add AppRef on AppBinding and Add Exporter Config Secret (#280)
- [82685157](https://github.com/kubedb/percona-xtradb/commit/82685157) Merge pull request #269 from kubedb/add-px-ops
- [f7f1898e](https://github.com/kubedb/percona-xtradb/commit/f7f1898e) Add Externally Managed Secret Support on PerconaXtraDB
- [43dcc76d](https://github.com/kubedb/percona-xtradb/commit/43dcc76d) Test against Kubernetes 1.25.0 (#278)
- [bc5c97db](https://github.com/kubedb/percona-xtradb/commit/bc5c97db) Check for PDB version only once (#276)
- [13a57a32](https://github.com/kubedb/percona-xtradb/commit/13a57a32) Handle status conversion for CronJob/VolumeSnapshot (#275)
- [6013a92e](https://github.com/kubedb/percona-xtradb/commit/6013a92e) Use Go 1.19 (#274)
- [45c413b9](https://github.com/kubedb/percona-xtradb/commit/45c413b9) Use k8s 1.25.1 libs (#273)
- [fd7d238a](https://github.com/kubedb/percona-xtradb/commit/fd7d238a) Update README.md
- [13da58d6](https://github.com/kubedb/percona-xtradb/commit/13da58d6) Stop using removed apis in Kubernetes 1.25 (#272)
- [6941e6d6](https://github.com/kubedb/percona-xtradb/commit/6941e6d6) Use health checker types from kmodules (#271)
- [9f813287](https://github.com/kubedb/percona-xtradb/commit/9f813287) Fix health check issue (#270)



## [kubedb/percona-xtradb-coordinator](https://github.com/kubedb/percona-xtradb-coordinator)

### [v0.2.0-rc.0](https://github.com/kubedb/percona-xtradb-coordinator/releases/tag/v0.2.0-rc.0)

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



## [kubedb/pg-coordinator](https://github.com/kubedb/pg-coordinator)

### [v0.13.0-rc.0](https://github.com/kubedb/pg-coordinator/releases/tag/v0.13.0-rc.0)

- [85fb61bb](https://github.com/kubedb/pg-coordinator/commit/85fb61bb) Prepare for release v0.13.0-rc.0 (#99)
- [58720b10](https://github.com/kubedb/pg-coordinator/commit/58720b10) Update dependencies (#98)
- [5a9dcc5f](https://github.com/kubedb/pg-coordinator/commit/5a9dcc5f) Test against Kubernetes 1.25.0 (#97)
- [eb45fd8e](https://github.com/kubedb/pg-coordinator/commit/eb45fd8e) Check for PDB version only once (#95)
- [a66884fb](https://github.com/kubedb/pg-coordinator/commit/a66884fb) Handle status conversion for CronJob/VolumeSnapshot (#94)
- [db150c63](https://github.com/kubedb/pg-coordinator/commit/db150c63) Use Go 1.19 (#93)
- [8bd4fcc5](https://github.com/kubedb/pg-coordinator/commit/8bd4fcc5) Use k8s 1.25.1 libs (#92)
- [4a510768](https://github.com/kubedb/pg-coordinator/commit/4a510768) Stop using removed apis in Kubernetes 1.25 (#91)
- [3b26263c](https://github.com/kubedb/pg-coordinator/commit/3b26263c) Use health checker types from kmodules (#90)



## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.29.0-rc.0](https://github.com/kubedb/postgres/releases/tag/v0.29.0-rc.0)

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



## [kubedb/redis](https://github.com/kubedb/redis)

### [v0.22.0-rc.0](https://github.com/kubedb/redis/releases/tag/v0.22.0-rc.0)

- [24a961a8](https://github.com/kubedb/redis/commit/24a961a8) Prepare for release v0.22.0-rc.0 (#432)
- [586d92c6](https://github.com/kubedb/redis/commit/586d92c6) Add Client Cert to Appbinding (#431)
- [9931e951](https://github.com/kubedb/redis/commit/9931e951) Update dependencies (#430)
- [5a27f772](https://github.com/kubedb/redis/commit/5a27f772) Add Redis Sentinel Ops Request Changes (#421)
- [81ad08ab](https://github.com/kubedb/redis/commit/81ad08ab) Add Support for Externally Managed Secret (#428)
- [b16212e4](https://github.com/kubedb/redis/commit/b16212e4) Test against Kubernetes 1.25.0 (#429)
- [05a1b814](https://github.com/kubedb/redis/commit/05a1b814) Check for PDB version only once (#427)
- [bd41d16d](https://github.com/kubedb/redis/commit/bd41d16d) Handle status conversion for CronJob/VolumeSnapshot (#426)
- [e1746638](https://github.com/kubedb/redis/commit/e1746638) Use Go 1.19 (#425)
- [b220f611](https://github.com/kubedb/redis/commit/b220f611) Use k8s 1.25.1 libs (#424)
- [538e2539](https://github.com/kubedb/redis/commit/538e2539) Update README.md
- [1513ca9a](https://github.com/kubedb/redis/commit/1513ca9a) Stop using removed apis in Kubernetes 1.25 (#423)
- [c29f0f6b](https://github.com/kubedb/redis/commit/c29f0f6b) Use health checker types from kmodules (#422)
- [bda4de79](https://github.com/kubedb/redis/commit/bda4de79) Fix health check issue (#420)



## [kubedb/redis-coordinator](https://github.com/kubedb/redis-coordinator)

### [v0.8.0-rc.0](https://github.com/kubedb/redis-coordinator/releases/tag/v0.8.0-rc.0)

- [21d63ea](https://github.com/kubedb/redis-coordinator/commit/21d63ea) Prepare for release v0.8.0-rc.0 (#52)
- [d7bcff0](https://github.com/kubedb/redis-coordinator/commit/d7bcff0) Update dependencies (#51)
- [db31014](https://github.com/kubedb/redis-coordinator/commit/db31014) Add Redis Sentinel Ops Requests Changes (#48)
- [3bc6a63](https://github.com/kubedb/redis-coordinator/commit/3bc6a63) Test against Kubernetes 1.25.0 (#50)
- [b144d17](https://github.com/kubedb/redis-coordinator/commit/b144d17) Check for PDB version only once (#47)
- [803f76a](https://github.com/kubedb/redis-coordinator/commit/803f76a) Handle status conversion for CronJob/VolumeSnapshot (#46)
- [a7cd5af](https://github.com/kubedb/redis-coordinator/commit/a7cd5af) Use Go 1.19 (#45)
- [f066d36](https://github.com/kubedb/redis-coordinator/commit/f066d36) Use k8s 1.25.1 libs (#44)
- [db04c50](https://github.com/kubedb/redis-coordinator/commit/db04c50) Stop using removed apis in Kubernetes 1.25 (#43)
- [10f1fb5](https://github.com/kubedb/redis-coordinator/commit/10f1fb5) Use health checker types from kmodules (#42)



## [kubedb/replication-mode-detector](https://github.com/kubedb/replication-mode-detector)

### [v0.16.0-rc.0](https://github.com/kubedb/replication-mode-detector/releases/tag/v0.16.0-rc.0)

- [d051a8eb](https://github.com/kubedb/replication-mode-detector/commit/d051a8eb) Prepare for release v0.16.0-rc.0 (#214)
- [2d51c3f3](https://github.com/kubedb/replication-mode-detector/commit/2d51c3f3) Update dependencies (#213)
- [0a544cf9](https://github.com/kubedb/replication-mode-detector/commit/0a544cf9) Test against Kubernetes 1.25.0 (#212)
- [aa1635cf](https://github.com/kubedb/replication-mode-detector/commit/aa1635cf) Check for PDB version only once (#210)
- [6549acf6](https://github.com/kubedb/replication-mode-detector/commit/6549acf6) Handle status conversion for CronJob/VolumeSnapshot (#209)
- [fc7a68fd](https://github.com/kubedb/replication-mode-detector/commit/fc7a68fd) Use Go 1.19 (#208)
- [2f9a7435](https://github.com/kubedb/replication-mode-detector/commit/2f9a7435) Use k8s 1.25.1 libs (#207)
- [c831c08e](https://github.com/kubedb/replication-mode-detector/commit/c831c08e) Stop using removed apis in Kubernetes 1.25 (#206)
- [8c80e5b4](https://github.com/kubedb/replication-mode-detector/commit/8c80e5b4) Use health checker types from kmodules (#205)



## [kubedb/tests](https://github.com/kubedb/tests)

### [v0.14.0-rc.0](https://github.com/kubedb/tests/releases/tag/v0.14.0-rc.0)

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



