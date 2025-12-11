# WheelsRent

WheelsRent is a user-friendly **online car rental web application** that enables customers to browse, book, and manage vehicle rentals. Built with **Laravel**, **Bootstrap**, and **MySQL**, it provides a full-stack solution for a modern rental service platform.

---

## 🧾 Table of Contents

1. [Overview](#overview)  
2. [Features](#features)  
3. [Tech Stack](#tech-stack)  
4. [Architecture](#architecture)  
5. [Installation](#installation)  
6. [Configuration](#configuration)  
7. [Usage](#usage)  
8. [Screenshots](#screenshots)  
9. [Testing](#testing)  
10. [Deployment](#deployment)  
11. [Contributing](#contributing)  
12. [License](#license)  
13. [Contact](#contact)

---

## 🌟 Overview

WheelsRent is a complete web-based platform for managing car rentals. It includes authentication, vehicle listings, booking features, and an admin dashboard for managing vehicles, users, and rental orders.

---

## 🚀 Features

- User registration & authentication  
- Browse available cars (brand, model, price, availability)  
- Search & filter vehicles  
- Book vehicles for selected dates  
- Admin dashboard with CRUD operations  
- Responsive UI using Bootstrap  
- Secure backend with Laravel  
- Session handling & validation  

---

## 🛠 Tech Stack

| Component | Technology |
|----------|------------|
| Backend  | Laravel (PHP) |
| Frontend | Bootstrap, HTML, CSS, JavaScript |
| Database | MySQL |
| ORM      | Laravel Eloquent |
| Views    | Blade Templates |
| Tools    | Composer, NPM, Artisan |

---

## 🏗 Architecture

```

┌─────────────────────────────────────┐
|             Browser / Client         |
|     (Bootstrap UI, HTML, CSS, JS)    |
└─────────────────────────────────────┘
▲
▼
┌─────────────────────────────────────┐
|              Laravel MVC             |
| • Models (Eloquent)                  |
| • Controllers (Business Logic)       |
| • Views (Blade Templates)            |
| • Routes                             |
└─────────────────────────────────────┘
▲
▼
┌─────────────────────────────────────┐
|             MySQL Database           |
| • Users                              |
| • Cars                               |
| • Bookings                           |
| • Locations                          |
└─────────────────────────────────────┘

````

---

## 📥 Installation

Follow these steps to install the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/hardihardi/WheelsRent.git
cd WheelsRent
````

### 2. Install PHP dependencies

```bash
composer install
```

### 3. Install Node modules (if applicable)

```bash
npm install
npm run dev
```

### 4. Copy environment file

```bash
cp .env.example .env
```

### 5. Generate application key

```bash
php artisan key:generate
```

---

## 🔧 Configuration

Edit your `.env` file and set your database credentials:

```env
APP_NAME=WheelsRent
APP_ENV=local
APP_KEY=base64:...
APP_DEBUG=true
APP_URL=http://localhost

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=wheelsrent
DB_USERNAME=root
DB_PASSWORD=
```

Run migrations and seeders:

```bash
php artisan migrate
php artisan db:seed
```

---

## ▶️ Usage

Start the development server:

```bash
php artisan serve
```

Open the application in your browser:

➡️ [http://127.0.0.1:8000](http://127.0.0.1:8000)

Users can:

* Register an account
* Browse cars
* Make bookings

Admins can:

* Manage vehicles
* Manage users
* Manage bookings

---

## 🖼 Screenshots

Add your UI screenshots here:

```
/screenshots/homepage.png
/screenshots/admin-dashboard.png
```

---

## 🧪 Testing

Run application tests:

```bash
php artisan test
```

---

## 🚢 Deployment

For production deployment:

```bash
composer install --optimize-autoloader --no-dev
npm run build
php artisan migrate --force
php artisan optimize
```

Ensure your server points to the **/public** directory.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit and push
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.
See the `LICENSE` file for details.

---

📬 Contact

Author: hardihardi
GitHub: https://github.com/hardihardi/WheelsRent
