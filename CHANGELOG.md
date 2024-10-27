## [0.3.3](https://github.com/LetsStreamIt/profile-service/compare/v0.3.2...v0.3.3) (2024-10-27)

### Bug Fixes

* wrong host for docker compose ([bca815f](https://github.com/LetsStreamIt/profile-service/commit/bca815f14aef53ac68b42186d207d1e9e9fa4f2a))

## [0.3.2](https://github.com/LetsStreamIt/profile-service/compare/v0.3.1...v0.3.2) (2024-10-27)

### Bug Fixes

* added possibility of getting server port from env ([0596fe1](https://github.com/LetsStreamIt/profile-service/commit/0596fe1a34f5dca3f081f6ba968d504134daf02c))

### General maintenance

* add error messages in auth service requests ([7e8aded](https://github.com/LetsStreamIt/profile-service/commit/7e8adedc9ad2872919b83fcf9792bc33e351b4bb))
* add logger ([5c9e3ac](https://github.com/LetsStreamIt/profile-service/commit/5c9e3ac2d813c379c068a3c2b49715599b7676b6))

## [0.3.1](https://github.com/LetsStreamIt/profile-service/compare/v0.3.0...v0.3.1) (2024-10-27)

### Bug Fixes

* cors settings ([279baf2](https://github.com/LetsStreamIt/profile-service/commit/279baf2ecef1cc47b67b02a91251c6c6d3bd55e3))

## [0.3.0](https://github.com/LetsStreamIt/profile-service/compare/v0.2.3...v0.3.0) (2024-10-27)

### Features

* added healthcheck ([bc89a64](https://github.com/LetsStreamIt/profile-service/commit/bc89a649cc85dc9aafebbcac7b651aed1a6c14dc))

### Dependency updates

* **deps:** update dependency ch.qos.logback:logback-classic to v1.5.12 ([a4e574e](https://github.com/LetsStreamIt/profile-service/commit/a4e574e1a61ae40344a19b5ab53e43f0b2b316fa))

### Build and continuous integration

* change docker image upload method ([36beecc](https://github.com/LetsStreamIt/profile-service/commit/36beeccba87befb6660d4bbf3ed7a97582658f4e))
* **deps:** update docker/build-push-action digest to 5e99dac ([3867be8](https://github.com/LetsStreamIt/profile-service/commit/3867be87c36cf9a88f2177dd2e3065c56fbfe75a))
* **deps:** update docker/login-action digest to 0689575 ([20db644](https://github.com/LetsStreamIt/profile-service/commit/20db64485e61e66e5b1d53acb5a2d8df241fe3bd))
* **deps:** update docker/metadata-action digest to d31acd5 ([8dfda56](https://github.com/LetsStreamIt/profile-service/commit/8dfda56f3762324d415af1b004672481c347d403))
* fix check if release happened ([3954c3a](https://github.com/LetsStreamIt/profile-service/commit/3954c3a5ca14481af98b7e668c28ff3fff792c99))
* fix repository name ([f156a3b](https://github.com/LetsStreamIt/profile-service/commit/f156a3b4b997799566b42d79e657c1110d23122d))
* revert release docs and docker image only when a new release is made ([e9d0800](https://github.com/LetsStreamIt/profile-service/commit/e9d0800f1940a210d381f27ae65ac46c37b5ffba))

### General maintenance

* update package-lock ([6cbd7d3](https://github.com/LetsStreamIt/profile-service/commit/6cbd7d3ec0caa478c6a81eae2f367ed73e367e3e))

## [0.2.3](https://github.com/LetsStreamIt/profile-service/compare/v0.2.2...v0.2.3) (2024-10-25)

### Dependency updates

* **deps:** update dependency semantic-release-preconfigured-conventional-commits to v1.1.112 ([d17658f](https://github.com/LetsStreamIt/profile-service/commit/d17658fcbbc2cdf290ed56173ff8f778250cc4c1))

### Bug Fixes

* **dockerfile:** add compilation step ([cbe5fbe](https://github.com/LetsStreamIt/profile-service/commit/cbe5fbe4d4cb4125c59a6245d7b232884519f163))

### Build and continuous integration

* **deps:** update actions/checkout action to v4.2.2 ([a7192f4](https://github.com/LetsStreamIt/profile-service/commit/a7192f4b48c9a9278a7351020a54a34b56910c1a))
* **deps:** update actions/setup-java action to v4.5.0 ([5bb47b3](https://github.com/LetsStreamIt/profile-service/commit/5bb47b3e0ddfb39d8388889bf8644565b09e2d18))
* **deps:** update actions/setup-node action to v4.1.0 ([32b5f78](https://github.com/LetsStreamIt/profile-service/commit/32b5f786d0b7edf8ca0f8a5b8407d6ddcd923c93))
* **deps:** update danysk/action-checkout action to v0.2.22 ([cec5430](https://github.com/LetsStreamIt/profile-service/commit/cec54308e40163e3227847289090e2aa9ddc5db9))
* **deps:** update docker/login-action digest to 5d8785b ([b9d80a2](https://github.com/LetsStreamIt/profile-service/commit/b9d80a27c88fbfd823ed108f98edc004f0473ac6))
* **deps:** update sbt/setup-sbt action to v1.1.2 ([a5cd8cf](https://github.com/LetsStreamIt/profile-service/commit/a5cd8cf126c8324979f674bdee3697168645a1cd))
* release docs and docker image only when a new release is made ([fe6718b](https://github.com/LetsStreamIt/profile-service/commit/fe6718b8f05163de7e9aae304901fe1631999a4b))

## [0.2.2](https://github.com/LetsStreamIt/profile-service/compare/v0.2.1...v0.2.2) (2024-10-23)

### Documentation

* added initial documentation ([37dc066](https://github.com/LetsStreamIt/profile-service/commit/37dc0661e1edccad066d728a58505751e7ddc698))

### Build and continuous integration

* add akka license key ([4b6d7d9](https://github.com/LetsStreamIt/profile-service/commit/4b6d7d9b0ea1533d38329f679acae62739acb328))
* added automatic docs upload ([69506c7](https://github.com/LetsStreamIt/profile-service/commit/69506c7679b4ba155ddc3e27a0305cf51921f566))
* added docker package publish ([a6ae614](https://github.com/LetsStreamIt/profile-service/commit/a6ae6143ac8cff3a1d7054427df8b23f723c3ae3))
* fix ' typo ([0dd8c9e](https://github.com/LetsStreamIt/profile-service/commit/0dd8c9ec2056937a4fd53afa9a725524a9a2afe5))
* fixed deploy image ([9543e53](https://github.com/LetsStreamIt/profile-service/commit/9543e537038a500942137d3ebdb68346a912153b))
* fixed registry and image name on docker image publish ([61af9e3](https://github.com/LetsStreamIt/profile-service/commit/61af9e3e586a2010f668e483d6ed75539f2ae015))
* fixed scala version output ([fc45e52](https://github.com/LetsStreamIt/profile-service/commit/fc45e52eac5627390a61bd75f3056f540599d080))
* fixed scala version output ([b0240f4](https://github.com/LetsStreamIt/profile-service/commit/b0240f4fd959b258e6feb33d06ddb099e4405277))
* fixed typo on docs build ([e839277](https://github.com/LetsStreamIt/profile-service/commit/e839277c928d71c46260ecc09e6ffebf666c6c19))
* removed apices around scala version ([375e4bd](https://github.com/LetsStreamIt/profile-service/commit/375e4bda3cb619c7f5770376b604c7aafb72a047))

### General maintenance

* add akka license key ([a0c062f](https://github.com/LetsStreamIt/profile-service/commit/a0c062f06b4d82fae2f346348b1f2540d1f5fdb8))

## [0.2.1](https://github.com/LetsStreamIt/profile-service/compare/v0.2.0...v0.2.1) (2024-10-21)

### Dependency updates

* **deps:** update dependency ch.qos.logback:logback-classic to v1.2.13 ([8f857c0](https://github.com/LetsStreamIt/profile-service/commit/8f857c002edd422e1796fcc899dd73a8a7385107))
* **deps:** update dependency ch.qos.logback:logback-classic to v1.5.11 ([f57810d](https://github.com/LetsStreamIt/profile-service/commit/f57810d8e24d0715e1feec5ab015321060c9400c))
* **deps:** update dependency org.scalatest:scalatest to v3.2.19 ([34e16b4](https://github.com/LetsStreamIt/profile-service/commit/34e16b4031d8c6c019d95706e5e803ceda536d5a))
* **deps:** update dependency sbt/sbt to v1.10.3 ([4db0a9d](https://github.com/LetsStreamIt/profile-service/commit/4db0a9de89330e0add3364f050d2e8c03e8a66b3))

### Bug Fixes

* added cors configuration ([ec4673b](https://github.com/LetsStreamIt/profile-service/commit/ec4673b0251693b6b1fc48446865ef2e26eed719))

### Tests

* added test for profile routes ([4fd900a](https://github.com/LetsStreamIt/profile-service/commit/4fd900a6ea1a6e89581c9d495a1271d701225dd9))

## [0.2.0](https://github.com/LetsStreamIt/profile-service/compare/v0.1.2...v0.2.0) (2024-10-19)

### Features

* added video route ([c0ff8fc](https://github.com/LetsStreamIt/profile-service/commit/c0ff8fc12babf8e316dc22426719f96223841371))
* authentication check ([eb4e129](https://github.com/LetsStreamIt/profile-service/commit/eb4e129cdc88dbe8541df3ca4f822fbea33d5f94))
* implemented user update ([31235c3](https://github.com/LetsStreamIt/profile-service/commit/31235c322f7ee3acdadb32ed7411587be288321d))

### Build and continuous integration

* **deps:** update sbt/setup-sbt action to v1.1.1 ([05ffe41](https://github.com/LetsStreamIt/profile-service/commit/05ffe418a731a470ea62d10d847835f7befc3558))

### General maintenance

* basic profile info implementation ([928a2b0](https://github.com/LetsStreamIt/profile-service/commit/928a2b0464f595b3921a8cdc3dbe1fd11b3ee443))

## [0.1.2](https://github.com/LetsStreamIt/profile-service/compare/v0.1.1...v0.1.2) (2024-10-17)

### Dependency updates

* **core-deps:** update dependency scala to v3.5.2 ([f4e6611](https://github.com/LetsStreamIt/profile-service/commit/f4e6611f4f9ed4cdd4b4f87d6d7847700c17170b))
* **deps:** update commitlint monorepo to v19.5.0 ([9f095f1](https://github.com/LetsStreamIt/profile-service/commit/9f095f1a4a8e5815eb60f3feb8411e9a36f66c3d))
* **deps:** update dependency @commitlint/cli to v19.4.1 ([5b3f81f](https://github.com/LetsStreamIt/profile-service/commit/5b3f81f87117e9f35bed1e7f469f47e932b9fce2))
* **deps:** update dependency ch.epfl.scala:sbt-scalafix to v0.13.0 ([03f30c2](https://github.com/LetsStreamIt/profile-service/commit/03f30c2d71b851d67f58d70ec6e1822fc3d599cf))
* **deps:** update dependency husky to v9.1.6 ([2307da5](https://github.com/LetsStreamIt/profile-service/commit/2307da592ed67ed06fb8c346a57a1406234176ac))
* **deps:** update dependency org.scalameta:munit to v1.0.2 ([b3a8c7e](https://github.com/LetsStreamIt/profile-service/commit/b3a8c7ee536f929b4630839c5d1c25c1a3d14117))
* **deps:** update dependency sbt/sbt to v1.10.2 ([f2d0d83](https://github.com/LetsStreamIt/profile-service/commit/f2d0d83722b472d3c9944e948f615d3331c39522))
* **deps:** update dependency semantic-release-preconfigured-conventional-commits to v1.1.109 ([62e750a](https://github.com/LetsStreamIt/profile-service/commit/62e750ae5f863bf252a8508bbbf7ec2f04aa4d27))
* **deps:** update dependency semantic-release-preconfigured-conventional-commits to v1.1.110 ([d1c5145](https://github.com/LetsStreamIt/profile-service/commit/d1c51455d529b6d7677814ea94805fa7b583c841))
* **deps:** update dependency semantic-release-preconfigured-conventional-commits to v1.1.111 ([b8495fe](https://github.com/LetsStreamIt/profile-service/commit/b8495fe401a6803e4a8c92be6a1d30c3bf88e80f))
* **deps:** update node.js to 20.18 ([b3767a7](https://github.com/LetsStreamIt/profile-service/commit/b3767a7e3e38978c6ba5cfee6801bf6dddb2e9ef))

### Build and continuous integration

* **deps:** update actions/checkout action to v4.2.0 ([5331b66](https://github.com/LetsStreamIt/profile-service/commit/5331b66055438ce1ae6123b11b4da95cdcbafb43))
* **deps:** update actions/checkout action to v4.2.1 ([c35cb9e](https://github.com/LetsStreamIt/profile-service/commit/c35cb9e824b1bb2a07f814e879dc4b74d37d932d))
* **deps:** update actions/setup-node action to v4.0.4 ([411714a](https://github.com/LetsStreamIt/profile-service/commit/411714a2dfda35a9a8a9412d2ba77fabae368bff))
* **deps:** update danysk/action-checkout action to v0.2.20 ([1b171ff](https://github.com/LetsStreamIt/profile-service/commit/1b171ffc2bd274b64b49427b480e267b47be3641))
* **deps:** update danysk/action-checkout action to v0.2.21 ([9cdc96a](https://github.com/LetsStreamIt/profile-service/commit/9cdc96a18ebbaf269a4c1ece80c47e02a1a77a92))
* **deps:** update sbt/setup-sbt action to v1.1.0 ([401585b](https://github.com/LetsStreamIt/profile-service/commit/401585b786fb5871a5b607af045ce10a2066b682))

## [0.1.1](https://github.com/LetsStreamIt/profile-service/compare/v0.1.0...v0.1.1) (2024-09-30)

### Dependency updates

* **core-deps:** update dependency scala to v3.5.1 ([d5f44fd](https://github.com/LetsStreamIt/profile-service/commit/d5f44fdad9a85c0e1e204aa8710c325bde23dd7f))

### Build and continuous integration

* **deps:** update actions/setup-java action to v4.4.0 ([be5231a](https://github.com/LetsStreamIt/profile-service/commit/be5231a2c4d46a6447f4610ca3c44fe4f31001a1))

## [1.1.2](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/compare/v1.1.1...v1.1.2) (2024-08-16)

### Dependency updates

* **core-deps:** update dependency scala to v3.5.0 ([d7e70d5](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/d7e70d574772ad38f5cc388051bf7e0866fa6ae6))
* **deps:** update dependency semantic-release-preconfigured-conventional-commits to v1.1.96 ([20375d8](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/20375d8f1eef4987f5883321ff6e449772f144ea))

## [1.1.1](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/compare/v1.1.0...v1.1.1) (2024-08-15)

### Dependency updates

* **core-deps:** update dependency scala to v3.4.3 ([81400dc](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/81400dced4fa6352a69d140aa4f06af8aed3d73d))
* **deps:** update dependency org.scalameta:munit to v1.0.1 ([6c3ee58](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/6c3ee58fd6551da00ce5b75bfb5e90797da11413))

## [1.1.0](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/compare/v1.0.1...v1.1.0) (2024-08-09)

### Features

* added lint and format checks to ci ([d7d9d03](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/d7d9d036eeddf307810c52bd4caf89ce8080f100))
* configured pre-commit hooks ([11e0fc6](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/11e0fc6761419ca7ab1f80f3b41b9816f2201ecf))

### Dependency updates

* **deps:** update dependency semantic-release-preconfigured-conventional-commits to v1.1.93 ([b9a7c34](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/b9a7c34a8170ee6a4691e9a1431c31d5e9c3fc75))
* **deps:** update dependency semantic-release-preconfigured-conventional-commits to v1.1.94 ([8b764c5](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/8b764c5f17e6032f13aa5a2ebf71cdc5f294b93d))
* **deps:** update dependency semantic-release-preconfigured-conventional-commits to v1.1.95 ([ae10bc1](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/ae10bc199d53974a59aedf4c371cc887e5705bf7))

### Bug Fixes

* removed hook creation in ci ([efde5e2](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/efde5e23b9b30cebe9e2509b09787f47566ce288))

### Build and continuous integration

* **deps:** update actions/setup-java action to v4.2.2 ([2749612](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/27496129827cc8bac7d5700fa81d44863824f955))

## [1.0.1](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/compare/v1.0.0...v1.0.1) (2024-07-28)

### Bug Fixes

* removed hardcoded version ([bcc659a](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/bcc659a3dad3dc0922634375286d94cf3a62858b))

### Build and continuous integration

* **deps:** update actions/checkout action to v4.1.7 ([6bab32c](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/6bab32c1beb260c08fa9462c56ef30c07a92c4be))
* **deps:** update actions/setup-node action to v4.0.3 ([8940c5c](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/8940c5c8da353c4e5abee399deeffbaa96168ce0))
* **deps:** update danysk/action-checkout action to v0.2.19 ([5321e0c](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/5321e0cdce7e59d3082555ec2ed3e1ed0514ad6c))

## 1.0.0 (2024-07-27)

### ⚠ BREAKING CHANGES

* added release configuration

### Features

* added release configuration ([fcbb353](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/fcbb35396ff500d19775d5495c3058aa9a8db6df))

### General maintenance

* created initial project template ([69ee542](https://github.com/LetsStreamIt/Template-for-Scala3-Projects/commit/69ee5423a9e5af031da8235997af6db161438e24))
