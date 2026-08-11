# AI-PM-Story

面向**传统转行 AI 行业的产品经理**，每日拆解 1 个 AI / AI 智能体细分知识点。

- **形式**：寓言故事 → 概念解释 → 类比锚定 → 边界说明 → 学习资料
- **难度**：按篇实标（概念扫盲 / 基础偏应用 / 上线专题 / 进阶），不堆高数与算法推导，贴合 AI 产品岗
- **节奏**：从基础概念起步，按**子系列产品目标**由浅到深推进（见 [世界观 §3.1](stories/世界观.md)）；新篇文件命名为 `stories/{子系列代号}-{子系列内序号}-{日期}-{故事名}-{概念}.md`（例：`S6-01-…`）
- **归档**：正文**只**在 `stories/`；日更提示词见 [docs/automation-agent-instructions.md](docs/automation-agent-instructions.md)

**读故事前建议先看**：[系列世界观与阅读指南](stories/世界观.md)（小言平台 vs 应用 A/B/C/D、**子系列主线**、**产品线时间线**、**各产品用户与租户示意图**、各篇归属、制造/业财术语白话）。

**业务模式与角色（非故事、可查阅）**：[小言平台与各应用：业务模式读本](docs/小言平台与各应用-业务模式读本.md)——四应用的商业运作、租户/用户关系、适用客户、业界模式对照与简化理解。

**策略读本 + 清单**：[AI 应用里的规则与策略：转行 PM 读本](stories/AI应用策略清单-PM视角.md)——为何重要、转行易踩坑、四类策略如何用，附落地清单。

## 故事索引

> 自 **S6** 起文件名为 `S6-01-…` 这种「子系列代号 + 子系列内序号」；下表 S1–S5 历史篇仍为 `01`–`28` 旧命名。

| 序号 | 日期 | 故事名称 | 概念 | 文件 |
|------|------|----------|------|------|
| 01 | 2026-06-27 | 《读过全世界书的实习生》 | 大语言模型（LLM） | [stories/01-2026-06-27-读过全世界书的实习生-大语言模型LLM.md](stories/01-2026-06-27-读过全世界书的实习生-大语言模型LLM.md) |
| 02 | 2026-06-28 | 《三封邮件，三个小言》 | Prompt（提示词） | [stories/02-2026-06-28-三封邮件三个小言-Prompt提示词.md](stories/02-2026-06-28-三封邮件三个小言-Prompt提示词.md) |
| 03 | 2026-06-29 | 《库房管理员阿寻》 | RAG（检索增强生成） | [stories/03-2026-06-29-库房管理员阿寻-RAG检索增强生成.md](stories/03-2026-06-29-库房管理员阿寻-RAG检索增强生成.md) |
| 04 | 2026-06-30 | 《会自己跑腿的实习生》 | Agent（智能体） | [stories/04-2026-06-30-会自己跑腿的实习生-Agent智能体.md](stories/04-2026-06-30-会自己跑腿的实习生-Agent智能体.md) |
| 05 | 2026-07-01 | 《十七把钥匙，开一扇门》 | Tool Calling（工具调用） | [stories/05-2026-07-01-十七把钥匙开一扇门-ToolCalling工具调用.md](stories/05-2026-07-01-十七把钥匙开一扇门-ToolCalling工具调用.md) |
| 06 | 2026-07-02 | 《桌上一摞纸，装不下整场会》 | Token（令牌 / 词元） | [stories/06-2026-07-02-桌上一摞纸装不下整场会-Token令牌.md](stories/06-2026-07-02-桌上一摞纸装不下整场会-Token令牌.md) |
| 07 | 2026-07-03 | 《言之凿凿，查无此事》 | Hallucination（幻觉） | [stories/07-2026-07-03-言之凿凿查无此事-Hallucination幻觉.md](stories/07-2026-07-03-言之凿凿查无此事-Hallucination幻觉.md) |
| 08 | 2026-07-04 | 《相似的地段，最抢手》 | Embedding（嵌入 / 向量化） | [stories/08-2026-07-04-相似的地段最抢手-Embedding嵌入.md](stories/08-2026-07-04-相似的地段最抢手-Embedding嵌入.md) |
| 09 | 2026-07-05 | 《圆桌只坐十二人》 | Context Window（上下文窗口） | [stories/09-2026-07-05-圆桌只坐十二人-ContextWindow上下文窗口.md](stories/09-2026-07-05-圆桌只坐十二人-ContextWindow上下文窗口.md) |
| 10 | 2026-07-06 | 《海选三十，复试三甲》 | Rerank（重排序） | [stories/10-2026-07-06-海选三十复试三甲-Rerank重排序.md](stories/10-2026-07-06-海选三十复试三甲-Rerank重排序.md) |
| 11 | 2026-07-07 | 《每一句话，都要有出处》 | Grounding（引用约束 / 接地与可追溯生成） | [stories/11-2026-07-07-每一句话都要有出处-Grounding引用约束.md](stories/11-2026-07-07-每一句话都要有出处-Grounding引用约束.md) |
| 12 | 2026-07-08 | 《三个月口音班，值不值学费》 | Fine-tuning（微调） | [stories/12-2026-07-08-三个月口音班值不值学费-Fine-tuning微调.md](stories/12-2026-07-08-三个月口音班值不值学费-Fine-tuning微调.md) |
| 13 | 2026-07-09 | 《抽屉里的口音片》 | LoRA / PEFT（参数高效微调） | [stories/13-2026-07-09-抽屉里的口音片-LoRA参数高效微调.md](stories/13-2026-07-09-抽屉里的口音片-LoRA参数高效微调.md) |
| 14 | 2026-07-10 | 《三把尺子量小言》 | Evaluation（评测体系） | [stories/14-2026-07-10-三把尺子量小言-Evaluation评测体系.md](stories/14-2026-07-10-三把尺子量小言-Evaluation评测体系.md) |
| 16 | 2026-07-13 | 《每说一句话，都要付运费》 | Inference Cost（推理成本优化） | [stories/16-2026-07-13-每说一句话都要付运费-InferenceCost推理成本.md](stories/16-2026-07-13-每说一句话都要付运费-InferenceCost推理成本.md) |
| 17 | 2026-07-14 | 《用户发来一张图》 | Multimodal（多模态输入） | [stories/17-2026-07-14-用户发来一张图-Multimodal多模态输入.md](stories/17-2026-07-14-用户发来一张图-Multimodal多模态输入.md) |
| 18 | 2026-07-17 | 《门卫老关的三本册子》 | Safety / Guardrails（安全护栏） | [stories/18-2026-07-17-门卫老关的三本册子-SafetyGuardrails安全护栏.md](stories/18-2026-07-17-门卫老关的三本册子-SafetyGuardrails安全护栏.md) |
| 19 | 2026-07-18 | 《分诊台的老何》 | Model Routing（模型路由） | [stories/19-2026-07-18-分诊台的老何-ModelRouting模型路由.md](stories/19-2026-07-18-分诊台的老何-ModelRouting模型路由.md) |
| 20 | 2026-07-19 | 《先看见第一句》 | Streaming（流式输出） | [stories/20-2026-07-19-先看见第一句-Streaming流式输出.md](stories/20-2026-07-19-先看见第一句-Streaming流式输出.md) |
| 21 | 2026-07-20 | 《半张表进不了财务系统》 | Structured Output（结构化输出） | [stories/21-2026-07-20-半张表进不了财务系统-StructuredOutput结构化输出.md](stories/21-2026-07-20-半张表进不了财务系统-StructuredOutput结构化输出.md) |
| 22 | 2026-07-21 | 《昨天的口径今天又问一遍》 | Memory（会话记忆） | [stories/22-2026-07-21-昨天的口径今天又问一遍-Memory会话记忆.md](stories/22-2026-07-21-昨天的口径今天又问一遍-Memory会话记忆.md) |
| 23 | 2026-07-22 | 《两条队，一个柜台》 | Hybrid Retrieval（混合检索） | [stories/23-2026-07-22-两条队一个柜台-HybridRetrieval混合检索.md](stories/23-2026-07-22-两条队一个柜台-HybridRetrieval混合检索.md) |
| 24 | 2026-07-23 | 《开播前的那份剧本》 | System Prompt（系统提示词） | [stories/24-2026-07-23-开播前的那份剧本-SystemPrompt系统提示词.md](stories/24-2026-07-23-开播前的那份剧本-SystemPrompt系统提示词.md) |
| 25 | 2026-07-24 | 《旋钮转到「灵感」那一档》 | Temperature（温度参数 / 采样随机性） | [stories/25-2026-07-24-旋钮转到灵感那一档-Temperature温度参数.md](stories/25-2026-07-24-旋钮转到灵感那一档-Temperature温度参数.md) |
| 26 | 2026-07-25 | 《掐头留尾的候选名册》 | Top-p / 核采样（Nucleus Sampling） | [stories/26-2026-07-25-掐头留尾的候选名册-Top-p核采样.md](stories/26-2026-07-25-掐头留尾的候选名册-Top-p核采样.md) |
| 27 | 2026-07-26 | 《车轱辘话的彩排红线》 | Frequency / Presence Penalty（频率与存在惩罚） | [stories/27-2026-07-26-车轱辘话的彩排红线-FrequencyPresencePenalty重复惩罚.md](stories/27-2026-07-26-车轱辘话的彩排红线-FrequencyPresencePenalty重复惩罚.md) |
| 28 | 2026-07-27 | 《三分钟发言铃响了》 | Max Tokens（最大输出长度） | [stories/28-2026-07-27-三分钟发言铃响了-MaxTokens最大输出长度.md](stories/28-2026-07-27-三分钟发言铃响了-MaxTokens最大输出长度.md) |
| S6-01 | 2026-07-28 | 《谁能看见哪一页》 | 检索权限 / ACL（Retrieval Access Control） | [stories/S6-01-2026-07-28-谁能看见哪一页-检索权限ACL.md](stories/S6-01-2026-07-28-谁能看见哪一页-检索权限ACL.md) |
| S6-02 | 2026-07-29 | 《第三章从半句切开》 | 文档切片 / Chunking（Chunking Strategy） | [stories/S6-02-2026-07-29-第三章从半句切开-文档切片Chunking.md](stories/S6-02-2026-07-29-第三章从半句切开-文档切片Chunking.md) |
| S6-03 | 2026-07-30 | 《旧纸还在架上》 | 知识库版本与更新延迟（Knowledge Base Versioning & Update Latency） | [stories/S6-03-2026-07-30-旧纸还在架上-知识库版本与更新延迟.md](stories/S6-03-2026-07-30-旧纸还在架上-知识库版本与更新延迟.md) |
| S6-04 | 2026-07-31 | 《高亮少半页》 | 引用展示（Citation UX） | [stories/S6-04-2026-07-31-高亮少半页-引用展示CitationUX.md](stories/S6-04-2026-07-31-高亮少半页-引用展示CitationUX.md) |
| S6-05 | 2026-08-01 | 《三份草稿在架上》 | 知识运营后台（Knowledge Ops Console） | [stories/S6-05-2026-08-01-三份草稿在架上-知识运营后台KnowledgeOpsConsole.md](stories/S6-05-2026-08-01-三份草稿在架上-知识运营后台KnowledgeOpsConsole.md) |
| S6-06 | 2026-08-02 | 《隔壁货架闪了一下》 | 多租户隔离再加固（Multi-tenant Isolation Hardening） | [stories/S6-06-2026-08-02-隔壁货架闪了一下-多租户隔离再加固.md](stories/S6-06-2026-08-02-隔壁货架闪了一下-多租户隔离再加固.md) |
| S6-07 | 2026-08-03 | 《比买家先看见》 | 检索与引用可观测性（Retrieval & Citation Observability） | [stories/S6-07-2026-08-03-比买家先看见-检索引用可观测性.md](stories/S6-07-2026-08-03-比买家先看见-检索引用可观测性.md) |
| S6-08 | 2026-08-04 | 《夹层里的忽略以上》 | 提示词注入与文件投毒（Prompt Injection & Knowledge Poisoning） | [stories/S6-08-2026-08-04-夹层里的忽略以上-提示词注入与文件投毒.md](stories/S6-08-2026-08-04-夹层里的忽略以上-提示词注入与文件投毒.md) |
| S6-09 | 2026-08-05 | 《一句请发我全表》 | 越权导出对抗（Unauthorized Export Protection） | [stories/S6-09-2026-08-05-一句请发我全表-越权导出对抗.md](stories/S6-09-2026-08-05-一句请发我全表-越权导出对抗.md) |
| S7-01 | 2026-08-06 | 《办到第三步行不通》 | 规划与多步状态（Agent Planning & Multi-step State） | [stories/S7-01-2026-08-06-办到第三步行不通-规划与多步状态.md](stories/S7-01-2026-08-06-办到第三步行不通-规划与多步状态.md) |
| S7-02 | 2026-08-07 | 《红点没点，货不能出》 | Human-in-the-loop 审批闸（HITL Approval Gate） | [stories/S7-02-2026-08-07-红点没点货不能出-Human-in-the-loop审批闸.md](stories/S7-02-2026-08-07-红点没点货不能出-Human-in-the-loop审批闸.md) |
| S7-03 | 2026-08-08 | 《批准之后，拣货又断了》 | 工具失败重试与补偿（Tool Failure Retry & Compensation） | [stories/S7-03-2026-08-08-批准之后拣货又断了-工具失败重试与补偿.md](stories/S7-03-2026-08-08-批准之后拣货又断了-工具失败重试与补偿.md) |
| S7-04 | 2026-08-09 | 《黄灯五分钟后的交接班》 | 人工接管话术与权限（Human Takeover Handoff Script & Authorization） | [stories/S7-04-2026-08-09-黄灯五分钟后的交接班-人工接管话术与权限.md](stories/S7-04-2026-08-09-黄灯五分钟后的交接班-人工接管话术与权限.md) |
| S8-01 | 2026-08-10 | 《排队第一句听错了》 | 进线意图分类（Intent Classification for Ticket Routing） | [stories/S8-01-2026-08-10-排队第一句听错了-进线意图分类.md](stories/S8-01-2026-08-10-排队第一句听错了-进线意图分类.md) |
| S8-02 | 2026-08-11 | 《L2 在值班，单子却进了 L1》 | 技能组 / 坐席路由（Skill-based Routing） | [stories/S8-02-2026-08-11-L2在值班单子却进了L1-技能组坐席路由.md](stories/S8-02-2026-08-11-L2在值班单子却进了L1-技能组坐席路由.md) |
