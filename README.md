# 🚀 ARIN BILLBOT

AI-powered billing and dashboard management system with automated backend and frontend startup.

---

## 📌 Features

✅ Automatic Python environment setup  
✅ Automatic dependency installation  
✅ FastAPI backend startup  
✅ React/Vite frontend startup  
✅ Local + Network access URLs  
✅ Beginner-friendly one-click startup script  

---

⚙️ Prerequisites

Install the following software before running the project:

🐍 Python

Download Python:
https://www.python.org/downloads/

✔ Important: Enable "Add Python to PATH" during installation.

🟢 Node.js

Download Node.js:
https://nodejs.org/

🚀 Getting Started
Step 1: Clone Repository
git clone https://github.com/your-username/arin-billbot.git
cd arin-billbot
Step 2: Run Startup Script

Simply double-click:

startup.bat

OR run from terminal:

startup.bat
🔥 What the Script Does
Backend
Creates virtual environment (.venv)
Installs Python dependencies
Starts FastAPI server

Runs on:

http://localhost:5000
Frontend
Installs npm dependencies if missing
Starts React/Vite dashboard

Runs on:

http://localhost:5173
🌐 Access URLs
Local
http://localhost:5173
Network
http://YOUR-IP:5173

Example:

http://192.168.1.5:5173
🛠 Backend Command
python -m uvicorn main:app --reload --host 0.0.0.0 --port 5000
🧪 Frontend Command
npm run dev -- --host
⚠️ Notes
Keep terminal windows open while using the application.
First startup may take a few minutes depending on internet speed.
If frontend does not load immediately, wait a few seconds and refresh the browser.
❌ Common Errors
Python Not Found

Install Python and enable:

Add Python to PATH
Node.js Not Found

Install latest Node.js version.

Dependency Installation Failed

Check:

Internet connection
Firewall restrictions
Correct Python version
🧰 Tech Stack
Backend
Python
FastAPI
Uvicorn
Frontend
React
Vite
Node.js
👨‍💻 Developed By

ARIN BILLBOT Team
