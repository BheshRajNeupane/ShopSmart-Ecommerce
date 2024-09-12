# ShopSmart E-commerce Project

Welcome to the **ShopSmart** e-commerce project, an API built with **TypeScript**, utilizing **TypeORM** as the ORM layer. The project features production-ready logging, authentication, authorization, and scalable error handling. It also integrates Swagger for API documentation and follows best practices for code scalability, maintainability, and structure.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)
- [Running the Application](#running-the-application)
- [API Documentation](#api-documentation)
- [Authentication and Authorization](#authentication-and-authorization)
- [Logging](#logging)
- [Error Handling](#error-handling)
- [Validation](#validation)
- [Environment Configuration](#environment-configuration)
- [Contributing](#contributing)

---

## Project Overview

ShopSmart is a scalable and secure e-commerce backend API built using **Node.js**, **TypeScript**, and **TypeORM**. The API supports the complete e-commerce functionality, including product management, order handling, authentication, and authorization. It also has a robust error-handling system and detailed request validation to ensure data integrity.

---

## Features

- **TypeScript** for static typing and code scalability.
- **Swagger** for API documentation and testing.
- **Authentication & Authorization** using **JWT**.
- **TypeORM** for database management with easy entity relations.
- **Winston Logger** for production-level logging and audit trails.
- **Centralized Error Handling** to manage and scale errors across the application.
- **Request Validation** to enforce strict validation rules on all incoming requests.
- Clear separation of concerns across **Config**, **Entities**, **Controllers**, **Middleware**, **Enums**, and more.
- Clean, well-formatted, and scalable codebase.

---

## Technologies Used

- **Node.js** with **Express.js**
- **TypeScript**
- **TypeORM**
- **PostgreSQL** (Can be replaced with other databases using TypeORM)
- **Swagger** (for API documentation)
- **JWT** (for authentication)
- **Winston** (for logging)
- **Express Validator** (for request validation)

---

## Project Structure

```plaintext
├── src
│   ├── config          # Configuration files (e.g., DB connection, environment settings)
│   ├── controllers     # API endpoint controllers
│   ├── entities        # Database entities using TypeORM
│   ├── middleware      # Middleware functions (e.g., authentication, validation)
│   ├── enums           # Enumerations for standard values (e.g., roles, statuses)
|   ├── interface       # Provide interfaces for other module
│   ├── utils           # Utility functions and reusable logic
│   ├── routes          # API routes
│   ├── services        # Business logic and service layers
│   ├── swagger         # Swagger documentation setup
│   └── app.ts          # Application entry point
├── .env                # Environment variables
├── tsconfig.json       # TypeScript configuration
├── ormconfig.json      # TypeORM configuration
├── package.json        # Dependencies and scripts
└── README.md           # Project documentation




```

**The documentation will be updated soon.. -** 

