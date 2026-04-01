---
title: PR 项目管理
createTime: 2026/04/01 09:14:16
permalink: /pr/project-manage/
---

::: note 请区分“文件管理”和“项目管理”
本页面讨论的是 **项目管理**（例如：完整打包项目、归档或发送给他人）。

如果你想了解的是 **文件管理**，即：如何在资源管理器中整理 Premiere Pro（PR）项目文件，使其结构清晰、便于查找与打开，请参考：[如何进行文件管理](files-manage)。
:::

PR 项目管理是指：将工程和素材等关键资源变成一个文件夹。该文件夹以 `已复制_` 开头，之后接的是你的 PR 工程文件名称。例如：`已复制_example-proj`。

进行项目管理的步骤：

<ImageCard
  image="images/LAPTOP-QBI12I8_mcenahle_20260401_11-34-31.png"
  title="第一步 - 打开 PR 工程"
/>

<ImageCard
  image="images/LAPTOP-QBI12I8_mcenahle_20260401_11-40-44.png"
  title="第二步 - 转到“文件” - “项目管理”"
/>

<ImageCard
image="images/LAPTOP-QBI12I8_mcenahle_20260401_13-37-17.png"
title="第三步 - 选择一些设置"
/>

::: tip 项目管理器
一、设置
1. 序列：选择要项目管理的序列。**默认全部选中**；
2. 选项中的`排除未使用剪辑`：①对于上交给老师/学校：**勾选**，以尽量减少文件夹的大小；②对于团队协作/发送给同学：**不勾选**，以让协作者继续完成项目；
3. 其它保持默认选项即可。

二、点击==目标路径==的`浏览`选择你要存档到的路径。比如：`F:\素材\皇后镇-04`。PR 会在其中创建目录以进行存档。

三、点击==生成项目大小==的`计算`以计算该文件夹的预估大小。该值仅为预览；实际以文件夹的大小为准。
:::

<ImageCard
image="images/LAPTOP-QBI12I8_mcenahle_20260401_14-02-43.png"
title="第四步 - 转到资源管理器，即可查看到新释放的文件夹"
/>

项目管理的文件夹结构（示例）如下：

::: file-tree icon="colored"

- F:
  - 素材
      - 皇后镇-04
        - DJI_20260104214010_0026_D.mov  素材文件（视频，mov）
        - 皇后镇-04.prproj  视频工程文件
        - AdobePremiereProAudioPreviews 音频预览文件夹
          - 皇后镇-04.PRV  音频预览文件
        - AdobePremiereProVideoPreviews 视频预览文件夹
          - 皇后镇-04.PRV  视频预览文件
:::

::: warning
不要更改此文件夹中的任何事项，包括文件名、文件位置等。也不要使用工程降级网站来替换降级的工程文件。

**进行以上行为都会导致无法打开工程；==项目文件夹亦将作废=={.danger}。**
:::