# PR0MPTSER — AI Execution Desk

**PR0MPTSER** is a local-first, zero-backend prompt IDE designed to craft, test, and manage *Execution Prompts* (system prompts) for various AI models (Claude, GPT, DeepSeek, Grok, Llama, etc.).

Built with a responsive *dark-mode IDE* interface, it allows you to perform advanced prompt engineering without worrying about your data being logged by third-party servers.

## ✨ Core Features

- **🔒 100% Local-First:** All prompts, versions, and API keys are stored in your browser's `localStorage`. No backend, no telemetry.
- **⚡ Model-Specific Templates:** Dozens of prompt templates meticulously tuned to each model's quirks (e.g., XML wrapper for Claude, `[INST]` for Llama, Direct Markdown for GPT).
- **🧠 AI Prompt Generator:** Don't want to write from scratch? Plug in your API Key (OpenRouter, OpenAI, DeepSeek, or xAI) and let the AI generate hardcore execution prompts based on your goal.
- **📂 Library & Versioning:** Save prompts in the sidebar, mark them as favorites, and save version snapshots for easy rollbacks.
- **🔍 Instant Search & Filter:** Quickly find prompts by title, content, or model category.

## 🚀 Usage

**Option 1: Use Live Demo (No Install)**
You don't need to clone or install anything. Just visit the live app here: 
👉 **[https://pr0mptser.vercel.app](https://pr0mptser.vercel.app)**

**Option 2: Self-Host / Local Development**
Want to modify the code or host it yourself? Since this is pure Vanilla HTML/CSS/JS, you don't need Node.js or a server.

1. **Clone the Repo:**
   `git clone https://github.com/c0dey1939-web/PROMPTSER.git`
2. **Run Locally:**
   Simply double-click the `index.html` file. Or, open it via *Live Server* in VS Code.
3. **Deploy via GitHub Pages (Free):**
   - Go to your GitHub repo.
   - Open **Settings** > **Pages**.
   - Under *Build and deployment*, select Branch: `main` and folder `/root`. Click **Save**.
   - Your app will be live at `https://c0dey1939-web.github.io/PROMPTSER/`.

## 🔑 How to Get an API Key (For AI Generator)

The *AI Gen* feature requires an API key from an external provider. Your key is **never sent to the developer**; it goes directly from your browser to the API provider.

- **OpenRouter (Highly Recommended):** Register at [openrouter.ai](https://openrouter.ai/). Get access to Claude 3.5 Sonnet, Llama 3, GPT-4o, etc., with a single key. They have plenty of free models.
- **DeepSeek API:** Register at [platform.deepseek.com](https://platform.deepseek.com/). Extremely cheap and excellent for reasoning tasks (DeepSeek-R1).
- **OpenAI:** Register at [platform.openai.com](https://platform.openai.com/).
- **xAI (Grok):** Register at [console.x.ai](https://console.x.ai/).

*Security Note: Your API Key is only saved in your browser's local storage. Anyone else visiting your deployed site will not be able to see your key.*

## 🛠️ Tech Stack

- **Vanilla JavaScript** (No frameworks, no NPM bloat)
- **Vanilla CSS** (Custom properties, flexbox, CSS Grid, dark mode)
- **LocalStorage API** (Data persistence)
- **Fetch API** (Direct connection to LLM Providers)

## ⚠️ Disclaimer

This application is provided purely for **educational purposes and prompt engineering research**. The creator is not responsible for any misuse of prompts, violations of AI model Terms of Service, or damages arising from the use of this application.

## 📄 License

[MIT License](https://choosealicense.com/licenses/mit/) — Fork it, modify it, distribute it as you wish.
