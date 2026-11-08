# Photoshop-Layers-Batch

Batch-execute custom actions on layers corresponding to video frames to achieve your desired video edits. Compatible with **Adobe Photoshop CC** and later versions.

对与视频帧相对应的图层批量执行自定义操作，以实现所需的视频编辑。兼容**Adobe Photoshop CC**及更高版本。

## Use Case Examples / **使用方法举例**

1. **Object Removal:** Batch-remove unwanted objects, blemishes, or watermarks across video frames using Content-Aware Fill or healing actions.

   **对象移除**：使用内容感知填充或修复操作，批量移除视频帧中不需要的对象、瑕疵或水印。

   [![Demo video演示视频：使用对象选择工具去除飞鸟](https://youtube.com)](https://youtu.be/W0Kouaf2zV0)
 
2. **Subject Repositioning:** Adjust or stabilize the position of a subject consistently across frame layers.The initial steps can also be used to remove backgrounds when creating GIFs or stickers.

   **主体位置调整**：在各个帧层中统一的调整主体的位置。前半部分步骤也可用于制作表情包时去除背景。

   [![Demo video演示视频：移动视频里的主体位置](https://youtube.com)](https://youtu.be/JudHqakzl7E)

## Basic Workflow / 基本工作流程

1. Import your video as layers in Photoshop.

   在Photoshop中将视频作为图层导入。

2. Record the custom **Action** you want to apply in the **Actions** panel.

   在“动作”面板中记录您想要应用的自定义**操作**。

3. Select the target video frame layers in the **Layers** panel.

   在**图层**面板中选择目标视频帧图层。 

4. Go to **File → Scripts → ^_^Video Frame Batch**, choose your desired action, and run the batch process.

   前往**文件 → 脚本 →^_^视频帧批处理**，选择所需操作，然后运行批处理。

## FAQ / 常见问题

[![Photoshop视频剪辑常见问题](https://youtube.com)](https://youtu.be/qhbBTBd5RWU)

1. What should I do if I cannot use "Video Frame to Layer" when importing a video? 

   导入视频时，无法使用”视频帧到图层“怎么办?

2. How to add sound to a video in Photoshop?

   Photoshop里如何给视频添加声音?

## Installation / **安装方法**

1. Download the script file (`.jsxbin`).

   下载脚本文件（.jsxbin）。

2. Copy the script file into your Photoshop `Scripts` directory:

   将脚本文件复制到 Photoshop 的 Scripts 目录：

   * **macOS**

     ```text
     /Applications/Adobe Photoshop [Version]/Presets/Scripts/
     ```

     *Example:*

     ```text
     /Applications/Adobe Photoshop 2024/Presets/Scripts/
     ```

   * **Windows**

     ```text
     \Adobe\Adobe Photoshop [Version]\Presets\Scripts\
     ```

     *Example:*

     ```text
     C:\Program Files\Adobe\Adobe Photoshop 2024\Presets\Scripts\
     ```

3. If Photoshop is currently running, **restart** the application to refresh the Scripts menu.

   如果 Photoshop 正在运行，请重新启动以刷新脚本菜单。

4. Once launched, navigate to **File → Scripts → [Script Name]** in the top menu bar to run the script.

   启动后，在菜单中选择「文件 → 脚本 → 脚本名称」运行。
