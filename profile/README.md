# StudentEase
![logolight](https://github.com/user-attachments/assets/be222b69-e9b3-4777-bb4f-73f8310af3b9)

Welcome to the **StudentEase-Team** organization! We are dedicated to developing applications that streamline and enhance the educational experience for students and educators. Below, you'll find an overview of our main projects and their functionalities.

## 🚀 Repositories

### 1. [StudentEase Backend Server](https://github.com/StudentEase-Team/student-ease-backend)
The backend server is a Java Spring application that powers the StudentEase platform. It provides essential services like API endpoints, database connections, user authentication, email notifications, and more.

- **Features:**
  - Database connection with PostgreSQL.
  - JWT-based user authentication.
  - Email notifications via SMTP.
  - REST API for communication with the frontend.
  
- **Prerequisites:**
  - Java 17+
  - Maven
  - IntelliJ IDEA or another IDE

- **Installation:**
  - Clone the repository: `git clone https://github.com/StudentEase-Team/student-ease-backend-server.git`
  - Install dependencies: `mvn install`
  - Set up environment variables in `.env` file.

- **Usage:**
  - Start the server: `mvn spring-boot:run`
  - The application will run on `http://localhost:8080`.

### 2. [StudentEase Frontend App](https://github.com/StudentEase-Team/student-ease-frontend)
This is the mobile frontend application for StudentEase, built with React Native and Expo. It connects with the backend server to provide students with a seamless and user-friendly interface for managing their educational resources.

- **Features:**
  - Cross-platform compatibility (iOS and Android).
  - API integration with the backend.
  - Secure user authentication.
  - Interactive 3D campus map.
  - Unified subject management.
  - Dark theme support.

- **Prerequisites:**
  - Node.js and npm
  - Expo CLI
  - VS Code or another IDE
  - Android Studio or Xcode

- **Installation:**
  - Clone the repository: `git clone https://github.com/StudentEase-Team/student-ease-frontend-app.git`
  - Install dependencies: `npm install`
  - Set up environment variables in `.env` file.

- **Usage:**
  - Run the app: `npx expo run:android`

### 3. [StudentEase Map Server](https://github.com/StudentEase-Team/student-ease-map-server)
The Map Server is a React-based web application that displays 3D objects, providing an interactive way to explore campus facilities. It supports both web and mobile platforms by rendering 3D objects using an iframe for web and a WebView for mobile devices.

- **Features:**
  - Cross-platform 3D object rendering.
  - Responsive design for various screen sizes.
  - Orbital controls for 3D object manipulation.

- **Prerequisites:**
  - Node.js

- **Installation:**
  - Clone the repository: `git clone https://github.com/StudentEase-Team/student-ease-map-server.git`
  - Install dependencies: `npm install`

- **Usage:**
  - Start the development server: `npm start`
  - Access the application on `http://localhost:3000`.
---
