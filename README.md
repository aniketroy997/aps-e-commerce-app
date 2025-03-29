# 🛒 APS E-Commerce Web Application

An ASP.NET MVC-based e-commerce web application built using Visual Studio. This project includes core functionality such as product listing, user registration, authentication, shopping cart, and order management.

---

## 📚 Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [How to Clone in Visual Studio](#how-to-clone-in-visual-studio)
- [Screenshots](#screenshots)
- [License](#license)

---

## ✅ Features

- User Registration and Login
- Product Display with Categories
- Shopping Cart Integration
- Checkout & Order Flow
- Admin Panel for Product Management
- Responsive Layout with Bootstrap

---

## 🛠 Technologies Used

- ASP.NET MVC 5
- Entity Framework
- SQL Server
- Razor Views
- Bootstrap & jQuery

---

## 📁 Project Structure

/App_Data - Database storage (localdb) /Controllers - MVC controllers (Product, Account, Cart, etc.) /Models - Entity models and ViewModels /Views - Razor Views grouped by feature /Scripts - JavaScript and jQuery scripts /Content - CSS and static assets /Migrations - Entity Framework Code First Migrations /Web.config - App settings and database connection aps-e-commerce-app.sln - Solution file

yaml
Copy
Edit

---

## ⚙️ Prerequisites

Make sure the following are installed:

- [Visual Studio 2022+](https://visualstudio.microsoft.com/)
- [.NET Framework 4.7.2 or compatible](https://dotnet.microsoft.com/)
- [SQL Server or LocalDB](https://learn.microsoft.com/en-us/sql/database-engine/configure-windows/sql-server-2019-express-localdb)
- [Git](https://git-scm.com/)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/aniketroy997/aps-e-commerce-app.git
Or in Visual Studio:

Go to File > Clone Repository

Paste: https://github.com/aniketroy997/aps-e-commerce-app.git

Click Clone

2. Open the Solution
Open aps-e-commerce-app.sln in Visual Studio.

3. Restore NuGet Packages
Go to Tools > NuGet Package Manager > Package Manager Console and run:

powershell
Copy
Edit
Update-Package -reinstall
4. Set Up the Database
Ensure SQL Server/LocalDB is running.

Update the connection string in Web.config if needed.

Run migrations:

powershell
Copy
Edit
Update-Database
5. Run the Application
Press F5 or click the green Start button in Visual Studio.

🧑‍💻 How to Clone in Visual Studio
Option 1: Clone Existing Repository
Open Visual Studio → File > Clone Repository

Paste this URL: https://github.com/aniketroy997/aps-e-commerce-app.git

Choose a local path and click Clone

Option 2: Publish Local Project to GitHub
Go to View > Git Changes

Click Create Git Repository if not initialized

Click Publish to GitHub

Sign in and select repository name

Click Publish

🖼️ Screenshots
Add screenshots here to showcase:

Home page

Product list

Cart functionality

Admin dashboard

📄 License
This project is licensed under the MIT License.

🤝 Contributing
Contributions and feature suggestions are welcome!
Fork the repo, create a new branch, and submit a pull request.

📬 Contact
Author: Aniket Roy
GitHub: @aniketroy997

