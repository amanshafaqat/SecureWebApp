🔐 Secure Web Application Against SQL Injection Attacks
This project demonstrates a secure login/register web application built using Flask (Python), highlighting how SQL Injection (SQLi) vulnerabilities can occur and how to prevent them using prepared statements, input sanitization, and secure coding practices.

📌 Features
🧾 User Registration and Login system
🔐 Demonstration of SQL Injection vulnerability
✅ Protection via Prepared Statements (Parameterized Queries)
🛡️ Input Sanitization to block SQL metacharacters
🧠 Admin Panel to view logged SQLi attempts
🗂️ Attempt Logging for every login
🎨 Responsive and colorful user interface
🔓 Role-based session handling (admin & users)
🚀 Technologies Used
Python 3
Flask
SQLite
HTML5/CSS3
Jinja2 Templates
VS Code
📁 Project Structure
SecureWebApp_SQLi/ │ ├── app.py # Main Flask Application ├── users.db # SQLite Database ├── injection_attempts.log # Log file for suspicious login attempts ├── templates/ │ └── auth.html # Login/Register + Dashboard UI │ └── report.html # Admin Panel to view SQLi logs ├── static/ │ └── styles.css # Custom CSS styling ├── README.md # This file └── requirements.txt # Python dependencies 📄 License This project is for educational and demonstration purposes only.

🙋‍♂️ Author
Aman Shafaqat
Software Engineering Student
