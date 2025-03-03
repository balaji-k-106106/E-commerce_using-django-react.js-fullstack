E-Commerce Platform (Django & React)

📌 Project Overview
This is a full-stack e-commerce web application built using Django (Backend) and React.js (Frontend). It allows users to browse products, add items to their cart, and complete purchases using a payment gateway.

🚀 Features
- ✅ User Authentication (JWT-based login & signup)
- ✅ Product Listings & Search Filters
- ✅ Shopping Cart & Checkout Process
- ✅ Payment Gateway Integration (Stripe/Razorpay)
- ✅ Order History & Admin Dashboard
- ✅ Mobile Responsive UI

🛠 Tech Stack
- Backend: Django, Django REST Framework (DRF)
- Frontend:React.js, Redux, Tailwind CSS
- Database: SQLite (default, can be switched to PostgreSQL)
- Authentication: JWT-based login
- Payment Gateway:Stripe/Razorpay

🏗 Installation & Setup
1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/ecommerce-django-react.git
cd ecommerce-django-react-main
```
2️⃣ Backend Setup (Django)
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r ../requirements.txt
python manage.py migrate
python manage.py runserver
```
3️⃣ Frontend Setup (React)
```bash
cd frontend
npm install
npm start
```

🎯 Usage
- Visit `http://localhost:8000/api/` for backend API endpoints.
- Visit `http://localhost:3000/` for the frontend UI.
- Create an account, browse products, and complete a purchase.

📂 Project Structure
```
ecommerce-django-react-main/
│-- backend/  # Django backend
│-- frontend/  # React frontend
│-- db.sqlite3  # Default database
│-- manage.py  # Django management script
│-- requirements.txt  # Python dependencies
│-- static/  # Static files
│-- media/  # Media uploads
│-- .gitignore  # Git ignore file
│-- Procfile / runtime.txt  # For deployment
```

