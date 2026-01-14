🍽️ FreshFood Pro – Full Stack Restaurant Management System

FreshFood Pro is a full-stack web application designed to digitize and automate restaurant operations such as menu management, table booking, food ordering, and user authentication.
The project is inspired by the Little Lemon case study and enhanced with modern backend practices and RESTful APIs.

This system is built with scalability and real-world restaurant workflows in mind, making it suitable for learning, academic projects, and portfolio showcasing.

🚀 Features
🔐 User & Admin Management

User registration and login

Role-based access (Admin / Customer)

Secure authentication system

Django Admin Panel support

📋 Menu Management

Add, update, and delete menu items

Categorized food items

Price and availability management

REST API access for menu data

📅 Table Booking System

Customers can book tables

Booking date and time validation

Prevents double bookings

Admin can view and manage bookings

🛒 Food Ordering (Optional Extension)

Order food items online

Order history tracking

Customer-based order management

🌐 RESTful APIs

API endpoints for menu and booking

JSON-based request/response

Can be integrated with mobile apps or frontend frameworks

🛠️ Tech Stack
Backend

Python

Django

Django REST Framework

Database

SQLite (default)

Easily extendable to MySQL / PostgreSQL

Frontend

HTML5

CSS3

Bootstrap (optional)

Tools & Libraries

Django Admin

REST APIs

Virtual Environment (venv)

📂 Project Structure
freshfood/
│── manage.py
│
├── freshfood/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── restaurant/
│   ├── models.py
│   ├── views.py
│   ├── serializers.py
│   ├── urls.py
│   └── admin.py
│
├── templates/
├── static/
├── db.sqlite3
└── requirements.txt

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/freshfood-pro.git
cd freshfood-pro

2️⃣ Create Virtual Environment
python -m venv env


Activate it:

Windows

env\Scripts\activate


Linux / macOS

source env/bin/activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Apply Migrations
python manage.py makemigrations
python manage.py migrate

5️⃣ Create Superuser
python manage.py createsuperuser

6️⃣ Run the Server
python manage.py runserver


Access the application:

Home: http://127.0.0.1:8000/

Admin Panel: http://127.0.0.1:8000/admin/

🔗 API Endpoints
Endpoint	Method	Description
/api/menu/	GET	View all menu items
/api/menu/	POST	Add new menu item
/api/bookings/	GET	View bookings
/api/bookings/	POST	Create booking
🧪 Testing

APIs tested using Postman

Manual UI testing via browser

Django Admin validation

📈 Future Enhancements

Payment gateway integration

AI-based food recommendations

JWT Authentication

React / Angular frontend

Mobile app integration

Cloud deployment (AWS / Azure)

🎓 Learning Outcomes

Django project structuring

REST API development

Backend authentication & authorization

Database modeling

Real-world application workflow design

👨‍💻 Author

Krishna Patil
CSE | AI & Data Science Enthusiast
Backend & AI Application Developer

⭐ Acknowledgements

Inspired by Little Lemon Project

Meta Backend Developer Curriculum

Django & DRF Documentation
