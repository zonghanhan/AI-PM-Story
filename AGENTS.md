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

## Cursor Cloud specific instructions

本仓库是**纯 Markdown 内容库**：正文全部在 `stories/`，**没有**应用代码、包管理文件、构建、lint 或自动化测试。产品即「在 GitHub 上渲染阅读的每日故事」。

- **无依赖**：启动 update 脚本是 no-op；不要为它添加 `pip install` / `npm install` 之类步骤。日常「开发」= 编辑 Markdown + 更新索引 + 开 PR。
- **主要「构建/测试」= 内容完整性校验**，而非编译。改动或新增故事后，务必确认两件事一致：
  - `README.md` 故事索引表新增/更新了对应行与相对路径链接；
  - `stories/世界观.md` §6 各篇归属表（及必要时 §3.1 子系列状态）同步更新。
  - 快速校验相对链接是否都指向真实文件，可跑一次性脚本（不必入库）：遍历 `README.md`、`stories/世界观.md`、`AGENTS.md` 中的 `](相对路径)`，逐个 `os.path.exists` 检查即可。
- **本地预览（可选、非仓库依赖）**：要像读者一样看渲染效果，可临时 `pip install markdown pygments`，用小脚本把 `*.md` 转 HTML 并 `python3 -m http.server` 提供服务（GitHub 上则直接看渲染后的 Markdown）。这只是临时开发工具，**不要**写进 update 脚本或提交入库。
- 写作流程、文件命名、Git/PR 约定等**不要在此重复**，以本文件上文各节与 [`docs/automation-agent-instructions.md`](docs/automation-agent-instructions.md) 为准。
