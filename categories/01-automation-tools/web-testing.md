# Web 测试工具

Web 端自动化测试工具和框架

| 工具名称 | 语言 | Stars | 适用场景 |
|---------|------|-------|---------|
| [Playwright](https://playwright.dev/) | TypeScript/JS/Python/Java/.NET | ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/playwright?style=social) | 现代 Web 应用测试 |
| [Cypress](https://www.cypress.io/) | JavaScript/TypeScript | ![GitHub Repo stars](https://img.shields.io/github/stars/cypress-io/cypress?style=social) | 前端开发者友好的测试框架 |
| [Selenium](https://www.selenium.dev/) | 多语言 | ![GitHub Repo stars](https://img.shields.io/github/stores/SeleniumHQ/selenium?style=social) | 传统 Web 自动化 |

---

## 推荐工具详情

### Playwright

> **官方文档**: [https://playwright.dev/](https://playwright.dev/)

**基本信息**

| 属性 | 说明 |
|-----|------|
| **维护者** | Microsoft |
| **首发时间** | 2020 |
| **主要语言** | TypeScript, JavaScript, Python, Java, .NET |
| **许可证** | Apache-2.0 |
| **GitHub Stars** | [61k+](https://github.com/microsoft/playwright) |
| **活跃度** | ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/microsoft/playwright) |

**特性**

- 跨浏览器支持 (Chromium, Firefox, WebKit)
- 自动等待机制，减少 flaky tests
- 强大的调试工具 (Trace Viewer, Codegen)
- 并行执行，快速测试
- 支持 API 测试和 Mobile 模拟

**适用场景**

- 现代 Web 应用 E2E 测试
- 需要快速反馈的 CI/CD 流水线
- 复杂交互的 SPA 应用测试

**学习资源**

- [官方文档](https://playwright.dev/docs/intro)
- [Best Practices](https://playwright.dev/docs/best-practices)

**标签**

`#web-testing` `#e2e` `#cross-browser` `#microsoft` `#typescript`

---

### Cypress

> **官方文档**: [https://docs.cypress.io/](https://docs.cypress.io/)

**基本信息**

| 属性 | 说明 |
|-----|------|
| **维护者** | Cypress.io (now SmartBear) |
| **首发时间** | 2017 |
| **主要语言** | JavaScript, TypeScript |
| **许可证** | MIT |
| **GitHub Stars** | [46k+](https://github.com/cypress-io/cypress) |
| **活跃度** | ![GitHub commit activity](https://img.shields.io/github/commit-activity/c/cypress-io/cypress) |

**特性**

- 运行在浏览器内，实时重载
- 时间旅行调试
- 自动等待，无需手动 sleep
- 网络请求控制和 stub
- 截图和视频录制

**适用场景**

- 前端开发者的自测工具
- React/Vue/Angular 应用测试
- 需要可视化调试的场景

**标签**

`#web-testing` `#e2e` `#javascript` `#developer-friendly` `#debugging`

---

### Selenium

> **官方文档**: [https://www.selenium.dev/documentation/](https://www.selenium.dev/documentation/)

**基本信息**

| 属性 | 说明 |
|-----|------|
| **维护者** | Selenium Community |
| **首发时间** | 2004 |
| **主要语言** | Java, Python, C#, JavaScript, Ruby 等 |
| **许可证** | Apache-2.0 |
| **GitHub Stars** | [29k+](https://github.com/SeleniumHQ/selenium) |
| **活跃度** | ![GitHub commit activity](https://img.shields.io/github/commit-activity/s/SeleniumHQ/selenium) |

**特性**

- 业界标准，生态最成熟
- 支持所有主流浏览器
- 多语言支持
- Selenium Grid 并行执行
- 与大量工具集成

**适用场景**

- 大型企业级测试框架
- 需要跨平台的测试解决方案
- 遗留系统维护

**标签**

`#web-testing` `#e2e` `#enterprise` `#legacy` `#cross-platform`

---

## 工具对比

| 特性 | Playwright | Cypress | Selenium |
|-----|-----------|---------|----------|
| 跨浏览器 | ✅ 全部 | ✅ Chrome-family | ✅ 全部 |
| 多语言 | ✅ 5+ | ❌ 仅 JS | ✅ 10+ |
| 速度 | ⚡ 快 | ⚡ 快 | 🐢 较慢 |
| 稳定性 | ✅ 高 | ✅ 高 | ⚠️ 中等 |
| 学习曲线 | 📈 中等 | 📉 低 | 📈 中高 |
| 调试体验 | ✅ 优秀 | ✅ 优秀 | ⚠️ 一般 |

---

## 推荐阅读

- [Playwright vs Cypress vs Selenium](https://www.headspin.io/blog/playwright-vs-cypress-vs-selenium)
- [Choosing the Right Web Testing Tool](https://testautomationu.applitools.com/)

---

## 贡献

如果你使用过其他优秀的 Web 测试工具，欢迎提交 PR 添加！
