# 🏕️ Wanderlust — An Airbnb-Style Full Stack Web Development Project

**Wanderlust** is a full-stack web application where users can list their own hotels or vacation stays, write and manage reviews, and explore listings with map integration — delivering a modern Airbnb-like experience.

---

## 🌐 Overview

Wanderlust is a comprehensive **Airbnb-clone** that allows:

- 🏡 Users to **add, edit, and delete hotel or stay listings**
- ✍️ **Write and manage reviews** for listings
- 🗺️ **View listings on an interactive map** using Mapbox
- 🔐 **Sign up, log in, and securely manage your content**
- 💻 Enjoy a clean, responsive interface 

---

## 🛠️ Tech Stack

| Layer        | Technology Used                             |
|--------------|---------------------------------------------|
| Frontend     | EJS Templates, Bootstrap, HTML/CSS          |
| Backend      | Node.js, Express.js                         |
| Database     | MongoDB (via Mongoose)                      |
| Authentication | Passport.js + express-session            |
| Maps         | Mapbox API                                  |
| File Uploads | Multer + Cloudinary                         |
| Deployment   | Render                                       |

---

## 🔥 Features

### 🏨 Listings System:
- Add new listings with:
  - Title, Description, Price, Location
  - Geocoded coordinates from Mapbox
  - One or more images (stored in Cloudinary)

### ✍️ Review System:
- Authenticated users can add reviews
- Users can delete only their own reviews

### 🗺️ Map Integration:
- Listings are geocoded and shown on a map
- Interactive Mapbox map enhances UI

### 🔐 Authentication:
- Register and login functionality using Passport.js
- Sessions and flash messages for feedback
- Access control to restrict edit/delete

### 💅 Interface:
- Fully responsive layout using Bootstrap
- User-friendly and minimal design
- Optimized for mobile and desktop

## ✨ Highlights
📦 Session management with MongoDB
🧠 Schema validation using Joi
🌐 Cloud image handling with Cloudinary
⚠️ Error handling using custom middleware
🗺️ Location services via Mapbox
🔒 Role-based access control for listings and reviews

## Install dependencies
npm install

## Create .env file with the following:
ATLASDB_URL=your-mongodb-atlas-uri
SECRET=your-session-secret
CLOUDINARY_CLOUD_NAME=your-cloud-name
CLOUDINARY_KEY=your-cloudinary-key
CLOUDINARY_SECRET=your-cloudinary-secret

## Start the development server
node app.js or nodemon app.js

👤 Author
Naghma Taj
GitHub: @naghmataj
LinkedIn: www.linkedin.com/in/naghmataj
