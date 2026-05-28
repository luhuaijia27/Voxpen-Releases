# Voxpen — 本地离线语音输入助手

> 按快捷键 → 录音 → AI 识别 → 自动粘贴文字。无需联网，隐私本地。

## 最新版本

| 平台 | 版本 |
|------|------|
| 🍎 macOS（Apple Silicon M 系列）| v1.0.2 |
| 🍎 macOS（Intel x86_64）| v1.0.2 |
| 🪟 Windows CPU 版 | v1.0.1 |
| 🪟 Windows GPU 版 | v1.0.0 |

### 直接下载

| 平台 | 文件 | 说明 |
|------|------|------|
| 🪟 Windows CPU 版 | [Voxpen_Setup_v1.0.1.zip](https://github.com/luhuaijia27/Voxpen-Releases/releases/download/windows-v1.0.1/Voxpen_Setup_v1.0.1.zip) | 解压后运行 `Voxpen_Setup.exe` |
| 🪟 Windows GPU 版 | [Voxpen_GPU_Setup_v1.0.0.zip](https://github.com/luhuaijia27/Voxpen-Releases/releases/download/windows-v1.0.1/Voxpen_GPU_Setup_v1.0.0.zip) | 需要 NVIDIA GPU，解压后运行 `Voxpen_GPU_Setup.exe` |
| 🍎 macOS Apple Silicon | [Voxpen_v1.0.2_macOS_arm64.dmg](https://github.com/luhuaijia27/Voxpen-Releases/releases/download/macos-v1.0.2/Voxpen_v1.0.2_macOS_arm64.dmg) | M1/M2/M3/M4 芯片 |
| 🍎 macOS Intel | [Voxpen_v1.0.2_macOS_x86_64.dmg](https://github.com/luhuaijia27/Voxpen-Releases/releases/download/macos-v1.0.2/Voxpen_v1.0.2_macOS_x86_64.dmg) | Intel 芯片 |

> **找不到下载按钮？** 直接点击上方表格中的文件名即可下载。

## 安装说明

### Windows
1. 下载并解压对应版本的 ZIP（不确定选 CPU 版，普通电脑均可用）
2. 运行 `Voxpen_Setup.exe`（CPU 版）或 `Voxpen_GPU_Setup.exe`（GPU 版），按提示完成安装
- **CPU 版**：适合所有 Windows 电脑
- **GPU 版**：需要 NVIDIA 独立显卡，推理速度约为 CPU 版的 3-5 倍

### macOS
1. 根据芯片下载对应版本（不确定请点击左上角苹果菜单 → 关于本机查看）
   - **Apple Silicon（M1/M2/M3/M4）**：下载 `arm64` 版本
   - **Intel**：下载 `x86_64` 版本
2. 双击挂载 DMG，将 Voxpen.app 拖入 Applications 文件夹
3. 打开「终端」，粘贴以下命令并回车（仅需一次）：
   ```
   xattr -cr /Applications/Voxpen.app
   ```
4. 完成后即可从启动台正常启动 Voxpen
5. 首次启动需在系统设置中授权：辅助功能、输入监控、麦克风

## 官网

[voxpen.tztd.com.cn](https://voxpen.tztd.com.cn)
