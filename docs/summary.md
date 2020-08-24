- 高并发架构

    - [消息队列](./docs/high-concurrency/mq-interview.md)
        - [为什么使用消息队列？](./docs/high-concurrency/why-mq.md)
        - [如何保证消息队列的高可用？](./docs/high-concurrency/how-to-ensure-high-availability-of-message-queues.md)
        - [如何保证消息不被重复消费？](./docs/high-concurrency/how-to-ensure-that-messages-are-not-repeatedly-consumed.md)
        - [如何保证消息的可靠性传输？](./docs/high-concurrency/how-to-ensure-the-reliable-transmission-of-messages.md)
        - [如何保证消息的顺序性？](./docs/high-concurrency/how-to-ensure-the-order-of-messages.md)
        - [如何解决消息队列的延时以及过期失效问题？](./docs/high-concurrency/mq-time-delay-and-expired-failure.md)
        - [如何设计一个消息队列？](./docs/high-concurrency/mq-design.md)

    - [搜索引擎](./docs/high-concurrency/es-introduction.md)
        - [ES 的分布式架构原理是什么？](./docs/high-concurrency/es-architecture.md)
        - [ES 写入数据的工作原理是什么？](./docs/high-concurrency/es-write-query-search.md)
        - [ES 在数十亿级别数量下如何提高查询效率？](./docs/high-concurrency/es-optimizing-query-performance.md)
        - [ES 生产集群的部署架构是什么？](./docs/high-concurrency/es-production-cluster.md)

    - 缓存
        - [在项目中缓存是如何使用的？](./docs/high-concurrency/why-cache.md)
        - [Redis 和 Memcached 有什么区别？](./docs/high-concurrency/redis-single-thread-model.md)
        - [Redis 都有哪些数据类型以及适用场景？](./docs/high-concurrency/redis-data-types.md)
        - [Redis 的过期策略都有哪些？](./docs/high-concurrency/redis-expiration-policies-and-lru.md)
        - [如何保证 Redis 高并发、高可用？](./docs/high-concurrency/how-to-ensure-high-concurrency-and-high-availability-of-redis.md)
        - [Redis 的持久化有哪几种方式？](./docs/high-concurrency/redis-persistence.md)
        - [Redis 集群模式的工作原理能说一下么？](./docs/high-concurrency/redis-cluster.md)
        - [Redis 的雪崩、穿透和击穿，如何应对？](./docs/high-concurrency/redis-caching-avalanche-and-caching-penetration.md)
        - [如何保证缓存与数据库双写一致性？](./docs/high-concurrency/redis-consistence.md)
        - [如何解决 Redis 的并发竞争问题？](./docs/high-concurrency/redis-cas.md)
        - [生产环境中的 Redis 是怎么部署的？](./docs/high-concurrency/redis-production-environment.md)

    - 分库分表
        - [为什么要分库分表？](./docs/high-concurrency/database-shard.md)
        - [分库分表如何平滑过渡？](./docs/high-concurrency/database-shard-method.md)
        - [设计一个动态扩容缩容的分库分表方案？](./docs/high-concurrency/database-shard-dynamic-expand.md)
        - [分库分表之后，id 主键如何处理？](./docs/high-concurrency/database-shard-global-id-generate.md)

    - 读写分离
        - [如何实现 MySQL 的读写分离？](./docs/high-concurrency/mysql-read-write-separation.md)

    - 高并发系统
        - [如何设计一个高并发系统？](./docs/high-concurrency/high-concurrency-design.md)
