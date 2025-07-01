
# 🛒 Ecommerce Full Stack Project

This is a full-stack E-commerce web application built using **Java (Spring Boot)** for the backend and **HTML/CSS/JavaScript** for the frontend. It demonstrates the core functionalities of an online shopping platform, including product listing, user authentication, cart management, and order placement.

---

## 🔧 Tech Stack

### 🖥️ Frontend
- HTML
- CSS
- JavaScript (Vanilla)

### ⚙️ Backend
- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate

### 🗄️ Database
- MySQL / H2 (for development)

### 📦 Build Tool
- Maven

---

## 📁 Project Structure

```

Ecommerce\_fullstack\_project/
│
├── .mvn/              # Maven Wrapper Files
├── src/               # Source Code
│   ├── main/
│   │   ├── java/
│   │   │   └── com/ikjas/ecommerce/  # Java source code
│   │   └── resources/
│   │       ├── static/               # HTML, CSS, JS
│   │       └── application.properties
│   └── test/                         # Unit tests
├── mvnw, mvnw\.cmd                    # Maven Wrapper
├── pom.xml                           # Project Dependencies
└── README.md                         # Project Overview

````

---

## ✅ Features

- 🛍️ Product Listing with Details
- 🔐 User Registration & Login (Spring Security optional)
- 🛒 Add to Cart / Remove from Cart
- 📦 Checkout & Order Placement
- 🧾 Order Summary and History
- ⚙️ Admin Panel : Add/Edit/Delete Products

---

## 🚀 Getting Started

### Prerequisites
- Java 17+
- Maven
- MySQL / H2
- IDE like IntelliJ IDEA or Eclipse

### Steps to Run

1. **Clone the Repository**
```bash
git clone https://github.com/ikjasrasool/Ecommerce_fullsatck_project.git
````

2. **Navigate to the Project Folder**

```bash
cd Ecommerce_fullsatck_project
```

3. **Configure Database**

* Update your `application.properties` file in `src/main/resources/` with your DB credentials.

4. **Build & Run the Project**

```bash
./mvnw spring-boot:run
```

5. **Open in Browser**

```
http://localhost:8080/
```

---

## 📌 To Do / Future Enhancements

* ✅ JWT-based authentication
* ✅ Payment Gateway integration (Razorpay/Stripe)
* ✅ Spring Security for Role-based access
* ✅ React.js frontend (MERN alternative)
* ✅ RESTful APIs for mobile integration

---

## 📸 Screenshots

*Add relevant screenshots here once the UI is ready.*

---

## 🤝 Contributing

Pull requests are welcome! Feel free to open issues for feature requests or bug fixes.

---





