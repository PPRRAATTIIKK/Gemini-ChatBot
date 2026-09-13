# 🤖 Gemini Chatbot

A simple and interactive AI chatbot built with **Python, Streamlit, and Google Gemini API**. The application provides a web-based chat interface where users can interact with Google's Gemini language model and receive AI-generated responses in real time.

## 🚀 Features

* 💬 Interactive chatbot interface using Streamlit
* 🤖 AI-powered responses using Google Gemini
* 🧠 Maintains conversation history during the session
* ⚡ Real-time response generation
* 📱 Clean and responsive web interface
* 🔐 Secure API key management using environment variables

## 🛠️ Technologies Used

* **Python**
* **Streamlit** – Web interface and application framework
* **Google Generative AI** – Gemini API for AI responses
* **Python-dotenv** – Environment variable management

## 📂 Project Structure

```text
Gemini-ChatBot/
│
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
├── .gitignore          # Files excluded from version control
├── LICENSE             # Project license
└── README.md           # Project documentation
```

## 💡 How It Works

The application follows a simple workflow:

1. The user enters a message through the Streamlit chat interface.
2. The application sends the message to the Google Gemini API.
3. Gemini processes the request and generates an AI response.
4. The response is displayed in the chat interface.
5. Conversation history is maintained using Streamlit session state.

## 🔑 API Key Management

The application uses the following environment variable:

| Variable         | Description                                  |
| ---------------- | -------------------------------------------- |
| `GOOGLE_API_KEY` | API key used to access the Google Gemini API |

The API key is kept separate from the source code to protect sensitive credentials.

## 🖥️ Application Interface

The chatbot provides:

* A clean chatbot interface
* Conversation history
* A user-friendly chat input field
* AI-generated responses
* Continuous conversation within the active session

## 🔒 Security

The Gemini API key is not hard-coded into the application.

The `.gitignore` file excludes:

```text
.env
```

This helps prevent the local environment file and API credentials from being accidentally committed to version control.

## 📋 Requirements

* Python 3.x
* Internet connection
* Google Gemini API key
* Python packages listed in `requirements.txt`

## 🔮 Future Improvements

* Support for multiple Gemini models
* Chat export functionality
* Persistent conversation storage
* User authentication
* Custom chatbot personalities
* Streaming AI responses
* File and document-based conversations
* Voice input and output
* Enhanced UI customization

## 📜 License

This project is distributed under the license included in the repository.

## 👨‍💻 Author

**Pratik Kumar**

Built using **Python, Streamlit, and Google Gemini AI**.
