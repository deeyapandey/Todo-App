# Todo App

A full-stack Todo Application built using **React** on the frontend, **Zod** for schema-based form validation, **.NET Web API** for backend logic, and **SQL Server** for persistent data storage.  
Supports full CRUD operations, clean architecture, and strong validation both client-side and server-side.

---

## ✨ Features

### 🔹 Frontend (React)
- Add, edit, delete, and mark todos as completed
- Form validation using **Zod** + **React Hook Form**
- Schema-based validation for clean and maintainable forms
- API service abstraction for backend communication
- Reusable components (TodoItem, TodoForm, ListView, etc.)
- Modern UI (Tailwind)
- State handling using React Hooks

### 🔹 Backend (.NET Web API)
- RESTful API endpoints for CRUD operations
- Entity Framework Core for DB access
- DTO-model separation
- Centralized validation & error handling
- CORS policy for React integration

### 🔹 Database (SQL Server)
- Todo table with fields like:
  - `Id`  
  - `Title`   
  - `IsCompleted`  
  - `CreatedAt`  
- EF Core migrations

---

## 🛠️ Tech Stack

### **Frontend**
- React
- React Hook Form
- **Zod validation**
- Fetch
- Vite
- Tailwind

### **Backend**
- .NET 6/7/8 Web API
- Entity Framework Core
- SQL Server

### **Database**
- SQL Server Express / LocalDB / SQL Server

