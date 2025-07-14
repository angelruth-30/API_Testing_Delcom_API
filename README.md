# 🔍 API Testing Collection — Auth, Todo, and Auction System

This repository contains a Postman collection used to test various REST API endpoints related to:
- **Authentication**
- **User Profile**
- **Todo Management**
- **Auction System**

Test cases include both **positive and negative scenarios**, ensuring the reliability of backend behavior under different conditions.

---

## 📁 Collection File
- `api-testing-auth-todo-auction.postman_collection.json`

---

## ✅ Tested API Endpoints

### 🔐 Authentication
- `POST` Register
- `POST` Login

### 👤 User & Profile
- `GET` Get All Users
- `GET` Get User by ID
- `GET` Get Profile
- `PUT` Update Profile
- `POST` Change Photo Profile
- `PUT` Change Password

---

### 📝 Todo System
- `POST` Add New Todo
- `POST` Change Cover Todo
- `PUT` Update Todo
- `GET` Get All Todos
- `GET` Detail Todo
- `DELETE` Delete Todo

---

### 🏷️ Auction System
- `POST` Add New Auction – Positive
- `POST` Add New Auction – Negative
- `POST` Change Cover Auction – Positive
- `POST` Change Cover Auction – Negative
- `PUT` Update Auction – Positive
- `PUT` Update Auction – Negative
- `GET` Get All Auction
- `DELETE` Delete Auction

---

## 🧪 Tools Used
- [Postman](https://www.postman.com/) — for writing and running API tests.
- Chai Assertion Library — used in `pm.test()` for validating responses.

---

## 💡 Features
- ✅ **Positive and negative tests** to validate both expected and edge case responses.
- 📸 File upload testing using `multipart/form-data`.
- 🔐 Authorization with Bearer Token in headers.
- ⌛ Timestamp field validation for auction closing time.
- 🎯 Assertions on JSON response structure and value.

---

## 📌 Author
Ruth Angel  
QA Tester & Web Developer
