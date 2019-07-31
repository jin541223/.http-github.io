---
title: hexo创建分类、标签及404页面
date: 2018-07-31 17:23:47
tags: hexo category tag
---

### 分类
``` bash
$ 命令：hexo new page "categories"
```
以上命令会在source目录中生成categories\/index.md

在index.md中增加页面类型：
type:"categories"

### 标签
``` bash
$ 命令：hexo new page "tags"
```
以上命令会在source目录中生成tags\/index.md

在index.md中增加页面类型：
type:"tags"

### 404页面
``` bash
$ 命令：hexo new page "404"
```
以上命令会在source目录中生成404\/index.md