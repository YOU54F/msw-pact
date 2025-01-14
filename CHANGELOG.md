# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [3.0.1](https://github.com/pactflow/pact-msw-adapter/compare/v3.0.0...v3.0.1) (2024-12-10)


### Bug Fixes

* Fix the cleanup of expired request listeners ([264ac15](https://github.com/pactflow/pact-msw-adapter/commit/264ac1561a0b3ef3e4eb88e85406316723738e48))

## [3.0.0](https://github.com/pactflow/pact-msw-adapter/compare/v2.0.1...v3.0.0) (2023-11-09)


### ⚠ BREAKING CHANGES

* make compatible and consistent with msw v2
* update dependencies including msw to v2

* make compatible and consistent with msw v2 ([63c98f6](https://github.com/pactflow/pact-msw-adapter/commit/63c98f67d911ed391e60860ec203f6cd14fa8b22))
* update dependencies including msw to v2 ([37cf49d](https://github.com/pactflow/pact-msw-adapter/commit/37cf49d79b4e44a2d0a0ba796a60bd117f22b7fe))

### [2.0.1](https://github.com/pactflow/pact-msw-adapter/compare/v2.0.0...v2.0.1) (2023-11-07)


### Bug Fixes

* unref asyncTimeout; fixes open handle issue in jest ([0ee1485](https://github.com/pactflow/pact-msw-adapter/commit/0ee1485403038ac80b2af3bf941c00090fbb42dc))

## [2.0.0](https://github.com/pactflow/pact-msw-adapter/compare/v1.5.0...v2.0.0) (2023-07-11)


### ⚠ BREAKING CHANGES

* Deps/node engines >=16 (#94)

### Bug Fixes

* Deps/node engines >=16 ([#94](https://github.com/pactflow/pact-msw-adapter/issues/94)) ([4c83113](https://github.com/pactflow/pact-msw-adapter/commit/4c831134f6d04cbd74633e9678db924515b2dca4))

## [1.5.0](https://github.com/pactflow/pact-msw-adapter/compare/v1.4.0...v1.5.0) (2023-05-22)


### Features

* allow dynamic provider matching ([58de667](https://github.com/pactflow/pact-msw-adapter/commit/58de667ef172c8a3e827f57fd36abf88c34766cf))

## [1.4.0](https://github.com/pactflow/pact-msw-adapter/compare/v1.3.1...v1.4.0) (2023-05-17)


### Features

* Add option to set logger ([6d45541](https://github.com/pactflow/pact-msw-adapter/commit/6d4554158d4ef2671e88e556604319379659b5a2))

### [1.3.1](https://github.com/pactflow/pact-msw-adapter/compare/v1.3.0...v1.3.1) (2023-02-08)


### Bug Fixes

* Remove timestamp from pact contract file name ([6b48836](https://github.com/pactflow/pact-msw-adapter/commit/6b48836965d99374b9661f08b9d2a3f8485d777c))

## [1.3.0](https://github.com/pactflow/pact-msw-adapter/compare/v1.2.1...v1.3.0) (2022-10-06)


### Features

* Add client name/version into pact file ([1c8aa9a](https://github.com/pactflow/pact-msw-adapter/commit/1c8aa9a35898be4280c99859d795b29a219b3bc6))

### [1.2.1](https://github.com/pactflow/pact-msw-adapter/compare/v1.2.0...v1.2.1) (2022-07-15)


### Bug Fixes

* include headers on interactions requests ([c5a0cea](https://github.com/pactflow/pact-msw-adapter/commit/c5a0ceaf854d97ac6dfaf62b2c8d40231617a653))

## [1.2.0](https://github.com/pactflow/pact-msw-adapter/compare/v1.1.1...v1.2.0) (2022-06-01)


### Features

* add query to request in the pact file ([1473315](https://github.com/pactflow/pact-msw-adapter/commit/147331570aa37d4b70c06e12dac3039cfdccc4b1))


### Bug Fixes

* change type ([1cfd279](https://github.com/pactflow/pact-msw-adapter/commit/1cfd27921fd770a5e098255724d015eccad5b70b))

### [1.1.1](https://github.com/pactflow/pact-msw-adapter/compare/v1.1.0...v1.1.1) (2022-05-21)


### Bug Fixes

* Fix for Post Requests ([#42](https://github.com/pactflow/pact-msw-adapter/issues/42)) ([4885572](https://github.com/pactflow/pact-msw-adapter/commit/48855721055757a54ef7ed08c7d98f04ecce23f4))

## [1.1.0](https://github.com/pactflow/pact-msw-adapter/compare/v0.11.1...v1.1.0) (2022-04-22)


### Features

* (release): 1.0.0 ([25292a9](https://github.com/pactflow/pact-msw-adapter/commit/25292a9bb8542e904090ada53e5d1d6e0beba863))
* Worker examples ([#39](https://github.com/pactflow/pact-msw-adapter/issues/39)) ([3a5d499](https://github.com/pactflow/pact-msw-adapter/commit/3a5d4993a291c4384d90dac54a90719fb295424d))

## [1.0.0](https://github.com/pactflow/pact-msw-adapter/compare/v0.11.1...v1.0.0) (2022-04-22)


### Features

* Worker examples ([#39](https://github.com/pactflow/pact-msw-adapter/issues/39)) ([3a5d499](https://github.com/pactflow/pact-msw-adapter/commit/3a5d4993a291c4384d90dac54a90719fb295424d))

### [0.11.1](https://github.com/pactflow/pact-msw-adapter/compare/v0.10.4...v0.11.1) (2022-03-10)


### Features

* release 0.11.0 ([be152b3](https://github.com/pactflow/pact-msw-adapter/commit/be152b3c9fa5f6797e23f9fdc7d1e1ef0258f468))

### [0.10.4](https://github.com/pactflow/msw-pact-adapter/compare/v0.10.3...v0.10.4) (2022-03-10)


### Features

* rename to <toolName>-pact-adapter for consistency ([#37](https://github.com/pactflow/msw-pact-adapter/issues/37)) ([239883c](https://github.com/pactflow/msw-pact-adapter/commit/239883c07c26fb449b301d0ecf153f929f86b7a7))

### [0.10.3](https://github.com/pactflow/pact-msw-adapter/compare/v0.10.1...v0.10.3) (2022-03-10)


### Features

* 0.10.2 ([42ae30b](https://github.com/pactflow/pact-msw-adapter/commit/42ae30b5ee1162e56e20cb12403eb5dea3801a02))
* release 0.10.1 ([b3578a0](https://github.com/pactflow/pact-msw-adapter/commit/b3578a0e34e47556f47761d36039f468b31df3f9))

### [0.10.1](https://github.com/pactflow/pact-msw-adapter/compare/v0.9.2...v0.10.1) (2022-03-10)


### Features

* release as pact-msw-adapter ([#36](https://github.com/pactflow/pact-msw-adapter/issues/36)) ([1850d33](https://github.com/pactflow/pact-msw-adapter/commit/1850d330fdb8625012079a26284ff229a52c075d))

### [0.9.2](https://github.com/pactflow/pact-msw-adapter/compare/v0.8.4...v0.9.2) (2022-03-08)


### Features

* release 0.9.1 ([8655ebe](https://github.com/pactflow/pact-msw-adapter/commit/8655ebec99822982a01a4e5ca9b6377fcf212280))

### [0.8.4](https://github.com/pactflow/pact-msw-adapter/compare/v0.8.2...v0.8.4) (2022-03-07)


### Features

* setup ci and release flow ([5a1e05d](https://github.com/pactflow/pact-msw-adapter/commit/5a1e05d1356a53996b845df7d52c0cbf4eb27e35))

### 0.8.2 (2022-03-07)
