<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=220&section=header&text=CANNOIL%20E-COMMERCE%20BACKEND&fontSize=44&fontColor=FFD700&fontAlignY=42&desc=⚡%20Node.js%20%2B%20Express%20REST%20API%20%C2%B7%20Prisma%20%C2%B7%20JWT%20Secured&descAlignY=62&descColor=DCDCDC&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&weight=700&size=20&duration=2800&pause=900&color=FFD700&center=true&vCenter=true&width=760&lines=%E2%9A%A1+RESTful+API+for+Product+Management;%F0%9F%94%92+JWT+Authentication+%26+Authorization;%F0%9F%9B%92+Order+Processing+Pipeline;%F0%9F%97%84%EF%B8%8F+Prisma+ORM+%2B+Migrations;%F0%9F%8F%86+%231+GitHub+Committer+in+Colombia)](https://git.io/typing-svg)

<br/>

<p align="center">
  <a href="https://github.com/NietoDeveloper">
    <img src="https://img.shields.io/badge/Engineer-Manuel%20Nieto-blue?style=for-the-badge&logo=github"/>
  </a>
  <a href="https://committers.top/colombia#NietoDeveloper">
    <img src="https://img.shields.io/badge/Committers.top-%231%20Colombia-gold?style=for-the-badge"/>
  </a>
  <a href="https://nodejs.org/">
    <img src="https://img.shields.io/badge/Backend-Node.js-green?style=for-the-badge&logo=node.js"/>
  </a>
  <a href="https://expressjs.com/">
    <img src="https://img.shields.io/badge/Framework-Express.js-lightgrey?style=for-the-badge&logo=express"/>
  </a>
  <a href="https://www.prisma.io/">
    <img src="https://img.shields.io/badge/ORM-Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/NietoDeveloper/Server-CannOil_1.1">
    <img src="https://img.shields.io/badge/📂_Source-NietoDeveloper%2FServer--CannOil__1.1-000000?style=for-the-badge&logo=github&logoColor=FFD700"/>
  </a>
</p>

</div>

---

## 📋 Overview

The backend for **Cannoil E-Commerce** — a model application for an online health products store. Built by **Manuel Nieto**, Software Developer, in 2024. Exposes a RESTful API handling product management, user authentication, and order processing, backed by Prisma-managed database migrations.

---

## 🗂️ Project Structure

```text
Server-CannOil_1.1/
├── migrations/          # Prisma database migrations (users, products, categories, cart/orders, blog)
├── public/
│   └── uploads/          # Uploaded media assets
└── src/
    ├── controllers/       # Business logic handlers
    ├── generated/          # Prisma generated client
    ├── models/             # Data models
    ├── routes/             # RESTful API endpoints
    └── validations/        # Request validation schemas
```

---

## 🔄 API Request Flow

```mermaid
flowchart LR
    A([🌐 Client Request]) --> B[Routes]
    B --> C[Validations]
    C --> D[Controllers]
    D --> E{Resource Type}
    E -->|Users| F[(Prisma\nUsers Table)]
    E -->|Products| G[(Prisma\nProducts Table)]
    E -->|Cart / Orders| H[(Prisma\nOrders Table)]
    D -->|JWT Issued| I([🔑 Authenticated Response])

    style A fill:#FFD700,color:#000,stroke:#FFD700
    style E fill:#0a0a0a,color:#FFD700,stroke:#FFD700
    style I fill:#000,color:#FFD700,stroke:#FFD700
```

---

## 🛠️ Technologies

<div align="center">

| Category | Technologies |
|:---------|:-------------|
| 🏃 **Runtime** | Node.js |
| ⚙️ **Framework** | Express (web framework for API development) |
| 🗄️ **ORM** | Prisma |
| 🔐 **Security** | JWT, Bcrypt |

</div>

---

## ✨ Features

- **RESTful API for Product Management:** Full CRUD endpoints for the product catalog.
- **User Authentication and Authorization:** JWT-based, securing protected routes.
- **Order Processing:** Cart and order lifecycle management.
- **Database Integration:** Prisma ORM with versioned migrations for users, products, categories, cart/orders, and blog entities.

---

## 🚀 Installation

**Step 1 — Clone the repository**

```bash
git clone https://github.com/NietoDeveloper/Server-CannOil_1.1
```

**Step 2 — Navigate to the backend directory**

```bash
cd Cannoil-Ejemplo1/server
```

**Step 3 — Install dependencies**

```bash
npm install
```

**Step 4 — Start the server**

```bash
npm start
```

---

## 📖 Usage

- API runs on `http://localhost:3000`.
- Endpoints for products, users, and orders available.

---

## 🤝 Contributing

Fork the repo and submit a pull request with your changes.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

Created by **Manuel Nieto (NietoDeveloper)**. Reach out via [GitHub](https://github.com/NietoDeveloper).

<div align="center">

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=120&section=footer&animation=fadeIn" width="100%"/>

</div>
