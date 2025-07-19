# QuickBlog

**QuickBlog** is an AI-powered blogging application that makes it easy to create, manage, and publish blog posts. With an intuitive React frontend, a Node/Express backend, and MongoDB for storage, QuickBlog also integrates ImageKit for seamless image uploads.

---

## 🚀 Live Demo

Check out the live app here:
🔗 [https://quick-blog-frontend-nu.vercel.app/](https://quick-blog-frontend-nu.vercel.app/)

---

## 🎨 Preview

Upload or replace the image below with a screenshot of your running QuickBlog app:

![QuickBlog Preview](./preview.png)

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
* **AI Integration**: (Your chosen AI service or library)

---

## 📝 Prerequisites

* Node.js v14+
* npm or yarn
* MongoDB (local or Atlas)
* ImageKit account (for API keys)
* (Optional) Gemini API key for additional AI features

---

## ⚙️ Configuration

### Backend

In `backend/.env`, create the file (or rename from `.env.example`) and fill in your values:

```dotenv
PORT=4000
MONGODB_URI=mongodb://localhost:27017/quickblog
# MONGODB_URI="mongodb+srv://<username>:<password>@cluster0.ix5ng.mongodb.net/quickblog"

# Admin Credentials
ADMIN_EMAIL='your-admin@example.com'
ADMIN_PASSWORD='yourAdminPassword'

# JWT Secret
JWT_SECRET='yourJwtSecret'

# ImageKit
IMAGEKIT_PUBLIC_KEY='yourImageKitPublicKey'
IMAGEKIT_PRIVATE_KEY='yourImageKitPrivateKey'
IMAGEKIT_URL_ENDPOINT='https://ik.imagekit.io/your_imagekit_id'

# Gemini (Optional)
GEMINI_API_KEY='yourGeminiApiKey'
```

### Frontend

In `frontend/.env`, create the file (or rename from `.env.example`) and fill in:

```dotenv
VITE_BACKEND_URL=http://localhost:4000
```

---

## 📦 Installation & Running

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/quickblog.git
cd quickblog
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
* (Optional) Explore AI-powered features for generating post ideas, titles, or content.

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 💬 Contact

Questions, feedback, or contributions? Reach out to:

* **Krishna Sikheriya** – [krishna@example.com](mailto:krishna@example.com)
* GitHub: [github.com/yourusername](https://github.com/yourusername)

---

*Happy blogging with QuickBlog!*
