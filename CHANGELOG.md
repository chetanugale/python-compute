# Changelog

## [0.5.0](https://www.github.com/googleapis/python-compute/compare/v0.4.2...v0.5.0) (2021-08-09)


### ⚠ BREAKING CHANGES

* uint64/int64 fields accept ints instead of strings (#92)

### Features

* add always_use_jwt_access ([4d673cf](https://www.github.com/googleapis/python-compute/commit/4d673cf06ea2aa3957a0514fed68885c86a338b0))


### Bug Fixes

* fix required query params handling (closes [#12](https://www.github.com/googleapis/python-compute/issues/12)) ([4d673cf](https://www.github.com/googleapis/python-compute/commit/4d673cf06ea2aa3957a0514fed68885c86a338b0))
* uint64/int64 fields accept ints instead of strings ([#92](https://www.github.com/googleapis/python-compute/issues/92)) ([4d673cf](https://www.github.com/googleapis/python-compute/commit/4d673cf06ea2aa3957a0514fed68885c86a338b0))

### Documentation
* adding samples to start/stop/reset operations ([#75](https://www.github.com/googleapis/python-compute/issues/75)) ([0df87a9](https://www.github.com/googleapis/python-compute/commit/0df87a9cc65c9a68c2ba6ae6bea2f6906626d488))


### Miscellaneous Chores

* release as 0.4.3 ([#89](https://www.github.com/googleapis/python-compute/issues/89)) ([fbc1a28](https://www.github.com/googleapis/python-compute/commit/fbc1a2869932883d0e7e8e498e16d2273fb25048))

### [0.4.2](https://www.github.com/googleapis/python-compute/compare/v0.4.1...v0.4.2) (2021-07-26)

### Bug Fixes

* **deps:** pin 'google-{api,cloud}-core', 'google-auth' to allow 2.x versions ([#81](https://www.github.com/googleapis/python-compute/issues/81)) ([1163f2b](https://www.github.com/googleapis/python-compute/commit/1163f2bb15f0e042bdd9562a31ad2ac7f39e3536))




* samples docstring and comments update ([#69](https://www.github.com/googleapis/python-compute/issues/69)) ([2d53eb1](https://www.github.com/googleapis/python-compute/commit/2d53eb1839a8751945ba7cdf12991f2970893df2))
* adding samples for default values ([#64](https://www.github.com/googleapis/python-compute/issues/64)) ([553e389](https://www.github.com/googleapis/python-compute/commit/553e3891179c2719a57d398ffc26c1459945bf4d))


### Miscellaneous Chores

* release as 0.4.2 ([#84](https://www.github.com/googleapis/python-compute/issues/84)) ([dc77c0c](https://www.github.com/googleapis/python-compute/commit/dc77c0c55eef9cc1c2e515137fe66b4d4afca77e))
* Kokoro uses separate project for concurent tests. ([#83](https://www.github.com/googleapis/python-compute/issues/83)) ([40afb33](https://www.github.com/googleapis/python-compute/commit/40afb333a963717853f70410a7a08eda5492418c))


### [0.4.1](https://www.github.com/googleapis/python-compute/compare/v0.4.0...v0.4.1) (2021-06-16)


### Bug Fixes

* exclude docs and tests from package ([#65](https://www.github.com/googleapis/python-compute/issues/65)) ([c157bf5](https://www.github.com/googleapis/python-compute/commit/c157bf507227d7c1c815d5e236e4d710e12fbdec))

## [0.4.0](https://www.github.com/googleapis/python-compute/compare/v0.3.0...v0.4.0) (2021-06-07)


### Features

* Adding code samples and tests for them ([#55](https://www.github.com/googleapis/python-compute/issues/55)) ([14cd352](https://www.github.com/googleapis/python-compute/commit/14cd352079281ddde3602597334e3c88c942ed30))
* Raise GoogleAPICallError on REST response errors ([01db23b](https://www.github.com/googleapis/python-compute/commit/01db23bc0af3ab30bfb5ad8205446ae49417f0f1))
* Re-generated to pick up changes from googleapis-discovery with latest fixes ([#60](https://www.github.com/googleapis/python-compute/issues/60)) ([01db23b](https://www.github.com/googleapis/python-compute/commit/01db23bc0af3ab30bfb5ad8205446ae49417f0f1))
* remove support for google-api-core < 1.28.0 ([01db23b](https://www.github.com/googleapis/python-compute/commit/01db23bc0af3ab30bfb5ad8205446ae49417f0f1))

## [0.3.0](https://www.github.com/googleapis/python-compute/compare/v0.2.1...v0.3.0) (2021-05-10)


### Features

* Regenerate newest version of python-compute with field presence support ([#49](https://www.github.com/googleapis/python-compute/issues/49)) ([6181460](https://www.github.com/googleapis/python-compute/commit/61814609cdd8f9d26ba2b4f121e91dab4c565849))

### [0.2.1](https://www.github.com/googleapis/python-compute/compare/v0.2.0...v0.2.1) (2021-02-26)


### Bug Fixes

* ignore unknown fields in response ([#25](https://www.github.com/googleapis/python-compute/issues/25)) ([a8c37b4](https://www.github.com/googleapis/python-compute/commit/a8c37b4b9dacc54e00a7ad3850e7c9c12ef477cf))

## [0.2.0](https://www.github.com/googleapis/python-compute/compare/v0.1.0...v0.2.0) (2021-02-11)


### Features

* run synthtool to pick up mtls feature ([#6](https://www.github.com/googleapis/python-compute/issues/6)) ([3abec21](https://www.github.com/googleapis/python-compute/commit/3abec21a1d5b1384779c48b899f23ba18ca0ddb3))


### Bug Fixes

* don't use integers for enums in json encoding ([a3685b5](https://www.github.com/googleapis/python-compute/commit/a3685b5a03a75256d2d00b89dcc8fda34596edde))
* fix body encoding for rest transport  ([#17](https://www.github.com/googleapis/python-compute/issues/17)) ([a3685b5](https://www.github.com/googleapis/python-compute/commit/a3685b5a03a75256d2d00b89dcc8fda34596edde))
* regenerate the client lib ([#9](https://www.github.com/googleapis/python-compute/issues/9)) ([b9def52](https://www.github.com/googleapis/python-compute/commit/b9def52a47067804d5b79e867fb3ff895f8f4c21))
* set development status classifier to alpha ([#2](https://www.github.com/googleapis/python-compute/issues/2)) ([54814f8](https://www.github.com/googleapis/python-compute/commit/54814f8ad15b8f8dff051c7c7819bc4a7b8e099f))
* stabilize order of query_params ([a3685b5](https://www.github.com/googleapis/python-compute/commit/a3685b5a03a75256d2d00b89dcc8fda34596edde))
* update paging implementation to handle unconventional pagination ([a3685b5](https://www.github.com/googleapis/python-compute/commit/a3685b5a03a75256d2d00b89dcc8fda34596edde))

## 0.1.0 (2021-01-08)


### Features

* generate v1 ([53f9a3d](https://www.github.com/googleapis/python-compute/commit/53f9a3d6f14ef45b5bc3e38a48e3fa17059591eb))
