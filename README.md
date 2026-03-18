# Vibe Coding 使用指南

本仓库用于整理 Vibe Coding 相关环境配置与使用说明，适合作为统一入口文档。

> **重要提示**：国内用户请先配置代理访问，并建议开启代理的 **TUN 模式**。

## 文档导航

### 基础环境配置
- [Vibe Coding 使用指南](#vibe-coding-使用指南)
  - [文档导航](#文档导航)
    - [基础环境配置](#基础环境配置)
    - [详细使用文档](#详细使用文档)
    - [仓库结构](#仓库结构)
  - [网络环境配置](#网络环境配置)
  - [安装 VSCode](#安装-vscode)
  - [安装 VSCode 插件](#安装-vscode-插件)
  - [安装 cc-switch 并配置](#安装-cc-switch-并配置)
  - [基础环境完成后怎么继续](#基础环境完成后怎么继续)
  - [更多资源](#更多资源)

### 详细使用文档
- [cc-switch 安装与配置指南](cc-switch/cc-Switch.md)
- [Codex 安装配置，使用指南](Codex/Codex.md)
- [Claude Code 安装配置，使用指南](Claude/Claude.md)

### 仓库结构
- [README.md](README.md)：总入口与快速开始
- [cc-switch/cc-Switch.md](cc-switch/cc-Switch.md)：cc-switch 安装与配置
- [Codex/Codex.md](Codex/Codex.md)：Codex 插件配置与使用
- [Claude/Claude.md](Claude/Claude.md)：Claude Code 配置与使用

---

## 网络环境配置

在开始之前，请先确认网络环境可用：

- 确保代理正常运行
- 建议启用代理的 **TUN 模式**

| 代理配置 | TUN 模式 |
|:--------:|:--------:|
| ![代理配置](IMG/clash.png) | ![TUN 模式](IMG/clash1.png) |

---

## 安装 VSCode

VSCode 下载地址：

https://code.visualstudio.com/docs/setup/mac

---

## 安装 VSCode 插件

安装步骤：

1. 打开 VSCode
2. 按 `Cmd + Shift + X` 打开扩展面板
3. 搜索并安装以下插件

| 插件名称 | 说明 |
|---------|------|
| **Claude Code for VS Code** | Claude 官方插件 |
| **Codex** | OpenAI Codex 插件 |

可选：安装中文语言包，搜索 `Chinese (Simplified)`。

![安装 VSCode 所需插件](Codex/IMG/image.png)

---

## 安装 cc-switch 并配置

cc-switch 用于接入和切换模型配置，建议先完成安装与基础设置：

- [cc-switch 安装与配置指南](cc-switch/cc-Switch.md)

---

## 基础环境完成后怎么继续

完成以上步骤后，可以按需阅读对应文档：

- [Codex 安装配置，使用指南](Codex/Codex.md)：适合需要配置 Codex 插件的用户
- [Claude Code 安装配置，使用指南](Claude/Claude.md)：适合需要配置 Claude Code 的用户

如果你是首次搭建环境，建议阅读顺序如下：

1. 先完成本页基础环境配置
2. 再阅读 [cc-switch 安装与配置指南](cc-switch/cc-Switch.md)
3. 最后按需选择：
   - [Codex 安装配置，使用指南](Codex/Codex.md)
   - [Claude Code 安装配置，使用指南](Claude/Claude.md)

---

## 更多资源

待补充。
