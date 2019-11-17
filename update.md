---
layout: page
title: 更新记录
tagline: 记录下每个版本的新功能和遇到的"虫子" (=・ω・=)
permalink: /update/index.html
---

## v1.0.0

Features: 

1. 添加`Google Breakpad`, 记录崩溃日志

Optimize: 

1. 笔记列表卡顿

Fixed bugs:

1. 无限期版本的许可证输入无效
2. emoji 显示
3. 笔记更新时间的无法更改


## v1.0.0.beta7

Features: 

1. 添加`Google Analytics`
2. 长按删除笔记按钮清空回收站
3. 长按新建笔记按钮恢复回收站所有笔记

Optimize: 

1. 许可证添加起始和过期时间

Fixed bugs:

1. 输入许可证后菜单未修改为删除许可证


## v1.0.0.beta6

Optimize: 

1. `MarkdownPreviewer`图片宽度自适应算法
2. 优化搜索笔记算法, 减轻卡顿
3. 进入应用后, 如果选中了笔记, 把该笔记置于顶部

Fixed bugs:

1. 当`MarkdownPreviewer`关闭再打开时, 图片显示不正常
2. 进入应用时, 笔记列表排序不正确
3. 自动锁屏逻辑错误, 顺便修复自动同步笔记
4. 同步笔记数量过多时主界面无响应
5. `Linux`和`Windows`平台, 分组列表未选中的情况下会有选中效果

## v1.0.0.beta5

Features: 

1. `MarkdownEditor`支持显示 web 图片

Optimize: 

1. `MarkdownEditor`样式, 使显示更自然
2. `MarkdownEditor`选中文本行时, 标记该行被选中(背景颜色不一样)
3. `MarkdownPreviewer`图片显示自适应宽

Fixed bugs:

1. 修改`macOS`平台, `libcrypto`链接库找不到
2. 初次打开`MarkdownEditor`时文本样式显示不正确



## v1.0.0.beta4

Optimize: 

1. 添加`Windows`和`Linux`平台分离器的分割线
2. 修改`Windows`和`Linux`平台滚动条样式

Fixed bugs:

1. 修复`Windows`平台第一次打开应用时未在屏幕中间

## v1.0.0.beta3

Fixed bugs:

1. 修复在`macOS`上编辑器无法输入中文 [#1](https://github.com/Gitnoter/Gitnoter/issues/1)
2. 修复在`Windows`上输入许可证无效 [#2](https://github.com/Gitnoter/Gitnoter/issues/2)
