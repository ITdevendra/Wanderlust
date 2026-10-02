# 🏡 Wanderlust - Full Stack Travel Listing Web Application

🔗 **Live Demo:** [Wanderlust](https://wanderlust-7ge4.onrender.com/listings)

Wanderlust is a full-stack web application inspired by travel and property-listing platforms such as Airbnb.

The application allows users to explore accommodation listings, create and manage their own listings, upload images, leave reviews, and interact with the platform through a secure authentication system.

---

## 🚀 Features

### 👤 User Authentication
- User registration and login
- Secure authentication using Passport.js
- Session-based authentication
- Protected routes
- Authorization for listing owners

### 🏠 Property Listings
- View all available listings
- View detailed information about a listing
- Create new listings
- Edit existing listings
- Delete listings
- Display listing owner information

### 🖼️ Image Management
- Upload property images
- Cloudinary integration for image storage
- Display uploaded images with listings

### ⭐ Reviews
- Add reviews to listings
- Display reviews
- Delete reviews
- Review authorization

### 🔐 Authorization
- Only authenticated users can create listings
- Only listing owners can edit/delete their listings
- Users can manage their own reviews

### 📱 Responsive UI
- Clean and simple user interface
- Responsive layout for different screen sizes
- EJS templates for dynamic pages

---

## 🛠️ Tech Stack

### Frontend

- HTML
- CSS
- JavaScript
- EJS
- EJS-Mate
- Bootstrap

### Backend

- Node.js
- Express.js

### Database

- MongoDB
- Mongoose

### Authentication

- Passport.js
- Passport-Local
- Express-Session

### Image Storage

- Cloudinary

### Other Tools

- Git
- GitHub
- VS Code
- dotenv
- Joi

---

## 📂 Project Structure

```text
Wanderlust/
│
├── controllers/
│   ├── listings.js
│   ├── reviews.js
│   └── users.js
│
├── models/
│   ├── listing.js
│   ├── review.js
│   └── user.js
│
├── routes/
│   ├── listing.js
│   ├── review.js
│   └── user.js
│
├── views/
│   ├── layouts/
│   ├── listings/
│   ├── users/
│   └── includes/
│
├── public/
│   ├── css/
│   └── js/
│
├── utils/
│   ├── ExpressError.js
│   └── wrapAsync.js
│
├── middleware.js
├── schema.js
├── cloudConfig.js
├── app.js
├── package.json
├── package-lock.json
└── README.md
