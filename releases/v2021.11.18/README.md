# KubeDB v2021.11.18 (2021-11-17)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.23.0](https://github.com/kubedb/apimachinery/releases/tag/v0.23.0)

- [ff3a4175](https://github.com/kubedb/apimachinery/commit/ff3a4175) Update repository config (#819)
- [1969d04c](https://github.com/kubedb/apimachinery/commit/1969d04c) Remove EnableAnalytics (#818)
- [1222a1d6](https://github.com/kubedb/apimachinery/commit/1222a1d6) Add pod and workload controller label support (#817)
- [1cef6837](https://github.com/kubedb/apimachinery/commit/1cef6837) Allow vertical scaling Coordinator (#816)
- [90d46474](https://github.com/kubedb/apimachinery/commit/90d46474) Add distribution tags for KubeDB (#815)
- [24d44217](https://github.com/kubedb/apimachinery/commit/24d44217) Update default resource for pg-coordinator (#813)
- [807280ce](https://github.com/kubedb/apimachinery/commit/807280ce) Add `applyConfig` in MongoDBOpsRequest for custom configuration (#811)
- [6f31cb6a](https://github.com/kubedb/apimachinery/commit/6f31cb6a) Add support for OpenSearch (#810)
- [b9f7eadd](https://github.com/kubedb/apimachinery/commit/b9f7eadd) Stop using storage.k8s.io/v1beta1 deprecated in k8s 1.22 (#814)
- [73f09b6b](https://github.com/kubedb/apimachinery/commit/73f09b6b) Add support for reconfigure Elasticsearch (#793)
- [997836d3](https://github.com/kubedb/apimachinery/commit/997836d3) Add Redis Constants for Config files (#812)
- [d0176524](https://github.com/kubedb/apimachinery/commit/d0176524) Remove statefulSetOrdinal from MySQL ops reuqest (#809)
- [ad8c1f78](https://github.com/kubedb/apimachinery/commit/ad8c1f78) Update MySQLClusterMode constants (#808)
- [8ce33b18](https://github.com/kubedb/apimachinery/commit/8ce33b18) Update deps
- [d8ea50ce](https://github.com/kubedb/apimachinery/commit/d8ea50ce) Update for release Stash@v2021.10.11 (#807)
- [4937544e](https://github.com/kubedb/apimachinery/commit/4937544e) Add MySQL Router constant (#805)
- [ee093b4d](https://github.com/kubedb/apimachinery/commit/ee093b4d) Add new distribution values (#806)
- [47b42be0](https://github.com/kubedb/apimachinery/commit/47b42be0) Add support for MySQL coordinator (#803)
- [d1f74f0b](https://github.com/kubedb/apimachinery/commit/d1f74f0b) Update repository config (#804)



## [kubedb/pg-coordinator](https://github.com/kubedb/pg-coordinator)

### [v0.7.0](https://github.com/kubedb/pg-coordinator/releases/tag/v0.7.0)

- [e81fa81](https://github.com/kubedb/pg-coordinator/commit/e81fa81) Prepare for release v0.7.0 (#54)
- [7c49a84](https://github.com/kubedb/pg-coordinator/commit/7c49a84) Update kmodules.xyz/monitoring-agent-api (#53)
- [aed68ec](https://github.com/kubedb/pg-coordinator/commit/aed68ec) Update repository config (#52)
- [b052255](https://github.com/kubedb/pg-coordinator/commit/b052255) Fix: Raft log corrupted issue (#51)
- [9413347](https://github.com/kubedb/pg-coordinator/commit/9413347) Use DisableAnalytics flag from license (#50)
- [2fe1bfc](https://github.com/kubedb/pg-coordinator/commit/2fe1bfc) Update license-verifier (#49)
- [d6f9afd](https://github.com/kubedb/pg-coordinator/commit/d6f9afd) Support custom pod and controller labels (#48)
- [fb2b48c](https://github.com/kubedb/pg-coordinator/commit/fb2b48c) Postgres Server Restart If Sig-Killed (#44)
- [ab85e39](https://github.com/kubedb/pg-coordinator/commit/ab85e39) Print logs at Debug level
- [9b65232](https://github.com/kubedb/pg-coordinator/commit/9b65232) Log timestamp from zap logger used in raft (#47)
- [6d3eb77](https://github.com/kubedb/pg-coordinator/commit/6d3eb77) Update xorm dependency (#46)
- [b77df43](https://github.com/kubedb/pg-coordinator/commit/b77df43) Fix satori/go.uuid security vulnerability (#45)
- [3cd9cc4](https://github.com/kubedb/pg-coordinator/commit/3cd9cc4) Fix jwt-go security vulnerability (#43)
- [bd2356d](https://github.com/kubedb/pg-coordinator/commit/bd2356d) Fix: Postgres server single user mode start for bullseye image (#42)
- [0c8c18d](https://github.com/kubedb/pg-coordinator/commit/0c8c18d) Update dependencies to publish SiteInfo (#40)
- [06ee14c](https://github.com/kubedb/pg-coordinator/commit/06ee14c) Add support for Postgres version v14.0 (#41)



## [kubedb/tests](https://github.com/kubedb/tests)

### [v0.8.0](https://github.com/kubedb/tests/releases/tag/v0.8.0)

- [50f414a9](https://github.com/kubedb/tests/commit/50f414a9) Prepare for release v0.8.0 (#156)
- [25e5c5b6](https://github.com/kubedb/tests/commit/25e5c5b6) Update kmodules.xyz/monitoring-agent-api (#155)
- [951d17ca](https://github.com/kubedb/tests/commit/951d17ca) Update repository config (#154)
- [d0988abf](https://github.com/kubedb/tests/commit/d0988abf) Use DisableAnalytics flag from license (#153)
- [7aea8907](https://github.com/kubedb/tests/commit/7aea8907) Update license-verifier (#152)
- [637ae1a0](https://github.com/kubedb/tests/commit/637ae1a0) Support custom pod and controller labels (#151)
- [45223290](https://github.com/kubedb/tests/commit/45223290) Update dependencies (#150)
- [fcef9222](https://github.com/kubedb/tests/commit/fcef9222) Fix satori/go.uuid security vulnerability (#149)
- [1d308fc7](https://github.com/kubedb/tests/commit/1d308fc7) Fix jwt-go security vulnerability (#148)
- [9c764d48](https://github.com/kubedb/tests/commit/9c764d48) Fix jwt-go security vulnerability (#147)
- [cef34499](https://github.com/kubedb/tests/commit/cef34499) Fix jwt-go security vulnerability (#146)
- [2c1d6094](https://github.com/kubedb/tests/commit/2c1d6094) Update dependencies to publish SiteInfo (#145)
- [443c8390](https://github.com/kubedb/tests/commit/443c8390) Update dependencies to publish SiteInfo (#144)
- [5f71478f](https://github.com/kubedb/tests/commit/5f71478f) Update repository config (#143)



