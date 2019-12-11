# 常用命令
- yarn build, 用来执行package.json里面的script->build
- npm install -g npx 全局安装
- yarn add xxx --dev 当前目录安装，并且更新package.json
- npx webpack 当前目录搜索webpack bin，并且运行

# 自动生成html
- yarn add html-webpack-plugin --dev
- plug-in 使用文档 https://github.com/jantimon/html-webpack-plugin
- 替换模板里的viewport 
  `<meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">`