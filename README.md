# awesome-npm-packages

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

这个仓库主要是收集一些非常好用的 npm package，主要面向使用 Node 的开发者。欢迎 Star 或 Fork。如果你有任何想法，或者知道一些好用的 package，请猛戳 PR 或 Issues 一起参与完善。非常欢迎您的参与，请在参与之前阅读 [贡献指南](contributing.md) 以更好的协作。

[中文](README.md) | [English](README-en.md)

## 目录

- [工具库](#工具库)
- [数据 Mock](#数据-mock)
- [网络服务框架](#网络服务框架)
- [Express 中间件](#express-中间件)
- [Koa 中间件](#koa-中间件)
- [命令行工具](#命令行工具)
- [命令行开发辅助](#命令行开发辅助)

## 工具库

- [hamburgers](https://github.com/jonsuh/hamburgers) - 使用 CSS 制作的各种 hamburger 动画图标。
- [lodash](https://github.com/lodash/lodash) - 具有一致接口、模块化、高性能等特性的现代化 JavaScript 工具库。
- [underscore](https://github.com/jashkenas/underscore) - 跟 lodash 类似，提供了一系列有用的辅助函数。
- [delay](https://github.com/sindresorhus/delay) - 在一定的时间内延迟执行 Promise。
- [eslint-config-airbnb](https://github.com/airbnb/javascript) - Airbnb JavaScript 代码风格的 ESLint 配置文件。
- [http-proxy](https://github.com/nodejitsu/node-http-proxy) - 支持 websockets 的HTTP 代理库。
- [jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) - JsonWebToken 在 Node 中的实践方案。
- [bcryptjs](https://github.com/dcodeIO/bcrypt.js) - 更好的 bcrypt 解决方案。
- [md5-file](https://github.com/roryrjb/md5-file) - 让你更轻松的计算文件的 MD5。
- [markdown-it](https://github.com/markdown-it/markdown-it) - 快速、易扩展的 Markdown 解析器。
- [marked](https://github.com/chjj/marked) - 又一个全功能的 Markdown 解析器。
- [nconf](https://github.com/indexzero/nconf) - 通过解析配置文件、环境变量、命令行参数让你轻松进行配置数据分层处理。
- [node-forge](https://github.com/digitalbazaar/forge) - [TLS](https://en.wikipedia.org/wiki/Transport_Layer_Security) 和其他各种加密方式的原生实现。
- [pretty-bytes](https://github.com/sindresorhus/pretty-bytes) - 将字节转换成人类易读的字符串，例如：1337 → 1.34 kB。
- [qr-image](https://github.com/alexeyten/qr-image) - 二维码生成器。
- [supertest](https://github.com/visionmedia/supertest) - 用来测试 HTTP 服务的一款非常强大的测试工具。
- [socket.io](https://github.com/socketio/socket.io/) - 这可能是史上最强大的 socket 实现库了。
- [node-notifier](https://github.com/mikaelbr/node-notifier) - 跨平台的发送系统原生通知的工具。
- [validator](https://github.com/chriso/validator.js) - 字符串格式校验工具。
- [connect](https://github.com/senchalabs/connect) - 使用中间件机制的可扩展的 HTTP 服务框架。
- [passport](https://github.com/jaredhanson/passport) - 强大的用户身份验证中间件。

## 数据 Mock

- [faker](https://github.com/Marak/Faker.js) - 让你在 Node 端和浏览器轻松构建大量用户信息的模拟数据。
- [mock-fs](https://github.com/tschaub/mock-fs) - 通过复写 fs 原生模块在内存中达到 Mock 文件的目的。
- [mock-require](https://github.com/boblauer/mock-require) - 轻松、直观的 Mock 任何你想要操作的模块。

## 网络服务框架

- [express](https://github.com/expressjs/express) - 极简、灵活的 web 应用开发框架，提供了一系列强大的特性，帮助你创建各种Web 和移动设备应用。
- [koa](https://github.com/koajs/koa) - 由 express 原班人马打造的号称下一代的轻量级 web 应用开发框架。
- [Meteor](https://github.com/meteor/meteor) - 用来开发实时网页程序的前后端同构框架。

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

## Koa 中间件

## 命令行工具

- [yarn](https://github.com/yarnpkg/yarn) - 快速、可靠和安全的依赖管理工具。
- [puer](https://github.com/leeluolee/puer) - 具有 web 服务、自动重载、Mock 数据等多种功能的前端开发效率提升工具。
- [istanbul](https://github.com/gotwarlost/istanbul) - 测试代码覆盖率检测工具。
- [nrm](https://github.com/Pana/nrm) - 非常方便的 NPM 源管理工具。

## 命令行开发辅助

- [commander](https://github.com/tj/commander.js) - 开发命令行工具的完整解决方案。
- [chalk](https://github.com/chalk/chalk) - 让你的终端字符变得丰富多彩、五颜六色。
- [colors](https://github.com/Marak/colors.js) - 又一个给控制台中的字符添加颜色和样式的工具库。
- [chokidar](https://github.com/paulmillr/chokidar) - 更好的 fs.watch / fs.watchFile 替代方案。
- [glob](https://github.com/isaacs/node-glob) - 使用 shell 模式来匹配文件路径。
- [mkdirp](https://github.com/substack/node-mkdirp) - `mkdir -p` 命令的 Node 实现。
- [ora](https://github.com/sindresorhus/ora) - 非常方便的实现终端 loading 动画效果。
- [progress](https://github.com/visionmedia/node-progress) - 在终端实现的 ascii loading 效果，提供了丰富灵活的配置。
- [ssh2](https://github.com/mscdex/ssh2) - SSH2 的客户端和服务端实现方案。
- [yargs](https://github.com/yargs/yargs) - 轻松解析命令行参数。

## 贡献

非常欢迎您的参与，请在参与之前阅读 [贡献指南](contributing.md) 以更好的协作。

[⬆ 返回顶部](#awesome-npm-packages)
