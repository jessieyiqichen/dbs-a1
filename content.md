# content.md · 内容冻结（所有版本只许用这里的事实）

来源：现有个人站 index.html（2026-09-21 版）。数字口径以此为准，读数日期已标。

## 身份
- 姓名：陈亦奇 Jessie Chen
- 一句话：AI 产品 · Chicago / Shanghai · Open to Opportunities
- 现在：芝加哥大学 计算社会科学硕士在读（经济学方向），GPA 4.0，2027 届
- 此前：香港中文大学 经济学学士
- 求职方向：AI 产品经理（AI 产品优先）
- 能力栈：产品定义 · AI 工程 · 数据分析 · 全栈开发
- 总述：过去一年独立完成五个 AI 产品从需求定义、开发到上线的全过程，其中三个至今每天在生产环境自动运行。
- 主张（现站 H1）：产品判断值不值钱，要用上线的产品来验证。
- 工作方式一句话：做产品偏数据和证据，北极星先定口径，成本逐笔记账，网站上每个数字都能给出后台、指标和读数日期。
- 在线版本：五个产品均有可试用的线上版本。

## 联系
- Email：jessiechenyiqi@outlook.com
- GitHub：https://github.com/jessieyiqichen
- 页脚：© 2026 陈亦奇 Jessie Chen · 手写 HTML/CSS，无框架，无跟踪

## 五个项目

### 01 Lecture Companion
- 角色：实时听课 AI 助手 · 独立开发 · 证明：交互设计 + 指标体系 + 成本工程
- 一段话：课堂提问的瓶颈在输入摩擦，不在模型能力。我把提问压缩成对转写句的一次点击，用多模态补齐板书与公式；北极星定在课后复习行为，成本按用量账本逐项管理。
- 数字：63 次标记，59 次零输入 ｜ 3 期灰度上线，零回滚 ｜ ASR 成本降至四分之一
- 链接：案例拆解 https://jessieyiqichen.github.io/projects/lecture-companion.html ｜ 在线演示 https://jessieyiqichen.github.io/lc-demo/ ｜ 引导式走读 https://jessieyiqichen.github.io/lecture-companion-walkthrough/
- 图：assets/img/lecture-companion.png

### 02 xhs-threads
- 角色：小红书收藏的思考轨迹还原 · 独立开发 · 证明：差异化定位 + AI 评测体系
- 一段话：收藏是高频动作，整理几乎不发生。我把整理做成零标注的主动归档：用户只管存，AI 自动归线、写笔记并质检。差异化经四类竞品调研确立，产出质量由独立审核模型把关。
- 数字：11 条思考轨迹，63 个节点（截至 2026-09）｜ 90% 调用走轻量档 ｜ 单条成本 ¥0.05–0.10
- 链接：案例拆解 https://jessieyiqichen.github.io/projects/xhs-threads.html ｜ 引导式演示 https://47.94.34.146:8443/demo ｜ 试玩实例 https://47.94.34.146:8443/try
- 图：assets/img/xhs-threads.png

### 03 Nous
- 角色：认知分身消息代理 · 三端产品 · 证明：研究到产品的全链路
- 一段话：别人的 bot 学你怎么说话，它学你怎么做决定。九维认知模型驱动的消息代理：替你判断回不回、按你的方式起草、在你「嘴上要答应但做不到」时发质检警告。飞书 bot + Mac 悬浮助手 + Web，三端生产自用中。
- 数字：行为预测 49→71% ｜ 3 端真实在线 ｜ 修正飞轮已闭环
- 链接：案例拆解 https://jessieyiqichen.github.io/projects/nous.html ｜ 引导式演示 https://jessieyiqichen.github.io/demos/nous.html ｜ 愿景沙盒 https://web-ten-omega-72.vercel.app/agent
- 图：assets/img/nous.png

### 04 JobPilot
- 角色：AI 求职军师 · 独立开发 · 开源 · 证明：产品洞察 + 功能取舍 + 工程质量
- 一段话：求职的卡点不在信息，在人。市面工具停在行为层，JobPilot 接入认知模型与语言样本，给出针对个人的诊断和像本人写的话术。六条产品取舍全部想清楚了为什么。
- 数字：349 岗采集，37 高分岗 ｜ 31 个 CLI 命令，544 测试（截至 2026-09）｜ CI + 线上只读 demo
- 链接：案例拆解 https://jessieyiqichen.github.io/projects/job-pilot.html ｜ 线上 demo https://jobpilot-demo-delta.vercel.app ｜ GitHub https://github.com/jessieyiqichen/job-pilot
- 图：assets/img/job-pilot.png

### 05 MusiClaw
- 角色：上海音乐剧市场数据平台 · 独立开发 · 证明：数据产品 + 内容运营闭环
- 一段话：把公开售票数据做成每天自动更新的数据产品：86 部剧的座位图快照、卡司归因分析、四条内容产线，支撑一个真实运营的数据账号。AI 的职责边界全部落成文档。
- 数字：86 部剧每日快照 ｜ 4 条内容产线 ｜ 发布后 24h 固定复盘
- 链接：案例拆解 https://jessieyiqichen.github.io/projects/musiclaw.html ｜ 数据仪表盘 https://jessieyiqichen.github.io/musiclaw-demo/
- 图：assets/img/musiclaw.png

## 四条工作方式
1. 痛点先于方案。动手前先确认瓶颈在哪一层：课堂提问的瓶颈在输入摩擦而非模型能力，收藏整理的瓶颈在「需要用户主动发起」这个动作本身。层判断错了，功能做得再好也不解决问题。
2. 灰度与归因。上线拆期，每期只引入一层变更，问题出现时可以立即定位责任层。多模态检索分三期灰度，两日全部合并，零回滚。
3. 指标先定口径。北极星选真正反映价值的：课后被复习的标记数，而非课中标记数。日活用 UV 不用 PV。任何进报告的数字，都要能说出哪个后台、哪个指标、哪天的读数。
4. 成本是产品参数。每次模型调用逐笔记账，按任务分档路由模型；降本之前先用影子双跑证明质量不掉。省钱是验证的结果，不是目标。

## 联系段文案
正在寻找 AI 产品方向的机会。2027 届，产品经理方向，AI 产品优先。想深入了解任何一个项目的细节，或者需要完整简历，欢迎邮件联系。
