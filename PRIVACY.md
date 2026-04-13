# Privacy Policy for WebDriver AI

**Last updated: April 12, 2026**

## 1. Overview
WebDriver AI ("the Extension") is committed to protecting your privacy. This policy explains what data we process and how it is handled.

## 2. Data Collection
We do **not** collect, store, or sell any personal data.
- **Browsing Data**: The Extension analyzes the content of the active tab only when you interact with the agent. This analysis is performed locally in your browser.
- **Login Information**: If you use "Google Login (OAuth2)", we receive an authentication token from Google. This token is stored locally in your extension's private storage and is only used to authenticate your requests to the Gemini API.

## 3. Data Processing and Transmission
To fulfill your requests, the Extension sends page data (IDs and labels of interactive elements) to the LLM provider you have selected in the settings:
- **Google Gemini**: Data is sent to Google's Generative AI servers.
- **OpenAI**: Data is sent to OpenAI's API servers.
- **Ollama**: Data is sent to your local instance (usually `localhost`).

No data is sent to any other third parties.

## 4. User Rights
Since we do not store any personal data on our servers, there is no data to delete or modify. You can clear your local chat history and authentication tokens at any time through the Extension's settings.

## 5. Contact
If you have any questions, please contact the developer via the official repository.
