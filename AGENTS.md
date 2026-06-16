# AGENTS.md

## 项目概述

基于 `m3u8-downloader` 命令行工具的 TUI 终端界面程序。

## 目录约定

- `app/` — 所有开发源码
- `doc/` — 项目文档

## 外部依赖

- `m3u8-downloader` — 已安装在 `/home/coder/.local/bin/m3u8-downloader`
  - 核心参数: `-url`, `-name`/`-o`, `-dir`/`-d`, `-threads`/`-n` (默认32), `-retries`/`-r`, `-force`/`-f`, `-keep`, `-insecure`/`-k`, `-cookie`, `-header`/`-H`, `-proxy`/`-p`
  - 该工具会自动生成 `config.json` 配置文件

## 仓库

- Git: `https://github.com/darkelfzdy/m3u8-tui.git`
- 主分支: `main`
