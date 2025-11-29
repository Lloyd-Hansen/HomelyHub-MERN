# 🏡 HomelyHub – MERN Stack Property Web Application

HomelyHub is a full-stack MERN application that allows users to **rent properties**, **list properties**, manage bookings, and interact with real-time authenticated features.  
It includes a powerful backend with JWT authentication, MongoDB property management, ImageKit integration, and a modern frontend.

HomelyHub is designed to demonstrate real-world production-level MERN development with complete API integration, secure authentication, and scalable architecture.

---

## 🚀 Features

- 🔐 **Secure Authentication** – Signup, login, JWT tokens, cookies  
- 🏘 **Property Listing System** – Add, update, delete, view properties  
- 🛎 **Booking & Renting Flow** – Users can rent available places  
- ⚡ **Real-Time Updates** – Backend changes instantly reflect on frontend  
- 📸 **Image Uploads** – ImageKit integration  
- 📧 **Email Notifications** – Mailtrap for secure testing  
- 📊 **MongoDB Storage** – Property & user data stored securely  
- 🎨 **Modern UI** – Responsive frontend design  
- 🗂 **Full MERN Stack** – Clear separation of frontend & backend  

---

## 🧱 How It Works

1. **User registers or logs in**  
2. Backend generates **JWT tokens** for authentication  
3. Authenticated users can:  
   - Add properties  
   - Rent properties  
   - Update or delete their listings  
4. Backend stores all data in **MongoDB**  
5. Image uploads sent to **ImageKit CDN**  
6. Mailtrap sends email confirmations  

---

## 🏛️ System Architecture

```
Frontend (React)
       ↓
Backend API (Node + Express)
       ↓
MongoDB Database
       ↓
ImageKit (Image Storage)
       ↓
Mailtrap (Email Testing)
```

---

## 📦 Project Structure

```
HomelyHub/
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── eslint.config.js
│   ├── index.html
│   ├── package-lock.json
│   ├── package.json
│   ├── README.md
│   └── vite.config.js 
│
├── backend/
│   ├── src/
│   ├── .env.example
│   ├── package-lock.json
│   ├── package.json
│   └── README.md
│
├── .gitignore
├── README.md
└── LICENSE

```

---

## 🛠 Tech Stack

### **Frontend**
- React.js  
- React Router  
- Tailwind / CSS  

### **Backend**
- Node.js  
- Express.js  
- MongoDB + Mongoose  
- JWT Authentication  
- Cookie Parser  
- Multer/ImageKit  

### **Other Services**
- ImageKit (Images)  
- Mailtrap (Emails)  

---

## ⚙️ Backend Environment Variables

Create a `.env` file in **/backend**

```
PORT=8080
MONGO_URI=mongodb://localhost:27017/HomelyHub

JWT_SECRET=
JWT_EXPIRES_IN=90d
JWT_COOKIE_EXPIRES_IN=90

MAILTRAP_SMTP_HOST=sandbox.smtp.mailtrap.io
MAILTRAP_SMTP_PORT=2525
MAILTRAP_SMTP_USER=
MAILTRAP_SMTP_PASS=

IMAGEKIT_URLENDPOINT=
IMAGEKIT_PRIVATEKEY=
IMAGEKIT_PUBLICKEY=
```

You may also provide a `backend/.env.example` file for GitHub.

---

## 🔧 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Lloyd-Hansen/HomelyHub-MERN.git
cd HomelyHub
```

---

## 🖥 Backend Setup

```bash
cd backend
npm install
cp .env.example .env   # Fill in your real values
npm run dev
```

Runs on:  
👉 **http://localhost:8080**

---

## 🎨 Frontend Setup

```bash
cd frontend
npm install
npm start
```

Runs on:  
👉 **http://localhost:3000**

---

## 🚀 Features Demo

### 🔐 Authentication  
- Secure JWT login  
- Password hashing  
- Cookie-based session  

### 🏘 Property Features  
- Add property  
- Upload images  
- Edit and manage listings  
- Search/filter  

### 🛎 Rent a Property  
- Real-time availability  
- Confirmation email  

---

## 🚨 Troubleshooting

### ❌ MongoDB not connecting  
✔ Ensure MongoDB service is running  
✔ Check `MONGO_URI` in `.env`

### ❌ ImageKit upload failing  
✔ Verify your ImageKit keys  
✔ Ensure URL endpoint is correct

### ❌ Mailtrap not sending emails  
✔ Check SMTP credentials in `.env`  
✔ Test with valid Mailtrap inbox

### ❌ CORS Errors  
✔ Make sure frontend URL is allowed in backend CORS settings

---

## 🎯 Future Enhancements

- 🔄 Booking history  
- ⭐ Reviews & ratings  
- 👤 User dashboard  
- 🗺 Map-based property search  
- 📱 Full mobile app  
- 💳 Payment gateway integration  
- 🧠 AI-powered recommendations (Gemini/ChatGPT)

---

## 🤝 Contributing

1. Fork the repository  
2. Create a new branch  
3. Commit your changes  
4. Push the branch  
5. Open a Pull Request  

---

## 📄 License

This project is licensed under the **MIT License** — see `LICENSE` file.

---

## 📞 Support

For any issues:

- Create an Issue on GitHub  
- Email: your-email@example.com  

---

<div align="center">

### **Built with ❤️ using MERN Stack**

[Report Bug](https://github.com/Lloyd-Hansen/HomelyHub-MERN/issues) ·  
[Request Feature](https://github.com/Lloyd-Hansen/HomelyHub-MERN/issues)

</div>
