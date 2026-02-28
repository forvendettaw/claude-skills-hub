# 📚 使用案例库 (Use Cases)

本目录收集了 Claude Code (OpenClaw) 的真实使用案例，每个案例都关联了相关技能。

---

## 📁 案例分类

### 01-效率工具 (Productivity)

| 案例 | 描述 | 关联技能 |
|------|------|----------|
| [自主项目管理](./01-productivity/autonomous-project-management.md) | 使用 STATE.yaml 的去中心化项目管理 | subagent-driven-development, writing-plans |
| [每日 Reddit 摘要](./01-productivity/daily-reddit-digest.md) | 自动追踪 Reddit 子版块热门内容 | reddit-fetch, memory-management |
| [多渠道客服](./01-productivity/multi-channel-customer-service.md) | 统一 AI 客服收件箱 | WhatsApp/Gmail Automation, knowledge-management |
| [会议记录与行动项](./01-productivity/meeting-notes-action-items.md) | 自动会议纪要和任务创建 | meeting-notes, Todoist/Asana Automation |
| [第二大脑](./01-productivity/second-brain.md) | 个人知识记忆系统 | tapestry, knowledge-management |

### 02-开发 (Development)

| 案例 | 描述 | 关联技能 |
|------|------|----------|
| [隔夜迷你应用](./02-development/overnight-mini-app-builder.md) | AI 自主通宵构建应用 | frontend-design, playwright, docker |
| [游戏开发流水线](./02-development/autonomous-game-dev-pipeline.md) | 完整游戏生命周期管理 | frontend-design, python, test-driven-development |

### 03-研究 (Research)

| 案例 | 描述 | 关联技能 |
|------|------|----------|
| [知识库 RAG](./03-research/knowledge-base-rag.md) | 智能知识库问答系统 | knowledge-management, deep-research, article-extractor |

### 04-商业 (Business)

| 案例 | 描述 | 关联技能 |
|------|------|----------|
| [Polymarket 自动交易](./04-business/polymarket-autopilot.md) | 预测市场自动化交易 | analytics-tracking, deep-research |

### 05-自动化 (Automation)

| 案例 | 描述 | 关联技能 |
|------|------|----------|
| [n8n 工作流编排](./05-automation/n8n-workflow-orchestration.md) | Webhook 触发的 API 自动化 | n8n-skills, webhook-handler |

### 06-社交媒体 (Social)

| 案例 | 描述 | 关联技能 |
|------|------|----------|
| [多源科技新闻](./06-social/multi-source-tech-news-digest.md) | 100+来源新闻聚合 | web-search, article-extractor, copywriting |

---

## 🔗 技能-案例映射

### 开发类技能

| 技能 | 相关案例 |
|------|----------|
| subagent-driven-development | 自主项目管理 |
| frontend-design | 隔夜迷你应用、游戏开发 |
| playwright | 隔夜迷你应用 |
| test-driven-development | 游戏开发 |
| docker-expert | 隔夜迷你应用 |

### 效率类技能

| 技能 | 相关案例 |
|------|----------|
| meeting-notes | 会议记录 |
| tapestry | 第二大脑 |
| knowledge-management | 多渠道客服、知识库 |
| n8n-skills | n8n 工作流 |

### 自动化类技能

| 技能 | 相关案例 |
|------|----------|
| WhatsApp Automation | 多渠道客服 |
| Gmail Automation | 多渠道客服 |
| Twitter Automation | 多源新闻 |
| deep-research | 知识库、交易系统 |

---

## 📊 案例统计

| 分类 | 案例数量 |
|------|----------|
| 效率工具 | 5 |
| 开发 | 2 |
| 研究 | 1 |
| 商业 | 1 |
| 自动化 | 1 |
| 社交媒体 | 1 |
| **总计** | **11** |

---

## 🤝 贡献案例

欢迎提交新的使用案例！请参考 [CONTRIBUTING.md](../CONTRIBUTING.md)

案例格式要求：
- 使用 Markdown 格式
- 包含案例概述、工作流程、关联技能
- 提供实施步骤和关键要点
