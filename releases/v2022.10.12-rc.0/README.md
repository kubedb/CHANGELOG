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



