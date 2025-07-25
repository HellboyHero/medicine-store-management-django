# Medicine Store Management System (Django)

## 📌 Overview
The **Medicine Store Management System** is a web-based application built using **Django** to manage a medical store's operations efficiently.  
It helps store owners and pharmacists to keep track of medicines, sales, stock, and customers in one place.

---

## 🚀 Features
- **Medicine Management**: Add, update, and remove medicines.
- **Stock Management**: Monitor stock levels and receive low-stock alerts.
- **Customer Management**: Maintain customer details and purchase history.
- **Billing System**: Generate invoices for customers.
- **User Authentication**: Secure login for admin and staff.
- **Reports**: Daily/Monthly sales reports.

---

## 🛠 Tech Stack
- **Backend**: Python (Django)
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (default, can be changed to MySQL/PostgreSQL)
- **Version Control**: Git

---

## 📂 Project Setup
### 1. Clone the repository
git clone https://github.com/your-username/medicine-store-management-django.git
cd medicine-store-management-django
2. Create Virtual Environment

python -m venv env
source env/bin/activate   # For Linux/macOS
env\Scripts\activate      # For Windows
3. Install Dependencies

pip install -r requirements.txt
4. Run Migrations

python manage.py makemigrations
python manage.py migrate
5. Create Superuser

python manage.py createsuperuser
6. Run Server
python manage.py runserver
Access the app at: http://127.0.0.1:8000

📷 Screenshots
(Add screenshots of your app here for better presentation)

👤 Author
Your Name – GitHub Profile

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
