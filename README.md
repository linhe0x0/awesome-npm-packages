# awesome-npm-packages

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

这个仓库主要是收集一些非常好用的 npm package，主要面向使用 Node 的开发者。欢迎 Star 或 Fork。如果你有任何想法，或者知道一些好用的 package，请猛戳 PR 或 Issues 一起参与完善。非常欢迎您的参与，请在参与之前阅读 [贡献指南](contributing.md) 以更好的协作。

[中文](README.md) | [English](README-en.md)

## 目录

- [工具库](#工具库)
- [网络服务框架](#网络服务框架)
- [Express 中间件](#express-中间件)
- [Koa 中间件](#koa-中间件)
- [测试工具](#测试工具)
- [命令行工具](#命令行工具)
- [命令行开发工具库](#命令行开发工具库)
- [JS 库](#前端-js-库)
- [React 周边](#react-周边)
- [Vue 周边](#vue-周边)
- [webpack 周边](#webpack-周边)
- [babel 周边](#babel-周边)
- [gulp 周边](#gulp-周边)
- [CSS 相关](#css-相关)

## 工具库

- [lodash](https://github.com/lodash/lodash) - 具有一致接口、模块化、高性能等特性的现代化 JavaScript 工具库。
- [underscore](https://github.com/jashkenas/underscore) - 跟 lodash 类似，提供了一系列有用的辅助函数。
- [delay](https://github.com/sindresorhus/delay) - 在一定的时间内延迟执行 Promise。
- [eslint](https://github.com/eslint/eslint) - 功能强大的 JavaScript 代码风格检查报告工具。
- [eslint-friendly-formatter](https://github.com/royriojas/eslint-friendly-formatter) - 以一种更加友好（指出文件和行号）的方式反馈 [eslint](https://github.com/eslint/eslint) 的错误。
- [eslint-config-airbnb](https://github.com/airbnb/javascript) - Airbnb JavaScript 代码风格的 ESLint 配置文件，包含 ECMAScript 6+ 和 React。
- [eslint-config-airbnb-base](https://github.com/airbnb/javascript) - Airbnb JavaScript 代码风格的 ESLint 配置文件，包含 ECMAScript 6+。
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - 支持 websockets 的 HTTP 代理库。
- [jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) - JsonWebToken 在 Node 中的实践方案。
- [bcryptjs](https://github.com/dcodeIO/bcrypt.js) - 更好的 bcrypt 解决方案。
- [md5-file](https://github.com/roryrjb/md5-file) - 让你更轻松的计算文件的 MD5。
- [markdown-it](https://github.com/markdown-it/markdown-it) - 快速、易扩展的 Markdown 解析器。
- [marked](https://github.com/chjj/marked) - 又一个全功能的 Markdown 解析器。
- [nconf](https://github.com/indexzero/nconf) - 通过解析配置文件、环境变量、命令行参数让你轻松进行配置数据分层处理。
- [node-forge](https://github.com/digitalbazaar/forge) - [TLS](https://en.wikipedia.org/wiki/Transport_Layer_Security) 和其他各种加密方式的原生实现。
- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - 将字节转换成人类易读的字符串，例如：1337 → 1.34 kB。
- [filesize](https://github.com/avoidwork/filesize.js) - 同样将文件大小格式的字符串转换成人类易读的字符串的工具。
- [qr-image](https://github.com/alexeyten/qr-image) - 二维码生成器。
- [socket.io](https://github.com/socketio/socket.io/) - 这可能是史上最强大的 socket 实现库了。
- [validator](https://github.com/chriso/validator.js) - 字符串格式校验工具。
- [connect](https://github.com/senchalabs/connect) - 使用中间件机制的可扩展的 HTTP 服务框架。
- [passport](https://github.com/jaredhanson/passport) - 强大的用户身份验证中间件。
- [dark-mode](https://github.com/sindresorhus/node-dark-mode) - 控制 macOS 的夜间模式状态。
- [run-jxa](https://github.com/sindresorhus/run-jxa) - 在 macOS 平台上通过 osascript 运行指定脚本。
- [js-yaml](https://github.com/nodeca/js-yaml) - 非常高效的 [YAML](http://en.wikipedia.org/wiki/YAML) 格式文件解析库。
- [csv](https://github.com/wdavidw/node-csv) - 简洁而又功能强大的 CSV 格式解析器。
- [moment](https://github.com/moment/moment) - 这可能是功能最强大的时间、日期处理库了。
- [date-fns](https://github.com/date-fns/date-fns) - 提供最全面、简单、一致的时间工具集，支持按需引入。
- [bluebird](https://github.com/petkaantonov/bluebird) - 高性能的 promise 全特性实现库。
- [sequelize](https://github.com/sequelize/sequelize) - 简单易用、支持多 SQL 语言的 ORM 实现。
- [opn](https://github.com/sindresorhus/opn) - 跨平台的打开指定文件或者网站的小工具。
- [rabbit.js](https://github.com/squaremo/rabbit.js) - 在 Node.JS 中使用 RabbitMQ 队列服务。
- [kue](https://github.com/Automattic/kue) - 基于 [redis](http://redis.io/) 实现的 消息队列服务。
- [request](https://github.com/request/request) - 简单、强大的 HTTP 请求库。
- [cheerio](https://github.com/cheeriojs/cheerio) - 快速、灵活、针对服务端实现的 jQuery 核心 API 工具。
- [path-exists](https://github.com/sindresorhus/path-exists) - 检测指定的路径是否存在。
- [conf](https://github.com/sindresorhus/conf) - 让你非常容易的对应用或模块做配置处理。
- [axios](https://github.com/mzabriskie/axios) - 能够同时用于浏览器端和 Node.js 端的基于 Promise 的 HTTP 客户端。
- [uuid](https://github.com/kelektiv/node-uuid) - 生成符合 RFC 规范的 UUID。
- [nanoid](https://github.com/ai/nanoid) - 轻量级、安全、URL 友好的唯一字符串生成器。
- [fs-extra](https://github.com/jprichardson/node-fs-extra) - 添加了很多原生 fs 模块中没有但实用的方法。
- [recursive-readdir](https://github.com/jergason/recursive-readdir) - 递归列出目录及其子目录中的所有文件，不会列出目录。
- [mkdirp](https://github.com/substack/node-mkdirp) - Shell 命令 `mkdir -p` 的实现。
- [del](https://github.com/sindresorhus/del) - 删除指定的文件或目录。
- [busboy](https://github.com/mscdex/busboy) - 响应 HTML 表单数据的流解析器。
- [mongoose](https://github.com/Automattic/mongoose) - 基于异步环境的 MongoDB 对象模型设计库。
- [semver](https://github.com/npm/node-semver) - semver 语义化版本号解析器。
- [debug](https://github.com/visionmedia/debug) - 轻量级的兼容 Node 和浏览器环境的 debug log 管理工具。
- [log4js](https://github.com/nomiddlename/log4js-node) - 功能强大的日志管理工具，灵活适应多个环境。
- [pino](https://github.com/pinojs/pino) - 拥有极高性能的日志分类管理的工具。
- [node-emoji](https://github.com/omnidan/node-emoji) - ✨ 在 Node.js 环境中使用 emoji 表情。
- [graceful-fs](https://github.com/isaacs/node-graceful-fs) - 文件系统模块的替代模块，优化了很多原生模块的不足。
- [lockfile](https://github.com/npm/lockfile) - 轻量级的添加文件锁的实用工具。
- [mime-types](https://github.com/jshttp/mime-types) - 根据文件类型判断其 content-type。
- [ajv](https://github.com/epoberezkin/ajv) - 性能极佳的 JSON Schema 验证工具。
- [config](https://github.com/lorenwest/node-config) - Node 应用的配置文件统一管理工具。
- [randomatic](https://github.com/jonschlinkert/randomatic) - 随机字符串生成器。
- [yauzl](https://github.com/thejoshwolfe/yauzl) - 对文件进行解压（unzip）的工具。
- [portfinder](https://github.com/indexzero/node-portfinder) - 端口冲突检查利器。

## 网络服务框架

- [express](https://github.com/expressjs/express) - 极简、灵活的 web 应用开发框架，提供了一系列强大的特性，帮助你创建各种Web 和移动设备应用。
- [koa](https://github.com/koajs/koa) - 由 express 原班人马打造的号称下一代的轻量级 web 应用开发框架。
- [Meteor](https://github.com/meteor/meteor) - 用来开发实时网页程序的前后端同构框架。
- [hapi](https://github.com/hapijs/hapi) - 简单易用、以配置为中心的 web 服务框架。
- [egg](https://github.com/eggjs/egg/) - 阿里开源的为企业级框架和应用而生的服务端框架。
- [micro](https://github.com/zeit/micro) - 轻量级的微服务框架。
- [restify](https://github.com/restify/node-restify) - 专注于构建 REST API 服务的轻量级服务端框架。
- [fastify](https://github.com/fastify/fastify) - 性能优先并开销极低的服务端框架。

## Express 中间件

- [compression](https://github.com/expressjs/compression) - 请求压缩中间件，支持 deflate、gzip 编码压缩。
- [body-parser](https://github.com/expressjs/body-parser) - 解析请求体的中间件。
- [express-session](https://github.com/expressjs/session) -  session 管理中间件。
- [cookie-parser](https://github.com/expressjs/cookie-parser) - 处理 Cookie 的中间件。
- [cookie-session](https://github.com/expressjs/cookie-session) - 基于 Cookie 实现 session 管理的中间件。
- [connect-timeout](https://github.com/expressjs/timeout) - 设置和管理请求超时时间的中间件。
- [csurf](https://github.com/expressjs/csurf) -  [CSRF](https://en.wikipedia.org/wiki/Cross-site_request_forgery) 中间件。
- [cors](https://github.com/expressjs/cors) - 用于启用 [CORS](http://en.wikipedia.org/wiki/Cross-origin_resource_sharing) 的中间件。
- [errorhandler](https://github.com/expressjs/errorhandler) - 用于开发环境处理错误信息的中间件。
- [morgan](https://github.com/expressjs/morgan) - Http 请求日志中间件。
- [response-time](https://github.com/expressjs/response-time) - 记录请求响应时间的中间件。
- [serve-favicon](https://github.com/expressjs/serve-favicon) - favicon 服务中间节。
- [serve-index](https://github.com/expressjs/serve-index) - 基于给定的路径渲染出目录列表。
- [serve-static](https://github.com/expressjs/serve-static) - 提供静态文件服务。
- [vhost](https://github.com/expressjs/vhost) - 很方便的域名处理中间节。
- [express-validator](https://github.com/ctavan/express-validator) - 依赖 validator 工具库实现的 express 验证中间件。
- [connect-redis](https://github.com/tj/connect-redis) - Redis session 存储中间件。
- [multer](https://github.com/expressjs/multer) - 响应 `multipart/form-data` 的中间件。

## Koa 中间件

- [koa-router](https://github.com/alexmingoia/koa-router) - Express 风格的路由处理中间件。
- [koa-static](https://github.com/koajs/static) - 静态文件服务中间件。
- [koa-static-cache](https://github.com/koajs/static-cache) - 静态文件缓存中间件。
- [koa-session](https://github.com/koajs/session) - 基于 cookie 的 session 中间件。
- [koa-favicon](https://github.com/koajs/favicon) - favicon 服务中间件。
- [koa-compress](https://github.com/koajs/compress) - 压缩中间件。
- [koa-csrf](https://github.com/koajs/csrf) - CSRF tokens 中间件。
- [koa-logger](https://github.com/koajs/logger) - 开发环境的日志记录中间件。
- [koa-react-view](koa-react-view) - React 服务端渲染中间件。
- [koa-redis](https://github.com/koajs/koa-redis) - 使用 Redis 持久化 session 的中间件。
- [koa-bodyparser](https://github.com/koajs/bodyparser) - 请求体内容解析中间件。
- [koa-ratelimit](https://github.com/koajs/ratelimit) -请求频率限制中间件。
- [koa-jwt](https://github.com/koajs/jwt) - JSON Web Tokens 验证中间件。
- [koa-multer](https://github.com/koa-modules/multer) - 响应 `multipart/form-data` 的中间件。
- [koa-locales](https://github.com/koajs/locales) - 实现多语言支持的中间件。
- [koa-markdown](https://github.com/koajs/koa-markdown) - 自动转化 Markdown 文件为 HTML 文件的中间件。

## 测试工具

- [mocha](https://github.com/mochajs/mocha) - 简单、灵活、强大的 Node.js 单元测试框架。
- [ava](https://github.com/avajs/ava) - 面向未来的 Javascript 单元测试框架。
- [supertest](https://github.com/visionmedia/supertest) - 专注测试 HTTP 服务的一款非常强大的测试工具。
- [istanbul](https://github.com/gotwarlost/istanbul) - 测试代码覆盖率检测工具。
- [nyc](https://github.com/istanbuljs/nyc) - 支持 [ava](https://github.com/avajs/ava) 的 [istanbul](https://github.com/gotwarlost/istanbul) 风格测试代码覆盖率检测工具。
- [faker](https://github.com/Marak/Faker.js) - 让你在 Node 端和浏览器轻松构建大量用户信息的模拟数据。
- [mock-fs](https://github.com/tschaub/mock-fs) - 通过复写 fs 原生模块在内存中达到 Mock 文件的目的。
- [mock-require](https://github.com/boblauer/mock-require) - 轻松、直观的 Mock 任何你想要操作的模块。
- [rewire](https://github.com/jhnns/rewire) - 对指定模块的私有成员进行单元测试。
- [chai](https://github.com/chaijs/chai) - 兼容所有测试框架的跨平台 BDD / TDD 风格断言库，支持 Node.js 和浏览器。
- [should](https://github.com/shouldjs/should.js) - BDD 风格的断言库。
- [expect.js](https://github.com/Automattic/expect.js) - 基于 [should](https://github.com/shouldjs/should.js) 的 BDD 风格断言库。
- [power-assert](https://github.com/power-assert-js/power-assert) - 没有记忆成本的断言库，大多数情况只需使用`assert()`一个方法即可。
- [tempfile](https://github.com/sindresorhus/tempfile) - 获取随机的临时文件路径。
- [temp-write](https://github.com/sindresorhus/temp-write) - 将字符串 / buffer / stream 写入随机的临时文件中。

## 命令行工具

- [npm](https://github.com/npm/npm) - Node.js 包管理工具。
- [yarn](https://github.com/yarnpkg/yarn) - 快速、可靠和安全的依赖管理工具。
- [puer](https://github.com/leeluolee/puer) - 具有 web 服务、自动重载、Mock 数据等多种功能的前端开发效率提升工具。
- [nrm](https://github.com/Pana/nrm) - 非常方便的 NPM 源管理工具。
- [gh-pages-deploy](https://github.com/meandavejustice/gh-pages-deploy) - 通过读取 package.json 里的配置自动发布内容到 gh-pages
- [decheck](https://github.com/egoist/decheck) - 使用命令行查看一个 npm 模块的依赖项。
- [coffee-script](https://github.com/jashkenas/coffeescript) - 一种采用优雅的语法并编译到 JavaScript 的小语种。
- [commitizen](https://github.com/commitizen/cz-cli) - 让你轻松写成符合社区建议的 commit 格式的交互式工具。
- [eslint](https://github.com/eslint/eslint) - Javascript 代码风格工具。
- [express-generator](https://github.com/expressjs/generator) - [Express](https://github.com/expressjs/express) 应用目录生成器。
- [koa-generator](https://github.com/17koa/koa-generator) - [Koa](https://github.com/koajs/koa) 应用目录生成器。
- [fecs](https://github.com/ecomfe/fecs) - 百度出品的前端代码风格工具。
- [font-spider](https://github.com/aui/font-spider) - 智能 WebFont 压缩工具，它能自动分析出页面使用的 WebFont 并进行按需压缩。
- [gifify](https://github.com/vvo/gifify) - 通过命令行将视频转换为 GIF 动态图片。
- [gitbook-cli](https://github.com/GitbookIO/gitbook-cli) - GitBook 的命令行工具。
- [gitmoji-cli](https://github.com/carloscuesta/gitmoji-cli) - 在 commit 信息中使用 emojis 的交互式工具。
- [hexo-cli](https://github.com/hexojs/hexo-cli) - 静态博客系统 Hexo 的命令行工具。
- [ionic](https://github.com/driftyco/ionic-cli) - [Ionic](http://ionicframework.com/) 的命令行工具。
- [mjml](https://github.com/mjmlio/mjml) - 轻松创建响应式邮件的命令行工具。
- [ngrok](https://github.com/bubenshchykov/ngrok) - ngrok 2 的 Node 版。
- [node-inspector](https://github.com/node-inspector/node-inspector) - 基于 Blink 开发者工具的 Node.js 应用调试器。
- [nodemon](https://github.com/remy/nodemon) - 开发阶段的应用热重载工具。
- [nodeppt](https://github.com/ksky521/nodePPT) - 功能强大的网页版演示库。
- [npms-cli](https://github.com/npms-io/npms-cli) - 命令行版的 npm package 搜索器。
- [placemat-cli](https://github.com/sqrthree/placemat) - 开发阶段获取随机图片进行网站占位。
- [pm2](https://github.com/Unitech/pm2) - 强大的负载均衡和进程管理工具。
- [slush](https://github.com/slushjs/slush) - 基于流的应用脚手架生成器。
- [tldr](https://github.com/tldr-pages/tldr-node-client) - [tldr](https://github.com/tldr-pages/tldr) 的命令行工具。
- [trash-cli](https://github.com/sindresorhus/trash-cli) - 移动文件至垃圾桶中，安心的删除文件。
- [vue-cli](https://github.com/vuejs/vue-cli) - Vue 项目脚手架。
- [lerna](https://github.com/lerna/lerna) - 同时管理多个包的 Javascript 项目管理工具。
- [serve](https://github.com/zeit/serve) - 用于开发阶段的本地静态文件服务工具。
- [json-server](https://github.com/typicode/json-server) - 零配置构建全能 REST API 风格的数据 Mock 服务器。

## 命令行开发工具库

- [commander](https://github.com/tj/commander.js) - 开发命令行工具的完整解决方案。
- [caporal](https://github.com/mattallty/Caporal.js) - 特性全面的开发命令行工具框架。
- [yargs](https://github.com/yargs/yargs) - 轻松解析命令行参数。
- [args](https://github.com/leo/args) - 开发命令行工具一个轻量级解决方案。
- [chalk](https://github.com/chalk/chalk) - 让你的终端字符变得丰富多彩、五颜六色。
- [colors](https://github.com/Marak/colors.js) - 又一个给控制台中的字符添加颜色和样式的工具库。
- [chokidar](https://github.com/paulmillr/chokidar) - 更好的 fs.watch / fs.watchFile 替代方案。
- [glob](https://github.com/isaacs/node-glob) - 使用 shell 模式来匹配文件路径。
- [mkdirp](https://github.com/substack/node-mkdirp) - `mkdir -p` 命令的 Node 实现。
- [ora](https://github.com/sindresorhus/ora) - 非常方便的实现终端 loading 动画效果。
- [progress](https://github.com/visionmedia/node-progress) - 在终端实现的 ascii loading 效果，提供了丰富灵活的配置。
- [ssh2](https://github.com/mscdex/ssh2) - SSH2 的客户端和服务端实现方案。
- [cliparoo](https://github.com/tj/node-cliparoo) - 复制指定字符串到系统剪贴板。
- [clipboardy](https://github.com/sindresorhus/clipboardy) - 提供跨平台级的剪贴板操作支持。
- [inquirer](https://github.com/sboudrias/Inquirer.js) - 提供了常见的几种交互式式命令行形式。
- [execa](https://github.com/sindresorhus/execa) - 更好用的 `child_process` 替代方案。
- [node-notifier](https://github.com/mikaelbr/node-notifier) - 跨平台的发送系统原生通知的工具。
- [quick-local-ip](https://github.com/aloksguha/myip) - 快速获取本机 ip 的小工具。
- [ip](https://github.com/indutny/node-ip) - 提供了一些实用的 IP 相关的方法。可以获取 IP 地址、比较 IP地址和验证 IP 地址等。
- [update-notifier](https://github.com/yeoman/update-notifier) - 以非侵入性的方式检查您的包是否需要更新并自动通知用户。
- [path-type](https://github.com/sindresorhus/path-type) - 检测指定的路径是否是文件、目录的工具库。
- [boxen](https://github.com/sindresorhus/boxen) - 在终端中创建出盒子（矩形）。
- [dargs](https://github.com/sindresorhus/dargs) - 将对象反向序列化为命令行参数形式的数组。
- [detect-port](https://github.com/node-modules/detect-port) - 端口检测器。

## 前端 JS 库

- [rxjs](https://github.com/ReactiveX/RxJS) - 大名鼎鼎的 Reactive 反应式编程的 JS 实现。
- [clipboard.js](https://github.com/zenorocha/clipboard.js) - 这可能是最好用的复制到剪贴板的工具库了。
- [g2](https://github.com/antvis/g2) - 蚂蚁金服出品的数据可视化库。

## React 周边

- [react](https://github.com/facebook/react) - Facebook 开发的大名鼎鼎的构建用户界面的轻量级框架。
- [react-dom](https://github.com/facebook/react) - Facebook 开发的大名鼎鼎的构建用户界面的轻量级框架 React 的 DOM 端。
- [redux](https://github.com/reactjs/redux) - 可预测的 JavaScript 应用程序的状态管理容器。
- [react-redux](https://github.com/reactjs/react-redux) - [Redux](https://github.com/reactjs/redux) 官方实现的绑定至 React 库。
- [react-router-dom](https://github.com/reacttraining/react-router) - 为 [react](https://github.com/facebook/react) 而生的声明式路由库。
- [react-router-config](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-config) - React Router 的静态路由配置助手。
- [react-router-redux](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-redux) - 将你的应用状态和路由保持同步。
- [redux-observable](https://github.com/redux-observable/redux-observable) - 在 [redux](https://github.com/reactjs/redux) 中使用 RxJS 的中间件。

## Vue 周边

- [vuetify](https://github.com/vuetifyjs/vuetify) - Material 设计风格的 UI 组件库。

## webpack 周边

- [webpack](https://github.com/webpack/webpack) - 目前为止最强大的 JS 模块加载器。
- [copy-webpack-plugin](https://github.com/kevlened/copy-webpack-plugin) - 在 [webpack](https://github.com/webpack/webpack) 中执行复制文件和文件夹的任务。
- [css-loader](https://github.com/webpack-contrib/css-loader) - 为 [webpack](https://github.com/webpack/webpack) 服务的 CSS 加载器。
- [eslint-loader](https://github.com/MoOx/eslint-loader) - 为 [webpack](https://github.com/webpack/webpack) 服务的 eslint 加载器。
- [extract-text-webpack-plugin](https://github.com/webpack-contrib/extract-text-webpack-plugin) - 从文件中提取特定的内容。
- [file-loader](https://github.com/webpack-contrib/file-loader) - 为 [webpack](https://github.com/webpack/webpack) 服务的文件加载器。
- [friendly-errors-webpack-plugin](https://github.com/geowarin/friendly-errors-webpack-plugin) - 非常好用的改善 [webpack](https://github.com/webpack/webpack) 的错误提醒插件。
- [html-webpack-plugin](https://github.com/jantimon/html-webpack-plugin) - 自动创建 HTMl 文件供 [webpack](https://github.com/webpack/webpack) 打包使用。
- [optimize-css-assets-webpack-plugin](https://github.com/NMFR/optimize-css-assets-webpack-plugin) - CSS 静态资源压缩、最小化的插件。
- [pug-loader](https://github.com/pugjs/pug-loader) - 为 [webpack](https://github.com/webpack/webpack) 服务的模板引擎 pug 加载器。
- [react-hot-loader](https://github.com/gaearon/react-hot-loader) - React 组件热重载插件。
- [sass-loader](https://github.com/webpack-contrib/sass-loader) - 为 [webpack](https://github.com/webpack/webpack) 服务的 Sass 加载器。
- [less-loader](https://github.com/webpack-contrib/less-loader) - 为 [webpack](https://github.com/webpack/webpack) 服务的 Less 加载器。
- [style-loader](https://github.com/webpack-contrib/style-loader) - 将 CSS 样式添加至 style 标签中。
- [url-loader](https://github.com/webpack-contrib/url-loader) - 为 [webpack](https://github.com/webpack/webpack) 服务的静态资源 URL 服务加载器。
- [webpack-bundle-analyzer](https://github.com/th0r/webpack-bundle-analyzer) - 非常实用的 [webpack](https://github.com/webpack/webpack) 构建分析器。
- [webpack-dev-middleware](https://github.com/webpack/webpack-dev-middleware) - [webpack](https://github.com/webpack/webpack) 开发服务器中间间。
- [webpack-hot-middleware](https://github.com/glenjamin/webpack-hot-middleware) - [webpack](https://github.com/webpack/webpack) 热重载中间间。
- [webpack-merge](https://github.com/survivejs/webpack-merge) - 合并多个 [webpack](https://github.com/webpack/webpack) 配置参数。

## babel 周边

- [babel-core](https://github.com/babel/babel/tree/master/packages/babel-core) - babel 核心实现。
- [babel-loader](https://github.com/babel/babel-loader) - 为 [webpack](https://github.com/webpack/webpack) 服务的 babel 加载器。
- [babel-preset-es2015](https://github.com/babel/babel/tree/master/packages/babel-preset-es2015) - 编译 ES2015 的 babel 插件。
- [babel-preset-react](https://github.com/babel/babel/tree/master/packages/babel-preset-react) - 编译 React 的 babel 插件。
- [babel-preset-stage-1](https://github.com/babel/babel/tree/master/packages/babel-preset-stage-1) - 编译 ES stage 1 阶段的 babel 插件。
- [babel-preset-stage-2](https://github.com/babel/babel/tree/master/packages/babel-preset-stage-2) - 编译 ES stage 2 阶段的 babel 插件。
- [babel-preset-stage-3](https://github.com/babel/babel/tree/master/packages/babel-preset-stage-3) - 编译 ES stage 3 阶段的 babel 插件。

## gulp 周边

- [gulp](https://github.com/gulpjs/gulp) - 基于流的前端自动化构建工具。
- [gulp-changed](https://github.com/sindresorhus/gulp-changed) - 通过比较源文件和生成文件来实现 Gulp 的增量编译。
- [gulp-cached](https://github.com/contra/gulp-cached) - 通过在内存中缓存文件和内容来实现 Gulp 的增量编译。
- [gulp-remember](https://github.com/ahaurw01/gulp-remember) - 同样在内存中缓存所有文件来实现 Gulp 的增量编译，和 gulp-cached 搭配使用效果更好。
- [gulp-newer](https://github.com/tschaub/gulp-newer) - 同样通过比较源文件和生成文件来实现 Gulp 的增量编译。
- [gulp-gh-pages](https://github.com/shinnn/gulp-gh-pages) - 使用 Gulp 自动部署内容到 GitHub pages。
- [gulp-yaml](https://github.com/crissdev/gulp-yaml) - 将 [YAML](http://en.wikipedia.org/wiki/YAML) 文件转化为 [JSON](https://en.wikipedia.org/wiki/JSON) 的工具。
- [gulp-imagemin](https://github.com/sindresorhus/gulp-imagemin) - 在 Gulp 中自动进行图片压缩。
- [gulp-imageisux](https://github.com/targetkiller/gulp-imageisux) - [智图](http://zhitu.isux.us/) 的 Gulp 插件。
- [gulp-lazyimagecss](https://github.com/weixin/gulp-lazyimagecss) - 高效地书写 CSS 必备，自动生成图片CSS属性，如：width & height 等。
- [gulp-svg-inline](https://github.com/weixin/gulp-svg-inline) - 内联 svg 文件到 CSS。
- [gulp-svg-symbols](https://github.com/Hiswe/gulp-svg-symbols) - 转化 svg 为 symbols。
- [gulp-cssnano](https://github.com/ben-eb/gulp-cssnano) - 在 Gulp 中使用 cssnano 进行 CSS 压缩。
- [gulp-postcss](https://github.com/postcss/gulp-postcss) - 在 Gulp 中使用 [PostCSS](https://github.com/postcss/postcss)。
- [gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer) - 在 Gulp 中使用 Autoprefixer 进行 CSS 前缀自动补全。
- [gulp-babel](https://github.com/babel/gulp-babel) - [Babel](https://babeljs.io/) 的 Gulp 插件。
- [gulp-if](https://github.com/robrich/gulp-if) - 有条件的运行任务。
- [gulp-uglify](https://github.com/terinjokes/gulp-uglify) - 使用 UglifyJS2 来压缩 JS 文件。
- [gulp-less](https://github.com/plus3network/gulp-less) - LESS 编译插件。
- [gulp-rename](https://github.com/hparra/gulp-rename) - 让你很容易的重命名一些文件。
- [gulp-replace](https://github.com/lazd/gulp-replace) - 一个字符串替换

## CSS 相关

- [hamburgers](https://github.com/jonsuh/hamburgers) - 使用 CSS 制作的各种 hamburger 动画图标。
