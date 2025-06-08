# @farcaster/frame-core

## 0.0.34

### Patch Changes

- [#211](https://github.com/farcasterxyz/miniapps/pull/211) [`a06cbb3`](https://github.com/farcasterxyz/miniapps/commit/a06cbb3349227af9260e9beffaf2e29305525978) Thanks [@Slokh](https://github.com/Slokh)! - feat: add experimental token actions

## 0.0.33

### Patch Changes

- [#205](https://github.com/farcasterxyz/miniapps/pull/205) [`b1c125f`](https://github.com/farcasterxyz/miniapps/commit/b1c125f594379a3007705a8c5ad29c18fd1fdd86) Thanks [@gabrielayuso](https://github.com/gabrielayuso)! - Added `noindex` field to the mini app manifest.

## 0.0.32

### Patch Changes

- [#195](https://github.com/farcasterxyz/miniapps/pull/195) [`2617d14`](https://github.com/farcasterxyz/miniapps/commit/2617d145a6f965643857b22e715ced42e71a7c0d) Thanks [@gabrielayuso](https://github.com/gabrielayuso)! - - Introduced new manifest metadata fields (see [discussions/191](https://github.com/farcasterxyz/miniapps/discussions/191))
  - Deprecated `imageUrl` and `buttonTitle` (see [discussions/194](https://github.com/farcasterxyz/miniapps/discussions/194))

## 0.0.31

### Patch Changes

- [#185](https://github.com/farcasterxyz/miniapps/pull/185) [`c960c03`](https://github.com/farcasterxyz/miniapps/commit/c960c0397c3812ed627f6c2b5ab3927ab02f2366) Thanks [@horsefacts](https://github.com/horsefacts)! - chore: increase URL max length to 1024 characters

## 0.0.30

### Patch Changes

- [#169](https://github.com/farcasterxyz/miniapps/pull/169) [`e0554b7`](https://github.com/farcasterxyz/miniapps/commit/e0554b77543f0f176e7125d9cd03b7ff76762e29) Thanks [@deodad](https://github.com/deodad)! - Added composeCast action

## 0.0.29

### Patch Changes

- [#120](https://github.com/farcasterxyz/frames/pull/120) [`7b9d2e1`](https://github.com/farcasterxyz/frames/commit/7b9d2e1947f824d1e0bb4111ba408a00325d1866) Thanks [@deodad](https://github.com/deodad)! - added MIT license

## 0.0.28

### Patch Changes

- [#118](https://github.com/farcasterxyz/frames/pull/118) [`11818e0`](https://github.com/farcasterxyz/frames/commit/11818e024da7d12c23c7e90a1c9f19b9d18cd33e) Thanks [@deodad](https://github.com/deodad)! - Refactor eth code into module

- [#118](https://github.com/farcasterxyz/frames/pull/118) [`11818e0`](https://github.com/farcasterxyz/frames/commit/11818e024da7d12c23c7e90a1c9f19b9d18cd33e) Thanks [@deodad](https://github.com/deodad)! - Removed duplicate type, use SignIn.SignInOptions

- [#118](https://github.com/farcasterxyz/frames/pull/118) [`11818e0`](https://github.com/farcasterxyz/frames/commit/11818e024da7d12c23c7e90a1c9f19b9d18cd33e) Thanks [@deodad](https://github.com/deodad)! - refactored ready into module

## 0.0.27

### Patch Changes

- [#107](https://github.com/farcasterxyz/frames/pull/107) [`a437325`](https://github.com/farcasterxyz/frames/commit/a43732592fb3c8fd33400f01a97a08d6fe11bb88) Thanks [@horsefacts](https://github.com/horsefacts)! - add swap/token actions

## 0.0.26

### Patch Changes

- [#102](https://github.com/farcasterxyz/frames/pull/102) [`b20e3cf`](https://github.com/farcasterxyz/frames/commit/b20e3cfd6105a2a7f837cc9f1db2ccd4620b274b) Thanks [@horsefacts](https://github.com/horsefacts)! - add aspectRatio to embed schema

## 0.0.25

### Patch Changes

- [#99](https://github.com/farcasterxyz/frames/pull/99) [`ce37061`](https://github.com/farcasterxyz/frames/commit/ce3706174e19bc074e302c66b19c529b5b99f84b) Thanks [@horsefacts](https://github.com/horsefacts)! - add view token action type

## 0.0.24

### Patch Changes

- [#90](https://github.com/farcasterxyz/frames/pull/90) [`41e13ce`](https://github.com/farcasterxyz/frames/commit/41e13ce646f3e4f34430fd346d2f6df258428da4) Thanks [@deodad](https://github.com/deodad)! - add viewProfile action

## 0.0.23

### Patch Changes

- [#88](https://github.com/farcasterxyz/frames/pull/88) [`5b8367c`](https://github.com/farcasterxyz/frames/commit/5b8367c37186c7bb9691ae0f7336c5203098239f) Thanks [@deodad](https://github.com/deodad)! - - added ChannelLocationContext type
  - export all context types under Context name
  - made naming of context types consistent and simpler
    - FrameLocationContextCastEmbed -> CastEmbedLocationContext
    - FrameLocationContextNotification -> NotificationLocationContext
    - FrameLocationContextLauncher -> LauncherNotificationContext

## 0.0.22

### Patch Changes

- [#70](https://github.com/farcasterxyz/frames/pull/70) [`2ada8e7`](https://github.com/farcasterxyz/frames/commit/2ada8e7b06dcc2b7b43363ffa619c0d19726a2f7) Thanks [@deodad](https://github.com/deodad)! - standardized naming in SignIn module

- [#68](https://github.com/farcasterxyz/frames/pull/68) [`937fc7c`](https://github.com/farcasterxyz/frames/commit/937fc7cecd66412077f790c92b12750b7ac3a99f) Thanks [@deodad](https://github.com/deodad)! - update dependencies

- [#66](https://github.com/farcasterxyz/frames/pull/66) [`b7624a6`](https://github.com/farcasterxyz/frames/commit/b7624a69fac63f4a533848ec470430c66d8b03e2) Thanks [@deodad](https://github.com/deodad)! - remove unused devDependencies

- [#71](https://github.com/farcasterxyz/frames/pull/71) [`4cf0e2d`](https://github.com/farcasterxyz/frames/commit/4cf0e2d5fbf6cb577351e49df78bb946823e72be) Thanks [@deodad](https://github.com/deodad)! - refactor AddFrame into module

- [`0006dde`](https://github.com/farcasterxyz/frames/commit/0006dde9b1ad9046962f02178daa4cc7529f1df8) Thanks [@deodad](https://github.com/deodad)! - support eip6963

## 0.0.21

### Patch Changes

- 1c4c66a: add embed to location context

## 0.0.20

### Patch Changes

- 6f9253d: add safeAreaInsets to client context
- 2a68a88: add embed to cast_embed location context

## 0.0.19

### Patch Changes

- f5457ab: Add real-time eventing from host to frame

## 0.0.18

### Patch Changes

- 27e8fca: add sign in action

## 0.0.17

### Patch Changes

- 2a5ec00: accept next as a valid frame schema version

## 0.0.16

### Patch Changes

- fdcc36a: Add imageUrl and buttonTitle to domain manifest frame config

## 0.0.15

### Patch Changes

- 2e0e776: fix esm distro of frame-core

## 0.0.14

### Patch Changes

- 444a210: ship cjs build alongside esm

## 0.0.13

### Patch Changes

- 4e2a50f: consistent schema names, domain manifest version

## 0.0.12

### Patch Changes

- a2e727d: add zod schemas for all data forms

## 0.0.11

### Patch Changes

- 06ca566: optional ready options
- 7f35aa5: Switch notificationId to a string from a UUID
- aaf9e0e: Standardize literals to snake_cast and add cast_embed location context + client context

## 0.0.10

### Patch Changes

- 840776c: add ready options with disableNativeGestures

## 0.0.9

### Patch Changes

- c4815e8: split out React Native host into its own package

## 0.0.8

### Patch Changes

- 5e70f39: support iframe channel in host and sdk

## 0.0.7

### Patch Changes

- e716b1c: Support Ethereum Provider events, preserve errors over the wire

## 0.0.6

### Patch Changes

- 886a9bb: Add location type=notification context

## 0.0.5

### Patch Changes

- a258394: Add support for adding frames, notifications and events

## 0.0.4

### Patch Changes

- 59ab89c: update FrameContext
