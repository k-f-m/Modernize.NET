# Modernize.NET: The AI-Powered Legacy Code Modernizer

[![Project Status: WIP](https://img.shields.io/badge/status-work%20in%20progress-yellow.svg)](https://github.com/k-f-m/Modernize.NET)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

An AI-powered tool to automatically refactor legacy C# code to modern .NET 8 best practices. This project aims to provide a clear and safe upgrade path for applications facing technical debt.

## The Vision

Countless businesses rely on applications built with older versions of the .NET Framework. Manually modernizing this code is a slow, expensive, and error-prone process. **Modernize.NET** is a web-based tool designed to solve this problem by leveraging AI to provide instant, expert-level code refactoring.

## Core Features (Planned)

- **Legacy-to-Modern Refactoring:** Paste legacy C# code and receive the modern .NET 8 equivalent.
- **Best Practice Implementation:** The AI will apply modern patterns like `async/await`, LINQ, and the latest C# syntax.
- **Clear "Before & After" UI:** A simple, intuitive interface to visualize the code transformation.

## Technology Stack (Planned)

This project is built using a modern, cloud-native stack to ensure scalability and maintainability:

- **Backend:** .NET 8 / ASP.NET Core Web API
- **Frontend:** Blazor
- **AI Engine:** A custom-engineered, multi-step prompt for a leading Large Language Model (LLM)
- **Deployment:** Docker & Microsoft Azure Container Apps
- **CI/CD:** GitHub Actions

## Project Status

This project is currently **under active development**.

## Roadmap

- [ ] **Phase 1: Backend Core:**
  - [ ] Set up ASP.NET Core Web API project.
  - [ ] Implement core AI prompting logic for basic refactoring.
- [ ] **Phase 2: Frontend UI:**
  - [ ] Develop the Blazor user interface with "before" and "after" code editors.
  - [ ] Connect the UI to the backend API.
- [ ] **Phase 3: Deployment:**
  - [ ] Dockerize the application.
  - [ ] Create a GitHub Actions workflow for CI/CD.
  - [ ] Deploy the application to Microsoft Azure.
- [ ] **Phase 4: Advanced Features:**
  - [ ] Add support for more complex refactoring scenarios.
  - [ ] Refine the AI prompt for higher accuracy.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
