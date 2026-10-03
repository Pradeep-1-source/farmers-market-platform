# 🌱 Farmers Market Platform

A full-stack Flask web application connecting local farmers directly with consumers. Farmers can list and manage their fresh farm produce, and customers can browse, cart, purchase items, and leave reviews.

---

## 🚀 Features

### For Farmers
- **Farmer Dashboard**: Overview of listed products, sales, and orders.
- **Product Management**: Add, update, and manage inventory (price, quantity, category, and images).
- **Order Management**: View incoming customer orders and track order fulfillment.
- **Customer Reviews**: View feedback and ratings from customers.

### For Customers
- **Marketplace Browsing**: Filter and search through produce by category and keyword.
- **Shopping Cart**: Add products to cart, adjust quantities, and checkout.
- **Order Tracking**: View order status and order history.
- **Product Reviews**: Submit reviews and ratings for purchased items.

### Security & Authentication
- User authentication and role-based access control (`farmer` vs `customer`).
- Secure password hashing with Werkzeug.
- Session management with Flask-Login.

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Database & ORM**: SQLite, Flask-SQLAlchemy
- **Authentication**: Flask-Login, Werkzeug Security
- **Frontend**: HTML5, Jinja2 Templates, Bootstrap 5, Vanilla CSS, JavaScript

---

## 📦 Getting Started

### Prerequisites
- Python 3.10+ installed
- Git installed

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pradeep-1-source/farmers-market-platform.git
   cd farmers-market-platform
   ```

2. **Create and activate a virtual environment (recommended):**
   ```bash
   # Windows
   py -m venv venv
   .\venv\Scripts\activate

   # macOS / Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**
   ```bash
   py app.py
   # or
   python app.py
   ```

5. **Open in browser:**
   Navigate to [http://localhost:5000](http://localhost:5000)

---

## 📁 Project Structure

```text
farmers-market-platform/
│
├── instance/
│   └── farmers_market.db      # SQLite database
├── static/
│   ├── css/
│   │   └── style.css          # Application styles
│   ├── images/                # Asset images & photos
│   └── js/
│       └── script.js          # Interactive frontend logic
├── templates/                 # Jinja2 HTML templates
│   ├── base.html
│   ├── index.html
│   ├── marketplace.html
│   ├── dashboard.html
│   └── ...
├── app.py                     # Main application entry point & routes
├── requirements.txt           # Project dependencies
└── README.md                  # Project documentation
```

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
