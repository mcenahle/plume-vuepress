---
title: 停止 Windows 更新
createTime: 2026/04/03 10:30:30
permalink: /system/stop-windows-update/
---

Windows 的更新以其强制性而臭名昭著。而本页面旨在解决此问题。

## 使用 Windows Update Blocker（WUB），暂停更新服务

1. [下载 WUB 1.8 版本](https://mcenahle.cn/resources/stop-windows-update/wub-1.8.zip) 并解压缩，双击打开 `Wub_x64.exe` 可执行文件。

![打开 WUB](/images/LAPTOP-QBI12I8_mcenahle_20260403_10-43-30.jpg)

2. 点击 `禁用更新` - `锁定服务设置` - `应用`。

![WUB 操作](/images/LAPTOP-QBI12I8_mcenahle_20260403_10-44-21.jpg)

3. 打开 `菜单` - `详细服务选项`：

![菜单](/images/屏幕截图-2026-04-03-104621.png)

4. 检查是否存在 `√` 的项目。若全为 `×`，则代表正确；

![全x](/images/LAPTOP-QBI12I8_mcenahle_20260403_10-48-48.jpg)

::: warning 若存在一个 `√`，则需要打开系统服务。
同时按下 `Windows 徽标` 键 + `R` 键，并输入 `services.msc` 以打开。

例如，我的 `BITS` 仍然是 `√`，则查看服务描述：`使用空闲网络带宽在后台传送文件。...`。

![示例服务](/images/LAPTOP-QBI12I8_mcenahle_20260403_10-57-47.jpg)

5. 在系统服务中，点按 `描述` 字样，按描述排序：

![点按描述](/images/LAPTOP-QBI12I8_mcenahle_20260403_10-59-59.jpg)

6. 找到服务，并双击打开：

![找到服务](/images/LAPTOP-QBI12I8_mcenahle_20260403_11-01-33.jpg)

7. 更改服务设置，先 `停止` 服务，再 `禁用` 服务：

![服务设置](/images/LAPTOP-QBI12I8_mcenahle_20260403_11-03-38.jpg)

8. 循环往复，直到 `详细服务选项` 的所有项目均为 `×`。
:::

## 使用注册表编辑器，暂停更新3000天

1. 使用 [本注册表项 (.reg)](https://mcenahle.cn/resources/stop-windows-update/pause_update_3000_d.reg) 以安装注册表项，以开放暂停更新 3000 天的渠道。

![运行前的提示](/images/LAPTOP-QBI12I8_mcenahle_20260403_10-37-39.jpg)

2. 点击 `是` 以继续。

3. 同时，也要转到::material-symbols:settings-outline-rounded::设置 [+设置]：

[+设置]:
   点击::mage:microsoft-windows::`Windows 徽标` 键 + `I` 键以打开。

![设置](/images/LAPTOP-QBI12I8_mcenahle_20260403_10-33-52.jpg)

4. 并点击“暂停一周”旁边的 `v`，

![2](/images/LAPTOP-QBI12I8_mcenahle_20260403_10-34-57.jpg)

5. 下拉找到 `暂停428周`：

![暂停428周](/images/LAPTOP-QBI12I8_mcenahle_20260403_10-35-53.jpg)

6. 若已经提示必须更新才能关机/重启，可::material-symbols:logout-sharp::注销 [+注销] 再次登录。点击 Windows 徽标::mage:microsoft-windows::，并依次点击用户名 - `注销` 以注销。

![注销路径](/images/LAPTOP-QBI12I8_mcenahle_20260403_11-17-26.jpg)

[+注销]:
   注销是指关闭当前用户的所有程序，并退出登录的行为。==注销前，请务必保存已经完成的工作！=={.important}