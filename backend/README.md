
---

# **Backend README.md**

````markdown
# 🏡 HomelyHub – Backend  
Powerful RESTful API backend powering the HomelyHub property rental platform.

## 🚀 Tech Stack
- **Node.js + Express.js**
- **MongoDB + Mongoose**
- **JWT Authentication**
- **bcryptjs** for password hashing  
- **ImageKit** for image storage  
- **Mailtrap** for transactional emails  
- **Multer** for file handling  
- **CORS** for secure cross-origin access  

---

## 📦 Installation & Setup

```bash
cd backend
npm install
````

---

## ▶️ Development

```bash
npm run dev     # Runs with nodemon
```

Runs on: **[http://localhost:8080](http://localhost:8080)**

---

## 🏃 Production

```bash
npm start
```

---

## 🔐 Environment Variables

Create `.env` inside **backend/**:

```env
# Server
PORT=8080
NODE_ENV=development

# Database
MONGO_URI=mongodb://localhost:27017/homelyhub

# JWT Auth
JWT_SECRET=your_jwt_secret_key
JWT_EXPIRES_IN=90d
JWT_COOKIE_EXPIRES_IN=90

# Mailtrap Email Service
MAILTRAP_SMTP_HOST=sandbox.smtp.mailtrap.io
MAILTRAP_SMTP_PORT=2525
MAILTRAP_SMTP_USER=your_mailtrap_user
MAILTRAP_SMTP_PASS=your_mailtrap_pass

# ImageKit (Media Storage)
IMAGEKIT_URLENDPOINT=your_imagekit_url
IMAGEKIT_PUBLICKEY=your_public_key
IMAGEKIT_PRIVATEKEY=your_private_key
```

---

## 📁 Project Structure

```
 backend/
    ├── src/
    │     ├── .env.example
    │     ├── package-lock.json
    │     ├── package.json
    │     └── README.md
    ├── .env.example
    ├── package-lock.json
    ├── package.json
    └── README.md    
```

---

## 🗂 API Endpoints

```
# Property
GET     /api/properties           → Get all properties
POST    /api/properties           → Add property
GET     /api/properties/:id       → Get single property
PUT     /api/properties/:id       → Update property
DELETE  /api/properties/:id       → Delete property

# Authentication
POST    /api/auth/register        → Register user
POST    /api/auth/login           → Login user
GET     /api/auth/logout          → Logout user
GET     /api/auth/me              → Current user profile

# Bookings
POST    /api/bookings             → Make a booking
GET     /api/bookings             → Get user bookings
```

---

## 🛡 Security Features

* 🔐 **Hashed passwords (bcryptjs)**
* 🛂 **JWT Authentication**
* 🚫 **Protected Route Middleware**
* 🌐 **CORS Setup**
* 🧹 **Input Validation**
* 🚦 **Rate Limiting (recommended for production)**

---

## 📊 Database Models

* **User** → Authentication, profile
* **Property** → Listing info, images
* **Booking** → Reservations
* **Review** → Ratings & comments

---

## 🔧 Scripts

```bash
npm start          # Production
npm run dev        # Development (nodemon)
npm test           # Testing (if added)
```

---

## 🚀 Deployment Notes

* Set `NODE_ENV=production`
* Use a **cloud MongoDB URI** (MongoDB Atlas)
* Add your **frontend domain** to CORS
* Use **strong JWT secrets**
* Use **ImageKit live keys**
* Secure HTTPS recommended

---

