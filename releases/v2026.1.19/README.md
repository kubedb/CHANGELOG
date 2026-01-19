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



