---
title: "用 Hugo 搭建个人博客"
date: 2026-06-26T10:00:00+08:00
draft: false
tags: ["Hugo", "博客", "GitHub Pages"]
categories: ["技术"]
summary: "从零开始用 Hugo 搭建一个漂亮的个人博客，并部署到 GitHub Pages。"
---

## 为什么选择 Hugo？

Hugo 是一个用 Go 语言编写的静态网站生成器，以极快的构建速度著称。

### 优点

- **速度极快**：毫秒级构建
- **主题丰富**：大量高质量主题可选
- **部署简单**：天然适合 GitHub Pages

### 快速开始

```bash
# 安装 Hugo
go install -tags extended github.com/gohugoio/hugo@latest

# 创建新站点
hugo new site my-blog
cd my-blog

# 添加主题
git submodule add https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod

# 本地预览
hugo server
```

就这么简单！
