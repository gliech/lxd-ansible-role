## [2.1.2](https://github.com/gliech/lxd-ansible-role/compare/v2.1.1...v2.1.2) (2024-03-16)


### Bug Fixes

* new lxd features networks.zones and storage.buckets in default and molecule configs ([10272d9](https://github.com/gliech/lxd-ansible-role/commit/10272d967222dd127bf102b6c80353e76d0b1e37))
* remove unneeded dependency on jq as `lxd init --dump` does not expose volatile configs anymore ([5019fa4](https://github.com/gliech/lxd-ansible-role/commit/5019fa42482052ad8d87ee06de596edc5a71f58c))
* switch license to gpl ([0651787](https://github.com/gliech/lxd-ansible-role/commit/0651787716375c8f82be5dc025c605531ed4002a))


### Continuous Integration

* use mose recent pipeline version ([dbabec4](https://github.com/gliech/lxd-ansible-role/commit/dbabec432703d872f687b0049012c4874be88ef4))

## [2.1.1](https://github.com/gliech/lxd-ansible-role/compare/v2.1.0...v2.1.1) (2021-11-15)


### Bug Fixes

* revert 6f5b3f1 ([8091376](https://github.com/gliech/lxd-ansible-role/commit/80913764c7b440837fabab58a4c13dd4a4c93703))

# [2.1.0](https://github.com/gliech/lxd-ansible-role/compare/v2.0.0...v2.1.0) (2021-11-13)


### Features

* lxd_client_cert directory ([6f5b3f1](https://github.com/gliech/lxd-ansible-role/commit/6f5b3f110fa8662f58d2122d679afcb810e56071))

# [2.0.0](https://github.com/gliech/lxd-ansible-role/compare/v1.0.0...v2.0.0) (2021-11-05)


### Bug Fixes

* filter lxd config with jq to exclude volatile values ([7144f99](https://github.com/gliech/lxd-ansible-role/commit/7144f9925833836add76b12b1dd87402b33873c8))


### Continuous Integration

* **fix:** install ansible-galaxy dependencies globally ([f063d00](https://github.com/gliech/lxd-ansible-role/commit/f063d0089911b8e743da8e609aa881afe1c7a1a0))


### BREAKING CHANGES

* filter lxd config with jq to exclude volatile values

# 1.0.0 (2021-10-29)


### Features

* initial commit ([8c20c1e](https://github.com/gliech/lxd-ansible-role/commit/8c20c1e345bcec99d00267961694f2dd355fa050))


### Tests

* **molecule:** remove verify step ([41f7f1f](https://github.com/gliech/lxd-ansible-role/commit/41f7f1f17e4a552fade00665b0ab15238b543ecc))
