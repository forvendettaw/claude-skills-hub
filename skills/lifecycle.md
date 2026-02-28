# 技能生命周期索引

> "人会自己找事情做，会不断迭代进步" —— 这份索引不是静态的列表，而是一个有生命的系统。

## 系统设计理念

本索引遵循 **GROWTH** 原则：

- **G** - Gathering: 持续收集新技能和场景
- **R** - Relating: 建立技能之间的关联
- **O** - Organizing: 有序组织知识结构
- **W** - Weighting: 动态评估技能价值
- **T** - Tracing: 追踪使用效果
- **H** - Healing: 自我修复和更新

---

## 技能依赖图谱

### 核心技能（所有场景的基础）

```
prompt-engineering (提示工程)
    │
    ├── mcp-builder (MCP开发)
    │       │
    │       └── api-integration (API集成)
    │
    ├── browser-use (浏览器自动化)
    │       │
    │       └── playwright (测试自动化)
    │
    └── deep-research (深度研究)
            │
            └── knowledge-management (知识管理)
                    │
                    └── tapestry (知识网络)
```

### 技能链学习路径

#### 路径 1: 全栈开发工程师
```
Step 1: frontend-design (基础)
    ↓
Step 2: vercel-react-best-practices (进阶)
    ↓
Step 3: test-driven-development (质量)
    ↓
Step 4: docker-expert (部署)
    ↓
Step 5: mcp-builder (扩展)
```

#### 路径 2: AI 自动化专家
```
Step 1: prompt-engineering (基础)
    ↓
Step 2: browser-use (自动化)
    ↓
Step 3: n8n-skills (编排)
    ↓
Step 4: connect (集成)
    ↓
Step 5: loki-mode (多代理)
```

#### 路径 3: 内容运营专家
```
Step 1: copywriting (基础)
    ↓
Step 2: seo-audit (优化)
    ↓
Step 3: social-content (创作)
    ↓
Step 4: twitter-automation (发布)
    ↓
Step 5: analytics-tracking (分析)
```

---

## 动态权重系统

技能的权重不是固定的，会根据以下因素动态调整：

### 权重计算公式

```
Weight = Base × Popularity × Recency × Utility

Base:      基础权重 (1.0)
Popularity: 安装量/使用量 × 0.3
Recency:   更新频率 × 0.3
Utility:   场景覆盖度 × 0.4
```

### 当前热门技能 (2025-03)

| 技能 | 热度指数 | 趋势 |
|------|----------|------|
| find-skills | 100% | ↑ 新增 |
| browser-use | 95% | ↑ 上升 |
| mcp-builder | 90% | ↑ 快速上升 |
| prompt-engineering | 88% | → 稳定 |
| n8n-skills | 85% | ↑ 上升 |
| playwright | 82% | → 稳定 |
| docker-expert | 80% | → 稳定 |

---

## 自我更新机制

### 每周任务

1. **采集**：从 skills.sh 获取新增技能
2. **验证**：检查技能是否可用
3. **分类**：归入对应分类
4. **索引**：更新 JSON 索引

### 每月任务

1. **评估**：更新技能权重
2. **清理**：移除过时技能
3. **补充**：添加新使用场景
4. **优化**：完善文档

### 每季度任务

1. **重构**：优化分类结构
2. **扩展**：增加新的场景
3. **发布**：版本更新

---

## 技能发现流程

当你不确定需要什么技能时：

```
1. 定义你的目标
   ↓
2. 从场景库选择最接近的场景
   ↓
3. 查看该场景的技能组合
   ↓
4. 根据技能链选择入门技能
   ↓
5. 开始学习，安装技能
   ↓
6. 实践并反馈效果
   ↓
7. 根据效果调整技能组合
```

---

## 反馈闭环

> 人的成长靠的是不断迭代和反馈。这个系统也需要你的参与。

### 反馈渠道

1. **GitHub Issue**: 报告错误或缺失
2. **Pull Request**: 直接贡献新内容
3. **Discussion**: 讨论使用心得

### 反馈类型

| 类型 | 处理方式 |
|------|----------|
| 新技能发现 | 验证后加入索引 |
| 使用场景补充 | 丰富场景描述 |
| 技能关联错误 | 修正关联关系 |
| 权重建议 | 审核后调整 |

---

## 版本历史

| 版本 | 日期 | 变化 |
|------|------|------|
| v1.0 | 2025-03-01 | 初始版本 |
| v2.0 | - | 添加技能链 |
| v3.0 | - | 添加生命周期 |

---

## 未来规划

- [ ] 自动抓取 skills.sh 新增技能
- [ ] 建立技能效果追踪系统
- [ ] 添加用户贡献排名
- [ ] 开发技能推荐算法
- [ ] 构建中文社区

---

*这个系统不是完美的，但它会像人一样，通过不断学习和迭代，变得越来越好。*
