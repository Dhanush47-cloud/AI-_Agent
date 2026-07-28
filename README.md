

# 🤖 Hospital AI Assistant – Symptom Classifier
 
An intelligent assistant that helps hospitals classify patient symptoms using Google’s Gemini LLM and LangGraph. It guides users to the correct department: General, Emergency, or Mental Health.


---

## 📌 Features

──────────────

🗣️ Conversational symptom input

🤖 AI-based symptom classification

🏥 Automated routing to the correct care path

🧩 Modular architecture using LangGraph



---

## 🧠 Tech Stack

──────────────

Python 3.x

LangChain – LLM orchestration

LangGraph – Graph-based flow control

Google Generative AI (Gemini 1.5 Flash) – LLM engine



---

## 🚀 How It Works

──────────────

1. User inputs a symptom


2. Gemini LLM classifies it as:

General

Emergency

Mental Health



3. The system routes to the appropriate response node


4. A final output is printed to guide the patient




---

## 🧪 Sample Interaction

──────────────

Welcome to XYZ Hospital, please enter your symptom: I have chest pain  
LLM Classifies the symptoms as: Emergency  
Final Output: 'I have chest pain' is a medical emergency! Seek immediate help.


---

##  Setup Instructions

──────────────

1. Clone the Repository

git clone https://github.com/your-username/hospital-ai-assistant.git
cd hospital-ai-assistant

2. Install Dependencies

pip install -r requirements.txt

3. Get Your Gemini API Key

Visit Google AI Studio

Create a project and obtain your Gemini API Key

Set it as an environment variable:


export GEMINI_API_KEY="your-api-key-here"

You can also use a .env file (make sure it’s listed in .gitignore).

4. Run the Application

python main.py


--
