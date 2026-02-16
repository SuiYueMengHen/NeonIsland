# NeonIsland 🏝️🎵

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Web_Audio_API-FF6B6B?style=for-the-badge&logo=web-audio-api&logoColor=white" alt="Web Audio API">
</p>

**NeonIsland** 是一个基于原生 HTML/CSS/JS 构建的单文件音乐播放器。它复刻了 iOS 灵动岛的交互体验，支持自由拖拽、边缘吸附、实时音频可视化以及毛玻璃拟态设计。无需构建工具，直接在浏览器中运行，轻量且高效。


---

## ✨ 核心特性

- **🏝️ 灵动岛交互**
  - 支持展开、收缩、迷你三种形态。
  - 智能点击判定：区分拖动操作与点击展开。

- **🖐️ 自由拖拽与吸附**
  - 支持鼠标和触摸屏拖动。
  - 拖动阈值判定，防止误触。
  - 松手自动吸附到屏幕最近边缘，带弹性动画。

- **🎧 真实音频体验**
  - 基于 Web Audio API 的实时频谱可视化。
  - 支持添加本地音乐文件 (MP3, WAV, FLAC, OGG, M4A 等)。
  - 完整的播放控制：播放/暂停、切歌、进度条、音量调节。
  - 循环模式：单曲循环、列表循环、随机播放。

- **🎨 现代视觉设计**
  - 霓虹渐变配色。
  - 高斯模糊毛玻璃效果。
  - 动态封面背景模糊。

- **⚡ 性能优化**
  - 使用 `requestAnimationFrame` 进行渲染。
  - CSS 硬件加速。
  - 单文件架构，无依赖加载。

---

## 🚀 快速开始

1.  克隆仓库或下载 `index.html` 文件。

```bash
git clone https://github.com/SuiYueMengHen/NeonIsland.git
```
2.  直接在浏览器中打开 `index.html`。
3.  点击“添加音乐”按钮，选择本地音频文件即可开始播放。

---

## 🛠️ 技术栈

- **HTML5**: 语义化结构。
- **Tailwind CSS (CDN)**: 快速样式构建与响应式布局。
- **Vanilla JavaScript**: 原生 JS 实现所有逻辑，无框架依赖。
- **Web Audio API**: 实现音频分析与可视化。
- **Canvas API**: 绘制实时频谱。

---

## 📝 待办事项

- [ ] 支持歌词解析与显示。
- [ ] 增加 PWA 支持，实现离线缓存。
- [ ] 支持从 URL 拖拽文件上传。

---

## 👤 作者

**SuiYueMengHen**

- GitHub: [@SuiYueMengHen](https://github.com/SuiYueMengHen)

---

## 📄 许可证

本项目基于 [MIT](LICENSE) 许可证开源。
    