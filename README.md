# inventory_project
# 🧾 Inventory Management System

A web-based Inventory Management System built using Flask, enabling efficient tracking, analytics, and management of stock with role-based access (Admin/Staff). Designed for use in retail or warehouse environments.

---

## 🚀 Features

### 🔐 Authentication & Authorization
- User registration and login
- Role-based access control (Admin, Staff)
- Secure password hashing

### 📦 Product Management
- Add, update, delete products
- Product fields: SKU, Name, Barcode, Category, Stock, Threshold, Expiry Date
- Server and client-side validations
- Product dashboard

### 📊 Analytics & Reporting
- Inventory statistics and summaries
- Low-stock and expired product alerts
- Export inventory data to CSV

### 🔄 Inventory Tracking & Logs
- Real-time stock updates
- Log history of updates
- Automatic alerts on low stock and expiry

---

## 🧱 System Architecture

### Frontend
- HTML, CSS, JavaScript
- Form validations and animated UI (login/register)
- Responsive and minimal UI

### Backend
- Flask (modular structure using Blueprints)
- Flask-Login for authentication
- Flask-Bcrypt for secure password storage
- Flask-SQLAlchemy for ORM
- SQLite database (can switch to PostgreSQL)

---

## ⚙️ Project Structure

inventory_system/
│
├── run.py # Entry point
├── requirements.txt # Python dependencies
│
├── inventory/ # Main app
│ ├── init.py
│ ├── models.py
│ ├── templates/
│ ├── static/
│ ├── auth/ # Authentication module
│ ├── products/ # Product management
│ ├── analytics/ # Analytics & export
│ └── tracking/ # Logs, alerts, stock updates


---

## 💾 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/inventory_system.git
   cd inventory_system

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   venv\Scripts\activate  # On Windows

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt

4. **Run the app**
   ```bash
   flask --app run.py run

5. **Access**
   - Navigate to http://127.0.0.1:5000
   - Register a user and login to start using the system

## Future Improvements
   - Role management UI

   - Product image upload

   - Email notifications for low stock

   - Unit tests and CI integration

## Team
Israth Julaiha I – Authentication, Product Module

Afrin Sulthana M – Inventory Tracking, Alerts 

Aneesa Tabasumm K – Analytics & Export



