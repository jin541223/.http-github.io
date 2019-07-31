---
title: 执行git push --set-upstream origin hexo报错
date: 2018-08-01 23:16:47
tags: git push --set-upstream
---

### 在用 git push --set-upstream origin branchHexo 与origin创建关联，并将branchHexo设置为默认分支时报错

``` bash
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.
```

### 解决方案
``` bash
git remote add origin github项目地址
```

如：git remote add origin git@github.com:userName/userName.github.io.git

这样将关联远程仓库