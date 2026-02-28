# 📊 数据分析 (Data & Analysis)

本类别包含所有与数据处理、分析、可视化和数据库操作相关的技能。

## 技能列表

### 3.1 数据处理

| 技能名称 | 描述 | 来源 | 热度 |
|----------|------|------|------|
| CSV Data Summarizer | 自动分析 CSV 文件并生成可视化洞察 | ComposioHQ | ⭐⭐⭐⭐ |
| root-cause-tracing | 追踪深层错误找到原始触发原因 | ComposioHQ | ⭐⭐⭐⭐ |
| native-data-fetching | 原生数据获取 | skills.sh | ⭐⭐⭐ |

### 3.2 数据库操作

#### 3.2.1 PostgreSQL

| 技能名称 | 描述 | 来源 | 热度 |
|----------|------|------|------|
| postgres | 对 PostgreSQL 数据库执行安全只读 SQL 查询 | ComposioHQ | ⭐⭐⭐⭐ |
| supabase-postgres-best-practices | Supabase PostgreSQL 最佳实践 | skills.sh | ⭐⭐⭐⭐ |
| postgresql-table-design | PostgreSQL 表设计 | skills.sh | ⭐⭐⭐ |
| azure-postgres | Azure PostgreSQL | skills.sh | ⭐⭐⭐ |

#### 3.2.2 其他数据库

| 技能名称 | 描述 | 来源 | 热度 |
|----------|------|------|------|
| sql-optimization-patterns | SQL 优化模式 | skills.sh | ⭐⭐⭐ |
| convex | Convex 数据库 | skills.sh | ⭐⭐⭐ |

### 3.3 数据可视化

| 技能名称 | 描述 | 来源 | 热度 |
|----------|------|------|------|
| D3.js Visualization | 生成 D3 图表和交互式数据可视化 | ComposioHQ | ⭐⭐⭐⭐ |
| claude-d3js-skill | D3.js 数据可视化技能 | travisvn | ⭐⭐⭐ |

### 3.4 数据分析工具

| 技能名称 | 描述 | 来源 | 热度 |
|----------|------|------|------|
| analytics-tracking | 分析追踪设置 | skills.sh | ⭐⭐⭐⭐ |
| schema-markup | Schema 标记 | skills.sh | ⭐⭐⭐ |
| ai-sdk | AI SDK 数据处理 | skills.sh | ⭐⭐⭐ |
| javascript-sdk | JavaScript SDK | skills.sh | ⭐⭐⭐ |

### 3.5 AI 研究

| 技能名称 | 描述 | 来源 | 热度 |
|----------|------|------|------|
| deep-research | 使用 Gemini Deep Research Agent 执行多步研究 | ComposioHQ | ⭐⭐⭐⭐ |

---

## 使用场景 (Use Cases)

### 场景 1: 数据报表自动化
- **描述**: 从数据库提取数据并生成可视化报表
- **适用技能**: postgres, CSV Data Summarizer, D3.js Visualization
- **使用步骤**:
  1. 使用 postgres 从数据库提取数据
  2. 使用 CSV Data Summarizer 分析数据
  3. 使用 D3.js Visualization 生成图表

### 场景 2: 用户行为分析
- **描述**: 分析网站/应用的用户行为数据
- **适用技能**: analytics-tracking, deep-research
- **使用步骤**:
  1. 使用 analytics-tracking 设置追踪
  2. 使用 deep-research 进行深度分析
  3. 生成分析报告

### 场景 3: 数据库性能优化
- **描述**: 优化慢查询，提升数据库性能
- **适用技能**: postgres, sql-optimization-patterns, postgresql-table-design
- **使用步骤**:
  1. 使用 postgres 定位慢查询
  2. 使用 sql-optimization-patterns 优化
  3. 使用 postgresql-table-design 优化表结构

---

## 安装使用

```bash
/plugin marketplace add postgres
/plugin marketplace add csv-data-summarizer
/plugin marketplace add d3-visualization
/plugin marketplace add deep-research
```

## 相关资源

- [PostgreSQL 文档](https://www.postgresql.org/)
- [D3.js 示例](https://d3js.org/)
