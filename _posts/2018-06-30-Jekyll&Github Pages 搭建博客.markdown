---
layout: post
title: Jekyll & Github 快速搭建博客
date: 2018-06-30 00:00:00 +0800
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: software.jpg # Add image post (optional)
tags: [Jekyll, Github, Blog, 个人博客] # add tag
---

一行代码都没写就搭好了自己的博客可以说是成就感十足了。是的没错，只需要一个模板一个github账号，一个域名里有自己id的博客就完成了，你值得拥有。

### 选择一个Jekyll模板

网址：jekyllthemes.org

这是jekyll的模板网站：

![jekylltheme]({{site.baseurl}}/assets/img/jekylltheme.png)

选择一个你喜欢的模板，点击进入可以看到预览和一些相关信息。点击**Homepage**进入该模板的github，将它fork到你的ghthub中。

### 利用Github Page搭建博客

fork之后，你的github库里就多了一个和你选择的模板同名的库。进入**Settings**修改库名，重点来了，==命名的规则有固定的格式，为username.github.io，其中username就是你的github用户名。== 这时候进入这个库的**Settings-Options-GitHub Pages**的部分，你可以看到打开博客的域名。如果运气好，点进去之后可以看到你刚才选择的模板。

![githubpage]({{site.baseurl}}/assets/img/gitpageaddr.png)

### 修改基础配置

但是也有可能打不开或者打开格式是错误的。这时候需要修改一些基本的配置。进入根目录下的**_comfig.yml**文件，这个文件是全局配置文件。修改一些基础的内容。
1.  title:  博客标题
2.  author: 博主姓名
3.  author-img: 可以上传一个头像
4.  url:    修改成你的域名

### 添加文章和图片

文章存储在根目录下的**_posts**文件夹下。注意每篇文章的标题命名格式也是固定的，为**2018-06-30-文章标题**的格式，前一部分是日期，后一部分是标题。文件是markdown格式，点开一篇示例文章后可以看到文章的顶部有一些固定的格式，只要照着这个进行修改就可以了。

如果不了解markdown的语法，可以看这篇文章简单入门：

https://www.jianshu.com/p/191d1e21f7ed

用到的图片存储在根目录下的**assets-imgs**文件夹中。也可以再创建子文件夹来方便整理结构，只需要注意引用图片时候的路径就好了。

