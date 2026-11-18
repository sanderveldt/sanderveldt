# Hi, I'm Sander

Self-taught **.NET developer** from the Netherlands. I can work full-stack but my focus is on **backend**.

🔍 **Currently looking for:** junior .NET backend or backend-focused full-stack roles in the Netherlands.

## 🛠️ Tech stack
- **Backend:** C#, .NET 10, ASP.NET Core Minimal APIs, Entity Framework Core, ASP.NET Core Identity, FluentValidation
- **Data:** SQL, PostgreSQL, SQLite
- **Frontend:** WPF (MVVM, CommunityToolkit.Mvvm), HTML, CSS
- **Testing:** xUnit, Testcontainers
- **Tools:** Git, Docker


- **Learning:** Typescript and React

## 📌 Featured project

### [ProcHub](https://github.com/sanderveldt/ProcHub): Procurement tracking System
An end-to-end system for managing suppliers, purchase orders, order status and payments.

- **Domain-driven design:** Rich domain model with private setters. Every state change goes through a method that enforces its business rules.
- **Layered architecture:** Separation of concerns; Domain owns business rules, Application coordinates use cases, Infrastructure for persistence and identity services and API exposes endpoints.
- **Request flow:** HTTP request → Authentication and authorization → API endpoint → Application handler → DbContext abstraction → EF Core → PostgreSQL
- **Optimistic concurrency** On frequently edited records, using PostgreSQL's `xmin` row version.
- **Authentication:** ASP.NET Core Identity with bearer tokens, role-based authorization (User / SuperUser / Admin) and account lockout.
- **API:** Minimal API endpoints with endpoint group routing by feature, global exception handler middleware with logging.
- **Tests:** xUnit domain tests, plus integration tests against a real PostgreSQL in Testcontainers.

## 🤖 How I use AI
Not anti-AI, but critical of it's output. Any code created with agentic assistance is thoroughly reviewed and understood before committed. I **DON'T** do vibecoding.

## 🌍 Languages
Dutch (native) 
English (fluent)

## 📫 Contact
[LinkedIn](https://www.linkedin.com/in/sander-veldt/) · [Email](sanderveldt98@hotmail.com)
