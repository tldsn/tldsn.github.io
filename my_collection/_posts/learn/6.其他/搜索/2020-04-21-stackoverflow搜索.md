---
layout: post
title: stackoverflow搜索
categories: 搜索技巧
tags: stackoverflow 搜索技巧
author: tldsn
---

* content
{:toc}

### base

* `"n"`　　精确匹配
* `*`　　通配符
* `空格`　　and
* `or`　　或
* `-n`　排除
* `title: n`
* `body: n`
* `[tag]`　　在标签下匹配
* `user:me`　　搜索自己

### 评分

* `score:-1或score:-1..`　　得分均等于或大于-1的帖子

### 时间

* `created:`　　指定创建帖子的时间
* `lastactive:`　　 指定时间段内处于活跃状态的帖子

<mark>
created:2012-04..2012-05　　在2012年4月1日至2012年5月31日之间创建的搜索帖子。
</mark>  

### 状态

* `intags:mine`　　仅返回出现在您标记为收藏的标签中的帖子。
* `isaccepted:yes / true / 1`　　仅返回已标记为“已接受”的答案；no / false / 0仅返回未标记为接受的答案。

### 参考

> [https://stackoverflow.com/help/searching](https://stackoverflow.com/help/searching)
