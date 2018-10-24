# vue-cli-webpack4 单页应用初始化代码

### 开发（在项目根目录下）
```bash
    
    # 安装依赖
    npm install

    ## 若上述不行则采取下面命令
    npm install --registry=https://registry.npm.taobao.org

    # 本地开发 开启服务
    npm run dev     //运行后自动打开浏览器
```

### 发布
```bash
    # 构建生成环境
    npm run build
```


### 目录结构
```shell
├── build                      // 构建相关  
├── config                     // 配置相关
├── src                        // 源代码
│   ├── api                    // 所有请求
│   ├── assets                 // 主题、字体、样式等静态资源
│   ├── components             // 全局公用组件
│   ├── router                 // 路由
│   ├── store                  // 全局store管理
│   ├── utils                  // 全局公用方法
│   ├── views                  // 页面组件
│   ├── App.vue                // 入口页面
│   └── main.js                // 入口 加载组件 初始化等
├── static                     // 第三方不打包资源
├── .babelrc                   // babel-loader 配置
├── .editorconfig              // 项目编码规范配置
├── .gitignore                 // git 忽略项
├── .postcssrc.js              // css处理配置
├── index.html                 // html模板
├── package-lock.json          // 锁定安装包版本
└── package.json               // package.json

```
------------
