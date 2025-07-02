# Visual SQL Builder

![Project Banner](link-para-seu-banner.png) A powerful and intuitive web application to visually build, edit, and manage SQL queries across multiple database systems. This project is designed to simplify data querying for developers, analysts, and anyone who needs to interact with databases without writing complex SQL by hand.

## 🚀 About The Project

Writing complex SQL queries can be a time-consuming and error-prone task. **Visual SQL Builder** aims to solve this by providing a rich, interactive user interface where users can build queries by selecting tables, columns, and conditions visually.

The core idea is to create a friendly mapping layer over existing database schemas, allowing for custom names and descriptions, making the data model understandable for everyone.

This project is built with a modern technology stack, featuring a robust **ASP.NET Core API** on the backend and a dynamic **Nuxt.js (Vue 3)** single-page application on the frontend.

### Key Features

* **✨ Visual Query Construction:** An interactive, point-and-click interface to build `SELECT` statements.
* **🗺️ Database Schema Mapping:** Connect to your database and create user-friendly aliases and descriptions for tables and columns.
* **🔗 Cross-Database Support:** Designed to be agnostic, with initial support planned for SQL Server, PostgreSQL, and MySQL.
* **⚡ Real-time SQL Generation:** Instantly see the generated SQL code as you build your query visually.
* **🔧 Comprehensive SELECT Operations:** Support for Columns Selection, Filtering (`WHERE`), Sorting (`ORDER BY`), and table Joins.
* **📱 Responsive UI:** A clean and modern user interface built with Vue 3 and Bootstrap.

## 🛠️ Built With

This project is powered by the following technologies:

* **Backend:**
    * [.NET 8](https://dotnet.microsoft.com/en-us/) / ASP.NET Core
    * REST API
    * Entity Framework Core (for schema mapping)
    * Dapper (for optimized query execution)
* **Frontend:**
    * [Nuxt.js 3](https://nuxt.com/) / [Vue.js 3](https://vuejs.org/)
    * [Bootstrap 5](https://getbootstrap.com/)
* **Architecture:**
    * Clean Architecture Principles

## Roadmap

This is an active portfolio project. Here are some of the features planned for the future:

* [ ] Advanced `JOIN` interface (LEFT, RIGHT, FULL OUTER).
* [ ] Support for `GROUP BY` and aggregate functions.
* [ ] Subquery building capabilities.
* [ ] In-app query execution and results preview.
* [ ] Export generated SQL to a `.sql` file.
* [ ] User accounts to save and manage queries.

## ⚙️ Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* .NET 8 SDK
* Node.js v18+
* A running SQL Server / PostgreSQL / MySQL instance.

### Installation

1.  Clone the repo:
    ```sh
    git clone [https://github.com/seu-usuario/visual-sql-builder.git](https://github.com/seu-usuario/visual-sql-builder.git)
    ```
2.  Setup Backend:
    ```sh
    cd visual-sql-builder/backend
    dotnet restore
    # (Update appsettings.json with your connection string)
    dotnet run
    ```
3.  Setup Frontend:
    ```sh
    cd visual-sql-builder/frontend
    npm install
    npm run dev
    ```

## 📄 License

Distributed under the MIT License. See `LICENSE` file for more information.

## 👤 Contact

Seu Nome - [Seu LinkedIn URL] - seu.email@exemplo.com

Project Link: [https://github.com/seu-usuario/visual-sql-builder](https://github.com/seu-usuario/visual-sql-builder)
