# 🏡 WanderLust – Airbnb Inspired Accommodation Platform

WanderLust is a full-stack accommodation listing platform inspired by modern vacation-rental applications. Users can explore properties, create listings, upload images, leave reviews, and manage their accounts.

## ✨ Features

* 🔐 User registration and login
* 🏠 Create and manage property listings
* 🔍 Search and explore accommodations
* 🗂️ Category-based property filtering
* 📍 Location-based listings
* ⭐ Reviews and ratings
* 🖼️ Cloud image uploads
* 🗺️ Interactive maps
* ✏️ Edit and delete listings
* 🔒 Protected routes
* 📱 Responsive design
* ✅ Server-side validation

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* EJS
* EJS-Mate

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* Passport.js
* Passport-Local-Mongoose

### Cloud & APIs

* Cloudinary
* Mapbox

### Validation & Utilities

* Joi
* Multer
* Express Middleware

## 🏗️ Architecture

```text
Client
  │
  ▼
Express.js Server
  │
  ├── Authentication
  ├── Routes
  ├── Controllers
  ├── Validation
  │
  ▼
MongoDB
  │
  ├── Users
  ├── Listings
  └── Reviews

External Services
  ├── Cloudinary → Images
  └── Mapbox → Maps
```

## 📁 Project Structure

```text
WanderLust/
├── controllers/
├── models/
├── routes/
├── middleware/
├── public/
├── views/
├── utils/
├── app.js
├── package.json
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/AdityaSingh-max/WanderLust-AirBnb.git
cd WanderLust-AirBnb
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file:

```env
ATLASDB_URL=your_mongodb_connection_string
SECRET=your_session_secret

CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret

MAP_TOKEN=your_mapbox_token
```

### 4. Start the application

```bash
npm start
```

Or, if your project uses nodemon:

```bash
npm run dev
```

## 🔐 Security

* Passwords are securely handled through authentication middleware
* Protected routes prevent unauthorized operations
* Environment variables are used for sensitive credentials
* Server-side validation helps prevent invalid data

## 🎯 Learning Outcomes

* Built a complete full-stack web application
* Worked with MVC architecture
* Implemented authentication and authorization
* Integrated MongoDB with Mongoose
* Implemented image uploads using Cloudinary
* Integrated Mapbox for location-based functionality
* Implemented reviews and listing management
* Practiced RESTful routing

## 🌐 Repository

https://github.com/AdityaSingh-max/WanderLust-AirBnb

## 👨‍💻 Author

**Aditya Singh**

* GitHub: [AdityaSingh-max](https://github.com/AdityaSingh-max)
* LinkedIn: [Aditya Singh](https://www.linkedin.com/in/aditya-singh-844173370/)

⭐ If you like this project, consider giving it a star!
