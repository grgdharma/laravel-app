# Laravel App

A web application built using **Laravel 12**, following modern Laravel standards and best practices.  
This repository is intended for learning, development, and production-ready experimentation.

---

## 📋 Requirements

Ensure your system meets the following requirements:

- PHP **8.2 or higher**
- Composer
- MySQL / PostgreSQL / SQLite
- Node.js & NPM (optional, for frontend assets)
- Git

---

## 🚀 Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/grgdharma/laravel-app.git
cd laravel-app
```
### 2️⃣ Install PHP dependencies
```bash
composer install
```
### 3️⃣ Create environment file
```bash
cp .env.example .env
```
### 4️⃣ Generate application key
```bash
php artisan key:generate
```
### 5️⃣ Configure database
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel12
DB_USERNAME=root
DB_PASSWORD=
```
### 6️⃣ Run database migrations
```bash
php artisan migrate
```
### 7️⃣ Start development server
```bash
php artisan serve
```
Application will be available at:
```bash
http://127.0.0.1:8000
```
## 🧪 Running Tests
```bash
php artisan test
```
## 🔐 Security
If you discover a security vulnerability, please report it responsibly.
Do not disclose vulnerabilities publicly.
## 🤝 Contributing
Contributions are welcome!

- Fork the repository
- Create a new branch
- Commit your changes
- Submit a pull request
## 📄 License
This project is open-sourced under the MIT License.
## 👤 Author
Dharma Raj Gurung
## ⭐ Support
If you like this project, please consider giving it a ⭐ on GitHub.
