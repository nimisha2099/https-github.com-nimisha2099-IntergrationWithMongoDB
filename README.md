<div align="center">

# 🧠 <span style="color:#199f4b;">INTEGRATION WITH MONGODB & FLASK</span>

![Python 3.10](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Framework-lightgrey?logo=flask)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen?logo=mongodb)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

</div>

---

## 📦 Project Overview

Elegant, minimal project showing end-to-end CRUD integration between a Flask backend and MongoDB database. Ideal as a learning starter or a foundation for robust RESTful APIs, this repo highlights clear data flows, modular structure, and seamless DB operations using PyMongo.

---

## ⚙️ Tech Stack / Dependencies

- Python 3.10+
- Flask
- Flask-PyMongo or PyMongo
- Jinja2
- MongoDB

---

## 📁 Folder Structure
```bash
Integrationwithmongodb_flask/
├── app.py                     # Main Flask application entry point
├── /templates                 # HTML templates (Jinja2)
├── /static                    # CSS, JS, and image files
├── /modules                   # Core business logic
│   ├── user_management.py     # Handles user CRUD operations
│   ├── db_integration.py      # MongoDB connection & data utilities
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation

```
---

## 🚀 Setup & Installation

#### 1️⃣ Clone the Repo

git clone https://github.com/KavanKumarpatel/Integrationwithmongodb_flask.git
cd Integrationwithmongodb_flask

#### 2️⃣ Create Virtual Environment (recommended)

python -m venv venv
source venv/bin/activate # On Windows: venv\Scripts\activate


#### 3️⃣ Install Dependencies

pip install -r requirements.txt


#### 4️⃣ Setup MongoDB

- Ensure MongoDB is running locally or provide your cloud MongoDB URI in the config.

#### 5️⃣ Run the App


#### 4️⃣ Setup MongoDB

- Ensure MongoDB is running locally or provide your cloud MongoDB URI in the config.

#### 5️⃣ Run the App


#### 4️⃣ Setup MongoDB

- Ensure MongoDB is running locally or provide your cloud MongoDB URI in the config.

#### 5️⃣ Run the App


---

## 🧱 Module-wise Structure

<hr/>

### <span style="color:#1976d2">🔵 User Management Module</span>

#### **Purpose**
Manage user accounts: registration, login, profile editing, and authentication.

#### **Core Features**
- 🟢 User Registration (`/register`)
- 🟢 User Login/Logout (`/login`, `/logout`)
- 🟡 Edit/Delete Profile (under improvement)
- 🔴 Password Reset (planned)

#### **Interactions**
Works with the database integration module to CRUD user data, and templates for front-end display.

#### 🧰 Libraries Used
- Flask-Login
- Flask
- Jinja2

---

### <span style="color:#388e3c">🟢 Database Integration Module</span>

#### **Purpose**
Handle all MongoDB operations (connect, CRUD, queries) using PyMongo or Flask-PyMongo.

#### **Core Features**
- 🟢 Establish and maintain database connection
- 🟢 Perform CRUD actions on user/tasks collections
- 🟡 Validation & data modeling (improving)
- 🔴 Advanced aggregation & pipeline (planned)

#### **Interactions**
Called by all modules needing persistent storage.

#### 🧰 Libraries Used
- PyMongo / Flask-PyMongo

---

### <span style="color:#ff9800">🟠 Task/Notes Feature Module (Sample)</span>

#### **Purpose**
Enable users to create, view, update, and delete notes/tasks linked to their account.

#### **Core Features**
- 🟢 Add/View Tasks
- 🟡 Edit Tasks
- 🔴 Attachments & Due Date (future)

#### **Interactions**
Uses User module for association and Database module for storage.

#### 🧰 Libraries Used
- Flask
- PyMongo

---

## 📚 Global Libraries Used

- Flask
- Flask-PyMongo
- Jinja2
- PyMongo

---

## 📝 Contribution Guide

1. **Fork** this repo.
2. **Clone** it locally.
3. Create your branch: `git checkout -b feature/YourFeature`
4. Commit and push changes: `git commit -m "Describe feature"` then `git push`
5. Start a pull request—let’s build this together!

---

## 👤 Author / Credits

[Nimisha Dabhi](https://github.com/nimisha2099)

---

## 📜 License

MIT License. See [LICENSE](LICENSE) for details.

---

<div align="center">
  <sub>Made with 💡 Flask + MongoDB</sub>
</div>

