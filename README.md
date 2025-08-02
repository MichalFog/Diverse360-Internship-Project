# 🌐 Diverse360 – Internship Project

**Diverse360** is a full-stack web application I developed as part of my internship at [Diversitech](https://www.diversitech.co.il).

The platform is designed for Diversitech students and alumni, offering:
- 📚 Learning materials
- 💼 Job board
- 🧑‍🤝‍🧑 Community features

🔗 **Live Demo:**  
👉 [diversitech.pages.dev](https://diversitech.pages.dev)

---

## ⚙️ Tech Stack

This project is powered by a modern TypeScript monorepo using:

- **Frontend**: React + TypeScript (deployed on Netlify)
- **Backend**: Express + TypeScript (deployed on Render)
- **Database**: Supabase (PostgreSQL with RLS and API integration)
- **CI/CD**: GitHub → Render / Netlify

---

## 📁 Project Structure

```
monorepo/
├── packages/
│   ├── frontend/       # React app
│   ├── backend/        # Express server
│   └── shared/         # Shared types and utilities
```

---

## 🚀 Setup Instructions (Dev Mode)

```bash
# Clone the repository
git clone <your-repo-url>
cd base-project

# Install all dependencies
npm run install:all

# Build shared package
cd packages/shared && npm run build && cd ../..

# Set up environment variables
cd packages/backend && cp .env.example .env
cd ../frontend && cp .env.example .env && cd ../..

# Run both frontend and backend
npm run dev
```

---

## 🏁 Deployment Overview

- **Frontend**: [Netlify](https://netlify.com)
- **Backend**: [Render](https://render.com)
- **Database**: [Supabase](https://supabase.com)

Production URLs:
- Frontend: [https://diversitech.pages.dev](https://diversitech.pages.dev)
- Backend API: [https://diverse-360-backend.onrender.com/api](https://diverse-360-backend.onrender.com/api)

---

## ✅ Features

- Responsive UI built with React and TypeScript
- REST API with authentication and validation
- Supabase integration with RLS and policies
- Deployment-ready monorepo with clear structure
- Health check and CORS configuration for production

---

## 🧑‍💻 Author

This project was created as part of my software development internship at Diversitech.

Feel free to explore the code, clone the repo, and reach out with feedback or questions!

---

*Thank you for visiting!* 🚀