# 🧠 SmartBlog : 

URL : smart-blog-phi.vercel.app
An **AI-powered full-stack blogging platform** built using the **MERN Stack**, integrated with **ImageKit** and **Google APIs** for intelligent automation and seamless media handling.

---

## 🚀 Overview

SmartBlog is a modern blog platform designed for both readers and creators.  
It allows users to **read, search, filter, and comment** on blogs — while admins can **create, manage, and publish** content through a secure admin panel.

With AI-assisted features like **auto-generated blog descriptions**, SmartBlog simplifies the writing process and enhances user engagement.

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose ODM)  
- **Authentication:** JWT (JSON Web Tokens)  
- **Image Handling:** ImageKit API  
- **AI Integration:** Google API for auto-generating blog descriptions  

---

## 🔐 Key Features

### 🌐 User Features
- Browse and read blogs with rich formatting  
- Search and filter posts by tags, categories, or keywords  
- Leave comments on posts  
- View AI-generated descriptions for smarter content discovery  

### 🧑‍💻 Admin Features
- **Secure authentication** via JWT and role-based access control  
- **Admin Dashboard** to:
  - Create, edit, and publish blogs  
  - Moderate user comments  
  - Manage authored posts and drafts  

---

## ⚙️ Setup & Installation

## 1️⃣ Clone the Repository

git clone https://github.com/<your-username>/SmartBlog.git
cd SmartBlog

---
## 2️⃣ Install Dependencies
For both client and server:

cd client
npm install
cd ../server
npm install

---
## 3️⃣ Configure Environment Variables
Create a .env file in the server directory with the following keys:

MONGO_URI=<your_mongodb_uri>
JWT_SECRET=<your_jwt_secret>
IMAGEKIT_PUBLIC_KEY=<your_imagekit_public_key>
IMAGEKIT_PRIVATE_KEY=<your_imagekit_private_key>
GOOGLE_API_KEY=<your_google_api_key>

---

## 4️⃣ Run the App
Start both frontend and backend:

bash
Copy code
# In server
npm run dev

# In client (new terminal)
npm start
App will be running on:

Frontend: http://localhost:3000
Backend:  http://localhost:5000
---

## 🤖 AI Integration (Google API)
SmartBlog uses Google API to automatically generate engaging blog descriptions using natural language processing.
Admins can leverage this feature while creating or editing posts to speed up content creation.

---
## 📸 Image Handling (ImageKit)
All media uploads are optimized and served via ImageKit CDN

Automatic resizing and compression for faster load times

Secure upload and retrieval using API authentication
---
###🧩 Folder Structure

SmartBlog/
├── client/              # React Frontend
│   ├── src/
│   ├── components/
│   └── pages/
├── server/              # Express Backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── middleware/
└── README.md
### 💡 Future Enhancements
AI-powered content summarization

User profiles and following system

Blog analytics dashboard for admins

Dark mode and accessibility improvements

### 👨‍💻 Developer
Krish Vanza
Developer




