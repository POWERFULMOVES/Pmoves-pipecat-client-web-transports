# Changelog

All notable changes to **Pipecat LiveKit Transport** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/compare/livekit-transport-v1.1.2...livekit-transport-v1.2.0) (2026-11-19)


### Features

* add livekit transport ([9c860dd](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/9c860dd225b537eb9b994959d74d7ce287a6d35d))
* **livekit-transport:** add mediaSupport ([9b4eefc](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/9b4eefce744f36e69acc7e4c4c52425efb18237b))
* report media support from each transport ([33dff50](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/33dff50eff8231ecd708e90a10a38104b25b5e0e))


### Bug Fixes

* **livekit-transport:** address review feedback from PR [#171](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/issues/171) ([9f5e470](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/9f5e4707de1d0d2d5ed13d02903edeac93caa5f7))
* **livekit-transport:** guard abort after publish, before connected ([10cf08f](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/10cf08f4beed8b7190480c1af3ac4f029163152a))
* **livekit-transport:** keep pre-join tracks alive through connect ([8a1f66b](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/8a1f66b7d60c7287a8f2e6a052751c278717e15b))
* **livekit-transport:** only dispatch rtvi-ai data messages ([534e674](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/534e674252a4882b3fba17297444933e2a688ba7))


### Miscellaneous Chores

* bump @pipecat-ai/client-js dependencies to 1.14.0 ([a58f148](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/a58f148120c748390b5ba1303ff4e49dcbd93703))
* bump client-js dependency to 1.15 and resolve vulnerabilities ([9265a43](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/9265a43e71be431d9c765eb91e313ec02c0fa17c))
* bump client-js dependency to version 1.16.0 ([9085f2a](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/9085f2a0e58151fce984a9300fd5dd2cde393493))
* curate release notes ([e6dbe02](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/e6dbe02f8f3bcad0a16c1e3a4e86ddcceff11599))
* curate release notes ([973138c](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/973138cc57e3136abbbcf129610fb95c23d63e27))
* curate release notes ([81dc9e7](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/81dc9e778ba7075f3d3ad1a556116cb864e779e1))
* **main:** release  livekit-transport 1.1.0 ([8d0dc34](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/8d0dc344c87daedbf72ab372b7bc4801669e0c9f))
* **main:** release  livekit-transport 1.1.1 ([98aca29](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/98aca29653ead502ab51a26155022ffd38eff80f))
* **main:** release  livekit-transport 1.1.2 ([d838686](https://github.com/POWERFULMOVES/Pmoves-pipecat-client-web-transports/commit/d83868645ccb41ba5eb2eac7de8e62cf168f9cbc))

## [1.1.2](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/livekit-transport-v1.1.1...livekit-transport-v1.1.2) (2026-10-29)

### Other

* `@pipecat-ai/livekit-transport` now requires `@pipecat-ai/client-js` `~1.16.0` as a peer dependency. Upgrade `@pipecat-ai/client-js` to 1.16.x alongside this release. ([c5465cd](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/c5465cddb143693cc1cac445b47c64e13af59ca4))

## [1.1.1](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/livekit-transport-v1.1.0...livekit-transport-v1.1.1) (2026-10-25)

### Changed

* `@pipecat-ai/livekit-transport` now requires `@pipecat-ai/client-js` `~1.15.0` as a peer dependency. Upgrade `@pipecat-ai/client-js` to 1.15.x alongside this release. ([d2a5122](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/d2a51222639c6013e1202d74a6abea17204b41df))

## [1.1.0](https://github.com/pipecat-ai/pipecat-client-web-transports/compare/livekit-transport-v1.0.0...livekit-transport-v1.1.0) (2026-10-17)

### Features

* `LiveKitTransport` now implements the `mediaSupport` getter, reporting that it carries the user's microphone and camera and the bot's audio and video, plus screen share where the browser can share a screen. `PipecatClient.mediaSupport` combines this with what the bot supports so your UI can hide controls that can't work. Requires `@pipecat-ai/client-js` 1.14.0 or later. ([9b4eefc](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/9b4eefce744f36e69acc7e4c4c52425efb18237b))

### Other

* Bumped the `@pipecat-ai/client-js` peer dependency to `~1.14.0`. Projects using `@pipecat-ai/livekit-transport` should upgrade `@pipecat-ai/client-js` to 1.14.x. ([6f1bf1a](https://github.com/pipecat-ai/pipecat-client-web-transports/commit/6f1bf1a37e7077e54e27a92b810c1e146be781fe))

## [1.0.0] - 2026-01-18

### Added

- Initial release of `@pipecat-ai/livekit-transport`
- WebRTC transport implementation using LiveKit infrastructure
- Complete device management for microphone, camera, and speaker
- Support for flexible authentication via `authUrl` or direct `url`/`token`
- Screen sharing functionality
- Real-time messaging via LiveKit data channels
- Comprehensive event handling for all LiveKit room events
- Participant tracking and management
- Transport state management aligned with Pipecat transport lifecycle
- Full TypeScript type definitions
- Integration with `@pipecat-ai/client-js` v1.13.0+

### Features

- 🎥 Camera device management with hot-swapping
- 🎤 Microphone input handling with device switching
- 🔊 Speaker output control
- 📡 WebRTC connection management via LiveKit SDK
- 🤖 Bot participant identification and tracking
- 📺 Screen sharing with audio support
- 💬 Real-time messaging and data channel communication
- 🔐 Flexible authentication methods (auth URL or direct credentials)
- ⚡ Automatic device enumeration and change detection
- 🎯 Proper synchronization of device states

### Dependencies

- `livekit-client`: ^2.17.0
- `@pipecat-ai/client-js`: ^1.13.0 (peer dependency)
