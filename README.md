# token-joiner-with-captcha-solver
discord token joiner
discord token joiner with cap solver
discord tools
discord
discord ev gen
discord pv tool
discord phone verifier tool
discord account gen
discord token gen

# Discord Multi-Tool — Server Joiner & AI Captcha Solver

A high-performance Python-based automation tool for server onboarding, featuring dual engine execution (Playwright Browser & REST API) and multi-provider AI hCaptcha solving.

## 🚀 Features

- **Dual Joiner Engines:**
  - **Native Browser Engine:** Playwright-driven Chromium session automation.
  - **Fast HTTP API Engine:** Lightweight REST API execution.
- **Multi-Provider AI Captcha Solver:**
  - Integrated solver supporting **Ollama** (local AI models), **Google Gemini API**, **Pollinations AI**, **Groq**, and **OpenRouter**.
  - Built-in rule-based deterministic text challenge solver.
- **Proxy Support:**
  - Supports Proxyless, HTTP/HTTPS, SOCKS4, SOCKS5, and Rotating proxy modes.
- **Token Validation & Workflow Automation:**
  - Automated token health verification.
  - Onboarding and rules-acknowledgment handling.

## 📋 Prerequisites

- Python 3.10 or higher
- Playwright Chromium binaries (for browser engine mode)

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/discord-multi-tool.git
   cd discord-multi-tool
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Install Playwright browser drivers:
   ```bash
   playwright install chromium
   ```

## ⚙️ Configuration (`config.json`)

Configure your settings, proxies, and AI provider priorities in `config.json`:

```json
{
    "invite_code": "YOUR_INVITE_CODE",
    "joiner_engine": "browser",
    "browser_headless": true,
    "threads": 3,
    "cooldown": 2,
    "captcha_solver": "ai_text",
    "ai_solver": {
        "provider_priority": [
            "ollama",
            "gemini",
            "pollinations",
            "groq"
        ],
        "gemini": {
            "api_key": "YOUR_GEMINI_API_KEY",
            "model": "gemini-1.5-flash"
        },
        "ollama": {
            "model": "qwen2.5:1.5b"
        }
    }
}
```

## 🎯 Usage

Run the main application interface:

```bash
python main.py
```

Select from the interactive menu:
- `[1]` Server Joiner
- `[2]` Set Invite Link
- `[3]` Token Checker
- `[4]` Proxy Settings
- `[5]` Proxy Checker
- `[6]` Config Settings

## ⚠️ Disclaimer

This software is provided for educational and testing purposes only. Usage must comply with applicable platform Terms of Service.




preview - https://youtu.be/M26L15_b2Z8?si=WVcAG6YC8oYnDU4P

dm @aryan_996 to buy on discord!
