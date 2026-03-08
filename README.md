# Xiaohongshu Daoru for Obsidian

**Version**: 1.2.0  
**Author**: [jadewolf1978](https://github.com/jadewolf1978)  
**Repository**: [https://github.com/jadewolf1978/xiaohongshu-daoru](https://github.com/jadewolf1978/xiaohongshu-daoru)  
**License**: MIT

**[中文版本](#chinese-readme)** (Scroll to the Chinese version)

## Overview

**Xiaohongshu Daoru** (formerly Xiaohongshu Importer) is an enhanced Obsidian plugin that allows you to seamlessly import notes from Xiaohongshu (小红书) into your Obsidian vault. This tool is an optimized upgrade of the original importer, featuring **Live Photo support**, **improved tag formatting**, and **robust video extraction**.

With this plugin, you can extract note content, images, videos (including Live Photos), and tags, and organize them into categorized Markdown files.

## New Features in v1.2.0

- **Live Photo Support**: Automatically detects and extracts Live Photos as video files, preserving the dynamic content of your notes.
- **Auto Import Tags Support**: Fixes issues with deletion lines and trailing `#` characters when auto-importing tags, ensuring clean and usable Obsidian tags.
- **Improved Video Extraction**: Uses a recursive search algorithm to find video streams in complex JSON structures, ensuring higher success rates for video notes.

## Key Features

- **Import Xiaohongshu Notes**: Import via share link or text (supports `discovery/item`, `explore`, and short links).
- **Auto Import Tags**: Automatically extracts tags from note content and generates Obsidian-formatted tags.
- **Media Download**: Option to download images, videos, and Live Photos locally to your vault.
- **Category Management**: Organize notes into custom categories (e.g., "Travel", "Food").
- **Smart Formatting**: auto-cleans content and formats metadata in YAML frontmatter.

## Installation

### Manual Installation

1. Download the latest release `main.js`, `manifest.json`, `styles.css`, and `data.json`.
2. Create a folder named `xiaohongshu-daoru` in your vault's plugins directory: `<vault>/.obsidian/plugins/xiaohongshu-daoru/`.
3. Copy the files into this folder.
4. Enable **Xiaohongshu Daoru** in **Settings > Community Plugins**.

## Usage

1. **Trigger Import**: Click the ribbon icon or use the command "Import Xiaohongshu note".
2. **Paste Link**: Paste the share text/URL from Xiaohongshu.
3. **Select Options**: Choose category and whether to download media.
4. **Done**: The note is created with all content and media.

## Configuration

Go to **Settings > Community Plugins > Xiaohongshu Daoru** to:
- Set default download folder.
- Toggle default media download setting.
- Manage categories.

---

# 小红书导入 (Xiaohongshu Daoru) for Obsidian <a id="chinese-readme"></a>

**版本**：1.2.0  
**作者**：[jadewolf1978](https://github.com/jadewolf1978)  
**代码仓库**：[https://github.com/jadewolf1978/xiaohongshu-daoru](https://github.com/jadewolf1978/xiaohongshu-daoru)  
**许可证**：MIT

## 概述

**Xiaohongshu Daoru** 是一个小红书导入插件的**增强优化版**。它不仅支持将小红书笔记导入 Obsidian，还特别修复了格式问题并新增了对 **Live Photo（实况照片）** 的支持。

## v1.2.0 新增功能

- **支持 Live Photo**：自动检测并提取实况照片为视频文件，完整保留动态画面。
- **支持自动导入标签**：修复了自动导入标签时出现的删除线和尾部 `#` 号问题，生成干净的 Obsidian 标签。
- **增强视频提取**：采用递归查找算法，能从复杂的数据结构中精准找到视频流地址，大幅提高视频笔记的导入成功率。

## 主要功能

- **一键导入**：支持通过分享链接或文本导入笔记（支持短链、发现页链接等）。
- **自动导入标签**：自动从笔记内容中提取标签，并生成 Obsidian 格式的标签。
- **媒体下载**：可选择将图片、视频和 Live Photo 下载到本地。
- **分类管理**：自定义笔记分类（如“美食”、“旅行”）。
- **自动格式化**：自动清理正文干扰字符，生成规范的 YAML 元数据。

## 安装方法

### 手动安装

1. 下载最新的 `main.js`、`manifest.json` 、 `styles.css` 、`data.json` 文件。
2. 在您的 Obsidian 库插件目录中创建一个名为 `xiaohongshu-daoru` 的文件夹：`<vault>/.obsidian/plugins/xiaohongshu-daoru/`。
3. 将文件复制到该文件夹中。
4. 在 **设置 > 社区插件** 中启用 **Xiaohongshu Daoru**。

## 使用方法

1. **开始导入**：点击侧边栏图标或使用命令“Import Xiaohongshu note”。
2. **粘贴链接**：输入小红书的分享文本或链接。
3. **选择选项**：选择分类和是否下载媒体。
4. **完成**：笔记将自动生成并打开。

## 开发与贡献

欢迎提交 PR 或 Issue 来改进此工具！

1. Fork 本仓库。
2. 创建新分支进行修改。
3. 提交 PR。

**构建命令**：
```bash
npm install
npm run build
```
