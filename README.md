# 📦 Review System Backend (Node.js + Express + MongoDB)

A backend API that allows users to create, read, update, and delete reviews.  
Built using MVC architecture with clean routing, controllers, and models.

---

## 🚀 Features

- Add new reviews  
- Get all reviews / reviews by ID  
- Update reviews  
- Delete reviews  
- MongoDB database integration  
- Modular MVC folder structure  
- REST API design  
- Environment variable support  

---

## 🧱 Project Structure

Review-System-Backend  
│  
├── config/ # Database connection setup  
├── controllers/ # Review logic  
├── models/ # Mongoose schemas  
├── routes/ # API routes  
├── middleware/ # (Optional) auth/validation  
├── server.js # Entry point  
└── package.json  

---

## 🛠️ Tech Stack  
- Node.js  
- Express.js  
- MongoDB & Mongoose  
- Nodemon  
- dotenv  

---
🧪 Testing  
Use Postman, Thunder Client, or Insomnia to test API routes.  

🧩 Future Enhancements  
User authentication (JWT)  
Review replies  
Like/Dislike system  
Rating aggregation  
React frontend UI  

---

## ⚙️ Installation
```bash
1️⃣ Clone the repository
git clone https://github.com/Diksha489/Review-System-Backend-2.git
cd Review-System-Backend-2

2️⃣ Install dependencies
npm install

3️⃣ Setup environment variables
Create a .env file:
PORT=5000
MONGO_URI=your_mongodb_connection_string

4️⃣ Start the server
npm start
Or using nodemon:
npm run dev  

📡 API Endpoints
Base URL: http://localhost:5000/api/reviews

POST/Add a new review
Example body:
{
  "name": "Diksha",
  "rating": 5,
  "comment": "Excellent!"
}

GET /
Get all reviews

GET /:id
Get review by ID

PUT /:id
Update a review

DELETE /:id
Delete a review  
