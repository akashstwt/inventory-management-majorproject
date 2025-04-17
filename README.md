# Inventory Management - Major Project

This is a full-stack Inventory Management system built with a **TypeScript + Node.js** backend and a **React.js** frontend.

## 📁 Project Structure

- `client/` — Frontend built using React.js
- `server/` — Backend built with Node.js, TypeScript, and Prisma ORM

---

## 🚀 Getting Started

### ✅ Prerequisites

- Node.js (v18+ recommended)
- npm
- PostgreSQL or your preferred database (used with Prisma)

---

## 🖥️ Frontend Setup (Client)

1. Navigate to the client folder:

cd client

2. Install dependencies:

npm install

3. Create a .env file in the client folder and add your environment variables.

NEXT_PUBLIC_API_BASE_URL=http://localhost:5000

4. Run the development server:

npm run dev



## 🛠️ Backend Setup (Server)

1. Navigate to the server folder:

cd server

2. Install dependencies:

npm install

3. Install development dependencies:

npm install -D ts-node typescript

4. Create a .env file in the server folder and add your environment variables.

DATABASE_URL=your_database_url_here
PORT=5000

5. Generate Prisma client:

npx prisma generate

6. Run database migrations:

npx prisma migrate dev --name add_data

7. Start the backend server:

npx ts-node src/index.ts



## 📦 Tech Stack

Frontend: React.js, Tailwind CSS (if used)

Backend: Node.js, TypeScript, Express (if used), Prisma ORM

Database: PostgreSQL (or your configured DB)

## 💡 Notes

Ensure your database is up and running before executing migrations.

Ports, API URLs, and other settings should be configured in the .env files.

You can customize the PORT in both client and server as needed.



