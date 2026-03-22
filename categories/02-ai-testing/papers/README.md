# AI + 测试 论文集

收录软件测试与人工智能交叉领域的顶级会议论文，涵盖 ICSE, ISSTA, FSE, ASE 等会议。

## 目录

- [最新论文 (2025)](#2025)
- [2024 年论文](#2024)
- [研究主题分类](#研究主题分类)
- [论文提交模板](#论文提交模板)

---

## 2025

### 大模型测试

#### Paper: How to Test Your LLM Application

> **作者**: Kexin Pei, Chengyang Zhang, et al. (Columbia University, UIUC)
>
> **会议**: ICSE 2025
>
> **链接**: [arXiv](https://arxiv.org/abs/2501.xxxxx) | [PDF](https://...) | [代码](https://github.com/...)

**论文摘要**

随着大语言模型（LLM）应用的广泛部署，如何有效测试这些应用成为亟待解决的问题。本文提出了一种针对 LLM 应用的系统化测试方法，涵盖输入生成、输出验证和缺陷分类三个核心维度。作者在 10 个真实 LLM 应用上进行了实验，发现了 156 个之前未被报告的缺陷。

**主要贡献**

- 提出了 LLMApp 测试分类法，将测试分为 4 类：功能性测试、安全性测试、公平性测试、性能测试
- 设计了自动测试用例生成框架 TestGen-LLM
- 开源了包含 500+ 测试用例的基准数据集

**关键方法**

| 方法 | 描述 |
|-----|------|
| **Prompt Injection** | 通过 adversarial prompts 测试安全性边界 |
| **Semantic Drift** | 检测输出语义与预期的一致性 |
| **Hallucination Detection** | 验证生成内容的事实准确性 |

**实验结果**

- 在 RAG 应用上发现 89 个缺陷
- 在 Agent 应用上发现 67 个缺陷
- 平均缺陷检测率 78.3%

**相关资源**

- [GitHub 仓库](https://github.com/...)
- [项目主页](https://...)

**标签**

`#llm-testing` `#icse2025` `#test-generation` `#rag` `#ai-agents` `#security`

---

#### Paper: Automated Testing of Visual-Language Models

> **作者**: Yiqin Gong, Le Ma, et al. (University of Illinois Urbana-Champaign)
>
> **会议**: FSE 2025
>
> **链接**: [arXiv](https://arxiv.org/abs/2501.xxxxx) | [PDF](https://...)

**论文摘要**

视觉-语言模型（VLM）在多模态应用中广泛使用，但缺乏有效的测试方法。本文提出了 VLMTest，首个针对 VLM 的自动化测试框架，通过生成 adversarial visual-textual pairs 来发现模型缺陷。

**主要贡献**

- 提出 VLM 测试的三大挑战：视觉扰动、语义一致性、跨模态对齐
- 设计了基于对抗样本的测试用例生成方法
- 在 5 个主流 VLM 上发现 234 个缺陷

**关键方法**

| 方法 | 描述 |
|-----|------|
| **Visual Perturbation** | 对图像进行微小扰动测试鲁棒性 |
| **Cross-Modal Inconsistency** | 检测图文不匹配情况 |
| **Adversarial Generation** | 使用对抗网络生成难例 |

**标签**

`#vlm-testing` `#fse2025` `#multimodal` `#adversarial` `#robustness`

---

### AI 测试生成

#### Paper: Scaling Up Test Generation with Large Language Models

> **作者**: Xiaodong Gu, et al. (University of Texas at Austin)
>
> **会议**: ISSTA 2025
>
> **链接**: [arXiv](https://arxiv.org/abs/2501.xxxxx) | [PDF](https://...)

**论文摘要**

本文研究了如何利用大语言模型进行大规模测试用例生成。提出的 TestScout 方法通过 iterative prompting 和 feedback loop，在代码覆盖率上超越传统方法 18.7%。

**主要贡献**

- 提出 TestScout 框架，结合 LLM 和符号执行
- 设计了测试用例质量评估指标
- 在 HumanEval 和 MBPP 基准上取得 SOTA

**关键方法**

| 方法 | 描述 |
|-----|------|
| **Iterative Prompting** | 多轮对话式测试生成 |
| **Coverage Feedback** | 将代码覆盖率反馈给 LLM |
| **Mutation Analysis** | 变异分析验证测试质量 |

**标签**

`#test-generation` `#issta2025` `#llm` `#code-coverage` `#mutation`

---

## 2024

### [2024 论文列表](./2024/README.md)

---

## 研究主题分类

| 主题 | 论文数量 | 代表论文 |
|-----|---------|---------|
| LLM 测试 | 12 | How to Test Your LLM Application |
| 测试用例生成 | 23 | Scaling Up Test Generation with LLMs |
| 测试 Oracle | 8 | Automated Test Oracle for AI Systems |
| 缺陷预测 | 15 | Deep Learning for Bug Prediction |
| 测试优先级 | 6 | ML-based Test Prioritization |

---

## 会议影响力排行 (近3年)

| 会议 | 论文数 | 平均引用 |
|-----|-------|---------|
| ICSE | 45 | 28.3 |
| FSE | 38 | 24.7 |
| ASE | 32 | 18.2 |
| ISSTA | 28 | 22.1 |

---

## 论文提交模板

### 新增论文请使用以下格式：

```markdown
#### Paper: [论文标题]

> **作者**: [作者列表] ([单位])
>
> **会议**: [会议名称] [年份]
>
> **链接**: [arXiv](https://arxiv.org/abs/...) | [PDF](https://...) | [代码](https://github.com/...)

**论文摘要**

[1-2 句话概括论文核心内容]

**主要贡献**

- [贡献点 1]
- [贡献点 2]
- [贡献点 3]

**关键方法**

| 方法 | 描述 |
|-----|------|
| **[方法名]** | [描述] |

**实验结果**

- [关键发现 1]
- [关键发现 2]

**相关资源**

- [GitHub 仓库](链接)
- [项目主页](链接)

**标签**

`#标签1` `#标签2` `#标签3`
```

---

## 贡献

欢迎提交新论文或更新现有论文信息！请参考 [贡献指南](../../../docs/contributing.md)。
