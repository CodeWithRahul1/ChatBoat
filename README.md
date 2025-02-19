🤖 Your Chat Boat ChatBot 🧠
A Streamlit-based chatbot using LLaMA 3.3-70B and LangChain Groq to provide AI-powered conversations.

📌 Features
    ✅ Interactive Chat Interface – Ask questions and get AI-powered responses.
    ✅ Chat History – Maintains conversation history for context-aware replies.
    ✅ Document Store – Stores past interactions to improve responses.
    ✅ Custom Styling – Enhanced UI with CSS for a better experience.
    ✅ Secure API Key Handling – Uses .env file to protect credentials.
    ✅ Clear Chat Option – Easily reset the conversation with a button click.

🛠️ Requirements
Ensure you have the following installed:

    Python 3.8+
    Streamlit
    LangChain Groq
    python-dotenv
🔧 Installation

1️⃣ Clone the repository

git clone https://github.com/your-repo/chatbot.git
cd chatbot

2️⃣ Create and activate a virtual environment

    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    venv\Scripts\activate     # On Windows


3️⃣ Install dependencies
    pip install -r requirements.txt

GROQ_API_KEY=your_groq_api_key

🚀 Run the Chatbot
    streamlit run ChatBoat.py