# Agent / 自动化约定（AI-PM-Story）

本仓库正文**只有一份**：`stories/`。日更自动化与人工改稿均遵守下列规则。

## 文件归档（唯一路径）

自 **S6** 起（含其后各季）：

```text
stories/{子系列代号}-{两位序号}-{YYYY-MM-DD}-{故事名}-{概念}.md
```

示例：`stories/S6-01-2026-07-28-谁能看见哪一页-检索权限ACL.md`

- **子系列代号**：`S1`…`S8`（见世界观 §3.1）
- **两位序号**：**该子系列内**从 `01` 起递增（每季独立编号，避免全系列两位序号耗尽）
- 历史篇 `stories/01-…`～`stories/28-…`（S1–S5）**保持旧名，不批量重命名**

**禁止**在仓库根目录创建 `AI概念寓言-*.md`（全文或 stub 都不行）。

索引入口：[`README.md`](README.md)、[`stories/世界观.md`](stories/世界观.md) §6。  
子系列主线：[`stories/世界观.md`](stories/世界观.md) §3.1。

## 日更完整提示词

可整段粘贴到 Cursor Automations → Agent Instructions 的文稿：

**[`docs/automation-agent-instructions.md`](docs/automation-agent-instructions.md)**

（复制该文件中 `BEGIN` → `END` 之间的内容。）

## Git

**直推 `main`**：在 main 上改 → commit → `git push origin main`。

## 冲突裁决

用户当次指令 > 仓库约定（本文件 / 世界观 / `docs/automation-agent-instructions.md`）> 自动化面板里的旧 Instructions > 历史记忆。
