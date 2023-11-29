# KubeDB v2023.11.29-rc.0 (2023-11-29)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.38.0-rc.0](https://github.com/kubedb/apimachinery/releases/tag/v0.38.0-rc.0)

- [e070a3ae](https://github.com/kubedb/apimachinery/commit/e070a3ae) Do not default the seccompProfile (#1079)
- [29c96031](https://github.com/kubedb/apimachinery/commit/29c96031) Set Default Security Context for MariaDB (#1077)
- [fc35d376](https://github.com/kubedb/apimachinery/commit/fc35d376) Set default SecurityContext for mysql (#1070)
- [ee71aca0](https://github.com/kubedb/apimachinery/commit/ee71aca0) Update dependencies
- [93b5ba51](https://github.com/kubedb/apimachinery/commit/93b5ba51) add encriptSecret to postgresAchiver (#1078)
- [2b06b6e5](https://github.com/kubedb/apimachinery/commit/2b06b6e5) Add mongodb & postgres archiver (#1016)
- [47793c9a](https://github.com/kubedb/apimachinery/commit/47793c9a) Set default  SecurityContext for Elasticsearch. (#1072)
- [90567b46](https://github.com/kubedb/apimachinery/commit/90567b46) Set default SecurityContext for Kafka (#1068)
- [449a4e00](https://github.com/kubedb/apimachinery/commit/449a4e00) Remove redundant helper functions for Kafka and Update constants (#1074)
- [b28463f4](https://github.com/kubedb/apimachinery/commit/b28463f4) Set fsGroup to 999 to avoid mountedPath's files permission issue in different storageClass (#1075)
- [8e497b92](https://github.com/kubedb/apimachinery/commit/8e497b92) Set Default Security Context for Redis (#1073)
- [88ab93c7](https://github.com/kubedb/apimachinery/commit/88ab93c7) Set default SecurityContext for mongodb (#1067)
- [e7ac5d2e](https://github.com/kubedb/apimachinery/commit/e7ac5d2e) Set default for security Context for postgres (#1069)
- [f5de4a28](https://github.com/kubedb/apimachinery/commit/f5de4a28) Add support for init with git-sync; Add const (#1065)



## [kubedb/cli](https://github.com/kubedb/cli)

### [v0.38.0-rc.0](https://github.com/kubedb/cli/releases/tag/v0.38.0-rc.0)

- [3a4dcc47](https://github.com/kubedb/cli/commit/3a4dcc47) Prepare for release v0.38.0-rc.0 (#737)



## [kubedb/elasticsearch](https://github.com/kubedb/elasticsearch)

### [v0.38.0-rc.0](https://github.com/kubedb/elasticsearch/releases/tag/v0.38.0-rc.0)

- [6b2943f1](https://github.com/kubedb/elasticsearch/commit/6b2943f19) Prepare for release v0.38.0-rc.0 (#678)
- [7f1a37e1](https://github.com/kubedb/elasticsearch/commit/7f1a37e1a) Add prepare cluster installer before test runner (#677)
- [1d49f16d](https://github.com/kubedb/elasticsearch/commit/1d49f16d2) Remove `init-sysctl` container and add default containerSecurityContext (#676)
- [4bb15e48](https://github.com/kubedb/elasticsearch/commit/4bb15e48b) Update daily-opensearch workflow to provision v1.3.13



## [kubedb/memcached](https://github.com/kubedb/memcached)

### [v0.31.0-rc.0](https://github.com/kubedb/memcached/releases/tag/v0.31.0-rc.0)

- [e44be0a6](https://github.com/kubedb/memcached/commit/e44be0a6) Prepare for release v0.31.0-rc.0 (#405)



## [kubedb/mysql](https://github.com/kubedb/mysql)

### [v0.31.0-rc.0](https://github.com/kubedb/mysql/releases/tag/v0.31.0-rc.0)

- [3c005b51](https://github.com/kubedb/mysql/commit/3c005b51) Prepare for release v0.31.0-rc.0 (#572)
- [bcdfaf4a](https://github.com/kubedb/mysql/commit/bcdfaf4a) Set Default Security Context for MySQL (#571)
- [9009bcac](https://github.com/kubedb/mysql/commit/9009bcac) Add git sync constants from apimachinery (#570)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.16.0-rc.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.16.0-rc.0)




## [kubedb/percona-xtradb](https://github.com/kubedb/percona-xtradb)

### [v0.25.0-rc.0](https://github.com/kubedb/percona-xtradb/releases/tag/v0.25.0-rc.0)

- [d374a542](https://github.com/kubedb/percona-xtradb/commit/d374a542) Prepare for release v0.25.0-rc.0 (#331)



## [kubedb/pg-coordinator](https://github.com/kubedb/pg-coordinator)

### [v0.22.0-rc.0](https://github.com/kubedb/pg-coordinator/releases/tag/v0.22.0-rc.0)

- [e4efa4db](https://github.com/kubedb/pg-coordinator/commit/e4efa4db) Prepare for release v0.22.0-rc.0 (#139)
- [7c862bcd](https://github.com/kubedb/pg-coordinator/commit/7c862bcd) Add support for arbiter (#136)
- [53ba32a9](https://github.com/kubedb/pg-coordinator/commit/53ba32a9) added postgres 16.0 support (#137)
- [24445f9b](https://github.com/kubedb/pg-coordinator/commit/24445f9b) Added & modified logs (#134)



## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.38.0-rc.0](https://github.com/kubedb/postgres/releases/tag/v0.38.0-rc.0)

- [8738ad73](https://github.com/kubedb/postgres/commit/8738ad73e) Prepare for release v0.38.0-rc.0 (#684)
- [adb69b02](https://github.com/kubedb/postgres/commit/adb69b02e) Implement PostgreSQL archiver (#628)
- [668e15dd](https://github.com/kubedb/postgres/commit/668e15dd4) Remove test directory (#683)
- [d857c354](https://github.com/kubedb/postgres/commit/d857c354a) added postgres arbiter support (#677)
- [8fc98e8e](https://github.com/kubedb/postgres/commit/8fc98e8ed) Fixed a bug for init container (#681)
- [a2b408ff](https://github.com/kubedb/postgres/commit/a2b408ffb) Bugfix for security context (#680)
- [fb14015e](https://github.com/kubedb/postgres/commit/fb14015e9) added nightly yml for postgres (#679)



## [kubedb/postgres-archiver](https://github.com/kubedb/postgres-archiver)

### [v0.1.0-rc.0](https://github.com/kubedb/postgres-archiver/releases/tag/v0.1.0-rc.0)




## [kubedb/redis-coordinator](https://github.com/kubedb/redis-coordinator)

### [v0.17.0-rc.0](https://github.com/kubedb/redis-coordinator/releases/tag/v0.17.0-rc.0)

- [9f724e43](https://github.com/kubedb/redis-coordinator/commit/9f724e43) Prepare for release v0.17.0-rc.0 (#80)



## [kubedb/replication-mode-detector](https://github.com/kubedb/replication-mode-detector)

### [v0.25.0-rc.0](https://github.com/kubedb/replication-mode-detector/releases/tag/v0.25.0-rc.0)

- [77886a28](https://github.com/kubedb/replication-mode-detector/commit/77886a28) Prepare for release v0.25.0-rc.0 (#244)



