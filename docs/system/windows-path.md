---
title: Windows 路径
createTime: 2026/04/01 18:00:06
permalink: /system/windows-path/
---

## 一、什么是Windows路径？
在现实环境中，地址是唯一标识一个建筑物所在的位置。

比如：

1. 上海图书馆（东馆）：::mdi:location::上海市浦东新区合欢路300号；

2. 浦东国际机场：::mdi:location::上海市浦东新区迎宾大道6000号；

3. 上海市卫生健康委员会：::mdi:location::上海市浦东新区世博村路300号4号楼；

4. 上海市人民政府：::mdi:location::上海市黄浦区人民大道200号。

同样的，在Windows系统中，为了唯一标识一个文件/文件夹的位置，我们引入“Windows路径”。

例如我们说，一个文件的路径是：`D:\path\to\file.txt`，即表示：

- `D:` → D 盘

- `path\to` → 文件夹层级

- `file.txt` → 文件

可以想象，我们打开一个D盘，再依次打开path文件夹和to文件夹，就找到了file.txt这个文本文件。所以该文本文件的路径就是：`D:\path\to\file.txt`。

## 二、如何在安装程序中更改文件路径？
安装程序的默认安装位置（即路径）一般是 `C:\Program Files\软件名`。如果软件都安装在 C 盘，可能会占满系统盘空间，从而影响电脑运行速度。因此可以考虑安装到其它盘。

安装软件时，注意这一类按钮：

- Browse...

- 更改

- Change

然后把路径改成例如这种：`D:\Software\软件名`。

::: tip 高级选项
对于熟悉电脑的同学，可以直接手动输入路径，而不是点击选择按钮。

例如：`F:\Software\IDEA`，或者：`D:\Apps\MyTools\ToolName`。
:::


## 三、注意事项（很重要）

- 安装后不要随意移动软件文件夹

- 不要手动改软件内部文件名

- 卸载软件请用“卸载程序”，不要直接删除桌面的快捷方式和安装的文件夹

::: info 软件推荐
关于卸载工具，可以使用Geek Uninstaller。该工具能在软件卸载后，自动检测残留项，防止软件“死灰复燃”。[::line-md:download::可在我的网站下载](https://mcenahle.cn/resources/geek.exe)
:::
