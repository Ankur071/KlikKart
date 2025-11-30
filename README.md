# 🛒 KlikKart

A full-stack e-commerce application built with **Spring Boot** and **React**, designed for managing and browsing products online.

## 📋 Overview

KlikKart is a modern e-commerce platform that provides a complete solution for product management. The application features a RESTful backend API built with Spring Boot and a responsive frontend built with React.

## 🛠️ Tech Stack

### Backend (`ecom-proj`)
- **Java 17+** - Core programming language
- **Spring Boot** - Application framework
- **Spring Data JPA** - Data persistence
- **Maven** - Build and dependency management

### Frontend (`ecom-frontend`)
- **React** - UI library
- **Vite** - Build tool
- **Axios** - HTTP client for API calls
- **React Context API** - State management

## 📁 Project Structure

```
KlikKart/
├── ecom-proj/                    # Backend (Spring Boot)
│   └── src/main/java/com/telusko/ecom_proj/
│       ├── controller/
│       │   └── ProductController.java
│       ├── model/
│       │   └── Product.java
│       ├── repo/
│       │   └── ProductRepo.java
│       ├── service/
│       │   └── ProductService.java
│       └── EcomProjApplication.java
│
├── ecom-frontend/                # Frontend (React)
│   └── src/
│       ├── components/
│       │   ├── AddProduct.jsx
│       │   ├── Home.jsx
│       │   ├── Navbar.jsx
│       │   ├── Product.jsx
│       │   └── UpdateProduct.jsx
│       ├── Context/
│       │   └── Context.jsx
│       ├── App.jsx
│       ├── axois.jsx
│       └── main.jsx
│
└── products Image/               # Product images storage
```

## ✨ Features

- 📦 **Product Management** - Add, update, delete, and view products
- 🖼️ **Image Upload** - Support for product images
- 🔍 **Product Browsing** - Browse and view product details
- 🔄 **Real-time Updates** - Dynamic UI updates with React Context
- 🌐 **RESTful API** - Clean API architecture

## 🚀 Getting Started

### Prerequisites

- Java 17 or higher
- Node.js 18+ and npm
- Maven 3.6+

### Backend Setup

1. **Navigate to backend directory**
   ```bash
   cd ecom-proj
   ```

2. **Build the project**
   ```bash
   ./mvnw clean install
   ```

3. **Run the Spring Boot application**
   ```bash
   ./mvnw spring-boot:run
   ```

4. **Backend runs on**
   ```
   http://localhost:8080
   ```

### Frontend Setup

1. **Navigate to frontend directory**
   ```bash
   cd ecom-frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Frontend runs on**
   ```
   http://localhost:5173
   ```

## 🔌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/api/products` | Get all products |
| `GET` | `/api/product/{id}` | Get product by ID |
| `POST` | `/api/product` | Add new product |
| `PUT` | `/api/product/{id}` | Update product |
| `DELETE` | `/api/product/{id}` | Delete product |

## ⚙️ Configuration

Backend configuration can be modified in:
```
ecom-proj/src/main/resources/application.properties
```

## 🧪 Running Tests

```bash
cd ecom-proj
./mvnw test
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and anyone can use it and make contribution.

## 👨‍💻 Author

**Ankur**

---

*Built with dedication using Spring Boot & React*
