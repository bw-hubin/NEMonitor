# ELEMENT/VUE环境搭建注意事项
1. 模板框架搭建
> vue-cli 是vue.js的脚手架，用于自动生成vue.js模板工程的。
- 安装vue-cli：
> npm install -g vue-cli
- 使用vue-cli构建项目
> vue init webpack project-name  //创建一个基于webpack模板的名为project-name的项目
- 目前可用的模板包括
> browserify–全功能的Browserify + vueify，包括热加载，静态检测，单元测试。</br>
> browserify-simple–一个简易的Browserify + vueify，以便于快速开始。</br>
> webpack–全功能的Webpack + vueify，包括热加载，静态检测，单元测试。</br>
> webpack-simple–一个简易的Webpack + vueify，以便于快速开始。</br>
2. 安装element-ui
- 安装element-ui到项目
> cnpm i element-ui@next -D</br>
> cnpm install style-loader --save-dev</br>
> cnpm install css-loader --save-dev</br>
> cnpm install file-loader --save-dev</br>
3. GIT配置
- 初始化后无法发布到GIT服务器解决办法
> git remote add origin https://github.com/xuanhun/vscode.git</br>
> git pull origin master ----allow-unrelated-histories