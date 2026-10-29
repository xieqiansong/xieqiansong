# xieqiansong

Java 开发工程师。个人主页，导航精选项目与笔记。

## 笔记

- **性能优化**
  - [TCP-over-WebSocket 隧道（Netty）：端到端性能基准与瓶颈分析](https://github.com/xieqiansong/chaos-notes/blob/main/performance/TCP-over-WebSocket隧道-端到端性能基准与瓶颈分析.md) — 逐字节转发开销、弱网与高延迟性能边界
  - [多租户分布式限流：本地 + Redis 双层限流](https://github.com/xieqiansong/chaos-notes/blob/main/performance/多租户分布式限流-本地加Redis双层限流.md) — 本地令牌桶、Redis 周期校准、热路径零网络开销、可控突发
  - [Redis 批量入库：自适应批量大小](https://github.com/xieqiansong/chaos-notes/blob/main/performance/Redis批量入库-自适应批量大小.md) — 队列攒批、批量大小在线寻优、削峰、低峰不滞留
- **踩坑记录**
  - [Linux 高负载：nf_conntrack 连接跟踪表溢出](https://github.com/xieqiansong/chaos-notes/blob/main/pitfalls/Linux高负载nf_conntrack连接跟踪表溢出.md) — 高并发长连接、连接跟踪表溢出、高负载调优
  - [ES 集群节点版本不一致导致数据不同步](https://github.com/xieqiansong/chaos-notes/blob/main/pitfalls/ES集群节点版本不一致导致数据不同步.md) — 节点小版本不一致、分片/数据不同步、排查与处理
- **技术学习**
  - [OAuth2 授权服务器与 Token 生命周期](https://github.com/xieqiansong/chaos-notes/blob/main/notes/OAuth2授权服务器与Token生命周期.md) — 手写 IdP、授权码+PKCE、JWT access+不透明 refresh、滚动刷新、撤销黑名单、JWKS
  - [RabbitMQ 学习记录](https://github.com/xieqiansong/chaos-notes/blob/main/notes/RabbitMQ学习记录.md) — Exchange 路由、Publisher Confirm、手动 Ack、TTL+DLX、消息可靠性
  - [WebFlux 响应式编程学习记录](https://github.com/xieqiansong/chaos-notes/blob/main/notes/WebFlux响应式编程学习记录.md) — Reactor、背压、RouterFunction、WebClient

> 更多笔记见 [Chaos Notes](https://github.com/xieqiansong/chaos-notes)。

## 项目

- [Chaos Java](https://github.com/xieqiansong/chaos-java) — Java 多版本生态下的中间件最小可用设计学习聚合仓库。按 JDK 约束划分 `jdk8`~`jdk25` 五个平台，一个模块一个技术点（jdk8 平台 22 个模块：Redis / RocketMQ / Kafka / Seata / Nacos / Sentinel / 秒杀 / 短链 等）
- [Chaos Lib](https://github.com/xieqiansong/chaos-lib) — 自托管个人工具箱：任务管理 / FSRS 间隔复习 / 环境变量与 SDK 多版本管理 / 端口转发
- [Chaos Tcp Over Websockets](https://github.com/xieqiansong/chaos-tcp-over-websockets) — Netty 实现的 TCP over WebSocket 隧道工具，受限网络下的端口穿透
- [Chaos IDEA Plugin](https://github.com/xieqiansong/chaos-idea-plugin) — IntelliJ IDEA 效率插件：IdeaVim 增强、文本替换、终端工具
- [Chaos Notes](https://github.com/xieqiansong/chaos-notes) — 踩坑记录、技术学习与性能优化笔记仓库
- [Chaos UI](https://github.com/xieqiansong/chaos-ui) — 前端练习项目：Vue 3 + Vite 前端（`chaos-vue`）配套 NestJS 11 + TypeORM + SQLite 后端（`chaos-nestjs`）

## License

[MIT License](LICENSE)（被引用项目保留其原始许可证与版权）。
