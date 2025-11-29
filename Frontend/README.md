
---

# **Frontend README.md**

````markdown
# ✨ HomelyHub – Frontend

A modern, fast, and elegantly crafted **React + Vite** frontend powering the HomelyHub property rental platform.  
Designed for seamless browsing, listing, and booking of properties — with a clean UI and smooth user experience.

---

## 🚀 Tech Stack

- ⚛️ **React 18** + Vite — blazing fast frontend development  
- 🧭 **React Router DOM** — effortless navigation  
- 🔗 **Axios** — smooth API communication  
- 🎨 **Tailwind CSS** — fully responsive modern UI  
- 🧠 **Context API** — global state management  
- 📝 **React Hook Form** — robust form validation  
- 🔔 **React Hot Toast** — elegant alerts & notifications  

---

## 📦 Installation & Setup

```bash
cd frontend
npm install
````

---

## ▶️ Development

```bash
npm run dev
```

App runs locally at:
👉 **[http://localhost:5173](http://localhost:5173)**

---

## 🌐 Environment Variables

Create `.env` inside the **frontend** directory:

```env
VITE_API_URL=http://localhost:8080/api
VITE_IMAGEKIT_URL=https://ik.imagekit.io/your_endpoint/
```

---

## 📁 Project Structure

```
frontend/
   ├── public/
   ├── src/
        ├── assets/
        ├── components/
        ├── css/
        ├── store/
        ├── utils/
        ├── App.css
        ├── App.jsx
        ├── index.css
        └── main.jsx
   ├── eslint.config.js
   ├── index.html
   ├── package-lock.json
   ├── package.json
   ├── README.md
   └── vite.config.js 
```

---

## 🎯 Key Features

* 🔐 **User Authentication** – Secure JWT login & signup
* 🏘️ **Property Management** – Add, edit, or remove properties
* 🔍 **Smart Browsing** – Search & filter listings easily
* 📅 **Booking System** – Reserve places instantly
* 📱 **Fully Responsive** – Works beautifully on all devices
* ☁️ **Cloud Uploads** – ImageKit integration for images

---

## 📦 Build for Production

```bash
npm run build
npm run preview  # Preview production build
```

---

## 🔧 Scripts

```bash
npm run dev          # Start development server
npm run build        # Create production build
npm run preview      # Preview production build
npm run lint         # Run ESLint
```

---

## 🛠 Dependencies

```bash
# Core
react react-dom react-router-dom
axios

# UI & Styling
tailwindcss @headlessui/react

# Forms & UX
react-hook-form react-hot-toast

# Development
@vitejs/plugin-react eslint
```


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

Here is your **Frontend README.md** made more **creative, clean, branded, and attractive**, while keeping your entire structure *exactly the same* — only improved wording, icons, spacing, and presentation.

Your code blocks, layout, and content remain fully intact.
Only improved the **readability + visual appeal**.
