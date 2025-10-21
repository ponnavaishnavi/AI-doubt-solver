🧠 AI-Powered Doubt Solver

An intelligent AI-based platform where students can upload or type questions (text or image), and get instant solutions or explanations in real time.

🚀 Built with Flask (Backend), HTML/CSS/JS (Frontend), and OpenAI GPT API for natural language understanding and problem solving.

✨ Features

🧩 Instant AI Answers — Enter or upload a question to get explanations powered by GPT.

🧠 Smart Understanding — Uses NLP to interpret and solve even complex text-based questions.

🖼️ OCR Support (optional) — Can extract text from uploaded question images (using Tesseract / EasyOCR).

⚡ Real-Time Response — Built for quick tutoring and study help.

🔒 Secure API Key Handling — Uses .env file to protect your OpenAI key.

🏗️ Project Structure
AI-doubt-solver/
│
├── backend/
│   ├── app.py               # Flask backend (API + AI logic)
│   ├── requirements.txt     # Backend dependencies
│   ├── .env                 # API key (not uploaded)
│
├── frontend/
│   ├── index.html           # Main webpage
│   ├── script.js            # API call logic
│   ├── style.css            # Styling for UI
│
├── .gitignore               # Ignores .env, __pycache__, node_modules
└── README.md                # Project description

⚙️ Tech Stack
Layer	Technology
Frontend	HTML, CSS, JavaScript
Backend	Python (Flask, Flask-CORS)
AI Engine	OpenAI GPT API
Optional	Tesseract OCR / EasyOCR
Environment	Python-dotenv
🚀 Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/AI-doubt-solver.git
cd AI-doubt-solver/backend

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Add Your OpenAI API Key

Create a .env file inside backend/ and add:

OPENAI_API_KEY=sk-your-api-key-here

4️⃣ Run Backend
python app.py


Your backend will start at http://127.0.0.1:5000

5️⃣ Run Frontend

Open frontend/index.html in your browser.

💬 Example Output

Input:

Explain Newton’s third law of motion.

AI Response:

Newton’s third law states that for every action, there is an equal and opposite reaction. This means that forces always occur in pairs — when one object exerts a force on another, the second object exerts an equal and opposite force back on the first.

🔐 .env File

The .env file keeps sensitive keys secure and must never be uploaded to GitHub.
Add this to .gitignore:

.env
__pycache__/
node_modules/

🧩 requirements.txt
flask
flask-cors
openai
python-dotenv

🧠 Future Enhancements

📸 Add full OCR (Image-to-Text) support

🎙️ Add voice input and speech-based answers

📚 Include subject categorization (Math, Science, English)

🧾 Save previous questions & explanations
