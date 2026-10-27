# PulseBoard

A project management application for organizing projects and tracking tasks.

The goal is to build a working full-stack application while practicing frontend architecture, REST API design, database modeling, testing, and deployment.

## MVP Features

- Create and view projects
- Create, view, and edit tasks
- Manage task statuses and priorities
- Search and filter tasks
- Validate form input
- Handle loading, error, empty, and success states
- Persist project and task data in PostgreSQL

## Technology Stack

### Frontend
- React
- TypeScript
- Vite
- TanStack Query for server state
- Zustand for selected local UI state
- Vitest and React Testing Library

### Backend
- Node.js
- Express.js
- TypeScript
- Jest for backend tests

### Database
- PostgreSQL

### Development and Deployment
- Git and GitHub
- Docker and Docker Compose
- Nginx
- GitHub Actions

## Architecture

PulseBoard follows a three-tier architecture.

### Frontend
React and TypeScript provide the user interface. TanStack Query manages server-state operations, while Zustand is reserved for appropriate local UI state.

### Backend
Node.js and Express.js expose a REST API. Routes direct requests to controllers and business logic. The backend validates input and handles errors.

### Database
PostgreSQL stores projects and tasks using relational tables, primary keys, and foreign keys.

### Data Flow

1. The user interacts with the React interface.
2. The frontend sends an HTTP request to the REST API.
3. Express.js validates the request and executes business logic.
4. The backend reads or writes data in PostgreSQL.
5. The API returns a response.
6. The frontend updates the displayed data and handles the resulting UI state.

## Additional Learning Labs

The following technologies are studied separately rather than being forced into the main application:

- Webpack
- NestJS
- Vue 2 and Vuex
- MySQL
- Redux

Optional stretch goals, depending on time and MVP stability:

- AWS
- Redis
- AI/LLM integration
- Kubernetes

## Project Status

Day 1: Repository setup and project specification.

The application implementation has not started yet.

## Development Approach

Each feature follows this cycle:

1. Understand the problem and the relevant concepts.
2. Implement the solution.
3. Test the behavior.
4. Debug issues.
5. Explain the design decisions and trade-offs.

AI tools may assist with explanations, debugging, and code review, but implementation decisions should be understood and verified.

## Planned Documentation

- Setup and installation instructions
- API endpoints
- Database schema
- Testing instructions
- Docker and deployment instructions
- Known limitations and future improvements
