# ebay-Online-Bidding-System

I developed the ebay-Online Bidding System under the Full Stack Development domain. The project required comprehensive expertise in both frontend (React JS) and backend (Spring Boot) technologies, aligning perfectly with the department's focus areas. It provided extensive practical exposure to complex database design with multi-entity relationships, RESTful API development, wallet management, third-party integration for delivery, real-time Bidding management systems, role-based access control, and modern responsive UI design principles. The project's multi-stakeholder architecture (Admin, Seller, Customer) and real-world features like wallet systems, notifications, and Bidding lifecycle management demonstrate advanced full-stack development capabilities essential for enterprise-level applications.

# Online Bidding System 

This project outlines the architecture of an "Online Bidding System" designed with a modular and scalable approach. The system is divided into three main layers:

## 🔧 Architectural Layers

### 1. "Frontend (React)"
The frontend serves as the user interface, providing intuitive access to all system functionalities.

- User Login & Registration
- Product Listing & Bidding Interface
- Seller/Product Management Dashboard
- File Upload Interface for Products

Communication: Sends HTTP requests to the backend via REST APIs.

---

### 2. "Backend (Spring Boot)"
The backend handles all business logic, security, and database operations.

- Authentication and Authorization
- Product and Bid Management
- File Upload Handling
- REST API Layer for frontend integration

Communication: Interacts with the MySQL database using JPA/Hibernate and serves API responses to the frontend.

---

### 3. "Database (MySQL)"
The relational database stores all persistent application data.

- `Users` Table: Stores user-profiles and credentials
- `Products` Table: Contains product details listed for bidding
- `Bids` Table: Tracks all bids placed by users
- `Files` Table: Metadata for product-related uploads

---

## 🔁 Data Flow

1. User Interaction: Users interact with the React UI.
2. API Requests: The frontend communicates with the backend via REST APIs.
3. Business Logic Execution: The Spring Boot backend processes requests, enforces rules and performs operations.
4. Data Persistence: Backend queries the MySQL database to read/write persistent data.

---

## 📊 Architecture Diagram

Below is a high-level representation of the system architecture:
![Architecture](https://github.com/user-attachments/assets/87ec7b6b-43c8-4f9a-9b25-421972dfac61)

---

## 📁 Folder Structure (Conceptual)

- `frontend/` — Contains all React components and UI logic
- `backend/` — Contains Spring Boot code, APIs, services, and models

---

## ✅ Highlights

- Clean separation of concerns
- Scalable and maintainable architecture
- Uses RESTful principles
- Supports file uploads and bidding functionality


