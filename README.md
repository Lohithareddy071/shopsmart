🛒 ShopSmart: Your Digital Grocery Store Experience
📌 Project Overview

**ShopSmart** is a full-stack web application designed to provide users with a seamless and convenient online grocery shopping experience. The platform allows customers to browse products, add items to their cart, manage orders, and complete secure purchases — all from the comfort of their homes.

This project demonstrates modern web development using the MERN stack and follows a client-server architecture.

🚀 Features

* 🔐 User Authentication (Register/Login)
* 🛍️ Browse Grocery Products by Categories
* 🔎 Search & Filter Products
* 🛒 Add to Cart / Remove from Cart
* 💳 Secure Checkout Process
* 📦 Order Management
* 🧾 Order History
* 🛠️ Admin Panel (Add/Edit/Delete Products)
* 📱 Responsive Design (Mobile & Desktop Friendly)


🏗️ Tech Stack

 Frontend

* HTML5
* CSS3
* JavaScript (ES6)
* Bootstrap
* React.js
Backend

* Node.js
* Express.js
Database

* MongoDB
 Tools & Services

* Git & GitHub
* Postman (API Testing)


📂 Project Structure

```
ShopSmart/
│
├── client/                 Frontend (React)
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   └── App.js
│   └── package.json
│
├── server/                  Backend (Node + Express)
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
├── .env
├── package.json
└── README.md
```


⚙️ Installation & Setup
 1️⃣ Clone the Repository

```bash
git clone https://github.com/Lohithareddy071/shopsmart/upload/main.git
cd shopsmart
```
 2️⃣ Setup Backend

```bash
cd server
npm install
```

Create a `.env` file in the `server` folder:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

Start the backend server:

```bash
npm start
```


 3️⃣ Setup Frontend

Open a new terminal:

```bash
cd client
npm install
npm start
```

The application will run at:

```
Frontend: http://localhost:3000
Backend:  http://localhost:5000
```

🔐 Environment Variables

| Variable   | Description                   |
| ---------- | ----------------------------- |
| MONGO_URI  | MongoDB connection string     |
| JWT_SECRET | Secret key for authentication |
| PORT       | Server port number            |


 🧪 API Endpoints (Sample)

 User Routes

* `POST /api/users/register`
* `POST /api/users/login`
* `GET /api/users/profile`
Product Routes

* `GET /api/products`
* `GET /api/products/:id`
* `POST /api/products` (Admin)
* `PUT /api/products/:id` (Admin)
* `DELETE /api/products/:id` (Admin)
Order Routes

* `POST /api/orders`
* `GET /api/orders/myorders`

 📸 Screenshots (Optional)

* Home Page
* Product Listing Page
* Cart Page
* Checkout Page
* Admin Dashboard


🔮 Future Enhancements

* Online Payment Integration (Stripe/Razorpay)
* Real-time Order Tracking
* Wishlist Feature
* Product Reviews & Ratings
* Push Notifications
* Deployment on AWS / Render / Vercel
