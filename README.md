# Eventora

Eventora is a full-stack event booking system that enables users to explore, filter, and book events, manage their bookings, and access an integrated web-based admin panel for complete event management.

## Live Demo

- Frontend: https://eventora-3102d.web.app/
- Backend API: https://valid-toma-eventora-c540447c.koyeb.app/api

## Admin Credentials

To access the admin panel, use the following credentials:

- **Email:** admin@eventora.com  
- **Password:** admin123


## Tech Stack

| Layer       | Technology                          |
|-------------|--------------------------------------|
| Frontend    | React + Vite                         |
| Backend     | Node.js + Express.js                 |
| Database    | MongoDB                              |
| Hosting     | Firebase (Frontend), Koyeb (Backend) |
| Media       | Cloudinary (Image Uploads)           |


### Project Structure

```bash
Eventora/
├── eventora_frontend/   # Frontend built with React + Vite
├── eventora_backend/    # Backend built with Node.js + Express
└── README/    # read me file for all instructions and details
```

## Features

### User-Side (Frontend)

- User Authentication (Sign Up / Login)
- Home page with categorized event grid
- Event details page with "Book Now" functionality
- Booking confirmation screen
- Add or remove events from Favorites
- Event filtering by:
  - Category
  - Min/Max price
  - Search by name
- Dark Mode support
- Fully responsive and modern design
- **Project structure follows Atomic Design Pattern** for better scalability and maintainability

### Admin Panel

- Integrated within the main app
- Admin-only access with role-based permissions
- Create, Update, Delete, and View events
- Event tagging and categorization
- Image upload via Cloudinary
- Pagination for efficient data management

### Backend Functionalities

- Authentication & Role-Based Authorization (USER, ADMIN)
- CRUD operations for events
- Image Upload API using Cloudinary
- Booking API and Favorites API
- Pagination for listings

## Installation Guide

### Frontend Setup

```bash
cd eventora_frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd eventora_backend
npm install
npm run dev
```

## Author - Abdelrahman Khaled

