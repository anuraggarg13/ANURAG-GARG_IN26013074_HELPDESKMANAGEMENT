# ANURAG-GARG_IN26013074_HELPDESKMANAGEMENT
# HelpDeskManagement

Help Desk Ticket Management System built using ASP.NET Core Web API, ASP.NET Core MVC, Entity Framework Core, SQL Server, xUnit, Moq and GitHub.

## Features
* **RESTful API Backend:** Fully functional Web API utilizing the Repository Pattern for clean database operations.
* **MVC Frontend:** A user-friendly web interface that securely consumes the API via a dedicated Service Layer (`HttpClient`).
* **Interactive Dashboard:** Live tracking of Total, Open, and Closed tickets.
* **Ticket Management:** Complete CRUD capabilities allowing users to raise, edit, view details, filter by status, and delete tickets.
* **Robust Testing:** Isolated unit tests using xUnit and Moq to ensure API reliability without hitting the database.

## Tech Stack
* **Backend:** ASP.NET Core Web API, C#
* **Frontend:** ASP.NET Core MVC, Razor Views, Bootstrap
* **Database:** SQL Server, Entity Framework Core (Code-First Migrations)
* **Testing:** xUnit, Moq
* **Version Control:** Git, GitHub

## Prerequisites
To run this project locally, ensure you have the following installed:
* Visual Studio 2022
* .NET SDK (Version 6.0 or higher)
* SQL Server (LocalDB or Express)

## How to Run Locally
1. **Clone the repository:**
   ```bash
   git clone https://github.com/anuraggarg13/HelpDeskManagement.git
   ```
2. Open the `HelpDeskManagement.sln` solution in Visual Studio.

3. Open the **Package Manager Console** (Tools > NuGet Package Manager), set the Default project to `HelpDesk.Api`, and run:
   ```PowerShell
   Update-Database
   ```
4. Right-click the Solution in Solution Explorer and select **Configure Startup Projects...**

5. Select **Multiple startup projects** and set the Action for both `HelpDesk.Api` and `HelpDesk.Mvc` to Start.

6. Press **F5** to build and run the application!

## 👨‍💻 Author

**ANURAG GARG**
* **GitHub:** [https://github.com/anuraggarg13](https://github.com/anuraggarg13)
* **Project Link:** [https://github.com/anuraggarg13/HelpDeskManagement](https://github.com/anuraggarg13/HelpDeskManagement)
