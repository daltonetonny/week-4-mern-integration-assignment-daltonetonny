# 📰 MERN Stack Blog – Week 4 Assignment

This project is a **full-stack blog application** built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It demonstrates full CRUD functionality, user authentication, and advanced features like image uploads, comments, and pagination.

---

## 🚀 Project Overview

The app allows users to:
- View all blog posts
- Read individual posts
- Create, edit, and delete blog posts
- Register and log in
- Upload featured images
- Leave comments on posts
- Search and filter content
- Paginate through posts

This project showcases clean architecture, API-driven design, and seamless integration between front-end and back-end systems.

---

## 🛠️ Tech Stack

| Layer        | Technology         |
|--------------|--------------------|
| Frontend     | React.js (Vite, Tailwind CSS, Axios) |
| Backend      | Node.js, Express.js |
| Database     | MongoDB (with Mongoose) |
| Auth         | JWT + bcrypt |
| Image Upload | Multer (local or cloud support) |
| Dev Tools    | Nodemon, ESLint, Prettier |

---

## 📁 Project Structure

mern-blog/
├── client/ # React front-end
│ ├── public/
│ ├── src/
│ │ ├── components/ # Reusable UI
│ │ ├── pages/ # Route pages
│ │ ├── hooks/ # Custom React hooks
│ │ ├── services/ # API functions
│ │ ├── context/ # React context
│ │ └── App.jsx
│ └── .env.example # Front-end environment config
├── server/ # Express back-end
│ ├── config/ # MongoDB & env setup
│ ├── controllers/ # Logic handlers
│ ├── models/ # Mongoose schemas
│ ├── routes/ # API routes
│ ├── middleware/ # Auth, error handlers
│ ├── utils/ # Helpers
│ └── server.js # Main server file
│ └── .env.example # Back-end environment config
└── README.md # Project documentation
└── Week4-Assignment.md # Assignment instructions

---

## 📦 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/mern-blog.git
cd mern-blog
2. Set up the server

cd server
cp .env.example .env
npm install
npm run dev
3. Set up the client


cd client
cp .env.example .env
npm install
npm run dev
🔌 API Documentation
Post Routes
Method	Endpoint	Description
GET	/api/posts	Get all posts
GET	/api/posts/:id	Get single post
POST	/api/posts	Create new post
PUT	/api/posts/:id	Update post
DELETE	/api/posts/:id	Delete post

Category Routes
Method	Endpoint	Description
GET	/api/categories	List all categories
POST	/api/categories	Create category

🧠 Features Implemented
 RESTful API

 Front-end routing (React Router)

 Full CRUD for blog posts

 MongoDB with Mongoose models

 JWT-based Auth

 Image upload with Multer

 Pagination & Filtering

 Responsive UI (Tailwind)

 Comments system

🖼️ Screenshots
📌 Include actual app screenshots here after development:
🧪 Testing
API tested using Postman

UI tested manually on Chrome, Firefox, and Edge

📄 License
This project is for educational purposes only under the PLP MERN Stack Program.

📚 References
MongoDB Docs

Express.js Docs

React Docs

Vite Docs
