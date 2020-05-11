---
title: hexo 安装方法
date: 2020-05-09 20:45:33
tags:
description: 摘要111
typora-copy-images-to: ..\images
typora-root-url: images
---

###### 安装hexo 

```bash
$ npm install -g hexo-cli #安装hexo到全局 -g: 全局安装
```
###### 生成hexo
```bash
$ hexo init #在当前目录生成hexo配置
```
###### 下载主题
```bash
$ git clone https://github.com/theme-next/hexo-theme-next .\themes\next
#下载next主题
```
###### 启用next主题
```yaml
# Extensions
theme: next  #在此处更改主题
```
###### 部署设置
```yaml
deploy:
  type: 'git' #使用git
  repo: 'git@github.com:ACHANG-GIT/ACHANG-GIT.github.io.git' #仓库地址
  branch: 'master' #分支
```
###### 下载部署工具
```bash
$ npm install hexo-deployer-git --save
```
###### 推送网站
```bash
$ hexo g #生成静态网页
$ hexo d #推送网站
```

![img_1587374661934](/../../images/1.jpg)

![img_1587377198588](/../../images/img_1587377198588.jpg)

![img_1587377265357](/../../images/img_1587377265357.jpg)

