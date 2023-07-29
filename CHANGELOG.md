# CHANGELOG

## [0.1.0](https://github.com/wkirschbaum/credo-language-server/compare/v0.3.0...v0.1.0) (2023-07-29)


### ⚠ BREAKING CHANGES

* change Readability and Consistency diagnostic severity to hint ([#47](https://github.com/wkirschbaum/credo-language-server/issues/47))

### Features

* add code action for the ParenthesesOnZeroArityDefs check ([#76](https://github.com/wkirschbaum/credo-language-server/issues/76)) ([f846c9d](https://github.com/wkirschbaum/credo-language-server/commit/f846c9d34a8d5b64516031df0d3b59122986839c))
* bin/start script for local dev ([cbb5a22](https://github.com/wkirschbaum/credo-language-server/commit/cbb5a22fdde0c48fcef64c9a32f27df6bf4af1ea))
* change Readability and Consistency diagnostic severity to hint ([#47](https://github.com/wkirschbaum/credo-language-server/issues/47)) ([060763e](https://github.com/wkirschbaum/credo-language-server/commit/060763e0b6f8334627152d6a144a05ca3cc851b1))
* code action for Credo.Check.Readability.ModuleDoc ([#23](https://github.com/wkirschbaum/credo-language-server/issues/23)) ([6fba718](https://github.com/wkirschbaum/credo-language-server/commit/6fba7187dd4ef54695680293d02757fac1a96079))
* include more data in diagnostic ([#52](https://github.com/wkirschbaum/credo-language-server/issues/52)) ([8d53850](https://github.com/wkirschbaum/credo-language-server/commit/8d538507c7c8a5d19415a6fc19e478bd994014c9))
* isolated node ([#32](https://github.com/wkirschbaum/credo-language-server/issues/32)) ([fe09487](https://github.com/wkirschbaum/credo-language-server/commit/fe094879ab2f7f92247f16b5312005ce27b57f90))
* log runtime errors to the client ([#48](https://github.com/wkirschbaum/credo-language-server/issues/48)) ([f7d76c9](https://github.com/wkirschbaum/credo-language-server/commit/f7d76c9405d56a2c8b5f0ff784c86cca53952e9a))
* log version when initialized ([#72](https://github.com/wkirschbaum/credo-language-server/issues/72)) ([c4f0cac](https://github.com/wkirschbaum/credo-language-server/commit/c4f0caccf5a11c4a26c90b42cf0d9759372b8e0a))
* replace deps.compile with deps.loadpaths ([#50](https://github.com/wkirschbaum/credo-language-server/issues/50)) ([fdeb381](https://github.com/wkirschbaum/credo-language-server/commit/fdeb381efd4e7e10eb23cf4c44c0cd78c0bb61d8))
* report progress ([#14](https://github.com/wkirschbaum/credo-language-server/issues/14)) ([7303af3](https://github.com/wkirschbaum/credo-language-server/commit/7303af353af4ed2eb3d028987519de5ab28ca6a2))
* the whole thing ([1218597](https://github.com/wkirschbaum/credo-language-server/commit/1218597c3730259ed4c083363d5f329e09313326))


### Bug Fixes

* bump gen_lsp 0.3 ([#69](https://github.com/wkirschbaum/credo-language-server/issues/69)) ([0fb8180](https://github.com/wkirschbaum/credo-language-server/commit/0fb81804b5741514112c647144be21fe69aec489)), closes [#68](https://github.com/wkirschbaum/credo-language-server/issues/68)
* correctly shutdown ([#28](https://github.com/wkirschbaum/credo-language-server/issues/28)) ([27a681b](https://github.com/wkirschbaum/credo-language-server/commit/27a681bc0eceb2a2fc9d1a2dfd7518a1028c4ad9)), closes [#27](https://github.com/wkirschbaum/credo-language-server/issues/27)
* correctly specify working dir ([#1](https://github.com/wkirschbaum/credo-language-server/issues/1)) ([bc4ddd4](https://github.com/wkirschbaum/credo-language-server/commit/bc4ddd48a8e39502ebc32a03ec8e4bce4e52f5a9))
* improve credo-language-server binary ([#61](https://github.com/wkirschbaum/credo-language-server/issues/61)) ([218873a](https://github.com/wkirschbaum/credo-language-server/commit/218873a79310dee96ade2736b5b8be21402be3d7))
* include priv dir when publishing ([0c7ffd5](https://github.com/wkirschbaum/credo-language-server/commit/0c7ffd5e91a578958f2c3f3bad19946d66ee3fd7))
* integrate runtime with application ([#38](https://github.com/wkirschbaum/credo-language-server/issues/38)) ([da473eb](https://github.com/wkirschbaum/credo-language-server/commit/da473eb84af3a536708ba42924ef7025fcfc5dba))
* return method_not_found for unsupported methods ([#15](https://github.com/wkirschbaum/credo-language-server/issues/15)) ([b9ad8e4](https://github.com/wkirschbaum/credo-language-server/commit/b9ad8e4b5cd84285a2eff7eddee7ef33be1cbf06)), closes [#8](https://github.com/wkirschbaum/credo-language-server/issues/8) [#10](https://github.com/wkirschbaum/credo-language-server/issues/10)
* set -S for shebang in bin/credo-language-server ([#56](https://github.com/wkirschbaum/credo-language-server/issues/56)) ([074c895](https://github.com/wkirschbaum/credo-language-server/commit/074c895b522f0e3a2b9548ec665e9011746911a2))
* set Runtime.call/2 timeout to :infinity ([#70](https://github.com/wkirschbaum/credo-language-server/issues/70)) ([909207b](https://github.com/wkirschbaum/credo-language-server/commit/909207b81120232816dc47395feeff947705ef58)), closes [#67](https://github.com/wkirschbaum/credo-language-server/issues/67)
* start script ([#36](https://github.com/wkirschbaum/credo-language-server/issues/36)) ([4fe34c8](https://github.com/wkirschbaum/credo-language-server/commit/4fe34c8157377ecbff82eb1c243c49247a3ed149))
* typo in log ([#63](https://github.com/wkirschbaum/credo-language-server/issues/63)) ([06f77d7](https://github.com/wkirschbaum/credo-language-server/commit/06f77d7334a93b2a7afe7ea41fdaaf9a14f5dda5))
* use a different MIX_ENV to avoid clobbering ([#42](https://github.com/wkirschbaum/credo-language-server/issues/42)) ([bc0f369](https://github.com/wkirschbaum/credo-language-server/commit/bc0f369eb9173382985807bf99883fa79087035d))
* use MIX_BUILD_ROOT ([#45](https://github.com/wkirschbaum/credo-language-server/issues/45)) ([4854ad3](https://github.com/wkirschbaum/credo-language-server/commit/4854ad3960c81545bece51116ee4fb3da51bf810))
* wait for runtime to be ready before handling some notifications ([#49](https://github.com/wkirschbaum/credo-language-server/issues/49)) ([6a0f22d](https://github.com/wkirschbaum/credo-language-server/commit/6a0f22db88a56e1e148e6efb4ecc7bf86b75897a))


### Miscellaneous Chores

* bump 0.1.0 ([42809b1](https://github.com/wkirschbaum/credo-language-server/commit/42809b17d2df388db7565f94009bb4b679f62dae))

## [0.3.0](https://github.com/elixir-tools/credo-language-server/compare/v0.2.0...v0.3.0) (2023-07-28)


### Features

* add code action for the ParenthesesOnZeroArityDefs check ([#76](https://github.com/elixir-tools/credo-language-server/issues/76)) ([f846c9d](https://github.com/elixir-tools/credo-language-server/commit/f846c9d34a8d5b64516031df0d3b59122986839c))

## [0.2.0](https://github.com/elixir-tools/credo-language-server/compare/v0.1.3...v0.2.0) (2023-06-27)


### Features

* log version when initialized ([#72](https://github.com/elixir-tools/credo-language-server/issues/72)) ([c4f0cac](https://github.com/elixir-tools/credo-language-server/commit/c4f0caccf5a11c4a26c90b42cf0d9759372b8e0a))


### Bug Fixes

* bump gen_lsp 0.3 ([#69](https://github.com/elixir-tools/credo-language-server/issues/69)) ([0fb8180](https://github.com/elixir-tools/credo-language-server/commit/0fb81804b5741514112c647144be21fe69aec489)), closes [#68](https://github.com/elixir-tools/credo-language-server/issues/68)
* set Runtime.call/2 timeout to :infinity ([#70](https://github.com/elixir-tools/credo-language-server/issues/70)) ([909207b](https://github.com/elixir-tools/credo-language-server/commit/909207b81120232816dc47395feeff947705ef58)), closes [#67](https://github.com/elixir-tools/credo-language-server/issues/67)

## [0.1.3](https://github.com/elixir-tools/credo-language-server/compare/v0.1.2...v0.1.3) (2023-06-23)


### Bug Fixes

* typo in log ([#63](https://github.com/elixir-tools/credo-language-server/issues/63)) ([06f77d7](https://github.com/elixir-tools/credo-language-server/commit/06f77d7334a93b2a7afe7ea41fdaaf9a14f5dda5))

## [0.1.2](https://github.com/elixir-tools/credo-language-server/compare/v0.1.1...v0.1.2) (2023-06-11)


### Bug Fixes

* improve credo-language-server binary ([#61](https://github.com/elixir-tools/credo-language-server/issues/61)) ([218873a](https://github.com/elixir-tools/credo-language-server/commit/218873a79310dee96ade2736b5b8be21402be3d7))

## [0.1.1](https://github.com/elixir-tools/credo-language-server/compare/v0.1.0...v0.1.1) (2023-06-11)


### Bug Fixes

* set -S for shebang in bin/credo-language-server ([#56](https://github.com/elixir-tools/credo-language-server/issues/56)) ([074c895](https://github.com/elixir-tools/credo-language-server/commit/074c895b522f0e3a2b9548ec665e9011746911a2))

## [0.1.0](https://github.com/elixir-tools/credo-language-server/compare/v0.1.0-rc.3...v0.1.0) (2023-06-09)


### Miscellaneous Chores

* bump 0.1.0 ([42809b1](https://github.com/elixir-tools/credo-language-server/commit/42809b17d2df388db7565f94009bb4b679f62dae))

## 0.1.0-rc.3

- feat: log runtime errors to the client by @mhanberg in https://github.com/elixir-tools/credo-language-server/pull/48
- fix: wait for runtime to be ready before handling some notifications by @mhanberg in https://github.com/elixir-tools/credo-language-server/pull/49
- feat: replace deps.compile with deps.loadpaths by @mhanberg in https://github.com/elixir-tools/credo-language-server/pull/50
- feat: include more data in diagnostic by @mhanberg in https://github.com/elixir-tools/credo-language-server/pull/52


## 0.1.0-rc.2

- feat!: Changed Readability and Consistency check diagnostics from `hint` to `information` severity.
- fix: build to correct alternate location

  The new runtime will compile artifacts to a new `.elixir-tools` directory in your project root. This should be added to the `.gitignore`

## 0.1.0-rc.1

- Include priv dir when publishing

## 0.1.0-rc.0

- Custom check/plugin compatibility

## v0.0.5

- Correctly shut down and do not leave zombie processes #28

## v0.0.4

- Now reports progress when checking for issues

## v0.0.3

- Code Action: Insert `@moduledoc false` to fix `Credo.Check.Readability.ModuleDoc`

## v0.0.2

- Correctly set Credo's working directory.

## v0.0.1

Initial Release
