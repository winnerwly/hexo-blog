---
title: 我来了 Hexo， 你好！
tags: "Testing"
---

很早以前就知道Hexo了，但是那时候对这种博客类的框架很不熟悉，一直不敢上手去弄自己的博客。

今天朋友发了一个别人写的博客给我看，看完，我想现在现在闲着也是闲着，所以就动手弄了起来。

<!-- more -->
> 这里记录一个我弄得过程吧

* 首页需要安装Hexo-cli

```Bash
$ npm install hexo-cli -g
```

Hexo-cli是让我们可以使用一些hexo相关的命令

* 初始化一个Hexo项目

```Bash
$ hexo init 项目名称
```

初始化项目的时候，命令很根据你输入的项目名称，自动在你命令所在的问价夹下生成一个由你项目名称命名的文件夹，会自动下载npm包，如果没有自动下载的话，自行 cd 到你的项目下 npm install || npm i

* 生成静态文件

```Bash
$ hexo g || hexo generate #生成文件
```

* 启动项目服务

```Bash
$ hexo s || hexo server #启动服务预览
```

现在可以访问 命令行提示的地址访问你的项目了

> 这边附上一些Hexo常用的命令及简写

```Bash
hexo n "我的博客" || hexo new "我的博客" # 创建新建文章
hexo p || hexo publish
hexo g || hexo generate # 生成
hexo s || hexo server # 启动服务预览
hexo d || hexo deploy # 部署
```
链接： 一个hexo常用命令笔记 [前往查看](https://blog.csdn.net/qq_26975307/article/details/62447489)

> 关于更换主题配色

* 我选的是鹅厂大牛的[yilid](https://github.com/litten/hexo-theme-yilia)的主题

```Bash
首页我们在我们项目目录下克隆主题的git项目

$ git clone https://github.com/litten/hexo-theme-yilia.git themes/yilia # 后面的themes/yilia表示克隆到根目录下的themes下的yilia

修改hexo根目录下的 _config.yml ： theme: yilia

生成静态文件 hexo g

运行当前项目 hexo s
```
* 这是就能看见一个全新的博客页面了

* 附： [yilia主题安装教程](https://github.com/litten/hexo-theme-yilia)

* 可能你会不太喜欢默认的主题，可以去 [Hexo主题中心](https://hexo.io/themes/)看看，或者去[Hexo知乎推荐](https://www.zhihu.com/question/24422335)瞅瞅，再者去[简书](https://www.jianshu.com/p/bcdbe7347c8d)

