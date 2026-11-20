# TaskFlow - Full-Stack Task Management App

## Project Description
TaskFlow is a full-stack web application designed to help 
individuals and teams organize, track, and prioritize their 
daily tasks efficiently. It solves the problem of scattered 
to-do lists by providing a centralized, real-time dashboard 
with seamless data synchronization across devices.

## Front-End Plan
The front-end focuses on delivering a fast, responsive, and 
intuitive user experience.

- **Core Technologies:** Blazor WebAssembly, C#, HTML, CSS
- **UI/UX Components:**
  - Responsive Dashboard: Adaptive layout for desktop and 
    mobile with dark/light mode support
  - Task Cards & Boards: Interactive task items with priority 
    badges, due dates, and status toggles (To-Do, In Progress, Completed)
  - Interactive Forms: Clean input forms with validation for 
    creating and editing tasks
  - Navigation & Filtering: Search functionality and 
    category/status filters
- **State Management:** Blazor components with real-time UI 
  updates via SignalR

## Back-End Plan
The back-end handles business logic, data persistence, 
security, and API routing.

- **Core Technologies:** C#, ASP.NET Core, RESTful API
- **Database:** SQL Server to store user profiles and task records
- **Authentication & Security:** JWT tokens for protected routes, 
  password hashing for user credentials
- **Key API Endpoints:**
  - `POST /api/auth/register` & `POST /api/auth/login` — Authentication
  - `GET /api/tasks` — Retrieve all tasks
  - `POST /api/tasks` — Create new task
  - `PUT /api/tasks/:id` — Update task
  - `DELETE /api/tasks/:id` — Delete task
- **Error Handling:** Centralized middleware for clean HTTP 
  responses

## Development Tools
- **VS Code** — Code editor
- **GitHub** — Version control and collaboration
- **GitHub Copilot** — Real-time AI code suggestions
- **Microsoft Copilot** — Debugging and code refinement

## Development Principles
- Optimize performance across all layers
- Prioritize security at front-end and back-end
- Ensure accessibility for all users
- Embrace responsive design for every device
