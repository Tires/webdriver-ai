# Privacy Policy for WebDriver AI

**Last updated: April 14, 2026**

## 1. Overview
WebDriver AI ("the Extension") is committed to protecting your privacy. This policy explains what data we process and how it is handled.

## 2. Data Collection
We do **not** collect, store, or sell any personal data.
- **Browsing Data**: The Extension analyzes the content of the active tab only when you interact with the agent. This analysis is performed locally in your browser.
- **Login Information**: The Extension does **not** use OAuth2 or personal account logins. All authentication is handled via user-provided API keys stored locally in the Extension's private storage.

## 3. Data Processing and Transmission
To fulfill your requests, the Extension sends page data (IDs and labels of interactive elements) to the LLM provider you have selected in the settings:
- **Google Gemini**: Data is sent to Google's Generative AI servers (using OpenAI-compatible endpoints).
- **OpenAI**: Data is sent to OpenAI's API servers.
- **OpenRouter**: Data is sent to OpenRouter's aggregation servers.
- **Ollama**: Data is sent to your local instance (usually `localhost`).

No data is sent to any other third parties.

## 4. User Rights
Since we do not store any personal data on our servers, there is no data to delete or modify. You can clear your local chat history and API keys at any time through the Extension's settings.

## 5. Contact
If you have any questions, please contact the developer via the official repository.
