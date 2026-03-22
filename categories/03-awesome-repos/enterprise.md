# 企业级测试实践

收录业界知名企业的测试架构和最佳实践仓库。

---

## Meta (Facebook)

### facebook/watchman

> **仓库**: [https://github.com/facebook/watchman](https://github.com/facebook/watchman)
>
> **Stars**: ![GitHub Repo stars](https://img.shields.io/github/stars/facebook/watchman?style=social)
>
> **语言**: C++

**项目简介**

Watchman 是 Facebook 开发的文件监听服务，用于触发测试和构建流程。它是 Buck 构建系统的核心组件，能够高效地监听文件变化并触发相应的测试任务。

**测试实践亮点**

| 实践 | 说明 |
|-----|------|
| **增量测试** | 只测试受影响代码相关的用例 |
| **分布式执行** | 跨多个 worker 并行执行 |
| **智能缓存** | 缓存测试结果，避免重复运行 |
| **快速反馈** | 平均 30 秒内完成测试反馈 |

**技术栈**

- 文件监听: inotify (Linux), FSEvents (macOS), ReadDirectoryChangesW (Windows)
- 通信协议: WebSocket
- 部署: 内部大规模集群

**可学习之处**

- 大规模代码库的测试选择策略
- 实时文件监听的最佳实践
- 与 CI/CD 系统的集成方案

**标签**

`#infrastructure` `#incremental-testing` `#ci-cd` `#large-scale` `#facebook`

---

### facebook/pyre-check

> **仓库**: [https://github.com/facebook/pyre-check](https://github.com/facebook/pyre-check)
>
> **Stars**: ![GitHub Repo stars](https://img.shields.io/github/stars/facebook/pyre-check?style=social)
>
> **语言**: Python, OCaml

**项目简介**

Pyre 是 Facebook 开发的类型检查工具，用于在运行前捕获代码缺陷。虽然主要用于静态分析，但其测试工程实践值得学习。

**测试实践亮点**

- 使用 OCaml 实现，自带严格的类型安全
- 大量回归测试确保改动正确性
- 性能测试确保大规模代码库的可用性

**标签**

`#static-analysis` `#type-checking` `#python` `#facebook` `#performance`

---

## Google

### google/googletest

> **仓库**: [https://github.com/google/googletest](https://github.com/google/googletest)
>
> **Stars**: ![GitHub Repo stars](https://img.shields.io/github/stars/google/googletest?style=social)
>
> **语言**: C++

**项目简介**

Google 的 C++ 测试框架，行业标准。

**测试实践亮点**

| 实践 | 说明 |
|-----|------|
| **参数化测试** | 一套测试逻辑，多组输入数据 |
| **Death 测试** | 断言异常和崩溃行为 |
| **Mock 支持** | gMock 提供强大的 mock 能力 |
| **XML 报告** | 与 CI 系统无缝集成 |

**技术栈**

- C++11 及以上
- 跨平台支持 (Windows, Linux, macOS)

**可学习之处**

- C++ 测试的最佳实践
- Mock 对象的设计和使用
- 大规模 C++ 项目的测试组织

**标签**

`#cpp` `#unit-testing` `#mocking` `#google` `#industry-standard`

---

### google/guice

> **仓库**: [https://github.com/google/guice](https://github.com/google/guice)
>
> **Stars**: ![GitHub Repo stars](https://img.shields.io/github/stars/google/guice?style=social)
>
> **语言**: Java

**项目简介**

Google 的轻量级依赖注入框架，通过依赖注入使代码更易于测试。

**测试实践亮点**

- 通过接口和依赖注入实现可测试设计
- 提供 TestModule 用于测试环境配置
- 大量单元测试示例

**标签**

`#java` `#dependency-injection` `#testing-patterns` `#google`

---

## Microsoft

### microsoft/Playwright

> **仓库**: [https://github.com/microsoft/playwright](https://github.com/microsoft/playwright)
>
> **Stars**: ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/playwright?style=social)
>
> **语言**: TypeScript

**项目简介**

现代跨浏览器端到端测试框架。

**测试实践亮点**

| 实践 | 说明 |
|-----|------|
| **自动等待** | 消除 flaky tests |
| **Trace Viewer** | 完整的测试执行回放 |
| **Multi-tab** | 测试多标签页场景 |
| **Network Mock** | API 测试和 mock |

**可学习之处**

- 现代测试框架的设计理念
- 如何消除 flaky tests
- 调试工具的设计

**标签**

`#e2e-testing` `#web-testing` `#typescript` `#microsoft` `#modern`

---

## Netflix

### Netflix/Testflix

> **仓库**: [内部项目，参考其技术博客](https://netflixtechblog.com/)

**测试实践亮点**

- **Chaos Engineering**: 混沌工程测试系统韧性
- **Fault Injection**: 故障注入测试
- **Canary Analysis**: 金丝雀发布验证

**可学习之处**

- 大规模微服务测试策略
- 混沌工程的实施方法
- 生产环境测试实践

**标签**

`#chaos-engineering` `#resilience` `#microservices` `#netflix` `#production`

---

## Airbnb

### Airbnb/mv3

> **仓库**: [内部实践]

**测试实践亮点**

- **Snapshot Testing**: React 组件快照测试
- **Visual Regression**: 视觉回归测试
- **Jest 集成**: 大规模 Jest 测试套件优化

**可学习之处**

- 前端测试的最佳实践
- 视觉测试的实施方案
- 测试性能优化

**标签**

`#frontend` `#react` `#visual-testing` `#airbnb` `#snapshot`

---

## 贡献

如果你知道其他值得学习的企业测试实践，欢迎提交 PR！
