# Changelog

## [0.9.0](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.30...pi-autosuggestions-v0.9.0) (2026-11-16)


### ⚠ BREAKING CHANGES

* adopt shared repo layout with src build and full baseline

### Features

* add zsh-autosuggestions history strategy and partial accept ([01b9147](https://github.com/AndrewM-F/pi-autosuggestions/commit/01b9147a39c08668ed9794a37757fd1b98503006))
* command-name completion from PATH at the bash command position ([2de5dfc](https://github.com/AndrewM-F/pi-autosuggestions/commit/2de5dfc493ffc06b83df7511cfa215e0b432b611))
* cross-session history, candidate cycling, theme-aware cursor, new dynamic sources ([cbe9555](https://github.com/AndrewM-F/pi-autosuggestions/commit/cbe9555c6c2d937a8d1d06317fb88ed69640b218))
* dynamic completions and expanded command tables ([89635d0](https://github.com/AndrewM-F/pi-autosuggestions/commit/89635d0a610087e3a569879b1e4172a5b5af689b))
* migrate formatting and linting from Prettier/ESLint to oxfmt/oxlint ([#31](https://github.com/AndrewM-F/pi-autosuggestions/issues/31)) ([a41ca58](https://github.com/AndrewM-F/pi-autosuggestions/commit/a41ca58fb527edc67e05f0b2163a389e5d80319d))
* subcommand completion for common bash commands ([cc106c6](https://github.com/AndrewM-F/pi-autosuggestions/commit/cc106c630a56592da69a6090a5f1f218728eb71d))


### Bug Fixes

* add repository metadata required for npm provenance ([bfd7e89](https://github.com/AndrewM-F/pi-autosuggestions/commit/bfd7e89453ba1e447d6358c3fcded16f874f1dd0))
* **ci:** pin generated callers to the adopted v1.4.1 runtime ([#38](https://github.com/AndrewM-F/pi-autosuggestions/issues/38)) ([376e655](https://github.com/AndrewM-F/pi-autosuggestions/commit/376e6552f3f1c14ee37275bf81fd0dfe161be593))
* complete fleet toolchain alignment ([#64](https://github.com/AndrewM-F/pi-autosuggestions/issues/64)) ([ada7536](https://github.com/AndrewM-F/pi-autosuggestions/commit/ada7536c618fcb01e67b35af5610ddac29318ffc))
* declare engines and limit published files for light installs ([da7dea9](https://github.com/AndrewM-F/pi-autosuggestions/commit/da7dea9b8c906e25edc85c2359b74674ea9542fa))
* **editor:** stop the software-blink ghost from overflowing the terminal ([#78](https://github.com/AndrewM-F/pi-autosuggestions/issues/78)) ([83ca703](https://github.com/AndrewM-F/pi-autosuggestions/commit/83ca703c8848761dfef7e511f3a43aeb9dc33c10)), closes [#67](https://github.com/AndrewM-F/pi-autosuggestions/issues/67)
* force white blinking bar cursor in terminals with themed cursors ([7760862](https://github.com/AndrewM-F/pi-autosuggestions/commit/7760862a356addf7e7621a8ffff782570f987428))
* keep the character under the cursor visible while the beam blinks ([718e69a](https://github.com/AndrewM-F/pi-autosuggestions/commit/718e69aa988f0cf7b79ed501ab7682db0a04baff))
* **pkg:** declare a Node engine range instead of an exact pin ([#79](https://github.com/AndrewM-F/pi-autosuggestions/issues/79)) ([77e68e2](https://github.com/AndrewM-F/pi-autosuggestions/commit/77e68e29291619166af29e203e96016d1f043d81)), closes [#66](https://github.com/AndrewM-F/pi-autosuggestions/issues/66)
* use the terminal's native blinking bar cursor ([a5a92ef](https://github.com/AndrewM-F/pi-autosuggestions/commit/a5a92efb4cee1f93c35b1c548acb1ef62059f746))
* verify trusted publishing via OIDC ([1dbb247](https://github.com/AndrewM-F/pi-autosuggestions/commit/1dbb2475f56d8a4e84b52f6439c79b80a760eda4))


### Performance

* add plugin performance regression budgets ([#42](https://github.com/AndrewM-F/pi-autosuggestions/issues/42)) ([bd8603d](https://github.com/AndrewM-F/pi-autosuggestions/commit/bd8603d4028762aea5d13c137dd1329fc7615c4f)), closes [#39](https://github.com/AndrewM-F/pi-autosuggestions/issues/39)


### Documentation

* correct cursor description, remove unused theme helpers ([91e1610](https://github.com/AndrewM-F/pi-autosuggestions/commit/91e1610f67bc326853dae36baf5c27a6e75a127c))
* correct pinned release tag format in install instructions ([102d33d](https://github.com/AndrewM-F/pi-autosuggestions/commit/102d33d6ce54bdb4a3e0e4d0c890b90ff3468c9b))
* keybindings, troubleshooting, schematic, and current install pin ([26ab7eb](https://github.com/AndrewM-F/pi-autosuggestions/commit/26ab7ebbeafe3de4de64bf0cbf1282e53d2e173d))


### CI

* add workflow_dispatch to release workflow ([db3d563](https://github.com/AndrewM-F/pi-autosuggestions/commit/db3d5639d1371279876f39d4caa9bb8d57b2cb02))
* declare root package in release-please config ([ea9ac24](https://github.com/AndrewM-F/pi-autosuggestions/commit/ea9ac241f674dddf78512d55e210c2bdd288047d))
* match canonical code-foundry release caller shape ([4bec61a](https://github.com/AndrewM-F/pi-autosuggestions/commit/4bec61aba9cb77d623d632cde8b3ef0ea82288f7))
* minimal reusable workflow call test ([08e2afc](https://github.com/AndrewM-F/pi-autosuggestions/commit/08e2afc50e8fdc48a5d04913ae6f851373b16b4c))
* route releases through code-foundry ([19e1500](https://github.com/AndrewM-F/pi-autosuggestions/commit/19e1500fb3fe8f6a86a6d1b09493e18375a29942))
* self-contained release-please and npm publish flow ([9729cce](https://github.com/AndrewM-F/pi-autosuggestions/commit/9729cce8e9547adb9c0521515da0b0027b971950))
* test code-foundry reusable workflow call (diagnostic) ([658c8fe](https://github.com/AndrewM-F/pi-autosuggestions/commit/658c8fe2e4a94c5b8274cd7eb154657e95f50943))
* test v0.39.0 ref ([efa891c](https://github.com/AndrewM-F/pi-autosuggestions/commit/efa891c6b07751ca354cebd7ff4fb0dc2daed36f))


### Maintenance

* adopt Code Foundry runtime v1.30.0 ([#62](https://github.com/AndrewM-F/pi-autosuggestions/issues/62)) ([f377e74](https://github.com/AndrewM-F/pi-autosuggestions/commit/f377e7469e9fcda4d09ce34675460b7794315877))
* adopt code-foundry v1.1.1 baseline ([#28](https://github.com/AndrewM-F/pi-autosuggestions/issues/28)) ([87a10b9](https://github.com/AndrewM-F/pi-autosuggestions/commit/87a10b9e5ceab06dd5df46e65af5f1b9c690c78f))
* adopt code-foundry v1.3.1 baseline and migrate to oxlint/oxfmt ([#33](https://github.com/AndrewM-F/pi-autosuggestions/issues/33)) ([2f6d094](https://github.com/AndrewM-F/pi-autosuggestions/commit/2f6d09432e54b6c2ce1f3858994dad376c9cceb4))
* adopt shared repo layout with src build and full baseline ([d1c83f9](https://github.com/AndrewM-F/pi-autosuggestions/commit/d1c83f9e4b48e16e513cd78f5b2131b7b4190c98))
* bun-1.4.4-cloud ([#97](https://github.com/AndrewM-F/pi-autosuggestions/issues/97)) ([48899e9](https://github.com/AndrewM-F/pi-autosuggestions/commit/48899e9e0e926552428948c3209c7d8fe5cbc2c6))
* **ci:** adopt code-foundry v0.40.2 runtime ([3f47ff2](https://github.com/AndrewM-F/pi-autosuggestions/commit/3f47ff27e5be47863ef46773e10aec7eda63ef10))
* **ci:** preserve authored MIT license on sync ([1997149](https://github.com/AndrewM-F/pi-autosuggestions/commit/1997149ea697c8d6cb1d85f40a228dc691936c7a))
* **ci:** publish releases to npm ([3d1cc16](https://github.com/AndrewM-F/pi-autosuggestions/commit/3d1cc168c58da2529037acce10a31ab02f358582))
* **ci:** switch Dependabot to bun ecosystem for bun.lock repo ([#68](https://github.com/AndrewM-F/pi-autosuggestions/issues/68)) ([15ad5e6](https://github.com/AndrewM-F/pi-autosuggestions/commit/15ad5e684d19bb944bd64399cd271030d0feba4f))
* **ci:** upgrade Code Foundry to v1.9.11 ([#44](https://github.com/AndrewM-F/pi-autosuggestions/issues/44)) ([b143282](https://github.com/AndrewM-F/pi-autosuggestions/commit/b1432824789f3cf90faf8429892ee5c296794203))
* **code-foundry:** upgrade runtime to v1.28.11 ([#52](https://github.com/AndrewM-F/pi-autosuggestions/issues/52)) ([afd575f](https://github.com/AndrewM-F/pi-autosuggestions/commit/afd575f2be68bc502cee07614ad3f72f0b81b980))
* **code-foundry:** upgrade runtime to v1.28.14 ([#54](https://github.com/AndrewM-F/pi-autosuggestions/issues/54)) ([fde6d99](https://github.com/AndrewM-F/pi-autosuggestions/commit/fde6d99457dfdbd9d1adeb4e2f42db4c2fc79cf6))
* **code-foundry:** upgrade runtime to v1.28.4 ([d87ba65](https://github.com/AndrewM-F/pi-autosuggestions/commit/d87ba651e08d9e63e7f79460204078fa27f1e599))
* **code-foundry:** upgrade runtime to v1.35.0 ([#69](https://github.com/AndrewM-F/pi-autosuggestions/issues/69)) ([954986d](https://github.com/AndrewM-F/pi-autosuggestions/commit/954986d44f639b59ed34fd60eff5d721b38ac3af))
* **code-foundry:** upgrade runtime to v1.36.4 ([#71](https://github.com/AndrewM-F/pi-autosuggestions/issues/71)) ([ad1bb80](https://github.com/AndrewM-F/pi-autosuggestions/commit/ad1bb80d1a7690bd10f1e336fe075d107bd9c672))
* **code-foundry:** upgrade runtime to v1.38.1 ([#83](https://github.com/AndrewM-F/pi-autosuggestions/issues/83)) ([42353e9](https://github.com/AndrewM-F/pi-autosuggestions/commit/42353e9f5a7c5eed03784cc8775a2b14c01ab4c1))
* **code-foundry:** upgrade runtime to v1.40.0 ([#85](https://github.com/AndrewM-F/pi-autosuggestions/issues/85)) ([6e5d50e](https://github.com/AndrewM-F/pi-autosuggestions/commit/6e5d50e04c4bd1ec157b2bdfe5067e3cb09449bb))
* **code-foundry:** upgrade runtime to v1.41.0 ([#87](https://github.com/AndrewM-F/pi-autosuggestions/issues/87)) ([6fe16d0](https://github.com/AndrewM-F/pi-autosuggestions/commit/6fe16d0dc959e31f44eb9eb321f3e2ac1be32cd0))
* **code-foundry:** upgrade runtime to v1.44.3 ([#89](https://github.com/AndrewM-F/pi-autosuggestions/issues/89)) ([2a6b1e0](https://github.com/AndrewM-F/pi-autosuggestions/commit/2a6b1e0a0504ba32a727e4b6b0c146457042e3f5))
* **code-foundry:** upgrade runtime to v1.47.1 ([#91](https://github.com/AndrewM-F/pi-autosuggestions/issues/91)) ([8b91bca](https://github.com/AndrewM-F/pi-autosuggestions/commit/8b91bcae76cee2c1b6e089f92602307ffdbc630d))
* **code-foundry:** upgrade to v1.38.0 ([#81](https://github.com/AndrewM-F/pi-autosuggestions/issues/81)) ([df0d85e](https://github.com/AndrewM-F/pi-autosuggestions/commit/df0d85eb7f5eea58e399c50bcb69e1f0ff6a6454))
* **code-foundry:** upgrade to v1.4.1 ([#35](https://github.com/AndrewM-F/pi-autosuggestions/issues/35)) ([c5cd597](https://github.com/AndrewM-F/pi-autosuggestions/commit/c5cd59768da321b2c445e7d1c1fa33008d4f0bb2))
* **code-foundry:** upgrade to v1.5.0 ([#40](https://github.com/AndrewM-F/pi-autosuggestions/issues/40)) ([eeb2ba6](https://github.com/AndrewM-F/pi-autosuggestions/commit/eeb2ba63143639a0b92cf764c5b41d9629e5d857))
* **config:** right-size runner lanes and drop default shard overrides ([#50](https://github.com/AndrewM-F/pi-autosuggestions/issues/50)) ([783253d](https://github.com/AndrewM-F/pi-autosuggestions/commit/783253dde99dfd486c0c7ff724b4c33bdb777d84))
* **deps-dev:** bump the bun-dependencies group across 1 directory with 4 updates ([#103](https://github.com/AndrewM-F/pi-autosuggestions/issues/103)) ([61dd121](https://github.com/AndrewM-F/pi-autosuggestions/commit/61dd121553b8f9a55d4ff7a746901b1c83aa7d7c))
* **deps:** build against pi 1.1.0 ([#93](https://github.com/AndrewM-F/pi-autosuggestions/issues/93)) ([0c11ce9](https://github.com/AndrewM-F/pi-autosuggestions/commit/0c11ce91763be0ce04d97a9c1b67da4d6d26ee0b))
* **deps:** update pi to 0.99.1 and pin the editor contract in tests ([#76](https://github.com/AndrewM-F/pi-autosuggestions/issues/76)) ([6eb9184](https://github.com/AndrewM-F/pi-autosuggestions/commit/6eb9184b8caac801fde89577937d0e5a3d238a24))
* **main:** release 0.8.10 ([#58](https://github.com/AndrewM-F/pi-autosuggestions/issues/58)) ([3f719ec](https://github.com/AndrewM-F/pi-autosuggestions/commit/3f719ec9a96ad571de81bba2cde25cb744b4ab06))
* **main:** release 0.8.11 ([#61](https://github.com/AndrewM-F/pi-autosuggestions/issues/61)) ([96be905](https://github.com/AndrewM-F/pi-autosuggestions/commit/96be905b75e05ae6bb911a5824b691de4a22454c))
* **main:** release 0.8.12 ([#63](https://github.com/AndrewM-F/pi-autosuggestions/issues/63)) ([fe9b815](https://github.com/AndrewM-F/pi-autosuggestions/commit/fe9b8158877b074caf9dbb574ebfafabb2076fd1))
* **main:** release 0.8.13 ([#65](https://github.com/AndrewM-F/pi-autosuggestions/issues/65)) ([355804c](https://github.com/AndrewM-F/pi-autosuggestions/commit/355804cb80621a18015f018c822146afb366b837))
* **main:** release 0.8.14 ([#70](https://github.com/AndrewM-F/pi-autosuggestions/issues/70)) ([637c501](https://github.com/AndrewM-F/pi-autosuggestions/commit/637c501d864d840e4507d7a260601c6c836aa203))
* **main:** release 0.8.15 ([#73](https://github.com/AndrewM-F/pi-autosuggestions/issues/73)) ([a8bddbd](https://github.com/AndrewM-F/pi-autosuggestions/commit/a8bddbd00ec3eb493348b7d23ff0d4d967093b44))
* **main:** release 0.8.16 ([#74](https://github.com/AndrewM-F/pi-autosuggestions/issues/74)) ([c0e99b7](https://github.com/AndrewM-F/pi-autosuggestions/commit/c0e99b72d088147b1fa51e5dca81eb9c81fa8966))
* **main:** release 0.8.17 ([#75](https://github.com/AndrewM-F/pi-autosuggestions/issues/75)) ([fd98f48](https://github.com/AndrewM-F/pi-autosuggestions/commit/fd98f48ebdcefa8b1c1be00cd3bc051b73ceddfb))
* **main:** release 0.8.18 ([#77](https://github.com/AndrewM-F/pi-autosuggestions/issues/77)) ([fcc5900](https://github.com/AndrewM-F/pi-autosuggestions/commit/fcc59002175a7088b05f485384f402aa262b7418))
* **main:** release 0.8.19 ([#80](https://github.com/AndrewM-F/pi-autosuggestions/issues/80)) ([9ae4ed7](https://github.com/AndrewM-F/pi-autosuggestions/commit/9ae4ed7d94aa64f2afc0aa2673aa776db6fb9875))
* **main:** release 0.8.20 ([#82](https://github.com/AndrewM-F/pi-autosuggestions/issues/82)) ([68e5fc7](https://github.com/AndrewM-F/pi-autosuggestions/commit/68e5fc7f6688c01b9feef2e60eed801ab4fcfb29))
* **main:** release 0.8.21 ([#84](https://github.com/AndrewM-F/pi-autosuggestions/issues/84)) ([ca5d34e](https://github.com/AndrewM-F/pi-autosuggestions/commit/ca5d34ef15eba7e55921a1e860ad6d71ada0157e))
* **main:** release 0.8.22 ([#86](https://github.com/AndrewM-F/pi-autosuggestions/issues/86)) ([48afaa6](https://github.com/AndrewM-F/pi-autosuggestions/commit/48afaa6054e8001c41809c91787e5b1b9346f7e0))
* **main:** release 0.8.23 ([#88](https://github.com/AndrewM-F/pi-autosuggestions/issues/88)) ([e6d6aaa](https://github.com/AndrewM-F/pi-autosuggestions/commit/e6d6aaa58ef8359347e3b5b28fb8ca508855769e))
* **main:** release 0.8.24 ([#90](https://github.com/AndrewM-F/pi-autosuggestions/issues/90)) ([956391e](https://github.com/AndrewM-F/pi-autosuggestions/commit/956391e1a7433e03b974feb31cc074cebb522c8c))
* **main:** release 0.8.25 ([#92](https://github.com/AndrewM-F/pi-autosuggestions/issues/92)) ([3f14e80](https://github.com/AndrewM-F/pi-autosuggestions/commit/3f14e80b0edc03a42e1756fcf3b2fc0c3c522d92))
* **main:** release 0.8.26 ([#94](https://github.com/AndrewM-F/pi-autosuggestions/issues/94)) ([4c008ba](https://github.com/AndrewM-F/pi-autosuggestions/commit/4c008ba44ac761c1c97e5debd24f283fdb8456d5))
* **main:** release 0.8.27 ([#98](https://github.com/AndrewM-F/pi-autosuggestions/issues/98)) ([696a89d](https://github.com/AndrewM-F/pi-autosuggestions/commit/696a89d285ac9586fb4140832f3e1447b256b041))
* **main:** release 0.8.28 ([#100](https://github.com/AndrewM-F/pi-autosuggestions/issues/100)) ([ca0119c](https://github.com/AndrewM-F/pi-autosuggestions/commit/ca0119cc3f0535b4bfed5e05c6b10405e0693ac4))
* **main:** release 0.8.29 ([#104](https://github.com/AndrewM-F/pi-autosuggestions/issues/104)) ([9edef72](https://github.com/AndrewM-F/pi-autosuggestions/commit/9edef7282ccb64aa920d5dd0ab166a24c9af7b15))
* **main:** release 0.8.30 ([#105](https://github.com/AndrewM-F/pi-autosuggestions/issues/105)) ([2a94c89](https://github.com/AndrewM-F/pi-autosuggestions/commit/2a94c898da5e568e848b78e2ebaa474a2465ab90))
* **main:** release 0.8.5 ([#46](https://github.com/AndrewM-F/pi-autosuggestions/issues/46)) ([0695790](https://github.com/AndrewM-F/pi-autosuggestions/commit/0695790d85637d5d89dc9dec9cc6c5d560329aef))
* **main:** release 0.8.6 ([#49](https://github.com/AndrewM-F/pi-autosuggestions/issues/49)) ([0374de6](https://github.com/AndrewM-F/pi-autosuggestions/commit/0374de69bf15c68439ed7938bc53483c13ad1ad3))
* **main:** release 0.8.7 ([#51](https://github.com/AndrewM-F/pi-autosuggestions/issues/51)) ([c4e0b99](https://github.com/AndrewM-F/pi-autosuggestions/commit/c4e0b9928dbfade3bd6cfba3e81992fc55fa4765))
* **main:** release 0.8.8 ([#53](https://github.com/AndrewM-F/pi-autosuggestions/issues/53)) ([f40268b](https://github.com/AndrewM-F/pi-autosuggestions/commit/f40268b83be985826bbea61e803b881bc1da0862))
* **main:** release 0.8.9 ([#55](https://github.com/AndrewM-F/pi-autosuggestions/issues/55)) ([eb67794](https://github.com/AndrewM-F/pi-autosuggestions/commit/eb677941d1861463158e8758d68983486dfc6135))
* **main:** release pi-autosuggestions 0.2.0 ([034d6a8](https://github.com/AndrewM-F/pi-autosuggestions/commit/034d6a8c1196e70b423700203285f0a408231e7d))
* **main:** release pi-autosuggestions 0.2.1 ([64a1c65](https://github.com/AndrewM-F/pi-autosuggestions/commit/64a1c652552ea84408c4ff827b70cedddad1d0f2))
* **main:** release pi-autosuggestions 0.2.2 ([d547e62](https://github.com/AndrewM-F/pi-autosuggestions/commit/d547e62a380ef84f375236a7c6ba3bf5fe1b186b))
* **main:** release pi-autosuggestions 0.2.3 ([4f00187](https://github.com/AndrewM-F/pi-autosuggestions/commit/4f00187b2293a6840ea554c67edf9cb0b5ded673))
* **main:** release pi-autosuggestions 0.2.4 ([a492c6e](https://github.com/AndrewM-F/pi-autosuggestions/commit/a492c6eb60a5e760ffaeaac3d9be8c66ef571ea4))
* **main:** release pi-autosuggestions 0.3.0 ([ac31b97](https://github.com/AndrewM-F/pi-autosuggestions/commit/ac31b970a524774090eef8045e28b9cf2c2d1faf))
* **main:** release pi-autosuggestions 0.3.1 ([7de3a1c](https://github.com/AndrewM-F/pi-autosuggestions/commit/7de3a1c922fe22f615ea3539b99dd6add0128646))
* **main:** release pi-autosuggestions 0.3.2 ([bb0af8d](https://github.com/AndrewM-F/pi-autosuggestions/commit/bb0af8d13849bdc6c3c22e93a2b5d0d2d1caa898))
* **main:** release pi-autosuggestions 0.3.3 ([db52eba](https://github.com/AndrewM-F/pi-autosuggestions/commit/db52eba0c651e97387d9487b0106bf386f700dff))
* **main:** release pi-autosuggestions 0.4.0 ([3e86087](https://github.com/AndrewM-F/pi-autosuggestions/commit/3e8608755d00bee34011a961b21ad817ea36c45d))
* **main:** release pi-autosuggestions 0.5.0 ([a1e7248](https://github.com/AndrewM-F/pi-autosuggestions/commit/a1e7248da70abfbe98653ccabfebbf9745436332))
* **main:** release pi-autosuggestions 0.6.0 ([dc7848b](https://github.com/AndrewM-F/pi-autosuggestions/commit/dc7848b38f01e6bb8c99efcad9f1f291b2aa605a))
* **main:** release pi-autosuggestions 0.6.1 ([b5aca60](https://github.com/AndrewM-F/pi-autosuggestions/commit/b5aca60226c171b3124d0c7af2166620dc3dccbc))
* **main:** release pi-autosuggestions 0.6.2 ([0d109ea](https://github.com/AndrewM-F/pi-autosuggestions/commit/0d109ea40049ace873cedd5af5ba070098cfdd00))
* **main:** release pi-autosuggestions 0.6.3 ([26402b1](https://github.com/AndrewM-F/pi-autosuggestions/commit/26402b1e170e6d1e9a3abb14fe203518f6ed1bb0))
* **main:** release pi-autosuggestions 0.7.0 ([96efc83](https://github.com/AndrewM-F/pi-autosuggestions/commit/96efc838867ba9b4e0eac0d3636976f619fad71c))
* **main:** release pi-autosuggestions 0.7.1 ([0121c6f](https://github.com/AndrewM-F/pi-autosuggestions/commit/0121c6f2524fba125d683a884da8ab84d4440b13))
* **main:** release pi-autosuggestions 0.7.10 ([153dd36](https://github.com/AndrewM-F/pi-autosuggestions/commit/153dd36e4868fccbba1e1bf12efb3ba7135d3495))
* **main:** release pi-autosuggestions 0.7.2 ([d56bc76](https://github.com/AndrewM-F/pi-autosuggestions/commit/d56bc76cabd7b32588c060cca908721fbaa51751))
* **main:** release pi-autosuggestions 0.7.3 ([f8a62e9](https://github.com/AndrewM-F/pi-autosuggestions/commit/f8a62e946ebd1caeca5fa3845a20ad7f08bf8fbc))
* **main:** release pi-autosuggestions 0.7.4 ([92a3076](https://github.com/AndrewM-F/pi-autosuggestions/commit/92a30766ecf9071cff98f7b6714f8aefdad06176))
* **main:** release pi-autosuggestions 0.7.5 ([b24c14f](https://github.com/AndrewM-F/pi-autosuggestions/commit/b24c14f826813df9b60cfb566d2a26e9f63e01d9))
* **main:** release pi-autosuggestions 0.7.6 ([d0bbfb6](https://github.com/AndrewM-F/pi-autosuggestions/commit/d0bbfb69f9523699037cca154ed9b8f17b363ba2))
* **main:** release pi-autosuggestions 0.7.7 ([4046bf4](https://github.com/AndrewM-F/pi-autosuggestions/commit/4046bf460d4e08d2cea498bd4512962282ff0623))
* **main:** release pi-autosuggestions 0.7.8 ([f81871c](https://github.com/AndrewM-F/pi-autosuggestions/commit/f81871cb2ee338fb8bfa651339df6b99d196fa42))
* **main:** release pi-autosuggestions 0.7.9 ([29c5ef7](https://github.com/AndrewM-F/pi-autosuggestions/commit/29c5ef790418a5fd3042bd9002a0a83a7cf7ff96))
* **main:** release pi-autosuggestions 0.8.0 ([2809b03](https://github.com/AndrewM-F/pi-autosuggestions/commit/2809b0363f230a9e1c724939539b2cb4549ce582))
* **main:** release pi-autosuggestions 0.8.1 ([f54d1da](https://github.com/AndrewM-F/pi-autosuggestions/commit/f54d1da733c12adf7343ca7ebcae55899845db8c))
* **main:** release pi-autosuggestions 0.8.2 ([2d07b21](https://github.com/AndrewM-F/pi-autosuggestions/commit/2d07b215abcade8eba8daad303a11f8952bf657d))
* **main:** release pi-autosuggestions 0.8.3 ([48ed1c1](https://github.com/AndrewM-F/pi-autosuggestions/commit/48ed1c1e78f1b6c9bca3e56d94faefffab9dbd02))
* **main:** release pi-autosuggestions 0.8.4 ([5f61a5f](https://github.com/AndrewM-F/pi-autosuggestions/commit/5f61a5f8594001223a25d285a2e37e4697cf0848))
* override undici to 8.10.2 for the two high advisories ([#72](https://github.com/AndrewM-F/pi-autosuggestions/issues/72)) ([fe22d2a](https://github.com/AndrewM-F/pi-autosuggestions/commit/fe22d2a4a379f911c315c5ba0b71d098b08bbda3))
* point GitHub references at AndrewM-F ([81ad0a3](https://github.com/AndrewM-F/pi-autosuggestions/commit/81ad0a3e83dceb58b9ae9d01c9ccf1c76641d0ee))
* rename package to pi-autosuggestions and adopt code-foundry release flow ([e2cf91c](https://github.com/AndrewM-F/pi-autosuggestions/commit/e2cf91cdcd4f1b92070f248c513e89c37b03c726))
* standardize lint and format toolchain ([#57](https://github.com/AndrewM-F/pi-autosuggestions/issues/57)) ([7cc29a8](https://github.com/AndrewM-F/pi-autosuggestions/commit/7cc29a8993ad792b1ed9a873fe41b0fc33bb0806))
* **sync:** adopt code-foundry v0.40.3 baseline ([f5c5c2e](https://github.com/AndrewM-F/pi-autosuggestions/commit/f5c5c2e61c510697cdab6c70e6b6165d3560763d))
* **sync:** adopt code-foundry v1.0.0 baseline ([672bd55](https://github.com/AndrewM-F/pi-autosuggestions/commit/672bd5556bb8fa3b0232f3131250f6e60b7669f6))
* **sync:** adopt code-foundry v1.0.1 baseline ([7d83392](https://github.com/AndrewM-F/pi-autosuggestions/commit/7d83392f141d17f1803d8d89db9c75cf5b3b5891))
* **sync:** adopt code-foundry v1.0.2 baseline ([522c4ee](https://github.com/AndrewM-F/pi-autosuggestions/commit/522c4eed1e2f3763290f36979a65db5045daeca5))
* **sync:** adopt code-foundry v1.0.3 baseline ([296c280](https://github.com/AndrewM-F/pi-autosuggestions/commit/296c2809829c98cff033be16010bddf15dbe535a))
* **sync:** adopt code-foundry v1.0.4 baseline ([94bc392](https://github.com/AndrewM-F/pi-autosuggestions/commit/94bc392a2fb38a08f49e0d577e49395d38974ca4))
* toolchain-alignment ([#60](https://github.com/AndrewM-F/pi-autosuggestions/issues/60)) ([c0fa4ec](https://github.com/AndrewM-F/pi-autosuggestions/commit/c0fa4ec2b158dc0ade0edb266ac19e241cb0680c))
* update Code Foundry to 1.48.8, Pi to 1.4.0, and fix npm 12 pack parsing ([#99](https://github.com/AndrewM-F/pi-autosuggestions/issues/99)) ([438cc61](https://github.com/AndrewM-F/pi-autosuggestions/commit/438cc61e84f97d4cfc85a2ebd6da442b38d7b2b3))

## [0.8.30](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.29...pi-autosuggestions-v0.8.30) (2026-11-16)


### Bug Fixes

* verify trusted publishing via OIDC ([009a892](https://github.com/AndrewM-F/pi-autosuggestions/commit/009a89288d87295037b69b7cea0bb195a6d80d4a))


### Maintenance

* **deps-dev:** bump the bun-dependencies group across 1 directory with 4 updates ([#103](https://github.com/AndrewM-F/pi-autosuggestions/issues/103)) ([1cefba8](https://github.com/AndrewM-F/pi-autosuggestions/commit/1cefba8fc87b1b1430f1186a0caf94c08da401f6))

## [0.8.29](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.28...pi-autosuggestions-v0.8.29) (2026-11-16)


### Maintenance

* point GitHub references at AndrewM-F ([67691d7](https://github.com/AndrewM-F/pi-autosuggestions/commit/67691d73370430d9c6017529236f8c52f3631310))

## [0.8.28](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.27...pi-autosuggestions-v0.8.28) (2026-10-24)


### Maintenance

* update Code Foundry to 1.48.8, Pi to 1.4.0, and fix npm 12 pack parsing ([#99](https://github.com/AndrewM-F/pi-autosuggestions/issues/99)) ([2c156ea](https://github.com/AndrewM-F/pi-autosuggestions/commit/2c156eaab067f7d1ea3a490f849806bbc0e5fd66))

## [0.8.27](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.26...pi-autosuggestions-v0.8.27) (2026-10-22)


### Maintenance

* bun-1.4.4-cloud ([#97](https://github.com/AndrewM-F/pi-autosuggestions/issues/97)) ([993bee1](https://github.com/AndrewM-F/pi-autosuggestions/commit/993bee1fa33bb874549bcab12b50315b8f0cdd95))

## [0.8.26](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.25...pi-autosuggestions-v0.8.26) (2026-10-08)


### Maintenance

* **deps:** build against pi 1.1.0 ([#93](https://github.com/AndrewM-F/pi-autosuggestions/issues/93)) ([9151da1](https://github.com/AndrewM-F/pi-autosuggestions/commit/9151da11ed2daf518a9cc84edb4ac250beb7a661))

## [0.8.25](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.24...pi-autosuggestions-v0.8.25) (2026-10-08)


### Maintenance

* **code-foundry:** upgrade runtime to v1.47.1 ([#91](https://github.com/AndrewM-F/pi-autosuggestions/issues/91)) ([7f00d4f](https://github.com/AndrewM-F/pi-autosuggestions/commit/7f00d4fcb93ea24e20c498ff23317ea325199967))

## [0.8.24](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.23...pi-autosuggestions-v0.8.24) (2026-10-03)


### Maintenance

* **code-foundry:** upgrade runtime to v1.44.3 ([#89](https://github.com/AndrewM-F/pi-autosuggestions/issues/89)) ([1f1809b](https://github.com/AndrewM-F/pi-autosuggestions/commit/1f1809b55af665e7af291b9a025bbcb1db672424))

## [0.8.23](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.22...pi-autosuggestions-v0.8.23) (2026-10-02)


### Maintenance

* **code-foundry:** upgrade runtime to v1.41.0 ([#87](https://github.com/AndrewM-F/pi-autosuggestions/issues/87)) ([a60b2c4](https://github.com/AndrewM-F/pi-autosuggestions/commit/a60b2c45f270063ae88dfb7d5a931dbbc86b408c))

## [0.8.22](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.21...pi-autosuggestions-v0.8.22) (2026-10-02)


### Maintenance

* **code-foundry:** upgrade runtime to v1.40.0 ([#85](https://github.com/AndrewM-F/pi-autosuggestions/issues/85)) ([75843ff](https://github.com/AndrewM-F/pi-autosuggestions/commit/75843ff7c848034696450dded349fa2425f1c396))

## [0.8.21](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.20...pi-autosuggestions-v0.8.21) (2026-09-30)


### Maintenance

* **code-foundry:** upgrade runtime to v1.38.1 ([#83](https://github.com/AndrewM-F/pi-autosuggestions/issues/83)) ([034a7f6](https://github.com/AndrewM-F/pi-autosuggestions/commit/034a7f6e10d9afd9410c4df77c6c1d10b0184602))

## [0.8.20](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.19...pi-autosuggestions-v0.8.20) (2026-09-30)


### Maintenance

* **code-foundry:** upgrade to v1.38.0 ([#81](https://github.com/AndrewM-F/pi-autosuggestions/issues/81)) ([ab25234](https://github.com/AndrewM-F/pi-autosuggestions/commit/ab2523421a0a064242b1be395cebd975be8f3547))

## [0.8.19](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.18...pi-autosuggestions-v0.8.19) (2026-09-30)


### Bug Fixes

* **editor:** stop the software-blink ghost from overflowing the terminal ([#78](https://github.com/AndrewM-F/pi-autosuggestions/issues/78)) ([c1854a8](https://github.com/AndrewM-F/pi-autosuggestions/commit/c1854a826913a1e37de1cf2d7062fd89d870e4cc)), closes [#67](https://github.com/AndrewM-F/pi-autosuggestions/issues/67)

## [0.8.18](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.17...pi-autosuggestions-v0.8.18) (2026-09-30)


### Maintenance

* **deps:** update pi to 0.99.1 and pin the editor contract in tests ([#76](https://github.com/AndrewM-F/pi-autosuggestions/issues/76)) ([74f53df](https://github.com/AndrewM-F/pi-autosuggestions/commit/74f53dfecad4cb16c86720de0f9ab471d51c0c6a))

## [0.8.17](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.16...pi-autosuggestions-v0.8.17) (2026-09-30)


### Maintenance

* **ci:** switch Dependabot to bun ecosystem for bun.lock repo ([#68](https://github.com/AndrewM-F/pi-autosuggestions/issues/68)) ([629b0aa](https://github.com/AndrewM-F/pi-autosuggestions/commit/629b0aaac7afead06e2952a93ab6e49f1cc9b01f))

## [0.8.16](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.15...pi-autosuggestions-v0.8.16) (2026-09-29)


### Maintenance

* **code-foundry:** upgrade runtime to v1.36.4 ([#71](https://github.com/AndrewM-F/pi-autosuggestions/issues/71)) ([95c5781](https://github.com/AndrewM-F/pi-autosuggestions/commit/95c5781db6e090d6f4b1c81f9fd0fcf3093f0a62))

## [0.8.15](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.14...pi-autosuggestions-v0.8.15) (2026-09-29)


### Maintenance

* override undici to 8.10.2 for the two high advisories ([#72](https://github.com/AndrewM-F/pi-autosuggestions/issues/72)) ([91b5bcf](https://github.com/AndrewM-F/pi-autosuggestions/commit/91b5bcfc5941f55aeea0059806882aca3cc89d46))

## [0.8.14](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.13...pi-autosuggestions-v0.8.14) (2026-09-29)


### Maintenance

* **code-foundry:** upgrade runtime to v1.35.0 ([#69](https://github.com/AndrewM-F/pi-autosuggestions/issues/69)) ([df00219](https://github.com/AndrewM-F/pi-autosuggestions/commit/df002191fa92e79e06ecbeab534bc3c10b542cdc))

## [0.8.13](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.12...pi-autosuggestions-v0.8.13) (2026-09-18)


### Bug Fixes

* complete fleet toolchain alignment ([#64](https://github.com/AndrewM-F/pi-autosuggestions/issues/64)) ([4f71528](https://github.com/AndrewM-F/pi-autosuggestions/commit/4f71528d11b7b1e986dcfdcc51be92631eba36b5))

## [0.8.12](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.11...pi-autosuggestions-v0.8.12) (2026-09-17)


### Maintenance

* adopt Code Foundry runtime v1.30.0 ([#62](https://github.com/AndrewM-F/pi-autosuggestions/issues/62)) ([0e62885](https://github.com/AndrewM-F/pi-autosuggestions/commit/0e62885b656b10538e7c93e972209d1d40e648d6))

## [0.8.11](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.10...pi-autosuggestions-v0.8.11) (2026-09-17)


### Maintenance

* toolchain-alignment ([#60](https://github.com/AndrewM-F/pi-autosuggestions/issues/60)) ([311f65e](https://github.com/AndrewM-F/pi-autosuggestions/commit/311f65e185aa570615d49abe040eb09366868141))

## [0.8.10](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.9...pi-autosuggestions-v0.8.10) (2026-09-17)


### Maintenance

* standardize lint and format toolchain ([#57](https://github.com/AndrewM-F/pi-autosuggestions/issues/57)) ([ce4ffce](https://github.com/AndrewM-F/pi-autosuggestions/commit/ce4ffce20fe66603f8b0e64a40b0f2654d4858bd))

## [0.8.9](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.8...pi-autosuggestions-v0.8.9) (2026-09-11)


### Maintenance

* **code-foundry:** upgrade runtime to v1.28.14 ([#54](https://github.com/AndrewM-F/pi-autosuggestions/issues/54)) ([691e2ff](https://github.com/AndrewM-F/pi-autosuggestions/commit/691e2ffead8a4c61776e3bfcab17fccbbcd9692c))

## [0.8.8](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.7...pi-autosuggestions-v0.8.8) (2026-09-11)


### Maintenance

* **code-foundry:** upgrade runtime to v1.28.11 ([#52](https://github.com/AndrewM-F/pi-autosuggestions/issues/52)) ([4a7c01e](https://github.com/AndrewM-F/pi-autosuggestions/commit/4a7c01e6b199bf46fcc94cd7bec92dedd3ad3f2f))

## [0.8.7](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.6...pi-autosuggestions-v0.8.7) (2026-09-11)


### Maintenance

* **config:** right-size runner lanes and drop default shard overrides ([#50](https://github.com/AndrewM-F/pi-autosuggestions/issues/50)) ([b118f01](https://github.com/AndrewM-F/pi-autosuggestions/commit/b118f01b2fd85babe173fb953bb0f9f22b8dba96))

## [0.8.6](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.5...pi-autosuggestions-v0.8.6) (2026-09-10)


### Maintenance

* **code-foundry:** upgrade runtime to v1.28.4 ([7619db4](https://github.com/AndrewM-F/pi-autosuggestions/commit/7619db4e497951cb2a487e874cfae176fe6f96d8))

## [0.8.5](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.4...pi-autosuggestions-v0.8.5) (2026-09-08)


### Maintenance

* **ci:** upgrade Code Foundry to v1.9.11 ([#44](https://github.com/AndrewM-F/pi-autosuggestions/issues/44)) ([fe68d36](https://github.com/AndrewM-F/pi-autosuggestions/commit/fe68d3605dfe7922848c38250a6c5e127a90813a))

## [0.8.4](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.3...pi-autosuggestions-v0.8.4) (2026-09-08)


### Performance

* add plugin performance regression budgets ([#42](https://github.com/AndrewM-F/pi-autosuggestions/issues/42)) ([c16eaac](https://github.com/AndrewM-F/pi-autosuggestions/commit/c16eaac3771ee30bba570498c1089c1330882508)), closes [#39](https://github.com/AndrewM-F/pi-autosuggestions/issues/39)

## [0.8.3](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.2...pi-autosuggestions-v0.8.3) (2026-09-08)


### Maintenance

* **code-foundry:** upgrade to v1.5.0 ([#40](https://github.com/AndrewM-F/pi-autosuggestions/issues/40)) ([f54e6ab](https://github.com/AndrewM-F/pi-autosuggestions/commit/f54e6ab9225e32dd69935f136755d3dc155e04fd))

## [0.8.2](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.1...pi-autosuggestions-v0.8.2) (2026-09-07)


### Bug Fixes

* **ci:** pin generated callers to the adopted v1.4.1 runtime ([#38](https://github.com/AndrewM-F/pi-autosuggestions/issues/38)) ([8c35f25](https://github.com/AndrewM-F/pi-autosuggestions/commit/8c35f25ff91d420b8e78ff24e6026c0e4ca4bd2d))


### Maintenance

* **code-foundry:** upgrade to v1.4.1 ([#35](https://github.com/AndrewM-F/pi-autosuggestions/issues/35)) ([b5c80fa](https://github.com/AndrewM-F/pi-autosuggestions/commit/b5c80fa478bc20d3e52719ecbfeecb8c21113844))

## [0.8.1](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.8.0...pi-autosuggestions-v0.8.1) (2026-09-07)


### Maintenance

* adopt code-foundry v1.3.1 baseline and migrate to oxlint/oxfmt ([#33](https://github.com/AndrewM-F/pi-autosuggestions/issues/33)) ([361a65a](https://github.com/AndrewM-F/pi-autosuggestions/commit/361a65a4682677b9e19e867d0b393ea991257292))

## [0.8.0](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.7.10...pi-autosuggestions-v0.8.0) (2026-09-07)


### Features

* migrate formatting and linting from Prettier/ESLint to oxfmt/oxlint ([#31](https://github.com/AndrewM-F/pi-autosuggestions/issues/31)) ([a0aff36](https://github.com/AndrewM-F/pi-autosuggestions/commit/a0aff36e10e72dc8592d2c481d94678f900b6dff))

## [0.7.10](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.7.9...pi-autosuggestions-v0.7.10) (2026-09-06)


### Maintenance

* adopt code-foundry v1.1.1 baseline ([#28](https://github.com/AndrewM-F/pi-autosuggestions/issues/28)) ([53bc259](https://github.com/AndrewM-F/pi-autosuggestions/commit/53bc2590ddfada556b4e8be72e170c142e49ea4e))

## [0.7.9](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.7.8...pi-autosuggestions-v0.7.9) (2026-09-06)


### Maintenance

* **sync:** adopt code-foundry v1.0.4 baseline ([248ee8a](https://github.com/AndrewM-F/pi-autosuggestions/commit/248ee8aba33685c29343c7d298bee57ad1b37581))

## [0.7.8](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.7.7...pi-autosuggestions-v0.7.8) (2026-09-06)


### Maintenance

* **sync:** adopt code-foundry v1.0.3 baseline ([1f37cc5](https://github.com/AndrewM-F/pi-autosuggestions/commit/1f37cc5c679a686a5452846a9bd147ce9cd598c1))

## [0.7.7](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.7.6...pi-autosuggestions-v0.7.7) (2026-09-06)


### Documentation

* keybindings, troubleshooting, schematic, and current install pin ([0c37efa](https://github.com/AndrewM-F/pi-autosuggestions/commit/0c37efa0d9bcc3131c2356ead9f40338b33bf022))

## [0.7.6](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.7.5...pi-autosuggestions-v0.7.6) (2026-09-06)


### Maintenance

* **sync:** adopt code-foundry v1.0.2 baseline ([2a737c7](https://github.com/AndrewM-F/pi-autosuggestions/commit/2a737c79f234d2ee07575313b6018a2d4341b595))

## [0.7.5](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.7.4...pi-autosuggestions-v0.7.5) (2026-09-05)


### Maintenance

* **sync:** adopt code-foundry v1.0.1 baseline ([4b8f866](https://github.com/AndrewM-F/pi-autosuggestions/commit/4b8f8664a5d3fd3b0310222470d33b78885e6896))

## [0.7.4](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.7.3...pi-autosuggestions-v0.7.4) (2026-09-05)


### Maintenance

* **ci:** publish releases to npm ([68e2946](https://github.com/AndrewM-F/pi-autosuggestions/commit/68e29468f6ed39d896a60c1f1fafaa4608372213))

## [0.7.3](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.7.2...pi-autosuggestions-v0.7.3) (2026-09-05)


### Maintenance

* **sync:** adopt code-foundry v1.0.0 baseline ([e83fa5c](https://github.com/AndrewM-F/pi-autosuggestions/commit/e83fa5c7076d458f654c3f8af3e61dbc407f877e))

## [0.7.2](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.7.1...pi-autosuggestions-v0.7.2) (2026-09-05)


### Maintenance

* **sync:** adopt code-foundry v0.40.3 baseline ([2c44da5](https://github.com/AndrewM-F/pi-autosuggestions/commit/2c44da52420fde5b3d91fecc25383fb0aa94deef))

## [0.7.1](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.7.0...pi-autosuggestions-v0.7.1) (2026-09-05)


### Maintenance

* **ci:** preserve authored MIT license on sync ([34bed9c](https://github.com/AndrewM-F/pi-autosuggestions/commit/34bed9c7890afcc1fc2b5927c10398027f781c13))

## [0.7.0](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.6.3...pi-autosuggestions-v0.7.0) (2026-09-05)


### ⚠ BREAKING CHANGES

* adopt shared repo layout with src build and full baseline

### Maintenance

* adopt shared repo layout with src build and full baseline ([ced5cbc](https://github.com/AndrewM-F/pi-autosuggestions/commit/ced5cbc75d34f166359eff54d4bab67debd99656))

## [0.6.3](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.6.2...pi-autosuggestions-v0.6.3) (2026-09-05)

### Maintenance

- **ci:** adopt code-foundry v0.40.2 runtime ([df4f46c](https://github.com/AndrewM-F/pi-autosuggestions/commit/df4f46c48431d4f3655a8a2f5ed28a383cafb8d1))

## [0.6.2](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.6.1...pi-autosuggestions-v0.6.2) (2026-09-05)

### Bug Fixes

- declare engines and limit published files for light installs ([8881ab4](https://github.com/AndrewM-F/pi-autosuggestions/commit/8881ab4c63ca694cc4d3ee56af1963b538f0050e))

## [0.6.1](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.6.0...pi-autosuggestions-v0.6.1) (2026-09-05)

### Documentation

- correct cursor description, remove unused theme helpers ([681f22d](https://github.com/AndrewM-F/pi-autosuggestions/commit/681f22d629b6d5251e8c4543a288814855e633c5))

## [0.6.0](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.5.0...pi-autosuggestions-v0.6.0) (2026-09-05)

### Features

- cross-session history, candidate cycling, theme-aware cursor, new dynamic sources ([71fe236](https://github.com/AndrewM-F/pi-autosuggestions/commit/71fe236ac272d54432da96aa35e53a919102f657))

## [0.5.0](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.4.0...pi-autosuggestions-v0.5.0) (2026-09-04)

### Features

- dynamic completions and expanded command tables ([4e99186](https://github.com/AndrewM-F/pi-autosuggestions/commit/4e991868049694c1f973bc8ab2069af433c8bf4c))

## [0.4.0](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.3.3...pi-autosuggestions-v0.4.0) (2026-09-04)

### Features

- subcommand completion for common bash commands ([3b17e1c](https://github.com/AndrewM-F/pi-autosuggestions/commit/3b17e1cc5c6ee0ef92b5f2f564a9f8a7ce896411))

## [0.3.3](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.3.2...pi-autosuggestions-v0.3.3) (2026-09-04)

### Bug Fixes

- force white blinking bar cursor in terminals with themed cursors ([20a3a24](https://github.com/AndrewM-F/pi-autosuggestions/commit/20a3a2499cad2ec3a83e1c8d1edd0c96b6d6a2ee))

## [0.3.2](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.3.1...pi-autosuggestions-v0.3.2) (2026-09-04)

### Bug Fixes

- use the terminal's native blinking bar cursor ([2abf68b](https://github.com/AndrewM-F/pi-autosuggestions/commit/2abf68b1f226c9b62ec2c9cdebeb3375601de632))

## [0.3.1](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.3.0...pi-autosuggestions-v0.3.1) (2026-09-04)

### Bug Fixes

- keep the character under the cursor visible while the beam blinks ([16833a7](https://github.com/AndrewM-F/pi-autosuggestions/commit/16833a788d30fb92e99a98fd29927d2ecaed8790))

## [0.3.0](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.2.4...pi-autosuggestions-v0.3.0) (2026-09-04)

### Features

- command-name completion from PATH at the bash command position ([9b4eef6](https://github.com/AndrewM-F/pi-autosuggestions/commit/9b4eef62c780979fc972cb2d304eeefe8fd98db7))

## [0.2.4](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.2.3...pi-autosuggestions-v0.2.4) (2026-09-04)

### CI

- route releases through code-foundry ([2747d07](https://github.com/AndrewM-F/pi-autosuggestions/commit/2747d07ba79a33c77bbca3c0f6fd1228eaeb3298))

## [0.2.3](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.2.2...pi-autosuggestions-v0.2.3) (2026-09-04)

### CI

- test code-foundry reusable workflow call (diagnostic) ([1316ff9](https://github.com/AndrewM-F/pi-autosuggestions/commit/1316ff92b6d650d8985520cbb2544fc21651d714))

## [0.2.2](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.2.1...pi-autosuggestions-v0.2.2) (2026-09-04)

### Documentation

- correct pinned release tag format in install instructions ([e936ed4](https://github.com/AndrewM-F/pi-autosuggestions/commit/e936ed4001a9e73e0e1f0a8cea54c5d0fef47c36))

## [0.2.1](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.2.0...pi-autosuggestions-v0.2.1) (2026-09-04)

### Bug Fixes

- add repository metadata required for npm provenance ([cfddf8d](https://github.com/AndrewM-F/pi-autosuggestions/commit/cfddf8d17f9f359b6f73ec9e0fb68b67748de0d6))

## [0.2.0](https://github.com/AndrewM-F/pi-autosuggestions/compare/pi-autosuggestions-v0.1.0...pi-autosuggestions-v0.2.0) (2026-09-04)

### Features

- add zsh-autosuggestions history strategy and partial accept ([951cd11](https://github.com/AndrewM-F/pi-autosuggestions/commit/951cd1148f8ce63230efbbf6d6815d31048cbd03))

### CI

- add workflow_dispatch to release workflow ([599b7bb](https://github.com/AndrewM-F/pi-autosuggestions/commit/599b7bbcb6460fe0550657e26a237652dc358d33))
- declare root package in release-please config ([7d505b9](https://github.com/AndrewM-F/pi-autosuggestions/commit/7d505b9a0dcbef26162844baf7c02f09063090c7))
- match canonical code-foundry release caller shape ([8533336](https://github.com/AndrewM-F/pi-autosuggestions/commit/85333360daa61d803d19020fad1b87f2d418aa11))
- minimal reusable workflow call test ([3864ab0](https://github.com/AndrewM-F/pi-autosuggestions/commit/3864ab07d929fee682c10b6f7dcd005dcb59bf00))
- self-contained release-please and npm publish flow ([b56cf97](https://github.com/AndrewM-F/pi-autosuggestions/commit/b56cf978b691f54afd93f739c63ba316ecbd7b84))
- test v0.39.0 ref ([be7e2d5](https://github.com/AndrewM-F/pi-autosuggestions/commit/be7e2d503dd6543850ffd926dc0e44efc5c77a9d))

### Maintenance

- rename package to pi-autosuggestions and adopt code-foundry release flow ([57b7265](https://github.com/AndrewM-F/pi-autosuggestions/commit/57b7265afd63b4bcb65f5f8ac7ff9507fc820b5c))
