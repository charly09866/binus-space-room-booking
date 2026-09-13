# Binus Space — Campus Room Booking Web App

A web-based platform for booking study rooms and facilities across BINUS University campuses, proposed under the **PKM-KC (Program Kreativitas Mahasiswa – Karsa Cipta)** student creativity grant scheme.

## Context
- **Type:** PKM-KC Proposal / Individual-authored proposal
- **My Role:** Authored the proposal — problem framing, system design, and feature scope.

## Problem Statement
Finding and booking an available study room or discussion space on campus is often manual and inefficient, relying on physical sign-up sheets or informal WhatsApp coordination. Binus Space proposes a centralized booking system to solve this.

## Proposed Features
- Browse room availability by campus, building, and time slot
- Book and cancel reservations
- Admin dashboard for facility management
- Booking history and notifications

## Tech Stack
| Layer | Technology |
|---|---|
| Frontend | React |
| Backend | Laravel |
| Database | PostgreSQL |

## Project Structure
```
binus-space-room-booking/
├── frontend/        # React app
├── backend/         # Laravel API
├── docs/            # PKM-KC proposal document
└── README.md
```

## Status
This started as a PKM-KC grant proposal. Implementation is in progress — see `docs/` for the full proposal covering problem background, objectives, and system design.

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
