# 為 IT 人員設計的 AI 提示

[![授權: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![歡迎貢獻](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](CONTRIBUTING.md)
[![歡迎 PR](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

這是一個專為 IT 專業人士（包括開發人員、DevOps 工程師、技術文件撰寫人員和系統管理員）設計的 AI 提示精選集合。這些提示已針對各種 AI 平台（包括 Gemini CLI、ChatGPT、Claude 和其他 AI 助理）進行了最佳化。

## 目錄

- [About](#about)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Quick Start Examples](#quick-start-examples)
- [Prompt Categories](#prompt-categories)
- [Contributing](#contributing)
- [Best Practices](#best-practices)
- [License](#license)

## About

本儲存庫是針對 IT 工作流程量身打造的 AI 提示綜合資源。無論您是在偵錯程式碼、撰寫文件、規劃部署或進行程式碼審查，您都會找到有助於您在日常工作中更有效地利用 AI 的提示。

### 為何使用這些提示？

- **節省時間**：預先製作的提示可減少您構思請求的時間
- **結果一致**：經過充分測試的提示可產生更可靠的輸出
- **最佳實踐**：融入了提示工程的最佳實踐
- **專注於 IT**：專為技術使用案例而設計
- **多平台**：與各種 AI 助理相容

## Repository Structure

```text
.
├── devops/
├── programming/
├── writing/
├── prompt-template.md
└── prompt-template.zh-TW.md
```

- `devops/` - 用於基礎架構、部署和維運任務的提示。
- `programming/` - 用於軟體開發任務的提示，包括程式碼審查、偵錯、重構和測試。
- `writing/` - 用於技術寫作、文件和內容創作的提示。
- `prompt-template.md` - 用於建立新提示的範本和指南（英文版）。
- `prompt-template.zh-TW.md` - 用於建立新提示的範本和指南（中文版）。

## Getting Started

1. **瀏覽分類**以尋找與您任務相關的提示
2. **複製**最符合您需求的提示
3. **客製化**提示，填入您的具體情境
4. **在您偏好的 AI 助理上使用** (Gemini CLI, ChatGPT, Claude 等)

舉例來說，對於程式碼審查，您可以使用以下提示詞：

```text
分析以下程式碼，找出潛在問題、安全漏洞和改進機會。請專注於：

- 程式碼品質與可讀性
- 效能最佳化
- 安全最佳實踐
- 錯誤處理
- 文件完整性

[此處貼上您的程式碼]
```

## Quick Start Examples

### 程式碼審查

使用 `programming/code-review.md` 在合併前取得您程式碼的詳細回饋。

### API 文件

使用 `writing/api-docs-generator.md` 從您的程式碼建立專業的 API 文件。

### 管線最佳化

使用 `devops/ci-cd-pipeline-optimizer.md` 來改善您的 CI/CD 管線效能和可靠性。

## Prompt Categories

### 程式設計

- 程式碼審查與分析
- 偵錯與疑難排解
- 程式碼重構與最佳化
- 測試生成與驗證
- 架構設計審查

### 技術寫作

- 文件產生
- API 文件
- 技術部落格文章
- README 檔案建立
- 使用者指南與教學

### DevOps 與基礎架構

- 部署自動化
- 基礎架構即程式碼
- 監控與警報
- 效能最佳化
- 安全性評估

## Contributing

我們歡迎 IT 社群的貢獻！您可以透過以下方式提供協助：

1. **Fork** 本儲存庫。
2. 為您的提示**建立**一個新的分支。
3. 遵循我們的[範本](prompt-template.md)**新增**您的提示。
4. 使用不同的 AI 助理**測試**您的提示。
5. **提交**一個附有清楚說明的 Pull Request。

### 貢獻指南

- 使用提供的範本以求一致。
- 包含清楚的描述和使用案例。
- 使用至少一個 AI 助理測試提示。
- 遵循既有的目錄結構。
- 在有幫助的情況下提供範例。

詳細指南請參閱 [CONTRIBUTING.zh-TW.md](CONTRIBUTING.zh-TW.md)。

## Best Practices

### 撰寫有效的提示

1. **要具體**：清楚定義您希望 AI 做什麼
2. **提供情境**：包含相關的背景資訊
3. **設定限制**：指定格式、長度或樣式要求
4. **使用範例**：盡可能展示期望的輸出格式
5. **反覆測試**：根據結果調整提示

### 有效地使用 AI 助理

- **從簡單開始**：從基本的提示開始，視需要增加複雜度
- **提供回饋**：使用後續提示來調整結果
- **驗證輸出**：務必審查和驗證 AI 產生的內容
- **結合工具**：將 AI 與您現有的開發工具結合使用

## License

本專案採用 MIT 授權 - 詳情請參閱 [LICENSE](LICENSE) 檔案。

## 🙋‍♂️ 支援

- **問題**：透過 [GitHub Issues](../../issues) 回報錯誤或請求功能
- **討論**：在 [GitHub Discussions](../../discussions) 中加入對話
- **貢獻**：請參閱我們的[貢獻指南](CONTRIBUTING.md)

---

*透過貢獻您最有效的 AI 提示，幫助我們發展這個集合！*

## 🔗 相關資源 {#resources}

- [主 README](README.zh-TW.md) - 專案概覽與入門
- [貢獻指南](CONTRIBUTING.zh-TW.md) - 如何貢獻提示
- [提示工程指南](https://www.promptingguide.ai/) - 學習提示工程最佳實踐
- [Gemini CLI 文件](https://ai.google.dev/gemini-api/docs/cli)
- [OpenAI 最佳實踐](https://platform.openai.com/docs/guides/prompt-engineering)

---

**需要協助嗎？** 在主儲存庫中開啟一個 issue 或開始一個 discussion。
