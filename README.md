# Backend Playground

> 一个面向后端开发者的多语言技术实验室、工程实践平台与个人代码知识库。

## 📖 项目介绍

Backend Playground 是一个用于学习、研究、实践和比较后端开发技术的开源项目，涵盖 Go、Java、C#、Python 等主流后端编程语言及其技术生态。

本项目通过最小可运行示例（Minimal Runnable Examples）、独立技术实验、跨语言对比和综合项目实践，系统性地积累后端开发知识与工程经验。

项目不局限于某一种编程语言或技术框架，而是关注后端开发中的通用技术原理、设计思想、工程实践以及不同技术生态下的解决方案。

希望将本项目逐步建设成为一个可以长期维护、持续扩展、快速查阅的个人后端工程知识库。

## 🎯 项目目标

- **技术学习（Learning）**：系统学习主流后端编程语言、框架及中间件。
- **代码参考（Reference）**：建立可运行、可复用、易于查阅的个人代码参考库。
- **技术实验（Experiment）**：通过独立实验验证技术原理、设计方案和技术边界。
- **横向对比（Comparison）**：研究不同编程语言及技术生态解决相同问题的方式。
- **工程实践（Engineering）**：积累真实开发场景中的工程经验与最佳实践。
- **知识沉淀（Documentation）**：记录技术原理、常见问题、踩坑经验和解决方案。
- **综合应用（Application）**：通过小型项目整合不同技术，提升系统设计与开发能力。

## 🛠️ 技术栈

以下为项目计划覆盖的技术生态。

| 技术领域 | Go                  | Java                    | TypeScript / JavaScript | C#                  | Python              |
| -------- | ------------------- | ----------------------- | ----------------------- | ------------------- | ------------------- |
| Web 框架 | Gin                 | Spring Boot             | Node.js / NestJS        | ASP.NET Core        | FastAPI / Django    |
| ORM      | GORM                | Hibernate / JPA         |                         | EF Core             | SQLAlchemy          |
| SQL 操作 | database/sql、sqlx  | MyBatis                 |                         | Dapper              | SQLAlchemy Core     |
| Redis    | go-redis            | Redisson / Lettuce      |                         | StackExchange.Redis | redis-py            |
| Kafka    | franz-go            | Spring Kafka            |                         | Confluent.Kafka     | confluent-kafka     |
| 并发编程 | Goroutine / Channel | Thread / Virtual Thread |                         | Task / async-await  | asyncio / threading |
| RPC      | gRPC                | gRPC                    |                         | gRPC                | gRPC                |
| 单元测试 | testing             | JUnit                   |                         | xUnit               | pytest              |
| 日志     | slog / Zap          | SLF4J / Logback         |                         | ILogger / Serilog   | logging             |
| 依赖管理 | Go Modules          | Maven / Gradle          |                         | NuGet               | uv                  |
| API 文档 | Swagger / OpenAPI   | Springdoc               |                         | OpenAPI             | OpenAPI             |

### 基础设施与中间件

- MySQL
- PostgreSQL
- MongoDB
- Redis
- Apache Kafka
- RabbitMQ
- Elasticsearch
- Docker & Docker Compose
- Nginx
- Prometheus
- Grafana
- OpenTelemetry

## 📂 项目目录结构

简单版目录结构：

```
backend-playground/
├── README.md
├── LICENSE
├── .gitignore
├── .env.example
├── go/
│   ├── README.md
│   └── go.mod
├── java/
│   └── README.md
├── typescript/
│   └── README.md
├── csharp/
│   └── README.md
├── python/
│   └── README.md
├── infrastructure/
│   └── compose.yaml
├── system-design/
│   └── README.md
├── comparisons/
│   └── README.md
├── projects/
│   └── README.md
└── docs/
    └── README.md
```

以下为项目的参考目录结构，将根据学习进度与实际需求逐步完善。

```text
backend-playground/
├── README.md
├── LICENSE
├── .gitignore
├── .env.example
│
├── go/
│   ├── README.md
│   ├── go.mod
│   ├── go.sum
│   ├── language/
│   ├── standard-library/
│   ├── concurrency/
│   ├── gin/
│   ├── gorm/
│   ├── database/
│   ├── redis/
│   ├── kafka/
│   ├── rabbitmq/
│   ├── grpc/
│   ├── security/
│   ├── design-patterns/
│   ├── testing/
│   ├── observability/
│   └── mini-projects/
│
├── java/
│   ├── README.md
│   ├── pom.xml
│   ├── language/
│   ├── standard-library/
│   ├── concurrency/
│   ├── jvm/
│   ├── spring-framework/
│   ├── spring-boot/
│   ├── spring-security/
│   ├── spring-data-jpa/
│   ├── mybatis/
│   ├── redis/
│   ├── kafka/
│   ├── rabbitmq/
│   ├── grpc/
│   ├── design-patterns/
│   ├── testing/
│   ├── observability/
│   └── mini-projects/
│
├── csharp/
│   ├── README.md
│   ├── BackendPlayground.sln
│   ├── language/
│   ├── standard-library/
│   ├── concurrency/
│   ├── aspnet-core/
│   ├── entity-framework/
│   ├── dapper/
│   ├── redis/
│   ├── kafka/
│   ├── rabbitmq/
│   ├── grpc/
│   ├── security/
│   ├── design-patterns/
│   ├── testing/
│   ├── observability/
│   └── mini-projects/
│
├── python/
│   ├── README.md
│   ├── pyproject.toml
│   ├── language/
│   ├── standard-library/
│   ├── concurrency/
│   ├── fastapi/
│   ├── django/
│   ├── flask/
│   ├── sqlalchemy/
│   ├── redis/
│   ├── kafka/
│   ├── rabbitmq/
│   ├── celery/
│   ├── grpc/
│   ├── security/
│   ├── design-patterns/
│   ├── testing/
│   ├── observability/
│   └── mini-projects/
│
├── infrastructure/
│   ├── README.md
│   ├── compose.yaml
│   ├── mysql/
│   ├── postgresql/
│   ├── mongodb/
│   ├── redis/
│   ├── kafka/
│   ├── rabbitmq/
│   ├── elasticsearch/
│   ├── nginx/
│   ├── prometheus/
│   └── grafana/
│
├── system-design/
│   ├── README.md
│   ├── caching/
│   ├── rate-limiting/
│   ├── distributed-lock/
│   ├── distributed-id/
│   ├── idempotency/
│   ├── distributed-transaction/
│   ├── message-queue/
│   ├── load-balancing/
│   ├── circuit-breaker/
│   ├── service-discovery/
│   └── high-availability/
│
├── comparisons/
│   ├── README.md
│   ├── rest-api/
│   ├── concurrency/
│   ├── database-access/
│   ├── dependency-injection/
│   ├── error-handling/
│   ├── authentication/
│   ├── serialization/
│   ├── caching/
│   └── benchmarks/
│
├── projects/
│   ├── README.md
│   ├── short-url/
│   ├── task-scheduler/
│   ├── notification-service/
│   ├── order-system/
│   └── polyglot-microservices/
│
├── docs/
│   ├── architecture/
│   ├── concepts/
│   ├── best-practices/
│   ├── troubleshooting/
│   ├── interview/
│   └── resources/
│
├── scripts/
│   ├── setup/
│   ├── testing/
│   └── benchmark/
│
└── .github/
    └── workflows/
        ├── go.yml
        ├── java.yml
        ├── csharp.yml
        └── python.yml
```

## 📁 目录说明

| 目录              | 说明                                   |
| ----------------- | -------------------------------------- |
| `go/`             | Go 语言及其后端技术生态                |
| `java/`           | Java 语言及 Spring 后端技术生态        |
| `csharp/`         | C# 语言及 .NET 后端技术生态            |
| `python/`         | Python 语言及其后端技术生态            |
| `infrastructure/` | 共享基础设施、中间件及容器配置         |
| `system-design/`  | 通用后端架构、系统设计与分布式系统原理 |
| `comparisons/`    | 跨语言、跨框架的技术对比实验           |
| `projects/`       | 跨技术栈或多语言综合实践项目           |
| `docs/`           | 技术文档、学习笔记、最佳实践与问题记录 |
| `scripts/`        | 环境初始化、测试及自动化脚本           |
| `.github/`        | GitHub Actions 与持续集成配置          |

各语言目录下的 `mini-projects/` 用于存放单一语言的小型实践项目，根目录下的 `projects/` 则用于存放跨语言、跨技术栈的综合实验项目。

## 📚 学习内容

### 1. 编程语言与标准库

- 基础语法与类型系统
- 面向对象与接口
- 泛型与反射
- 异常与错误处理
- 集合与数据结构
- 文件与网络编程
- 内存管理与垃圾回收
- 常用标准库

### 2. 并发与异步编程

- 线程、协程与异步任务
- 线程池与 Worker Pool
- 锁与同步机制
- 原子操作
- 生产者与消费者模型
- 超时与任务取消
- 并发安全
- 死锁与资源泄漏
- 优雅关闭

### 3. Web 后端开发

- HTTP 协议
- RESTful API
- 路由与请求处理
- 参数绑定与校验
- 中间件与拦截器
- 全局异常处理
- 文件上传与下载
- WebSocket
- Server-Sent Events（SSE）
- API 版本管理
- OpenAPI 文档

### 4. 数据库

- SQL 基础与高级查询
- CRUD 操作
- ORM 框架
- 分页查询
- 数据库事务
- 事务隔离级别
- 索引与查询优化
- 乐观锁与悲观锁
- 数据库连接池
- 数据库迁移
- 数据库死锁

### 5. 缓存

- Redis 基础数据结构
- 缓存读写策略
- Cache Aside
- 缓存穿透
- 缓存击穿
- 缓存雪崩
- 缓存一致性
- 分布式锁
- 限流
- 延迟任务

### 6. 消息队列

- 消息生产与消费
- 消息确认机制
- Offset 管理
- 消息重试
- 死信队列
- 消息顺序性
- 重复消费与幂等性
- 消息可靠性
- 消费者组
- Transactional Outbox

### 7. RPC 与微服务

- Protocol Buffers
- gRPC
- 服务注册与发现
- 服务间通信
- 负载均衡
- 超时与重试
- 熔断与降级
- API Gateway
- 分布式配置
- 分布式链路追踪

### 8. 安全

- Authentication & Authorization
- Session & Cookie
- JWT
- OAuth 2.0
- OpenID Connect
- RBAC
- CORS
- CSRF
- SQL Injection 防护
- 密码哈希与安全存储
- API 安全

### 9. 软件设计与架构

- SOLID 原则
- 常用设计模式
- 依赖注入
- 分层架构
- Clean Architecture
- Hexagonal Architecture
- Domain-Driven Design（DDD）
- CQRS
- Event-Driven Architecture
- Modular Monolith
- Microservices

### 10. 测试与工程实践

- 单元测试
- 集成测试
- Mock 与 Stub
- Testcontainers
- 性能测试
- Benchmark
- 压力测试
- 结构化日志
- Metrics
- Distributed Tracing
- Profiling
- CI/CD

## 🔬 Demo 组织规范

每个 Demo 应尽可能独立、简单、可运行，并围绕一个明确的技术知识点展开。

### 示例：Go Redis

```text
go/redis/
├── README.md
├── basic-commands/
│   ├── README.md
│   └── main.go
├── cache-aside/
│   ├── README.md
│   ├── main.go
│   └── main_test.go
├── cache-penetration/
├── cache-breakdown/
├── cache-avalanche/
├── distributed-lock/
├── rate-limiter/
└── pub-sub/
```

### 示例：Java Spring Boot

```text
java/spring-boot/
├── README.md
├── hello-world/
│   ├── pom.xml
│   ├── README.md
│   └── src/
│       ├── main/
│       │   ├── java/
│       │   └── resources/
│       └── test/
│           └── java/
├── rest-api/
├── request-validation/
├── exception-handling/
├── dependency-injection/
├── configuration/
└── interceptor/
```

### 示例：C# ASP.NET Core

```text
csharp/aspnet-core/
├── README.md
├── hello-world/
│   ├── README.md
│   ├── HelloWorld.csproj
│   ├── Program.cs
│   └── appsettings.json
├── minimal-api/
├── web-api/
├── middleware/
├── dependency-injection/
├── exception-handling/
└── configuration/
```

### 示例：Python FastAPI

```text
python/fastapi/
├── README.md
├── hello-world/
│   ├── README.md
│   └── main.py
├── routing/
├── request-validation/
├── dependency-injection/
├── middleware/
├── exception-handling/
├── async-endpoint/
└── websocket/
```

各语言遵循自身的项目组织规范，不强制使用完全相同的文件结构。

## 📝 Demo 文档规范

建议每个 Demo 包含独立的 README，并根据实际情况记录以下内容：

| 内容                | 说明               |
| ------------------- | ------------------ |
| Overview            | 功能介绍与实验背景 |
| Learning Objectives | 学习目标           |
| Concepts            | 核心技术原理       |
| Implementation      | 实现思路与关键代码 |
| Prerequisites       | 环境与依赖要求     |
| Quick Start         | 运行方式           |
| Expected Results    | 预期运行结果       |
| Test Cases          | 测试与验证方式     |
| Edge Cases          | 异常情况与边界条件 |
| Use Cases           | 实际业务应用场景   |
| Best Practices      | 工程实践与注意事项 |
| References          | 官方文档及参考资料 |

简单 Demo 无须包含全部内容，以清晰、实用为原则。

## ⚖️ 跨语言技术对比

本项目不仅关注单一语言的技术实现，也关注不同技术生态之间的差异。

例如，针对缓存模式、REST API、数据库事务、分布式锁等通用后端问题，分别使用 Go、Java、C# 和 Python 进行实现与对比。

```text
comparisons/
└── cache-aside/
    ├── README.md
    ├── specification.md
    ├── test-cases/
    └── benchmark/
```

具体实现优先复用各语言目录下的 Demo，通过文档链接、统一接口约定及测试用例进行关联，避免重复维护相同代码。

对比维度包括：

- 语言特性与实现方式
- 代码复杂度与可读性
- 框架设计与抽象程度
- 并发模型与运行机制
- 异常处理方式
- CPU 与内存占用
- 吞吐量与响应延迟
- 开发效率与维护成本
- 实际业务适用场景

性能对比应尽可能采用一致的硬件环境、业务逻辑、测试数据和测试条件，并记录运行时版本及相关配置。

## 🚀 快速开始

### 1. 克隆项目

```bash
git clone https://github.com/<your-username>/backend-playground.git

cd backend-playground
```

请将 `<your-username>` 替换为实际的 GitHub 用户名。

### 2. 准备开发环境

根据需要安装对应语言的开发工具：

| 环境           | 用途         |
| -------------- | ------------ |
| Go SDK         | Go 开发      |
| JDK / Maven    | Java 开发    |
| .NET SDK       | C# 开发      |
| Python / uv    | Python 开发  |
| Docker         | 容器化环境   |
| Docker Compose | 基础设施管理 |
| Git            | 版本控制     |

具体版本要求以各语言目录及 Demo 文档为准，无须同时安装所有语言环境。

### 3. 启动基础设施

项目计划使用 Docker Compose 统一管理常用数据库和中间件。

配置完成后，可以根据实验需求单独启动服务：

```bash
cd infrastructure

docker compose up -d redis
```

启动 MySQL：

```bash
docker compose up -d mysql
```

查看服务状态：

```bash
docker compose ps
```

停止服务：

```bash
docker compose down
```

不同 Demo 应通过独立的数据库名称、Redis Key 前缀、Kafka Topic 和 Consumer Group 等方式隔离实验数据。

### 4. 运行 Demo

以下命令为对应示例完成后的参考运行方式。

**Go**

```bash
cd go
go mod download
go run ./gin/hello-world
```

**Java**

```bash
cd java/spring-boot/hello-world
mvn spring-boot:run
```

**C#**

```bash
cd csharp/aspnet-core/hello-world
dotnet run
```

**Python**

```bash
cd python
uv sync
uv run uvicorn main:app \
  --app-dir fastapi/hello-world
```

具体启动方式、端口、环境变量及依赖要求，请参考对应 Demo 的 README。

## 🏗️ 项目设计原则

### Minimal — 最小化

每个 Demo 聚焦一个明确的技术问题，避免引入不必要的业务逻辑和复杂架构。

### Independent — 独立性

各 Demo 尽可能独立运行，减少不同实验之间的耦合。

### Runnable — 可运行

代码不仅用于阅读，也应能够实际运行并验证技术行为。

### Testable — 可测试

通过测试用例验证功能、异常处理、边界条件以及并发安全性。

### Reproducible — 可复现

明确记录依赖版本、运行环境、配置参数和实验步骤。

### Documented — 可查阅

记录技术原理、实现方式、使用场景、常见问题及参考资料。

### Extensible — 可扩展

支持未来加入新的编程语言、框架、中间件和技术领域。

### Practical — 实用性

关注实际开发中的问题与解决方案，而不仅仅是 API 的简单使用。

## 🔄 学习与实践流程

```text
Learn       学习技术原理
    ↓
Implement   编写最小可运行示例
    ↓
Experiment  进行技术实验与异常模拟
    ↓
Test        验证功能与边界条件
    ↓
Document    记录知识与工程经验
    ↓
Compare     对比不同技术实现
    ↓
Apply       应用于实际业务项目
    ↓
Refactor    持续改进与完善
```

通过持续实践，将零散的技术知识转化为可复用的工程经验。

## 📋 开发与学习路线

以下为初始规划，将根据实际学习进度持续调整。

### Phase 1 — Backend Fundamentals

- [ ] 编程语言与标准库
- [ ] 并发与异步编程
- [ ] HTTP 与 RESTful API
- [ ] 主流 Web 框架
- [ ] SQL 与 ORM
- [ ] 单元测试

### Phase 2 — Backend Core Technologies

- [ ] Redis 缓存
- [ ] 身份认证与权限管理
- [ ] Kafka 与 RabbitMQ
- [ ] gRPC 与 Protocol Buffers
- [ ] Docker & Docker Compose
- [ ] 数据库事务与性能优化

### Phase 3 — Software Engineering

- [ ] 设计模式
- [ ] 软件架构
- [ ] 集成测试
- [ ] CI/CD
- [ ] 日志与监控
- [ ] 性能分析
- [ ] 跨语言技术对比

### Phase 4 — Distributed Systems

- [ ] 分布式锁
- [ ] 分布式 ID
- [ ] 分布式事务
- [ ] 幂等性设计
- [ ] 限流与熔断
- [ ] 服务注册与发现
- [ ] 高并发与高可用设计

### Phase 5 — Practical Projects

- [ ] Todo REST API
- [ ] 用户认证服务
- [ ] 短链接系统
- [ ] 异步任务系统
- [ ] 消息通知服务
- [ ] 订单管理系统
- [ ] 秒杀系统
- [ ] 多语言微服务系统

## 📐 代码与提交规范

### 代码规范

- 遵循各编程语言的官方编码规范。
- 使用清晰且具有语义的变量、函数和目录名称。
- 避免过度设计与不必要的抽象。
- 优先保证代码的正确性、可读性和可维护性。
- 不提交密码、Token、API Key 等敏感信息。
- 使用环境变量或示例配置文件管理敏感配置。
- 对关键逻辑、异常场景和技术原理添加必要说明。

### Git 提交规范

推荐使用 Conventional Commits 规范。

```text
feat(go): add gin middleware example
feat(java): add redis distributed lock
feat(csharp): add ef core transaction example
feat(python): add fastapi dependency injection
fix(go): fix worker pool goroutine leak
docs(redis): explain cache aside pattern
test(java): add transaction rollback tests
refactor(python): simplify database access
chore(infra): update docker compose configuration
perf(go): optimize serialization benchmark
```

## 📖 参考资料

### 编程语言

- [Go Documentation](https://go.dev/doc/)
- [Java Documentation](https://dev.java/)
- [.NET Documentation](https://learn.microsoft.com/dotnet/)
- [Python Documentation](https://docs.python.org/3/)

### Web 框架与 ORM

- [Gin](https://gin-gonic.com/docs/)
- [GORM](https://gorm.io/docs/)
- [Spring Boot](https://spring.io/projects/spring-boot)
- [MyBatis](https://mybatis.org/mybatis-3/)
- [ASP.NET Core](https://learn.microsoft.com/aspnet/core/)
- [Entity Framework Core](https://learn.microsoft.com/ef/core/)
- [FastAPI](https://fastapi.tiangolo.com/)
- [Django](https://docs.djangoproject.com/)
- [SQLAlchemy](https://docs.sqlalchemy.org/)

### 基础设施与中间件

- [MySQL](https://dev.mysql.com/doc/)
- [PostgreSQL](https://www.postgresql.org/docs/)
- [Redis](https://redis.io/docs/)
- [Apache Kafka](https://kafka.apache.org/documentation/)
- [RabbitMQ](https://www.rabbitmq.com/docs)
- [gRPC](https://grpc.io/docs/)
- [Docker](https://docs.docker.com/)
- [Prometheus](https://prometheus.io/docs/)
- [OpenTelemetry](https://opentelemetry.io/docs/)



## 🌱 持续维护

Backend Playground 是一个持续演进的个人技术实验室，而不是一个具有固定完成日期的业务项目。

随着技术学习、实际开发经验和工程能力的提升，本项目将不断补充新的技术示例、设计方案、实验结果以及最佳实践。

**Learn · Build · Experiment · Compare · Document · Improve**

学习、构建、实验、对比、沉淀、持续改进。
