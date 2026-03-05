# Event Management System

A full-stack **Event Management System** where users can view and register for events and Admin can manage events.  
Built with **Spring Boot + Gradle** for the backend and **React + TypeScript** for the frontend.

---

## Project Structure
```
event-management-system/
  │
  ├── backend/ # Spring Boot  
  ├── frontend/ # React + TypeScript 
```


---

## Technologies Used
### Frontend
- React
- TypeScript
- Tailwind CSS

### Backend
- Java
- Spring Boot
- Spring Security + JWT Authentication
- Spring Data JPA
- PostgreSQL
- Gradle

##  How to run

### 1. Clone the Repository

```bash
git clone https://github.com/Priyansh7999/event-management-system.git
cd event-management-system
```
### 2. Backend Setup

- Configure database in src/main/resources/application.properties

Run the Spring Boot application:
```
./gradlew bootRun
```
Backend server runs at: http://localhost:8080

### 3. Frontend Setup


Install dependencies:
```
npm install
```
Run the development server:
```
npm run dev
```
Frontend runs at: http://localhost:5173
