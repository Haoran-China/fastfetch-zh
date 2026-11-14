# fastfetch-zh 简体中文汉化版

本项目基于原版 `fastfetch` 进行源码级简体中文本地化修改，并提供了适用于不同 ARM 架构的预编译二进制文件，方便用户开箱即用。

## ⚠️ 声明与致谢

- **原项目地址**：[fastfetch-cli/fastfetch](https://github.com/fastfetch-cli/fastfetch)
- **版权说明**：本项目的核心代码与设计版权归原作者所有。
- **开源协议**：本项目严格遵循原项目的 **MIT License** 开源协议。
- **修改内容**：本仓库仅针对软件内部的系统信息标签、提示语及输出文本进行了硬编码汉化，未修改任何核心运行逻辑。

## ✨ 特性

- **完全汉化**：系统信息面板、输出信息等全面中文化。
- **多架构支持**：提供以下主流 ARM 架构的预编译文件：`aarch64` (64位 ARM) 与 `arm32` (32位 ARM)。
- **开箱即用**：无需配置复杂的编译环境，下载即可直接运行。

## 📥 下载与安装

请根据你的设备系统架构，选择对应的版本下载（建议在 Termux 等终端环境使用）：

- 👉 [下载 aarch64 (64位 ARM) 版本](https://github.com/Haoran-China/fastfetch-zh/releases/download/v1.0.0/fastfetch-aarch64)
- 👉 [下载 arm32 (32位 ARM) 版本](https://github.com/Haoran-China/fastfetch-zh/releases/download/v1.0.0/fastfetch-arm32)

### 🚀 手动使用步骤

1. 将下载的文件重命名为 `fastfetch`。
2. 在终端中赋予执行权限：`chmod +x fastfetch`
3. 运行程序：`./fastfetch`

## 🛠️ 编译指南

若预编译版本无法在你的设备上运行，或你需要自定义功能，可拉取本仓库源码自行编译。

本项目使用 CMake 构建系统。仓库中已包含针对不同架构的构建目录：
- `fastfetch-aarch64`：用于 64 位 ARM 架构编译。
- `fastfetch-arm32`：用于 32 位 ARM 架构编译。

进入对应的构建目录，执行 `make` 即可生成可执行文件。

## 📄 许可证

[MIT License](LICENSE)

请在使用、修改或分发本项目时，保留原作者的版权声明及本开源协议。