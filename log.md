# Node.js/ELEMENT/VUE/GIT/ESLint环境搭建注意事项
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
- GIT发布新的分支后，上传到服务器，需要指定分支名称。
> git push origin develop(develop为本地创建的分支名称)
4. ESLint配置
- 使用 NPM 安装 ESLint
> cnpm install eslint -g 
- ESLint在项目中初始化，进入项目目录，运行以下命令
> eslint --init
> 根据web应用程序更新eslint配置文件.eslintrc.js，
> 模板文件保存在个人文件夹中
- cnpm install 各种依赖包