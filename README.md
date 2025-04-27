

# Handpickd - Artisanal Marketplace for Handmade Goods




<div align="center">
   <img src="https://img.shields.io/badge/-Laravel-FF2D20?style=for-the-badge&logoColor=white&logo=laravel" alt="Laravel" />
   <img src="https://img.shields.io/badge/-Alpine.js-8BC0D0?style=for-the-badge&logoColor=white&logo=alpine.js" alt="AlpineJS" />
   <img src="https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logoColor=white&logo=mysql" alt="MySQL" />
</div>

Handpickd is a community-driven platform that celebrates creativity and craftsmanship. Our marketplace provides a space for artisans to showcase their handmade goods and for enthusiasts to discover unique, handcrafted items. Built as a school project using Laravel, Alpine.js, and MySQL, Handpickd is a testament to the power of community and craftsmanship.

## 📖 Table of Contents

- [Project Overview](#-project-overview)
- [Requirements](#-requirements)
- [Installation Instructions](#️-installation-instructions)
- [Features & Functionality](#-features--functionality)
- [Technologies Used](#-technologies-used)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Authors](#-authors)

## 🌟 Project Overview

Handpickd offers an alternative to mass-produced goods by highlighting unique, handcrafted items. It's a digital homage to the tradition of artisanry, designed to connect makers with those who appreciate the value of bespoke creations.

## 🔧 Requirements

Handpickd requires the following tools to run:

- [NodeJS](https://nodejs.org/en): JavaScript runtime environment
- [XAMPP](https://www.apachefriends.org/download.html): Web server solution stack package (Apache, MySQL, PHP)
- [Composer](https://getcomposer.org/): PHP dependency management tool
- [Laravel](https://laravel.com/): PHP web application framework
- [Git Bash](https://gitforwindows.org/): Recommended for installation of Laravel and Composer on Windows

## ⚙️ Installation Instructions

### 1. Install Prerequisites
- Install NodeJS
- Install XAMPP
- Install Composer (via Git Bash recommended on Windows)
- Install Laravel
- Configure PHP.ini to enable the GD extension

### 2. Clone and Setup
bash
# Clone the repository
git clone https://github.com/Uttam53/handpickd.git

# Navigate to the repository
cd handpickd

# Install dependencies
npm install
composer install

# Set up the environment
cp [.env.example](http://_vscodecontentref_/1) .env
php artisan key:generate

# Create a symbolic link to the storage folder (for images)
php artisan storage:link

# Run migrations and seed the database
php artisan migrate --seed
