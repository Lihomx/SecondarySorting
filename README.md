# 📦 二次分拣系统 · Secondary Sorting System

> 仓库 SKU 条码扫描分拣工具，支持语音播报（中文/西语），数据备份到 GitHub。  
> 无需安装，手机/PDA/电脑浏览器直接使用。

[![GitHub Pages](https://img.shields.io/badge/部署-GitHub%20Pages-blue)](https://你的用户名.github.io/你的仓库名)
![单文件](https://img.shields.io/badge/架构-单文件%20HTML-green)
![无依赖](https://img.shields.io/badge/依赖-零依赖-brightgreen)

---

## ✨ 功能特点

- 🔍 **扫描枪直连** — 扫码自动回车，零延迟响应
- 🧺 **自动分配篮子** — 新 SKU 自动创建并分配下一个篮子编号
- 🔊 **语音播报** — 朗读篮子编号，支持中文 / 西班牙语
- 📱 **移动端优化** — 适配手机和 PDA，大按钮易触控
- 💾 **GitHub 备份** — 一键将数据备份到指定仓库的 `backup/` 文件夹
- 🌙 **深色主题** — 仓库环境护眼，工业风设计

## 📖 文档

| 文档 | 说明 |
|------|------|
| [使用教程.md](./使用教程.md) | 操作手册，含扫描、语音、备份完整说明 |
| [开发日志.md](./开发日志.md) | 版本历史、技术选型、路线图 |

## 🚀 快速部署

1. Fork 本仓库
2. Settings → Pages → Branch: `main` → `/ (root)` → Save
3. 访问 `https://用户名.github.io/仓库名`

## 📁 目录结构

```
├── index.html     # 主程序（全部功能集成）
├── README.md      # 项目说明
├── 使用教程.md     # 操作手册
├── 开发日志.md     # 开发记录
└── backup/        # 备份文件自动存入此处
```

---

MIT License
