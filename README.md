# ASP.NET-MVC-Employee-Management-System
This is a web-based Employee Management System built with ASP.NET MVC that allows users to manage employees and departments securely using authentication and authorization mechanisms. The system supports role-based access and provides basic CRUD operations for employee and department data.

🔧 Technologies Used
⚙️ ASP.NET MVC (.NET Framework or .NET Core)

🗃️ Entity Framework (Code First / Database First)

🔐 ASP.NET Identity (for user login and roles)

💻 Razor Views

🧩 SQL Server (LocalDB or full SQL)

📌 Core Features
👥 Authentication & Authorization
User registration and login system

Role-based access (e.g., Admin, HR, User)

Authorized users only can access certain features

👤 Employee Module
Create, Read, Update, Delete (CRUD) Employees

Assign employees to departments

Search and filter employees

🏬 Department Module
Manage departments (Add, Edit, Delete)

View all employees in a department

📁 Project Structure
Models: Employee, Department, ApplicationUser

Controllers: AccountController, EmployeeController, DepartmentController

Views: Strongly-typed Razor views for clean UI

Database: Managed with Entity Framework (Code First or Database First)

🚀 How to Run the Project
Clone the repository

Open in Visual Studio

Configure the connection string in appsettings.json or Web.config

Run EF Migrations (if Code First) or update database

Run the application (F5)

📈 Future Enhancements
Employee performance evaluation module

Department hierarchy visualization

Pagination and advanced filtering

Email notifications
