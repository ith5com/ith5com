## 👋 Hi，我是麦勇潮

**AI Agent / 全栈开发工程师**，2016 年起从事前端开发，现聚焦 Agent 工程化与全栈交付。

独立开发「万小课」，面向技术创作者的知识付费平台，将内容购买、阅读、AI 导读、知识问答、复习题、知识图谱和思维导图串成一条学习链路。

🛠 **技术栈** · React + TypeScript · Go · NestJS · Python · PostgreSQL / MySQL · Redis · Docker · AWS

### 🏗️ 精选项目

**[agent-runtime](https://github.com/ith5com/agent-runtime)**

从零实现的 Agent 运行时，配套十章详解。涵盖工具循环、结构化输出校验与重试、运行记账、SSE 流式输出、三态熔断、超时回收与幂等回调，并提供 FastAPI 服务与 LangChain 适配层。

**万小课 · 线上运行，私有仓库**

独立完成 React + TypeScript 前端、Go 主服务和 Python AI 服务，已上线五个业务 Agent。Go 统一处理租户、身份、配额与任务派发，Python 执行 AI 任务，OpenTelemetry 贯穿服务调用。使用 Docker + Goploy 完成容器化部署与持续交付，另有 AWS Serverless 部署经验。

**第六个 Agent 与评测框架 · 开发中**

基于公共 Runtime 实现导读、RAG 问答、复习题、知识图谱、思维导图与智能客服，配套索引基础设施及规则与模型裁判评测，计划随教程公开。

### 🧰 开源后台基座

两套前后端分离的后台管理系统，同一套产品思路，分别用 Go 和 Node.js 实现，可作为中后台项目的起点。

**[go-gin-react-admin](https://github.com/ith5com/go-gin-react-admin)**

Gin + GORM + React 19 + Ant Design 6。覆盖 JWT 双令牌认证、角色与数据范围权限、动态菜单、定时任务、日志审计与系统监控，内置数据表导入式代码生成、表结构维护与软删除回收站，附首次安装向导。

**[nestjs-react-admin](https://github.com/ith5com/nestjs-react-admin)**

NestJS 11 + TypeORM + React 19 + Ant Design，若依风格。用户、角色、菜单、部门、字典、定时任务等系统模块齐全，支持按钮级权限与菜单自动注册，代码生成器可一键产出前后端 CRUD。[在线 Demo](http://admin.ith5.cn/)。

### 🧱 我怎么做系统

- **公共机制沉淀到运行时。** 从多个业务场景抽离工具循环、结构化输出、记账、超时、熔断与任务回收，通过工具、Schema 和业务校验回调承载场景差异。
- **权限由业务服务控制。** 身份、配额、扣点与越权检查收敛在 Go 侧，Python 在受控的租户上下文中执行 AI 任务。
- **用代码约束模型输出。** 问答有检索阈值拒答与引用回填，复习题依据必须在正文逐字定位。知识图谱由代码生成候选、模型判断关系、并查集完成合并。
- **先评测，再改提示词。** 规则与模型裁判结合，支持基于产物快照重评。提示词从 v1 到 v6 均保留评测数据。

### 🤖 AI 辅助开发

- **Harness Engineering** · 以 specs 驱动任务，按 Feature / Task 编排专业 Skills，串联开发、双轮代码审查、按需 QA 与文档同步，通过任务状态持久化、上下文重载和经验沉淀支持跨任务持续开发。
- **设计 Skill** · 将页面设计方法封装为可复用 Skill，已应用于万小课的界面生成与前端开发。

### 🧭 经历

- **2024—2025** · 企业级 Agent 配置与运行平台（兼职），涉及版本模型、Agent Loop、Tool Calling、RAG 与流式输出。
- **2022—2025** · 物流智能询价系统，从需求到前后端与小程序落地，带领两名前端开发者。
- **2016 年起** · 前端开发，参与游戏官网、广告后台、小游戏 SDK 与跨端社区等项目。

### 📮 找到我

- GitHub · [ith5com](https://github.com/ith5com)
- 微信 · ith5cn
- 邮箱 · ith5cn@163.com

欢迎交流 Agent 运行时、评测驱动的提示词迭代，以及 Go 后端开发。
