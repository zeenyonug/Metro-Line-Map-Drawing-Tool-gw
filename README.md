# 地铁线路图绘制工具 - 官网

Metro Line Map Drawing Tool - Official Landing Website

---

## 介绍

本仓库是「地铁线路图绘制工具」的官方宣传网站源码，使用纯 HTML/CSS/JS 单文件实现，零依赖、零构建。

This repository contains the official landing page source code for the Metro Line Map Drawing Tool, implemented as a single zero-dependency HTML file with no build step.

## 特性

- 滚动驱动动画，随滚动进度逐步展示编辑器核心功能
- 中英双语实时切换，所有文案同步更新
- 统一琥珀色主题 `#f59e0b` + 深蓝背景
- 全站禁止文本选中、右键菜单、复制剪切、双击缩放
- 文本不换行，保证视觉整洁
- 响应式布局，自适应桌面/平板/移动设备
- GitHub 链接仅出现在页脚

## 本地预览

```bash
# 直接双击 index.html 打开
# 或用 Python 启动本地服务器
cd Metro-Line-Map-Drawing-Tool-gw
python -m http.server 8080
```

## 部署

通过 GitHub Pages 部署，Source 选择 Deploy from branch，Branch 选择 main / /(root)。

Deploy via GitHub Pages: Settings -> Pages -> Source = Deploy from branch -> Branch = main / /(root).

## 目录结构

```
Metro-Line-Map-Drawing-Tool-gw/
├── index.html     # 官网单文件（HTML + CSS + JS 内联）
└── README.md      # 本文件
```

## 相关链接

| 项目 | 链接 |
|---|---|
| 主应用仓库 | https://github.com/zeenyonug/Metro-Line-Map-Drawing-Tool |
| 本仓库官网 | https://zeenyonug.github.io/Metro-Line-Map-Drawing-Tool-gw/ |

## 协议

© zeenyonug
