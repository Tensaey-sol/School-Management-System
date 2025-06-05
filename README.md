# 🏫 School Management System

A modern, beginner-friendly **School Management System** built with **React**, **Next.js**, **Prisma ORM**, and **PostgreSQL**. This project includes admin, teacher, student, and parent dashboards all styled with **Tailwind CSS**, featuring responsive tables, animated charts, role-based authentication, and containerized for deployment using **Docker**.

---

## 🚀 Features

- 🔐 **Authentication** with login and role-based access control
- 🧭 **Protected routes** using Next.js middleware
- 📊 **Dynamic dashboards** for Admin, Teacher, Student, and Parent roles
- 🧑‍🏫 **CRUD operations** for users and resources
- 🎨 Responsive UI with Tailwind CSS
- 📈 Interactive and animated charts (Recharts)
- 🐳 **Dockerized** for containerized deployment
- 🗃️ **PostgreSQL** as the primary database
- ⚙️ **Prisma ORM** for database interaction

---

## 🛠 Tech Stack

- **Frontend:** React, Next.js, Tailwind CSS
- **Backend:** Next.js API Routes
- **ORM:** Prisma
- **Database:** PostgreSQL
- **Authentication:** Clerk (role-based)
- **Charts:** Recharts
- **Deployment:** Docker

---

## 📦 Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- PostgreSQL
- Docker (optional, for containerized setup)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Tensaey-sol/School-Management-System.git
   cd school-management-dashboard
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Configure environment variables:**

   - Copy `.env.example` to `.env` and update the database connection string and Clerk credentials.

4. **Set up the database:**

   ```bash
   npx prisma migrate dev --name init
   npx prisma db seed
   ```

5. **Run the development server:**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🐳 Docker Usage

1. **Build and run with Docker:**
   ```bash
   docker-compose up --build
   ```
   This will start the app and a PostgreSQL database.

---

## 📚 Project Structure

- `/src/app` — Next.js app directory (pages, layouts, API routes)
- `/src/components` — Reusable UI components
- `/src/lib` — Utility functions, Prisma client, and mock data
- `/prisma` — Prisma schema and seed scripts

---

## 👤 Roles & Dashboards

- **Admin:** Manage users, classes, subjects, and view analytics.
- **Teacher:** Manage lessons, assignments, grades, and view schedules.
- **Student:** View personal schedule, results, and announcements.
- **Parent:** View child's progress, results, and school events.

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Create a new Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
