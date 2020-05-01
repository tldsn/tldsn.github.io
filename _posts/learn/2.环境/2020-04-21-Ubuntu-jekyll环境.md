---
layout: post
title: Ubuntu-jekyll环境
categories: 环境
tags: Ubuntu jekyll 环境
author: tldsn
---

* content
{:toc}

### 学习：Ubuntu//jekyll

1. gcc编译包

    ```
    sudo apt install build-essential
    ```

2. ruby

    ```
    sudo apt-get install ruby-full
    ```

3. rubygems

    ```
    sudo apt install rubygems　　//安装
    sudo gem update --system　　//升级
    ```

4. jekyll

    ```
    sudo gem install jekyll　　//安装
    sudo gem update jekyll　　//升级
    ```

### gem镜像

```
gem sources --add https://gems.ruby-china.com/ --remove https://rubygems.org/
```
