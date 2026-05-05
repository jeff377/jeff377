# Hi, I'm Jeff 👋

**Software Architect** · Taipei, Taiwan

I specialize in enterprise application architecture — designing systems that are modular, maintainable, and built to scale. My focus is on applying **N-Tier + Clean Architecture + MVVM** patterns to real-world ERP and business information systems.

---

## 🔭 Featured Project

### [Bee.NET Framework](https://github.com/jeff377/bee-library)

A **Definition-Driven Architecture** for .NET enterprise app development — a single schema drives UI, DB, and validation.

- **Single source of truth** — `FormSchema` drives UI layout, database schema, and validation simultaneously
- **Hybrid architecture** — Layered separation with MVVM presentation, tuned for ERP transactional flows
- **Cross-platform** — Core packages target `netstandard2.0; net10.0`
- **Modular** — Decoupled assemblies for core utilities, data access, business logic, and API hosting

```
        Bee.Core · Bee.Definition · Bee.Api.Contracts
                          │
          ┌───────────────┴───────────────┐
        Server                          Client
          │                                │
   Bee.Db · Bee.Repository           Bee.Api.Client
          │
     Bee.Business
          │
   Bee.Api.AspNetCore
     (JSON-RPC 2.0)
```

---

## 🛠️ Tech Stack

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![JSON-RPC](https://img.shields.io/badge/JSON--RPC_2.0-gray?style=flat)
![NuGet](https://img.shields.io/badge/NuGet-004880?style=flat&logo=nuget&logoColor=white)

**Architecture Patterns:** N-Tier · Clean Architecture · MVVM · Definition-Driven Architecture  
**Domain:** Enterprise Information Systems · ERP · Business Object Design

---

## 📝 Technical Notes

I share hands-on architecture experience and implementation notes on HackMD:

👉 [hackmd.io/@jeff377](https://hackmd.io/@jeff377)

Topics include .NET architecture design, enterprise system patterns, and Bee.NET framework deep dives.

---

## 📬 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jeff-tsai-9476151a0/)
[![HackMD](https://img.shields.io/badge/HackMD-000000?style=flat&logo=hackmd&logoColor=white)](https://hackmd.io/@jeff377)
[![NuGet](https://img.shields.io/badge/NuGet-004880?style=flat&logo=nuget&logoColor=white)](https://www.nuget.org/profiles/jeff377)
