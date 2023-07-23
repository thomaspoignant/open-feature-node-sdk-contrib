# Changelog

## [0.8.0](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/compare/flagd-provider-v0.7.7...flagd-provider-v0.8.0) (2023-07-23)


### ⚠ BREAKING CHANGES

* update OpenFeature SDK version ([#137](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/137))
* migrate to sdk 0.5.0 ([#114](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/114))
* add support for environment variables ([#107](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/107))
* update to js-sdk ([#108](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/108))
* Fix object parsing, remove HTTP ([#102](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/102))
* set openfeature sdk min version to 0.2.0 ([#93](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/93))

### 🐛 Bug Fixes

* Add buf dependency to release process ([#80](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/80)) ([f55bc20](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/f55bc20362c55441dc0a1d562b95957c8ab8c810))
* correct dependencies ([#182](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/182)) ([16cbe42](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/16cbe421d6255bd95a78c3914890a63adcce831e))
* **deps:** update dependency lru-cache to v8 ([#260](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/260)) ([e752c4a](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/e752c4a13efb856e35d424a0938ab83b898ec5b5))
* **deps:** update dependency lru-cache to v9 ([#321](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/321)) ([6e247ad](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/6e247ad2ba14d148ff99ff1d5283ccce5708e366))
* failure to create grpc credentials ([#431](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/431)) ([71379c8](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/71379c8d2b2a71f244aeff8ea0c83f1d593aacc9))
* fix ESM and web polyfills issue ([#201](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/201)) ([acee6e1](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/acee6e1817a7846251f456455a7218bf98efb00e))
* Fix object parsing, remove HTTP ([#102](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/102)) ([d6db366](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/d6db366a6ef7eb47230dcc6512f189a48c0b4ef2))
* handling zero value responses (previously undefined) ([#330](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/330)) ([2db7fa8](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/2db7fa825bd12d18d0804997e54d0b6aa3cd5a14))
* improved errors, handle undefined context props ([#110](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/110)) ([ea05b49](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/ea05b493096664b793fcdcf5c9a66493f25e72a9))
* module issues with types ([#212](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/212)) ([d2b97dd](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/d2b97dd24c952661ce08724a84e4b312860a9211))
* set openfeature sdk min version to 0.2.0 ([#93](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/93)) ([a733102](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/a733102f523f9289fdce356a342828cc2e020f48))


### ✨ New Features

* add standard flagd caching ([1e93b5f](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/1e93b5f3845beb5b4a523d1f9081a4c538200924))
* add standard flagd caching ([#218](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/218)) ([1e93b5f](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/1e93b5f3845beb5b4a523d1f9081a4c538200924))
* add support for environment variables ([#107](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/107)) ([fcc360b](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/fcc360bffa328a38594ae9dc30da339aaaed8b93))
* add Unix socket support ([#97](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/97)) ([326e65a](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/326e65ad1e518302b5a7b6a2498dec53c8c93a43))
* change flagD default port to 8013 ([#85](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/85)) ([9e26840](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/9e268406509a072b7561910fff6b8ab8bb0265c8))
* flagd provider ([#66](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/66)) ([9d6cb86](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/9d6cb868908264b8661ed95a207397ae67693527))
* flagd-web provider ([#142](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/142)) ([bd83124](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/bd8312418fbfab16d77a4ec069d3ff9452f7f744))
* migrate to sdk 0.5.0 ([#114](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/114)) ([f9e9a55](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/f9e9a55ad5a16e99bb169fdf1a8d11c959520f7b))
* update flagd provider to use float api ([#87](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/87)) ([9f871f1](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/9f871f1880022297b28601d472da2b4200325127))
* update to js-sdk ([#108](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/108)) ([60d6146](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/60d6146e30d3ca547e940c3ba441d80fd75d886d))


### 🧹 Chore

* **main:** release flagd-provider 0.7.6 ([#270](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/270)) ([0797d4e](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/0797d4e791ad359d7e22386c7e0ebebed69f2189))
* **main:** release flagd-provider 0.7.7 ([#346](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/346)) ([d2a3109](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/d2a310976ea09368ef3b4cafe0ea91b0b17cf364))
* migrate buf ([#456](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/456)) ([8568af1](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/8568af1e26f92f4d0e9a942b9fc3e001d919ef03))
* migrate to nx 16 ([#366](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/366)) ([7a9c201](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/7a9c201d16fd7f070a1bcd2e359487ba6e7b78d7))
* release main ([#103](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/103)) ([31f81e7](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/31f81e72c87c46096d92bd6bf8561cc3bc633aee))
* release main ([#111](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/111)) ([9af8e1c](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/9af8e1c3e8f72886c7eb8c4337359fd59b48452e))
* release main ([#115](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/115)) ([8e41930](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/8e41930f7bfd68c520d09a27f60aa911b9796474))
* release main ([#138](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/138)) ([f0b7704](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/f0b7704cfe26817e07d6591e41396768bdcd6f48))
* release main ([#163](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/163)) ([a56a280](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/a56a2804f5fada634dbb2b5115858832dfd6be4e))
* release main ([#183](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/183)) ([0867b93](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/0867b93d3016bb1a80be8c0f204725414c18b7ab))
* release main ([#195](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/195)) ([551eb86](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/551eb867981c60344b390c7a304d69c8aeb34526))
* release main ([#213](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/213)) ([be55c42](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/be55c42bce438f3b4d082a82c1d96d45808caac1))
* release main ([#227](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/227)) ([1390a81](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/1390a81ee27e92fb5323a7f826c6f28bd42300c4))
* release main ([#79](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/79)) ([4cc4a52](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/4cc4a521c25142474e8a2db0d9eccb0043686f41))
* release main ([#81](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/81)) ([0f59d72](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/0f59d72c92f82ececa39ac56c9563bcb1e3c90a1))
* release main ([#89](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/89)) ([31d1938](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/31d193825719504e18cceca93339e1242cd0fe9b))
* release main ([#94](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/94)) ([3bc8799](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/3bc87990f3db5dae27969b5eaa9c1ee77dbb7ef3))
* update OpenFeature SDK version ([#137](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/issues/137)) ([245f024](https://github.com/thomaspoignant/open-feature-node-sdk-contrib/commit/245f02441d62f7f42627174737943f1556a6a326))

## [0.7.7](https://github.com/open-feature/js-sdk-contrib/compare/flagd-provider-v0.7.6...flagd-provider-v0.7.7) (2023-07-03)


### 🧹 Chore

* migrate to nx 16 ([#366](https://github.com/open-feature/js-sdk-contrib/issues/366)) ([7a9c201](https://github.com/open-feature/js-sdk-contrib/commit/7a9c201d16fd7f070a1bcd2e359487ba6e7b78d7))


### 🐛 Bug Fixes

* **deps:** update dependency lru-cache to v9 ([#321](https://github.com/open-feature/js-sdk-contrib/issues/321)) ([6e247ad](https://github.com/open-feature/js-sdk-contrib/commit/6e247ad2ba14d148ff99ff1d5283ccce5708e366))
* failure to create grpc credentials ([#431](https://github.com/open-feature/js-sdk-contrib/issues/431)) ([71379c8](https://github.com/open-feature/js-sdk-contrib/commit/71379c8d2b2a71f244aeff8ea0c83f1d593aacc9))

## [0.7.6](https://github.com/open-feature/js-sdk-contrib/compare/flagd-provider-v0.7.5...flagd-provider-v0.7.6) (2023-04-25)


### 🐛 Bug Fixes

* **deps:** update dependency lru-cache to v8 ([#260](https://github.com/open-feature/js-sdk-contrib/issues/260)) ([e752c4a](https://github.com/open-feature/js-sdk-contrib/commit/e752c4a13efb856e35d424a0938ab83b898ec5b5))
* handling zero value responses (previously undefined) ([#330](https://github.com/open-feature/js-sdk-contrib/issues/330)) ([2db7fa8](https://github.com/open-feature/js-sdk-contrib/commit/2db7fa825bd12d18d0804997e54d0b6aa3cd5a14))

## [0.7.5](https://github.com/open-feature/js-sdk-contrib/compare/flagd-provider-v0.7.4...flagd-provider-v0.7.5) (2023-03-02)


### Features

* add standard flagd caching ([1e93b5f](https://github.com/open-feature/js-sdk-contrib/commit/1e93b5f3845beb5b4a523d1f9081a4c538200924))
* add standard flagd caching ([#218](https://github.com/open-feature/js-sdk-contrib/issues/218)) ([1e93b5f](https://github.com/open-feature/js-sdk-contrib/commit/1e93b5f3845beb5b4a523d1f9081a4c538200924))

## [0.7.4](https://github.com/open-feature/js-sdk-contrib/compare/flagd-provider-v0.7.3...flagd-provider-v0.7.4) (2023-01-19)


### Bug Fixes

* module issues with types ([#212](https://github.com/open-feature/js-sdk-contrib/issues/212)) ([d2b97dd](https://github.com/open-feature/js-sdk-contrib/commit/d2b97dd24c952661ce08724a84e4b312860a9211))

## [0.7.3](https://github.com/open-feature/js-sdk-contrib/compare/flagd-provider-v0.7.2...flagd-provider-v0.7.3) (2022-12-29)


### Bug Fixes

* fix ESM and web polyfills issue ([#201](https://github.com/open-feature/js-sdk-contrib/issues/201)) ([acee6e1](https://github.com/open-feature/js-sdk-contrib/commit/acee6e1817a7846251f456455a7218bf98efb00e))

## [0.7.2](https://github.com/open-feature/js-sdk-contrib/compare/flagd-provider-v0.7.1...flagd-provider-v0.7.2) (2022-12-09)


### Bug Fixes

* correct dependencies ([#182](https://github.com/open-feature/js-sdk-contrib/issues/182)) ([16cbe42](https://github.com/open-feature/js-sdk-contrib/commit/16cbe421d6255bd95a78c3914890a63adcce831e))

## [0.7.1](https://github.com/open-feature/js-sdk-contrib/compare/flagd-provider-v0.7.0...flagd-provider-v0.7.1) (2022-12-09)


### Miscellaneous Chores

* dependency updates

## [0.7.0](https://github.com/open-feature/js-sdk-contrib/compare/flagd-provider-v0.6.0...flagd-provider-v0.7.0) (2022-10-19)


### ⚠ BREAKING CHANGES

* update OpenFeature SDK version (#137)

### Miscellaneous Chores

* update OpenFeature SDK version ([#137](https://github.com/open-feature/js-sdk-contrib/issues/137)) ([245f024](https://github.com/open-feature/js-sdk-contrib/commit/245f02441d62f7f42627174737943f1556a6a326))

## [0.6.0](https://github.com/open-feature/js-sdk-contrib/compare/flagd-provider-v0.5.1...flagd-provider-v0.6.0) (2022-10-03)


### ⚠ BREAKING CHANGES

* migrate to sdk 0.5.0 (#114)

### Features

* migrate to sdk 0.5.0 ([#114](https://github.com/open-feature/js-sdk-contrib/issues/114)) ([f9e9a55](https://github.com/open-feature/js-sdk-contrib/commit/f9e9a55ad5a16e99bb169fdf1a8d11c959520f7b))

## [0.5.1](https://github.com/open-feature/js-sdk-contrib/compare/flagd-provider-v0.5.0...flagd-provider-v0.5.1) (2022-09-22)


### Bug Fixes

* improved errors, handle undefined context props ([#110](https://github.com/open-feature/js-sdk-contrib/issues/110)) ([ea05b49](https://github.com/open-feature/js-sdk-contrib/commit/ea05b493096664b793fcdcf5c9a66493f25e72a9))

## [0.5.0](https://github.com/open-feature/js-sdk-contrib/compare/flagd-provider-v0.4.0...flagd-provider-v0.5.0) (2022-09-20)


### ⚠ BREAKING CHANGES

* add support for environment variables (#107)
* update to js-sdk (#108)
* Fix object parsing, remove HTTP (#102)

### Features

* add support for environment variables ([#107](https://github.com/open-feature/js-sdk-contrib/issues/107)) ([fcc360b](https://github.com/open-feature/js-sdk-contrib/commit/fcc360bffa328a38594ae9dc30da339aaaed8b93))
* add Unix socket support ([#97](https://github.com/open-feature/js-sdk-contrib/issues/97)) ([326e65a](https://github.com/open-feature/js-sdk-contrib/commit/326e65ad1e518302b5a7b6a2498dec53c8c93a43))
* update to js-sdk ([#108](https://github.com/open-feature/js-sdk-contrib/issues/108)) ([60d6146](https://github.com/open-feature/js-sdk-contrib/commit/60d6146e30d3ca547e940c3ba441d80fd75d886d))


### Bug Fixes

* Fix object parsing, remove HTTP ([#102](https://github.com/open-feature/js-sdk-contrib/issues/102)) ([d6db366](https://github.com/open-feature/js-sdk-contrib/commit/d6db366a6ef7eb47230dcc6512f189a48c0b4ef2))

## [0.4.0](https://github.com/open-feature/js-sdk-contrib/compare/flagd-provider-v0.3.0...flagd-provider-v0.4.0) (2022-08-15)


### ⚠ BREAKING CHANGES

* set openfeature sdk min version to 0.2.0 (#93)

### Bug Fixes

* set openfeature sdk min version to 0.2.0 ([#93](https://github.com/open-feature/js-sdk-contrib/issues/93)) ([a733102](https://github.com/open-feature/js-sdk-contrib/commit/a733102f523f9289fdce356a342828cc2e020f48))

## [0.3.0](https://github.com/open-feature/js-sdk-contrib/compare/flagd-provider-v0.2.1...flagd-provider-v0.3.0) (2022-08-09)


### Features

* change flagD default port to 8013 ([#85](https://github.com/open-feature/js-sdk-contrib/issues/85)) ([9e26840](https://github.com/open-feature/js-sdk-contrib/commit/9e268406509a072b7561910fff6b8ab8bb0265c8))
* update flagd provider to use float api ([#87](https://github.com/open-feature/js-sdk-contrib/issues/87)) ([9f871f1](https://github.com/open-feature/js-sdk-contrib/commit/9f871f1880022297b28601d472da2b4200325127))

## [0.2.1](https://github.com/open-feature/js-sdk-contrib/compare/flagd-provider-v0.2.0...flagd-provider-v0.2.1) (2022-07-29)


### Bug Fixes

* Add buf dependency to release process ([#80](https://github.com/open-feature/js-sdk-contrib/issues/80)) ([f55bc20](https://github.com/open-feature/js-sdk-contrib/commit/f55bc20362c55441dc0a1d562b95957c8ab8c810))

## [0.2.0](https://github.com/open-feature/js-sdk-contrib/compare/flagd-provider-v0.1.0...flagd-provider-v0.2.0) (2022-07-27)


### Features

* flagd provider ([#66](https://github.com/open-feature/js-sdk-contrib/issues/66)) ([9d6cb86](https://github.com/open-feature/js-sdk-contrib/commit/9d6cb868908264b8661ed95a207397ae67693527))
