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



