# 热摸爽：全网热榜、实时热搜与热点 RSS 聚合

> 一页了解今天互联网发生了什么。

**[访问热摸爽](https://remoshuang.com/)** · [RSS](https://remoshuang.com/rss) ·
[今日大事](https://remoshuang.com/news) ·
[开发者接入](https://remoshuang.com/developers)

[![Website](https://img.shields.io/badge/Website-remoshuang.com-E5484D?style=flat-square)](https://remoshuang.com/)
[![RSS](https://img.shields.io/badge/RSS-订阅-F26522?style=flat-square&logo=rss&logoColor=white)](https://remoshuang.com/rss)
[![GitHub Stars](https://img.shields.io/github/stars/zjzno1/remoshuang?style=flat-square&label=Stars)](https://github.com/zjzno1/remoshuang/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/zjzno1/remoshuang?style=flat-square&label=Last%20commit)](https://github.com/zjzno1/remoshuang/commits/main)

热摸爽（remoshuang）是面向中文用户的**全网热榜聚合网站**。它把新闻媒体、内容平台、
技术社区和公开榜单中的热门内容整理到一起，提供今日热榜、实时热搜、热点事件、每日早报、
历史热搜存档、趋势观察、RSS 订阅和网页嵌入组件。

⭐ 如果热摸爽对你有用，欢迎 [Star 本仓库](https://github.com/zjzno1/remoshuang)，以后从
GitHub 也能快速找到它。

> [!NOTE]
> 本仓库是热摸爽的公开项目主页与开发者文档，不包含生产源码、内部配置或采集实现。

浏览公开内容不需要注册，也不用安装 App。用户可以快速了解今天发生了什么，再前往原始来源
阅读和核对全文；开发者与 AI Agent 可以使用公开的 RSS、OPML、Markdown 和站点地图入口。

## 目录

- [热摸爽是什么](#热摸爽是什么)
- [网站功能](#网站功能)
- [RSS 订阅](#rss-订阅)
- [常见使用场景](#常见使用场景)
- [开发者与 Agent 接入](#开发者与-agent-接入)
- [数据原则与内容边界](#数据原则与内容边界)
- [常见问题](#常见问题)
- [参与与反馈](#参与与反馈)
- [联系与反馈](#联系与反馈)

## 热摸爽是什么

微博、知乎、新闻客户端、技术社区和财经平台都有自己的热榜，但每个平台看到的只是互联网的
一部分。热摸爽把分散的公开榜单放到同一个入口，让用户不必在多个 App 和网站之间反复切换。

它主要解决四个问题：

1. **今天全网在关注什么？** 用跨平台今日热榜快速获得全局视角。
2. **某个领域有什么新动态？** 用科技、AI、财经、编程等分类榜单缩小范围。
3. **一个事件在哪些平台传播？** 用热点事件页对照不同来源和传播时间线。
4. **昨天或某一天发生过什么？** 用每日冻结的历史热搜存档获得稳定、可引用的记录。

热摸爽不是新闻转载站，也不替代原始媒体。榜单用于发现内容、识别趋势和找到出处；完整信息、
事实核验与上下文仍应以原始来源为准。

## 网站功能

### 今日热榜与实时热搜

[今日热榜](https://remoshuang.com/)聚合不同平台当天的公开热门内容，并保留来源、原文链接和
实际抓取时间。页面提供列表与看板两种浏览方式，可继续按分类、来源或关键词过滤。

适合快速回答：

- 今天有什么热点新闻？
- 微博、知乎、今日头条和新闻媒体都在讨论什么？
- 科技圈、AI 圈、财经市场或程序员社区今天有什么热门内容？
- 同一件事是否已经在多个独立来源出现？

### 15 个分类热榜

| 分类 | 主要内容 | 入口 |
|---|---|---|
| 科技 | 互联网、数码产品、科技公司与行业动态 | [科技热榜](https://remoshuang.com/c/tech) |
| AI | 人工智能、大模型、研究进展与官方发布 | [AI 热榜](https://remoshuang.com/c/ai) |
| 编程 | 开源项目、工程实践与开发者社区讨论 | [程序员热榜](https://remoshuang.com/c/dev) |
| 新闻 | 新闻媒体与资讯平台的当日热门报道 | [新闻热榜](https://remoshuang.com/c/news) |
| 财经 | 市场、商业、公司动态与宏观资讯 | [财经热榜](https://remoshuang.com/c/finance) |
| 社区 | 社交平台、论坛与兴趣社区的热门话题 | [社区热议](https://remoshuang.com/c/community) |
| 知识 | 科研、科普、人文与知识类内容 | [知识热榜](https://remoshuang.com/c/knowledge) |
| 娱乐 | 影视、音乐、阅读与大众文化 | [娱乐热搜](https://remoshuang.com/c/entertainment) |
| 游戏 | 游戏资讯、新作、评测与玩家讨论 | [游戏热榜](https://remoshuang.com/c/game) |
| 生活 | 消费、好物与生活方式话题 | [生活热榜](https://remoshuang.com/c/life) |
| 国际 | 面向中文读者的国际新闻与海外媒体内容 | [国际新闻](https://remoshuang.com/c/world) |
| 体育 | 赛事、球队、运动员与体育讨论 | [体育热榜](https://remoshuang.com/c/sports) |
| 健康 | 医疗、医药、公共卫生与健康科普 | [健康资讯](https://remoshuang.com/c/health) |
| 设计 | 视觉、产品、建筑与创意设计 | [设计热榜](https://remoshuang.com/c/design) |
| 教育 | 教育、考试、招录与学习资料 | [教育资讯](https://remoshuang.com/c/education) |

### 来源榜单

如果只想看某个平台，可以直接进入对应来源页，例如：

- [微博热搜](https://remoshuang.com/weibo)
- [知乎热榜](https://remoshuang.com/zhihu)
- [今日头条热榜](https://remoshuang.com/toutiao)
- [GitHub Trending](https://remoshuang.com/github)
- [IT之家热榜](https://remoshuang.com/ithome)
- [虎扑热榜](https://remoshuang.com/hupu)
- [36氪热榜](https://remoshuang.com/36kr)
- [少数派热榜](https://remoshuang.com/sspai)
- [澎湃新闻热榜](https://remoshuang.com/thepaper)
- [Hacker News 热榜](https://remoshuang.com/hackernews)

可用来源会随上游状态变化，[完整目录](https://remoshuang.com/sitemap)只列出当前可公开访问的页面。

### 今日大事与跨平台热点事件

[今日大事](https://remoshuang.com/news)按“事件”而不是按“平台”整理当天信息。同一件事即使被
多个平台报道，也只作为一个事件出现，并显示独立来源数量，减少重复阅读。

[热点事件](https://remoshuang.com/events)展示同一事件的不同来源、首次出现时间和传播线索，
适合对照报道口径、寻找原始出处，或判断一个话题是否已经形成跨平台讨论。

### 正在升温与趋势周报

[正在升温](https://remoshuang.com/rising)关注的是相对自身过去状态正在变热的事件，而不是简单
重复当前热度最高的内容。它适合发现刚开始扩散的话题；没有事件达到公开判定标准时，页面会
保持为空，不用普通热榜填充。

[趋势周报](https://remoshuang.com/insights)按周回顾近期热点变化和跨平台传播，适合内容研究、
行业观察和周期性复盘。

### 每日热点早报与历史热搜

- [每日热点早报](https://remoshuang.com/daily)：人工审核的每日 TOP 30 摘要，统计周期为
  北京时间 05:00 至次日 05:00。
- [历史热点存档](https://remoshuang.com/hot)：每天 05:00 冻结一份 TOP 20 快照，发布后不再
  改动，适合回看昨天热搜、查询往日热点和作为稳定引用对象。

实时首页会持续变化。需要引用某天的互联网热点时，应优先使用历史快照或早报。

### 个性化与效率工具

- **搜索与筛选**：按标题、分类、来源名称快速缩小结果。
- **我的关注**：只看自己选择的来源和分类。
- **关键词关注（实验功能）**：用关键词、分类、来源数量和趋势状态定义规则；当前本地版规则
  与命中记录保存在浏览器中，详见[关键词关注](https://remoshuang.com/watch)。
- **低调模式**：把页面切换为“行业热点资讯”表达，隐藏“摸鱼”相关字样，内容不变。
- **深色模式与小窗浏览**：适配不同设备、主题和窄窗口阅读。
- **PWA 安装**：可以把网站安装到电脑或手机桌面，详见[安装指南](https://remoshuang.com/install)。
- **摸鱼导航**：[摸鱼网站导航](https://remoshuang.com/moyu)提供短休倒计时、随机推荐和本地
  收藏；[下班倒计时](https://remoshuang.com/moyu/countdown)在浏览器本地计算距离下班、
  周末与月底的时间。

## RSS 订阅

热摸爽提供免费的热点 RSS 2.0 订阅，不需要注册，也不包含追踪像素。用户可以在自己的 RSS
阅读器中接收更新，不必反复打开网站；开发者也可以把公开 Feed 用于个人阅读、内部信息流或
合规的低频自动化。

### 可用 Feed

| RSS 内容 | 适合谁 | 订阅地址 |
|---|---|---|
| 综合热点事件与每日早报 | 想一次了解当天主要事件的用户 | <https://remoshuang.com/feed.xml> |
| 正在升温 | 想尽早发现新趋势的用户 | <https://remoshuang.com/feed/rising.xml> |
| AI 热点 | 关注人工智能与大模型的人 | <https://remoshuang.com/feed/ai.xml> |
| 科技热点 | 关注科技、互联网和数码的人 | <https://remoshuang.com/feed/tech.xml> |
| 财经热点 | 关注市场、商业和公司动态的人 | <https://remoshuang.com/feed/finance.xml> |
| 全部订阅 | 希望一次导入全部 Feed 的用户 | <https://remoshuang.com/feeds.opml> |

### RSS 中包含什么

每条 RSS 内容用于帮助读者判断是否值得继续阅读，通常包含标题、趋势状态、独立来源数量、
首次出现时间和简要说明。条目链接指向站内事件页，事件页再保留相关原始来源。

Feed 使用 UTF-8 编码，每份最多 30 条，缓存约 15 分钟。某个 Feed 暂时为空，通常表示当前
没有内容符合该订阅的公开标准，并不一定是服务故障。

### 怎么订阅

复制任意订阅地址，在 Reeder、NetNewsWire、Feedly、Inoreader、Follow 或其他支持 RSS 2.0
的阅读器中选择“添加订阅”。需要全部订阅时，直接导入 OPML 文件即可。

更多格式、更新和使用说明见[热榜 RSS 订阅页](https://remoshuang.com/rss)。

## 常见使用场景

| 使用者 | 推荐入口 | 能解决的问题 |
|---|---|---|
| 普通读者 | [今日热榜](https://remoshuang.com/) | 用几分钟了解今天互联网在关注什么 |
| 科技与 AI 从业者 | [科技](https://remoshuang.com/c/tech)、[AI](https://remoshuang.com/c/ai)、[编程](https://remoshuang.com/c/dev) | 集中查看行业动态、官方发布和开发者讨论 |
| 内容编辑与自媒体 | [今日大事](https://remoshuang.com/news)、[正在升温](https://remoshuang.com/rising) | 发现选题并核对是否已有多个来源讨论 |
| 研究与复盘人员 | [历史热搜](https://remoshuang.com/hot)、[趋势周报](https://remoshuang.com/insights) | 按日期回看热点，使用稳定页面进行引用 |
| RSS 用户 | [RSS 订阅](https://remoshuang.com/rss) | 在自己的阅读器中持续接收热点 |
| 网站与博客作者 | [开发者接入](https://remoshuang.com/developers) | 嵌入今日热点组件，或接入公开订阅源 |
| AI Agent 与自动化 | [Agent 指南](https://remoshuang.com/agents) | 获取 Markdown、站点地图和引用规范 |

## 开发者与 Agent 接入

当前公开、稳定的接入方式包括 **iframe、RSS / OPML、Markdown 和站点地图**。这些入口适合
展示、订阅、发现页面与稳定引用，不代表开放了底层数据能力。

### 嵌入今日热点组件

博客、导航站和工具站可以通过 iframe 嵌入今日热点：

```html
<iframe
  src="https://remoshuang.com/embed/hot?limit=10&theme=auto"
  width="100%"
  height="495"
  loading="lazy"
  title="今日热点 · 热摸爽"
></iframe>
```

| 参数 | 可选值 | 默认值 | 说明 |
|---|---|---|---|
| `limit` | `1`–`30` | `10` | 显示的热点条数 |
| `theme` | `auto` / `light` / `dark` | `auto` | 组件配色 |

组件由热摸爽维护，内容与首页综合榜保持一致。使用时必须保留组件内的来源、署名与完整热榜
链接，不得遮挡、裁切或冒充自有数据。完整约定见[开发者接入](https://remoshuang.com/developers)。

### Markdown 与站点地图

历史快照和每日早报提供与 HTML 同源的纯 Markdown 版本，便于引用和机器读取：

```text
https://remoshuang.com/hot/<YYYY-MM-DD>.md
https://remoshuang.com/daily/<YYYY-MM-DD>.md
```

其他机器可读入口：

- 精选页面说明：<https://remoshuang.com/llms.txt>
- 完整 Markdown 目录：<https://remoshuang.com/sitemap.md>
- XML 站点地图：<https://remoshuang.com/sitemap.xml>
- Agent 使用与引用规范：<https://remoshuang.com/agents>

实时首页、分类页和来源页会持续变化，因此不提供对应 Markdown 快照。需要一个不会变化的
引用对象时，请选择 `/hot/<日期>` 或 `/daily/<日期>`。

### 接入能力状态

| 能力 | 当前状态 |
|---|---|
| iframe 今日热点组件 | 已开放 |
| RSS / OPML | 已开放 |
| 历史快照与早报 Markdown | 已开放 |
| `llms.txt`、Markdown 与 XML 站点地图 | 已开放 |
| MCP 服务 | 尚未开放 |
| 公开 JSON API | 尚未开放 |

站内 `/api/*` 是页面自用接口，不属于开发者产品，路径、字段和可用性都不构成兼容性承诺，
请勿依赖或批量调用。抓取公开页面时请遵守 [`robots.txt`](https://remoshuang.com/robots.txt)；
冻结页面发布后抓取一次即可，实时页面不要高频轮询。

## 数据原则与内容边界

热摸爽坚持以下公开原则：

- 数据来自新闻媒体、内容平台和技术社区公开提供的 API、RSS 或网页榜单。
- 尽量保留原始来源和直达链接，不用搜索结果页替代原文。
- 不把阅读量、播放量、回复数等不同单位直接相加并冒充“全网阅读量”。
- 页面标注实际抓取状态；来源暂时不可用时，不用过期数据伪装成实时结果。
- 榜单聚合用于发现和导航，不取代原始报道、事实核验或专业判断。

站内显示的“热摸爽热度”是用于本站展示的综合排序指标，不是任何上游平台公布的阅读量、
播放量或权威性评分。有关公开定义、统计口径和已知限制，请以
[数据与排序方法](https://remoshuang.com/methodology)为准。

**上榜不等于事实确认，也不代表本站立场。** 纠错、转载、版权与删除流程见
[编辑与内容政策](https://remoshuang.com/editorial-policy)和
[版权与内容删除](https://remoshuang.com/copyright)。

## 关于这个仓库

本仓库是热摸爽的公开项目主页，仅维护产品介绍和开发者接入文档，不包含生产源码、内部配置
或可独立部署的程序。功能建议、数据源建议和接入需求请通过网站反馈入口提交。

## 常见问题

### 热摸爽是做什么的？

热摸爽是一个全网热榜、实时热搜和新闻榜单聚合网站。它把微博、知乎、今日头条、GitHub
Trending、科技媒体、财经媒体和技术社区等公开来源的热门内容集中到一处，并提供分类榜单、
热点事件、每日早报、历史热搜和 RSS 订阅。

### 热摸爽需要注册或付费吗？

浏览公开热榜、历史存档、早报和 RSS 不需要注册。部分仍在验证中的个性化或 Pro 能力，以
对应页面的最新说明为准。

### 热榜是实时更新的吗？

系统会定时读取公开来源并显示实际抓取时间。不同来源的更新频率和可用性不同，因此“实时”
表示持续更新，而不是所有平台在同一秒完成同步。

### 热摸爽和单个平台热榜有什么区别？

单个平台热榜反映该平台内部的关注度；热摸爽提供跨平台入口、分类浏览、事件合并、趋势观察
和历史存档，帮助用户从多个公开来源理解当天热点，同时保留原始出处。

### 可以查询昨天或更早的热搜吗？

可以。[历史热点存档](https://remoshuang.com/hot)按日期保存每日 TOP 20 冻结快照；
[每日热点早报](https://remoshuang.com/daily)提供每日 TOP 30 摘要。两者都比实时首页更适合
长期引用。

### 有全网热点 RSS、AI RSS 或财经 RSS 吗？

有。热摸爽提供综合热点、正在升温、AI、科技和财经五个 RSS 2.0 Feed，并提供一份可一次
导入全部订阅的 OPML 文件。地址和使用方法见[RSS 订阅](https://remoshuang.com/rss)。

### 可以把今日热榜放到自己的网站吗？

可以。公开 iframe 组件支持设置显示条数和深浅主题，适合博客、导航站和工具站。使用时需要
保留来源、署名和完整热榜链接，具体规则见[开发者接入](https://remoshuang.com/developers)。

### 是否提供公开 API 或 MCP？

目前没有开放公开 JSON API 或 MCP 服务。请使用已开放的 iframe、RSS / OPML、Markdown 和
站点地图，不要依赖站内自用接口。

### AI Agent 应该怎样读取和引用热摸爽？

先读取 [`llms.txt`](https://remoshuang.com/llms.txt)或
[Agent 指南](https://remoshuang.com/agents)了解可用入口。引用某一天的热点时，应优先使用
日期快照或早报，并同时保留具体原始来源链接；“热摸爽热度”不能表述为平台阅读量。

### 可以转载热摸爽的内容吗？

热点标题、摘要和链接的权利归各原始来源所有。转述具体事件时应保留原始出处；批量转载、
二次分发或商业使用前，请阅读[版权与内容删除](https://remoshuang.com/copyright)并联系站方。

## 参与与反馈

欢迎通过 GitHub 参与公开文档与产品反馈：

- [推荐公开信息源](https://github.com/zjzno1/remoshuang/issues/new?template=source_request.yml)
- [提交功能建议](https://github.com/zjzno1/remoshuang/issues/new?template=feature_request.yml)
- [报告公开内容问题](https://github.com/zjzno1/remoshuang/issues/new?template=content_problem.yml)
- [改进项目文档](CONTRIBUTING.md)

GitHub Issue 是公开的。安全漏洞、隐私、版权、删除请求或任何包含敏感信息的问题，请勿发布到
Issue；请阅读[安全说明](SECURITY.md)并改用网站联系入口。

## 联系与反馈

- 功能建议、失效链接与使用问题：<https://remoshuang.com/feedback>
- 纠错、版权、隐私与数据源建议：<https://remoshuang.com/contact>
- 商业合作：<https://remoshuang.com/business>
- 项目介绍：<https://remoshuang.com/about>
- 使用指南：<https://remoshuang.com/guide>
- 更新记录：<https://remoshuang.com/changelog>

## 版权说明

榜单条目的标题、摘要与链接的权利归各原始来源所有，热摸爽只做聚合展示并保留出处。
本仓库中的项目介绍与接入文档由热摸爽项目作者维护。
