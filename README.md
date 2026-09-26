# XFileSuite

**打开文件，接着把事情做完。** XFileSuite 是面向 Mac 的多格式文件工作台，把预览、检查、编辑与导出集中在一个应用中。

[官网与获取说明](https://xfilesuite.com/) · [问题反馈](mailto:support@xfilesuite.com) · [安全问题报告](SECURITY.md)

## 可以做什么

| 场景 | 代表能力 |
| --- | --- |
| 浏览文件 | 从 Finder、拖放或应用内打开文件；在目录中切换同类文件，查看最近文件。 |
| 图片与设计素材 | 预览常见图片、动图、SVG、PSD 和部分相机 RAW；对适用图片进行裁剪、色彩调整、涂鸦、量尺测量、切割与格式导出。PSD 是预览用途，不提供 PSD 图层编辑。 |
| 批量图片 | 为多张图片设置导出格式、尺寸与质量；使用图片模板绑定 CSV/XLSX 文本字段，按记录生成图片。 |
| 图片序列 | 拆分和调整序列帧，再导出为支持的图片或动画格式。 |
| 音频 | 查看波形，框选、试听并分别导出多个片段；转换支持的音频格式。批量音频转换受 VIP 权限控制。 |
| 视频 | 播放视频及透明画面，切换可用音轨和字幕；截取当前片段为 MP4，或将多个片段组合导出为 GIF、动态 WebP；也可导出视频中的音频片段。 |
| PDF 与文档 | 阅读 PDF、添加标注和涂鸦，导出页面图片或新 PDF；预览和编辑 Markdown，并导出 DOCX；预览已有 DOCX，按当前预览导出 PDF。已有 DOCX 不在应用内编辑。 |
| 结构化数据 | 折叠、搜索和编辑 JSON、XML、YAML；以表格查看和编辑 UTF-8 CSV。JSONL 提供分页记录浏览与搜索，不作为整份可编辑文档处理。 |

不同格式的**预览、编辑、转换和导出**能力并不相同。能打开文件，不代表可以编辑原格式或导出为任意格式；结果也取决于文件内容、编码、系统环境和当前版本。

## 获取与平台

当前公开介绍以 **macOS 13 及以上版本**为准。发行状态、实际可用的获取渠道与系统要求，请以[官网](https://xfilesuite.com/)的最新说明为准。本仓库的 Releases 还包含第三方原生依赖的发布记录，列表中的“Latest”不一定是 XFileSuite App 安装包。

Windows 构建目前未作为可获取版本在这里提供；请不要根据旧版介绍或依赖发布记录推断已有 Windows 安装包。

## 本仓库

这里是 XFileSuite 的**公开发布仓库**，保存历史发布文件及第三方原生依赖的公开清单。App 源代码在私有仓库 `XFileSuiteSource`；本仓库不是可直接克隆构建的完整 App 源码。发布构建与依赖同步由 [`XFileSuiteNativeDeps`](https://github.com/XFileSuite/XFileSuiteNativeDeps) 维护。

XFileSuite 主程序为专有软件；第三方组件分别遵循各自的许可证。发现安全问题请参阅 [SECURITY.md](SECURITY.md)，普通使用反馈请发送至 [support@xfilesuite.com](mailto:support@xfilesuite.com)。
