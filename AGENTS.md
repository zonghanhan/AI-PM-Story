# Agent / 自动化约定（AI-PM-Story）

本仓库正文**只有一份**：`stories/`。日更自动化与人工改稿均遵守下列规则。

## 文件归档（唯一路径）

自 **S6** 起（含其后各季）：

```text
stories/{子系列代号}-{两位序号}-{YYYY-MM-DD}-{故事名}-{概念}.md
```

示例：`stories/S6-01-2026-07-28-谁能看见哪一页-检索权限ACL.md`

- **子系列代号**：`S1`…`S10`（见世界观 §3.1）
- **两位序号**：**该子系列内**从 `01` 起递增（每季独立编号，避免全系列两位序号耗尽）
- 历史篇 `stories/01-…`～`stories/28-…`（S1–S5）**保持旧名，不批量重命名**

**禁止**在仓库根目录创建 `AI概念寓言-*.md`（全文或 stub 都不行）。

索引入口：[`README.md`](README.md)、[`stories/世界观.md`](stories/世界观.md) §6。  
子系列主线：[`stories/世界观.md`](stories/世界观.md) §3.1。

## 日更完整提示词

可整段粘贴到 Cursor Automations → Agent Instructions 的文稿：

**[`docs/automation-agent-instructions.md`](docs/automation-agent-instructions.md)**

（复制该文件中 `BEGIN` → `END` 之间的内容。）

文风要点（详见该文件「文风与禁忌」）：**寓言是现场戏，正解/Checklist 才是说明书**；禁止故事章编号 SOP、条款体「坑→规定」、大段可照抄清单。

## Git

**推荐策略（单人日更）：建分支 → 开 PR → 默认自动合进 `main`。**

| 模式 | 何时用 | 行为 |
|------|--------|------|
| **默认 · 自动合并** | 没空审、希望 `main` 常新 | 分支推送 → 开 PR → **合并进 main** → `main` 上能看到最新正文 |
| **审核后再合** | 当次想自己看过再合 | 用户指令含「仅开 PR / 先不合并 / 等我审核」→ **只开 PR，不合并**；你在 GitHub 上自行 Merge |

分支名：`cursor/ai-fable-{YYYY-MM-DD}`（同日重跑可加 `-2` 后缀）。  
细则见 [`docs/automation-agent-instructions.md`](docs/automation-agent-instructions.md)「Git 工作流」。

**为何不推荐继续直推 `main`**：出错稿直接落在默认分支，回滚靠 revert/强推，缺少「今天先放着、我晚上再合」的闸门；对单人仓库风险不算致命，但性价比低于「PR + 默认自动合」。

## 冲突裁决

用户当次指令 > 仓库约定（本文件 / 世界观 / `docs/automation-agent-instructions.md`）> 自动化面板里的旧 Instructions > 历史记忆。
