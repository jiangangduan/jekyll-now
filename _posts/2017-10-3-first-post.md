---
layout: post
title: First post!
---

Follow instruction on [link](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/) to create this web site w/o local Jekyll installation.

* 直接fork [github project link](https://github.com/barryclark/jekyll-now)
* 本地不需要创建Jekyll的build的环境（其实这个也不一定好，但总的来说还是方便）
* 基本的修改包括：
  *  _config.yml
  * about.md
  * 上传自己的avatar
* On this [link](https://programminghistorian.org/lessons/building-static-sites-with-jekyll-github-pages), 有一些关于配置的描述.
* 碰到过的一些问题
  * build失败 - 可以到相应项目的setting页面看到build错误的信息
  * read more - 大概是在post的ｍｄ里面的第一个段落(通过多余一个空行来生成一个新的段落)会被显示在index页面上，后面的会落在read more
  * 添加新的post - cp一下post下面的md,修改日期即可

* TODO
  * Theme还是没有实验 [link](https://help.github.com/articles/creating-a-github-pages-site-with-the-jekyll-theme-chooser/)
  * 本地Jekyll没有实验
