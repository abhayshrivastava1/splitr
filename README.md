# Splitr – AI-Powered Expense Splitting App 💸

Splitr is a full-stack, real-time expense splitting application powered by AI. It simplifies group and individual expense management with smart insights, collaborative features, and automated reminders.

## 🚀 Features

- 💡 AI-generated spending insights
- 🔄 Real-time sync for group expenses
- ✉️ Automated payment reminders via email
- 🔐 Secure user authentication and access control
- 📊 Clean, responsive UI for desktop and mobile

## 🛠️ Tech Stack

### Frontend
- React 19
- Next.js 15 (App Router)
- Tailwind CSS
- Shadcn UI

### Backend
- Convex (real-time backend and functions)
- Prisma ORM
- PostgreSQL

### Auth & Automation
- Clerk (Authentication & Authorization)
- Inngest (Serverless workflows)
- Resend (Transactional Emails)

## ⚙️ Architecture Overview

- `Convex` handles API logic, real-time updates, and state management.
- `Prisma + PostgreSQL` stores structured expense data.
- `Clerk` provides secure authentication flows.
- `Inngest` automates AI-driven analysis and reminder jobs.
- `Resend` sends transactional emails for reminders and updates.


