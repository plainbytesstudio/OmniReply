# OmniReply

<p align="center">
  <img src="./Assets/OmniReply.png" width="128" height="128" alt="OmniReply Logo">
</p>

<p align="center">
  <strong>A Clipboard-Driven AI Assistant for Fast Social Media Replies.</strong>
</p>

<p align="center">
  <a href="https://github.com/plainbytesstudio/OmniReply/releases"><img src="https://img.shields.io/github/v/release/plainbytesstudio/OmniReply?style=flat-square" alt="Latest Release"></a>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-blue?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/License-Proprietary-red?style=flat-square" alt="License">
</p>



## 🌟 What is OmniReply?

**OmniReply** is a lightweight, privacy-focused Windows desktop tool that turns clipboard content into AI-generated replies. It captures text from your clipboard, generates context-aware responses based on your predefined personas and platform rules, and **types them back** into any active window as if you were typing them yourself.

Whether you are managing social media accounts (Reddit, Twitter, Facebook), engaging in e-commerce customer service, or simply looking for a faster way to communicate, OmniReply streamlines your workflow with intelligence and speed.



## ✨ Key Features

- **Smart Clipboard Monitoring:** Instantly detects and cleans text from your clipboard using native Win32 APIs.
- **Context-Aware Engine (Meta-Prompting):** Combine **Personas** (Novice, Pro, OP), **Scenes** (Reddit, Twitter, TikTok), and **Objectives** (Recommend, Support, Rebuttal) for the perfect reply.
- **Multi-Model Integration:** Direct support for OpenAI (GPT-4o), Google Gemini (1.5 Pro/Flash), xAI Grok, and DeepSeek.
- **Human-like Write-back:** Simulates hardware-level keyboard input with random delays to ensure compatibility and to better mimic natural typing behavior.
- **Privacy-First Architecture:** 
    - **No Intermediary Servers:** Your data goes directly from your machine to the AI provider.
    - **Local Storage:** Profiles, rules, and history logs stay on your hard drive.
- **Modern UI:** A Windows 11 Fluent Design interface with Mica/Acrylic effects and a non-intrusive floating mode.



## 🚀 How It Works

1. **Copy:** Select any text (e.g., a comment or a post) and press `Ctrl+C`.
2. **Generate:** Open the OmniReply panel, select your target **Scene** and **Persona**.
3. **Write-back:** Click the **Write-back** button. OmniReply will hide itself and "type" the AI-generated content into your target input field.



## 📦 Installation

OmniReply is distributed as a pre-compiled Windows application. 

1. **Microsoft Store:** https://apps.microsoft.com/detail/9N9GDZPV40XR



## 🔐 Privacy & Security

OmniReply is built with transparency in mind.
- Your API Keys are stored locally and encrypted.
- No telemetry or usage data is collected by PlainBytes Studio.
- For more details, please read our [Privacy Policy](PRIVACY.md).



## ⚙️ Technical Notes

- Built with .NET / WPF
- Uses Win32 clipboard listener (AddClipboardFormatListener)
- Stateless API requests (no conversation history)



## 📜 License & Terms

**OmniReply is NOT Open Source software.**

- **Proprietary:** The source code is confidential and owned by **PlainBytes Studio**.
- **Usage:** You are free to download and use the application according to the provided terms. 
- **Restrictions:** Redistribution, de-compilation, or reverse-engineering of the binary files is strictly prohibited.



## 🛠 Support & Feedback

As this is a proprietary product, the GitHub repository is used for **documentation, distribution, and issue tracking**.

- **Bug Reports:** Please open a [GitHub Issue](https://github.com/plainbytesstudio/OmniReply/issues).
- **Feature Requests:** Feel free to suggest new models or platform rules via Issues.
- **Official Website:** [https://plainbytesstudio.github.io/products/OmniReply](https://plainbytesstudio.github.io/products/OmniReply)

---
<p align="center">
  © 2026 PlainBytes Studio. All rights reserved.
</p>
