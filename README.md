# 地铁线路图绘制工具 · 官网

> Metro Line Map Drawing Tool · Official Landing Website

---

<div align="center">

🌐 **在线访问**：https://zeenyonug.github.io/Metro-Line-Map-Drawing-Tool-gw/  
🎨 **编辑器应用**：https://zeenyonug.github.io/Metro-Line-Map-Drawing-Tool/  
💻 **主仓库**：https://github.com/zeenyonug/Metro-Line-Map-Drawing-Tool

</div>

---

## 📖 介绍 · Introduction

本仓库是「地铁线路图绘制工具」的**官方宣传网站（Landing Page）**源码，使用纯 HTML/CSS/JS 单文件实现，零依赖、零构建。

This repository contains the **official landing page** source code for the Metro Line Map Drawing Tool, implemented as a single zero-dependency HTML file with no build step.

## ✨ 特性 · Features

| 特性 · Feature | 说明 · Description |
|---|---|
| 🎬 滚动驱动动画 · Scroll-driven Animations | 随滚动进度逐步展示站点放置、线路绘制、环线换乘、线路类型、主题切换、导出等功能场景 |
| 🌐 中英双语切换 · Bilingual (CN/EN) | 左上角一键切换中英文，所有文案与标签实时同步 |
| 🎨 统一主题色 · Unified Accent | 采用主编辑器相同的琥珀色主题 `#f59e0b` + 深蓝背景 `#0f172a` |
| 🔒 防复制与选中 · Anti-copy / Anti-select | 全站禁止文本选中、右键菜单、复制剪切粘贴、双击缩放、放大镜手势、Ctrl+F 查找高亮等 |
| 🚫 文本不换行 · No Text Wrap | 所有文本元素默认不换行，保证视觉整洁 |
| 📱 响应式布局 · Responsive | 自适应桌面 / 平板 / 移动设备 |
| 🧭 固定 GitHub 位置 · Fixed GitHub Placement | GitHub 链接仅出现在页脚，不占据顶部导航黄金位 |

## 🏗️ 本地预览 · Local Preview

由于是纯静态单文件，直接用浏览器打开即可：

Since it is a pure static single file, just open it directly in the browser:

```bash
# 方式 1：双击 index.html
# Option 1: Double-click index.html

# 方式 2：用 Python 启动本地服务器（推荐，避免部分浏览器限制）
# Option 2: Start a local HTTP server (recommended)
cd Metro-Line-Map-Drawing-Tool-gw
python -m http.server 8080
# 然后打开 / Then visit: http://localhost:8080
```

## 🚀 部署 · Deployment

本仓库已内置 **GitHub Pages 自动部署工作流**（`.github/workflows/pages.yml`）：

This repository ships with a **GitHub Pages auto-deploy workflow** (`.github/workflows/pages.yml`):

1. **推送到 `main` 分支** 即自动触发部署
   **Push to `main`** automatically triggers deployment.

2. **首次需手动启用 Pages**：仓库 Settings → Pages → Build and deployment → Source 选择 **GitHub Actions**
   **One-time Pages enablement**：Repo Settings → Pages → Build and deployment → Source = **GitHub Actions**

3. 等待 1~2 分钟，即可通过 `https://zeenyonug.github.io/Metro-Line-Map-Drawing-Tool-gw/` 访问
   Wait 1-2 minutes, then visit the URL above.

> 手动触发：Actions → Deploy to GitHub Pages → Run workflow
> Manual trigger：Actions → Deploy to GitHub Pages → Run workflow

## 🗂️ 目录结构 · Structure

```
Metro-Line-Map-Drawing-Tool-gw/
├── .github/
│   └── workflows/
│       └── pages.yml          # Pages 自动部署工作流 · Auto-deploy workflow
├── index.html                 # 官网单文件（HTML + CSS + JS 内联）· Single-file Landing Page
└── README.md                  # 本文件 · This file
```

## 🔗 相关链接 · Links

| 项目 · Project | 链接 · Link |
|---|---|
| 🎨 主应用仓库 · Editor App Repo | https://github.com/zeenyonug/Metro-Line-Map-Drawing-Tool |
| 🚀 主应用在线版 · Live Editor | https://zeenyonug.github.io/Metro-Line-Map-Drawing-Tool/ |
| 🌐 本仓库官网 · This Landing Page | https://zeenyonug.github.io/Metro-Line-Map-Drawing-Tool-gw/ |

## 📄 协议 · License

与主项目保持一致 © zeenyonug

Consistent with the main project © zeenyonug