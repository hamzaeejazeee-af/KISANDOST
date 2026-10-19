# Kisan Dost - a project by Hamza Ejaz
Copyright (c) 2026 Hamza Ejaz. All rights reserved.

## Standalone version
1. `pip install -r requirements.txt`
2. Copy `.env.example` to `.env`, then paste your key after `ANTHROPIC_API_KEY=` (get one at https://console.anthropic.com/settings/keys).
3. `python server.py`, then open http://localhost:5000
## Ollama (free, offline)
Install from https://ollama.com/download, then run `ollama pull llama3.2` and `ollama pull llama3.2-vision`. Pick "AI: Ollama (local)" in the sidebar.
## Weather
Live forecasts come from Open-Meteo (no key). Set your region in the sidebar.
## Safety
The key stays in `.env` on the server. Never put it in the HTML or share the file.


## Easiest start
Run `start.bat` (Windows) or `./start.sh`. See HOW-TO-RUN.txt. Free Groq key: https://console.groq.com/keys (Grok/xAI also supported, paid). "Auto" picks whatever is available.
