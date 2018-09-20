---
layout: post
title: '一次坑爹的git提交'
date: 2017-09-20
author: lvxus
color: rgb(255,210,32)
cover: 'http://on2171g4d.bkt.clouddn.com/jekyll-banner.png'
tags: git
---

#起因：
###在搞这个blog的时候，想要提交测试修改的文件到GitHub上面去，但是由于对git的不熟悉，导致了一连串的失败，绝大多数是Permission denied xxx的错误。查百度发现这个是所谓的权限错误？所以我就把公钥和私钥清除掉重新生成。
###(其实不用的，只需要执行 ssh-keygen -t rsa -C "youremail@example.com" ，引号里面是自己的注册账号，回车，显示如下的命令行时)
