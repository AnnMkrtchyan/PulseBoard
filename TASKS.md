# PulseBoard — 14-Day Development Roadmap

## Day 1 — Foundation and Specification
- [x] Create public GitHub repository
- [x] Initialize local Git repository
- [x] Connect local repository to GitHub
- [x] Create `.gitignore`
- [ ] Finalize MVP specification
- [ ] Document the planned technology stack
- [ ] Document frontend/API/database architecture
- [ ] Create `.env.example` with placeholder values
- [ ] Enable GitHub two-factor authentication
- [ ] Review files and Git changes
- [ ] Create the initial commit
- [ ] Push the initial commit to GitHub

## Day 2 — React + TypeScript Setup
- [ ] Set up Vite and TypeScript
- [ ] Configure linting and formatting
- [ ] Establish the component structure
- [ ] Build the application layout and navigation
- [ ] Add project and task list placeholders
- [ ] Implement loading, error, and empty states
- [ ] Add responsive styling

## Day 3 — UI and TypeScript Models
- [ ] Define Project and Task types
- [ ] Define TaskStatus and TaskPriority
- [ ] Build the task list and task items
- [ ] Implement status and priority filters
- [ ] Add task creation and editing forms
- [ ] Handle form validation errors
- [ ] Use mock data for the initial UI

## Day 4 — Server State, UI State, and Frontend Tests
- [ ] Integrate TanStack Query
- [ ] Use mock API data if the real API is not ready
- [ ] Use Zustand for appropriate local UI state
- [ ] Avoid duplicating server data in Zustand
- [ ] Configure Vitest and React Testing Library
- [ ] Test loading, error, empty, and success states

## Day 5 — Webpack Mini-Lab
- [ ] Create a separate Webpack demonstration
- [ ] Configure a minimal TypeScript/JavaScript build
- [ ] Compare Webpack with Vite
- [ ] Document the findings in a lab README

## Day 6 — Express.js REST API
- [ ] Set up Express.js and TypeScript
- [ ] Separate routes, controllers, and business logic
- [ ] Implement task CRUD operations
- [ ] Implement essential project operations
- [ ] Add JSON middleware and error handling
- [ ] Add safe request logging
- [ ] Document API endpoints

## Day 7 — PostgreSQL and SQL
- [ ] Design projects and tasks tables
- [ ] Define primary keys and foreign keys
- [ ] Add appropriate constraints
- [ ] Configure schema initialization or migrations
- [ ] Connect Express.js to PostgreSQL
- [ ] Practice SELECT, JOIN, GROUP BY, and HAVING
- [ ] Practice a transaction
- [ ] Add indexes only when justified

## Day 8 — NestJS Mini-Lab
- [ ] Create a separate NestJS demonstration
- [ ] Implement a module, controller, and service
- [ ] Add a DTO and validation
- [ ] Practice Dependency Injection
- [ ] Compare NestJS and Express.js
- [ ] Document the trade-offs

## Day 9 — Validation and Backend Tests
- [ ] Validate incoming API requests
- [ ] Standardize API error responses
- [ ] Configure Jest for backend tests
- [ ] Test business logic and API behavior
- [ ] Test invalid input and missing resources
- [ ] Review authentication requirements if applicable

## Day 10 — Docker and Docker Compose
- [ ] Create a Dockerfile for the API
- [ ] Containerize the frontend if appropriate
- [ ] Configure Docker Compose
- [ ] Add PostgreSQL to the local environment
- [ ] Configure environment variables safely
- [ ] Verify the documented startup procedure

## Day 11 — Nginx and Integration
- [ ] Configure Nginx as a reverse proxy or static server
- [ ] Connect frontend and API routing
- [ ] Review CORS and environment configuration
- [ ] Test the complete task workflow
- [ ] Document known limitations

## Day 12 — GitHub Actions / CI
- [ ] Create a GitHub Actions workflow
- [ ] Install dependencies in CI
- [ ] Run linting and tests
- [ ] Verify the production build
- [ ] Configure minimal workflow permissions
- [ ] Document CI status and checks

## Day 13 — One Optional Stretch Goal
- [ ] Choose at most one additional goal if the MVP is stable
- [ ] Consider AWS deployment
- [ ] Consider Redis caching
- [ ] Consider an AI/LLM endpoint
- [ ] Consider a local Kubernetes lab
- [ ] Document the decision and trade-offs

## Day 14 — Release and Portfolio
- [ ] Verify setup instructions from a clean environment
- [ ] Run tests, build, and CI
- [ ] Finalize README documentation
- [ ] Document architecture and trade-offs
- [ ] Add screenshots of the actual application
- [ ] Add a live demo only if safely deployed
- [ ] Pin the repository on GitHub
- [ ] Publish a truthful project summary on LinkedIn
- [ ] Document remaining knowledge gaps

## Additional Labs — After the MVP
- [ ] Redux vs. Zustand
- [ ] Vue 2 + Vuex
- [ ] MySQL vs. PostgreSQL
- [ ] Redis caching
- [ ] AI/LLM integration
- [ ] Local Kubernetes
- [ ] AWS deployment

## Definition of Done
- [ ] React + TypeScript frontend communicates with the API
- [ ] API persists data in PostgreSQL
- [ ] Core project and task workflows work
- [ ] Validation and error handling are implemented
- [ ] Key logic is tested
- [ ] Docker Compose supports local development
- [ ] GitHub Actions runs the required checks
- [ ] README explains setup, architecture, and limitations
- [ ] No secrets or employer/client code are exposed
- [ ] I can explain and debug the main parts independently
