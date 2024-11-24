## 项目简介

当前仓库为【22 级中医实训】的 uni-app 项目模板。

## 技术栈

- 前端框架：uni-app
- 状态管理：pinia
- 组件库：uni-ui

## 运行程序

1. 安装依赖

- npm 方式

```bash
npm i --registry=https://registry.npmmirror.com
```

- pnpm 方式

```
pnpm i --registry=https://registry.npmmirror.com
```

2. 运行程序(微信小程序)

```
npm run dev:mp-weixin
```

3. 微信开发者工具导入 /dist/dev/mp-weixin 目录

## 工程结构解析

├── .vscode # VS Code 插件 + 设置 + 配置文件
├── dist # 打包文件夹（可删除重新打包）
├── src # 源代码
│ ├── api # 所有请求
│ ├── components # 全局组件
│ ├── composables # 组合式函数
│ ├── pages # 主包页面
│ ├── index # 首页
│ ├── contribute # 投稿页
│ ├── my # 我的
│ └── login # 登录页
│ ├── service # 封装网络请求
│ ├── static # 存放应用引用的本地静态资源的目录
│ ├── images # 普通图片
│ └── tabs # tabBar 图片
│ ├── stores # 全局 pinia store
│ ├── modules # 模块
│ └── index.ts # store 入口
│ ├── styles # 全局样式
├── global.scss # 样式
│ └── fonts.scss # 字体图标
│ ├── utils # 全局方法
│ ├── App.vue # 入口页面
│ ├── main.js # Vue 初始化入口文件
│ ├── pages.json # 配置页面路由等页面类信息
│ ├── manifest.json # 配置 appid 等打包信息
│ └── uni.scss # uni-app 内置的常用样式变量
├── .editorconfig # editorconfig 配置
├── .eslintrc.cjs # eslint 配置
├── .prettierrc.cjs # prettier 配置
├── .gitignore # git 忽略文件
├── index.html # H5 端首页
├── package.json # package.json 依赖
└── vite.config.ts # vite 配置
