# 🛒 E-Commerce Admin Panel (MERN Stack)

A **full-stack E-Commerce Admin Panel** built using the **MERN stack**, featuring **Category, Sub-Category, and Product management**, secure **Admin Authentication**, **Cloudinary image handling**, and a **modern React + Tailwind UI**.

🌐 **Live App:**  
https://ecommerce-bysabbir.netlify.app/

---

## 🚀 Tech Stack

### Frontend
- React (Vite)
- Tailwind CSS
- Context API
- Fetch API
- React Router DOM

### Backend
- Node.js
- Express.js
- MongoDB + Mongoose (local server) and MongoDB compass (cloud)
- JWT Authentication
- Bcrypt
- Cors
- Cloudinary
- Multer

### Deployment
- Frontend: Netlify  
- Backend: Render  
- Database: MongoDB Atlas  
- Images: Cloudinary  

---

## 🔐 Authentication & Authorization
- Admin login with JWT
- Protected admin routes
- Persistent login on refresh
- Auto redirect logic
- Logout support

---

## 📦 Features

### Category
- Add / Edit / Delete
- Image upload
- Active / Inactive status
- Cloudinary cleanup

### Sub-Category
- Add / Edit / Delete
- Category mapping
- Image + status update

### Product
- Add / Edit / Delete
- Multiple images
- Category & Sub-category select
- Status update
- Image cleanup

### Dashboard
- Category count
- Sub-category count
- Product count

---

## 📁 Backend Structure

```
backend/
├── auth/
├── config/
├── controllers/
├── db/
├── middleware/
├── models/
├── routes/
├── utils/
├── server.js
└── package.json
```

---

## 📁 Frontend Structure

```
frontend/
├── src/
│   ├── admin/
│   ├── context/
│   ├── App.jsx
│   └── main.jsx
├── public/
└── package.json
```

---

## 🧠 Image Handling
- Centralized upload API
- Stores public_id + url
- Deletes images on update & delete

---

## ✅ Status
All core admin panel features are implemented.  
No pending critical functionality.

---

## 👤 Author
**Sk Sabbir Ali**
