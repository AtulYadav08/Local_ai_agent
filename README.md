# Local_ai_agent

# 🧠 CareerGuide AI — Local Career Counseling Assistant

**CareerGuide AI** is a privacy-first, AI-powered career guidance web application built with **Flask**, **LangChain**, and **Ollama (LLaMA 3.1)**. It runs **entirely on your local machine** without any internet-based AI API — perfect for offline environments.

---

## ✨ Features

- 💬 **AI Chatbot** using locally hosted LLaMA 3.1 (via Ollama)
- 🧠 Contextual Q&A powered by LangChain
- 🔄 Reset sessions and start new conversations easily

---

## 🖥️ Live Preview

Once set up, visit: [http://localhost:5000](http://localhost:5000)

---

## 📁 Project Structure

career-guide-ai/
├── main.py # Flask application
├── requirements.txt # Python dependencies
├── templates/
  └── index.html # Frontend HTML


---

## ⚙️ Setup Instructions

Follow these steps to run the project on your machine:

### 1. 🧩 Install Ollama

Download and install Ollama from the official website:  
👉 [https://ollama.ai](https://ollama.ai)

### 2. 📥 Pull the LLaMA 3.1 Model

Open your terminal and run:


ollama pull llama3.1

Then start the model:
ollama run llama3.1

Keep this running in a terminal tab or background process.

3. 📦 Clone the Repository

git clone https://github.com/AtulYadav08/Local_ai_agent
cd Local_ai_agent

4. 🧪 Create & Activate Virtual Environment
# Create virtual environment
python -m venv venv

# Activate it
# On Windows
venv\Scripts\activate

# On macOS/Linux
source venv/bin/activate

5. 📦 Install Dependencies
pip install -r requirements.txt

6. ▶️ Run the Application
python main.py
Visit: http://localhost:5000

🛠 Technologies Used
Python 3.11+

Flask 2.3.3

LangChain (langchain-core, langchain-ollama)

Ollama + LLaMA 3.1

✅ Requirements
Python 3.11 or higher

Ollama installed and LLaMA 3.1 pulled

Virtual environment with Flask and LangChain installed

🧰 Troubleshooting
Problem	Solution
Ollama not responding	Ensure ollama run llama3.1 is running
Model not found	Re-run: ollama pull llama3.1
Port conflict	Change port in main.py (app.run(port=5001))
Session not working	Ensure SECRET_KEY is set in Flask app

📸 Screenshots

![image alt](https://github.com/AtulYadav08/Local_ai_agent/blob/063b029f4a1332451ed160e6cdabeb467435adf6/static/Screenshot%202025-06-16%20172438.png)



🙏 Acknowledgments
LangChain

Ollama

Meta LLaMA 3

