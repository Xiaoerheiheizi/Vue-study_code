# syl-app

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

<pre class="hljs lua"><code><span class="hljs-comment">-- build                     目录放的是构建脚本（包括构建时要用到的webpack 配置）</span>
<span class="hljs-comment">-- config                    配置脚本（vue项目启动时需要的配置，开发模式和生产模式）</span>
<span class="hljs-comment">-- node_modules              通过npm install 安装的项目依赖包</span>
<span class="hljs-comment">-- src                       项目源码目录</span>
     <span class="hljs-comment">-- assets                 项目模块资源文件包括：图片，css（会被webpack处理）</span>
     <span class="hljs-comment">-- components             项目相关的vue组件，便于重用</span>
     <span class="hljs-comment">-- router                 项目的路由定义</span>
        App.vue                页面入口文件
        main.js                项目的入口文件，挂在vue实例，加载路由，中间件等公共组件
<span class="hljs-comment">-- static                    页面需要引入的外部的纯静态资源(会直接拷贝到dist/static/里面)</span>
<span class="hljs-comment">-- test                      项目测试</span>
     <span class="hljs-comment">-- e2e                    模拟用户行为的测试</span>
     <span class="hljs-comment">-- unit                   单元测试</span>
.babelrc                     ES6语法编译配置,把我们ES2105的代码通过它编译成ES5的
.editorconfig                编辑器配置，定义代码格式
.eslintignore                忽略语法检查的目录文件配置
.eslintrc.js                 eslint的配置文件
.gitignore                   配置Git仓库的忽略项
.postcssrc.js                postcss的配置
index.html                   项目入口模板文件
<span class="hljs-built_in">package</span>.json                 项目基本信息，运行脚本和相关依赖
README.md                    项目介绍及开发指南
</code></pre>
