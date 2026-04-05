# OpenClaude ( Modified by Ankon Polley) 🚀

OpenClaude is an open-source coding-agent CLI for cloud and local model providers, customized and maintained by **Ankon Polley**.

Use OpenAI-compatible APIs, Gemini, GitHub Models, Codex, Ollama, Atomic Chat, and other supported backends while keeping one terminal-first workflow: prompts, tools, agents, MCP, slash commands, and streaming output.

![Build](https://img.shields.io/badge/PR_Checks-passing-success) ![Release](https://img.shields.io/badge/release-v0.1.7-blue) ![Security](https://img.shields.io/badge/security-policy-teal) ![License](https://img.shields.io/badge/license-MIT-blue)

<p align="left">
  <a href="https://www.instagram.com/itz_vorzhevik_volnyshev?igsh=OTNqMndzdDFzZ293"><img src="https://img.shields.io/badge/Instagram-Main-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
  <a href="https://www.instagram.com/its_ankon_polley?igsh=MXQyNnVpcGV2bmF5aw=="><img src="https://img.shields.io/badge/Instagram-Alt-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
  <a href="https://x.com/AnkonPolley"><img src="https://img.shields.io/badge/Twitter-Follow-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
  <a href="https://www.threads.net/@itz_vorzhevik_volnyshev"><img src="https://img.shields.io/badge/Threads-Follow-000000?style=for-the-badge&logo=threads&logoColor=white" /></a>
  <a href="https://www.facebook.com/share/1DrXE7djH1/"><img src="https://img.shields.io/badge/Facebook-Connect-1877F2?style=for-the-badge&logo=facebook&logoColor=white" /></a>
  <a href="https://www.reddit.com/u/robertoppenheimer123/s/1lsT0KNM9r"><img src="https://img.shields.io/badge/Reddit-Profile-FF4500?style=for-the-badge&logo=reddit&logoColor=white" /></a>
  <a href="https://pin.it/3uKE8ZdFc"><img src="https://img.shields.io/badge/Pinterest-Saves-E60023?style=for-the-badge&logo=pinterest&logoColor=white" /></a>
</p>

---

# 📥 Installation Guide

### **Linux & macOS**
1. **Global Install via NPM:**
   ```bash
   npm install -g anknpolley123/openclaude
2. **Run This Tool:***
   ```bash
   openclaude
3. **Set Custom Alias (Optional):**
 ```bash
Add this to your ~/.bashrc:
alias ankon-claude='node ~/path-to-repo/bin/claude.js'
 ```
### Installation In Windows
1. **Install Node.js:**
2. ```bash
   Download from nodejs.org
   ```
   **Open PowerShell (as Admin) and run:**
   ```bash
   npm install -g anknpolley123/openclaude
   ```
   **Configure Environment:**
   ```bash
   $env:CLAUDE_CODE_USE_OPENAI="1"
   openclaude
   ```
### In Termux
 **Setup Environment:**
 ```bash
  pkg update && pkg upgrade
  pkg install nodejs git ripgrep
 ```
### In Kali NetHunter
```bash

   sudo apt update && sudo apt upgrade
   sudo apt install nodejs git ripgrep

 ```
### Install & Launch:

```bash

npm install -g anknpolley123/openclaude
openclaude

```
### 🛠 Supported Providers
**Provider**          **Setup Path**
**Google Gemini:**   Run /provider inside the app

**OpenAI/Groq:**       Run /provider or set Env Vars

**Ollama (Local):**   Set OPENAI_BASE_URL=http://localhost:11434/v1

### ⚖️ Disclaimer
This project is an independent community build by Ankon Polley and is not affiliated with Anthropic.
​© 2026 Ankon Polley. All rights reserved.



