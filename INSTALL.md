
## 开发人员首次拉取远程项目

$ git clone git@github.com:feng18/bwsg-weapp.git
$ cd bwsg-weapp
$ npm install
$ npm run dev

## 全新创建项目

$ npm install @wepy/cli -g # 全局安装 WePY 2.0 CLI 工具
$ wepy init standard myproj # 使用 standard 模板初始化项目
$ cd myproj # 进入到项目目录
$ npm install # 安装项目依赖包
$ npm run dev # 监听并且编译项目

(base) hscy sunny$wepy init standard bwsg-weapp
? Project name bwsg-weapp
? AppId touristappid
? Project description A WePY project
? Author Sunny Feng <sunny@jiandan.com>
? Use ESLint to lint your code? Yes
? Choose a state container Vuex

   wepy-cli · Generated "bwsg-weapp".

## 初始化仓库

(base) bwsg-weapp sunny$git init
(base) bwsg-weapp sunny$git remote add origin git@github.com:feng18/bwsg-weapp.git
(base) bwsg-weapp sunny$git add -A
(base) bwsg-weapp sunny$git commit -m "init wepy"
(base) bwsg-weapp sunny$git push -u origin master
