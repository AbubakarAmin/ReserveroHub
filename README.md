# ReserveroHub

A multi-tenant booking and business directory platform built with Laravel 11 — designed for service-based businesses that need a reliable, scalable way to manage reservations, staff, and services.

ReserveroHub solves the fragmentation problem in local service bookings. Business owners get a dedicated workspace to manage their listings, employees, and operating hours. Admins maintain full platform oversight. Clients get a clean, consistent experience across every business on the platform.

---

## 🚀 Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel 11" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP 8.2" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Alpine.js-8BC0D0?style=for-the-badge&logo=alpine.js&logoColor=white" alt="Alpine.js" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Pest-F14552?style=for-the-badge&logo=testing-library&logoColor=white" alt="Pest PHP" />
</p>

---

## ✨ Key Features

- **Role-Based Access Control** — Separate dashboards and permission layers for `Admin`, `Owner`, and `User` roles, each guarded by custom middleware
- **Multi-Tenant Business Profiles** — Owners can register and manage their own business workspace including branding (logo/banner), contact info, and location
- **Service & Employee Management** — Build service menus, assign categories, toggle availability in real-time, and manage staff rosters
- **Custom Operating Hours** — Flexible scheduling engine lets each business define their own working hours independently
- **Admin Control Panel** — Platform-wide management of categories, business owners, and end-users from a single dashboard
- **Secure Authentication** — Auth system built with Laravel Breeze with role-aware redirects post-login

---

## 🛠️ My Contributions

I built this project as the sole developer, responsible for both backend architecture and frontend integration.

**Backend**
- Designed the domain-driven folder structure separating `Admin`, `Owner`, and `Front` logic across controllers and models — keeps the codebase modular as it scales
- Architected the relational database schema across Users, Businesses, Categories, Services, and Business Hours — including pivot tables (`business_category`, `category_service`) and full Eloquent relationship mapping
- Built three separate, secured routing files (`admin.php`, `owner.php`, `web.php`) each protected by custom role-based middleware to prevent privilege escalation between roles

**Frontend Integration**
- Integrated the Laravel backend with Alpine.js and Tailwind CSS via Vite for a reactive, component-driven UI without a heavy JavaScript framework

**Testing**
- Set up Pest PHP as the testing foundation — structured for feature and unit test coverage as the platform grows

---

## 💡 Skills This Project Demonstrates

- Multi-role authorization architecture (Admin / Owner / User separation)
- Complex Eloquent relationships — `BelongsTo`, `HasMany`, `BelongsToMany` with pivot tables
- Clean controller design — thin controllers, domain-organized codebase
- Laravel 11 with modern tooling: Vite, Alpine.js, Tailwind CSS
- Testing setup with Pest PHP

---

## 📫 Contact

Open to freelance projects and remote opportunities.

- **GitHub:** [github.com/abubakaramin1](https://github.com/abubakaramin1)
- **Email:** *(add your email here)*
