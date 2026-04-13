# 🛠 Hardware Shop Management System

A robust and scalable **Django-based Hardware Shop Management System** designed to manage products, suppliers, inventory, and customer orders efficiently in a modern digital environment.

---

## 🚀 Project Overview

The Hardware Shop Management System is a complete web-based solution that automates the operations of a hardware store. It provides seamless interaction between **customers, suppliers, and administrators**.

This system ensures efficient inventory control, order management, and supplier coordination.

---

## ✨ Key Features

### 👤 Customer Module

* User Registration & Login
* Browse Hardware Products
* Add to Cart & Buy Now
* Order Placement & Tracking

---

### 🏪 Supplier Module

* Supplier Registration & Login
* Add Product Requests
* Stock Management
* Product Approval Workflow

---

### 🛠 Admin Panel

* Category Management (Tools, Materials, Safety Gear, etc.)
* Product Approval System
* Order Monitoring
* Supplier Management
* Feedback & Contact Handling

---

### 📦 Inventory Management

* Real-time stock tracking
* Product availability updates
* Low stock monitoring

---

### 💳 Payment System

* Cash on Delivery (COD)
* Razorpay Integration

---

### 📊 Reporting System

* Order Reports (PDF)
* Sales Tracking
* Customer Feedback Analysis

---

## 🧰 Technologies Used

| Category        | Technology                       |
| --------------- | -------------------------------- |
| Backend         | Django (Python)                  |
| Frontend        | HTML, CSS, Bootstrap, JavaScript |
| Database        | SQLite                           |
| Deployment      | Render                           |
| Payment Gateway | Razorpay                         |
| PDF Reports     | ReportLab                        |

---

## 📁 Project Structure

```id="3nq7ml"
hardware_shop/
│
├── manage.py
├── requirements.txt
│
├── hardware_shop/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│
├── shop/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   ├── static/
│
├── media/
├── staticfiles/
```

---

## ⚙️ Installation Guide

### 1️⃣ Clone Repository

```bash id="y3o6z6"
git clone https://github.com/NidhiRathod298/hardware-shop-management-system.git
cd hardware-shop-management-system
```

### 2️⃣ Create Virtual Environment

```bash id="h10l9v"
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash id="w9f9e1"
pip install -r requirements.txt
```

### 4️⃣ Apply Migrations

```bash id="6j4q0y"
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Run Server

```bash id="4ixk9m"
python manage.py runserver
```

👉 Open: http://127.0.0.1:8000/

---

## 🌐 Deployment (Render)

* GitHub Integrated Deployment
* Gunicorn WSGI Server
* WhiteNoise for Static Files
* Environment Variables Configuration

---

## 🔐 Environment Variables

```id="j2w9bx"
SECRET_KEY=your_secret_key
DEBUG=False
ALLOWED_HOSTS=.onrender.com
```

---

## 📸 Project Output

### 🏠 Dashboard

* Modern UI with hardware categories
* Real-time statistics

### 🧰 Categories

* Hand Tools
* Power Tools
* Plumbing Tools
* Electrical Tools
* Safety Gear
* Building Materials

### 🛒 Products

* Product listing with price & stock
* Add to Cart / Buy Now

### 📦 Orders

* Order tracking system
* Status updates (Placed → Delivered)

---

## 🎯 Objectives

* Digitize hardware shop operations
* Improve inventory accuracy
* Enhance customer experience
* Automate supplier-product workflow

---

## 🔮 Future Enhancements

* 📱 Mobile App Integration
* ☁️ Cloud Storage (Cloudinary/AWS)
* 🤖 AI-based inventory prediction
* 📊 Advanced analytics dashboard

---

## 👨‍💻 Developer

**Viral Gujariya**
💻 BCA Student | Full Stack Developer

---

## 📄 License

This project is developed for **academic and educational purposes only**.

---
👨‍💻 Developer

Nidhi Rathod
💻 BCA Student | Full Stack Developer

## ⭐ Conclusion

The Hardware Shop Management System demonstrates a complete full-stack implementation using Django, covering real-world features such as inventory control, supplier management, and secure transactions. It is suitable for both academic projects and real-world deployment.

---

⭐ If you like this project, please give it a star on GitHub!
