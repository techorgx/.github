# E-commerce Application [Name TBD]

This repository contains a microservices-based e-commerce application for buying and selling used items. The application is designed to provide a platform for users to browse, list, and chat about items they want to buy or sell.

## Table of Contents

- [Features](#features)
- [Architecture](#architecture)
- [Technologies](#technologies)
- [Services](#services)
- [Setup](#setup)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Authentication](#authentication)
- [Contributing](#contributing)
- [License](#license)

## Features

- User registration and authentication using JWT tokens.
- Customer management.
- Advertisement listing and search.
- Real-time chat between users.
- Frontend and backend orchestration services.

## Architecture

The application follows a microservices architecture, with the following components:

- **Identity Service:** Handles user registration and authentication.
- **Customer Service:** Manages customer profiles.
- **Ads Service:** Manages advertisement listings and searches.
- **Chat Service:** Provides real-time chat functionality.
- **Search Service:** Provides Ads searching functionality.
- **Frontend Service:** The user interface for the application.
- **Backend Orchestrator Service:** Orchestrates communication between the services.

## Technologies

- Java and Kotlin
- Spring Boot for REST APIs and gRPC services
- JWT for user authentication
- AWS DynamoDB for the database

## Services

- **Identity Service:** [Link to Identity Service README](./identity-service/README.md)
- **Customer Service:** [Link to Customer Service README](./customer-service/README.md)
- **Ads Service:** [Link to Ads Service README](./ads-service/README.md)
- **Chat Service:** [Link to Chat Service README](./chat-service/README.md)
- **Search Service:** [Link to Chat Service README](./seach-service/README.md)
- **Frontend Service:** [Link to Frontend Service README](./frontend-service/README.md)
- **Backend Orchestrator Service:** [Link to Orchestrator Service README](./backend-orchestrator-service/README.md)

## Setup

Please follow the individual READMEs for each service to set up and run the microservices.

## Usage

- Start each service using the provided instructions.
- Access the frontend service for the user interface.
- Explore the API documentation for REST and gRPC endpoints.

## API Documentation

- [Link to API Documentation](./api-documentation.md)

## Authentication

- JWT tokens are used for user authentication.
- Make requests with a valid JWT token in the `Authorization` header.

## Contributing

If you'd like to contribute to this project, please follow our [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License. - see the [LICENSE](LICENSE) file for details.

---

For detailed information about each service and how to set up and use them, please refer to the individual service READMEs.

Happy coding!

