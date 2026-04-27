# 🚀 Zero to Local LLM (llama.cpp)

Run a local LLM in minutes using `llama.cpp` and GGUF models — no API, no cloud, 100% local.

This repo provides a simple notebook to:
- Install Homebrew (Linux)
- Install `llama.cpp`
- Run a lightweight open-source LLM locally

---

## 🧠 What This Does

This project helps you quickly bootstrap a local AI environment using:

- 🛠️ `llama.cpp` (fast C++ inference engine)
- 📦 GGUF models (optimized for local use)
- 💻 Works on low-resource machines

---

## ⚡ Quick Start

### Run the notebook (Google Colab or local Jupyter)

The notebook will:

Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
Setup environment

```bash
import os
os.environ['PATH'] += ":/home/linuxbrew/.linuxbrew/bin"
```
brew install llama.cpp

```bash
brew install llama.cpp
```

Run a model
```bash
llama-cli -hf ggml-org/gemma-3-1b-it-GGUF
```
---

## 🧪 Model Used
-gemma-3-1b-it (GGUF format)
-Lightweight and fast
-Suitable for low-resource environments

---

## 💡 Why This Matters
-No API costs 💸
-No internet needed after setup 🌐❌
-Full control over your AI 🔒
-Perfect for:
 -Developers
 -Hackathons 
 -Offline AI tools
 -Learning LLM internals

---

##⚠️ Notes
-First run may take time (downloads model)
-Performance depends on your CPU/RAM
-You can swap models easily (GGUF format)
