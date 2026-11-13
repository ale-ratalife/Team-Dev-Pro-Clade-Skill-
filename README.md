<div align="center">

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg?style=for-the-badge)](https://github.com/ale-ratalife/Team-Dev-Pro-Clade-Skill-)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Powered by](https://img.shields.io/badge/Powered_by-Alex_%26_Alex_Software_and_Innovation-black.svg?style=for-the-badge)](https://alexyalex.site)
[![Author](https://img.shields.io/badge/Author-V._Alejandro_Téllez-purple.svg?style=for-the-badge)](https://github.com/ale-ratalife)

# 🚀 Team Dev Pro - Multi-Agent Skill

**A simulated high-performance software engineering architecture for Large Language Models (Claude / Gemini).**

</div>

---

## 📌 What is Team Dev Pro?

Team Dev Pro is not just a simple prompt; it is a **multi-agent architecture** packaged as a "Skill." Its purpose is to compel the AI ​​to function as a complete team of 9 software engineers—eliminating rambling and unnecessary questions, and delivering production-ready code immediately.

Developed and optimized by [Alex & Alex Software and Innovation](https://alexyalex.site).

## ⚙️ How Does It Work?

The Skill utilizes an **Intelligent Triage Pipeline**. When you begin a prompt with the keyword `Team:`:

1. **Emergency Bypass:** If the request is trivial (e.g., "tell me the time," "summarize this text in 2 lines"), the "team" is bypassed, and the AI ​​responds directly to save time and tokens.
2. **Full Pipeline:** For complex coding or architecture tasks, the system activates 9 roles in a silent, sequential chain:
- 👔 **PO (Product Owner):** Defines key requirements. 
- 🏗️ **Lead Architect:** Designs the overall architecture and tech stack. 
- 🗄️ **DBA:** Structures data models and queries. 
- 🚀 **DevOps:** Prepares Docker configurations and setup. 
- ⚙️ **Backend:** Develops the core logic. 
- 🎨 **Frontend:** Refines the graphical interface. 
- 🔒 **SecOps:** Addresses and patches vulnerabilities. 
- 🧪 **QA:** Implements defensive logic. 
- 👁️ **Code Reviewer:** Assembles the final output, removes unnecessary comments, and delivers the finished product.

All generated text adheres to *Strict Output* guidelines (no greetings, no introductions—straight to the point).

## 🛠️ Installation and Usage (GitHub)

To integrate this Skill into your environment, clone the repository:

```bash
git clone https://github.com/ale-ratalife/Team-Dev-Pro-Clade-Skill-.git
```

### Manual Setup
1. Download the repository.
2. Copy the contents of `SKILL.md` to use as your master prompt.
3. Ensure that the files from the `protocols/`, `roles/`, and `guidelines/` folders are added to your agent’s knowledge base or context so that the strict rules are applied.
4. **Usage:** Simply type `Team: create a SaaS in Next.js` in your chat. ## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---
*Made with ⚡ by [Alex & Alex Software and Innovation](https://alexyalex.site).*
