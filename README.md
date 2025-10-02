# Crudify ⚡


A boilerplate/tool designed to quickly and efficiently generate CRUD (Create, Read, Update, Delete) operations, leveraging the power of Laravel for the back-end and the reactivity of Vue.js with TypeScript for the front-end.

---

## 📋 Table of Contents

- [About The Project](#-about-the-project)
- [🛠️ Tech Stack](#️-tech-stack)
- [🚀 Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [📬 Contact](#-contact)

---

## 📝 About The Project

**Crudify** was born from the need to speed up the development of web applications that rely on many CRUD operations. Instead of rewriting the same repetitive code, this project provides a solid foundation and tools to generate complete modules (models, controllers, migrations, and views/components) with just a few commands.

---

## 🛠️ Tech Stack

This project was built using the following technologies:

- **Back-end:**
  - [PHP](https://www.php.net/)
  - [Laravel](https://laravel.com/)
  - [Composer](https://getcomposer.org/)

- **Front-end:**
  - [Vue.js](https://vuejs.org/)
  - [TypeScript](https://www.typescriptlang.org/)
  - [Vite](https://vitejs.dev/) (or Laravel Mix)
  - [Node.js](https://nodejs.org/)

- **Database:**
  - Compatible with MySQL, PostgreSQL, SQLite, etc.

---


## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have the following software installed on your machine:
- [PHP](https://www.php.net/downloads.php) (Laravel's recommended version)
- [Composer](https://getcomposer.org/download/)
- [Node.js and NPM](https://nodejs.org/en/)
- A database server (e.g., MySQL, MariaDB, PostgreSQL).

### Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/thiagobraga77/crudify.git && cd crudify

2. **Install PHP dependencies**
   ```sh
   composer install

3. **Install Node.js dependencies**
   ```sh
   npm install
4.  **Set up the environment**
    * Copy the example environment file:
        ```sh
        cp .env.example .env
        ```
    * Generate the application key:
        ```sh
        php artisan key:generate
        ```
    * Configure your database variables (`DB_HOST`, `DB_DATABASE`, `DB_USERNAME`, `DB_PASSWORD`) in the `.env` file.

5.  **Run the Migrations**
    ```sh
    php artisan migrate
    ```
    *Optional: Run the seeders to populate the database with sample data:*
    ```sh
    php artisan db:seed
    ```

6.  **Compile the front-end assets**
    * For development environment (with hot-reloading):
      ```sh
      npm run dev
      ```
    * For production environment:
      ```sh
      npm run build
      ```

7.  **Start the development server**
    ```sh
    php artisan serve
    ```

You can now access the project at `http://localhost:8000`.


## 📬 Contact

Thiago Braga - [Linkedin(https://www.linkedin.com/in/thiago-braga-433a43358/)

Project Link: [https://github.com/thiagobraga77/crudify](https://github.com/thiagobraga77/crudify)
