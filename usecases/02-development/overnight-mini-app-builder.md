# 隔夜迷你应用构建器 (Overnight Mini App Builder)

## 案例概述

AI 自主生成和完成每日任务，包括通宵构建迷你应用。这是一种"eland sleep, wake up with a product"的开发模式。

## 工作原理

1. **睡前**：设定应用需求和目标
2. **夜间**：AI 自主开发，完全无需干预
3. **醒来**：获得完整可运行的应用

## 技术要求

- Claude Code 自主运行能力
- 完整的项目上下文（SPEC.md）
- 自动测试和验证
- 部署能力

## 实施步骤

1. 编写详细 SPEC.md（功能、UI、验收标准）
2. 启动 Claude Code 自主模式
3. 设置检查点（可选）
4. 醒来后验证和调整

## 关键洞察

- 详细的需求文档是关键
- 避免中途干预，信任 AI 的决策
- 保持简单的项目范围
- 预设部署配置

## 关联技能

| 技能 | 用途 |
|------|------|
| frontend-design | 应用设计 |
| web-artifacts-builder | 构建前端 |
| playwright | E2E 测试 |
| docker-expert | 容器化部署 |
| test-driven-development | 测试驱动开发 |

## 适用项目

- 最小可行产品 (MVP)
- 内部工具
- 原型验证
- 自动化脚本
- 个人小工具
