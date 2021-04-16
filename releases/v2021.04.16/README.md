# KubeDB v2021.04.16 (2021-04-16)


## [kubedb/apimachinery](https://github.com/kubedb/apimachinery)

### [v0.18.0](https://github.com/kubedb/apimachinery/releases/tag/v0.18.0)

- [fdf2681b](https://github.com/kubedb/apimachinery/commit/fdf2681b) Remove some panics from MongoDB (#734)
- [4bc52e52](https://github.com/kubedb/apimachinery/commit/4bc52e52) Add Ops Request Phase `Pending` (#736)
- [62e6b324](https://github.com/kubedb/apimachinery/commit/62e6b324) Add timeout for MongoDBOpsrequest (#738)
- [15a029cc](https://github.com/kubedb/apimachinery/commit/15a029cc) Check for all Stash CRDs before starting Start controller (#740)
- [b9da5117](https://github.com/kubedb/apimachinery/commit/b9da5117) Add backup condition constants for ops requests (#737)
- [989d8200](https://github.com/kubedb/apimachinery/commit/989d8200) Remove Panic from MariaDB (#731)
- [b7b2a28c](https://github.com/kubedb/apimachinery/commit/b7b2a28c) Remove panic from Postgres (#739)
- [264c0872](https://github.com/kubedb/apimachinery/commit/264c0872) Add IsIP helper
- [feebf1d8](https://github.com/kubedb/apimachinery/commit/feebf1d8) Add pod identity for cluster configuration (#729)
- [1b58e82b](https://github.com/kubedb/apimachinery/commit/1b58e82b) Add SecurityContext to ElasticsearchVersion CRD (#733)
- [b3c20afc](https://github.com/kubedb/apimachinery/commit/b3c20afc) Update for release Stash@v2021.04.07 (#735)
- [ced2341f](https://github.com/kubedb/apimachinery/commit/ced2341f) Return default cert-secret name if missing (#730)
- [ecf77001](https://github.com/kubedb/apimachinery/commit/ecf77001) Rename Features to SecurityContext in Postgres Version Spec (#732)
- [e5917a15](https://github.com/kubedb/apimachinery/commit/e5917a15) Rename RunAsAny to RunAsAnyNonRoot in PostgresVersion
- [5060058c](https://github.com/kubedb/apimachinery/commit/5060058c) Add Custom UID Options for Postgres (#728)
- [ed221fe1](https://github.com/kubedb/apimachinery/commit/ed221fe1) Fix spelling



## [kubedb/cli](https://github.com/kubedb/cli)

### [v0.18.0](https://github.com/kubedb/cli/releases/tag/v0.18.0)

- [a1a424ba](https://github.com/kubedb/cli/commit/a1a424ba) Prepare for release v0.18.0 (#598)
- [c8bec973](https://github.com/kubedb/cli/commit/c8bec973) Fix spelling



## [kubedb/mariadb](https://github.com/kubedb/mariadb)

### [v0.2.0](https://github.com/kubedb/mariadb/releases/tag/v0.2.0)

- [db6efa46](https://github.com/kubedb/mariadb/commit/db6efa46) Prepare for release v0.2.0 (#65)
- [01575e35](https://github.com/kubedb/mariadb/commit/01575e35) Updated validator for requireSSL field. (#61)
- [585f1873](https://github.com/kubedb/mariadb/commit/585f1873) Introduced MariaDB init-container (#62)
- [821c3688](https://github.com/kubedb/mariadb/commit/821c3688) Updated MustCertSecretName to GetCertSecretName (#64)
- [5d41c58a](https://github.com/kubedb/mariadb/commit/5d41c58a) Add POD_IP env variable (#63)
- [11e56c19](https://github.com/kubedb/mariadb/commit/11e56c19) Use license-verifier v0.8.1
- [f7d6c516](https://github.com/kubedb/mariadb/commit/f7d6c516) Use license verifier v0.8.0
- [3cfc4979](https://github.com/kubedb/mariadb/commit/3cfc4979) Update license verifier
- [60e8e7a3](https://github.com/kubedb/mariadb/commit/60e8e7a3) Update stash make targets (#60)
- [9424f4be](https://github.com/kubedb/mariadb/commit/9424f4be) Fix spelling



## [kubedb/memcached](https://github.com/kubedb/memcached)

### [v0.11.0](https://github.com/kubedb/memcached/releases/tag/v0.11.0)

- [4f391d75](https://github.com/kubedb/memcached/commit/4f391d75) Prepare for release v0.11.0 (#293)
- [294fb730](https://github.com/kubedb/memcached/commit/294fb730) Use license-verifier v0.8.1
- [717a5c06](https://github.com/kubedb/memcached/commit/717a5c06) Use license verifier v0.8.0
- [37f7bba6](https://github.com/kubedb/memcached/commit/37f7bba6) Update license verifier
- [4a6fea4d](https://github.com/kubedb/memcached/commit/4a6fea4d) Fix spelling



## [kubedb/postgres](https://github.com/kubedb/postgres)

### [v0.18.0](https://github.com/kubedb/postgres/releases/tag/v0.18.0)

- [e0b70d83](https://github.com/kubedb/postgres/commit/e0b70d83) Prepare for release v0.18.0 (#489)
- [a3ffea16](https://github.com/kubedb/postgres/commit/a3ffea16) remove panic from postgres (#488)
- [09adb390](https://github.com/kubedb/postgres/commit/09adb390) Remove wait-group from postgres operator (#487)
- [ae8b87da](https://github.com/kubedb/postgres/commit/ae8b87da) Use license-verifier v0.8.1
- [77f220b8](https://github.com/kubedb/postgres/commit/77f220b8) Update KubeDB api (#486)
- [b0234c4b](https://github.com/kubedb/postgres/commit/b0234c4b) Add Custom-UID Support for Debian Images (#485)
- [fdf4d2df](https://github.com/kubedb/postgres/commit/fdf4d2df) Use license verifier v0.8.0
- [dd59f9b1](https://github.com/kubedb/postgres/commit/dd59f9b1) Update license verifier
- [43fd0c33](https://github.com/kubedb/postgres/commit/43fd0c33) Update stash make targets (#484)
- [8632e4c5](https://github.com/kubedb/postgres/commit/8632e4c5) Fix spelling



## [kubedb/tests](https://github.com/kubedb/tests)

### [v0.3.0](https://github.com/kubedb/tests/releases/tag/v0.3.0)

- [1d230e5](https://github.com/kubedb/tests/commit/1d230e5) Prepare for release v0.3.0 (#115)
- [a2148b0](https://github.com/kubedb/tests/commit/a2148b0) Rename `MustCertSecretName` to `GetCertSecretName` (#113)



