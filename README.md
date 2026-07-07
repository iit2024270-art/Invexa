# 🚀 InveXa - Smart Inventory Management System

## Overview

InveXa is a full-stack inventory management system that helps businesses efficiently manage inventory, suppliers, purchase orders, sales orders, and demand insights from a centralized platform.

The application provides an intuitive dashboard for monitoring stock levels, managing products, tracking suppliers, and analyzing inventory trends. It combines a modern React frontend with an Express backend and PostgreSQL database to deliver a complete inventory management solution.

---

## Features

* Inventory dashboard with real-time stock overview
* Product management
* Purchase order management
* Sales order management
* Supplier management
* AI-enabled demand insights
* Stock movement tracking
* Reorder alerts
* Secure authentication
* REST API with Swagger documentation
* PostgreSQL database using Prisma ORM

---

## Tech Stack

### Frontend

* React 19
* TypeScript
* Vite
* Tailwind CSS
* React Router

### Backend

* Node.js
* Express.js
* Prisma ORM
* JWT Authentication
* Swagger UI

### Database

* PostgreSQL

---

## Project Structure

```text
Invexa/
├── backend/
├── public/
├── src/
├── README.md
├── package.json
└── vite.config.ts
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/iit2024270-art/Invexa.git

cd Invexa
```

---

## Frontend Setup

```bash
npm install

npm run dev
```

The frontend runs at:

```
http://localhost:5173
```

---

## Backend Setup

```bash
cd backend

npm install

cp .env.example .env

docker compose up -d

npm run prisma:generate

npm run prisma:migrate -- --name init

npm run prisma:seed

npm run dev
```

The backend runs at:

```
http://localhost:4000
```

---

## Demo Login

**Email**

```
admin@example.com
```

**Password**

```
ChangeMe123!
```

---

## API Documentation

Swagger UI

```
http://localhost:4000/api/docs
```

OpenAPI JSON

```
http://localhost:4000/api/openapi.json
```

Health Check

```
http://localhost:4000/api/health
```

---

## Available Scripts

### Frontend

```bash
npm run dev
npm run build
npm run preview
npm run lint
```

### Backend

```bash
npm run dev
npm run build
npm run lint
npm run test
npm run test:unit
npm run test:integration
npm run prisma:generate
npm run prisma:migrate
npm run prisma:seed
```

---

## Application Modules

* Dashboard
* Inventory
* Products
* Orders
* Suppliers
* Demand Insights
* Reports
* Calendar
* Settings
* User Profile
* Authentication

---

## Future Improvements

* Barcode and QR code scanning
* Multi-warehouse management
* Email notifications
* Advanced analytics and reporting
* Export reports to PDF and Excel
* Role-based access control
* Mobile responsive enhancements

---

## License

This project is licensed under the MIT License.
