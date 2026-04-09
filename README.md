# 🛡 FalconStrix – Real-Time Web-Based TCP Port Scanner

FalconStrix is a full-stack cybersecurity lab tool built with Flask and SocketIO that performs real-time TCP port scanning with authentication, live progress tracking, banner grabbing, and scan history logging.

⚠️ This tool is for educational and authorized security testing purposes only.

---

## 🚀 Features

- 🔐 User Authentication System (Login Required)
- ⚡ Real-Time Port Scanning (WebSocket Powered)
- 📊 Live Progress Bar
- 🗂 Scan History Stored in SQLite Database
- 🔎 Banner Grabbing (Service Detection)
- 🧵 Multithreaded Scanning Engine
- 🎨 Modern Dark Cybersecurity UI
- 📁 Structured Flask Project Architecture

---

## 🧠 Technologies Used

- Python 3
- Flask
- Flask-SocketIO (threading mode)
- Flask-Login
- Flask-SQLAlchemy
- SQLite
- HTML / CSS / JavaScript
- ThreadPoolExecutor

---

##  Installation

### Clone Repository

### git clone https://github.com/your-username/falconstrix.git
cd falconstrix


### Create Virtual Environment
python -m venv .venv
.\.venv\Scripts\activate


### Install Requirements
pip install -r requirements.txt


### Run Application
python app.py
Application will run at:
http://127.0.0.1:5000

### Default Login
Username: admin
Password: admin123

#### Safe Testing
To test open ports locally:
 python -m http.server 8000
scan:
Host: 127.0.0.1
Start: 8000
End: 8005


📁 Project Structure
FalconStrix/
│
├── app.py
├── requirements.txt
│
├── templates/
│   ├── login.html
│   ├── dashboard.html
│   └── history.html
│
└── static/
    ├── style.css
    └── script.js
⚠️ Disclaimer
This project is developed strictly for:

Educational use

Cybersecurity lab environments

Authorized penetration testing

Do NOT scan systems without explicit permission.

🎯 Future Enhancements
Password hashing (bcrypt)

Export results to CSV

Dashboard analytics charts

Role-based access control

Deployment to cloud (Render / Railway)

Vulnerability intelligence integration

👨‍💻 Author
Muhammad Zaid Saqib
Cybersecurity & Systems Enthusiast

