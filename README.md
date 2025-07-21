---

🤖 Hospital AI Assistant – Symptom Classifier

An intelligent assistant for hospitals that classifies patient symptoms using Google’s Gemini LLM and LangGraph. The assistant guides patients to the appropriate department: General, Emergency, or Mental Health.


---

📌 Features

🗣️ Conversational symptom input

🤖 AI-based symptom classification

🏥 Automated routing to the correct care path

🧩 Modular architecture using LangGraph



---

🧠 Tech Stack

Python 3.x

LangChain – LLM orchestration

LangGraph – Graph-based flow control

Google Generative AI (Gemini 1.5 Flash) – LLM engine



---

🚀 How It Works

1. User inputs a symptom


2. Gemini LLM classifies it into one of three categories:

General

Emergency

Mental Health



3. The system routes the symptom to the appropriate response node


4. Final output is printed to guide the patient




---

🧪 Sample Interaction

Welcome to XYZ Hospital, please enter your symptom: I have chest pain  
LLM Classifies the symptoms as: Emergency  
Final Output: 'I have chest pain' is a medical emergency! Seek immediate help.


---

🔧 Setup Instructions

1. Clone the Repository

git clone https://github.com/your-username/hospital-ai-assistant.git
cd hospital-ai-assistant

2. Install Dependencies

pip install -r requirements.txt

3. Get Your Gemini API Key

Visit Google AI Studio

Create a project and get your Gemini API Key

Set it as an environment variable:


export GEMINI_API_KEY="your-api-key-here"

Alternatively, you can use a .env file (make sure it’s listed in .gitignore).

4. Run the Application

python main.py


---

🔐 API Key Safety

> ⚠️ Important: Never commit your API key to GitHub.
Use environment variables or a .env file to keep your credentials safe.




---

📄 License

This project is licensed under the MIT License.
See the LICENSE file for more details.


---



