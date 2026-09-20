# Local-AI-Web-App
A web interface for running and managing AI models locally, fully offline and privacy-focused. Built to be flexible, easily modifiable, and ready to connect to an external website via Cloudflare.


Features
Local Execution & Privacy: No external API calls. All data stays on your local machine.

Cloudflare Integration: Pre-configured to connect securely to a domain or web app via Cloudflare Tunnels if you need remote access.

Model Management: Quick switching between different models (Ollama, etc.) directly from the interface.

Dedicated Modes:

Coding Mode: Interface and parameters optimized for code generation and debugging.

Agent Mode: Designed for complex tasks and automated workflows.

RAG Module: Memory and retrieval system for uploading documents and files for the models to analyze.

Admin Panel & Authentication:

User login system with password encryption.

Encryption key configuration is managed within the repository setup.

Dedicated admin dashboard to manage user access and settings.

Open Source Code: The entire system is customizable so you can adapt it to your needs.

<img width="782" height="849" alt="image" src="https://github.com/user-attachments/assets/15befd62-b225-4e63-9af6-6781656344aa" />


Project Status
Note: Source code files will be pushed to this repository as soon as the current debugging and testing phase is complete.

Tech Stack
LLM Engine: Ollama / Local Runner

Networking/Tunneling: Cloudflare

Storage & RAG: Local Vector Database for document memory

Security: Password encryption for user authentication

License
Open Source project.
