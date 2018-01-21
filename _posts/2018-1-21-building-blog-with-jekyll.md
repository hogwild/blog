---
layout: post
---
# Building blog with Jekyll
jekyll 可以理解为一个文件自动转换平台，能将 html或者markdown写的文件，转换成静态网页。
一般而言，jekyll框架下的网站结构主要包含一下几个目录：
- _layouts文件夹: 存放的是网页的布局，通常是html格式的文件
- _posts文件夹： 存放的是要发表在网站上的一些博客文章， 可以是html格式的文件，也可以是markdown写的文件
  - 每个文件必须有一个头部（head), 位于文件的开头，格式为：
    ```markdown
    ---
    layout: name of the format you would like to use
    title: the title you would like to give to the page
    ---
    ```
此外，还有一个 _config.yml文件，用来存放一些格式化的通用信息，比如，网站主人的名称，电子邮件等，以及一些网站的设置参数。

在 github page上，还得在根目录下存放一个index.html（或者 index.md）文件，作为整个网站的首页。

接下来简单讲一下 jekyll 的安装：
1. install ruby:
For Ubuntu, the installation is different to  other system.
  - rvm
2. install jekyll: 建议使用 bundle insall
