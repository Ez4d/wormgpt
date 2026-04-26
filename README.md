pass:EZADKING08

# Prerequisites
 Node.js 18+
 
 Ollama (auto-installed by install.sh)
 
 windows 11/10

# 🚀 Llama3 Lexi Uncensored Local Deploy

Simple and fast setup for running Llama3 Lexi Uncensored locally.

## 🛠️ Installation & Execution

```bash
# 1. Install Ollama (Windows PowerShell)
irm [https://ollama.com/install.ps1](https://ollama.com/install.ps1) | iex

# 2. Pull the required model
ollama pull godmoded/llama3-lexi-uncensored

# 3. Start the Ollama service
ollama serve

# 4. Install dependencies and build project
cd app && npm install && npm run build && cd ..
cd server && npm install && cd ..

# 5. Start the server
cd server && node index.js
