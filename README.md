# Smart Rental Room System with AI

## 1. Introduction

Smart Rental Room System with AI is a web-based platform that connects tenants and landlords through an intelligent room searching and rental management system.

The system allows tenants to search for rooms based on:
- Location
- Price
- Area
- Amenities
- Rental conditions

In addition, the platform integrates an AI chatbot that helps users find suitable rooms using natural language.

Example:
“I need a room under 4 million VND near the university.”


The AI system will analyze the request and recommend suitable rooms automatically.

The project also supports:
- Online deposit payment
- Room management
- Rental request management
- Admin moderation system
- AI room recommendation

---

# 2. Research-Based Learning (RBL)

## Main Research Focus

This project applies the Research-Based Learning (RBL) approach focusing on:

### 2.1 System Architecture Research
Research and design of a scalable full-stack web application architecture including:
- Frontend architecture using ReactJS
- Backend RESTful API using NodeJS and ExpressJS
- SQL Server relational database design
- AI service integration
- Payment gateway integration

---

### 2.2 Database Design & Optimization
Research on:
- Database normalization (3NF)
- Relational database design
- Index optimization
- Foreign key constraints
- Soft delete strategy
- Audit tracking
- Denormalization for performance optimization

The system database is designed to handle:
- User management
- Room management
- Booking transactions
- Online payment
- AI chatbot conversation history

---

### 2.3 AI Chatbot Integration
Research on integrating OpenAI API into a rental room platform.

The AI chatbot supports:
- Natural language processing
- Room recommendation
- Smart searching
- User interaction enhancement

Example:
“Find me a room under 5 million near FPT University.”


The AI system analyzes:
- Budget
- Location
- User preferences
- Room conditions

Then returns recommended rooms.

---

### 2.4 Payment Gateway Integration
Research on VNPay Sandbox integration:
- Online deposit payment
- Payment verification
- Transaction callback handling
- Payment history management

---

### 2.5 UI/UX Research
Research on:
- Responsive web design
- User experience optimization
- Dashboard system design
- Search and filtering UX
- AI chatbot interaction UI

---

# 3. Technologies Used

## Frontend
- ReactJS
- TailwindCSS
- Axios
- React Router

---

## Backend
- NodeJS
- ExpressJS
- JWT Authentication

---

## Database
- SQL Server

---

## AI
- OpenAI API

---

## Payment
- VNPay Sandbox

---

## Tools
- GitHub
- Figma
- Postman
- PlantUML
- Visual Studio Code

---

# 4. Main Features

## Tenant Features
- Register/Login
- Search rooms
- Filter rooms
- View room details
- Save favorite rooms
- Send rental requests
- Online deposit payment
- AI chatbot support

---

## Landlord Features
- Create room posts
- Manage rooms
- Upload room images
- Manage rental requests
- Track deposit status

---

## Admin Features
- User management
- Room moderation
- Remove violating posts
- System analytics

---

# 5. System Architecture

```text
Frontend (ReactJS)
        ↓
Backend API (NodeJS + ExpressJS)
        ↓
SQL Server Database
        ↓
External Services
 ├── OpenAI API
 └── VNPay Sandbox