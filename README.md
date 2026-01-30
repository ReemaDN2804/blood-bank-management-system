---

# Blood Bank Management System

A **secure, role-based web application** for managing blood donors, receivers, and blood inventory, built using **Flask** and **MySQL** with a clean MVC-style structure.

---

## 🔹 Key Highlights

* **End-to-end CRUD system** for donors, receivers, and blood inventory
* **Secure authentication** with password hashing (**bcrypt**) and session management
* **Role-based access control** (Admin vs User)
* **Search & filtering** by blood group and name
* **Eligibility validation** for donors (age & weight checks)
* **Admin dashboard** with real-time system statistics

---

## 🛠 Tech Stack

* **Backend:** Flask (Python)
* **Frontend:** HTML, CSS, JavaScript
* **Database:** MySQL
* **Security:** bcrypt, Flask sessions

---

## 📂 Architecture

* Modular Flask routes
* Jinja2 template inheritance (`base.html`)
* Separation of concerns:

  * `templates/` → UI
  * `static/` → CSS & JS
  * `app.py` → backend logic

---

## ⚙️ Setup (Quick)

```bash
pip install -r requirements.txt
python app.py
```

Runs locally at `http://127.0.0.1:5000/`

---

## 🎯 Why This Project Matters

This project demonstrates:

* **Backend web development fundamentals**
* **Secure authentication & authorization**
* **Relational database design**
* **Clean code structure suitable for production systems**

---

## 🚀 Future Scope

* Blood compatibility matching
* Notification system
* Cloud deployment

---