---
title: "Helix_with_tmux"
date: 2022-04-07T08:45:04+08:00
draft: false
tags: 
  - Dev
categories:
  - Linux
---


# **helix结合tmux使用注意事项**

在tmux环境使用helix的时候发现使用Esc执行模式切换会有延迟，需要在 `~/.tmux.conf` 中添加如下配置: 

&emsp;`set escape-time 0`

然后关闭并重新打开tmux即可