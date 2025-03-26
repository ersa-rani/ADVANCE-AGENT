# 🤖 Greeting and Weather Bot with Chainlit & Gemini API

This repository contains a simple chatbot built using Chainlit and Gemini API, designed to greet users and provide weather updates. ☀️🌍

## ✨ Features
- 👋 Greets users with "Salam from Ersa Rani."
- ⛅ Provides weather updates for a specified location.
- 👋 Says "Allah Hafiz from Ersa Rani" when a user says goodbye.
- 🚫 Limits responses to greetings and weather queries.
- 🔐 Uses OAuth authentication with GitHub.
- 📝 Maintains chat history using Chainlit's session management.

## 🛠 Tech Stack
- 🐍 Python
- 🔗 Chainlit
- 🤖 OpenAI API (Gemini API)
- 🔑 Dotenv (for environment variable management)

## 📥 Installation
### Prerequisites
Make sure you have Python installed on your machine. 🖥️

### Steps
1. 📂 Clone the repository:
   ```sh
   git clone https://github.com/ersa-rani/ADVANCE-AGENT.git
   cd ADVANCE-AGENT
   ```
2. 📦 Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. 🔐 Set up environment variables:
   - Create a `.env` file and add your API key:
     ```sh
     GEMINI_API_KEY=your_api_key_here
     ```
4. ▶️ Run the application:
   ```sh
   python main.py
   ```

## ⚙️ How It Works
- 🤖 The bot initializes using the Gemini API as the language model.
- 📩 When a user sends a message:
  - If it's a greeting, the bot responds with "Salam from Ersa Rani."
  - If it's a weather-related query, it fetches the weather using `get_weather()`.
  - If the user says "bye," it responds with "Allah Hafiz from Ersa Rani."
  - For any other questions, it replies: "Ersa is here just for greeting and weather, I can't answer anything else, sorry."

## 🔐 OAuth Authentication
- 🔗 The bot supports OAuth authentication with GitHub.
- 📊 Handles the OAuth callback and prints user data for debugging.

## 🤝 Contributions
Feel free to contribute by submitting issues or pull requests. 🚀

## 📜 License
This project is licensed under the MIT License. ✅

---
Developed by Ersa Rani 💡

