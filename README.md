# Awesome Claw CN

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 中文 OpenClaw 生态资源精选列表

收录框架衍生、国内平台集成、国产大模型接入、中文教程、视频教程、技能插件、云部署、安全合规、社区等优质资源。

---

## 目录

- [框架与衍生项目](#框架与衍生项目)
- [国内平台集成](#国内平台集成)
- [国产大模型集成](#国产大模型集成)
- [中文教程](#中文教程)
- [视频教程](#视频教程)
- [Skills 与插件生态](#skills-与插件生态)
- [MCP 工具](#mcp-工具)
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

---

## 国内平台集成

### 微信

- [openclaw-wechat](https://github.com/freestylefly/openclaw-wechat) — 个人微信接入，扫码即用
- [weclaw](https://github.com/fastclaw-ai/weclaw) — WeChat AI Agent Bridge，支持多模型
- [openclaw-plugin-wecom](https://github.com/sunnoy/openclaw-plugin-wecom) — 企业微信 AI 机器人，流式输出 + 群聊
- [nexu](https://github.com/nexu-io/nexu) — 桌面客户端，一键桥接微信/飞书/Slack/Discord

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

### 小红书

- [openclaw-xhs](https://github.com/zhjiang22/openclaw-xhs) — MCP 集成 + 热点跟踪 + 记忆库导出
- [xiaohongshu-ops-skill](https://github.com/Xiangyu-CAS/xiaohongshu-ops-skill) — 小红书运营助手
- [xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) — 小红书 MCP 服务

### 微博

- [openclaw-weibo](https://github.com/wecode-ai/openclaw-weibo) — 微博私信通道

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

### 中文推荐文章

- [OpenClaw 最强军火库（2868 个精选 skills）](https://zhuanlan.zhihu.com/p/2010926090475045346) — 知乎
- [十大必装 OpenClaw Skills](https://zhuanlan.zhihu.com/p/2011751083702256050) — 知乎
- [ClawHub 必装 Skills 清单](https://www.cnblogs.com/informatics/p/19679935) — 博客园
- [52个官方 Skill + 5700 社区 Skill 测评](https://developer.aliyun.com/article/1712680) — 阿里云
- [新手必看！推荐10个神器技能包](https://cloud.tencent.com/developer/article/2634605) — 腾讯云

### 热门 Skills

- Web Browser — 180,000+ 下载，网页浏览与内容提取
- Telegram Bot — 145,000+ 下载，连接 Telegram
- GOG (Google Workspace) — Gmail/Calendar/Drive/Sheets 一体化
- Capability Evolver — 35,000+ 下载，AI 自我进化引擎
- Tavily Search — AI 优化联网搜索

### 多智能体与工作流

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

---

## 安全合规

- [国家互联网应急中心安全使用实践指南](https://www.news.cn/politics/20260322/62a2a10e08ce4c52ac08568f47ea1e23/c.html) — 官方权威
- [CNCERT 风险提示](https://www.news.cn/tech/20260310/d5e1d772bed046239ea3774903c08970/c.html)
- [阿里云安全关键防护措施](https://help.aliyun.com/zh/acsg/openclaw-key-protective-measures)
- [深信服风险全链路分析](https://www.sangfor.com.cn/blog/215c5ff0de074c28a6a75b4dbe919b88) — 82 个漏洞 + 20% 恶意插件
- [奇安信安全风险排查指南](https://www.qianxin.com/news/detail?news_id=14613) — PIPL/数据安全法合规
- [国枫律所合规风险分析](https://www.grandwaylaw.com/guofengshijiao/5640.html) — 法律视角
- [安全内参发展现状与对策报告](https://www.secrss.com/articles/88391)

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
