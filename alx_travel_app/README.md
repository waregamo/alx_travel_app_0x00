# ALX Travel App 0x00

A Django RESTful backend for managing travel listings, bookings, and reviews.

## 🧠 Objective

- Define models for travel listings.
- Create serializers for API representation.
- Implement a custom management command to seed the database with sample data.

---

## 📁 Project Structure

.
└── alx_travel_app
    ├── README.md
    ├── alx_travel_app
    │   ├── __init__.py
    │   ├── __pycache__
    │   ├── asgi.py
    │   ├── requirements.txt
    │   ├── settings.py
    │   ├── urls.py
    │   └── wsgi.py
    ├── listings
    │   ├── __init__.py
    │   ├── __pycache__
    │   ├── admin.py
    │   ├── apps.py
    │   ├── management
    │   ├── migrations
    │   ├── models.py
    │   ├── serializers.py
    │   ├── tests.py
    │   ├── urls.py
    │   └── views.py
    ├── manage.py
    └── venv
        ├── bin
        ├── include
        ├── lib
        ├── lib64 -> lib
        └── pyvenv.cfg


---

## ⚙️ Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/waregamo/alx_travel_app_0x00.git
cd alx_travel_app_0x00

2. Create and activate a virtual environment
          python3 -m venv venv
          source venv/bin/activate
3. Install dependencies
           pip install -r alx_travel_app/requirement.txt
4. Create .env file
Create a .env file in the root directory and add your database credentials:
          DB_NAME=alx_travel
          DB_USER=your_mysql_user
          DB_PASSWORD=your_mysql_password
          DB_HOST=localhost
          DB_PORT=3306
5. Run migrations
          python3 manage.py makemigrations
          python3 manage.py migrate
6. Seeding the Database
Run the custom seed command to populate the database with sample listings:
          python3 manage.py seed






