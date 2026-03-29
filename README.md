# Awesome Claw CN

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--03--28-brightgreen)](https://github.com/anthhub/awesome-claw-cn)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/anthhub/awesome-claw-cn/pulls)

> 中文 OpenClaw 生态资源精选列表 — 最全、最新、持续更新

收录框架衍生、国内平台集成、国产大模型接入、中文教程、视频教程、技能插件、记忆增强、多 Agent 编排、云部署、安全合规、社区等优质资源。

---

### 本周新增 (2026-03-28)

> 以下项目为本次更新新收录，标注 `NEW` 的为首次入选。

| 项目 | Stars | 亮点 |
|---|---|---|
| [OpenViking](https://github.com/volcengine/OpenViking) `NEW` | 19.8k | 字节跳动出品，Agent 上下文数据库，文件系统范式管理记忆/资源/技能 |
| [NemoClaw](https://github.com/NVIDIA/NemoClaw) `NEW` | 17.6k | NVIDIA 出品，安全沙箱 + 托管推理，两周 17k stars |
| [edict 三省六部制](https://github.com/cft0808/edict) `NEW` | 13.4k | 9 个专业 AI Agent 编排系统，实时仪表盘 + 审计追踪 |
| [memU](https://github.com/NevaMind-AI/memU) `NEW` | 13.2k | 24/7 常驻 Agent 专用记忆系统 |
| [moltworker](https://github.com/cloudflare/moltworker) `NEW` | 9.8k | Cloudflare 官方，Workers 边缘部署 OpenClaw |
| [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) `NEW` | 9.4k | 从想法到论文的全自动科研，两周爆涨 |
| [memory-lancedb-pro](https://github.com/CortexReach/memory-lancedb-pro) `NEW` | 3.7k | 混合检索长期记忆，向量+BM25+Cross-Encoder 重排序 |
| [lossless-claw](https://github.com/Martian-Engineering/lossless-claw) `NEW` | 3.7k | 无损上下文管理，DAG 分层摘要，零信息丢失 |
| [openclaw-a2a-gateway](https://github.com/win4r/openclaw-a2a-gateway) `NEW` | 353 | A2A 协议 v0.3.0，双向 Agent 通信网关 |
| [openclaw-codex-app-server](https://github.com/pwrdrvr/openclaw-codex-app-server) `NEW` | 150 | Codex 引入 Telegram/Discord |
| [shellward](https://github.com/jnMetaCode/shellward) `NEW` | 50 | AI Agent 安全中间件，8 层防护 + DLP + Prompt 注入检测 |

---

## 目录

- [框架与衍生项目](#框架与衍生项目)
- [国内平台集成](#国内平台集成)
- [国产大模型集成](#国产大模型集成)
- [中文教程](#中文教程)
- [视频教程](#视频教程)
- [Skills 与插件生态](#skills-与插件生态)
- [MCP 工具](#mcp-工具)
- [记忆与上下文管理](#记忆与上下文管理)
- [Skill 开发](#skill-开发)
- [云部署方案](#云部署方案)
- [安全合规](#安全合规)
- [社区与讨论](#社区与讨论)
- [贡献指南](#贡献指南)

---

## 框架与衍生项目

- [openclaw-cn](https://github.com/jiulingyun/openclaw-cn) — 中文社区版，内置钉钉/企业微信/飞书/QQ/微信，国内网络优化
- [OpenClawChinese](https://github.com/MaoTouHU/OpenClawChinese) — 全中文 CLI + Dashboard 汉化版，每小时自动同步上游
- [openclaw-china](https://github.com/BytePioneer-AI/openclaw-china) — 中国插件合集，支持飞书/钉钉/QQ/企业微信/微信
- [openmozi](https://github.com/oujingzhou/openmozi) — 轻量级，专为国内通讯平台设计
- [clawdbot-cn](https://github.com/bbylw/clawdbot-cn) — Clawdbot 中文版
- [OpenClawChineseTranslation](https://github.com/1186258278/OpenClawChineseTranslation) — 汉化版 + 全流程搭建教程 + 排错指南
- [OpenClaw-Docker-CN-IM](https://github.com/justlovemaki/OpenClaw-Docker-CN-IM) — Docker 一键部署，预装飞书/钉钉/QQ/企业微信
- [MetaClaw](https://github.com/aiming-lab/MetaClaw) — 持续学习扩展层，能从用户对话中学习并自我进化
- [goclaw](https://github.com/smallnest/goclaw) — Go 语言重实现的 AI 助手框架
- [ClawPanel](https://github.com/zhaoxinyi02/ClawPanel) — Go 单二进制可视化管理面板，支持 20+ 通道管理
- [Nanobot](https://github.com/HKUDS/nanobot) — 港大出品，仅 4000 行 Python 的极简版（34.6K stars）
- [ZeroClaw](https://github.com/theonlyhennygod/zeroclaw) — Rust 实现，比 OpenClaw 快 400 倍，<10ms 启动，3.4MB，22+ AI 提供商
- [PicoClaw](https://github.com/sipeed/picoclaw) — Go 实现，运行于 $10 RISC-V 硬件，<10MB RAM（矽速科技出品）
- [NanoClaw](https://github.com/qwibitai/nanoclaw) — 容器隔离安全架构，基于 Anthropic Claude Agent SDK
- [ZeptoClaw](https://github.com/qhkm/zeptoclaw) — Rust "终极形态"，集成安全+体积+功能，1300+ 测试
- [MimiClaw](https://github.com/memovai/mimiclaw) — C 实现，运行在 $5 ESP32-S3 芯片上
- [TinyClaw](https://github.com/jlia0/tinyclaw) — 多智能体团队协作，专属角色
- [NemoClaw](https://github.com/NVIDIA/NemoClaw) — **NVIDIA 出品**，在 OpenShell 安全沙箱运行 OpenClaw + 托管推理（17.6K stars）`NEW`
- [moltworker](https://github.com/cloudflare/moltworker) — **Cloudflare 官方**，在 Workers 边缘网络运行 OpenClaw，全球低延迟（9.8K stars）`NEW`
- [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) — 从想法到论文的全自动科研系统，多智能体辩论 + 引用验证（9.4K stars）`NEW`
- [IronClaw](https://github.com/nearai/ironclaw) — NEAR AI 出品，Rust，侧重隐私与安全
- [CherryStudio](https://github.com/CherryHQ/cherry-studio) — AI 生产力工作台，300+ 助手预设
- [n8n-claw](https://github.com/freddy-schuetz/n8n-claw) — 基于 n8n + PostgreSQL 的自主代理
- [LangBot](https://github.com/langbot-app/LangBot) — 生产级多平台 IM 机器人，支持 Discord/微信/飞书/钉钉/QQ

---

## 国内平台集成

### 微信

- [openclaw-wechat](https://github.com/freestylefly/openclaw-wechat) — 个人微信接入，扫码即用
- [weclaw](https://github.com/fastclaw-ai/weclaw) — WeChat AI Agent Bridge，支持多模型
- [openclaw-plugin-wecom](https://github.com/sunnoy/openclaw-plugin-wecom) — 企业微信 AI 机器人，流式输出 + 群聊
- [nexu](https://github.com/nexu-io/nexu) — 桌面客户端，一键桥接微信/飞书/Slack/Discord
- [openclaw-wechat-kf](https://github.com/pawastation/wechat-kf) — 微信客服频道，支持文本/图片/语音/视频/小程序，免费

### 飞书

- [openclaw-lark](https://github.com/larksuite/openclaw-lark) — 飞书官方出品，消息/文档/多维表格/日历/任务
- [openclaw-plugin-feishu](https://github.com/xzq-xu/openclaw-plugin-feishu) — 社区版飞书 Channel 插件
- [feishu-openclaw](https://github.com/AlexAnys/feishu-openclaw) — 无需公网服务器，5 分钟部署
- [openclaw-feishu](https://github.com/AlexAnys/openclaw-feishu) — 保姆级配置，含内网穿透方案
- [clawdbot-feishu](https://github.com/m1heng/clawdbot-feishu) — Wiki/Drive/Bitable 多维表格工具

### 钉钉

- [dingtalk-openclaw-connector](https://github.com/DingTalk-Real-AI/dingtalk-openclaw-connector) — 钉钉官方出品，AI Card 流式响应
- [openclaw-channel-dingtalk](https://github.com/soimy/openclaw-channel-dingtalk) — 文档网关 + 群会话 + 引用消息
- [openclaw-dingtalk](https://github.com/xuanmiss/openclaw-dingtalk) — Stream 模式钉钉集成

### QQ

- [openclaw-qqbot](https://github.com/tencent-connect/openclaw-qqbot) — 腾讯官方出品
- [openclaw-onebot](https://github.com/xucheng/openclaw-onebot) — OneBot 11 QQ 频道插件，支持 NapCat/go-cqhttp
- [openclaw-satori-channel](https://github.com/DoiiarX/openclaw-satori-channel) — Satori 协议，一个插件支持 QQ/Telegram/Discord

### 小红书

- [openclaw-xhs](https://github.com/zhjiang22/openclaw-xhs) — MCP 集成 + 热点跟踪 + 记忆库导出
- [xiaohongshu-ops-skill](https://github.com/Xiangyu-CAS/xiaohongshu-ops-skill) — 小红书运营助手
- [xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) — 小红书 MCP 服务

### 微博

- [openclaw-weibo](https://github.com/wecode-ai/openclaw-weibo) — 微博私信通道

### 闲鱼

- [xianyu-openclaw-channel](https://github.com/laozuzhen/xianyu-openclaw-channel) — 闲鱼频道插件，自动回复客服、自动发货

### 其他

- [openclaw-serverchan-bot](https://github.com/easychen/openclaw-serverchan-bot) — Server酱³ Bot 频道插件

### 多平台数据

- [opencli-rs-skill](https://github.com/nashsu/opencli-rs-skill) — 55+ 平台实时数据获取
- [opencli-skill](https://github.com/joeseesun/opencli-skill) — B站/微博/小红书/V2EX/雪球等
- [social-auto-upload](https://github.com/dreammis/social-auto-upload) — 自动化上传到抖音/小红书/B站

---

## 国产大模型集成

- [通义千问 (Qwen)](https://help.aliyun.com/zh/model-studio/openclaw) — 阿里云百炼平台官方支持，每日 2000 次免费
- [DeepSeek](https://www.160.com/article/11915.html) — 国内社区最热门选择，超高性价比（配置指南）
- [智谱 GLM](https://clawcn.net/guides/domestic-models) — 支持接入
- [文心一言 (Wenxin)](https://help.aliyun.com/zh/model-studio/openclaw) — 百度智能云一键部署
- [Kimi / MiniMax / 豆包](https://blog.csdn.net/weixin_45110225/article/details/157724298) — CSDN 完整配置指南
- [讯飞星火](https://www.xfyun.cn/doc/spark/Agent-AstronClaw使用指南.html) — AstronClaw 云端 AI 助手
- [性价比对比](https://help.apiyi.com/en/openclaw-cost-effective-models-deepseek-minimax-glm5-en.html) — DeepSeek / MiniMax / GLM5 性价比横评

---

## 中文教程

### GitHub 教程项目

- [hello-claw](https://github.com/datawhalechina/hello-claw) — Datawhale 出品，首个体系化中文教程（用户指南 11 章 + 实战场景 + 开发者指南 15 章）
- [awesome-openclaw-tutorial](https://github.com/xianyu110/awesome-openclaw-tutorial) — 从零开始，安装/配置/实战/避坑
- [openclaw-docs](https://github.com/yeuxuan/openclaw-docs) — 中文文档站，276 篇深度教程 + 源码剖析
- [claw0](https://github.com/shareAI-lab/claw0) — 从 0 到 1 手动构建 AI Agent
- [awesome-openclaw-usecases-zh](https://github.com/AlexAnys/awesome-openclaw-usecases-zh) — 40+ 真实场景用例

### 知乎

- [OpenClaw 完全指南（3.2 万字）](https://zhuanlan.zhihu.com/p/2015027745743189513)
- [完全部署指南：从入门到安全加固](https://zhuanlan.zhihu.com/p/2004187601276540473) — 11 种部署路径
- [入门完全指南](https://zhuanlan.zhihu.com/p/2011730782876612463)
- [从新手到中级完整教程](https://zhuanlan.zhihu.com/p/2012169208067282681)
- [入门站（7 天教程 + 70 篇资源）](https://zhuanlan.zhihu.com/p/2002370444339212951)
- [从安装到入门的完全指南](https://zhuanlan.zhihu.com/p/2002485126714644013)
- [2026 年极速部署及技能精选指南](https://zhuanlan.zhihu.com/p/2014016157661811265)
- [OpenClaw 才是真正的 Agent-OS！架构深度拆解](https://zhuanlan.zhihu.com/p/2012755823194054947)

### 掘金

- [国内使用完全攻略](https://juejin.cn/post/7617763599540830243) — DeepSeek/Qwen + GPT/Claude 混合策略
- [2026 路线图解读](https://juejin.cn/post/7616193982247518227)
- [最新功能全解析](https://juejin.cn/post/7615426060050300928)
- [本地化部署：AI "智慧养虾"](https://juejin.cn/post/7617003285255241766)

### CSDN

- [中文汉化版介绍/下载/安装/配置](https://blog.csdn.net/qq_44866828/article/details/157876493)
- [云上及本地部署保姆级教程](https://damodev.csdn.net/69a7a68d54b52172bc5ee3bb.html)
- [华为云/MacOS/Linux/Windows 3 分钟搭建](https://blog.csdn.net/yunfuuwqi/article/details/159384223)

### 菜鸟教程

- [OpenClaw 教程](https://www.runoob.com/ai-agent/openclaw-clawdbot-tutorial.html)
- [一键部署](https://www.runoob.com/ai-agent/openclaw-cloud.html)

### 官方中文文档

- [OpenClaw 官方入门指南](https://docs.openclaw.ai/zh-CN/start/getting-started)

---

## 视频教程（B 站）

- [一个视频搞懂 OpenClaw！](https://www.bilibili.com/video/BV1jEAaz3E6K/) — 470 万+ 播放
- [接入微信/QQ/飞书教程](https://www.bilibili.com/video/BV1mcwtzVEnt/) — 零度解说
- [保姆级全网最细教学](https://www.bilibili.com/video/BV1TpAZzeEiZ/) — AI 学长小林
- [北航何静副教授科研教程](https://www.bilibili.com/video/BV1RVwYzzE83/) — 硕博生专项
- [36 个实战案例](https://www.bilibili.com/video/BV16MP4ziExA/)
- [必装 5 个 Skill + 2 个自动化玩法](https://www.bilibili.com/video/BV1PsNwzkEjN/)
- [Windows + 飞书接入](https://www.bilibili.com/video/BV1WDPhzWEVb/)
- [中级到高级完整教程](https://www.bilibili.com/video/BV1ZiNwzPEhP/)

---

## Skills 与插件生态

### 官方生态

- [ClawHub](https://clawhub.ai/) — 官方技能市场，15,000+ 技能，支持向量语义搜索和 CLI 一键安装
- [OpenClaw 官方技能仓库](https://github.com/openclaw/skills) — 所有 ClawHub 技能的归档
- [OpenClaw Skill 文档](https://docs.openclaw.ai/tools/skills) — 官方技能使用文档

### 中文技能列表

- [awesome-openclaw-skills-zh](https://github.com/clawdbot-ai/awesome-openclaw-skills-zh) — 中文官方技能库，支持中文自然语言调用
- [Rito-w/awesome-openclaw-skills-zh](https://github.com/Rito-w/awesome-openclaw-skills-zh) — 5,494 个技能的中文翻译与分类
- [awesome-openclaw-skills-cn](https://github.com/AgentWorkers/awesome-openclaw-skills-cn) — 3000+ 技能分类
- [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) — 5,400+ 精选技能（英文，社区最权威）
- [sundial-org/awesome-openclaw-skills](https://github.com/sundial-org/awesome-openclaw-skills) — 913 个精选顶级技能
- [LeoYeAI/openclaw-master-skills](https://github.com/LeoYeAI/openclaw-master-skills) — 339+ 精选技能，每周更新

### 中文推荐文章

- [OpenClaw 最强军火库（2868 个精选 skills）](https://zhuanlan.zhihu.com/p/2010926090475045346) — 知乎
- [十大必装 OpenClaw Skills](https://zhuanlan.zhihu.com/p/2011751083702256050) — 知乎
- [ClawHub 必装 Skills 清单](https://www.cnblogs.com/informatics/p/19679935) — 博客园
- [52个官方 Skill + 5700 社区 Skill 测评](https://developer.aliyun.com/article/1712680) — 阿里云
- [新手必看！推荐10个神器技能包](https://cloud.tencent.com/developer/article/2634605) — 腾讯云
- [liyupi/ai-guide](https://github.com/liyupi/ai-guide) — 程序员鱼皮出品，含 Vibe Coding 教程和 AI 编程变现

### 热门 Skills

- Web Browser — 180,000+ 下载，网页浏览与内容提取
- Telegram Bot — 145,000+ 下载，连接 Telegram
- GOG (Google Workspace) — Gmail/Calendar/Drive/Sheets 一体化
- Capability Evolver — 35,000+ 下载，AI 自我进化引擎
- Tavily Search — AI 优化联网搜索

### 多智能体编排与工作流

- [edict 三省六部制](https://github.com/cft0808/edict) — **9 个专业 AI Agent 编排系统**，实时仪表盘 + 看板视图 + 完整审计追踪，灵感源自中国古代行政制度（13.4K stars）`NEW`
- [openclaw-a2a-gateway](https://github.com/win4r/openclaw-a2a-gateway) — **A2A 协议 v0.3.0**，双向 Agent 通信网关，标准化多 Agent 互操作（353 stars）`NEW`
- [openclaw-codex-app-server](https://github.com/pwrdrvr/openclaw-codex-app-server) — 将 OpenAI Codex 引入 Telegram/Discord，跨平台 AI 编程助手 `NEW`
- [opencrew](https://github.com/AlexAnys/opencrew) — 多智能体协同系统
- [ClawFlows](https://www.sitepoint.com/clawflows-prebuilt-ai-workflows-openclaw/) — 111 个预构建 AI 工作流
- [agents-radar](https://github.com/duanyytop/agents-radar) — OpenClaw 生态中文日报
- [AstronClaw](https://www.xfyun.cn/doc/spark/Agent-AstronClaw使用指南.html) — 讯飞出品云端 AI 助手

---

## MCP 工具

- [openclaw-mcp](https://github.com/freema/openclaw-mcp) — OpenClaw MCP 服务器，OAuth2 认证安全桥接 Claude.ai
- [openclaw-mcp-server](https://github.com/Helms-AI/openclaw-mcp-server) — 将 OpenClaw Gateway 工具暴露给 MCP 客户端
- [openclaw-claude-code-skill](https://github.com/Enderfga/openclaw-claude-code-skill) — 通过 MCP 集成 Claude Code 能力
- [xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) — 小红书 MCP 服务
- [MCP 服务器推荐](https://openclawlaunch.com/guides/best-mcp-servers) — 2026 年最佳 MCP 服务器指南

---

## 记忆与上下文管理

> Agent 的记忆能力是当前 OpenClaw 生态最活跃的创新方向之一。以下按「长期记忆」和「上下文管理」两个维度整理。

### 长期记忆 vs 上下文管理 — 如何选？

| 维度 | 长期记忆插件 | 上下文管理插件 |
|---|---|---|
| **解决什么问题** | 跨会话记住用户偏好、历史决策 | 当前对话超长时不丢失上下文 |
| **记忆跨度** | 永久（跨会话） | 单会话内 |
| **代表项目** | memory-lancedb-pro, Mem0, memU | lossless-claw, OpenViking |
| **插件槽位** | `memory` | `contextEngine` |
| **能否同时用** | 可以，互补不冲突 | |

**最佳实践：** 同时启用一个长期记忆插件 + 一个上下文管理插件，前者让 Agent 跨会话"认识你"，后者让当前对话"不健忘"。

### 长期记忆

- [memory-lancedb-pro](https://github.com/CortexReach/memory-lancedb-pro) — **混合检索长期记忆**，向量+BM25+Cross-Encoder 重排序，自动捕获 6 类知识，Weibull 衰减模型（3.7K stars）`NEW`
- [memU](https://github.com/NevaMind-AI/memU) — **24/7 常驻 Agent 专用**，支持 Claude Skills + MCP 协议，Python 实现（13.2K stars）`NEW`
- [Mem0 集成](https://docs.mem0.ai/integrations/openclaw) — 最主流的持久记忆方案
- [OceanBase PowerMem](https://github.com/oceanbase/powermem) — 阿里 OceanBase 出品的记忆后端
- [Supermemory](https://github.com/supermemoryai/openclaw-supermemory) — Supermemory 集成

### 上下文管理

- [lossless-claw](https://github.com/Martian-Engineering/lossless-claw) — **无损上下文管理**，DAG 分层摘要 + SQLite 持久化，零信息丢失，`lcm_grep`/`lcm_expand` 随时回溯（3.7K stars）`NEW`
- [OpenViking](https://github.com/volcengine/OpenViking) — **字节跳动火山引擎出品**，Agent 上下文数据库，文件系统范式统一管理记忆/资源/技能，支持分层上下文传递与自进化（19.8K stars）`NEW`
- [MemOS](https://github.com/MemTensor/MemOS) — 记忆操作系统
- [memov](https://github.com/memovai/memov) — 通用记忆层
- [openamnesia](https://github.com/vincentkoc/openamnesia) — 持续学习上下文引擎

---

## Skill 开发

- [官方创建指南](https://docs.openclaw.ai/tools/creating-skills) — 官方 Skill 开发文档
- [插件 SDK 文档](https://docs.openclaw.ai/tools/plugin) — Plugin SDK
- [DataCamp: 自定义 Skill 教程](https://www.datacamp.com/tutorial/building-open-claw-skills) — 实操教程
- [中文开发指南](https://www.ququ123.top/en/2026/02/openclaw-skill-development/) — 中文 Skill 开发
- [HackMD 完整攻略](https://hackmd.io/@BASHCAT/rylaWmGuWe) — 繁体中文

---

## 云部署方案

- [阿里云官方一键部署](https://help.aliyun.com/zh/simple-application-server/use-cases/quickly-deploy-and-use-openclaw) — 68 元/年起
- [腾讯云部署实战](https://cloud.tencent.com/developer/article/2634684) — 99 元/年起
- [国内云服务器保姆级攻略](https://zhuanlan.zhihu.com/p/2002724451545027691) — 阿里云/腾讯云
- [七大平台深度对比](https://zhuanlan.zhihu.com/p/2003131482483482878) — 含华为云/Fly.io
- [5 大云平台保姆级教程](https://zhuanlan.zhihu.com/p/2002470825673107300)
- [多平台实战指南](https://apifox.com/apiskills/openclaw-docker-compose-feishu-dingtalk-wecom/) — Docker Compose + 飞书/钉钉/企微
- [菜鸟教程一键部署](https://www.runoob.com/ai-agent/openclaw-cloud.html)
- [HuggingClaw](https://github.com/democra-ai/HuggingClaw) — 免费在 HuggingFace Spaces 部署，2vCPU + 16GB RAM
- [openclaw-kasmvnc](https://github.com/ddong8/openclaw-kasmvnc) — 浏览器桌面实时观看智能体操作
- [u-claw](https://github.com/dongsheng123132/u-claw) — 中国离线安装包，适合网络限制环境
- [OpenClaw-Admin](https://github.com/itq5/OpenClaw-Admin) — Vue 3 网页管理面板

---

## 安全合规

- [国家互联网应急中心安全使用实践指南](https://www.news.cn/politics/20260322/62a2a10e08ce4c52ac08568f47ea1e23/c.html) — 官方权威
- [CNCERT 风险提示](https://www.news.cn/tech/20260310/d5e1d772bed046239ea3774903c08970/c.html)
- [阿里云安全关键防护措施](https://help.aliyun.com/zh/acsg/openclaw-key-protective-measures)
- [深信服风险全链路分析](https://www.sangfor.com.cn/blog/215c5ff0de074c28a6a75b4dbe919b88) — 82 个漏洞 + 20% 恶意插件
- [奇安信安全风险排查指南](https://www.qianxin.com/news/detail?news_id=14613) — PIPL/数据安全法合规
- [国枫律所合规风险分析](https://www.grandwaylaw.com/guofengshijiao/5640.html) — 法律视角
- [安全内参发展现状与对策报告](https://www.secrss.com/articles/88391)
- [腾讯 AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard) — 腾讯出品，全栈 AI 红队测试平台，含 OpenClaw 安全扫描
- [慢雾安全实践指南](https://github.com/slowmist/openclaw-security-practice-guide) — 面向 Agentic Zero-Trust 的安全实践
- [shellward](https://github.com/jnMetaCode/shellward) — AI Agent 安全中间件，8 层纵深防御 + DLP 数据防泄漏 + Prompt 注入检测，零依赖 `NEW`

---

## 社区与讨论

- [OpenClaw 中文社区](https://clawd.org.cn/) — 官网 + 微信群
- [GitHub 中文讨论区](https://github.com/openclaw/openclaw/discussions/10227)
- [ClawCN 中文站](https://clawcn.net/start/getting-started)
- [腾讯云开发者社区专栏](https://cloud.tencent.com/developer/article/2624973)
- [智源社区讨论](https://hub.baai.ac.cn/view/52807)
- [LINUX DO 论坛 Claw 类项目大横评](https://linux.do/t/topic/1790443) — 对比 OpenClaw、ZeroClaw、NanoClaw、IronClaw 等框架
- [OpenClaw 生态爆发（知乎）](https://zhuanlan.zhihu.com/p/2011029302767032126)

---

## 贡献指南

欢迎提交 PR 来补充资源！请确保提交的内容：

1. 与 OpenClaw 中文生态相关
2. 链接有效且可访问
3. 附有简短的中文描述
4. 放置在合适的分类下

如发现失效链接或信息有误，也欢迎提 Issue。

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

本列表以 [CC0 1.0 通用](https://creativecommons.org/publicdomain/zero/1.0/) 协议发布，可自由使用。
