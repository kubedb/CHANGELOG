# KubeDB v2022.05.24 (2022-05-20)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.27.0](https://github.com/kubedb/apimachinery/releases/tag/v0.27.0)

- [3634eb14](https://github.com/kubedb/apimachinery/commit/3634eb14) Add `HealthCheckPaused` condition and `Unknown` phase (#898)
- [a3a3b1df](https://github.com/kubedb/apimachinery/commit/a3a3b1df) Add Raft metrics port as constants (#896)
- [6f9afd91](https://github.com/kubedb/apimachinery/commit/6f9afd91) Add support for MySQL semi-sync cluster (#890)
- [bf17bf6d](https://github.com/kubedb/apimachinery/commit/bf17bf6d) Add constants for Kibana 8 (#894)
- [a8461374](https://github.com/kubedb/apimachinery/commit/a8461374) Add method and constants for proxysql (#893)
- [a57c9577](https://github.com/kubedb/apimachinery/commit/a57c9577) Add doubleOptIn funcs & shortnames for schema-manager (#889)
- [af6f51f3](https://github.com/kubedb/apimachinery/commit/af6f51f3) Add constants and helpers for ES Internal Users (#886)
- [74c4fc13](https://github.com/kubedb/apimachinery/commit/74c4fc13) Fix typo (#888)
- [023a7988](https://github.com/kubedb/apimachinery/commit/023a7988) Update ProxySQL types and helpers (#883)
- [29217d17](https://github.com/kubedb/apimachinery/commit/29217d17) Fix pgbouncer Version Spec
- [3b994342](https://github.com/kubedb/apimachinery/commit/3b994342) Add support for mariadbdatabase with webhook (#858)
- [4be4a876](https://github.com/kubedb/apimachinery/commit/4be4a876) Add spec for MongoDB arbiter support (#862)
- [36e97b5a](https://github.com/kubedb/apimachinery/commit/36e97b5a) Add TopologySpreadConstraints (#885)
- [27c7483d](https://github.com/kubedb/apimachinery/commit/27c7483d) Add SyncStatefulSetPodDisruptionBudget helper method (#884)
- [0e635b9f](https://github.com/kubedb/apimachinery/commit/0e635b9f) Make ClusterHealth inline in ES insight (#881)
- [761d8ca3](https://github.com/kubedb/apimachinery/commit/761d8ca3) fix: update Postgres shared buffer func (#880)
- [8579cef3](https://github.com/kubedb/apimachinery/commit/8579cef3) Add Support for Opensearch Dashboards (#878)
- [24eadd87](https://github.com/kubedb/apimachinery/commit/24eadd87) Use Go 1.18 (#879)



## [kubedb/cli](https://github.com/kubedb/cli)

### [v0.27.0](https://github.com/kubedb/cli/releases/tag/v0.27.0)

- [01318a20](https://github.com/kubedb/cli/commit/01318a20) Prepare for release v0.27.0 (#664)
- [6d399a31](https://github.com/kubedb/cli/commit/6d399a31) Update dependencies (#663)
- [3e9a658f](https://github.com/kubedb/cli/commit/3e9a658f) Update dependencies(nats client, mongo-driver) (#662)



## [kubedb/elasticsearch](https://github.com/kubedb/elasticsearch)

### [v0.27.0](https://github.com/kubedb/elasticsearch/releases/tag/v0.27.0)

- [ba7dee10](https://github.com/kubedb/elasticsearch/commit/ba7dee10) Prepare for release v0.27.0 (#577)
- [cfdb4d21](https://github.com/kubedb/elasticsearch/commit/cfdb4d21) Update dependencies (#576)
- [d24dfadc](https://github.com/kubedb/elasticsearch/commit/d24dfadc) Add support for ElasticStack Built-In  Users (#574)
- [cdb4d974](https://github.com/kubedb/elasticsearch/commit/cdb4d974) Update dependencies(nats client, mongo-driver) (#575)
- [865d0703](https://github.com/kubedb/elasticsearch/commit/865d0703) Add support for Elasticsearch 8 (#573)



## [kubedb/mariadb](https://github.com/kubedb/mariadb)

### [v0.11.0](https://github.com/kubedb/mariadb/releases/tag/v0.11.0)

- [b2fd680d](https://github.com/kubedb/mariadb/commit/b2fd680d) Prepare for release v0.11.0 (#147)
- [39ac8190](https://github.com/kubedb/mariadb/commit/39ac8190) Update dependencies (#146)
- [f081a5ee](https://github.com/kubedb/mariadb/commit/f081a5ee) Update MariaDB conditions on health check (#138)
- [385f270d](https://github.com/kubedb/mariadb/commit/385f270d) Update dependencies(nats client, mongo-driver) (#145)
- [6879d6a6](https://github.com/kubedb/mariadb/commit/6879d6a6) Cleanup PodDisruptionBudget when the replica count is one or less (#144)



## [kubedb/mariadb-coordinator](https://github.com/kubedb/mariadb-coordinator)

### [v0.7.0](https://github.com/kubedb/mariadb-coordinator/releases/tag/v0.7.0)

- [23da6cd](https://github.com/kubedb/mariadb-coordinator/commit/23da6cd) Prepare for release v0.7.0 (#43)
- [e1fca00](https://github.com/kubedb/mariadb-coordinator/commit/e1fca00) Update dependencies (#42)
- [20d90c6](https://github.com/kubedb/mariadb-coordinator/commit/20d90c6) Update dependencies(nats client, mongo-driver) (#41)



## [kubedb/mongodb](https://github.com/kubedb/mongodb)

### [v0.20.0](https://github.com/kubedb/mongodb/releases/tag/v0.20.0)

- [85063ec7](https://github.com/kubedb/mongodb/commit/85063ec7) Prepare for release v0.20.0 (#477)
- [ab3a33f7](https://github.com/kubedb/mongodb/commit/ab3a33f7) Update dependencies (#476)
- [275fbdc4](https://github.com/kubedb/mongodb/commit/275fbdc4) Fix shard database write check (#475)
- [643c958c](https://github.com/kubedb/mongodb/commit/643c958c) Use updated commit-hash (#474)
- [8ba58693](https://github.com/kubedb/mongodb/commit/8ba58693) Add arbiter support (#470)
- [a8ecbc33](https://github.com/kubedb/mongodb/commit/a8ecbc33) Update dependencies(nats client, mongo-driver) (#472)
- [3073bbec](https://github.com/kubedb/mongodb/commit/3073bbec) Cleanup PodDisruptionBudget when the replica count is one or less (#471)
- [e7c146cb](https://github.com/kubedb/mongodb/commit/e7c146cb) Refactor statefulset-related files (#449)



## [kubedb/mysql](https://github.com/kubedb/mysql)

### [v0.20.0](https://github.com/kubedb/mysql/releases/tag/v0.20.0)

- [988eab76](https://github.com/kubedb/mysql/commit/988eab76) Prepare for release v0.20.0 (#470)
- [47c7e612](https://github.com/kubedb/mysql/commit/47c7e612) Update dependencies (#469)
- [a972735f](https://github.com/kubedb/mysql/commit/a972735f) Pass `--set-gtid-purged=OFF` to app binding for stash (#468)
- [a4f2e6a5](https://github.com/kubedb/mysql/commit/a4f2e6a5) Add Raft Server ports for MySQL Semi-sync (#467)
- [b9a3c322](https://github.com/kubedb/mysql/commit/b9a3c322) Add Support for Semi-sync cluster (#464)
- [2d7a0080](https://github.com/kubedb/mysql/commit/2d7a0080) Update dependencies(nats client, mongo-driver) (#466)
- [684d553a](https://github.com/kubedb/mysql/commit/684d553a) Cleanup PodDisruptionBudget when the replica count is one or less (#462)
- [5caa331a](https://github.com/kubedb/mysql/commit/5caa331a) Patch existing Auth secret to db ojbect (#463)



## [kubedb/percona-xtradb](https://github.com/kubedb/percona-xtradb)

### [v0.14.0](https://github.com/kubedb/percona-xtradb/releases/tag/v0.14.0)

- [83f74c17](https://github.com/kubedb/percona-xtradb/commit/83f74c17) Prepare for release v0.14.0 (#258)
- [bfae8113](https://github.com/kubedb/percona-xtradb/commit/bfae8113) Update dependencies (#257)
- [bcc010f8](https://github.com/kubedb/percona-xtradb/commit/bcc010f8) Update dependencies(nats client, mongo-driver) (#256)



## [kubedb/pg-coordinator](https://github.com/kubedb/pg-coordinator)

### [v0.11.0](https://github.com/kubedb/pg-coordinator/releases/tag/v0.11.0)

- [373a83e](https://github.com/kubedb/pg-coordinator/commit/373a83e) Prepare for release v0.11.0 (#80)
- [254c361](https://github.com/kubedb/pg-coordinator/commit/254c361) Update dependencies (#79)
- [7f6a6c0](https://github.com/kubedb/pg-coordinator/commit/7f6a6c0) Add Raft Metrics And graceful shutdown of Postgres (#74)
- [c1a5b53](https://github.com/kubedb/pg-coordinator/commit/c1a5b53) Update dependencies(nats client, mongo-driver) (#78)
- [b6da859](https://github.com/kubedb/pg-coordinator/commit/b6da859) Fix: Fast Shut-down Postgres server to avoid single-user mode shutdown failure (#73)



## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.27.0](https://github.com/kubedb/postgres/releases/tag/v0.27.0)

- [bc3cf38e](https://github.com/kubedb/postgres/commit/bc3cf38e) Prepare for release v0.27.0 (#573)
- [14c87e8f](https://github.com/kubedb/postgres/commit/14c87e8f) Update dependencies (#572)
- [7cb31a1d](https://github.com/kubedb/postgres/commit/7cb31a1d) Add Raft Metrics exporter Port for Monitoring (#569)
- [3a71b165](https://github.com/kubedb/postgres/commit/3a71b165) Update dependencies(nats client, mongo-driver) (#571)
- [131dd7d9](https://github.com/kubedb/postgres/commit/131dd7d9) Cleanup podDiscruptionBudget when the replica count is one or less (#570)
- [44e929d8](https://github.com/kubedb/postgres/commit/44e929d8) Fix: Fast Shut-down Postgres server to avoid single-user mode shutdown failure (#568)



## [kubedb/redis](https://github.com/kubedb/redis)

### [v0.20.0](https://github.com/kubedb/redis/releases/tag/v0.20.0)

- [3dcfc3c7](https://github.com/kubedb/redis/commit/3dcfc3c7) Prepare for release v0.20.0 (#397)
- [ac65b0b3](https://github.com/kubedb/redis/commit/ac65b0b3) Update dependencies (#396)
- [177c0329](https://github.com/kubedb/redis/commit/177c0329) Update dependencies(nats client, mongo-driver) (#395)
- [6bf1db27](https://github.com/kubedb/redis/commit/6bf1db27) Redis Shard Cluster Dynamic Failover (#393)
- [4fa76436](https://github.com/kubedb/redis/commit/4fa76436) Refactor StatefulSet ENVs for Redis (#394)
- [b12bfef9](https://github.com/kubedb/redis/commit/b12bfef9) Cleanup PodDisruptionBudget when the replica count is one or less (#392)



## [kubedb/redis-coordinator](https://github.com/kubedb/redis-coordinator)

### [v0.6.0](https://github.com/kubedb/redis-coordinator/releases/tag/v0.6.0)

- [fb4f029](https://github.com/kubedb/redis-coordinator/commit/fb4f029) Prepare for release v0.6.0 (#33)
- [69cc834](https://github.com/kubedb/redis-coordinator/commit/69cc834) Update dependencies (#32)
- [9c1cbd9](https://github.com/kubedb/redis-coordinator/commit/9c1cbd9) Update dependencies(nats client, mongo-driver) (#31)
- [33baab6](https://github.com/kubedb/redis-coordinator/commit/33baab6) Update Env Variables (#30)



## [kubedb/replication-mode-detector](https://github.com/kubedb/replication-mode-detector)

### [v0.14.0](https://github.com/kubedb/replication-mode-detector/releases/tag/v0.14.0)

- [fcb720f2](https://github.com/kubedb/replication-mode-detector/commit/fcb720f2) Prepare for release v0.14.0 (#194)
- [b59867e3](https://github.com/kubedb/replication-mode-detector/commit/b59867e3) Update dependencies (#193)
- [bc287981](https://github.com/kubedb/replication-mode-detector/commit/bc287981) Update dependencies(nats client, mongo-driver) (#192)



