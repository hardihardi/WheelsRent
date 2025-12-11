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
- Browse available cars with details (brand, model, price, availability)  
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

┌─────────────────────────────────────┐
|             Browser / Client         |
| (Bootstrap UI, HTML, CSS, JS)        |
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
|               MySQL Database         |
| • Users                              |
| • Cars                               |
| • Bookings                           |
| • Locations                          |
└─────────────────────────────────────┘
MySQL Database


---

## 📥 Installation

Follow these steps to install the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/hardihardi/WheelsRent.git
cd WheelsRent

2. Install PHP dependencies
composer install

3. Install Node modules (if applicable)
npm install
npm run dev

4. Copy environment file
cp .env.example .env

5. Generate the application key
php artisan key:generate

🔧 Configuration

Edit your .env file and set your database credentials:

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


Run database migrations:

php artisan migrate
php artisan db:seed

▶️ Usage

Start the local development server:

php artisan serve


Open the application in your browser:

➡️ http://127.0.0.1:8000

From here, users can register, browse cars, and make bookings.
Admins can access the dashboard to manage vehicles, users, and bookings.

🖼 Screenshots

Add your UI screenshots here.

Example:

/screenshots/homepage.png  
/screenshots/admin-dashboard.png

🧪 Testing

Run application tests:

php artisan test

🚢 Deployment

For production deployment:

composer install --optimize-autoloader --no-dev
npm run build
php artisan migrate --force
php artisan optimize


Ensure your server points to the /public directory.

🤝 Contributing

Contributions are welcome!

Fork the repository

Create a new branch

Make your changes

Commit and push

Open a Pull Request

📄 License

This project is licensed under the MIT License.
See the LICENSE file for more information.

📬 Contact

Author: hardihardi
GitHub: https://github.com/hardihardi/WheelsRent
