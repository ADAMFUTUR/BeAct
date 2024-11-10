# BeAct Association - Member Registration and Event Management System

This system is designed for the **BeAct Association** to manage members, event registrations, and provide an administrative interface for handling member data and event management. The system allows members to register for events and enables admins to manage member data, event details, and registrations.

## Features

### 1. **Member Registration**
- New members can sign up by providing their personal information, including:
  - Name
  - Email
  - Phone number
  - -age

### 2. **Event Inscription**
- Registered members can view and sign up for upcoming events.
- Members can track their registered events.

### 3. **Admin Dashboard**
- Admin users have an extended interface with permissions to:
  - Create, update, or delete events.
  - Manage member profiles (update, delete, or deactivate accounts).
  - View event registrations and track attendance.

### 4. **Member Profile Management**
- Members have personal profiles displaying their information and a list of events they have registered for.
  
### 5. **Event Management**
- Admins can create and manage events, including:
  - Event name, description, date, location.
  - Event registration deadlines.
  - Deleting events when necessary.

### 6. **Reporting and Tracking**
- Admins can track member registrations for events and generate reports on participation.

---

## Technologies Used

### 1. **Frontend**
- **HTML**: For structuring pages (forms, tables, and user interfaces).
- **CSS**: For custom styling and design.
- **JavaScript**: For interactive elements like form validation and event handling.
- **Bootstrap**: Provides responsive grid layouts and components (forms, buttons, cards).
- **Tailwind CSS**: A utility-first CSS framework used to design custom UI elements.

### 2. **Backend**
- **Java**: For the core application logic and server-side operations.
- **JEE (Java EE)**: Used to build enterprise-level applications with support for web technologies.
- **Servlets**: For handling HTTP requests, routing, and response management.
- **JDBC**: For database interaction between Java and MySQL.

### 3. **Database**
- **MySQL**: Relational database used for storing member details, event data, and event registration information.
- **JDBC**: Java interface to manage database interactions like queries, inserts, updates, and deletions.

### 4. **Authentication**
- Passwords are hashed for security (using Java’s `MessageDigest` or libraries like `Spring Security`).
- Sessions are used for user authentication and maintaining user state.

---

## Setup Instructions

### Prerequisites
- Java 8 or higher
- MySQL server
- Apache Tomcat or any Java EE compatible server
- A modern web browser for accessing the frontend

### 1. **Clone the repository**
```bash
git clone https://github.com/yourusername/beact-association.git
cd beact-association
