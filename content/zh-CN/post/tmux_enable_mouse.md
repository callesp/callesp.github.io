---
title: "Tmux_enable_mouse"
date: 2022-04-07T15:36:52+08:00
draft: true
tags: 
  - Dev
categories:
  - Linux
---

# tmux启用鼠标控制

查看当前tmux版本：

`tmux -V`

编辑tmux配置文件：

`vim ~/.tmux.conf`

tmux2.1之后:

`set-option -g mouse on`

tmux2.1之前:

```
setw -g mouse-resize-pane on

setw -g mouse-select-pane on

setw -g mouse-select-window on

setw -g mode-mouse on
```
