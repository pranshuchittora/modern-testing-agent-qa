# 贡献指南

感谢你有兴趣为 **awesome-modern-testing** 做出贡献！

## 贡献方式

### 1. 报告问题

如果你发现了错误或有改进建议：

1. 检查 [Issues](https://github.com/your-username/awesome-modern-testing/issues) 是否已有类似问题
2. 如果没有，创建新的 Issue，使用合适的模板：
   - **Bug 报告**: 用于报告错误
   - **资源推荐**: 用于推荐新的工具/论文/仓库
   - **改进建议**: 用于提出改进想法

### 2. 添加新资源

#### 添加开源工具/框架

在对应的分类文件（如 `web-testing.md`）中添加工具信息：

```markdown
### [工具名称](链接)

> **官方文档**: [文档链接](...)

**基本信息**

| 属性 | 说明 |
|-----|------|
| **维护者** | 个人/组织 |
| **首发时间** | 年份 |
| **主要语言** | 编程语言 |
| **许可证** | 开源协议 |
| **GitHub Stars** | [数量](链接) |
| **活跃度** | ![GitHub commit activity](...) |

**特性**

- 特点 1
- 特点 2
- 特点 3

**适用场景**

- 场景 1
- 场景 2

**学习资源**

- [文档 1](链接)
- [文档 2](链接)

**标签**

`#标签1` `#标签2` `#标签3`
```

#### 添加 AI 测试论文

在 `categories/02-ai-testing/papers/README.md` 中添加：

```markdown
#### Paper: [论文标题]

> **作者**: [作者列表] ([单位])
>
> **会议**: [会议名称] [年份]
>
> **链接**: [arXiv](链接) | [PDF](链接) | [代码](链接)

**论文摘要**

[1-2 句话概括论文]

**主要贡献**

- 贡献 1
- 贡献 2

**关键方法**

| 方法 | 描述 |
|-----|------|
| **[方法名]** | [描述] |

**实验结果**

- 发现 1
- 发现 2

**相关资源**

- [GitHub](链接)
- [项目主页](链接)

**标签**

`#标签1` `#标签2` `#标签3`
```

#### 添加优秀仓库

在 `categories/03-awesome-repos/` 对应文件中添加：

```markdown
### [组织名]/[仓库名]

> **仓库**: [GitHub 链接](...)
>
> **Stars**: ![GitHub Repo stars](https://img.shields.io/github/stars/org/repo?style=social)
>
> **语言**: 编程语言

**项目简介**

[简要描述项目]

**测试实践亮点**

| 实践 | 说明 |
|-----|------|
| **实践名** | 描述 |

**技术栈**

- 技术列表

**可学习之处**

- 可学习点 1
- 可学习点 2

**标签**

`#标签1` `#标签2` `#标签3`
```

### 3. 改进现有内容

- 修正错误信息
- 更新过时的链接或数据
- 添加使用经验或最佳实践
- 翻译文档

### 4. 审阅 PR

帮助审核其他人的贡献，检查：
- 格式是否正确
- 内容是否准确
- 链接是否有效
- 是否符合资源筛选标准

---

## 资源筛选标准

添加的资源需满足：

| 标准 | 要求 |
|-----|------|
| **活跃度** | 近 6 个月有更新或有维护者响应 |
| **质量** | 有清晰文档，社区有正面反馈 |
| **影响力** | Stars > 100 或有业界应用案例 |
| **相关性** | 与软件测试强相关 |
| **开放性** | 开源或提供免费使用 |

**例外情况**: 对于经典项目（如 Selenium）或重要学术论文，可酌情放宽标准。

---

## 开发流程

### 1. Fork 仓库

```bash
# Fork 后克隆到本地
git clone https://github.com/your-username/awesome-modern-testing.git
cd awesome-modern-testing
```

### 2. 创建分支

```bash
# 使用有意义的分支名
git checkout -b add-playwright-guide
# 或
git checkout -b fix-typo-in-readme
```

### 3. 修改文件

按照上面的格式添加或修改内容。

### 4. 提交更改

```bash
git add .
git commit -m "Add: Playwright 最佳实践指南"
```

**提交消息格式**:

- `Add:` - 添加新内容
- `Fix:` - 修复错误
- `Update:` - 更新现有内容
- `Docs:` - 文档修改

### 5. 推送并创建 PR

```bash
git push origin add-playwright-guide
```

然后在 GitHub 上创建 Pull Request。

---

## PR 检查清单

提交 PR 前请确认：

- [ ] 遵循了内容格式规范
- [ ] 链接都是可访问的
- [ ] 添加了适当的标签
- [ ] 更新了相关索引（如果需要）
- [ ] 提交消息清晰描述了改动
- [ ] 没有引入不必要的格式化改动

---

## 代码规范

### Markdown 格式

- 使用 2 空格缩进
- 列表项之间保留空行
- 链接使用描述性文字
- 表格对齐一致

### 标签规范

使用统一的标签分类：

**工具类型**:
- `#unit-testing` - 单元测试
- `#e2e-testing` - 端到端测试
- `#api-testing` - API 测试
- `#mobile-testing` - 移动端测试
- `#performance-testing` - 性能测试
- `#security-testing` - 安全测试

**编程语言**:
- `#python` `#javascript` `#java` `#go` `#cpp` 等

**会议标签**:
- `#icse2025` `#fse2025` `#issta2025` `#ase2025`

**其他**:
- `#ai` `#llm` `#enterprise` `#opensource`

---

## 行为准则

- 尊重所有贡献者
- 建设性的反馈
- 欢迎新手参与
- 用中文进行讨论

---

## 获得认可

所有贡献者将出现在 [Contributors](https://github.com/your-username/awesome-modern-testing/graphs/contributors) 列表中。

---

## 许可

贡献的内容将继承项目的 MIT 许可证。

---

有问题？请随时 [提 Issue](https://github.com/your-username/awesome-modern-testing/issues) 或在 PR 中提问！
