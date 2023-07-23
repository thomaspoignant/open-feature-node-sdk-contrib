# Changelog

## [0.6.0](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/compare/go-feature-flag-provider-v0.5.12...go-feature-flag-provider-v0.6.0) (2023-07-23)


### ⚠ BREAKING CHANGES

* update OpenFeature SDK version ([#137](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/137))
* migrate to sdk 0.5.0 ([#114](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/114))
* update to js-sdk ([#108](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/108))
* set openfeature sdk min version to 0.2.0 ([#93](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/93))

### 🐛 Bug Fixes

* add test ([#71](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/71)) ([080fc4b](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/080fc4b3c926728361ad34d6763df7bc2d5ab023))
* comment typo ([#315](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/315)) ([d9130c8](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/d9130c8e058676babb51464e4a912641032a4ee1))
* correct dependencies ([#182](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/182)) ([16cbe42](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/16cbe421d6255bd95a78c3914890a63adcce831e))
* fix ESM and web polyfills issue ([#201](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/201)) ([acee6e1](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/acee6e1817a7846251f456455a7218bf98efb00e))
* go-feature-flag provider add authentication header ([#317](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/317)) ([eaf6458](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/eaf6458d1d66578dfba052f5abfce45516429008))
* go-feature-flag provider this.apiKey is undefined ([#319](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/319)) ([ff60b6f](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/ff60b6fd988d5e6a479589b5e320221a3a807775))
* handling zero value responses (previously undefined) ([#330](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/330)) ([2db7fa8](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/2db7fa825bd12d18d0804997e54d0b6aa3cd5a14))
* module issues with types ([#212](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/212)) ([d2b97dd](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/d2b97dd24c952661ce08724a84e4b312860a9211))
* Peer dependencies error ([#77](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/77)) ([3e4ab86](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/3e4ab861c1a8d94be50bf2e2445044d820d9164b))
* set openfeature sdk min version to 0.2.0 ([#93](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/93)) ([a733102](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/a733102f523f9289fdce356a342828cc2e020f48))
* shell scripts in templates ([#73](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/73)) ([89c8cfe](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/89c8cfe981348376995f50ca757299077249544e))
* use copy-anything for deepClone to be compatible with nodeJS before v17 ([#429](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/429)) ([b4a7ffe](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/b4a7ffe0dce5073046ec6d5c6dc08e1eafb31b3f))


### ✨ New Features

* add LRU TTL cache for GO Feature Flag Provider ([#411](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/411)) ([1a76aec](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/1a76aec01350cfab7c3324dcc5e15ea4e90e1462))
* flagd-web provider ([#142](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/142)) ([bd83124](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/bd8312418fbfab16d77a4ec069d3ff9452f7f744))
* Go feature flag provider ([#64](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/64)) ([f32d3b0](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/f32d3b0d8ae9203c6922cb8c6a6a2a291f5f9068))
* migrate to sdk 0.5.0 ([#114](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/114)) ([f9e9a55](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/f9e9a55ad5a16e99bb169fdf1a8d11c959520f7b))
* Return CACHED reason when using cache ([#425](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/425)) ([f285dab](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/f285dab379f98c3f1d70e144d5599847fe6cf0f5))
* Support apiKey for GO Feature Flag relay proxy v1.7.0 ([#310](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/310)) ([ba0b2a2](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/ba0b2a283cbdfb462d385fe0aef97ea7c4decec8))
* support metadata (go feature flag provider) ([#410](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/410)) ([9aadf74](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/9aadf7492e3bca54db5ec648249c3f63858066fe))
* update to js-sdk ([#108](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/108)) ([60d6146](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/60d6146e30d3ca547e940c3ba441d80fd75d886d))


### 🧹 Chore

* correct publish executor ([#378](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/378)) ([395ed18](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/395ed186de8811ae249f087821fdbdf8899c19f2))
* **main:** release go-feature-flag-provider 0.5.10 ([#414](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/414)) ([e026c9d](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/e026c9dcef49556f6b19d1ee65cd81c407665a25))
* **main:** release go-feature-flag-provider 0.5.11 ([#426](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/426)) ([9966281](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/9966281fcb72ac2d2a1eebcebd967f2ed664dc2a))
* **main:** release go-feature-flag-provider 0.5.12 ([#432](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/432)) ([302150c](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/302150c12a0f32f624328fee3bb2a182f70244ed))
* **main:** release go-feature-flag-provider 0.5.5 ([#311](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/311)) ([f4cddd5](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/f4cddd5e835e9f1d7756738ad3732896ea010214))
* **main:** release go-feature-flag-provider 0.5.6 ([#316](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/316)) ([c903e0f](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/c903e0f20faa38acbf3b0cb8de22709a5da9befd))
* **main:** release go-feature-flag-provider 0.5.7 ([#318](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/318)) ([0294c7d](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/0294c7d20b71135c3e250cbf09984e8872f8db42))
* **main:** release go-feature-flag-provider 0.5.8 ([#320](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/320)) ([acc0c01](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/acc0c018329693387bcf3104106eabb13a85756d))
* **main:** release go-feature-flag-provider 0.5.9 ([#338](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/338)) ([7a589fa](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/7a589fa2097c933baa248c89622a241f2ded6674))
* migrate to nx 16 ([#366](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/366)) ([7a9c201](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/7a9c201d16fd7f070a1bcd2e359487ba6e7b78d7))
* release main ([#103](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/103)) ([31f81e7](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/31f81e72c87c46096d92bd6bf8561cc3bc633aee))
* release main ([#115](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/115)) ([8e41930](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/8e41930f7bfd68c520d09a27f60aa911b9796474))
* release main ([#138](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/138)) ([f0b7704](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/f0b7704cfe26817e07d6591e41396768bdcd6f48))
* release main ([#163](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/163)) ([a56a280](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/a56a2804f5fada634dbb2b5115858832dfd6be4e))
* release main ([#183](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/183)) ([0867b93](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/0867b93d3016bb1a80be8c0f204725414c18b7ab))
* release main ([#195](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/195)) ([551eb86](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/551eb867981c60344b390c7a304d69c8aeb34526))
* release main ([#213](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/213)) ([be55c42](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/be55c42bce438f3b4d082a82c1d96d45808caac1))
* release main ([#70](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/70)) ([333f9f0](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/333f9f035d20c60be79371ea973481e63196a4fe))
* release main ([#72](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/72)) ([b424678](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/b4246781b1efb2b86ca43e82d8c9bfe3943657cc))
* release main ([#74](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/74)) ([0b85175](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/0b851755a2e071a9db30655840dd625679eb8726))
* release main ([#78](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/78)) ([7db7d31](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/7db7d310e015ee8e4bbbb2e2a860879dd1a27f0d))
* release main ([#94](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/94)) ([3bc8799](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/3bc87990f3db5dae27969b5eaa9c1ee77dbb7ef3))
* update OpenFeature SDK version ([#137](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/137)) ([245f024](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/245f02441d62f7f42627174737943f1556a6a326))


### 🔄 Refactoring

* update go feature flag provider to use not deprecated context transformer ([#92](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/92)) ([42adc78](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/42adc7881fcc792fcfa625ada2ced8a5ed7a67f4))

## [0.5.12](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.5.11...go-feature-flag-provider-v0.5.12) (2023-06-28)


### 🐛 Bug Fixes

* use copy-anything for deepClone to be compatible with nodeJS before v17 ([#429](https://github.com/open-feature/js-sdk-contrib/issues/429)) ([b4a7ffe](https://github.com/open-feature/js-sdk-contrib/commit/b4a7ffe0dce5073046ec6d5c6dc08e1eafb31b3f))

## [0.5.11](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.5.10...go-feature-flag-provider-v0.5.11) (2023-06-27)


### ✨ New Features

* Return CACHED reason when using cache ([#425](https://github.com/open-feature/js-sdk-contrib/issues/425)) ([f285dab](https://github.com/open-feature/js-sdk-contrib/commit/f285dab379f98c3f1d70e144d5599847fe6cf0f5))

## [0.5.10](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.5.9...go-feature-flag-provider-v0.5.10) (2023-06-16)


### ✨ New Features

* add LRU TTL cache for GO Feature Flag Provider ([#411](https://github.com/open-feature/js-sdk-contrib/issues/411)) ([1a76aec](https://github.com/open-feature/js-sdk-contrib/commit/1a76aec01350cfab7c3324dcc5e15ea4e90e1462))
* support metadata (go feature flag provider) ([#410](https://github.com/open-feature/js-sdk-contrib/issues/410)) ([9aadf74](https://github.com/open-feature/js-sdk-contrib/commit/9aadf7492e3bca54db5ec648249c3f63858066fe))

## [0.5.9](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.5.8...go-feature-flag-provider-v0.5.9) (2023-05-16)


### 🐛 Bug Fixes

* handling zero value responses (previously undefined) ([#330](https://github.com/open-feature/js-sdk-contrib/issues/330)) ([2db7fa8](https://github.com/open-feature/js-sdk-contrib/commit/2db7fa825bd12d18d0804997e54d0b6aa3cd5a14))


### 🧹 Chore

* correct publish executor ([#378](https://github.com/open-feature/js-sdk-contrib/issues/378)) ([395ed18](https://github.com/open-feature/js-sdk-contrib/commit/395ed186de8811ae249f087821fdbdf8899c19f2))
* migrate to nx 16 ([#366](https://github.com/open-feature/js-sdk-contrib/issues/366)) ([7a9c201](https://github.com/open-feature/js-sdk-contrib/commit/7a9c201d16fd7f070a1bcd2e359487ba6e7b78d7))

## [0.5.8](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.5.7...go-feature-flag-provider-v0.5.8) (2023-04-08)


### 🐛 Bug Fixes

* go-feature-flag provider this.apiKey is undefined ([#319](https://github.com/open-feature/js-sdk-contrib/issues/319)) ([ff60b6f](https://github.com/open-feature/js-sdk-contrib/commit/ff60b6fd988d5e6a479589b5e320221a3a807775))

## [0.5.7](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.5.6...go-feature-flag-provider-v0.5.7) (2023-04-08)


### 🐛 Bug Fixes

* go-feature-flag provider add authentication header ([#317](https://github.com/open-feature/js-sdk-contrib/issues/317)) ([eaf6458](https://github.com/open-feature/js-sdk-contrib/commit/eaf6458d1d66578dfba052f5abfce45516429008))

## [0.5.6](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.5.5...go-feature-flag-provider-v0.5.6) (2023-04-08)


### 🐛 Bug Fixes

* comment typo ([#315](https://github.com/open-feature/js-sdk-contrib/issues/315)) ([d9130c8](https://github.com/open-feature/js-sdk-contrib/commit/d9130c8e058676babb51464e4a912641032a4ee1))

## [0.5.5](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.5.4...go-feature-flag-provider-v0.5.5) (2023-04-07)


### ✨ New Features

* Support apiKey for GO Feature Flag relay proxy v1.7.0 ([#310](https://github.com/open-feature/js-sdk-contrib/issues/310)) ([ba0b2a2](https://github.com/open-feature/js-sdk-contrib/commit/ba0b2a283cbdfb462d385fe0aef97ea7c4decec8))

## [0.5.4](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.5.3...go-feature-flag-provider-v0.5.4) (2023-01-19)


### Bug Fixes

* module issues with types ([#212](https://github.com/open-feature/js-sdk-contrib/issues/212)) ([d2b97dd](https://github.com/open-feature/js-sdk-contrib/commit/d2b97dd24c952661ce08724a84e4b312860a9211))

## [0.5.3](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.5.2...go-feature-flag-provider-v0.5.3) (2022-12-29)


### Bug Fixes

* fix ESM and web polyfills issue ([#201](https://github.com/open-feature/js-sdk-contrib/issues/201)) ([acee6e1](https://github.com/open-feature/js-sdk-contrib/commit/acee6e1817a7846251f456455a7218bf98efb00e))

## [0.5.2](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.5.1...go-feature-flag-provider-v0.5.2) (2022-12-09)


### Bug Fixes

* correct dependencies ([#182](https://github.com/open-feature/js-sdk-contrib/issues/182)) ([16cbe42](https://github.com/open-feature/js-sdk-contrib/commit/16cbe421d6255bd95a78c3914890a63adcce831e))

## [0.5.1](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.5.0...go-feature-flag-provider-v0.5.1) (2022-12-09)


### Miscellaneous Chores

* dependency updates

## [0.5.0](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.4.0...go-feature-flag-provider-v0.5.0) (2022-10-19)


### ⚠ BREAKING CHANGES

* update OpenFeature SDK version (#137)

### Miscellaneous Chores

* update OpenFeature SDK version ([#137](https://github.com/open-feature/js-sdk-contrib/issues/137)) ([245f024](https://github.com/open-feature/js-sdk-contrib/commit/245f02441d62f7f42627174737943f1556a6a326))

## [0.4.0](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.3.0...go-feature-flag-provider-v0.4.0) (2022-10-03)


### ⚠ BREAKING CHANGES

* migrate to sdk 0.5.0 (#114)

### Features

* migrate to sdk 0.5.0 ([#114](https://github.com/open-feature/js-sdk-contrib/issues/114)) ([f9e9a55](https://github.com/open-feature/js-sdk-contrib/commit/f9e9a55ad5a16e99bb169fdf1a8d11c959520f7b))

## [0.3.0](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.2.0...go-feature-flag-provider-v0.3.0) (2022-09-20)


### ⚠ BREAKING CHANGES

* update to js-sdk (#108)

### Features

* update to js-sdk ([#108](https://github.com/open-feature/js-sdk-contrib/issues/108)) ([60d6146](https://github.com/open-feature/js-sdk-contrib/commit/60d6146e30d3ca547e940c3ba441d80fd75d886d))

## [0.2.0](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.1.3...go-feature-flag-provider-v0.2.0) (2022-08-15)


### ⚠ BREAKING CHANGES

* set openfeature sdk min version to 0.2.0 (#93)

### Bug Fixes

* set openfeature sdk min version to 0.2.0 ([#93](https://github.com/open-feature/js-sdk-contrib/issues/93)) ([a733102](https://github.com/open-feature/js-sdk-contrib/commit/a733102f523f9289fdce356a342828cc2e020f48))

## [0.1.3](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.1.2...go-feature-flag-provider-v0.1.3) (2022-07-23)


### Bug Fixes

* Peer dependencies error ([#77](https://github.com/open-feature/js-sdk-contrib/issues/77)) ([3e4ab86](https://github.com/open-feature/js-sdk-contrib/commit/3e4ab861c1a8d94be50bf2e2445044d820d9164b))

## [0.1.2](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.1.1...go-feature-flag-provider-v0.1.2) (2022-07-21)


### Bug Fixes

* shell scripts in templates ([#73](https://github.com/open-feature/js-sdk-contrib/issues/73)) ([89c8cfe](https://github.com/open-feature/js-sdk-contrib/commit/89c8cfe981348376995f50ca757299077249544e))

## [0.1.1](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.1.0...go-feature-flag-provider-v0.1.1) (2022-07-21)


### Bug Fixes

* add test ([#71](https://github.com/open-feature/js-sdk-contrib/issues/71)) ([080fc4b](https://github.com/open-feature/js-sdk-contrib/commit/080fc4b3c926728361ad34d6763df7bc2d5ab023))

## [0.1.0](https://github.com/open-feature/js-sdk-contrib/compare/go-feature-flag-provider-v0.0.1...go-feature-flag-provider-v0.1.0) (2022-07-21)


### Features

* Go feature flag provider ([#64](https://github.com/open-feature/js-sdk-contrib/issues/64)) ([f32d3b0](https://github.com/open-feature/js-sdk-contrib/commit/f32d3b0d8ae9203c6922cb8c6a6a2a291f5f9068))
