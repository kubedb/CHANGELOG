# KubeDB v2026.2.27 (2026-02-26)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.61.0](https://github.com/kubedb/apimachinery/releases/tag/v0.61.0)

- [63cc8851](https://github.com/kubedb/apimachinery/commit/63cc8851f) Update for release KubeStash@v2026.2.27 (#1610)
- [9e5bc952](https://github.com/kubedb/apimachinery/commit/9e5bc9529) Fix linter warning
- [542ee577](https://github.com/kubedb/apimachinery/commit/542ee5772) Mark coordinator fields as required (#1609)
- [9551a464](https://github.com/kubedb/apimachinery/commit/9551a4641) Change postgres default client authentication method for pg 18 (#1602)
- [42d32c4d](https://github.com/kubedb/apimachinery/commit/42d32c4dd) Add HanaDB clustering (#1543)
- [a2ec144f](https://github.com/kubedb/apimachinery/commit/a2ec144f5) Implement progressing controller for ops (#1607)
- [f29876fb](https://github.com/kubedb/apimachinery/commit/f29876fbf) Add Neo4j Opsreq = [ReconfigureTLS] (#1605)
- [412dad63](https://github.com/kubedb/apimachinery/commit/412dad63b) Fix linter warning
- [c1839a90](https://github.com/kubedb/apimachinery/commit/c1839a90c) Update nats.go to v1.49.0
- [015c3493](https://github.com/kubedb/apimachinery/commit/015c3493e) Report cluster features via site info (#1606)
- [88d5ab20](https://github.com/kubedb/apimachinery/commit/88d5ab201) Fix CVE (#1603)
- [913319e2](https://github.com/kubedb/apimachinery/commit/913319e2e) Add Neo4j Monitoring, TLS,  Restart Ops Req  APIs (#1552)
- [24696181](https://github.com/kubedb/apimachinery/commit/246961815) Fix CVE (#1601)
- [71337bae](https://github.com/kubedb/apimachinery/commit/71337bae8) Update for release KubeStash@v2026.2.16-rc.0 (#1598)
- [f207902b](https://github.com/kubedb/apimachinery/commit/f207902b5) go fix ./... (#1597)
- [54c28427](https://github.com/kubedb/apimachinery/commit/54c284279) Update migrator image spec (#1596)
- [78da1b2d](https://github.com/kubedb/apimachinery/commit/78da1b2d6) Redis Config Secret Conversion fix (#1595)
- [f1ac6610](https://github.com/kubedb/apimachinery/commit/f1ac6610d) Standardize migrator pkg (#1594)
- [8c54988a](https://github.com/kubedb/apimachinery/commit/8c54988a4) Report k8s distro and storage provisioners (#1593)
- [3ab9a8c4](https://github.com/kubedb/apimachinery/commit/3ab9a8c46) Fix CI (#1592)
- [46868bd0](https://github.com/kubedb/apimachinery/commit/46868bd03) Add Distributed Archiver Support for MariaDB (#1582)
- [d390f703](https://github.com/kubedb/apimachinery/commit/d390f7030) Add Migrator Operator APIs and Configs for CLI (#1588)
- [71146793](https://github.com/kubedb/apimachinery/commit/711467936) Add Qdrant Monitoring Support (#1550)
- [8591d06f](https://github.com/kubedb/apimachinery/commit/8591d06f2) Add read replica support for Postgres (#1580)
- [09750ca1](https://github.com/kubedb/apimachinery/commit/09750ca1e) Add Milvus Cluster Apis (#1551)
- [eec0c01f](https://github.com/kubedb/apimachinery/commit/eec0c01f2) Introduce log RetentionPeriod for log cleanup (#1537)
- [05e2788c](https://github.com/kubedb/apimachinery/commit/05e2788ca) Add Kafka Tiered Storage APIs (#1378)
- [719ce3b0](https://github.com/kubedb/apimachinery/commit/719ce3b05) Update license header (#1591)
- [04bd7de6](https://github.com/kubedb/apimachinery/commit/04bd7de62) Add Constant For Opensearch/Elasticsearch (#1578)
- [7eb9e9a4](https://github.com/kubedb/apimachinery/commit/7eb9e9a4c) Add tolerations to pvc-mounter pod for storageclass migration (#1589)
- [81a671f5](https://github.com/kubedb/apimachinery/commit/81a671f52) Add relabel config support to ServiceMonitor (#1584)



## [kubedb/crd-manager](https://github.com/kubedb/crd-manager)

### [v0.16.0](https://github.com/kubedb/crd-manager/releases/tag/v0.16.0)

- [acf7d0d6](https://github.com/kubedb/crd-manager/commit/acf7d0d6) Prepare for release v0.16.0 (#116)
- [3378cd91](https://github.com/kubedb/crd-manager/commit/3378cd91) Maintain active versions using configMap (#113)
- [89ba8728](https://github.com/kubedb/crd-manager/commit/89ba8728) Update deps (#114)
- [b842153d](https://github.com/kubedb/crd-manager/commit/b842153d) Prepare for release v0.16.0-rc.1 (#112)
- [2d2c0c9a](https://github.com/kubedb/crd-manager/commit/2d2c0c9a) Prepare for release v0.16.0-rc.0 (#110)



## [kubedb/db-client-go](https://github.com/kubedb/db-client-go)

### [v0.16.0](https://github.com/kubedb/db-client-go/releases/tag/v0.16.0)

- [263ed82c](https://github.com/kubedb/db-client-go/commit/263ed82c) Prepare for release v0.16.0 (#226)
- [92155aaf](https://github.com/kubedb/db-client-go/commit/92155aaf) Set maxPoolSize & idleTime for mongo client (#222)
- [2ee83ba1](https://github.com/kubedb/db-client-go/commit/2ee83ba1) Add reconfigure TLS (#225)
- [96ffd3fa](https://github.com/kubedb/db-client-go/commit/96ffd3fa) Prepare for release v0.16.0-rc.1 (#224)
- [9d31719c](https://github.com/kubedb/db-client-go/commit/9d31719c) Add Neo4j TLS (#220)
- [3cbe8746](https://github.com/kubedb/db-client-go/commit/3cbe8746) Prepare for release v0.16.0-rc.0 (#221)
- [496ef203](https://github.com/kubedb/db-client-go/commit/496ef203) Add Creating MariaDB Client without MariaDB Instance (#218)



## [kubedb/mariadb-archiver](https://github.com/kubedb/mariadb-archiver)

### [v0.21.0](https://github.com/kubedb/mariadb-archiver/releases/tag/v0.21.0)




## [kubedb/mssqlserver](https://github.com/kubedb/mssqlserver)

### [v0.16.0](https://github.com/kubedb/mssqlserver/releases/tag/v0.16.0)

- [61c15dea](https://github.com/kubedb/mssqlserver/commit/61c15dea) Prepare for release v0.16.0 (#112)
- [c86e1178](https://github.com/kubedb/mssqlserver/commit/c86e1178) Prepare for release v0.16.0-rc.1 (#111)
- [b11cee95](https://github.com/kubedb/mssqlserver/commit/b11cee95) Prepare for release v0.16.0-rc.0 (#109)
- [ca90875f](https://github.com/kubedb/mssqlserver/commit/ca90875f) Update for KubeStash API (#108)
- [da9faff4](https://github.com/kubedb/mssqlserver/commit/da9faff4) Integrate shouldProceed() utility on runParallel (#105)



## [kubedb/mysql](https://github.com/kubedb/mysql)

### [v0.54.0](https://github.com/kubedb/mysql/releases/tag/v0.54.0)

- [19dafdf3](https://github.com/kubedb/mysql/commit/19dafdf3e) Prepare for release v0.54.0 (#729)
- [b7d7ccda](https://github.com/kubedb/mysql/commit/b7d7ccda1) added backupstorage support from different namespace (#728)
- [318ed147](https://github.com/kubedb/mysql/commit/318ed147b) Fix multiple ops request in progressing state (#727)
- [53ca7c58](https://github.com/kubedb/mysql/commit/53ca7c585) Remove previous config volume if exist (#725)
- [0db51d13](https://github.com/kubedb/mysql/commit/0db51d13c) Prepare for release v0.54.0-rc.1 (#726)
- [05e392f5](https://github.com/kubedb/mysql/commit/05e392f58) Prepare for release v0.54.0-rc.0 (#722)
- [95604806](https://github.com/kubedb/mysql/commit/95604806d) added permission for binlog-cleanup (#719)
- [8959e3ea](https://github.com/kubedb/mysql/commit/8959e3ea5) Update for Kubestash API (#721)
- [865c8dd0](https://github.com/kubedb/mysql/commit/865c8dd0e) Add pod toleration during storageClass migration (#718)
- [5fed4bfc](https://github.com/kubedb/mysql/commit/5fed4bfc7) Update ops parallelism (#716)
- [62650d63](https://github.com/kubedb/mysql/commit/62650d638) Upgrade Exporter to v0.18.0 (#715)



