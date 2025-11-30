# 网易云音乐官网重构

## 📖 项目简介

这是一个**网易云音乐官网的前端静态页面重构项目**，完整复刻了网易云音乐 PC 端官网的首页，包括顶部导航栏、轮播图、推荐内容、排行榜等核心模块。项目注重还原官网 UI 细节，实现了像素级的页面布局和交互效果。

## 🖼️ 项目展示

### 首页效果

![网易云音乐首页](https://raw.githubusercontent.com/ljm399/html-css/refs/heads/main/doc/images/Snipaste_2025-11-30_10-44-18.png)

## 🛠️ 技术栈

### 核心技术

- **HTML5**：语义化标签（header、nav、section、footer 等）
- **CSS3**：Flexbox 布局、定位、伪元素、过渡动画
- **CSS Sprites**：雪碧图技术优化图片加载性能

### 技术亮点

- **模块化 CSS**：将样式拆分为多个 CSS 文件（topbar、carousel、main 等）
- **CSS Reset**：消除浏览器默认样式差异
- **Sprite 图技术**：合并小图标减少 HTTP 请求
- **BEM 命名规范**：清晰的 CSS 类名结构
- **语义化 HTML**：利于 SEO 和可访问性

## 📚 优化

- ✅ HTML5 语义化标签的正确使用
- ✅ CSS 布局技巧（浮动、定位、Flexbox）
- ✅ CSS Sprites 雪碧图优化技术
- ✅ 模块化 CSS 的组织方式
- ✅ 前端性能优化基础
- ✅ 页面细节还原能力
- ✅ SEO 优化基础知识

## 🚀 快速开始

### 方式一：直接打开

1. 克隆或下载项目到本地
2. 直接双击 `index.html` 文件在浏览器中打开

### 方式二：使用 Live Server（推荐）

1. 安装 VS Code 插件 [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
2. 右键点击 `index.html`，选择 "Open with Live Server"
3. 项目将在 `http://127.0.0.1:5500` 启动

### 方式三：使用 http-server

```bash
# 全局安装 http-server
npm install -g http-server

# 在项目目录运行
http-server

# 访问 http://localhost:8080
```
