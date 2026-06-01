# 📚 BookBazaar - Full-Stack E-Commerce Platform

BookBazaar is a full-stack e-commerce web application built using ASP.NET Core MVC and SQL Server. The platform enables users to browse books, manage shopping carts, place orders, and track purchases, while administrators can manage inventory, genres, books, stock levels, and customer orders through a dedicated dashboard.

## 🚀 Features

### Customer Features

- User Registration & Authentication
- Browse Books by Genre
- Search and Filter Books
- Shopping Cart Management
- Secure Checkout Process
- Order History Tracking
- User Profile Management

### Admin Features

- Admin Dashboard
- Book Management (Add, Update, Delete)
- Genre Management
- Inventory & Stock Management
- Order Processing & Status Updates
- Sales Reporting
- Top Selling Books Analytics

## 🛠️ Tech Stack

### Backend

- ASP.NET Core MVC (.NET)
- C#
- Entity Framework Core
- ASP.NET Identity

### Database

- Microsoft SQL Server

### Frontend

- Razor Views
- HTML5
- CSS3
- Bootstrap 5
- JavaScript

### Tools

- Visual Studio
- SQL Server Management Studio
- Git & GitHub

## 🏗️ Architecture

The application follows the MVC (Model-View-Controller) architecture pattern:

- Models: Business entities and database models
- Views: Razor pages for UI rendering
- Controllers: Handle user requests and application logic
- Repository Layer: Encapsulates data access operations
- Entity Framework Core: Database interaction and ORM

## 📋 Core Modules

### Authentication & Authorization

- User Registration
- Login/Logout
- Role-Based Access Control
- ASP.NET Identity Integration

### Product Catalog

- Book Listings
- Genre Filtering
- Product Details

### Shopping Cart

- Add to Cart
- Update Quantity
- Remove Items
- Checkout Process

### Order Management

- Place Orders
- View Order History
- Track Order Status

### Inventory Management

- Stock Monitoring
- Stock Updates
- Product Availability Tracking

### Reporting & Analytics

- Top Selling Books
- Sales Overview
- Order Statistics

## ⚙️ Installation

### Prerequisites

- .NET SDK
- SQL Server
- Visual Studio 2022/2026

### Clone Repository

git clone <https://github.com/Zeny1303/BookBazaar.git>  
cd BookBazaar

### Configure Database

Update the connection string in:

appsettings.json

"ConnectionStrings": {  
"DefaultConnection": "Your_SQL_Server_Connection_String"  
}

### Apply Migrations

dotnet ef database update

### Run Application

dotnet run

Application will start on:

<https://localhost:5001>

## 🔐 Admin Access

Create an admin account through the application or seed initial data through database migrations.

## 📊 Key Functionalities

- Complete E-Commerce Workflow
- Inventory Management System
- Order Lifecycle Management
- Role-Based Authentication
- Admin Analytics Dashboard
- Responsive User Interface

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience with:

- ASP.NET Core MVC
- Entity Framework Core
- SQL Server Database Design
- Authentication & Authorization
- Repository Pattern
- CRUD Operations
- MVC Architecture
- Full-Stack Development
- Database Migrations
- Enterprise Application Design

## 🔮 Future Enhancements

- Payment Gateway Integration (Stripe/Razorpay)
- Product Reviews & Ratings
- Wishlist Functionality
- REST API Integration
- Email Notifications
- Azure Deployment
- Docker Containerization
- Advanced Analytics Dashboard

## 👩‍💻 Developer

**Sneha Kashyap**

- LinkedIn: <https://linkedin.com/in/sneha-kashyap1309>
- GitHub: <https://github.com/Zeny1303>

## ⭐ Support

If you found this project helpful, consider giving it a star on GitHub.
