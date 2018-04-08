---
title: 第一次的Hexo
date: 2018-03-30 12:08:46
tags: [hexo,第一次]
---
## 什么是Hexo
用官网的话来说：A fast, simple & powerful blog framework, powered by [Node.js](https://nodejs.org/).
## 安装Node.js
下载[Node.js](https://nodejs.org/en/download/)并安装
## 安装Git
下载[Git](https://git-scm.com/downloads)并安装。安装完成后登录自己的github账号
## 初始化 Hexo
1. 在磁盘建立个人的博客文件夹，这个文件夹就是放置Hexo文件的目录  
1. 进入这个目录，鼠标右键，选择`Git Bash Here`，使用命令`npm i -g hexo`即可开始安装Hexo
1. 使用`hexo -v`命令查看是否安装好Hexo，若安装完成则使用命令`hexo init`即可初始化博客目录
1. 使用命令`hexo g`解析markdown文件生成html文件，使用命令`hexo s`启动服务预览
1. 浏览器访问`http://localhost:4000/`即可预览效果
1. 配置_config.yml，填入自己的github信息
1. 使用命令`hexo d`即可发布到github  

## 更多Hexo命令
请查看[Hexo官网](https://hexo.io/)
