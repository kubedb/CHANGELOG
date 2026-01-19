# KubeDB v2026.1.19 (2026-01-19)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.60.0](https://github.com/kubedb/apimachinery/releases/tag/v0.60.0)

- [c843a2f3](https://github.com/kubedb/apimachinery/commit/c843a2f36) Update for release KubeStash@v2026.1.19 (#1570)
- [9f97d1bb](https://github.com/kubedb/apimachinery/commit/9f97d1bb1) Add/Update webhook validation for all dbs' ops requests (#1569)
- [ef9045d6](https://github.com/kubedb/apimachinery/commit/ef9045d61) Update redis, pgpool api and memcached ops api (#1568)
- [eae49b09](https://github.com/kubedb/apimachinery/commit/eae49b096) Add Qdrant TLS Support (#1559)
- [3f91ae3f](https://github.com/kubedb/apimachinery/commit/3f91ae3fe) Improve and generalize configure-reconfigure process for all dbs (#1558)
- [b9b80eb8](https://github.com/kubedb/apimachinery/commit/b9b80eb8d) Update for release KubeStash@v2026.1.8-rc.0 (#1566)
- [5b6cda2f](https://github.com/kubedb/apimachinery/commit/5b6cda2f2) Resume stash backupconfigs currently (#1565)
- [0a4e17cd](https://github.com/kubedb/apimachinery/commit/0a4e17cdd) Review Postgres custom config api (#1556)
- [0a605892](https://github.com/kubedb/apimachinery/commit/0a605892f) Implement common method for merging logic (#1563)
- [f12630f5](https://github.com/kubedb/apimachinery/commit/f12630f5c) Add shard config scheme for cached client (#1555)
- [89c8cc89](https://github.com/kubedb/apimachinery/commit/89c8cc899) Correctly set the serviceMonitor scheme (#1562)
- [3fb97b25](https://github.com/kubedb/apimachinery/commit/3fb97b259) Use k8s 1.34 client go libs (#1560)
- [eb03debc](https://github.com/kubedb/apimachinery/commit/eb03debc7) Add DatabaseInfo api (#1557)
- [72d44c38](https://github.com/kubedb/apimachinery/commit/72d44c386) Update deps
- [d30d72e0](https://github.com/kubedb/apimachinery/commit/d30d72e0f) Test against k8s 1.35 (#1554)
- [da3e069f](https://github.com/kubedb/apimachinery/commit/da3e069f8) Update deps
- [7086a4bd](https://github.com/kubedb/apimachinery/commit/7086a4bd8) Add "EndOfLife" field in catalogs (#1553)
- [5cfded61](https://github.com/kubedb/apimachinery/commit/5cfded61a) Update deps
- [bd999704](https://github.com/kubedb/apimachinery/commit/bd9997041) Update deps
- [fac813c7](https://github.com/kubedb/apimachinery/commit/fac813c78) Update deps
- [e58fe916](https://github.com/kubedb/apimachinery/commit/e58fe916a) Update license libraries
- [0562e8d1](https://github.com/kubedb/apimachinery/commit/0562e8d15) Use golangci-lint 2.x (#1549)
- [3d10db60](https://github.com/kubedb/apimachinery/commit/3d10db600) Implement upgradability helpers (#1536)
- [9131dc31](https://github.com/kubedb/apimachinery/commit/9131dc317) Add milvus apis (#1533)
- [7d56b3e6](https://github.com/kubedb/apimachinery/commit/7d56b3e6c) Virtual secret for pgbouncer pgpool redis (#1516)
- [e1143b59](https://github.com/kubedb/apimachinery/commit/e1143b591) Add MaxRetries api (#1547)
- [b8b8a903](https://github.com/kubedb/apimachinery/commit/b8b8a9030) Fix webhook: postgres volume exp ops, memcached auth secret spec (#1548)
- [56ba059d](https://github.com/kubedb/apimachinery/commit/56ba059d8) Add oracle tls api (#1545)
- [0c8e327b](https://github.com/kubedb/apimachinery/commit/0c8e327b1) Allow Force Failover with data loss | add tuning api (#1542)
- [e34d1088](https://github.com/kubedb/apimachinery/commit/e34d1088a) Add Weaviate APIs (#1528)
- [8059bb8b](https://github.com/kubedb/apimachinery/commit/8059bb8b7) Add DB2 APIs (#1530)
- [285acd8b](https://github.com/kubedb/apimachinery/commit/285acd8bd) Add Neo4j API (#1544)
- [7e98c3f0](https://github.com/kubedb/apimachinery/commit/7e98c3f00) Update skipper and webhook for config merger (#1535)
- [e3c8ce90](https://github.com/kubedb/apimachinery/commit/e3c8ce90f) Add Hanadb (#1527)
- [f56bbc3a](https://github.com/kubedb/apimachinery/commit/f56bbc3a4) Fix MySQL reconfigure apply config (#1534)
- [2ed241d2](https://github.com/kubedb/apimachinery/commit/2ed241d26) Add hazelcast binding implementation (#1540)
- [2bbafe54](https://github.com/kubedb/apimachinery/commit/2bbafe54f) Add Qdrant (#1524)
- [4de23d6d](https://github.com/kubedb/apimachinery/commit/4de23d6d3) Update vulnerable deps (#1541)
- [832e8ff4](https://github.com/kubedb/apimachinery/commit/832e8ff48) Move lib pkg from ops-manager (#1532)
- [bf32e8fc](https://github.com/kubedb/apimachinery/commit/bf32e8fca) Remove redundant print column `Type` in DB CRs.  (#1531)
- [bbc01408](https://github.com/kubedb/apimachinery/commit/bbc014087) make gen fmt (#1529)
- [9ae5deaa](https://github.com/kubedb/apimachinery/commit/9ae5deaaa) Update deps



## [kubedb/cassandra](https://github.com/kubedb/cassandra)

### [v0.13.0](https://github.com/kubedb/cassandra/releases/tag/v0.13.0)

- [b3cd8596](https://github.com/kubedb/cassandra/commit/b3cd8596) Prepare for release v0.13.0 (#58)
- [70d0a9d0](https://github.com/kubedb/cassandra/commit/70d0a9d0) Improve and generalize configure-reconfigure process (#57)
- [04f224cf](https://github.com/kubedb/cassandra/commit/04f224cf) Prepare for release v0.13.0-rc.1 (#56)
- [8bd54c7a](https://github.com/kubedb/cassandra/commit/8bd54c7a) Use k8s 1.34 client libs (#55)
- [00e147f5](https://github.com/kubedb/cassandra/commit/00e147f5) Test against k8s 1.35 (#54)
- [78213d47](https://github.com/kubedb/cassandra/commit/78213d47) Prepare for release v0.13.0-rc.0 (#53)
- [8f8458f1](https://github.com/kubedb/cassandra/commit/8f8458f1) Fix multiple restart issue by introducing parallelismController (#52)
- [5563cf24](https://github.com/kubedb/cassandra/commit/5563cf24) Moved ops code to dev repo (#51)



## [kubedb/cassandra-medusa-plugin](https://github.com/kubedb/cassandra-medusa-plugin)

### [v0.7.0](https://github.com/kubedb/cassandra-medusa-plugin/releases/tag/v0.7.0)

- [52d43201](https://github.com/kubedb/cassandra-medusa-plugin/commit/52d43201) Prepare for release v0.7.0 (#21)
- [804c9f62](https://github.com/kubedb/cassandra-medusa-plugin/commit/804c9f62) Prepare for release v0.7.0-rc.1 (#19)
- [7dfbd231](https://github.com/kubedb/cassandra-medusa-plugin/commit/7dfbd231) Use k8s 1.34 client libs (#18)
- [7db29d99](https://github.com/kubedb/cassandra-medusa-plugin/commit/7db29d99) Fix makefile indentation (#17)
- [0ca8af6d](https://github.com/kubedb/cassandra-medusa-plugin/commit/0ca8af6d) Publish Image for Redhat software certification (#16)
- [dd6cbb12](https://github.com/kubedb/cassandra-medusa-plugin/commit/dd6cbb12) Prepare for release v0.7.0-rc.0 (#15)
- [b2132d1a](https://github.com/kubedb/cassandra-medusa-plugin/commit/b2132d1a) update deps (#14)



## [kubedb/cli](https://github.com/kubedb/cli)

### [v0.60.0](https://github.com/kubedb/cli/releases/tag/v0.60.0)

- [d0b02fca](https://github.com/kubedb/cli/commit/d0b02fca7) Prepare for release v0.60.0 (#810)
- [691493f2](https://github.com/kubedb/cli/commit/691493f27) Prepare for release v0.60.0-rc.1 (#809)
- [f3e2ac0a](https://github.com/kubedb/cli/commit/f3e2ac0aa) Use k8s 1.34 client libs (#808)
- [fe2da356](https://github.com/kubedb/cli/commit/fe2da3569) Prepare for release v0.60.0-rc.0 (#807)
- [3fc4051c](https://github.com/kubedb/cli/commit/3fc4051ca) Add gitops CLI (#804)
- [8749544b](https://github.com/kubedb/cli/commit/8749544bc) Update Lint (#806)
- [41a390a6](https://github.com/kubedb/cli/commit/41a390a60) Make the debug cli common (#805)



## [kubedb/clickhouse](https://github.com/kubedb/clickhouse)

### [v0.15.0](https://github.com/kubedb/clickhouse/releases/tag/v0.15.0)

- [36b98fc2](https://github.com/kubedb/clickhouse/commit/36b98fc2) Prepare for release v0.15.0 (#80)
- [41fe5c21](https://github.com/kubedb/clickhouse/commit/41fe5c21) Update Configure reconfigure process (#79)
- [9c394a8f](https://github.com/kubedb/clickhouse/commit/9c394a8f) Prepare for release v0.15.0-rc.1 (#78)
- [e482f9ab](https://github.com/kubedb/clickhouse/commit/e482f9ab) Use k8s 1.34 client libs (#77)
- [918b772c](https://github.com/kubedb/clickhouse/commit/918b772c) Test against k8s 1.35 (#75)
- [49c77055](https://github.com/kubedb/clickhouse/commit/49c77055) Prepare for release v0.15.0-rc.0 (#74)
- [876fb0be](https://github.com/kubedb/clickhouse/commit/876fb0be) Fix go version (#73)
- [2bcf4461](https://github.com/kubedb/clickhouse/commit/2bcf4461) Fix multiple restart issue by introducing parallelismController (#72)
- [d3ebb6df](https://github.com/kubedb/clickhouse/commit/d3ebb6df) Move in Ops-manager code to ClickHouse (#71)



## [kubedb/crd-manager](https://github.com/kubedb/crd-manager)

### [v0.15.0](https://github.com/kubedb/crd-manager/releases/tag/v0.15.0)

- [e9b0cd26](https://github.com/kubedb/crd-manager/commit/e9b0cd26) Prepare for release v0.15.0 (#107)
- [f16d4769](https://github.com/kubedb/crd-manager/commit/f16d4769) Add crd for cassandra, hazelcast, oracle (#106)
- [09f8c382](https://github.com/kubedb/crd-manager/commit/09f8c382) Prepare for release v0.15.0-rc.1 (#105)
- [02225ed0](https://github.com/kubedb/crd-manager/commit/02225ed0) Use k8s 1.34 client libs (#104)
- [8565968f](https://github.com/kubedb/crd-manager/commit/8565968f) Fix makefile indentation (#103)
- [370e88f2](https://github.com/kubedb/crd-manager/commit/370e88f2) Publish Image for Redhat software certification (#102)
- [d4dd9b8c](https://github.com/kubedb/crd-manager/commit/d4dd9b8c) Prepare for release v0.15.0-rc.0 (#101)
- [8347e307](https://github.com/kubedb/crd-manager/commit/8347e307) replace go1.25.5 to go1.25 (#100)
- [34895de8](https://github.com/kubedb/crd-manager/commit/34895de8) Add neo4j
- [c89068f3](https://github.com/kubedb/crd-manager/commit/c89068f3) HanaDB (#90)
- [1245ee00](https://github.com/kubedb/crd-manager/commit/1245ee00) Add milvus crd-manager (#94)
- [da01d86e](https://github.com/kubedb/crd-manager/commit/da01d86e) Add Weaviate Crds (#97)
- [521fbd57](https://github.com/kubedb/crd-manager/commit/521fbd57) Add Db2 Crds (#96)
- [1cf9a782](https://github.com/kubedb/crd-manager/commit/1cf9a782) Add Neo4j Crds (#98)
- [80e2bc36](https://github.com/kubedb/crd-manager/commit/80e2bc36) Add Qdrant CRD (#92)



## [kubedb/dashboard-restic-plugin](https://github.com/kubedb/dashboard-restic-plugin)

### [v0.18.0](https://github.com/kubedb/dashboard-restic-plugin/releases/tag/v0.18.0)

- [c6ab8f5](https://github.com/kubedb/dashboard-restic-plugin/commit/c6ab8f5) Prepare for release v0.18.0 (#58)
- [9ca336a](https://github.com/kubedb/dashboard-restic-plugin/commit/9ca336a) Use forked kubestash/restic (#57)
- [4825ed5](https://github.com/kubedb/dashboard-restic-plugin/commit/4825ed5) Use forked kubestash/restic (#56)
- [334a35e](https://github.com/kubedb/dashboard-restic-plugin/commit/334a35e) Prepare for release v0.18.0-rc.1 (#55)
- [51ae5d7](https://github.com/kubedb/dashboard-restic-plugin/commit/51ae5d7) Use k8s 1.34 client libs (#54)
- [901091a](https://github.com/kubedb/dashboard-restic-plugin/commit/901091a) Fix makefile indentation (#53)
- [a5bafae](https://github.com/kubedb/dashboard-restic-plugin/commit/a5bafae) Publish Image for Redhat software certification (#52)
- [c970a47](https://github.com/kubedb/dashboard-restic-plugin/commit/c970a47) Prepare for release v0.18.0-rc.0 (#51)
- [b42b5f6](https://github.com/kubedb/dashboard-restic-plugin/commit/b42b5f6) change to 1.25 (#50)
- [c1811e1](https://github.com/kubedb/dashboard-restic-plugin/commit/c1811e1) Update Dependency (#49)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.15.0](https://github.com/kubedb/db-client-go/releases/tag/v0.15.0)

- [2ecc2b55](https://github.com/kubedb/db-client-go/commit/2ecc2b55) Prepare for release v0.15.0 (#217)
- [9854141c](https://github.com/kubedb/db-client-go/commit/9854141c) fix opensearch-v3 health check issues (#216)
- [d08174b5](https://github.com/kubedb/db-client-go/commit/d08174b5) Add Qdrant TLS Support (#212)
- [3f74e4df](https://github.com/kubedb/db-client-go/commit/3f74e4df) Prepare for release v0.15.0-rc.1 (#215)
- [d7814284](https://github.com/kubedb/db-client-go/commit/d7814284) Update vulnerable deps (#214)
- [cf25883f](https://github.com/kubedb/db-client-go/commit/cf25883f) Use k8s 1.34 client libs (#213)
- [17120b90](https://github.com/kubedb/db-client-go/commit/17120b90) Update deps
- [238d08e2](https://github.com/kubedb/db-client-go/commit/238d08e2) Prepare for release v0.15.0-rc.0 (#209)
- [3789532d](https://github.com/kubedb/db-client-go/commit/3789532d) Fix Go version (#208)
- [eaca6fc1](https://github.com/kubedb/db-client-go/commit/eaca6fc1) Add Weaviate Client Go (#202)
- [1826245f](https://github.com/kubedb/db-client-go/commit/1826245f) Add hanadb client-go (#201)
- [fbf24826](https://github.com/kubedb/db-client-go/commit/fbf24826) Add milvus db-client-go (#198)
- [2e876291](https://github.com/kubedb/db-client-go/commit/2e876291) Update go.mod file
- [e3d3ecca](https://github.com/kubedb/db-client-go/commit/e3d3ecca) Use golangci-lint 2.x (#207)
- [5beb8789](https://github.com/kubedb/db-client-go/commit/5beb8789) Add Oracle tls support (#205)
- [0daf0012](https://github.com/kubedb/db-client-go/commit/0daf0012) Add Neo4j Client (#204)
- [8f852044](https://github.com/kubedb/db-client-go/commit/8f852044) Add db2 client go (#206)
- [0b613041](https://github.com/kubedb/db-client-go/commit/0b613041) Add Qdrant (#197)
- [f77e6314](https://github.com/kubedb/db-client-go/commit/f77e6314) Add Virtual Secret Pgbouncer Pgpool Redis Valkey (#199)
- [b824c01d](https://github.com/kubedb/db-client-go/commit/b824c01d) move go_es file to db-client (#200)



## [kubedb/db2](https://github.com/kubedb/db2)

### [v0.1.0](https://github.com/kubedb/db2/releases/tag/v0.1.0)

- [aafe21ff](https://github.com/kubedb/db2/commit/aafe21ff) Prepare for release v0.1.0 (#8)
- [e64f6a2f](https://github.com/kubedb/db2/commit/e64f6a2f) Prepare for release v0.1.0-rc.1 (#7)
- [46dfb4fb](https://github.com/kubedb/db2/commit/46dfb4fb) Use k8s 1.34 client libs (#5)
- [c61ee118](https://github.com/kubedb/db2/commit/c61ee118) Prepare for release v0.1.0-rc.0 (#3)
- [e5dd65e7](https://github.com/kubedb/db2/commit/e5dd65e7) Implement db2 controller
- [cbe78ad6](https://github.com/kubedb/db2/commit/cbe78ad6) Add vendor



## [kubedb/druid](https://github.com/kubedb/druid)

### [v0.15.0](https://github.com/kubedb/druid/releases/tag/v0.15.0)

- [34a18a5a](https://github.com/kubedb/druid/commit/34a18a5a) Prepare for release v0.15.0 (#111)
- [6236221f](https://github.com/kubedb/druid/commit/6236221f) Reconfigure redesign (#110)
- [08fa3cc6](https://github.com/kubedb/druid/commit/08fa3cc6) Prepare for release v0.15.0-rc.1 (#109)
- [d0d33608](https://github.com/kubedb/druid/commit/d0d33608) Use k8s 1.34 client libs (#108)
- [d9ada989](https://github.com/kubedb/druid/commit/d9ada989) Test against k8s 1.35 (#106)
- [d1e1b108](https://github.com/kubedb/druid/commit/d1e1b108) Prepare for release v0.15.0-rc.0 (#105)
- [5632cb2f](https://github.com/kubedb/druid/commit/5632cb2f) Fix multiple restart issue by introducing parallelismController (#104)
- [5f237f3c](https://github.com/kubedb/druid/commit/5f237f3c) fixed some mistake (#103)
- [23ad9f70](https://github.com/kubedb/druid/commit/23ad9f70) move ops code to db repo (#102)



## [kubedb/elasticsearch](https://github.com/kubedb/elasticsearch)

### [v0.60.0](https://github.com/kubedb/elasticsearch/releases/tag/v0.60.0)

- [bf671dfe](https://github.com/kubedb/elasticsearch/commit/bf671dfe6) Prepare for release v0.60.0 (#786)
- [3d9d54ad](https://github.com/kubedb/elasticsearch/commit/3d9d54ad0) Fix Opensearch health check issue for v3.0 (#785)
- [10542dbb](https://github.com/kubedb/elasticsearch/commit/10542dbb0) Improve and generalize configure-reconfigure process (#782)
- [1c7a0371](https://github.com/kubedb/elasticsearch/commit/1c7a0371f) Prepare for release v0.60.0-rc.1 (#784)
- [119a44ab](https://github.com/kubedb/elasticsearch/commit/119a44abc) Use k8s 1.34 client libs (#783)
- [d686d92a](https://github.com/kubedb/elasticsearch/commit/d686d92a3) Test against k8s 1.35 (#781)
- [f75c70d0](https://github.com/kubedb/elasticsearch/commit/f75c70d09) Prepare for release v0.60.0-rc.0 (#780)
- [da290110](https://github.com/kubedb/elasticsearch/commit/da2901102) move go_es file to db-client-go (#779)
- [1de4f810](https://github.com/kubedb/elasticsearch/commit/1de4f8105) move ops code to db repo (#778)



## [kubedb/elasticsearch-restic-plugin](https://github.com/kubedb/elasticsearch-restic-plugin)

### [v0.23.0](https://github.com/kubedb/elasticsearch-restic-plugin/releases/tag/v0.23.0)

- [a025d501](https://github.com/kubedb/elasticsearch-restic-plugin/commit/a025d501) Prepare for release v0.23.0 (#81)
- [63215a12](https://github.com/kubedb/elasticsearch-restic-plugin/commit/63215a12) Use forked kubestash/restic (#80)
- [085362c3](https://github.com/kubedb/elasticsearch-restic-plugin/commit/085362c3) Use forked kubestash/restic (#79)
- [94598fe3](https://github.com/kubedb/elasticsearch-restic-plugin/commit/94598fe3) Prepare for release v0.23.0-rc.1 (#78)
- [fb7521bd](https://github.com/kubedb/elasticsearch-restic-plugin/commit/fb7521bd) Fix makefile indentation (#77)
- [ce5dfcea](https://github.com/kubedb/elasticsearch-restic-plugin/commit/ce5dfcea) Publish Image for Redhat software certification (#76)
- [38775457](https://github.com/kubedb/elasticsearch-restic-plugin/commit/38775457) Use nodejs:22
- [4f368d25](https://github.com/kubedb/elasticsearch-restic-plugin/commit/4f368d25) Fix build rule
- [da511bd8](https://github.com/kubedb/elasticsearch-restic-plugin/commit/da511bd8) Prepare for release v0.23.0-rc.0 (#75)
- [f8bc69f1](https://github.com/kubedb/elasticsearch-restic-plugin/commit/f8bc69f1) change to 1.25 (#74)
- [e5a1b21d](https://github.com/kubedb/elasticsearch-restic-plugin/commit/e5a1b21d) update-deps (#73)



## [kubedb/ferretdb](https://github.com/kubedb/ferretdb)

### [v0.15.0](https://github.com/kubedb/ferretdb/releases/tag/v0.15.0)

- [dba7aed1](https://github.com/kubedb/ferretdb/commit/dba7aed1) Prepare for release v0.15.0 (#98)
- [b7b021cb](https://github.com/kubedb/ferretdb/commit/b7b021cb) Update OpsReq Type (#97)
- [5ef0a4a1](https://github.com/kubedb/ferretdb/commit/5ef0a4a1) Prepare for release v0.15.0-rc.1 (#96)
- [8e07c378](https://github.com/kubedb/ferretdb/commit/8e07c378) Use k8s 1.34 client libs (#95)
- [8e5d5e72](https://github.com/kubedb/ferretdb/commit/8e5d5e72) Test against k8s 1.35 (#94)
- [7b572633](https://github.com/kubedb/ferretdb/commit/7b572633) Prepare for release v0.15.0-rc.0 (#93)
- [b05a9345](https://github.com/kubedb/ferretdb/commit/b05a9345) Fix go version (#92)
- [e5d1ee2d](https://github.com/kubedb/ferretdb/commit/e5d1ee2d) Fix multiple restart issue by introducing parallelismController (#91)
- [719326aa](https://github.com/kubedb/ferretdb/commit/719326aa) Move in FerretDb Ops Manager Code (#90)
- [6662b891](https://github.com/kubedb/ferretdb/commit/6662b891) Test against k8s 1.34 (#89)
- [3c73ec67](https://github.com/kubedb/ferretdb/commit/3c73ec67) No need to check backend's owner ref



## [kubedb/gitops](https://github.com/kubedb/gitops)

### [v0.8.0](https://github.com/kubedb/gitops/releases/tag/v0.8.0)

- [5948210d](https://github.com/kubedb/gitops/commit/5948210d) Prepare for release v0.8.0 (#37)
- [4dae1f47](https://github.com/kubedb/gitops/commit/4dae1f47) Update Configuration Changes (#36)
- [bd6e94c4](https://github.com/kubedb/gitops/commit/bd6e94c4) Prepare for release v0.8.0-rc.1 (#35)
- [2b260a9d](https://github.com/kubedb/gitops/commit/2b260a9d) Use k8s 1.34 client libs (#34)
- [119edc0b](https://github.com/kubedb/gitops/commit/119edc0b) Fix makefile indentation (#33)
- [5be586ab](https://github.com/kubedb/gitops/commit/5be586ab) Publish Image for Redhat software certification (#32)
- [2e506be8](https://github.com/kubedb/gitops/commit/2e506be8) Prepare for release v0.8.0-rc.0 (#31)
- [9de37946](https://github.com/kubedb/gitops/commit/9de37946) Fix vertical scaling ops creation for storage resouce changes (#30)



## [kubedb/hanadb](https://github.com/kubedb/hanadb)

### [v0.1.0](https://github.com/kubedb/hanadb/releases/tag/v0.1.0)

- [d29c0289](https://github.com/kubedb/hanadb/commit/d29c0289) Prepare for release v0.1.0 (#11)
- [ebaf0578](https://github.com/kubedb/hanadb/commit/ebaf0578) Prepare for release v0.1.0-rc.1 (#8)
- [c80e6397](https://github.com/kubedb/hanadb/commit/c80e6397) Use k8s 1.34 client libs (#7)
- [3d484cef](https://github.com/kubedb/hanadb/commit/3d484cef) Test against k8s 1.35 (#6)
- [3fc76f7e](https://github.com/kubedb/hanadb/commit/3fc76f7e) Prepare for release v0.1.0-rc.0 (#5)
- [67f88948](https://github.com/kubedb/hanadb/commit/67f88948) Modify go.mod (#4)
- [c440319c](https://github.com/kubedb/hanadb/commit/c440319c) Modify Go version (#3)
- [aa961389](https://github.com/kubedb/hanadb/commit/aa961389) Test against k8s 1.34 (#2)
- [a5a5049f](https://github.com/kubedb/hanadb/commit/a5a5049f) Add HanaDB provisioner (#1)



## [kubedb/hazelcast](https://github.com/kubedb/hazelcast)

### [v0.6.0](https://github.com/kubedb/hazelcast/releases/tag/v0.6.0)

- [03cc9a0b](https://github.com/kubedb/hazelcast/commit/03cc9a0b) Prepare for release v0.6.0 (#24)
- [9dc7cbac](https://github.com/kubedb/hazelcast/commit/9dc7cbac)  Improve and generalize configure-reconfigure process (#23)
- [0257c68a](https://github.com/kubedb/hazelcast/commit/0257c68a) Prepare for release v0.6.0-rc.1 (#22)
- [62dca5f2](https://github.com/kubedb/hazelcast/commit/62dca5f2) Use k8s 1.34 client libs (#21)
- [d08bf4d9](https://github.com/kubedb/hazelcast/commit/d08bf4d9) Test against k8s 1.35 (#19)
- [37277ce1](https://github.com/kubedb/hazelcast/commit/37277ce1) Prepare for release v0.6.0-rc.0 (#18)
- [dbfe579c](https://github.com/kubedb/hazelcast/commit/dbfe579c) Fix multiple restart issue by introducing parallelismController (#17)
- [da33d710](https://github.com/kubedb/hazelcast/commit/da33d710) move ops code to db repo (#16)



## [kubedb/ignite](https://github.com/kubedb/ignite)

### [v0.7.0](https://github.com/kubedb/ignite/releases/tag/v0.7.0)

- [f648ea48](https://github.com/kubedb/ignite/commit/f648ea48) Prepare for release v0.7.0 (#33)
- [50699ff3](https://github.com/kubedb/ignite/commit/50699ff3) Re-design Configuration process (#32)
- [b9b125a9](https://github.com/kubedb/ignite/commit/b9b125a9) Prepare for release v0.7.0-rc.1 (#31)
- [70ba3420](https://github.com/kubedb/ignite/commit/70ba3420) Use k8s 1.34 client libs (#30)
- [e361b1c0](https://github.com/kubedb/ignite/commit/e361b1c0) Test against k8s 1.35 (#28)
- [35277e58](https://github.com/kubedb/ignite/commit/35277e58) Prepare for release v0.7.0-rc.0 (#27)
- [c642d15e](https://github.com/kubedb/ignite/commit/c642d15e) Fix multiple restart issue by introducing parallelismController (#26)
- [371c83df](https://github.com/kubedb/ignite/commit/371c83df) Move ops to db repo (#24)



## [kubedb/kafka](https://github.com/kubedb/kafka)

### [v0.31.0](https://github.com/kubedb/kafka/releases/tag/v0.31.0)

- [3ccdb0fd](https://github.com/kubedb/kafka/commit/3ccdb0fd) Prepare for release v0.31.0 (#173)
- [8806da50](https://github.com/kubedb/kafka/commit/8806da50) Update Reconfigure/Configure (#172)
- [50dda47a](https://github.com/kubedb/kafka/commit/50dda47a) Prepare for release v0.31.0-rc.1 (#171)
- [6794c280](https://github.com/kubedb/kafka/commit/6794c280) Use k8s 1.34 client libs (#170)
- [46f4f915](https://github.com/kubedb/kafka/commit/46f4f915) Test against k8s 1.35 (#168)
- [1003c37f](https://github.com/kubedb/kafka/commit/1003c37f) Prepare for release v0.31.0-rc.0 (#167)
- [e270d3e6](https://github.com/kubedb/kafka/commit/e270d3e6) Fix multiple restart issue by introducing parallelismController (#166)
- [3f7bf918](https://github.com/kubedb/kafka/commit/3f7bf918) Move ops-manager code to base repo (#165)



## [kubedb/kibana](https://github.com/kubedb/kibana)

### [v0.36.0](https://github.com/kubedb/kibana/releases/tag/v0.36.0)

- [c454080c](https://github.com/kubedb/kibana/commit/c454080c) Prepare for release v0.36.0 (#167)
- [5a5a15d1](https://github.com/kubedb/kibana/commit/5a5a15d1) Prepare for release v0.36.0-rc.1 (#166)
- [0d968837](https://github.com/kubedb/kibana/commit/0d968837) Use k8s 1.34 client libs (#165)
- [ebd87bba](https://github.com/kubedb/kibana/commit/ebd87bba) Fix makefile indentation (#164)
- [64a99c80](https://github.com/kubedb/kibana/commit/64a99c80) Publish Image for Redhat software certification (#163)
- [f3dea03e](https://github.com/kubedb/kibana/commit/f3dea03e) Update deps
- [85873246](https://github.com/kubedb/kibana/commit/85873246) Build ubi image (#162)
- [c8e38f13](https://github.com/kubedb/kibana/commit/c8e38f13) Use golangci-lint 2.x
- [92ca7ab3](https://github.com/kubedb/kibana/commit/92ca7ab3) Prepare for release v0.36.0-rc.0 (#161)
- [529d7301](https://github.com/kubedb/kibana/commit/529d7301) update deps (#160)



## [kubedb/kubedb-manifest-plugin](https://github.com/kubedb/kubedb-manifest-plugin)

### [v0.23.0](https://github.com/kubedb/kubedb-manifest-plugin/releases/tag/v0.23.0)

- [39aabbc2](https://github.com/kubedb/kubedb-manifest-plugin/commit/39aabbc2) Prepare for release v0.23.0 (#113)
- [6ab7dfbc](https://github.com/kubedb/kubedb-manifest-plugin/commit/6ab7dfbc) Use forked kubestash/restic (#112)
- [839e93d7](https://github.com/kubedb/kubedb-manifest-plugin/commit/839e93d7) Use forked kubestash/restic (#111)
- [4b8b2ed0](https://github.com/kubedb/kubedb-manifest-plugin/commit/4b8b2ed0) Prepare for release v0.23.0-rc.1 (#110)
- [f062b2b2](https://github.com/kubedb/kubedb-manifest-plugin/commit/f062b2b2) Use k8s 1.34 client libs (#109)
- [23a4536c](https://github.com/kubedb/kubedb-manifest-plugin/commit/23a4536c) Fix makefile indentation (#108)
- [0b1e9561](https://github.com/kubedb/kubedb-manifest-plugin/commit/0b1e9561) Publish Image for Redhat software certification (#107)
- [1a10c291](https://github.com/kubedb/kubedb-manifest-plugin/commit/1a10c291) Prepare for release v0.23.0-rc.0 (#106)
- [75d723c8](https://github.com/kubedb/kubedb-manifest-plugin/commit/75d723c8) update-dep (#105)



## [kubedb/kubedb-verifier](https://github.com/kubedb/kubedb-verifier)

### [v0.11.0](https://github.com/kubedb/kubedb-verifier/releases/tag/v0.11.0)

- [fc8b0048](https://github.com/kubedb/kubedb-verifier/commit/fc8b0048) Prepare for release v0.11.0 (#36)
- [04634147](https://github.com/kubedb/kubedb-verifier/commit/04634147) Prepare for release v0.11.0-rc.1 (#34)
- [b99b0af5](https://github.com/kubedb/kubedb-verifier/commit/b99b0af5) Update vulnerable deps (#33)
- [0ed52eed](https://github.com/kubedb/kubedb-verifier/commit/0ed52eed) Use k8s 1.34 client libs (#32)
- [acdfea3d](https://github.com/kubedb/kubedb-verifier/commit/acdfea3d) Fix makefile indentation (#31)
- [562ab0a9](https://github.com/kubedb/kubedb-verifier/commit/562ab0a9) Publish Image for Redhat software certification (#29)
- [616c0b5d](https://github.com/kubedb/kubedb-verifier/commit/616c0b5d) Prepare for release v0.11.0-rc.0 (#28)
- [78b37027](https://github.com/kubedb/kubedb-verifier/commit/78b37027) Use golangci-lint 2.x (#27)



## [kubedb/mariadb](https://github.com/kubedb/mariadb)

### [v0.44.0](https://github.com/kubedb/mariadb/releases/tag/v0.44.0)

- [b5e215a5](https://github.com/kubedb/mariadb/commit/b5e215a53) Prepare for release v0.44.0 (#366)
- [2b103c38](https://github.com/kubedb/mariadb/commit/2b103c386) Use Exporter Version v0.18.0 (#365)
- [0cfc4998](https://github.com/kubedb/mariadb/commit/0cfc49986) Improve and generalize configure-reconfigure (#363)
- [5573297f](https://github.com/kubedb/mariadb/commit/5573297fb) Prepare for release v0.44.0-rc.1 (#364)
- [681968b1](https://github.com/kubedb/mariadb/commit/681968b1c) Use k8s 1.34 client libs (#362)
- [f3396108](https://github.com/kubedb/mariadb/commit/f33961085) Test against k8s 1.35 (#361)
- [ea4d4a69](https://github.com/kubedb/mariadb/commit/ea4d4a69a) Prepare for release v0.44.0-rc.0 (#358)
- [d9257a6e](https://github.com/kubedb/mariadb/commit/d9257a6ea) Change Makefile GO Version (#357)
- [4f419cbe](https://github.com/kubedb/mariadb/commit/4f419cbec) Add golangci (#356)
- [96a12452](https://github.com/kubedb/mariadb/commit/96a12452c) Fix multiple restart issue by introducing parallelismController (#355)
- [c1fccdd7](https://github.com/kubedb/mariadb/commit/c1fccdd74) Fi Archiver Version Compatibility (#354)
- [b95f58e6](https://github.com/kubedb/mariadb/commit/b95f58e69) move ops code to db repo (#353)



## [kubedb/mariadb-archiver](https://github.com/kubedb/mariadb-archiver)

### [v0.20.0](https://github.com/kubedb/mariadb-archiver/releases/tag/v0.20.0)

- [40710dc0](https://github.com/kubedb/mariadb-archiver/commit/40710dc0) Prepare for release v0.20.0 (#72)
- [ce027593](https://github.com/kubedb/mariadb-archiver/commit/ce027593) Fix redhat catalog submission (#70)
- [e9eaec6e](https://github.com/kubedb/mariadb-archiver/commit/e9eaec6e) Prepare for release v0.20.0-rc.1 (#69)
- [72598a18](https://github.com/kubedb/mariadb-archiver/commit/72598a18) Use k8s 1.34 client libs (#68)
- [4704b4ad](https://github.com/kubedb/mariadb-archiver/commit/4704b4ad) Fix makefile indentation (#67)
- [1e935bfa](https://github.com/kubedb/mariadb-archiver/commit/1e935bfa) Publish Image for Redhat software certification (#66)
- [046fee71](https://github.com/kubedb/mariadb-archiver/commit/046fee71) Fix build rule
- [5a4450ec](https://github.com/kubedb/mariadb-archiver/commit/5a4450ec) Prepare for release v0.20.0-rc.0 (#64)
- [51b288e1](https://github.com/kubedb/mariadb-archiver/commit/51b288e1) Change Makefile GO Version (#63)
- [12dd22cc](https://github.com/kubedb/mariadb-archiver/commit/12dd22cc) Add golangci (#62)
- [4364d82b](https://github.com/kubedb/mariadb-archiver/commit/4364d82b) Build and push ubi image (#61)
- [cd57feb0](https://github.com/kubedb/mariadb-archiver/commit/cd57feb0) Fix none mode slave not running issue (#60)



## [kubedb/mariadb-coordinator](https://github.com/kubedb/mariadb-coordinator)

### [v0.40.0](https://github.com/kubedb/mariadb-coordinator/releases/tag/v0.40.0)

- [08b426e5](https://github.com/kubedb/mariadb-coordinator/commit/08b426e5) Prepare for release v0.40.0 (#161)
- [9b802d89](https://github.com/kubedb/mariadb-coordinator/commit/9b802d89) Prepare for release v0.40.0-rc.1 (#160)
- [f69441b7](https://github.com/kubedb/mariadb-coordinator/commit/f69441b7) Use k8s 1.34 client libs (#159)
- [5046d4ba](https://github.com/kubedb/mariadb-coordinator/commit/5046d4ba) Fix makefile indentation (#158)
- [4b8af065](https://github.com/kubedb/mariadb-coordinator/commit/4b8af065) Publish Image for Redhat software certification (#157)
- [e007307f](https://github.com/kubedb/mariadb-coordinator/commit/e007307f) Prepare for release v0.40.0-rc.0 (#156)
- [67015617](https://github.com/kubedb/mariadb-coordinator/commit/67015617) Simplify code
- [8a015658](https://github.com/kubedb/mariadb-coordinator/commit/8a015658) format grpc package
- [810d7607](https://github.com/kubedb/mariadb-coordinator/commit/810d7607) Build ubi image (#155)
- [0b95dc57](https://github.com/kubedb/mariadb-coordinator/commit/0b95dc57) Use golangci-lint 2.x (#154)



## [kubedb/mariadb-csi-snapshotter-plugin](https://github.com/kubedb/mariadb-csi-snapshotter-plugin)

### [v0.20.0](https://github.com/kubedb/mariadb-csi-snapshotter-plugin/releases/tag/v0.20.0)

- [26607e35](https://github.com/kubedb/mariadb-csi-snapshotter-plugin/commit/26607e35) Prepare for release v0.20.0 (#65)
- [59c939d3](https://github.com/kubedb/mariadb-csi-snapshotter-plugin/commit/59c939d3) Prepare for release v0.20.0-rc.1 (#63)
- [9eab57a2](https://github.com/kubedb/mariadb-csi-snapshotter-plugin/commit/9eab57a2) Use k8s 1.34 client libs (#62)
- [762e091e](https://github.com/kubedb/mariadb-csi-snapshotter-plugin/commit/762e091e) Fix makefile indentation (#61)
- [bfc6a10d](https://github.com/kubedb/mariadb-csi-snapshotter-plugin/commit/bfc6a10d) Publish Image for Redhat software certification (#60)
- [615724cf](https://github.com/kubedb/mariadb-csi-snapshotter-plugin/commit/615724cf) Prepare for release v0.20.0-rc.0 (#59)
- [f44d64b1](https://github.com/kubedb/mariadb-csi-snapshotter-plugin/commit/f44d64b1) Change Makefile GO Version (#58)
- [38df4729](https://github.com/kubedb/mariadb-csi-snapshotter-plugin/commit/38df4729) Add golangci (#57)



## [kubedb/mariadb-restic-plugin](https://github.com/kubedb/mariadb-restic-plugin)

### [v0.18.0](https://github.com/kubedb/mariadb-restic-plugin/releases/tag/v0.18.0)




## [kubedb/memcached](https://github.com/kubedb/memcached)

### [v0.53.0](https://github.com/kubedb/memcached/releases/tag/v0.53.0)

- [d9c49db8](https://github.com/kubedb/memcached/commit/d9c49db82) Prepare for release v0.53.0 (#519)
- [25b0aa41](https://github.com/kubedb/memcached/commit/25b0aa419) Update memcached reconfigure (#518)
- [a03adaf4](https://github.com/kubedb/memcached/commit/a03adaf45) Prepare for release v0.53.0-rc.1 (#517)
- [eadd34c6](https://github.com/kubedb/memcached/commit/eadd34c62) Use k8s 1.34 client libs (#516)
- [3bad84ba](https://github.com/kubedb/memcached/commit/3bad84baa) Test against k8s 1.35 (#515)
- [dc1dc137](https://github.com/kubedb/memcached/commit/dc1dc137f) Prepare for release v0.53.0-rc.0 (#514)
- [aa8446d9](https://github.com/kubedb/memcached/commit/aa8446d99) Fix multiple restart issue by introducing parallelismController (#513)
- [1e26cc41](https://github.com/kubedb/memcached/commit/1e26cc416) Move ops to db repo (#512)



## [kubedb/milvus](https://github.com/kubedb/milvus)

### [v0.1.0](https://github.com/kubedb/milvus/releases/tag/v0.1.0)

- [6a714e39](https://github.com/kubedb/milvus/commit/6a714e39) Prepare for release v0.1.0 (#11)
- [e5782e5c](https://github.com/kubedb/milvus/commit/e5782e5c) Update Configuration process (#10)
- [7dee1617](https://github.com/kubedb/milvus/commit/7dee1617) Prepare for release v0.1.0-rc.1 (#9)
- [13b241f4](https://github.com/kubedb/milvus/commit/13b241f4) Use k8s 1.34 client libs (#8)
- [c43dc470](https://github.com/kubedb/milvus/commit/c43dc470) Test against k8s 1.35 (#7)
- [f2c9cbe4](https://github.com/kubedb/milvus/commit/f2c9cbe4) Prepare for release v0.1.0-rc.0 (#6)
- [348ba5dc](https://github.com/kubedb/milvus/commit/348ba5dc) Downgrade k8s version (#5)
- [d7c414da](https://github.com/kubedb/milvus/commit/d7c414da) goversion modified (#3)
- [12dad438](https://github.com/kubedb/milvus/commit/12dad438) Test against k8s 1.34 (#2)
- [c595065b](https://github.com/kubedb/milvus/commit/c595065b) Add milvus provisioner (standalone) (#1)
- [c31441d5](https://github.com/kubedb/milvus/commit/c31441d5) Update .gitignore



## [kubedb/mongodb](https://github.com/kubedb/mongodb)

### [v0.53.0](https://github.com/kubedb/mongodb/releases/tag/v0.53.0)

- [4a9999a2](https://github.com/kubedb/mongodb/commit/4a9999a24) Prepare for release v0.53.0 (#729)
- [06a6f687](https://github.com/kubedb/mongodb/commit/06a6f687d) Re-design Configure reconfigure process (#726)
- [87a59111](https://github.com/kubedb/mongodb/commit/87a591118) Prepare for release v0.53.0-rc.1 (#728)
- [96ec9961](https://github.com/kubedb/mongodb/commit/96ec99618) Use k8s 1.34 client libs (#727)
- [a38f8785](https://github.com/kubedb/mongodb/commit/a38f87851) Test against k8s 1.35 (#725)
- [f73a7159](https://github.com/kubedb/mongodb/commit/f73a7159f) Prepare for release v0.53.0-rc.0 (#724)
- [4a27317f](https://github.com/kubedb/mongodb/commit/4a27317f1) Update golang version
- [3b46da51](https://github.com/kubedb/mongodb/commit/3b46da516) Fix linter (#723)
- [75045740](https://github.com/kubedb/mongodb/commit/75045740a) Fix multiple restart issue by introducing parallelismController (#722)
- [d42b514f](https://github.com/kubedb/mongodb/commit/d42b514f8) Move ops code to db repo (#721)



## [kubedb/mongodb-csi-snapshotter-plugin](https://github.com/kubedb/mongodb-csi-snapshotter-plugin)

### [v0.21.0](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/releases/tag/v0.21.0)

- [e6fd5d5f](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/e6fd5d5f) Prepare for release v0.21.0 (#68)
- [6d6f78bf](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/6d6f78bf) Prepare for release v0.21.0-rc.1 (#66)
- [d9a7e2c2](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/d9a7e2c2) Use k8s 1.34 client libs (#65)
- [7f6dc710](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/7f6dc710) Fix makefile indentation (#64)
- [bbf8bfc9](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/bbf8bfc9) Publish Image for Redhat software certification (#63)
- [75b334b9](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/75b334b9) Prepare for release v0.21.0-rc.0 (#62)
- [2e658828](https://github.com/kubedb/mongodb-csi-snapshotter-plugin/commit/2e658828) Fix linter (#61)



## [kubedb/mongodb-restic-plugin](https://github.com/kubedb/mongodb-restic-plugin)

### [v0.23.0](https://github.com/kubedb/mongodb-restic-plugin/releases/tag/v0.23.0)

- [9ebb8b53](https://github.com/kubedb/mongodb-restic-plugin/commit/9ebb8b53) Prepare for release v0.23.0 (#102)
- [34d434d2](https://github.com/kubedb/mongodb-restic-plugin/commit/34d434d2) Use forked kubestash/restic (#100)
- [eba27b4e](https://github.com/kubedb/mongodb-restic-plugin/commit/eba27b4e) Prepare for release v0.23.0-rc.1 (#99)
- [7b9d416a](https://github.com/kubedb/mongodb-restic-plugin/commit/7b9d416a) Use k8s 1.34 client libs (#98)
- [ae919478](https://github.com/kubedb/mongodb-restic-plugin/commit/ae919478) Fix makefile indentation (#97)
- [e6cd9a26](https://github.com/kubedb/mongodb-restic-plugin/commit/e6cd9a26) Publish Image for Redhat software certification (#96)
- [ecc63fec](https://github.com/kubedb/mongodb-restic-plugin/commit/ecc63fec) Prepare for release v0.23.0-rc.0 (#95)
- [821c386c](https://github.com/kubedb/mongodb-restic-plugin/commit/821c386c) Fix makefile for ubi images (#94)



## [kubedb/mssql-coordinator](https://github.com/kubedb/mssql-coordinator)

### [v0.15.0](https://github.com/kubedb/mssql-coordinator/releases/tag/v0.15.0)

- [cbb8df3b](https://github.com/kubedb/mssql-coordinator/commit/cbb8df3b) Prepare for release v0.15.0 (#53)
- [a9d3248b](https://github.com/kubedb/mssql-coordinator/commit/a9d3248b) Correctly check if sqlservr process is running for new versions (#52)
- [2b55ad11](https://github.com/kubedb/mssql-coordinator/commit/2b55ad11) Prepare for release v0.15.0-rc.1 (#51)
- [29767f76](https://github.com/kubedb/mssql-coordinator/commit/29767f76) Use k8s 1.34 client libs (#50)
- [b3136eda](https://github.com/kubedb/mssql-coordinator/commit/b3136eda) fix makefile (#49)
- [22da7333](https://github.com/kubedb/mssql-coordinator/commit/22da7333) Publish Image for Redhat software certification (#48)
- [e859024e](https://github.com/kubedb/mssql-coordinator/commit/e859024e) Prepare for release v0.15.0-rc.0 (#47)
- [1b3d5a4d](https://github.com/kubedb/mssql-coordinator/commit/1b3d5a4d) Fix container build command
- [a3e461c3](https://github.com/kubedb/mssql-coordinator/commit/a3e461c3) Build ubi image (#46)
- [9268580a](https://github.com/kubedb/mssql-coordinator/commit/9268580a) Use golangci-lint 2.x (#45)



## [kubedb/mssqlserver](https://github.com/kubedb/mssqlserver)

### [v0.15.0](https://github.com/kubedb/mssqlserver/releases/tag/v0.15.0)

- [6567d1a5](https://github.com/kubedb/mssqlserver/commit/6567d1a5) Prepare for release v0.15.0 (#103)
- [2f64f6a0](https://github.com/kubedb/mssqlserver/commit/2f64f6a0) Improve and generalize configure-reconfigure process (#100)
- [605da415](https://github.com/kubedb/mssqlserver/commit/605da415) Prepare for release v0.15.0-rc.1 (#102)
- [566491fe](https://github.com/kubedb/mssqlserver/commit/566491fe) Use k8s 1.34 client libs (#101)
- [5125d044](https://github.com/kubedb/mssqlserver/commit/5125d044) Test against k8s 1.35 (#99)
- [ac4cbed6](https://github.com/kubedb/mssqlserver/commit/ac4cbed6) Prepare for release v0.15.0-rc.0 (#98)
- [0c591eba](https://github.com/kubedb/mssqlserver/commit/0c591eba) Add ReconfigureOps merger (#96)
- [e3ad8e20](https://github.com/kubedb/mssqlserver/commit/e3ad8e20) Improve codebase by refactoring (#93)
- [01ab5c30](https://github.com/kubedb/mssqlserver/commit/01ab5c30) Fix multiple restart issue by introducing parallelismController (#97)
- [2f9976d3](https://github.com/kubedb/mssqlserver/commit/2f9976d3) Fix archiver issue for TLS secure Minio (#94)
- [b02aeeb3](https://github.com/kubedb/mssqlserver/commit/b02aeeb3) Move ops to DB repo (#95)



## [kubedb/mssqlserver-archiver](https://github.com/kubedb/mssqlserver-archiver)

### [v0.14.0](https://github.com/kubedb/mssqlserver-archiver/releases/tag/v0.14.0)

- [720ce9b](https://github.com/kubedb/mssqlserver-archiver/commit/720ce9b) Update release wf (#21)
- [0377147](https://github.com/kubedb/mssqlserver-archiver/commit/0377147) Use k8s 1.34 client libs (#20)
- [1c173bf](https://github.com/kubedb/mssqlserver-archiver/commit/1c173bf) Fix makefile indentation (#19)
- [5c69310](https://github.com/kubedb/mssqlserver-archiver/commit/5c69310) Merge pull request #16 from kubedb/rhm
- [c65e2ae](https://github.com/kubedb/mssqlserver-archiver/commit/c65e2ae) Use golangci-lint 2.x (#15)



## [kubedb/mssqlserver-walg-plugin](https://github.com/kubedb/mssqlserver-walg-plugin)

### [v0.14.0](https://github.com/kubedb/mssqlserver-walg-plugin/releases/tag/v0.14.0)

- [91b8945](https://github.com/kubedb/mssqlserver-walg-plugin/commit/91b8945) Prepare for release v0.14.0 (#43)
- [07f0670](https://github.com/kubedb/mssqlserver-walg-plugin/commit/07f0670) Prepare for release v0.14.0-rc.1 (#41)
- [231ae1c](https://github.com/kubedb/mssqlserver-walg-plugin/commit/231ae1c) Use k8s 1.34 client libs (#40)
- [343568c](https://github.com/kubedb/mssqlserver-walg-plugin/commit/343568c) Fix makefile indentation (#39)
- [bc447f8](https://github.com/kubedb/mssqlserver-walg-plugin/commit/bc447f8) Publish Image for Redhat software certification (#38)
- [93cd25f](https://github.com/kubedb/mssqlserver-walg-plugin/commit/93cd25f) Prepare for release v0.14.0-rc.0 (#37)
- [677dc46](https://github.com/kubedb/mssqlserver-walg-plugin/commit/677dc46) Use golangci-lint 2.x (#36)



## [kubedb/mysql](https://github.com/kubedb/mysql)

### [v0.53.0](https://github.com/kubedb/mysql/releases/tag/v0.53.0)

- [55900db8](https://github.com/kubedb/mysql/commit/55900db8b) Prepare for release v0.53.0 (#714)
- [0a9fd37d](https://github.com/kubedb/mysql/commit/0a9fd37d4) Add Reconfig PodRestart based on User Requirement (#713)
- [b74becf0](https://github.com/kubedb/mysql/commit/b74becf00) Improve and generalize configure-reconfigure (#711)
- [f87bcd7f](https://github.com/kubedb/mysql/commit/f87bcd7fd) Prepare for release v0.53.0-rc.1 (#712)
- [f8490909](https://github.com/kubedb/mysql/commit/f8490909b) Use k8s 1.34 client libs (#710)
- [95a71063](https://github.com/kubedb/mysql/commit/95a710638) Test against k8s 1.35 (#709)
- [5cf311be](https://github.com/kubedb/mysql/commit/5cf311be2) Fix Archiver Panic for Azure backend (#708)
- [613bbbe1](https://github.com/kubedb/mysql/commit/613bbbe19) Prepare for release v0.53.0-rc.0 (#707)
- [6f1a6f0e](https://github.com/kubedb/mysql/commit/6f1a6f0ea) Change Makefile GO Version (#706)
- [1f037c8e](https://github.com/kubedb/mysql/commit/1f037c8e4) Use golangci-lint 2.x (#705)
- [6b649dec](https://github.com/kubedb/mysql/commit/6b649dec9) Fix multiple restart issue by introducing parallelismController (#704)
- [57998a04](https://github.com/kubedb/mysql/commit/57998a04b) move ops code to db repo (#703)



## [kubedb/mysql-archiver](https://github.com/kubedb/mysql-archiver)

### [v0.21.0](https://github.com/kubedb/mysql-archiver/releases/tag/v0.21.0)

- [6b3becf0](https://github.com/kubedb/mysql-archiver/commit/6b3becf0) Prepare for release v0.21.0 (#77)
- [9a8fa9f6](https://github.com/kubedb/mysql-archiver/commit/9a8fa9f6) Submit to red hat catalog (#74)
- [3be30caf](https://github.com/kubedb/mysql-archiver/commit/3be30caf) Prepare for release v0.21.0-rc.1 (#73)
- [3d14d6df](https://github.com/kubedb/mysql-archiver/commit/3d14d6df) Use k8s 1.34 client libs (#72)
- [27ff79e7](https://github.com/kubedb/mysql-archiver/commit/27ff79e7) Fix build rule
- [da732228](https://github.com/kubedb/mysql-archiver/commit/da732228) Prepare for release v0.21.0-rc.0 (#71)
- [e3a552e8](https://github.com/kubedb/mysql-archiver/commit/e3a552e8) Change Makefile GO Version (#70)
- [ad8911b6](https://github.com/kubedb/mysql-archiver/commit/ad8911b6) Add golangci (#69)



## [kubedb/mysql-coordinator](https://github.com/kubedb/mysql-coordinator)

### [v0.38.0](https://github.com/kubedb/mysql-coordinator/releases/tag/v0.38.0)

- [64575b6f](https://github.com/kubedb/mysql-coordinator/commit/64575b6f) Prepare for release v0.38.0 (#160)
- [22cf05ff](https://github.com/kubedb/mysql-coordinator/commit/22cf05ff) Prepare for release v0.38.0-rc.1 (#159)
- [13232ee9](https://github.com/kubedb/mysql-coordinator/commit/13232ee9) Use k8s 1.34 client libs (#157)
- [1f1196f7](https://github.com/kubedb/mysql-coordinator/commit/1f1196f7) Fix makefile indentation (#156)
- [e354dcea](https://github.com/kubedb/mysql-coordinator/commit/e354dcea) Publish Image for Redhat software certification (#155)
- [4f0b448e](https://github.com/kubedb/mysql-coordinator/commit/4f0b448e) Prepare for release v0.38.0-rc.0 (#154)
- [78c11d72](https://github.com/kubedb/mysql-coordinator/commit/78c11d72) Build ubi image (#153)
- [c4ae8e49](https://github.com/kubedb/mysql-coordinator/commit/c4ae8e49) Use golangci-lint 2.x (#152)



## [kubedb/mysql-csi-snapshotter-plugin](https://github.com/kubedb/mysql-csi-snapshotter-plugin)

### [v0.21.0](https://github.com/kubedb/mysql-csi-snapshotter-plugin/releases/tag/v0.21.0)

- [be4af0c4](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/be4af0c4) Prepare for release v0.21.0 (#65)
- [aacc62c7](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/aacc62c7) Prepare for release v0.21.0-rc.1 (#63)
- [50746a8e](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/50746a8e) Use k8s 1.34 client libs (#62)
- [a4ef9a0b](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/a4ef9a0b) Fix makefile indentation (#61)
- [6b1059ae](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/6b1059ae) Publish Image for Redhat software certification (#60)
- [64893d8b](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/64893d8b) Prepare for release v0.21.0-rc.0 (#59)
- [48a23ce5](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/48a23ce5) Change Makefile GO Version (#58)
- [d1732152](https://github.com/kubedb/mysql-csi-snapshotter-plugin/commit/d1732152) Add golangci (#57)



## [kubedb/mysql-restic-plugin](https://github.com/kubedb/mysql-restic-plugin)

### [v0.23.0](https://github.com/kubedb/mysql-restic-plugin/releases/tag/v0.23.0)

- [3dbb2b6f](https://github.com/kubedb/mysql-restic-plugin/commit/3dbb2b6f) Prepare for release v0.23.0 (#92)
- [13952311](https://github.com/kubedb/mysql-restic-plugin/commit/13952311) Use forked kubestash/restic (#90)
- [0eca6918](https://github.com/kubedb/mysql-restic-plugin/commit/0eca6918) Prepare for release v0.23.0-rc.1 (#89)
- [0ceec91e](https://github.com/kubedb/mysql-restic-plugin/commit/0ceec91e) Use k8s 1.34 client libs (#88)
- [d12eee48](https://github.com/kubedb/mysql-restic-plugin/commit/d12eee48) Fix makefile indentation (#87)
- [c22220cd](https://github.com/kubedb/mysql-restic-plugin/commit/c22220cd) Publish Image for Redhat software certification (#86)
- [4552f5f7](https://github.com/kubedb/mysql-restic-plugin/commit/4552f5f7) Prepare for release v0.23.0-rc.0 (#85)
- [1358b920](https://github.com/kubedb/mysql-restic-plugin/commit/1358b920) Fix makefile for ubi images (#84)



## [kubedb/mysql-router-init](https://github.com/kubedb/mysql-router-init)

### [v0.38.0](https://github.com/kubedb/mysql-router-init/releases/tag/v0.38.0)

- [757d12e](https://github.com/kubedb/mysql-router-init/commit/757d12e) Use k8s 1.34 client libs (#55)
- [0983b29](https://github.com/kubedb/mysql-router-init/commit/0983b29) Use golangci-lint 2.x (#54)
- [57d25a8](https://github.com/kubedb/mysql-router-init/commit/57d25a8) Use k8s 1.32 client libs (#53)



## [kubedb/neo4j](https://github.com/kubedb/neo4j)

### [v0.1.0](https://github.com/kubedb/neo4j/releases/tag/v0.1.0)

- [bfe1d9d4](https://github.com/kubedb/neo4j/commit/bfe1d9d4) Prepare for release v0.1.0 (#11)
- [11567e45](https://github.com/kubedb/neo4j/commit/11567e45) Re-design Neo4j configuration field (#10)
- [51303fa4](https://github.com/kubedb/neo4j/commit/51303fa4) Prepare for release v0.1.0-rc.1 (#9)
- [190cb7ee](https://github.com/kubedb/neo4j/commit/190cb7ee) Use k8s 1.34 client libs (#8)
- [669b8b79](https://github.com/kubedb/neo4j/commit/669b8b79) Use k8s 1.32 client libraries (#6)
- [3d0c2f6f](https://github.com/kubedb/neo4j/commit/3d0c2f6f) Prepare for release v0.1.0-rc.0 (#5)
- [b2f7e8f0](https://github.com/kubedb/neo4j/commit/b2f7e8f0) Fix Readme
- [63ee24ca](https://github.com/kubedb/neo4j/commit/63ee24ca) replace go1.25.5 to go1.25 (#3)
- [78e8ae36](https://github.com/kubedb/neo4j/commit/78e8ae36) Neo4j Operator



## [kubedb/oracle](https://github.com/kubedb/oracle)

### [v0.6.0](https://github.com/kubedb/oracle/releases/tag/v0.6.0)

- [30a93cc0](https://github.com/kubedb/oracle/commit/30a93cc0) Prepare for release v0.6.0 (#24)
- [6483df83](https://github.com/kubedb/oracle/commit/6483df83) Prepare for release v0.6.0-rc.1 (#23)
- [8dcfd2ed](https://github.com/kubedb/oracle/commit/8dcfd2ed) Use k8s 1.34 client libs (#22)
- [f8d1e749](https://github.com/kubedb/oracle/commit/f8d1e749) Prepare for release v0.6.0-rc.0 (#20)
- [0aaf27b2](https://github.com/kubedb/oracle/commit/0aaf27b2) Oracle tls complete after review (#18)
- [06611a2f](https://github.com/kubedb/oracle/commit/06611a2f) Moved ops code in oracle operator (#19)



## [kubedb/oracle-coordinator](https://github.com/kubedb/oracle-coordinator)

### [v0.6.0](https://github.com/kubedb/oracle-coordinator/releases/tag/v0.6.0)

- [7e1bc65](https://github.com/kubedb/oracle-coordinator/commit/7e1bc65) Prepare for release v0.6.0 (#20)
- [5d1358a](https://github.com/kubedb/oracle-coordinator/commit/5d1358a) Prepare for release v0.6.0-rc.1 (#19)
- [e0d0e32](https://github.com/kubedb/oracle-coordinator/commit/e0d0e32) Use k8s 1.34 client libs (#18)
- [028fd7d](https://github.com/kubedb/oracle-coordinator/commit/028fd7d) Fix makefile indentation (#17)
- [67c4d12](https://github.com/kubedb/oracle-coordinator/commit/67c4d12) Publish Image for Redhat software certification (#16)
- [6ca661e](https://github.com/kubedb/oracle-coordinator/commit/6ca661e) Prepare for release v0.6.0-rc.0 (#15)
- [f3d4752](https://github.com/kubedb/oracle-coordinator/commit/f3d4752) Build ubi image (#14)
- [c141fa7](https://github.com/kubedb/oracle-coordinator/commit/c141fa7) Use golangci-lint 2.x (#13)
- [f0b4cbb](https://github.com/kubedb/oracle-coordinator/commit/f0b4cbb) Support TLS (#12)



## [kubedb/percona-xtradb](https://github.com/kubedb/percona-xtradb)

### [v0.47.0](https://github.com/kubedb/percona-xtradb/releases/tag/v0.47.0)

- [c6b0c8cc](https://github.com/kubedb/percona-xtradb/commit/c6b0c8ccc) Prepare for release v0.47.0 (#430)
- [aa2c94b2](https://github.com/kubedb/percona-xtradb/commit/aa2c94b20) Use Exporter Version v0.18.0 (#429)
- [a607e1af](https://github.com/kubedb/percona-xtradb/commit/a607e1af5) Improve and generalize configure-reconfigure (#428)
- [0047860f](https://github.com/kubedb/percona-xtradb/commit/0047860f3) Prepare for release v0.47.0-rc.1 (#427)
- [645e9afa](https://github.com/kubedb/percona-xtradb/commit/645e9afaf) Use k8s 1.34 client libs (#426)
- [d383e813](https://github.com/kubedb/percona-xtradb/commit/d383e813d) Test against k8s 1.35 (#425)
- [528043c1](https://github.com/kubedb/percona-xtradb/commit/528043c17) Prepare for release v0.47.0-rc.0 (#424)
- [c3cb6155](https://github.com/kubedb/percona-xtradb/commit/c3cb6155c) update go version in makefile (#423)
- [654c6464](https://github.com/kubedb/percona-xtradb/commit/654c6464e) Use golangci-lint 2.x (#422)
- [0ec47977](https://github.com/kubedb/percona-xtradb/commit/0ec479776) fix multiple restart issue by introducing parallelism controller (#421)
- [4208a065](https://github.com/kubedb/percona-xtradb/commit/4208a065f) move ops code to db repo (#420)



## [kubedb/percona-xtradb-coordinator](https://github.com/kubedb/percona-xtradb-coordinator)

### [v0.33.0](https://github.com/kubedb/percona-xtradb-coordinator/releases/tag/v0.33.0)

- [6d891d1e](https://github.com/kubedb/percona-xtradb-coordinator/commit/6d891d1e) Prepare for release v0.33.0 (#110)
- [a2ac2089](https://github.com/kubedb/percona-xtradb-coordinator/commit/a2ac2089) Prepare for release v0.33.0-rc.1 (#109)
- [53ccb3e1](https://github.com/kubedb/percona-xtradb-coordinator/commit/53ccb3e1) Use k8s 1.34 client libs (#108)
- [3393d9f4](https://github.com/kubedb/percona-xtradb-coordinator/commit/3393d9f4) Fix makefile indentation (#107)
- [83523a0f](https://github.com/kubedb/percona-xtradb-coordinator/commit/83523a0f) Publish Image for Redhat software certification (#106)
- [d0d71987](https://github.com/kubedb/percona-xtradb-coordinator/commit/d0d71987) Prepare for release v0.33.0-rc.0 (#105)
- [f3648936](https://github.com/kubedb/percona-xtradb-coordinator/commit/f3648936) Update image source and name in Dockerfile.ubi
- [9e9945b7](https://github.com/kubedb/percona-xtradb-coordinator/commit/9e9945b7) Build ubi image (#104)
- [437be99c](https://github.com/kubedb/percona-xtradb-coordinator/commit/437be99c) Use golangci-lint 2.x (#103)



## [kubedb/pgbouncer](https://github.com/kubedb/pgbouncer)

### [v0.47.0](https://github.com/kubedb/pgbouncer/releases/tag/v0.47.0)

- [0e9564ce](https://github.com/kubedb/pgbouncer/commit/0e9564ce6) Prepare for release v0.47.0 (#393)
- [2d669051](https://github.com/kubedb/pgbouncer/commit/2d669051a) Improve and generalize configure-reconfigure process for all dbs (#392)
- [b9a64657](https://github.com/kubedb/pgbouncer/commit/b9a646574) Prepare for release v0.47.0-rc.1 (#391)
- [8cdeb750](https://github.com/kubedb/pgbouncer/commit/8cdeb7501) Use k8s 1.34 client libs (#390)
- [1defb0fe](https://github.com/kubedb/pgbouncer/commit/1defb0fe1) Test against k8s 1.35 (#389)
- [f90f38f4](https://github.com/kubedb/pgbouncer/commit/f90f38f40) Prepare for release v0.47.0-rc.0 (#388)
- [d8410281](https://github.com/kubedb/pgbouncer/commit/d84102818) Add golnagci (#387)
- [2b58993f](https://github.com/kubedb/pgbouncer/commit/2b58993f3) Add virtual secret and update Lint (#383)
- [6396e383](https://github.com/kubedb/pgbouncer/commit/6396e383b) Move ops code to db repo (#386)



## [kubedb/pgpool](https://github.com/kubedb/pgpool)

### [v0.15.0](https://github.com/kubedb/pgpool/releases/tag/v0.15.0)

- [ccff7fd9](https://github.com/kubedb/pgpool/commit/ccff7fd9) Prepare for release v0.15.0 (#96)
- [a849809d](https://github.com/kubedb/pgpool/commit/a849809d) Improve and generalize configure-reconfigure process (#95)
- [e5f20e47](https://github.com/kubedb/pgpool/commit/e5f20e47) Fix resource watcher for vsecret (#92)
- [17ba50ae](https://github.com/kubedb/pgpool/commit/17ba50ae) Prepare for release v0.15.0-rc.1 (#94)
- [f6428269](https://github.com/kubedb/pgpool/commit/f6428269) Use k8s 1.34 client libs (#93)
- [c93510d6](https://github.com/kubedb/pgpool/commit/c93510d6) Test against k8s 1.35 (#91)
- [536c4368](https://github.com/kubedb/pgpool/commit/536c4368) Prepare for release v0.15.0-rc.0 (#90)
- [ce38a201](https://github.com/kubedb/pgpool/commit/ce38a201) Add golangci (#89)
- [92bf292e](https://github.com/kubedb/pgpool/commit/92bf292e) add virtual secret and update lint (#88)
- [66cfd1c1](https://github.com/kubedb/pgpool/commit/66cfd1c1) Move ops code to db repo (#87)



## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.60.0](https://github.com/kubedb/postgres/releases/tag/v0.60.0)

- [a313afc9](https://github.com/kubedb/postgres/commit/a313afc9e) Prepare for release v0.60.0 (#847)
- [4d86169d](https://github.com/kubedb/postgres/commit/4d86169d7) Add sharding facility for Postgres Ops-Requests (#843)
- [a4b0d948](https://github.com/kubedb/postgres/commit/a4b0d9486) Prepare for release v0.60.0-rc.1 (#846)
- [2e264101](https://github.com/kubedb/postgres/commit/2e2641018) Use k8s 1.34 client libs (#845)
- [44a384b0](https://github.com/kubedb/postgres/commit/44a384b00) Test against k8s 1.35 (#844)
- [43ab7076](https://github.com/kubedb/postgres/commit/43ab70768) Prepare for release v0.60.0-rc.0 (#842)
- [1f118af2](https://github.com/kubedb/postgres/commit/1f118af2f) Fix postgres split brain | Add auto config tuning support |   (#841)
- [73418b2f](https://github.com/kubedb/postgres/commit/73418b2f8) Virtual Secret further bug fix (#836)
- [57e8114e](https://github.com/kubedb/postgres/commit/57e8114ed) Move in Ops-manager code to Postgres (#837)



## [kubedb/postgres-archiver](https://github.com/kubedb/postgres-archiver)

### [v0.21.0](https://github.com/kubedb/postgres-archiver/releases/tag/v0.21.0)

- [f45faf8c](https://github.com/kubedb/postgres-archiver/commit/f45faf8c) Prepare for release v0.21.0 (#80)
- [0c1f7850](https://github.com/kubedb/postgres-archiver/commit/0c1f7850) Fix redhat catalog submission (#78)
- [16aaff7c](https://github.com/kubedb/postgres-archiver/commit/16aaff7c) Prepare for release v0.21.0-rc.1 (#77)
- [da7738a0](https://github.com/kubedb/postgres-archiver/commit/da7738a0) Prepare for release v0.21.0-rc.1 (#76)
- [7736eaa2](https://github.com/kubedb/postgres-archiver/commit/7736eaa2) Use k8s 1.34 client libs (#75)
- [53ae9b13](https://github.com/kubedb/postgres-archiver/commit/53ae9b13) Fix makefile indentation (#74)
- [fc256522](https://github.com/kubedb/postgres-archiver/commit/fc256522) Publish Image for Redhat software certification (#73)
- [4b6e2958](https://github.com/kubedb/postgres-archiver/commit/4b6e2958) Fix build rule
- [1658ccf6](https://github.com/kubedb/postgres-archiver/commit/1658ccf6) Prepare for release v0.21.0-rc.0 (#72)
- [fb8f8428](https://github.com/kubedb/postgres-archiver/commit/fb8f8428) Update Go version (#71)
- [d0df1d7b](https://github.com/kubedb/postgres-archiver/commit/d0df1d7b) Merge pull request #70 from kubedb/lint
- [26d3ba73](https://github.com/kubedb/postgres-archiver/commit/26d3ba73) update linter
- [4f806c00](https://github.com/kubedb/postgres-archiver/commit/4f806c00) Build and push ubi image (#69)



## [kubedb/postgres-csi-snapshotter-plugin](https://github.com/kubedb/postgres-csi-snapshotter-plugin)

### [v0.21.0](https://github.com/kubedb/postgres-csi-snapshotter-plugin/releases/tag/v0.21.0)

- [ea6e3c50](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/ea6e3c50) Prepare for release v0.21.0 (#75)
- [7d99eb19](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/7d99eb19) Prepare for release v0.21.0-rc.1 (#73)
- [2d482cda](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/2d482cda) Use k8s 1.34 client libs (#72)
- [48e2e4c9](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/48e2e4c9) Fix makefile indentation (#71)
- [ea89b1db](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/ea89b1db) Publish Image for Redhat software certification (#70)
- [0b38fae9](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/0b38fae9) Prepare for release v0.21.0-rc.0 (#69)
- [6a3af86c](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/6a3af86c) Update golang version (#68)
- [3ad4fd33](https://github.com/kubedb/postgres-csi-snapshotter-plugin/commit/3ad4fd33) update lint (#67)



## [kubedb/postgres-restic-plugin](https://github.com/kubedb/postgres-restic-plugin)

### [v0.23.0](https://github.com/kubedb/postgres-restic-plugin/releases/tag/v0.23.0)

- [ff45044b](https://github.com/kubedb/postgres-restic-plugin/commit/ff45044b) Prepare for release v0.23.0 (#90)
- [441378e5](https://github.com/kubedb/postgres-restic-plugin/commit/441378e5) Use forked kubestash/restic (#89)
- [f5f19a6f](https://github.com/kubedb/postgres-restic-plugin/commit/f5f19a6f) Use forked kubestash/restic (#88)
- [a8876977](https://github.com/kubedb/postgres-restic-plugin/commit/a8876977) Prepare for release v0.23.0-rc.1 (#87)
- [13e072fb](https://github.com/kubedb/postgres-restic-plugin/commit/13e072fb) Use k8s 1.34 client libs (#86)
- [b258277e](https://github.com/kubedb/postgres-restic-plugin/commit/b258277e) Fix makefile indentation (#85)
- [5a182fc7](https://github.com/kubedb/postgres-restic-plugin/commit/5a182fc7) Publish Image for Redhat software certification (#84)
- [397396b9](https://github.com/kubedb/postgres-restic-plugin/commit/397396b9) Prepare for release v0.23.0-rc.0 (#83)
- [b53cd1ba](https://github.com/kubedb/postgres-restic-plugin/commit/b53cd1ba) Update Go version (#82)
- [cfe47963](https://github.com/kubedb/postgres-restic-plugin/commit/cfe47963) Update linter (#81)



## [kubedb/provider-aws](https://github.com/kubedb/provider-aws)

### [v0.21.0](https://github.com/kubedb/provider-aws/releases/tag/v0.21.0)




## [kubedb/provider-azure](https://github.com/kubedb/provider-azure)

### [v0.21.0](https://github.com/kubedb/provider-azure/releases/tag/v0.21.0)




## [kubedb/provider-gcp](https://github.com/kubedb/provider-gcp)

### [v0.21.0](https://github.com/kubedb/provider-gcp/releases/tag/v0.21.0)




## [kubedb/proxysql](https://github.com/kubedb/proxysql)

### [v0.47.0](https://github.com/kubedb/proxysql/releases/tag/v0.47.0)

- [cdcee6ba](https://github.com/kubedb/proxysql/commit/cdcee6baf) Prepare for release v0.47.0 (#413)
- [96edac7b](https://github.com/kubedb/proxysql/commit/96edac7b7) Improve and generalize configure-reconfigure process (#412)
- [7ec3ed3f](https://github.com/kubedb/proxysql/commit/7ec3ed3f5) Prepare for release v0.47.0-rc.1 (#411)
- [99a845b1](https://github.com/kubedb/proxysql/commit/99a845b14) Use k8s 1.34 client libs (#410)
- [71efc19c](https://github.com/kubedb/proxysql/commit/71efc19c6) Test against k8s 1.35 (#409)
- [10258db5](https://github.com/kubedb/proxysql/commit/10258db59) Remove github.com/go-xorm/xorm dependency
- [1f965f4f](https://github.com/kubedb/proxysql/commit/1f965f4fd) Prepare for release v0.47.0-rc.0 (#408)
- [4ed80eed](https://github.com/kubedb/proxysql/commit/4ed80eed3) Fix multiple restart issue by introducing parallelismController (#407)
- [111aa2aa](https://github.com/kubedb/proxysql/commit/111aa2aa5) Move ops to db repo (#406)



## [kubedb/qdrant](https://github.com/kubedb/qdrant)

### [v0.1.0](https://github.com/kubedb/qdrant/releases/tag/v0.1.0)

- [1ce521e9](https://github.com/kubedb/qdrant/commit/1ce521e9) Prepare for release v0.1.0 (#14)
- [051524f1](https://github.com/kubedb/qdrant/commit/051524f1) Re-design Configuration process (#12)
- [27031124](https://github.com/kubedb/qdrant/commit/27031124) Add TLS support (#9)
- [47542dd7](https://github.com/kubedb/qdrant/commit/47542dd7) Prepare for release v0.1.0-rc.1 (#11)
- [2653e252](https://github.com/kubedb/qdrant/commit/2653e252) Use k8s 1.34 client libs (#10)
- [a3318df6](https://github.com/kubedb/qdrant/commit/a3318df6) Test against k8s 1.35 (#8)
- [61f7198f](https://github.com/kubedb/qdrant/commit/61f7198f) Prepare for release v0.1.0-rc.0 (#7)
- [55cd4a5c](https://github.com/kubedb/qdrant/commit/55cd4a5c) k8s downgrade (#6)
- [23165061](https://github.com/kubedb/qdrant/commit/23165061) makefile go 1.25 (#4)
- [a3c6b74e](https://github.com/kubedb/qdrant/commit/a3c6b74e) Add Qdrant Provisioner
- [251a144d](https://github.com/kubedb/qdrant/commit/251a144d) Update .gitignore



## [kubedb/rabbitmq](https://github.com/kubedb/rabbitmq)

### [v0.15.0](https://github.com/kubedb/rabbitmq/releases/tag/v0.15.0)

- [34fefed0](https://github.com/kubedb/rabbitmq/commit/34fefed0) Prepare for release v0.15.0 (#108)
- [4de46792](https://github.com/kubedb/rabbitmq/commit/4de46792) Update configure-reconfigure process (#107)
- [5730ad2b](https://github.com/kubedb/rabbitmq/commit/5730ad2b) Prepare for release v0.15.0-rc.1 (#105)
- [fc6d5de0](https://github.com/kubedb/rabbitmq/commit/fc6d5de0) Use k8s 1.34 client libs (#104)
- [34ac217c](https://github.com/kubedb/rabbitmq/commit/34ac217c) Test against k8s 1.35 (#103)
- [8a124e34](https://github.com/kubedb/rabbitmq/commit/8a124e34) Prepare for release v0.15.0-rc.0 (#102)
- [4b3e6a49](https://github.com/kubedb/rabbitmq/commit/4b3e6a49) Fix multiple restart issue by introducing parallelismController (#101)
- [f05a5396](https://github.com/kubedb/rabbitmq/commit/f05a5396) Move ops manager repo to base (#100)



## [kubedb/redis](https://github.com/kubedb/redis)

### [v0.53.0](https://github.com/kubedb/redis/releases/tag/v0.53.0)

- [eeaf253e](https://github.com/kubedb/redis/commit/eeaf253e9) Prepare for release v0.53.0 (#616)
- [9d27adae](https://github.com/kubedb/redis/commit/9d27adaeb) Improve and generalize configure-reconfigure process (#615)
- [504bc21c](https://github.com/kubedb/redis/commit/504bc21c1) Prepare for release v0.53.0-rc.1 (#614)
- [082ef45b](https://github.com/kubedb/redis/commit/082ef45b4) Use k8s 1.34 client libs (#613)
- [ce19d04e](https://github.com/kubedb/redis/commit/ce19d04e5) Test against k8s 1.35 (#612)
- [acecd5f2](https://github.com/kubedb/redis/commit/acecd5f21) Prepare for release v0.53.0-rc.0 (#611)
- [fc0fe37b](https://github.com/kubedb/redis/commit/fc0fe37bd) add Virtual Secret and update lint (#610)
- [994b34ec](https://github.com/kubedb/redis/commit/994b34ece) Move ops code to db repo (#609)



## [kubedb/redis-coordinator](https://github.com/kubedb/redis-coordinator)

### [v0.39.0](https://github.com/kubedb/redis-coordinator/releases/tag/v0.39.0)

- [0a121386](https://github.com/kubedb/redis-coordinator/commit/0a121386) Prepare for release v0.39.0 (#144)
- [c7289d79](https://github.com/kubedb/redis-coordinator/commit/c7289d79) Prepare for release v0.39.0-rc.1 (#143)
- [a135f6e5](https://github.com/kubedb/redis-coordinator/commit/a135f6e5) Use k8s 1.34 client libs (#142)
- [42038efc](https://github.com/kubedb/redis-coordinator/commit/42038efc) Fix makefile indentation (#141)
- [9924e4eb](https://github.com/kubedb/redis-coordinator/commit/9924e4eb) Publish Image for Redhat software certification (#140)
- [75f9f5d9](https://github.com/kubedb/redis-coordinator/commit/75f9f5d9) Prepare for release v0.39.0-rc.0 (#139)
- [5f7ce82b](https://github.com/kubedb/redis-coordinator/commit/5f7ce82b) Virtual Secret added and Make Lint update (#138)
- [520f67f2](https://github.com/kubedb/redis-coordinator/commit/520f67f2) Update Dockerfile label for Redis Coordinator
- [a190c965](https://github.com/kubedb/redis-coordinator/commit/a190c965) Build ubi image (#137)
- [1d673b73](https://github.com/kubedb/redis-coordinator/commit/1d673b73) Use golangci-lint 2.x (#136)



## [kubedb/redis-restic-plugin](https://github.com/kubedb/redis-restic-plugin)

### [v0.23.0](https://github.com/kubedb/redis-restic-plugin/releases/tag/v0.23.0)

- [acb3ec20](https://github.com/kubedb/redis-restic-plugin/commit/acb3ec20) Prepare for release v0.23.0 (#85)
- [095746db](https://github.com/kubedb/redis-restic-plugin/commit/095746db) Use forked kubestash/restic (#84)
- [ecb820f6](https://github.com/kubedb/redis-restic-plugin/commit/ecb820f6) Use forked kubestash/restic (#83)
- [84b3bcce](https://github.com/kubedb/redis-restic-plugin/commit/84b3bcce) Prepare for release v0.23.0-rc.1 (#82)
- [b2ea9fc3](https://github.com/kubedb/redis-restic-plugin/commit/b2ea9fc3) Use k8s 1.34 client libs (#81)
- [3b705e12](https://github.com/kubedb/redis-restic-plugin/commit/3b705e12) Fix makefile indentation (#80)
- [6801fb25](https://github.com/kubedb/redis-restic-plugin/commit/6801fb25) Publish Image for Redhat software certification (#79)
- [7dfce486](https://github.com/kubedb/redis-restic-plugin/commit/7dfce486) Prepare for release v0.23.0-rc.0 (#78)
- [fec65710](https://github.com/kubedb/redis-restic-plugin/commit/fec65710) Update linter (#77)
- [927601ab](https://github.com/kubedb/redis-restic-plugin/commit/927601ab) Update make lint and Add Virtual Secret (#76)



## [kubedb/replication-mode-detector](https://github.com/kubedb/replication-mode-detector)

### [v0.47.0](https://github.com/kubedb/replication-mode-detector/releases/tag/v0.47.0)

- [e43601fb](https://github.com/kubedb/replication-mode-detector/commit/e43601fb) Prepare for release v0.47.0 (#307)
- [77ec3ba3](https://github.com/kubedb/replication-mode-detector/commit/77ec3ba3) Prepare for release v0.47.0-rc.1 (#306)
- [4cb9f404](https://github.com/kubedb/replication-mode-detector/commit/4cb9f404) Use k8s 1.34 client libs (#305)
- [77e5286c](https://github.com/kubedb/replication-mode-detector/commit/77e5286c) Fix makefile indentation (#304)
- [9322cc0c](https://github.com/kubedb/replication-mode-detector/commit/9322cc0c) Publish Image for Redhat software certification (#303)
- [7c77bd18](https://github.com/kubedb/replication-mode-detector/commit/7c77bd18) Prepare for release v0.47.0-rc.0 (#302)
- [5a586bb3](https://github.com/kubedb/replication-mode-detector/commit/5a586bb3) Update Dockerfile label for application name
- [09bc4ae6](https://github.com/kubedb/replication-mode-detector/commit/09bc4ae6) Build ubi image (#301)
- [fd4f2bb5](https://github.com/kubedb/replication-mode-detector/commit/fd4f2bb5) Use golangci-lint 2.x (#300)



## [kubedb/schema-manager](https://github.com/kubedb/schema-manager)

### [v0.36.0](https://github.com/kubedb/schema-manager/releases/tag/v0.36.0)

- [c83b51e0](https://github.com/kubedb/schema-manager/commit/c83b51e0) Prepare for release v0.36.0 (#154)
- [6b881db3](https://github.com/kubedb/schema-manager/commit/6b881db3) Prepare for release v0.36.0-rc.1 (#153)
- [f9e6fea0](https://github.com/kubedb/schema-manager/commit/f9e6fea0) Use k8s 1.34 client libs (#152)
- [76951266](https://github.com/kubedb/schema-manager/commit/76951266) Fix makefile indentation (#151)
- [49234341](https://github.com/kubedb/schema-manager/commit/49234341) Publish Image for Redhat software certification (#150)
- [09a0cc3a](https://github.com/kubedb/schema-manager/commit/09a0cc3a) Fix build
- [1ebf2d05](https://github.com/kubedb/schema-manager/commit/1ebf2d05) Prepare for release v0.36.0-rc.0 (#149)
- [f58a1650](https://github.com/kubedb/schema-manager/commit/f58a1650) Fix linter (#148)



## [kubedb/singlestore](https://github.com/kubedb/singlestore)

### [v0.15.0](https://github.com/kubedb/singlestore/releases/tag/v0.15.0)

- [d655bfec](https://github.com/kubedb/singlestore/commit/d655bfec) Prepare for release v0.15.0 (#96)
- [08bcff61](https://github.com/kubedb/singlestore/commit/08bcff61) Improve and generalize configure-reconfigure (#95)
- [9dd2d8a5](https://github.com/kubedb/singlestore/commit/9dd2d8a5) Prepare for release v0.15.0-rc.1 (#94)
- [73d9f999](https://github.com/kubedb/singlestore/commit/73d9f999) Use k8s 1.34 client libs (#93)
- [f84e08b4](https://github.com/kubedb/singlestore/commit/f84e08b4) Test against k8s 1.35 (#92)
- [f3529d24](https://github.com/kubedb/singlestore/commit/f3529d24) Prepare for release v0.15.0-rc.0 (#91)
- [5378a876](https://github.com/kubedb/singlestore/commit/5378a876) update go version in makefile (#90)
- [57f14b26](https://github.com/kubedb/singlestore/commit/57f14b26) Use golangci-lint 2.x (#89)
- [d2c074b5](https://github.com/kubedb/singlestore/commit/d2c074b5) fix multiple restart issue by introducing parallelism controller (#87)
- [4fe9d994](https://github.com/kubedb/singlestore/commit/4fe9d994) Fix frequent db patch and requeue issue (#88)
- [d771a53e](https://github.com/kubedb/singlestore/commit/d771a53e) move ops code to db repo (#86)



## [kubedb/singlestore-coordinator](https://github.com/kubedb/singlestore-coordinator)

### [v0.15.0](https://github.com/kubedb/singlestore-coordinator/releases/tag/v0.15.0)

- [49dc2d43](https://github.com/kubedb/singlestore-coordinator/commit/49dc2d43) Prepare for release v0.15.0 (#57)
- [2b1fa919](https://github.com/kubedb/singlestore-coordinator/commit/2b1fa919) Prepare for release v0.15.0-rc.1 (#56)
- [4a067f5f](https://github.com/kubedb/singlestore-coordinator/commit/4a067f5f) Use k8s 1.34 client libs (#55)
- [67248c77](https://github.com/kubedb/singlestore-coordinator/commit/67248c77) Fix makefile indentation (#54)
- [e7847baf](https://github.com/kubedb/singlestore-coordinator/commit/e7847baf) Publish Image for Redhat software certification (#53)
- [0fe5c823](https://github.com/kubedb/singlestore-coordinator/commit/0fe5c823) Prepare for release v0.15.0-rc.0 (#52)
- [4fd8963e](https://github.com/kubedb/singlestore-coordinator/commit/4fd8963e) Update Dockerfile label from 'External DNS Operator' to 'Singlestore Coordinator'
- [2115237f](https://github.com/kubedb/singlestore-coordinator/commit/2115237f) Build ubi image (#51)
- [a2c1fa53](https://github.com/kubedb/singlestore-coordinator/commit/a2c1fa53) Use golangci-lint 2.x (#50)



## [kubedb/singlestore-restic-plugin](https://github.com/kubedb/singlestore-restic-plugin)

### [v0.18.0](https://github.com/kubedb/singlestore-restic-plugin/releases/tag/v0.18.0)

- [c5f8dafa](https://github.com/kubedb/singlestore-restic-plugin/commit/c5f8dafa) Prepare for release v0.18.0 (#65)
- [c98bdded](https://github.com/kubedb/singlestore-restic-plugin/commit/c98bdded) Use forked kubestash/restic (#63)
- [5762f17e](https://github.com/kubedb/singlestore-restic-plugin/commit/5762f17e) Prepare for release v0.18.0-rc.1 (#62)
- [3e2214d7](https://github.com/kubedb/singlestore-restic-plugin/commit/3e2214d7) Use k8s 1.34 client libs (#61)
- [b638ab06](https://github.com/kubedb/singlestore-restic-plugin/commit/b638ab06) Fix makefile indentation (#60)
- [378183ea](https://github.com/kubedb/singlestore-restic-plugin/commit/378183ea) Publish Image for Redhat software certification (#59)
- [88634e70](https://github.com/kubedb/singlestore-restic-plugin/commit/88634e70) Prepare for release v0.18.0-rc.0 (#58)
- [285e4640](https://github.com/kubedb/singlestore-restic-plugin/commit/285e4640) update go version in makefile (#57)
- [25bff270](https://github.com/kubedb/singlestore-restic-plugin/commit/25bff270) Use golangci-lint 2.x (#56)
- [25f1e628](https://github.com/kubedb/singlestore-restic-plugin/commit/25f1e628) Fix makefile for ubi images (#55)



## [kubedb/solr](https://github.com/kubedb/solr)

### [v0.15.0](https://github.com/kubedb/solr/releases/tag/v0.15.0)

- [620d72f7](https://github.com/kubedb/solr/commit/620d72f7) Prepare for release v0.15.0 (#108)
- [f58a1f91](https://github.com/kubedb/solr/commit/f58a1f91) Update Configure reconfigure process (#107)
- [4073694e](https://github.com/kubedb/solr/commit/4073694e) Prepare for release v0.15.0-rc.1 (#106)
- [1bd7aa31](https://github.com/kubedb/solr/commit/1bd7aa31) Use k8s 1.34 client libs (#105)
- [a1581efa](https://github.com/kubedb/solr/commit/a1581efa) Bump k8s.io/kubernetes from 1.32.8 to 1.32.10 (#104)
- [ec4afd2b](https://github.com/kubedb/solr/commit/ec4afd2b) Test against k8s 1.35 (#103)
- [090077d5](https://github.com/kubedb/solr/commit/090077d5) Prepare for release v0.15.0-rc.0 (#102)
- [cb654575](https://github.com/kubedb/solr/commit/cb654575) Fix multiple restart issue by introducing parallelismController (#101)
- [8919aabd](https://github.com/kubedb/solr/commit/8919aabd) Move in Ops-manager code to Solr (#100)



## [kubedb/tests](https://github.com/kubedb/tests)

### [v0.45.0](https://github.com/kubedb/tests/releases/tag/v0.45.0)

- [3516c7cb](https://github.com/kubedb/tests/commit/3516c7cb) Prepare for release v0.45.0 (#504)
- [dab2b9be](https://github.com/kubedb/tests/commit/dab2b9be) remove init_config form pgpool (#503)
- [0f520a67](https://github.com/kubedb/tests/commit/0f520a67) reconfigure change: druid, solr, pgpool, redis, (#502)
- [4dc2db5c](https://github.com/kubedb/tests/commit/4dc2db5c) add apimachinery changes [reconfigurationSpec] (#501)
- [66510754](https://github.com/kubedb/tests/commit/66510754) Prepare for release v0.45.0-rc.1 (#499)
- [3b1d93be](https://github.com/kubedb/tests/commit/3b1d93be) Use k8s 1.34 client libs (#498)
- [ec3491a2](https://github.com/kubedb/tests/commit/ec3491a2) Test against k8s 1.35 (#496)
- [5ad85722](https://github.com/kubedb/tests/commit/5ad85722) MSSQLServer Logical Backup (Wal-G) (#481)
- [f3b02cd7](https://github.com/kubedb/tests/commit/f3b02cd7) MariaDB MaxScale VerticalScale (#491)
- [2bd7d59f](https://github.com/kubedb/tests/commit/2bd7d59f) Prepare for release v0.45.0-rc.0 (#495)
- [c91842f7](https://github.com/kubedb/tests/commit/c91842f7) Update go version (#494)
- [e2d20207](https://github.com/kubedb/tests/commit/e2d20207) Release Change: Go- 1.25.5, Linter Fix (#493)
- [ec7c52a1](https://github.com/kubedb/tests/commit/ec7c52a1) MariaDB MaxScale Volume Expansion (#492)
- [2096100e](https://github.com/kubedb/tests/commit/2096100e) MariaDB MaxScale Scaling (Ops) (#488)
- [82246e84](https://github.com/kubedb/tests/commit/82246e84) Add restic, Volumesnapshotter to CI (#490)
- [08bba9ff](https://github.com/kubedb/tests/commit/08bba9ff) Add Base-Backup Mode for Postgres (#484)
- [42ba4e21](https://github.com/kubedb/tests/commit/42ba4e21) Test against k8s 1.34 (#489)
- [16eed29b](https://github.com/kubedb/tests/commit/16eed29b) MySQL Archiver CI  (restic+volumesnapshotter mode) (#473)
- [a635b1eb](https://github.com/kubedb/tests/commit/a635b1eb) add rotate-auth for semi-sync, innodb (#487)



## [kubedb/ui-server](https://github.com/kubedb/ui-server)

### [v0.36.0](https://github.com/kubedb/ui-server/releases/tag/v0.36.0)

- [50ce64af](https://github.com/kubedb/ui-server/commit/50ce64af) Prepare for release v0.36.0 (#186)
- [aa21b74c](https://github.com/kubedb/ui-server/commit/aa21b74c) Prepare for release v0.36.0-rc.1 (#185)
- [10372bf9](https://github.com/kubedb/ui-server/commit/10372bf9) Update vulnerable deps (#184)
- [dc899cea](https://github.com/kubedb/ui-server/commit/dc899cea) Use k8s 1.34 client libs (#183)
- [c1d34c7e](https://github.com/kubedb/ui-server/commit/c1d34c7e) Fix makefile indentation (#182)
- [9ebbb2ac](https://github.com/kubedb/ui-server/commit/9ebbb2ac) Publish Image for Redhat software certification (#179)
- [f5d4d79e](https://github.com/kubedb/ui-server/commit/f5d4d79e) Prepare for release v0.36.0-rc.0 (#178)
- [3563951b](https://github.com/kubedb/ui-server/commit/3563951b) Update Lint (#177)
- [072090b3](https://github.com/kubedb/ui-server/commit/072090b3) make lint update (#176)



## [kubedb/weaviate](https://github.com/kubedb/weaviate)

### [v0.1.0](https://github.com/kubedb/weaviate/releases/tag/v0.1.0)

- [cc2297c3](https://github.com/kubedb/weaviate/commit/cc2297c3) Prepare for release v0.1.0 (#10)
- [71791e5b](https://github.com/kubedb/weaviate/commit/71791e5b) Configuration redesign (#9)
- [429e6c27](https://github.com/kubedb/weaviate/commit/429e6c27) Prepare for release v0.1.0-rc.1 (#8)
- [110cd467](https://github.com/kubedb/weaviate/commit/110cd467) Update vulnerable deps (#7)
- [a5f58ee6](https://github.com/kubedb/weaviate/commit/a5f58ee6) Use k8s 1.34 client libs (#6)
- [387e92f6](https://github.com/kubedb/weaviate/commit/387e92f6) Test against k8s 1.34 (#1)
- [8bb614d5](https://github.com/kubedb/weaviate/commit/8bb614d5) Prepare for release v0.1.0-rc.0 (#4)
- [d53d53e9](https://github.com/kubedb/weaviate/commit/d53d53e9) Add Weaviate DB Support
- [1b27e93a](https://github.com/kubedb/weaviate/commit/1b27e93a) Add vendor



## [kubedb/zookeeper](https://github.com/kubedb/zookeeper)

### [v0.15.0](https://github.com/kubedb/zookeeper/releases/tag/v0.15.0)

- [e354f44a](https://github.com/kubedb/zookeeper/commit/e354f44a) Prepare for release v0.15.0 (#99)
- [7eeed01d](https://github.com/kubedb/zookeeper/commit/7eeed01d) Update Configure reconfigure process (#98)
- [05a44ba9](https://github.com/kubedb/zookeeper/commit/05a44ba9) Prepare for release v0.15.0-rc.1 (#97)
- [bfdf1c28](https://github.com/kubedb/zookeeper/commit/bfdf1c28) Use k8s 1.34 client libs (#96)
- [ca2cbe8b](https://github.com/kubedb/zookeeper/commit/ca2cbe8b) Test against k8s 1.35 (#95)
- [4be45687](https://github.com/kubedb/zookeeper/commit/4be45687) Prepare for release v0.15.0-rc.0 (#94)
- [c1da0e5f](https://github.com/kubedb/zookeeper/commit/c1da0e5f) replace go1.25.5 to go1.25 (#93)
- [55fe861b](https://github.com/kubedb/zookeeper/commit/55fe861b) Fix multiple restart issue by introducing parallelismController (#91)
- [c75acf90](https://github.com/kubedb/zookeeper/commit/c75acf90) Make Update go version and lint fix (#92)
- [23219262](https://github.com/kubedb/zookeeper/commit/23219262) Move ops code to db repo (#90)



## [kubedb/zookeeper-restic-plugin](https://github.com/kubedb/zookeeper-restic-plugin)

### [v0.16.0](https://github.com/kubedb/zookeeper-restic-plugin/releases/tag/v0.16.0)

- [479cf05](https://github.com/kubedb/zookeeper-restic-plugin/commit/479cf05) Prepare for release v0.16.0 (#54)
- [a1be425](https://github.com/kubedb/zookeeper-restic-plugin/commit/a1be425) Use forked kubestash/restic (#53)
- [89d7089](https://github.com/kubedb/zookeeper-restic-plugin/commit/89d7089) Use forked kubestash/restic (#52)
- [1f1a5f1](https://github.com/kubedb/zookeeper-restic-plugin/commit/1f1a5f1) Prepare for release v0.16.0-rc.1 (#51)
- [f4afa89](https://github.com/kubedb/zookeeper-restic-plugin/commit/f4afa89) Use k8s 1.34 client libs (#50)
- [ecd338e](https://github.com/kubedb/zookeeper-restic-plugin/commit/ecd338e) Fix makefile indentation (#49)
- [513fdf0](https://github.com/kubedb/zookeeper-restic-plugin/commit/513fdf0) Publish Image for Redhat software certification (#48)
- [8970e4d](https://github.com/kubedb/zookeeper-restic-plugin/commit/8970e4d) Prepare for release v0.16.0-rc.0 (#47)
- [079fdca](https://github.com/kubedb/zookeeper-restic-plugin/commit/079fdca) Go version update (#46)
- [4c5f81a](https://github.com/kubedb/zookeeper-restic-plugin/commit/4c5f81a) linter fix (#45)



