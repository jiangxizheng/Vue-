# vue-newBee项目
## 1. 项目初始化
1. 安装依赖  `yarn install` 
2. 启动项目  `yarn dev`
> 启动时出现 core.js报错  则重新删除node_modules包  执行 yarn add core-js

## 2. 更改项目
1. 更改`main.js`  设置elementUI为中文版
2. 更改`router.js` 配置左侧菜单栏  **左侧菜单栏根据路由配置表动态加载的**
  + 删除多余路由配置（除dashboard以外） 
  + 删除多余页面文件 【login、dashboard, 404.vue】
  