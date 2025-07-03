# DevSecOps Portfolio Project

This project is a simple Node.js (Express) web application created to demonstrate DevSecOps principles using GitHub Actions.

## Security Checks

This project includes a GitHub Actions workflow (`.github/workflows/security.yml`) that runs on every push and pull request to the `main` branch. The workflow performs the following security checks:

- **Linting**: Checks the code for style and quality issues using ESLint.
- **Dependency Scanning**: Uses `npm audit` to check for known vulnerabilities in the project's dependencies.
- **Static Application Security Testing (SAST)**: Uses GitHub's CodeQL to scan the JavaScript code for security vulnerabilities.

## Getting Started

1. Clone the repository.
2. Run `npm install` to install the dependencies.
3. Run `npm start` to start the server.
