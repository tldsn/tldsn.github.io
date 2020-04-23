---
layout: post
title: ERROR
categories: Exception
tags: Exception git
author: tldsn
---

* content
{:toc}

ERROR//Git错误:
>ServicePointManager 不支持具有 socks5h 方案的代理

原因：
>虽然配置了socks5h代理，但是git remote add origin配置的是https的项目地址，
所以代理无法使用

解决：
>git remote rm origin删除
重新配置为SSH的项目地址
