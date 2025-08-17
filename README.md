# ✋ SignEase 🤟
_A Sign Language Recognition & Communication Aid_

SignEase is a **PHP + MySQL web application** designed to bridge the communication gap for the hearing/speech-impaired community.  
It provides an intuitive platform where users can register, sign in, and interact, while administrators manage posts, categories, and users.

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
```
SignEase/
│── index.php             # Home page
│── signin.php            # User login
│── signup.php            # User registration
│── sign.php              # Sign-related feature page
│── about.php             # About page
│── contact.php           # Contact page
│── services.php          # Services page
│── Database/
│   └── signease.sql      # Database schema
│── admin/                # Admin dashboard
│   ├── add-post.php
│   ├── edit-post.php
│   ├── manage-users.php
│   ├── config/
│   │   └── constants.php
│   └── ... (other CRUD logic files)
```

---

## ⚡ Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/ramgopal-m/SignEase.git
cd SignEase
```

### 2️⃣ Setup Database
1. Open **phpMyAdmin** (or MySQL CLI)  
2. Create a new database, e.g. `signease`  
3. Import the SQL file from:  
   ```
   Database/signease.sql
   ```

### 3️⃣ Run the Project
1. Place the project folder inside your web server directory:  
   - For **XAMPP** → `htdocs/SignEase/`  
   - For **WAMP/LAMP** → `www/SignEase/`  
2. Start **Apache** and **MySQL** from your server control panel.  
3. Open in browser:  
   ```
   http://localhost/SignEase
   ```

---

## 👨‍💻 Author
**Ramgopal Mukhamatam**  
- GitHub: [@ramgopal-m](https://github.com/ramgopal-m)  
- Email: ramgopal_mukhamatam@srmap.edu.in  

---

⭐ If you found this project useful, don’t forget to **star the repo**!
