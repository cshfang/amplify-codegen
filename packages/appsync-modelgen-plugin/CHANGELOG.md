# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.27.2](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.27.1...@aws-amplify/appsync-modelgen-plugin@1.27.2) (2021-08-18)


### Bug Fixes

* **appsync-modelgen-plugin:** dart model internal constructor with no internal fields ([#210](https://github.com/aws-amplify/amplify-codegen/issues/210)) ([4d743b9](https://github.com/aws-amplify/amplify-codegen/commit/4d743b9cf29545591ae7dae0cf13619a1dac9513))
* **appsync-modelgen-plugin:** remove warning and uuid check for java ([#198](https://github.com/aws-amplify/amplify-codegen/issues/198)) ([6f932d0](https://github.com/aws-amplify/amplify-codegen/commit/6f932d006fb7bd3c19e280acf0d05c3d05f0ae0d))





## [1.27.1](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.27.0...@aws-amplify/appsync-modelgen-plugin@1.27.1) (2021-07-28)


### Bug Fixes

* **appsync-modelgen-plugin:** fix init when no read-only fields found ([#205](https://github.com/aws-amplify/amplify-codegen/issues/205)) ([7265f3a](https://github.com/aws-amplify/amplify-codegen/commit/7265f3a4214e107b88346181329c30c64dbca5a0))





# [1.27.0](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.26.0...@aws-amplify/appsync-modelgen-plugin@1.27.0) (2021-07-12)


### Features

* **appsync-modelgen-plugin:** expose readonly labels to model ts output ([#185](https://github.com/aws-amplify/amplify-codegen/issues/185)) ([368a7c0](https://github.com/aws-amplify/amplify-codegen/commit/368a7c002e3aa56d2dcb03764490eead6df3b9bb))





# [1.26.0](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.25.0...@aws-amplify/appsync-modelgen-plugin@1.26.0) (2021-06-30)


### Features

* **codegen:** iOS index directive support ([#174](https://github.com/aws-amplify/amplify-codegen/issues/174)) ([abb966c](https://github.com/aws-amplify/amplify-codegen/commit/abb966c647b08537564f85314a4266a5cbe33ffd))
* **modelgen:** ios - emit provider in [@auth](https://github.com/auth) rules ([#184](https://github.com/aws-amplify/amplify-codegen/issues/184)) ([f9c1b1a](https://github.com/aws-amplify/amplify-codegen/commit/f9c1b1af89a837ed4b705e21085f6c8402e94283))





# [1.25.0](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.24.0...@aws-amplify/appsync-modelgen-plugin@1.25.0) (2021-06-02)


### Bug Fixes

* **appsync-modelgen-plugin:** include auth rule provider in the Java models, if available ([#168](https://github.com/aws-amplify/amplify-codegen/issues/168)) ([69cd61a](https://github.com/aws-amplify/amplify-codegen/commit/69cd61a4fe111d4950896c0debfb64415e14b512))
* **appsync-modelgen-plugin:** skip query/mutation/sub types ([#180](https://github.com/aws-amplify/amplify-codegen/issues/180)) ([aa0dbb3](https://github.com/aws-amplify/amplify-codegen/commit/aa0dbb31e9ebe285ec643ef98335021561dd2168))


### Features

* **modelgen:** ios - support public/private [@auth](https://github.com/auth) rules ([#181](https://github.com/aws-amplify/amplify-codegen/issues/181)) ([a649136](https://github.com/aws-amplify/amplify-codegen/commit/a6491366e84c9b7ef07da0e9678d6ad1194e88d7))





# [1.24.0](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.23.1...@aws-amplify/appsync-modelgen-plugin@1.24.0) (2021-05-25)


### Bug Fixes

* **appsync-modelgen-plugin:** restore the old init if timestamp disabled ([#177](https://github.com/aws-amplify/amplify-codegen/issues/177)) ([f923e14](https://github.com/aws-amplify/amplify-codegen/commit/f923e144e9cf51f904d792a5c01ceffca685d0ea))


### Features

* **modelgen:** add timestamp fields createdAt & updatedAt for [@model](https://github.com/model) ([#114](https://github.com/aws-amplify/amplify-codegen/issues/114)) ([f611e94](https://github.com/aws-amplify/amplify-codegen/commit/f611e94ef8cbd37cf8e8f356df83adcb9a8d3465))





## [1.23.1](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.23.0...@aws-amplify/appsync-modelgen-plugin@1.23.1) (2021-03-31)


### Bug Fixes

* **modelgen:** revert not adding ID field automatically ([4a3c000](https://github.com/aws-amplify/amplify-codegen/commit/4a3c000adac2be10cc5c648d2d83461b24e35816))





# [1.23.0](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.22.10...@aws-amplify/appsync-modelgen-plugin@1.23.0) (2021-03-29)


### Bug Fixes

* **modelgen:** match the error message in test ([115a311](https://github.com/aws-amplify/amplify-codegen/commit/115a31182ff3695caa5d651efb908fbdbd38867a))
* **modelgen:** throw error when id field is not present on models ([d19a317](https://github.com/aws-amplify/amplify-codegen/commit/d19a3179bee56cb40774684d5eeae536ba70ce0b))


### Features

* **dart-modelgen:** change the naming pattern for classType ([#115](https://github.com/aws-amplify/amplify-codegen/issues/115)) ([8dfa6a6](https://github.com/aws-amplify/amplify-codegen/commit/8dfa6a64cef62e996300d60a8a9c19691326dc79))





## [1.22.10](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.22.9...@aws-amplify/appsync-modelgen-plugin@1.22.10) (2021-02-25)


### Bug Fixes

* **@aws-amplify/appsync-modelgen-plugin:** JS targetName for hasOne ([#93](https://github.com/aws-amplify/amplify-codegen/issues/93)) ([3a5c4a5](https://github.com/aws-amplify/amplify-codegen/commit/3a5c4a5e020ee3444c775dfee93547353ce0ed8c))





## [1.22.9](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.22.8...@aws-amplify/appsync-modelgen-plugin@1.22.9) (2021-02-22)

**Note:** Version bump only for package @aws-amplify/appsync-modelgen-plugin





## [1.22.8](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.22.7...@aws-amplify/appsync-modelgen-plugin@1.22.8) (2021-02-15)


### Bug Fixes

* **amplify-flutter:** correctly serialize empty model lists ([0b724ee](https://github.com/aws-amplify/amplify-codegen/commit/0b724eee6b1bf23c67381c7c4923b51c3a0179ef))
* **modelgen-dart:** rename test model called TemporalTime to avoid conflicts with dart type ([aa72032](https://github.com/aws-amplify/amplify-codegen/commit/aa720325bd37bced33e589445145823a62ab824e))
* **modelgen-dart-optionals-fix:** fix rendering optionals in dart modelgen ([a64177f](https://github.com/aws-amplify/amplify-codegen/commit/a64177f0bdd5fe151b64e72fdd045f3544a6430e))
* **modelgen-flutter:** correctly handle nullable strings in dart toString ([434c024](https://github.com/aws-amplify/amplify-codegen/commit/434c024236871aaef5338593eff1649d85a4ada7))
* **modelgen-flutter:** correctly handle nullable strings in dart toString ([76e1ac6](https://github.com/aws-amplify/amplify-codegen/commit/76e1ac6d048d18d8dc23a2f2a4b0d4d8dc17d499))
* **modelgen-flutter:** Fix Optional ([d335b17](https://github.com/aws-amplify/amplify-codegen/commit/d335b17ec7e10ed4c0974940974603400d898855))
* **modelgen-java:** change float type mapping to double ([5e7f0a7](https://github.com/aws-amplify/amplify-codegen/commit/5e7f0a77a55de9142b61780752d8e47f22b42e6e))
* **modelgen-java:** change float type mapping to double ([fa1da80](https://github.com/aws-amplify/amplify-codegen/commit/fa1da80f032b7f95e3274cc03c52b5323e821245))





## [1.22.7](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.22.6...@aws-amplify/appsync-modelgen-plugin@1.22.7) (2021-02-10)


### Bug Fixes

* **appsync-modelgen-plugin:** change the time native type mapping and tostring method ([3d0d852](https://github.com/aws-amplify/amplify-codegen/commit/3d0d852a189938ddaa9fc282ce79732950605918))
* **modelgen:** add additional param to query fields ([0ce8cf3](https://github.com/aws-amplify/amplify-codegen/commit/0ce8cf387e70497cb7f2d23ee59a94f4da009b39))
* **modelgen-android:** add additional param to query fields ([46485a9](https://github.com/aws-amplify/amplify-codegen/commit/46485a93d7f2964a4b56d1418fbd7a6459a24769))
* **modelgen-flutter:** change the time native type mapping and tostring method ([526839d](https://github.com/aws-amplify/amplify-codegen/commit/526839d724d5d3bd8dcf07f2a52b024d0b82afa5))





## [1.22.6](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.22.4...@aws-amplify/appsync-modelgen-plugin@1.22.6) (2021-02-05)


### Bug Fixes

* **patch-release:** override previous patch release ([f2fe6e7](https://github.com/aws-amplify/amplify-codegen/commit/f2fe6e7bc3afa9a5fc634292564b9a97bf6bbc04))





## [1.22.4](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.22.3...@aws-amplify/appsync-modelgen-plugin@1.22.4) (2020-12-17)


### Bug Fixes

* **appsync-modelgen-plugin:** add get modeltype method in model provider ([b3daebb](https://github.com/aws-amplify/amplify-codegen/commit/b3daebb5b1425ca51fe6f85ff671960d6696510a))
* **appsync-modelgen-plugin:** generate correct output for field/enum w/o list or nullable ([129ed4c](https://github.com/aws-amplify/amplify-codegen/commit/129ed4c79adf7b9c89da53c14bf0ba024b3b57d9))
* **modelgen:** add targetName in hasOne relation ([16ff6c3](https://github.com/aws-amplify/amplify-codegen/commit/16ff6c3992ef3cd5c94a5ba016d127106ef34a5d))





## [1.22.3](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.22.2...@aws-amplify/appsync-modelgen-plugin@1.22.3) (2020-12-11)


### Bug Fixes

* **modelgen:** reduce the @types/node dependency to 12.12.6 ([e2a6047](https://github.com/aws-amplify/amplify-codegen/commit/e2a60475a62d1c6c981601d8de2a79d7ddc69ca3))





## [1.22.2](https://github.com/aws-amplify/amplify-codegen/compare/@aws-amplify/appsync-modelgen-plugin@1.22.1...@aws-amplify/appsync-modelgen-plugin@1.22.2) (2020-12-04)

**Note:** Version bump only for package @aws-amplify/appsync-modelgen-plugin





## [1.22.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.22.0...amplify-codegen-appsync-model-plugin@1.22.1) (2020-12-03)



## 4.37.1 (2020-12-02)


### Bug Fixes

* **amplify-codegen-appsync-model-plugin:** address feedback from flutter team(Nov 28) ([#6004](https://github.com/aws-amplify/amplify-cli/issues/6004)) ([b624e0f](https://github.com/aws-amplify/amplify-cli/commit/b624e0fff58659d0aeb13bc3e79b437071295aa3))





# [1.22.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.21.1...amplify-codegen-appsync-model-plugin@1.22.0) (2020-11-26)


### Bug Fixes

* snapshot for dart modelgen ([#5953](https://github.com/aws-amplify/amplify-cli/issues/5953)) ([83777ee](https://github.com/aws-amplify/amplify-cli/commit/83777ee5bf9bb4b532669d7927078db489d72975))



# 4.36.0 (2020-11-24)


### Features

* **amplify-codegen-appsync-model-plugin:** add appsync dart visitor … ([#5937](https://github.com/aws-amplify/amplify-cli/issues/5937)) ([28168ad](https://github.com/aws-amplify/amplify-cli/commit/28168ad25c341c038bfd13d7ca54b1b7bd74adc7))





## [1.21.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.20.10...amplify-codegen-appsync-model-plugin@1.21.1) (2020-11-22)

**Note:** Version bump only for package amplify-codegen-appsync-model-plugin





# 1.21.0 (2020-11-22)


### Bug Fixes

* ** amplify-codegen-appsync-model-plugin:** field name errors ([#3055](https://github.com/aws-amplify/amplify-cli/issues/3055)) ([cde1bc0](https://github.com/aws-amplify/amplify-cli/commit/cde1bc0806693d4a3a00806b01ef56d6cc90cbe7))
* **amplify-codegen:** use Java Long for AWSTimestamp ([#3615](https://github.com/aws-amplify/amplify-cli/issues/3615)) ([051b2fb](https://github.com/aws-amplify/amplify-cli/commit/051b2fb4de7266d950af8a51170f30b43d0d9b50)), closes [#3593](https://github.com/aws-amplify/amplify-cli/issues/3593)
* **amplify-codegen-appsync-model-plugin:**  Support Embeddable Types for iOS  ([#4545](https://github.com/aws-amplify/amplify-cli/issues/4545)) ([bb51678](https://github.com/aws-amplify/amplify-cli/commit/bb51678c589e2b09f8c72af68ed5a6aef448a6cb))
* **amplify-codegen-appsync-model-plugin:** add additional scalars ([#2919](https://github.com/aws-amplify/amplify-cli/issues/2919)) ([4521f67](https://github.com/aws-amplify/amplify-cli/commit/4521f675ce735df1b5ce824e4cec9001ea414781))
* **amplify-codegen-appsync-model-plugin:** add Amplify extension to ios ([4a97971](https://github.com/aws-amplify/amplify-cli/commit/4a97971b7cae61891998ce29a2558e2c8c1a647f))
* **amplify-codegen-appsync-model-plugin:** add auth directive info ([#3050](https://github.com/aws-amplify/amplify-cli/issues/3050)) ([9951402](https://github.com/aws-amplify/amplify-cli/commit/9951402777b047277e6e05c6cb84fea92c238e82))
* **amplify-codegen-appsync-model-plugin:** Add delimiter in Android `toString` output ([#4463](https://github.com/aws-amplify/amplify-cli/issues/4463)) ([395ee16](https://github.com/aws-amplify/amplify-cli/commit/395ee16372ca285aa5d5ab868f69416478339dd4))
* **amplify-codegen-appsync-model-plugin:** add field level [@auth](https://github.com/auth) process ([#5543](https://github.com/aws-amplify/amplify-cli/issues/5543)) ([1340343](https://github.com/aws-amplify/amplify-cli/commit/1340343c18e2a155bdb35321a2915d910f1f851e))
* **amplify-codegen-appsync-model-plugin:** add missing packages ([aaab38e](https://github.com/aws-amplify/amplify-cli/commit/aaab38e4456c15a00c61e0e00dc940ee7d7aea01))
* **amplify-codegen-appsync-model-plugin:** add ownerField to modelgen… ([#5455](https://github.com/aws-amplify/amplify-cli/issues/5455)) ([763f4af](https://github.com/aws-amplify/amplify-cli/commit/763f4af9238729894e5c95eba298d3c1b08a33db))
* **amplify-codegen-appsync-model-plugin:** add toString in hashCode ([5b74dfa](https://github.com/aws-amplify/amplify-cli/commit/5b74dfa0b0badc9a6f4d8eb8f1bbdc03e3819ecc))
* **amplify-codegen-appsync-model-plugin:** builder to exclude connection ([6b78f3d](https://github.com/aws-amplify/amplify-cli/commit/6b78f3d91545ef8933759b2e0ea44dc45571383e))
* **amplify-codegen-appsync-model-plugin:** DataStore Array Support ([#5327](https://github.com/aws-amplify/amplify-cli/issues/5327)) ([c88bee1](https://github.com/aws-amplify/amplify-cli/commit/c88bee1a4eed9aafca0e764fb2867176eed1c8e2)), closes [#5139](https://github.com/aws-amplify/amplify-cli/issues/5139)
* **amplify-codegen-appsync-model-plugin:** fix android models ([#2800](https://github.com/aws-amplify/amplify-cli/issues/2800)) ([cc96a05](https://github.com/aws-amplify/amplify-cli/commit/cc96a0557a385d89af9235148c56455f715a8731))
* **amplify-codegen-appsync-model-plugin:** fix connection keyname issue ([e3e52b3](https://github.com/aws-amplify/amplify-cli/commit/e3e52b3cddfc30961a486b43ee7e14f4b02c2e36))
* **amplify-codegen-appsync-model-plugin:** fix nullable lists ([#5450](https://github.com/aws-amplify/amplify-cli/issues/5450)) ([ec02076](https://github.com/aws-amplify/amplify-cli/commit/ec02076e9a4aab119a8a85e729b19fb4727607f4))
* **amplify-codegen-appsync-model-plugin:** fix typo in swift model gen ([#3256](https://github.com/aws-amplify/amplify-cli/issues/3256)) ([c5109ba](https://github.com/aws-amplify/amplify-cli/commit/c5109baf5f9b47e91ab19bc5f5c7a0e4e3089adf))
* **amplify-codegen-appsync-model-plugin:** generate nullable types for list ([#5493](https://github.com/aws-amplify/amplify-cli/issues/5493)) ([8b5043c](https://github.com/aws-amplify/amplify-cli/commit/8b5043c9e26ecb157ea3159e4e13dae097215301))
* **amplify-codegen-appsync-model-plugin:** refactor the build step in java modelgen ([#5500](https://github.com/aws-amplify/amplify-cli/issues/5500)) ([95838c7](https://github.com/aws-amplify/amplify-cli/commit/95838c71c340584314bd3502219234c7de114719))
* **amplify-codegen-appsync-model-plugin:** revert changes of adding ownerField for implicit cases for [@auth](https://github.com/auth) ([#5682](https://github.com/aws-amplify/amplify-cli/issues/5682)) ([85c9c93](https://github.com/aws-amplify/amplify-cli/commit/85c9c931408cc9ac3bd93f36481181829b882753))
* add owner field if owner auth is included in auth rules ([#5335](https://github.com/aws-amplify/amplify-cli/issues/5335)) ([2200f51](https://github.com/aws-amplify/amplify-cli/commit/2200f51c70ffa6c3fe88efa6b563e962668da3e0))
* bug in CopyofBuilder class with no nullable and non nullable fields ([#5108](https://github.com/aws-amplify/amplify-cli/issues/5108)) ([646435a](https://github.com/aws-amplify/amplify-cli/commit/646435adf35ab057f8c19b35eb86bab077a36a80))
* **amplify-codegen-appsync-model-plugin:** include enums in JS exports ([#2805](https://github.com/aws-amplify/amplify-cli/issues/2805)) ([cac07aa](https://github.com/aws-amplify/amplify-cli/commit/cac07aa2b36a65b4f86bffb82ccfacf270ee7d49))
* **amplify-codegen-appsync-model-plugin:** revert lazy load ([3323a31](https://github.com/aws-amplify/amplify-cli/commit/3323a31f936dbe3c870244e1dee31291fcfbf6a4))
* **amplify-codegen-appsync-model-plugin:** support non-codeable types ([#3226](https://github.com/aws-amplify/amplify-cli/issues/3226)) ([9c5b7e9](https://github.com/aws-amplify/amplify-cli/commit/9c5b7e931e8382fe744516dee35a1aa545a91a97)), closes [#3035](https://github.com/aws-amplify/amplify-cli/issues/3035)
* correct casing of string type ([#2947](https://github.com/aws-amplify/amplify-cli/issues/2947)) ([c9887c3](https://github.com/aws-amplify/amplify-cli/commit/c9887c3c0ed949c2f93e04f5724e43ca777199e2)), closes [#2945](https://github.com/aws-amplify/amplify-cli/issues/2945)
* pass appsync specific directives to model gen ([#3211](https://github.com/aws-amplify/amplify-cli/issues/3211)) ([c9a6ada](https://github.com/aws-amplify/amplify-cli/commit/c9a6ada683a32f2a82ef9fdc4b0cb37ea70ccb11))
* **amplify-codegen-appsync-model-plugin:** make id field as first field ([474ff97](https://github.com/aws-amplify/amplify-cli/commit/474ff97371be7432eb4c96b3ef3b53ab45356c90))
* **amplify-codegen-appsync-model-plugin:** remove non connected models ([6422a63](https://github.com/aws-amplify/amplify-cli/commit/6422a634e54cb01d1cc9540992a913c694950972))
* **amplify-codegen-appsync-model-plugin:** remove swift loader extension ([d7b1995](https://github.com/aws-amplify/amplify-cli/commit/d7b199594533a5f0d9fb798c5d76bd0d46c3db03))
* **amplify-codegen-appsync-model-plugin:** remove targetName from model ([#2871](https://github.com/aws-amplify/amplify-cli/issues/2871)) ([f2ab7a3](https://github.com/aws-amplify/amplify-cli/commit/f2ab7a31fcab868bdc7038aa0b7285eb8f6b91c1))
* **amplify-codegen-appsync-model-plugin:** support self referncing connections ([#3046](https://github.com/aws-amplify/amplify-cli/issues/3046)) ([2c46431](https://github.com/aws-amplify/amplify-cli/commit/2c46431d5e582e4b8ef41919a624e0c7814b99d2)), closes [#3040](https://github.com/aws-amplify/amplify-cli/issues/3040)
* **amplify-codegen-appsync-model-plugin:** update QueryField name (java) ([#2884](https://github.com/aws-amplify/amplify-cli/issues/2884)) ([fb480fd](https://github.com/aws-amplify/amplify-cli/commit/fb480fd07fae9b2c10e09ba30038b254e7524c89))
* **amplify-codegen-appsync-model-plugin:** update swift protocol ([#2911](https://github.com/aws-amplify/amplify-cli/issues/2911)) ([38c4196](https://github.com/aws-amplify/amplify-cli/commit/38c41962ceaa6bc47c6fd97897b583d94c4adbe4))
* **amplify-codegen-appsync-model-plugin:** use LazyCollection (JS/TS) ([#2905](https://github.com/aws-amplify/amplify-cli/issues/2905)) ([4fa3a53](https://github.com/aws-amplify/amplify-cli/commit/4fa3a5339f3183dfea461f4ca61016be9f55381c)), closes [#2](https://github.com/aws-amplify/amplify-cli/issues/2)


### Features

* Lambda layers ([#4697](https://github.com/aws-amplify/amplify-cli/issues/4697)) ([4e97400](https://github.com/aws-amplify/amplify-cli/commit/4e974007d95c894ab4108a2dff8d5996e7e3ce25))
* **amplify-codegen-appsync-model-plugin:** add fromId method ([#2843](https://github.com/aws-amplify/amplify-cli/issues/2843)) ([2f422da](https://github.com/aws-amplify/amplify-cli/commit/2f422da89c28aaafec60e8464505d490665a2db7))
* **amplify-codegen-appsync-model-plugin:** add non-model support - Java ([#3976](https://github.com/aws-amplify/amplify-cli/issues/3976)) ([0016135](https://github.com/aws-amplify/amplify-cli/commit/001613516f8a8f5425ddd6e918d1ea613d67d97f)), closes [#3586](https://github.com/aws-amplify/amplify-cli/issues/3586)
* **amplify-codegen-appsync-model-plugin:** add support for keyName ([#4258](https://github.com/aws-amplify/amplify-cli/issues/4258)) ([024b825](https://github.com/aws-amplify/amplify-cli/commit/024b82517a313a203f5ca851137e723f22f32649))
* **amplify-codegen-appsync-model-plugin:** iOS add suport for auth ([#4329](https://github.com/aws-amplify/amplify-cli/issues/4329)) ([05cc6fc](https://github.com/aws-amplify/amplify-cli/commit/05cc6fcc6181b740030d2aa69a3b1f8921ba0b61))
* **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
* **amplify-codegen-appsync-model-plugin:** support [@connection](https://github.com/connection) with fields in modelgen ([#3680](https://github.com/aws-amplify/amplify-cli/issues/3680)) ([088d46f](https://github.com/aws-amplify/amplify-cli/commit/088d46f2d67dcbb7e3bd213f8d869f2c87b2df5d)), closes [#3225](https://github.com/aws-amplify/amplify-cli/issues/3225)
* **amplify-codegen-appsync-model-plugin:** support types sans model ([3dad60a](https://github.com/aws-amplify/amplify-cli/commit/3dad60addc82c574776462d553ff068511271ab8))
* **amplify-codegen-appsync-model-plugin:** update java model generator ([#2785](https://github.com/aws-amplify/amplify-cli/issues/2785)) ([c66148c](https://github.com/aws-amplify/amplify-cli/commit/c66148cdd126b316f8d1cbe6d40e0d8bf8226ed9))
* **amplify-codegen-appsync-model-plugin:** update java tostring to include fields  ([#3773](https://github.com/aws-amplify/amplify-cli/issues/3773)) ([547cf94](https://github.com/aws-amplify/amplify-cli/commit/547cf942bf44a6e6776565b795e32553f94a6b90))





## [1.20.10](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.20.9...amplify-codegen-appsync-model-plugin@1.20.10) (2020-10-30)


### Bug Fixes

* **amplify-codegen-appsync-model-plugin:** revert changes of adding ownerField for implicit cases for [@auth](https://github.com/auth) ([#5682](https://github.com/aws-amplify/amplify-cli/issues/5682)) ([85c9c93](https://github.com/aws-amplify/amplify-cli/commit/85c9c931408cc9ac3bd93f36481181829b882753))





## [1.20.9](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.20.8...amplify-codegen-appsync-model-plugin@1.20.9) (2020-10-22)


### Bug Fixes

* **amplify-codegen-appsync-model-plugin:** add field level [@auth](https://github.com/auth) process ([#5543](https://github.com/aws-amplify/amplify-cli/issues/5543)) ([1340343](https://github.com/aws-amplify/amplify-cli/commit/1340343c18e2a155bdb35321a2915d910f1f851e))
* **amplify-codegen-appsync-model-plugin:** generate nullable types for list ([#5493](https://github.com/aws-amplify/amplify-cli/issues/5493)) ([8b5043c](https://github.com/aws-amplify/amplify-cli/commit/8b5043c9e26ecb157ea3159e4e13dae097215301))
* **amplify-codegen-appsync-model-plugin:** refactor the build step in java modelgen ([#5500](https://github.com/aws-amplify/amplify-cli/issues/5500)) ([95838c7](https://github.com/aws-amplify/amplify-cli/commit/95838c71c340584314bd3502219234c7de114719))





## [1.20.8](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.20.7...amplify-codegen-appsync-model-plugin@1.20.8) (2020-10-07)


### Bug Fixes

* **amplify-codegen-appsync-model-plugin:** add ownerField to modelgen… ([#5455](https://github.com/aws-amplify/amplify-cli/issues/5455)) ([763f4af](https://github.com/aws-amplify/amplify-cli/commit/763f4af9238729894e5c95eba298d3c1b08a33db))





## [1.20.7](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.20.6...amplify-codegen-appsync-model-plugin@1.20.7) (2020-10-01)


### Bug Fixes

* **amplify-codegen-appsync-model-plugin:** DataStore Array Support ([#5327](https://github.com/aws-amplify/amplify-cli/issues/5327)) ([c88bee1](https://github.com/aws-amplify/amplify-cli/commit/c88bee1a4eed9aafca0e764fb2867176eed1c8e2)), closes [#5139](https://github.com/aws-amplify/amplify-cli/issues/5139)
* **amplify-codegen-appsync-model-plugin:** fix nullable lists ([#5450](https://github.com/aws-amplify/amplify-cli/issues/5450)) ([ec02076](https://github.com/aws-amplify/amplify-cli/commit/ec02076e9a4aab119a8a85e729b19fb4727607f4))





## [1.20.6](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.20.5...amplify-codegen-appsync-model-plugin@1.20.6) (2020-09-25)


### Bug Fixes

* add owner field if owner auth is included in auth rules ([#5335](https://github.com/aws-amplify/amplify-cli/issues/5335)) ([2200f51](https://github.com/aws-amplify/amplify-cli/commit/2200f51c70ffa6c3fe88efa6b563e962668da3e0))





## [1.20.5](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.20.4...amplify-codegen-appsync-model-plugin@1.20.5) (2020-08-31)

**Note:** Version bump only for package amplify-codegen-appsync-model-plugin





## [1.20.4](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.20.3...amplify-codegen-appsync-model-plugin@1.20.4) (2020-08-20)


### Bug Fixes

* bug in CopyofBuilder class with no nullable and non nullable fields ([#5108](https://github.com/aws-amplify/amplify-cli/issues/5108)) ([646435a](https://github.com/aws-amplify/amplify-cli/commit/646435adf35ab057f8c19b35eb86bab077a36a80))





## [1.20.3](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.20.2...amplify-codegen-appsync-model-plugin@1.20.3) (2020-08-06)

**Note:** Version bump only for package amplify-codegen-appsync-model-plugin





## [1.20.2](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.20.0...amplify-codegen-appsync-model-plugin@1.20.2) (2020-07-29)

**Note:** Version bump only for package amplify-codegen-appsync-model-plugin





## [1.20.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.20.0...amplify-codegen-appsync-model-plugin@1.20.1) (2020-07-23)

**Note:** Version bump only for package amplify-codegen-appsync-model-plugin





# [1.20.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.19.2...amplify-codegen-appsync-model-plugin@1.20.0) (2020-07-07)


### Features

* Lambda layers ([#4697](https://github.com/aws-amplify/amplify-cli/issues/4697)) ([c55b2e0](https://github.com/aws-amplify/amplify-cli/commit/c55b2e0c3377127aaf887591d7bc20d7240ef11d))





## [1.19.2](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.19.1...amplify-codegen-appsync-model-plugin@1.19.2) (2020-06-18)


### Bug Fixes

* **amplify-codegen-appsync-model-plugin:**  Support Embeddable Types for iOS  ([#4545](https://github.com/aws-amplify/amplify-cli/issues/4545)) ([7d4652b](https://github.com/aws-amplify/amplify-cli/commit/7d4652be017c660379832702c6ec8eb7005d9989))





## [1.19.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.19.0...amplify-codegen-appsync-model-plugin@1.19.1) (2020-06-10)


### Bug Fixes

* **amplify-codegen-appsync-model-plugin:** Add delimiter in Android `toString` output ([#4463](https://github.com/aws-amplify/amplify-cli/issues/4463)) ([a0a3972](https://github.com/aws-amplify/amplify-cli/commit/a0a39727b477954c6c13ab519aa998addbe729a8))





# [1.19.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.18.0...amplify-codegen-appsync-model-plugin@1.19.0) (2020-05-26)


### Features

* **amplify-codegen-appsync-model-plugin:** iOS add suport for auth ([#4329](https://github.com/aws-amplify/amplify-cli/issues/4329)) ([17ac344](https://github.com/aws-amplify/amplify-cli/commit/17ac344d7096470e698b26d68d8c586446190352))





# [1.18.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.17.0...amplify-codegen-appsync-model-plugin@1.18.0) (2020-05-15)


### Features

* **amplify-codegen-appsync-model-plugin:** add support for keyName ([#4258](https://github.com/aws-amplify/amplify-cli/issues/4258)) ([024b825](https://github.com/aws-amplify/amplify-cli/commit/024b82517a313a203f5ca851137e723f22f32649))





# [1.17.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.16.0...amplify-codegen-appsync-model-plugin@1.17.0) (2020-05-08)


### Features

* **amplify-codegen-appsync-model-plugin:** add non-model support - Java ([#3976](https://github.com/aws-amplify/amplify-cli/issues/3976)) ([0016135](https://github.com/aws-amplify/amplify-cli/commit/001613516f8a8f5425ddd6e918d1ea613d67d97f)), closes [#3586](https://github.com/aws-amplify/amplify-cli/issues/3586)





# [1.16.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.15.0...amplify-codegen-appsync-model-plugin@1.16.0) (2020-04-23)


### Features

* **amplify-codegen-appsync-model-plugin:** update java tostring to include fields  ([#3773](https://github.com/aws-amplify/amplify-cli/issues/3773)) ([547cf94](https://github.com/aws-amplify/amplify-cli/commit/547cf942bf44a6e6776565b795e32553f94a6b90))





# [1.15.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.14.0...amplify-codegen-appsync-model-plugin@1.15.0) (2020-04-06)


### Features

* **amplify-codegen-appsync-model-plugin:** support [@connection](https://github.com/connection) with fields in modelgen ([#3680](https://github.com/aws-amplify/amplify-cli/issues/3680)) ([088d46f](https://github.com/aws-amplify/amplify-cli/commit/088d46f2d67dcbb7e3bd213f8d869f2c87b2df5d)), closes [#3225](https://github.com/aws-amplify/amplify-cli/issues/3225)





# [1.14.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.13.5...amplify-codegen-appsync-model-plugin@1.14.0) (2020-03-26)


### Features

* **amplify-codegen-appsync-model-plugin:** support types sans model ([3dad60a](https://github.com/aws-amplify/amplify-cli/commit/3dad60addc82c574776462d553ff068511271ab8))





## [1.13.5](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.13.4...amplify-codegen-appsync-model-plugin@1.13.5) (2020-03-22)

**Note:** Version bump only for package amplify-codegen-appsync-model-plugin





## [1.13.4](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.13.3...amplify-codegen-appsync-model-plugin@1.13.4) (2020-03-10)


### Bug Fixes

* **amplify-codegen:** use Java Long for AWSTimestamp ([#3615](https://github.com/aws-amplify/amplify-cli/issues/3615)) ([051b2fb](https://github.com/aws-amplify/amplify-cli/commit/051b2fb4de7266d950af8a51170f30b43d0d9b50)), closes [#3593](https://github.com/aws-amplify/amplify-cli/issues/3593)





## [1.13.3](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.13.2...amplify-codegen-appsync-model-plugin@1.13.3) (2020-02-13)

**Note:** Version bump only for package amplify-codegen-appsync-model-plugin





## [1.13.2](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.13.1...amplify-codegen-appsync-model-plugin@1.13.2) (2020-02-07)

**Note:** Version bump only for package amplify-codegen-appsync-model-plugin





## [1.13.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen-appsync-model-plugin@1.13.0...amplify-codegen-appsync-model-plugin@1.13.1) (2020-01-24)


### Bug Fixes

* **amplify-codegen-appsync-model-plugin:** fix typo in swift model gen ([#3256](https://github.com/aws-amplify/amplify-cli/issues/3256)) ([c5109ba](https://github.com/aws-amplify/amplify-cli/commit/c5109baf5f9b47e91ab19bc5f5c7a0e4e3089adf))





# 1.13.0 (2020-01-23)

### Bug Fixes

- ** amplify-codegen-appsync-model-plugin:** field name errors ([#3055](https://github.com/aws-amplify/amplify-cli/issues/3055)) ([cde1bc0](https://github.com/aws-amplify/amplify-cli/commit/cde1bc0806693d4a3a00806b01ef56d6cc90cbe7))
- **amplify-codegen-appsync-model-plugin:** add additional scalars ([#2919](https://github.com/aws-amplify/amplify-cli/issues/2919)) ([4521f67](https://github.com/aws-amplify/amplify-cli/commit/4521f675ce735df1b5ce824e4cec9001ea414781))
- **amplify-codegen-appsync-model-plugin:** add Amplify extension to ios ([4a97971](https://github.com/aws-amplify/amplify-cli/commit/4a97971b7cae61891998ce29a2558e2c8c1a647f))
- **amplify-codegen-appsync-model-plugin:** add auth directive info ([#3050](https://github.com/aws-amplify/amplify-cli/issues/3050)) ([9951402](https://github.com/aws-amplify/amplify-cli/commit/9951402777b047277e6e05c6cb84fea92c238e82))
- **amplify-codegen-appsync-model-plugin:** add missing packages ([aaab38e](https://github.com/aws-amplify/amplify-cli/commit/aaab38e4456c15a00c61e0e00dc940ee7d7aea01))
- **amplify-codegen-appsync-model-plugin:** add toString in hashCode ([5b74dfa](https://github.com/aws-amplify/amplify-cli/commit/5b74dfa0b0badc9a6f4d8eb8f1bbdc03e3819ecc))
- **amplify-codegen-appsync-model-plugin:** builder to exclude connection ([6b78f3d](https://github.com/aws-amplify/amplify-cli/commit/6b78f3d91545ef8933759b2e0ea44dc45571383e))
- **amplify-codegen-appsync-model-plugin:** fix android models ([#2800](https://github.com/aws-amplify/amplify-cli/issues/2800)) ([cc96a05](https://github.com/aws-amplify/amplify-cli/commit/cc96a0557a385d89af9235148c56455f715a8731))
- **amplify-codegen-appsync-model-plugin:** fix connection keyname issue ([e3e52b3](https://github.com/aws-amplify/amplify-cli/commit/e3e52b3cddfc30961a486b43ee7e14f4b02c2e36))
- **amplify-codegen-appsync-model-plugin:** include enums in JS exports ([#2805](https://github.com/aws-amplify/amplify-cli/issues/2805)) ([cac07aa](https://github.com/aws-amplify/amplify-cli/commit/cac07aa2b36a65b4f86bffb82ccfacf270ee7d49))
- **amplify-codegen-appsync-model-plugin:** make id field as first field ([474ff97](https://github.com/aws-amplify/amplify-cli/commit/474ff97371be7432eb4c96b3ef3b53ab45356c90))
- **amplify-codegen-appsync-model-plugin:** remove non connected models ([6422a63](https://github.com/aws-amplify/amplify-cli/commit/6422a634e54cb01d1cc9540992a913c694950972))
- **amplify-codegen-appsync-model-plugin:** remove swift loader extension ([d7b1995](https://github.com/aws-amplify/amplify-cli/commit/d7b199594533a5f0d9fb798c5d76bd0d46c3db03))
- **amplify-codegen-appsync-model-plugin:** remove targetName from model ([#2871](https://github.com/aws-amplify/amplify-cli/issues/2871)) ([f2ab7a3](https://github.com/aws-amplify/amplify-cli/commit/f2ab7a31fcab868bdc7038aa0b7285eb8f6b91c1))
- correct casing of string type ([#2947](https://github.com/aws-amplify/amplify-cli/issues/2947)) ([c9887c3](https://github.com/aws-amplify/amplify-cli/commit/c9887c3c0ed949c2f93e04f5724e43ca777199e2)), closes [#2945](https://github.com/aws-amplify/amplify-cli/issues/2945)
- **amplify-codegen-appsync-model-plugin:** revert lazy load ([3323a31](https://github.com/aws-amplify/amplify-cli/commit/3323a31f936dbe3c870244e1dee31291fcfbf6a4))
- **amplify-codegen-appsync-model-plugin:** support non-codeable types ([#3226](https://github.com/aws-amplify/amplify-cli/issues/3226)) ([9c5b7e9](https://github.com/aws-amplify/amplify-cli/commit/9c5b7e931e8382fe744516dee35a1aa545a91a97)), closes [#3035](https://github.com/aws-amplify/amplify-cli/issues/3035)
- **amplify-codegen-appsync-model-plugin:** support self referncing connections ([#3046](https://github.com/aws-amplify/amplify-cli/issues/3046)) ([2c46431](https://github.com/aws-amplify/amplify-cli/commit/2c46431d5e582e4b8ef41919a624e0c7814b99d2)), closes [#3040](https://github.com/aws-amplify/amplify-cli/issues/3040)
- pass appsync specific directives to model gen ([#3211](https://github.com/aws-amplify/amplify-cli/issues/3211)) ([c9a6ada](https://github.com/aws-amplify/amplify-cli/commit/c9a6ada683a32f2a82ef9fdc4b0cb37ea70ccb11))
- **amplify-codegen-appsync-model-plugin:** update QueryField name (java) ([#2884](https://github.com/aws-amplify/amplify-cli/issues/2884)) ([fb480fd](https://github.com/aws-amplify/amplify-cli/commit/fb480fd07fae9b2c10e09ba30038b254e7524c89))
- **amplify-codegen-appsync-model-plugin:** update swift protocol ([#2911](https://github.com/aws-amplify/amplify-cli/issues/2911)) ([38c4196](https://github.com/aws-amplify/amplify-cli/commit/38c41962ceaa6bc47c6fd97897b583d94c4adbe4))
- **amplify-codegen-appsync-model-plugin:** use LazyCollection (JS/TS) ([#2905](https://github.com/aws-amplify/amplify-cli/issues/2905)) ([4fa3a53](https://github.com/aws-amplify/amplify-cli/commit/4fa3a5339f3183dfea461f4ca61016be9f55381c)), closes [#2](https://github.com/aws-amplify/amplify-cli/issues/2)

### Features

- **amplify-codegen-appsync-model-plugin:** add fromId method ([#2843](https://github.com/aws-amplify/amplify-cli/issues/2843)) ([2f422da](https://github.com/aws-amplify/amplify-cli/commit/2f422da89c28aaafec60e8464505d490665a2db7))
- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **amplify-codegen-appsync-model-plugin:** update java model generator ([#2785](https://github.com/aws-amplify/amplify-cli/issues/2785)) ([c66148c](https://github.com/aws-amplify/amplify-cli/commit/c66148cdd126b316f8d1cbe6d40e0d8bf8226ed9))

# 1.12.0 (2020-01-09)

### Bug Fixes

- ** amplify-codegen-appsync-model-plugin:** field name errors ([#3055](https://github.com/aws-amplify/amplify-cli/issues/3055)) ([cde1bc0](https://github.com/aws-amplify/amplify-cli/commit/cde1bc0806693d4a3a00806b01ef56d6cc90cbe7))
- **amplify-codegen-appsync-model-plugin:** add additional scalars ([#2919](https://github.com/aws-amplify/amplify-cli/issues/2919)) ([4521f67](https://github.com/aws-amplify/amplify-cli/commit/4521f675ce735df1b5ce824e4cec9001ea414781))
- **amplify-codegen-appsync-model-plugin:** add Amplify extension to ios ([4a97971](https://github.com/aws-amplify/amplify-cli/commit/4a97971b7cae61891998ce29a2558e2c8c1a647f))
- **amplify-codegen-appsync-model-plugin:** add auth directive info ([#3050](https://github.com/aws-amplify/amplify-cli/issues/3050)) ([9951402](https://github.com/aws-amplify/amplify-cli/commit/9951402777b047277e6e05c6cb84fea92c238e82))
- **amplify-codegen-appsync-model-plugin:** add missing packages ([aaab38e](https://github.com/aws-amplify/amplify-cli/commit/aaab38e4456c15a00c61e0e00dc940ee7d7aea01))
- **amplify-codegen-appsync-model-plugin:** add toString in hashCode ([5b74dfa](https://github.com/aws-amplify/amplify-cli/commit/5b74dfa0b0badc9a6f4d8eb8f1bbdc03e3819ecc))
- **amplify-codegen-appsync-model-plugin:** builder to exclude connection ([6b78f3d](https://github.com/aws-amplify/amplify-cli/commit/6b78f3d91545ef8933759b2e0ea44dc45571383e))
- **amplify-codegen-appsync-model-plugin:** fix android models ([#2800](https://github.com/aws-amplify/amplify-cli/issues/2800)) ([cc96a05](https://github.com/aws-amplify/amplify-cli/commit/cc96a0557a385d89af9235148c56455f715a8731))
- **amplify-codegen-appsync-model-plugin:** fix connection keyname issue ([e3e52b3](https://github.com/aws-amplify/amplify-cli/commit/e3e52b3cddfc30961a486b43ee7e14f4b02c2e36))
- **amplify-codegen-appsync-model-plugin:** include enums in JS exports ([#2805](https://github.com/aws-amplify/amplify-cli/issues/2805)) ([cac07aa](https://github.com/aws-amplify/amplify-cli/commit/cac07aa2b36a65b4f86bffb82ccfacf270ee7d49))
- **amplify-codegen-appsync-model-plugin:** make id field as first field ([474ff97](https://github.com/aws-amplify/amplify-cli/commit/474ff97371be7432eb4c96b3ef3b53ab45356c90))
- **amplify-codegen-appsync-model-plugin:** remove non connected models ([6422a63](https://github.com/aws-amplify/amplify-cli/commit/6422a634e54cb01d1cc9540992a913c694950972))
- **amplify-codegen-appsync-model-plugin:** remove swift loader extension ([d7b1995](https://github.com/aws-amplify/amplify-cli/commit/d7b199594533a5f0d9fb798c5d76bd0d46c3db03))
- **amplify-codegen-appsync-model-plugin:** remove targetName from model ([#2871](https://github.com/aws-amplify/amplify-cli/issues/2871)) ([f2ab7a3](https://github.com/aws-amplify/amplify-cli/commit/f2ab7a31fcab868bdc7038aa0b7285eb8f6b91c1))
- **amplify-codegen-appsync-model-plugin:** revert lazy load ([3323a31](https://github.com/aws-amplify/amplify-cli/commit/3323a31f936dbe3c870244e1dee31291fcfbf6a4))
- **amplify-codegen-appsync-model-plugin:** support self referncing connections ([#3046](https://github.com/aws-amplify/amplify-cli/issues/3046)) ([2c46431](https://github.com/aws-amplify/amplify-cli/commit/2c46431d5e582e4b8ef41919a624e0c7814b99d2)), closes [#3040](https://github.com/aws-amplify/amplify-cli/issues/3040)
- **amplify-codegen-appsync-model-plugin:** update QueryField name (java) ([#2884](https://github.com/aws-amplify/amplify-cli/issues/2884)) ([fb480fd](https://github.com/aws-amplify/amplify-cli/commit/fb480fd07fae9b2c10e09ba30038b254e7524c89))
- **amplify-codegen-appsync-model-plugin:** update swift protocol ([#2911](https://github.com/aws-amplify/amplify-cli/issues/2911)) ([38c4196](https://github.com/aws-amplify/amplify-cli/commit/38c41962ceaa6bc47c6fd97897b583d94c4adbe4))
- **amplify-codegen-appsync-model-plugin:** use LazyCollection (JS/TS) ([#2905](https://github.com/aws-amplify/amplify-cli/issues/2905)) ([4fa3a53](https://github.com/aws-amplify/amplify-cli/commit/4fa3a5339f3183dfea461f4ca61016be9f55381c)), closes [#2](https://github.com/aws-amplify/amplify-cli/issues/2)
- correct casing of string type ([#2947](https://github.com/aws-amplify/amplify-cli/issues/2947)) ([c9887c3](https://github.com/aws-amplify/amplify-cli/commit/c9887c3c0ed949c2f93e04f5724e43ca777199e2)), closes [#2945](https://github.com/aws-amplify/amplify-cli/issues/2945)

### Features

- **amplify-codegen-appsync-model-plugin:** add fromId method ([#2843](https://github.com/aws-amplify/amplify-cli/issues/2843)) ([2f422da](https://github.com/aws-amplify/amplify-cli/commit/2f422da89c28aaafec60e8464505d490665a2db7))
- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **amplify-codegen-appsync-model-plugin:** update java model generator ([#2785](https://github.com/aws-amplify/amplify-cli/issues/2785)) ([c66148c](https://github.com/aws-amplify/amplify-cli/commit/c66148cdd126b316f8d1cbe6d40e0d8bf8226ed9))

# 1.11.0 (2019-12-31)

### Bug Fixes

- ** amplify-codegen-appsync-model-plugin:** field name errors ([#3055](https://github.com/aws-amplify/amplify-cli/issues/3055)) ([cde1bc0](https://github.com/aws-amplify/amplify-cli/commit/cde1bc0806693d4a3a00806b01ef56d6cc90cbe7))
- **amplify-codegen-appsync-model-plugin:** add additional scalars ([#2919](https://github.com/aws-amplify/amplify-cli/issues/2919)) ([4521f67](https://github.com/aws-amplify/amplify-cli/commit/4521f675ce735df1b5ce824e4cec9001ea414781))
- **amplify-codegen-appsync-model-plugin:** add Amplify extension to ios ([4a97971](https://github.com/aws-amplify/amplify-cli/commit/4a97971b7cae61891998ce29a2558e2c8c1a647f))
- **amplify-codegen-appsync-model-plugin:** add auth directive info ([#3050](https://github.com/aws-amplify/amplify-cli/issues/3050)) ([9951402](https://github.com/aws-amplify/amplify-cli/commit/9951402777b047277e6e05c6cb84fea92c238e82))
- **amplify-codegen-appsync-model-plugin:** add missing packages ([aaab38e](https://github.com/aws-amplify/amplify-cli/commit/aaab38e4456c15a00c61e0e00dc940ee7d7aea01))
- **amplify-codegen-appsync-model-plugin:** add toString in hashCode ([5b74dfa](https://github.com/aws-amplify/amplify-cli/commit/5b74dfa0b0badc9a6f4d8eb8f1bbdc03e3819ecc))
- **amplify-codegen-appsync-model-plugin:** builder to exclude connection ([6b78f3d](https://github.com/aws-amplify/amplify-cli/commit/6b78f3d91545ef8933759b2e0ea44dc45571383e))
- **amplify-codegen-appsync-model-plugin:** fix android models ([#2800](https://github.com/aws-amplify/amplify-cli/issues/2800)) ([cc96a05](https://github.com/aws-amplify/amplify-cli/commit/cc96a0557a385d89af9235148c56455f715a8731))
- **amplify-codegen-appsync-model-plugin:** fix connection keyname issue ([e3e52b3](https://github.com/aws-amplify/amplify-cli/commit/e3e52b3cddfc30961a486b43ee7e14f4b02c2e36))
- **amplify-codegen-appsync-model-plugin:** include enums in JS exports ([#2805](https://github.com/aws-amplify/amplify-cli/issues/2805)) ([cac07aa](https://github.com/aws-amplify/amplify-cli/commit/cac07aa2b36a65b4f86bffb82ccfacf270ee7d49))
- **amplify-codegen-appsync-model-plugin:** make id field as first field ([474ff97](https://github.com/aws-amplify/amplify-cli/commit/474ff97371be7432eb4c96b3ef3b53ab45356c90))
- **amplify-codegen-appsync-model-plugin:** remove non connected models ([6422a63](https://github.com/aws-amplify/amplify-cli/commit/6422a634e54cb01d1cc9540992a913c694950972))
- **amplify-codegen-appsync-model-plugin:** remove swift loader extension ([d7b1995](https://github.com/aws-amplify/amplify-cli/commit/d7b199594533a5f0d9fb798c5d76bd0d46c3db03))
- **amplify-codegen-appsync-model-plugin:** remove targetName from model ([#2871](https://github.com/aws-amplify/amplify-cli/issues/2871)) ([f2ab7a3](https://github.com/aws-amplify/amplify-cli/commit/f2ab7a31fcab868bdc7038aa0b7285eb8f6b91c1))
- **amplify-codegen-appsync-model-plugin:** revert lazy load ([3323a31](https://github.com/aws-amplify/amplify-cli/commit/3323a31f936dbe3c870244e1dee31291fcfbf6a4))
- **amplify-codegen-appsync-model-plugin:** support self referncing connections ([#3046](https://github.com/aws-amplify/amplify-cli/issues/3046)) ([2c46431](https://github.com/aws-amplify/amplify-cli/commit/2c46431d5e582e4b8ef41919a624e0c7814b99d2)), closes [#3040](https://github.com/aws-amplify/amplify-cli/issues/3040)
- **amplify-codegen-appsync-model-plugin:** update QueryField name (java) ([#2884](https://github.com/aws-amplify/amplify-cli/issues/2884)) ([fb480fd](https://github.com/aws-amplify/amplify-cli/commit/fb480fd07fae9b2c10e09ba30038b254e7524c89))
- **amplify-codegen-appsync-model-plugin:** update swift protocol ([#2911](https://github.com/aws-amplify/amplify-cli/issues/2911)) ([38c4196](https://github.com/aws-amplify/amplify-cli/commit/38c41962ceaa6bc47c6fd97897b583d94c4adbe4))
- **amplify-codegen-appsync-model-plugin:** use LazyCollection (JS/TS) ([#2905](https://github.com/aws-amplify/amplify-cli/issues/2905)) ([4fa3a53](https://github.com/aws-amplify/amplify-cli/commit/4fa3a5339f3183dfea461f4ca61016be9f55381c)), closes [#2](https://github.com/aws-amplify/amplify-cli/issues/2)
- correct casing of string type ([#2947](https://github.com/aws-amplify/amplify-cli/issues/2947)) ([c9887c3](https://github.com/aws-amplify/amplify-cli/commit/c9887c3c0ed949c2f93e04f5724e43ca777199e2)), closes [#2945](https://github.com/aws-amplify/amplify-cli/issues/2945)

### Features

- **amplify-codegen-appsync-model-plugin:** add fromId method ([#2843](https://github.com/aws-amplify/amplify-cli/issues/2843)) ([2f422da](https://github.com/aws-amplify/amplify-cli/commit/2f422da89c28aaafec60e8464505d490665a2db7))
- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **amplify-codegen-appsync-model-plugin:** update java model generator ([#2785](https://github.com/aws-amplify/amplify-cli/issues/2785)) ([c66148c](https://github.com/aws-amplify/amplify-cli/commit/c66148cdd126b316f8d1cbe6d40e0d8bf8226ed9))

# 1.10.0 (2019-12-28)

### Bug Fixes

- ** amplify-codegen-appsync-model-plugin:** field name errors ([#3055](https://github.com/aws-amplify/amplify-cli/issues/3055)) ([cde1bc0](https://github.com/aws-amplify/amplify-cli/commit/cde1bc0806693d4a3a00806b01ef56d6cc90cbe7))
- **amplify-codegen-appsync-model-plugin:** add additional scalars ([#2919](https://github.com/aws-amplify/amplify-cli/issues/2919)) ([4521f67](https://github.com/aws-amplify/amplify-cli/commit/4521f675ce735df1b5ce824e4cec9001ea414781))
- **amplify-codegen-appsync-model-plugin:** add Amplify extension to ios ([4a97971](https://github.com/aws-amplify/amplify-cli/commit/4a97971b7cae61891998ce29a2558e2c8c1a647f))
- **amplify-codegen-appsync-model-plugin:** add auth directive info ([#3050](https://github.com/aws-amplify/amplify-cli/issues/3050)) ([9951402](https://github.com/aws-amplify/amplify-cli/commit/9951402777b047277e6e05c6cb84fea92c238e82))
- **amplify-codegen-appsync-model-plugin:** add missing packages ([aaab38e](https://github.com/aws-amplify/amplify-cli/commit/aaab38e4456c15a00c61e0e00dc940ee7d7aea01))
- **amplify-codegen-appsync-model-plugin:** add toString in hashCode ([5b74dfa](https://github.com/aws-amplify/amplify-cli/commit/5b74dfa0b0badc9a6f4d8eb8f1bbdc03e3819ecc))
- **amplify-codegen-appsync-model-plugin:** builder to exclude connection ([6b78f3d](https://github.com/aws-amplify/amplify-cli/commit/6b78f3d91545ef8933759b2e0ea44dc45571383e))
- **amplify-codegen-appsync-model-plugin:** fix android models ([#2800](https://github.com/aws-amplify/amplify-cli/issues/2800)) ([cc96a05](https://github.com/aws-amplify/amplify-cli/commit/cc96a0557a385d89af9235148c56455f715a8731))
- **amplify-codegen-appsync-model-plugin:** fix connection keyname issue ([e3e52b3](https://github.com/aws-amplify/amplify-cli/commit/e3e52b3cddfc30961a486b43ee7e14f4b02c2e36))
- **amplify-codegen-appsync-model-plugin:** include enums in JS exports ([#2805](https://github.com/aws-amplify/amplify-cli/issues/2805)) ([cac07aa](https://github.com/aws-amplify/amplify-cli/commit/cac07aa2b36a65b4f86bffb82ccfacf270ee7d49))
- **amplify-codegen-appsync-model-plugin:** make id field as first field ([474ff97](https://github.com/aws-amplify/amplify-cli/commit/474ff97371be7432eb4c96b3ef3b53ab45356c90))
- **amplify-codegen-appsync-model-plugin:** remove non connected models ([6422a63](https://github.com/aws-amplify/amplify-cli/commit/6422a634e54cb01d1cc9540992a913c694950972))
- **amplify-codegen-appsync-model-plugin:** remove swift loader extension ([d7b1995](https://github.com/aws-amplify/amplify-cli/commit/d7b199594533a5f0d9fb798c5d76bd0d46c3db03))
- **amplify-codegen-appsync-model-plugin:** remove targetName from model ([#2871](https://github.com/aws-amplify/amplify-cli/issues/2871)) ([f2ab7a3](https://github.com/aws-amplify/amplify-cli/commit/f2ab7a31fcab868bdc7038aa0b7285eb8f6b91c1))
- **amplify-codegen-appsync-model-plugin:** revert lazy load ([3323a31](https://github.com/aws-amplify/amplify-cli/commit/3323a31f936dbe3c870244e1dee31291fcfbf6a4))
- **amplify-codegen-appsync-model-plugin:** support self referncing connections ([#3046](https://github.com/aws-amplify/amplify-cli/issues/3046)) ([2c46431](https://github.com/aws-amplify/amplify-cli/commit/2c46431d5e582e4b8ef41919a624e0c7814b99d2)), closes [#3040](https://github.com/aws-amplify/amplify-cli/issues/3040)
- **amplify-codegen-appsync-model-plugin:** update QueryField name (java) ([#2884](https://github.com/aws-amplify/amplify-cli/issues/2884)) ([fb480fd](https://github.com/aws-amplify/amplify-cli/commit/fb480fd07fae9b2c10e09ba30038b254e7524c89))
- **amplify-codegen-appsync-model-plugin:** update swift protocol ([#2911](https://github.com/aws-amplify/amplify-cli/issues/2911)) ([38c4196](https://github.com/aws-amplify/amplify-cli/commit/38c41962ceaa6bc47c6fd97897b583d94c4adbe4))
- **amplify-codegen-appsync-model-plugin:** use LazyCollection (JS/TS) ([#2905](https://github.com/aws-amplify/amplify-cli/issues/2905)) ([4fa3a53](https://github.com/aws-amplify/amplify-cli/commit/4fa3a5339f3183dfea461f4ca61016be9f55381c)), closes [#2](https://github.com/aws-amplify/amplify-cli/issues/2)
- correct casing of string type ([#2947](https://github.com/aws-amplify/amplify-cli/issues/2947)) ([c9887c3](https://github.com/aws-amplify/amplify-cli/commit/c9887c3c0ed949c2f93e04f5724e43ca777199e2)), closes [#2945](https://github.com/aws-amplify/amplify-cli/issues/2945)

### Features

- **amplify-codegen-appsync-model-plugin:** add fromId method ([#2843](https://github.com/aws-amplify/amplify-cli/issues/2843)) ([2f422da](https://github.com/aws-amplify/amplify-cli/commit/2f422da89c28aaafec60e8464505d490665a2db7))
- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **amplify-codegen-appsync-model-plugin:** update java model generator ([#2785](https://github.com/aws-amplify/amplify-cli/issues/2785)) ([c66148c](https://github.com/aws-amplify/amplify-cli/commit/c66148cdd126b316f8d1cbe6d40e0d8bf8226ed9))

# 1.9.0 (2019-12-26)

### Bug Fixes

- ** amplify-codegen-appsync-model-plugin:** field name errors ([#3055](https://github.com/aws-amplify/amplify-cli/issues/3055)) ([cde1bc0](https://github.com/aws-amplify/amplify-cli/commit/cde1bc0806693d4a3a00806b01ef56d6cc90cbe7))
- **amplify-codegen-appsync-model-plugin:** add additional scalars ([#2919](https://github.com/aws-amplify/amplify-cli/issues/2919)) ([4521f67](https://github.com/aws-amplify/amplify-cli/commit/4521f675ce735df1b5ce824e4cec9001ea414781))
- **amplify-codegen-appsync-model-plugin:** add Amplify extension to ios ([4a97971](https://github.com/aws-amplify/amplify-cli/commit/4a97971b7cae61891998ce29a2558e2c8c1a647f))
- **amplify-codegen-appsync-model-plugin:** add auth directive info ([#3050](https://github.com/aws-amplify/amplify-cli/issues/3050)) ([9951402](https://github.com/aws-amplify/amplify-cli/commit/9951402777b047277e6e05c6cb84fea92c238e82))
- **amplify-codegen-appsync-model-plugin:** add missing packages ([aaab38e](https://github.com/aws-amplify/amplify-cli/commit/aaab38e4456c15a00c61e0e00dc940ee7d7aea01))
- **amplify-codegen-appsync-model-plugin:** add toString in hashCode ([5b74dfa](https://github.com/aws-amplify/amplify-cli/commit/5b74dfa0b0badc9a6f4d8eb8f1bbdc03e3819ecc))
- **amplify-codegen-appsync-model-plugin:** builder to exclude connection ([6b78f3d](https://github.com/aws-amplify/amplify-cli/commit/6b78f3d91545ef8933759b2e0ea44dc45571383e))
- **amplify-codegen-appsync-model-plugin:** fix android models ([#2800](https://github.com/aws-amplify/amplify-cli/issues/2800)) ([cc96a05](https://github.com/aws-amplify/amplify-cli/commit/cc96a0557a385d89af9235148c56455f715a8731))
- **amplify-codegen-appsync-model-plugin:** fix connection keyname issue ([e3e52b3](https://github.com/aws-amplify/amplify-cli/commit/e3e52b3cddfc30961a486b43ee7e14f4b02c2e36))
- **amplify-codegen-appsync-model-plugin:** include enums in JS exports ([#2805](https://github.com/aws-amplify/amplify-cli/issues/2805)) ([cac07aa](https://github.com/aws-amplify/amplify-cli/commit/cac07aa2b36a65b4f86bffb82ccfacf270ee7d49))
- **amplify-codegen-appsync-model-plugin:** make id field as first field ([474ff97](https://github.com/aws-amplify/amplify-cli/commit/474ff97371be7432eb4c96b3ef3b53ab45356c90))
- **amplify-codegen-appsync-model-plugin:** remove non connected models ([6422a63](https://github.com/aws-amplify/amplify-cli/commit/6422a634e54cb01d1cc9540992a913c694950972))
- **amplify-codegen-appsync-model-plugin:** remove swift loader extension ([d7b1995](https://github.com/aws-amplify/amplify-cli/commit/d7b199594533a5f0d9fb798c5d76bd0d46c3db03))
- **amplify-codegen-appsync-model-plugin:** remove targetName from model ([#2871](https://github.com/aws-amplify/amplify-cli/issues/2871)) ([f2ab7a3](https://github.com/aws-amplify/amplify-cli/commit/f2ab7a31fcab868bdc7038aa0b7285eb8f6b91c1))
- **amplify-codegen-appsync-model-plugin:** revert lazy load ([3323a31](https://github.com/aws-amplify/amplify-cli/commit/3323a31f936dbe3c870244e1dee31291fcfbf6a4))
- **amplify-codegen-appsync-model-plugin:** support self referncing connections ([#3046](https://github.com/aws-amplify/amplify-cli/issues/3046)) ([2c46431](https://github.com/aws-amplify/amplify-cli/commit/2c46431d5e582e4b8ef41919a624e0c7814b99d2)), closes [#3040](https://github.com/aws-amplify/amplify-cli/issues/3040)
- **amplify-codegen-appsync-model-plugin:** update QueryField name (java) ([#2884](https://github.com/aws-amplify/amplify-cli/issues/2884)) ([fb480fd](https://github.com/aws-amplify/amplify-cli/commit/fb480fd07fae9b2c10e09ba30038b254e7524c89))
- **amplify-codegen-appsync-model-plugin:** update swift protocol ([#2911](https://github.com/aws-amplify/amplify-cli/issues/2911)) ([38c4196](https://github.com/aws-amplify/amplify-cli/commit/38c41962ceaa6bc47c6fd97897b583d94c4adbe4))
- **amplify-codegen-appsync-model-plugin:** use LazyCollection (JS/TS) ([#2905](https://github.com/aws-amplify/amplify-cli/issues/2905)) ([4fa3a53](https://github.com/aws-amplify/amplify-cli/commit/4fa3a5339f3183dfea461f4ca61016be9f55381c)), closes [#2](https://github.com/aws-amplify/amplify-cli/issues/2)
- correct casing of string type ([#2947](https://github.com/aws-amplify/amplify-cli/issues/2947)) ([c9887c3](https://github.com/aws-amplify/amplify-cli/commit/c9887c3c0ed949c2f93e04f5724e43ca777199e2)), closes [#2945](https://github.com/aws-amplify/amplify-cli/issues/2945)

### Features

- **amplify-codegen-appsync-model-plugin:** add fromId method ([#2843](https://github.com/aws-amplify/amplify-cli/issues/2843)) ([2f422da](https://github.com/aws-amplify/amplify-cli/commit/2f422da89c28aaafec60e8464505d490665a2db7))
- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **amplify-codegen-appsync-model-plugin:** update java model generator ([#2785](https://github.com/aws-amplify/amplify-cli/issues/2785)) ([c66148c](https://github.com/aws-amplify/amplify-cli/commit/c66148cdd126b316f8d1cbe6d40e0d8bf8226ed9))

# 1.8.0 (2019-12-25)

### Bug Fixes

- ** amplify-codegen-appsync-model-plugin:** field name errors ([#3055](https://github.com/aws-amplify/amplify-cli/issues/3055)) ([cde1bc0](https://github.com/aws-amplify/amplify-cli/commit/cde1bc0806693d4a3a00806b01ef56d6cc90cbe7))
- **amplify-codegen-appsync-model-plugin:** add additional scalars ([#2919](https://github.com/aws-amplify/amplify-cli/issues/2919)) ([4521f67](https://github.com/aws-amplify/amplify-cli/commit/4521f675ce735df1b5ce824e4cec9001ea414781))
- **amplify-codegen-appsync-model-plugin:** add Amplify extension to ios ([4a97971](https://github.com/aws-amplify/amplify-cli/commit/4a97971b7cae61891998ce29a2558e2c8c1a647f))
- **amplify-codegen-appsync-model-plugin:** add auth directive info ([#3050](https://github.com/aws-amplify/amplify-cli/issues/3050)) ([9951402](https://github.com/aws-amplify/amplify-cli/commit/9951402777b047277e6e05c6cb84fea92c238e82))
- **amplify-codegen-appsync-model-plugin:** add missing packages ([aaab38e](https://github.com/aws-amplify/amplify-cli/commit/aaab38e4456c15a00c61e0e00dc940ee7d7aea01))
- **amplify-codegen-appsync-model-plugin:** add toString in hashCode ([5b74dfa](https://github.com/aws-amplify/amplify-cli/commit/5b74dfa0b0badc9a6f4d8eb8f1bbdc03e3819ecc))
- **amplify-codegen-appsync-model-plugin:** builder to exclude connection ([6b78f3d](https://github.com/aws-amplify/amplify-cli/commit/6b78f3d91545ef8933759b2e0ea44dc45571383e))
- **amplify-codegen-appsync-model-plugin:** fix android models ([#2800](https://github.com/aws-amplify/amplify-cli/issues/2800)) ([cc96a05](https://github.com/aws-amplify/amplify-cli/commit/cc96a0557a385d89af9235148c56455f715a8731))
- **amplify-codegen-appsync-model-plugin:** fix connection keyname issue ([e3e52b3](https://github.com/aws-amplify/amplify-cli/commit/e3e52b3cddfc30961a486b43ee7e14f4b02c2e36))
- **amplify-codegen-appsync-model-plugin:** include enums in JS exports ([#2805](https://github.com/aws-amplify/amplify-cli/issues/2805)) ([cac07aa](https://github.com/aws-amplify/amplify-cli/commit/cac07aa2b36a65b4f86bffb82ccfacf270ee7d49))
- **amplify-codegen-appsync-model-plugin:** make id field as first field ([474ff97](https://github.com/aws-amplify/amplify-cli/commit/474ff97371be7432eb4c96b3ef3b53ab45356c90))
- **amplify-codegen-appsync-model-plugin:** remove non connected models ([6422a63](https://github.com/aws-amplify/amplify-cli/commit/6422a634e54cb01d1cc9540992a913c694950972))
- **amplify-codegen-appsync-model-plugin:** remove swift loader extension ([d7b1995](https://github.com/aws-amplify/amplify-cli/commit/d7b199594533a5f0d9fb798c5d76bd0d46c3db03))
- **amplify-codegen-appsync-model-plugin:** remove targetName from model ([#2871](https://github.com/aws-amplify/amplify-cli/issues/2871)) ([f2ab7a3](https://github.com/aws-amplify/amplify-cli/commit/f2ab7a31fcab868bdc7038aa0b7285eb8f6b91c1))
- **amplify-codegen-appsync-model-plugin:** revert lazy load ([3323a31](https://github.com/aws-amplify/amplify-cli/commit/3323a31f936dbe3c870244e1dee31291fcfbf6a4))
- **amplify-codegen-appsync-model-plugin:** support self referncing connections ([#3046](https://github.com/aws-amplify/amplify-cli/issues/3046)) ([2c46431](https://github.com/aws-amplify/amplify-cli/commit/2c46431d5e582e4b8ef41919a624e0c7814b99d2)), closes [#3040](https://github.com/aws-amplify/amplify-cli/issues/3040)
- **amplify-codegen-appsync-model-plugin:** update QueryField name (java) ([#2884](https://github.com/aws-amplify/amplify-cli/issues/2884)) ([fb480fd](https://github.com/aws-amplify/amplify-cli/commit/fb480fd07fae9b2c10e09ba30038b254e7524c89))
- **amplify-codegen-appsync-model-plugin:** update swift protocol ([#2911](https://github.com/aws-amplify/amplify-cli/issues/2911)) ([38c4196](https://github.com/aws-amplify/amplify-cli/commit/38c41962ceaa6bc47c6fd97897b583d94c4adbe4))
- **amplify-codegen-appsync-model-plugin:** use LazyCollection (JS/TS) ([#2905](https://github.com/aws-amplify/amplify-cli/issues/2905)) ([4fa3a53](https://github.com/aws-amplify/amplify-cli/commit/4fa3a5339f3183dfea461f4ca61016be9f55381c)), closes [#2](https://github.com/aws-amplify/amplify-cli/issues/2)
- correct casing of string type ([#2947](https://github.com/aws-amplify/amplify-cli/issues/2947)) ([c9887c3](https://github.com/aws-amplify/amplify-cli/commit/c9887c3c0ed949c2f93e04f5724e43ca777199e2)), closes [#2945](https://github.com/aws-amplify/amplify-cli/issues/2945)

### Features

- **amplify-codegen-appsync-model-plugin:** add fromId method ([#2843](https://github.com/aws-amplify/amplify-cli/issues/2843)) ([2f422da](https://github.com/aws-amplify/amplify-cli/commit/2f422da89c28aaafec60e8464505d490665a2db7))
- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **amplify-codegen-appsync-model-plugin:** update java model generator ([#2785](https://github.com/aws-amplify/amplify-cli/issues/2785)) ([c66148c](https://github.com/aws-amplify/amplify-cli/commit/c66148cdd126b316f8d1cbe6d40e0d8bf8226ed9))

# 1.7.0 (2019-12-20)

### Bug Fixes

- **amplify-codegen-appsync-model-plugin:** add additional scalars ([#2919](https://github.com/aws-amplify/amplify-cli/issues/2919)) ([4521f67](https://github.com/aws-amplify/amplify-cli/commit/4521f675ce735df1b5ce824e4cec9001ea414781))
- **amplify-codegen-appsync-model-plugin:** add Amplify extension to ios ([4a97971](https://github.com/aws-amplify/amplify-cli/commit/4a97971b7cae61891998ce29a2558e2c8c1a647f))
- **amplify-codegen-appsync-model-plugin:** add missing packages ([aaab38e](https://github.com/aws-amplify/amplify-cli/commit/aaab38e4456c15a00c61e0e00dc940ee7d7aea01))
- **amplify-codegen-appsync-model-plugin:** add toString in hashCode ([5b74dfa](https://github.com/aws-amplify/amplify-cli/commit/5b74dfa0b0badc9a6f4d8eb8f1bbdc03e3819ecc))
- **amplify-codegen-appsync-model-plugin:** builder to exclude connection ([6b78f3d](https://github.com/aws-amplify/amplify-cli/commit/6b78f3d91545ef8933759b2e0ea44dc45571383e))
- **amplify-codegen-appsync-model-plugin:** fix android models ([#2800](https://github.com/aws-amplify/amplify-cli/issues/2800)) ([cc96a05](https://github.com/aws-amplify/amplify-cli/commit/cc96a0557a385d89af9235148c56455f715a8731))
- **amplify-codegen-appsync-model-plugin:** fix connection keyname issue ([e3e52b3](https://github.com/aws-amplify/amplify-cli/commit/e3e52b3cddfc30961a486b43ee7e14f4b02c2e36))
- **amplify-codegen-appsync-model-plugin:** include enums in JS exports ([#2805](https://github.com/aws-amplify/amplify-cli/issues/2805)) ([cac07aa](https://github.com/aws-amplify/amplify-cli/commit/cac07aa2b36a65b4f86bffb82ccfacf270ee7d49))
- **amplify-codegen-appsync-model-plugin:** make id field as first field ([474ff97](https://github.com/aws-amplify/amplify-cli/commit/474ff97371be7432eb4c96b3ef3b53ab45356c90))
- **amplify-codegen-appsync-model-plugin:** remove non connected models ([6422a63](https://github.com/aws-amplify/amplify-cli/commit/6422a634e54cb01d1cc9540992a913c694950972))
- **amplify-codegen-appsync-model-plugin:** remove swift loader extension ([d7b1995](https://github.com/aws-amplify/amplify-cli/commit/d7b199594533a5f0d9fb798c5d76bd0d46c3db03))
- **amplify-codegen-appsync-model-plugin:** remove targetName from model ([#2871](https://github.com/aws-amplify/amplify-cli/issues/2871)) ([f2ab7a3](https://github.com/aws-amplify/amplify-cli/commit/f2ab7a31fcab868bdc7038aa0b7285eb8f6b91c1))
- **amplify-codegen-appsync-model-plugin:** revert lazy load ([3323a31](https://github.com/aws-amplify/amplify-cli/commit/3323a31f936dbe3c870244e1dee31291fcfbf6a4))
- **amplify-codegen-appsync-model-plugin:** update QueryField name (java) ([#2884](https://github.com/aws-amplify/amplify-cli/issues/2884)) ([fb480fd](https://github.com/aws-amplify/amplify-cli/commit/fb480fd07fae9b2c10e09ba30038b254e7524c89))
- correct casing of string type ([#2947](https://github.com/aws-amplify/amplify-cli/issues/2947)) ([c9887c3](https://github.com/aws-amplify/amplify-cli/commit/c9887c3c0ed949c2f93e04f5724e43ca777199e2)), closes [#2945](https://github.com/aws-amplify/amplify-cli/issues/2945)
- **amplify-codegen-appsync-model-plugin:** update swift protocol ([#2911](https://github.com/aws-amplify/amplify-cli/issues/2911)) ([38c4196](https://github.com/aws-amplify/amplify-cli/commit/38c41962ceaa6bc47c6fd97897b583d94c4adbe4))
- **amplify-codegen-appsync-model-plugin:** use LazyCollection (JS/TS) ([#2905](https://github.com/aws-amplify/amplify-cli/issues/2905)) ([4fa3a53](https://github.com/aws-amplify/amplify-cli/commit/4fa3a5339f3183dfea461f4ca61016be9f55381c)), closes [#2](https://github.com/aws-amplify/amplify-cli/issues/2)

### Features

- **amplify-codegen-appsync-model-plugin:** add fromId method ([#2843](https://github.com/aws-amplify/amplify-cli/issues/2843)) ([2f422da](https://github.com/aws-amplify/amplify-cli/commit/2f422da89c28aaafec60e8464505d490665a2db7))
- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **amplify-codegen-appsync-model-plugin:** update java model generator ([#2785](https://github.com/aws-amplify/amplify-cli/issues/2785)) ([c66148c](https://github.com/aws-amplify/amplify-cli/commit/c66148cdd126b316f8d1cbe6d40e0d8bf8226ed9))

# 1.6.0 (2019-12-10)

### Bug Fixes

- **amplify-codegen-appsync-model-plugin:** add additional scalars ([#2919](https://github.com/aws-amplify/amplify-cli/issues/2919)) ([4521f67](https://github.com/aws-amplify/amplify-cli/commit/4521f675ce735df1b5ce824e4cec9001ea414781))
- **amplify-codegen-appsync-model-plugin:** add Amplify extension to ios ([4a97971](https://github.com/aws-amplify/amplify-cli/commit/4a97971b7cae61891998ce29a2558e2c8c1a647f))
- **amplify-codegen-appsync-model-plugin:** add missing packages ([aaab38e](https://github.com/aws-amplify/amplify-cli/commit/aaab38e4456c15a00c61e0e00dc940ee7d7aea01))
- **amplify-codegen-appsync-model-plugin:** add toString in hashCode ([5b74dfa](https://github.com/aws-amplify/amplify-cli/commit/5b74dfa0b0badc9a6f4d8eb8f1bbdc03e3819ecc))
- **amplify-codegen-appsync-model-plugin:** builder to exclude connection ([6b78f3d](https://github.com/aws-amplify/amplify-cli/commit/6b78f3d91545ef8933759b2e0ea44dc45571383e))
- **amplify-codegen-appsync-model-plugin:** fix android models ([#2800](https://github.com/aws-amplify/amplify-cli/issues/2800)) ([cc96a05](https://github.com/aws-amplify/amplify-cli/commit/cc96a0557a385d89af9235148c56455f715a8731))
- **amplify-codegen-appsync-model-plugin:** fix connection keyname issue ([e3e52b3](https://github.com/aws-amplify/amplify-cli/commit/e3e52b3cddfc30961a486b43ee7e14f4b02c2e36))
- **amplify-codegen-appsync-model-plugin:** include enums in JS exports ([#2805](https://github.com/aws-amplify/amplify-cli/issues/2805)) ([cac07aa](https://github.com/aws-amplify/amplify-cli/commit/cac07aa2b36a65b4f86bffb82ccfacf270ee7d49))
- **amplify-codegen-appsync-model-plugin:** make id field as first field ([474ff97](https://github.com/aws-amplify/amplify-cli/commit/474ff97371be7432eb4c96b3ef3b53ab45356c90))
- **amplify-codegen-appsync-model-plugin:** remove non connected models ([6422a63](https://github.com/aws-amplify/amplify-cli/commit/6422a634e54cb01d1cc9540992a913c694950972))
- **amplify-codegen-appsync-model-plugin:** remove swift loader extension ([d7b1995](https://github.com/aws-amplify/amplify-cli/commit/d7b199594533a5f0d9fb798c5d76bd0d46c3db03))
- **amplify-codegen-appsync-model-plugin:** remove targetName from model ([#2871](https://github.com/aws-amplify/amplify-cli/issues/2871)) ([f2ab7a3](https://github.com/aws-amplify/amplify-cli/commit/f2ab7a31fcab868bdc7038aa0b7285eb8f6b91c1))
- **amplify-codegen-appsync-model-plugin:** revert lazy load ([3323a31](https://github.com/aws-amplify/amplify-cli/commit/3323a31f936dbe3c870244e1dee31291fcfbf6a4))
- **amplify-codegen-appsync-model-plugin:** update QueryField name (java) ([#2884](https://github.com/aws-amplify/amplify-cli/issues/2884)) ([fb480fd](https://github.com/aws-amplify/amplify-cli/commit/fb480fd07fae9b2c10e09ba30038b254e7524c89))
- correct casing of string type ([#2947](https://github.com/aws-amplify/amplify-cli/issues/2947)) ([c9887c3](https://github.com/aws-amplify/amplify-cli/commit/c9887c3c0ed949c2f93e04f5724e43ca777199e2)), closes [#2945](https://github.com/aws-amplify/amplify-cli/issues/2945)
- **amplify-codegen-appsync-model-plugin:** update swift protocol ([#2911](https://github.com/aws-amplify/amplify-cli/issues/2911)) ([38c4196](https://github.com/aws-amplify/amplify-cli/commit/38c41962ceaa6bc47c6fd97897b583d94c4adbe4))
- **amplify-codegen-appsync-model-plugin:** use LazyCollection (JS/TS) ([#2905](https://github.com/aws-amplify/amplify-cli/issues/2905)) ([4fa3a53](https://github.com/aws-amplify/amplify-cli/commit/4fa3a5339f3183dfea461f4ca61016be9f55381c)), closes [#2](https://github.com/aws-amplify/amplify-cli/issues/2)

### Features

- **amplify-codegen-appsync-model-plugin:** add fromId method ([#2843](https://github.com/aws-amplify/amplify-cli/issues/2843)) ([2f422da](https://github.com/aws-amplify/amplify-cli/commit/2f422da89c28aaafec60e8464505d490665a2db7))
- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **amplify-codegen-appsync-model-plugin:** update java model generator ([#2785](https://github.com/aws-amplify/amplify-cli/issues/2785)) ([c66148c](https://github.com/aws-amplify/amplify-cli/commit/c66148cdd126b316f8d1cbe6d40e0d8bf8226ed9))

# 1.4.0 (2019-12-03)

### Bug Fixes

- **amplify-codegen-appsync-model-plugin:** add Amplify extension to ios ([4a97971](https://github.com/aws-amplify/amplify-cli/commit/4a97971b7cae61891998ce29a2558e2c8c1a647f))
- **amplify-codegen-appsync-model-plugin:** add missing packages ([aaab38e](https://github.com/aws-amplify/amplify-cli/commit/aaab38e4456c15a00c61e0e00dc940ee7d7aea01))
- **amplify-codegen-appsync-model-plugin:** add toString in hashCode ([5b74dfa](https://github.com/aws-amplify/amplify-cli/commit/5b74dfa0b0badc9a6f4d8eb8f1bbdc03e3819ecc))
- **amplify-codegen-appsync-model-plugin:** builder to exclude connection ([6b78f3d](https://github.com/aws-amplify/amplify-cli/commit/6b78f3d91545ef8933759b2e0ea44dc45571383e))
- **amplify-codegen-appsync-model-plugin:** fix android models ([#2800](https://github.com/aws-amplify/amplify-cli/issues/2800)) ([cc96a05](https://github.com/aws-amplify/amplify-cli/commit/cc96a0557a385d89af9235148c56455f715a8731))
- **amplify-codegen-appsync-model-plugin:** fix connection keyname issue ([e3e52b3](https://github.com/aws-amplify/amplify-cli/commit/e3e52b3cddfc30961a486b43ee7e14f4b02c2e36))
- **amplify-codegen-appsync-model-plugin:** include enums in JS exports ([#2805](https://github.com/aws-amplify/amplify-cli/issues/2805)) ([cac07aa](https://github.com/aws-amplify/amplify-cli/commit/cac07aa2b36a65b4f86bffb82ccfacf270ee7d49))
- **amplify-codegen-appsync-model-plugin:** remove non connected models ([6422a63](https://github.com/aws-amplify/amplify-cli/commit/6422a634e54cb01d1cc9540992a913c694950972))
- **amplify-codegen-appsync-model-plugin:** remove swift loader extension ([d7b1995](https://github.com/aws-amplify/amplify-cli/commit/d7b199594533a5f0d9fb798c5d76bd0d46c3db03))
- **amplify-codegen-appsync-model-plugin:** remove targetName from model ([#2871](https://github.com/aws-amplify/amplify-cli/issues/2871)) ([f2ab7a3](https://github.com/aws-amplify/amplify-cli/commit/f2ab7a31fcab868bdc7038aa0b7285eb8f6b91c1))
- **amplify-codegen-appsync-model-plugin:** revert lazy load ([3323a31](https://github.com/aws-amplify/amplify-cli/commit/3323a31f936dbe3c870244e1dee31291fcfbf6a4))
- **amplify-codegen-appsync-model-plugin:** update QueryField name (java) ([#2884](https://github.com/aws-amplify/amplify-cli/issues/2884)) ([fb480fd](https://github.com/aws-amplify/amplify-cli/commit/fb480fd07fae9b2c10e09ba30038b254e7524c89))
- **amplify-codegen-appsync-model-plugin:** update swift protocol ([#2911](https://github.com/aws-amplify/amplify-cli/issues/2911)) ([38c4196](https://github.com/aws-amplify/amplify-cli/commit/38c41962ceaa6bc47c6fd97897b583d94c4adbe4))
- **amplify-codegen-appsync-model-plugin:** use LazyCollection (JS/TS) ([#2905](https://github.com/aws-amplify/amplify-cli/issues/2905)) ([4fa3a53](https://github.com/aws-amplify/amplify-cli/commit/4fa3a5339f3183dfea461f4ca61016be9f55381c)), closes [#2](https://github.com/aws-amplify/amplify-cli/issues/2)

### Features

- **amplify-codegen-appsync-model-plugin:** add fromId method ([#2843](https://github.com/aws-amplify/amplify-cli/issues/2843)) ([2f422da](https://github.com/aws-amplify/amplify-cli/commit/2f422da89c28aaafec60e8464505d490665a2db7))
- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **amplify-codegen-appsync-model-plugin:** update java model generator ([#2785](https://github.com/aws-amplify/amplify-cli/issues/2785)) ([c66148c](https://github.com/aws-amplify/amplify-cli/commit/c66148cdd126b316f8d1cbe6d40e0d8bf8226ed9))

# 1.3.0 (2019-12-01)

### Bug Fixes

- **amplify-codegen-appsync-model-plugin:** add Amplify extension to ios ([4a97971](https://github.com/aws-amplify/amplify-cli/commit/4a97971b7cae61891998ce29a2558e2c8c1a647f))
- **amplify-codegen-appsync-model-plugin:** add missing packages ([aaab38e](https://github.com/aws-amplify/amplify-cli/commit/aaab38e4456c15a00c61e0e00dc940ee7d7aea01))
- **amplify-codegen-appsync-model-plugin:** builder to exclude connection ([6b78f3d](https://github.com/aws-amplify/amplify-cli/commit/6b78f3d91545ef8933759b2e0ea44dc45571383e))
- **amplify-codegen-appsync-model-plugin:** fix android models ([#2800](https://github.com/aws-amplify/amplify-cli/issues/2800)) ([cc96a05](https://github.com/aws-amplify/amplify-cli/commit/cc96a0557a385d89af9235148c56455f715a8731))
- **amplify-codegen-appsync-model-plugin:** fix connection keyname issue ([e3e52b3](https://github.com/aws-amplify/amplify-cli/commit/e3e52b3cddfc30961a486b43ee7e14f4b02c2e36))
- **amplify-codegen-appsync-model-plugin:** include enums in JS exports ([#2805](https://github.com/aws-amplify/amplify-cli/issues/2805)) ([cac07aa](https://github.com/aws-amplify/amplify-cli/commit/cac07aa2b36a65b4f86bffb82ccfacf270ee7d49))
- **amplify-codegen-appsync-model-plugin:** remove non connected models ([6422a63](https://github.com/aws-amplify/amplify-cli/commit/6422a634e54cb01d1cc9540992a913c694950972))
- **amplify-codegen-appsync-model-plugin:** remove targetName from model ([#2871](https://github.com/aws-amplify/amplify-cli/issues/2871)) ([f2ab7a3](https://github.com/aws-amplify/amplify-cli/commit/f2ab7a31fcab868bdc7038aa0b7285eb8f6b91c1))
- **amplify-codegen-appsync-model-plugin:** update QueryField name (java) ([#2884](https://github.com/aws-amplify/amplify-cli/issues/2884)) ([fb480fd](https://github.com/aws-amplify/amplify-cli/commit/fb480fd07fae9b2c10e09ba30038b254e7524c89))

### Features

- **amplify-codegen-appsync-model-plugin:** add fromId method ([#2843](https://github.com/aws-amplify/amplify-cli/issues/2843)) ([2f422da](https://github.com/aws-amplify/amplify-cli/commit/2f422da89c28aaafec60e8464505d490665a2db7))
- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **amplify-codegen-appsync-model-plugin:** update java model generator ([#2785](https://github.com/aws-amplify/amplify-cli/issues/2785)) ([c66148c](https://github.com/aws-amplify/amplify-cli/commit/c66148cdd126b316f8d1cbe6d40e0d8bf8226ed9))

# 1.2.0 (2019-11-27)

### Bug Fixes

- **amplify-codegen-appsync-model-plugin:** add missing packages ([aaab38e](https://github.com/aws-amplify/amplify-cli/commit/aaab38e4456c15a00c61e0e00dc940ee7d7aea01))
- **amplify-codegen-appsync-model-plugin:** fix android models ([#2800](https://github.com/aws-amplify/amplify-cli/issues/2800)) ([cc96a05](https://github.com/aws-amplify/amplify-cli/commit/cc96a0557a385d89af9235148c56455f715a8731))
- **amplify-codegen-appsync-model-plugin:** include enums in JS exports ([#2805](https://github.com/aws-amplify/amplify-cli/issues/2805)) ([cac07aa](https://github.com/aws-amplify/amplify-cli/commit/cac07aa2b36a65b4f86bffb82ccfacf270ee7d49))

### Features

- **amplify-codegen-appsync-model-plugin:** add fromId method ([#2843](https://github.com/aws-amplify/amplify-cli/issues/2843)) ([2f422da](https://github.com/aws-amplify/amplify-cli/commit/2f422da89c28aaafec60e8464505d490665a2db7))
- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **amplify-codegen-appsync-model-plugin:** update java model generator ([#2785](https://github.com/aws-amplify/amplify-cli/issues/2785)) ([c66148c](https://github.com/aws-amplify/amplify-cli/commit/c66148cdd126b316f8d1cbe6d40e0d8bf8226ed9))

# 1.1.0 (2019-11-27)

### Bug Fixes

- **amplify-codegen-appsync-model-plugin:** fix android models ([#2800](https://github.com/aws-amplify/amplify-cli/issues/2800)) ([cc96a05](https://github.com/aws-amplify/amplify-cli/commit/cc96a0557a385d89af9235148c56455f715a8731))
- **amplify-codegen-appsync-model-plugin:** include enums in JS exports ([#2805](https://github.com/aws-amplify/amplify-cli/issues/2805)) ([cac07aa](https://github.com/aws-amplify/amplify-cli/commit/cac07aa2b36a65b4f86bffb82ccfacf270ee7d49))

### Features

- **amplify-codegen-appsync-model-plugin:** add fromId method ([#2843](https://github.com/aws-amplify/amplify-cli/issues/2843)) ([2f422da](https://github.com/aws-amplify/amplify-cli/commit/2f422da89c28aaafec60e8464505d490665a2db7))
- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **amplify-codegen-appsync-model-plugin:** update java model generator ([#2785](https://github.com/aws-amplify/amplify-cli/issues/2785)) ([c66148c](https://github.com/aws-amplify/amplify-cli/commit/c66148cdd126b316f8d1cbe6d40e0d8bf8226ed9))
