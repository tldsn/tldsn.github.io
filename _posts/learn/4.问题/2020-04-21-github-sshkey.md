---
layout: post
title: 为什么GitHub需要SSH Key呢？
categories: 问题
tags: github SSH
author: tldsn
---

* content
{:toc}

### 为什么GitHub需要SSH Key呢

>因为GitHub需要识别出你推送的提交确实是你推送的，而不是别人冒充的，  
而Git支持SSH协议，所以，GitHub只要知道了你的公钥，就可以确认只有你自己才能推送。

### 特点

* ssh方式单独使用非对称的秘钥进行认证和加密传输，和账号密码分离开来，不需要账号也可以访问repo。  
* 生成和管理秘钥有点繁琐，需要管理员添加成员的public key。不能进行匿名访问，ssh不利于对权限进行细分，用户必须具有通过SSH协议访问你主机的权限，才能进行下一步操作，比较适合内部项目
