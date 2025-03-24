# KubeDB v2025.3.24 (2025-03-24)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.53.0](https://github.com/kubedb/apimachinery/releases/tag/v0.53.0)

- [1f19088e](https://github.com/kubedb/apimachinery/commit/1f19088e5) Update for release KubeStash@v2025.3.24 (#1437)
- [c3966a55](https://github.com/kubedb/apimachinery/commit/c3966a553) Dont use selector while setting up restoresession reconciler (#1436)
- [b7bdda58](https://github.com/kubedb/apimachinery/commit/b7bdda585) Configure restore session controller name by db kind
- [d15c5892](https://github.com/kubedb/apimachinery/commit/d15c58928) Udate license verifier
- [525f2962](https://github.com/kubedb/apimachinery/commit/525f29629) Generate release notes (#1435)
- [26f19746](https://github.com/kubedb/apimachinery/commit/26f197466) Configure restoresession controller name (#1434)
- [ceb4a0bc](https://github.com/kubedb/apimachinery/commit/ceb4a0bcc) Update deps
- [7b4a7dd0](https://github.com/kubedb/apimachinery/commit/7b4a7dd05) Fix MariaDB Webhook (#1432)
- [12201f9f](https://github.com/kubedb/apimachinery/commit/12201f9fa) Add const for zookeeper-ready  (#1433)
- [749f062a](https://github.com/kubedb/apimachinery/commit/749f062a9) Add postgres version in FerretDBVersion (#1429)
- [c1c97c5d](https://github.com/kubedb/apimachinery/commit/c1c97c5d7) Update deps
- [e7fb1125](https://github.com/kubedb/apimachinery/commit/e7fb1125f) Move & convert oldDB validators to new-webhook signature (#1428)
- [d82a3f17](https://github.com/kubedb/apimachinery/commit/d82a3f17c) Register cassandra autoscaler types
- [4d0febcc](https://github.com/kubedb/apimachinery/commit/4d0febcc5) Rename SecretSource -> SecretStore
- [f80d5dc7](https://github.com/kubedb/apimachinery/commit/f80d5dc74) Move webhooks folder inside pkg
- [5e31d682](https://github.com/kubedb/apimachinery/commit/5e31d6825) update ferretdb autoscaler api (#1427)
- [5d295e37](https://github.com/kubedb/apimachinery/commit/5d295e374) Move & convert opsRequest validator files to new webhook style (#1425)
- [051711da](https://github.com/kubedb/apimachinery/commit/051711da2) Update deps
- [70c28b34](https://github.com/kubedb/apimachinery/commit/70c28b34c) Update autoscaler webhooks (#1424)
- [a9caf6ac](https://github.com/kubedb/apimachinery/commit/a9caf6acf) Update deps
- [999c0b80](https://github.com/kubedb/apimachinery/commit/999c0b803) Update deps
- [ee518661](https://github.com/kubedb/apimachinery/commit/ee5186618) Fix build (#1423)
- [28f8a1d6](https://github.com/kubedb/apimachinery/commit/28f8a1d6d) Add FerretDB replication support (#1420)
- [4fcb10d1](https://github.com/kubedb/apimachinery/commit/4fcb10d1c) Integrate virtual-secret in `authSecret` (#1414)
- [7b3b2d57](https://github.com/kubedb/apimachinery/commit/7b3b2d57a) Remove defaultclient from kafka api group (#1419)
- [3b730ac8](https://github.com/kubedb/apimachinery/commit/3b730ac81) Add Engine-type in Redis-Version to distinguish valkey version (#1410)
- [f5d0d929](https://github.com/kubedb/apimachinery/commit/f5d0d929f) Fix ChangeRequest Status type (#1411)
- [9493bd16](https://github.com/kubedb/apimachinery/commit/9493bd16d) Update schema manager to new webhook style (#1421)
- [dc851d6f](https://github.com/kubedb/apimachinery/commit/dc851d6fb) Increate MSSQL CPU Request (#1412)
- [38bb7a72](https://github.com/kubedb/apimachinery/commit/38bb7a72c) Add Operator Sharding Support (#1415)
- [5db581f5](https://github.com/kubedb/apimachinery/commit/5db581f54) Use k8s 1.32 client libs (#1405)
- [64f26616](https://github.com/kubedb/apimachinery/commit/64f266165) Set securityContext for exporter containers (#1418)
- [8673786a](https://github.com/kubedb/apimachinery/commit/8673786aa) Add IsCluster inside Replication (#1416)
- [d57315cd](https://github.com/kubedb/apimachinery/commit/d57315cdf) Add regex to kubedb object names (#1417)
- [c3871c5d](https://github.com/kubedb/apimachinery/commit/c3871c5de) Test against k8s 1.32 (#1409)
- [5065873e](https://github.com/kubedb/apimachinery/commit/5065873e2) Test against k8s 1.32 (#1407)
- [93b6bea8](https://github.com/kubedb/apimachinery/commit/93b6bea8a) Fix CI (#1408)
- [d685cb86](https://github.com/kubedb/apimachinery/commit/d685cb862) Add gitops apis (#1406)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.8.0](https://github.com/kubedb/db-client-go/releases/tag/v0.8.0)

- [a9aa5a3e](https://github.com/kubedb/db-client-go/commit/a9aa5a3e) Prepare for release v0.8.0 (#169)
- [ca0ff72d](https://github.com/kubedb/db-client-go/commit/ca0ff72d) Prepare for release v0.8.0-rc.1 (#168)
- [2beb4691](https://github.com/kubedb/db-client-go/commit/2beb4691) Prepare for release v0.8.0-rc.0 (#167)
- [214a0339](https://github.com/kubedb/db-client-go/commit/214a0339) Remove decoding of data (#166)
- [0303ed1c](https://github.com/kubedb/db-client-go/commit/0303ed1c) Updates for integrating `Virtual-Secrets` (#165)
- [056c3ddf](https://github.com/kubedb/db-client-go/commit/056c3ddf) Fix TLS Handshake Issue for MySQL 5.7.x (#164)



## [kubedb/kubedb-manifest-plugin](https://github.com/kubedb/kubedb-manifest-plugin)

### [v0.16.0](https://github.com/kubedb/kubedb-manifest-plugin/releases/tag/v0.16.0)

- [e14d1611](https://github.com/kubedb/kubedb-manifest-plugin/commit/e14d1611) Prepare for release v0.16.0 (#92)
- [8dbc92d0](https://github.com/kubedb/kubedb-manifest-plugin/commit/8dbc92d0) Prepare for release v0.16.0-rc.1 (#91)



## [kubedb/mariadb-archiver](https://github.com/kubedb/mariadb-archiver)

### [v0.13.0](https://github.com/kubedb/mariadb-archiver/releases/tag/v0.13.0)

- [e31a2586](https://github.com/kubedb/mariadb-archiver/commit/e31a2586) Prepare for release v0.13.0 (#47)
- [ea393fb4](https://github.com/kubedb/mariadb-archiver/commit/ea393fb4) Prepare for release v0.13.0-rc.1 (#46)
- [a7e37d89](https://github.com/kubedb/mariadb-archiver/commit/a7e37d89) Prepare for release v0.13.0-rc.0 (#45)



## [kubedb/mongodb-csi-snapshotter-plugin](https://github.com/kubedb/mongodb-csi-snapshotter-plugin)

### [v0.14.0](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/releases/tag/v0.14.0)

- [d944f36c](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/d944f36c) Prepare for release v0.14.0 (#49)
- [f23ef219](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/f23ef219) Prepare for release v0.14.0-rc.1 (#48)



## [kubedb/mssql-coordinator](https://github.com/kubedb/mssql-coordinator)

### [v0.8.0](https://github.com/kubedb/mssql-coordinator/releases/tag/v0.8.0)

- [d420a4b3](https://github.com/kubedb/mssql-coordinator/commit/d420a4b3) Prepare for release v0.8.0 (#34)
- [d2e1774a](https://github.com/kubedb/mssql-coordinator/commit/d2e1774a) Prepare for release v0.8.0-rc.1 (#33)
- [cbb75c6a](https://github.com/kubedb/mssql-coordinator/commit/cbb75c6a) Prepare for release v0.8.0-rc.0 (#32)



## [kubedb/mssqlserver-archiver](https://github.com/kubedb/mssqlserver-archiver)

### [v0.7.0](https://github.com/kubedb/mssqlserver-archiver/releases/tag/v0.7.0)




## [kubedb/mysql-coordinator](https://github.com/kubedb/mysql-coordinator)

### [v0.31.0](https://github.com/kubedb/mysql-coordinator/releases/tag/v0.31.0)

- [fecf1748](https://github.com/kubedb/mysql-coordinator/commit/fecf1748) Prepare for release v0.31.0 (#140)
- [d4bc9ecb](https://github.com/kubedb/mysql-coordinator/commit/d4bc9ecb) Prepare for release v0.31.0-rc.1 (#139)
- [8750fb07](https://github.com/kubedb/mysql-coordinator/commit/8750fb07) Prepare for release v0.31.0-rc.0 (#138)
- [026cf350](https://github.com/kubedb/mysql-coordinator/commit/026cf350) Fix TLS Handshake Issue for MySQL 5.7.x (#137)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.31.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.31.0)




## [kubedb/percona-xtradb-coordinator](https://github.com/kubedb/percona-xtradb-coordinator)

### [v0.26.0](https://github.com/kubedb/percona-xtradb-coordinator/releases/tag/v0.26.0)

- [c8c2b7f0](https://github.com/kubedb/percona-xtradb-coordinator/commit/c8c2b7f0) Prepare for release v0.26.0 (#94)
- [20479694](https://github.com/kubedb/percona-xtradb-coordinator/commit/20479694) Prepare for release v0.26.0-rc.1 (#93)



## [kubedb/postgres-archiver](https://github.com/kubedb/postgres-archiver)

### [v0.14.0](https://github.com/kubedb/postgres-archiver/releases/tag/v0.14.0)

- [50b71c6c](https://github.com/kubedb/postgres-archiver/commit/50b71c6c) Prepare for release v0.14.0 (#59)
- [96f5fde6](https://github.com/kubedb/postgres-archiver/commit/96f5fde6) Prepare for release v0.14.0-rc.1 (#58)



## [kubedb/postgres-csi-snapshotter-plugin](https://github.com/kubedb/postgres-csi-snapshotter-plugin)

### [v0.14.0](https://github.com/kubedb/postgres-csi-snapshotter-plugin/releases/tag/v0.14.0)

- [3810d222](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/3810d222) Prepare for release v0.14.0 (#55)
- [c910645a](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/c910645a) Prepare for release v0.14.0-rc.1 (#54)



## [kubedb/xtrabackup-restic-plugin](https://github.com/kubedb/xtrabackup-restic-plugin)

### [v0.2.0](https://github.com/kubedb/xtrabackup-restic-plugin/releases/tag/v0.2.0)




