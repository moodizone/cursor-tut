# TaskFlow

A modern task management application built with Next.js, Node.js, and Docker.

## Project Structure

```
taskflow/
├── frontend/          # Next.js frontend application
├── backend/           # Node.js backend API
├── docker/            # Docker configuration files
└── docs/             # Project documentation
```

## Tech Stack

### Frontend
- Next.js 14
- TypeScript
- Tailwind CSS
- React Query
- Socket.io Client

### Backend
- Node.js
- Express
- TypeScript
- PostgreSQL
- Socket.io
- JWT Authentication

### DevOps
- Docker
- Docker Compose
- GitHub Actions

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   # Install frontend dependencies
   cd frontend
   npm install

   # Install backend dependencies
   cd ../backend
   npm install
   ```
3. Start the development environment:
   ```bash
   docker-compose up
   ```

## Development

- Frontend runs on: http://localhost:3000
- Backend API runs on: http://localhost:4000

## Features

- [ ] User authentication
- [ ] Task management (CRUD operations)
- [ ] Real-time updates
- [ ] Drag-and-drop interface
- [ ] Dark/Light mode
- [ ] Responsive design
- [ ] Task categories and labels
- [ ] Search and filtering
- [ ] Task sharing and collaboration 