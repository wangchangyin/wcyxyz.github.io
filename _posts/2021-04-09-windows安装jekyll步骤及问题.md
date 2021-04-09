---
layout:     post
iframe:     "http://huangxuan.me/js-module-7day/"
title:      jekyll搭建
subtitle:   jekyll搭建
date:       2021-04-09
author:     WangChangYin
header-img: img/post-bg-ios9-web.jpg
catalog: 	 true
tags:
    - jekyll搭建
---

# windows安装jekyll步骤及问题

#### 1.安装Ruby和DevKit

下载地址：https://rubyinstaller.org/downloads/

![QQ图片20210409171744](./image/QQ图片20210409171744.png)

#### 2.安装jekyll

```java
gem install jekyll
```

测试一下

```java
jekyll --version
```

新建项目

```
jekyll new myblog
```

#### 3.运行服务器

进入myblog

```
cd myblog

myblog>jekyll serve
```

