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



