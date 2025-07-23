# 🧩 Jira Clone – Full Stack Project

A modern, production-ready **Jira Clone** built using **Next.js**, **React**, **Tailwind CSS**, **Prisma**, **Neon**, **Clerk Auth**, and **Shadcn UI**.

---

## 🚀 Tech Stack

- **Next.js 14 (App Router)**
- **React 18**
- **Tailwind CSS**
- **Prisma + Neon DB**
- **Clerk Authentication**
- **Shadcn UI**
- **Zustand (State Management)**

---

## ✨ Features

- 🔐 Secure Auth via Clerk
- 🧑‍💼 Organization Creation + Switching
- 📋 Kanban Board with Issues
- 📁 Modular & Scalable Folder Structure
- 🎨 Beautiful UI with Shadcn Components

---

## ⚙️ Setup Instructions

### 1. Clone & Install

```bash
git clone https://github.com/Bhushansatpute06/Zcrum-Jira-clone-.git
cd Zcrum-Jira-clone-
npm install

2. Create .env File
DATABASE_URL=your_neon_database_url

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
3. Prisma Setup
npx prisma generate
npx prisma migrate dev --name init
4. Run the App
npm run dev
