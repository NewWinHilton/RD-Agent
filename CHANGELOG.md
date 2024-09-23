# Changelog

## [0.3.0](https://github.com/microsoft/RD-Agent/compare/v0.2.1...v0.3.0) (2024-09-23)


### Features

* add a new template for kaggle ([#289](https://github.com/microsoft/RD-Agent/issues/289)) ([eee3ab5](https://github.com/microsoft/RD-Agent/commit/eee3ab5b25198224826cb7a8a17eab28bd5d1f7d))
* add kaggle command ([#271](https://github.com/microsoft/RD-Agent/issues/271)) ([0938394](https://github.com/microsoft/RD-Agent/commit/0938394b7084ffbf3294d8c23d2d34bf7322ca0b))
* add more templates for kaggle ([#291](https://github.com/microsoft/RD-Agent/issues/291)) ([da752ec](https://github.com/microsoft/RD-Agent/commit/da752ec806e6f5f5679bc27ac1c072ed9a319251))
* Add runtime measurement for each step and loop in RDLoop. ([#281](https://github.com/microsoft/RD-Agent/issues/281)) ([83058c8](https://github.com/microsoft/RD-Agent/commit/83058c864ceeec413dd29bf501030d5a7bd34679))
* Added RepoAnalyzer to empower auto-summary of a workspace ([#264](https://github.com/microsoft/RD-Agent/issues/264)) ([0bd349a](https://github.com/microsoft/RD-Agent/commit/0bd349af50b9b881ba1774bdeb4d723529ef2aa9))
* Added support for loading and storing RAG in Kaggle scenarios. ([#269](https://github.com/microsoft/RD-Agent/issues/269)) ([c4895de](https://github.com/microsoft/RD-Agent/commit/c4895de83f1ed000e563d42b3468a6bd9e5a4965))
* Factor Implement Search Enhancement ([#294](https://github.com/microsoft/RD-Agent/issues/294)) ([4ecf25f](https://github.com/microsoft/RD-Agent/commit/4ecf25f0acf2389a172b14d3dab20895daf2ab89))
* Feature selection v3 to support all actions  ([#280](https://github.com/microsoft/RD-Agent/issues/280)) ([0047641](https://github.com/microsoft/RD-Agent/commit/00476413fbf00e36e71ab3ccb48d4e766b6ccf4d))
* fix some bugs and add original features' description ([#259](https://github.com/microsoft/RD-Agent/issues/259)) ([1a5f45a](https://github.com/microsoft/RD-Agent/commit/1a5f45a40d821c017bdba14af8c93710707c5ea5))
* Initial version if Graph RAG in KAGGLE scenario ([#301](https://github.com/microsoft/RD-Agent/issues/301)) ([fd3c0fd](https://github.com/microsoft/RD-Agent/commit/fd3c0fd26eff7d3be72fa4f2a234e33b9f796627))
* Integrate RAG into the Kaggle scenarios. ([#262](https://github.com/microsoft/RD-Agent/issues/262)) ([be0e48a](https://github.com/microsoft/RD-Agent/commit/be0e48a7dfbee2b5d2947d09115db5db2e5266f1))
* Kaggle loop update (Feature & Model) ([#241](https://github.com/microsoft/RD-Agent/issues/241)) ([4cf22a6](https://github.com/microsoft/RD-Agent/commit/4cf22a65c964123b4267569ee02c0c7094c54ca4))
* kaggle templates related ([#287](https://github.com/microsoft/RD-Agent/issues/287)) ([785fdc1](https://github.com/microsoft/RD-Agent/commit/785fdc144d16fa8454b7c9d2e53e78fe7f22a29a))
* Model context for tuning and selection ([#284](https://github.com/microsoft/RD-Agent/issues/284)) ([f2831e7](https://github.com/microsoft/RD-Agent/commit/f2831e7442510668b0ca75953b3359894803ef3c))
* refine the code in model description and fix some bugs in feedback.py ([#288](https://github.com/microsoft/RD-Agent/issues/288)) ([5b124d7](https://github.com/microsoft/RD-Agent/commit/5b124d7372137e4c613eb2749ddcc773922cc7b6))


### Bug Fixes

* actively raised errors aer also considered as negative feedback. ([#268](https://github.com/microsoft/RD-Agent/issues/268)) ([46ec908](https://github.com/microsoft/RD-Agent/commit/46ec908e3594ac5e4cdc4057268e2f8800f5ed1f))
* eval_method cannot catch run factor error ([#260](https://github.com/microsoft/RD-Agent/issues/260)) ([2aaab31](https://github.com/microsoft/RD-Agent/commit/2aaab317ccb7a0121063bcd85fc36c21c7b8a391))
* fix some bugs in feedback.py and refine the prompt ([#292](https://github.com/microsoft/RD-Agent/issues/292)) ([d834052](https://github.com/microsoft/RD-Agent/commit/d8340527f133dcc649d599d90d6402eddd37859e))
* fix some bugs in the entire loop ([#274](https://github.com/microsoft/RD-Agent/issues/274)) ([8a564ec](https://github.com/microsoft/RD-Agent/commit/8a564ece1d87b27ee98b76db317935e802468965))
* improve_execution_time_in_kaggle_loop ([#279](https://github.com/microsoft/RD-Agent/issues/279)) ([4c8f998](https://github.com/microsoft/RD-Agent/commit/4c8f998c76f1e983a5687d2c65d3251750f2a9a0))
* kaggle data mount problem ([#297](https://github.com/microsoft/RD-Agent/issues/297)) ([795df31](https://github.com/microsoft/RD-Agent/commit/795df311e3f93cd2f3fb51ba5698adaf10f6bd62))
* refactor Bench ([#302](https://github.com/microsoft/RD-Agent/issues/302)) ([78a87f6](https://github.com/microsoft/RD-Agent/commit/78a87f624780ff67c0fa995ae4692678a120f99c))
* refine the prompt ([#286](https://github.com/microsoft/RD-Agent/issues/286)) ([77966c4](https://github.com/microsoft/RD-Agent/commit/77966c4f5e9f492c437c5b4b78d89c0f875ef0d8))
* support seed and fix absolute path ([#278](https://github.com/microsoft/RD-Agent/issues/278)) ([26352e1](https://github.com/microsoft/RD-Agent/commit/26352e13121cad5be95c0de78bb9f5dda4330614))
* test kaggle method ([#296](https://github.com/microsoft/RD-Agent/issues/296)) ([91a6196](https://github.com/microsoft/RD-Agent/commit/91a619618be1d7db660ea2b413a78dfaba9417a1))
* update code to fix a small bug in model cache md5 hash ([#303](https://github.com/microsoft/RD-Agent/issues/303)) ([b00e4dc](https://github.com/microsoft/RD-Agent/commit/b00e4dc2eff5b16029a2a12a6589eadac5cfd148))
* update new feature engineering code format ([#272](https://github.com/microsoft/RD-Agent/issues/272)) ([7850b80](https://github.com/microsoft/RD-Agent/commit/7850b8006a7c89d22629b345b4f361b0f35bc60d))
* Update runner.py to fix a small bug ([#282](https://github.com/microsoft/RD-Agent/issues/282)) ([8aef3ab](https://github.com/microsoft/RD-Agent/commit/8aef3abcecd6002bd4bfeedcbe2c786d8bbfe2be))

## [0.2.1](https://github.com/microsoft/RD-Agent/compare/v0.2.0...v0.2.1) (2024-09-10)


### Bug Fixes

* default model value in config ([#256](https://github.com/microsoft/RD-Agent/issues/256)) ([c097585](https://github.com/microsoft/RD-Agent/commit/c097585f631f401c2c0966f6ad4c17286924f011))
* fix_dotenv_error ([#257](https://github.com/microsoft/RD-Agent/issues/257)) ([923063c](https://github.com/microsoft/RD-Agent/commit/923063c1fd957c4ed42e97272c72b5e9545451dc))
* readme ([#248](https://github.com/microsoft/RD-Agent/issues/248)) ([8cede22](https://github.com/microsoft/RD-Agent/commit/8cede2209922876490148459e1134da828e1fda0))

## [0.2.0](https://github.com/microsoft/RD-Agent/compare/v0.1.0...v0.2.0) (2024-09-07)


### Features

* add collect info ([#233](https://github.com/microsoft/RD-Agent/issues/233)) ([89f4af9](https://github.com/microsoft/RD-Agent/commit/89f4af90fb4d95a0689bf9efc8ffd9326469c0aa))
* add cross validation for kaggle scenario ([#236](https://github.com/microsoft/RD-Agent/issues/236)) ([e0b03ba](https://github.com/microsoft/RD-Agent/commit/e0b03ba6b5c3d9aa552b99d470e106d4e348e64d))
* add progress status for docker env ([#215](https://github.com/microsoft/RD-Agent/issues/215)) ([538d4ef](https://github.com/microsoft/RD-Agent/commit/538d4ef2e52de795b90d3f75b2e1e877ab85c18d))
* Added loop code for Kaggle scene. ([#211](https://github.com/microsoft/RD-Agent/issues/211)) ([975c327](https://github.com/microsoft/RD-Agent/commit/975c32715e51aec6b49537401f5fc59115e04a01))
* Demo display effect and usage ([#162](https://github.com/microsoft/RD-Agent/issues/162)) ([8cf122a](https://github.com/microsoft/RD-Agent/commit/8cf122a0155f434fa4477ae7a6d616b5caecd3e0))
* piloting of the framework ([#227](https://github.com/microsoft/RD-Agent/issues/227)) ([e9b103e](https://github.com/microsoft/RD-Agent/commit/e9b103e684fdd2b98cd1a89971a3fce2d6e884a1))
* support more models for kaggle scenario ([#223](https://github.com/microsoft/RD-Agent/issues/223)) ([e3a9659](https://github.com/microsoft/RD-Agent/commit/e3a96598c0720fe092ec86d7ca8c195c7d6bcc72))
* update model_experiment.py to support basic EDA ([#220](https://github.com/microsoft/RD-Agent/issues/220)) ([bf2684c](https://github.com/microsoft/RD-Agent/commit/bf2684c4d55ab8e1048ac0291695475ad53b0cd6))


### Bug Fixes

* fix some bugs in llm calling ([#217](https://github.com/microsoft/RD-Agent/issues/217)) ([7b010f8](https://github.com/microsoft/RD-Agent/commit/7b010f8b5940aba65a58f1d78192aa80bcd0e654))
* package dependency. ([#234](https://github.com/microsoft/RD-Agent/issues/234)) ([46be295](https://github.com/microsoft/RD-Agent/commit/46be2952952af534fd8d98a656c704c688d7cbdd))
* remove useless line ([#177](https://github.com/microsoft/RD-Agent/issues/177)) ([64e9a8e](https://github.com/microsoft/RD-Agent/commit/64e9a8e39a2072a962111db18f5b9565df5b0176))

## [0.1.0](https://github.com/microsoft/RD-Agent/compare/v0.0.1...v0.1.0) (2024-08-09)


### Features

* add entry for rdagent. ([#187](https://github.com/microsoft/RD-Agent/issues/187)) ([121b6d9](https://github.com/microsoft/RD-Agent/commit/121b6d98de38cd03be30cbee47b40baf39a2b60b))
* change ui entry ([#197](https://github.com/microsoft/RD-Agent/issues/197)) ([fa5d335](https://github.com/microsoft/RD-Agent/commit/fa5d3354d22240888f4fc4007d9834f7424632aa))
* remove pdfs and enable online pdf readings ([#183](https://github.com/microsoft/RD-Agent/issues/183)) ([18c0501](https://github.com/microsoft/RD-Agent/commit/18c05016a23d694c7b12759cf1322562dcffc56a))


### Bug Fixes

* Fix a fail href in readme ([#189](https://github.com/microsoft/RD-Agent/issues/189)) ([1b89218](https://github.com/microsoft/RD-Agent/commit/1b89218f6bc697494f4a1b8a42ad18963002714f))
* fix quick start problem ([#191](https://github.com/microsoft/RD-Agent/issues/191)) ([44f61bf](https://github.com/microsoft/RD-Agent/commit/44f61bfa1058a8efb59ca48b7f1417765aeea33e))
* update command line in readme.md ([#192](https://github.com/microsoft/RD-Agent/issues/192)) ([9c45d24](https://github.com/microsoft/RD-Agent/commit/9c45d24a192da02f7d9765cb001097da1bc36c61))

## 0.0.1 (2024-08-08)


### Features

* Add description for scenario experiments. ([#174](https://github.com/microsoft/RD-Agent/issues/174)) ([fbd8c6d](https://github.com/microsoft/RD-Agent/commit/fbd8c6d87e1424c08997103b8e8fbf264858c4ed))
* Added QlibFactorFromReportScenario and improved the report-factor loop. ([#161](https://github.com/microsoft/RD-Agent/issues/161)) ([882c79b](https://github.com/microsoft/RD-Agent/commit/882c79bf11583980e646b130f71cfa20201ffc7b))
* filter feature which is high correlation to former implemented features ([#145](https://github.com/microsoft/RD-Agent/issues/145)) ([e818326](https://github.com/microsoft/RD-Agent/commit/e818326422740e04a4863f7c3c18744dde2ad98f))
* Remove redundant 'key steps' section in frontend scene display. ([#169](https://github.com/microsoft/RD-Agent/issues/169)) ([e767005](https://github.com/microsoft/RD-Agent/commit/e76700513bee29232c93b97414419df330d9be8d))
* streamlit webapp demo for different scenarios ([#135](https://github.com/microsoft/RD-Agent/issues/135)) ([d8da7db](https://github.com/microsoft/RD-Agent/commit/d8da7db865e6653fc4740efee9a843b69bd79699))
* Uploaded Documentation, Updated Prompts & Some Code for model demo ([#144](https://github.com/microsoft/RD-Agent/issues/144)) ([529f935](https://github.com/microsoft/RD-Agent/commit/529f935aa98623f0dc1dda29eecee3ef738dd446))


### Bug Fixes

* Add framework handling for task coding failure. ([#176](https://github.com/microsoft/RD-Agent/issues/176)) ([5e14fa5](https://github.com/microsoft/RD-Agent/commit/5e14fa54a9dd30a94aebe2643b8c9a3b85517a11))
* Comprehensive update to factor extraction. ([#143](https://github.com/microsoft/RD-Agent/issues/143)) ([b5ea040](https://github.com/microsoft/RD-Agent/commit/b5ea04019fd5fa15c0f8b9a7e4f18f490f7057d4))
* first round app folder cleaning ([#166](https://github.com/microsoft/RD-Agent/issues/166)) ([6a5a750](https://github.com/microsoft/RD-Agent/commit/6a5a75021912927deb5e8e4c7ad3ec4b51bfc788))
* fix pickle problem ([#140](https://github.com/microsoft/RD-Agent/issues/140)) ([7ee4258](https://github.com/microsoft/RD-Agent/commit/7ee42587b60d94417f34332cee395cf210dc8a0e))
* fix release CI ([#165](https://github.com/microsoft/RD-Agent/issues/165)) ([85d6a5e](https://github.com/microsoft/RD-Agent/commit/85d6a5ed91113fda34ae079b23c89aa24acd2cb2))
* fix release CI error ([#160](https://github.com/microsoft/RD-Agent/issues/160)) ([1c9f8ef](https://github.com/microsoft/RD-Agent/commit/1c9f8ef287961731944acc9008496b4dddeddca7))
* fix several bugs in data mining scenario ([#147](https://github.com/microsoft/RD-Agent/issues/147)) ([b233380](https://github.com/microsoft/RD-Agent/commit/b233380e2c66fb030db39424f0f040c86e37f5c4))
* fix some small bugs in report-factor loop ([#152](https://github.com/microsoft/RD-Agent/issues/152)) ([a79f9f9](https://github.com/microsoft/RD-Agent/commit/a79f9f93406aff6305a76e6a6abd3852642e4c62))
* fix_release_ci_error ([#150](https://github.com/microsoft/RD-Agent/issues/150)) ([4f82e99](https://github.com/microsoft/RD-Agent/commit/4f82e9960a2638af9d831581185ddd3bac5711fc))
* Fixed some bugs introduced during refactoring. ([#167](https://github.com/microsoft/RD-Agent/issues/167)) ([f8f1445](https://github.com/microsoft/RD-Agent/commit/f8f1445283fb89aefeb2918243c35a219a51a56c))
* optimize some prompts in factor loop. ([#158](https://github.com/microsoft/RD-Agent/issues/158)) ([c2c1330](https://github.com/microsoft/RD-Agent/commit/c2c13300b9ad315a663ec2d0eada414e56c6f54f))


### Miscellaneous Chores

* release 0.0.1 ([1feacd3](https://github.com/microsoft/RD-Agent/commit/1feacd39b21193de11e9bbecf880ddf96d7c261c))
