Eventora
Eventora is a full-stack event booking system that allows users to explore and book events, manage their bookings, and provides an integrated web-based admin panel for complete event management.

Live Demo
Frontend: https://eventora-3102d.web.app/

Backend API: https://valid-toma-eventora-c540447c.koyeb.app/api

Tech Stack
Frontend: React + Vite
Backend: Node.js + Express.js
Database: MongoDB
Hosting: Firebase (Frontend), Koyeb (Backend), Cloudinary (Image Uploads)

Features
User-Side
User Authentication (Sign up / Login)
Browse events on the home page with categorized display
View detailed event information
Book tickets directly from the event page
Get confirmation on a “Congratulations” page after booking
Add or remove events from Favorites
Filter events by:
- Category
- Minimum and maximum price
- Search by name
Responsive and modern UI with support for all screen sizes
Dark mode support

Admin Panel
Integrated admin dashboard inside the web app
Role-based access (Admin privileges)
Create, update, view, and delete events
Event tags and Categories
Uploaded images (via Cloudinary)
Pagination support for event listings

Backend Functionality
Authentication and role-based authorization
CRUD operations for event management
Image upload with Cloudinary
Booking and favorite APIs
Pagination for optimized data fetching

Installation
Frontend
cd eventora-frontend
npm install
npm run dev
To run locally with the backend, update the baseURL in axios.config.js to http://localhost:3000.

Backend
cd eventora-backend
npm install
npm run dev
Make sure MongoDB is running and accessible from your environment.

Project Structure
Eventora/
├── eventora-frontend/    # React + Vite frontend
└── eventora-backend/     # Node.js + Express backend

Contributors
Project developed by Abdelrahman Nazem
