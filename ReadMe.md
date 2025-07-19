# <img src="./WebPics/favicon.svg" alt="QuickBlog Logo" width="50" height="29"> QuickBlog

**QuickBlog** is an AI-powered blogging application that makes it easy to create, manage, and publish blog posts. 🌟 With an intuitive React frontend, a Node/Express backend, and MongoDB for storage, QuickBlog also integrates ImageKit for seamless image uploads. 🖼️

---

## 🚀 Live Demo

Check out the live app here:
🔗 [https://quick-blog-frontend-nu.vercel.app/](https://quick-blog-frontend-nu.vercel.app/)

---

## 🎨 Preview

![QuickBlog Preview](./WebPics/preview1.png)

![QuickBlog Preview](./WebPics/preview2.png)

---

## 📂 Project Structure

```
quickblog/
├── backend/
│   ├── src/
│   ├── .env
│   ├── package.json
│   └── ...
└── frontend/
    ├── src/
    ├── .env
    ├── package.json
    └── ...
```

---

## 🔧 Tech Stack

* **Frontend**: Vite + React 19
* **Backend**: Node.js + Express
* **Database**: MongoDB
* **Image Uploads**: ImageKit
* **AI Integration**: Gemini free model

---

## 📝 Prerequisites

* Node.js v14+
* npm or yarn
* MongoDB (local or Atlas)
* ImageKit account (for API keys)
* Gemini API key for additional AI features

---

## ⚙️ Configuration

### Backend

In `backend/.env`, create the file (or rename from `.env.example`) and fill in your values:

```dotenv
PORT=4000
MONGODB_URI="Your Mongodb_Url"

# Admin Credentials
ADMIN_EMAIL='your-admin@example.com'
ADMIN_PASSWORD='yourAdminPassword'

# JWT Secret
JWT_SECRET='yourJwtSecret'

# ImageKit
IMAGEKIT_PUBLIC_KEY='yourImageKitPublicKey'
IMAGEKIT_PRIVATE_KEY='yourImageKitPrivateKey'
IMAGEKIT_URL_ENDPOINT='yourImageKitUrlPoint'

# Gemini (Optional)
GEMINI_API_KEY='yourGeminiApiKey'
```

### Frontend

In `frontend/.env`, create the file (or rename from `.env.example`) and fill in:

```dotenv
VITE_BACKEND_URL="YourBackendUrl" (e.g. http://localhost:4000)
```

---

## 📦 Installation & Running

### 1. Clone the repo

```bash
git clone https://github.com/Krishna200608/QuickBlog.git
cd QuickBlog
```

### 2. Backend Setup

```bash
cd backend
npm install

# Create or update your .env file now with the variables above
# Then start the server:
npm run server
```

By default, the backend will run at `http://localhost:4000`.

### 3. Frontend Setup

Open a new terminal:

```bash
cd frontend
npm install

# Start the client:
npm start
```

The frontend will start at `http://localhost:5173` (or another port Vite chooses).

---

## 🎉 Usage

* Register or log in with the admin credentials you set in your backend `.env`.
* Create, edit, and delete blog posts.
* Upload images directly via ImageKit integration.
* Explore AI-powered features for generating post ideas, titles, or content.

---

## 📝 License

This project is licensed under the IIITA License.

---

## 💬 Contact

Questions, feedback, or contributions? Reach out to:

* **Krishna Sikheriya** – [krishnasikheriya001@gmail.com](mailto:krishnasikheriya001@gmail.com)
* GitHub: [github.com/Krishna200608](https://github.com/Krishna200608)

---

*Happy blogging with QuickBlog!*
