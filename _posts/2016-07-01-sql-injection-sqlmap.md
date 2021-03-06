---
layout: post
title: SQL 注入 — sqlmap
date: '2016-07-01 08:00:00 +0800'
tags: [PT]
categories: test
---

# sqlmap

sqlmap 是一个开源的渗透测试工具，可以用来自动化的检测，利用SQL注入漏洞，获取数据库服务器的权限。它具有功能强大的检测引擎,针对各种不同类型数据库的渗透测试的功能选项，包括获取数据库中存储的数据，访问操作系统文件甚至可以通过外带数据连接的方式执行操作系统命令。

## 安装

安装很简单，到官网 <https://github.com/sqlmapproject/sqlmap> 下载并解压即可。

## 参数

命令行输入 `python sqlmap.py -h` 可以查看帮助文档。

最常用的命令主要有

- `-u` 目标的URL地址
- `-data` 用来传递POST参数
- `-p` 指定注入的参数

## 示例

示例一： 直接对一个url进行注入检测（GET）

```
python sqlmap.py -u "http://www.sqltest.org/sql1.php?user=jack&id=1"
```

示例二： 直接对一个url进行注入检测（POST）

```
python sqlmap.py -u "http://www.sqltest.org/sql1.php" --data="user=jack&id=1"
```
