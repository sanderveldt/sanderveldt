# Hi, I'm Sander 👋

Self-taught **.NET developer** from the Netherlands. I can work full-stack but my focus is on **backend**.

🔍 **Currently looking for:** junior .NET backend or backend-focused full-stack roles in the Netherlands.

## 🛠️ Tech stack
- **Backend:** C#, .NET 10, ASP.NET Core Minimal APIs, Entity Framework Core, ASP.NET Core Identity, FluentValidation
- **Data:** SQL, PostgreSQL, SQLite
- **Frontend:** WPF (MVVM, CommunityToolkit.Mvvm), HTML, CSS
- **Testing:** xUnit, Testcontainers
- **Tools:** Git, Docker Compose


- **Learning:** Typescript and React

## 📌 Featured project

### [ProcHub](https://github.com/sanderveldt/ProcHub): Procurement & Supplier tracking
An end-to-end system for tracking purchase orders through 13 statuses, from draft to delivery to close and their pending payments. Made with a .NET 10 API and a WPF desktop client.

- **Domain-driven design:** Rich domain model with private setters. Every state change goes through a method that enforces its business rules.
- **Layered architecture:** Domain → Application (commands/queries + FluentValidation) → Infrastructure → API, with dependencies pointing inward.
- **Optimistic concurrency** On frequently edited records, using PostgreSQL's `xmin` row version.
- **Authentication:** ASP.NET Core Identity with bearer tokens, role-based authorization (User / SuperUser / Admin) and account lockout.
- **API:** Minimal API endpoints with Group routing per feature, Global exception handler middleware with logging, separate client side DTO's.
- **Tests:** xUnit domain tests, plus integration tests against a real PostgreSQL in Testcontainers.

## 🤖 How I use AI
Not anti-AI, but critical of it's output. Any code created with agentic assistance is thoroughly reviewed and understood before committed. **NO** vibecoding.

## 🌍 Languages
Dutch (native) · English (fluent)

## 📫 Contact
[LinkedIn](https://www.linkedin.com/in/sander-veldt/) · [Email](sanderveldt98@hotmail.com)
