# Agent / 自动化约定（AI-PM-Story）

本仓库正文**只有一份**：`stories/`。日更自动化与人工改稿均遵守下列规则。

## 文件归档（唯一路径）

```text
stories/{两位序号}-{YYYY-MM-DD}-{故事名}-{概念}.md
```

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
