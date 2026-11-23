# e-commerce-agent

我做的是给想要在网上售卖充电器、数据线、手机壳这样的3C配件的商铺，核心技术是做1个Agent电商客服, 专门来介绍这个商铺卖哪些商品, 手机壳、充电器它们是适配华为手机还是适配苹果手机, 下单过哪些商品
这个Agent智能体我把它类成比成淘宝店小蜜、杭州网易七鱼、上海智齿科技的

## 项目仓库

- [gba-merchant-bao](https://github.com/e-commerce-agent/gba-merchant-bao) ——主工程仓库（Java后端+Vue前端）

## 技术栈

**后端**：Java21、Spring Boot3.5.16、MySQL8.4、Flyway、Redis、RabbitMQ、Docker、JWT、MongoDB、MinIO
**AI 能力**：LangChain4j、Milvus向量库、SSE流式输出、RAG混合检索、Embedding向量化、Tool Calling
**前端**：Vue 3 + TypeScript + Vite + Pinia + Element Plus + ECharts，单应用多路由

## 成员分工

| 角色 | 职责 |
| --- | --- |
| 项目组长 | 前端开发 : 认证模块、商品模块、库存模块、订单模块、物流模块、任务分配、需求文档、数据库表设计文档、后端物流模块开发 |
| 后端开发 | 业务场景与技术模块设计、后端技术模块架构、表结构与api接口设计、后端开发 : 认证模块、Agent对话模块、RAG检索模块、Tool Calling模块、单元测试与集成测试、Apifox测试、eval评测集、JMeter压测、Docker中间件部署、Github组织仓库维护 |
| 订单模块负责人 | 后端订单模块开发、前后端联调、演示视频录制 |
| 库存模块负责人 | 后端库存模块开发、用例图、UML技术图绘制 |
| 商品模块负责人 | 后端商品模块开发、各成员分工PPT制作 |
| 单元测试负责人 | 单元测试文档 |

## 说明

本项目为简历项目、毕业设计，代码与文档仅用于简历项目、2026年暑假开学后的Codex智能体调用gpt 6.1 sol high开发学习
使用到的技术可能被淘汰, 所以这个项目不代表项目负责人最新技术动态
