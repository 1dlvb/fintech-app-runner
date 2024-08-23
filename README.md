# Microservices Deployment with Docker Compose

This repository contains a Docker Compose configuration for deploying a suite of microservices. The setup includes four microservices and two libraries, each designed to work together seamlessly.

## Microservices

- **Auth Service**: Handles authentication and user management.
  - Repository: [auth-microservice](https://github.com/1dlvb/auth)

- **Contractor Service**: Manages contractor-related operations.
  - Repository: [contractor-microservice](https://github.com/1dlvb/contractor)

- **Deal Service**: Manages deal-related operations.
  - Repository: [deal-microservice](https://github.com/1dlvb/deal)

- **Message Receiver Service**: Receives and processes kafka messages.
  - Repository: [message-receiver-microservice](https://github.com/1dlvb/audit-lib/tree/main/message-receiver)

## Libraries

- **Audit Library**: Provides audit logging and kafka messaging functionality.
  - Repository: [audit-lib](https://github.com/1dlvb/audit-lib)

- **JWT Library**: Provides JSON Web Token (JWT) support.
  - Repository: [jwt-lib](https://github.com/1dlvb/jwt-lib)

### Running the Services

To start the services, use the following command:

- For Ubuntu:
  ```docker compose up```
- For Windows:
```docker-compose up```
  ###
You can also run the services in detached mode by adding the -d flag:

- For Ubuntu:
```docker compose up -d```
- For Windows:
```docker-compose up -d```

### Stopping the Services
To stop the running services, use:

- For Ubuntu:
```docker compose stop```

- For Windows:
```docker-compose stop```
