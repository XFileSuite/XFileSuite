# XFileSuite

![macOS Build](https://github.com/XFileSuite/XFileSuite/actions/workflows/build-macos.yml/badge.svg) ![Windows Build](https://github.com/XFileSuite/XFileSuite/actions/workflows/build-windows.yml/badge.svg) ![Deploy](https://github.com/XFileSuite/XFileSuite/actions/workflows/sync-cloudflare.yml/badge.svg)

XFileSuite · 全能预览 — 桌面端全能文件预览与编辑工具的发布仓库。

🌐 **[产品主页](https://xfilesuite.com/)** — 了解 XFileSuite 的完整功能与使用场景

## 仓库用途

| 功能 | 说明 |
|------|------|
| **CI/CD 构建** | GitHub Actions 自动构建 macOS 和 Windows 安装包 |
| **GitHub Releases** | 托管各版本安装包历史归档（DMG / EXE） |
| **Cloudflare 同步** | 构建完成后触发本仓库的串行同步工作流，再同步最新安装包到 Cloudflare R2 和 API；第三方源码与许可证资料仅发布到 GitHub Release |

> 源代码存放在私有仓库，本仓库仅包含 CI 工作流和发布产物。

## 下载

👉 **[立即下载最新版本](https://xfilesuite.com/)**

| 平台 | 格式 | 要求 |
|------|------|------|
| macOS | DMG | macOS 13.0+ |
| Windows | EXE 安装包 | Windows 10+ |

已安装的用户可通过应用内自动更新获取最新版本。

## 支持的文件格式

XFileSuite 支持 **50+ 种文件格式**：

| 类别 | 格式数 | 代表格式 |
|------|--------|----------|
| 🖼️ 图片 | 20+ | JPEG · PNG · GIF · BMP · TIFF · WebP · HEIC · SVG · PSD · ICO · ICNS · AVIF |
| 🎬 视频 | 15+ | MP4 · MOV · MKV · AVI · WebM · FLV · WMV · RMVB · 3GP · MTS |
| 🎵 音频 | 10+ | MP3 · FLAC · AAC · WAV · M4A · OGG · Opus · AIFF · MIDI |
| 📄 文档 | 2 | PDF · Markdown |

## 核心功能

- **🚀 闪电预览** — 拖入即看，无需等待
- **🔗 目录联动导航** — 同类文件间无缝切换
- **🎨 专业图像编辑** — 裁剪、旋转、色彩调整、涂鸦标注
- **⚡ 高效压缩** — MozJPEG + libwebp 引擎
- **🔄 格式转换** — 一键互转，含 ICO/ICNS 图标导出
- **✂️ 图片切割** — 横切/纵切/网格宫格
- **🎞️ 音频波形可视化** — 选区循环播放、片段截取
- **🎬 全格式视频播放** — 基于 libmpv，多轨道切换
- **🌗 深色模式** — 自动跟随系统主题
