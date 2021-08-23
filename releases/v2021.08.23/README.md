# KubeDB v2021.08.23 (2021-08-23)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.20.0](https://github.com/kubedb/apimachinery/releases/tag/v0.20.0)

- [c8377128](https://github.com/kubedb/apimachinery/commit/c8377128) Add constant for Redis (#783)
- [86bf3060](https://github.com/kubedb/apimachinery/commit/86bf3060) Remove Auth secret after Deletion of Redis (#781)
- [a982c412](https://github.com/kubedb/apimachinery/commit/a982c412) Add KubeDB distribution for Elasticsearch images (#782)
- [a8eb885c](https://github.com/kubedb/apimachinery/commit/a8eb885c) Revert back to old structure
- [a3581bc6](https://github.com/kubedb/apimachinery/commit/a3581bc6) Move secret and statefulset informer to Controller (#780)
- [3327d4c1](https://github.com/kubedb/apimachinery/commit/3327d4c1) Remove WatchNamespace from Config
- [5465bfd4](https://github.com/kubedb/apimachinery/commit/5465bfd4) Restrict watchers to a namespace (#779)
- [d5e158ef](https://github.com/kubedb/apimachinery/commit/d5e158ef) Add support for Elasticsearch secure settings (#777)
- [e6ff1fd6](https://github.com/kubedb/apimachinery/commit/e6ff1fd6) Update documentation for enableSSL field (#778)
- [f011f893](https://github.com/kubedb/apimachinery/commit/f011f893) Update repository config (#776)
- [ba3edad2](https://github.com/kubedb/apimachinery/commit/ba3edad2) Update repository config (#775)
- [2c8e7ea7](https://github.com/kubedb/apimachinery/commit/2c8e7ea7) Test crds (#774)
- [89c85a98](https://github.com/kubedb/apimachinery/commit/89c85a98) Remove panic for Redis (#773)
- [24bc990a](https://github.com/kubedb/apimachinery/commit/24bc990a) Update dependencies
- [7fe9731b](https://github.com/kubedb/apimachinery/commit/7fe9731b) Only generate crd v1 yamls (#772)
- [1ce46330](https://github.com/kubedb/apimachinery/commit/1ce46330) Rename Opendistro for Elasticsearch performance analyzer port name (#770)
- [1c1e6ef0](https://github.com/kubedb/apimachinery/commit/1c1e6ef0) Allow customizing resource settings for pg coordinator container (#771)



## [kubedb/cli](https://github.com/kubedb/cli)

### [v0.20.0](https://github.com/kubedb/cli/releases/tag/v0.20.0)

- [d5f1dbd4](https://github.com/kubedb/cli/commit/d5f1dbd4) Prepare for release v0.20.0 (#619)
- [2e84e662](https://github.com/kubedb/cli/commit/2e84e662) Add `show-credentials` commands (#618)
- [79ccacd2](https://github.com/kubedb/cli/commit/79ccacd2) Add pause/resume support (#597)
- [e1d6e1ef](https://github.com/kubedb/cli/commit/e1d6e1ef) Add `restart` command (#599)
- [3fa6c894](https://github.com/kubedb/cli/commit/3fa6c894) Update dependencies (#617)
- [998ec275](https://github.com/kubedb/cli/commit/998ec275) Update dependencies (#616)
- [231371de](https://github.com/kubedb/cli/commit/231371de) Update dependencies (#615)
- [654dd914](https://github.com/kubedb/cli/commit/654dd914) Update dependencies (#614)
- [3e1f519a](https://github.com/kubedb/cli/commit/3e1f519a) Update dependencies (#613)
- [1a7cdbc7](https://github.com/kubedb/cli/commit/1a7cdbc7) Update dependencies (#611)
- [2fcf8e6d](https://github.com/kubedb/cli/commit/2fcf8e6d) Stop using deprecated api kinds in k8s 1.22



## [kubedb/elasticsearch](https://github.com/kubedb/elasticsearch)

### [v0.20.0](https://github.com/kubedb/elasticsearch/releases/tag/v0.20.0)

- [0568ed61](https://github.com/kubedb/elasticsearch/commit/0568ed61) Prepare for release v0.20.0 (#511)
- [da28bf06](https://github.com/kubedb/elasticsearch/commit/da28bf06) Add support for Hot-Warm Clustering for OpenDistro of Elasticsearch (#506)
- [5859b723](https://github.com/kubedb/elasticsearch/commit/5859b723) Add support for secure settings (#509)
- [e9478903](https://github.com/kubedb/elasticsearch/commit/e9478903) Restrict Community Edition to demo namespace (#510)
- [7e8d91c5](https://github.com/kubedb/elasticsearch/commit/7e8d91c5) Update repository config (#508)
- [dc5d7fed](https://github.com/kubedb/elasticsearch/commit/dc5d7fed) Update dependencies (#507)
- [f472c1ea](https://github.com/kubedb/elasticsearch/commit/f472c1ea) Stop using deprecated api kinds in k8s 1.22
- [ee479fa6](https://github.com/kubedb/elasticsearch/commit/ee479fa6) Only points to the ingest nodes from stats service (#505)
- [6b576eb9](https://github.com/kubedb/elasticsearch/commit/6b576eb9) Fix repetitive patch-ing (#504)



## [kubedb/mariadb](https://github.com/kubedb/mariadb)

### [v0.4.0](https://github.com/kubedb/mariadb/releases/tag/v0.4.0)

- [55924eb9](https://github.com/kubedb/mariadb/commit/55924eb9) Prepare for release v0.4.0 (#85)
- [355da6ee](https://github.com/kubedb/mariadb/commit/355da6ee) Restrict Community Edition to demo namespace (#84)
- [b284cde6](https://github.com/kubedb/mariadb/commit/b284cde6) Update repository config (#83)
- [8d25306b](https://github.com/kubedb/mariadb/commit/8d25306b) Update repository config (#82)
- [c7c999a0](https://github.com/kubedb/mariadb/commit/c7c999a0) Update dependencies (#81)
- [7ac44469](https://github.com/kubedb/mariadb/commit/7ac44469) Fix repetitive patch issue in MariaDB (#79)
- [24fe8f76](https://github.com/kubedb/mariadb/commit/24fe8f76) Stop using deprecated api kinds in k8s 1.22



## [kubedb/memcached](https://github.com/kubedb/memcached)

### [v0.13.0](https://github.com/kubedb/memcached/releases/tag/v0.13.0)

- [98287a7b](https://github.com/kubedb/memcached/commit/98287a7b) Prepare for release v0.13.0 (#306)
- [5ab5673d](https://github.com/kubedb/memcached/commit/5ab5673d) Restrict Community Edition to demo namespace (#305)
- [399bc04e](https://github.com/kubedb/memcached/commit/399bc04e) Update repository config (#304)
- [95694c2f](https://github.com/kubedb/memcached/commit/95694c2f) Update repository config (#303)
- [6fb5b271](https://github.com/kubedb/memcached/commit/6fb5b271) Update dependencies (#302)
- [2d3550fc](https://github.com/kubedb/memcached/commit/2d3550fc) Stop using api kinds deprecated in k8s 1.22



## [kubedb/mongodb](https://github.com/kubedb/mongodb)

### [v0.13.0](https://github.com/kubedb/mongodb/releases/tag/v0.13.0)

- [34999e07](https://github.com/kubedb/mongodb/commit/34999e07) Prepare for release v0.13.0 (#409)
- [9dadff03](https://github.com/kubedb/mongodb/commit/9dadff03) Restrict Community Edition to demo namespace (#408)
- [20e8d6d7](https://github.com/kubedb/mongodb/commit/20e8d6d7) Update repository config (#407)
- [410dc379](https://github.com/kubedb/mongodb/commit/410dc379) Update repository config (#406)
- [ba8ea791](https://github.com/kubedb/mongodb/commit/ba8ea791) Update dependencies (#404)
- [fb5f5257](https://github.com/kubedb/mongodb/commit/fb5f5257) Stop using api kinds deprecated in k8s 1.22
- [e38b4aa5](https://github.com/kubedb/mongodb/commit/e38b4aa5) Fix repetitive patch-ing (#403)



## [kubedb/mysql](https://github.com/kubedb/mysql)

### [v0.13.0](https://github.com/kubedb/mysql/releases/tag/v0.13.0)

- [2700a224](https://github.com/kubedb/mysql/commit/2700a224) Prepare for release v0.13.0 (#399)
- [83b1b7e9](https://github.com/kubedb/mysql/commit/83b1b7e9) Restrict Community Edition to demo namespace (#398)
- [1a0dcd47](https://github.com/kubedb/mysql/commit/1a0dcd47) Update repository config (#397)
- [d59061fd](https://github.com/kubedb/mysql/commit/d59061fd) Update repository config (#396)
- [3066cd54](https://github.com/kubedb/mysql/commit/3066cd54) Update dependencies (#395)
- [ef8b78d1](https://github.com/kubedb/mysql/commit/ef8b78d1) Fix Repetitive Patch Issue MySQL (#394)
- [99bcc275](https://github.com/kubedb/mysql/commit/99bcc275) Stop using api kinds removed in k8s 1.22



## [kubedb/percona-xtradb](https://github.com/kubedb/percona-xtradb)

### [v0.7.0](https://github.com/kubedb/percona-xtradb/releases/tag/v0.7.0)

- [0bcb7e8c](https://github.com/kubedb/percona-xtradb/commit/0bcb7e8c) Prepare for release v0.7.0 (#208)
- [5c94a9b0](https://github.com/kubedb/percona-xtradb/commit/5c94a9b0) Restrict Community Edition to demo namespace (#207)
- [bd6740df](https://github.com/kubedb/percona-xtradb/commit/bd6740df) Update repository config (#206)
- [67fcc570](https://github.com/kubedb/percona-xtradb/commit/67fcc570) Update repository config (#205)
- [2dfcfd3f](https://github.com/kubedb/percona-xtradb/commit/2dfcfd3f) Update dependencies (#204)
- [1a0aa385](https://github.com/kubedb/percona-xtradb/commit/1a0aa385) Stop using api versions removed in k8s 1.22



## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.20.0](https://github.com/kubedb/postgres/releases/tag/v0.20.0)

- [d3eec559](https://github.com/kubedb/postgres/commit/d3eec559) Prepare for release v0.20.0 (#515)
- [ea11e98d](https://github.com/kubedb/postgres/commit/ea11e98d) Restrict Community Edition to demo namespace (#514)
- [d3d17bfc](https://github.com/kubedb/postgres/commit/d3d17bfc) Update repository config (#513)
- [698c72b5](https://github.com/kubedb/postgres/commit/698c72b5) Update repository config (#512)
- [4bd33547](https://github.com/kubedb/postgres/commit/4bd33547) Update dependencies (#511)
- [39f294df](https://github.com/kubedb/postgres/commit/39f294df) Stop using api versions deprecated in k8s 1.22
- [6cb08c0f](https://github.com/kubedb/postgres/commit/6cb08c0f) Fix Continuous Statefulset Patching (#510)



## [kubedb/redis](https://github.com/kubedb/redis)

### [v0.13.0](https://github.com/kubedb/redis/releases/tag/v0.13.0)

- [4e331b2c](https://github.com/kubedb/redis/commit/4e331b2c) Prepare for release v0.13.0 (#334)
- [cefba860](https://github.com/kubedb/redis/commit/cefba860) Add Auth Secret in Redis (#333)
- [b412a862](https://github.com/kubedb/redis/commit/b412a862) Restrict Community Edition to demo namespace (#332)
- [765c767c](https://github.com/kubedb/redis/commit/765c767c) Restrict Community Edition to demo namespace (#331)
- [f5b0af55](https://github.com/kubedb/redis/commit/f5b0af55) Update repository config (#330)
- [7004f37f](https://github.com/kubedb/redis/commit/7004f37f) Update repository config (#329)
- [bbe8a4fe](https://github.com/kubedb/redis/commit/bbe8a4fe) Update dependencies (#328)
- [4bd2a852](https://github.com/kubedb/redis/commit/4bd2a852) Remove panic And Fix Repetitive Statefulset patch  (#327)
- [d941d122](https://github.com/kubedb/redis/commit/d941d122) Stop using api versions removed in k8s 1.22



## [kubedb/replication-mode-detector](https://github.com/kubedb/replication-mode-detector)

### [v0.7.0](https://github.com/kubedb/replication-mode-detector/releases/tag/v0.7.0)

- [5acb289](https://github.com/kubedb/replication-mode-detector/commit/5acb289) Prepare for release v0.7.0 (#153)
- [779ca5f](https://github.com/kubedb/replication-mode-detector/commit/779ca5f) Update dependencies (#152)
- [07e8917](https://github.com/kubedb/replication-mode-detector/commit/07e8917) Update dependencies (#151)
- [7184fc6](https://github.com/kubedb/replication-mode-detector/commit/7184fc6) Update dependencies (#150)
- [fe3d8e3](https://github.com/kubedb/replication-mode-detector/commit/fe3d8e3) Update dependencies (#149)
- [cc1b4e9](https://github.com/kubedb/replication-mode-detector/commit/cc1b4e9) Update dependencies (#148)
- [e80918a](https://github.com/kubedb/replication-mode-detector/commit/e80918a) Update repository config (#147)
- [b17c5e4](https://github.com/kubedb/replication-mode-detector/commit/b17c5e4) Update dependencies (#145)



## [kubedb/tests](https://github.com/kubedb/tests)

### [v0.5.0](https://github.com/kubedb/tests/releases/tag/v0.5.0)

- [8526856](https://github.com/kubedb/tests/commit/8526856) Prepare for release v0.5.0 (#133)
- [9d517da](https://github.com/kubedb/tests/commit/9d517da) Update dependencies (#132)
- [66c9042](https://github.com/kubedb/tests/commit/66c9042) Update dependencies (#131)
- [712e2e3](https://github.com/kubedb/tests/commit/712e2e3) Update dependencies (#130)
- [b92a730](https://github.com/kubedb/tests/commit/b92a730) Update dependencies (#129)
- [2c4bd02](https://github.com/kubedb/tests/commit/2c4bd02) Update dependencies (#128)
- [f8bb956](https://github.com/kubedb/tests/commit/f8bb956) Update repository config (#127)
- [0d2e0d6](https://github.com/kubedb/tests/commit/0d2e0d6) Update dependencies (#126)



