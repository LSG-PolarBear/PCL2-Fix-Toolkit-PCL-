# PCL2-Fix-Toolkit-PCL-
🛠️ PCL2 旧版启动器与配置一键修复工具包。包含旧版主程序与修改 Setup.ini 的修复工具，解决近期无法下载 Minecraft 或启动异常问题。支持自动备份。A toolkit including a legacy PCL2 launcher and a Setup.ini fixer to resolve download/launch issues. Includes auto-backup.
# PCL2 旧版启动器与配置一键修复工具包

# PCL2 旧版启动器与配置一键修复工具包 (PCL2 Legacy Launcher & Config Fix Toolkit)

由于近期 PCL2 官方及网络环境调整，部分用户使用新版启动器时遇到无法下载 Minecraft 或启动异常的问题。本仓库提供了一个包含**旧版启动器主程序**与**配置修复工具**的整合压缩包，帮助你快速恢复游戏体验。
> Due to recent changes in PCL2 and the network environment, some users are experiencing issues with downloading Minecraft or launch failures. This repository provides a toolkit containing a **Legacy Launcher Executable** and a **Config Fixer** to help you restore your gaming experience.

## 📦 压缩包内容说明 (Package Contents)

下载解压后，你将看到两个文件：
1. **`PCL2_Fix.exe`**：配置一键修复工具（用于修改 `Setup.ini` 绕过限制）。
2. **旧版 PCL2 启动器主程序**（例如 `Plain Craft Launcher 2.exe`）。

> After extracting the ZIP, you will see two files:
> 1. **`PCL2_Fix.exe`**: Configuration fixer (modifies `Setup.ini` to bypass restrictions).
> 2. **Legacy PCL2 Launcher Executable** (e.g., `Plain Craft Launcher 2.exe`).

## 🚀 使用步骤 (How to Use)

### 第一步：解压并放置文件 (Step 1: Extract and Place Files)
将压缩包内的 **两个文件（修复工具 + 旧版启动器）** 放到**同一个文件夹**中。如果你原本有 PCL2 文件夹，直接复制进去覆盖原有主程序即可。
> Extract **both files** and place them in the **same folder**. If you already have a PCL2 folder, just copy them in to overwrite the main executable.

### 第二步：运行修复工具 (Step 2: Run the Fix Tool)
**在运行启动器之前**，先双击运行 **`PCL2_Fix.exe`**。工具会自动修改/生成 `Setup.ini` 配置文件（添加 `SystemSystemUpdate:3` 参数），并自动备份原配置为 `Setup.ini.bak`。
> **Before launching the game**, double-click **`PCL2_Fix.exe`**. It will automatically modify/generate the `Setup.ini` file (adding `SystemSystemUpdate:3`) and back up the original as `Setup.ini.bak`.

### 第三步：启动与反馈 (Step 3: Launch and Feedback)
看到修复工具提示“恢复完成”后，**不要关闭工具窗口**。双击同目录下的 **旧版 PCL2 启动器** 测试。
*   如果正常：回到工具窗口输入 `Y` 退出。
*   如果不正常：输入 `N`，根据提示联系作者。
> Once it displays "Fix Completed", **do not close the tool window**. Double-click the **Legacy Launcher** to test.
> *   If it works: Type `Y` in the tool window to exit.
> *   If it fails: Type `N` and follow the instructions to contact the author.

## ⚠️ 注意事项 (Important Notes)

1. **防杀毒误报**：修复工具使用 Python 打包，部分杀毒软件可能出现**误报拦截**。本程序完全开源透明，请手动添加信任。
> **Antivirus False Positives**: The Fix Tool is packed using Python. Some antivirus software may trigger **false positive alerts**. It is completely safe and open-source; please add it to your trust list.

2. **同目录原则**：修复工具**必须**和旧版启动器放在同一个文件夹下运行，否则会提示“检测失败”。
> **Same Directory Rule**: The Fix Tool **must** be placed in the same folder as the Legacy Launcher, otherwise, it will fail to validate.

3. **进程冲突**：运行修复工具前，**请确保 PCL2 启动器已完全关闭**（可在任务管理器中确认）。
> **Process Conflict**: Before running the Fix Tool, **ensure no PCL2 instances are running** in the background.

4. **还原配置**：如修复后出现问题，将生成的 `Setup.ini.bak` 重命名为 `Setup.ini` 即可还原。
> **Restore Config**: If issues occur, rename `Setup.ini.bak` back to `Setup.ini` to restore.

## 🛠️ 联系作者 (Contact)
如果你遇到无法解决的问题，请联系：
> If you encounter unsolvable issues, please contact:
*   **QQ**: 2429871514
*   *(联系时请附上报错截图和修复工具的运行截图 / Please include screenshots of the error and the tool's console window)*
