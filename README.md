
# MERN-BOILER-PLATE-TS

A modern **MERN (MongoDB, Express, React, Node.js)** fullstack boilerplate built with **TypeScript**. This repository is designed to help developers quickly bootstrap scalable applications with a clean architecture, modular structure, and essential features already integrated.

---

## 🧰 Tech Stack

### 🔹 Frontend
- **React.js** (Vite)
- **TypeScript**
- **Tailwind CSS**
- **Axios**
- **React Router DOM**

### 🔹 Backend
- **Node.js**
- **Express.js**
- **TypeScript**
- **Prisma ORM**
- **MongoDB**
- **Multer** (for file uploads)
- **Cloudinary** (for image storage)
- **JWT** (with HTTP-only cookies)

---

## 📁 Project Structure

```
MERN-BOILER-PLATE-TS/
├── backend/                  # Backend API
│   ├── config/               # DB & Prisma setup
│   ├── controllers/          # Express route controllers (class-based)
│   ├── routes/               # Express route definitions
│   ├── services/             # Business logic layer
│   ├── middlewares/          # Auth, error handler, multer config, etc.
│   ├── utils/                # Reusable helper functions
│   └── index.ts              # Server entry point
│
├── frontend/                 # Frontend React App
│   ├── src/
│   │   ├── components/       # Reusable UI components
│   │   ├── pages/            # Views
│   │   ├── services/         # Axios API services
│   │   ├── types/            # Custom type declarations
│   │   └── main.tsx         # App entry
│
├── docker-compose.yml        # Docker setup (optional)
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/ImRaffy14/MERN-BOILER-PLATE-TS.git
cd MERN-BOILER-PLATE-TS
```

### 2. Install dependencies

#### Backend
```bash
cd backend
yarn install
```

#### Frontend
```bash
cd frontend
yarn install
```

### 3. Environment Variables

#### Backend `.env`
```env
DATABASE_URL=mongodb+srv://<user>:<pass>@cluster.mongodb.net/yourDB
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
JWT_SECRET=your_jwt_secret
PORT=5001
```

#### Frontend `.env`
```env
VITE_API_URL=http://localhost:5000
```

### 4. Run Development Servers

#### Backend
```bash
cd backend
yarn dev
```

#### Frontend
```bash
cd frontend
yarn dev
```

---

## Features

- Full-stack MERN boilerplate with TypeScript support
- User management system including registration, login, profile management, password change, and user editing
- RESTful API with Express and Prisma ORM
- Authentication with JWT and secure cookie handling
- File upload support (e.g., user avatars) using Multer and cloud storage integration
- Middleware for request validation and error handling
- React frontend with TypeScript, React Router, and Axios for API communication
- Modular architecture for easy scalability and maintainability


---

## 📦 Deployment

You can deploy using services like:

- **Frontend:** Vercel, Netlify
- **Backend:** Railway, Render, Fly.io
- **Database:** MongoDB Atlas

---

## 👨‍💻 Author

**ImRaffy14**  
🔗 [GitHub Profile](https://github.com/ImRaffy14)

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).
