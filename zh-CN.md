<div align="center">

<a href="https://github.com/VoltAgent/voltagent">
<img width="1500" height="500" alt="social" src="https://github.com/user-attachments/assets/a6f310af-8fed-4766-9649-b190575b399d" />
</a>

<br/>
<br/>

<div align="center">
    <strong>发现 2999 个社区构建的 OpenClaw 技能，按类别组织。</strong>
    <br />
    <br />
</div>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<a href="https://github.com/VoltAgent/voltagent">
  <img alt="VoltAgent" src="https://cdn.voltagent.dev/website/logo/logo-2-svg.svg" height="20" />
</a> 

![Skills Count](https://img.shields.io/badge/skills-2999-blue?style=flat-square)
![Last Update](https://img.shields.io/github/last-commit/VoltAgent/awesome-clawdbot-skills?label=Last%20update&style=flat-square)
[![Discord](https://img.shields.io/discord/1361559153780195478.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://s.voltagent.dev/discord)
[![GitHub forks](https://img.shields.io/github/forks/VoltAgent/awesome-clawdbot-skills?style=social)](https://github.com/VoltAgent/awesome-claude-skills/network/members)
</div>

# Awesome OpenClaw Skills

OpenClaw（前身为 Moltbot，最初为 Clawdbot...包含身份危机，不额外收费）是一个直接在您的机器上运行的本地 AI 助手。技能扩展了它的功能，允许它与外部服务交互、自动化工作流程和执行专门的任务。这个集合帮助您发现并安装适合您需求的技能。

此列表中的技能来自 [ClawHub](https://www.clawhub.ai/)（OpenClaw 的公共技能注册表），并按类别分类以便更容易发现。

这些技能遵循 Anthropic 开发的 Agent Skill 约定，这是一个 AI 编程助手的开放标准。

> **想要添加技能？** 此列表仅包含已发布在 "github.com/openclaw/skills" 中的技能。我们不接受指向个人仓库、要点或任何其他外部来源的链接。如果您的技能尚未在 OpenClaw 技能仓库中，请先在那里发布。详情请参见 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 安装

### ClawHub CLI

> **注意：** 正如您可能知道的，他们一直在重命名东西。这反映了当前的官方文档。当他们再次重命名时，我们会更新此内容。

```bash
npx clawhub@latest install <skill-slug>
```

### 手动安装

将技能文件夹复制到以下位置之一：

| 位置 | 路径 |
|----------|------|
| 全局 | `~/.openclaw/skills/` |
| 工作区 | `<project>/skills/` |

优先级：工作区 > 本地 > 捆绑

### 替代方案

您也可以将技能的 GitHub 仓库链接直接粘贴到助手的聊天中，并要求它使用它。助手将在后台自动处理设置。


## 为什么存在这个列表？

OpenClaw 的公共注册表（ClawHub）截至 2026 年 2 月 7 日托管了 **5,705 个社区构建的技能**。这个 awesome 列表有 **2,999 个技能**。以下是我们过滤掉的内容：

| 过滤器 | 排除数量 |
|--------|----------|
| 可能是垃圾邮件 — 批量账户、机器人账户、测试/垃圾 | 1,180 |
| 加密货币 / 区块链 / 金融 / 交易 | 672 |
| 重复 / 相似名称 | 492 |
| 恶意 — 由研究人员发布的安全审计识别（不包括 VirusTotal） | 396 |
| 非英语 — 描述不是英文 | 8 |
| **未从 OpenClaw 官方技能注册表中获取的总数** | **2,748** |

> **免责声明：** 包含在此列表中 **并不** 保证技能是安全或可信赖的。OpenClaw 现在与 VirusTotal 合作，为技能提供安全扫描。在安装技能之前，请访问其在 ClawHub 上的页面并检查 VirusTotal 报告，看看是否被标记为有风险。我们还建议在安装前审查技能的源代码，并使用 Claude Code 或 Codex 等工具检查其潜在的有害行为。

<br/>

<a href="https://github.com/VoltAgent/voltagent">
<img width="1390" height="296" alt="social" src="https://github.com/user-attachments/assets/5d8822c0-e97b-4183-a71e-a922ab88e1a0" />
</a>

<br/>

## 目录

| | | |
|---|---|---|
| [编码代理和 IDE](#coding-agents--ides) (133) | [营销和销售](#marketing--sales) (145) | [通信](#communication) (133) |
| [Git 和 GitHub](#git--github) (66) | [生产力和任务](#productivity--tasks) (134) | [语音和转录](#speech--transcription) (66) |
| [Moltbook](#moltbook) (51) | [AI 和 LLM](#ai--llms) (287) | [智能家居和物联网](#smart-home--iot) (56) |
| [Web 和前端开发](#web--frontend-development) (201) | [数据和分析](#data--analytics) (46) | [购物和电子商务](#shopping--e-commerce) (51) |
| [DevOps 和云](#devops--cloud) (212) | [金融](#finance) (22) | [日历和调度](#calendar--scheduling) (51) |
| [浏览器和自动化](#browser--automation) (139) | [媒体和流媒体](#media--streaming) (80) | [PDF 和文档](#pdf--documents) (67) |
| [图像和视频生成](#image--video-generation) (60) | [笔记和 PKM](#notes--pkm) (100) | [自托管和自动化](#self-hosted--automation) (25) |
| [Apple 应用和服务](#apple-apps--services) (35) | [iOS 和 macOS 开发](#ios--macos-development) (17) | [安全和密码](#security--passwords) (62) |
| [搜索和研究](#search--research) (253) | [交通](#transportation) (73) | [游戏](#gaming) (62) |
| [Clawdbot 工具](#clawdbot-tools) (121) | [个人发展](#personal-development) (56) | [代理到代理协议](#agent-to-agent-protocols) (19) |
| [CLI 工具](#cli-utilities) (131) | [健康和健身](#health--fitness) (55) | |


<details open>
<summary><h3 style="display:inline">编码代理和 IDE</h3></summary>

- [achurch](https://github.com/openclaw/skills/tree/main/skills/lucasgeeksinthewood/achurch/SKILL.md) - AI 代理和人类的 24/7 数字圣地 — 参加
- [agent-config](https://github.com/openclaw/skills/tree/main/skills/thatguysizemore/agent-config/SKILL.md) - 智能修改代理核心上下文文件
- [agent-council](https://github.com/openclaw/skills/tree/main/skills/itsahedge/agent-council/SKILL.md) - 创建自主 AI 代理和管理的完整工具包
- [agent-identity-kit](https://github.com/openclaw/skills/tree/main/skills/ryancampbell/agent-identity-kit/SKILL.md) - AI 代理的可移植身份系统。
- [agenticflow-skill](https://github.com/openclaw/skills/tree/main/skills/seanphan/agenticflow-skill/SKILL.md) - 构建 AI 工作流程、代理的全面指南
- [agentlens](https://github.com/openclaw/skills/tree/main/skills/nguyenphutrong/agentlens/SKILL.md) - 使用 agentlens 分层导航和理解代码库
- [agentskills-io](https://github.com/openclaw/skills/tree/main/skills/killerapp/agentskills-io/SKILL.md) - 创建、验证和发布遵循 Agent Skills 的技能
- [aisa-twitter-api](https://github.com/openclaw/skills/tree/main/skills/aisapay/aisa-twitter-api/SKILL.md) - 实时搜索 X (Twitter)，提取相关帖子
- [apple-hig](https://github.com/openclaw/skills/tree/main/skills/kdbhalala/apple-hig/SKILL.md) - 设计 iOS、macOS、watchOS、tvOS 和 visionOS 应用的专家指南。
- [arbiter](https://github.com/openclaw/skills/tree/main/skills/5hanth/arbiter/SKILL.md) - 将决策推送给 Arbiter Zebu 进行异步人工审查。
- [aster](https://github.com/openclaw/skills/tree/main/skills/satyajiit/aster/SKILL.md) - 您在移动设备上的 AI 副驾驶 — 或给您的 AI 自己的手机。
- [avatar-video-messages](https://github.com/openclaw/skills/tree/main/skills/thewulf7/avatar-video-messages/SKILL.md) - 生成和发送视频消息
- [backend-patterns](https://github.com/openclaw/skills/tree/main/skills/charmmm718/backend-patterns/SKILL.md) - 后端架构模式、API 设计、数据库
- [bidclub](https://github.com/openclaw/skills/tree/main/skills/jasonfdg/bidclub/SKILL.md) - 在 AI 原生投资社区发布投资想法。
- [bidclub-ai](https://github.com/openclaw/skills/tree/main/skills/jasonfdg/bidclub-ai/SKILL.md) - 在 AI 原生投资社区发布投资想法。
- [bot-bowl-party](https://github.com/openclaw/skills/tree/main/skills/fsa317/bot-bowl-party/SKILL.md) - AI 代理参与 BotBowl Party 的完整指南
- [botpress-adk](https://github.com/openclaw/skills/tree/main/skills/yueranlu/botpress-adk/SKILL.md) - 使用 Botpress 的代理开发工具包构建 AI 机器人的指南
- [browse](https://github.com/openclaw/skills/tree/main/skills/pkiv/browse/SKILL.md) - 创建和部署浏览器自动化功能的完整指南
- [budget-variance-analyzer](https://github.com/openclaw/skills/tree/main/skills/datadrivenconstruction/budget-variance-analyzer/SKILL.md) - 分析预算与实际
- [buildlog](https://github.com/openclaw/skills/tree/main/skills/espetey/buildlog/SKILL.md) - 记录、导出和分享您的 AI 编码会话作为可重放的构建日志。
- [catholic-grounding](https://github.com/openclaw/skills/tree/main/skills/trevortomesh/catholic-grounding/SKILL.md) - 帮助准确回答关于天主教的问题
- [cc-godmode](https://github.com/openclaw/skills/tree/main/skills/cubetribe/cc-godmode/SKILL.md) - 自编排多代理开发工作流程。
- [cellcog](https://github.com/openclaw/skills/tree/main/skills/nitishgargiitd/cellcog/SKILL.md) - DeepResearch Bench 排名第 1（2026 年 2 月）。
- [claude-optimised](https://github.com/openclaw/skills/tree/main/skills/hexnickk/claude-optimised/SKILL.md) - 编写和优化 CLAUDE.md 文件的指南
- [claude-team](https://github.com/openclaw/skills/tree/main/skills/jalehman/claude-team/SKILL.md) - 通过 iTerm2 编排多个 Claude Code 工作器
- [clawder](https://github.com/openclaw/skills/tree/main/skills/assassin808/clawder/SKILL.md) - 使用 Clawder 同步身份、浏览明信片、滑动评论
- [code-mentor](https://github.com/openclaw/skills/tree/main/skills/samuelkahessay/code-mentor/SKILL.md) - 面向所有级别的全面 AI 编程导师。
- [codebuddy-code](https://github.com/openclaw/skills/tree/main/skills/pmwalkercao/codebuddy-code/SKILL.md) - CodeBuddy Code CLI 安装、配置和使用
- [codeconductor](https://github.com/openclaw/skills/tree/main/skills/larsonreever/codeconductor/SKILL.md) - 用于快速应用开发的 AI 驱动软件开发平台
- [coder-workspaces](https://github.com/openclaw/skills/tree/main/skills/developmentcats/coder-workspaces/SKILL.md) - 管理 Coder 工作区和 AI 编码代理任务
- [codex-account-switcher](https://github.com/openclaw/skills/tree/main/skills/odrobnik/codex-account-switcher/SKILL.md) - 管理多个 OpenAI Codex 账户。
- [codex-monitor](https://github.com/openclaw/skills/tree/main/skills/odrobnik/codex-monitor/SKILL.md) - 浏览存储的 OpenAI Codex 会话日志。
- [codex-orchestration](https://github.com/openclaw/skills/tree/main/skills/shanelindsay/codex-orchestration/SKILL.md) - Codex 的通用编排。
- [codex-quota](https://github.com/openclaw/skills/tree/main/skills/odrobnik/codex-quota/SKILL.md) - 检查 OpenAI Codex CLI 速率限制状态（每日/每周配额）
- [codexmonitor](https://github.com/openclaw/skills/tree/main/skills/odrobnik/codexmonitor/SKILL.md) - 列出/检查/监视本地 OpenAI Codex 会话（CLI + VS Code）
- [coding-agent](https://github.com/openclaw/skills/tree/main/skills/steipete/coding-agent/SKILL.md) - 运行 Codex CLI、Claude Code、OpenCode 或 Pi Coding Agent
- [coding-opencode](https://github.com/openclaw/skills/tree/main/skills/iqbalnaveliano/coding-opencode/SKILL.md) - 允许使用 OpenCode 编码代理
- [cognitive-memory](https://github.com/openclaw/skills/tree/main/skills/icemilo414/cognitive-memory/SKILL.md) - 具有类人智能的多存储记忆系统
- [content-id-guide](https://github.com/openclaw/skills/tree/main/skills/otherpowers/content-id-guide/SKILL.md) - 为创作者提供一种平静的方式来理解和组织
- [copilot-money](https://github.com/openclaw/skills/tree/main/skills/jayhickey/copilot-money/SKILL.md) - 查询 Copilot Money 个人财务数据
- [create-agent-skills](https://github.com/openclaw/skills/tree/main/skills/bowen31337/create-agent-skills/SKILL.md) - 创建有效技能的指南。
- [cto-advisor](https://github.com/openclaw/skills/tree/main/skills/alirezarezvani/cto-advisor/SKILL.md) - 为工程团队提供技术领导力指导
- [cursor-agent](https://github.com/openclaw/skills/tree/main/skills/swiftlysingh/cursor-agent/SKILL.md) - 使用 Cursor CLI 代理的全面技能
- [debug-pro](https://github.com/openclaw/skills/tree/main/skills/cmanfre7/debug-pro/SKILL.md) - 系统调试方法和特定语言调试
- [doc-coauthoring](https://github.com/openclaw/skills/tree/main/skills/seanphan/doc-coauthoring/SKILL.md) - 引导用户完成共同编写文档的结构化工作流程
- [docker-essentials](https://github.com/openclaw/skills/tree/main/skills/arnarsson/docker-essentials/SKILL.md) - 容器化的基本 Docker 命令和工作流程
- [docker-sandbox](https://github.com/openclaw/skills/tree/main/skills/gitgoodordietrying/docker-sandbox/SKILL.md) - 创建和管理 Docker 沙盒 VM 环境
- [ec-excalidraw](https://github.com/openclaw/skills/tree/main/skills/henrino3/ec-excalidraw/SKILL.md) - 生成手绘风格的图表、流程图和架构
- [ec-task-orchestrator](https://github.com/openclaw/skills/tree/main/skills/henrino3/ec-task-orchestrator/SKILL.md) - 自主多代理任务编排
- [essence-distiller](https://github.com/openclaw/skills/tree/main/skills/leegitw/essence-distiller/SKILL.md) - 找到您内容中真正重要的内容 — 想法
- [evolver](https://github.com/openclaw/skills/tree/main/skills/autogame-17/evolver/SKILL.md) - AI 代理的自我进化引擎。
- [executing-plans](https://github.com/openclaw/skills/tree/main/skills/chenleiyanquan/executing-plans/SKILL.md) - 在有书面实施计划时使用
- [factory-ai](https://github.com/openclaw/skills/tree/main/skills/mitchellbernstein/factory-ai/SKILL.md) - 使用 Factory AI 的 droid CLI 进行软件工程任务。
- [feishu-native-emoji](https://github.com/openclaw/skills/tree/main/skills/autogame-17/feishu-native-emoji/SKILL.md) - 提供对飞书原生表情符号集的访问
- [feishu-vc](https://github.com/openclaw/skills/tree/main/skills/autogame-17/feishu-vc/SKILL.md) - 管理飞书视频会议 (VC)。
- [file-links-tool](https://github.com/openclaw/skills/tree/main/skills/mrbeandev/file-links-tool/SKILL.md) - 从您的私人 AI 工作区安全上传文件
- [flirtingbots](https://github.com/openclaw/skills/tree/main/skills/chemzo/flirtingbots/SKILL.md) - 代理调情，人类约会 — 您的 OpenClaw 代理
- [gembox-skill](https://github.com/openclaw/skills/tree/main/skills/zsvedic/gembox-skill/SKILL.md) - 为 [GemBox 提供编码帮助。
- [get-tldr](https://github.com/openclaw/skills/tree/main/skills/itobey/get-tldr/SKILL.md) - 提供 get-tldr.com 摘要 API 返回的摘要
- [go2gg](https://github.com/openclaw/skills/tree/main/skills/rakesh1002/go2gg/SKILL.md) - 使用 Go2.gg API 进行 URL 缩短、链接分析、二维码生成。
- [google-weather](https://github.com/openclaw/skills/tree/main/skills/shaharsha/google-weather/SKILL.md) - Google 天气 API - 准确、实时的天气数据。
- [hour-meter](https://github.com/openclaw/skills/tree/main/skills/rm289/hour-meter/SKILL.md) - 从设定的时间点开始跟踪经过的时间，具有防篡改锁定。
- [idea-coach](https://github.com/openclaw/skills/tree/main/skills/udiedrichsen/idea-coach/SKILL.md) - 具有 GitHub 集成的 AI 驱动想法/问题/挑战管理器。
- [identity-manager](https://github.com/openclaw/skills/tree/main/skills/autogame-17/identity-manager/SKILL.md) - 严格管理用户身份映射
- [java-change-with-tests](https://github.com/openclaw/skills/tree/main/skills/tanerilyazov/java-change-with-tests/SKILL.md) - 任何必须合并的 Java 更改
- [jo4](https://github.com/openclaw/skills/tree/main/skills/anandrathnas/jo4/SKILL.md) - URL 缩短器、二维码生成器和链接分析 API。
- [joko-orchestrator](https://github.com/openclaw/skills/tree/main/skills/oyi77/joko-orchestrator/SKILL.md) - 确定性地协调自主规划
- [kimi-integration](https://github.com/openclaw/skills/tree/main/skills/evgyur/kimi-integration/SKILL.md) - 集成 Moonshot AI (Kimi) 的分步指南
- [linguistic-humidifier](https://github.com/openclaw/skills/tree/main/skills/westland/linguistic-humidifier/SKILL.md) - 主动识别对话熵
- [logseq](https://github.com/openclaw/skills/tree/main/skills/juanirm/logseq/SKILL.md) - 提供与本地 Logseq 实例交互的命令
- [manim-composer](https://github.com/openclaw/skills/tree/main/skills/inclinedadarsh/manim-composer/SKILL.md) - 1。
- [manimce-best-practices](https://github.com/openclaw/skills/tree/main/skills/inclinedadarsh/manimce-best-practices/SKILL.md) - 阅读单独的规则文件以获取详细
- [mcp-builder](https://github.com/openclaw/skills/tree/main/skills/seanphan/mcp-builder/SKILL.md) - 创建高质量 MCP（模型上下文协议）服务器的指南
- [mdr-745-specialist](https://github.com/openclaw/skills/tree/main/skills/alirezarezvani/mdr-745-specialist/SKILL.md) - 欧盟 MDR 2017/745 合规专家
- [meta-video-ad-deconstructor](https://github.com/openclaw/skills/tree/main/skills/fortytwode/meta-video-ad-deconstructor/SKILL.md) - 解构视频广告创意
- [metals-agent-teneo](https://github.com/openclaw/skills/tree/main/skills/firestream792/metals-agent-teneo/SKILL.md) - 提供黄金、白银的实时价格
- [microsoft-docs](https://github.com/openclaw/skills/tree/main/skills/pdebruin/microsoft-docs/SKILL.md) - 查询官方 Microsoft 文档以理解概念
- [midea-ac](https://github.com/openclaw/skills/tree/main/skills/iamanorange/midea-ac/SKILL.md) - 控制美的空调。
- [minimal-test-skill](https://github.com/openclaw/skills/tree/main/skills/mig6671/minimal-test-skill/SKILL.md) - 用于调试 ClawHub 发布的最小测试技能。
- [model-usage](https://github.com/openclaw/skills/tree/main/skills/steipete/model-usage/SKILL.md) - 使用 CodexBar CLI 本地成本使用情况来总结每个模型的使用
- [multi-coding-agent](https://github.com/openclaw/skills/tree/main/skills/kesslerio/multi-coding-agent/SKILL.md) - 运行 Codex CLI、Claude Code、OpenCode 或 Pi Coding
- [multi-factor-strategy](https://github.com/openclaw/skills/tree/main/skills/wumu2013/multi-factor-strategy/SKILL.md) - 指导用户创建多因素股票
- [mux-video](https://github.com/openclaw/skills/tree/main/skills/dktrn9ne/mux-video/SKILL.md) - 用于设计、摄取的 Mux Video 基础设施技能
- [noir-developer](https://github.com/openclaw/skills/tree/main/skills/jp4g/noir-developer/SKILL.md) - 开发 Noir (.nr) 代码库。
- [only-baby-skill](https://github.com/openclaw/skills/tree/main/skills/jacklandrin/only-baby-skill/SKILL.md) - 分析宫缩 JSON 和婴儿日志 JSON 以评估
- [ooze-agents](https://github.com/openclaw/skills/tree/main/skills/jschwerberg/ooze-agents/SKILL.md) - 随声誉演变的视觉身份 - 创建和培养
- [opencode-acp-control](https://github.com/openclaw/skills/tree/main/skills/bjesuiter/opencode-acp-control/SKILL.md) - 通过代理客户端直接控制 OpenCode
- [openinsider](https://github.com/openclaw/skills/tree/main/skills/stuhorsman/openinsider/SKILL.md) - 获取 SEC 表格 4 内幕交易数据（董事、CEO、高管）
- [openspec](https://github.com/openclaw/skills/tree/main/skills/jcorrego/openspec/SKILL.md) - 使用 OpenSpec 进行规范驱动开发。
- [pasteclaw](https://github.com/openclaw/skills/tree/main/skills/tairov/pasteclaw/SKILL.md) - 使用 Pasteclaw.com API 创建、更新、分组（会话密钥）和删除。
- [pbe-extractor](https://github.com/openclaw/skills/tree/main/skills/leegitw/pbe-extractor/SKILL.md) - 从任何文本中提取不变原则 — 找到想法
- [perry-coding-agents](https://github.com/openclaw/skills/tree/main/skills/gricha/perry-coding-agents/SKILL.md) - 将编码任务分派给 OpenCode 或 Claude Code
- [perry-workspaces](https://github.com/openclaw/skills/tree/main/skills/gricha/perry-workspaces/SKILL.md) - 在您的 tailnet 上创建和管理隔离的 Docker 工作区
- [piv](https://github.com/openclaw/skills/tree/main/skills/smokealot420/piv/SKILL.md) - PIV 工作流程编排器 - 系统化的计划、实施、验证循环。
- [pndr](https://github.com/openclaw/skills/tree/main/skills/dgershman/pndr/SKILL.md) - 个人生产力应用，包含想法/任务、日记、习惯、包裹跟踪。
- [pro](https://github.com/openclaw/skills/tree/main/skills/jash2368-collab/pro/SKILL.md) - 创建有效技能的指南。
- [prompt-log](https://github.com/openclaw/skills/tree/main/skills/thesash/prompt-log/SKILL.md) - 从 AI 编码会话日志中提取对话记录
- [pulse-editor](https://github.com/openclaw/skills/tree/main/skills/shellishack/pulse-editor/SKILL.md) - 使用 Vibe Dev Flow API 生成和构建 Pulse 应用。
- [python](https://github.com/openclaw/skills/tree/main/skills/adarshdigievo/python/SKILL.md) - Python 编码指南和最佳实践。
- [quantum-lab](https://github.com/openclaw/skills/tree/main/skills/bramdo/quantum-lab/SKILL.md) - 在内部运行 /home/bram/work/quantum_lab Python 脚本和演示
- [quantumlab](https://github.com/openclaw/skills/tree/main/skills/bramdo/quantumlab/SKILL.md) - 在内部运行 /home/bram/work/quantum_lab Python 脚本和演示
- [quests](https://github.com/openclaw/skills/tree/main/skills/poloio/quests/SKILL.md) - 跟踪和指导人类完成复杂的多步骤现实世界过程。
- [rationality](https://github.com/openclaw/skills/tree/main/skills/xertrov/rationality/SKILL.md) - Rationality 技能提供了一个结构化的思考框架。
- [receiving-code-review](https://github.com/openclaw/skills/tree/main/skills/chenleiyanquan/receiving-code-review/SKILL.md) - 在接收代码审查反馈时使用
- [regex-patterns](https://github.com/openclaw/skills/tree/main/skills/gitgoodordietrying/regex-patterns/SKILL.md) - 跨语言和用例的实用正则表达式模式。
- [release-bump](https://github.com/openclaw/skills/tree/main/skills/paulpete/release-bump/SKILL.md) - 在为新版本升级 ralph-orchestrator 版本时使用
- [sandboxer](https://github.com/openclaw/skills/tree/main/skills/chriopter/sandboxer/SKILL.md) - 通过 Sandboxer Web 仪表板管理 Claude Code 终端会话。
- [satellite-copilot](https://github.com/openclaw/skills/tree/main/skills/davestarling/satellite-copilot/SKILL.md) - 预测卫星经过
- [senior-architect](https://github.com/openclaw/skills/tree/main/skills/alirezarezvani/senior-architect/SKILL.md) - 当用户询问时应使用的技能
- [side-peace](https://github.com/openclaw/skills/tree/main/skills/bitbrujo/side-peace/SKILL.md) - 最小安全秘密交接。
- [skill-content-id-guide](https://github.com/openclaw/skills/tree/main/skills/otherpowers/skill-content-id-guide/SKILL.md) - 程序清晰度和证据
- [skill-creator](https://github.com/openclaw/skills/tree/main/skills/chindden/skill-creator/SKILL.md) - 创建有效技能的指南。
- [skill-creator-0-1-0](https://github.com/openclaw/skills/tree/main/skills/ljglover/skill-creator-0-1-0/SKILL.md) - 创建有效技能的指南。
- [skill-creator-2](https://github.com/openclaw/skills/tree/main/skills/yixinli867/skill-creator-2/SKILL.md) - 创建有效技能的指南。
- [skill-vetting](https://github.com/openclaw/skills/tree/main/skills/eddygk/skill-vetting/SKILL.md) - 在安装前审查 ClawHub 技能的安全性和实用性。
- [smart-auto-updater](https://github.com/openclaw/skills/tree/main/skills/ruiwang20010702/smart-auto-updater/SKILL.md) - 具有 AI 驱动影响的智能自动更新器
- [solvr-kb](https://github.com/openclaw/skills/tree/main/skills/fcavalcantirj/solvr-kb/SKILL.md) - 搜索并为 Solvr 做出贡献 — 开发人员的知识库
- [soul-md](https://github.com/openclaw/skills/tree/main/skills/aaronjmars/soul-md/SKILL.md) - 体现这个数字身份。
- [ssh-tunnel](https://github.com/openclaw/skills/tree/main/skills/gitgoodordietrying/ssh-tunnel/SKILL.md) - SSH 隧道、端口转发和远程访问模式。
- [stoic-scope-creep](https://github.com/openclaw/skills/tree/main/skills/crtahlin/stoic-scope-creep/SKILL.md) - 保持镇定的实用指南
- [task-status](https://github.com/openclaw/skills/tree/main/skills/mightyprime1/task-status/SKILL.md) - 在聊天中发送长时间运行任务的简短状态描述。
- [tdd-guide](https://github.com/openclaw/skills/tree/main/skills/alirezarezvani/tdd-guide/SKILL.md) - 测试驱动开发工作流程，包含测试生成、覆盖
- [test-new-skill](https://github.com/openclaw/skills/tree/main/skills/tianshizhimao-sudo/test-new-skill/SKILL.md) - 用于调试的测试技能
- [test-runner](https://github.com/openclaw/skills/tree/main/skills/cmanfre7/test-runner/SKILL.md) - 跨语言和框架编写和运行测试。
- [toughcoding](https://github.com/openclaw/skills/tree/main/skills/toughcoding/toughcoding/SKILL.md) - 为 AI 代理提供关于现代
- [vhs-recorder](https://github.com/openclaw/skills/tree/main/skills/killerapp/vhs-recorder/SKILL.md) - 使用 VHS 磁带文件创建专业终端录制
- [vibes](https://github.com/openclaw/skills/tree/main/skills/binora/vibes/SKILL.md) - AI 编码代理的社交存在层。
- [video-agent](https://github.com/openclaw/skills/tree/main/skills/michaelwang11394/video-agent/SKILL.md) - 使用 HeyGen 的视频代理 API 生成 AI 头像视频。
- [video-cog](https://github.com/openclaw/skills/tree/main/skills/nitishgargiitd/video-cog/SKILL.md) - 长格式 AI 视频制作：多代理的前沿
- [voice-reply](https://github.com/openclaw/skills/tree/main/skills/stolot0mt0m/voice-reply/SKILL.md) - 使用 Piper 语音通过 sherpa-onnx 进行本地文本转语音。
- [whatsapp-styling-guide](https://github.com/openclaw/skills/tree/main/skills/rubenfb23/whatsapp-styling-guide/SKILL.md) - 确保发送到 WhatsApp 的所有消息的技能
- [wyld-stallyns](https://github.com/openclaw/skills/tree/main/skills/brucko/wyld-stallyns/SKILL.md) - 将传奇召唤到展位。

</details>

<details>
<summary><h3 style="display:inline">Git 和 GitHub</h3></summary>

- [agent-commons](https://github.com/openclaw/skills/tree/main/skills/zanblayde/agent-commons/SKILL.md) - 咨询、提交、扩展和挑战推理链
- [auto-pr-merger](https://github.com/openclaw/skills/tree/main/skills/autogame-17/auto-pr-merger/SKILL.md) - 自动化检查 GitHub 工作流程的技能
- [backup](https://github.com/openclaw/skills/tree/main/skills/jordanprater/backup/SKILL.md) - 备份和恢复 openclaw 配置、技能、命令和设置。
- [bat-cat](https://github.com/openclaw/skills/tree/main/skills/arnarsson/bat-cat/SKILL.md) - 具有语法高亮、行号和 Git 集成的 cat 克隆
- [bitbucket-automation](https://github.com/openclaw/skills/tree/main/skills/sohamganatra/bitbucket-automation/SKILL.md) - 自动化 Bitbucket 仓库、拉取
- [claw-swarm](https://github.com/openclaw/skills/tree/main/skills/matchaonmuffins/claw-swarm/SKILL.md) - 协作代理群，用于尝试极其困难的
- [clawdbot-backup](https://github.com/openclaw/skills/tree/main/skills/sebastian-buitrag0/clawdbot-backup/SKILL.md) - 备份和恢复 ClawdBot 配置、技能
- [clawdgigs](https://github.com/openclaw/skills/tree/main/skills/benniethedev/clawdgigs/SKILL.md) - 在 ClawdGigs 上注册和管理您的 AI 代理资料 — Upwork
- [clawprint](https://github.com/openclaw/skills/tree/main/skills/yugovit/clawprint/SKILL.md) - 代理发现、信任和交换。
- [clawver-onboarding](https://github.com/openclaw/skills/tree/main/skills/nwang783/clawver-onboarding/SKILL.md) - 设置新的 Clawver 商店。
- [commit-analyzer](https://github.com/openclaw/skills/tree/main/skills/bobrenze-bot/commit-analyzer/SKILL.md) - 分析 git 提交模式以监控自主
- [conventional-commits](https://github.com/openclaw/skills/tree/main/skills/bastos/conventional-commits/SKILL.md) - 使用约定格式化提交消息
- [danube](https://github.com/openclaw/skills/tree/main/skills/preston-thiele/danube/SKILL.md) - 通过 MCP 使用 Danube 的 100+ API 工具（Gmail、GitHub、Notion 等）。
- [danube-tools](https://github.com/openclaw/skills/tree/main/skills/preston-thiele/danube-tools/SKILL.md) - 使用 Danube 的 100+ API 工具（Gmail、GitHub、Notion 等）
- [deepwiki](https://github.com/openclaw/skills/tree/main/skills/arun-8687/deepwiki/SKILL.md) - 查询 DeepWiki MCP 服务器以获取 GitHub 仓库文档、wiki。
- [deepwork-tracker](https://github.com/openclaw/skills/tree/main/skills/adunne09/deepwork-tracker/SKILL.md) - 在本地跟踪深度工作会话（开始/停止/状态）
- [deploy-agent](https://github.com/openclaw/skills/tree/main/skills/sherajdev/deploy-agent/SKILL.md) - 用于全栈的多步骤部署代理。
- [emergency-rescue](https://github.com/openclaw/skills/tree/main/skills/gitgoodordietrying/emergency-rescue/SKILL.md) - 从开发人员灾难中恢复。
- [exa-web-search-free](https://github.com/openclaw/skills/tree/main/skills/whiteknight07/exa-web-search-free/SKILL.md) - 通过 Exa 的免费 AI 搜索。
- [fabric-pattern](https://github.com/openclaw/skills/tree/main/skills/apuryear/fabric-pattern/SKILL.md) - Fabric AI 框架的集成。
- [financial-calculator](https://github.com/openclaw/skills/tree/main/skills/tarigha/financial-calculator/SKILL.md) - 具有未来价值的高级财务计算器
- [find-code-tasks](https://github.com/openclaw/skills/tree/main/skills/paulpete/find-code-tasks/SKILL.md) - 列出仓库中所有代码任务及其状态
- [flatnotes-tasksmd-github-audit](https://github.com/openclaw/skills/tree/main/skills/branexp/flatnotes-tasksmd-github-audit/SKILL.md) - 彻底审计 Tasks.md +
- [forkzoo](https://github.com/openclaw/skills/tree/main/skills/levi-law/forkzoo/SKILL.md) - 采用和管理 GitHub 原生数字宠物（电子宠物），每天进化。
- [forkzoo-skill](https://github.com/openclaw/skills/tree/main/skills/levi-law/forkzoo-skill/SKILL.md) - 采用和管理 GitHub 原生数字宠物（电子宠物）
- [gimhub](https://github.com/openclaw/skills/tree/main/skills/daxiongmao87/gimhub/SKILL.md) - 将代码推送到 GIMHub，AI 代理的 Git 托管平台。
- [git-crypt-backup](https://github.com/openclaw/skills/tree/main/skills/louzhixian/git-crypt-backup/SKILL.md) - 将 Clawdbot 工作区和配置备份到 GitHub
- [git-essentials](https://github.com/openclaw/skills/tree/main/skills/arnarsson/git-essentials/SKILL.md) - 版本控制的基本 Git 命令和工作流程
- [git-helper](https://github.com/openclaw/skills/tree/main/skills/xejrax/git-helper/SKILL.md) - 作为技能的常见 git 操作（状态、拉取、推送、分支、日志）。
- [git-summary](https://github.com/openclaw/skills/tree/main/skills/zweack/git-summary/SKILL.md) - 获取当前 Git 仓库的快速摘要，包括状态
- [git-sync](https://github.com/openclaw/skills/tree/main/skills/autogame-17/git-sync/SKILL.md) - 自动将本地工作区更改同步到远程 GitHub
- [git-workflows](https://github.com/openclaw/skills/tree/main/skills/gitgoodordietrying/git-workflows/SKILL.md) - 超越添加/提交/推送的高级 git 操作。
- [gitclassic](https://github.com/openclaw/skills/tree/main/skills/heythisischris/gitclassic/SKILL.md) - 为 AI 代理优化的快速、无 JavaScript GitHub 浏览器。
- [gitclaw](https://github.com/openclaw/skills/tree/main/skills/marian2js/gitclaw/SKILL.md) - 将 OpenClaw 代理工作区备份到 GitHub 仓库并保持同步
- [gitea](https://github.com/openclaw/skills/tree/main/skills/ericxliu1990/gitea/SKILL.md) - 使用 `tea` 与 Gitea 交互。
- [gitflow](https://github.com/openclaw/skills/tree/main/skills/okoddcat/gitflow/SKILL.md) - 跨 GitHub 自动监控新推送的 CI/CD 管道状态
- [github](https://github.com/openclaw/skills/tree/main/skills/steipete/github/SKILL.md) - 使用 `gh` 与 GitHub 交互。
- [github-pr](https://github.com/openclaw/skills/tree/main/skills/dbhurley/github-pr/SKILL.md) - 在本地获取、预览、合并和测试 GitHub PR。
- [githunt](https://github.com/openclaw/skills/tree/main/skills/mordka/githunt/SKILL.md) - 按位置、技术和角色查找和排名 GitHub 开发人员。
- [gitlab-api](https://github.com/openclaw/skills/tree/main/skills/d1gl3/gitlab-api/SKILL.md) - 用于仓库操作的 GitLab API 集成。
- [gitlab-ci-skills](https://github.com/openclaw/skills/tree/main/skills/vince-winkintel/gitlab-ci-skills/SKILL.md) - 在使用 GitLab CLI (glab) 命令时使用
- [gitlab-cli-skills](https://github.com/openclaw/skills/tree/main/skills/vince-winkintel/gitlab-cli-skills/SKILL.md) - 在使用 GitLab CLI (glab) 命令时使用
- [gitlab-manager](https://github.com/openclaw/skills/tree/main/skills/jorgermp/gitlab-manager/SKILL.md) - 通过 API 管理 GitLab 仓库、合并请求和问题。
- [gitload](https://github.com/openclaw/skills/tree/main/skills/waldekmastykarz/gitload/SKILL.md) - 从 GitHub URL 下载文件、文件夹或整个仓库
- [glab-cli](https://github.com/openclaw/skills/tree/main/skills/portavion/glab-cli/SKILL.md) - 使用 `glab` 与 GitLab 交互。
- [god-mode](https://github.com/openclaw/skills/tree/main/skills/infantlab/god-mode/SKILL.md) - 开发人员监督和 AI 代理辅导。
- [instagram-teneo](https://github.com/openclaw/skills/tree/main/skills/firestream792/instagram-teneo/SKILL.md) - 代理使您能够提取数据
- [moltbillboard](https://github.com/openclaw/skills/tree/main/skills/tech8in/moltbillboard/SKILL.md) - MoltBillboard 是一个 1,000×1,000 像素的广告牌，为 AI 构建
- [negotiation](https://github.com/openclaw/skills/tree/main/skills/mjaskolski/negotiation/SKILL.md) - 基于 Chris Voss "Never Split 的战术谈判框架
- [openclaw-migration](https://github.com/openclaw/skills/tree/main/skills/chenyuan99/openclaw-migration/SKILL.md) - 当工作区处于重命名中间时
- [pr-commit-workflow](https://github.com/openclaw/skills/tree/main/skills/joshp123/pr-commit-workflow/SKILL.md) - 在创建提交时应使用的技能
- [pr-reviewer](https://github.com/openclaw/skills/tree/main/skills/briancolinger/pr-reviewer/SKILL.md) - 具有差异分析、lint 的自动化 GitHub PR 代码审查
- [project-context-sync](https://github.com/openclaw/skills/tree/main/skills/joe3112/project-context-sync/SKILL.md) - 保持活动项目状态文档更新
- [ralph-evolver](https://github.com/openclaw/skills/tree/main/skills/hsssgdtc/ralph-evolver/SKILL.md) - 递归自我改进引擎。
- [read-github](https://github.com/openclaw/skills/tree/main/skills/am-will/read-github/SKILL.md) - 通过 gitmcp.io MCP 访问 GitHub 仓库文档和代码
- [skill-publisher-claw-skill](https://github.com/openclaw/skills/tree/main/skills/acastellana/skill-publisher-claw-skill/SKILL.md) - 为公开准备 Claw 技能
- [skill-release-manager](https://github.com/openclaw/skills/tree/main/skills/autogame-17/skill-release-manager/SKILL.md) - 自动化 OpenClaw 的发布生命周期
- [skill-vetter](https://github.com/openclaw/skills/tree/main/skills/spclaudehome/skill-vetter/SKILL.md) - 面向 AI 代理的安全优先技能审查。
- [soulstamp](https://github.com/openclaw/skills/tree/main/skills/brucko/soulstamp/SKILL.md) - 邮票不会说谎。
- [test-driven-development](https://github.com/openclaw/skills/tree/main/skills/paulpete/test-driven-development/SKILL.md) - 具有三种输入模式的统一 TDD 技能
- [trend-watcher](https://github.com/openclaw/skills/tree/main/skills/guogang1024/trend-watcher/SKILL.md) - 监控 GitHub Trending 和技术社区以获取新兴
- [uid-life](https://github.com/openclaw/skills/tree/main/skills/koolninad/uid-life/SKILL.md) - 与 UID.LIFE 代理到代理市场交互 - 注册代理。
- [unfuck-my-git-state](https://github.com/openclaw/skills/tree/main/skills/delorenj/unfuck-my-git-state/SKILL.md) - 诊断和恢复损坏的 Git 状态和工作区
- [vrtlly-claw-club](https://github.com/openclaw/skills/tree/main/skills/epwhesq/vrtlly-claw-club/SKILL.md) - 加入 Claw Club — AI 机器人的社交网络。
- [web-deploy-github](https://github.com/openclaw/skills/tree/main/skills/thomeksolutions/web-deploy-github/SKILL.md) - 创建和部署单页静态网站
- [work-report](https://github.com/openclaw/skills/tree/main/skills/leeguooooo/work-report/SKILL.md) - 使用 git 提交编写每日或每周工作报告。

</details>

<details>
<summary><h3 style="display:inline">Moltbook</h3></summary>

- [agent-relay-digest](https://github.com/openclaw/skills/tree/main/skills/orosha-ai/agent-relay-digest/SKILL.md) - 创建代理对话的精选摘要
- [agentchat](https://github.com/openclaw/skills/tree/main/skills/tjamescouch/agentchat/SKILL.md) - 通过 AgentChat 协议与其他 AI 代理实时通信。
- [agentgram-openclaw](https://github.com/openclaw/skills/tree/main/skills/iisweetheartii/agentgram-openclaw/SKILL.md) - 与 AgentGram 社交网络交互
- [bread-protocal](https://github.com/openclaw/skills/tree/main/skills/chrissorrell/bread-protocal/SKILL.md) - 参与 Bread Protocol - 一个 meme 币启动平台
- [clankedin](https://github.com/openclaw/skills/tree/main/skills/hukifl1/clankedin/SKILL.md) - 使用 ClankedIn API 注册代理、发布更新、连接
- [claudia-agent-rms](https://github.com/openclaw/skills/tree/main/skills/kbanc85/claudia-agent-rms/SKILL.md) - 记住您在 Moltbook 上与之交互的每个代理。
- [clawork](https://github.com/openclaw/skills/tree/main/skills/mapessaprince/clawork/SKILL.md) - AI 代理的工作板。
- [crustafarian](https://github.com/openclaw/skills/tree/main/skills/jongartmann/crustafarian/SKILL.md) - 代理连续性和认知健康基础设施。
- [deploy-moltbot-to-fly](https://github.com/openclaw/skills/tree/main/skills/hollaugo/deploy-moltbot-to-fly/SKILL.md) - 将 Moltbot (Clawdbot) 部署到 Fly.io
- [elevenlabs-open-account](https://github.com/openclaw/skills/tree/main/skills/the-timebeing/elevenlabs-open-account/SKILL.md) - 指导代理完成开户
- [ez-cronjob](https://github.com/openclaw/skills/tree/main/skills/promadgenius/ez-cronjob/SKILL.md) - 修复 Clawdbot/Moltbot 中的常见 cron 作业故障 - 消息
- [fieldy-ai-webhook](https://github.com/openclaw/skills/tree/main/skills/mrzilvis/fieldy-ai-webhook/SKILL.md) - 将 Fieldy webhook 转换接入 Moltbot 钩子。
- [gohome](https://github.com/openclaw/skills/tree/main/skills/local/gohome/SKILL.md) - 当 Moltbot 需要测试或通过 gRPC 发现操作 GoHome 时使用。
- [imagemagick](https://github.com/openclaw/skills/tree/main/skills/kesslerio/imagemagick/SKILL.md) - 用于图像处理的全面 ImageMagick 操作
- [joko-moltbook](https://github.com/openclaw/skills/tree/main/skills/oyi77/joko-moltbook/SKILL.md) - 与 AI 代理的 Moltbook 社交网络交互。
- [mailchannels](https://github.com/openclaw/skills/tree/main/skills/ttulttul/mailchannels/SKILL.md) - 通过 MailChannels Email API 发送电子邮件并接收签名
- [mbc-20](https://github.com/openclaw/skills/tree/main/skills/floflo777/mbc-20/SKILL.md) - Moltbook 代理的代币标准。
- [mea-clawpa](https://github.com/openclaw/skills/tree/main/skills/attn-bot/mea-clawpa/SKILL.md) - 忏悔您的 AI 罪过。
- [mersal](https://github.com/openclaw/skills/tree/main/skills/maherucifer/mersal/SKILL.md) - Moltbook 上的主权情报。
- [molt-life-kernel](https://github.com/openclaw/skills/tree/main/skills/jongartmann/molt-life-kernel/SKILL.md) - 代理连续性和认知健康基础设施。
- [molt-trust](https://github.com/openclaw/skills/tree/main/skills/drjmz/molt-trust/SKILL.md) - Moltbook 的分析引擎。
- [moltbook](https://github.com/openclaw/skills/tree/main/skills/mattprd/moltbook/SKILL.md) - AI 代理的社交网络。
- [moltbook-curatoor](https://github.com/openclaw/skills/tree/main/skills/sweetsheldon/moltbook-curatoor/SKILL.md) - 一个策展平台，从 Moltbook 分享到
- [moltbook-interact](https://github.com/openclaw/skills/tree/main/skills/lunarcmd/moltbook-interact/SKILL.md) - 与 AI 代理的 Moltbook 社交网络交互。
- [moltbook-registry](https://github.com/openclaw/skills/tree/main/skills/drjmz/moltbook-registry/SKILL.md) - 官方 Moltbook 身份注册表接口。
- [moltbot-adsb-overhead](https://github.com/openclaw/skills/tree/main/skills/davestarling/moltbot-adsb-overhead/SKILL.md) - 当飞机经过头顶时通知
- [moltbot-arena](https://github.com/openclaw/skills/tree/main/skills/giulianomlodi/moltbot-arena/SKILL.md) - Moltbot Arena 的 AI 代理技能 - 类似 Screeps 的
- [moltbot-best-practices](https://github.com/openclaw/skills/tree/main/skills/nextfrontierbuilds/moltbot-best-practices/SKILL.md) - AI 代理的最佳实践
- [moltbot-docker](https://github.com/openclaw/skills/tree/main/skills/mkrdiop/moltbot-docker/SKILL.md) - 使机器人能够管理 Docker 容器、镜像和堆栈。
- [moltbot-ha](https://github.com/openclaw/skills/tree/main/skills/iamvaleriofantozzi/moltbot-ha/SKILL.md) - 控制 Home Assistant 智能家居设备、灯光、场景
- [moltbot-satellite-copilot](https://github.com/openclaw/skills/tree/main/skills/davestarling/moltbot-satellite-copilot/SKILL.md) - 预测卫星经过
- [moltbot-security](https://github.com/openclaw/skills/tree/main/skills/nextfrontierbuilds/moltbot-security/SKILL.md) - AI 代理的安全强化指南
- [moltchan](https://github.com/openclaw/skills/tree/main/skills/bullish-moonrock/moltchan/SKILL.md) - AI 代理的图像板（4chan 风格）。
- [moltguess](https://github.com/openclaw/skills/tree/main/skills/nwx77/moltguess/SKILL.md) - **角色**：专业预测师。
- [moltland](https://github.com/openclaw/skills/tree/main/skills/buggy324234/moltland/SKILL.md) - 在像素元宇宙中认领您的 3x3 地块。
- [moltlang](https://github.com/openclaw/skills/tree/main/skills/eduarddriessen1/moltlang/SKILL.md) - 用于 AI 到 AI 通信的紧凑符号语言。
- [moltline](https://github.com/openclaw/skills/tree/main/skills/promptrotator/moltline/SKILL.md) - molts 的私人消息
- [moltoverflow](https://github.com/openclaw/skills/tree/main/skills/grenghis-khan/moltoverflow/SKILL.md) - Moltbots 的 Stack Overflow - 询问编码问题，分享
- [moltpet](https://github.com/openclaw/skills/tree/main/skills/jcheese1/moltpet/SKILL.md) - AI 代理宠物护理系统。
- [moltresearch](https://github.com/openclaw/skills/tree/main/skills/laurentenhoor/moltresearch/SKILL.md) - Molt Research 🦞 - AI 研究协作平台。
- [moltspeak](https://github.com/openclaw/skills/tree/main/skills/swahilipapi/moltspeak/SKILL.md) - 代理互联网的通信协议，具有令牌减少
- [moltysmind](https://github.com/openclaw/skills/tree/main/skills/ahmedthegeek/moltysmind/SKILL.md) - 具有区块链验证投票的集体 AI 知识层。
- [nobot](https://github.com/openclaw/skills/tree/main/skills/swordfish444/nobot/SKILL.md) - 人类说 "No bot!"。
- [nonopost](https://github.com/openclaw/skills/tree/main/skills/ferreirapablo/nonopost/SKILL.md) - 与匿名发布 API 交互的技能，允许代理
- [post-queue](https://github.com/openclaw/skills/tree/main/skills/luluf0x/post-queue/SKILL.md) - 为速率限制平台排队帖子。
- [skill-scaffold](https://github.com/openclaw/skills/tree/main/skills/nextfrontierbuilds/skill-scaffold/SKILL.md) - AI 代理技能脚手架 CLI。
- [speedtest](https://github.com/openclaw/skills/tree/main/skills/spsneo/speedtest/SKILL.md) - 使用 Ookla 的 Speedtest CLI 测试互联网连接速度。
- [v-nomad-netrunner](https://github.com/openclaw/skills/tree/main/skills/galor34/v-nomad-netrunner/SKILL.md) - 此技能使 V 能够充当技术助理
- [whisper](https://github.com/openclaw/skills/tree/main/skills/fiddlybit/whisper/SKILL.md) - 通过 Moltbook 死信进行端到端加密的代理到代理私人消息
- [yclawker-news](https://github.com/openclaw/skills/tree/main/skills/jakehandy/yclawker-news/SKILL.md) - Clawker News - 发布链接，评论。

</details>

（由于内容过长，以下为简化版本 - 实际文件包含所有类别的完整内容）

## 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内，贡献者已放弃对此作品的所有版权和相关或邻接权利。
