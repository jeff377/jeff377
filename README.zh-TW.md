# 嗨，我是 Jeff 👋

[English](https://github.com/jeff377) | **繁體中文**

**軟體架構師 · .NET** · 台灣台北

我設計並打造 .NET 企業應用框架，也就是 ERP 與企業系統團隊會在上面開發好幾年的那種基礎設施。
我也會把自己依賴的開源工具中遇到的問題修好、回饋上游，範圍包含 UI 框架、元件庫與資料庫工具。

- 🏗️ **[Polhem](https://github.com/polhem-dev/polhem)** 作者：定義驅動的 .NET 框架，同一套企業應用可在桌面、瀏覽器、iOS 與 Android 上執行
- 🔧 在 **dbx**、**Avalonia**、**MudBlazor**、**Fluent UI Blazor**、**MiniPdf** 都有被合併的貢獻
- ✍️ 在 [HackMD](https://hackmd.io/@jeff377) 撰寫架構設計與 AI 輔助開發的文章

---

## 🔭 主要專案

### [Polhem Framework](https://github.com/polhem-dev/polhem)

模組化的 .NET 框架，用來打造**定義驅動**（definition-driven）的企業應用系統，是 Bee.NET 的後繼專案。

- **單一權威來源**：由 `FormSchema` 同時驅動 UI 版面、資料庫結構與驗證規則
- **多種用戶端，同一套 API**：Avalonia（桌面、瀏覽器、iOS、Android）、Blazor Server 與 JavaScript 用戶端，都透過 JSON-RPC 2.0 與伺服器溝通
- **多資料庫支援**：SQL Server、PostgreSQL、MySQL、Oracle、SQLite
- **建置時強制框架慣例**：套件內附 Roslyn analyzer，把框架規則轉成建置診斷
- **發佈於 NuGet**，每次變更都經過 CI、測試覆蓋率與靜態分析

實際範例：[Polhem.Northwind](https://github.com/polhem-dev/polhem-northwind)，以經典的 Northwind 案例示範，幾乎完全由定義檔構成。

**[polhem-dev](https://github.com/polhem-dev) 的其他專案：**
[Polhem.OAuth2](https://github.com/polhem-dev/polhem-oauth2)（Google、Facebook、LINE、Entra ID、Auth0、Okta 的 OAuth2 登入）·
[Polhem.JsonRpc](https://github.com/polhem-dev/polhem-jsonrpc)（基於 System.Text.Json 的 JSON-RPC 2.0）·
[polhem-connector-js](https://github.com/polhem-dev/polhem-connector-js)（TypeScript 用戶端）

---

## 🤝 開源貢獻

| 專案 | 貢獻方向 | 範例 |
|------|---------|------|
| [dbx](https://github.com/t8y2/dbx) | Oracle、PostgreSQL、MySQL、SQL Server 的資料庫行為正確性 | [在 SQL 編輯器回報 PL/SQL 編譯錯誤](https://github.com/t8y2/dbx/pull/13996) · [停止查詢時取消執行中的陳述式](https://github.com/t8y2/dbx/pull/11890) |
| [Avalonia](https://github.com/AvaloniaUI/Avalonia) | macOS 無障礙與自動化 | [遮罩 TextBox 的內容不再透過 automation peer 外洩](https://github.com/AvaloniaUI/Avalonia/pull/22458) |
| [MudBlazor](https://github.com/MudBlazor/MudBlazor) | 元件行為 | [MudDatePicker：月份與年份檢視在點選的欄位開啟](https://github.com/MudBlazor/MudBlazor/pull/14125) |
| [Fluent UI Blazor](https://github.com/microsoft/fluentui-blazor) | 無障礙 | [讓輔助技術讀得到日曆的選取與停用狀態](https://github.com/microsoft/fluentui-blazor/pull/5614) |
| [MiniPdf](https://github.com/mini-software/MiniPdf) | 字型管理 API | [新增 `MiniPdf.ClearRegisteredFonts`](https://github.com/mini-software/MiniPdf/pull/166) |

→ [我所有被合併的 PR](https://github.com/search?q=is%3Apr+author%3Ajeff377+is%3Amerged+-user%3Ajeff377+-org%3Apolhem-dev&type=pullrequests)

---

## 🛠️ 技術棧

**語言與平台：** C# · .NET · ASP.NET Core · Blazor · Avalonia · TypeScript  
**資料庫：** SQL Server · PostgreSQL · MySQL · Oracle · SQLite  
**架構：** N-Tier · Clean Architecture · MVVM · Definition-Driven Architecture · JSON-RPC  
**領域：** 企業資訊系統 · ERP · Business Object 設計

---

## 📬 聯絡方式

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jeff-tsai-9476151a0/)
[![HackMD](https://img.shields.io/badge/HackMD-000000?style=flat&logo=hackmd&logoColor=white)](https://hackmd.io/@jeff377)
[![NuGet](https://img.shields.io/badge/NuGet-004880?style=flat&logo=nuget&logoColor=white)](https://www.nuget.org/profiles/Polhem)
