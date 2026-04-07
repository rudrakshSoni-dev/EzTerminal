# 🤖 Ez Terminal

**The AI-powered CLI that makes the terminal feel like a chat.**

Stop memorizing flags, complex shell syntax, and nested `package.json` scripts. **Node-Buddy** is a smart CLI layer that uses **local LLM inference** to turn natural language into executable Node.js commands. No API keys, no internet, no data leaks—just pure local power.

---

## ✨ Key Features

*   🧠 **Local Inference**: Powered by lightweight models (Phi-3, Llama-3, or Mistral) running on your machine via Ollama.
*   🔍 **Context Awareness**: Automatically reads your `package.json` to suggest the right scripts for your specific project.
*   🗣️ **Natural Language Prompting**: Type "run my app in debug mode" and it translates it to `node --inspect index.js` instantly.
*   ⚡ **Smart Autocomplete**: Interactive UI that predicts your next command based on project history.
*   🛡️ **Safety-First Execution**: Commands are generated and explained first; nothing runs without your explicit permission.

---

## 🚀 Installation & Setup

### 1. Prerequisites
You must have [Ollama](https://ollama.com) installed and running on your machine to handle the local AI inference.

```bash
# Verify Ollama is running
ollama --version

# Pull a lightweight model (recommended for speed)
ollama pull phi3 


