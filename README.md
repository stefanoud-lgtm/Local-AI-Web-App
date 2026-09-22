# Local-AI-Desktop-&-Web-App

A hybrid Windows desktop app and web portal designed to run and manage fine-tuned LLMs locally. Built for total privacy, daily productivity, and high performance on consumer-grade hardware.

> **Platform Notice:** Currently developed and tested exclusively for **Windows**. Linux and macOS are not supported at this stage.

---

## What Makes This Project Different

* **Optimized for Consumer GPUs:** Tuned specifically to run on budget local hardware (such as the **NVIDIA RTX 3050**) rather than expensive enterprise cloud infrastructure.
* **Proven Performance:** Benchmarked using a custom-tuned local model achieving **~40 tokens/second** on an RTX 3050. Tested by generating fully playable 2D HTML games in just 2 to 3 prompts.
* **Dual Interface (Desktop & Web):** Operates as a standalone Windows desktop application and as a web portal linked to a private custom domain.
* **100% Private & Local:** Powered by a local Ollama backend. Zero external API calls—your data and conversations never leave your machine.

## Key Features

* **Daily Assistant & Coding Engine:** Optimized system prompts and parameters specifically tuned for writing, debugging, and executing code.
* **RAG & Local Knowledge Base:** Built-in vector database to index and query PDFs, documents, and local codebases offline.
* **Cloudflare Tunnel Routing:** Pre-configured networking setup to securely access the interface remotely via Cloudflare Tunnels without opening router ports.
* **Authentication & Admin Control:** User login system, encrypted local password storage, and an admin dashboard for access management.

## Architecture & Licensing

This project uses a **hybrid model**:
* **Open Engine:** Built on top of open-source backends (Ollama) and local vector store libraries.
* **Proprietary UI & Optimization:** The Windows desktop application, custom web UI, and specific model optimizations are proprietary.

## Tech Stack

* **Target OS:** Windows 10 / 11
* **Target Hardware:** Consumer NVIDIA GPUs (Optimized for RTX 3050)
* **LLM Engine:** Ollama / Local Runner
* **Networking:** Cloudflare Tunnels
* **Vector Storage:** Local Vector DB
* **Security:** Encrypted authentication & local key management

## Project Status

> Currently in active testing and debugging. Release binaries and documentation will be pushed as the Windows build stabilizes.

<img width="782" height="849" alt="image" src="https://github.com/user-attachments/assets/15befd62-b225-4e63-9af6-6781656344aa" />


