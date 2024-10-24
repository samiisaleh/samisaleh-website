# Personal Website - Sami Saleh

A modern, secure, and professional personal website built with Spring Boot and React.

## Tech Stack

- Backend: Spring Boot (Java 21)
- Frontend: React
- Database: PostgreSQL
- Containerization: Docker
- CI/CD: GitHub Actions
- Hosting: DigitalOcean

## Prerequisites

- Java 21
- Node.js (LTS version)
- Docker Desktop
- Maven
- Git

## Project Structure

```
samisaleh-website/
├── backend/             # Spring Boot application
├── frontend/            # React application
├── docker/             # Docker configurations
└── .github/workflows/  # CI/CD pipeline configurations
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/samisaleh-website.git
   ```

2. Start the database:
   ```bash
   docker-compose up -d db
   ```

3. Run the backend:
   ```bash
   cd backend
   ./mvnw spring-boot:run
   ```

4. Run the frontend:
   ```bash
   cd frontend
   npm install
   npm start
   ```

## Development

- Backend runs on: http://localhost:8080
- Frontend runs on: http://localhost:3000
- Database runs on: localhost:5432

## Security

This project implements:
- JWT-based authentication
- HTTPS encryption
- CORS protection
- Environment-specific configurations
- Security best practices

## Testing

Run tests with:
```bash
# Backend tests
cd backend
./mvnw test

# Frontend tests
cd frontend
npm test
```

## Deployment

The application is automatically deployed to DigitalOcean using GitHub Actions when pushing to the main branch.

## License

MIT