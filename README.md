# Laravel Blog Admin CMS

A fully functional Blog Admin Content Management System built using Laravel. This project allows admins to manage blog posts, categories, tags, and user roles through a secure dashboard.

## 🔍 Features

- Admin authentication and dashboard
- Create, edit, and delete blog posts
- Manage categories and tags
- User role management
- Rich text editor for posts
- Image upload support
- SEO-friendly slugs and URLs

## 🚀 Tech Stack

- **Backend:** Laravel (PHP)
- **Database:** MySQL
- **Frontend:** Blade templating, Bootstrap
- **Package Manager:** Composer
- **Local Server:** XAMPP

## 🛠️ Setup Instructions

1. **Clone the Repository**

```
git clone https://github.com/kratiggg/laravel-blog-admin-cms.git
cd laravel-blog-admin-cms
```
2. **Install Dependencies**

Make sure you have Composer and PHP installed:
```
composer install
```
3. **Set Up Environment**

Duplicate .env.example to .env and update database credentials

```
cp .env.example .env
php artisan key:generate
```

4. Run Migrations (if available)

```
php artisan migrate
```
5. Start Development Server
```
php artisan serve
```

📁 Folder Structure Highlights
/app – Laravel core logic
/resources/views – Blade templates
/routes/web.php – Web routes
/public – Publicly accessible files
/database – Migrations & seeders

🤝 Contributions
This is a self-developed personal project created as part of my Laravel learning and web development journey. Feel free to fork and modify for your own use.

📌 Author
Krati Gupta
GitHub: @kratiggg[https://github.com/kratiggg]


