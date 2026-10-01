# 🌸 All-in-One Local Anime Discord Bot Framework

A zero-coding, one-click desktop application launcher that bundles a lightweight, quantized local LLM backend with a custom character personality profile and a Discord API bridge.

## 🚀 The Vision
Non-technical users can download a single package, input their Discord Bot Token via a simple GUI dashboard, and immediately bring an immersive roleplay character into their server—running 100% locally on their own hardware.

## 🛠️ Tech Stack & Architecture
- **Frontend GUI:** [Tauri / CustomTkinter / Electron] (Handles token setup & process lifecycle)
- **Model Engine:** KoboldCPP / Llama.cpp (Silent background execution)
- **AI Brain:** Quantized 3B to 8B GGUF Model (Optimized for roleplay)
- **Bridge:** Python (`discord.py`) compiled into a standalone binary via PyInstaller

## 📋 Current Progress & Roadmap
- [x] Initial repository structure and architecture design
- [ ] Build the minimalist Python GUI wrapper for token management
- [ ] Implement robust background sub-process management (Start/Stop lifecycle)
- [ ] Implement the `discord.py` character persona bridge script
- [ ] Bundle and compile into a single-click Windows Installer (.exe)
