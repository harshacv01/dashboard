# Next.js Dashboard Application

## 🚀 Overview
This project is a fully-functional dashboard application built using **Next.js**. It highlights the framework's advanced features while providing a robust and user-friendly interface for managing data.

## ✨ Features

### 🔒 Authentication & Authorization
- Secure login and access control.
- User authentication ensures that only authorized users can access the dashboard.

### 🛠️ CRUD Operations
- Perform full **Create, Read, Update, and Delete** actions for data management.

### 🚀 Server Components
- Optimized with Next.js server components to improve performance and scalability.

### ⚙️ Error Handling
- Comprehensive error management for a seamless user experience.

### ⚡ Caching
- Smart caching strategies implemented to boost application speed.

### 🔧 Next.js Features
- Leveraged features such as file-based routing, API routes, and built-in CSS/SCSS support.

### 🗄️ Database ORM & PostgreSQL
- Integrated with an ORM for smooth interactions with a PostgreSQL database.

## 🛠️ Setup and Installation

### Prerequisites
- Node.js (v14 or higher)
- PostgreSQL

### Installation
1. Clone the repository:
   ```bash
   git clone https://lnkd.in/gczAbbXY
   cd nextjs-dashboard
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure environment variables:
   Create a `.env` file with the following variables:
   ```env
   NEXTAUTH_SECRET = 7c3a68fb196e087ef2ffe9d0947e5251
   POSTGRES_URL_NON_POOLING = postgres://default:9Heb2AmxaCTM@ep-shrill-forest-a4g8duyx.us-east-1.aws.neon.tech/verceldb?sslmode=require
   POSTGRES_URL_NO_SSL = postgres://default:9Heb2AmxaCTM@ep-shrill-forest-a4g8duyx-pooler.us-east-1.aws.neon.tech/verceldb
   POSTGRES_PRISMA_URL = postgres://default:9Heb2AmxaCTM@ep-shrill-forest-a4g8duyx-pooler.us-east-1.aws.neon.tech/verceldb?pgbouncer=true&connect_timeout=15&sslmode=require
   POSTGRES_USER = default
   POSTGRES_PASSWORD = 9Heb2AmxaCTM
   POSTGRES_HOST = ep-shrill-forest-a4g8duyx-pooler.us-east-1.aws.neon.tech
   POSTGRES_DATABASE = verceldb
   POSTGRES_URL = postgres://default:9Heb2AmxaCTM@ep-shrill-forest-a4g8duyx-pooler.us-east-1.aws.neon.tech/verceldb?sslmode=require
   ```
4. Run database migrations:
   ```bash
   npx prisma migrate dev
   ```
5. Start the development server:
   ```bash
   npm run dev
   ```
6. Open your browser and visit:
   ```
   http://localhost:3000
   ```

## 🔗 Credentials for Testing
- **Email**: `user@nextmail.com`
- **Password**: `123456`

## 📚 References
- [Next.js Documentation](https://nextjs.org/)
- [Prisma ORM](https://www.prisma.io/)
