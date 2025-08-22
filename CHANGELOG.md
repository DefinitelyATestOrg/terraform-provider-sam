# Changelog

## 0.1.0-alpha.1 (2025-08-22)

Full Changelog: [v0.0.1-alpha.0...v0.1.0-alpha.1](https://github.com/DefinitelyATestOrg/terraform-provider-sam/compare/v0.0.1-alpha.0...v0.1.0-alpha.1)

### Features

* add docs generation to format script ([#29](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/29)) ([f2cde61](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/f2cde6120bf15ca1d740206d623241834aef0779))
* add SKIP_BREW env var to ./scripts/bootstrap ([#28](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/28)) ([5b6a70b](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/5b6a70bf19d8933674324d132413f9d4ac11f51a))
* add timeouts to terraform resources ([#7](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/7)) ([eec3514](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/eec3514c4f16bcbe5bc519efaf66e8032a282dfb))
* **api:** update via SDK Studio ([93a2300](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/93a23005e44930675c587e47b7aab225f4e65cbd))
* **api:** update via SDK Studio ([b9602aa](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/b9602aa1a679329c4f0adb7eb63744a83246c7c4))
* **build:** allow for building against private go repos ([#25](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/25)) ([f92a734](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/f92a7342a11191114037911851f43a208f837073))
* **client:** support environments property from Stainless config ([f6a19ec](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/f6a19ecce781c1f9765b2034b74fde394cf346c9))
* **docs:** generate documentation using tfplugindocs ([#11](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/11)) ([e233c7d](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/e233c7da69f555361a3688e0a2030f428167e3e4))
* **docs:** run tfplugindocs during build ([#20](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/20)) ([a4b73e5](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/a4b73e5f7158573acd1ae03835f0e9061e0d7b57))
* ensure `internal/apiform` encoder can handle "force_encode" serialization tag ([c0189f8](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/c0189f823e95ece4b46cf5b47f1eb01833db70e9))
* new option to send computed values back to server ([52571af](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/52571af1198572ea0060403f10b6f82da05d9274))
* new terraform config options ([#1](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/1)) ([242187f](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/242187f12cb1aae34b2968e049a5c2017498756f))
* setup go prod repo ([#15](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/15)) ([36db8f3](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/36db8f347462da6ed8a63563fdadbf7820089194))
* setup prod repos ([7b574c4](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/7b574c4658747f00b40f134e81b657a216c2317f))
* support sending explicit `null` properties when an attribute is unset ([#12](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/12)) ([0b65c31](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/0b65c31bdacd8d3566b80eb6d4f8377251dec182))
* support using environment variables as provider attributes ([#19](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/19)) ([be69cde](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/be69cde18faa1f30631c7c9a46b8b3a3d66e8c6c))


### Bug Fixes

* **api:** do not send `null` for missing properties ([#10](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/10)) ([da5c937](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/da5c93769ab104852ef21d6e56fd1c57e24576a1))
* **api:** handle mismatched dynamic array types in state and plan during serialization ([63103df](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/63103df3d65b835768d17bb49f6126b1179d9583))
* **build:** do not fail if go mod tidy fails during bootstrapping ([cc5969b](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/cc5969b4af5a65874dbd74bf7453ba42d3756ae6))
* **build:** enable building against private Go production repos ([d21fc5c](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/d21fc5cb906227cd94ba4d7ae66077b4204c8321))
* **build:** ensure scripts/generate-docs works regardless of PATH ([#22](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/22)) ([db3f44d](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/db3f44d9291dd872cc6d6f5913beb6d57b732d16))
* **build:** improve release process ([#21](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/21)) ([4aa194c](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/4aa194ca5058a3c72875244e30bdbdb5a3d8bd66))
* **ci:** release-doctor — report correct token name ([a6c37ff](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/a6c37ffc269f70e68d196b8581cd6c44f03147e9))
* do not call path.Base on ContentType ([#26](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/26)) ([e8670d8](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/e8670d8648f96530f09d4438f9deadd59d995287))
* **docs:** skip tfplugindocs generation if `generate_docs` is false ([#24](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/24)) ([1490b56](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/1490b56c8667f9eba7c135d45d02bcc1fabc4a45))
* dynamic type validators should handle int and floats correctly ([7b9f77f](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/7b9f77f9843c1d494d2769715682acb70d7b6dc3))
* encoder crash for nested nils in dynamic types ([3fe1907](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/3fe19079f873fc05bbb1f6487ce8cc2c9ad29c65))
* fix caching issue between Unmarshal and UnmarshalComputed ([9e38444](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/9e38444015c42c7e79279d90f6c7c10973d2f3a7))
* null nested attribute decoding ([a195e71](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/a195e71e508f7c941d7d40931fdfa0853aee3321))
* only unmarshal attributes that exist on the read response schema during refresh ([685771a](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/685771a5a2b042cce6dfb0b5ee5d0499958e6f0f))
* populate computed_optional collections from API responses ([a16dc2a](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/a16dc2ad2309bf5fd659d6b50b4adaabddd480fe))
* **release:** update README and version correctly in release PRs ([22dd4c6](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/22dd4c6ca0555b708df778a3992b289d467fe888))


### Chores

* **build:** scripts/format should not fail if generate-docs fails ([#30](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/30)) ([495dc48](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/495dc48ac4423555ec7ed8fc7f1c07dfb0e14f1f))
* **build:** update go.mod indirect dependencies ([293cef2](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/293cef2fa1d303d5acb6260340d4a961229822a0))
* bump deps to avoid GetResourceIdentitySchemas errors for Terraform CLI v1.12+ ([551e517](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/551e517cd760e1d6bbe4d56f044484b4ac3de38d))
* **ci:** enable for pull requests ([5933689](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/59336893e706dc898bbfa243b85732d620c7d7e0))
* **ci:** only run for pushes and fork pull requests ([38b662e](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/38b662e4bf6f7dcb6217d959469a6c9d04d38ed7))
* **ci:** only use depot for staging repos ([94f63d0](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/94f63d09d688678a0cd2543735c5bab422fd5aa8))
* **ci:** run on more branches ([228808f](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/228808f9a7d92bd999ab02ccbbd185ef7a3ab4d3))
* **ci:** run on more branches and use depot runners ([0fc6809](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/0fc6809cd48289ced6f941394c06f67e4037d349))
* cleanup apijson code ([#14](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/14)) ([e2390c2](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/e2390c26192d68546570e037f25506a683d1a80e))
* **docs:** add SECURITY.md ([#5](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/5)) ([56a7e51](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/56a7e510d907e14f0381b803d75956aa4a2245f3))
* **docs:** grammar improvements ([f820393](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/f820393959ab05893d26e73ec4c4e5531796f025))
* gitignore test server logs ([#13](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/13)) ([d9d7a82](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/d9d7a8254bd8a56486494ba5e7681dca15ed7acf))
* **internal:** add scripts-to-rule-them-all ([#6](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/6)) ([f581f21](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/f581f216ffe77d2e698ca09a2b32a69ba8a831d0))
* **internal:** add scripts/mock ([#3](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/3)) ([558b5c5](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/558b5c50d718b6ee7c253f6684b02d6d958a387b))
* **internal:** add test rule to lint for dynamic attributes that do not have planmodifier ([e118f0a](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/e118f0a9e46b1389921e085d8abba722189a3516))
* **internal:** bump mock server version to ~5.8.0 ([#4](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/4)) ([10fccde](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/10fccde4e1584a738f45f82f432a6b8ccf9ad77f))
* **internal:** bumps go dependencies ([#18](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/18)) ([df3363c](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/df3363c8746a71f610a641736dc4092cbd8caeea))
* **internal:** codegen related update ([#16](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/16)) ([7dd3f5e](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/7dd3f5ee230ba38be0fadc91eb962b4ead261a1e))
* **internal:** codegen related update ([#17](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/17)) ([15c32b4](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/15c32b4a79825884446e2787db010b0f04b18d1d))
* **internal:** codegen related update ([#2](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/2)) ([2cbee51](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/2cbee5160da6bbc50176625796eed6d5475ee395))
* **internal:** codegen related update ([#23](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/23)) ([2f4a0c9](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/2f4a0c9c1a0408e41db62065a79be5fe70b131a8))
* **internal:** codegen related update ([#8](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/8)) ([405650c](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/405650cd1899e1fb950ffb09b93b988956786181))
* **internal:** upgrade cloudflare/circl ([6692f4a](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/6692f4af43d1e76e532fd0be618dd7807024ce15))
* rebuild project due to codegen change ([#9](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/9)) ([45584bd](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/45584bdd18f50536316778b356d866c844132c03))
* **release:** enable release PRs to be opened before publishing to hashicorp ([dda0fc5](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/dda0fc5cff7d2cd951479c491289bc3a6668a75c))
* update @stainless-api/prism-cli to v5.15.0 ([3ac8efb](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/3ac8efbc3e9d96a2d6e9c8c40d0c1b6be0f9f67f))


### Documentation

* update documentation links to be more uniform ([39da7bb](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/39da7bb682c9937c74a0432eb452b49f69af8c84))
* update URLs from stainlessapi.com to stainless.com ([#27](https://github.com/DefinitelyATestOrg/terraform-provider-sam/issues/27)) ([660b5b1](https://github.com/DefinitelyATestOrg/terraform-provider-sam/commit/660b5b1ae93073bfa7ac69fb23a154ee5940d55c))
