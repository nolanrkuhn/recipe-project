# Recipe App 🍽️

A full-stack recipe app using React (frontend) and Express.js (backend), powered by Spoonacular API.

## 📥 Installation

### **1️⃣ Clone or Download the Project**
- **Download ZIP**: Extract the files from the provided ZIP.
- **Or Clone via Git**:
  ```bash
  git clone https://github.com/nolanrkuhn/recipe-app.git
  cd recipe-app
  ```

### **2️⃣ Backend Setup (Server)**
```bash
cd server
npm install
cp .env.example .env  # Add your Spoonacular API Key
npm start  # Runs on http://localhost:5000
```

### **3️⃣ Frontend Setup (React App)**
```bash
cd ../react-app
npm install
npm start  # Runs on http://localhost:3000
```

---

## 🚀 Deployment

### **Backend: Deploy on Render**
1. Go to [Render](https://render.com/)
2. Create a new **Web Service**.
3. Connect your GitHub repo or upload files manually.
4. Set environment variable `SPOONACULAR_API_KEY`.
5. Deploy!

### **Frontend: Deploy on Vercel or Surge**
#### **Vercel**
```bash
npm install -g vercel
vercel
```
#### **Surge**
```bash
npm install -g surge
npm run build
surge ./build your-app-name.surge.sh
```

---

## 📌 Features
- 🔍 **Search Recipes** using Spoonacular API.
- ⭐ **Save Favorites** and manage your collection.
- 📖 **View Recipe Details** with full instructions.

Enjoy coding! 🚀
