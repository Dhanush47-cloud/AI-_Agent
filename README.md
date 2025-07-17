# 🤖 Hospital AI Assistant – Symptom Classifier
An intelligent hospital assistant that helps classify patient symptoms using Google’s Gemini LLM and LangGraph. This assistant guides users to the right department based on their input symptoms: General, Emergency, or Mental Health.

📌 Features
Conversational symptom input

AI-based symptom classification

Automated routing to the correct care path

Modular architecture using LangGraph

🧠 Tech Stack
Python 3.x

LangChain – LLM orchestration

LangGraph – Graph-based flow control

Google Generative AI – Gemini 1.5 Flash model

🚀 How It Works
User is asked to input a symptom.

The Gemini LLM classifies it into:

General

Emergency

Mental Health

The system routes the patient to the correct response node.

Final response is printed for user guidance.

🔧 Setup Instructions
Install dependencies
Use pip to install required libraries (see requirements.txt).

Get your Gemini API key

Visit Google AI Studio

Create a project and get your API key

Set it as an environment variable

Run the application

🧪 Sample Interaction
pgsql
Copy
Edit
Welcome to xyz hospital, please enter your symptom: I have chest pain  
LLM Classifies the symptoms as: Emergency  
Final Output: 'I have chest pain' is a medical emergency! Seek immediate help.
🔐 API Key Safety
Important: Never commit your API key to GitHub. Use environment variables or a .env file (and make sure it’s listed in .gitignore).

📃 License
This project is licensed under the MIT License.
