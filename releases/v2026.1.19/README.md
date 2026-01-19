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



## [kubedb/mssqlserver-walg-plugin](https://github.com/kubedb/mssqlserver-walg-plugin)

### [v0.14.0](https://github.com/kubedb/mssqlserver-walg-plugin/releases/tag/v0.14.0)

- [91b8945](https://github.com/kubedb/mssqlserver-walg-plugin/commit/91b8945) Prepare for release v0.14.0 (#43)
- [07f0670](https://github.com/kubedb/mssqlserver-walg-plugin/commit/07f0670) Prepare for release v0.14.0-rc.1 (#41)
- [231ae1c](https://github.com/kubedb/mssqlserver-walg-plugin/commit/231ae1c) Use k8s 1.34 client libs (#40)
- [343568c](https://github.com/kubedb/mssqlserver-walg-plugin/commit/343568c) Fix makefile indentation (#39)
- [bc447f8](https://github.com/kubedb/mssqlserver-walg-plugin/commit/bc447f8) Publish Image for Redhat software certification (#38)
- [93cd25f](https://github.com/kubedb/mssqlserver-walg-plugin/commit/93cd25f) Prepare for release v0.14.0-rc.0 (#37)
- [677dc46](https://github.com/kubedb/mssqlserver-walg-plugin/commit/677dc46) Use golangci-lint 2.x (#36)



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



