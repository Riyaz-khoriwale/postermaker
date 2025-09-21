# 🎨 Poster Maker Web App

A **full‑stack web application** that allows users to create stunning posters online, save them, and view them anytime.  
Built with **Node.js, Express, MongoDB, and HTML5 Canvas**. ✨  

---

## 🚀 Features

- 🔐 User Authentication (Login & Signup with JWT)  
- 🎨 Poster Editor with HTML5 Canvas  
- 💾 Save posters to MongoDB (as Base64 or Cloud URL)  
- 📂 User Dashboard → View your saved posters  
- 📱 Responsive frontend (HTML, CSS, JS)  
- 🌐 REST API backend with Express & MongoDB  

---

## 🏗️ Tech Stack

- **Frontend:** HTML, CSS, Vanilla JS (Canvas API)  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (local/Atlas)  
- **Auth:** JWT + bcrypt for secure password storage  
- **Hosting (optional):** Netlify/Vercel (frontend) + Render/Heroku (backend)  

---

## 📂 Project Structure

---

## ⚙️ Installation & Setup (Local Development)

### 1. Clone the repository
```bash
git clone https://github.com/your-username/poster-maker-web-app.git
cd poster-maker-web-app
cd backend
npm install
MONGO_URI=mongodb://127.0.0.1:27017/postermaker
JWT_SECRET=your_secret_key
PORT=5000
node server.js


👉 Backend will run at http://localhost:5000

3. Setup Frontend
Simply open frontend/index.html in your browser
(or use VS Code’s Live Server extension).

📌 API Endpoints
Auth

POST /api/auth/signup → register user
POST /api/auth/login → login, returns JWT
Posters

POST /api/posters/save → save canvas image
GET /api/posters/my → fetch user’s posters

🎯 Usage
Signup/login to create your account
Go to Create Poster page → add your design with text
Click Save Poster → poster stored in DB
View all your saved posters in My Posters page

💡 Future Improvements
Upload custom images in poster
Drag & drop elements
Share poster via link
Export as PDF / PNG
👨‍💻 Author
Made with ❤️ by Riyaztech
