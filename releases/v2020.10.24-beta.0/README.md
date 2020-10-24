# KubeDB v2020.10.24-beta.0 (2020-10-24)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.14.0-beta.4](https://github.com/kubedb/apimachinery/releases/tag/v0.14.0-beta.4)

- [61b26532](https://github.com/kubedb/apimachinery/commit/61b26532) Add MySQL constants (#633)
- [42888647](https://github.com/kubedb/apimachinery/commit/42888647) Update Kubernetes v1.18.9 dependencies (#632)
- [a57a7df5](https://github.com/kubedb/apimachinery/commit/a57a7df5) Set prx as ProxySQL short code (#631)
- [282992ea](https://github.com/kubedb/apimachinery/commit/282992ea) Update for release Stash@v2020.10.21 (#630)
- [5f17e1b4](https://github.com/kubedb/apimachinery/commit/5f17e1b4) Set default CA secret name even if the SSL is disabled. (#624)
- [c3710b61](https://github.com/kubedb/apimachinery/commit/c3710b61) Add host functions for different components of MongoDB (#625)
- [028d939d](https://github.com/kubedb/apimachinery/commit/028d939d) Refine api (#629)
- [4f4cfb3b](https://github.com/kubedb/apimachinery/commit/4f4cfb3b) Update Kubernetes v1.18.9 dependencies (#626)
- [47eaa486](https://github.com/kubedb/apimachinery/commit/47eaa486) Add MongoDBCustomConfigFile constant
- [5201c39b](https://github.com/kubedb/apimachinery/commit/5201c39b) Update MySQL ops request custom config api (#623)
- [06c2076f](https://github.com/kubedb/apimachinery/commit/06c2076f) Rename redis ConfigMapName to ConfigSecretName
- [0d4040b4](https://github.com/kubedb/apimachinery/commit/0d4040b4) API refinement (#622)
- [2eabe4c2](https://github.com/kubedb/apimachinery/commit/2eabe4c2) Update Kubernetes v1.18.9 dependencies (#621)
- [ac3ff1a6](https://github.com/kubedb/apimachinery/commit/ac3ff1a6) Handle halted condition (#620)
- [8ed26973](https://github.com/kubedb/apimachinery/commit/8ed26973) Update constants for Elasticsearch conditions (#618)
- [97c32f71](https://github.com/kubedb/apimachinery/commit/97c32f71) Use core/v1 ConditionStatus (#619)
- [304c48b8](https://github.com/kubedb/apimachinery/commit/304c48b8) Update Kubernetes v1.18.9 dependencies (#617)
- [a841401e](https://github.com/kubedb/apimachinery/commit/a841401e) Fix StatefulSet controller (#616)
- [517285ea](https://github.com/kubedb/apimachinery/commit/517285ea) Add spec.init.initialized field (#615)
- [057d3aef](https://github.com/kubedb/apimachinery/commit/057d3aef) Implement ReplicasAreReady (#614)
- [32105113](https://github.com/kubedb/apimachinery/commit/32105113) Update appcatalog dependency
- [34bf142e](https://github.com/kubedb/apimachinery/commit/34bf142e) Update swagger.json
- [7d9095af](https://github.com/kubedb/apimachinery/commit/7d9095af) Fix build (#613)
- [ad7988a8](https://github.com/kubedb/apimachinery/commit/ad7988a8) Fix build
- [0cf6469d](https://github.com/kubedb/apimachinery/commit/0cf6469d) Switch kubedb apiVersion to v1alpha2 (#612)
- [fd3131cd](https://github.com/kubedb/apimachinery/commit/fd3131cd) Add Volume Expansion and Configuration for MySQL OpsRequest (#607)
- [fd285012](https://github.com/kubedb/apimachinery/commit/fd285012) Add `alias` in the name of MongoDB server certificates (#611)
- [e562def9](https://github.com/kubedb/apimachinery/commit/e562def9) Remove GetMonitoringVendor method
- [a71f9b7e](https://github.com/kubedb/apimachinery/commit/a71f9b7e) Fix build
- [c97abe0d](https://github.com/kubedb/apimachinery/commit/c97abe0d) Update monitoring api dependency (#610)
- [d6070fc7](https://github.com/kubedb/apimachinery/commit/d6070fc7) Remove deprecated fields for monitoring (#609)
- [8d2f606a](https://github.com/kubedb/apimachinery/commit/8d2f606a) Add framework support for conditions (#608)
- [a74ea7a4](https://github.com/kubedb/apimachinery/commit/a74ea7a4) Bring back mysql ops spec StatefulSetOrdinal field
- [bda2d85a](https://github.com/kubedb/apimachinery/commit/bda2d85a) Add VerticalAutoscaler type (#606)
- [b9b22a35](https://github.com/kubedb/apimachinery/commit/b9b22a35) Add MySQL constant (#604)
- [2b887957](https://github.com/kubedb/apimachinery/commit/2b887957) Fix typo
- [c31cd2fd](https://github.com/kubedb/apimachinery/commit/c31cd2fd) Update ops request enumerations
- [41083a9d](https://github.com/kubedb/apimachinery/commit/41083a9d) Revise ops request apis (#603)
- [acfb1564](https://github.com/kubedb/apimachinery/commit/acfb1564) Revise api conditions (#602)
- [5c12de3a](https://github.com/kubedb/apimachinery/commit/5c12de3a) Update DB condition types and phases (#598)
- [f27cb720](https://github.com/kubedb/apimachinery/commit/f27cb720) Write data restore completion event using dynamic client (#601)
- [60ada14c](https://github.com/kubedb/apimachinery/commit/60ada14c) Update Kubernetes v1.18.9 dependencies (#600)
- [5779a5d7](https://github.com/kubedb/apimachinery/commit/5779a5d7) Update for release Stash@v2020.09.29 (#599)
- [86121dad](https://github.com/kubedb/apimachinery/commit/86121dad) Update Kubernetes v1.18.9 dependencies (#597)
- [da9fbe59](https://github.com/kubedb/apimachinery/commit/da9fbe59) Add DB conditions
- [7399d13f](https://github.com/kubedb/apimachinery/commit/7399d13f) Rename ES root-cert to ca-cert (#594)
- [1cd75609](https://github.com/kubedb/apimachinery/commit/1cd75609) Remove spec.paused & deprecated fields DB crds (#596)
- [9c85f9f1](https://github.com/kubedb/apimachinery/commit/9c85f9f1) Use `status.conditions` to handle database initialization (#593)
- [87e8e58b](https://github.com/kubedb/apimachinery/commit/87e8e58b) Update Kubernetes v1.18.9 dependencies (#595)
- [32206db2](https://github.com/kubedb/apimachinery/commit/32206db2) Add helper methods for MySQL (#592)
- [10aca81a](https://github.com/kubedb/apimachinery/commit/10aca81a) Rename client node to ingest node (#583)
- [d8bbd5ec](https://github.com/kubedb/apimachinery/commit/d8bbd5ec) Update repository config (#591)
- [4d51a066](https://github.com/kubedb/apimachinery/commit/4d51a066) Update repository config (#590)
- [5905c2cb](https://github.com/kubedb/apimachinery/commit/5905c2cb) Update Kubernetes v1.18.9 dependencies (#589)
- [3dc3d970](https://github.com/kubedb/apimachinery/commit/3dc3d970) Update Kubernetes v1.18.3 dependencies (#588)
- [53b42277](https://github.com/kubedb/apimachinery/commit/53b42277) Add event recorder in controller struct (#587)



## [kubedb/mysql-replication-mode-detector](https://github.com/kubedb/mysql-replication-mode-detector)

### [v0.1.0-beta.4](https://github.com/kubedb/mysql-replication-mode-detector/releases/tag/v0.1.0-beta.4)

- [557e8f7](https://github.com/kubedb/mysql-replication-mode-detector/commit/557e8f7) Prepare for release v0.1.0-beta.4 (#70)
- [4dd885a](https://github.com/kubedb/mysql-replication-mode-detector/commit/4dd885a) Update KubeDB api (#69)
- [dc0ed39](https://github.com/kubedb/mysql-replication-mode-detector/commit/dc0ed39) Update Kubernetes v1.18.9 dependencies (#68)
- [f49a1d1](https://github.com/kubedb/mysql-replication-mode-detector/commit/f49a1d1) Update Kubernetes v1.18.9 dependencies (#65)
- [306235a](https://github.com/kubedb/mysql-replication-mode-detector/commit/306235a) Update KubeDB api (#64)
- [3c9e99a](https://github.com/kubedb/mysql-replication-mode-detector/commit/3c9e99a) Update KubeDB api (#63)
- [974a940](https://github.com/kubedb/mysql-replication-mode-detector/commit/974a940) Update KubeDB api (#62)
- [8521462](https://github.com/kubedb/mysql-replication-mode-detector/commit/8521462) Update Kubernetes v1.18.9 dependencies (#61)
- [38f7a4c](https://github.com/kubedb/mysql-replication-mode-detector/commit/38f7a4c) Update KubeDB api (#60)
- [a7b7c87](https://github.com/kubedb/mysql-replication-mode-detector/commit/a7b7c87) Update KubeDB api (#59)
- [daa02dd](https://github.com/kubedb/mysql-replication-mode-detector/commit/daa02dd) Update KubeDB api (#58)
- [341b6b6](https://github.com/kubedb/mysql-replication-mode-detector/commit/341b6b6) Add tls config (#40)
- [04161c8](https://github.com/kubedb/mysql-replication-mode-detector/commit/04161c8) Update KubeDB api (#57)
- [fdd705d](https://github.com/kubedb/mysql-replication-mode-detector/commit/fdd705d) Update Kubernetes v1.18.9 dependencies (#56)
- [22cb410](https://github.com/kubedb/mysql-replication-mode-detector/commit/22cb410) Update KubeDB api (#55)
- [11b1758](https://github.com/kubedb/mysql-replication-mode-detector/commit/11b1758) Update KubeDB api (#54)
- [9df3045](https://github.com/kubedb/mysql-replication-mode-detector/commit/9df3045) Update KubeDB api (#53)
- [6557f92](https://github.com/kubedb/mysql-replication-mode-detector/commit/6557f92) Update KubeDB api (#52)
- [43c3694](https://github.com/kubedb/mysql-replication-mode-detector/commit/43c3694) Update Kubernetes v1.18.9 dependencies (#51)
- [511e974](https://github.com/kubedb/mysql-replication-mode-detector/commit/511e974) Publish docker images to ghcr.io (#50)
- [093a995](https://github.com/kubedb/mysql-replication-mode-detector/commit/093a995) Update KubeDB api (#49)
- [49c07e9](https://github.com/kubedb/mysql-replication-mode-detector/commit/49c07e9) Update KubeDB api (#48)
- [91ead1c](https://github.com/kubedb/mysql-replication-mode-detector/commit/91ead1c) Update KubeDB api (#47)
- [45956b4](https://github.com/kubedb/mysql-replication-mode-detector/commit/45956b4) Update KubeDB api (#46)
- [a6c57a7](https://github.com/kubedb/mysql-replication-mode-detector/commit/a6c57a7) Update KubeDB api (#45)
- [8a2fd20](https://github.com/kubedb/mysql-replication-mode-detector/commit/8a2fd20) Update KubeDB api (#44)
- [be63987](https://github.com/kubedb/mysql-replication-mode-detector/commit/be63987) Update KubeDB api (#43)
- [f33220a](https://github.com/kubedb/mysql-replication-mode-detector/commit/f33220a) Update KubeDB api (#42)
- [46b7d44](https://github.com/kubedb/mysql-replication-mode-detector/commit/46b7d44) Update KubeDB api (#41)
- [c151070](https://github.com/kubedb/mysql-replication-mode-detector/commit/c151070) Update KubeDB api (#38)
- [7a04763](https://github.com/kubedb/mysql-replication-mode-detector/commit/7a04763) Update KubeDB api (#37)
- [4367ef5](https://github.com/kubedb/mysql-replication-mode-detector/commit/4367ef5) Update KubeDB api (#36)
- [6bc4f1c](https://github.com/kubedb/mysql-replication-mode-detector/commit/6bc4f1c) Update Kubernetes v1.18.9 dependencies (#35)
- [fdaff01](https://github.com/kubedb/mysql-replication-mode-detector/commit/fdaff01) Update KubeDB api (#34)
- [087170a](https://github.com/kubedb/mysql-replication-mode-detector/commit/087170a) Update KubeDB api (#33)
- [127efe7](https://github.com/kubedb/mysql-replication-mode-detector/commit/127efe7) Update Kubernetes v1.18.9 dependencies (#32)
- [1df3573](https://github.com/kubedb/mysql-replication-mode-detector/commit/1df3573) Move constant to apimachinery repo (#24)
- [74b41b0](https://github.com/kubedb/mysql-replication-mode-detector/commit/74b41b0) Update repository config (#31)
- [b0932a7](https://github.com/kubedb/mysql-replication-mode-detector/commit/b0932a7) Update repository config (#30)
- [8e9c235](https://github.com/kubedb/mysql-replication-mode-detector/commit/8e9c235) Update Kubernetes v1.18.9 dependencies (#29)
- [8f61ebc](https://github.com/kubedb/mysql-replication-mode-detector/commit/8f61ebc) Update Kubernetes v1.18.3 dependencies (#28)



## [kubedb/pg-leader-election](https://github.com/kubedb/pg-leader-election)

### [v0.2.0-beta.4](https://github.com/kubedb/pg-leader-election/releases/tag/v0.2.0-beta.4)

- [46c6bf5](https://github.com/kubedb/pg-leader-election/commit/46c6bf5) Update KubeDB api (#36)
- [e662de8](https://github.com/kubedb/pg-leader-election/commit/e662de8) Update Kubernetes v1.18.9 dependencies (#35)
- [f4167b5](https://github.com/kubedb/pg-leader-election/commit/f4167b5) Update KubeDB api (#34)
- [e1d3199](https://github.com/kubedb/pg-leader-election/commit/e1d3199) Update Kubernetes v1.18.9 dependencies (#33)
- [933baa7](https://github.com/kubedb/pg-leader-election/commit/933baa7) Update KubeDB api (#32)
- [3edfc19](https://github.com/kubedb/pg-leader-election/commit/3edfc19) Update KubeDB api (#31)
- [cef0f38](https://github.com/kubedb/pg-leader-election/commit/cef0f38) Update KubeDB api (#30)
- [319a452](https://github.com/kubedb/pg-leader-election/commit/319a452) Update Kubernetes v1.18.9 dependencies (#29)
- [7d82228](https://github.com/kubedb/pg-leader-election/commit/7d82228) Update KubeDB api (#28)
- [bd6617b](https://github.com/kubedb/pg-leader-election/commit/bd6617b) Update Kubernetes v1.18.9 dependencies (#27)
- [465c6a9](https://github.com/kubedb/pg-leader-election/commit/465c6a9) Update KubeDB api (#26)
- [e90b2ba](https://github.com/kubedb/pg-leader-election/commit/e90b2ba) Update Kubernetes v1.18.9 dependencies (#25)
- [2feb7bc](https://github.com/kubedb/pg-leader-election/commit/2feb7bc) Update repository config (#24)
- [32ca246](https://github.com/kubedb/pg-leader-election/commit/32ca246) Update Kubernetes v1.18.9 dependencies (#23)
- [03fe9f9](https://github.com/kubedb/pg-leader-election/commit/03fe9f9) Update Kubernetes v1.18.3 dependencies (#22)



