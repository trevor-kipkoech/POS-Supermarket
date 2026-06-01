Overview

The Supermarket Management System is a software application designed to streamline and automate supermarket operations. The system helps manage products, inventory, sales, customers, suppliers, and employee activities efficiently.

Features
Product Management
Add, update, view, and delete products
Categorize products
Track product prices and stock levels
Inventory Management
Monitor stock availability
Automatic stock updates after sales
Low-stock alerts
Sales Management
Process customer purchases
Generate receipts
Track daily, weekly, and monthly sales
Customer Management
Store customer information
Manage loyalty programs
View purchase history
Supplier Management
Add and manage suppliers
Track product deliveries
Manage supplier contacts
Employee Management
Register employees
Assign roles and permissions
Track employee activities
Reporting
Sales reports
Inventory reports
Product performance analysis
Customer activity reports
Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: PHP / Laravel
Database: MySQL
Version Control: Git & GitHub
Installation
Prerequisites
PHP 8.x
Composer
MySQL
Web Server (Apache/Nginx)
Git
Steps
Clone the repository:
git clone https://github.com/your-username/supermarket-management-system.git
Navigate to the project directory:
cd supermarket-management-system
Install dependencies:
composer install
Create the environment file:
cp .env.example .env
Generate the application key:
php artisan key:generate
Configure database credentials in .env.
Run migrations:
php artisan migrate
Start the development server:
php artisan serve
Open the application:
http://127.0.0.1:8000
