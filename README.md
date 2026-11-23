# Hi, I'm 杨斌

**Go 后端开发工程师** · 杭州

目前在做数据中心动环监控网关，负责设备变化事件的北向可靠上报：事件保序、断线缓存、恢复补传与双 Broker 故障隔离。关注消息可靠性、状态一致性与故障恢复。

### 技术栈

Go · Gin · gRPC / Protobuf · MQTT · Redis · MySQL · RabbitMQ · Asynq · Docker · Linux

### 精选项目

- **[cooking-platform](https://github.com/quqxiaoli/cooking-platform)** — 做饭内容分享平台（前后端与部署）：Gin + MySQL + Redis + RabbitMQ；Redis Sentinel 旁路缓存、GORM DBResolver 读写分离、EventBus 抽象 Channel / RabbitMQ 双实现；配套 CI、集成测试与压测。
- **[DSS](https://github.com/quqxiaoli/DSS)** — 分布式缓存系统：手写带虚拟节点的一致性哈希，支持节点加入 / 移除时的数据迁移、LRU 与 TTL，配套单元测试。
- **[collaborative-blackboard](https://github.com/quqxiaoli/collaborative-blackboard)** — 实时协作白板后端：WebSocket + Redis Pub/Sub 广播房间操作；Lua 脚本原子执行状态更新与版本递增；Asynq 异步持久化到 MySQL。

### 联系

quqxiaoli@gmail.com
