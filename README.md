# awesome-any
Less is more.

目录
- [Node.js](#nodejs)
- [Web](#web)
- [React](#react)
- [前端工程化](#前端工程化)
- [设计资源](#%E8%AE%BE%E8%AE%A1%E8%B5%84%E6%BA%90)
- [标准规范](#标准规范)
- [速查表](#速查表)
- [工具](#桌面工具)
- [参考](#参考)

## [Node.js](https://github.com/nodejs/node)

Node.js JavaScript runtime. https://nodejs.org/ ([Chinese](http://nodejs.cn/))

**脚手架**
- [nvm](https://github.com/creationix/nvm) Node Version Manager - Simple bash script to manage multiple active node.js versions
- [nodemon](https://github.com/remy/nodemon) Monitor for any changes in your node.js application and automatically restart the server - perfect for development http://nodemon.io/ 
- [ts-node](https://github.com/TypeStrong/ts-node) TypeScript execution and REPL for node.js 
- [tsdx](https://github.com/palmerhq/tsdx) Zero-config CLI for TypeScript package development
- [oclif](https://github.com/oclif/oclif) Node.js Open CLI Framework. https://oclif.io
- [semantic-release](https://github.com/semantic-release/semantic-release): Fully automated version management and package publishing https://semantic-release.gitbook.io

**日志**
- [log4js-node](https://github.com/log4js-node/log4js-node) A port of log4js to node.js

**配置**
- [dotenv](https://github.com/motdotla/dotenv) Loads environment variables from .env for nodejs projects. 
- [dotenv-expand](https://github.com/motdotla/dotenv-expand) Variable expansion for dotenv. Expand variables already on your machine for use in your .env file.
- [cosmiconfig](https://github.com/davidtheclark/cosmiconfig) Find and load configuration from a package.json property, rc file, or CommonJS module
- [env-cmd](https://github.com/toddbluhm/env-cmd) Setting the environment from a file

**浏览器**
- [jsdom](https://github.com/jsdom/jsdom) A JavaScript implementation of the WHATWG DOM and HTML standards, for use with node.js
- [puppeteer](https://github.com/GoogleChrome/puppeteer) Headless Chrome Node API https://pptr.dev 

**Git**
- [nodegit](https://github.com/nodegit/nodegit) Native Node bindings to Git. https://www.nodegit.org/
- [git-js](https://github.com/steveukx/git-js) A light weight interface for running git commands in any node.js application.
- [isomorphic-git](https://github.com/isomorphic-git/isomorphic-git) A pure JavaScript implementation of git for node and browsers! https://isomorphic-git.org/ (node & browser)

**编译器**
- [antlr4](https://github.com/antlr/antlr4) ANTLR (ANother Tool for Language Recognition) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. http://antlr.org 
- [antlr4ts](https://github.com/tunnelvisionlabs/antlr4ts) Optimized TypeScript target for ANTLR 4 
- [pegjs](https://github.com/pegjs/pegjs) PEG.js: Parser generator for JavaScript https://pegjs.org/ 
## 文档
- [jsdoc](https://github.com/jsdoc/jsdoc) An API documentation generator for JavaScript. https://jsdoc.app/ 
- [TypeDoc](https://github.com/TypeStrong/TypeDoc) Documentation generator for TypeScript projects. https://typedoc.org 
- [docusaurus](https://github.com/facebook/docusaurus) Easy to maintain open source documentation websites. https://docusaurus.io 
- [jekyll](https://github.com/jekyll/jekyll)  Jekyll is a blog-aware static site generator in Ruby https://jekyllrb.com

**杂项**
- [tapable](https://github.com/webpack/tapable) Just a little module for plugins.
- [pug](https://github.com/pugjs/pug) robust, elegant, feature rich template engine for Node.js - <https://pugjs.org> 
- [flexsearch](https://github.com/nextapps-de/flexsearch/) Next-Generation full text search library for Browser and Node.js (node & browser)
- [json-server](https://github.com/typicode/json-server) Get a full fake REST API with zero coding in less than 30 seconds  

**运维**
- [pm2](https://github.com/Unitech/pm2) Node.js Production Process Manager with a built-in Load Balancer. http://pm2.keymetrics.io 
- [nginx](https://nginx.org/en/docs/) is an HTTP and reverse proxy server, a mail proxy server, and a generic TCP/UDP proxy server.

## Web

**脚手架**
  - [parcel](https://github.com/parcel-bundler/parcel) Blazing fast, zero configuration web application bundler https://parceljs.org
  
**JS 库（Browser & Node.js）**
  - [lodash](https://github.com/lodash/lodash/) A modern JavaScript utility library delivering modularity, performance, & extras. https://lodash.com/
  - [observer-util](https://github.com/nx-js/observer-util) Transparent reactivity with 100% language coverage. Made with ❤️ and ES6 Proxies.
  - [compiler-util](https://github.com/nx-js/compiler-util) An NX utility, responsible for executing code in the context of an object.
  - [dayjs](https://github.com/iamkun/dayjs) Day.js 2KB immutable date library alternative to Moment.js with the same modern API 
  - [date-fns](https://github.com/date-fns/date-fns) Modern JavaScript date utility library  https://date-fns.org

**CSS 库**
  - [linaria](https://github.com/callstack/linaria) Zero-runtime CSS in JS library https://linaria.now.sh
  - [polished](https://github.com/styled-components/polished) A lightweight toolset for writing styles in JavaScript ✨ https://polished.js.org/
  - [bulma](https://github.com/jgthms/bulma) Modern CSS framework based on Flexbox https://bulma.io 
  - [bootstrap](https://github.com/twbs/bootstrap) The most popular HTML, CSS, and JavaScript framework for developing responsive, mobile first projects on the web. https://getbootstrap.com
  - [material design](https://material.io/develop/web/) Build beautiful, usable products using Material Components for the web

**网络**
  - [api-sharp](https://github.com/whinc/api-sharp) Customizable, configuration-based, cross-platform javascript HTTP client. 
  - [axios](https://github.com/axios/axios) Promise based HTTP client for the browser and node.js

**可视化**
- [echarts](https://github.com/apache/incubator-echarts) A powerful, interactive charting and visualization library for browser http://echarts.apache.org/
- [AntV](https://github.com/antvis) 是蚂蚁金服全新一代数据可视化解决方案 https://antv.alipay.com/zh-cn/index.html
  - [g2](https://github.com/antvis/g2) The Grammar of Graphics in JavaScript
  - [g6](https://github.com/antvis/g6) A Graph Visualization Framework in JavaScript
  - [f2](https://github.com/antvis/f2) An elegant, interactive and flexible charting library for mobile.
- [mermaid](https://github.com/knsv/mermaid) Generation of diagram and flowchart from text in a similar manner as markdown - http://knsv.github.io/mermaid/

**文本处理**
- [unified](https://github.com/unifiedjs/unified) friendly interface backed by an ecosystem of plugins built for creating and manipulating content https://unifiedjs.com
  - [remark](https://github.com/remarkjs/remark) Markdown processor powered by plugins part of the @unifiedjs collective https://remark.js.org
  - [rehype](https://github.com/rehypejs/rehype) HTML processor powered by plugins part of the @unifiedjs collective https://unifiedjs.com

**其他**
- [vanilla-router](https://github.com/Graidenix/vanilla-router) Vanilla Router for SPA sites
- [monaco-editor](https://github.com/microsoft/monaco-editor): A browser based code editor https://microsoft.github.io/monaco-editor/
- [perfect-scrollbar](https://github.com/mdbootstrap/perfect-scrollbar) Minimalistic but perfect custom scrollbar plugin
- [xterm.js](https://github.com/xtermjs/xterm.js) A terminal for the web https://xtermjs.org/
- [html2canvas](https://github.com/niklasvh/html2canvas) Screenshots with JavaScript https://html2canvas.hertzen.com/
- [stacktrace.js](https://github.com/stacktracejs/stacktrace.js) Generate, parse, and enhance JavaScript stack traces in all web browsers https://www.stacktracejs.com/ 
- [hanzi-writer](https://github.com/chanind/hanzi-writer) Chinese character stroke order animations and practice quizzes https://chanind.github.io/hanzi-writer 


## [React](https://github.com/facebook/react/)
A declarative, efficient, and flexible JavaScript library for building user interfaces https://zh-hans.reactjs.org

**脚手架**
- [create-react-app](https://github.com/facebook/create-react-app) Set up a modern web app by running one command. https://facebook.github.io/create-react-app/
- [customize-cra](https://github.com/arackaf/customize-cra) Override webpack configurations for create-react-app 2.0

**路由**
- [react-router](https://github.com/ReactTraining/react-router) Declarative routing for React https://reacttraining.com/react-router/

**样式**
- [styled-components](https://github.com/styled-components/styled-components) Visual primitives for the component age. https://styled-components.com 


**组件库**
- [ant-design](https://github.com/ant-design/ant-design) A UI Design Language and React UI library https://ant.design
  - [ant-design-dark-theme](https://github.com/ant-design/ant-design-dark-theme)  Dark theme variables of Ant Design https://ant.design/docs/react/customize-theme
  - [ant-motion](https://github.com/ant-design/ant-motion) Animate specification and components of Ant Design http://motion.ant.design
- [material-ui](https://github.com/mui-org/material-ui) React components that implement [Google's Material Design](https://www.google.com/design/spec/material-design/introduction.html). https://material-ui.com/

**状态管理**
- [redux](https://github.com/reduxjs/redux) Predictable state container for JavaScript apps http://redux.js.org
- [mobx](https://github.com/mobxjs/mobx) Simple, scalable state management. http://mobx.js.org
  - [mobx-react](https://github.com/mobxjs/mobx-react) React bindings for MobX
  - [mobx-react-lite](https://github.com/mobxjs/mobx-react-lite)  Lightweight React bindings for MobX based on React 16.8 and Hooks https://mobx-react.js.org
  - [mobx-state-tree](https://github.com/mobxjs/mobx-state-tree) Opinionated, transactional, MobX powered state container combining the best features of the immutable and mutable world for an optimal DX
- [constate](https://github.com/diegohaz/constate) Scalable state using React Hooks & Context

**工具库**
- [prop-types](https://github.com/facebook/prop-types) Runtime type checking for React props and similar objects
- [immer](https://github.com/immerjs/immer) Create the next immutable state by mutating the current one - https://immerjs.github.io/immer/

**编辑器**
- [draft-js](https://github.com/facebook/draft-js): A React framework for building text editors. https://draftjs.org/ 
- [react-monaco-editor](https://github.com/react-monaco-editor/react-monaco-editor) Monaco Editor for React.
- [GGEditor](https://github.com/gaoli/GGEditor) A visual graph editor based on G6 and React http://ggeditor.com/

**特殊组件**
- [react-markdown](https://github.com/rexxars/react-markdown) Render Markdown as React components https://rexxars.github.io/react-markdown/
- [react-split-pane](https://github.com/tomkp/react-split-pane) React split-pane component https://react-split-pane.now.sh
- [react-grid-layout](https://github.com/STRML/react-grid-layout) A draggable and resizable grid layout with responsive breakpoints, for React.
- [react-infinite-scroller](https://github.com/CassetteRocks/react-infinite-scroller) Infinite scroll component for React
- [react-custom-scrollbars](https://github.com/malte-wessel/react-custom-scrollbars) React scrollbars component https://malte-wessel.com/react-custom-scrollbars/

**Hooks**
- [react-use](https://github.com/streamich/react-use) Collection of essential React Hooks. http://streamich.github.io/react-use

## 前端工程化

**TypeScript**
- [TypeScript](https://github.com/microsoft/TypeScript) is a superset of JavaScript that compiles to clean JavaScript output. https://www.typescriptlang.org

**预处理器**
- [babel](https://github.com/babel/babel)  Babel is a compiler for writing next generation JavaScript. https://babeljs.io/
- [sass](https://github.com/sass/sass) Sass makes CSS fun! https://sass-lang.com
- [pug](https://github.com/pugjs/pug) robust, elegant, feature rich template engine. https://pugjs.org

**打包器**
- [webpack](https://github.com/webpack/webpack) A bundler for javascript and friends. https://webpack.js.org
- [rollup](https://github.com/rollup/rollup) Next-generation ES module bundler https://rollupjs.org
- [parcel](https://github.com/parcel-bundler/parcel) Blazing fast, zero configuration web application bundler https://parceljs.org

**代码质量**
- [prettier](https://github.com/prettier/prettier) Prettier is an opinionated code formatter. https://prettier.io
- [eslint](https://github.com/eslint/eslint) A fully pluggable tool for identifying and reporting on patterns in JavaScript https://eslint.org

**测试框架**
- [jest](https://github.com/facebook/jest) Delightful JavaScript Testing. https://jestjs.io 
- [storybook](https://github.com/storybookjs/storybook) UI component dev & test: React, Vue, Angular, React Native, Ember, Web Components & more! https://storybook.js.org 


**其他**
- [browserslist](https://github.com/browserslist/browserslist) Share target browsers between different front-end tools, like Autoprefixer, Stylelint and babel-preset-env https://twitter.com/browserslist

## 设计资源
- [ant-design-colors](https://github.com/ant-design/ant-design-colors) Color Palettes Calculator of Ant Design https://ant.design/docs/spec/colors
- [Iconfont](https://www.iconfont.cn/)
- [Font Awesome](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)

## 标准规范
- [estree](https://github.com/estree/estree) The ESTree Spec
- [ecma262](https://github.com/tc39/ecma262) Status, process, and documents for ECMA-262 https://tc39.es/ecma262/
- [JSON-RPC 2.0 Specification](https://www.jsonrpc.org/specification) JSON-RPC is a stateless, light-weight remote procedure call (RPC) protocol （[中文版](http://wiki.geekdream.com/Specification/json-rpc_2.0.html)）
- [language-server-protocol](https://github.com/microsoft/language-server-protocol) Defines a common protocol for language servers. https://microsoft.github.io/language-server-protocol/

## 速查表
- [Git](https://github.com/skywind3000/awesome-cheatsheets/blob/master/tools/git.txt)
- [Bash](https://github.com/skywind3000/awesome-cheatsheets/blob/master/languages/bash.sh)
- [Tmux](https://github.com/skywind3000/awesome-cheatsheets/blob/master/tools/tmux.txt)
- [Vim](https://github.com/skywind3000/awesome-cheatsheets/blob/master/editors/vim.txt)

## 桌面工具
- [carbon](https://github.com/carbon-app/carbon) Create and share beautiful images of your source code https://carbon.now.sh
- [source-code-pro](https://github.com/adobe-fonts/source-code-pro) Monospaced font family for user interface and coding environments
- [PicGo](https://github.com/Molunerfinn/PicGo) A simple & beautiful tool for pictures uploading built by electron-vue https://molunerfinn.com/PicGo/
- [Snipaste](https://zh.snipaste.com/index.html) 一个简单但强大的截图工具
- [artipub](https://github.com/crawlab-team/artipub) Article publishing platform that automatically distributes your articles to various media channels
- [ScreenToGif](https://github.com/NickeManarin/ScreenToGif) ScreenToGif allows you to record a selected area of your screen, edit and save it as a gif or video. http://www.screentogif.com
- [readme-md-generator](https://github.com/kefranabg/readme-md-generator) CLI that generates beautiful README.md files

## 参考
* [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs#command-line-utilities)
* [awesome-react](https://github.com/enaqx/awesome-react)
* [Open Source Awards](https://osawards.com/)
* [awesome-cheatsheets](https://github.com/skywind3000/awesome-cheatsheets)
* [antd-社区精选组件](https://ant.design/docs/react/recommendation-cn)
* [awesome-react-hooks](https://github.com/rehooks/awesome-react-hooks)
