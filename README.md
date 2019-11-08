# awesome-f2e-libs

> 整理我平时关注的前端库。

## 打包工具

* [**webpack**](https://github.com/webpack/webpack) - 打包项目。
* [**rollup**](https://github.com/rollup/rollup) - 打包 npm 库。
* [**parcel**](https://github.com/parcel-bundler/parcel) - webpack 竞品，但发展前景不乐观，再观察一段时间。
* [**@pikapkg/pack**](https://github.com/pikapkg/pack) - 又一组件打包工具。
* [**systemjs**](https://github.com/systemjs/systemjs) - 针对一些特殊场景会比较有用，比如云 ide，支付宝小程序 IDE 等。
* [**microbundle**](https://github.com/developit/microbundle) - 基于 rollup，简化配置。
* [**bili**](https://github.com/egoist/bili) - 基于 rollup，同上。
* [**webpack-dev-server**](https://github.com/webpack/webpack-dev-server) - webpack 开发服务器。
* [**webpack-dev-middleware**](https://github.com/webpack/webpack-dev-middleware) - webpack 中间件。
* [**vue-cli**](https://github.com/vuejs/vue-cli) - vue 命令行工具。
* [**create-react-app**](https://github.com/facebook/create-react-app) - react 官方脚手架。
* [**webpack-merge**](https://github.com/survivejs/webpack-merge) - 合并 webpack 配置。
* [**webpack-chain**](https://github.com/neutrinojs/webpack-chain) - 通过 chain 风格 api 的方式修改 webpack 配置。
* [**prepack**](https://github.com/facebook/prepack) - 通过预先执行的方式优化打包结果。
* [**swc**](https://github.com/swc-project/swc) - 基于 rust 的语法转换器，babel 的竞争者。
* [**nathan/pax**](https://github.com/nathan/pax) - 基于 rust，据说是这个星球最快的 JavaScript 打包工具。
* [**pikapkg/web**](https://github.com/pikapkg/web) - 浏览器里跑 npm 依赖，面向现代浏览器。
* [**lebab/lebab**](https://github.com/lebab/lebab) - 把 es5 代码转成 es6，反向 babel。
* [**palmerhq/tsdx**](https://github.com/palmerhq/tsdx) - Zero-config CLI for TypeScript package development.

### webpack loader 和插件

* [**hard-source-webpack-plugin**](https://github.com/mzgoddard/hard-source-webpack-plugin) - 性能提升 70%，但有坑。
* [**svgr**](https://github.com/smooth-code/svgr) - svg 转 react 组件。
* [**postcss**](https://github.com/postcss/postcss) - CSS 界的 babel。
* [**autoprefixer**](https://github.com/postcss/autoprefixer) - 为 CSS 选择权自动加 prefix。
* [**cssnano**](https://github.com/cssnano/cssnano) - CSS 压缩，也有类 preset 的概念。
* [**mini-css-extract-plugin**](https://github.com/webpack-contrib/mini-css-extract-plugin) - 提取 CSS 为单独文件。
* [**webpackbar**](https://github.com/nuxt/webpackbar) - webpack 进度条。
* [**webpack-bundle-analyzer**](https://github.com/webpack-contrib/webpack-bundle-analyzer) - 构建产物占比分析。
* [**uglifyjs-webpack-plugin**](https://github.com/webpack-contrib/uglifyjs-webpack-plugin) - JS 压缩，产物为 ES5 语法。
* [**terser-webpack-plugin**](https://github.com/webpack-contrib/terser-webpack-plugin) - JS 压缩，产物为 ES6 语法。
* [**webpack-manifest-plugin**](https://github.com/danethurber/webpack-manifest-plugin) - 生成 manifest.json。
* [**copy-webpack-plugin**](https://github.com/webpack-contrib/copy-webpack-plugin) - 复制额外的文件到输出目录。
* [**case-sensitive-paths-webpack-plugin**](https://github.com/Urthen/case-sensitive-paths-webpack-plugin) - 大小写敏感检测，能规避一些问题，但构建时性能消耗较大。
* [**css-hot-loader**](https://github.com/shepherdwind/css-hot-loader) - CSS 热更新，搭配 mini-css-extract-plugin 使用。
* [**duplicate-package-checker-webpack-plugin**](https://github.com/darrenscerri/duplicate-package-checker-webpack-plugin) - 重复依赖检测。
* [**fork-ts-checker-webpack-plugin**](https://github.com/Realytics/fork-ts-checker-webpack-plugin) - ts 语法检测。
* [**speed-measure-webpack-plugin**](https://github.com/stephencookdev/speed-measure-webpack-plugin) - 统计 webpack 各阶段耗时。

## 包管理

* [**yarn**](https://github.com/yarnpkg/yarn) - 我用这个。
* [**npm**](https://github.com/npm/cli)
### npm 相关工具
* [**npm-check**](https://www.npmjs.com/package/npm-check) - 检查依赖包的版本，可以一键进行升级

## babel

* [**babel**](https://github.com/babel/babel)
* [**babel-plugin-rawest**](https://github.com/sokra/rawact) - React 的 DOM 直出方案。
* [**babel-plugin-macros**](https://github.com/kentcdodds/babel-plugin-macros) - 前端文件写 node 逻辑。
* [**babel-plugin-dynamic-import-node**](https://github.com/airbnb/babel-plugin-dynamic-import-node) - 有些场景下会需要禁用 `import()` 语法。
* [**babel-plugin-react-require**](https://github.com/vslinko/babel-plugin-react-require) - 自动为 jsx 语法加 react 引用。
* [**babel-plugin-transform-react-remove-prop-types**](https://github.com/oliviertassinari/babel-plugin-transform-react-remove-prop-types) - 删除 prop-types，生产环境用。
* [**promise-polyfill**](https://github.com/taylorhakes/promise-polyfill) - 轻量级的 promise 垫片实现
 -  
## 测试

* [**jest**](https://github.com/facebook/jest)
* [**ts-jest**](https://github.com/kulshekhar/ts-jest)
* [**enzyme**](https://github.com/airbnb/enzyme)
* [**jsdom**](https://github.com/jsdom/jsdom)
* [**puppeteer**](https://github.com/GoogleChrome/puppeteer)
* [**react-test-rerender**](https://github.com/facebook/react/tree/master/packages/react-test-renderer) - 官方出品。
* [**react-testing-library**](https://github.com/kentcdodds/react-testing-library) - kentcdodds 出品。

## 框架

* [**react**](https://github.com/facebook/react)
* [**vue**](https://github.com/vuejs/vue)
* [**next.js**](https://github.com/zeit/next.js)
* [**nuxt.js**](https://github.com/nuxt/nuxt.js)
* [**gastby**](https://github.com/gatsbyjs/gatsby)
* [**umi**](https://github.com/umijs/umi) - 蚂蚁金服的前端框架，[sorrycc](https://github.com/sorrycc)目前在维护。
* [**rekit**](https://github.com/rekit/rekit) - IDE and toolkit for building scalable web applications with React, Redux and React-router.
* [**choo**](https://github.com/choojs/choo) - dva 最初的 API 是参考这个实现的，已经不怎么发展了，再关注一段时间。
* [**taro**](https://github.com/NervJS/taro) - 用 React 写小程序，适配微信和支付宝等。
* [**after.js**](https://github.com/jaredpalmer/after.js)
* [**mint**](https://github.com/mint-lang/mint) - 提供了语言层方案的框架。
* [**quasar**](https://github.com/quasarframework/quasar) - 基于 vue，一套代码多处适用。

## react 相关库

* [**preact**](https://github.com/developit/preact) - 轻量级 React 实现。
* [**inferno**](https://github.com/infernojs/inferno) - 轻量级 React 实现。
* [**react-router**](https://github.com/ReactTraining/react-router) - React 路由方案。
* [**reach-router**](https://github.com/reach/router) - React 路由方案，较新，优势是可访问性。
* [**router5**](https://github.com/router5/router5) - 通用的路由方案。
* [**react-loadable**](https://github.com/jamiebuilds/react-loadable) - 按需加载 react 组件。
* [**ant-design**](https://github.com/ant-design/ant-design) - 蚂蚁金服的 React UI 库。
* [**material-ui**](https://github.com/mui-org/material-ui) - UI 库。
* [**react-intl**](https://github.com/yahoo/react-intl) - React 的国际化方案。
* [**react-dnd**](https://github.com/react-dnd/react-dnd) - 拖拽实现。
* [**react-helmet**](https://github.com/nfl/react-helmet) - 修改 html 的 header 内容。
* [**react-jsonschema-form**](https://github.com/mozilla-services/react-jsonschema-form) - A React component for building Web forms from JSON Schema.

## react hooks 相关

* [**react-use**](https://github.com/streamich/react-use)
* [**rehooks**](https://github.com/rehooks)

## vue 相关库

* [**vue-router**](https://github.com/vuejs/vue-router)
* [**vant**](https://github.com/youzan/vant) 有赞 - 移动端组件库
* [**nutui**](https://github.com/jdf2e/nutui) 京东出品
* [**cube-ui**](https://github.com/didi/cube-ui) 滴滴 - 基于 Vue 实现的精致移动端组件库
* [**mand-mobile**](https://github.com/didi/mand-mobile) 滴滴 - 面向金融场景的 Vue 移动端组件库
* [**mint-ui**](https://github.com/ElemeFE/mint-ui) 饿了么 - Vue 移动端组件库

## flutter 实例参考

* [**FlutterDouBan**](https://github.com/kaina404/FlutterDouBan)

## 工具类

* [**history**](https://github.com/ReactTraining/history)
* [**path-to-regexp**](https://github.com/pillarjs/path-to-regexp) - path 转正则，路由相关处理的底层库。
* [**lodash**](https://github.com/lodash/lodash) - 工具集合。
* [**fastclick**](https://github.com/ftlabs/fastclick)
* [**date-fns**](https://github.com/date-fns/date-fns) - 时间处理。
* [**dayjs**](https://github.com/iamkun/dayjs) - 时间处理，小巧
* [**print-js**](https://www.npmjs.com/package/print-js) - 打印。
* [**fpjs**](https://fingerprintjs.com/zh) - 浏览器指纹生成库
* [**cloud-utils**](https://www.npmjs.com/package/@liwb/cloud-utils) - 常用的工具函数库
* [**Recorder**](https://github.com/xiangyuecn/Recorder) - html5 js 录音 mp3 wav ogg webm amr 格式，支持pc和Android、ios部分浏览器、和Hybrid App（提供Android IOS App源码），微信也是支持的，提供H5版语音通话聊天示例
* [**bignumber.js**](https://github.com/MikeMcl/bignumber.js) -大量浮点数计算问题
* [**nanoid**](https://github.com/ai/nanoid/) -一个极小的 uuid 生成的 JS 库

## 数据流

* [**redux**](https://github.com/reduxjs/redux)
* [**immer**](https://github.com/mweststrate/immer)
* [**mobx**](https://github.com/mobxjs/mobx)
* [**unstated**](https://github.com/jamiebuilds/unstated)
* [**rxjs**](https://github.com/ReactiveX/rxjs)
* [**dva**](https://github.com/dvajs/dva) - [sorrycc](https://github.com/sorrycc)写的数据流，基于 redux。
* [**rematch**](https://github.com/rematch/rematch) - 基于 redux。
* [**vuex**](https://github.com/vuejs/vuex)
* [**ngrx**](https://github.com/ngrx/platform)

### redux 扩展

* [**react-redux**](https://github.com/reduxjs/react-redux) - 绑定 react 和 redux。
* [**redux-saga**](https://github.com/redux-saga/redux-saga)
* [**redux-persist**](https://github.com/rt2zz/redux-persist)
* [**redux-bundler**](https://github.com/henrikjoreteg/redux-bundler)
* [**redux-box**](https://github.com/anish000kumar/redux-box)

## 性能优化

* [**workbox**](https://github.com/GoogleChrome/workbox) - PWA 方案，Google 出品。
* [**critical**](https://github.com/addyosmani/critical) - 提取关键 CSS。

## 语言

* [**typescript**](https://github.com/Microsoft/TypeScript)
* [**flow**](https://github.com/facebook/flow)
* [**graphql**](https://github.com/graphql/graphql-js)

## 文档

* [**vuepress**](https://github.com/vuejs/vuepress)
* [**docz**](https://github.com/pedronauck/docz)
* [**storybook**](https://github.com/storybooks/storybook)
* [**mdx**](https://github.com/mdx-js/mdx) - jsx + markdown。

## 工程

* [**lerna**](https://github.com/lerna/lerna) - monorepo 管理。
* [**lerna-changelog**](https://github.com/lerna/lerna-changelog) - 为 lerna 项目自动生成 changelog。
* [**eslint**](https://github.com/eslint/eslint) - JS 风格约束。
* [**eslint-config-airbnb**](https://github.com/airbnb/javascript)
* [**xo**](https://github.com/xojs/xo) - 封装自 eslint。
* [**prettier**](https://github.com/prettier/prettier) - 更主观的风格自动修改。
* [**yeoman-generator**](https://github.com/yeoman/generator) - 脚手架工具。
* [**serve**](https://github.com/zeit/serve) - 本地静态服务器。
* [**servor**](https://github.com/lukejacksonn/servor) - 另一个静态服务器。
* [**budo**](https://github.com/mattdesl/budo) - 又一个静态服务器。
* [**np**](https://github.com/sindresorhus/np) - npm publish 辅助，自动 push、打 tag、升版本等。
* [**lint-staged**](https://github.com/okonet/lint-staged) - eslint 提速，只 lint 提交的代码。
* [**coveralls**](https://github.com/marketplace/coveralls) - 覆盖率。
* [**husky**](https://github.com/typicode/husky) - 添加 git hooks。
* [**cross-env**](https://github.com/kentcdodds/cross-env) - 跨平台的环境变量声明。
* [**projj**](https://github.com/popomore/projj) - 本地 git 项目管理，支持 github 和 gitlab。
* [**nvm**](https://github.com/creationix/nvm) - 管理 node 版本。
* [**concurrently**](https://github.com/kimmobrunfeldt/concurrently) - 在 npm scripts 里并行执行命令。
* [**@zeit/ncc**](https://github.com/zeit/ncc) - 打包为 npm 包为一个文件。
* [**npm-check**](https://github.com/dylang/npm-check) - 检测依赖升级情况，我会和 `yarn upgrade-interactive` 配合着用，主要用来检测冗余依赖。
* [**cpx**](https://github.com/mysticatea/cpx) - 复制，支持 glob，并且可以 watch。
* [**onchange**](https://github.com/Qard/onchange) - 监听文件变动然后做一些事。
* [**just**](https://github.com/Microsoft/just) - 微软出的任务管理器。
* [**tern**](https://github.com/ternjs/tern) - 代码分析器，为不少编辑器服务。

## 编辑器

* [**VSCode**](https://code.visualstudio.com/)
* [**IntelliJ IDEA**](https://www.jetbrains.com/idea/) - 我用这个。
* [**codesandbox**](https://codesandbox.io/)
* [**stackblitz**](https://stackblitz.com/)

## CloudIDE

* [**theia**](https://github.com/theia-ide/theia)
* [**che**](https://github.com/eclipse/che)
* [**codesandbox-client**](https://github.com/CompuIves/codesandbox-client)

## 字体

* [**FiraCode**](https://github.com/tonsky/FiraCode)
* [**Dank Mono**](https://dank.sh/)
* [**Operator Mono**](https://www.typography.com/blog/introducing-operator)

## css

* [**css modules**](https://github.com/css-modules/css-modules)
* [**emotion**](https://github.com/emotion-js/emotion)
* [**css 30seconds**](https://css.30secondsofcode.org/)
* [**css 30seconds 中文**](http://caibaojian.com/30-seconds-of-css/)


## 命令行

* [**yargs**](https://github.com/yargs/yargs) - 命令行入口套件。
* [**yargs-parser**](https://github.com/yargs/yargs-parser) - 命令行参数解析。
* [**chalk**](https://github.com/chalk/chalk) - 输出不同颜色。
* [**cheerio**](https://github.com/cheeriojs/cheerio) - 用类 jQuery 语法处理 HTML。
* [**chokidar**](https://github.com/paulmillr/chokidar) - 文件监听。
* [**clipboardy**](https://github.com/sindresorhus/clipboardy) - 复制文本到粘贴板。
* [**debug**](https://github.com/visionmedia/debug) - 打印调试信息。
* [**deprecate**](https://github.com/brianc/node-deprecate) - 给过期警告。
* [**glob**](https://github.com/isaacs/node-glob) - 文件查找。
* [**tiny-glob**](https://github.com/terkelg/tiny-glob) - 文件查找。
* [**signale**](https://github.com/klaussinani/signale) - 漂亮的日志打印。
* [**semver**](https://github.com/npm/node-semver) - semver 版本处理。
* [**update-notifier**](https://github.com/yeoman/update-notifier) - 更新提醒。
* [**rimraf**](https://github.com/isaacs/rimraf) - 删除文件。
* [**depd**](https://github.com/dougwilson/nodejs-depd) - 给出 deprecated 警告。
* [**execa**](https://github.com/sindresorhus/execa) - 比 child_process 好用，返回 Promise。
* [**ora**](https://github.com/sindresorhus/ora) - 控制命令行光标，显示 loading 等。
* [**inquirer**](https://github.com/SBoudrias/Inquirer.js) - 交互式命令接口，比如 prompt。
* [**enquirer**](https://github.com/enquirer/enquirer) - 同上，更 cool 一些。
* [**ajv**](https://github.com/epoberezkin/ajv) - 参数校验。
* [**ink**](https://github.com/vadimdemedes/ink) - 用 React 处理命令行输出。
* [**figures**](https://github.com/sindresorhus/figures) - ✔︎ 等特殊字符，做了 windows 兼容处理。
* [**ntl**](https://github.com/ruyadorno/ntl) - npm task list

## 请求处理

* [**whatwg-fetch**](https://github.com/github/fetch)
* [**got**](https://github.com/sindresorhus/got)
* [**axios**](https://github.com/axios/axios)
* [**request**](https://github.com/request/request)
* [**reqwest**](https://github.com/ded/reqwest)

## 压缩解压缩

* [**yazl**](https://www.npmjs.com/package/yazl) - zip 压缩。
* [**yauzl**](https://github.com/thejoshwolfe/yauzl) - zip 解压缩。
* [**tar-fs**](https://github.com/mafintosh/tar-fs) - tar 的压缩和解压缩。

## 语法解析

* [**esquery**](https://github.com/estools/esquery) - 语法树查询。

## 其他

* [**electron**](https://github.com/electron/electron)
* [**DeskGap**](https://github.com/patr0nus/DeskGap/) - 类 electron，由于不包含浏览器的部分，所以产物更小
* [**fx**](https://github.com/antonmedv/fx) - 交互式 JSON 查看。
* [**chrome-plugin-demo**](https://github.com/sxei/chrome-plugin-demo) - Chrome插件开发全攻略配套完整Demo
* [**mirror-config-china**](https://github.com/gucong3000/mirror-config-china) - 中国内地的Node.js相关镜像配置，提供模块安装速度
* [**zenflowchart**](https://www.zenflowchart.com/) - 简单好用的在线流程图工具
* [**bankcardinfo**](https://github.com/navyxie/bankcardinfo) - 根据银行卡卡号查询银行类型和卡类型

## 代码高亮
* [**highlightjs**](https://highlightjs.org/)
* [**syntaxhighlighter**](https://github.com/syntaxhighlighter/syntaxhighlighter)

## rtfs

- [**reactjs/rfcs**](https://github.com/reactjs/rfcs)
- [**eslint/rfcs**](https://github.com/eslint/rfcs)
- [**vuejs/rfcs**](https://github.com/vuejs/rfcs)
- [**yarnpkg/rfcs**](https://github.com/yarnpkg/rfcs)
- [**npm/rfcs**](https://github.com/npm/rfcs)
- [**gastbyjs/rfcs**](https://github.com/gatsbyjs/rfcs)
- [**nuxtjs/rfcs**](https://github.com/nuxt/rfcs)

## 跨终端
* [**taro**](https://nervjs.github.io/taro/) - 京东出品，多端统一开发框架，支持用 React 的开发方式编写一次代码，生成能运行在微信/百度/字节跳动/支付宝/QQ小程序、快应用、H5、React Native 等平台的应用
* [**chameleon**](https://github.com/didi/chameleon) - 滴滴出品，一套代码运行多端，一端所见即多端所见

## github 不错的组织
- [**ThoughtWorksInc**](https://github.com/ThoughtWorksInc)
- [**iuap-design**](https://github.com/iuap-design)
- [**ice-lab**](https://github.com/ice-lab)

## npm 中文
- [**npm.cn**] (https://www.npmjs.cn)

## 相关

- [awesome-tools](https://github.com/sorrycc/awesome-tools) - 我在用的工具。

