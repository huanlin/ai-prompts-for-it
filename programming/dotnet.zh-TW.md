# .NET

## 描述

針對 .NET (C#) 程式設計的提示詞。

## 提示

在使用以下各個提示之前，建議先用 [analyze-project](analyze-project.zh-TW.md) 裡面的提示詞來讓 AI 替你的專案進行程式架構的分析與總結。然後，從 AI 總結的輸出結果當中，再逐條針對個別改善建議對 AI agent 提出具體的問題。

以下是幾個常用的提示，可直接複製或稍加修改後餵給 AI agent。

### File-scoped namespaces

```text
轉換所有 C# 檔案為 file-scoped namespaces。
```

### Use MinVer

```text
使用 MinVer 套件來自動管理此專案的建置與發布時的版本編號。
```

### Central Package Management

```text
使用 Central Package Management (CPM) 來統一管理相依套件的版本。
```

> See also: [Central Package Management (CPM)](https://learn.microsoft.com/en-us/nuget/consume-packages/central-package-management)

### Unit tests

```text
加入單元測試。
```

### CI/CD pipeline

```text
建立 GitHub Actions workflow 來建置和發布此專案。
```

## 已測試平台

- [X] Gemini CLI
- [ ] ChatGPT
- [ ] Claude
- [ ] 其他：___________

