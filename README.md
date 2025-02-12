# Cursor Rules

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Security Policy](https://img.shields.io/badge/Security-Policy-red.svg)](SECURITY.md)

A collection of standardized development rules and best practices for projects built with the [Cursor IDE](https://cursor.sh).

[Getting Started](#-getting-started) •
[Documentation](#-documentation) •
[Contributing](#-contributing) •
[Security](#-security) •

</div>

## 📋 Overview

Cursor Rules is a community-driven collection of AI behavior rules that help teams maintain consistency and quality across their projects. By providing semantic descriptions for different file types and development patterns, these rules enable Cursor's AI to better understand your codebase and provide more relevant assistance.

### Key Features

- 🎯 **Project-Specific Rules**: Configure AI behavior for different parts of your project
- 🔄 **Context-Aware**: Rules are automatically applied based on file patterns
- 📦 **Reusable**: Share rules across projects and teams
- 🛠️ **Customizable**: Adapt rules to your specific needs and preferences

## 🚀 Getting Started

### Prerequisites

- [Cursor IDE](https://cursor.sh) installed
- Git

### Installation

1. Clone this repository into your project:

   ```bash
   git clone https://github.com/drengskapur/.cursor.git 
   ```

## 📖 Documentation

### Structure

Rules are stored in the `.cursor/rules` directory and provide semantic descriptions for:

- File pattern matching
- Auto-generated code handling
- Development patterns
- Architecture guidelines

### Creating Rules

Create new rules using the Cursor command palette:

1. Press `Cmd + Shift + P` (Mac) or `Ctrl + Shift + P` (Windows/Linux)
2. Type "New Cursor Rule"
3. Follow the prompts

### Available Categories

- **Authentication**: Security and authentication patterns
- **Framework**: Application architecture and patterns
- **Testing**: Unit, integration, and E2E testing standards
- **UI**: Component architecture and documentation
- **Automation**: Development workflows
- **State**: Application state management

### Rule Format

Each rule set includes:

- Best practices and conventions
- Code snippets and examples
- Configuration templates
- Common patterns and anti-patterns

## 🤝 Contributing

We believe in the power of community collaboration. Whether you're fixing bugs, adding new rules, or improving documentation, your contributions are welcome!

See our [Contributing Guide](CONTRIBUTING.md) for details on:

- Code of Conduct
- Development process
- Pull request guidelines
- Rule creation guidelines

## 💬 Community

- [GitHub Issues](../../issues) for bug reports and feature requests
- [GitHub Discussions](../../discussions) for questions and discussions
- [Pull Requests](../../pulls) for contributions
- [Security Policy](SECURITY.md) for vulnerability reporting

## 🔒 Security

We take the security of Cursor Rules seriously. If you believe you have found a security vulnerability, please read our [Security Policy](SECURITY.md) for reporting guidelines.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
