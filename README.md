pass:EZADKING08

# Prerequisites
 Node.js 18+
 
 Ollama (auto-installed by install.sh)
 
 windows 11/10




<img width="1918" height="949" alt="{5F45D85F-A9C5-4B61-90BF-A0EA5C56954E}" src="https://github.com/user-attachments/assets/6d0eef2c-0d11-4d4e-af80-46e3b47131d9" />



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
