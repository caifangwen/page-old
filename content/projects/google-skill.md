---
title: 'Google Family Bucket Skill'
date: 2026-05-08T18:00:00+08:00
draft: false
slug: google-skill
description: "一套覆盖 Google Workspace 全家桶的 Claude Prompt 技能库，60+ 精心设计的提示词，将 Gmail、Calendar、Drive、Docs 等工具与 AI 深度整合。"
summary: "Google Workspace 全家桶 Claude Prompt 完全手册，60+ 提示词覆盖邮件、日程、文档、表格、演示、任务等全场景。"
featured: true
tags:
  - project
  - google
  - claude
  - prompt
  - productivity
categories:
  - projects
cover: ""
github: ""
demo: "https://www.261449.xyz/google-skill/"
website: "https://www.261449.xyz/google-skill/"
tech_stack:
  - Claude
  - Google Workspace
  - Prompt Engineering
status: "completed"
---

## 项目概述

**Google Family Bucket Skill** 是一套专为 Google Workspace 用户设计的 Claude Prompt 技能库。项目将 Gmail、Calendar、Drive、Docs 等核心工具与 Claude AI 深度整合，通过 60+ 精心打磨的提示词，让日常办公流程实现自动化与智能化。

项目地址：[https://www.261449.xyz/google-skill/](https://www.261449.xyz/google-skill/)

## 核心亮点

- **全家桶覆盖**：10 大 Google 工具，从邮件到联系人无一遗漏
- **场景化设计**：每个 Prompt 对应真实办公场景，开箱即用
- **跨工具联动**：10 个集成工作流，打通工具间的数据壁垒
- **移动优先**：专设移动端场景 Prompt，适配碎片时间处理

## 模块详解

### 📧 Gmail（6 Prompts）
| 功能 | 说明 |
|------|------|
| 收件箱概览 | 快速总结未读邮件优先级 |
| 搜索邮件 | 自然语言定位历史邮件 |
| 未读邮件整理 | 自动分类与批量归档建议 |
| 起草回复 | 根据上下文生成专业回复草稿 |
| 新建邮件 | 从要点扩写成完整邮件 |
| 移动场景 | 语音/快速输入场景下的邮件处理 |

### 📅 Calendar（7 Prompts）
| 功能 | 说明 |
|------|------|
| 今日日程 | 晨间日程概览与准备提醒 |
| 本周概览 + 空闲时间 | 周计划梳理与可预约时段分析 |
| 下周预览 | 提前规划下周重点事项 |
| 创建事件 | 从对话中提取信息自动生成日程 |
| 修改/删除事件 | 自然语言调整已有日程 |
| 移动场景 | 外出时的快速日程查询与调整 |

### 💾 Drive（5 Prompts）
搜索文件、最近文件概览、整理建议、读取文档内容、保存到 Drive。

### 📝 Docs（5 Prompts）
文档摘要、对比两个文档、起草新文档、润色文档、会议纪要生成。

### 📊 Sheets（6 Prompts）
读取表格数据、数据查询、更新单元格、追加新行、数据分析、自动周报表格。

### 🎨 Slides（3 Prompts）
演示文稿摘要、生成演示大纲、生成演讲备注。

### ✅ Tasks（6 Prompts）
今日任务列表、本周任务概览、快速/批量添加任务、标记完成、移动场景。

### 📋 Forms（3 Prompts）
表单响应总结、筛选特定答案、设计表单结构。

### 💬 Chat（3 Prompts）
搜索消息、发送消息、未读消息概览。

### 👥 Contacts（4 Prompts）
搜索联系人、生日提醒、更新联系人、整理重复联系人。

## 集成工作流（10 Workflows）

跨工具联动是项目的核心价值。以下工作流将多个 Google 工具串联成自动化流水线：

1. **晨间智能简报** — 日历 + 邮件 + 任务，一键生成每日概览
2. **会前准备** — 从日历提取会议，自动检索相关邮件与文档
3. **会后整理** — 根据会议内容生成待办任务并写入 Tasks
4. **项目周报** — 汇总 Tasks 完成项 + Sheets 数据，自动生成周报文档
5. **任务拆解** — 将项目目标拆解为 Calendar 事件 + Tasks 子任务
6. **邮件转日程** — 识别邮件中的时间信息，自动创建 Calendar 事件
7. **日程汇总邮件** — 将下周日程整理为邮件，发送给相关方
8. **周末规划** — 结合 Tasks 与 Calendar，生成周末安排建议
9. **旅行准备** — 邮件确认单 + 日程 + 联系人，生成出行清单
10. **每日收尾** — 回顾当日邮件、任务、日程，生成次日待办

## 使用方式

每个 Prompt 均为独立 Markdown 文件，包含：
- **使用场景**：明确该 Prompt 解决什么问题
- **输入示例**：期望用户提供的信息格式
- **Prompt 正文**：可直接复制到 Claude 使用的完整提示词
- **输出示例**：AI 返回结果的参考样式

## 适用人群

- **职场人士**：日常重度依赖 Google Workspace 的办公用户
- **项目经理**：需要跨工具协调日程、任务、文档的协作者
- **效率极客**：追求 AI 工具链整合的自动化爱好者
- **远程团队**：分布式团队中的异步沟通与信息管理

## 相关链接

- **项目主页**：[https://www.261449.xyz/google-skill/](https://www.261449.xyz/google-skill/)
- **关联主题**：[Frida Home](https://www.261449.xyz/) — 基于 Tailwind CSS 4.0 的 Hugo 主题
