---
title: 如何添加插件
---

本篇文档将教你如何在服务端安装插件。

:::warning 部分内容已过期

本文档部分内容已过期！现已隐藏！

:::

## 前言

### 关于LiteloaderBDS/LevLamina

:::warning 过期的内容

此部分内容已过期！

:::

<!-- :::info 提示

在下文中，LiteloaderBDS将被简称为`LL2`，LevLamina将被简称为`LL3`。

:::

+ LL2与LL3不兼容，所有为LL2适配的插件无法直接安装在LL3服务端上。

+ LL3无法安装LL2的`.dll`格式的插件。

+ LL3想安装LLSE的插件(包含`.lua`，`.js`，`.py`等格式的插件)需要先安装[Legacy转译层](https://github.com/LiteLDev/LegacyScriptEngine)，根据LSE插件编写语言的不同，转译层也分为好几种。
-->

### 关于Nukkit系服务端

+ Nukkit系由于各种分支层出不穷，因此在安装插件前请确认插件是否兼容此服务端。

## 如何安装

:::caution 不适用

此教程不适用于以下服务端：

- BDS
- BDS on Windows

:::

1. 进入实例，点击`文件`

2. 进入`plugins`文件夹

3. 上传您的插件

:::tip 注意事项

+ 注意检查插件版本，前置等。

+ 不要把LL2/LL3插件安装在Nukkit系服务端上，反之亦然！

+ LL3在安装LLSE插件前确保已经安装了对应的转译层。

+ LL2在安装插件时注意插件版本，不要安装成了LL3插件！

:::
