# Changelog

All notable changes to **Pipecat Websocket Transport** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.9.0](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/compare/websocket-transport-v1.8.2...websocket-transport-v1.9.0) (2026-11-19)


### Features

* report media support from each transport ([33dff50](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/33dff50eff8231ecd708e90a10a38104b25b5e0e))
* support optional auth token in connection params ([c9504c8](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/c9504c8b28f01a990a8a116ec26d62322f6c9b9c))
* support optional auth token in connection params ([2977621](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/2977621395afc97e402e7ef1067e21f432d127bc))
* **websocket-transport:** add mediaSupport ([0b5fe6c](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/0b5fe6c0c5e4866a71dc491fbead54938b51a863))


### Bug Fixes

* add exports map for proper ESM/CJS resolution ([bd53457](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/bd53457d82df32117d2bba09261e1763593c6a42))
* log a warning instead of an error for unsupported features ([3cae2f2](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/3cae2f2e241ed3518b0915cf19adf7f050aeb0aa))
* **small-webrtc,websocket:** Fix bot disconnection logic to match Daily ([c6accf2](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/c6accf2a9ad62b3fc1fb8594269354f95a9dc0af))
* **small-webrtc,websocket:** Fix bot disconnection logic to match Daily ([4a231dc](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/4a231dc825ae60eeeb501088bdaea136e2ad22d7))
* **transports:** log unrecognized connection params at info level ([2f4a53c](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/2f4a53cd75656b7bb6e636bdd7c6d8b28ae8d0a8))
* **websocket-transport:** accept a start endpoint's response as connect params ([8dbc1e2](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/8dbc1e2594b84050fb8c23f495746644c67e872f))
* **websocket-transport:** build connect url per connect so the token does not accumulate ([2e9a012](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/2e9a0128220454f5bd5cea405c6dd652db60b7d2))
* **websocket-transport:** build the connect url per connect so the token does not accumulate ([0b77e6f](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/0b77e6fe7624dfc4c916a2ce7ab670a67968239f))
* **websocket-transport:** Fix missing transport option exports for websocket-transport ([0e9b366](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/0e9b3661821ab153b4828dd3f7c917d4a2fd3485))
* **websocket-transport:** Update protobuf to match latest pipecat and handle interruption frames ([33de4c5](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/33de4c5a138945c8177a820bbc7f1ff5a8e6820a))


### Miscellaneous Chores

* bump @pipecat-ai/client-js dependencies to 1.14.0 ([a58f148](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/a58f148120c748390b5ba1303ff4e49dcbd93703))
* Bump client-js dependencies to lastest 1.8.0 ([72c2026](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/72c20269539367048c923b6afa3e9e5bad41f933))
* Bump client-js dependency for all transports to 1.10.0 ([5c4568e](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/5c4568e3d5a049118c2983e275805848aacac823))
* Bump client-js dependency for all transports to 1.10.0 ([7cfe831](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/7cfe83100d4e9f2f598db5013833444fccd5257e))
* Bump client-js dependency for all transports to 1.11.0 ([67ccb57](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/67ccb57ea8f5f8b7e7424788e2c3cafa863ff08f))
* Bump client-js dependency for all transports to 1.11.0 ([8a38dab](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/8a38dab477191d4ce2bc31e9f4f40b49da921771))
* Bump client-js dependency for all transports to 1.12.0 ([781e0dd](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/781e0dd9621f16a00a87308b02174d941400a624))
* Bump client-js dependency for all transports to 1.12.0 ([ef7a2c3](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/ef7a2c30f3082d5433e8b0c0423e732a13e5a95f))
* Bump client-js dependency in transports to 1.13.0 and fix changelogs ([0dba28c](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/0dba28c4b3fcedd8851e43ad7935b537679efe1b))
* bump client-js dependency to 1.15 and resolve vulnerabilities ([9265a43](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/9265a43e71be431d9c765eb91e313ec02c0fa17c))
* Bump client-js dependency to latest 1.9.0 and clean up changelogs ([175795b](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/175795bd22a660b2f66152864e66cec112b6ecae))
* Bump client-js dependency to latest 1.9.0 and clean up changelogs ([fe9347f](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/fe9347f73493d2b64a1304a9c6f80ce84fa721a3))
* bump client-js dependency to version 1.16.0 ([9085f2a](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/9085f2a0e58151fce984a9300fd5dd2cde393493))
* Bump daily-js dependencies to 0.94.0 ([eff5bf5](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/eff5bf5c3f6bdf977907c09c50da3a884c96b6d7))
* bump daily-js to latest 0.90.0 ([5f05e59](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/5f05e599ae5f3a1d2c1403c662ad4f81914bed41))
* curate release notes ([4ff21d6](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/4ff21d68d28c45eb5ba6c034a239d083cbb64bc6))
* curate release notes ([291c874](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/291c87405631a9adb265e4284c23e0f562376b1d))
* curate release notes ([0523b45](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/0523b45c189831ebca4ff104e705d049cbbf44e5))
* **daily,gemini,openai,small-webrtc,websocket:** Bump client-js dep… ([9180f89](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/9180f890bb01c1e8c2f74a9abe7fc8e0777a86c3))
* **daily,gemini,openai,small-webrtc,websocket:** Bump client-js dependency to latest 1.7.0 ([8825761](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/882576168ed38e4eb01d03211363c7cafed72967))
* **main:** release  websocket-transport 1.6.3 ([9ea804f](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/9ea804f420adbf472064ea015dc1f884a4a2af7f))
* **main:** release  websocket-transport 1.6.3 ([7db629c](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/7db629c1eb3e7fa8cd9a03728f1856e1c680ce28))
* **main:** release  websocket-transport 1.6.4 ([0de08fb](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/0de08fba7e9af9a298a6e34ce86112bd0d4c9d96))
* **main:** release  websocket-transport 1.6.5 ([110c915](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/110c915828bec99af0dea85fce10047c0d41b412))
* **main:** release  websocket-transport 1.6.5 ([302483a](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/302483a29e11806612436fbba5b7507c258cdabd))
* **main:** release  websocket-transport 1.6.6 ([f873291](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/f873291d7da100f9858069a5c9fa59722e62f698))
* **main:** release  websocket-transport 1.6.6 ([baf59c8](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/baf59c8f63d0b957c27e5d0cd2d006722c6a3820))
* **main:** release  websocket-transport 1.6.7 ([81d3553](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/81d35537a9796d470405cac35d665d51cd1a9ea3))
* **main:** release  websocket-transport 1.6.7 ([35c4fbe](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/35c4fbef4549c44b7ae5a32ab939c066c300f7de))
* **main:** release  websocket-transport 1.7.0 ([a076c45](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/a076c4508b49934c3a99de14ad1f451351c83f9e))
* **main:** release  websocket-transport 1.7.0 ([adbc976](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/adbc976c09ecb0457ab719168d51611e51bf3b35))
* **main:** release  websocket-transport 1.7.1 ([f8053f1](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/f8053f1bd7d214b90ff389fc9ed1d6513f3529b7))
* **main:** release  websocket-transport 1.7.1 ([129749a](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/129749a7c0a61d671b374211a9d543724ffcb4e5))
* **main:** release  websocket-transport 1.7.2 ([bfc84d3](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/bfc84d3280ac72c93a7fbde07071160dce3cc273))
* **main:** release  websocket-transport 1.7.2 ([b1cd648](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/b1cd6483a555f7d56144f0f5bdfb64d565394442))
* **main:** release  websocket-transport 1.7.2 ([13e9412](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/13e9412e0e97a4b9f2afe23bb35ad3158c6f2e7b))
* **main:** release  websocket-transport 1.8.0 ([8ff1b76](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/8ff1b763b731a9aee2c1440740f4435c009b7813))
* **main:** release  websocket-transport 1.8.1 ([c34afc5](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/c34afc53033aa8eabad31f698fa1c237380ee68d))
* **main:** release  websocket-transport 1.8.2 ([68c8d47](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/68c8d47720c585f0a3abf6d4e8be2a1f2ca93a5b))
* **main:** release websocket-transport 1.6.1 ([f3b2804](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/f3b2804520638c953a0f9793b5a5f0da6eedd3b4))
* **main:** release websocket-transport 1.6.1 ([e6e61ed](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/e6e61ed8ba659902207a6021aa2ffd1e2f7388c7))
* release  websocket-transport 1.6.2 ([ab4bcff](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/ab4bcffe90c058d138ef557b34ca948a2350e84a))
* release  websocket-transport 1.6.2 ([acf57ee](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/acf57ee136ec860585d4e687df0cc012c88460c2))
* update transport-lib dependencies to 0.2.0 ([730e0e4](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/730e0e4ca2a2abc9f1c1a5b9b88eff4495e19c5a))
* **websocket:** release  websocket-transport 1.6.4 ([9a1103a](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/9a1103afc5d8e9a9d48b39eef80eabc60fe68675))


### Dependencies

* The following workspace dependencies were updated
  * devDependencies
    * @pipecat-ai/transport-lib bumped from ^0.2.0 to ^0.3.0

## [1.8.2](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/websocket-transport-v1.8.1...websocket-transport-v1.8.2) (2026-10-29)

### Other

* `@pipecat-ai/websocket-transport` now requires `@pipecat-ai/client-js` `~1.16.0` as a peer dependency. Upgrade `@pipecat-ai/client-js` to 1.16.x alongside this release. ([c5465cd](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/c5465cddb143693cc1cac445b47c64e13af59ca4))

## [1.8.1](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/websocket-transport-v1.8.0...websocket-transport-v1.8.1) (2026-10-25)

### Changed

* `@pipecat-ai/websocket-transport` now requires `@pipecat-ai/client-js` `~1.15.0` as a peer dependency. Upgrade `@pipecat-ai/client-js` to 1.15.x alongside this release. ([d2a5122](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/d2a51222639c6013e1202d74a6abea17204b41df))

## [1.8.0](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/websocket-transport-v1.7.2...websocket-transport-v1.8.0) (2026-10-16)

### Features

* `WebSocketTransport` now implements the `mediaSupport` getter, reporting that it carries audio only: the camera, screen share, and bot video are always reported as unsupported, the bot's audio is supported, and the microphone follows what the media manager reports. Requires `@pipecat-ai/client-js` 1.14.0 or later. ([0b5fe6c](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/0b5fe6c0c5e4866a71dc491fbead54938b51a863))

### Bug Fixes

* Fixed `WebSocketTransport` piling up tokens on its stored URL across connects. Connecting again with a new `token` and no new `wsUrl` used to open a URL like `wss://host/ws?token=old&token=new`, so most servers read the stale token. The token is now added to the base URL on each connect, which gives `wss://host/ws?token=new`. As a result, a connect without a `token` no longer reuses one from an earlier connect. `initializeWebsocket()` now takes an optional `url` argument that defaults to the stored base URL. ([2e9a012](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/2e9a0128220454f5bd5cea405c6dd652db60b7d2))
* Fixed `WebSocketTransport` throwing a `TypeError` when a `token` was passed without any URL. It now throws `TransportStartError` and sets the transport state to `"error"`, which is what already happened when neither a URL nor a token was given. ([2e9a012](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/2e9a0128220454f5bd5cea405c6dd652db60b7d2))
* `@pipecat-ai/websocket-transport` now exports the `WebSocketTransportOptions` and `WebSocketTransportConstructorOptions` types, so you can type the options passed to the `WebSocketTransport` constructor. ([cddd96f](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/cddd96fadbbf06d73d89378f42891aba66460a10))
* `@pipecat-ai/websocket-transport` now exports the `WebSocketSerializer` interface and the `DeserializedData` type, so you can implement a custom serializer and pass it via the `serializer` option. ([cddd96f](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/cddd96fadbbf06d73d89378f42891aba66460a10))
* `ProtobufFrameSerializer` now understands the `InterruptionFrame` sent by recent Pipecat servers. Previously these frames caused `Unknown frame kind` deserialization errors. When one arrives, `WebSocketTransport` now stops bot playback and flushes buffered bot audio right away. ([214d7ab](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/214d7abf9db1f655b342b0820a7fc22b0356f575))
* `ProtobufFrameSerializer` now logs a warning and ignores frame kinds it doesn't recognize, instead of throwing. ([214d7ab](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/214d7abf9db1f655b342b0820a7fc22b0356f575))
* `TwilioSerializer` now treats Twilio's `clear` event as an interruption, so `WebSocketTransport` flushes buffered bot audio when it's received. Previously the event was ignored. ([214d7ab](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/214d7abf9db1f655b342b0820a7fc22b0356f575))

### Other

* Bumped the `@pipecat-ai/client-js` peer dependency to `~1.14.0`. Projects using `@pipecat-ai/websocket-transport` should upgrade `@pipecat-ai/client-js` to 1.14.x. ([6f1bf1a](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/6f1bf1a37e7077e54e27a92b810c1e146be781fe))
* `@pipecat-ai/websocket-transport` now depends on `@daily-co/daily-js` `^0.94.0` (previously `^0.90.0`), which its `DailyMediaManager`-based media handling uses. ([1ffa4f8](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/1ffa4f87edd988bf289768877c16c6d4dd37567d))

### Miscellaneous Chores

* update transport-lib dependencies to 0.2.0 ([730e0e4](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/730e0e4ca2a2abc9f1c1a5b9b88eff4495e19c5a))

## [1.7.2](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/websocket-transport-v1.7.1...websocket-transport-v1.7.2) (2026-09-15)


### Bug Fixes

* Fixed issue with mute toggle states being delayed ([51954df](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/51954df18f7f1f23b6965e863ac0425493f9be4d))

## [1.7.1](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/websocket-transport-v1.7.0...websocket-transport-v1.7.1) (2026-07-16)


### Miscellaneous Chores

* Bump client-js dependency for all transports to 1.13.0

## [1.7.0](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/websocket-transport-v1.6.7...websocket-transport-v1.7.0) (2026-06-19)


### Features

* support optional auth token in connection params ([2977621](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/2977621395afc97e402e7ef1067e21f432d127bc))


### Miscellaneous Chores

* Bump client-js dependency for all transports to 1.12.0 ([ef7a2c3](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/ef7a2c30f3082d5433e8b0c0423e732a13e5a95f))

## [1.6.7](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/websocket-transport-v1.6.6...websocket-transport-v1.6.7) (2026-06-03)


### Miscellaneous Chores

* Bump client-js dependency for all transports to 1.11.0 ([8a38dab](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/8a38dab477191d4ce2bc31e9f4f40b49da921771))

## [1.6.6](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/websocket-transport-v1.6.5...websocket-transport-v1.6.6) (2026-06-02)


### Bug Fixes

* log a warning instead of an error for unsupported features ([3cae2f2](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/3cae2f2e241ed3518b0915cf19adf7f050aeb0aa))

## [1.6.5](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/websocket-transport-v1.6.4...websocket-transport-v1.6.5) (2026-05-27)


### Miscellaneous Chores

* Bump client-js dependency for all transports to 1.10.0 ([7cfe831](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/7cfe83100d4e9f2f598db5013833444fccd5257e))

## [1.6.4](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/websocket-transport-v1.6.3...websocket-transport-v1.6.4) (2026-05-15)


### Miscellaneous Chores

* Bump client-js dependency to latest 1.9.0 and clean up changelogs ([fe9347f](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/fe9347f73493d2b64a1304a9c6f80ce84fa721a3))
* Bump daily-js to latest 0.90.0 ([5f05e59](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/5f05e599ae5f3a1d2c1403c662ad4f81914bed41))

## [1.6.3](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/websocket-transport-v1.6.2...websocket-transport-v1.6.3) (2026-05-08)


### Miscellaneous Chores

* Bump client-js dependencies to lastest 1.8.0 ([72c2026](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/72c20269539367048c923b6afa3e9e5bad41f933))

## [1.6.2](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/websocket-transport-v1.6.1...websocket-transport-v1.6.2) (2026-03-24)

### Changed

- Bump daily-js version dependency to 0.89.1
- Bump client-js version to work with latest 1.7.0 and support latest features

### Bug Fixes

- Fix bot disconnection logic to match Daily ([c6accf2](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/c6accf2a9ad62b3fc1fb8594269354f95a9dc0af))


## [1.6.1](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/websocket-transport-v1.6.0...websocket-transport-v1.6.1) (2026-03-11)

### Bug Fixes

- add exports map for proper ESM/CJS resolution ([bd53457](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/bd53457d82df32117d2bba09261e1763593c6a42))
- Set `_maxMessageSize` to the server's supported max size (1 MB)


## [1.6.0]

- Bump client-js version to work with latest 1.6.0 and support latest features

## [1.5.0]

- Bump client-js version to work with latest 1.5.0 and support latest features
- Bump daily-js version dependency to 0.84.0

## [1.4.0]

- Enable useDevicePreferenceCookies to store preferred devices by default
- Bump client-js version to work with latest 1.4.0 and support latest features

## [1.3.0]

- Bump client-js version to work with latest 1.3.0 and support latest features

## [1.2.1]

- Bump daily-js version dependency to 0.83.1 to get Chrome 140 fix

## [1.2.0]

- Deprecated the transport option `ws_url` in lieu of a properly camelCased `wsUrl` for consistency. `ws_url` is still accepted from endpoints.
- Fixed connection type to not allow anything but `wsUrl` as providing other options are no-ops.

## [1.1.0]

- Add support for generating `onDeviceError` callbacks/events when receiving a camera or speaker error.

## [1.0.0]

- PipecatClient and Transport 1.0.0 Updates:
  See [the migration guide](https://docs.pipecat.ai/client/js/migration-guide) for details
  - Updated WebsocketTransport to PipecatClient 1.0.0 changes, which include:
    - Updating naming/dependencies from RTVIClient -> PipecatClient
    - Modified connect() to follow the new pattern of providing connection details at the time of connection vs. constructor
    - Added validation for connection parameters
