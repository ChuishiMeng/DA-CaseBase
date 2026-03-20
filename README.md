# DA-CaseBase 项目结构

> **项目名称**: Data Agent 案例库技术
> **创建时间**: 2026-03-17
> **最后更新**: 2026-03-19

---

## 📁 目录结构

```
DA-CaseBase/
├── P1-问题定义.md        ✅ 已完成
├── P2-文献调研.md        ✅ 已完成（含技术方法总结）
├── review/           # 论文 PDF 文件（34个）
│   ├── P01-2025-LangCache-Semantic-Caching.pdf
│   ├── P02-2026-CBR-to-SQL-Case-Based-Reasoning.pdf（待补充）
│   └── ...
│
├── review/               # 论文深度解读（38个）
│   ├── P01-2025-LangCache-Semantic-Caching.md
│   ├── P02-2026-CBR-to-SQL-Case-Based-Reasoning.md
│   └── ...
│
├── code/                 # 实验代码
│   └── ...
│
├── data/                 # 数据文件
│   └── ...
│
└── paper/                # 论文撰写
    ├── main.tex
    └── figures/
```

---

## 📂 文件夹说明

| 文件夹 | 用途 | 内容 |
|--------|------|------|
| **review/** | 原始论文 | PDF 文件，按 `P<序号>-<年份>-<关键词>-<简称>.pdf` 命名 |
| **review/** | 深度解读 | md 文件，按 `P<序号>-<年份>-<关键词>-<简称>.md` 命名 |
| **code/** | 实验代码 | Python/其他代码 |
| **data/** | 数据文件 | 数据集、中间结果 |
| **paper/** | 论文撰写 | LaTeX 源文件、图表 |

---

## 📝 阶段文件位置

**Obsidian 知识库**: `~/agentKB/Obsidian/AI-Workspace/Research/DA-CaseBase/`

| 阶段 | 文件 | 状态 |
|------|------|------|
| P1 | P1-问题定义.md | ✅ 已完成（2026-03-17）|
| P2 | P2-文献调研.md（含技术方法总结）| ✅ 已完成（2026-03-19）|
| P3 | 研究空白分析 | ⏳ 下一步 |

---

## 📊 论文统计

| 类别 | 数量 | 说明 |
|------|------|------|
| **PDF 文件** | 34 | review/ 目录 |
| **深度解读** | 38 | review/ 目录（含简化解读）|
| **核心论文** | 21 | P01-P21 |
| **补充论文** | 17 | P22-P38 |

---

## 📋 论文编号规则

- 从 `P01` 开始递增
- 全局唯一，不重复
- 命名格式: `P<序号>-<年份>-<关键词>-<简称>.<扩展名>`

**示例**:
- PDF: `P02-2026-CBR-to-SQL-Case-Based-Reasoning.pdf`
- 解读: `P02-2026-CBR-to-SQL-Case-Based-Reasoning.md`

---

## 🔗 相关链接

- **SKILL.md**: `~/.openclaw/agents/researcher/skills/research-methodology/SKILL.md`
- **论文清单**: `~/agentKB/Obsidian/AI-Workspace/Research/DA-CaseBase/论文清单.md`
- **Obsidian 解读**: `~/agentKB/Obsidian/AI-Workspace/Research/DA-CaseBase/review/`

---

*创建时间: 2026-03-18*
*最后更新: 2026-03-19*