# Visual SQL Builder

![Project Banner](link-to-your-banner.png)  
A powerful and intuitive web application to visually build, edit, and manage SQL queries across multiple database systems. This project is designed to simplify data querying for developers, analysts, and anyone who needs to interact with databases without writing complex SQL by hand.

---

## 🚀 About The Project

Writing complex SQL queries can be a time-consuming and error-prone task. **Visual SQL Builder** aims to solve this by providing a rich, interactive user interface where users can build queries by selecting tables, columns, and conditions visually.

The core idea is to create a friendly mapping layer over existing database schemas, allowing for custom names and descriptions, making the data model understandable for everyone.

This project is built with a modern technology stack, featuring a robust **Node.js API (NestJS)** on the backend and a dynamic **Nuxt.js (Vue 3)** single-page application on the frontend. Both backend and frontend are being developed with **TypeScript** for type safety and scalability.

⚠️ *Note: I am more experienced in .NET technologies and is using this project as a way to learn and deepen knowledge of Node.js, NestJS, and Nuxt.js while building a real application.*

---

### 🗝️ Key Features

* **✨ Visual Query Construction:** An interactive, point-and-click interface to build `SELECT` statements.
* **🗺️ Database Schema Mapping:** Connect to your database and create user-friendly aliases and descriptions for tables and columns.
* **🔗 Cross-Database Support:** Designed to be agnostic, with initial support planned for SQL Server, PostgreSQL, and MySQL.
* **⚡ Real-time SQL Generation:** Instantly see the generated SQL code as you build your query visually.
* **🔧 Comprehensive SELECT Operations:** Support for Columns Selection, Filtering (`WHERE`), Sorting (`ORDER BY`), and table Joins.
* **📱 Responsive UI:** A clean and modern user interface built with Vue 3 and Bootstrap.

---

## 🛠️ Built With

This project is powered by the following technologies:

* **Backend:**
  * [Node.js](https://nodejs.org/en/) / [NestJS](https://nestjs.com/)
  * REST API
  * TypeORM (for schema mapping and database access)
  * Knex.js or Prisma (for optimized query execution)
  * TypeScript

* **Frontend:**
  * [Nuxt.js 3](https://nuxt.com/) / [Vue.js 3](https://vuejs.org/)
  * [Bootstrap 5](https://getbootstrap.com/)
  * TypeScript

* **Architecture:**
  * Clean Architecture Principles

---

## 🛣️ Roadmap

This is an active portfolio project and under development. Here are some planned features:

- [ ] Advanced `JOIN` interface (LEFT, RIGHT, FULL OUTER)
- [ ] Support for `GROUP BY` and aggregate functions
- [ ] Subquery building capabilities
- [ ] In-app query execution and results preview
- [ ] Export generated SQL to a `.sql` file
- [ ] User accounts to save and manage queries

---

## ⚙️ Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Node.js v18+
* A running PostgreSQL 

### Installation

1. Clone the repo:
    ```bash
    git clone https://github.com/wendersondev0/visual-sql-builder.git
    ```
2. Setup Backend:
    ```bash
    cd visual-sql-builder/backend
    npm install
    # (Update `.env` file with your connection string)
    npm run start:dev
    ```
3. Setup Frontend:
    ```bash
    cd visual-sql-builder/frontend
    npm install
    npm run dev
    ```

---

## 📄 License

Distributed under the MIT License. See `LICENSE` file for more information.

---

## 👤 Contact

Wenderson da silva schroder - https://www.linkedin.com/in/wenderson-schroder/ - wendersondasilva3@gmail.com

Project Link: [https://github.com/your-username/visual-sql-builder](https://github.com/your-username/visual-sql-builder)
