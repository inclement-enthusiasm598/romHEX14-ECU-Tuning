<div align="center">

**[English](README.md)** | **[中文](README_zh.md)**

# romHEX 14

### 全球首款 AI 驱动的 ECU 标定软件

<br>

<img src="https://img.shields.io/badge/版本-1.0.0--beta1-blue?style=for-the-badge" alt="版本">
<img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows">
<img src="https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white" alt="macOS">
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
<img src="https://img.shields.io/badge/Qt-6.10-41CD52?style=for-the-badge&logo=qt" alt="Qt 6">
<img src="https://img.shields.io/badge/许可-LGPL--3.0-orange?style=for-the-badge" alt="许可">

<br><br>

**专业 ECU 调校软件，全面支持 A2L/HEX/OLS，内置 AI 工具，兼容 WinOLS 工作流。**

<br>

[**下载最新版本**](https://github.com/ctabuyo/romHEX14-ECU-Tuning/releases/latest)&nbsp;&nbsp;·&nbsp;&nbsp;[**官网**](https://romhex14.com)&nbsp;&nbsp;·&nbsp;&nbsp;[**文档**](https://romhex14.com/docs)

---

<br>

<img src="screenshot.png" alt="romHEX 14 截图" width="100%">

<br>

*地图编辑器 — 2D/3D 可视化、AI 助手、十六进制视图、多语言地图标签*

---

</div>

<br>

## 下载

| 平台 | 下载链接 | 说明 |
|:---:|:---:|:---|
| <img src="https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white"> | [**RX14-Setup.exe**](https://github.com/ctabuyo/romHEX14-ECU-Tuning/releases/latest/download/RX14-Setup.exe) | Windows 10/11 (64位) — 单文件安装包 |
| <img src="https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white"> | [**RX14.dmg**](https://github.com/ctabuyo/romHEX14-ECU-Tuning/releases/latest/download/RX14.dmg) | macOS 12+ (Apple Silicon 和 Intel) |
| <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"> | [**RX14.AppImage**](https://github.com/ctabuyo/romHEX14-ECU-Tuning/releases/latest/download/RX14.AppImage) | Ubuntu 22.04+, Fedora 38+, Arch |

> **中国用户：** 如果 GitHub 下载速度较慢，应用程序在检查更新时将自动提供镜像下载链接。

<br>

## Beta 1 新功能

- **WinOLS OLS 导入** — 完整的 OLS 项目文件解析器，支持 ROM 提取、地图记录、缩放、维度和字节序检测。已在 60+ 个 OLS 文件中验证
- **WinOLS KP 导入** — 地图包导入对话框，带 ROM 概览条、偏移配置、自动检测和重复处理
- **地图叠加 v2** — 现代感知热力图渐变、白色文字暗色描边、渐变光照单元格、磨砂玻璃轴标题、明亮选区高亮
- **校验和校正** — 148 个 WinOLS 兼容校验和 DLL，通过 32 位桥接支持所有主流 ECU（EDC15/16/17、ME7/9、MED17、SIMOS 等）
- **AI 调校功能** — 自动化 DPF 删除、EGR 关闭、AdBlue/SCR 关闭、去催化、涡流阀、限速器、启停禁用，支持自定义值和风险提示
- **AI 故障码管理** — 故障码识别和管理
- **链接 ROM 同步** — 链接 ROM 之间同步滚动，自动启用光标同步，[原始] 标记参考 ROM
- **十六进制视图小地图** — 滚动条旁的垂直概览条，显示 ROM 数据强度和地图区域
- **视图同步** — 文本视图和 2D 视图之间无缝滚动位置同步
- **完整国际化** — 中文（简体）和西班牙语（Español）完整翻译，覆盖所有对话框、工具栏、AI 助手、配置和校验和界面

<br>

## 功能特性

**A2L、HEX 和 OLS 引擎**
- 完整 ASAP2 (A2L) 解析器，支持特性、轴和测量
- HEX/BIN/S19 文件加载，自动 ECU 检测
- WinOLS OLS 项目导入，支持 ROM 提取和地图定义
- WinOLS KP 地图包导入，支持偏移自动检测
- 并排 ROM 对比，字节级差异可视化

**AI 助手** — *行业首创*
- AI 驱动的 ECU 标定助手（Claude、GPT-4o、通义千问、DeepSeek、Gemini、本地模型）
- 智能地图识别和标签
- AI 跨语言地图翻译
- AI 调校功能（DPF、EGR、AdBlue、去催化、限速器等）
- AI 故障码管理
- 自然语言查询标定数据

**地图编辑器**
- 交互式 2D/3D 地图可视化，现代热力图
- 拖拽编辑，实时预览
- 3D 仿真视图
- 地图包导入/导出
- 补丁创建和管理 (.rxpatch)

**校验和校正**
- 148 个 ECU 专用校验和算法（WinOLS 兼容 DLL）
- 支持 Bosch EDC15/16/17、ME7/9、MED17、MG1、SIMOS 等
- 刷写前验证和校正校验和

**项目管理**
- 多文件项目，链接 ROM 同步滚动
- [原始] 标记识别参考/原始 ROM
- 项目注册表，快速访问
- 版本快照，支持还原
- 自动保存，崩溃恢复
- 完整撤销/重做历史

**多语言**
- 英语、西班牙语 (Español)、中文（简体中文）、泰语 (ไทย)
- AI 跨语言地图标签翻译
- 自适应 CJK 工具栏图标

<br>

## 支持的 ECU

| 制造商 | ECU 系列 |
|---|---|
| **Bosch** | MED17, MG1, MD1, EDC17, EDC16, EDC15, ME7, ME9, MED9, MSV, MSD |
| **Continental** | SIMOS 12/16/18/19/22, SID, SCG, SCM |
| **Delphi** | DCM3.x, DCM6.x, DCU-10x |
| **Denso** | 多代产品 |
| **Magneti Marelli** | MJD, 7GV/8GMK |
| **Valeo** | VD46 |

<br>

## 系统要求

| | 最低配置 | 推荐配置 |
|---|---|---|
| **操作系统** | Windows 10 / macOS 12 / Ubuntu 22.04 | Windows 11 / macOS 14 / 最新 LTS |
| **内存** | 4 GB | 8 GB |
| **磁盘** | 500 MB | 1 GB |
| **显示器** | 1280 x 720 | 1920 x 1080 |

<br>

## 安装

**Windows** — 下载 `RX14-Setup.exe` 并运行，单文件安装包，无需额外依赖。

**macOS** — 下载 `RX14.dmg`，打开后将 romHEX 14 拖到"应用程序"文件夹。

**Linux** — 下载 `RX14.AppImage`，设置可执行权限 (`chmod +x`)，然后运行。

<br>

## 从源码构建

```bash
# 前置条件：Qt 6.10+、CMake 3.16+、C++17 编译器

git clone https://github.com/ctabuyo/romHEX14-ECU-Tuning.git
cd romHEX14-ECU-Tuning
mkdir build && cd build
cmake .. -DCMAKE_PREFIX_PATH=/path/to/qt6
cmake --build . -j$(nproc)
```

<br>

## 许可证

本软件基于 [GNU 宽通用公共许可证 v3.0](https://www.gnu.org/licenses/lgpl-3.0.html) (LGPL-3.0) 分发。

使用 [Qt 框架](https://www.qt.io/) (LGPL) 构建。

版权所有 (c) 2024-2026 CT14 Garage Co., Ltd. 保留所有权利。

<br>

---

<div align="center">
<sub>由 <b>CT14 Garage</b> 精心打造 — 专业 ECU 标定解决方案</sub>
</div>
