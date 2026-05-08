---
title: '红楼回忆志'
date: 2026-05-08T17:00:00+08:00
draft: false
slug: honglou
description: "基于 Godot 4 引擎开发的《红楼梦》题材独立游戏，融合角色扮演、策略经营与百人异步竞技，以 AI 行为树驱动的大观园世界。"
summary: "基于 Godot 4 的《红楼梦》题材独立游戏，Roguelike 机制、百人异步竞技、AI 行为树驱动角色生态。"
featured: true
tags:
  - project
  - godot
  - game
  - roguelike
  - pixel-art
categories:
  - projects
cover: ""
github: "https://github.com/caifangwen/honglou"
demo: "https://www.261449.xyz/honglou/"
website: "https://www.261449.xyz/honglou/"
tech_stack:
  - Godot 4
  - GDScript
  - Supabase
  - Docker
  - AI 生成工作流
status: "in_progress"
---

## 项目概述

**《红楼回忆志 · 大观园浮世录》** 是一款基于 Godot 4 引擎开发的《红楼梦》题材独立游戏。项目以贾府大观园为舞台，融合角色扮演、策略经营与异步竞技玩法，试图用 Roguelike 机制与 AI 行为树技术，重现百年前的繁华与沉浮。

项目主页：[https://www.261449.xyz/honglou/](https://www.261449.xyz/honglou/)  
GitHub 仓库：[https://github.com/caifangwen/honglou](https://github.com/caifangwen/honglou)

## 核心玩法

- **角色扮演**：扮演贾府成员，在大观园中经营日常、处理人际、参与诗社
- **策略经营**：资源管理、人员调度、庄园建设，维持贾府运转
- **异步竞技**：百人异步竞技场，与其他玩家的"影子"一较高下
- **Roguelike 元素**：每局随机事件、角色关系动态变化，重玩价值高

## 技术架构

### 游戏引擎
- **Godot 4**：核心游戏逻辑、UI 系统、瓦片地图（TileMap）、动画与物理
- **GDScript**：游戏玩法脚本、状态机、事件系统

### 后端与数据
- **Supabase**：云端数据库、用户认证、实时数据同步
- **Docker**：服务端容器化部署，支持快速扩缩容

### AI 系统
- **AI 行为树（Behavior Tree）**：驱动 NPC 日常决策与社交互动
- **状态机 + 概率模型**：角色性格、情绪、关系网的动态演化
- **异步竞技场 AI**：基于玩家历史行为生成的"影子对手"

### 美术工作流
- **AI 辅助像素画**：利用 Stable Diffusion / Midjourney 生成概念图，再转为像素风格
- **像素风场景**：大观园各处景致以复古像素艺术呈现

## 系统模块

| 模块 | 说明 |
|------|------|
| 管家系统 | 贾府内部资源调度、人员任命、收支管理 |
| 诗社对诗 | 诗词卡牌博弈玩法，考验文学储备与策略 |
| 庄园活动 | 节气活动、宴会筹备、诗社聚会等限时事件 |
| 角色关系网 | 基于红楼梦原著的人物关系，动态影响剧情走向 |
| 瓦片地图系统 | 大观园全景地图，支持探索与场景切换 |
| 多人联机 | Godot 4 原生 multiplayer 架构，RPC 同步与延迟补偿 |

## 开发日志系列

项目配套了完整的开发文档与博客记录：

1. **行为树的类型谱系与角色关联性断层诊断** — AI 系统底层设计
2. **大观园浮世录 v4 管家系统设计** — 核心经营系统架构
3. **管家系统深度设计：十二种博弈玩法全解析** — 博弈机制详解
4. **Godot 4 多人联机与实时交互完整指南** — 网络同步方案
5. **瓦片地图系统接入与架构关系** — TileMap 集成实践
6. **深度介绍 Godot 瓦片地图 TileMap** — 地图系统指南
7. **利用 AI 制作像素风游戏画面** — 美术工作流分享
8. **数据库迁移的 Prompt 工程实践** — 数据架构升级记录
9. **Mock 数据最佳实践** — 测试数据构造方法论
10. **大观园项目任务闭环拆解清单** — 敏捷开发管理
11. **红楼梦主要人物大全** — 游戏角色设定参考
12. **重构提示词模板** — AI 辅助代码重构经验

## 项目文档

- **架构说明** — 整体技术选型与模块划分
- **数据库指南** — Supabase 表结构、索引与查询优化
- **Docker 部署** — 生产环境容器化部署方案
- **本地搭建指南** — 开发者环境配置步骤
- **对诗功能** — 诗词博弈系统的规则与算法
- **Supabase 表结构说明** — 数据模型详细文档
- **庄园活动** — 活动系统设计与配置说明
- **游戏开发 QA 指南** — 测试规范与常见问题

## 未来计划

- [ ] 完成大观园全部场景的像素美术
- [ ] 主线剧情「贾府兴衰」多结局系统
- [ ] 角色语音与配乐
- [ ] Steam 页面上线与抢先体验
- [ ] 移动端适配（Android / iOS）

## 相关链接

- **项目主页**：[https://www.261449.xyz/honglou/](https://www.261449.xyz/honglou/)
- **GitHub 仓库**：[https://github.com/caifangwen/honglou](https://github.com/caifangwen/honglou)
- **开发日志分类**：[游戏开发](https://www.261449.xyz/categories/游戏开发/)
