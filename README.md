# Generative-AI-Gemini-Chat-bot

# Gemini ChatBot - Your AI-Powered Conversational Partner 🧑‍💻

Welcome to **Gemini ChatBot**, an advanced AI-powered chatbot built using **Google Gemini** and deployed with **Streamlit**! 🚀

Gemini ChatBot is designed to provide intelligent and engaging conversations, whether you're seeking answers, assistance, or just a fun chat. Powered by cutting-edge AI technology, it uses the **Gemini** generative model for high-quality, dynamic responses. Whether you're a developer, researcher, or just an AI enthusiast, Gemini ChatBot is ready to interact and assist you!

## Features ✨
- **AI-powered Conversations**: Get intelligent, context-aware responses powered by the Gemini model.
- **Real-time Interaction**: Chat with Gemini in real time using Streamlit’s simple and user-friendly interface.
- **Seamless Setup**: Easy-to-use environment, ready to run with minimal configuration.
- **Start New Conversations**: The option to reset the chat and start fresh with a simple click.
- **Easy Deployment**: Simple deployment process using GitHub and Streamlit sharing.

## 🛠️ Technologies Used
- **Gemini (Google AI)**: High-quality, generative AI model.
- **Streamlit**: A fast and simple framework for building beautiful data apps.
- **Python**: The backbone of the chatbot logic and functionality.
- **dotenv**: Secure management of API keys.

## 🚀 Getting Started

### Prerequisites
Before you begin, ensure that you have the following installed:
- Python 3.7 or higher
- A Google API key for Gemini (You can obtain this from [Google Generative AI API](https://generativeai.google.com/))
- Streamlit (For running the web app locally)
- `dotenv` library to load environment variables securely

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gemini-chatbot.git
   cd gemini_pro_chatbot
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up your **Google API Key** in a `.env` file:
   ```plaintext
   GOOGLE_API_KEY=your_google_api_key
   ```

5. Run the app locally:
   ```bash
   streamlit run app.py
   ```

### Deploy to Streamlit Sharing
- Push your code to GitHub and link it to [Streamlit Sharing](https://streamlit.io/sharing) to deploy it in the cloud for free.

## 🧑‍💻 How It Works
1. **User Input**: The user types a message into the Streamlit chat interface.
2. **Gemini AI**: The input is sent to the Gemini AI model, which generates a response based on the input context.
3. **Response Display**: The generated response is displayed back to the user in real-time.
4. **New Chat Option**: Users can reset the conversation at any time with a simple button.

## 📝 Example Chat

**User**: "What is the weather like today?"  
**Gemini**: "I’m afraid I can't check the weather for you, but I can help with a wide range of other topics!"

---

## 📂 File Structure

```
gemini-chatbot/
│
├── app.py            # Streamlit app that runs the chatbot interface
├── .env              # Store your Google API key securely
├── requirements.txt  # List of dependencies
├── README.md         # This file

```

### Happy Chatting with Gemini! 🧑‍💻

---
