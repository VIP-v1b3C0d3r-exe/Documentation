# Architecture

```
┌─────────────┐     ┌─────────────┐  Http endpoints   ┌─────────────┐
│   Browser   │────>│   Frontend  │──────────────────>│   Backend   │
└─────────────┘     └─────────────┘                   └──────┬──────┘
                                                             │
                                                             v
                                                      ┌─────────────┐
                                                      │  DataBase   │
                                                      └─────────────┘
```

Disclaimer: Complete technical documentation and implementation details are available in the project repositories.

## Component description

### 1. Browser (Client)
Role: User interface, sending requests to the frontend.
Responsibilities: Rendering the UI, handling events, storing local state (localStorage, cookies).
Technologies: Any modern browser (Chrome, Firefox, Edge).

### 2. Frontend
Role: Visualization and business logic on the client side, interaction with the API.
Tasks:
UI pages and components
Working with state 
HTTP API calls to the backend
Authentication and routing

### 3. Backend
Role: Request processing, business logic, data access.
Tasks:
REST API endpoints
Authorization and authentication
Database interaction via ORM
Logging, error handling

### 4. Database
Role: Storing application data.
Tasks: Tables/collections for users, application entities, logs, and metadata.
Repository: Typically, migrations/schemas and data seed scripts.

### 5. Docker / Deployment
Role: Isolation and containerization of components, facilitating deployment.
Tasks:
- Containers for the backend, databases, and optionally the frontend
- Docker Compose for local development
- Support for CI/CD processes

## Component Interaction
- Browser → Frontend
  - The user performs an action (click, form submission).
  - The frontend calls the API using fetch or axios.
- Frontend → Backend
  - HTTP requests (GET, POST, PUT, DELETE).
  - The backend returns a JSON/HTTP response.
  - The frontend updates the UI based on the response.
- Backend → Database
  - The backend executes database queries via the Repository.
  - Hibernate/ORM automatically maps Java objects to tables/documents.
