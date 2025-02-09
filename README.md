# 🛒 Product Store

## 📌 Overview
The **Product Store** is a full-stack e-commerce application built using the **PostgreSQL, Express.js, React.js, and Node.js (PERN stack)**. It allows users to browse products, add them to a cart, and manage orders efficiently.

## 🚀 Features
- 🛍️ **Product Management**: Create, read, update, and delete (CRUD) products.
- 🛒 **Cart System**: Add/remove products from the cart.
- 🔐 **User Authentication**: Secure login/signup using JWT.
- 🗄️ **PostgreSQL Database**: Relational data storage for products, users, and orders.
- ⚡ **RESTful API**: Built with Express.js and Node.js.
- 🎨 **Responsive UI**: Designed with React.js and Tailwind CSS.

## 🏗️ Tech Stack
- **Frontend**: React.js, React Router, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL (using Sequelize ORM)
- **Authentication**: JWT (JSON Web Token)

## 📂 Project Structure
```
pern-product-store/
│── backend/           # Express.js backend
│   ├── models/        # Database models (Sequelize)
│   ├── routes/        # API routes
│   ├── controllers/   # Request handling logic
│   ├── config/        # Database connection
│   ├── server.js      # Entry point
│
│── frontend/          # React.js frontend
│   ├── src/
│   │   ├── components/   # Reusable UI components
│   │   ├── pages/        # Page components
│   │   ├── services/     # API service functions
│   │   ├── App.js        # Main React component
│
│── .env               # Environment variables
│── package.json       # Dependencies and scripts
│── README.md          # Project documentation
```

## 🛠️ Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Piyushchannawar/PostgreStore.git
```

### 2️⃣ Backend Setup
```bash
cd backend
npm install
cp  .env   # Configure database settings
npm start
```

### 3️⃣ Frontend Setup
```bash
cd ../frontend
npm install
npm start
```

### 4️⃣ Open in Browser
The application runs on:
- **Frontend**: `http://localhost:3000`
- **Backend API**: `http://localhost:5000`

## 📸 Screenshots
![Product List](C:\Users\piyush channavar\Desktop\Project\PERN_Stack_ProductStore\frontend\public\image.png)

## 🛡️ Security & Best Practices
- **Use environment variables** for sensitive information.
- **Implement role-based authentication** for admin and users.
- **Validate user inputs** to prevent SQL injection.

## 🤝 Contributing
Pull requests are welcome! Follow these steps:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m "Added new feature"`)
4. Push to the branch (`git push origin feature-name`)
5. Create a pull request

## 📄 License
This project is licensed under the MIT License.
