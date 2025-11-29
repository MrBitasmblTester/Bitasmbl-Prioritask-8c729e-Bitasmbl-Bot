# Bitasmbl-Prioritask-8c729e-Bitasmbl-Bot

## Description
A modern full-stack task management web app where authenticated users manage project-based tasks with priorities. React powers a responsive SPA frontend, while a Node.js and Express.js backend exposes secure JWT-protected APIs for authentication, project categorization, and priority-sorted task operations, all covered with Jest tests to ensure maintainability and clean code practices.

## Tech Stack
- Express.js
- React
- Node.js
- JWT
- Jest (Node.js)

## Requirements
- Implement JWT-based authentication so only logged-in users can access project and task APIs.
- Support project-based task categorization with per-user ownership.
- Display tasks sorted by priority in the React UI for the selected project.
- Cover critical Node.js routes and JWT middleware with Jest tests.

## Installation
bash
git clone https://github.com/MrBitasmblTester/Bitasmbl-Prioritask-8c729e-Bitasmbl-Bot.git
cd Bitasmbl-Prioritask-8c729e-Bitasmbl-Bot
npm install
cd client
npm install


## Usage
bash
# Backend
npm test
npm start

# Frontend
cd client
npm start


## Implementation Steps
1. Set up Express.js server and Node.js project structure.
2. Implement JWT-based authentication middleware for protected routes.
3. Create user-specific project APIs for project-based task categorization.
4. Implement task APIs supporting priority-sorted operations per project.
5. Build React SPA to display projects and priority-sorted tasks.
6. Write Jest tests for critical Node.js routes and JWT middleware.

## API Endpoints
- POST /auth/login
- POST /auth/register
- GET /projects
- POST /projects
- GET /projects/:projectId/tasks
- POST /projects/:projectId/tasks