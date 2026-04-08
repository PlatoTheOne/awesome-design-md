<a href="https://github.com/VoltAgent/voltagent">
     <img width="1500" height="801" alt="claude-skills" src="https://github.com/user-attachments/assets/d012a0d2-cec3-4630-ba5e-acc339dbe6cf" />
</a>


<br/>
<br/>

<div align="center">
    <strong>灵感来自开发者导向网站的精选 DESIGN.md 文件合集。</strong>
    <br />
    <br />

</div>

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![DESIGN.md Count](https://img.shields.io/badge/DESIGN.md%20count-59-10b981?style=classic)
[![Last Update](https://img.shields.io/github/last-commit/VoltAgent/awesome-design-md?label=Last%20update&style=classic)](https://github.com/VoltAgent/awesome-design-md)
[![Discord](https://img.shields.io/discord/1361559153780195478.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://s.voltagent.dev/discord)

</div>
</div>

# Awesome DESIGN.md

把一个 `DESIGN.md` 放进你的项目根目录，再告诉你的 AI agent “照这个风格帮我做一个页面”，就能生成真正贴近目标风格、细节也更准确的界面。


## 什么是 DESIGN.md？

[DESIGN.md](https://stitch.withgoogle.com/docs/design-md/overview/) 是 Google Stitch 提出的一个新概念。它是一份纯文本的设计系统文档，供 AI agents 读取，用来生成风格一致的 UI。

它本质上就是一个 markdown 文件。不需要导出 Figma，不需要 JSON schema，也不需要额外工具。只要把它放到项目根目录，无论是 AI coding agent 还是 Google Stitch，都能立即理解你的界面应该呈现什么样子。Markdown 也是 LLM 最擅长读取的格式，因此无需额外解析或配置。

| 文件 | 读取者 | 定义内容 |
|------|-------------|-----------------|
| `AGENTS.md` | Coding agents | 项目应如何构建 |
| `DESIGN.md` | Design agents | 产品应呈现什么样的视觉与体验 |

**这个仓库提供的是可直接使用的 DESIGN.md 文件**，内容提取自真实网站。



## 每个 DESIGN.md 里有什么

每个文件都遵循 [Stitch DESIGN.md format](https://stitch.withgoogle.com/docs/design-md/format/)，并扩展了更多章节：

| # | 章节 | 覆盖内容 |
|---|---------|-----------------|
| 1 | Visual Theme & Atmosphere | 整体气质、密度与设计哲学 |
| 2 | Color Palette & Roles | 语义化颜色命名、十六进制值与使用角色 |
| 3 | Typography Rules | 字体家族与完整的层级规范 |
| 4 | Component Stylings | 按钮、卡片、输入框、导航及其状态样式 |
| 5 | Layout Principles | 间距尺度、网格与留白原则 |
| 6 | Depth & Elevation | 阴影系统与层级关系 |
| 7 | Do's and Don'ts | 设计守则与常见反模式 |
| 8 | Responsive Behavior | 断点、触控尺寸与折叠策略 |
| 9 | Agent Prompt Guide | 颜色速查与可直接使用的提示词 |

每个站点都包含：

| 文件 | 用途 |
|------|---------|
| `DESIGN.md` | 设计系统本体，供 agents 读取 |
| `preview.html` | 可视化样例页，展示色板、字阶、按钮、卡片等 |
| `preview-dark.html` | 同样的样例页，但以深色界面呈现 |

### 如何使用


1. 将某个站点的 `DESIGN.md` 复制到你的项目根目录
2. 告诉你的 AI agent 使用它


## 申请新增 DESIGN.md

[使用这个模板创建 GitHub issue](https://github.com/VoltAgent/awesome-design-md/issues/new?template=design-md-request.yml)，申请为某个网站生成对应的 `DESIGN.md`。


## 收录目录

### AI 与机器学习

- [**Claude**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/claude/) - Anthropic 的 AI assistant。暖陶土色强调，干净的编辑式排版
- [**Cohere**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/cohere/) - 企业级 AI 平台。鲜明渐层，带有数据密度的仪表盘气质
- [**ElevenLabs**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/elevenlabs/) - AI 语音平台。电影感深色界面，带有音频波形视觉语言
- [**Minimax**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/minimax/) - 模型提供方。大胆的深色界面与霓虹强调
- [**Mistral AI**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/mistral.ai/) - 开放权重 LLM 提供方。法式工程感极简风，偏紫色调
- [**Ollama**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/ollama/) - 在本地运行 LLM。终端优先、黑白分明的极简风格
- [**OpenCode AI**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/opencode.ai/) - AI coding 平台。面向开发者的深色主题
- [**Replicate**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/replicate/) - 通过 API 运行 ML 模型。白底清爽、偏代码导向
- [**RunwayML**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/runwayml/) - AI 视频生成平台。电影感深色界面，媒体展示丰富
- [**Together AI**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/together.ai/) - 开源 AI 基础设施。技术感强，带有蓝图式设计语言
- [**VoltAgent**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/voltagent/) - AI agent 框架。纯黑背景、祖母绿强调、终端原生气质
- [**xAI**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/x.ai/) - Elon Musk 的 AI 实验室。黑白强对比、未来感极简风

### 开发工具与平台

- [**Cursor**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/cursor/) - AI-first code editor。流畅的深色界面与渐层强调
- [**Expo**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/expo/) - React Native 平台。深色主题、紧凑字距、明显偏代码场景
- [**Linear**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/linear.app/) - 面向工程团队的项目管理工具。极简、精确、紫色点缀
- [**Lovable**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/lovable/) - AI 全栈构建工具。活泼渐层，亲和的开发者气质
- [**Mintlify**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/mintlify/) - 文档平台。干净、绿色点缀、强调阅读体验
- [**PostHog**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/posthog/) - 产品分析平台。带有刺猬品牌感的活泼深色界面，对开发者友好
- [**Raycast**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/raycast/) - 效率启动器。利落的深色外观与鲜艳渐层强调
- [**Resend**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/resend/) - 面向开发者的 Email API。极简深色主题，带有 monospace 点缀
- [**Sentry**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/sentry/) - 错误监控平台。深色仪表盘、高信息密度、粉紫色强调
- [**Supabase**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/supabase/) - 开源 Firebase 替代方案。深色祖母绿主题，代码气质鲜明
- [**Superhuman**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/superhuman/) - 高速 Email 客户端。高级感深色界面，键盘优先，带紫色光晕
- [**Vercel**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/vercel/) - 前端部署平台。黑白极致克制，Geist 字体风格鲜明
- [**Warp**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/warp/) - 现代终端。深色 IDE 风格界面，命令块式布局
- [**Zapier**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/zapier/) - 自动化平台。暖橙色调，插画驱动，亲和友好

### 基础设施与云

- [**ClickHouse**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/clickhouse/) - 高性能分析数据库。黄色强调，技术文档气质浓厚
- [**Composio**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/composio/) - 工具集成平台。现代深色风格，搭配多彩集成图标
- [**HashiCorp**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/hashicorp/) - 基础设施自动化平台。企业级洁净感，黑白克制
- [**MongoDB**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/mongodb/) - 文档数据库。绿色叶片品牌识别，强调开发者文档场景
- [**Sanity**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/sanity/) - Headless CMS。红色强调，内容优先的编辑式布局
- [**Stripe**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/stripe/) - 支付基础设施平台。标志性的紫色渐层与轻盈优雅的字重

### 设计与效率工具

- [**Airtable**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/airtable/) - 表格与数据库混合工具。色彩丰富、友好、强调结构化信息
- [**Cal.com**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/cal/) - 开源日程安排工具。中性清爽，对开发者友好
- [**Clay**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/clay/) - 创意机构。有机形态、柔和渐层、带有艺术指导感的布局
- [**Figma**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/figma/) - 协作设计工具。多彩鲜明，活泼但仍然专业
- [**Framer**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/framer/) - 网站构建工具。大胆的黑蓝配色，强调动效与设计感
- [**Intercom**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/intercom/) - 客户沟通平台。友好的蓝色体系，偏对话式 UI 模式
- [**Miro**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/miro/) - 可视化协作平台。亮黄色强调，无限画布气质鲜明
- [**Notion**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/notion/) - 一体化工作平台。温和极简、衬线标题、柔和表面层次
- [**Pinterest**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/pinterest/) - 视觉发现平台。红色强调，瀑布流布局，图片优先
- [**Webflow**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/webflow/) - 可视化建站工具。蓝色强调，成熟精致的营销站风格

### 金融科技与加密

- [**Cash App**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/cash.app/) - 消费金融平台。高对比金融科技界面，Cash Green 强调，带温度的 neo-grotesque 字体气质
- [**Coinbase**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/coinbase/) - 加密货币交易平台。干净的蓝色识别，强调信任感与机构气质
- [**Kraken**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/kraken/) - 加密交易平台。紫色强调的深色界面，高信息密度仪表盘
- [**Revolut**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/revolut/) - 数字银行。流畅的深色界面、渐层卡片、金融科技式精密感
- [**Wise**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/wise/) - 国际汇款平台。明亮绿色强调，清晰、友好、直接

### 企业与消费品牌

- [**Airbnb**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/airbnb/) - 旅行平台。暖珊瑚色强调，摄影驱动，圆角友好
- [**Apple**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/apple/) - 消费电子品牌。高级留白、SF Pro、电影式画面语言
- [**IBM**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/ibm/) - 企业科技品牌。Carbon design system，结构化蓝色体系
- [**NVIDIA**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/nvidia/) - GPU 计算品牌。绿黑高能量，技术力量感强
- [**SpaceX**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/spacex/) - 航天科技品牌。黑白分明、全幅画面、未来主义气质
- [**Spotify**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/spotify/) - 音乐流媒体平台。深色背景上的亮绿色，高冲击字体与专辑视觉驱动
- [**Uber**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/uber/) - 出行平台。大胆的黑白对比、紧致字距、城市感强

### 汽车品牌

- [**BMW**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/bmw/) - 豪华汽车品牌。深色高级表面，精确克制的德式工程气质
- [**Ferrari**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/ferrari/) - 豪华汽车品牌。黑白明暗对照式编辑风，Ferrari Red 极度克制地使用
- [**Lamborghini**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/lamborghini/) - 豪华汽车品牌。纯黑如大教堂般的空间感，金色强调，LamboType 定制 Neo-Grotesk
- [**Renault**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/renault/) - 法国汽车品牌。鲜明极光渐层，NouvelR 专有字体，零圆角按钮
- [**Tesla**](https://github.com/VoltAgent/awesome-design-md/tree/main/design-md/tesla/) - 电动车品牌。极致删繁就简，全屏电影式摄影，Universal Sans



## 贡献方式

请参阅 [CONTRIBUTING.md](CONTRIBUTING.md) 了解具体规范。

- **改进现有文件**：修正错误颜色、补足缺失 token、加强较弱的描述
- **报告问题**：如果发现哪里不对，请告诉我们

在提交 PR 之前，请先[创建一个 issue](https://github.com/VoltAgent/awesome-design-md/issues)，与维护者讨论你的想法并获取反馈。


## 许可

MIT License，详见 [LICENSE](LICENSE)

这个仓库是一个从公开网站提取而来的设计系统文档精选集。所有 `DESIGN.md` 文件均按 “as is” 形式提供，不附带任何保证。文中提取的 design tokens 来自公开可见的 CSS 值。我们不主张对任何网站的视觉识别拥有所有权。这些文档存在的目的，是帮助 AI agents 生成更一致的 UI。
