# 🚀 CodeQuest – Coding Challenges Web App

CodeQuest is a Flask-based web application where users can register, log in, solve coding challenges, and compete on a leaderboard.

---

## 📌 Features

- 📝 User Authentication (Sign Up / Log In / Log Out)
- 🧠 Coding Challenge Dashboard
- 🧩 Challenge Attempt Interface
- 🏆 Leaderboard Sorted by Points
- 💡 Session Management to Keep Users Logged In

---

## ⚙️ Tech Stack

- Python (Flask)
- HTML + Jinja2 Templates
- CSS (custom-styled UI)
- MySQL (User and Challenge data)

---

## 🔧 Installation & Running Locally

```bash
# 1. Clone the repository
git clone https://github.com/your-username/codequest.git
cd codequest

# 2. Create and activate a virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install flask mysql-connector-python

# 4. Set up your MySQL database
# Run schema.sql to create 'users' and 'challenges' tables (add your schema file)

# 5. Run the application
python app.py
