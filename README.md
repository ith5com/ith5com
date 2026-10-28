# 👋 Hi，我是 麦勇潮

- 🧑‍💻 **AI Agent 开发 / AI 全栈开发**，Python 与 Go 后端独立交付，前端出身所以能一个人把产品做完
- 🤖 正在独立开发 **万小课**：面向技术创作者的知识付费平台，读者买一本小册同时得到导读、复习题、能答问题的助教和知识图谱。Go 主服务、Python AI 服务、创作者后台与读者端都是我写的
- 🧰 偏好先手写 Agent 运行时再对照框架：httpx 写通全链路后换 LangChain，循环一行不改
- 📏 用评测驱动提示词迭代，用代码校验约束模型输出；身份、配额、越权控制放在 Go 侧，Python 不持有业务权限
- 📘 边做边写教程，代码和详解同步公开

## 🏗️ 正在做的

| 项目 | 简介 | 技术栈 | 状态 |
|------|------|--------|------|
| [agent-runtime](https://github.com/ith5cn/agent-runtime) | 从零手写的 Agent 运行时：工具循环、SQLite 记账、pydantic 结构化输出打回重试、FastAPI 服务化与回调、SSE 流式、三态熔断与僵尸回收、LangChain 适配层，十章配套详解 | Python 3.12, FastAPI, pydantic, httpx, LangChain, pytest | ✅ 完成 |
| 六个 Agent | 在上面的运行时之上做导读、索引与 RAG 问答、复习题、知识图谱、思维导图、智能客服，加规则与模型裁判的评测框架 | DeepSeek, pgvector, 通义 embedding | 🚧 进行中 |
| 万小课 AI 服务 | 线上版五个 Agent：导读两阶段工具调用；RAG 问答按段切块不拆代码、相似度阈值拒答、引用回填；复习题每题依据逐字定位、按节配额、哈希增量；知识图谱代码找候选、模型选、并查集合并；思维导图 | Python, FastAPI, LangChain, pgvector | 线上运行，私有仓库 |
| 万小课 Go 主服务 | 约 3 万行、157 个接口。多租户三库隔离、不透明 Token 会话、Python 任务派发与超时回收、/internal 常量时间校验、Redis 先占额配额、统一错误体系、OpenTelemetry 贯穿到 Python 侧 | Go 1.25, Gin, GORM, PostgreSQL, Redis, Docker Compose | 线上运行，私有仓库 |

## 🧭 走过的路

- 2024 至 2025 兼职参与企业级 Agent 配置与运行平台：Agent 定义与版本模型、Agent Loop、Tool Calling、RAG 注入与流式输出
- 2022 至 2025 物流智能询价从需求到前后端与小程序落地，带两人前端
- 2016 起十年前端：游戏官网、广告后台、小游戏 SDK、跨端社区、AI 广告投放平台

## 🗺️ 接下来

- 六个 Agent 做完，公开《Agent 运行时详解》和《六个 Agent 详解》两套教程
- 读者学习助理：一个入口，路由到问答、选课、复习、查订单、转人工，范围由已购内容圈定
- 用 LangGraph 把六个 Agent 重写一遍，同一评测集重判，做手写与框架的对照
- 抽一个通用 harness：会话日志为真相、事件、工具目录与权限

## 🌍 找到我

- GitHub：[github.com/ith5cn](https://github.com/ith5cn)
- 邮箱：ith5cn@163.com

---

📬 欢迎交流 Agent 运行时、评测驱动的提示词迭代，以及 Go 后端。
