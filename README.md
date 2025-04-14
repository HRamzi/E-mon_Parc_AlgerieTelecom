# 🚗 Chauffeur & Mission Management System

A full-stack web application built for Algérie Télécom to manage drivers, missions, recoveries, and schedules.

## 🛠 Tech Stack

- Frontend: React.js
- Backend: Laravel (PHP)
- Database: MySQL

## 📦 Features

- Chauffeur account and schedule management (Full-time & Part-time)
- Mission creation (short or long distance)
- Automatic calculation of recovery days
- Calendar view for all assignments
- Prioritization rules for mission assignments
- Role-based access (Admin, Dispatcher, Driver)
- Dashboard with statistics and reporting

## 🗂️ Project Structure

/client    → React frontend
/server    → Laravel backend


## 🚀 Getting Started

### Prerequisites

- Node.js & npm
- PHP & Composer
- MySQL
- Laravel CLI

### Frontend Setup

cd client
npm install
npm run dev


### Backend Setup

cd server
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve


## 👥 Team

Developed by a group of Computer Science students as part of a final year project in collaboration with Algérie Télécom.

## 📄 License

This project is private and developed exclusively for educational and internal use at Algérie Télécom.
