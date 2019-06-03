---
layout: post
title: Post文件的配置
date: 2017-09-12 13:32:20 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: i-rest.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Holidays, Hawaii]
---

此处为文章摘要，方便读者了解文章大致内容


## 此处是文章正文内容

* 每篇文章的头部，必须有一个yaml文件头，用来设置一些元数据。

* 它用三根短划线"---"，标记开始和结束，里面每一行设置一种元数据。
* "layout:post"，表示该文章的模板使用_layouts目录下的post.html文件；
* "title:Post文件的配置"，表示该文章的标题是"Post文件的配置"，如果不设置这个值，默认使用嵌入文件名的标题，即"how i rest from work"。

在yaml文件头后面，就是文章的正式内容，里面可以使用模板变量。{{ page.title }}就是文件头中设置的"你好，世界"，{{ page.date }}则是嵌入文件名的日期（也可以在文件头重新定义date变量），"| date_to_string"表示将page.date变量转化成人类可读的格式。

![I and My friends]({{site.baseurl}}/assets/img/we-in-rest.jpg)

