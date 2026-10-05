# 嗨，我是 Jeff 👋

[English](https://github.com/jeff377) | **繁體中文**

**軟體架構師** · 台灣台北

專注於企業應用系統架構，設計模組化、易維護、可擴展的系統。主要將 **N-Tier + Clean Architecture + MVVM** 應用在實際的 ERP 與企業資訊系統上。

---

## 🔭 主要專案

### [Polhem Framework](https://github.com/polhem-dev/polhem)

模組化的 .NET 框架，用來打造**定義驅動**（definition-driven）的企業應用系統，是 Bee.NET 的後繼專案。

- **單一權威來源**：由 `FormSchema` 同時驅動 UI 版面、資料庫結構與驗證規則
- **混合式架構**：N-Tier + Clean Architecture + MVVM，針對 ERP 交易流程調校
- **多種用戶端，同一套 API**：Avalonia（桌面、瀏覽器、iOS、Android）、Blazor Server 與 JavaScript 用戶端，都透過 JSON-RPC 2.0 與伺服器溝通
- **多資料庫支援**：SQL Server、PostgreSQL、MySQL、Oracle、SQLite
- **建置時強制框架慣例**：套件內附 Roslyn analyzer，把框架規則轉成建置診斷

實際範例：[Polhem.Northwind](https://github.com/polhem-dev/polhem-northwind)，以經典的 Northwind 案例示範，幾乎完全由定義檔構成，可在桌面、瀏覽器、iOS 與 Android 上執行。

### [polhem-dev](https://github.com/polhem-dev) 的其他專案

- **[Polhem.JsonRpc](https://github.com/polhem-dev/polhem-jsonrpc)**：基於 System.Text.Json 的 .NET JSON-RPC 2.0 實作，含伺服器、ASP.NET Core 端點與用戶端
- **[Polhem.OAuth2](https://github.com/polhem-dev/polhem-oauth2)**：輕量的 .NET OAuth2 登入函式庫（Google、Facebook、LINE、Microsoft Entra ID、Auth0、Okta）
- **[polhem-connector-js](https://github.com/polhem-dev/polhem-connector-js)**：Polhem JSON-RPC API 的 JavaScript / TypeScript 連接器

---

## 🛠️ 技術棧

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![JSON-RPC](https://img.shields.io/badge/JSON--RPC_2.0-gray?style=flat)
![NuGet](https://img.shields.io/badge/NuGet-004880?style=flat&logo=nuget&logoColor=white)

**架構模式：** N-Tier · Clean Architecture · MVVM · Definition-Driven Architecture  
**領域：** 企業資訊系統 · ERP · Business Object 設計

---

## 📝 技術筆記

我在 HackMD 分享架構實務經驗與實作筆記：

👉 [hackmd.io/@jeff377](https://hackmd.io/@jeff377)

主題涵蓋 .NET 架構設計、企業系統設計模式，以及 Polhem 框架的深入解析。

---

## 📬 聯絡方式

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jeff-tsai-9476151a0/)
[![HackMD](https://img.shields.io/badge/HackMD-000000?style=flat&logo=hackmd&logoColor=white)](https://hackmd.io/@jeff377)
[![NuGet](https://img.shields.io/badge/NuGet-004880?style=flat&logo=nuget&logoColor=white)](https://www.nuget.org/profiles/Polhem)
