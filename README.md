# node
学习node.js相关知识

 Node.js® 是一个免费、开源、跨平台的 JavaScript 运行时环境, 它让开发人员能够创建服务器 Web 应用、命令行工具和脚本。

## 1.安装相关环境

nvm,全名node.js [version](https://so.csdn.net/so/search?q=version&spm=1001.2101.3001.7020) management，顾名思义是一个nodejs的版本管理工具。通过它可以安装和切换不同版本的nodejs。下面列出下载、安装及使用方法。(python和anaconda的对比)

[mac安装nvm详细教程](https://blog.csdn.net/weixin_45324044/article/details/136781368)

```bash
nvm install node//下载node
# 安装一个特定的 Node.js 版本，例如 14.17.0
nvm install 14.17.0

# 切换到最新版本的 Node.js
nvm use node

# 切换到特定版本的 Node.js，例如 14.17.0
nvm use 14.17.0

nvm list
```

[mac环境下安装nvm以及环境变量配置](https://juejin.cn/post/6844904095292063752)

存在问题：npm一直无法下载，[解决方法](https://stackoverflow.com/questions/60037937/how-to-resolve-npm-proxy-issue-whilel-running-node-js-application)。

![image-20250103142612085](/Users/yexian/Desktop/myGithub/node/assets/image-20250103142612085.png)

## 2.基本语法

