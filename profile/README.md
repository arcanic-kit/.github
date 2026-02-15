# Arcanic

### Modern Architecture Toolkit for .NET
**Build cleaner, scalable, and maintainable applications with ease.**

## 🔮 About Arcanic

**Arcanic** is a comprehensive ecosystem of developer tools designed to simplify the implementation of **Clean Architecture**, **Domain-Driven Design (DDD)**, and modern patterns in .NET applications.

We believe that robust architecture shouldn't require boilerplate overload. Our goal is to provide lightweight, modular libraries that encapsulate complex patterns—like Mediator, Result, and Repository—into fluent, easy-to-use interfaces. Whether you are building a microservice or a modular monolith, Arcanic provides the building blocks to do it right.

## 🚀 The Ecosystem

Arcanic is split into modular packages, allowing you to pull in only what you need.

### Core Libraries

| Package | Description |
| :--- | :--- |
| **`Arcanic.Mediator`** | A lightweight, zero-dependency implementation of the **Mediator pattern**. Decouple your in-process messaging with distinct Command and Query handling. |
| **`Arcanic.Result`** | *Coming Soon* - A functional approach to error handling. Replace exceptions with a robust **Result pattern** to handle success, failure, and validation states explicitly. |
| **`Arcanic.Repository`** | *Coming Soon* - Generic repository abstractions and implementations to streamline data access while keeping your domain pure. |
| **`Arcanic.MinimalApi`** | *Coming Soon* - Extensions and wrappers to organize **Minimal APIs** into structured, testable endpoints without losing the performance benefits. |

<!-- ### 🛠️ Project Templates

Don't start from scratch. We provide `dotnet new` templates pre-configured with Arcanic best practices.

- **`Arcanic.CleanArch.Template`**: A full Clean Architecture solution structure (Domain, Application, Infrastructure, API).
- **`Arcanic.ModularMonolith.Template`**: A setup designed for modular systems with clear boundary separation.

---

## ⚡ Quick Start

Install the templates to spin up a new project instantly:

```bash
dotnet new install Arcanic.Templates
mkdir MyNewProject
cd MyNewProject
dotnet new arcanic-clean -n MyNewProject -->

## 🎯 Philosophy

- Developer Experience First: APIs should be intuitive and discoverable.
- Zero Bloat: Minimal external dependencies.
- Standard Compliant: Built specifically for the modern .NET ecosystem.
- Testable: Every component is designed with unit testing in mind.

## 🤝 Contributing

We welcome contributions! Whether it's fixing a bug, adding a new feature to the Result pattern, or improving the templates, please check out our Contribution Guidelines before getting started.

1. Fork the repository.
2. Create your feature branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the branch (git push origin feature/AmazingFeature).
5. Open a Pull Request.

## 📄 License
Arcanic is open-source software licensed under the MIT License.
