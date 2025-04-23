# Laravel Shop

A Laravel-based e-commerce platform designed to provide a customizable and scalable online shopping experience.

## 🚀 Features

- Product catalog with categories and tags
- Shopping cart functionality
- User authentication and profile management
- Order processing and management
- Responsive design for mobile and desktop

## 🛠️ Technologies Used

- Laravel Framework
- PHP
- MySQL or PostgreSQL
- Blade templating engine
- Bootstrap for responsive design
- Composer for dependency management

## 📦 Installation

### Prerequisites

- PHP 7.4 or higher
- Composer
- MySQL or PostgreSQL

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/SergeiElesin/laravel_shop.git
   cd laravel_shop
   ```

2. Install PHP dependencies:
   ```bash
   composer install
   ```

3. Copy the example environment file and configure it:
   ```bash
   cp .env.example .env
   ```

4. Generate the application key:
   ```bash
   php artisan key:generate
   ```

5. Configure your database settings in the `.env` file.

6. Run database migrations:
   ```bash
   php artisan migrate
   ```

7. Start the development server:
   ```bash
   php artisan serve
   ```

## 📄 License

This project is open-source and available under the [MIT license](LICENSE).
