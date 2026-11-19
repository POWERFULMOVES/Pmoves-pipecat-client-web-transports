# Changelog

All notable changes to **Pipecat MoqTransport** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.4.0](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/compare/moq-transport-v0.3.4...moq-transport-v0.4.0) (2026-11-19)


### Features

* add moq docs ([99ac7f0](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/99ac7f09a55c246febf8871af28eb582066eafc4))
* add moq transport support ([b678463](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/b678463f7a4332060e21379c5f60962e10ce4c43))
* improving the MoQ transport README ([659f4a5](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/659f4a562d0190c7efdf31f964f51d6dd83c0484))
* improving the MoQ transport README ([5501d99](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/5501d99cd1860bbf465660bba33744913eaf174c))
* moq refactor- use libs ([7c9dd26](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/7c9dd26197c62f67ab8dfab6fb7469a9575fff3b))
* **moq-transport:** add mediaSupport ([4fd131a](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/4fd131a658b1ffc2acedbe8cbc1504347f9e0c0c))
* **moq-transport:** number transcript records and drop replays on resubscribe ([91476a3](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/91476a36324c357928affcac84fa3091125bdab5))
* **moq-transport:** number transcript records and drop replays on resubscribe ([633cf2c](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/633cf2c80987033ef2535f4e97c0f567afa8372b))
* **moq-transport:** send session-ending on disconnect and redial when the bot's tracks end without it ([f2ff607](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/f2ff6077a3cf27ca611925a45d8fc18e573e0c4a))
* **moq:** add client→bot RTVI message channel ([1a338ff](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/1a338ff41dd673773b3f50968a70c1b929ff18c8))
* **moq:** carry the RTVI transcript on a lossless compressed JSON stream ([a272282](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/a27228287e4a0bd3a80c840380b31bed79efedb3))
* **moq:** carry the RTVI transcript on a lossless compressed JSON stream ([79f8cb3](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/79f8cb3e8873b4014c3863aa4f23f81a903a5eef))
* **moq:** play bot audio via @moq/watch buffered playback ([e7b95da](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/e7b95dac3669f217a6f54dc69d10659f567f9bcb))
* report media support from each transport ([33dff50](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/33dff50eff8231ecd708e90a10a38104b25b5e0e))


### Bug Fixes

* add _wasReady flag to handle moq-relay reconnects ([ba308e1](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/ba308e1424114142abf8130db22dd527f54407c2))
* moq transport ([61c4d97](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/61c4d97e9a062ee9cb2f6e6e6160243ad80124cd))
* **moq-transport:** hold client-ready until the bot audio subscription is live ([dc56c47](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/dc56c4700950ec55697705f3fb9f3f86f314eeb8))
* **moq-transport:** hold client-ready until the bot audio subscription is live ([795b91a](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/795b91a2cea0f7cc12849e869e88fc5ea8a1f5d7))
* **moq-transport:** hold ready through relay reconnects ([f25ebc1](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/f25ebc159bd887e6023bff43d1ff0705243f5458))
* **moq-transport:** keep the kept retry window honest across page suspension ([d7a16c9](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/d7a16c9db9abb53d3a91f94759fc21e3ff8058d8))
* **moq-transport:** keep trying to reach the relay for 60 seconds ([43b6060](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/43b6060b051510000e73ea26bd7d8ffade96d568))
* **moq-transport:** keep trying to reach the relay for 60 seconds ([a5207c6](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/a5207c683098c303a862fcea33296a1141c86c90))
* **moq-transport:** redial a relay attempt that gets no answer ([c21561d](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/c21561d3e1b95ac4fc56e3c86506a5264c8a2b17))
* wait for the bot's broadcast before subscribing to the transcript ([9ff8594](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/9ff8594ae6596f591d1f2507634b85acc108b84b))


### Miscellaneous Chores

* bump @pipecat-ai/client-js dependencies to 1.14.0 ([a58f148](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/a58f148120c748390b5ba1303ff4e49dcbd93703))
* bump client-js dependency to 1.15 and resolve vulnerabilities ([9265a43](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/9265a43e71be431d9c765eb91e313ec02c0fa17c))
* bump client-js dependency to version 1.16.0 ([9085f2a](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/9085f2a0e58151fce984a9300fd5dd2cde393493))
* curate release notes ([aba59dd](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/aba59dd8a638306a47b82ff82d9d3030d4c5afcb))
* curate release notes ([ceb8914](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/ceb8914f328abfe5867f300dbcce3a282965d992))
* curate release notes ([d4953e8](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/d4953e8ddfb779c10b10467d5c6ba0059025c95c))
* curate release notes ([b757bf3](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/b757bf3f6b43df1ae60e5f32d1f94b9d10cdbaa5))
* curate release notes ([795323a](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/795323a7ddf8cb4cddbd4cc032aa1432acc35c1d))
* **deps:** bump moq-transport libs patch versions ([f54a98c](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/f54a98c8d2c517c8bffb783d4cc2f714d273db0e))
* **main:** release  moq-transport 0.1.0 ([9917590](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/9917590d4149ba26e1ea7597e6c03e1fd4243751))
* **main:** release  moq-transport 0.1.0 ([2c5c109](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/2c5c109a96ef28315f233617d0a194f2dd673d17))
* **main:** release  moq-transport 0.1.1 ([a7cf5d4](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/a7cf5d4b129dfc6b1af0b8fb2dd32270e0bbe06c))
* **main:** release  moq-transport 0.1.1 ([01cd192](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/01cd192e51e1f5a126c5df679e3f548ba4738534))
* **main:** release  moq-transport 0.2.0 ([fd6e771](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/fd6e771a0c0004c961a78c50d8cc53d91f449fc4))
* **main:** release  moq-transport 0.2.0 ([328be86](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/328be86f2a1d950e47e113cffa8477ce8d7810e5))
* **main:** release  moq-transport 0.2.1 ([fc9389b](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/fc9389b9a48cb5a57c433f274338b6b287456d68))
* **main:** release  moq-transport 0.2.1 ([2c32c55](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/2c32c55ac5447829746f184a5fda6c07fb4a5a00))
* **main:** release  moq-transport 0.3.0 ([6681e0e](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/6681e0e3fc5945c327d3f244df3a9ef2edc01155))
* **main:** release  moq-transport 0.3.1 ([34b5fdc](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/34b5fdc861977f3aac89d53b0c91c28771da2e39))
* **main:** release  moq-transport 0.3.2 ([570f6e6](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/570f6e68273feb88278a389b70f69194d2ff3a8e))
* **main:** release  moq-transport 0.3.3 ([1a1a7be](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/1a1a7be0a25eda6437acf9b560832ec81a7ee3f4))
* **main:** release  moq-transport 0.3.4 ([ad2f77c](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/ad2f77cffa96deb25a4703f8f5810834cc8496ab))

## [0.3.4](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/moq-transport-v0.3.3...moq-transport-v0.3.4) (2026-11-16)

### Changed

* Raised the minimum versions of the Media-over-QUIC client libraries to their latest patch releases to pick up upstream bug fixes: `@moq/hang` `^0.5.4`, `@moq/net` `^0.4.7`, `@moq/publish` `^0.5.6`, and `@moq/watch` `^0.6.6`. ([98b7f73](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/98b7f732f8da96695d0d3dce951f220355bc741f))

## [0.3.3](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/moq-transport-v0.3.2...moq-transport-v0.3.3) (2026-11-04)

### Bug Fixes

* A relay reconnect no longer stalls for over a minute when a redial gets no answer. Each attempt to reach the relay now has a deadline, 5 seconds and doubling up to 20, after which it is dialed again. `relayRetryTimeoutMs` (60 seconds by default) still bounds the whole outage, and as before it starts afresh when a page comes back from the back/forward cache. ([#244](https://github.com/pipecat-ai/pipecat-client-web-transports/pull/244))
* `disconnect()` before the session is ready now stops a connection that is between attempts, instead of leaving it dialing. ([#244](https://github.com/pipecat-ai/pipecat-client-web-transports/pull/244))
* When the relay stays unreachable for the whole window, the error now says how many attempts got no answer, for example `still unreachable after 60 s; 3 attempts got no answer`. ([#244](https://github.com/pipecat-ai/pipecat-client-web-transports/pull/244))

## [0.3.2](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/moq-transport-v0.3.1...moq-transport-v0.3.2) (2026-10-29)

### Other

* `@pipecat-ai/moq-transport` now requires `@pipecat-ai/client-js` `~1.16.0` as a peer dependency. Upgrade `@pipecat-ai/client-js` to 1.16.x alongside this release. ([c5465cd](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/c5465cddb143693cc1cac445b47c64e13af59ca4))

## [0.3.1](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/moq-transport-v0.3.0...moq-transport-v0.3.1) (2026-10-25)

### Changed

* `@pipecat-ai/moq-transport` now requires `@pipecat-ai/client-js` `~1.15.0` as a peer dependency. Upgrade `@pipecat-ai/client-js` to 1.15.x alongside this release. ([d2a5122](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/d2a51222639c6013e1202d74a6abea17204b41df))

## [0.3.0](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/moq-transport-v0.2.1...moq-transport-v0.3.0) (2026-10-17)

### Features

* `MoqTransport` now implements the `mediaSupport` getter, reporting that it carries the user's microphone and the bot's audio only; the camera, screen share, and bot video are reported as unsupported. Requires `@pipecat-ai/client-js` 1.14.0 or later. ([4fd131a](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/4fd131a658b1ffc2acedbe8cbc1504347f9e0c0c))

### Other

* Bumped the `@pipecat-ai/client-js` peer dependency to `~1.14.0`. Projects using `@pipecat-ai/moq-transport` should upgrade `@pipecat-ai/client-js` to 1.14.x. ([6f1bf1a](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/6f1bf1a37e7077e54e27a92b810c1e146be781fe))

## [0.2.1](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/moq-transport-v0.2.0...moq-transport-v0.2.1) (2026-10-02)


### Bug Fixes

* **moq-transport:** keep trying to reach the relay for 60 seconds ([43b6060](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/43b6060b051510000e73ea26bd7d8ffade96d568))

## [0.2.0](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/moq-transport-v0.1.1...moq-transport-v0.2.0) (2026-09-30)


### Features

* **moq-transport:** upgrade to @moq-dev 0.4 ([242dd8c](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/242dd8cb29cfc6087964bf6c00d9807a908b92e0))
* **moq-transport:** number transcript records and drop replays on resubscribe ([91476a3](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/91476a36324c357928affcac84fa3091125bdab5))
* **moq-transport:** send session-ending on disconnect and redial when the bot's tracks end without it ([f2ff607](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/f2ff6077a3cf27ca611925a45d8fc18e573e0c4a))


### Bug Fixes

* **moq-transport:** add _wasReady flag to handle moq-relay reconnects ([ba308e1](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/ba308e1424114142abf8130db22dd527f54407c2))
* **moq-transport:** hold client-ready until the bot audio subscription is live ([dc56c47](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/dc56c4700950ec55697705f3fb9f3f86f314eeb8))
* **moq-transport:** hold ready through relay reconnects ([f25ebc1](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/f25ebc159bd887e6023bff43d1ff0705243f5458))

## [0.1.1](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/moq-transport-v0.1.0...moq-transport-v0.1.1) (2026-08-13)


### Bug Fixes

* moq transport ([61c4d97](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/61c4d97e9a062ee9cb2f6e6e6160243ad80124cd))
* wait for the bot's broadcast before subscribing to the transcript ([9ff8594](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/9ff8594ae6596f591d1f2507634b85acc108b84b))

## [0.1.0](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/moq-transport-v0.0.1...moq-transport-v0.1.0) (2026-07-16)

- Initial release of `@pipecat-ai/moq-transport`.
- Media-over-QUIC transport built on `@moq/net`, `@moq/publish`, `@moq/watch`, `@moq/json`, and `@moq/signals`.
- Microphone capture and Opus publish under `<namespace>/<clientId>`.
- Catalog-driven subscription to the bot broadcast at `<namespace>/<botId>`, with bounded-latency audio playback via `@moq/watch` (`Watch.Broadcast` + `Watch.Audio.Source`/`Decoder`/`Emitter`).
- Bidirectional RTVI message delivery over dedicated transcript tracks (`@moq/json` lossless append-log streams): bot→client events/transcripts, and client→bot messages including `client-ready`.
- WebTransport connection with WebSocket fallback (raced by `@moq/net`), and `serverCertificateHashes` support for self-signed dev relays.
