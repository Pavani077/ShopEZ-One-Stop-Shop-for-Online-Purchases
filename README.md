🛒 ShopEZ — One Stop Shop for Online Purchases
ShopEZ is a full-stack e-commerce web application that allows users to browse products, filter by categories, manage carts, and place orders. It also includes an simple admin panel for managing products and categories.

This project is built using the MERN stack (MongoDB, Express, React, Node.js).

🚀 Features
👤 User Features
*Register and login Screenshot (335)

Screenshot (334)
Browse all products
Filter products by category and gender
Screenshot (354)
Sort by price and discount
Add products to cart
image
View cart and order details
image
Responsive user interface Screenshot_18-2-2026_135748_localhost
🔧 Admin Features
Screenshot (342)
Add new products Screenshot (343)

Update existing products

Screenshot (357)
Delete products
Add categories
Delete categories
Manage product listings
🛠️ Tech Stack
Frontend

React.js
React Router
CSS
Axios
Backend

Node.js
Express.js
Database

MongoDB
📁 Project Structure
ShopEZ/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── server.js
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
│
└── README.md
⚙️ Installation & Setup
Prerequisites
Make sure you have installed:

Node.js
npm
MongoDB (local or MongoDB Atlas)
Step 1: Clone the repository
git clone https://github.com/padmajakaturi/ShopEZ-One-Stop-Shop-for-Online-Purchases.git
cd ShopEZ-One-Stop-Shop-for-Online-Purchases
Step 2: Setup Backend
cd backend
npm install
Create a .env file inside the backend folder:

MONGO_URI=your_mongodb_connection_string
PORT=6001
Start backend server:

npm start
Step 3: Setup Frontend
Open a new terminal:

cd frontend
npm install
npm start
Open browser:

http://localhost:3000
🔗 API Endpoints
Categories
GET /fetch-categories → Get all categories
POST /add-category → Add category
DELETE /delete-category/:cat → Delete category
Products
GET /fetch-products → Get all products
POST /add-product → Add product
PUT /update-product/:id → Update product
DELETE /delete-product/:id → Delete product
🧠 How It Works
Frontend communicates with backend using REST APIs.
Backend handles product and category logic.
MongoDB stores all application data.
React Router manages navigation.
Axios is used for API requests.
