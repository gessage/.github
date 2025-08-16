# Gessage — Intelligent Git Commit Messages

> **Making every commit message meaningful with AI-powered Conventional Commits**

[![GitHub stars](https://img.shields.io/github/stars/ispooya/gessage-cli?style=social)](https://github.com/ispooya/gessage-cli)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🎯 Project Vision

Gessage transforms the way developers write commit messages by leveraging AI to generate consistent, meaningful, and standard-compliant Git commits. Our mission is to eliminate poorly written commit messages while saving developers time and mental energy.

## 🌟 Why Gessage?

**The Problem:** Most developers struggle with writing good commit messages. Research shows that 78% of commit messages in open-source projects don't follow any standard, making project history hard to navigate and understand.

**Our Solution:** AI-powered commit message generation that:
- ✅ Always follows Conventional Commits standard  
- ✅ Analyzes your actual code changes
- ✅ Provides multiple backend options (OpenAI, OpenRouter, Ollama)
- ✅ Offers completely free usage through OpenRouter
- ✅ Maintains privacy with automatic secret redaction

## 🚀 Get Started

Ready to improve your Git workflow? Head over to our main repository for installation and usage instructions:

**👉 [Install Gessage CLI](https://github.com/ispooya/gessage-cli)**

### Quick Preview
```bash
# Install with one command
curl -fsSL https://raw.githubusercontent.com/ispooya/gessage-cli/refs/heads/main/install.sh | bash

# Setup with free models
gessage setup --model openrouter

# Generate commits effortlessly  
git add .
gessage
```

## 🔥 Featured Capabilities

| Feature | Description |
|---------|-------------|
| **🆓 Free Forever** | Use OpenRouter's free models — no credit card required |
| **🤖 Multiple AI Backends** | OpenAI GPT-4, OpenRouter, or local Ollama models |
| **📏 Smart Sizing** | Auto-selects appropriate models based on diff complexity |
| **🔒 Privacy First** | Automatic secret detection and redaction |
| **⚡ Interactive Flow** | Approve, edit, regenerate, or cancel before committing |
| **📋 Standards Compliant** | Enforces Conventional Commits format automatically |

## 🛠️ Technical Architecture

Gessage is built with:
- **Go** for high-performance CLI operations
- **Advanced diff analysis** for context-aware message generation  
- **Modular AI backend system** supporting multiple providers
- **Robust validation** ensuring commit message quality
- **Cross-platform support** (Linux, macOS, Windows)

## 📊 Project Stats & Roadmap

### Current Status
- ✅ Core CLI functionality
- ✅ Multi-backend AI support  
- ✅ Interactive commit flow
- ✅ Cross-platform installation
- ✅ Free usage tier

### Coming Soon
- 🔄 IDE integrations (VS Code, JetBrains)
- 📈 Commit analytics and insights
- 🎨 Customizable commit templates
- 🌐 Web dashboard for team usage
- 📱 Mobile companion app

## 🤝 Community & Ecosystem

### Core Repository
**[ispooya/gessage-cli](https://github.com/ispooya/gessage-cli)** — Main CLI tool with full documentation, issues, and releases

### Get Involved
- 🐛 **Report Issues:** Found a bug? Let us know!
- 💡 **Feature Requests:** Have ideas? We'd love to hear them
- 🔀 **Contribute:** Check our contribution guidelines
- 💬 **Discussions:** Join our community conversations

## 📈 Why Choose Gessage?

### For Individual Developers
- Save time on commit message writing
- Improve your project's commit history quality  
- Learn better commit message practices
- Use completely free with OpenRouter models

### For Teams
- Standardize commit messages across all repositories
- Improve code review processes with consistent messaging
- Better project documentation through meaningful commits
- Enhanced Git history for debugging and analysis

## 🎯 Created by Developers, for Developers

Gessage is crafted by **[Pooya Karimi](https://github.com/ispooya)**, a passionate software engineer dedicated to building tools that make developers' lives easier. With expertise in scalable architecture and clean code practices, Pooya understands the daily challenges developers face and builds solutions that actually work.

---

**Ready to revolutionize your commit messages?**

[**🚀 Start Using Gessage**](https://github.com/ispooya/gessage-cli) | [**📚 Documentation**](https://github.com/ispooya/gessage-cli#readme) | [**💬 Community**](https://github.com/ispooya/gessage-cli/discussions)

---
<sub>© 2025 Gessage Project • MIT Licensed • Made with ❤️ for the developer community</sub>


