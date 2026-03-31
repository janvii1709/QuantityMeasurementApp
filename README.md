# 🚀 Quantity Measurement Application

A robust and scalable **Quantity Measurement System** developed using **Java & Spring Boot**, designed to handle multiple measurement domains including **Length, Weight, Volume, and Temperature**.

The application supports accurate **unit conversion**, **cross-unit comparison**, and **arithmetic operations**, following a **Use Case–driven approach (UC1–UC18)**. It evolves from core **OOP concepts** to a secure, **database-integrated backend system** with **RESTful APIs**.

---

## 👤 Developer
**Janhavi Singh**

---

## 🧠 Use Cases (UC1 – UC18)

### 📏 Core Measurement (UC1 – UC8)
| UC | 📌 Description |
|----|----------------|
| UC1 | Value-based equality for Feet objects using `equals()` and `hashCode()`. |
| UC2 | Equality extended to support both Feet and Inches. |
| UC3 | Cross-unit comparison using base unit conversion. |
| UC4 | Support for multiple length units (Inch, Feet, Yard, CM). |
| UC5 | Unit conversion across length units. |
| UC6 | Addition for quantities of the same unit. |
| UC7 | Addition for different units via base unit conversion. |
| UC8 | Enforced immutability, validation, and proper equality handling. |

### ⚖️ Extended Measurement (UC9 – UC11)
| UC | 📌 Description |
|----|----------------|
| UC9 | Weight measurement (Kg, Gram, Tonne) with conversion. |
| UC10 | Generic Quantity class with Unit interface to support multiple categories. |
| UC11 | Volume measurement (Litre, ML, Gallon) with conversion and operations. |

### ➕ Advanced Operations (UC12 – UC14)
| UC | 📌 Description |
|----|----------------|
| UC12 | Subtraction and division operations for quantities. |
| UC13 | Centralized arithmetic logic following DRY principles. |
| UC14 | Temperature measurement with restricted operations and proper abstractions. |

### 🏗️ Architecture & Backend (UC15 – UC18)
| UC | 📌 Description |
|----|----------------|
| UC15 | N-Tier architecture: Controller → Service → Repository. |
| UC16 | JDBC integration with CRUD operations for database persistence. |
| UC17 | RESTful APIs built using Spring Boot for scalable backend. |
| UC18 | Secure authentication & authorization using Spring Security, JWT & Google OAuth2. |

---

## 🛠️ Tech Stack
- **Java**
- **Spring Boot**
- **Spring Security**
- **JWT Authentication**
- **OAuth2 (Google Login)**
- **JDBC & MySQL**
- **JUnit**
- **Postman**

---

## ✅ Highlights
- Multi-domain measurement support: Length, Weight, Volume, Temperature.  
- Clean, modular, and scalable architecture.  
- Strong adherence to **OOP** and design principles.  
- Secure backend with authentication and authorization.  
- RESTful API integration for seamless frontend communication.

---

## 🔗 GitHub Repository
[Quantity Measurement App](https://github.com/janvii1709/QuantityMeasurementApp)

---

## ✅ Use Case Implementation Summary

- **UC1 – UC2:** Implemented equality checks for Feet and Inches using `equals()` and `hashCode()`.  
- **UC3 – UC5:** Added cross-unit comparison and conversion for multiple length units.  
- **UC6 – UC7:** Supported addition for same and different units while maintaining immutability.  
- **UC8:** Enforced validation, immutability, and proper equality handling.  
- **UC9 – UC11:** Extended support to Weight and Volume with conversions and arithmetic.  
- **UC12 – UC13:** Added subtraction and division operations with centralized arithmetic logic.  
- **UC14:** Temperature measurement with selective arithmetic operations.  
- **UC15 – UC17:** Developed N-Tier architecture, JDBC CRUD operations, and RESTful APIs.  
- **UC18:** Implemented secure authentication with JWT and Google OAuth2.

---

## 🙏 Acknowledgement
Thanks to **BridgeLabz** for structured learning, guidance, and inspiration.
