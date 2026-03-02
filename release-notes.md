:robot: I have created a release *beep* *boop*
---


<details><summary>cli: 9.41.0</summary>

## [9.41.0](https://github.com/qqqqww1/vm0/compare/cli-v9.40.3...cli-v9.41.0) (2026-03-02)


### Features

* add notify-slack preference to gate slack schedule notifications ([#2945](https://github.com/qqqqww1/vm0/issues/2945)) ([a0058e6](https://github.com/qqqqww1/vm0/commit/a0058e6d2c2a7f6c4d20c78a287488ba843cce02))
* add organization scope support with clerk integration ([#2863](https://github.com/qqqqww1/vm0/issues/2863)) ([ec821d7](https://github.com/qqqqww1/vm0/commit/ec821d79768153368aa3ff213b31e3e219baf320))
* allow users to set timezone preference for sandbox and scheduling ([#2866](https://github.com/qqqqww1/vm0/issues/2866)) ([89437c7](https://github.com/qqqqww1/vm0/commit/89437c733b4e34eee46009b20c99f455c5963289))
* **cli:** add --check-env flag to vm0 run commands ([#2760](https://github.com/qqqqww1/vm0/issues/2760)) ([f6711e0](https://github.com/qqqqww1/vm0/commit/f6711e0d047aa872c76f97c8cfaf1257d2f35fb0))
* **cli:** add agent delete command ([#2767](https://github.com/qqqqww1/vm0/issues/2767)) ([11d555a](https://github.com/qqqqww1/vm0/commit/11d555ad5432a9893ddc37e55f89a58e7dd5657c))
* **cli:** add auto-pagination to logs command ([#2855](https://github.com/qqqqww1/vm0/issues/2855)) ([e487a1a](https://github.com/qqqqww1/vm0/commit/e487a1a687146002f3d7abf2b4904b507b3b29c5))
* **cli:** add computer connector support ([#3124](https://github.com/qqqqww1/vm0/issues/3124)) ([a950821](https://github.com/qqqqww1/vm0/commit/a9508213014337b0a4a7effb4756ed7056e3cb0f))
* **cli:** add vm0 upgrade command ([#3305](https://github.com/qqqqww1/vm0/issues/3305)) ([7150d0f](https://github.com/qqqqww1/vm0/commit/7150d0f0bdd1f2ab583d3b3346e38f91cbcfdc26))
* **cli:** detect field typos in vm0.yaml agent definitions ([#3307](https://github.com/qqqqww1/vm0/issues/3307)) ([c3c5969](https://github.com/qqqqww1/vm0/commit/c3c59695f2e3d4a1cc04ae4be765d8d0d913901e))
* **cli:** enable GitHub URL compose without experimental flag ([#2728](https://github.com/qqqqww1/vm0/issues/2728)) ([3158138](https://github.com/qqqqww1/vm0/commit/315813840b9590aca5d5f52575dcb24ddfebbae2)), closes [#2724](https://github.com/qqqqww1/vm0/issues/2724)
* **email:** add email notifications and reply-to-continue via Resend ([#2836](https://github.com/qqqqww1/vm0/issues/2836)) ([fd6aa4c](https://github.com/qqqqww1/vm0/commit/fd6aa4c032a84f25e8c6a8cf4ba4cef5ff070bd9))
* **platform:** add environment variables setup page ([#2737](https://github.com/qqqqww1/vm0/issues/2737)) ([d33842a](https://github.com/qqqqww1/vm0/commit/d33842a2e5e72eb5bfebe66cd442135b49f35a51))
* **scope:** enable vm0 admin users to activate system scope ([#3378](https://github.com/qqqqww1/vm0/issues/3378)) ([c4d05ac](https://github.com/qqqqww1/vm0/commit/c4d05acc257e7777dab8822362e07437add11511))
* **slack:** send DM notification when scheduled agent run completes ([#2720](https://github.com/qqqqww1/vm0/issues/2720)) ([77cf47b](https://github.com/qqqqww1/vm0/commit/77cf47b9911a28394bd0b851d75183ea22764bab))
* **storage:** add optional volume support for graceful degradation ([#2929](https://github.com/qqqqww1/vm0/issues/2929)) ([fd052a4](https://github.com/qqqqww1/vm0/commit/fd052a4fef4b2157bb1b1a7a2a0eaccffa6ff262))


### Bug Fixes

* **api:** use framework-based filename lookup in instructions api ([#3192](https://github.com/qqqqww1/vm0/issues/3192)) ([607608a](https://github.com/qqqqww1/vm0/commit/607608aa76b4237e2692dec598318a614e44ac02))
* **ci:** unique runner name per metal host ([#3141](https://github.com/qqqqww1/vm0/issues/3141)) ([ad5dcf4](https://github.com/qqqqww1/vm0/commit/ad5dcf49e603392ac476d2e44a033e635756d47b))
* **cli:** add environment and release to sentry config and prevent test leaks ([#2706](https://github.com/qqqqww1/vm0/issues/2706)) ([56578ad](https://github.com/qqqqww1/vm0/commit/56578adccbdb20b8299ef0d66e44526d4eaf2a1d))
* **cli:** add error handling to connector connect and display error.cause ([#2682](https://github.com/qqqqww1/vm0/issues/2682)) ([d19a29e](https://github.com/qqqqww1/vm0/commit/d19a29e5e2134de5fd7b28bb1ee16467cb6d7046))
* **cli:** add missing try/catch to auth and cook commands ([#2690](https://github.com/qqqqww1/vm0/issues/2690)) ([216758d](https://github.com/qqqqww1/vm0/commit/216758de8f0a860dde5c5b69df9ea15e0eddccb7))
* **cli:** add missing try/catch to onboard command ([#2699](https://github.com/qqqqww1/vm0/issues/2699)) ([cec0044](https://github.com/qqqqww1/vm0/commit/cec00445c45b0ce6ff2cc8a5e83191442b85d126))
* **cli:** check dependencies before connecting computer connector ([#3146](https://github.com/qqqqww1/vm0/issues/3146)) ([1e9d814](https://github.com/qqqqww1/vm0/commit/1e9d814ea5b49fbe687bbab3e6b8357fbdbe7619))
* **cli:** test release-please cli version bump ([#3179](https://github.com/qqqqww1/vm0/issues/3179)) ([8eb6b9e](https://github.com/qqqqww1/vm0/commit/8eb6b9e811ac438d2788181fc6f3e5c70890dd53))
* **cli:** use fake timers in usage tests to avoid time-dependent failures ([#3032](https://github.com/qqqqww1/vm0/issues/3032)) ([9cd34bf](https://github.com/qqqqww1/vm0/commit/9cd34bfe0a4b7d1ca3fe3f413fca2ab9d7edf6b5))
* **cli:** use nullish coalescing for sentry environment fallback ([#2709](https://github.com/qqqqww1/vm0/issues/2709)) ([b70248f](https://github.com/qqqqww1/vm0/commit/b70248fa7e0685091ddbbdd3de2f7a2747df23c8))
* **e2e:** make agent names unique to prevent compose config collisions ([#3147](https://github.com/qqqqww1/vm0/issues/3147)) ([022c83f](https://github.com/qqqqww1/vm0/commit/022c83fcb4dd21135b50964d71f8cac193d42254))
* **e2e:** make secret and variable names unique in t20-schedule test ([#3149](https://github.com/qqqqww1/vm0/issues/3149)) ([4ef861f](https://github.com/qqqqww1/vm0/commit/4ef861f72b361bf9a66201f512e58a8d65a40261))
* exclude connector-provided secrets from missing-secrets checks ([#2752](https://github.com/qqqqww1/vm0/issues/2752)) ([3dc98d4](https://github.com/qqqqww1/vm0/commit/3dc98d47451a2084b50a9a6ebce2f2ccb31d2833)), closes [#2747](https://github.com/qqqqww1/vm0/issues/2747)
* **runner:** add path validation and ci hash guards ([#3161](https://github.com/qqqqww1/vm0/issues/3161)) ([c5313ff](https://github.com/qqqqww1/vm0/commit/c5313ffdaee030c5fb3d48b950c8d7b6e36e90ae))
* **test:** remove vi.unstubAllEnvs from CLI tests and fix compose job race condition ([#2695](https://github.com/qqqqww1/vm0/issues/2695)) ([04ab29b](https://github.com/qqqqww1/vm0/commit/04ab29bf89201bb921d6a2f63b9ea4e3f2ab899d))
* **web:** disable json query to fix flaky ambiguous-prefix test ([#2701](https://github.com/qqqqww1/vm0/issues/2701)) ([a5f8e8a](https://github.com/qqqqww1/vm0/commit/a5f8e8a375a3a84c46518780201b66f75ea845a3))


### Performance Improvements

* **ci:** deploy runner to all metal hosts in parallel ([#3134](https://github.com/qqqqww1/vm0/issues/3134)) ([88152d3](https://github.com/qqqqww1/vm0/commit/88152d30f602490b463ce6049d327c67d21516cb))
* **ci:** increase runner e2e parallelism to 5 per host ([#3135](https://github.com/qqqqww1/vm0/issues/3135)) ([d81e066](https://github.com/qqqqww1/vm0/commit/d81e066c9b6b3520ba6a734b0b62bd2ddb030f5f))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @vm0/core bumped to 8.29.0
</details>

<details><summary>core: 8.29.0</summary>

## [8.29.0](https://github.com/qqqqww1/vm0/compare/core-v8.28.0...core-v8.29.0) (2026-03-02)


### Features

* add computer connector api for authenticated local tunneling via ngrok ([#2937](https://github.com/qqqqww1/vm0/issues/2937)) ([4f3fc4e](https://github.com/qqqqww1/vm0/commit/4f3fc4ebf137409a30b85b5882634a6bb8846836))
* add gmail connector with nango platform integration ([#3065](https://github.com/qqqqww1/vm0/issues/3065)) ([d43dfe1](https://github.com/qqqqww1/vm0/commit/d43dfe1a5a868c8413ffd2b8a250d48dafc791cb))
* add notify-slack preference to gate slack schedule notifications ([#2945](https://github.com/qqqqww1/vm0/issues/2945)) ([a0058e6](https://github.com/qqqqww1/vm0/commit/a0058e6d2c2a7f6c4d20c78a287488ba843cce02))
* add organization scope support with clerk integration ([#2863](https://github.com/qqqqww1/vm0/issues/2863)) ([ec821d7](https://github.com/qqqqww1/vm0/commit/ec821d79768153368aa3ff213b31e3e219baf320))
* allow users to set timezone preference for sandbox and scheduling ([#2866](https://github.com/qqqqww1/vm0/issues/2866)) ([89437c7](https://github.com/qqqqww1/vm0/commit/89437c733b4e34eee46009b20c99f455c5963289))
* **api:** add backend support for agent detail page ([#2979](https://github.com/qqqqww1/vm0/issues/2979)) ([4103d8f](https://github.com/qqqqww1/vm0/commit/4103d8f66ccc9546bccc67454d139b8d1de04599))
* **cli:** add --check-env flag to vm0 run commands ([#2760](https://github.com/qqqqww1/vm0/issues/2760)) ([f6711e0](https://github.com/qqqqww1/vm0/commit/f6711e0d047aa872c76f97c8cfaf1257d2f35fb0))
* **cli:** add agent delete command ([#2767](https://github.com/qqqqww1/vm0/issues/2767)) ([11d555a](https://github.com/qqqqww1/vm0/commit/11d555ad5432a9893ddc37e55f89a58e7dd5657c))
* **cli:** add computer connector support ([#3124](https://github.com/qqqqww1/vm0/issues/3124)) ([a950821](https://github.com/qqqqww1/vm0/commit/a9508213014337b0a4a7effb4756ed7056e3cb0f))
* **connector:** add deel oauth2 connector ([#3401](https://github.com/qqqqww1/vm0/issues/3401)) ([8128da7](https://github.com/qqqqww1/vm0/commit/8128da7cb693bdb51b006edc7ed8cc1aae14b9c2))
* **connector:** add docusign oauth2 connector ([#3402](https://github.com/qqqqww1/vm0/issues/3402)) ([2273b1c](https://github.com/qqqqww1/vm0/commit/2273b1c3db937c8c2e5794c0348f2d5a063c724e))
* **connector:** add gmail connector feature flag ([#3381](https://github.com/qqqqww1/vm0/issues/3381)) ([50b45eb](https://github.com/qqqqww1/vm0/commit/50b45eb00469afce5b433e03e590fa0070c77458))
* **connector:** add google sheets, docs, and drive oauth2 connectors ([#3403](https://github.com/qqqqww1/vm0/issues/3403)) ([97cca63](https://github.com/qqqqww1/vm0/commit/97cca638861824b887feaa3d97372028e8affdba))
* **connector:** add mercury oauth2 connector ([#3397](https://github.com/qqqqww1/vm0/issues/3397)) ([a5f4e79](https://github.com/qqqqww1/vm0/commit/a5f4e794fe12e6250d770fef1d8ec444a5cdcec3))
* **connector:** add strava and garmin connect oauth2 connectors ([#3399](https://github.com/qqqqww1/vm0/issues/3399)) ([2aa431a](https://github.com/qqqqww1/vm0/commit/2aa431ae1142234ee0d2add1438249540dc91ad8))
* **connectors:** add dropbox oauth connector ([#3368](https://github.com/qqqqww1/vm0/issues/3368)) ([1dc5d4c](https://github.com/qqqqww1/vm0/commit/1dc5d4c151f986ded68c169b19bd7c9c6a07f4b6))
* **connectors:** add feature flag for linear connector visibility ([#3372](https://github.com/qqqqww1/vm0/issues/3372)) ([f6da04e](https://github.com/qqqqww1/vm0/commit/f6da04e4653c62103975cb43f44d7c70067e4dc1))
* **connectors:** add figma oauth connector ([#3369](https://github.com/qqqqww1/vm0/issues/3369)) ([4d93f59](https://github.com/qqqqww1/vm0/commit/4d93f59827c3567ba83ef115d90decc4ca7fa294))
* **connectors:** add gmail oauth connector ([#3332](https://github.com/qqqqww1/vm0/issues/3332)) ([ca303b7](https://github.com/qqqqww1/vm0/commit/ca303b71916095e799c22b975f71216ea89df021))
* **connectors:** add linear oauth connector ([#3366](https://github.com/qqqqww1/vm0/issues/3366)) ([f943498](https://github.com/qqqqww1/vm0/commit/f94349842e5501fe487d078fa7138a3010d65635))
* **connectors:** add self-hosted slack connector ([#3281](https://github.com/qqqqww1/vm0/issues/3281)) ([13e92fd](https://github.com/qqqqww1/vm0/commit/13e92fde8468324ca7502fa8ded5eb60179eba05)), closes [#3279](https://github.com/qqqqww1/vm0/issues/3279)
* **connectors:** remove linear connector feature flag ([#3394](https://github.com/qqqqww1/vm0/issues/3394)) ([bcb0266](https://github.com/qqqqww1/vm0/commit/bcb02665109aeda6e5c6052dcdaa8ebe261545e3))
* **core:** add glm-5 model and fix model id casing ([#2889](https://github.com/qqqqww1/vm0/issues/2889)) ([f7dff90](https://github.com/qqqqww1/vm0/commit/f7dff9098110a983c8bf6c15740fa01010f09f5b)), closes [#2883](https://github.com/qqqqww1/vm0/issues/2883)
* **core:** add user-targeted feature switch with enabled user ids ([#3451](https://github.com/qqqqww1/vm0/issues/3451)) ([9e1c37a](https://github.com/qqqqww1/vm0/commit/9e1c37ac3a66882f29db39d0d1b11f165bc12f42))
* **email:** add email notifications and reply-to-continue via Resend ([#2836](https://github.com/qqqqww1/vm0/issues/2836)) ([fd6aa4c](https://github.com/qqqqww1/vm0/commit/fd6aa4c032a84f25e8c6a8cf4ba4cef5ff070bd9))
* **platform:** add agent detail page with feature flag gating ([#2998](https://github.com/qqqqww1/vm0/issues/2998)) ([5386de0](https://github.com/qqqqww1/vm0/commit/5386de0662eb2a85e69040788e2ca08e7f976cba))
* **platform:** add editable agent name and skills multi-select to config dialog ([#3216](https://github.com/qqqqww1/vm0/issues/3216)) ([50fc6f3](https://github.com/qqqqww1/vm0/commit/50fc6f3fc03d6595b9ee326df2dd88a1697eb837))
* **runner:** inject agent name and scope env vars into sandbox runtime ([#3375](https://github.com/qqqqww1/vm0/issues/3375)) ([53a1d42](https://github.com/qqqqww1/vm0/commit/53a1d4211cf4dbb477b1fb92a2412b719d46d8a8))
* **scope:** enable vm0 admin users to activate system scope ([#3378](https://github.com/qqqqww1/vm0/issues/3378)) ([c4d05ac](https://github.com/qqqqww1/vm0/commit/c4d05acc257e7777dab8822362e07437add11511))
* **storage:** add optional volume support for graceful degradation ([#2929](https://github.com/qqqqww1/vm0/issues/2929)) ([fd052a4](https://github.com/qqqqww1/vm0/commit/fd052a4fef4b2157bb1b1a7a2a0eaccffa6ff262))
* use ngrok reserved domains for computer connector ([#3116](https://github.com/qqqqww1/vm0/issues/3116)) ([7e30f2c](https://github.com/qqqqww1/vm0/commit/7e30f2c83f7fb4f82dd0b1e9aed38267ca5919f9))
* **vsock:** add environment variable support to exec/spawn_watch ([#2736](https://github.com/qqqqww1/vm0/issues/2736)) ([6f93486](https://github.com/qqqqww1/vm0/commit/6f9348601ae5736e20a8c32a2064ac394a70e70b))
* **web:** add Notion OAuth connector support ([#2738](https://github.com/qqqqww1/vm0/issues/2738)) ([a201b5d](https://github.com/qqqqww1/vm0/commit/a201b5d7ffdd081b4a9f299297bad0e06fa890b1))
* **web:** update connector oauth scopes and add deel pkce support ([#3459](https://github.com/qqqqww1/vm0/issues/3459)) ([3c9926a](https://github.com/qqqqww1/vm0/commit/3c9926ac223b3458c9ffc38600e0c19cc552b044))


### Bug Fixes

* **api:** use framework-based filename lookup in instructions api ([#3192](https://github.com/qqqqww1/vm0/issues/3192)) ([607608a](https://github.com/qqqqww1/vm0/commit/607608aa76b4237e2692dec598318a614e44ac02))
* exclude connector-provided secrets from missing-secrets checks ([#2752](https://github.com/qqqqww1/vm0/issues/2752)) ([3dc98d4](https://github.com/qqqqww1/vm0/commit/3dc98d47451a2084b50a9a6ebce2f2ccb31d2833)), closes [#2747](https://github.com/qqqqww1/vm0/issues/2747)
* **platform:** resolve empty logs page for scoped agents ([#3392](https://github.com/qqqqww1/vm0/issues/3392)) ([d611bd0](https://github.com/qqqqww1/vm0/commit/d611bd026a6f74a27707c3877c1c4f9cb19acb65))
* remove nango integration and simplify oauth flow ([#3105](https://github.com/qqqqww1/vm0/issues/3105)) ([a1c601e](https://github.com/qqqqww1/vm0/commit/a1c601e2217456d16b1e34de0a41fe61a0026e7a))
* **schedule:** reject schedule creation for organization-scoped agents ([#3420](https://github.com/qqqqww1/vm0/issues/3420)) ([7945a10](https://github.com/qqqqww1/vm0/commit/7945a10ea3d2c21e8bde0516326f98804e61ea87))
* **web:** disable json query to fix flaky ambiguous-prefix test ([#2701](https://github.com/qqqqww1/vm0/issues/2701)) ([a5f8e8a](https://github.com/qqqqww1/vm0/commit/a5f8e8a375a3a84c46518780201b66f75ea845a3))
</details>

<details><summary>platform: 0.76.0</summary>

## [0.76.0](https://github.com/qqqqww1/vm0/compare/platform-v0.75.1...platform-v0.76.0) (2026-03-02)


### Features

* add computer connector api for authenticated local tunneling via ngrok ([#2937](https://github.com/qqqqww1/vm0/issues/2937)) ([4f3fc4e](https://github.com/qqqqww1/vm0/commit/4f3fc4ebf137409a30b85b5882634a6bb8846836))
* add gmail connector with nango platform integration ([#3065](https://github.com/qqqqww1/vm0/issues/3065)) ([d43dfe1](https://github.com/qqqqww1/vm0/commit/d43dfe1a5a868c8413ffd2b8a250d48dafc791cb))
* add markdown preview for prompts, slack image hints, and platform tests ([#2991](https://github.com/qqqqww1/vm0/issues/2991)) ([35da51b](https://github.com/qqqqww1/vm0/commit/35da51b563330c45444e1cb16b3de566519d2c07))
* **api:** add backend support for agent detail page ([#2979](https://github.com/qqqqww1/vm0/issues/2979)) ([4103d8f](https://github.com/qqqqww1/vm0/commit/4103d8f66ccc9546bccc67454d139b8d1de04599))
* **connector:** add deel oauth2 connector ([#3401](https://github.com/qqqqww1/vm0/issues/3401)) ([8128da7](https://github.com/qqqqww1/vm0/commit/8128da7cb693bdb51b006edc7ed8cc1aae14b9c2))
* **connector:** add docusign oauth2 connector ([#3402](https://github.com/qqqqww1/vm0/issues/3402)) ([2273b1c](https://github.com/qqqqww1/vm0/commit/2273b1c3db937c8c2e5794c0348f2d5a063c724e))
* **connector:** add gmail connector feature flag ([#3381](https://github.com/qqqqww1/vm0/issues/3381)) ([50b45eb](https://github.com/qqqqww1/vm0/commit/50b45eb00469afce5b433e03e590fa0070c77458))
* **connector:** add google sheets, docs, and drive oauth2 connectors ([#3403](https://github.com/qqqqww1/vm0/issues/3403)) ([97cca63](https://github.com/qqqqww1/vm0/commit/97cca638861824b887feaa3d97372028e8affdba))
* **connector:** add mercury oauth2 connector ([#3397](https://github.com/qqqqww1/vm0/issues/3397)) ([a5f4e79](https://github.com/qqqqww1/vm0/commit/a5f4e794fe12e6250d770fef1d8ec444a5cdcec3))
* **connector:** add strava and garmin connect oauth2 connectors ([#3399](https://github.com/qqqqww1/vm0/issues/3399)) ([2aa431a](https://github.com/qqqqww1/vm0/commit/2aa431ae1142234ee0d2add1438249540dc91ad8))
* **connectors:** add dropbox oauth connector ([#3368](https://github.com/qqqqww1/vm0/issues/3368)) ([1dc5d4c](https://github.com/qqqqww1/vm0/commit/1dc5d4c151f986ded68c169b19bd7c9c6a07f4b6))
* **connectors:** add feature flag for linear connector visibility ([#3372](https://github.com/qqqqww1/vm0/issues/3372)) ([f6da04e](https://github.com/qqqqww1/vm0/commit/f6da04e4653c62103975cb43f44d7c70067e4dc1))
* **connectors:** add figma oauth connector ([#3369](https://github.com/qqqqww1/vm0/issues/3369)) ([4d93f59](https://github.com/qqqqww1/vm0/commit/4d93f59827c3567ba83ef115d90decc4ca7fa294))
* **connectors:** add gmail oauth connector ([#3332](https://github.com/qqqqww1/vm0/issues/3332)) ([ca303b7](https://github.com/qqqqww1/vm0/commit/ca303b71916095e799c22b975f71216ea89df021))
* **connectors:** add linear oauth connector ([#3366](https://github.com/qqqqww1/vm0/issues/3366)) ([f943498](https://github.com/qqqqww1/vm0/commit/f94349842e5501fe487d078fa7138a3010d65635))
* **connectors:** add self-hosted slack connector ([#3281](https://github.com/qqqqww1/vm0/issues/3281)) ([13e92fd](https://github.com/qqqqww1/vm0/commit/13e92fde8468324ca7502fa8ded5eb60179eba05)), closes [#3279](https://github.com/qqqqww1/vm0/issues/3279)
* **connectors:** add self-hosted slack connector ([#3286](https://github.com/qqqqww1/vm0/issues/3286)) ([6089289](https://github.com/qqqqww1/vm0/commit/608928923103497eadee7c832c9103d9545aa826))
* **connectors:** remove linear connector feature flag ([#3394](https://github.com/qqqqww1/vm0/issues/3394)) ([bcb0266](https://github.com/qqqqww1/vm0/commit/bcb02665109aeda6e5c6052dcdaa8ebe261545e3))
* **core:** add user-targeted feature switch with enabled user ids ([#3451](https://github.com/qqqqww1/vm0/issues/3451)) ([9e1c37a](https://github.com/qqqqww1/vm0/commit/9e1c37ac3a66882f29db39d0d1b11f165bc12f42))
* **deploy:** add self-hosted deployment support with docker and local auth ([#2718](https://github.com/qqqqww1/vm0/issues/2718)) ([498da5e](https://github.com/qqqqww1/vm0/commit/498da5e0a411a034df83c18c00fc287143dc0259))
* owner inline editing for agent instructions ([#3015](https://github.com/qqqqww1/vm0/issues/3015)) ([e7022c8](https://github.com/qqqqww1/vm0/commit/e7022c848b7b247ee6f2475c204bfb656588c5ad))
* **platform:** add agent detail page with feature flag gating ([#2998](https://github.com/qqqqww1/vm0/issues/2998)) ([5386de0](https://github.com/qqqqww1/vm0/commit/5386de0662eb2a85e69040788e2ca08e7f976cba))
* **platform:** add agent detail routes and shared signals ([#2989](https://github.com/qqqqww1/vm0/issues/2989)) ([ddf6fca](https://github.com/qqqqww1/vm0/commit/ddf6fca91c2737231a75b77beca2efb3d9bdc8f4))
* **platform:** add agent log detail as nested sub-route ([#3418](https://github.com/qqqqww1/vm0/issues/3418)) ([f4bac30](https://github.com/qqqqww1/vm0/commit/f4bac30730979d345f0bc2d9dfbc36caf9b2459f))
* **platform:** add agent logs and connections pages ([#3017](https://github.com/qqqqww1/vm0/issues/3017)) ([cf943b2](https://github.com/qqqqww1/vm0/commit/cf943b224b55438152ee67d339c60894709133a8))
* **platform:** add config dialog and run dialog for agent detail page ([#3016](https://github.com/qqqqww1/vm0/issues/3016)) ([7811f00](https://github.com/qqqqww1/vm0/commit/7811f0045c022856d283174722cfacf6ced72b7f))
* **platform:** add connector management to settings page ([#2769](https://github.com/qqqqww1/vm0/issues/2769)) ([418bc1e](https://github.com/qqqqww1/vm0/commit/418bc1e2dd6afb94b3caca84abf260bf542359c8)), closes [#2766](https://github.com/qqqqww1/vm0/issues/2766)
* **platform:** add connector-based environment variable setup ([#2847](https://github.com/qqqqww1/vm0/issues/2847)) ([7a0004f](https://github.com/qqqqww1/vm0/commit/7a0004f3c0436e53d591f1308b7ec5b59d56f226))
* **platform:** add editable agent name and skills multi-select to config dialog ([#3216](https://github.com/qqqqww1/vm0/issues/3216)) ([50fc6f3](https://github.com/qqqqww1/vm0/commit/50fc6f3fc03d6595b9ee326df2dd88a1697eb837))
* **platform:** add environment variables setup page ([#2737](https://github.com/qqqqww1/vm0/issues/2737)) ([d33842a](https://github.com/qqqqww1/vm0/commit/d33842a2e5e72eb5bfebe66cd442135b49f35a51))
* **platform:** add incremental polling for log detail auto-refresh ([#2716](https://github.com/qqqqww1/vm0/issues/2716)) ([aad0134](https://github.com/qqqqww1/vm0/commit/aad0134608f0d8af1f55bbe6cda6bcac8972d451))
* **platform:** add lint rule enforcing render mode in tests ([#2802](https://github.com/qqqqww1/vm0/issues/2802)) ([2c8de3b](https://github.com/qqqqww1/vm0/commit/2c8de3b70741f74ea56c17c3f64cdb1f974d7965))
* **platform:** add schedule management dialog and enhanced cron options ([#3211](https://github.com/qqqqww1/vm0/issues/3211)) ([d1f30aa](https://github.com/qqqqww1/vm0/commit/d1f30aa17651a80964296e3c1a677049586b9caa))
* **platform:** add schedule summary tooltip to agent header ([#3221](https://github.com/qqqqww1/vm0/issues/3221)) ([1032c95](https://github.com/qqqqww1/vm0/commit/1032c95b0f9e2d787965f047f4e13e965c62cef7))
* **platform:** detect and display missing secrets for agents ([#2664](https://github.com/qqqqww1/vm0/issues/2664)) ([e43fb63](https://github.com/qqqqww1/vm0/commit/e43fb63d574f3f614254e702c76270b59381fedf))
* **settings:** improve ui consistency and add success notifications ([#2976](https://github.com/qqqqww1/vm0/issues/2976)) ([6418997](https://github.com/qqqqww1/vm0/commit/6418997a206901e7739c6398c9129474449c0e66))
* **slack:** move settings to platform integrations page ([#2797](https://github.com/qqqqww1/vm0/issues/2797)) ([030e41f](https://github.com/qqqqww1/vm0/commit/030e41fa55e7f7eeebb811f6619ad84c954de173))
* **slack:** redirect to provider setup after connect ([#2854](https://github.com/qqqqww1/vm0/issues/2854)) ([3701bf6](https://github.com/qqqqww1/vm0/commit/3701bf66ad61c8d2ed525e2f97547cfa4bca8d82))
* **web:** update connector oauth scopes and add deel pkce support ([#3459](https://github.com/qqqqww1/vm0/issues/3459)) ([3c9926a](https://github.com/qqqqww1/vm0/commit/3c9926ac223b3458c9ffc38600e0c19cc552b044))


### Bug Fixes

* hide connect button while polling ([#3107](https://github.com/qqqqww1/vm0/issues/3107)) ([be3af5d](https://github.com/qqqqww1/vm0/commit/be3af5da3a372d5f110410279e10db860dfabf75))
* **platform:** add bg-card to agent instructions container ([#3454](https://github.com/qqqqww1/vm0/issues/3454)) ([5319877](https://github.com/qqqqww1/vm0/commit/5319877e6071c47e779f4c8141be8c950f1a8014))
* **platform:** connector setup improvements and trailing ? fix ([#2857](https://github.com/qqqqww1/vm0/issues/2857)) ([5f65661](https://github.com/qqqqww1/vm0/commit/5f656610669ccc9999d709f0b8f06f6f15f4ef49))
* **platform:** enforce MSW onUnhandledRequest error mode ([#2791](https://github.com/qqqqww1/vm0/issues/2791)) ([ce092a5](https://github.com/qqqqww1/vm0/commit/ce092a514d198fef5cb90b0ae72818c874c2a383))
* **platform:** fix agents page missing vars, connector suggestions, and stale state ([#2946](https://github.com/qqqqww1/vm0/issues/2946)) ([b20addf](https://github.com/qqqqww1/vm0/commit/b20addf0266a0326ee5f263d54ba299f7e71546e))
* **platform:** fix bash error overflow and markdown table light mode ([#2891](https://github.com/qqqqww1/vm0/issues/2891)) ([98c89fd](https://github.com/qqqqww1/vm0/commit/98c89fd53acfe601bc818b1b48b5d67e30676374))
* **platform:** improve environment-variables-setup connector UI ([#2932](https://github.com/qqqqww1/vm0/issues/2932)) ([fbc02b1](https://github.com/qqqqww1/vm0/commit/fbc02b16f832ee35fe914210f5cd1224737bf973))
* **platform:** persist model selection for providers with predefined models ([#2925](https://github.com/qqqqww1/vm0/issues/2925)) ([cf014c0](https://github.com/qqqqww1/vm0/commit/cf014c0a6c4a439748251023937b97f5d60dcf6c)), closes [#2923](https://github.com/qqqqww1/vm0/issues/2923)
* **platform:** resolve empty logs page for scoped agents ([#3392](https://github.com/qqqqww1/vm0/issues/3392)) ([d611bd0](https://github.com/qqqqww1/vm0/commit/d611bd026a6f74a27707c3877c1c4f9cb19acb65))
* **platform:** show skeleton loading state instead of flashing empty state in secrets/vars lists ([#2840](https://github.com/qqqqww1/vm0/issues/2840)) ([cab7682](https://github.com/qqqqww1/vm0/commit/cab7682483252324f0d4e14dfa07b67fceb5ac0a)), closes [#2658](https://github.com/qqqqww1/vm0/issues/2658)
* **platform:** show workspace agent in slack settings when not owned by user ([#2918](https://github.com/qqqqww1/vm0/issues/2918)) ([07f5451](https://github.com/qqqqww1/vm0/commit/07f54516e32bca44c3fa61cff0b696a390cf741c))
* **platform:** use existing schedule name when editing and fix error parsing ([#3421](https://github.com/qqqqww1/vm0/issues/3421)) ([810345b](https://github.com/qqqqww1/vm0/commit/810345b073a40712624cfd714010e13e615af688))
* remove eslint-disable for unused vars in error boundary ([#3289](https://github.com/qqqqww1/vm0/issues/3289)) ([f6e9c79](https://github.com/qqqqww1/vm0/commit/f6e9c79716d34cd2a72c97ebf7e9297f20b52fed))
* remove nango integration and simplify oauth flow ([#3105](https://github.com/qqqqww1/vm0/issues/3105)) ([a1c601e](https://github.com/qqqqww1/vm0/commit/a1c601e2217456d16b1e34de0a41fe61a0026e7a))
* resolve double scrollbar on mobile safari in agent detail page ([#3386](https://github.com/qqqqww1/vm0/issues/3386)) ([2e75a81](https://github.com/qqqqww1/vm0/commit/2e75a818b1985ea607c64dd453512d0fbfe9c50a)), closes [#3229](https://github.com/qqqqww1/vm0/issues/3229)
* sanitize mock data and rename platform env var ([#2912](https://github.com/qqqqww1/vm0/issues/2912)) ([b56b513](https://github.com/qqqqww1/vm0/commit/b56b513076eddc3d25b4e106e005b2ab9bc4f518))
* **slack:** preserve scope prefix in agent navigation and selection ([#3223](https://github.com/qqqqww1/vm0/issues/3223)) ([61bd643](https://github.com/qqqqww1/vm0/commit/61bd643a4e6b0f2977dddf881fd7f5718382e6a6))


### Performance Improvements

* **platform:** skip rendering in signal-only tests ([#2798](https://github.com/qqqqww1/vm0/issues/2798)) ([e438809](https://github.com/qqqqww1/vm0/commit/e4388091362b0e7812ea859c9a085061a99a6acf))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @vm0/core bumped to 8.29.0
</details>

<details><summary>docs: 2.14.0</summary>

## [2.14.0](https://github.com/qqqqww1/vm0/compare/docs-v2.13.0...docs-v2.14.0) (2026-03-02)


### Features

* **docs:** add ecosystem section with slack integration guide ([#2635](https://github.com/qqqqww1/vm0/issues/2635)) ([3a0d45a](https://github.com/qqqqww1/vm0/commit/3a0d45a84e8bc834bb409d39d109e2dd7ef3a844))
* **docs:** update slack docs and rename ecosystem to integrations ([#2917](https://github.com/qqqqww1/vm0/issues/2917)) ([fe90cd9](https://github.com/qqqqww1/vm0/commit/fe90cd90aa92291fd3f277ca324dd9f43d76b6ac))
* **self-host:** add docker compose setup ([#2853](https://github.com/qqqqww1/vm0/issues/2853)) ([bd757fd](https://github.com/qqqqww1/vm0/commit/bd757fd21385dca449e82f6880bc5265dcf1b80d))
</details>

<details><summary>web: 12.61.0</summary>

## [12.61.0](https://github.com/qqqqww1/vm0/compare/web-v12.60.0...web-v12.61.0) (2026-03-02)


### Features

* add computer connector api for authenticated local tunneling via ngrok ([#2937](https://github.com/qqqqww1/vm0/issues/2937)) ([4f3fc4e](https://github.com/qqqqww1/vm0/commit/4f3fc4ebf137409a30b85b5882634a6bb8846836))
* add gmail connector with nango platform integration ([#3065](https://github.com/qqqqww1/vm0/issues/3065)) ([d43dfe1](https://github.com/qqqqww1/vm0/commit/d43dfe1a5a868c8413ffd2b8a250d48dafc791cb))
* add markdown preview for prompts, slack image hints, and platform tests ([#2991](https://github.com/qqqqww1/vm0/issues/2991)) ([35da51b](https://github.com/qqqqww1/vm0/commit/35da51b563330c45444e1cb16b3de566519d2c07))
* add notify-slack preference to gate slack schedule notifications ([#2945](https://github.com/qqqqww1/vm0/issues/2945)) ([a0058e6](https://github.com/qqqqww1/vm0/commit/a0058e6d2c2a7f6c4d20c78a287488ba843cce02))
* add organization scope support with clerk integration ([#2863](https://github.com/qqqqww1/vm0/issues/2863)) ([ec821d7](https://github.com/qqqqww1/vm0/commit/ec821d79768153368aa3ff213b31e3e219baf320))
* add webhook callback mechanism for agent run completion ([#2829](https://github.com/qqqqww1/vm0/issues/2829)) ([6069b7c](https://github.com/qqqqww1/vm0/commit/6069b7c6c99bc8bda79f214e10df5d2590ef5fad))
* allow users to set timezone preference for sandbox and scheduling ([#2866](https://github.com/qqqqww1/vm0/issues/2866)) ([89437c7](https://github.com/qqqqww1/vm0/commit/89437c733b4e34eee46009b20c99f455c5963289))
* **api:** add backend support for agent detail page ([#2979](https://github.com/qqqqww1/vm0/issues/2979)) ([4103d8f](https://github.com/qqqqww1/vm0/commit/4103d8f66ccc9546bccc67454d139b8d1de04599))
* **api:** include email-shared agents in agent list endpoints ([#2941](https://github.com/qqqqww1/vm0/issues/2941)) ([1687a74](https://github.com/qqqqww1/vm0/commit/1687a7453b1fa796b85327f959cbfefe1f3f9ee4))
* **cli:** add --check-env flag to vm0 run commands ([#2760](https://github.com/qqqqww1/vm0/issues/2760)) ([f6711e0](https://github.com/qqqqww1/vm0/commit/f6711e0d047aa872c76f97c8cfaf1257d2f35fb0))
* **cli:** add agent delete command ([#2767](https://github.com/qqqqww1/vm0/issues/2767)) ([11d555a](https://github.com/qqqqww1/vm0/commit/11d555ad5432a9893ddc37e55f89a58e7dd5657c))
* **cli:** add computer connector support ([#3124](https://github.com/qqqqww1/vm0/issues/3124)) ([a950821](https://github.com/qqqqww1/vm0/commit/a9508213014337b0a4a7effb4756ed7056e3cb0f))
* **connector:** add deel oauth2 connector ([#3401](https://github.com/qqqqww1/vm0/issues/3401)) ([8128da7](https://github.com/qqqqww1/vm0/commit/8128da7cb693bdb51b006edc7ed8cc1aae14b9c2))
* **connector:** add docusign oauth2 connector ([#3402](https://github.com/qqqqww1/vm0/issues/3402)) ([2273b1c](https://github.com/qqqqww1/vm0/commit/2273b1c3db937c8c2e5794c0348f2d5a063c724e))
* **connector:** add google sheets, docs, and drive oauth2 connectors ([#3403](https://github.com/qqqqww1/vm0/issues/3403)) ([97cca63](https://github.com/qqqqww1/vm0/commit/97cca638861824b887feaa3d97372028e8affdba))
* **connector:** add mercury oauth2 connector ([#3397](https://github.com/qqqqww1/vm0/issues/3397)) ([a5f4e79](https://github.com/qqqqww1/vm0/commit/a5f4e794fe12e6250d770fef1d8ec444a5cdcec3))
* **connector:** add strava and garmin connect oauth2 connectors ([#3399](https://github.com/qqqqww1/vm0/issues/3399)) ([2aa431a](https://github.com/qqqqww1/vm0/commit/2aa431ae1142234ee0d2add1438249540dc91ad8))
* **connectors:** add dropbox oauth connector ([#3368](https://github.com/qqqqww1/vm0/issues/3368)) ([1dc5d4c](https://github.com/qqqqww1/vm0/commit/1dc5d4c151f986ded68c169b19bd7c9c6a07f4b6))
* **connectors:** add feature flag for linear connector visibility ([#3372](https://github.com/qqqqww1/vm0/issues/3372)) ([f6da04e](https://github.com/qqqqww1/vm0/commit/f6da04e4653c62103975cb43f44d7c70067e4dc1))
* **connectors:** add figma oauth connector ([#3369](https://github.com/qqqqww1/vm0/issues/3369)) ([4d93f59](https://github.com/qqqqww1/vm0/commit/4d93f59827c3567ba83ef115d90decc4ca7fa294))
* **connectors:** add gmail oauth connector ([#3332](https://github.com/qqqqww1/vm0/issues/3332)) ([ca303b7](https://github.com/qqqqww1/vm0/commit/ca303b71916095e799c22b975f71216ea89df021))
* **connectors:** add linear oauth connector ([#3366](https://github.com/qqqqww1/vm0/issues/3366)) ([f943498](https://github.com/qqqqww1/vm0/commit/f94349842e5501fe487d078fa7138a3010d65635))
* **connectors:** add self-hosted slack connector ([#3281](https://github.com/qqqqww1/vm0/issues/3281)) ([13e92fd](https://github.com/qqqqww1/vm0/commit/13e92fde8468324ca7502fa8ded5eb60179eba05)), closes [#3279](https://github.com/qqqqww1/vm0/issues/3279)
* **connectors:** add self-hosted slack connector ([#3286](https://github.com/qqqqww1/vm0/issues/3286)) ([6089289](https://github.com/qqqqww1/vm0/commit/608928923103497eadee7c832c9103d9545aa826))
* **connectors:** add token expiry and refresh token storage (phase 0.5) ([#3326](https://github.com/qqqqww1/vm0/issues/3326)) ([d1f42f8](https://github.com/qqqqww1/vm0/commit/d1f42f87be4075be2c8d98051b7c91eddd07e959))
* **deploy:** add self-hosted deployment support with docker and local auth ([#2718](https://github.com/qqqqww1/vm0/issues/2718)) ([498da5e](https://github.com/qqqqww1/vm0/commit/498da5e0a411a034df83c18c00fc287143dc0259))
* **docs:** update slack docs and rename ecosystem to integrations ([#2917](https://github.com/qqqqww1/vm0/issues/2917)) ([fe90cd9](https://github.com/qqqqww1/vm0/commit/fe90cd90aa92291fd3f277ca324dd9f43d76b6ac))
* **email:** add email notifications and reply-to-continue via Resend ([#2836](https://github.com/qqqqww1/vm0/issues/2836)) ([fd6aa4c](https://github.com/qqqqww1/vm0/commit/fd6aa4c032a84f25e8c6a8cf4ba4cef5ff070bd9))
* **email:** add email-triggered agent runs ([#2959](https://github.com/qqqqww1/vm0/issues/2959)) ([a4ce976](https://github.com/qqqqww1/vm0/commit/a4ce976bd364744ef8f73bf575c5272d1682cb04))
* **email:** add threading, mirrored from address, and original subject to trigger response ([#3227](https://github.com/qqqqww1/vm0/issues/3227)) ([21f7962](https://github.com/qqqqww1/vm0/commit/21f79620893424bdf8b9d465cf203354011f99c6))
* **email:** add vm0 branding to scheduled run notifications ([#2949](https://github.com/qqqqww1/vm0/issues/2949)) ([db03c4a](https://github.com/qqqqww1/vm0/commit/db03c4af4c67cb25c57163238e241a76a5e67348))
* **email:** auto-detect scope from sender for agent-only addresses ([#3198](https://github.com/qqqqww1/vm0/issues/3198)) ([ad0837d](https://github.com/qqqqww1/vm0/commit/ad0837dba470110ca1bd13840ff171e9feed8860))
* **email:** improve reply template with content-first layout ([#3261](https://github.com/qqqqww1/vm0/issues/3261)) ([3d28058](https://github.com/qqqqww1/vm0/commit/3d280583470605ff095f063424109e216a823c8e))
* **email:** pass attachments to agent sessions via r2 presigned urls ([#3249](https://github.com/qqqqww1/vm0/issues/3249)) ([b524482](https://github.com/qqqqww1/vm0/commit/b524482998f31d443e65da1f211bf6479d478f81))
* **email:** send error reply emails for inbound processing failures ([#3400](https://github.com/qqqqww1/vm0/issues/3400)) ([5d781fe](https://github.com/qqqqww1/vm0/commit/5d781fe0aaee3cfb29482f7140085a384d24a002))
* **github:** add database schema for github issue integration ([#3456](https://github.com/qqqqww1/vm0/issues/3456)) ([0d1f88d](https://github.com/qqqqww1/vm0/commit/0d1f88dd939c691c357467dca492a0ba59b7a66f)), closes [#3439](https://github.com/qqqqww1/vm0/issues/3439)
* owner inline editing for agent instructions ([#3015](https://github.com/qqqqww1/vm0/issues/3015)) ([e7022c8](https://github.com/qqqqww1/vm0/commit/e7022c848b7b247ee6f2475c204bfb656588c5ad))
* **platform:** add agent detail page with feature flag gating ([#2998](https://github.com/qqqqww1/vm0/issues/2998)) ([5386de0](https://github.com/qqqqww1/vm0/commit/5386de0662eb2a85e69040788e2ca08e7f976cba))
* **platform:** add config dialog and run dialog for agent detail page ([#3016](https://github.com/qqqqww1/vm0/issues/3016)) ([7811f00](https://github.com/qqqqww1/vm0/commit/7811f0045c022856d283174722cfacf6ced72b7f))
* **platform:** add connector management to settings page ([#2769](https://github.com/qqqqww1/vm0/issues/2769)) ([418bc1e](https://github.com/qqqqww1/vm0/commit/418bc1e2dd6afb94b3caca84abf260bf542359c8)), closes [#2766](https://github.com/qqqqww1/vm0/issues/2766)
* **platform:** add editable agent name and skills multi-select to config dialog ([#3216](https://github.com/qqqqww1/vm0/issues/3216)) ([50fc6f3](https://github.com/qqqqww1/vm0/commit/50fc6f3fc03d6595b9ee326df2dd88a1697eb837))
* **platform:** detect and display missing secrets for agents ([#2664](https://github.com/qqqqww1/vm0/issues/2664)) ([e43fb63](https://github.com/qqqqww1/vm0/commit/e43fb63d574f3f614254e702c76270b59381fedf))
* **runner:** inject agent name and scope env vars into sandbox runtime ([#3375](https://github.com/qqqqww1/vm0/issues/3375)) ([53a1d42](https://github.com/qqqqww1/vm0/commit/53a1d4211cf4dbb477b1fb92a2412b719d46d8a8))
* **scope:** enable vm0 admin users to activate system scope ([#3378](https://github.com/qqqqww1/vm0/issues/3378)) ([c4d05ac](https://github.com/qqqqww1/vm0/commit/c4d05acc257e7777dab8822362e07437add11511))
* **self-host:** add docker compose setup ([#2853](https://github.com/qqqqww1/vm0/issues/2853)) ([bd757fd](https://github.com/qqqqww1/vm0/commit/bd757fd21385dca449e82f6880bc5265dcf1b80d))
* simplify environment variable naming ([#3047](https://github.com/qqqqww1/vm0/issues/3047)) ([609ba7d](https://github.com/qqqqww1/vm0/commit/609ba7d35985e905f6e198275e0ab862313deafe))
* simplify environment variable naming ([#3050](https://github.com/qqqqww1/vm0/issues/3050)) ([9241e1f](https://github.com/qqqqww1/vm0/commit/9241e1fc28e12024fad37e27334c79569fd69665))
* **slack:** add compose agent button to app home ([#2751](https://github.com/qqqqww1/vm0/issues/2751)) ([f5ee9e5](https://github.com/qqqqww1/vm0/commit/f5ee9e57f03b7c5db669480923f019a3a7875e8e))
* **slack:** add context preamble for better tone matching ([#3433](https://github.com/qqqqww1/vm0/issues/3433)) ([1fb35b0](https://github.com/qqqqww1/vm0/commit/1fb35b0e0c118f1a5fa08e74a6caa72068f80cfe))
* **slack:** add documentation link to app home and help command ([#2744](https://github.com/qqqqww1/vm0/issues/2744)) ([17145af](https://github.com/qqqqww1/vm0/commit/17145af4512ad4181a7d368bc1b8d931fbf46355))
* **slack:** auto-setup scope, model provider check, and artifact during link flow ([#2697](https://github.com/qqqqww1/vm0/issues/2697)) ([846f90d](https://github.com/qqqqww1/vm0/commit/846f90d652a63bb9c1487768f79cf637f9fa3798))
* **slack:** deduplicate context messages across thread turns ([#2641](https://github.com/qqqqww1/vm0/issues/2641)) ([f0159cb](https://github.com/qqqqww1/vm0/commit/f0159cbccb96089a6379735617836ca930a247ca))
* **slack:** move settings to platform integrations page ([#2797](https://github.com/qqqqww1/vm0/issues/2797)) ([030e41f](https://github.com/qqqqww1/vm0/commit/030e41fa55e7f7eeebb811f6619ad84c954de173))
* **slack:** redesign to per-workspace single-agent model ([#2772](https://github.com/qqqqww1/vm0/issues/2772)) ([58f2b94](https://github.com/qqqqww1/vm0/commit/58f2b94b8c6220a5c87de3ecc13bca5eae60dd08))
* **slack:** redirect to provider setup after connect ([#2854](https://github.com/qqqqww1/vm0/issues/2854)) ([3701bf6](https://github.com/qqqqww1/vm0/commit/3701bf66ad61c8d2ed525e2f97547cfa4bca8d82))
* **slack:** replace thinking reaction with assistant thread status ([#3410](https://github.com/qqqqww1/vm0/issues/3410)) ([08ebf8a](https://github.com/qqqqww1/vm0/commit/08ebf8ad2ed2b2e1c821040fd12f94c22532542c))
* **slack:** send DM notification when scheduled agent run completes ([#2720](https://github.com/qqqqww1/vm0/issues/2720)) ([77cf47b](https://github.com/qqqqww1/vm0/commit/77cf47b9911a28394bd0b851d75183ea22764bab))
* **storage:** add optional volume support for graceful degradation ([#2929](https://github.com/qqqqww1/vm0/issues/2929)) ([fd052a4](https://github.com/qqqqww1/vm0/commit/fd052a4fef4b2157bb1b1a7a2a0eaccffa6ff262))
* **storage:** auto-create artifact when not found during run ([#3446](https://github.com/qqqqww1/vm0/issues/3446)) ([1b045c4](https://github.com/qqqqww1/vm0/commit/1b045c4ee576d41bc94c39a410c13341a0190e75))
* use ngrok reserved domains for computer connector ([#3116](https://github.com/qqqqww1/vm0/issues/3116)) ([7e30f2c](https://github.com/qqqqww1/vm0/commit/7e30f2c83f7fb4f82dd0b1e9aed38267ca5919f9))
* **web:** add eslint rule to detect duplicate migration prefixes ([#2845](https://github.com/qqqqww1/vm0/issues/2845)) ([7fcd801](https://github.com/qqqqww1/vm0/commit/7fcd801491b0e9bd2dd29caa6b4472ae03c93cb1))
* **web:** add eslint rule to forbid relative paths in vi.mock() ([#2748](https://github.com/qqqqww1/vm0/issues/2748)) ([d909568](https://github.com/qqqqww1/vm0/commit/d9095686a9060da19ef6f61a6355c0a9d5459c75))
* **web:** add instatus status popup widget ([#3285](https://github.com/qqqqww1/vm0/issues/3285)) ([c798155](https://github.com/qqqqww1/vm0/commit/c7981558cfba13848884c1f4548b2afcebe719be))
* **web:** add keyword detection for slack agent responses with deep links ([#3003](https://github.com/qqqqww1/vm0/issues/3003)) ([24adaff](https://github.com/qqqqww1/vm0/commit/24adaffd619e65a692eb643a4dec25d8cb6f457c)), closes [#2995](https://github.com/qqqqww1/vm0/issues/2995)
* **web:** add migration consistency testing ([#3066](https://github.com/qqqqww1/vm0/issues/3066)) ([cef8348](https://github.com/qqqqww1/vm0/commit/cef83484f87bfceacf03f1bfd185be49504080da))
* **web:** add Notion OAuth connector support ([#2738](https://github.com/qqqqww1/vm0/issues/2738)) ([a201b5d](https://github.com/qqqqww1/vm0/commit/a201b5d7ffdd081b4a9f299297bad0e06fa890b1))
* **web:** add per-user cloud endpoint with traffic policy for computer connector ([#3019](https://github.com/qqqqww1/vm0/issues/3019)) ([24e8154](https://github.com/qqqqww1/vm0/commit/24e81542baffb2efe15c2633a34e808c37ab2a92))
* **web:** auto-upload skill storage on compose save from platform ([#3434](https://github.com/qqqqww1/vm0/issues/3434)) ([b591a23](https://github.com/qqqqww1/vm0/commit/b591a231e1ebfee1418fa1f1bb71e41514630fa1))
* **web:** update connector oauth scopes and add deel pkce support ([#3459](https://github.com/qqqqww1/vm0/issues/3459)) ([3c9926a](https://github.com/qqqqww1/vm0/commit/3c9926ac223b3458c9ffc38600e0c19cc552b044))


### Bug Fixes

* **api:** include clerk error details in org creation failure logs ([#3426](https://github.com/qqqqww1/vm0/issues/3426)) ([59fb565](https://github.com/qqqqww1/vm0/commit/59fb5657ab9f3c4865cfb806c10caafab779bd38))
* **api:** preserve slack admin and default agent on workspace re-install ([#2963](https://github.com/qqqqww1/vm0/issues/2963)) ([d8f26b2](https://github.com/qqqqww1/vm0/commit/d8f26b2e9146fd0923f88c7f082c2c117dfc5a79))
* **api:** use framework-based filename lookup in instructions api ([#3192](https://github.com/qqqqww1/vm0/issues/3192)) ([607608a](https://github.com/qqqqww1/vm0/commit/607608aa76b4237e2692dec598318a614e44ac02))
* **db:** clean up fk references before deleting system scopes in migration 0093 ([#3455](https://github.com/qqqqww1/vm0/issues/3455)) ([ce9ed6a](https://github.com/qqqqww1/vm0/commit/ce9ed6a1ef3df2cdb9e1a813feec5f1ea7fc1ed6))
* **db:** register orphaned migration 0077 as 0079 in journal ([#2785](https://github.com/qqqqww1/vm0/issues/2785)) ([7a5e013](https://github.com/qqqqww1/vm0/commit/7a5e01395c083b497b38ff3c1b36a3a15b0c6828))
* **email:** align reply subject with schedule notification for threading ([#2952](https://github.com/qqqqww1/vm0/issues/2952)) ([b70c814](https://github.com/qqqqww1/vm0/commit/b70c8149847e70ab831ea2e7f502d6efcdda1711))
* **email:** correct In-Reply-To and References headers for proper threading ([#3235](https://github.com/qqqqww1/vm0/issues/3235)) ([fe86f75](https://github.com/qqqqww1/vm0/commit/fe86f752d24b8f5497db6044ff1504bb93f54fee))
* **email:** prefer html body with text fallback for inbound email content ([#3220](https://github.com/qqqqww1/vm0/issues/3220)) ([d10236f](https://github.com/qqqqww1/vm0/commit/d10236ff20612560cd99f06cecb2a42b002dd741))
* **email:** validate sender authenticity via dmarc for email triggers ([#3196](https://github.com/qqqqww1/vm0/issues/3196)) ([aec7039](https://github.com/qqqqww1/vm0/commit/aec703937eb780fdc5594ef600d92b13d9c579a7)), closes [#3194](https://github.com/qqqqww1/vm0/issues/3194)
* enable parallel test execution in web app ([#2865](https://github.com/qqqqww1/vm0/issues/2865)) ([0c04ef0](https://github.com/qqqqww1/vm0/commit/0c04ef08066bf2854b43029b862a48511cce2ccb))
* ensure after() awaits callback dispatch promise ([#2902](https://github.com/qqqqww1/vm0/issues/2902)) ([d62c92f](https://github.com/qqqqww1/vm0/commit/d62c92fcbcf0f7ac330493a6a8be1d52f8643d26))
* exclude connector-provided secrets from missing-secrets checks ([#2752](https://github.com/qqqqww1/vm0/issues/2752)) ([3dc98d4](https://github.com/qqqqww1/vm0/commit/3dc98d47451a2084b50a9a6ebce2f2ccb31d2833)), closes [#2747](https://github.com/qqqqww1/vm0/issues/2747)
* improve validation error handler robustness ([#3114](https://github.com/qqqqww1/vm0/issues/3114)) ([6506d06](https://github.com/qqqqww1/vm0/commit/6506d066ab5dd01c4c33a3f1e6dbe6241ac662cb))
* **platform:** fix bash error overflow and markdown table light mode ([#2891](https://github.com/qqqqww1/vm0/issues/2891)) ([98c89fd](https://github.com/qqqqww1/vm0/commit/98c89fd53acfe601bc818b1b48b5d67e30676374))
* **platform:** resolve empty logs page for scoped agents ([#3392](https://github.com/qqqqww1/vm0/issues/3392)) ([d611bd0](https://github.com/qqqqww1/vm0/commit/d611bd026a6f74a27707c3877c1c4f9cb19acb65))
* prevent env validation errors on client side ([#3059](https://github.com/qqqqww1/vm0/issues/3059)) ([886bd66](https://github.com/qqqqww1/vm0/commit/886bd663b062ec515d59821663d21011f83b391e))
* redirect to platform after sign-up and handle locale-prefixed auth paths ([#3438](https://github.com/qqqqww1/vm0/issues/3438)) ([28206ac](https://github.com/qqqqww1/vm0/commit/28206ac632eb65148d1fdb4b0829a3fd95c836cd)), closes [#3390](https://github.com/qqqqww1/vm0/issues/3390)
* remove eslint-disable for no-explicit-any in global types ([#3292](https://github.com/qqqqww1/vm0/issues/3292)) ([d8dbc75](https://github.com/qqqqww1/vm0/commit/d8dbc75cf99ab682b7383cbd499320d2f281fb8d))
* remove eslint-disable for no-html-link-for-pages in navbar ([#3293](https://github.com/qqqqww1/vm0/issues/3293)) ([55532c4](https://github.com/qqqqww1/vm0/commit/55532c453ff0d9afdb6684e4a58a2f6f2f4a330f))
* remove eslint-disable suppressions in skills client ([#3294](https://github.com/qqqqww1/vm0/issues/3294)) ([42cf6e3](https://github.com/qqqqww1/vm0/commit/42cf6e3cd1348113807ad109f589e15eeda6c20f))
* remove lint suppressions in test-helpers ([#3296](https://github.com/qqqqww1/vm0/issues/3296)) ([5c2d34f](https://github.com/qqqqww1/vm0/commit/5c2d34fe7d70ed89a31a72d5c4a337cc2fb7b739))
* replace inline image data uris with placeholder in email body ([#3255](https://github.com/qqqqww1/vm0/issues/3255)) ([7bd85bf](https://github.com/qqqqww1/vm0/commit/7bd85bf91ee8b17504bd59615c53f1b2ea9919f9)), closes [#3254](https://github.com/qqqqww1/vm0/issues/3254)
* **schedule:** reject schedule creation for organization-scoped agents ([#3420](https://github.com/qqqqww1/vm0/issues/3420)) ([7945a10](https://github.com/qqqqww1/vm0/commit/7945a10ea3d2c21e8bde0516326f98804e61ea87))
* **slack:** add artifact name to create-run call in slack agent handler ([#2955](https://github.com/qqqqww1/vm0/issues/2955)) ([e12262d](https://github.com/qqqqww1/vm0/commit/e12262d261237b4742160ceb0e00f7291984cf5c))
* **slack:** preserve scope prefix in agent navigation and selection ([#3223](https://github.com/qqqqww1/vm0/issues/3223)) ([61bd643](https://github.com/qqqqww1/vm0/commit/61bd643a4e6b0f2977dddf881fd7f5718382e6a6))
* **slack:** return caddy proxy address for platform in dev environment ([#2687](https://github.com/qqqqww1/vm0/issues/2687)) ([d2fa6e4](https://github.com/qqqqww1/vm0/commit/d2fa6e4c278dc021b490087c505ca43e7beea603))
* **slack:** sync agent permissions when admin switches workspace agent ([#3024](https://github.com/qqqqww1/vm0/issues/3024)) ([dbdafec](https://github.com/qqqqww1/vm0/commit/dbdafeca2ba2483841ac0606d5216a45198f3c4d))
* **slack:** use most recent workspace link for settings api ([#2928](https://github.com/qqqqww1/vm0/issues/2928)) ([53513d1](https://github.com/qqqqww1/vm0/commit/53513d18d9817254a2f6869c6283fa3e618168f6))
* **slack:** use session's compose when continuing conversation ([#2934](https://github.com/qqqqww1/vm0/issues/2934)) ([ca19a82](https://github.com/qqqqww1/vm0/commit/ca19a8266cad225d4e8f3f726f49d3cd66c074e6))
* **telemetry:** await db fallback instead of fire-and-forget ([#2841](https://github.com/qqqqww1/vm0/issues/2841)) ([7dbabc0](https://github.com/qqqqww1/vm0/commit/7dbabc0cdb6c34e1a221d0353aa77b1405e15e03))
* **test:** remove vi.unstubAllEnvs from CLI tests and fix compose job race condition ([#2695](https://github.com/qqqqww1/vm0/issues/2695)) ([04ab29b](https://github.com/qqqqww1/vm0/commit/04ab29bf89201bb921d6a2f63b9ea4e3f2ab899d))
* unify variable resolution in build-context via caller-provided scope ([#3417](https://github.com/qqqqww1/vm0/issues/3417)) ([3563fb2](https://github.com/qqqqww1/vm0/commit/3563fb24962f10f9a4480ec9d7e69540af884398))
* **web:** add pointer-events-none to auth page overlays and fix otp input styles ([#2683](https://github.com/qqqqww1/vm0/issues/2683)) ([aca61f1](https://github.com/qqqqww1/vm0/commit/aca61f16767942d6bd9b5ab4922bd5d22ae258e7))
* **web:** disable json query to fix flaky ambiguous-prefix test ([#2701](https://github.com/qqqqww1/vm0/issues/2701)) ([a5f8e8a](https://github.com/qqqqww1/vm0/commit/a5f8e8a375a3a84c46518780201b66f75ea845a3))
* **web:** ensure platform url is available in client components ([#2873](https://github.com/qqqqww1/vm0/issues/2873)) ([b16f8f9](https://github.com/qqqqww1/vm0/commit/b16f8f93dc7c7487681a214050e874dbe3e898d3))
* **web:** fix drizzle-kit generate partial indexes ([#3062](https://github.com/qqqqww1/vm0/issues/3062)) ([96eca9b](https://github.com/qqqqww1/vm0/commit/96eca9b8b8ee8074f78f43d9fe08761ed4bfe6d4))
* **web:** make vars validation respect checkenv flag ([#2960](https://github.com/qqqqww1/vm0/issues/2960)) ([a52b291](https://github.com/qqqqww1/vm0/commit/a52b291dbbadec36d048387aa1f76c4131d44fd5))
* **web:** rebuild migration snapshots for consistency ([#3070](https://github.com/qqqqww1/vm0/issues/3070)) ([c455382](https://github.com/qqqqww1/vm0/commit/c4553824116e78002f755bcdac28a8041055ac2e))
* **web:** resolve build warnings for circular imports, ssh2, and e2b ([#2933](https://github.com/qqqqww1/vm0/issues/2933)) ([87ac6c4](https://github.com/qqqqww1/vm0/commit/87ac6c4a1884629e415447e37e2f2055b5f8b3a3))
* **web:** suppress remaining build warnings ([#2953](https://github.com/qqqqww1/vm0/issues/2953)) ([8bd2c4f](https://github.com/qqqqww1/vm0/commit/8bd2c4f5bc069f1ca9018ceb99703fd5b3938dd0))
* **web:** use next/link for sign-up to prevent locale prefix 404 ([#3444](https://github.com/qqqqww1/vm0/issues/3444)) ([2e7b471](https://github.com/qqqqww1/vm0/commit/2e7b471a7232ff21da01b4436dc6c958b59ebca7)), closes [#3390](https://github.com/qqqqww1/vm0/issues/3390)


### Performance Improvements

* **ci:** speed up preview deploy with vercel prebuilt and skip sentry source maps ([#2712](https://github.com/qqqqww1/vm0/issues/2712)) ([bf2fdfd](https://github.com/qqqqww1/vm0/commit/bf2fdfdb9c10137bcafe3099f8c107bece82eee6))
* **web:** optimize agent API query performance with JOINs and Promise.all ([#2816](https://github.com/qqqqww1/vm0/issues/2816)) ([5149283](https://github.com/qqqqww1/vm0/commit/5149283480a3c8c2525a75dace00b6c41946f203))
* **web:** replace N+1 upsert loop with single INSERT...SELECT in aggregate-usage cron ([#2795](https://github.com/qqqqww1/vm0/issues/2795)) ([f5dd92c](https://github.com/qqqqww1/vm0/commit/f5dd92c2f1704697895e07fd8fce6b65fe0735dd))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @vm0/core bumped to 8.29.0
</details>

<details><summary>ably-subscriber: 0.7.0</summary>

## [0.7.0](https://github.com/qqqqww1/vm0/compare/ably-subscriber-v0.6.3...ably-subscriber-v0.7.0) (2026-03-02)


### Features

* **ably-subscriber:** add dropped message counter for backpressure observability ([#2913](https://github.com/qqqqww1/vm0/issues/2913)) ([94325b9](https://github.com/qqqqww1/vm0/commit/94325b9481f84026e046b04a96ca7878702c8080)), closes [#2909](https://github.com/qqqqww1/vm0/issues/2909)
* **ably-subscriber:** add rust ably realtime subscribe-only sdk ([#2790](https://github.com/qqqqww1/vm0/issues/2790)) ([d1f630c](https://github.com/qqqqww1/vm0/commit/d1f630cb2d30aab52e46a7aba20f9495da00d2cd))
* **ably-subscriber:** extract timing constants into configurable struct ([#2938](https://github.com/qqqqww1/vm0/issues/2938)) ([0ac4072](https://github.com/qqqqww1/vm0/commit/0ac407272ac166f134d2ca61874f58214a966849))


### Bug Fixes

* **ably-subscriber:** align protocol handling with ably-js sdk ([#3275](https://github.com/qqqqww1/vm0/issues/3275)) ([7b01abf](https://github.com/qqqqww1/vm0/commit/7b01abf76b978416aaf7f6c7ccc3ee6efb94e1c3)), closes [#3274](https://github.com/qqqqww1/vm0/issues/3274)
* **ably-subscriber:** always re-attach channel after reconnect to prevent zombie subscriptions ([#3271](https://github.com/qqqqww1/vm0/issues/3271)) ([0e449cb](https://github.com/qqqqww1/vm0/commit/0e449cb1ef1cb2e54fc05675f6634a0659923497))
* **ably-subscriber:** handle close frames and skip backoff on clean disconnect ([#3263](https://github.com/qqqqww1/vm0/issues/3263)) ([caddb21](https://github.com/qqqqww1/vm0/commit/caddb213b4df4dada54f8d368083ada6a6d9a287)), closes [#3262](https://github.com/qqqqww1/vm0/issues/3262)
* **crates:** use system tls certificates instead of bundled webpki-roots ([#2824](https://github.com/qqqqww1/vm0/issues/2824)) ([aa95e93](https://github.com/qqqqww1/vm0/commit/aa95e9328dc99d77215d30e8545de11211a12792))
</details>

<details><summary>guest-agent: 0.13.0</summary>

## [0.13.0](https://github.com/qqqqww1/vm0/compare/guest-agent-v0.12.3...guest-agent-v0.13.0) (2026-03-02)


### Features

* add intermediate e2e telemetry metrics for cli cold-start diagnosis ([#3251](https://github.com/qqqqww1/vm0/issues/3251)) ([82121a9](https://github.com/qqqqww1/vm0/commit/82121a93edcca096cacc787283edbc7275b88f42)), closes [#3250](https://github.com/qqqqww1/vm0/issues/3250)
* **guest-agent:** add api_to_cli_init telemetry metric ([#3245](https://github.com/qqqqww1/vm0/issues/3245)) ([b1f78b6](https://github.com/qqqqww1/vm0/commit/b1f78b63fbf1da80dd37ee92c3602319cfd1ecdc)), closes [#3244](https://github.com/qqqqww1/vm0/issues/3244)
* **guest-agent:** implement rust guest-agent crate ([#2759](https://github.com/qqqqww1/vm0/issues/2759)) ([8a91042](https://github.com/qqqqww1/vm0/commit/8a910429b6adb47c86659638e69f5a6d024e4851))
* **guest-mock-claude:** add rust mock-claude binary for firecracker vms ([#2783](https://github.com/qqqqww1/vm0/issues/2783)) ([d06b37a](https://github.com/qqqqww1/vm0/commit/d06b37a3c19449f049c83cf32b690bf40c6f77a5))


### Bug Fixes

* **crates:** remove dead code and fix type inconsistency ([#2826](https://github.com/qqqqww1/vm0/issues/2826)) ([63b19d5](https://github.com/qqqqww1/vm0/commit/63b19d57ed29dfbf8c1b3c79a43bc1ebf6a94d96))
* **guest-agent:** add tests and document review followup items ([#2775](https://github.com/qqqqww1/vm0/issues/2775)) ([4c85ea2](https://github.com/qqqqww1/vm0/commit/4c85ea2a731047c6ec459718362aa22a71ab3673))
* **guest-agent:** detect cli process exit to prevent hanging on orphaned pipes ([#3409](https://github.com/qqqqww1/vm0/issues/3409)) ([2381c50](https://github.com/qqqqww1/vm0/commit/2381c50ef76c889e8ab03ee37c994950fd0bd9e3))
* **guest-agent:** only set claude-specific env vars for claude-code cli ([#3416](https://github.com/qqqqww1/vm0/issues/3416)) ([df3f92c](https://github.com/qqqqww1/vm0/commit/df3f92cff9611b017b04d6adfc5a1d43d36376ee))
* **guest-agent:** skip api calls in local provider mode ([#3164](https://github.com/qqqqww1/vm0/issues/3164)) ([6d6d7cd](https://github.com/qqqqww1/vm0/commit/6d6d7cd1423fa59a69ba651a4d32763bca8cfffe))
* **runner:** make runner sole reporter of job completion ([#2852](https://github.com/qqqqww1/vm0/issues/2852)) ([807e2f9](https://github.com/qqqqww1/vm0/commit/807e2f9489ff4780eb3ff235d0eac2baae1b37d1))


### Performance Improvements

* **guest-agent:** disable non-essential cli network traffic on startup ([#3407](https://github.com/qqqqww1/vm0/issues/3407)) ([4b45f77](https://github.com/qqqqww1/vm0/commit/4b45f773632adbb1d3323eeab7e7a4c95506842b))
* **guest-agent:** pre-warm dns cache before cli spawn ([#3298](https://github.com/qqqqww1/vm0/issues/3298)) ([b3e3fb2](https://github.com/qqqqww1/vm0/commit/b3e3fb268df1e3a3570070d81be3c6506277ed2d))
* **sandbox-fc:** enable v8 compile cache for faster cli cold start ([#3267](https://github.com/qqqqww1/vm0/issues/3267)) ([6f1c8be](https://github.com/qqqqww1/vm0/commit/6f1c8be89cd5c7168326b5fa822d26eb2f9fa824))
</details>

<details><summary>guest-download: 0.13.0</summary>

## [0.13.0](https://github.com/qqqqww1/vm0/compare/guest-download-v0.12.3...guest-download-v0.13.0) (2026-03-02)


### Features

* **guest-download:** log download url ([#3323](https://github.com/qqqqww1/vm0/issues/3323)) ([78a6a26](https://github.com/qqqqww1/vm0/commit/78a6a26df02ae3c8ed5b9d3243edbe125f52db30))


### Bug Fixes

* **guest-download:** only treat 404 as non-fatal for artifact downloads ([#2900](https://github.com/qqqqww1/vm0/issues/2900)) ([8711a0f](https://github.com/qqqqww1/vm0/commit/8711a0f5cfad3ac0fa8eda31ff74d48e3fbcde6e))
* **guest-download:** retry on 429 rate limiting ([#2911](https://github.com/qqqqww1/vm0/issues/2911)) ([8913f1d](https://github.com/qqqqww1/vm0/commit/8913f1d0da2d36cbbf286fab12a6bef6ff4d14aa)), closes [#2905](https://github.com/qqqqww1/vm0/issues/2905)
* **guest-download:** skip retry on 4xx errors and log failed url ([#2846](https://github.com/qqqqww1/vm0/issues/2846)) ([8579be9](https://github.com/qqqqww1/vm0/commit/8579be91fa132202f4d0b7361e3fe602fc538e3d))
* **guest-download:** use is_valid_url for artifact and preserve panic info ([#2827](https://github.com/qqqqww1/vm0/issues/2827)) ([55e6b66](https://github.com/qqqqww1/vm0/commit/55e6b660e28f5c7e6744cc2850f884eba2e9296b))
</details>

<details><summary>guest-init: 0.13.0</summary>

## [0.13.0](https://github.com/qqqqww1/vm0/compare/guest-init-v0.12.3...guest-init-v0.13.0) (2026-03-02)


### Bug Fixes

* **vsock-guest:** handle echild race with pid 1 zombie reaper ([#3118](https://github.com/qqqqww1/vm0/issues/3118)) ([985f349](https://github.com/qqqqww1/vm0/commit/985f349134b981d6123fe26ee79f991ec56ceb59))
</details>

<details><summary>guest-mock-claude: 0.13.0</summary>

## [0.13.0](https://github.com/qqqqww1/vm0/compare/guest-mock-claude-v0.12.3...guest-mock-claude-v0.13.0) (2026-03-02)


### Features

* **guest-mock-claude:** add rust mock-claude binary for firecracker vms ([#2783](https://github.com/qqqqww1/vm0/issues/2783)) ([d06b37a](https://github.com/qqqqww1/vm0/commit/d06b37a3c19449f049c83cf32b690bf40c6f77a5))
</details>

<details><summary>runner-rs: 0.13.0</summary>

## [0.13.0](https://github.com/qqqqww1/vm0/compare/runner-rs-v0.12.3...runner-rs-v0.13.0) (2026-03-02)


### Features

* allow users to set timezone preference for sandbox and scheduling ([#2866](https://github.com/qqqqww1/vm0/issues/2866)) ([89437c7](https://github.com/qqqqww1/vm0/commit/89437c733b4e34eee46009b20c99f455c5963289))
* **guest-agent:** implement rust guest-agent crate ([#2759](https://github.com/qqqqww1/vm0/issues/2759)) ([8a91042](https://github.com/qqqqww1/vm0/commit/8a910429b6adb47c86659638e69f5a6d024e4851))
* **runner:** add --dry-run flag to rootfs, snapshot, and build commands ([#3169](https://github.com/qqqqww1/vm0/issues/3169)) ([62b62e3](https://github.com/qqqqww1/vm0/commit/62b62e3cf2931ae14a67ed8d481f702131a4e323)), closes [#3168](https://github.com/qqqqww1/vm0/issues/3168)
* **runner:** add --env flag to benchmark command ([#3335](https://github.com/qqqqww1/vm0/issues/3335)) ([25683a5](https://github.com/qqqqww1/vm0/commit/25683a5049ae80a3644a065d4f401f8ca1887052))
* **runner:** add --env flag to runner service start/install ([#3112](https://github.com/qqqqww1/vm0/issues/3112)) ([d2f8ec8](https://github.com/qqqqww1/vm0/commit/d2f8ec85ca4591ac4f4aa12ffebc073bd1f6ed9f))
* **runner:** add `runner doctor` command for runtime health diagnostics ([#3138](https://github.com/qqqqww1/vm0/issues/3138)) ([e075414](https://github.com/qqqqww1/vm0/commit/e075414291d0aa313af2f903f2f46d75ab0f92b8))
* **runner:** add `runner gc` command to clean up unused rootfs and snapshots ([#3128](https://github.com/qqqqww1/vm0/issues/3128)) ([d4e6235](https://github.com/qqqqww1/vm0/commit/d4e6235c40a63d4f1411ce982ab1800d905d6fe7))
* **runner:** add `setup` command to download firecracker and kernel ([#2825](https://github.com/qqqqww1/vm0/issues/2825)) ([f5ba977](https://github.com/qqqqww1/vm0/commit/f5ba9773e0c4ed54c56cad26d30abc3dafa1bfda))
* **runner:** add ably realtime subscription to start command ([#3048](https://github.com/qqqqww1/vm0/issues/3048)) ([553ba2d](https://github.com/qqqqww1/vm0/commit/553ba2d1727466fd30683a4dd690036df995d7e9))
* **runner:** add benchmark subcommand for single-shot vm execution ([#2982](https://github.com/qqqqww1/vm0/issues/2982)) ([a4ee02a](https://github.com/qqqqww1/vm0/commit/a4ee02ad56e2c86b6a4bbbc9f03fa6ebe99c474c))
* **runner:** add build command combining rootfs + snapshot ([#2914](https://github.com/qqqqww1/vm0/issues/2914)) ([305c038](https://github.com/qqqqww1/vm0/commit/305c03867368a44f30d2421e9f23490ec91e960f))
* **runner:** add build-rootfs command to replace bash script ([#2858](https://github.com/qqqqww1/vm0/issues/2858)) ([3a298f6](https://github.com/qqqqww1/vm0/commit/3a298f6a29941e14e062cfb4301ea112c69ccad4))
* **runner:** add execution telemetry for sandbox operations ([#3068](https://github.com/qqqqww1/vm0/issues/3068)) ([4e7fbb3](https://github.com/qqqqww1/vm0/commit/4e7fbb3545f1d548a8e6345d120b560a0a3439a2))
* **runner:** add firewall rules and seal secrets to proxy registry ([#3028](https://github.com/qqqqww1/vm0/issues/3028)) ([752f9b5](https://github.com/qqqqww1/vm0/commit/752f9b549447dde65c23bd81bcc9e805796d441d))
* **runner:** add kill command to terminate running sandboxes ([#3153](https://github.com/qqqqww1/vm0/issues/3153)) ([26d4e7d](https://github.com/qqqqww1/vm0/commit/26d4e7d1763eaa55166e243ecc96052ceba15c7c))
* **runner:** add local job provider and submit command ([#3158](https://github.com/qqqqww1/vm0/issues/3158)) ([4d300cb](https://github.com/qqqqww1/vm0/commit/4d300cb95baa0713866d7332a050e4b5b32c6ac1))
* **runner:** add mitmproxy integration to benchmark command ([#3027](https://github.com/qqqqww1/vm0/issues/3027)) ([7dab1cd](https://github.com/qqqqww1/vm0/commit/7dab1cd38f8c4e58fbdca98890b5a3b21bf53e9e))
* **runner:** add proxy support to start command ([#3045](https://github.com/qqqqww1/vm0/issues/3045)) ([5a7016f](https://github.com/qqqqww1/vm0/commit/5a7016f20e698c616728d42bca481c8c87338623))
* **runner:** add runner.yaml config file generated by build ([#2935](https://github.com/qqqqww1/vm0/issues/2935)) ([9b9577a](https://github.com/qqqqww1/vm0/commit/9b9577a3197b72f64866ff12769fa919c252a347))
* **runner:** add service subcommand for systemd lifecycle management ([#3098](https://github.com/qqqqww1/vm0/issues/3098)) ([9686c65](https://github.com/qqqqww1/vm0/commit/9686c659797f53c58333903968a4b3b62d3523ef))
* **runner:** add snapshot subcommand with content-addressable caching ([#2903](https://github.com/qqqqww1/vm0/issues/2903)) ([c00ab8d](https://github.com/qqqqww1/vm0/commit/c00ab8d387bcdca0917ed1efd13a870c032adf44))
* **runner:** add version flag to cli ([#3038](https://github.com/qqqqww1/vm0/issues/3038)) ([0afc49a](https://github.com/qqqqww1/vm0/commit/0afc49a163e76d6f999fb9c94ff3067109f0ff8e))
* **runner:** auto-restart mitmproxy on crash ([#3083](https://github.com/qqqqww1/vm0/issues/3083)) ([2261025](https://github.com/qqqqww1/vm0/commit/2261025f85537333b76299903748be96c5c9dfb5))
* **runner:** copy guest system log to host after job ([#3329](https://github.com/qqqqww1/vm0/issues/3329)) ([e1fc90b](https://github.com/qqqqww1/vm0/commit/e1fc90ba7f5f8b555a93028e05086ffac6c3c003))
* **runner:** detect oom kills and return clear error message ([#3093](https://github.com/qqqqww1/vm0/issues/3093)) ([38718c9](https://github.com/qqqqww1/vm0/commit/38718c9a00485e33a623954778e41cdfda89ec0f))
* **runner:** download and install mitmdump in setup command ([#2838](https://github.com/qqqqww1/vm0/issues/2838)) ([d171672](https://github.com/qqqqww1/vm0/commit/d171672409b0cdd1b850dc3db07d1ecbc5592364))
* **runner:** embed guest binaries via build.rs ([#3319](https://github.com/qqqqww1/vm0/issues/3319)) ([acacb39](https://github.com/qqqqww1/vm0/commit/acacb39e6861d04853f148be090367f6de0e8f8a))
* **runner:** extend gc to clean up old deployment versions ([#3201](https://github.com/qqqqww1/vm0/issues/3201)) ([09f2d1c](https://github.com/qqqqww1/vm0/commit/09f2d1cabac6089daf4bb2365abb88d95e1065c4))
* **runner:** gc stale network log files older than 7 days ([#3137](https://github.com/qqqqww1/vm0/issues/3137)) ([43bb9c1](https://github.com/qqqqww1/vm0/commit/43bb9c1ec457b208005333bcdd570c2860fbc429))
* **runner:** gc system and metrics logs alongside network logs ([#3330](https://github.com/qqqqww1/vm0/issues/3330)) ([4e5b0fb](https://github.com/qqqqww1/vm0/commit/4e5b0fbc68eb9ddd4c472561756a8c22f412bd0b))
* **runner:** implement rust runner crate for job polling and execution ([#2722](https://github.com/qqqqww1/vm0/issues/2722)) ([38b494e](https://github.com/qqqqww1/vm0/commit/38b494e563f0c87486419a36df265fe5c0d8c032))
* **runner:** log snapshot file sizes (logical and disk) ([#2997](https://github.com/qqqqww1/vm0/issues/2997)) ([671cbad](https://github.com/qqqqww1/vm0/commit/671cbad4d55594dbc5df4858fa6acbfffcbee57b))
* **runner:** redirect guest-download output to system log file ([#3328](https://github.com/qqqqww1/vm0/issues/3328)) ([68ba78d](https://github.com/qqqqww1/vm0/commit/68ba78dcb0e931aae14c74d1cd809b4f6d5924d1))
* **runner:** replace socket-based local provider with file queue ([#3166](https://github.com/qqqqww1/vm0/issues/3166)) ([658c007](https://github.com/qqqqww1/vm0/commit/658c007f30a633934d4d691791b46361ddf236fc))
* **runner:** upload mitmproxy network logs to telemetry endpoint ([#3071](https://github.com/qqqqww1/vm0/issues/3071)) ([80023b0](https://github.com/qqqqww1/vm0/commit/80023b0f627d6b3b57bd1aa9a46cd4244118710e))
* **runner:** use service install/drain in ci upgrade test ([#3167](https://github.com/qqqqww1/vm0/issues/3167)) ([4ebb1d7](https://github.com/qqqqww1/vm0/commit/4ebb1d73afd5405cdbe21d0c4aa88280606f386b))
* **runner:** write logs to file in addition to stderr ([#3101](https://github.com/qqqqww1/vm0/issues/3101)) ([fa4000b](https://github.com/qqqqww1/vm0/commit/fa4000bec7db04abcc040076121c43caecbf3354))
* **sandbox-fc:** per-sandbox proxy control with dual-queue netns pool ([#3035](https://github.com/qqqqww1/vm0/issues/3035)) ([deda648](https://github.com/qqqqww1/vm0/commit/deda64875625f49f4a72513d2b286dba12be0986)), closes [#3033](https://github.com/qqqqww1/vm0/issues/3033)
* **vsock:** add environment variable support to exec/spawn_watch ([#2736](https://github.com/qqqqww1/vm0/issues/2736)) ([6f93486](https://github.com/qqqqww1/vm0/commit/6f9348601ae5736e20a8c32a2064ac394a70e70b))
* **vsock:** add sudo flag to exec/spawn_watch protocol ([#2985](https://github.com/qqqqww1/vm0/issues/2985)) ([9c42331](https://github.com/qqqqww1/vm0/commit/9c423314a07f8de0f1b92ea3adca4efa4c6de987)), closes [#2984](https://github.com/qqqqww1/vm0/issues/2984)


### Bug Fixes

* **crates:** remove dead code and fix type inconsistency ([#2826](https://github.com/qqqqww1/vm0/issues/2826)) ([63b19d5](https://github.com/qqqqww1/vm0/commit/63b19d57ed29dfbf8c1b3c79a43bc1ebf6a94d96))
* **crates:** use system tls certificates instead of bundled webpki-roots ([#2824](https://github.com/qqqqww1/vm0/issues/2824)) ([aa95e93](https://github.com/qqqqww1/vm0/commit/aa95e9328dc99d77215d30e8545de11211a12792))
* **runner:** add exclusive lock on base_dir to prevent silent data corruption ([#3126](https://github.com/qqqqww1/vm0/issues/3126)) ([61ac8b7](https://github.com/qqqqww1/vm0/commit/61ac8b7e9121465d934f77c9dd8fb47acbc883ab)), closes [#3125](https://github.com/qqqqww1/vm0/issues/3125)
* **runner:** add flock to prevent concurrent rootfs/snapshot builds ([#2980](https://github.com/qqqqww1/vm0/issues/2980)) ([96a8559](https://github.com/qqqqww1/vm0/commit/96a8559f03ebebc0833af97d7bfe5c3c1562cb24))
* **runner:** add path validation and ci hash guards ([#3161](https://github.com/qqqqww1/vm0/issues/3161)) ([c5313ff](https://github.com/qqqqww1/vm0/commit/c5313ffdaee030c5fb3d48b950c8d7b6e36e90ae))
* **runner:** clean up request_start_times on flow error in mitm-addon ([#3076](https://github.com/qqqqww1/vm0/issues/3076)) ([a6e8cb1](https://github.com/qqqqww1/vm0/commit/a6e8cb1d9b9dece53f66aea35b8c32627bf4270e)), closes [#3073](https://github.com/qqqqww1/vm0/issues/3073)
* **runner:** deterministic active_run_ids order in status.json ([#3290](https://github.com/qqqqww1/vm0/issues/3290)) ([b87e8a2](https://github.com/qqqqww1/vm0/commit/b87e8a28d6bd1e8adf1d7ce9dfc133c2aa8f9893))
* **runner:** exclude network log upload from cleanup telemetry metric ([#3075](https://github.com/qqqqww1/vm0/issues/3075)) ([5b1beb1](https://github.com/qqqqww1/vm0/commit/5b1beb1a06cf19ebc67ba435a03ada529ef47f22)), closes [#3072](https://github.com/qqqqww1/vm0/issues/3072)
* **runner:** forward mock-claude env var to guest ([#3089](https://github.com/qqqqww1/vm0/issues/3089)) ([2978851](https://github.com/qqqqww1/vm0/commit/297885167fb36a2fcd1b3a5566a4c00bf4a571cb)), closes [#3088](https://github.com/qqqqww1/vm0/issues/3088)
* **runner:** gc removes unused lock files with safe inode recheck ([#3132](https://github.com/qqqqww1/vm0/issues/3132)) ([1e9d234](https://github.com/qqqqww1/vm0/commit/1e9d2345cb3209ade7b8f17f221f3621e9915172)), closes [#3131](https://github.com/qqqqww1/vm0/issues/3131)
* **runner:** prevent vm process leak on executor task panic ([#3079](https://github.com/qqqqww1/vm0/issues/3079)) ([6677bb5](https://github.com/qqqqww1/vm0/commit/6677bb55aa95096988c634879b23a775c9d63352)), closes [#3078](https://github.com/qqqqww1/vm0/issues/3078)
* **runner:** re-establish ably subscription after fatal error ([#3077](https://github.com/qqqqww1/vm0/issues/3077)) ([be681ca](https://github.com/qqqqww1/vm0/commit/be681cada26167aa8ebe1809edb326621902085b)), closes [#3074](https://github.com/qqqqww1/vm0/issues/3074)
* **runner:** sanitize runner name used in log file prefix ([#3103](https://github.com/qqqqww1/vm0/issues/3103)) ([b028b89](https://github.com/qqqqww1/vm0/commit/b028b89440019c077c0a0fc8cfced3178f74d797))
* **runner:** set node ca certs env var for mitm mode ([#3091](https://github.com/qqqqww1/vm0/issues/3091)) ([8626d58](https://github.com/qqqqww1/vm0/commit/8626d58b203a6fdbabea21aa21cb228ddc9cff78))
* **runner:** sort gc artifacts by last-used time instead of creation time ([#3130](https://github.com/qqqqww1/vm0/issues/3130)) ([42efcb2](https://github.com/qqqqww1/vm0/commit/42efcb29da6ef4d96fe6fb640953354f12bda516))
* **runner:** use run_id as sandbox_id instead of random uuid ([#3151](https://github.com/qqqqww1/vm0/issues/3151)) ([3e13c72](https://github.com/qqqqww1/vm0/commit/3e13c727b7a972c76b0f96c56e59ef2e65eca864))
* **runner:** walk ppid chain for orphan detection instead of checking immediate parent ([#3154](https://github.com/qqqqww1/vm0/issues/3154)) ([c377a54](https://github.com/qqqqww1/vm0/commit/c377a544643cd1908b32e505d533448ed73bc98c))
* **sandbox-fc:** move runtime sockets to /run/vm0 to fix sun_path limit ([#2951](https://github.com/qqqqww1/vm0/issues/2951)) ([#2966](https://github.com/qqqqww1/vm0/issues/2966)) ([4b91e0d](https://github.com/qqqqww1/vm0/commit/4b91e0d9ad2f677475afd768f95f19af852c9b46))
* **sandbox-fc:** remove double su wrapper from prewarm script ([#3265](https://github.com/qqqqww1/vm0/issues/3265)) ([3df62d1](https://github.com/qqqqww1/vm0/commit/3df62d1b9be9310e5112f3423edce504295f1775))
* **sandbox-fc:** use deterministic mac on tap devices for snapshot arp stability ([#3269](https://github.com/qqqqww1/vm0/issues/3269)) ([4c73c27](https://github.com/qqqqww1/vm0/commit/4c73c275ae6ae6bb3fbea6b5ee93ee5b0b761418)), closes [#3268](https://github.com/qqqqww1/vm0/issues/3268)


### Performance Improvements

* **rootfs:** install claude code as standalone binary for faster cold-start ([#3278](https://github.com/qqqqww1/vm0/issues/3278)) ([e8cbefa](https://github.com/qqqqww1/vm0/commit/e8cbefad6e5d3f6ea91d0eefd07baac743db8ab1))
* **runner:** prefetch snapshot memory.bin via sequential read ([#3373](https://github.com/qqqqww1/vm0/issues/3373)) ([21289eb](https://github.com/qqqqww1/vm0/commit/21289ebcff774e6c763a350dbb57be23f1ebeed8)), closes [#3342](https://github.com/qqqqww1/vm0/issues/3342)
* **sandbox-fc:** enable v8 compile cache for faster cli cold start ([#3267](https://github.com/qqqqww1/vm0/issues/3267)) ([6f1c8be](https://github.com/qqqqww1/vm0/commit/6f1c8be89cd5c7168326b5fa822d26eb2f9fa824))
* **sandbox-fc:** include prewarm script in snapshot hash computation ([#3004](https://github.com/qqqqww1/vm0/issues/3004)) ([3c27ac0](https://github.com/qqqqww1/vm0/commit/3c27ac0b4ffb8ab487fbea71cf62bf9681f31b0f)), closes [#3002](https://github.com/qqqqww1/vm0/issues/3002)
* **sandbox-fc:** pre-warm claude and codex in snapshot ([#3232](https://github.com/qqqqww1/vm0/issues/3232)) ([5534465](https://github.com/qqqqww1/vm0/commit/553446505f92aa30b1ac38b396f9238a6ff4c9ac))
* **sandbox-fc:** pre-warm real claude execution path instead of --help ([#3272](https://github.com/qqqqww1/vm0/issues/3272)) ([5d95121](https://github.com/qqqqww1/vm0/commit/5d95121b69e9ac5dbe76cb0859cc90b4b48a3743)), closes [#3258](https://github.com/qqqqww1/vm0/issues/3258)
* **sandbox-fc:** use full cli invocation for snapshot pre-warm ([#3395](https://github.com/qqqqww1/vm0/issues/3395)) ([318deaa](https://github.com/qqqqww1/vm0/commit/318deaa20216059e92c1702a10ef0203c98af00e))
</details>

<details><summary>sandbox: 0.7.0</summary>

## [0.7.0](https://github.com/qqqqww1/vm0/compare/sandbox-v0.6.0...sandbox-v0.7.0) (2026-03-02)


### Features

* **runner:** add mitmproxy integration to benchmark command ([#3027](https://github.com/qqqqww1/vm0/issues/3027)) ([7dab1cd](https://github.com/qqqqww1/vm0/commit/7dab1cd38f8c4e58fbdca98890b5a3b21bf53e9e))
* **runner:** add snapshot subcommand with content-addressable caching ([#2903](https://github.com/qqqqww1/vm0/issues/2903)) ([c00ab8d](https://github.com/qqqqww1/vm0/commit/c00ab8d387bcdca0917ed1efd13a870c032adf44))
* **runner:** implement rust runner crate for job polling and execution ([#2722](https://github.com/qqqqww1/vm0/issues/2722)) ([38b494e](https://github.com/qqqqww1/vm0/commit/38b494e563f0c87486419a36df265fe5c0d8c032))
* **sandbox-fc:** per-sandbox proxy control with dual-queue netns pool ([#3035](https://github.com/qqqqww1/vm0/issues/3035)) ([deda648](https://github.com/qqqqww1/vm0/commit/deda64875625f49f4a72513d2b286dba12be0986)), closes [#3033](https://github.com/qqqqww1/vm0/issues/3033)
* **vsock:** add environment variable support to exec/spawn_watch ([#2736](https://github.com/qqqqww1/vm0/issues/2736)) ([6f93486](https://github.com/qqqqww1/vm0/commit/6f9348601ae5736e20a8c32a2064ac394a70e70b))
* **vsock:** add sudo flag to exec/spawn_watch protocol ([#2985](https://github.com/qqqqww1/vm0/issues/2985)) ([9c42331](https://github.com/qqqqww1/vm0/commit/9c423314a07f8de0f1b92ea3adca4efa4c6de987)), closes [#2984](https://github.com/qqqqww1/vm0/issues/2984)


### Bug Fixes

* **crates:** remove dead code and fix type inconsistency ([#2826](https://github.com/qqqqww1/vm0/issues/2826)) ([63b19d5](https://github.com/qqqqww1/vm0/commit/63b19d57ed29dfbf8c1b3c79a43bc1ebf6a94d96))
</details>

<details><summary>sandbox-fc: 0.7.0</summary>

## [0.7.0](https://github.com/qqqqww1/vm0/compare/sandbox-fc-v0.6.7...sandbox-fc-v0.7.0) (2026-03-02)


### Features

* **runner:** add mitmproxy integration to benchmark command ([#3027](https://github.com/qqqqww1/vm0/issues/3027)) ([7dab1cd](https://github.com/qqqqww1/vm0/commit/7dab1cd38f8c4e58fbdca98890b5a3b21bf53e9e))
* **runner:** add runner.yaml config file generated by build ([#2935](https://github.com/qqqqww1/vm0/issues/2935)) ([9b9577a](https://github.com/qqqqww1/vm0/commit/9b9577a3197b72f64866ff12769fa919c252a347))
* **runner:** add snapshot subcommand with content-addressable caching ([#2903](https://github.com/qqqqww1/vm0/issues/2903)) ([c00ab8d](https://github.com/qqqqww1/vm0/commit/c00ab8d387bcdca0917ed1efd13a870c032adf44))
* **runner:** implement rust runner crate for job polling and execution ([#2722](https://github.com/qqqqww1/vm0/issues/2722)) ([38b494e](https://github.com/qqqqww1/vm0/commit/38b494e563f0c87486419a36df265fe5c0d8c032))
* **sandbox-fc:** auto-allocate netns pool index via flock ([#2708](https://github.com/qqqqww1/vm0/issues/2708)) ([828ed61](https://github.com/qqqqww1/vm0/commit/828ed619217245d4a87a1afa27290ba175232143)), closes [#2704](https://github.com/qqqqww1/vm0/issues/2704)
* **sandbox-fc:** implement snapshot creation workflow ([#2668](https://github.com/qqqqww1/vm0/issues/2668)) ([02d4418](https://github.com/qqqqww1/vm0/commit/02d441840260d6257e9e52cca72330cb1568fb41))
* **sandbox-fc:** per-sandbox proxy control with dual-queue netns pool ([#3035](https://github.com/qqqqww1/vm0/issues/3035)) ([deda648](https://github.com/qqqqww1/vm0/commit/deda64875625f49f4a72513d2b286dba12be0986)), closes [#3033](https://github.com/qqqqww1/vm0/issues/3033)
* **sandbox-fc:** proactive crash notification for firecracker sandbox ([#3087](https://github.com/qqqqww1/vm0/issues/3087)) ([ff6a795](https://github.com/qqqqww1/vm0/commit/ff6a795b77c42f389fc2b998dda9e262b1049c46))
* **vsock:** add environment variable support to exec/spawn_watch ([#2736](https://github.com/qqqqww1/vm0/issues/2736)) ([6f93486](https://github.com/qqqqww1/vm0/commit/6f9348601ae5736e20a8c32a2064ac394a70e70b))
* **vsock:** add sudo flag to exec/spawn_watch protocol ([#2985](https://github.com/qqqqww1/vm0/issues/2985)) ([9c42331](https://github.com/qqqqww1/vm0/commit/9c423314a07f8de0f1b92ea3adca4efa4c6de987)), closes [#2984](https://github.com/qqqqww1/vm0/issues/2984)


### Bug Fixes

* **crates:** remove dead code and fix type inconsistency ([#2826](https://github.com/qqqqww1/vm0/issues/2826)) ([63b19d5](https://github.com/qqqqww1/vm0/commit/63b19d57ed29dfbf8c1b3c79a43bc1ebf6a94d96))
* **runner:** add flock to prevent concurrent rootfs/snapshot builds ([#2980](https://github.com/qqqqww1/vm0/issues/2980)) ([96a8559](https://github.com/qqqqww1/vm0/commit/96a8559f03ebebc0833af97d7bfe5c3c1562cb24))
* **runner:** prevent vm process leak on executor task panic ([#3079](https://github.com/qqqqww1/vm0/issues/3079)) ([6677bb5](https://github.com/qqqqww1/vm0/commit/6677bb55aa95096988c634879b23a775c9d63352)), closes [#3078](https://github.com/qqqqww1/vm0/issues/3078)
* **sandbox-fc:** add prerequisite checks to create_snapshot ([#2971](https://github.com/qqqqww1/vm0/issues/2971)) ([f508fa2](https://github.com/qqqqww1/vm0/commit/f508fa2cfc6a70900670377f029b041b53ac8cdd))
* **sandbox-fc:** move runtime sockets to /run/vm0 to fix sun_path limit ([#2951](https://github.com/qqqqww1/vm0/issues/2951)) ([#2966](https://github.com/qqqqww1/vm0/issues/2966)) ([4b91e0d](https://github.com/qqqqww1/vm0/commit/4b91e0d9ad2f677475afd768f95f19af852c9b46))
* **sandbox-fc:** redesign api error as enum to distinguish fatal from retryable errors ([#2700](https://github.com/qqqqww1/vm0/issues/2700)) ([dae4042](https://github.com/qqqqww1/vm0/commit/dae40421ec934018cfef485d73dabc5cdac33672))
* **sandbox-fc:** reject sudo invocation and clean stale work dir on snapshot ([#2698](https://github.com/qqqqww1/vm0/issues/2698)) ([f298633](https://github.com/qqqqww1/vm0/commit/f2986332cdc212167e5dd4323039ddaf554859e4)), closes [#2696](https://github.com/qqqqww1/vm0/issues/2696)
* **sandbox-fc:** remove double su wrapper from prewarm script ([#3265](https://github.com/qqqqww1/vm0/issues/3265)) ([3df62d1](https://github.com/qqqqww1/vm0/commit/3df62d1b9be9310e5112f3423edce504295f1775))
* **sandbox-fc:** use deterministic mac on tap devices for snapshot arp stability ([#3269](https://github.com/qqqqww1/vm0/issues/3269)) ([4c73c27](https://github.com/qqqqww1/vm0/commit/4c73c275ae6ae6bb3fbea6b5ee93ee5b0b761418)), closes [#3268](https://github.com/qqqqww1/vm0/issues/3268)


### Performance Improvements

* **runner:** prefetch snapshot memory.bin via sequential read ([#3373](https://github.com/qqqqww1/vm0/issues/3373)) ([21289eb](https://github.com/qqqqww1/vm0/commit/21289ebcff774e6c763a350dbb57be23f1ebeed8)), closes [#3342](https://github.com/qqqqww1/vm0/issues/3342)
* **sandbox-fc:** enable v8 compile cache for faster cli cold start ([#3267](https://github.com/qqqqww1/vm0/issues/3267)) ([6f1c8be](https://github.com/qqqqww1/vm0/commit/6f1c8be89cd5c7168326b5fa822d26eb2f9fa824))
* **sandbox-fc:** include prewarm script in snapshot hash computation ([#3004](https://github.com/qqqqww1/vm0/issues/3004)) ([3c27ac0](https://github.com/qqqqww1/vm0/commit/3c27ac0b4ffb8ab487fbea71cf62bf9681f31b0f)), closes [#3002](https://github.com/qqqqww1/vm0/issues/3002)
* **sandbox-fc:** pre-warm claude and codex in snapshot ([#3232](https://github.com/qqqqww1/vm0/issues/3232)) ([5534465](https://github.com/qqqqww1/vm0/commit/553446505f92aa30b1ac38b396f9238a6ff4c9ac))
* **sandbox-fc:** pre-warm pam cache during snapshot creation ([#3000](https://github.com/qqqqww1/vm0/issues/3000)) ([8b95fcd](https://github.com/qqqqww1/vm0/commit/8b95fcdb9e33b1ea89b68d4ff6eef210f74cf91c)), closes [#2994](https://github.com/qqqqww1/vm0/issues/2994)
* **sandbox-fc:** pre-warm real claude execution path instead of --help ([#3272](https://github.com/qqqqww1/vm0/issues/3272)) ([5d95121](https://github.com/qqqqww1/vm0/commit/5d95121b69e9ac5dbe76cb0859cc90b4b48a3743)), closes [#3258](https://github.com/qqqqww1/vm0/issues/3258)
* **sandbox-fc:** prefetch snapshot memory.bin on factory startup ([#3370](https://github.com/qqqqww1/vm0/issues/3370)) ([891041e](https://github.com/qqqqww1/vm0/commit/891041ee8cae18ddbd83864fb80e2c3e6f3dab2d))
* **sandbox-fc:** use full cli invocation for snapshot pre-warm ([#3395](https://github.com/qqqqww1/vm0/issues/3395)) ([318deaa](https://github.com/qqqqww1/vm0/commit/318deaa20216059e92c1702a10ef0203c98af00e))
</details>

<details><summary>vsock-guest: 0.7.0</summary>

## [0.7.0](https://github.com/qqqqww1/vm0/compare/vsock-guest-v0.6.0...vsock-guest-v0.7.0) (2026-03-02)


### Features

* **vsock:** add environment variable support to exec/spawn_watch ([#2736](https://github.com/qqqqww1/vm0/issues/2736)) ([6f93486](https://github.com/qqqqww1/vm0/commit/6f9348601ae5736e20a8c32a2064ac394a70e70b))
* **vsock:** add sudo flag to exec/spawn_watch protocol ([#2985](https://github.com/qqqqww1/vm0/issues/2985)) ([9c42331](https://github.com/qqqqww1/vm0/commit/9c423314a07f8de0f1b92ea3adca4efa4c6de987)), closes [#2984](https://github.com/qqqqww1/vm0/issues/2984)


### Bug Fixes

* **vsock-guest:** handle echild race with pid 1 zombie reaper ([#3118](https://github.com/qqqqww1/vm0/issues/3118)) ([985f349](https://github.com/qqqqww1/vm0/commit/985f349134b981d6123fe26ee79f991ec56ceb59))
</details>

<details><summary>vsock-host: 0.7.0</summary>

## [0.7.0](https://github.com/qqqqww1/vm0/compare/vsock-host-v0.6.0...vsock-host-v0.7.0) (2026-03-02)


### Features

* **vsock:** add environment variable support to exec/spawn_watch ([#2736](https://github.com/qqqqww1/vm0/issues/2736)) ([6f93486](https://github.com/qqqqww1/vm0/commit/6f9348601ae5736e20a8c32a2064ac394a70e70b))
* **vsock:** add sudo flag to exec/spawn_watch protocol ([#2985](https://github.com/qqqqww1/vm0/issues/2985)) ([9c42331](https://github.com/qqqqww1/vm0/commit/9c423314a07f8de0f1b92ea3adca4efa4c6de987)), closes [#2984](https://github.com/qqqqww1/vm0/issues/2984)
</details>

<details><summary>vsock-proto: 0.7.0</summary>

## [0.7.0](https://github.com/qqqqww1/vm0/compare/vsock-proto-v0.6.0...vsock-proto-v0.7.0) (2026-03-02)


### Features

* **vsock:** add environment variable support to exec/spawn_watch ([#2736](https://github.com/qqqqww1/vm0/issues/2736)) ([6f93486](https://github.com/qqqqww1/vm0/commit/6f9348601ae5736e20a8c32a2064ac394a70e70b))
* **vsock:** add sudo flag to exec/spawn_watch protocol ([#2985](https://github.com/qqqqww1/vm0/issues/2985)) ([9c42331](https://github.com/qqqqww1/vm0/commit/9c423314a07f8de0f1b92ea3adca4efa4c6de987)), closes [#2984](https://github.com/qqqqww1/vm0/issues/2984)
</details>

<details><summary>vsock-test: 0.7.0</summary>

## [0.7.0](https://github.com/qqqqww1/vm0/compare/vsock-test-v0.6.0...vsock-test-v0.7.0) (2026-03-02)


### Features

* **vsock:** add environment variable support to exec/spawn_watch ([#2736](https://github.com/qqqqww1/vm0/issues/2736)) ([6f93486](https://github.com/qqqqww1/vm0/commit/6f9348601ae5736e20a8c32a2064ac394a70e70b))
* **vsock:** add sudo flag to exec/spawn_watch protocol ([#2985](https://github.com/qqqqww1/vm0/issues/2985)) ([9c42331](https://github.com/qqqqww1/vm0/commit/9c423314a07f8de0f1b92ea3adca4efa4c6de987)), closes [#2984](https://github.com/qqqqww1/vm0/issues/2984)
</details>

---
This PR was generated with [Release Please](https://github.com/googleapis/release-please). See [documentation](https://github.com/googleapis/release-please#release-please).