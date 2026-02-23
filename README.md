<div dir="rtl">

# سیستم حمل و نقل بار  
**Cargo Transportation System**

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

</div>

## توضیحات | Description

**فارسی**  
این پروژه یک وب‌سایت ساده مدیریت باربری است که به صاحبان بار امکان ثبت سفارش حمل بار می‌دهد و به رانندگان/صاحبان ماشین‌های سنگین (خاور، تک، جفت، تریلی) اجازه می‌دهد بارهای مناسب را مشاهده و قبول کنند.  
با **Laravel** + **PHP** + **HTML** (و Blade) ساخته شده و هدفش ساده‌سازی فرآیند اعلام بار و انتخاب توسط راننده برای باربری‌های کوچک و متوسط است.

**English**  
A simple web-based cargo transportation management system.  
Cargo owners can register new transport orders, while heavy truck drivers/owners (Khavar, Single-axle, Double-axle, Trailer) can view available loads and accept suitable ones.  
Built using **Laravel** + **PHP** + **HTML** (with Blade templating) to streamline order posting and selection for small to medium trucking operations.

## ویژگی‌های اصلی | Main Features

- فرم ثبت سفارش جدید توسط صاحب بار (مبدا، مقصد، نوع بار، وزن تقریبی)  
- انتخاب نوع کامیون مورد نیاز از بین خاور / تک / جفت / تریلی  
- پنل اعلام بار توسط صاحب بار و امکان مشاهده و انتخاب بار توسط راننده  

(ویژگی‌های احتمالی آینده: محاسبه کرایه خودکار، لیست سفارش‌ها با وضعیت، احراز هویت نقش‌ها، پنل جداگانه راننده/صاحب بار)

## تکنولوژی‌های استفاده شده | Technologies

- Laravel (backend framework)  
- PHP  
- HTML + Blade templating  
- MySQL / MariaDB (database)  
- Git + GitHub

## نصب و راه‌اندازی | Installation & Setup

1. پروژه را کلون کنید:
   ```bash
   git clone https://github.com/SalehPRD/YOUR_REPO_NAME.git وارد پوشه پروژه شوید:
2. وارد پوشه پروژه شوید:
   ```bash
   cd Special-Topics404
3. وابستگی‌ها را نصب کنید:
   ```bash
   composer install
4. فایل محیطی را آماده کنید:
   ```bash
   cp .env.example .env
 فایل **.env** را باز کنید و تنظیمات دیتابیس (DB_DATABASE، DB_USERNAME، DB_PASSWORD و …) را انجام دهید.

5. کلید اپلیکیشن تولید کنید:
   ```bash
   php artisan key:generate
6. دیتابیس را migrate کنید:
   ```bash
   php artisan migrate
7. سرور را اجرا کنید:
   ```bash
   php artisan serve

## نحوه استفاده | Usage

1. صاحب بار وارد سایت می‌شود و فرم ثبت سفارش را پر می‌کند (مبدا، مقصد، نوع بار، وزن، نوع کامیون دلخواه).  
2. رانندگان بارهای ثبت‌شده را مشاهده می‌کنند و بار مناسب را انتخاب/قبول می‌کنند.

<div align="center">

### نمونه فرم ثبت سفارش  
![فرم ثبت سفارش](screenshots/form.png)

</div>

## نویسنده | Author

- **Saleh**  
  GitHub: [@SalehPRD](https://github.com/SalehPRD)


