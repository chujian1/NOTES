### npx
```
npx是npm的一个包执行器，在npm的基础上，npx让npm中的一些命令行工具以及可执行文件在使用上变的更加简单
```
### npx和npm的区别
```
区别1：npm是永久存在，npx是临时安装
  npm
    npm i -g create-react-app // 全局安装了react的脚手架工具，这个包会存储在node目录下
    create-react-app react-test // 创建了react项目
  npx
    npx create-react-app react-test // create-react-app包被npx临时安装上，等到项目初始化结束后，就会被删除
```