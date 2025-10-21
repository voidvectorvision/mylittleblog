---
title: "PaperMod 功能测试文档"
subtitle: "示例文章：段落、标题、目录、代码与图片"
date: 2025-10-19T12:00:00+08:00
description: "摘要：测试 Hugo + PaperMod 的 Markdown 渲染、目录生成、代码高亮与多级标题表现。"
tags: ["测试", "Markdown", "PaperMod"]
categories: ["示例"]
showtoc: true
tocopen: false
---

## 一、引言

这是一个用于测试 **Hugo PaperMod** 渲染效果的示例文档。  
它包含常见的 Markdown 元素：标题、列表、引用、代码、表格与图片。  

> “冰上的苔藓仍在生长。” —— IceMoss

---

## 二、段落与文本样式

普通文本、**加粗**、*斜体*、`行内代码`。  
下面是分段测试：

这是第一段。  
换行后继续第二段。  
最后一段收尾。

---

## 三、列表与引用

### 无序列表
- 北极光  
- 苔藓  
- 寒风  

### 有序列表
1. 初始化 Hugo 项目  
2. 安装 PaperMod 主题  
3. 部署到 Cloudflare Pages  

### 嵌套列表
- 摄影设备：
  - Fuji X100V
  - iPhone 15 Pro Max

---

## 四、代码块与语法高亮

### Bash 示例
```bash
hugo new site myblog
cd myblog
git submodule add https://github.com/adityatelange/hugo-PaperMod themes/PaperMod
hugo server -D
