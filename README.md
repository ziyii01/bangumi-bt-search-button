# Bangumi → Mikan 搜索按钮

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

在 [Bangumi（bgm.tv）](https://bgm.tv) 动画条目页面的标题旁，一键跳转至 **蜜柑计划（Mikan Project）** 的搜索结果页，快速查找资源！

> 🌟 无需复制粘贴，告别手动搜索！支持 `mikanani.me` 和 `mikanime.tv` 双站点。

---

## 🔧 快速安装

点击下方按钮，使用 [Tampermonkey](https://www.tampermonkey.net/) 或 [Violentmonkey](https://violentmonkey.github.io/) 一键安装本脚本：

<a href="https://raw.githubusercontent.com/ziyii01/bangumi-bt-search-button/main/bangumi-bt-search-button.user.js">
  <img src="https://custom-icon-badges.demolab.com/badge/-/Install%20with%20Tampermonkey-FF6F61?style=for-the-badge&logo=tampermonkey&logoColor=white" alt="Install with Tampermonkey">
</a>

> 💡 **提示**：请确保已安装用户脚本管理器（如 Tampermonkey）。若按钮无效，请手动下载 [`bangumi-mikan-search.user.js`](https://github.com/ziyii01/bangumi-bt-search-button/raw/main/bangumi-mikan-search.user.js) 并打开。

---

## 🚀 主要功能

- ✅ 自动识别当前 Bangumi 条目的动画名称（从 `<h1>` 标题中提取）
- ✅ 在标题右侧添加醒目下拉按钮 **“🔍 Mikan 搜索 ▼”**
- ✅ 点击后展开菜单，支持一键跳转至：
  - [mikanani.me](https://mikanani.me)
  - [mikanime.tv](https://mikanime.tv)
- ✅ 所有链接在新标签页中打开，安全无跳转干扰
- ✅ 响应式设计，适配 Bangumi 现有页面布局

---

## 🖼️ 效果预览

> ![示例截图](https://raw.githubusercontent.com/ziyii01/bangumi-bt-search-button/main/screenshots/PixPin_2025-12-12_14-07-41.png)

---

## 🌐 兼容性

| 浏览器  | 用户脚本管理器 | 支持        |
| ------- | -------------- | ----------- |
| Chrome  | Tampermonkey   | ⚠️ 我没试过 |
| Firefox | Violentmonkey  | ⚠️ 我没试过 |
| Edge    | Tampermonkey   | ✅          |

> 脚本仅在 `https://bgm.tv/subject/*` 页面激活。

---

## 📜 许可证

本项目采用 [GNU Affero General Public License v3.0 (AGPL-3.0)](LICENSE) 开源协议。

```text
Copyright (C) 2025 ziyii

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.
```

---

## 🙌 贡献与反馈

欢迎提交 Issue 或 Pull Request！如果你有以下想法，非常欢迎参与：

- 添加更多 BT/磁力站支持（如 Nyaa、ACG.RIP 等）
- 支持 Bangumi 别名/罗马音自动匹配
- 优化移动端体验

---

> Made with ❤️ for Bangumi & Mikan users.
