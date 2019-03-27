---
layout:     post
title:      "如何搭建自己的博客"
subtitle:   "搭建博客过程记录"
date:       2019-03-19 12:00:00
author:     "kyle"
header-img: "img/post-bg-dlam.jpg"
tags:
    - life
---

> “How to build a blog. ”

## 一 开始 
### 1 创建一个public repo
命名为 `<githubusername>.github.io`

### 2 拉取repo
`git clone https://github.com/uiiuiiuac/huxpro.github.io`

### 3 拷贝
将拉取的repo中的内容全部拷贝放入你自己的repo`<githubusername>.github.io`

### 4 修改基本信息
修改_config中的信息
```yaml
# Site settings
title: 窗外蟋蟀
SEOTitle: 窗外蟋蟀的博客 | Keysaim Blog
header-img: img/home-bg-hill.jpg
email: keysaim@gmail.com
description: "描述"
keyword: "窗外蟋蟀, keysaim"
url: "https://keysaim.github.io"
baseurl: ""
```

### 5 写博客
模仿_posts中的文档，开始写自己的博客。
可以将里面的原有的文章删除。

### 6 查看博客
通过网址`<githubusername>.github.io`查看博客

## 二 本地运行
安装ruby[官方教程](https://www.ruby-lang.org/en/downloads/)
- mac 安装ruby
```bash
rew install ruby
```
- 安装`github pages`
- 开启`jykell`本地服务
```bash
cd <githubusername>.github.io
jekyll serve --watch
```
默认情况下，该服务会侦听在本地4000的端口上，可以打开浏览器访问`http://127.0.0.1:4000`，这样就可以在本地查看自己的博文效果了。

## 三 总结
安装使用过程中遇到了一些问题，本地运行和网络访问都出现了不同的问题，但是基本的功能是可以使用的。bug准备在使用的过程中慢慢修复，之后再加上问题和解决过程。