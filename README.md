# 极简全网视频解析 (Minimalist Video Parser)

一个基于现代极简主义设计的静态网页工具，旨在提供纯净、无广告的全网视频解析体验。

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen.svg)
![Theme](https://img.shields.io/badge/theme-Glassmorphism-indigo.svg)

## ✨ 项目亮点

- 🎨 **极简视觉设计**：采用毛玻璃效果 (Glassmorphism) 与现代排版，视觉大方美观。
- 🌓 **双模式切换**：默认开启 **暗黑模式**，支持通过悬浮按钮实时切换明亮/暗黑主题。
- 📱 **完美适配移动端**：针对手机浏览器优化，统一交互控件高度，触控体验极佳。
- 🎬 **影院模式自适应**：解析成功后，网页容器平滑放宽，自动滚动至播放区域。
- 🚀 **零依赖加载**：纯原生 HTML/CSS/JS 开发，引入 Google Fonts 与在线 SVG Favicon，加载速度极快。
- 🛠️ **多接口支持**：预设 12 个优质解析接口，覆盖全网主流视频平台。

## 🚀 快速开始

### 方案 A：直接运行
1. 下载仓库中的 `index.html` 文件。
2. 双击在浏览器中打开即可使用。

### 方案 B：GitHub Pages 部署 (推荐)
1. 将 `index.html` 上传至你的 GitHub 仓库。
2. 进入仓库设置 **Settings** -> **Pages**。
3. 选择 `main` 分支并保存，稍等片刻即可通过 `https://你的用户名.github.io/项目名/` 访问。

## 🛠️ 技术栈

- **Core**: HTML5, CSS3, JavaScript (ES6+)
- **Fonts**: [Google Fonts](https://fonts.google.com/) (Inter & Noto Sans SC)
- **Icons**: Inline SVG Data URI

## 📸 功能预览

- **输入**: 粘贴各大视频网站 (爱优腾、B站等) 的播放页链接。
- **解析**: 点击“立即解析”，系统将调用预设接口进行无广告播放。
- **交互**: 
  - 右下角悬浮按钮一键切换昼夜模式。
  - 支持回车键快速触发解析。

## 📋 支持平台

本工具仅作为前端 UI 集合，解析能力由第三方接口提供，通常支持：
- 腾讯视频、爱奇艺、优酷、哔哩哔哩 (Bilibili)、芒果TV、搜狐视频、PP视频等。

## ⚖️ 免责声明

1. 本项目仅供前端网页设计交流与技术学习使用，不存储任何视频资源，不参与任何视频解析过程。
2. 网页所引用的解析接口均来自互联网，版权归原作者所有。
3. 请勿将本项目用于任何商业用途，因使用产生的任何法律责任由使用者自行承担。

## 📄 开源协议

本项目遵循 [MIT License](LICENSE) 协议。