# Event Registration System

A full-stack web application for managing event registrations, built with Spring Boot backend and Vue.js frontend.

## Project Structure

- **EventRegistration-Backend/** - Spring Boot REST API server
- **EventRegistration-Frontend/** - Vue.js web application

## Features

- Event management (create, view, update events)
- User registration for events
- RESTful API for frontend-backend communication
- Responsive web interface

## Prerequisites

- Java 11 or higher
- Node.js and npm
- Maven or Gradle

## Getting Started

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd EventRegistration-Backend
   ```

2. Run the Spring Boot application:
   ```bash
   ./mvnw spring-boot:run
   ```
   
   Or using Gradle:
   ```bash
   ./gradlew bootRun
   ```

The backend server will start on `http://localhost:8080`

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd EventRegistration-Frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

The frontend application will start on `http://localhost:8081`

## Testing

### Backend Tests
```bash
cd EventRegistration-Backend
./mvnw test
```

### Frontend Tests
```bash
cd EventRegistration-Frontend
npm run test
```

## API Endpoints

The backend provides REST endpoints for:
- `/events` - Event management
- `/persons` - User management  
- `/registrations` - Registration management

## Built With

- **Backend**: Spring Boot, Spring Data REST, Maven/Gradle
- **Frontend**: Vue.js 2.x, Vue Router, Bootstrap Vue, Axios
- **Testing**: JUnit (Backend), Karma + Mocha (Frontend)
