# Stanley Zheong

AI来临，我又能重回编码一线。记录很多做AI的体验和实现。

时间大概是逆序吧，

2025年，用cursor，gemini、amp、也能输出代码，但是总体质量就是demo，能做的事情也很少，写写agent.md，写写claude.md，总体还是在prompt层面想办法。玩了好多，都是在玩罢了，

2025年，最惊艳的不是manus、zenspark这样的产品，而是lovable、bolt.new这两个， 模型的微调做的真好，看见可以实用的经验，也是他两家开始。

2026年上半年，harness是一层大的提升，开始进入更高的门槛和更快的减速度，openspec、speckit、ohmyopenagent、superpowers、GSD、grill Me，隔一阵出一个，但用下来总是觉得还差点啥，前面这些多数都在flow/role这个维度，而specifacation极少说该做呢没做，这个维度认同晶磊的推荐，[spex](https://github.com/sublang-ai/spex) 的软件定义方式，迭代周期里能符合人类的成长，然后就开始尝试了各种融合、CLADA、KnowCle都是那时候尝试的。

2026年下半年开始做业务系统，把一些想法用ai做出来，包括老系统的改造、AI 工具和自动化实验。很多项目从一个具体问题开始：数据太散、流程太手工、知识不好找，或者一个内部工具值得被做得更顺手。

做了很多，就是挺遗憾的是始终没有闭环，都没有经过实际上线的验证。

## 行业应用类

| 项目 | 介绍 |
| --- | --- |
| [dbia](https://github.com/Stanley-Zheong/dbia) | 面向 DBA 场景的数据库智能助手，覆盖诊断、知识检索和运维问答。 |
| [ycsan](https://github.com/Stanley-Zheong/ycsan) | 业务应用与内部流程系统，关注数据流转、服务接口和运营动作。 |
| [ycsopen-sms](https://github.com/Stanley-Zheong/ycsopen-sms) | 短信能力接入服务，用于通知、验证和业务消息链路。 |
| [odoo-ai](https://github.com/Stanley-Zheong/odoo-ai) | Odoo 业务系统上的 AI 扩展和流程助手。 |
| [snipeit-ai](https://github.com/Stanley-Zheong/snipeit-ai) | 围绕 Snipe-IT 资产数据做的 AI 辅助管理实验。 |
| [supplychainfinence](https://github.com/Stanley-Zheong/supplychainfinence) | 供应链金融方向的业务建模、数据结构和流程实验。 |

## Harness 研究

| 项目 | 介绍 |
| --- | --- |
| [knowcle](https://github.com/Stanley-Zheong/knowcle) | 面向知识组织、检索和 agent 上下文管理的实验。 |
| [clada](https://github.com/Stanley-Zheong/clada) | agent 开发循环、自动化任务和工作流 harness 研究。 |
| [spec-x](https://github.com/Stanley-Zheong/spec-x) | 规格驱动开发实验，研究从需求到实现的结构化交付。 |
| [naipai](https://github.com/Stanley-Zheong/naipai) | AI 辅助产品和工程任务的 harness 实验。 |
| [ai-intel-daily](https://github.com/Stanley-Zheong/ai-intel-daily) | AI 情报的日常收集、摘要和追踪工作流。 |
| [jarvis-box](https://github.com/Stanley-Zheong/jarvis-box) | 本地 agent 运行时和知识盒子实验，用来改进人和 agent 的协作方式。 |
| [ragbases](https://github.com/Stanley-Zheong/ragbases) | 可复现的 RAG 基础项目，目前用于 Oracle DBA 培训知识库、chunk 和 hybrid retrieval。 |

## 做着玩的

| 项目 | 介绍 |
| --- | --- |
| [multi-sync](https://github.com/Stanley-Zheong/multi-sync) | 多端数据和工具同步实验。 |
| [eshoping-javaee-full](https://github.com/Stanley-Zheong/eshoping-javaee-full) | Java EE 电商完整应用，用于学习、参考和实验。 |
| [wx-auto](https://github.com/Stanley-Zheong/wx-auto) | 微信自动化方向的小工具实验。 |
| [xianyu-backedn](https://github.com/Stanley-Zheong/xianyu-backedn) | 闲鱼类交易场景的后端实验。 |
| [unaip](https://github.com/Stanley-Zheong/unaip) | 小型应用和自动化原型。 |
| [autocs](https://github.com/Stanley-Zheong/autocs) | 客服自动化实验。 |
| [fbaa](https://github.com/Stanley-Zheong/fbaa) | 业务自动化和助手类实验。 |
| [dia-for](https://github.com/Stanley-Zheong/dia-for) | 轻量工具和个人原型项目。 |

## 现在关注

- 把 RAG 的解析、切片、评测做成可复现工程，而不是只做聊天界面。
- 把业务流程拆成小工具，让 AI 参与具体步骤。
- 研究更稳定的 agent harness，让任务能被计划、验证和复用。
