
# 🖥️ Full-Stack Web Application with MongoDB & Automated Testing

## 📌 Overview
This project is a **full-stack web application** built with **ASP.NET Core** and **MongoDB**, designed for managing courses, lessons, and users (students, instructors, and admins).  
It follows a clean architecture with **Controllers, Models, DTOs, and Repository patterns**, and integrates **automated end-to-end testing** using Cypress.

---

## 🚀 Features
- **User Management**: Register, login, and manage user roles (student/instructor/admin).  
- **Course Management**: Create, update, subscribe, and manage courses and lessons.  
- **RESTful APIs**: Backend implemented with ASP.NET Core and MongoDB.  
- **Frontend Integration**: React-based frontend connected with backend services.  
- **Testing**: Cypress automated tests for ensuring application reliability.  
- **Environment Configurations**: Supports `Development` and `Production` using `appsettings.json`.

---

## 🛠️ Tech Stack
- **Backend**: ASP.NET Core (.NET 6)  
- **Frontend**: React (TypeScript)  
- **Database**: MongoDB  
- **Testing**: Cypress  
- **Other Tools**: Git, VS Code, Postman  

---

## 📂 Project Structure
```
├── Controllers/         # REST API controllers
├── Models/              # Database models
├── Dto/                 # Data Transfer Objects
├── MongoDB/             # MongoDB integration and context
├── Program.cs           # Application entry point
├── appsettings.json     # Environment configuration
└── cypress/             # Cypress end-to-end tests
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Backend Setup (ASP.NET Core)
```bash
dotnet restore
dotnet build
dotnet run
```

### 3️⃣ Frontend Setup (React)
```bash
cd frontend
npm install
npm start
```

### 4️⃣ Run Tests (Cypress)
```bash
npx cypress open
```
## 👤 Author
- **Abdelrahaman Ehab**  
  - [LinkedIn](https://www.linkedin.com/in/abdelrahaman-ehab-58405b36a)  
  - [GitHub](https://github.com/Abood660)  

---

## 📜 License
This project is licensed under the **MIT License**.
