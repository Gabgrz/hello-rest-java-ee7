# Java EE 7 REST Application

A Maven-based Java EE 7 web application demonstrating REST APIs, JSF frontend, and JPA persistence.

## Features

- **REST API**: JAX-RS endpoints for Person CRUD operations (`/persons`)
- **Web Interface**: JSF 2.2 with CDI backing beans
- **Persistence**: JPA with H2 in-memory database
- **Health Check**: Servlet endpoint at `/health`
- **Architecture**: Stateless EJBs with transaction management

## Endpoints

- `GET /persons` - List all persons
- `GET /persons/{id}` - Get person by ID
- `POST /persons` - Create/update person
- `DELETE /persons/{id}` - Delete person
- `GET /health` - Health check (returns "OK")

## Tech Stack

- Java EE 7 (JAX-RS, JSF, JPA, EJB, CDI)
- Maven WAR packaging
- H2 in-memory database
