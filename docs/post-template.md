---
title: 文章标题（必填）
date: 2026-08-27 09:00:00 +0800   # 必填，发布时间
categories: [QS]                  # 必填，分类（建议固定：QS / Contract / Engineering / Career）
tags: [boq, note]                 # 标签（可多个）
author: ShengMengping             # 可选，默认用站点配置
pin: false                        # true 则置顶到首页
toc: true                         # 是否显示右侧目录
math: false                       # true 则启用 LaTeX 公式
mermaid: false                    # true 则启用图表
image: /assets/img/posts/cover.jpg  # 可选：封面图（放 assets/img/posts/ 下）
description: 一句话摘要，用于搜索引擎和分享
comments: false                   # 评论（本站未启用）
---

## 小标题一

正文内容，直接写 Markdown 即可。

### 列表

- 项目一
- 项目二

### 代码块（自动语法高亮）

```python
print("Hello, world!")
```

### 插入图片

图片先放到 `assets/img/posts/` 目录，然后：

![图片说明](/assets/img/posts/你的图片.jpg)

### 引用

> 引用内容用 `>` 开头。

### 数学公式（需在 front matter 设 math: true）

行内公式 $E = mc^2$，独立公式：

$$ \int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2} $$

### 提示框（Chirpy 特色）

> 这是一条提示。
{: .prompt-tip }

> 这是一条警告。
{: .prompt-warning }

> 这是一条危险提示。
{: .prompt-danger }

## 结尾

写完后把本文件复制到 `_posts/` 目录，文件名改成 `YYYY-MM-DD-标题.md`（如 `2026-08-27-my-first-post.md`），commit 并 push 即可自动发布。
