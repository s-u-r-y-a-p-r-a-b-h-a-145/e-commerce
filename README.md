# 🛍️ Footwear City - E-Commerce Website

**Footwear City** is a simple e-commerce web application that allows users to browse, add products to their shopping cart, and proceed to checkout. The project is built using **React (Frontend)** and **Node.js with Express (Backend)**, with MongoDB as the database.

## 📌 Features
✅ Browse footwear products  
✅ Add & remove items from the shopping cart  
✅ View cart details & total price  
✅ User authentication & cart management  
✅ Backend API with Express.js  
✅ MongoDB for database storage  

## 🏗️ Tech Stack
- **Frontend:** React, Redux, Bootstrap  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose)  
- **Other:** JWT Authentication, Axios for API calls  

## 🚀 Setup & Installation
### 1️⃣ Clone the repository
```sh
git clone https://github.com/your-username/footwear-city.git
cd footwear-city
```

### 2️⃣ Install dependencies
```sh
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```

### 3️⃣ Start the backend server
```sh
cd backend
node server.js  # or nodemon server.js
```

### 4️⃣ Start the frontend
```sh
cd ../frontend
npm start
```

### 5️⃣ Open in Browser
Visit `http://localhost:3000/` to view the website.

## 🛠️ Issues & Debugging
If the frontend cannot connect to the backend:
- Ensure the backend is running on the correct port (`8000` by default).
- Check `package.json` in the frontend for the `proxy` setting.
- Verify MongoDB is running (`mongod` command).

## 🤝 Contributing
Feel free to fork this repository, raise issues, and submit pull requests!

## 📜 License
This project is licensed under the MIT License.

