Synapse
A private AI assistant for Windows that runs entirely on your own PC.
Offline by default. Your conversations and documents never leave your machine unless you choose otherwise.
> **Platform:** Windows 10 / 11 only, at this stage.
---
Why Synapse
Private by design. A local LLM (via Ollama) answers on your hardware. Internet access is off by default and enabled only when you switch to Mixed mode.
Runs on consumer hardware. Built and tested on a single NVIDIA RTX 3050 with 8 GB of VRAM. No cloud subscription, no enterprise GPU.
Two interfaces, one assistant. A minimal desktop HUD for quick questions, and a full web app for longer work.
Interfaces
Desktop HUD
A minimal, Dynamic Island–style bar that stays out of the way.
Opens and closes with a global shortcut (`Alt+Space`)
Glassmorphism design, click-through when not in use
Live status indicator: model ready, generating, or unavailable
Remembers the current conversation; saved chat history
Web app
The full workspace, available as a desktop window or in the browser.
Projects and conversation history with search
Optional secure remote access through Cloudflare Tunnel, behind login
Features
Local document search (RAG). Index PDFs, Word, OpenDocument and Excel files, then ask questions about them. Answers cite their sources.
Long-term memory. Remembers useful facts and preferences across sessions, stored encrypted on your PC. You can review and delete any memory.
Offline voice. Speech-to-text with faster-whisper and neural text-to-speech with Piper, with no internet connection.
Built-in utilities. Calculator, unit conversion, date and time, reminders.
Offline Italian geography. Over 63,000 places from GeoNames: location details and distances, without internet.
Mixed mode (optional). Anonymous web search when you explicitly enable it.
Security & Privacy
Offline by default; internet use is always an explicit choice
Backend bound to the local machine; remote access only through an authenticated tunnel
User accounts with salted password hashing and mandatory password change on first login
Role-based access: administrative functions are restricted to admins
Local data encrypted at rest with Windows DPAPI
Optional system firewall rule that blocks the app's outbound internet traffic
External content (documents, web results) is treated as data, never as instructions
What's New
October 2026
New minimal desktop HUD
Agent mode removed: the assistant no longer runs commands or modifies files, reducing the attack surface
Security hardening across authentication, access control and network exposure
Conversation memory and chat history in the HUD
Coming Next
A brand-new web interface, redesigned from the ground up
Light and dark themes, multi-monitor support and more HUD settings
Performance work for faster responses
Requirements
Windows 10 / 11
NVIDIA GPU with at least 8 GB of VRAM (tested on RTX 3050 8 GB)
Ollama with at least one model (default: `qwen2.5:7b`)
Screenshots
<img width="782" height="849" alt="Synapse login" src="https://github.com/user-attachments/assets/15befd62-b225-4e63-9af6-6781656344aa" />
Project Status
Active development and testing. Release builds will be published once the Windows version is stable.
License
Synapse is proprietary software. The source code is not public.
For licensing inquiries: [your contact]
