# 大模型测试

LLM 应用的测试方法、工具和最佳实践

---

## 测试框架与工具

### Promptfoo

> **官网**: [https://promptfoo.dev/](https://promptfoo.dev/)
>
> **GitHub**: [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo)

| 属性 | 说明 |
|-----|------|
| **类型** | LLM 测试评估框架 |
| **主要功能** | Prompt 测试、模型对比、红队测试 |
| **GitHub Stars** | ![GitHub Repo stars](https://img.shields.io/github/stars/promptfoo/promptfoo?style=social) |
| **许可证** | MIT |

**特性**

- 支持 OpenAI, Anthropic, 本地模型等
- 可视化测试结果对比
- CI/CD 集成
- 红队测试模板

**适用场景**

- Prompt 工程验证
- 模型选型对比
- 回归测试

**标签**

`#llm-testing` `#prompt-engineering` `#evaluation` `#red-teaming`

---

### Giskard

> **官网**: [https://www.giskard.ai/](https://www.giskard.ai/)
>
> **GitHub**: [Giskard-AI/giskard](https://github.com/Giskard-AI/giskard)

| 属性 | 说明 |
|-----|------|
| **类型** | AI 模型测试平台 |
| **主要功能** | 自动化测试、漏洞扫描、性能监控 |
| **GitHub Stars** | ![GitHub Repo stars](https://img.shields.io/github/stars/Giskard-AI/giskard?style=social) |

**特性**

- 自动发现模型缺陷
- 数据泄露检测
- 偏见和公平性测试
- 与 MLflow 集成

**标签**

`#llm-testing` `#ml-testing` `#vulnerability-scanning` `#monitoring`

---

## 测试方法分类

| 测试类型 | 描述 | 工具 |
|---------|------|------|
| **功能性测试** | 验证模型输出正确性 | Promptfoo, LangSmith |
| **安全性测试** | Prompt 注入、数据泄露 | Giskard, Lakera Gandalf |
| **公平性测试** | 检测偏见和歧视 | Fairlearn, AIF360 |
| **性能测试** | 响应时间、吞吐量 | Locust, k6 |
| **幻觉检测** | 事实一致性验证 | RAGAS, TruLens |

---

## 资源链接

- [LLM Testing 论文](papers/README.md#llm-testing)
- [Prompt Engineering 指南](https://platform.openai.com/docs/prompt-engineering)
- [Red Teaming 手册](https://github.com/Giskard-AI/giskard)

---

## 贡献

欢迎提交 LLM 测试相关的工具和方法！
