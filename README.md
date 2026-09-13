# Binus Space — Campus Room Booking Web App

A web-based platform that lets students, lecturers, and facility admins manage campus room bookings — with real-time availability, a centralized approval flow, and automatic double-booking prevention.

## Context
- **Type:** PKM-KC (Program Kreativitas Mahasiswa – Karsa Cipta) group project
- **Team:** Muhamad Rifki Perkasa, Aria Rahmatanto Putro, Malvin Yonatan Muliawan, Charly Prayoga

## Problem Statement
Room booking at BINUS was largely manual, making it hard to check real-time availability and prone to double-booking. There was also no transparency into approval status once a request was submitted.

## Target Users
- **Students & Lecturers** — submit room booking requests for academic and organizational activities.
- **Facility Admins** — manage and approve/reject booking requests.

## Features
1. Check room availability with search & category filters
2. Book online through a simple multi-step form
3. Admin dashboard with multi-user login & encrypted passwords
4. Approval system — approve/reject with reason, with an admin audit trail
5. Automatic server-side double-booking prevention

## Impact
- **More efficient** — booking becomes fast and self-service, no manual process
- **Transparent** — request status and approval history are trackable
- **No conflicts** — the system automatically prevents double-booking

## Tech Stack
| Layer | Technology |
|---|---|
| Frontend | React + Vite + Tailwind CSS |
| Backend | Laravel 12 (REST API) |
| Database | PostgreSQL / MySQL |
| Deployment | Vercel (frontend) + Render (backend) |

## Live Demo
- **Website:** https://binus-space-frontend-1vdvixhsn-rifki-perkasa-s-projects.vercel.app/

## Getting Started
```bash
# Backend
cd backend
composer install
php artisan serve

# Frontend
cd frontend
npm install
npm run dev
```

## Notes
This project was built as part of a PKM-KC student creativity grant proposal for BINUS University, with the full proposal document covering background, objectives, and system design.
