---
title: "Centos7.9安装gcc8环境"
date: 2022-03-31T09:57:17+08:00
# url: 2020/09/11/hexo-hello-world.html
tags: 
  - 学习
categories:
  - Linux
---

# Centos7.9安装gcc8环境

执行命令
```shell
  yum install centos-release-scl
  yum install devtoolset-8-gcc*
```

完成后执行环境切换
```shel
  scl enable devtoolset-8 bash
```

查看gcc版本
```
  gcc --version
```