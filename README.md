<div align="center">
  <h1>🧠 Synapse</h1>
  <h3>Your private AI assistant — running entirely on your own PC</h3>
  <p><em>Offline by default. Your data never leaves your machine.</em></p>
  <p>
    <img alt="Platform" src="https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white">
    <img alt="Status" src="https://img.shields.io/badge/status-active%20development-orange?style=for-the-badge">
    <img alt="Privacy" src="https://img.shields.io/badge/privacy-local%20first-2ea44f?style=for-the-badge">
    <img alt="GPU" src="https://img.shields.io/badge/GPU-RTX%203050%208GB-76B900?style=for-the-badge&logo=nvidia&logoColor=white">
  </p>
</div>
---
✨ Why Synapse
	
🔒	Private by design — a local LLM answers on your hardware. Internet is off unless you turn it on.
💻	Runs on consumer hardware — built and tested on a single RTX 3050 with 8 GB of VRAM. No cloud, no subscription.
🪟	Two interfaces, one assistant — a minimal desktop HUD for quick questions, a full web app for longer work.
---
🖥️ Interfaces
⚡ Desktop HUD
A minimal, Dynamic Island–style bar that stays out of your way.
⌨️ Opens and closes with a global shortcut — `Alt + Space`
🫧 Glassmorphism design, click-through when idle
🟢 Live status dot: ready · generating · unavailable
💬 Remembers the conversation, with saved chat history
🌐 Web App
The full workspace — as a desktop window or in the browser.
📁 Projects and conversation history with search
🔐 Optional secure remote access via Cloudflare Tunnel, behind login
---
🚀 Features
Feature	What it does
📚 Local document search	Ask questions about your PDFs, Word, OpenDocument and Excel files — answers cite their sources
🧩 Long-term memory	Remembers useful facts across sessions, encrypted on your PC. Review or delete anytime
🎙️ Offline voice	Speech-to-text (faster-whisper) and neural text-to-speech (Piper), no internet needed
🧮 Built-in utilities	Calculator, unit conversion, date & time, reminders
🗺️ Offline Italian geography	63,000+ places from GeoNames — details and distances, fully offline
🔎 Mixed mode (optional)	Anonymous web search, only when you explicitly enable it
---
🛡️ Security & Privacy
✅ Offline by default — going online is always your choice
✅ Backend bound to the local machine; remote access only through an authenticated tunnel
✅ Salted password hashing + mandatory password change on first login
✅ Role-based access — admin functions restricted to admins
✅ Local data encrypted at rest (Windows DPAPI)
✅ Optional firewall rule to block all outbound traffic
✅ Documents and web results treated as data, never as instructions
---
🆕 What's New — October 2026
🎨 Brand-new minimal desktop HUD
🧹 Agent mode removed — the assistant no longer runs commands or edits files, shrinking the attack surface
🔐 Security hardening across authentication, access control and network exposure
💬 Conversation memory and chat history in the HUD
🔮 Coming Next
> 🌟 **A completely redesigned web interface** — stay tuned.
🌗 Light & dark themes
🖥️ Multi-monitor support and more HUD settings
⚡ Faster responses
---
📸 Screenshots
<div align="center">
<img width="600" alt="Synapse login" src="https://github.com/user-attachments/assets/15befd62-b225-4e63-9af6-6781656344aa" />
</div>
---
⚙️ Requirements
🪟 Windows 10 / 11
🎮 NVIDIA GPU with 8 GB+ VRAM (tested on RTX 3050 8 GB)
🦙 Ollama with at least one model (default: `qwen2.5:7b`)
---
<div align="center">
  <h3>📜 License</h3>
  <p><strong>Synapse is proprietary software.</strong> The source code is not public.</p>
  <p>📩 Licensing inquiries: []</p>
</div>
