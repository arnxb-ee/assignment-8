# To-Do List API Backend

This is a Node.js, Express.js, and MongoDB backend for a To-Do List application.

## Features
- Create, Read, Update, Delete tasks
- Update task status
- Search tasks
- Modular structure (controllers, services, routes)
- Error handling and validation

## Setup & Run
1. Clone the repo and navigate to `todo-backend` folder.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up MongoDB (local or Atlas) and update `.env`:
   ```env
   MONGODB_URI=mongodb://localhost:27017/todo_db
   PORT=5000
   ```
4. Start the server:
   ```bash
   npm run dev
   ```
5. Test APIs using Postman at `http://localhost:5000/api/tasks`

## API Endpoints
- `POST /api/tasks` - Create task
- `GET /api/tasks` - List tasks
- `GET /api/tasks/:id` - Get task by ID
- `PUT /api/tasks/:id` - Update task
- `PATCH /api/tasks/:id/status` - Update status
- `DELETE /api/tasks/:id` - Delete task
- `GET /api/tasks/search?q=keyword` - Search tasks

## Environment Variables
- `MONGODB_URI` - MongoDB connection string
- `PORT` - Server port

## Challenges & Solutions

Replace MongoDB URI with your own if using Atlas. For any issues, check logs for error details.
>>>>>>> 8867ff0 (Initial commit: To-Do List backend and frontend)
