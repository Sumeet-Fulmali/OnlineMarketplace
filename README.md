#  OnlineMarketplace

A Spring Boot REST API application for an online marketplace that enables users to browse products, manage categories, place orders, and securely manage customer information. The project follows a layered architecture and demonstrates RESTful API development using Spring Boot, Spring Data JPA, Hibernate, and MySQL.

---

#  Features

- User Registration & Login
- Product Management
- Category Management
- Customer Management
- Shopping Cart
- Order Management
- Inventory Management
- Search Products
- Exception Handling
- Input Validation
- RESTful APIs
- MySQL Database Integration

---

#  Technologies Used

- Java 17
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- Lombok
- REST APIs
- Postman
- Git & GitHub

---

#  Project Structure

```
OnlineMarketplace
│
├── controller
├── service
├── repository
├── entity
├── dto
├── exception
├── configuration
├── util
└── resources
```

---

#  API Endpoints

## User APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /users/register | Register User |
| POST | /users/login | Login User |
| GET | /users | Get All Users |
| GET | /users/{id} | Get User By ID |
| PUT | /users/{id} | Update User |
| DELETE | /users/{id} | Delete User |

---

## Product APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /products | Add Product |
| GET | /products | Get All Products |
| GET | /products/{id} | Get Product By ID |
| PUT | /products/{id} | Update Product |
| DELETE | /products/{id} | Delete Product |

---

## Category APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /categories | Add Category |
| GET | /categories | Get All Categories |
| PUT | /categories/{id} | Update Category |
| DELETE | /categories/{id} | Delete Category |

---

## Cart APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /cart/add | Add Product to Cart |
| GET | /cart | View Cart |
| DELETE | /cart/remove/{id} | Remove Product from Cart |

---

## Order APIs

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /orders | Place Order |
| GET | /orders | Get All Orders |
| GET | /orders/{id} | Get Order By ID |
| PUT | /orders/{id} | Update Order Status |
| DELETE | /orders/{id} | Cancel Order |

---

# 💾 Database Configuration

Configure the database in `application.properties`.

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/onlinemarketplace
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true
```

---

#  Running the Project

## Clone Repository

```bash
git clone https://github.com/your-username/OnlineMarketplace.git
```

## Navigate to Project

```bash
cd OnlineMarketplace
```

## Build the Project

```bash
mvn clean install
```

## Run the Application

```bash
mvn spring-boot:run
```

Application runs at:

```
http://localhost:8080
```

---

# 🧪 Testing APIs

You can test the REST APIs using:

- Postman
- Swagger UI (if configured)

Example:

```
GET http://localhost:8080/products
```

---

# 📁 Sample Product JSON

```json
{
  "name": "Wireless Mouse",
  "description": "Ergonomic wireless mouse",
  "category": "Electronics",
  "price": 799,
  "stock": 50
}
```

---

# 📈 Future Enhancements

- Spring Security with JWT Authentication
- Role-Based Access Control (Admin, Seller, Customer)
- Payment Gateway Integration
- Email Notifications
- Wishlist Management
- Product Reviews & Ratings
- Order Tracking
- Docker Support
- Kafka for Order Processing
- Redis Caching
- Elasticsearch for Product Search
- AWS Deployment
- CI/CD using Jenkins and GitHub Actions

---

# 📸 Project Workflow

```
Customer
    │
    ▼
Browse Products
    │
    ▼
Add to Cart
    │
    ▼
Checkout
    │
    ▼
Place Order
    │
    ▼
Payment
    │
    ▼
Order Confirmation
```

---

# 📚 Learning Objectives

This project demonstrates:

- RESTful API Development
- Spring Boot Architecture
- CRUD Operations
- Layered Architecture
- Spring Data JPA & Hibernate
- Entity Relationships
- Exception Handling
- Bean Validation
- MySQL Integration
- Clean Code Practices

---

#  Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push your branch
5. Create a Pull Request

---

#  Author

**Sumeet Fulmali**

Java Backend Developer

### Skills

- Java
- Spring Boot
- Spring MVC
- Hibernate
- Spring Data JPA
- REST APIs
- MySQL
- Microservices
- Maven
- Git
- Docker

---

#  Support

If you found this project useful, please consider giving it a **Star ⭐** on GitHub.

---

# 📄 License

This project is licensed under the **MIT License**.
