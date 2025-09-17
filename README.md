# 📌 Laravel Starter Kit  

[![GitHub stars](https://img.shields.io/github/stars/wadecalvin9/Laravel-Starter-Kit?style=social)](https://github.com/wadecalvin9/Laravel-Starter-Kit/stargazers)  
[![GitHub issues](https://img.shields.io/github/issues/wadecalvin9/Laravel-Starter-Kit)](https://github.com/wadecalvin9/Laravel-Starter-Kit/issues)  
[![GitHub forks](https://img.shields.io/github/forks/wadecalvin9/Laravel-Starter-Kit?style=social)](https://github.com/wadecalvin9/Laravel-Starter-Kit/network/members)  
[![GitHub license](https://img.shields.io/github/license/wadecalvin9/Laravel-Starter-Kit)](https://github.com/wadecalvin9/Laravel-Starter-Kit/blob/main/LICENSE)  
[![Laravel](https://img.shields.io/badge/Laravel-11.x-red.svg)](https://laravel.com)  
[![Filament](https://img.shields.io/badge/Filament-3.x-blueviolet.svg)](https://filamentphp.com)  

A **comprehensive Laravel starter kit** with authentication, user & admin panels, role management, two-factor authentication, email notifications, announcement banners, log viewer, and more.  

---

## ✨ Features  

- 🔑 Authentication (Login, Register, Password Reset)  
- 👤 User & Admin Panels  
- 🛡️ Role & Permission Management  
- 📲 Two-Factor Authentication (2FA)  
- 📧 Email Notifications (welcome, password reset, etc.)  
- 📢 Announcement Banners  
- 📜 Activity Log Viewer & User Log Viewer  
- 🎨 Pre-built UI components with Filament/Laravel Blade  
- ⚡ Easy to extend for production apps  

---

## 🚀 Installation  

### 1. Clone the repository  
```bash
git clone https://github.com/wadecalvin9/Laravel-Starter-Kit.git
cd Laravel-Starter-Kit
```

### 2. Install dependencies  
```bash
composer install
npm install && npm run dev
```

### 3. Setup environment  
```bash
cp .env.example .env
php artisan key:generate
```

Update `.env` with your database and mail credentials.  

### 4. Run migrations  
```bash
php artisan migrate
```

### 5. Generate permissions & policies (Laravel Shield)  
```bash
php artisan shield:generate --all
```

### 6. Create a Filament user  
```bash
php artisan make:filament-user
```

### 7. Generate a Super Admin user  
```bash
php artisan shield:super-admin
```

### 8. Start the development server  
```bash
php artisan serve
```
Or, if using Vite:  
```bash
composer run dev
```

---

## 🔑 Default Access  

- **Super Admin** → Full access to all features  
- **User** → Restricted panel  

---

## 🛠️ Tech Stack  

- [Laravel 11](https://laravel.com)  
- [Filament](https://filamentphp.com)  
- [Tailwind CSS](https://tailwindcss.com)  
- MySQL / PostgreSQL  

---

## 🤝 Contributing  

Contributions are welcome!  
1. Fork the repo  
2. Create a new branch (`git checkout -b feature-branch`)  
3. Commit your changes (`git commit -m 'Add feature'`)  
4. Push to the branch (`git push origin feature-branch`)  
5. Open a Pull Request  

---

## 📜 License  

This project is open-source under the [MIT License](LICENSE).  
