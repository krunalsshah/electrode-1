# 4/18/2019

- fix subapp in prod mode
- support for React16's renderToNodeStream
- remove css-split-plugin
- allow sourcemap to work in local prod mode
- babel extendLoader babel config through babel-loader instead of babelrc

## Packages

### Directly Updated

-   `electrode-archetype-react-app@6.4.4` `(6.4.3 => 6.4.4)`
-   `electrode-archetype-react-app-dev@6.4.4` `(6.4.3 => 6.4.4)`
-   `electrode-react-webapp@3.6.0` `(3.5.2 => 3.6.0)`
-   `electrode-redux-router-engine@2.3.0` `(2.2.0 => 2.3.0)`
-   `subapp-server@1.0.4` `(1.0.3 => 1.0.4)`
-   `subapp-util@1.0.1` `(1.0.0 => 1.0.1)`
-   `subapp-web@1.0.1` `(1.0.0 => 1.0.1)`

### Lerna Updated

-   `subapp-redux@1.0.1` `(1.0.0 => 1.0.1)`

## Commits

-   `packages/electrode-archetype-react-app[-dev]`

    -   allow sourcemap to work in local prod mode ([#1216](https://github.com/electrode-io/electrode/pull/1216)) [commit](http://github.com/electrode-io/electrode/commit/dc4e1dac89e57cd56a510b8cc36d3a9c1375bd56)
    -   remove css-split-plugin ([#1215](https://github.com/electrode-io/electrode/pull/1215)) [commit](http://github.com/electrode-io/electrode/commit/628e957fb1ac484dd0cdbac81d03fa4b21ad504e)
    -   use all code under src and dirs starts with server as server ([#1211](https://github.com/electrode-io/electrode/pull/1211)) [commit](http://github.com/electrode-io/electrode/commit/c868210f317b933263c2f85221a729f159a2db3a)
    -   separate hasMultiTargets & add extendLoader ([#1209](https://github.com/electrode-io/electrode/pull/1209)) [commit](http://github.com/electrode-io/electrode/commit/34382d2409e8c1386379aa466593106ee15e1136)
    -   [patch] fix webpack entry partial context for subapps ([#1206](https://github.com/electrode-io/electrode/pull/1206)) [commit](http://github.com/electrode-io/electrode/commit/b24debb6c985204586fbfb4a58826ce94bf0b92d)
    -   [patch] fix webpack dev detection and loading iso loader config ([#1204](https://github.com/electrode-io/electrode/pull/1204)) [commit](http://github.com/electrode-io/electrode/commit/248ba799d3b13ce2c2357cee5db31175f13437d2)
    -   skip dev middleware for production with express and koa ([#1199](https://github.com/electrode-io/electrode/pull/1199)) [commit](http://github.com/electrode-io/electrode/commit/191f1f1ecb9532bceeadb2e05f658f2eb2e12176)
    -   Add useBuiltIns for @babel/preset-env ([#1195](https://github.com/electrode-io/electrode/pull/1195)) [commit](http://github.com/electrode-io/electrode/commit/04b5395cae88b97da78cfc8aa0d71da1093002d8)
    -   [patch] handle @babel/polyfill in entry for multi target's default ([#1194](https://github.com/electrode-io/electrode/pull/1194)) [commit](http://github.com/electrode-io/electrode/commit/178a3ed76d49746edcdefe7f8ee02a52908d2756)
    -   babel ignore test files under entire src ([#1192](https://github.com/electrode-io/electrode/pull/1192)) [commit](http://github.com/electrode-io/electrode/commit/de33e170c5a0a52c044130a9224cfa33b1cfc1f6)

-   `packages/electrode-react-webapp`

    -   handle SSR stream errors ([#1221](https://github.com/electrode-io/electrode/pull/1221)) [commit](http://github.com/electrode-io/electrode/commit/bfefe2675a73704f59b51faf06fe88ae252043c3)
    -   allow renderToNodeStream for subapp ([#1210](https://github.com/electrode-io/electrode/pull/1210)) [commit](http://github.com/electrode-io/electrode/commit/cbe0da0474f1b6bf1ef807507f6d1cfa71d92dfa)
    -   [minor] allow content to specify use streams for generating output ([#1201](https://github.com/electrode-io/electrode/pull/1201)) [commit](http://github.com/electrode-io/electrode/commit/690dec1295234c038575cc2b189af873d96fa2d3)

-   `packages/electrode-redux-router-engine`

    -   [minor] support using render to stream APIs for SSR ([#1202](https://github.com/electrode-io/electrode/pull/1202)) [commit](http://github.com/electrode-io/electrode/commit/965e70f75ec59866f65657dbeca126bcd0407ecc)

-   `packages/subapp-server`

    -   allow renderToNodeStream for subapp ([#1210](https://github.com/electrode-io/electrode/pull/1210)) [commit](http://github.com/electrode-io/electrode/commit/cbe0da0474f1b6bf1ef807507f6d1cfa71d92dfa)

-   `packages/subapp-util`

    -   fix subapp in prod mode ([#1212](https://github.com/electrode-io/electrode/pull/1212)) [commit](http://github.com/electrode-io/electrode/commit/6829049401d23bfd15acd26582cd25717569f5d0)
    -   add subapp-util test ([#1222](https://github.com/electrode-io/electrode/pull/1222)) [commit](http://github.com/electrode-io/electrode/commit/6a407805fb4b516a8c155ef58a56392f5c4dde0e)

-   `packages/subapp-web`

    -   fix get vendor bundles for prod mode ([#1219](https://github.com/electrode-io/electrode/pull/1219)) [commit](http://github.com/electrode-io/electrode/commit/092160187842375d163c099399cda8686175ea01)
    -   allow renderToNodeStream for subapp ([#1210](https://github.com/electrode-io/electrode/pull/1210)) [commit](http://github.com/electrode-io/electrode/commit/cbe0da0474f1b6bf1ef807507f6d1cfa71d92dfa)

-   `samples/hapi-app`

    -   update samples lock and auto gen files [commit](http://github.com/electrode-io/electrode/commit/b689c165b1434718db01f00e1d830e4350d34984)
    -   update sample lockfile [commit](http://github.com/electrode-io/electrode/commit/41caa73c31679cdaa3d2ef4528fd34cf24577269)

-   `samples/poc-subapp`

    -   update samples lock and auto gen files [commit](http://github.com/electrode-io/electrode/commit/b689c165b1434718db01f00e1d830e4350d34984)
    -   allow renderToNodeStream for subapp ([#1210](https://github.com/electrode-io/electrode/pull/1210)) [commit](http://github.com/electrode-io/electrode/commit/cbe0da0474f1b6bf1ef807507f6d1cfa71d92dfa)

-   `docs`

    -   [minor] support using render to stream APIs for SSR ([#1202](https://github.com/electrode-io/electrode/pull/1202)) [commit](http://github.com/electrode-io/electrode/commit/965e70f75ec59866f65657dbeca126bcd0407ecc)
    -   Fix broken image URLs ([#1203](https://github.com/electrode-io/electrode/pull/1203)) [commit](http://github.com/electrode-io/electrode/commit/42821703df38bdc32d4a2163ae412b1c3eb1fb2a)
    -   update doc of extract-style part ([#1184](https://github.com/electrode-io/electrode/pull/1184)) [commit](http://github.com/electrode-io/electrode/commit/5a0aa5e73e31226554e7276cbfd5f0c653a87aa9)

# 3/26/2019

- electrode-react-webapp
  - handle multi targeted bundle selection when user defined entries

## Packages

### Directly Updated

-   `electrode-react-webapp@3.5.2` `(3.5.1 => 3.5.2)`

### Lerna Updated

## Commits

-   `packages/electrode-react-webapp`

    -   handle multi targeted bundle selection when user defined entries ([#1191](https://github.com/electrode-io/electrode/pull/1191)) [commit](http://github.com/electrode-io/electrode/commit/525b8a6a7f966c30c4984d48ecf5a138277b5827)

-   `packages/webpack-config-composer`

    -   [chore] update CI scripts [commit](http://github.com/electrode-io/electrode/commit/49e54bdb768eac78ec32603a352e1d0d7e7474e9)

-   `samples/universal-react-node`

    -   [chore] update sample lockfile [commit](http://github.com/electrode-io/electrode/commit/5794b307d47835bc7824e5e5cf1b3330307e0b57)

# 3/21/2019

## Packages

### Directly Updated

-   `electrode-archetype-react-app@6.4.3` `(6.4.2 => 6.4.3)`
-   `electrode-archetype-react-app-dev@6.4.3` `(6.4.2 => 6.4.3)`
-   `electrode-react-webapp@3.5.1` `(3.5.0 => 3.5.1)`
-   `generator-electrode@5.1.4` `(5.1.3 => 5.1.4)`

### Lerna Updated

-   `subapp-server@1.0.3` `(1.0.2 => 1.0.3)`

## Commits

-   `packages/electrode-archetype-react-app[-dev]`

    -   keep original behavior if no extra babel targets specified ([#1188](https://github.com/electrode-io/electrode/pull/1188)) [commit](http://github.com/electrode-io/electrode/commit/2319643556ae6250ce9d3e529643d8f88d9a70c3)

-   `packages/electrode-ignite`

    -   [chore] update CI scripts [commit](http://github.com/electrode-io/electrode/commit/5479e3471525ce3f622f903402d9576c914627e1)

-   `packages/electrode-react-webapp`

    -   keep original behavior if no extra babel targets specified ([#1188](https://github.com/electrode-io/electrode/pull/1188)) [commit](http://github.com/electrode-io/electrode/commit/2319643556ae6250ce9d3e529643d8f88d9a70c3)

-   `packages/generator-electrode`

    -   keep original behavior if no extra babel targets specified ([#1188](https://github.com/electrode-io/electrode/pull/1188)) [commit](http://github.com/electrode-io/electrode/commit/2319643556ae6250ce9d3e529643d8f88d9a70c3)

-   `samples/hapi-app`

    -   update hapi-app sample with dynamic import ([#1186](https://github.com/electrode-io/electrode/pull/1186)) [commit](http://github.com/electrode-io/electrode/commit/f540d4f348af9456ac9cb3fa042d4509fc219d9c)

# 3/20/2019

- electrode-react-app-archetype:
  - support .less styles
  - dynamic import support and demo
  - fix cssModuleSupport flag
  - support webappPrefix for apps

## Packages

### Directly Updated

-   `electrode-archetype-react-app-dev@6.4.2` `(6.4.1 => 6.4.2)`
-   `electrode-react-webapp@3.5.0` `(3.4.1 => 3.5.0)`
-   `electrode-redux-router-engine@2.2.0` `(2.1.8 => 2.2.0)`
-   `electrode-ui-config@1.3.0` `(1.2.0 => 1.3.0)`
-   `generator-electrode@5.1.3` `(5.1.2 => 5.1.3)`

### Lerna Updated

-   `electrode-archetype-react-app@6.4.2` `(6.4.1 => 6.4.2)`

## Commits

-   `packages/electrode-archetype-opt-css-module`

    -   [chore] CI runs coverage [commit](http://github.com/electrode-io/electrode/commit/5ad18247c8634d2da3ef09bbe884a392a58fdead)

-   `packages/electrode-archetype-opt-inferno`

    -   [chore] CI runs coverage [commit](http://github.com/electrode-io/electrode/commit/5ad18247c8634d2da3ef09bbe884a392a58fdead)

-   `packages/electrode-archetype-react-app[-dev]`

    -   change cssModuleSupport type to boolean ([#1187](https://github.com/electrode-io/electrode/pull/1187)) [commit](http://github.com/electrode-io/electrode/commit/60c2131b18933218e7e4571222325e13c4f8650b)
    -   add dynamic demo in templates ([#1176](https://github.com/electrode-io/electrode/pull/1176)) [commit](http://github.com/electrode-io/electrode/commit/c5f9705a42bac8e3bcdecfcd975a9fca92f686a9)
    -   support .less style ([#1181](https://github.com/electrode-io/electrode/pull/1181)) [commit](http://github.com/electrode-io/electrode/commit/74a6d9d9317bf31a20577b6d51d73f0dc4f62afd)
    -   [chore] CI runs coverage [commit](http://github.com/electrode-io/electrode/commit/5ad18247c8634d2da3ef09bbe884a392a58fdead)

-   `packages/electrode-cookies`

    -   [chore] CI runs coverage [commit](http://github.com/electrode-io/electrode/commit/5ad18247c8634d2da3ef09bbe884a392a58fdead)

-   `packages/electrode-ignite`

    -   [chore] CI runs coverage [commit](http://github.com/electrode-io/electrode/commit/5ad18247c8634d2da3ef09bbe884a392a58fdead)

-   `packages/electrode-react-context`

    -   [chore] CI runs coverage [commit](http://github.com/electrode-io/electrode/commit/5ad18247c8634d2da3ef09bbe884a392a58fdead)

-   `packages/electrode-react-webapp`

    -   [minor] handle webappPrefix for ui config ([#1185](https://github.com/electrode-io/electrode/pull/1185)) [commit](http://github.com/electrode-io/electrode/commit/267afb5ba673c782defc7a7c9254c4f717edbf38)
    -   add missing test cases in electrode-react-webapp ([#1183](https://github.com/electrode-io/electrode/pull/1183)) [commit](http://github.com/electrode-io/electrode/commit/dcc5bc4cb7e22ea49a25213d5a1d621d549ecd9b)
    -   [minor] support webappPrefix to allow multiple apps on the same page ([#1182](https://github.com/electrode-io/electrode/pull/1182)) [commit](http://github.com/electrode-io/electrode/commit/a3a087fbc690d06c13cd394c87197b034563e934)

-   `packages/electrode-redux-router-engine`

    -   [minor] support webappPrefix to allow multiple apps on the same page ([#1182](https://github.com/electrode-io/electrode/pull/1182)) [commit](http://github.com/electrode-io/electrode/commit/a3a087fbc690d06c13cd394c87197b034563e934)

-   `packages/electrode-ui-config`

    -   [minor] handle webappPrefix for ui config ([#1185](https://github.com/electrode-io/electrode/pull/1185)) [commit](http://github.com/electrode-io/electrode/commit/267afb5ba673c782defc7a7c9254c4f717edbf38)

-   `packages/electrode-ui-logger`

    -   [chore] CI runs coverage [commit](http://github.com/electrode-io/electrode/commit/5ad18247c8634d2da3ef09bbe884a392a58fdead)

-   `packages/electrode-webpack-reporter`

    -   [chore] CI runs coverage [commit](http://github.com/electrode-io/electrode/commit/5ad18247c8634d2da3ef09bbe884a392a58fdead)

-   `packages/generator-electrode`

    -   add dynamic demo in templates ([#1176](https://github.com/electrode-io/electrode/pull/1176)) [commit](http://github.com/electrode-io/electrode/commit/c5f9705a42bac8e3bcdecfcd975a9fca92f686a9)
    -   [chore] CI runs coverage [commit](http://github.com/electrode-io/electrode/commit/5ad18247c8634d2da3ef09bbe884a392a58fdead)

-   `packages/ignite-core`

    -   [chore] CI runs coverage [commit](http://github.com/electrode-io/electrode/commit/5ad18247c8634d2da3ef09bbe884a392a58fdead)

-   `packages/subapp-redux`

    -   [chore] CI runs coverage [commit](http://github.com/electrode-io/electrode/commit/5ad18247c8634d2da3ef09bbe884a392a58fdead)

-   `packages/subapp-server`

    -   [chore] CI runs coverage [commit](http://github.com/electrode-io/electrode/commit/5ad18247c8634d2da3ef09bbe884a392a58fdead)

-   `packages/subapp-util`

    -   [chore] CI runs coverage [commit](http://github.com/electrode-io/electrode/commit/5ad18247c8634d2da3ef09bbe884a392a58fdead)

-   `packages/subapp-web`

    -   [chore] CI runs coverage [commit](http://github.com/electrode-io/electrode/commit/5ad18247c8634d2da3ef09bbe884a392a58fdead)

-   `packages/webpack-config-composer`

    -   [chore] CI runs coverage [commit](http://github.com/electrode-io/electrode/commit/5ad18247c8634d2da3ef09bbe884a392a58fdead)

-   `samples/hapi-app`

    -   [minor] handle webappPrefix for ui config ([#1185](https://github.com/electrode-io/electrode/pull/1185)) [commit](http://github.com/electrode-io/electrode/commit/267afb5ba673c782defc7a7c9254c4f717edbf38)
    -   [minor] support webappPrefix to allow multiple apps on the same page ([#1182](https://github.com/electrode-io/electrode/pull/1182)) [commit](http://github.com/electrode-io/electrode/commit/a3a087fbc690d06c13cd394c87197b034563e934)

-   `samples/universal-react-node`

    -   [chore] update sample lockfile [commit](http://github.com/electrode-io/electrode/commit/c98f08f43d5e0d7dde35dd961509d80d019fb570)

# 3/18/2019

- server side bundle selection for different babel targets

## Packages

### Directly Updated

-   `electrode-archetype-react-app@6.4.1` `(6.4.0 => 6.4.1)`
-   `electrode-archetype-react-app-dev@6.4.1` `(6.4.0 => 6.4.1)`
-   `electrode-react-webapp@3.4.1` `(3.4.0 => 3.4.1)`

### Lerna Updated

-   `subapp-server@1.0.2` `(1.0.1 => 1.0.2)`

## Commits

-   `packages/electrode-archetype-react-app[-dev]`

    -   [chore] use xclap.concurrent to make concurrent tasks ([#1175](https://github.com/electrode-io/electrode/pull/1175)) [commit](http://github.com/electrode-io/electrode/commit/b1eb3b6ebaabf94c618a50228bb220578798d19e)
    -   server side bundle selection for different targets ([#1166](https://github.com/electrode-io/electrode/pull/1166)) [commit](http://github.com/electrode-io/electrode/commit/2eac014736f462a030917cc1a26575aefc48bcd3)
    -   [patch] remove transform plugins already in @babel/preset-env ([#1174](https://github.com/electrode-io/electrode/pull/1174)) [commit](http://github.com/electrode-io/electrode/commit/5688e8f81710c2d2de2fb34bce37beabb9eb54c6)

-   `packages/electrode-react-webapp`

    -   server side bundle selection for different targets ([#1166](https://github.com/electrode-io/electrode/pull/1166)) [commit](http://github.com/electrode-io/electrode/commit/2eac014736f462a030917cc1a26575aefc48bcd3)

-   `samples/universal-react-node`

    -   [chore] update sample lockfile [commit](http://github.com/electrode-io/electrode/commit/fb4e55f680740f25f911914976ec58d51d5e5a56)

# 3/12/2019

- electrode-react-webapp - [feat] run time select template support

## Packages

### Directly Updated

-   `electrode-react-webapp@3.4.0` `(3.3.3 => 3.4.0)`

### Lerna Updated

-   `subapp-server@1.0.1` `(1.0.0 => 1.0.1)`

## Commits

-   `packages/electrode-react-webapp`

    -   [minor] allow user to specify template cache key ([#1172](https://github.com/electrode-io/electrode/pull/1172)) [commit](http://github.com/electrode-io/electrode/commit/6317129572370ff453d90d808961577e86d48817)
    -   [minor] support run time selectTemplate ([#1167](https://github.com/electrode-io/electrode/pull/1167)) [commit](http://github.com/electrode-io/electrode/commit/3c54ce0e0742b39f101158d0c5cc2474cc5978ff)
    -   [patch] selectTemplate can return options for route ([#1173](https://github.com/electrode-io/electrode/pull/1173)) [commit](http://github.com/electrode-io/electrode/commit/b8368e292eb1f82748ec814658f380c32fe2ee16)

# 3/7/2019

- Fix: getHeader missing for webpack-dev-middleware
- New features (beta)
  - subapp support
  - output multiple bundles targetting different browsers

## Packages

### Directly Updated

- `electrode-archetype-react-app@6.4.0` `(6.3.2 => 6.4.0)`
- `electrode-archetype-react-app-dev@6.4.0` `(6.3.2 => 6.4.0)`
- `subapp-redux@1.0.0` `(0.1.0 => 1.0.0)`
- `subapp-server@1.0.0` `(0.1.0 => 1.0.0)`
- `subapp-util@1.0.0` `(0.1.0 => 1.0.0)`
- `subapp-web@1.0.0` `(0.1.0 => 1.0.0)`

## Commits

- `packages/electrode-archetype-react-app[-dev]`

  - [patch] fix multi webpack build startup racing ([#1164](https://github.com/electrode-io/electrode/pull/1164)) [commit](http://github.com/electrode-io/electrode/commit/71ae63240c7e407772fd9405351366ccde5faf6e)
  - [patch] fix output `dist-X` issue ([#1163](https://github.com/electrode-io/electrode/pull/1163)) [commit](http://github.com/electrode-io/electrode/commit/08dc5101c1a95febbd2a97ffe7aacdb5cf9cad25)
  - [chore] fix lint error [commit](http://github.com/electrode-io/electrode/commit/42a6abe2200e9c03894aad262cd115bffd00f9a8)
  - [patch] add getHeader() to middleware ([#1162](https://github.com/electrode-io/electrode/pull/1162)) [commit](http://github.com/electrode-io/electrode/commit/2c5951ffc08dfb71eda2fd2bd71efce483d9b016)
  - [patch] support multiple babel preset-env targets ([#1160](https://github.com/electrode-io/electrode/pull/1160)) [commit](http://github.com/electrode-io/electrode/commit/d9ad0aba3c5380505215a3f07c7b1d2099b3f8df)
  - [minor][feat] subapp support ([#1158](https://github.com/electrode-io/electrode/pull/1158)) [commit](http://github.com/electrode-io/electrode/commit/2bcc5922984edcf314aac29ea0ab78485f0bbeda)

- `packages/subapp-redux`

  - [minor][feat] subapp support ([#1158](https://github.com/electrode-io/electrode/pull/1158)) [commit](http://github.com/electrode-io/electrode/commit/2bcc5922984edcf314aac29ea0ab78485f0bbeda)
  - [major] subapp first beta release [commit](http://github.com/electrode-io/electrode/commit/24167ccdb10ec4f5f19966f6136e26912e5a1526)

- `packages/subapp-server`

  - [minor][feat] subapp support ([#1158](https://github.com/electrode-io/electrode/pull/1158)) [commit](http://github.com/electrode-io/electrode/commit/2bcc5922984edcf314aac29ea0ab78485f0bbeda)
  - [major] subapp first beta release [commit](http://github.com/electrode-io/electrode/commit/24167ccdb10ec4f5f19966f6136e26912e5a1526)

- `packages/subapp-util`

  - [patch] fix scaning for subapp server entry ([#1159](https://github.com/electrode-io/electrode/pull/1159)) [commit](http://github.com/electrode-io/electrode/commit/6f15a2bdc4b60ad3087a1376e72ae867137e0a7e)
  - [minor][feat] subapp support ([#1158](https://github.com/electrode-io/electrode/pull/1158)) [commit](http://github.com/electrode-io/electrode/commit/2bcc5922984edcf314aac29ea0ab78485f0bbeda)
  - [major] subapp first beta release [commit](http://github.com/electrode-io/electrode/commit/24167ccdb10ec4f5f19966f6136e26912e5a1526)

- `packages/subapp-web`

  - [minor][feat] subapp support ([#1158](https://github.com/electrode-io/electrode/pull/1158)) [commit](http://github.com/electrode-io/electrode/commit/2bcc5922984edcf314aac29ea0ab78485f0bbeda)
  - [major] subapp first beta release [commit](http://github.com/electrode-io/electrode/commit/24167ccdb10ec4f5f19966f6136e26912e5a1526)

- `samples/hapi-app`

  - [patch] fix multi webpack build startup racing ([#1164](https://github.com/electrode-io/electrode/pull/1164)) [commit](http://github.com/electrode-io/electrode/commit/71ae63240c7e407772fd9405351366ccde5faf6e)
  - [minor][feat] subapp support ([#1158](https://github.com/electrode-io/electrode/pull/1158)) [commit](http://github.com/electrode-io/electrode/commit/2bcc5922984edcf314aac29ea0ab78485f0bbeda)
  - [chore] update sample gitignore and lockfile [commit](http://github.com/electrode-io/electrode/commit/94b555b3f7dffdb9216a3f7466e4920a31e2ab17)

- `samples/poc-subapp`

  - [patch] fix scaning for subapp server entry ([#1159](https://github.com/electrode-io/electrode/pull/1159)) [commit](http://github.com/electrode-io/electrode/commit/6f15a2bdc4b60ad3087a1376e72ae867137e0a7e)
  - [minor][feat] subapp support ([#1158](https://github.com/electrode-io/electrode/pull/1158)) [commit](http://github.com/electrode-io/electrode/commit/2bcc5922984edcf314aac29ea0ab78485f0bbeda)

- `samples/react-vendor-dll`

  - [minor][feat] subapp support ([#1158](https://github.com/electrode-io/electrode/pull/1158)) [commit](http://github.com/electrode-io/electrode/commit/2bcc5922984edcf314aac29ea0ab78485f0bbeda)

- `samples/universal-react-node`

  - [minor][feat] subapp support ([#1158](https://github.com/electrode-io/electrode/pull/1158)) [commit](http://github.com/electrode-io/electrode/commit/2bcc5922984edcf314aac29ea0ab78485f0bbeda)

# 2/26/2019

- electrode-archetype-react-app
  - minor updates and fixes for dev admin server
  - always save stats to disk in webpack dev mode
- electrode-react-webapp
  - use require to load module for token
  - insert more informative token ids in rendered output with props

## Packages

### Directly Updated

- `electrode-archetype-react-app@6.3.2` `(6.3.1 => 6.3.2)`
- `electrode-archetype-react-app-dev@6.3.2` `(6.3.1 => 6.3.2)`
- `electrode-react-webapp@3.3.3` `(3.3.2 => 3.3.3)`
- `ignite-core@1.1.8` `(1.1.7 => 1.1.8)`

### Lerna Updated

- `electrode-ignite@3.0.8` `(3.0.7 => 3.0.8)`

## Commits

- `packages/electrode-archetype-react-app[-dev]`

  - [patch] make dev admin key input case insensitive ([#1152](https://github.com/electrode-io/electrode/pull/1152)) [commit](http://github.com/electrode-io/electrode/commit/a3ce7a341f26a0506e48b709264febd602feb022)
  - [patch] detect unexpect server exit before start message received [commit](http://github.com/electrode-io/electrode/commit/e33cc24750b1d97dd42491225e68c3b78211e85e)
  - [patch] enable same controls for webpack dev server ([#1149](https://github.com/electrode-io/electrode/pull/1149)) [commit](http://github.com/electrode-io/electrode/commit/41668f1be751c72bc4ea510982f7fec89241c2d5)
  - [patch] always save stats to disk in webpack dev mode ([#1148](https://github.com/electrode-io/electrode/pull/1148)) [commit](http://github.com/electrode-io/electrode/commit/8eac8c814e0109e6e04ffe26d2baf6c6e8889a95)

- `packages/electrode-react-webapp`

  - [patch] use require to load module for token ([#1156](https://github.com/electrode-io/electrode/pull/1156)) [commit](http://github.com/electrode-io/electrode/commit/c0ea998a62759fc09b7f00221abea4973b25e279)
  - [patch] insert more informative token ids in rendered output with props ([#1150](https://github.com/electrode-io/electrode/pull/1150)) [commit](http://github.com/electrode-io/electrode/commit/1adbe96b7d07d19995dd7685cffb5cd8bec170bf)

- `packages/ignite-core`

  - [patch] use nix-clap [commit](http://github.com/electrode-io/electrode/commit/4bd2c54c4c1a976cc9e3421dfbb0f9f2aba476ef)

- `samples/universal-react-node`

  - [chore] update lockfile for sample [commit](http://github.com/electrode-io/electrode/commit/14dd37266632965b44b1404b818019cf5956cf88)

# 2/5/2019

- app archetype

  - fix to support custom jest config
  - fix dev admin to watch for app-setup only for app start

- generator

  - make ui config module an option param

## Packages

### Directly Updated

- `electrode-archetype-react-app@6.3.1` `(6.3.0 => 6.3.1)`
- `electrode-archetype-react-app-dev@6.3.1` `(6.3.0 => 6.3.1)`
- `generator-electrode@5.1.2` `(5.1.1 => 5.1.2)`

### Lerna Updated

- `electrode-ignite@3.0.7` `(3.0.6 => 3.0.7)`

## Commits

- `packages/electrode-archetype-react-app[-dev]`

  - [patch] read custom jest config ([#1145](https://github.com/electrode-io/electrode/pull/1145)) [commit](http://github.com/electrode-io/electrode/commit/557bda40de8e1c4d0ecb8b68482832f77148387b)
  - [patch] dev admin should watch for app-setup only for app start ([#1147](https://github.com/electrode-io/electrode/pull/1147)) [commit](http://github.com/electrode-io/electrode/commit/41c2e57037dd1cb3027f7ac0ba1468b0fa2ce50f)

- `packages/generator-electrode`

  - [patch] make ui config module a param ([#1146](https://github.com/electrode-io/electrode/pull/1146)) [commit](http://github.com/electrode-io/electrode/commit/95940bde0e0de2865d4928563587196d46752ffb)

# 2/4/2019

- added development admin console - allow controlling webpack dev server and app server without shutdown everything.

## Packages

- `electrode-archetype-react-app@6.3.0` `(6.2.2 => 6.3.0)`
- `electrode-archetype-react-app-dev@6.3.0` `(6.2.2 => 6.3.0)`
- `electrode-react-webapp@3.3.2` `(3.3.1 => 3.3.2)`

## Commits

- `packages/electrode-archetype-react-app[-dev]`

  - [patch][log] log errors for missing required env vars ([#1142](https://github.com/electrode-io/electrode/pull/1142)) [commit](http://github.com/electrode-io/electrode/commit/97e6dca09fe9dfe398147f13314a44da343ce579)
  - [patch][fix] re-enable HMR for webpack-dev-server ([#1141](https://github.com/electrode-io/electrode/pull/1141)) [commit](http://github.com/electrode-io/electrode/commit/095277e3979f91be7ea74a9b03cea0007017d858)
  - [minor] dev admin server ([#1144](https://github.com/electrode-io/electrode/pull/1144)) [commit](http://github.com/electrode-io/electrode/commit/e424803ebb3695567c71ad20f6dc3bb442187c64)

- `packages/electrode-react-webapp`

  - [patch] consolidate and fix content resolve for all frameworks ([#1143](https://github.com/electrode-io/electrode/pull/1143)) [commit](http://github.com/electrode-io/electrode/commit/f47eb270d4f259fb0c224ce388456011789f59fc)

# 1/31/2019

- fix koa app
- fix source map issue
- compile to commonjs in non prod mode to allow stub ES modules in test

## Packages

### Directly Updated

- `electrode-archetype-react-app@6.2.2` `(6.2.1 => 6.2.2)`
- `electrode-archetype-react-app-dev@6.2.2` `(6.2.1 => 6.2.2)`
- `electrode-react-webapp@3.3.1` `(3.3.0 => 3.3.1)`
- `generator-electrode@5.1.1` `(5.1.0 => 5.1.1)`

### Lerna Updated

- `electrode-ignite@3.0.6` `(3.0.5 => 3.0.6)`

## Commits

- `packages/electrode-archetype-react-app[-dev]`

  - [patch][fix] keep modules auto in prod mode ([#1138](https://github.com/electrode-io/electrode/pull/1138)) [commit](http://github.com/electrode-io/electrode/commit/2d73f850850c6cadff40530b859c9abe2dd75f98)
  - [patch][bug] fix source map issue ([#1137](https://github.com/electrode-io/electrode/pull/1137)) [commit](http://github.com/electrode-io/electrode/commit/44f04048f6d52aaa905fa2d1e358b094cefae59f)
  - [patch][fix] get koa app to work with latest archetype ([#1135](https://github.com/electrode-io/electrode/pull/1135)) [commit](http://github.com/electrode-io/electrode/commit/2ebd42119392064d4d33d34d0d28959c736f5038)

- `packages/electrode-react-webapp`

  - [patch] fix dep for koa-router [commit](http://github.com/electrode-io/electrode/commit/f2f24f5c815598acc09c966ba991e621b9e5b71d)
  - [patch][bug] fix express-app config.ui.demo issue ([#1136](https://github.com/electrode-io/electrode/pull/1136)) [commit](http://github.com/electrode-io/electrode/commit/595ffc4866f0b6b769454e01c922db9a092b21f5)
  - [patch][fix] get koa app to work with latest archetype ([#1135](https://github.com/electrode-io/electrode/pull/1135)) [commit](http://github.com/electrode-io/electrode/commit/2ebd42119392064d4d33d34d0d28959c736f5038)

- `packages/generator-electrode`

  - [patch][bug] fix express-app config.ui.demo issue ([#1136](https://github.com/electrode-io/electrode/pull/1136)) [commit](http://github.com/electrode-io/electrode/commit/595ffc4866f0b6b769454e01c922db9a092b21f5)
  - [patch][fix] get koa app to work with latest archetype ([#1135](https://github.com/electrode-io/electrode/pull/1135)) [commit](http://github.com/electrode-io/electrode/commit/2ebd42119392064d4d33d34d0d28959c736f5038)
  - [patch][chore] use .babelrc.js ([#1140](https://github.com/electrode-io/electrode/pull/1140)) [commit](http://github.com/electrode-io/electrode/commit/ca1d251f509f89e9cba8b2b68d05f6f8062a44e9)

- `samples/hapi-app`

  - [chore] update sample app files [commit](http://github.com/electrode-io/electrode/commit/7422008197a22e719b5eca9700a42faef16af9bc)

- `samples/universal-react-node`

  - [chore] update sample app lockfile [commit](http://github.com/electrode-io/electrode/commit/9e540f9e57a8e8d3e725006765bc777c3dfbdee6)

# 1/30/2019

- [patch][fix] explicitly set babel env modules config

## Packages

- `electrode-archetype-react-app@6.2.1` `(6.2.0 => 6.2.1)`
- `electrode-archetype-react-app-dev@6.2.1` `(6.2.0 => 6.2.1)`

## Commits

- `packages/electrode-archetype-react-app[-dev]`

  - add a simple dev dashboard [commit](http://github.com/electrode-io/electrode/commit/70d5b7b602c62d8d04858828bc74e2f735d80863)
  - [chore] use chalker to do terminal colors [commit](http://github.com/electrode-io/electrode/commit/3b3cf197a3e374f6c669168e3ac88ceddfbdb93b)
  - [patch][fix] explicitly set babel env modules config ([#1132](https://github.com/electrode-io/electrode/pull/1132)) [commit](http://github.com/electrode-io/electrode/commit/cdf466caaf2a4ba785ab9d0634c7a79ca5d9ff0b)

# 1/23/2019

- electrode-archetype-react-app

  - remove uglify and use webpack 4 built-in optimization
  - fix server watch for typescript
  - fix css module for production build
  - fix path separator for windows

- electrode-ui-config
  - add demo to generated sample app

## Packages

### Directly Updated

- `electrode-archetype-react-app@6.2.0` `(6.1.4 => 6.2.0)`
- `electrode-archetype-react-app-dev@6.2.0` `(6.1.4 => 6.2.0)`
- `electrode-react-webapp@3.3.0` `(3.2.3 => 3.3.0)`
- `electrode-ui-config@1.2.0` `(1.1.2 => 1.2.0)`
- `generator-electrode@5.1.0` `(5.0.3 => 5.1.0)`

### Lerna Updated

- `electrode-ignite@3.0.5` `(3.0.4 => 3.0.5)`
- `electrode-ui-logger@1.1.4` `(1.1.3 => 1.1.4)`

## Commits

- `packages/electrode-archetype-react-app[-dev]`

  - [patch][bug] ensures app mode dir always use / ([#1125](https://github.com/electrode-io/electrode/pull/1125)) [commit](http://github.com/electrode-io/electrode/commit/7108b4cb0365bb64eb292e98f708dffe5a66aadb)
  - fix: remove undeeded uglify partial [commit](http://github.com/electrode-io/electrode/commit/64a007016942b29548336fb2aa643e51518afa70)
  - [minor][bug] fix server watch when using typescript ([#1111](https://github.com/electrode-io/electrode/pull/1111)) [commit](http://github.com/electrode-io/electrode/commit/2d6e32ec6edc77cc89c08f46d5ef620d4dd4856d)
  - [patch][bug] set env for production build ([#1126](https://github.com/electrode-io/electrode/pull/1126)) [commit](http://github.com/electrode-io/electrode/commit/af28874dbfe3b70c890267263d142bbc651f9b3d)

- `packages/electrode-react-webapp`

  - [minor] add token to send ui config to window.\_config [commit](http://github.com/electrode-io/electrode/commit/14cb09a2b3b698ce2d3170179f6cdc3a2a404911)

- `packages/electrode-ui-config`

  - [minor] support hapi 17 ([#1119](https://github.com/electrode-io/electrode/pull/1119)) [commit](http://github.com/electrode-io/electrode/commit/4338d8c813f5a116d453d72645954260f05e92ad)

- `packages/generator-electrode`

  - [minor] add demo for electrode-ui-config [commit](http://github.com/electrode-io/electrode/commit/cea397d0077471e5b76f10a0717b2c26898eba8d)

- `samples/hapi-app`

  - add samples/hapi-app ([#1127](https://github.com/electrode-io/electrode/pull/1127)) [commit](http://github.com/electrode-io/electrode/commit/d1ce389c384e2382975e9fccc098462ea0c8edba)

- `MISC`

  - fix CI [commit](http://github.com/electrode-io/electrode/commit/22fd89f6c31bd4bbabb9f609b0015898043dc4db)
  - [ci][chore] add electrode-ui-config to local dep list [commit](http://github.com/electrode-io/electrode/commit/86ecd73af5a3a87d552990c531861306b657023d)
  - update CONTRIBUTING.md for sample start ([#1118](https://github.com/electrode-io/electrode/pull/1118)) [commit](http://github.com/electrode-io/electrode/commit/a33bf78a0e64df0e694be1c5fb5959d9c23cc69a)

# 1/10/2019

- fix component babel config to preserve ESM

## Packages

- `electrode-archetype-react-component@6.1.4` `(6.1.3 => 6.1.4)`
- `electrode-archetype-react-component-dev@6.1.4` `(6.1.3 => 6.1.4)`

## Commits

- `packages/electrode-archetype-react-component[-dev]`

  - [patch] allow component to be published w/o dist-min files [commit](http://github.com/electrode-io/electrode/commit/9afa43088566d48398295be25ff4e9fe503623c9)
  - [patch] fix component babel config to preserve ESM [commit](http://github.com/electrode-io/electrode/commit/b6b30b72f5af07192a2876680a5c004b7f526efb)

- `samples/demo-component`

  - use module field to point to ES6 module code [commit](http://github.com/electrode-io/electrode/commit/2119fb10ff4a121983ad1f388a664a1baa1afef5)
  - update samples auto gen files [commit](http://github.com/electrode-io/electrode/commit/aff8ead4b5a5816c3336735934650d204d4d9fe4)

- `samples/demo-tree-shaking`

  - test tree-shaking [commit](http://github.com/electrode-io/electrode/commit/ee590ca4ad9a90fb7f829f44dace05b93f5ac316)
  - update samples auto gen files [commit](http://github.com/electrode-io/electrode/commit/aff8ead4b5a5816c3336735934650d204d4d9fe4)

- `samples/stylus-sample`

  - update samples auto gen files [commit](http://github.com/electrode-io/electrode/commit/aff8ead4b5a5816c3336735934650d204d4d9fe4)

- `samples/universal-react-node`

  - update samples auto gen files [commit](http://github.com/electrode-io/electrode/commit/aff8ead4b5a5816c3336735934650d204d4d9fe4)

- `MISC`

  - build demo-component before test-tree-shaking [commit](http://github.com/electrode-io/electrode/commit/3d6b2a5580662e731177ec7a5769412436ccb527)

# 1/8/2019

- fix for express

## Packages

### Directly Updated

- `electrode-archetype-react-app@6.1.4` `(6.1.3 => 6.1.4)`
- `electrode-archetype-react-app-dev@6.1.4` `(6.1.3 => 6.1.4)`
- `generator-electrode@5.0.3` `(5.0.2 => 5.0.3)`

### Lerna Updated

- `electrode-ignite@3.0.4` `(3.0.3 => 3.0.4)`

## Commits

- `packages/electrode-archetype-react-app[-dev]`

  - [patch][bug] fix webpack-dev-express middleware setup [commit](http://github.com/electrode-io/electrode/commit/f5bbd9d9c70a681b96cd5a5eafde118eb5ad0853)

- `packages/generator-electrode`

  - fix express-server linting errors [commit](http://github.com/electrode-io/electrode/commit/7ddbb3b6b6a1ba3d37f22fc7cc39beadc205658f)

- `MISC`

  - test express app generator [commit](http://github.com/electrode-io/electrode/commit/e35f18c4dd6fef951040e679b90c7ddfca8cda3c)

# 1/7/2019

- Add ES6 module support for component to enable webpack treeshaking
- Add express dev middleware for app archetype

## Packages

- `electrode-archetype-react-app@6.1.3` `(6.1.2 => 6.1.3)`
- `electrode-archetype-react-app-dev@6.1.3` `(6.1.2 => 6.1.3)`
- `electrode-archetype-react-component@6.1.3` `(6.1.2 => 6.1.3)`
- `electrode-archetype-react-component-dev@6.1.3` `(6.1.2 => 6.1.3)`

## Commits

- `packages/electrode-archetype-react-app[-dev]`

  - add express dev middleware ([#1007](https://github.com/electrode-io/electrode/pull/1007)) [commit](http://github.com/electrode-io/electrode/commit/bff7946489d1b689d7d4416af5631b3121ff4b64)

- `packages/electrode-archetype-react-component[-dev]`

  - build components with ES6 module syntax intact ([#1022](https://github.com/electrode-io/electrode/pull/1022)) [commit](http://github.com/electrode-io/electrode/commit/8c2fec36fa3a97656875e8b3182b5d89d93c38d5)

- `samples/demo-component`

  - update demo-component to support ES6 modules [commit](http://github.com/electrode-io/electrode/commit/20a669a9fe4d762fd371e9ae0ce36ac2ce586562)

- `samples/demo-tree-shaking`

  - add sample app to demo webpack tree shaking using components [commit](http://github.com/electrode-io/electrode/commit/0b0a1f9fc0f9a517604594a7235960c260fdd8e0)

- `MISC`

  - changelog [commit](http://github.com/electrode-io/electrode/commit/3d4567437b7ba92cad7a832637b71a0e57f82a94)

# 1/7/2019

## Packages

- `electrode-archetype-react-app@6.1.2` `(6.1.1 => 6.1.2)`
- `electrode-archetype-react-app-dev@6.1.2` `(6.1.1 => 6.1.2)`

## Commits

- `packages/electrode-archetype-react-app[-dev]`

  - [patch][bug] put @babel/runtime in electrode-archetype-react-app ([#1108](https://github.com/electrode-io/electrode/pull/1108)) [commit](http://github.com/electrode-io/electrode/commit/070ed3ea7a18f8213688bbb043c99b1e003bcd6c)

# 1/3/2019

## Packages

- `electrode-react-webapp@3.2.3` `(3.2.2 => 3.2.3)`

## Commits

- `packages/electrode-react-webapp`

  - [patch][bug] account for basePath from config.ui for routes ([#1106](https://github.com/electrode-io/electrode/pull/1106)) [commit](http://github.com/electrode-io/electrode/commit/3bb4e019a09bbc87191da3bc5cef944ff1357829)

# 1/2/2019

## Packages

- `electrode-archetype-react-component@6.1.2` `(6.1.1 => 6.1.2)`
- `electrode-archetype-react-component-dev@6.1.2` `(6.1.1 => 6.1.2)`
- `electrode-react-webapp@3.2.2` `(3.2.1 => 3.2.2)`

## Commits

- `packages/electrode-archetype-react-component[-dev]`

  - [patch][bug] fix babelrc being overriden ([#1105](https://github.com/electrode-io/electrode/pull/1105)) [commit](http://github.com/electrode-io/electrode/commit/a13399588cb16475af4aac8786009e5f7f466b6e)

- `packages/electrode-react-webapp`

  - [patch] check for "false" on WEBPACK_DEV_HTTPS ([#1103](https://github.com/electrode-io/electrode/pull/1103)) [commit](http://github.com/electrode-io/electrode/commit/97b75f94c2bacd32cb748aed703cb59221f84a75)


# [01/12/2018 - 12/11/2018](./xchangelog//2018.md)
# [02/14/2017 - 11/20/2017](./xchangelog//2017.md)
