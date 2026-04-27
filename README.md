MindMate AI
An AI-powered Mood-Aware Assistant

MindMate AI is an intelligent conversational assistant designed to help users reflect on their emotions, gain insights, and receive supportive responses through AI-driven dialogue.

The application provides a simple and interactive interface built with Streamlit, enabling real-time conversations powered by high-performance language models via the Groq API.

Features:

AI-powered conversational assistant
Mood-aware interaction system
Ultra-fast responses using Groq inference
Simple and clean Streamlit interface
Secure API key usage via environment variables
Interactive UI for seamless user experience

Tech Stack

Frontend
Streamlit
Backend / AI
Python
Groq API (LLM inference)
Libraries
streamlit
groq
python-dotenv

📂 Project Structure
MindMate-AI
│
├── app.py                # Main Streamlit application
├── requirements.txt      # Python dependencies
├── .env                  # API keys (not pushed to GitHub)
├── utils.py              # Helper functions (optional)
├── assets                # Images / UI resources
└── README.md

⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/yourusername/mindmate-ai.git
cd mindmate-ai
2️⃣ Create Virtual Environment (Recommended)
python -m venv venv

Activate it:
Windows
venv\Scripts\activate
Mac/Linux
source venv/bin/activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Add Groq API Key

Create a .env file:

GROQ_API_KEY=your_api_key_here

You can get an API key from
https://console.groq.com

5️⃣ Run the Application
streamlit run app.py

The app will open in your browser:

http://localhost:8501
💡 How It Works

1️⃣ User enters a message through the Streamlit interface
2️⃣ The message is sent to the Groq LLM API
3️⃣ The model processes the request and generates a response
4️⃣ The response is displayed instantly in the UI

🔮 Future Improvements

Emotion detection from user input

Personalized AI responses

Chat history storage

Mobile-friendly UI

Mental health insights dashboard

👨‍💻 Author

Vikas Varma

GitHub: https://github.com/Vikasvarma-hub
