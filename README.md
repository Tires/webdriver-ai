# WebDriver AI 🤖

**Autonomous AI browser assistant for the Chrome sidebar.** WebDriver AI transforms your browser into an intelligent agent capable of navigating, searching, and interacting with web pages autonomously.

## 🚀 Features

- **Autonomous Navigation**: The agent can search Google, click links, fill forms, and solve complex tasks across multiple steps.
- **Multi-Model Support**: Use **Gemini (2.0/2.5-flash/pro)**, **OpenAI (GPT-4o)**, **OpenRouter**, or local models via **Ollama**.
- **OpenRouter Integration**: Access a vast library of free and paid models (Llama 3, Claude 3, Mistral, etc.) with a single API key.
- **Modern Messenger UI**: A clean, sidebar-based chat interface with assistant avatars, real-time "thinking" indicators, and compact progress logging.
- **Tab Lock Security**: Ensures the agent stays within the active tab to maintain context and security by neutralizing `target="_blank"` and overriding `window.open`.
- **Precise Control**: Manually abort loops (✕), resubmit prompts (🔄), or toggle API key visibility (👁️) for enhanced security.
- **Model Auto-Selection**: Automatically prioritizes high-quality free models (like Gemini 2.0 Flash) when using OpenRouter.

## 🛠️ How it works

WebDriver AI uses advanced DOM analysis to identify interactive elements. It constructs a semantic map of the page, allowing the LLM to make informed decisions about which buttons to click or which fields to fill to reach your goal.

## 🔒 Privacy & Security

WebDriver AI is designed with privacy in mind:
- **No Data Collection**: The extension does not track your browsing history or collect personal data.
- **Direct API Communication**: Your data is sent directly to the LLM providers (Google, OpenAI, OpenRouter, or your local Ollama instance).
- **Tab Isolation**: The agent only interacts with the pages you explicitly ask it to.

---

[Privacy Policy](PRIVACY.md) | [Terms of Service](TERMS.md)
