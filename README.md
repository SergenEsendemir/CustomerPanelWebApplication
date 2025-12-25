# Customer Panel Web Application

![ASP.NET MVC](https://img.shields.io/badge/ASP.NET-MVC-blue)
![CSharp](https://img.shields.io/badge/C%23-.NET-green)
![Platform](https://img.shields.io/badge/Platform-Web-lightgrey)
![Status](https://img.shields.io/badge/Status-Demo%20Project-orange)
![License](https://img.shields.io/badge/License-Not%20Specified-red)

A simple **Customer Panel Web Application** developed with **ASP.NET MVC**.  
This project demonstrates a basic customer management panel including authentication, dashboard views, and CRUD-style operations.

---

## 🧠 Overview

This application is designed to demonstrate:

- A web-based **customer panel**
- Basic **login & authentication** flow
- Customer-focused dashboard pages
- MVC architecture usage
- Clean separation of UI and backend logic

The project is suitable for **learning**, **demo**, and **internal tool** scenarios.

---

## ✨ Features

- User authentication (login/logout)
- Customer dashboard
- Basic data listing and management
- MVC-based page navigation
- Simple and clean UI

---

## 🧰 Tech Stack

- **ASP.NET MVC (.NET Framework)**
- **C#**
- **HTML / CSS / JavaScript**
- **Entity Framework** (optional)
- **SQL Server** (LocalDB or full)

---

## 📂 Project Structure

```text
MusteriPaneliUygulamasiWeb/
├── Controllers/          # MVC Controllers
├── Models/               # ViewModels & domain models
├── Views/                # Razor Views (.cshtml)
│   ├── Shared/           # Layouts & shared views
│   └── Home/             # Page-specific views
├── Content/              # CSS files
├── Scripts/              # JavaScript files
├── App_Start/            # Route & filter configurations
├── Properties/           # Assembly info
├── Web.config            # Application configuration
├── Global.asax            # Application startup
└── README.md
```

> This structure follows the **classic ASP.NET MVC (.NET Framework)** project layout.

---

## 📌 Prerequisites

To run this project locally, make sure you have:

- Visual Studio 2019 or later
- ASP.NET Web Development workload installed
- .NET Framework compatible with the project
- SQL Server (LocalDB or full version)

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/SergenEsendemir/MusteriPaneliUygulamasiWeb.git
```

### 2. Open the solution
- Open the `.sln` file in Visual Studio

### 3. Configure Database (if used)
- Update the connection string in `Web.config`
- Apply migrations or ensure tables exist

### 4. Run
- Press **F5** or click **Start Debugging**

---

## 🎯 Purpose

This project was created to:

- Practice ASP.NET MVC development
- Demonstrate a customer panel concept
- Serve as a base for larger enterprise dashboards

It is intended as a **learning and demonstration project**, not a production-ready system.

---

## 🤝 Contributing

Contributions are welcome:

- UI improvements
- Validation & error handling
- Feature extensions
- Code refactoring

---

## 👤 Author

**Sergen Esendemir**  
GitHub: https://github.com/SergenEsendemir

---

## 📄 License

No license is currently specified.  
You may add one if required (e.g., MIT License).
