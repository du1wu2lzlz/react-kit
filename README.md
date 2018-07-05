# react-kit
react脚手架

+ 打包工具： wepack 支持hot

+ 异步： redux-saga
+ 组件: antd-design
+ 检查：eslint-airbnb
+ 路由： react-router

+ 运行: 

  npm i  
  
  npm run start  
  
  默认地址：localhost:3030



结构: 
```

|--components
|
|        server.js           -- 接口处理文件
|        list                -- 列表目录
|                 image
|                 view.jsx   -- 列表页入口
|                 reducer.js
|                 action.js
|                 saga.js
|                 type.js
|                 style.css
|        edit                -- 编辑页面
|
|--lib
|--middleware
|--entry.jsx                 -- 页面入口 
|

```
