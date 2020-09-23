---
layout: post
title: git error
categories: 异常
tags: 异常 git
author: tldsn
---

* content
{:toc}

**ServicePointManager 不支持具有 socks5h 方案的代理**  

* **原因：**  
    虽然配置了socks5h代理，但是git remote add origin配置的是https的项目地址，  
    所以代理无法使用  

* **解决：**  
  1. `git remote rm origin`删除  
  2. 重新配置为SSH的项目地址
