# 🌍 Awesome Claude Skills & Use Cases

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/forvendettaw/claude-skills-hub?style=flat)
![GitHub forks](https://img.shields.io/github/forks/forvendettaw/claude-skills-hub?style=flat)
![License](https://img.shields.io/github/license/forvendettaw/claude-skills-hub)
![Skills](https://img.shields.io/badge/Skills-500+-green)
![UseCases](https://img.shields.io/badge/UseCases-11+-blue)
![Weekly](https://img.shields.io/badge/Updated-Weekly-purple)

**全球最大最全的 Claude Code (OpenClaw) Skills 与使用案例分类检索库**

*[English](./README_EN.md) | 简体中文*

</div>

---

## ✨ 特性

- 🔍 **双向检索** - 从技能找场景，从场景找技能
- 📚 **完整分类** - 12 大类，100+ 子类
- 🏃 **实时更新** - 每周采集最新热门技能
- 📖 **使用案例** - 真实案例 + 详细步骤
- 🎯 **技能路径** - 学习路径 + 依赖图谱

---

## 📋 目录

1. [快速导航](#-快速导航)
2. [数据来源](#-数据来源)
3. [双向检索指南](#-双向检索指南)
4. [技能分类](#-技能分类)
5. [使用案例](#-使用案例)
6. [学习路径](#-学习路径)
7. [每周更新](#-每周更新)
8. [贡献指南](#-贡献指南)

---

## 🚀 快速导航

### 🎯 我想...

| 目标 | 行动 |
|------|------|
| 查找某个技能的用法 | 查看 [技能分类](#-技能分类) |
| 做某件事需要什么技能 | 使用 [反向索引](./skills/reverse-index.md) |
| 参考真实案例 | 查看 [使用案例](#-使用案例) |
| 从零开始学习 | 按照 [学习路径](#-学习路径) |
| 了解最新技能 | 查看 [每周更新](./changelog/) |

---

## 📡 数据来源

| 来源 | 类型 | 数量 | 链接 |
|------|------|-----:|------|
| anthropics/skills | 官方 | 16 | [GitHub](https://github.com/anthropics/skills) |
| ComposioHQ | 社区精选 | 100+ | [GitHub](https://github.com/ComposioHQ/awesome-claude-skills) |
| skills.sh | 技能市场 | 79,177+ | [Website](https://skills.sh) |
| inference-sh-9 | AI 技能 | 新兴 | [GitHub](https://github.com/inference-sh-9/skills) |
| Microsoft | 云技能 | 20+ | [GitHub](https://github.com/microsoft) |

---

## 🔍 双向检索指南

### 方式一：技能 → 场景（正向）

```
我学会了一个技能，想了解它能做什么？
```

| 技能 | 分类 | 能做什么 |
|------|------|----------|
| [frontend-design](./skills/02-development/) | 开发工具 | Web 应用界面设计 |
| [n8n-skills](./skills/12-automation/) | 自动化 | 工作流编排 |
| [copywriting](./skills/05-communication/) | 沟通写作 | 营销文案撰写 |
| [tapestry](./skills/07-productivity/) | 生产力 | 知识网络构建 |

### 方式二：场景 → 技能（反向）

```
我有一个目标，想知道需要什么技能？
```

| 目标场景 | 所需技能 |
|----------|----------|
| 开发一个网站 | frontend-design + playwright + docker + github-actions |
| 构建 AI 客服 | knowledge-management + n8n + whatsapp + gmail |
| 做内容营销 | copywriting + seo + twitter + content-strategy |
| 构建知识库 | knowledge-management + tapestry + article-extractor |

**[→ 查看完整反向索引](./skills/reverse-index.md)**

### 方式三：案例驱动

```
我想参考别人是怎么做的？
```

| 案例 | 涉及技能 |
|------|----------|
| [隔夜迷你应用](./usecases/02-development/overnight-mini-app-builder.md) | frontend, playwright, docker, TDD |
| [多渠道客服](./usecases/01-productivity/multi-channel-customer-service.md) | knowledge, n8n, whatsapp, gmail |
| [第二大脑](./usecases/01-productivity/second-brain.md) | tapestry, memory, knowledge |

---

## 📂 技能分类

### 12 大分类

| # | 分类 | 技能数 | 说明 |
|:-:|------|-------:|------|
| 01 | [📄 文档处理](./skills/01-document/) | 10+ | Word、PDF、Excel、PPT |
| 02 | [💻 开发工具](./skills/02-development/) | 100+ | 前端、后端、移动、测试 |
| 03 | [📊 数据分析](./skills/03-data-analysis/) | 30+ | 数据库、可视化、研究 |
| 04 | [💼 商业与营销](./skills/04-business/) | 30+ | 营销、销售、品牌 |
| 05 | [✍️ 沟通与写作](./skills/05-communication/) | 20+ | 文案、社交媒体、SEO |
| 06 | [🎨 创意与媒体](./skills/06-creative/) | 30+ | 图像、视频、设计 |
| 07 | [⚡ 生产力工具](./skills/07-productivity/) | 20+ | 效率、知识管理 |
| 08 | [🤝 协作与项目管理](./skills/08-collaboration/) | 20+ | Git、代码审查、团队 |
| 09 | [🔒 安全与系统](./skills/09-security/) | 20+ | 审计、渗透测试 |
| 10 | [☁️ 云服务与 DevOps](./skills/10-cloud-devops/) | 60+ | AWS、Azure、CI/CD |
| 11 | [🤖 AI 与机器学习](./skills/11-ai-ml/) | 40+ | LLM、Prompt、MCP |
| 12 | [🔄 自动化与工作流](./skills/12-automation/) | 100+ | n8n、API集成 |

### 热门技能 TOP 10

| 排名 | 技能 | 热度 | 分类 |
|:---:|------|-----:|------|
| 1 | find-skills | ⭐⭐⭐⭐⭐ | 开发工具 |
| 2 | frontend-design | ⭐⭐⭐⭐⭐ | 开发工具 |
| 3 | playwright | ⭐⭐⭐⭐⭐ | 测试 |
| 4 | mcp-builder | ⭐⭐⭐⭐⭐ | AI扩展 |
| 5 | prompt-engineering | ⭐⭐⭐⭐⭐ | AI |
| 6 | n8n-skills | ⭐⭐⭐⭐ | 自动化 |
| 7 | docker-expert | ⭐⭐⭐⭐ | DevOps |
| 8 | ai-image-generation | ⭐⭐⭐⭐ | 创意 |
| 9 | twitter-automation | ⭐⭐⭐⭐ | 社交 |
| 10 | seo-audit | ⭐⭐⭐⭐ | 营销 |

---

## 📖 使用案例

### 案例分类

| 分类 | 案例数 | 示例 |
|------|------:|------|
| 效率工具 | 5 | 自主项目管理、多渠道客服 |
| 开发 | 2 | 隔夜迷你应用、游戏开发 |
| 研究 | 1 | 知识库 RAG |
| 商业 | 1 | 自动交易 |
| 自动化 | 1 | n8n 工作流 |
| 社交媒体 | 1 | 多源新闻聚合 |

**[→ 查看全部案例](./usecases/)**

---

## 🎓 学习路径

### 路径一：全栈开发工程师

```
frontend-design → vercel-react → playwright → docker → mcp-builder
```

### 路径二：AI 自动化专家

```
prompt-engineering → browser-use → n8n → connect → loki-mode
```

### 路径三：内容运营专家

```
copywriting → seo-audit → social-content → twitter-automation
```

**[→ 查看完整技能链](./skills/lifecycle.md)**

---

## 📅 每周更新

### 本周热门 (2025-W1)

| 技能 | 安装数 | 趋势 |
|------|-------:|------|
| agent-browser | 16.5K | 🔥 |
| ai-image-generation | 16.4K | 🔥 |
| sleek-design-mobile-apps | 540 | ↑ +294% |

**[→ 查看更新日志](./changelog/2025-W1.md)**

---

## 🤝 贡献指南

欢迎贡献！请阅读 [CONTRIBUTING.md](./CONTRIBUTING.md)

### 贡献方式

- ⭐ 添加新技能
- 📝 补充使用案例
- 🔧 修复错误
- 📊 更新数据

---

## 📄 许可证

MIT License - 详见 [LICENSE](./LICENSE)

---

## 🙏 致谢

- [anthropics/skills](https://github.com/anthropics/skills)
- [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)
- [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases)
- [skills.sh](https://skills.sh)

---

<div align="center">

**让这个系统像人一样，不断学习，不断成长**

⭐ Star | 🍴 Fork | 📢 Share

</div>
