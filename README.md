# Task Management System

A web-based task management system built with React, Express, and MongoDB.

## Features

- Create tasks with title and description
- Mark tasks as complete/incomplete
- View all tasks in a clean interface
- Edit existing tasks

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or higher)
- npm (comes with Node.js)
- MongoDB (v4.4 or higher)

## Installation

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create environment configuration:
   ```bash
   cp .env.example .env
   ```

4. Configure your MongoDB connection in `.env`:
   ```
   MONGODB_URI=mongodb://localhost:27017/task-management
   PORT=8000
   ```

5. Start the backend server:
   ```bash
   npm start
   ```

The backend server will run on http://localhost:8000

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the frontend development server:
   ```bash
   npm start
   ```

The frontend application will run on http://localhost:3000

## Usage

1. Create a Task:
   - Click the "Add Task" button
   - Enter task title and description
   - Click "Save" to create the task

2. View Tasks:
   - All tasks are displayed on the main page
   - Tasks show their title, description, and completion status

3. Complete/Incomplete Tasks:
   - Click the checkbox next to a task to toggle its completion status

4. Edit Tasks:
   - Click the "Edit" button on a task
   - Modify the title and/or description
   - Click "Save" to update the task

## API Endpoints

The backend provides the following RESTful endpoints:

- `GET /api/tasks` - Get all tasks
- `POST /api/tasks` - Create a new task
- `PATCH /api/tasks/:id` - Update a task
- `DELETE /api/tasks/:id` - Delete a task

## Tech Stack

- Frontend:
  - React with TypeScript
  - Tailwind CSS for styling
  - React Hooks for state management

- Backend:
  - Node.js with Express
  - MongoDB for data storage
  - RESTful API architecture

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
