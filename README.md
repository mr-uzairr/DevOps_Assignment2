# DevOps Assignment Project

## Setup Instructions

1. Clone this repository.
2. Navigate to the project folder and run:
   ```sh
   docker-compose up --build
   ```
3. The backend will be available at `http://localhost:5000`.
4. The frontend will be available at `http://localhost:3000`.

## Docker Optimizations
- Used minimal Alpine-based Node.js images for both frontend and backend.
- Multi-stage builds could be added for production environments.
- Non-root users can be implemented for better security.

## CI/CD Pipeline
- GitHub Actions will be used to build, lint, and deploy containers.
- Security measures will be implemented in GitHub Secrets.

