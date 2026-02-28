# n8n 工作流编排 (n8n Workflow Orchestration)

## 案例概述

通过 webhook 委托 API 调用，实现复杂的自动化工作流。

## 核心功能

- Webhook 触发
- API 链式调用
- 条件分支处理
- 错误处理和重试

## 技术架构

```
外部触发 → OpenClaw → n8n → 多个 API → 结果返回
```

## 实施步骤

1. 在 n8n 中创建 webhook 端点
2. 配置工作流逻辑
3. 设置 OpenClaw 集成
4. 定义错误处理

## 关联技能

| 技能 | 用途 |
|------|------|
| n8n-skills | n8n 工作流 |
| webhook-handler | Webhook 处理 |
| api-integration | API 集成 |

## 使用场景

- 数据同步
- 通知自动化
- 定时任务
- 表单处理
