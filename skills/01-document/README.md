# 📄 文档处理 (Document Processing)

本类别包含所有与文档创建、编辑、处理和分析相关的技能。

## 技能列表

### 1.1 文字处理

| 技能名称 | 描述 | 来源 | 热度 |
|----------|------|------|------|
| docx | 创建、编辑和分析 Word 文档，支持修订追踪、评论和格式设置 | anthropics/skills | ⭐⭐⭐⭐⭐ |
| doc-coauthoring | 协作文档处理和格式转换 | skills.sh | ⭐⭐⭐ |

### 1.2 PDF 处理

| 技能名称 | 描述 | 来源 | 热度 |
|----------|------|------|------|
| pdf | 提取文本、表格、元数据，合并和标注 PDF | anthropics/skills | ⭐⭐⭐⭐⭐ |

### 1.3 表格处理

| 技能名称 | 描述 | 来源 | 热度 |
|----------|------|------|------|
| xlsx | 电子表格操作：公式、图表、数据转换 | anthropics/skills | ⭐⭐⭐⭐⭐ |

### 1.4 演示文稿

| 技能名称 | 描述 | 来源 | 热度 |
|----------|------|------|------|
| pptx | 读取、生成和调整幻灯片、布局、模板 | anthropics/skills | ⭐⭐⭐⭐⭐ |
| theme-factory | 应用专业字体和配色主题到演示文稿 | ComposioHQ | ⭐⭐⭐ |
| frontend-slides | 创建动画丰富的 HTML 演示文稿 | travisvn | ⭐⭐⭐ |

### 1.5 电子书制作

| 技能名称 | 描述 | 来源 | 热度 |
|----------|------|------|------|
| Markdown to EPUB Converter | 将 Markdown 文档转换为专业 EPUB 电子书 | ComposioHQ | ⭐⭐⭐ |

---

## 使用场景 (Use Cases)

### 场景 1: 合同文档批量处理
- **描述**: 自动化处理大量合同文档，统一格式并提取关键条款
- **适用技能**: docx, pdf
- **使用步骤**:
  1. 使用 pdf 技能提取合同文本
  2. 使用 docx 技能生成标准化合同模板
  3. 批量替换关键信息

### 场景 2: 会议记录整理
- **描述**: 将会议录音转换为结构化文档
- **适用技能**: docx, pptx
- **使用步骤**:
  1. 使用语音转文字工具获取会议记录
  2. 使用 docx 技能整理成会议纪要
  3. 使用 pptx 技能生成演示版本

### 场景 3: 数据报告生成
- **描述**: 将数据分析结果生成为专业的报告文档
- **适用技能**: xlsx, pptx, pdf
- **使用步骤**:
  1. 使用 xlsx 技能进行数据分析
  2. 使用 pptx 技能生成图表
  3. 使用 pdf 技能导出最终报告

---

## 安装使用

```bash
/plugin marketplace add docx
/plugin marketplace add pdf
/plugin marketplace add xlsx
/plugin marketplace add pptx
```

## 相关资源

- [官方文档技能](https://github.com/anthropics/skills/tree/main/skills)
- [ComposioHQ 技能列表](https://github.com/ComposioHQ/awesome-claude-skills)
