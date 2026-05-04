# ZOPO Suggestion Platform (website-suggestion)

这是一个为 ZOPO 公司内部成员设计的建议分享平台示例。

功能概览：
- 登录 / 注册（示例用户已预置）
- 新用户介绍页面
- 发布建议（标题、内容、分类）
- 帖子 feed（点赞、回复、过滤）
- 多语言支持（中文 / English / Português）
- 内置翻译按钮（页面内切换展示）
- 页面动画与微交互

如何在本地查看：
1. 在浏览器中打开 `website-suggestion.html`（不需要服务器，双击或在浏览器中打开本文件）。
2. 若需要通过 HTTP 服务运行，可使用简单的静态服务器，例如 Python：

```powershell
# Python 3
python -m http.server 8000
# 然后在浏览器打开 http://localhost:8000/website-suggestion.html
```

提交与部署：
- 本仓库可以直接推送到 GitHub，并启用 GitHub Pages 来托管静态页面（Settings → Pages）。

注意：当前实现为前端静态演示，未包含服务器端鉴权或持久化存储。若要用于生产，请添加后端认证、数据库存储和安全策略。

---

README (English)

A simple internal suggestion platform prototype for ZOPO.

Quick start:
- Open `website-suggestion.html` in your browser.
- Or serve via a static server (Python example above).

This repository contains only a client-side demo. For production usage, implement backend auth and persistence.
