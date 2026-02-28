# 🔒 安全与系统 (Security & Systems)

本类别包含所有与系统安全、渗透测试、漏洞检测和数字取证相关的技能。

## 技能列表

### 6.1 安全审计

| 技能名称 | 描述 | 来源 | 热度 |
|----------|------|------|------|
| computer-forensics | 数字取证分析和调查技术 | ComposioHQ | ⭐⭐⭐⭐ |
| metadata-extraction | 提取分析文件元数据用于取证 | ComposioHQ | ⭐⭐⭐⭐ |
| threat-hunting-with-sigma-rules | 使用 Sigma 规则检测威胁 | ComposioHQ | ⭐⭐⭐⭐ |
| security-audit | 安全审计 | 社区 | ⭐⭐⭐ |
| code-security-analysis | 代码安全分析 | 社区 | ⭐⭐⭐ |
| security-requirement-extraction | 安全需求提取 | skills.sh | ⭐⭐⭐ |

### 6.2 渗透测试

| 技能名称 | 描述 | 来源 | 热度 |
|----------|------|------|------|
| FFUF Web Fuzzing | 集成 Web 模糊测试工具进行漏洞分析 | ComposioHQ | ⭐⭐⭐⭐⭐ |
| ffuf-web-fuzzing | ffuf Web 模糊测试 | travisvn | ⭐⭐⭐⭐ |
| penetration-testing | 渗透测试技能 | 社区 | ⭐⭐⭐ |
| vulnerability-scanning | 漏洞扫描 | 社区 | ⭐⭐⭐ |

### 6.3 安全工具

| 技能名称 | 描述 | 来源 | 热度 |
|----------|------|------|------|
| Trail of Bits Security Skills | CodeQL/Semgrep 静态分析安全技能 | travisvn | ⭐⭐⭐⭐⭐ |
| security-best-practices | 安全最佳实践 | 社区 | ⭐⭐⭐ |
| security-requirement-extraction | 安全需求提取 | skills.sh | ⭐⭐⭐ |

### 6.4 系统管理

| 技能名称 | 描述 | 来源 | 热度 |
|----------|------|------|------|
| system-administration | 系统管理 | 社区 | ⭐⭐⭐ |
| server-hardening | 服务器加固 | 社区 | ⭐⭐⭐ |
| backup-strategies | 备份策略 | 社区 | ⭐⭐⭐ |
| file-deletion | 安全文件删除和数据擦除方法 | ComposioHQ | ⭐⭐⭐⭐ |

---

## 使用场景 (Use Cases)

### 场景 1: Web 应用渗透测试
- **描述**: 对 Web 应用进行安全测试，发现潜在漏洞
- **适用技能**: FFUF Web Fuzzing, vulnerability-scanning
- **使用步骤**:
  1. 使用 FFUF Web Fuzzing 进行模糊测试
  2. 分析测试结果
  3. 生成渗透测试报告

### 场景 2: 代码安全审计
- **描述**: 扫描代码库，发现安全漏洞
- **适用技能**: Trail of Bits Security Skills, code-security-analysis
- **使用步骤**:
  1. 使用 Trail of Bits 工具进行静态分析
  2. 修复发现的安全问题
  3. 生成审计报告

### 场景 3: 威胁检测
- **描述**: 使用 Sigma 规则检测系统威胁
- **适用技能**: threat-hunting-with-sigma-rules
- **使用步骤**:
  1. 配置 Sigma 规则
  2. 分析日志数据
  3. 识别和响应威胁

### 场景 4: 数字取证调查
- **描述**: 分析可疑文件，进行取证调查
- **适用技能**: computer-forensics, metadata-extraction
- **使用步骤**:
  1. 提取文件元数据
  2. 分析取证线索
  3. 生成取证报告

---

## 安装使用

```bash
/plugin marketplace add ffuf-web-fuzzing
/plugin marketplace add computer-forensics
/plugin marketplace add threat-hunting
```

## 相关资源

- [OWASP 安全指南](https://owasp.org/)
- [Sigma 规则库](https://github.com/SigmaHQ/sigma)
- [Trail of Bits](https://trailofbits.com/)
