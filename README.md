<div style="display:flex;justify-content:center;align-items:center;gap:10px">
  <h1 align="center">BiliNote 威力加强版 v0.1.0</h1>
</div>

<p align="center"><i>AI 视频笔记工作台 · 批量处理 · 智能教程 · 个人知识库</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/平台-Windows%2010%20%7C%2011-0078D4" />
  <img src="https://img.shields.io/badge/安装方式-一键安装-success" />
  <img src="https://img.shields.io/badge/Docker-无需安装-2496ED" />
  <img src="https://img.shields.io/badge/版本-0.1.0-7C3AED" />
  <img src="https://img.shields.io/badge/状态-持续迭代-success" />
</p>

<p align="center">
  <a href="https://github.com/987161661/bilinote-V/releases"><b>🚀 下载 BiliNote 威力加强版</b></a>
</p>

<p align="center">
  <b>不需要 Docker，不需要配置 Python / Node.js。</b><br/>
  下载 Windows 安装包、双击安装、填入自己的模型 API Key，即可开始使用。
</p>

## ✨ 项目简介

**BiliNote 威力加强版** 基于 BiliNote 原版能力扩展而来。

原版解决的是「把一条视频转成笔记」；威力加强版进一步解决「如何持续处理视频、检查笔记质量、按主题归档，并在需要时找回知识」。它将新建笔记、批量任务、合集、知识库、智能体与用量监控整合到统一工作台中。

支持哔哩哔哩、YouTube、本地视频、抖音、快手等来源；生成 Markdown 笔记后，仍可校对、编辑、预览、导出与归档。

## 📦 桌面版下载

前往 [Releases](https://github.com/987161661/bilinote-V/releases) 下载最新的 Windows `.exe` 安装包。

安装完成后从开始菜单启动 **BiliNote 威力加强版** 即可。应用已内置后端与 FFmpeg；无需 Docker，也不会占用或修改原版 BiliNote 的数据。

> 💡 首次使用时只需在「AI 模型设置」中配置自己的模型供应商和 API Key。本地 Whisper 模型会在需要时下载；也可以选用在线转写服务。

## 🔧 功能特性

### 保留原版核心能力

- 支持 Bilibili、YouTube、本地视频、抖音、快手等多平台视频
- 支持 Markdown 笔记、原片跳转、原片截图、目录与 AI 总结
- 支持视觉理解、多种笔记风格、中文 / 英文输出
- 支持自行配置 MiniMax CN、DeepSeek 等模型供应商
- 支持本地 Faster Whisper 与在线转写器

### 威力加强版新增

- **工作台**：左侧常驻入口，统一进入新建笔记、合集、知识库、批量任务、用量监控和智能体管理
- **批量任务**：仿视频站的视频流浏览、搜索、分区、分页、关注创作者与处理队列；点击标题即可加入队列
- **队列与状态保持**：查看处理进度、失败重试、已处理绿勾、重新加入；跨页面切换仍保留工作状态
- **合集**：创建主题合集，三栏查看已收录笔记与未收录笔记，预览后仍可编辑、校对、导出、移除
- **知识库**：将沉淀笔记纳入知识库并进行问答
- **智能体管理**：集中配置 AI 解析、校对、知识库问答智能体的模型、标签、Skills 与高级 API 参数
- **AI 校对栏**：疑点在原文中红色高亮；点击后在最右侧查看修正建议，不会自动覆盖原稿
- **用量监控**：查看云端模型 API 调用消耗
- **智能教程**：替代原「教程」风格；先规划读者目标与可执行路径，再生成教程，并校正高置信度的转写术语错误
- **配置复用**：批量处理自动继承新建笔记的语言、目录、截图、AI 总结、视觉理解与输出规格

### v0.1.0 新增

- 发布 **BiliNote 威力加强版** Windows 一键安装包
- 无 Docker 桌面运行：前端、后端与 FFmpeg 随安装包提供
- 用户数据统一保存至 `%LOCALAPPDATA%\BiliNote-Power`
- 启动时自动检查 GitHub Releases；检测到新版本时显示更新按钮

## 🚀 快速开始

1. 在 [Releases](https://github.com/987161661/bilinote-V/releases) 下载最新 `.exe`。
2. 双击运行安装程序，按向导完成安装。
3. 启动应用，前往「AI 模型设置」添加模型供应商与 API Key。
4. 在「新建笔记」粘贴视频链接，或在「批量任务」中建立处理队列。

## ❓ 常见问题

### 是否需要 Docker？

不需要。威力加强版是桌面安装版，后端会随应用启动和关闭。

### 数据会上传吗？

笔记、截图、模型、账号授权与配置默认存于本机 `%LOCALAPPDATA%\BiliNote-Power`。调用你配置的云端模型时，相关内容会按该模型供应商的 API 请求发送。

### 为什么首次转写需要等待？

本地转写首次使用会下载 Whisper 模型。可先选 tiny / base 模型快速体验，或改用在线转写器。

### 如何更新？

应用启动时会检测本仓库 Releases；出现「发现新版本，立即更新」后，点击按钮下载新版安装包并覆盖安装即可。

## 📜 License

本项目基于原版 BiliNote 的 MIT License 进行功能扩展与桌面发行。

---

💬 欢迎通过 Issue 提交使用反馈与改进建议。
