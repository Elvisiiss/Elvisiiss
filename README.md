<div align="center">

<img src="assets/banner.svg" alt="L_dream · Backend Engineer" width="100%" />

<br />

<a href="mailto:3115089759@qq.com"><img src="https://img.shields.io/badge/3115089759%40qq.com-7F5AF0?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://space.bilibili.com/103149744"><img src="https://img.shields.io/badge/%E5%93%94%E5%93%A9%E5%93%94%E5%93%A9-00A1D6?style=flat-square&logo=bilibili&logoColor=white" alt="Bilibili" /></a>
<img src="https://img.shields.io/badge/%E8%B5%A3%E5%8D%97%E7%A7%91%E6%8A%80%E5%AD%A6%E9%99%A2-2CB67D?style=flat-square&logo=googlescholar&logoColor=white" alt="School" />
<a href="https://github.com/happyDElife"><img src="https://img.shields.io/badge/happyDElife-6246EA?style=flat-square&logo=github&logoColor=white" alt="Org" /></a>
<a href="https://github.com/Elvisiiss?tab=repositories"><img src="https://img.shields.io/badge/All%20Repositories-1B1F2E?style=flat-square&logo=gitbook&logoColor=white" alt="Repositories" /></a>

</div>

<img src="assets/section-rule.svg" width="100%" />

## 🧭 关于我

- 🎓 **2026 届** ｜ 赣南科技学院 · 数据科学与大数据技术 ｜ `2022.09 – 2026.06`
- 💻 **Go / Java 后端开发**：高并发服务、网络 I/O、分布式与存储检索
- 🤖 **LLM 应用工程**：Agent 编排、Context / Memory 工程、RAG 检索链路
- 🏢 三段实习：**网易 CC 直播**（Go）· **点点互动**（后台）· **晓多科技**（Agent）
- 📈 喜欢把性能做成数字：连接数 **2w → 5w**、死锁率 **43% → 0%**、内存 **-90%**
- ✨ 信条：**希望是指南针，信仰是扬起的船帆。**

<img src="assets/section-rule.svg" width="100%" />

## 🛠 技术栈

<div align="center">

<img src="https://skillicons.dev/icons?i=go,java,spring,mysql,redis,docker,kubernetes,linux,git,idea" alt="Tech Stack" />

<br /><br />

<img src="https://img.shields.io/badge/Spring%20Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white" alt="Spring Cloud" />
<img src="https://img.shields.io/badge/Dubbo-C1252E?style=flat-square" alt="Dubbo" />
<img src="https://img.shields.io/badge/MyBatis-DC382D?style=flat-square" alt="MyBatis" />
<img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white" alt="Elasticsearch" />
<img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka" />
<img src="https://img.shields.io/badge/Milvus-00A1EA?style=flat-square" alt="Milvus" />
<img src="https://img.shields.io/badge/RAG-7F5AF0?style=flat-square" alt="RAG" />
<img src="https://img.shields.io/badge/Agent-2CB67D?style=flat-square" alt="Agent" />

</div>

<img src="assets/section-rule.svg" width="100%" />

## 💼 实习经历

**🎮 广州网易互动娱乐 · CC 直播事业部** ｜ `Golang 开发实习生` ｜ `2026.03 – 2026.05`

- **WS 网关重构**：重排 goroutine 模型、以 `gnet` 替换网络 I/O 层，单机连接数 **2w → 5w**，吞吐 **10MB/s → 100MB/s**
- **榜单模块**：数据截断 + 缓存策略设计，手写 Ringbuffer 限流，支撑 Top100 与「未上榜」状态查询
- **七日签到**：独立落地，用 DB 幂等表固定 Rows + 流水表控成本，活动期零故障
- **Agent 平台**：旧 workflow 编排改造，参与 TAO / Replan 自主规划优化与知识库建模重构

**🎲 点点互动科技** ｜ `后台开发实习生` ｜ `2025.05 – 2025.10`

- **海外活动研发**：抽奖、任务、签到、榜单、碎片兑换等高频上新活动的设计与实现，与前端、测试共创活动营收
- **组件模板抽象**：同类玩法复用，让新活动低成本快速上线
- **死锁治理**：SQL 优化解决发奖接口数据库死锁，死锁率 **43% → 0%**
- **存储瘦身**：bitmap 分片替代 hash 存储礼包状态，50w 用户 **24MB → 0.5MB**（内存 ↓90%+）
- **消息积压**：参与 Kafka 通用消费积压方案的落地

**🤖 晓多科技** ｜ `Agent 开发实习生` ｜ `2024.10 – 2025.01`

- **Context 工程**：关键事实 / 用户画像 / 历史会话 / RAG 分类存储，优化上下文提升回答准确率
- **意图识别**：`keyword / rule / mini / weight` 多层置信度决策，兼顾安全性与准确率
- **Memory 工程**：滑动窗口保留近 N 轮，超阈值由 LLM 摘要落 MySQL，异步抽取用户特征同步 ES
- **检索链路**：查询重写 + ES/Milvus 混合检索，父子分段 + RRF 重排，提升召回率
- **MCP 双端实现**：Server / Client 双侧打通第三方工具生态
- **ES 调优**：fd / swap / search_after / reindex / refresh / ILM / JVM，查询效率 ↑ **25%**

<img src="assets/section-rule.svg" width="100%" />

## 🚀 精选项目

- 🎓 **[EduSphere](https://github.com/Elvisiiss/EduSphere_server)** · `Java` `Vue` — 教育平台，后端服务 + Web 前端双仓库
- 🏭 **[金属微丝产线管理平台](https://github.com/Elvisiiss/metal_micro_wire_backend)** · `Java` `Vue` — 产线数据管理与前端看板
- ⚙️ **[设备管理系统](https://github.com/Elvisiiss/Equipment_Management_System_Web)** · `Vue` — 设备台账与运维管理 Web 端
- 🏗️ **[IntelliMES](https://github.com/Elvisiiss/IntelliMES)** · `JavaScript` — 智能制造执行系统
- 📖 **[Elvel](https://github.com/Elvisiiss/Elvel)** · `Java` — 小说阅读应用
- 🎮 **[Twilight-Of-The-Gods](https://github.com/Elvisiiss/Twilight-Of-The-Gods)** · `GDScript` — Godot 引擎小游戏「诸神黄昏」

<sub>还有一些没上架的东西放在私有仓库里：在线测评题解、定时巡视脚本、日记本 ……</sub>

<img src="assets/section-rule.svg" width="100%" />

## 🏆 竞赛荣誉

<div align="center">

<img src="https://img.shields.io/badge/%E8%93%9D%E6%A1%A5%E6%9D%AF%20%C2%B7%20%E5%9B%BD%E8%B5%9B%E4%BA%8C%E7%AD%89%E5%A5%96-4285F4?style=flat-square" alt="蓝桥杯" />
<img src="https://img.shields.io/badge/ICPC%20%E6%B2%B3%E5%8D%97%E7%9C%81%E8%B5%9B%20%C2%B7%20%E9%93%9C%E7%89%8C-B87333?style=flat-square" alt="ICPC" />
<br />
<img src="https://img.shields.io/badge/%E7%89%A9%E8%81%94%E7%BD%91%E8%AE%BE%E8%AE%A1%E7%AB%9E%E8%B5%9B%20%C2%B7%20%E5%9B%BD%E5%AE%B6%E4%B8%80%E7%AD%89%E5%A5%96-2CB67D?style=flat-square" alt="物联网设计竞赛" />
<img src="https://img.shields.io/badge/%E5%B5%8C%E5%85%A5%E5%BC%8F%E8%8A%AF%E7%89%87%E4%B8%8E%E7%B3%BB%E7%BB%9F%E8%AE%BE%E8%AE%A1%20%C2%B7%20%E5%9B%BD%E5%AE%B6%E4%BA%8C%E7%AD%89%E5%A5%96-7F5AF0?style=flat-square" alt="嵌入式芯片与系统设计" />

</div>

<img src="assets/section-rule.svg" width="100%" />

## 📬 找到我

<div align="center">

<a href="mailto:3115089759@qq.com"><img src="https://img.shields.io/badge/Email-3115089759%40qq.com-7F5AF0?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://space.bilibili.com/103149744"><img src="https://img.shields.io/badge/Bilibili-%E7%A9%BA%E9%97%B4-00A1D6?style=flat-square&logo=bilibili&logoColor=white" alt="Bilibili" /></a>
<a href="https://github.com/Elvisiiss"><img src="https://img.shields.io/badge/GitHub-Elvisiiss-1B1F2E?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>

<br /><br />

<sub>「 希望是指南针，信仰是扬起的船帆。」</sub>

<br />

<sub>如果哪个仓库对你有用，欢迎点个 ⭐</sub>

</div>
