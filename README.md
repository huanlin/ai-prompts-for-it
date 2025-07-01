# AI Prompts for IT

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](CONTRIBUTING.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A curated collection of AI prompts specifically for IT professionals, including developers, DevOps engineers, technical writers, and system administrators.

> Chinese: 此 repo 是用來蒐集供 IT 人員（包括開發人員、DevOps 工程師、技術文件撰寫人員和系統管理員）使用的 AI 提示。

## 📋 Table of Contents

- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Quick Start Examples](#quick-start-examples)
- [Prompt Categories](#prompt-categories)
- [Contributing](#contributing)
- [Best Practices](#best-practices)
- [License](#license)

## Repository Structure

```text
.
├── devops/
├── programming/
├── writing/
├── prompt-template.md
└── prompt-template.zh-TW.md
```

| Folder/File Name              | Description                                       |
|-------------------------------|----------------------------------------------------------|
| `devops/`                     | 用於基礎架構、部署和維運任務的提示。                   |
| `programming/`                | 用於軟體開發任務的提示，包括程式碼審查、偵錯、重構和測試。 |
| `writing/`                    | 用於技術寫作、文件和內容創作的提示。                   |
| `prompt-template.md`          | 用於建立新提示的範本和指南（英文版）。                 |
| `prompt-template.zh-TW.md`    | 用於建立新提示的範本和指南（中文版）。                  |

## Getting Started

1. **Browse the category folders** to find prompts relevant to your task
2. **Copy the prompt** that best matches your needs
3. **Customize** the prompt with your specific context
4. **Use with your preferred AI assistant** (Gemini CLI, ChatGPT, Claude, etc.)

As an example, for code review, you might use:

```text
Analyze the following code for potential issues, security vulnerabilities, and improvement opportunities. Focus on:

- Code quality and readability
- Performance optimizations
- Security best practices
- Error handling
- Documentation completeness

[Your code here]
```

Chinese version:

```text
分析以下程式碼，找出潛在問題、安全漏洞和改進機會。請專注於：

- 程式碼品質與可讀性
- 效能最佳化
- 安全最佳實踐
- 錯誤處理
- 文件完整性

[此處貼上您的程式碼]
```

## Use Cases

### Programming (程式設計)

| English                             | Chinese      |
| ----------------------------------- | --------- |
| **Debugging and troubleshooting**   | 偵錯與疑難排解   |
| **Refactoring and optimizing code** | 程式碼重構與最佳化 |
| **Generating and validating tests** | 測試生成與驗證   |
| **Reviewing architectural design**  | 架構設計審查    |
| **Reviewing and analyzing code**    | 程式碼審查與分析  |

### Technical Writing (技術寫作)

| English                                | Chinese              |
|----------------------------------------|------------------------|
| Generating documentation               | 文件產生               |
| Creating API documentation             | API 文件               |
| Writing technical blog posts           | 技術部落格文章         |
| Creating README files                  | README 檔案建立         |
| Writing user guides and tutorials      | 使用者指南與教學       |

### DevOps 與基礎架構

| English                               | Chinese           |
|---------------------------------------|--------------------|
| Automating deployment                 | 部署自動化         |
| Managing infrastructure as code       | 基礎架構即程式碼   |
| Setting up monitoring and alerts      | 監控與警報         |
| Optimizing performance                | 效能最佳化         |
| Conducting security assessments       | 安全性評估         |

## Contributing

Here's how you can help:

1. **Fork** this repository
2. **Create** a new branch for your prompts
3. **Add** your prompts following our [template](prompts/templates/prompt-template.md)
4. **Test** your prompts with different AI assistants
5. **Submit** a pull request with a clear description

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

## Best Practices (最佳實踐)

### Writing Effective Prompts

1. **Be Specific**: Clearly define what you want the AI to do
2. **Provide Context**: Include relevant background information
3. **Set Constraints**: Specify format, length, or style requirements
4. **Use Examples**: Show the desired output format when possible
5. **Iterate**: Refine prompts based on results

### Using AI Assistants Effectively

- **Start Simple**: Begin with basic prompts and add complexity as needed
- **Provide Feedback**: Use follow-up prompts to refine results
- **Verify Output**: Always review and validate AI-generated content
- **Combine Tools**: Use AI alongside your existing development tools

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

- **Issues**: Report bugs or request features via [GitHub Issues](../../issues)
- **Discussions**: Join conversations in [GitHub Discussions](../../discussions)
- **Contributing**: See our [Contributing Guide](CONTRIBUTING.md)

---

*Help us grow this collection by contributing your most effective AI prompts!*

## Related Resources

- [Main README](../README.md) - Project overview and getting started
- [Contributing Guide](../CONTRIBUTING.md) - How to contribute prompts
- [Prompt Engineering Guide](https://www.promptingguide.ai/) - Learn prompt engineering best practices
- [Gemini CLI Documentation](https://ai.google.dev/gemini-api/docs/cli)
- [OpenAI Best Practices](https://platform.openai.com/docs/guides/prompt-engineering)

---

**Need help?** Open an issue or start a discussion in the main repository.
