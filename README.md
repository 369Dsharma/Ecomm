# 🛍️ MERN Shop - E-Store

A full-stack **E-Commerce Web Application** built using the **MERN stack**.  
It includes **authentication**, **product listing with filters**, **cart management**, and **persistent sessions**.

---

## 📌 Features
- User Authentication using **JWT**
- Sign Up & Login functionality
- Product listing with filters (price, category, sorting)
- Add to Cart & Remove from Cart
- Cart persists even after logging out
- Secure backend with **Express + MongoDB**
- Modern UI with **React + Tailwind CSS**

---

## 🛠️ Tech Stack

### Frontend
- React 19
- React Router DOM
- Tailwind CSS
- Axios
- Lucide React (icons)

### Backend
- Node.js + Express.js
- MongoDB + Mongoose
- JWT (Authentication)
- Bcrypt (Password hashing)
- CORS, dotenv

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/mern-shop.git
cd mern-shop
```

### 2️⃣ Setup Backend
```bash
cd ecomm-backend
npm install
```

Create a `.env` file in `ecomm-backend` with:
```
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

Start the backend:
```bash
npm run dev
```

### 3️⃣ Setup Frontend
```bash
cd ../ecomm-frontend
npm install

Create a `.env` file in `ecomm-frontend` with:
```
VITE_API_URL=
```

Start the frontend:
```bash
npm run dev
```

---

## 🚀 Future Enhancements
- Order management system
- Payment gateway integration
- Admin dashboard
- Product reviews & ratings

---

