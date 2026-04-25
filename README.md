# Zero Trust Access Control System

TrustSphere - Zero Trust Access Control System is a secure web application designed to implement the principles of Zero Trust security architecture. The system verifies and authenticates every user and request before granting access to protected resources, helping improve security and reducing unauthorized access risks.

This project focuses on secure authentication, role-based access management, protected APIs, and continuous verification using modern web technologies.

---

## Features

- Secure user authentication
- Role-based access control
- Protected routes and APIs
- Session management
- Access verification system
- Environment variable management using dotenv
- Responsive user interface
- Scalable frontend and backend architecture

---

## Tech Stack

### Frontend
- Angular
- TypeScript
- HTML
- CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Authentication & Security
- JWT Authentication
- Password Hashing
- Middleware-based Authorization
- dotenv for environment variable management

---

## Project Structure

```bash
frontend/
backend/
README.md
```

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/ZeroTrustAccessControlSystem.git
```

### Navigate to the project folder

```bash
cd ZeroTrustAccessControlSystem
```

---

## Frontend Setup

```bash
cd frontend
npm install
ng serve
```

The frontend will run on:

```bash
http://localhost:4200
```

---

## Backend Setup

```bash
cd backend
npm install
npm start
```

The backend server will run on:

```bash
http://localhost:5000
```

---

## Environment Variables

Create a `.env` file inside the backend directory and add:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

dotenv is used to securely manage environment variables and sensitive credentials.

---

## Screenshots

### Login Page
<img width="438" height="277" alt="image" src="https://github.com/user-attachments/assets/5440b32c-f041-4b75-9845-2083d3b5eaca" />

### Dashboard
<img width="491" height="273" alt="image" src="https://github.com/user-attachments/assets/3a49dac9-0107-442d-8e61-ffe8dff99fc3" />

### Access Control Interface
<img width="434" height="265" alt="image" src="https://github.com/user-attachments/assets/e0e7101f-0eff-4f81-bcd7-764fef2dba74" />

### User Management Section
<img width="480" height="264" alt="image" src="https://github.com/user-attachments/assets/e8dcff0e-2429-4152-a6b0-a1794589f639" />

---

## Future Improvements

- Multi-factor authentication
- Device-based verification
- Activity monitoring and logging
- AI-based threat detection
- OAuth integration
- Real-time security alerts

---

## Learning Outcomes

This project helped in understanding:
- Zero Trust security principles
- Authentication and authorization
- Secure API development
- JWT-based session handling
- Angular frontend development
- Backend integration with MongoDB
- Environment variable management using dotenv

---

## Deployment

The project can be deployed using:
- Vercel
- Render
- Railway

---

## License

This project is created for learning and educational purposes.
