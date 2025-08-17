# ✋ SignEase 🤟
_A Sign Language Recognition & Communication Aid_

SignEase is a **PHP + MySQL web application** designed to bridge the communication gap for the hearing/speech-impaired community.  
It enables users to sign up, log in, share posts, and interact seamlessly with an easy-to-use interface.

---

## 🚀 Features
- 🔐 User authentication (Sign up, Sign in, Logout)
- 📝 Create, edit, and delete posts
- 📂 Categories for organizing content
- 👨‍💼 Admin panel for managing users, posts, and categories
- 💾 MySQL database integration

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL  

---

## 📂 Project Structure

SignEase/
│── index.php # Home page
│── signin.php # User login
│── signup.php # User registration
│── sign.php # Sign-related feature page
│── about.php # About page
│── contact.php # Contact page
│── services.php # Services page
│── Database/
│ └── signease.sql # Database schema
│── admin/ # Admin dashboard
│ ├── add-post.php
│ ├── edit-post.php
│ ├── manage-users.php
│ ├── config/
│ │ └── constants.php
│ └── ... (other CRUD logic files)


---

## ⚡ Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/ramgopal-m/SignEase.git
cd SignEase

### 2️⃣ Setup Database

Open phpMyAdmin (or MySQL CLI)

Create a new database, e.g. signease

Import the SQL file:

Database/signease.sql

### 3️⃣ Run the Project

Place the project folder inside your web server directory:

For XAMPP → htdocs/SignEase/

For WAMP/LAMP → www/SignEase/

Start Apache and MySQL from your server control panel.

Open in browser:
  
