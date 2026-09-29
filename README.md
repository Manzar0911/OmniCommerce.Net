# OmniCommerce.Net

<p align="center">
  <h1 align="center">OmniCommerce.Net</h1>
  <p align="center">
    <strong>A Modular, Scalable & High-Performance All-in-One E-Commerce Platform</strong>
    <br />
    Built on <strong>ASP.NET Core 10</strong>, <strong>Entity Framework Core 10</strong>, <strong>Bootstrap</strong>, <strong>Sass</strong>, and <strong>Vue.js</strong>.
  </p>
</p>

---

## 🌟 Overview

**OmniCommerce.Net** is a modern, modular, enterprise-grade e-commerce engine designed for scalability, speed, and seamless extensibility. Featuring a clean domain-driven architecture, it empowers businesses to operate multi-store, multi-currency, and multi-lingual storefronts with an intuitive administrative portal and visual CMS page builder.

---

## ✨ Key Capabilities

### 🛒 Storefront & Catalog Management
- **Multi-Store & Multi-Domain**: Manage multiple independent storefronts from a single management console.
- **Dynamic Catalog**: Support for complex product variants, bundles, downloadable ESD products, tier pricing, customer-group pricing, and custom specifications.
- **Faceted Search**: High-speed layered navigation and search filtering capable of handling extensive product inventories.
- **Modern Responsive Experience**: SEO-optimized, mobile-first storefront themes with smooth micro-interactions.

### ⚙️ Architecture & Modularity
- **Modular Extension System**: Dynamic plug-and-play architecture for payment providers, shipping calculators, and authentication handlers.
- **CMS & Visual Page Builder**: Drag-and-drop block builder and menu designer for creating content pages without touching code.
- **Liquid Templating**: Fully customizable email and communication templates powered by Liquid.
- **Database Agnostic**: Native support for **Microsoft SQL Server**, **PostgreSQL**, **MySQL**, and **SQLite** using FluentMigrator schema migrations.
- **High Performance**: Optimized with multi-level output caching, async pipeline processing, and distributed cache readiness (Redis).

---

## 🛠️ Technology Stack

| Layer | Technology |
|---|---|
| **Backend Framework** | .NET 10 / C# / ASP.NET Core 10 |
| **Data Access & ORM** | Entity Framework Core 10 & FluentMigrator |
| **Frontend & UI** | Bootstrap 5, Modern Sass (Dart Sass), Vue.js, jQuery |
| **Templating** | DotLiquid |
| **Dependency Injection** | Autofac / ASP.NET Core DI |
| **Cross-Platform** | Windows, Linux, macOS & Docker containers |

---

## 🚀 Getting Started

### Prerequisites
- [.NET 10 SDK](https://dotnet.microsoft.com/download)
- Visual Studio 2022+ / JetBrains Rider / VS Code
- Database instance (SQL Server, MySQL, PostgreSQL, or SQLite)

### Installation & Execution

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Manzar0911/OmniCommerce.Net.git
   cd OmniCommerce.Net
   ```

2. **Build the Solution:**
   ```bash
   dotnet build Smartstore.sln -c Debug
   ```

3. **Run the Web Application:**
   ```bash
   dotnet run --project src/Smartstore.Web/Smartstore.Web.csproj
   ```

4. **Complete Setup:**
   Open `http://localhost:5000` in your browser and follow the on-screen setup wizard to configure your database and initial store administrator credentials.

---

## 📁 Solution Structure

```
├── src/
│   ├── Smartstore/              # Core foundational library & utilities
│   ├── Smartstore.Core/         # Domain models, services, catalog, checkout & CMS
│   ├── Smartstore.Web/          # Front-end ASP.NET Core web host & admin portal
│   ├── Smartstore.Web.Common/   # Web infrastructure, theming & Razor components
│   ├── Smartstore.Data/         # Database providers (SqlServer, PostgreSql, MySql, Sqlite)
│   ├── Smartstore.Modules/      # Pluggable feature modules (Payment, Shipping, etc.)
│   └── Smartstore.Build/        # Central MSBuild props & build configurations
└── test/                        # Comprehensive unit and integration test suites
```

---

## 📜 License
Distributed under the GNU General Public License. See `LICENSE` for more information.