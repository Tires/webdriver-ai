# WebDriver AI 🤖

**Autonomous AI browser assistant for the Chrome sidebar.** WebDriver AI transforms your browser into an intelligent agent capable of navigating, searching, and interacting with web pages autonomously.

## 🚀 Features

- **Autonomous Navigation**: The agent can search Google, click links, fill forms, and solve complex tasks across multiple steps.
- **Multi-Model Support**: Use **Gemini (2.5-flash/pro)**, **OpenAI (GPT-4o)**, or local models via **Ollama**.
- **Google OAuth2 Integration**: Seamlessly use your personal Gemini quota via Google Login without sharing API keys.
- **Modern Messenger UI**: A clean, sidebar-based chat interface with real-time "thinking" indicators and progress logging.
- **Tab Lock Security**: Ensures the agent stays within the active tab to maintain context and security.
- **Precise Control**: Manually abort loops or resubmit prompts from any point in the history.

## 🛠️ How it works

WebDriver AI uses advanced DOM analysis to identify interactive elements. It constructs a semantic map of the page, allowing the LLM to make informed decisions about which buttons to click or which fields to fill to reach your goal.

## 🔒 Privacy & Security

WebDriver AI is designed with privacy in mind:
- **No Data Collection**: The extension does not track your browsing history or collect personal data.
- **Direct API Communication**: Your data is sent directly to the LLM providers (Google, OpenAI, or your local Ollama instance).
- **Tab Isolation**: The agent only interacts with the pages you explicitly ask it to.

---

[Privacy Policy](PRIVACY.md) | [Terms of Service](TERMS.md)
