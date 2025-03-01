# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [2.26.3](https://github.com/aws-amplify/amplify-codegen/compare/amplify-codegen@2.26.2...amplify-codegen@2.26.3) (2021-08-18)

**Note:** Version bump only for package amplify-codegen





## [2.26.2](https://github.com/aws-amplify/amplify-codegen/compare/amplify-codegen@2.26.1...amplify-codegen@2.26.2) (2021-07-28)

**Note:** Version bump only for package amplify-codegen





## [2.26.1](https://github.com/aws-amplify/amplify-codegen/compare/amplify-codegen@2.26.0...amplify-codegen@2.26.1) (2021-07-12)

**Note:** Version bump only for package amplify-codegen





# [2.26.0](https://github.com/aws-amplify/amplify-codegen/compare/amplify-codegen@2.25.1...amplify-codegen@2.26.0) (2021-06-30)


### Features

* **codegen:** iOS index directive support ([#174](https://github.com/aws-amplify/amplify-codegen/issues/174)) ([abb966c](https://github.com/aws-amplify/amplify-codegen/commit/abb966c647b08537564f85314a4266a5cbe33ffd))
* **modelgen:** ios - emit provider in [@auth](https://github.com/auth) rules ([#184](https://github.com/aws-amplify/amplify-codegen/issues/184)) ([f9c1b1a](https://github.com/aws-amplify/amplify-codegen/commit/f9c1b1af89a837ed4b705e21085f6c8402e94283))





## [2.25.1](https://github.com/aws-amplify/amplify-codegen/compare/amplify-codegen@2.25.0...amplify-codegen@2.25.1) (2021-06-02)


### Bug Fixes

* **appsync-modelgen-plugin:** skip query/mutation/sub types ([#180](https://github.com/aws-amplify/amplify-codegen/issues/180)) ([aa0dbb3](https://github.com/aws-amplify/amplify-codegen/commit/aa0dbb31e9ebe285ec643ef98335021561dd2168))





# [2.25.0](https://github.com/aws-amplify/amplify-codegen/compare/amplify-codegen@2.24.2...amplify-codegen@2.25.0) (2021-05-25)


### Bug Fixes

* **amplify-codegen:** add correct error msg for flutter codegen ([#140](https://github.com/aws-amplify/amplify-codegen/issues/140)) ([a99d67c](https://github.com/aws-amplify/amplify-codegen/commit/a99d67c1053896cc62f9cfc1898fff3c992907da))
* **amplify-codegen:** Correct cli help re: codegen `--maxDepth` flag ([#138](https://github.com/aws-amplify/amplify-codegen/issues/138)) ([960b900](https://github.com/aws-amplify/amplify-codegen/commit/960b900f1f7de5f232bfd96cf673de93fae1643c))
* **appsync-modelgen-plugin:** restore the old init if timestamp disabled ([#177](https://github.com/aws-amplify/amplify-codegen/issues/177)) ([f923e14](https://github.com/aws-amplify/amplify-codegen/commit/f923e144e9cf51f904d792a5c01ceffca685d0ea))


### Features

* add E2e testing ([#169](https://github.com/aws-amplify/amplify-codegen/issues/169)) ([19e17df](https://github.com/aws-amplify/amplify-codegen/commit/19e17df3c04bf5c18341efa1a53a5ecf4a7cc42e)), closes [#151](https://github.com/aws-amplify/amplify-codegen/issues/151) [#156](https://github.com/aws-amplify/amplify-codegen/issues/156) [#157](https://github.com/aws-amplify/amplify-codegen/issues/157) [#163](https://github.com/aws-amplify/amplify-codegen/issues/163)
* **modelgen:** add timestamp fields createdAt & updatedAt for [@model](https://github.com/model) ([#114](https://github.com/aws-amplify/amplify-codegen/issues/114)) ([f611e94](https://github.com/aws-amplify/amplify-codegen/commit/f611e94ef8cbd37cf8e8f356df83adcb9a8d3465))





## [2.24.2](https://github.com/aws-amplify/amplify-codegen/compare/amplify-codegen@2.24.1...amplify-codegen@2.24.2) (2021-03-31)

**Note:** Version bump only for package amplify-codegen





## [2.24.1](https://github.com/aws-amplify/amplify-codegen/compare/amplify-codegen@2.24.0...amplify-codegen@2.24.1) (2021-03-29)


### Bug Fixes

* Revert "feat(amplify-codegen): Add Amplify CLI version as a comment for the Modelgen output files" ([#131](https://github.com/aws-amplify/amplify-codegen/issues/131)) ([b813657](https://github.com/aws-amplify/amplify-codegen/commit/b813657c0b7abce67cfe16fcd0f93389ba63120d))





# [2.24.0](https://github.com/aws-amplify/amplify-codegen/compare/amplify-codegen@2.23.1...amplify-codegen@2.24.0) (2021-03-29)


### Bug Fixes

* **amplify-codegen:** add amplify-codegen version to version metadata comment ([bb508e1](https://github.com/aws-amplify/amplify-codegen/commit/bb508e18377909e67990e7be2f1e27d9e2033442))
* **amplify-codegen:** have correct error msg for api meta not found ([#125](https://github.com/aws-amplify/amplify-codegen/issues/125)) ([2894f43](https://github.com/aws-amplify/amplify-codegen/commit/2894f43d8c5eaea9f04c05ed3508feb162115f60))
* **amplify-codegen:** minor changes to use lambda functions ([06ba31a](https://github.com/aws-amplify/amplify-codegen/commit/06ba31ac41dc6ec2b92b913ec2a262580defda17))
* **amplify-codegen:** remove commented test ([11cb697](https://github.com/aws-amplify/amplify-codegen/commit/11cb697a506eeb7d407ef61dfb7101cdfc8aca76))
* **amplify-codegen:** rephrase the amplify version comment ([c46105e](https://github.com/aws-amplify/amplify-codegen/commit/c46105e9014aa7c3d5c553bbe6d52bce705b3a90))


### Features

* **amplify-codegen:** Add Amplify CLI version as a comment for the Modelgen output files ([3ee4728](https://github.com/aws-amplify/amplify-codegen/commit/3ee4728c485e5805cda385ae62edb5db3242cb2b))





## [2.23.1](https://github.com/aws-amplify/amplify-codegen/compare/amplify-codegen@2.23.0...amplify-codegen@2.23.1) (2021-03-12)


### Bug Fixes

* **amplify-codegen:** disable cleanGeneratedModels FF ([3b3ca86](https://github.com/aws-amplify/amplify-codegen/commit/3b3ca869bd57558793b86e0e3469a0362960fcd4))
* **amplify-codegen:** print syntax error in a readable output ([#105](https://github.com/aws-amplify/amplify-codegen/issues/105)) ([3f87faa](https://github.com/aws-amplify/amplify-codegen/commit/3f87faa6995388ba2f22db0b986f2a6caadda49d))





# [2.23.0](https://github.com/aws-amplify/amplify-codegen/compare/amplify-codegen@2.22.4...amplify-codegen@2.23.0) (2021-03-11)


### Bug Fixes

* **amplify-codegen:** re-arrange models cmd tests ([0c970d5](https://github.com/aws-amplify/amplify-codegen/commit/0c970d54538e42f1fc480bbb72aeaf143b92a6be))
* **amplify-codegen:** rebase and fix merge conflicts ([69ca760](https://github.com/aws-amplify/amplify-codegen/commit/69ca760db6bc032eb105710cdfa91b35bcaf1c7b))
* **amplify-codegen:** refactor test setup into a common method ([825136d](https://github.com/aws-amplify/amplify-codegen/commit/825136de3799bce2accc9cc2a7414cdf9f6e7590))
* **amplify-codegen:** remove references to mock variable ([56ef92d](https://github.com/aws-amplify/amplify-codegen/commit/56ef92d0a555d3a27e3803a1299d4300584b2874))
* **amplify-codegen:** rename imported module mockFs ([0525dc5](https://github.com/aws-amplify/amplify-codegen/commit/0525dc5ff004dbf482052bc573c70e5e0f2b5553))
* **amplify-codegen:** rename mock to mockFs ([b146457](https://github.com/aws-amplify/amplify-codegen/commit/b1464578269ec94b334e6c6123959549d51fd428))
* **docsgen:** change FF name to codegen.retainCaseStyle ([caee85f](https://github.com/aws-amplify/amplify-codegen/commit/caee85f4378f009cdf3bb8d2dec88e11659a637a))
* **docsgen:** update to use FeatureFlag retainCaseStyle ([5b100f4](https://github.com/aws-amplify/amplify-codegen/commit/5b100f406e245388fe2d219ea809cbaa8b3c4c7c))


### Features

* **modelgen:** fetch graphql schemas from nested input folder ([8e2e009](https://github.com/aws-amplify/amplify-codegen/commit/8e2e009a36a3871fa6f9ddf282cd287d70396f1a))
* **modelgen:** support clearing outdated models using a feature flag ([f2bfce0](https://github.com/aws-amplify/amplify-codegen/commit/f2bfce0f6834c3f78cf01b0748868c2d8b8d0836))
* **modelgen:** support clearing outdated models using a feature flag ([6810541](https://github.com/aws-amplify/amplify-codegen/commit/681054112e3499ae11ccd0dd87109b80e1deaf2f))





## [2.22.4](https://github.com/aws-amplify/amplify-codegen/compare/amplify-codegen@2.22.3...amplify-codegen@2.22.4) (2021-03-04)


### Bug Fixes

* **amplify-codegen:** minor linting fixes ([4c3d980](https://github.com/aws-amplify/amplify-codegen/commit/4c3d980b8d4edcb3714f11e3b6f45bcf4ee8447d))
* **amplify-codegen:** move upstream CLI dependencies as peerDependencies ([83b0ce8](https://github.com/aws-amplify/amplify-codegen/commit/83b0ce87f517c5836fe0aae3b1e3ab590234f9b5))
* **amplify-codegen:** moving the constant back ([1611ee8](https://github.com/aws-amplify/amplify-codegen/commit/1611ee8cc7a19b2beebfe08883fd91e0a935aa64))
* **amplify-codegen:** use feature flag instances inside a method and not top level ([695b7a6](https://github.com/aws-amplify/amplify-codegen/commit/695b7a646c91656d917e437b2e767d333f93a6df))





## [2.22.3](https://github.com/aws-amplify/amplify-codegen/compare/amplify-codegen@2.22.2...amplify-codegen@2.22.3) (2021-02-25)


### Bug Fixes

* **amplify-codegen:** use correct array type for includePattern ([ac0bc6d](https://github.com/aws-amplify/amplify-codegen/commit/ac0bc6de56b549fb5b3bc65fd5dd8b7978e451ee))





## [2.22.2](https://github.com/aws-amplify/amplify-codegen/compare/amplify-codegen@2.22.1...amplify-codegen@2.22.2) (2021-02-23)


### Reverts

* Revert "Migrate amplify-codegen package (#76)" (#79) ([74f85ac](https://github.com/aws-amplify/amplify-codegen/commit/74f85ac9f89090f1497b0418cb7866cadab72f02)), closes [#76](https://github.com/aws-amplify/amplify-codegen/issues/76) [#79](https://github.com/aws-amplify/amplify-codegen/issues/79)





## 2.22.1 (2021-02-22)

**Note:** Version bump only for package amplify-codegen





## [2.21.2](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.21.1...amplify-codegen@2.21.2) (2021-02-17)

**Note:** Version bump only for package amplify-codegen





## [2.21.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.21.0...amplify-codegen@2.21.1) (2021-02-11)


### Bug Fixes

* **amplify-codegen:** set sourceDir path to correct graphql schema location ([#6512](https://github.com/aws-amplify/amplify-cli/issues/6512)) ([6edf229](https://github.com/aws-amplify/amplify-cli/commit/6edf2298ebbabda57230f9e0b9c6c4f504f8a275)), closes [aws-amplify/amplify-cli#5483](https://github.com/aws-amplify/amplify-cli/issues/5483) [aws-amplify/amplify-cli#5483](https://github.com/aws-amplify/amplify-cli/issues/5483)





# [2.21.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.20.5...amplify-codegen@2.21.0) (2021-02-10)


### Features

* add Flutter  support for Admin UI ([#6516](https://github.com/aws-amplify/amplify-cli/issues/6516)) ([d9ee44b](https://github.com/aws-amplify/amplify-cli/commit/d9ee44be73f43b11da2a07d21fd60108f49b1608))





## [2.20.5](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.20.4...amplify-codegen@2.20.5) (2021-01-08)


### Bug Fixes

* remove process on next and await ([#6239](https://github.com/aws-amplify/amplify-cli/issues/6239)) ([59d4a0e](https://github.com/aws-amplify/amplify-cli/commit/59d4a0eb318d2b3ad97be34bda9dee756cf82d74))





## [2.20.4](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.20.3...amplify-codegen@2.20.4) (2020-12-31)


### Bug Fixes

* **amplify-codegen:** excludes flutter projects from gql gen ([#6199](https://github.com/aws-amplify/amplify-cli/issues/6199)) ([450616e](https://github.com/aws-amplify/amplify-cli/commit/450616e42d28e862919c54b29454a29dbd715eaf))





## [2.20.3](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.20.2...amplify-codegen@2.20.3) (2020-12-21)

**Note:** Version bump only for package amplify-codegen





## [2.20.2](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.20.1...amplify-codegen@2.20.2) (2020-12-16)

**Note:** Version bump only for package amplify-codegen





## [2.20.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.20.0...amplify-codegen@2.20.1) (2020-12-11)

**Note:** Version bump only for package amplify-codegen





# [2.20.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.19.1...amplify-codegen@2.20.0) (2020-12-07)


### Features

* add support for multiple [@key](https://github.com/key) changes in same [@model](https://github.com/model) ([#6044](https://github.com/aws-amplify/amplify-cli/issues/6044)) ([e574637](https://github.com/aws-amplify/amplify-cli/commit/e5746379ea1330c53dacb55e8f6a9de7b17b55ae))





## [2.19.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.19.0...amplify-codegen@2.19.1) (2020-12-03)



## 4.37.1 (2020-12-02)


### Bug Fixes

* **amplify-codegen-appsync-model-plugin:** address feedback from flutter team(Nov 28) ([#6004](https://github.com/aws-amplify/amplify-cli/issues/6004)) ([b624e0f](https://github.com/aws-amplify/amplify-cli/commit/b624e0fff58659d0aeb13bc3e79b437071295aa3))





# [2.19.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.18.1...amplify-codegen@2.19.0) (2020-11-30)


### Features

* pre-deploy pull, new login mechanism and pkg cli updates ([#5941](https://github.com/aws-amplify/amplify-cli/issues/5941)) ([7274251](https://github.com/aws-amplify/amplify-cli/commit/7274251faadc1035acce5f44699b172e10e2e67d))





## [2.18.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.18.0...amplify-codegen@2.18.1) (2020-11-27)

**Note:** Version bump only for package amplify-codegen





# [2.18.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.17.1...amplify-codegen@2.18.0) (2020-11-26)



# 4.36.0 (2020-11-24)


### Features

* **amplify-codegen-appsync-model-plugin:** add appsync dart visitor … ([#5937](https://github.com/aws-amplify/amplify-cli/issues/5937)) ([28168ad](https://github.com/aws-amplify/amplify-cli/commit/28168ad25c341c038bfd13d7ca54b1b7bd74adc7))





## [2.17.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.16.2...amplify-codegen@2.17.1) (2020-11-22)



# 4.33.0 (2020-11-19)


### Bug Fixes

* **amplify-codegen:** generate eslintignore in js ([#5865](https://github.com/aws-amplify/amplify-cli/issues/5865)) ([baa8a6f](https://github.com/aws-amplify/amplify-cli/commit/baa8a6f76dc6cdbd69685f77300a02073c270ac9))
* eslintignore creation with uninitialized project ([#5913](https://github.com/aws-amplify/amplify-cli/issues/5913)) ([a7b7a8c](https://github.com/aws-amplify/amplify-cli/commit/a7b7a8c1a193dc4fc5eaf120307d9494e6e2c8ca))





# [2.17.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.5.7...amplify-codegen@2.17.0) (2020-11-22)


### Bug Fixes

* eslintignore creation with uninitialized project ([#5913](https://github.com/aws-amplify/amplify-cli/issues/5913)) ([a7b7a8c](https://github.com/aws-amplify/amplify-cli/commit/a7b7a8c1a193dc4fc5eaf120307d9494e6e2c8ca))
* **amplify-codegen:** add proper response type for subs ([#5317](https://github.com/aws-amplify/amplify-cli/issues/5317)) ([48d2e11](https://github.com/aws-amplify/amplify-cli/commit/48d2e11b2a9dbb9616cc989aa76c207eb7b5f13b)), closes [#5284](https://github.com/aws-amplify/amplify-cli/issues/5284)
* **amplify-codegen:** generate eslintignore in js ([#5865](https://github.com/aws-amplify/amplify-cli/issues/5865)) ([baa8a6f](https://github.com/aws-amplify/amplify-cli/commit/baa8a6f76dc6cdbd69685f77300a02073c270ac9))
* [#2360](https://github.com/aws-amplify/amplify-cli/issues/2360) - meta json was written as object ([#2381](https://github.com/aws-amplify/amplify-cli/issues/2381)) ([7dd3c37](https://github.com/aws-amplify/amplify-cli/commit/7dd3c370552af31d63a4c2352c7b7453d6ab1fc0))
* [#4549](https://github.com/aws-amplify/amplify-cli/issues/4549) [#4550](https://github.com/aws-amplify/amplify-cli/issues/4550) init and folder exist checks ([#4553](https://github.com/aws-amplify/amplify-cli/issues/4553)) ([30a33f9](https://github.com/aws-amplify/amplify-cli/commit/30a33f9e8ca9ff23d6e7343ef8e869461133f709))
* added exit code on remove ([#5427](https://github.com/aws-amplify/amplify-cli/issues/5427)) ([33132f7](https://github.com/aws-amplify/amplify-cli/commit/33132f764b290cafd345720409a5db8ea6088069))
* changed default config to user defined config ([#5334](https://github.com/aws-amplify/amplify-cli/issues/5334)) ([c630145](https://github.com/aws-amplify/amplify-cli/commit/c63014558547f75a0afa7e506116d8bb124c44d2))
* codegen spelling mistake ([#4757](https://github.com/aws-amplify/amplify-cli/issues/4757)) ([7896ebd](https://github.com/aws-amplify/amplify-cli/commit/7896ebdfe538478d1c6d8e5e7e2318c7baf1bb69))
* data inconsitency ([#5344](https://github.com/aws-amplify/amplify-cli/issues/5344)) ([bfe1903](https://github.com/aws-amplify/amplify-cli/commit/bfe19038b5b676056f45d7ffcc4c2460057936d8))
* **amplify-category-api:** use standard json read ([#2581](https://github.com/aws-amplify/amplify-cli/issues/2581)) ([3adc395](https://github.com/aws-amplify/amplify-cli/commit/3adc395a5e4ccf3673735f8091db63923a46c501))
* **amplify-codegen:** add framework only if javascript ([5709742](https://github.com/aws-amplify/amplify-cli/commit/5709742f33a20916c93869243f2bc699d40ddcce))
* **amplify-codegen:** add framework only if javascript ([#2342](https://github.com/aws-amplify/amplify-cli/issues/2342)) ([57c29c4](https://github.com/aws-amplify/amplify-cli/commit/57c29c450082c35dc6925be3d005422a2f5732bf))
* **amplify-codegen:** await statement generation before generating types ([#2168](https://github.com/aws-amplify/amplify-cli/issues/2168)) ([4c3aad0](https://github.com/aws-amplify/amplify-cli/commit/4c3aad032924a821497eaef7cc303dfcaa09dee2)), closes [#2129](https://github.com/aws-amplify/amplify-cli/issues/2129)
* **amplify-codegen:** fix headless push with codegen ([#2743](https://github.com/aws-amplify/amplify-cli/issues/2743)) ([da248a4](https://github.com/aws-amplify/amplify-cli/commit/da248a456d96ed37533f964c066651ae22459166))
* **amplify-codegen:** replace upath with slash ([#3133](https://github.com/aws-amplify/amplify-cli/issues/3133)) ([a565053](https://github.com/aws-amplify/amplify-cli/commit/a565053463e563ed3d44f1405ab551520e0cd818)), closes [#3131](https://github.com/aws-amplify/amplify-cli/issues/3131)
* **amplify-codegen:** support appsync scalars in modelgen ([#3424](https://github.com/aws-amplify/amplify-cli/issues/3424)) ([a6eba85](https://github.com/aws-amplify/amplify-cli/commit/a6eba858f2ed31192a1214a22a3180dd243c80c7)), closes [#3296](https://github.com/aws-amplify/amplify-cli/issues/3296)
* **amplify-codegen:** use ResDir directory to compute modelgen output ([#4145](https://github.com/aws-amplify/amplify-cli/issues/4145)) ([06a7ec5](https://github.com/aws-amplify/amplify-cli/commit/06a7ec5ede3b311e2ac0d2f86ee393bc04ef3eb5)), closes [#3993](https://github.com/aws-amplify/amplify-cli/issues/3993)
* [#1056](https://github.com/aws-amplify/amplify-cli/issues/1056), dedup environment file reading ([#2088](https://github.com/aws-amplify/amplify-cli/issues/2088)) ([940deaa](https://github.com/aws-amplify/amplify-cli/commit/940deaa6bbe7370e40e61946d0f1073623ba6e90))
* e2e tests, tsconfigs, [@deprecated](https://github.com/deprecated) directive for codegen: ([#3338](https://github.com/aws-amplify/amplify-cli/issues/3338)) ([2ed7715](https://github.com/aws-amplify/amplify-cli/commit/2ed77151dd6367ac9547f78fe600e7913a3d37b2))
* **amplify-codegen:** support headless push for newly added api ([#2442](https://github.com/aws-amplify/amplify-cli/issues/2442)) ([84c08e7](https://github.com/aws-amplify/amplify-cli/commit/84c08e79623fdb68ba8d0f24acf33f342fc83bb5)), closes [#2365](https://github.com/aws-amplify/amplify-cli/issues/2365)
* fix load config withoutinit ([389e739](https://github.com/aws-amplify/amplify-cli/commit/389e73916946d16b46805ebd00f0672064539966))
* **amplify-codegen:** support multi os team workflow in codegen ([#2212](https://github.com/aws-amplify/amplify-cli/issues/2212)) ([e4a0454](https://github.com/aws-amplify/amplify-cli/commit/e4a045468d761c9333a799d3b3dae6c6399dc179)), closes [#2147](https://github.com/aws-amplify/amplify-cli/issues/2147) [#2002](https://github.com/aws-amplify/amplify-cli/issues/2002)
* **amplify-codegen:** support nonarray includes/excludes in codegen conf ([#2271](https://github.com/aws-amplify/amplify-cli/issues/2271)) ([30904a0](https://github.com/aws-amplify/amplify-cli/commit/30904a0ac01b2ae6064d57109c998c9243b36d68)), closes [#2262](https://github.com/aws-amplify/amplify-cli/issues/2262)
* **cli:** fix new plugin platform codegen related issue ([#2266](https://github.com/aws-amplify/amplify-cli/issues/2266)) ([c557182](https://github.com/aws-amplify/amplify-cli/commit/c557182b2d423bb1c2f8832ecd49076c806b05bb))
* local mock fix ([#1982](https://github.com/aws-amplify/amplify-cli/issues/1982)) ([8ee9029](https://github.com/aws-amplify/amplify-cli/commit/8ee90298189f4d3140ab84fe2d40d16bcb95485f))
* move test package dependencies to devDependencies ([#2034](https://github.com/aws-amplify/amplify-cli/issues/2034)) ([f5623d0](https://github.com/aws-amplify/amplify-cli/commit/f5623d04a43e685901f4f1cd96e2a227164c71ee))


### Features

* **amplify-codegen:** add schema compile process in codegen commands ([#5164](https://github.com/aws-amplify/amplify-cli/issues/5164)) ([85f739a](https://github.com/aws-amplify/amplify-cli/commit/85f739a46112ff29b3b04e882ecd8db020452308))
* **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
* **cli:** cLI updates and new features for Amplify Console ([#2742](https://github.com/aws-amplify/amplify-cli/issues/2742)) ([0fd0dd5](https://github.com/aws-amplify/amplify-cli/commit/0fd0dd5102177766c454c8715fa5acac32385048))
* **cli:** new plugin platform ([#2254](https://github.com/aws-amplify/amplify-cli/issues/2254)) ([7ec29dd](https://github.com/aws-amplify/amplify-cli/commit/7ec29dd4f2da8c90727b36469eca646d289877b6))
* add support for multiauth in mock server ([#2109](https://github.com/aws-amplify/amplify-cli/issues/2109)) ([fe8ee8c](https://github.com/aws-amplify/amplify-cli/commit/fe8ee8cff355a826fa9ccddcf0fad8a200a081af))
* adding amplify cli predictions category ([#1936](https://github.com/aws-amplify/amplify-cli/issues/1936)) ([b7b7c2c](https://github.com/aws-amplify/amplify-cli/commit/b7b7c2c1927da10f8c54f38a523021187361131c))
* implement multi-auth functionality ([#1916](https://github.com/aws-amplify/amplify-cli/issues/1916)) ([b99f58e](https://github.com/aws-amplify/amplify-cli/commit/b99f58e4a2b85cbe9f430838554ae3c277440132))
* mock support for API, function and storage ([#1893](https://github.com/aws-amplify/amplify-cli/issues/1893)) ([372e534](https://github.com/aws-amplify/amplify-cli/commit/372e5346ee1f27a2e9bee25fbbdcb19417f5230f))


### Reverts

* Revert "feat(amplify-codegen): add schema compile process in codegen commands (#5164)" (#5707) ([d83f496](https://github.com/aws-amplify/amplify-cli/commit/d83f496f9ab51ded2eef6b0dd796627009eaf556)), closes [#5164](https://github.com/aws-amplify/amplify-cli/issues/5164) [#5707](https://github.com/aws-amplify/amplify-cli/issues/5707)





## [2.16.4](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.16.2...amplify-codegen@2.16.4) (2020-11-20)


### Bug Fixes

* eslintignore creation with uninitialized project ([#5913](https://github.com/aws-amplify/amplify-cli/issues/5913)) ([a7b7a8c](https://github.com/aws-amplify/amplify-cli/commit/a7b7a8c1a193dc4fc5eaf120307d9494e6e2c8ca))
* **amplify-codegen:** generate eslintignore in js ([#5865](https://github.com/aws-amplify/amplify-cli/issues/5865)) ([baa8a6f](https://github.com/aws-amplify/amplify-cli/commit/baa8a6f76dc6cdbd69685f77300a02073c270ac9))





## [2.16.3](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.16.2...amplify-codegen@2.16.3) (2020-11-20)


### Bug Fixes

* eslintignore creation with uninitialized project ([#5913](https://github.com/aws-amplify/amplify-cli/issues/5913)) ([a7b7a8c](https://github.com/aws-amplify/amplify-cli/commit/a7b7a8c1a193dc4fc5eaf120307d9494e6e2c8ca))
* **amplify-codegen:** generate eslintignore in js ([#5865](https://github.com/aws-amplify/amplify-cli/issues/5865)) ([baa8a6f](https://github.com/aws-amplify/amplify-cli/commit/baa8a6f76dc6cdbd69685f77300a02073c270ac9))





## [2.16.2](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.16.1...amplify-codegen@2.16.2) (2020-10-30)

**Note:** Version bump only for package amplify-codegen





## [2.16.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.16.0...amplify-codegen@2.16.1) (2020-10-27)


### Reverts

* Revert "feat(amplify-codegen): add schema compile process in codegen commands (#5164)" (#5707) ([d83f496](https://github.com/aws-amplify/amplify-cli/commit/d83f496f9ab51ded2eef6b0dd796627009eaf556)), closes [#5164](https://github.com/aws-amplify/amplify-cli/issues/5164) [#5707](https://github.com/aws-amplify/amplify-cli/issues/5707)





# [2.16.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.21...amplify-codegen@2.16.0) (2020-10-22)


### Bug Fixes

* **amplify-codegen:** add proper response type for subs ([#5317](https://github.com/aws-amplify/amplify-cli/issues/5317)) ([48d2e11](https://github.com/aws-amplify/amplify-cli/commit/48d2e11b2a9dbb9616cc989aa76c207eb7b5f13b)), closes [#5284](https://github.com/aws-amplify/amplify-cli/issues/5284)


### Features

* **amplify-codegen:** add schema compile process in codegen commands ([#5164](https://github.com/aws-amplify/amplify-cli/issues/5164)) ([85f739a](https://github.com/aws-amplify/amplify-cli/commit/85f739a46112ff29b3b04e882ecd8db020452308))





## [2.15.21](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.20...amplify-codegen@2.15.21) (2020-10-07)

**Note:** Version bump only for package amplify-codegen





## [2.15.20](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.19...amplify-codegen@2.15.20) (2020-10-01)


### Bug Fixes

* added exit code on remove ([#5427](https://github.com/aws-amplify/amplify-cli/issues/5427)) ([33132f7](https://github.com/aws-amplify/amplify-cli/commit/33132f764b290cafd345720409a5db8ea6088069))
* changed default config to user defined config ([#5334](https://github.com/aws-amplify/amplify-cli/issues/5334)) ([c630145](https://github.com/aws-amplify/amplify-cli/commit/c63014558547f75a0afa7e506116d8bb124c44d2))





## [2.15.19](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.18...amplify-codegen@2.15.19) (2020-09-25)


### Bug Fixes

* data inconsitency ([#5344](https://github.com/aws-amplify/amplify-cli/issues/5344)) ([bfe1903](https://github.com/aws-amplify/amplify-cli/commit/bfe19038b5b676056f45d7ffcc4c2460057936d8))





## [2.15.18](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.17...amplify-codegen@2.15.18) (2020-08-31)

**Note:** Version bump only for package amplify-codegen





## [2.15.17](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.16...amplify-codegen@2.15.17) (2020-08-20)

**Note:** Version bump only for package amplify-codegen





## [2.15.16](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.15...amplify-codegen@2.15.16) (2020-08-06)

**Note:** Version bump only for package amplify-codegen





## [2.15.15](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.13...amplify-codegen@2.15.15) (2020-07-29)

**Note:** Version bump only for package amplify-codegen





## [2.15.14](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.13...amplify-codegen@2.15.14) (2020-07-23)

**Note:** Version bump only for package amplify-codegen





## [2.15.13](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.12...amplify-codegen@2.15.13) (2020-07-15)


### Bug Fixes

* codegen spelling mistake ([#4757](https://github.com/aws-amplify/amplify-cli/issues/4757)) ([454fdc0](https://github.com/aws-amplify/amplify-cli/commit/454fdc01f97f74fce337a25efa12950257597174))





## [2.15.12](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.11...amplify-codegen@2.15.12) (2020-07-07)

**Note:** Version bump only for package amplify-codegen





## [2.15.11](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.10...amplify-codegen@2.15.11) (2020-06-18)


### Bug Fixes

* [#4549](https://github.com/aws-amplify/amplify-cli/issues/4549) [#4550](https://github.com/aws-amplify/amplify-cli/issues/4550) init and folder exist checks ([#4553](https://github.com/aws-amplify/amplify-cli/issues/4553)) ([543d531](https://github.com/aws-amplify/amplify-cli/commit/543d5312823783db7794ad574d03d0ca3991c8b5))





## [2.15.10](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.9...amplify-codegen@2.15.10) (2020-06-10)

**Note:** Version bump only for package amplify-codegen





## [2.15.9](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.8...amplify-codegen@2.15.9) (2020-05-26)

**Note:** Version bump only for package amplify-codegen





## [2.15.8](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.7...amplify-codegen@2.15.8) (2020-05-15)

**Note:** Version bump only for package amplify-codegen





## [2.15.7](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.6...amplify-codegen@2.15.7) (2020-05-08)


### Bug Fixes

* **amplify-codegen:** use ResDir directory to compute modelgen output ([#4145](https://github.com/aws-amplify/amplify-cli/issues/4145)) ([06a7ec5](https://github.com/aws-amplify/amplify-cli/commit/06a7ec5ede3b311e2ac0d2f86ee393bc04ef3eb5)), closes [#3993](https://github.com/aws-amplify/amplify-cli/issues/3993)





## [2.15.6](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.5...amplify-codegen@2.15.6) (2020-04-23)

**Note:** Version bump only for package amplify-codegen





## [2.15.5](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.4...amplify-codegen@2.15.5) (2020-04-06)

**Note:** Version bump only for package amplify-codegen





## [2.15.4](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.3...amplify-codegen@2.15.4) (2020-03-26)

**Note:** Version bump only for package amplify-codegen





## [2.15.3](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.2...amplify-codegen@2.15.3) (2020-03-22)

**Note:** Version bump only for package amplify-codegen





## [2.15.2](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.15.1...amplify-codegen@2.15.2) (2020-03-10)

**Note:** Version bump only for package amplify-codegen





## [2.15.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.13.3...amplify-codegen@2.15.1) (2020-03-07)

**Note:** Version bump only for package amplify-codegen





## [2.14.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.13.5-beta.0...amplify-codegen@2.14.1) (2020-03-05)

**Note:** Version bump only for package amplify-codegen





## [2.13.3](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.13.2...amplify-codegen@2.13.3) (2020-02-13)


### Bug Fixes

* **amplify-codegen:** support appsync scalars in modelgen ([#3424](https://github.com/aws-amplify/amplify-cli/issues/3424)) ([a6eba85](https://github.com/aws-amplify/amplify-cli/commit/a6eba858f2ed31192a1214a22a3180dd243c80c7)), closes [#3296](https://github.com/aws-amplify/amplify-cli/issues/3296)





## [2.13.2](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.13.1...amplify-codegen@2.13.2) (2020-02-07)


### Bug Fixes

* e2e tests, tsconfigs, [@deprecated](https://github.com/deprecated) directive for codegen: ([#3338](https://github.com/aws-amplify/amplify-cli/issues/3338)) ([2ed7715](https://github.com/aws-amplify/amplify-cli/commit/2ed77151dd6367ac9547f78fe600e7913a3d37b2))





## [2.13.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@2.13.0...amplify-codegen@2.13.1) (2020-01-24)

**Note:** Version bump only for package amplify-codegen





# [2.13.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.29.0...amplify-codegen@2.13.0) (2020-01-23)

### Bug Fixes

- **amplify-codegen:** fix headless push with codegen ([#2743](https://github.com/aws-amplify/amplify-cli/issues/2743)) ([da248a4](https://github.com/aws-amplify/amplify-cli/commit/da248a456d96ed37533f964c066651ae22459166))
- **amplify-codegen:** replace upath with slash ([#3133](https://github.com/aws-amplify/amplify-cli/issues/3133)) ([a565053](https://github.com/aws-amplify/amplify-cli/commit/a565053463e563ed3d44f1405ab551520e0cd818)), closes [#3131](https://github.com/aws-amplify/amplify-cli/issues/3131)

### Features

- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **cli:** cLI updates and new features for Amplify Console ([#2742](https://github.com/aws-amplify/amplify-cli/issues/2742)) ([0fd0dd5](https://github.com/aws-amplify/amplify-cli/commit/0fd0dd5102177766c454c8715fa5acac32385048))

# [2.12.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.29.0...amplify-codegen@2.12.0) (2020-01-09)

### Bug Fixes

- **amplify-codegen:** fix headless push with codegen ([#2743](https://github.com/aws-amplify/amplify-cli/issues/2743)) ([da248a4](https://github.com/aws-amplify/amplify-cli/commit/da248a456d96ed37533f964c066651ae22459166))
- **amplify-codegen:** replace upath with slash ([#3133](https://github.com/aws-amplify/amplify-cli/issues/3133)) ([a565053](https://github.com/aws-amplify/amplify-cli/commit/a565053463e563ed3d44f1405ab551520e0cd818)), closes [#3131](https://github.com/aws-amplify/amplify-cli/issues/3131)

### Features

- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **cli:** cLI updates and new features for Amplify Console ([#2742](https://github.com/aws-amplify/amplify-cli/issues/2742)) ([0fd0dd5](https://github.com/aws-amplify/amplify-cli/commit/0fd0dd5102177766c454c8715fa5acac32385048))

# [2.11.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.29.0...amplify-codegen@2.11.0) (2019-12-31)

### Bug Fixes

- **amplify-codegen:** fix headless push with codegen ([#2743](https://github.com/aws-amplify/amplify-cli/issues/2743)) ([da248a4](https://github.com/aws-amplify/amplify-cli/commit/da248a456d96ed37533f964c066651ae22459166))

### Features

- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **cli:** cLI updates and new features for Amplify Console ([#2742](https://github.com/aws-amplify/amplify-cli/issues/2742)) ([0fd0dd5](https://github.com/aws-amplify/amplify-cli/commit/0fd0dd5102177766c454c8715fa5acac32385048))

# [2.10.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.29.0...amplify-codegen@2.10.0) (2019-12-28)

### Bug Fixes

- **amplify-codegen:** fix headless push with codegen ([#2743](https://github.com/aws-amplify/amplify-cli/issues/2743)) ([da248a4](https://github.com/aws-amplify/amplify-cli/commit/da248a456d96ed37533f964c066651ae22459166))

### Features

- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **cli:** cLI updates and new features for Amplify Console ([#2742](https://github.com/aws-amplify/amplify-cli/issues/2742)) ([0fd0dd5](https://github.com/aws-amplify/amplify-cli/commit/0fd0dd5102177766c454c8715fa5acac32385048))

# [2.9.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.29.0...amplify-codegen@2.9.0) (2019-12-26)

### Bug Fixes

- **amplify-codegen:** fix headless push with codegen ([#2743](https://github.com/aws-amplify/amplify-cli/issues/2743)) ([da248a4](https://github.com/aws-amplify/amplify-cli/commit/da248a456d96ed37533f964c066651ae22459166))

### Features

- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **cli:** cLI updates and new features for Amplify Console ([#2742](https://github.com/aws-amplify/amplify-cli/issues/2742)) ([0fd0dd5](https://github.com/aws-amplify/amplify-cli/commit/0fd0dd5102177766c454c8715fa5acac32385048))

# [2.8.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.29.0...amplify-codegen@2.8.0) (2019-12-25)

### Bug Fixes

- **amplify-codegen:** fix headless push with codegen ([#2743](https://github.com/aws-amplify/amplify-cli/issues/2743)) ([da248a4](https://github.com/aws-amplify/amplify-cli/commit/da248a456d96ed37533f964c066651ae22459166))

### Features

- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **cli:** cLI updates and new features for Amplify Console ([#2742](https://github.com/aws-amplify/amplify-cli/issues/2742)) ([0fd0dd5](https://github.com/aws-amplify/amplify-cli/commit/0fd0dd5102177766c454c8715fa5acac32385048))

# [2.7.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.29.0...amplify-codegen@2.7.0) (2019-12-20)

### Bug Fixes

- **amplify-codegen:** fix headless push with codegen ([#2743](https://github.com/aws-amplify/amplify-cli/issues/2743)) ([da248a4](https://github.com/aws-amplify/amplify-cli/commit/da248a456d96ed37533f964c066651ae22459166))

### Features

- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **cli:** cLI updates and new features for Amplify Console ([#2742](https://github.com/aws-amplify/amplify-cli/issues/2742)) ([0fd0dd5](https://github.com/aws-amplify/amplify-cli/commit/0fd0dd5102177766c454c8715fa5acac32385048))

# [2.6.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.29.0...amplify-codegen@2.6.0) (2019-12-10)

### Bug Fixes

- **amplify-codegen:** fix headless push with codegen ([#2743](https://github.com/aws-amplify/amplify-cli/issues/2743)) ([da248a4](https://github.com/aws-amplify/amplify-cli/commit/da248a456d96ed37533f964c066651ae22459166))

### Features

- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **cli:** cLI updates and new features for Amplify Console ([#2742](https://github.com/aws-amplify/amplify-cli/issues/2742)) ([0fd0dd5](https://github.com/aws-amplify/amplify-cli/commit/0fd0dd5102177766c454c8715fa5acac32385048))

# [2.4.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.29.0...amplify-codegen@2.4.0) (2019-12-03)

### Bug Fixes

- **amplify-codegen:** fix headless push with codegen ([#2743](https://github.com/aws-amplify/amplify-cli/issues/2743)) ([da248a4](https://github.com/aws-amplify/amplify-cli/commit/da248a456d96ed37533f964c066651ae22459166))

### Features

- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **cli:** cLI updates and new features for Amplify Console ([#2742](https://github.com/aws-amplify/amplify-cli/issues/2742)) ([0fd0dd5](https://github.com/aws-amplify/amplify-cli/commit/0fd0dd5102177766c454c8715fa5acac32385048))

# [2.3.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.29.0...amplify-codegen@2.3.0) (2019-12-01)

### Bug Fixes

- **amplify-codegen:** fix headless push with codegen ([#2743](https://github.com/aws-amplify/amplify-cli/issues/2743)) ([da248a4](https://github.com/aws-amplify/amplify-cli/commit/da248a456d96ed37533f964c066651ae22459166))

### Features

- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **cli:** cLI updates and new features for Amplify Console ([#2742](https://github.com/aws-amplify/amplify-cli/issues/2742)) ([0fd0dd5](https://github.com/aws-amplify/amplify-cli/commit/0fd0dd5102177766c454c8715fa5acac32385048))

# [2.2.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.29.0...amplify-codegen@2.2.0) (2019-11-27)

### Bug Fixes

- **amplify-codegen:** fix headless push with codegen ([#2743](https://github.com/aws-amplify/amplify-cli/issues/2743)) ([da248a4](https://github.com/aws-amplify/amplify-cli/commit/da248a456d96ed37533f964c066651ae22459166))

### Features

- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **cli:** cLI updates and new features for Amplify Console ([#2742](https://github.com/aws-amplify/amplify-cli/issues/2742)) ([0fd0dd5](https://github.com/aws-amplify/amplify-cli/commit/0fd0dd5102177766c454c8715fa5acac32385048))

# [2.1.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.29.0...amplify-codegen@2.1.0) (2019-11-27)

### Bug Fixes

- **amplify-codegen:** fix headless push with codegen ([#2743](https://github.com/aws-amplify/amplify-cli/issues/2743)) ([da248a4](https://github.com/aws-amplify/amplify-cli/commit/da248a456d96ed37533f964c066651ae22459166))

### Features

- **amplify-codegen-appsync-model-plugin:** modelgen connection support ([#2836](https://github.com/aws-amplify/amplify-cli/issues/2836)) ([353749c](https://github.com/aws-amplify/amplify-cli/commit/353749ce6643a07206a1f4c30d00beb775db169e))
- **cli:** cLI updates and new features for Amplify Console ([#2742](https://github.com/aws-amplify/amplify-cli/issues/2742)) ([0fd0dd5](https://github.com/aws-amplify/amplify-cli/commit/0fd0dd5102177766c454c8715fa5acac32385048))

# [1.11.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.5.7...amplify-codegen@1.11.0) (2019-08-30)

### Bug Fixes

- [#1056](https://github.com/aws-amplify/amplify-cli/issues/1056), dedup environment file reading ([#2088](https://github.com/aws-amplify/amplify-cli/issues/2088)) ([940deaa](https://github.com/aws-amplify/amplify-cli/commit/940deaa))
- local mock fix ([#1982](https://github.com/aws-amplify/amplify-cli/issues/1982)) ([8ee9029](https://github.com/aws-amplify/amplify-cli/commit/8ee9029))
- move test package dependencies to devDependencies ([#2034](https://github.com/aws-amplify/amplify-cli/issues/2034)) ([f5623d0](https://github.com/aws-amplify/amplify-cli/commit/f5623d0))
- **amplify-codegen:** await statement generation before generating types ([#2168](https://github.com/aws-amplify/amplify-cli/issues/2168)) ([4c3aad0](https://github.com/aws-amplify/amplify-cli/commit/4c3aad0)), closes [#2129](https://github.com/aws-amplify/amplify-cli/issues/2129)

### Features

- adding amplify cli predictions category ([#1936](https://github.com/aws-amplify/amplify-cli/issues/1936)) ([b7b7c2c](https://github.com/aws-amplify/amplify-cli/commit/b7b7c2c))
- mock support for API, function and storage ([#1893](https://github.com/aws-amplify/amplify-cli/issues/1893)) ([372e534](https://github.com/aws-amplify/amplify-cli/commit/372e534))

# [1.10.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.5.7...amplify-codegen@1.10.0) (2019-08-28)

### Bug Fixes

- [#1056](https://github.com/aws-amplify/amplify-cli/issues/1056), dedup environment file reading ([#2088](https://github.com/aws-amplify/amplify-cli/issues/2088)) ([940deaa](https://github.com/aws-amplify/amplify-cli/commit/940deaa))
- local mock fix ([#1982](https://github.com/aws-amplify/amplify-cli/issues/1982)) ([8ee9029](https://github.com/aws-amplify/amplify-cli/commit/8ee9029))
- move test package dependencies to devDependencies ([#2034](https://github.com/aws-amplify/amplify-cli/issues/2034)) ([f5623d0](https://github.com/aws-amplify/amplify-cli/commit/f5623d0))

### Features

- adding amplify cli predictions category ([#1936](https://github.com/aws-amplify/amplify-cli/issues/1936)) ([b7b7c2c](https://github.com/aws-amplify/amplify-cli/commit/b7b7c2c))
- mock support for API, function and storage ([#1893](https://github.com/aws-amplify/amplify-cli/issues/1893)) ([372e534](https://github.com/aws-amplify/amplify-cli/commit/372e534))

# [1.9.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.5.7...amplify-codegen@1.9.0) (2019-08-13)

### Bug Fixes

- local mock fix ([#1982](https://github.com/aws-amplify/amplify-cli/issues/1982)) ([8ee9029](https://github.com/aws-amplify/amplify-cli/commit/8ee9029))

### Features

- adding amplify cli predictions category ([#1936](https://github.com/aws-amplify/amplify-cli/issues/1936)) ([b7b7c2c](https://github.com/aws-amplify/amplify-cli/commit/b7b7c2c))
- mock support for API, function and storage ([#1893](https://github.com/aws-amplify/amplify-cli/issues/1893)) ([372e534](https://github.com/aws-amplify/amplify-cli/commit/372e534))

# [1.8.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.5.7...amplify-codegen@1.8.0) (2019-08-07)

### Bug Fixes

- local mock fix ([#1982](https://github.com/aws-amplify/amplify-cli/issues/1982)) ([8ee9029](https://github.com/aws-amplify/amplify-cli/commit/8ee9029))

### Features

- adding amplify cli predictions category ([#1936](https://github.com/aws-amplify/amplify-cli/issues/1936)) ([b7b7c2c](https://github.com/aws-amplify/amplify-cli/commit/b7b7c2c))
- mock support for API, function and storage ([#1893](https://github.com/aws-amplify/amplify-cli/issues/1893)) ([372e534](https://github.com/aws-amplify/amplify-cli/commit/372e534))

# [1.7.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.5.7...amplify-codegen@1.7.0) (2019-08-02)

### Features

- adding amplify cli predictions category ([#1936](https://github.com/aws-amplify/amplify-cli/issues/1936)) ([b7b7c2c](https://github.com/aws-amplify/amplify-cli/commit/b7b7c2c))

# [1.6.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.5.7...amplify-codegen@1.6.0) (2019-07-31)

### Features

- adding amplify cli predictions category ([#1936](https://github.com/aws-amplify/amplify-cli/issues/1936)) ([b7b7c2c](https://github.com/aws-amplify/amplify-cli/commit/b7b7c2c))

## [1.5.7](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.5.6...amplify-codegen@1.5.7) (2019-07-23)

### Bug Fixes

- **amplify-codegen:** fix cross os issue ([#1741](https://github.com/aws-amplify/amplify-cli/issues/1741)) ([ae20d0d](https://github.com/aws-amplify/amplify-cli/commit/ae20d0d)), closes [#1522](https://github.com/aws-amplify/amplify-cli/issues/1522)

## [1.5.6](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.5.5...amplify-codegen@1.5.6) (2019-06-20)

### Bug Fixes

- **cli:** fix inquirer version ([#1690](https://github.com/aws-amplify/amplify-cli/issues/1690)) ([9246032](https://github.com/aws-amplify/amplify-cli/commit/9246032)), closes [#1688](https://github.com/aws-amplify/amplify-cli/issues/1688)

## [1.5.5](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.5.4...amplify-codegen@1.5.5) (2019-06-12)

**Note:** Version bump only for package amplify-codegen

## [1.5.4](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.5.3...amplify-codegen@1.5.4) (2019-06-11)

**Note:** Version bump only for package amplify-codegen

## [1.5.3](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.5.2...amplify-codegen@1.5.3) (2019-06-06)

**Note:** Version bump only for package amplify-codegen

## [1.5.2](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.5.1...amplify-codegen@1.5.2) (2019-05-21)

### Bug Fixes

- **amplify-codegen:** auto detect S3Object in swift codegen ([#1482](https://github.com/aws-amplify/amplify-cli/issues/1482)) ([ea2de2d](https://github.com/aws-amplify/amplify-cli/commit/ea2de2d)), closes [#1468](https://github.com/aws-amplify/amplify-cli/issues/1468)

## [1.5.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.5.0...amplify-codegen@1.5.1) (2019-05-17)

**Note:** Version bump only for package amplify-codegen

# [1.5.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.4.2...amplify-codegen@1.5.0) (2019-04-30)

### Bug Fixes

- **amplify-codegen:** make codegen multienv aware ([b146c77](https://github.com/aws-amplify/amplify-cli/commit/b146c77)), closes [#1243](https://github.com/aws-amplify/amplify-cli/issues/1243)

### Features

- Multiauth external api add ([#1329](https://github.com/aws-amplify/amplify-cli/issues/1329)) ([13d9fc3](https://github.com/aws-amplify/amplify-cli/commit/13d9fc3))

## [1.4.2](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.4.1...amplify-codegen@1.4.2) (2019-04-16)

**Note:** Version bump only for package amplify-codegen

## [1.4.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.3.1...amplify-codegen@1.4.1) (2019-04-09)

**Note:** Version bump only for package amplify-codegen

## [1.3.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.0.10...amplify-codegen@1.3.1) (2019-04-03)

### Bug Fixes

- **amplify-cli:** promise not resolving in lts/dubnium ([#1028](https://github.com/aws-amplify/amplify-cli/issues/1028)) ([8a966be](https://github.com/aws-amplify/amplify-cli/commit/8a966be))

## [1.0.10](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.0.9...amplify-codegen@1.0.10) (2019-03-05)

### Bug Fixes

- **amplify-codegen:** use path relative to project root for codegen ([#951](https://github.com/aws-amplify/amplify-cli/issues/951)) ([7b52efb](https://github.com/aws-amplify/amplify-cli/commit/7b52efb)), closes [#886](https://github.com/aws-amplify/amplify-cli/issues/886)

## [1.0.9](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.0.8...amplify-codegen@1.0.9) (2019-02-20)

**Note:** Version bump only for package amplify-codegen

## [1.0.8](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.0.6...amplify-codegen@1.0.8) (2019-02-15)

**Note:** Version bump only for package amplify-codegen

## [1.0.7](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.0.6...amplify-codegen@1.0.7) (2019-02-14)

**Note:** Version bump only for package amplify-codegen

## [1.0.6](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.0.5...amplify-codegen@1.0.6) (2019-02-12)

**Note:** Version bump only for package amplify-codegen

## [1.0.5](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.0.3-beta.0...amplify-codegen@1.0.5) (2019-02-11)

**Note:** Version bump only for package amplify-codegen

## [1.0.3](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.0.3-beta.0...amplify-codegen@1.0.3) (2019-02-11)

**Note:** Version bump only for package amplify-codegen

## [1.0.3-beta.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@1.0.2...amplify-codegen@1.0.3-beta.0) (2019-02-11)

**Note:** Version bump only for package amplify-codegen

<a name="0.2.1-multienv.7"></a>

## [0.2.1-multienv.7](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.2.1-multienv.6...amplify-codegen@0.2.1-multienv.7) (2019-01-24)

**Note:** Version bump only for package amplify-codegen

<a name="0.2.1-multienv.6"></a>

## [0.2.1-multienv.6](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.2.1-multienv.5...amplify-codegen@0.2.1-multienv.6) (2019-01-22)

### Bug Fixes

- **amplify-codegen:** hide types gen message for JS ([bd39555](https://github.com/aws-amplify/amplify-cli/commit/bd39555))

<a name="0.2.1-multienv.5"></a>

## [0.2.1-multienv.5](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.2.1-multienv.4...amplify-codegen@0.2.1-multienv.5) (2019-01-16)

**Note:** Version bump only for package amplify-codegen

<a name="0.2.1-multienv.4"></a>

## [0.2.1-multienv.4](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.2.1-multienv.3...amplify-codegen@0.2.1-multienv.4) (2018-12-27)

**Note:** Version bump only for package amplify-codegen

<a name="0.2.1-multienv.3"></a>

## [0.2.1-multienv.3](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.2.1-multienv.2...amplify-codegen@0.2.1-multienv.3) (2018-12-10)

**Note:** Version bump only for package amplify-codegen

<a name="0.2.1-multienv.2"></a>

## [0.2.1-multienv.2](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.2.1-multienv.1...amplify-codegen@0.2.1-multienv.2) (2018-12-04)

**Note:** Version bump only for package amplify-codegen

<a name="0.2.1-multienv.1"></a>

## [0.2.1-multienv.1](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.2.1-multienv.0...amplify-codegen@0.2.1-multienv.1) (2018-11-30)

### Features

- **amplify-codegen:** add remove support ([#510](https://github.com/aws-amplify/amplify-cli/issues/510)) ([#521](https://github.com/aws-amplify/amplify-cli/issues/521)) ([21e6b7e](https://github.com/aws-amplify/amplify-cli/commit/21e6b7e))

<a name="0.2.1-multienv.0"></a>

## [0.2.1-multienv.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.35-multienv.0...amplify-codegen@0.2.1-multienv.0) (2018-11-21)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.35-multienv.0"></a>

## [0.1.35-multienv.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.34...amplify-codegen@0.1.35-multienv.0) (2018-11-16)

### Bug Fixes

- fix projectPath references in ios and codegen packages & fix for correct AWS profile pickup in the cloudformation provider ([a73656e](https://github.com/aws-amplify/amplify-cli/commit/a73656e))
- **amplify-codgen:** codegen headless support ([#452](https://github.com/aws-amplify/amplify-cli/issues/452)) ([bbb27c3](https://github.com/aws-amplify/amplify-cli/commit/bbb27c3))

### Features

- headless Init and configure ([#371](https://github.com/aws-amplify/amplify-cli/issues/371)) ([acd14a8](https://github.com/aws-amplify/amplify-cli/commit/acd14a8))

<a name="0.1.34"></a>

## [0.1.34](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.34-beta.0...amplify-codegen@0.1.34) (2018-11-13)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.34-beta.0"></a>

## [0.1.34-beta.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.33...amplify-codegen@0.1.34-beta.0) (2018-11-13)

### Bug Fixes

- **amplify-codegen:** update the params passed to types generator ([#442](https://github.com/aws-amplify/amplify-cli/issues/442)) ([9b87c74](https://github.com/aws-amplify/amplify-cli/commit/9b87c74)), closes [in#434](https://github.com/in/issues/434) [#434](https://github.com/aws-amplify/amplify-cli/issues/434)

<a name="0.1.33"></a>

## [0.1.33](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.33-beta.0...amplify-codegen@0.1.33) (2018-11-09)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.33-beta.0"></a>

## [0.1.33-beta.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.13...amplify-codegen@0.1.33-beta.0) (2018-11-09)

### Features

- **amplify-codegen:** add angular codegen support ([7dd7259](https://github.com/aws-amplify/amplify-cli/commit/7dd7259))

<a name="0.1.32"></a>

## [0.1.32](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.32-beta.0...amplify-codegen@0.1.32) (2018-11-05)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.32-beta.0"></a>

## [0.1.32-beta.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.13...amplify-codegen@0.1.32-beta.0) (2018-11-05)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.31"></a>

## [0.1.31](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.13...amplify-codegen@0.1.31) (2018-11-02)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.30"></a>

## [0.1.30](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.30-beta.0...amplify-codegen@0.1.30) (2018-11-02)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.30-beta.0"></a>

## [0.1.30-beta.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.13...amplify-codegen@0.1.30-beta.0) (2018-11-02)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.29"></a>

## [0.1.29](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.29-beta.0...amplify-codegen@0.1.29) (2018-10-23)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.29-beta.0"></a>

## [0.1.29-beta.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.13...amplify-codegen@0.1.29-beta.0) (2018-10-23)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.28"></a>

## [0.1.28](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.28-beta.0...amplify-codegen@0.1.28) (2018-10-18)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.28-beta.0"></a>

## [0.1.28-beta.0](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.13...amplify-codegen@0.1.28-beta.0) (2018-10-12)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.13"></a>

## [0.1.13](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.12...amplify-codegen@0.1.13) (2018-08-23)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.12"></a>

## [0.1.12](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.11...amplify-codegen@0.1.12) (2018-08-23)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.11"></a>

## [0.1.11](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.9...amplify-codegen@0.1.11) (2018-08-23)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.9"></a>

## [0.1.9](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.8...amplify-codegen@0.1.9) (2018-08-23)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.8"></a>

## [0.1.8](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.7...amplify-codegen@0.1.8) (2018-08-23)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.7"></a>

## [0.1.7](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.6...amplify-codegen@0.1.7) (2018-08-23)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.6"></a>

## [0.1.6](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.5...amplify-codegen@0.1.6) (2018-08-23)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.5"></a>

## [0.1.5](https://github.com/aws-amplify/amplify-cli/compare/amplify-codegen@0.1.4...amplify-codegen@0.1.5) (2018-08-23)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.4"></a>

## 0.1.4 (2018-08-23)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.3"></a>

## 0.1.3 (2018-08-23)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.2"></a>

## 0.1.2 (2018-08-23)

**Note:** Version bump only for package amplify-codegen

<a name="0.1.1"></a>

## 0.1.1 (2018-08-23)

**Note:** Version bump only for package amplify-codegen
