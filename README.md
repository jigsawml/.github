<div align="center">

<img width="1929" height="689" alt="Logo-Svg" src="https://github.com/user-attachments/assets/af46cbbd-0709-4c97-a629-1e0754488599" />

**Architectural Intelligence for AI-generated software.**

Auto-generated, always-live architecture diagrams from your code and cloud infrastructure. Understand any system in seconds.

https://github.com/user-attachments/assets/afadb5ad-7665-476a-b5a5-46e33e01c97a

</div>

[![Get Started](https://img.shields.io/badge/Get_Started-blue?style=for-the-badge)](https://jigsawml.com/start)
[![Privacy First](https://img.shields.io/badge/Privacy_First-Runs_Locally-green?style=for-the-badge)](#privacy-first)
[![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white)](https://jigsawml.com/start)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://jigsawml.com/start)
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://reddit.com/r/jigsawml)
[![Follow on X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/JigsawML)
[![Demo Video](https://img.shields.io/badge/Watch_Demo-red?style=for-the-badge&logo=youtube&logoColor=white)](https://jigsawml.com/demo)

## 🏗️ Featured Architecture Examples

Real codebases, automatically mapped:

- **[NanoClaw](https://jigsawml.com/canvas/nanoclaw)** - A security-focused personal AI agent platform built on Claude
- **[NemoClaw](https://jigsawml.com/canvas/nemoclaw)** - A secure runtime environment for running OpenClaw AI agents
- **[Pydantic](https://jigsawml.com/canvas/pydantic)** - A high-performance data validation library for Python for type hints
- **[Flask](https://jigsawml.com/canvas/flask)** - Python web framework internals
- **[Axios](https://jigsawml.com/canvas/axios)** - HTTP client request flow  
- **[Zod](https://jigsawml.com/canvas/zod)** - TypeScript schema validation
- **[Hono](https://jigsawml.com/canvas/hono)** - Lightweight web framework

## 🎯 Who Is This For?

| | | |
|---|---|---|
| **🤖 AI-Assisted Developers** | **👥 Engineering Leads** | **🆕 New Team Members** |
| You're shipping faster than ever with Copilot, Cursor, or Claude. But AI-generated code still needs to fit into your existing system and do exactly what you want it to do. JigsawML shows you exactly where new code lands and what it touches. | You're responsible for a system that's growing faster than your team's ability to reason about it. JigsawML gives you a live, shared map of the architecture - no more stale diagrams or tribal knowledge. | You just joined and the codebase is 800K lines. JigsawML lets you see the full system structure in minutes instead of spending your first two weeks asking "what calls what?" |

## 💡 Why Architecture Matters for AI Code

Modern development moves fast. AI generates more code than ever. But understanding what you've built becomes the bottleneck.

JigsawML creates live architecture diagrams that:
- **Debug AI-generated code faster** - See how new code fits into your existing system
- **Onboard team members in minutes** - Visual system overview beats hours of documentation
- **Review pull requests with full context** - Understand changes at the architecture level
- **Document legacy systems automatically** - No more outdated diagrams or tribal knowledge
- **Show system boundaries** - What talks to what, and how
- **Track drift** - When code changes break your mental model
- **Map cloud resources** - Connect your code symbols to AWS/GCP/Azure
- **Scale with complexity** - From single functions to microservice meshes

## 🔧 How It Works

JigsawML builds architecture diagrams through static analysis - no runtime agents, no code execution, no data leaving your machine.

### The Pipeline

**1. Parse** - Full AST analysis of your source code. Functions, classes, modules, imports, and call paths are extracted per language (Python, TypeScript/JavaScript, Go).

**2. Resolve** - Dependencies are traced across files and packages. JigsawML builds a complete graph of what calls what, what inherits from what, and what imports what.

**3. Correlate** - Cloud infrastructure resources (S3 buckets, Lambda functions, API Gateways, etc.) are mapped back to the code symbols that reference them. Your architecture diagram shows both the code *and* the infra it touches.

**4. Render** - The graph is displayed as a live, interactive diagram. Zoom into a single function or zoom out to see the full system. Every node is clickable, searchable, and stays current as your code changes.

### Three Ways to Run

| Mode | Best For |
|---|---|
| **Local Installer** | Teams that need code to stay on their machines. Nothing leaves your environment. |
| **Cloud-Hosted** | Quick evaluation or solo devs who want zero setup. |
| **Containerized** | CI/CD integration and automated architecture checks. |

## 🔗 Get Started

- **[Try JigsawML](https://jigsawml.com/start)** - Local installer for Mac, Windows, Linux
- **[Demo Video](https://jigsawml.com/demo)** - A 5-min video of what's coming.
- **[Interactive Examples](https://jigsawml.com/open-source-projects)** - Interactive trimmed down examples using well known open source repositories.
- **[Reddit](https://reddit.com/r/jigsawml) | [X](https://x.com/JigsawML) | [LinkedIn](https://www.linkedin.com/company/jigsawml/)** - Join the community for Architecture discussions.

## 🚀 Supported Languages

- **Python** - Full AST analysis, import tracking, class hierarchies
- **TypeScript/JavaScript** - ES modules, React components, Node.js backends  
- **Go** - Package dependencies, struct relationships, interface mappings

---

**Backed by betaworks, True Ventures, and Slack Fund.**
