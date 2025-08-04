# SneakerHub

SneakerHub is a sleek, modern sneaker e-commerce web application built using **React**, **TypeScript**, **Tailwind CSS**, and **Vite**. This project features responsive layouts, dynamic product pages, and elegant UI components tailored for sneakerheads and collectors.

🔗 Live Demo: [sneakerrhub.netlify.app](https://sneakerrhub.netlify.app)

---

## 🚀 Features

- ⚡ Lightning-fast performance using **Vite**.
- 🎨 Utility-first styling with **Tailwind CSS**.
- 🔄 Dynamic routing with **React Router DOM**.
- 📦 Global state/data fetching using **TanStack React Query**.
- 🎯 Tooltips and toasts with `@/components/ui/tooltip` and `sonner`.
- 🔍 Product detail page with route parameter (`/product/:id`).
- ❌ Custom 404 Not Found page.
- 📱 Fully responsive UI.

---

## 🛠️ Technologies Used

- React (with Hooks)
- TypeScript
- Vite
- Tailwind CSS
- React Router DOM
- TanStack React Query
- Toast + Sonner + Tooltip components

---

## 📂 Folder Structure

```
sneakerhub/
│
├── client/                # Frontend (React + Vite)
│   ├── public/
│   ├── src/
│   │   ├── assets/         # Images, logos, icons
│   │   ├── components/     # Reusable components (ShoeCard, Navbar, etc.)
│   │   ├── pages/          # Routes/views like Home, ProductPage
│   │   ├── service/        # API service functions
│   │   ├── App.tsx
│   │   ├── main.tsx
│   │   └── index.css
│   ├── vite.config.ts      # Vite config (with proxy)
│   └── package.json
│
├── server/               # Backend (Node + Express)
│   ├── controllers/       # Business logic for routes
│   │   └── sneakerController.js
│   ├── models/            # DB schema (if using MongoDB later)
│   ├── routes/
│   │   └── sneakerRoutes.js
│   ├── config/
│   │   └── db.js           # DB connection logic (optional now)
│   ├── server.js           # Main Express entry point
│   └── package.json
│
├── .env                  # Environment variables
├── README.md
└── .gitignore
```

---

## ✨ Special Elements

1. **React Query Integration**
   - Powerful global state and async data handling with `@tanstack/react-query`.

2. **Advanced Notification System**
   - Dual-layer feedback using both `Toaster` and `Sonner` components.

3. **Dynamic Product Routing**
   - Clean product detail navigation using `/product/:id`.

4. **TypeScript Architecture**
   - Robust type safety across the entire codebase.

5. **Mobile-First & Component-Based UI**
   - Built with Tailwind and modular design to ensure performance and scalability.

---

## 📦 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/your-username/sneakerhub.git
cd sneakerhub

# Install dependencies
npm install

# Run the development server
npm run dev




---

🌐 Live URL

👉 https://sneakerrhub.netlify.app



