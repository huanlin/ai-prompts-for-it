# .NET

## 描述

針對 .NET (C#) 程式設計的提示詞。

## 提示

在使用以下各個提示之前，建議先用 [analyze-project](analyze-project.zh-TW.md) 裡面的提示詞來讓 AI 替你的專案進行程式架構的分析與總結。然後，從 AI 總結的輸出結果當中，再逐條針對個別改善建議對 AI agent 提出具體的問題。

以下是幾個常用的提示，可直接複製或稍加修改後餵給 AI agent。

### CI/CD pipeline

```text
建立 GitHub Actions workflow 來建置和發布此專案。
```

使用 MinVer：

```text
使用 MinVer 套件來自動管理此專案的建置與發布時的版本編號，並且視需要修改 GitHub Actions workflow。
```

### Package management

使用 Central Package Management：

```text
使用 Central Package Management (CPM) 來統一管理相依套件的版本。
```

> See also: [Central Package Management (CPM)](https://learn.microsoft.com/en-us/nuget/consume-packages/central-package-management)

找出未使用的 NuGet 套件：

```text
分析此專案，找出可能未被使用到的 NuGet 套件並列出清單。
```

### Code readability

File-scoped namespaces:

```text
轉換所有 C# 檔案為 file-scoped namespaces。
```

重構方法：

```text
重構 [檔案路徑] 中的 [方法名稱] 方法，以提高可讀性和降低圈複雜度 (cyclomatic complexity)。
```

格式化程式碼：

```text
執行 dotnet format 命令來自動化程式碼排版，使其風格保持一致。
```

產生註解：

```text
為 [檔案路徑] 內的 [類別名稱] 中所有 public 方法和屬性產生 XML 文件註解 (XML documentation comments)。
```

### Unit tests

```text
為此專案加入單元測試。
```

為特定方法產生單元測試：

```text
閱讀 [檔案路徑] 中的 [類別名稱] 類別，並為 [方法名稱] 方法編寫一個 xUnit 或 NUnit 的單元測試檔案。
```

### Optimizations

使用 `async/await`：

```text
分析 [檔案路徑]，將同步的 I/O 操作 (如 File.ReadAllText, HttpClient.GetAsync().Result) 改為非同步的 async/await 模式。
```

使用 `StringBuilder`：

```text
找出 [檔案路徑] 中在迴圈內使用 + 或 += 進行字串串接的地方，並將其重構為使用 StringBuilder。
```

### Best practices

啟用 Nullable 參考型別：

```text
在 [專案檔.csproj] 中啟用可為 Null 參考型別 (Nullable Reference Types)，然後修復因此產生的編譯警告。
```

## 已測試平台

- [X] Gemini CLI
- [ ] ChatGPT
- [ ] Claude
- [ ] 其他：___________

