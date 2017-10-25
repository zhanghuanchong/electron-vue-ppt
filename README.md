title: 使用 Electron, ES6+, Vue, Element UI 和 RxDB 开发桌面应用
speaker: Hans Zhang
transition: slide3
theme: blue

[slide]
# 使用 Electron, ES6+, Vue, Element UI 和 RxDB 开发桌面应用
-- Hans Zhang

[slide]
# 技术选型
----
* 打包机项目 - 性能要求不高
* 开发效率优先
* Web 布局方便
* 调试方便
* 扩展/迁移方便
* 大杂烩
* 演示

[slide]
# 技术方案
---
* Electron
* ES6+
* Vue
* Element UI
* RxDB

[slide]

# Electron
## Github出品，Atom
http://electron.atom.io/
* 基于 Chromium + Note.js
* 自动更新
* 本地菜单和通知
* 错误报告
* 调试
* 生成安装包
* 跨平台

[slide]

# Electron
* 主进程
* 渲染进程
* 不同的V8分支
* 项目代码

[slide]
# Electron builder
----
https://www.electron.build/
* 多种格式的安装包
* 图标
* 自动更新
* 代码签名

[slide]
# node-printer
https://github.com/tojocky/node-printer
* electron-rebuild. package.json
* printDirect

[slide]
# node-escpos
https://github.com/song940/node-escpos/blob/master/commands.js
* 开钱箱
* 打印
* 切纸

[slide]
# ES6+
* http://es6.ruanyifeng.com/
* async, await
* Promise
* 参数的解构赋值
* npm vs. yarn

[slide]
# Vue
* https://github.com/SimulatedGREG/electron-vue
* https://cn.vuejs.org
* Webpack
* Electron + Vue
* Weex + Vue vs. React Native 

[slide]

## Vuex
https://vuex.vuejs.org/zh-cn/intro.html
* 状态管理, 借鉴 Redux, Flux
* State
* Getter
* Mutation
* Action
* Module
* 项目代码

[slide]
# Vue Router
https://router.vuejs.org/zh-cn/
* &lt;router-link :to="..." replace&gt;
* this.$router.replace

[slide]
# http://element.eleme.io/
* Layout
* Dialog
* Button
* Form
* MessageBox
* Notification
* Dropdown
* Tabs
* Breadcrumb
* 自定义 scss

[slide]
# RxDB
https://github.com/pubkey/rxdb
* Multiplatform support
* rxjs
* Hook
* 基于PouchDB，兼容 CouchDB, IBM Cloudant
* Replication
* JSON Schema
* Mango-Query
* Encryption

[slide]
# RxDB
* Import/Export
* Multi-Window
* ORM-capabilities
* Leveldown-adapters: indexedDB, websql, localStorage, mysql, memory... 
* Leader-Election
* Key-Compression
* 项目代码

[slide]
# Thank you
### Questions?