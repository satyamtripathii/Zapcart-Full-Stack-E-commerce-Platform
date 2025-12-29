# 🛒 MERN E-Commerce 2025

A modern **E-Commerce web application** built with the **MERN stack** (MongoDB, Express.js, React, Node.js).  
This project includes authentication, product management, cart system, and order checkout functionality.  

---

## 🚀 Tech Stack

- **Frontend:** React, Redux Toolkit, TailwindCSS / Bootstrap  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB + Mongoose  
- **Authentication:** JWT (JSON Web Tokens)  
- **Tools:** Nodemon, dotenv, bcryptjs, cors  

---

## 📂 Project Structure

mern-ecommerce-2025/
│
├── client/ # React frontend
│ ├── src/
│ └── package.json
│
├── server/ # Express backend
│ ├── server.js
│ ├── models/
│ ├── routes/
│ └── package.json
│
└── README.md

yaml
Copy code

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/mern-ecommerce-2025.git
cd mern-ecommerce-2025
2️⃣ Install Dependencies
Backend (Server)
bash
Copy code
cd server
npm install
Frontend (Client)
bash
Copy code
cd ../client
npm install
▶️ Running the Project
Start Backend
bash
Copy code
cd server
npm run dev
Start Frontend
bash
Copy code
cd client
npm start
🔑 Environment Variables
Create a .env file inside the server folder:

ini
Copy code
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
🌟 Features
✅ User Authentication (Login / Register)
✅ JWT-based Authorization
✅ Product Listing & Search
✅ Shopping Cart Functionality
✅ Order Management
✅ Admin Dashboard (Add / Remove Products, View Orders)




