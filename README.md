## 欢迎🎉🎉🎉🎉🎉

非常感谢你使用Aurora主题，当你看到这个页面的时候，说明你已经使用[Aurora脚手架](https://github.com/vuepress-aurora/theme-cli)搭建好博客了，在你配置博客之前，请先阅读该[文章](https://aurora.xcye.xyz/issue/)，对你的博客配置很有帮助，一定要读

### 原项目地址
https://github.com/vuepress-aurora/vuepress-theme-aurora



## 主题文档

主题文档地址为[Aurora docs](https://aurora.xcye.xyz/)


## **npm**常用命令

1. 本地启动博客

   ```sh
   npm run dev
   ```

2. 打包(`默认生成的静态文件在docs/.vuepress/dist内`)

   ```sh
   npm run build
   ```

3. 安装依赖

   ```sh
   npm install
   ```



## 博客配置

1. [所有配置项](https://aurora.xcye.xyz/home/config.html)
2. [首页配置](https://aurora.xcye.xyz/homeconfig.html)
3. [部署](https://aurora.xcye.xyz/home/deploy.html)
4. [插件](https://aurora.xcye.xyz/plugin/coze)
5. [Leancloud官网](https://console.leancloud.app/)


## 快速安装

### Node安装

运行环境需要依赖`node`，如果你未安装`node`，请先安装node，我安装的版本为`v14.17.3`

> 安装node可查看[Node 安装](https://aurora.xcye.xyz/node.html)

### 安装CLI

- npm

  ```sh
  npm i vuepress-theme-cli -g
  ```

- yarn

  ```sh
  yarn global vuepress-theme-cli
  ```



### 创建博客

待脚手架cli安装成功之后，在命令行处输入下面命令(`之后一直按Enter键`)

```sh
aurora blog-demo
```

> `blog-demo`是你的博客文件件名称，会自动创建以此名字命名的文件夹
>
> 当你输入`aurora blog-demo`命令之后，会需要你填写一下`description`和`logoText(首页logo文字)`，你可以随便填一下
>
> 如果提示下面错误，请看[这里](https://aurora.xcye.xyz/issue/cli-issue.md)
>
> ```sh 
> 'aurora' 不是内部或外部命令，也不是可运行的程序
> 或批处理文件。
> ```



> 这个过程大概几秒，取决于你的网速，待安装成功之后，你会发现在当前目录下，多了一个目录



不知道你有没有注意到上图红色框中的信息，当博客模板下载完成之后，你还需要根据提示三步，才能启动博客



> 这里举个例子:
> 假如你电脑没有安装`yarn`，那么需要执行带有`npm`的命令，对于`yarn`的命令，就不需要执行



待依赖安装成功之后，运行`npm run dev`，会出现一个地址，你只需要在浏览器中，输入这个地址，就可以看到默认页面了



恭喜你，到这里，你已经安装成功了，接下来便可以尽情书写博客和修改配置(`上图展示出来的效果是默认配置，你可以更改`)



为了更好的对主题进行配置，你可以直接复制我GitHub中的<a href="https://github.com/vuepress-aurora/vuepress-theme-aurora/blob/master/docs/.vuepress/config-copy.js" target="_blank">config.js</a>文件


