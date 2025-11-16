# 🍽️ Restaurant Application Frontend

This repository contains the frontend of my **MERN stack Restaurant Application**, built using **React, React Router, and Context API**. It provides a smooth and minimal UI for browsing menus, placing orders, and handling authentication while communicating with the backend API.

---

## 🚀 Tech Stack

- **React (Functional Components)**
- **React Router**
- **Context API** for global state  
- **Fetch / Axios** for API requests  
- **CSS** (or your preferred styling)

---

## 📁 Project Structure

restaurant-frontend/
│
├── public/
├── src/
│ ├── components/
│ ├── pages/
│ ├── context/
│ ├── App.jsx
│ └── main.jsx
│
├── package.json
└── README.md

yaml
Copy code

---

## 📦 Features

### ✅ Public Pages
- **Home** – Overview screen  
- **Menu** – Fetch menu items from backend  

### 🔐 Authentication
- **Login**  
- **Signup**  
- JWT-based flow with backend  

### 🛒 Orders
- View user orders  
- Create orders (authenticated)  

---

## 🔗 Backend Integration

Frontend communicates with a backend hosted on Railway:

**Backend API:**  
https://restaurant-backend-production-619b.up.railway.app/

### Used for:
- **Auth** (login / register)  
- **Menu Items** (fetching)  
- **Orders** (create + fetch)  

Currently the backend URL is directly used inside fetch/axios calls (no `.env`).

---

## 🧪 Installation & Setup

### 1️⃣ Clone the project
```sh
git clone https://github.com/Vasu10134/Restaurant-Frontend
cd Restaurant-Frontend
2️⃣ Install dependencies
sh
Copy code
npm install
3️⃣ Run in development mode
sh
Copy code
npm run dev
Runs at:
arduino
Copy code
http://localhost:5173
🌐 Deployment
Frontend is deployed on Netlify:

🔥 Live URL
https://restrau-frontend.netlify.app/

Build command:

arduino
Copy code
npm run build
Output folder:

nginx
Copy code
dist
🔗 Related Repositories & Links
Section	URL
Frontend Repo	https://github.com/Vasu10134/Restaurant-Frontend
Frontend Live	https://restrau-frontend.netlify.app/
Backend Repo	https://github.com/Vasu10134/Restaurant-Backend
Backend API	https://restaurant-backend-production-619b.up.railway.app/

📌 Notes
This frontend works tightly with the backend’s JWT-based authentication, menu CRUD, and order APIs. Context API is used for managing global states like user auth and cart/order info.

yaml
Copy code

---

If you want, I can also add:

✅ Screenshots section  
✅ API usage examples  
✅ Badges (build, tech stack icons, etc.)  
Just say the word.
