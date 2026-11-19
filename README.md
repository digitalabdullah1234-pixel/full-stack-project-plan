# TaskFlow - Full-Stack Task Management App

## Project Description
TaskFlow is a full-stack web application designed to help individuals and teams organize, track, and prioritize their daily tasks efficiently. It solves the problem of scattered to-do lists by providing a centralized, real-time dashboard with seamless data synchronization across devices.

## Front-End Plan
The front-end focuses on delivering a fast, responsive, and intuitive user experience.
- **Core Technologies:** React.js, Next.js, TypeScript, and Tailwind CSS for modern, utility-first styling.
- **UI/UX Components:**
  - **Responsive Dashboard:** Adaptive layout optimized for both desktop and mobile screens with dark/light mode support.
  - **Task Cards & Boards:** Interactive task items with priority badges, due dates, and status toggles (To-Do, In Progress, Completed).
  - **Interactive Forms & Modals:** Clean input forms with client-side validation for creating and editing tasks.
  - **Navigation & Filtering:** Top navigation bar with search functionality and category/status filters.
- **State Management & API Integration:** React Hooks (`useState`, `useEffect`) and Axios/Fetch for handling real-time UI updates and communicating with the back-end.

## Back-End Plan
The back-end handles business logic, data persistence, security, and API routing.
- **Core Technologies:** Node.js with Express.js framework for building a scalable RESTful API.
- **Database & Schema:** PostgreSQL (or MongoDB) to securely store user profiles, authentication credentials, and task records.
- **Authentication & Security:** JWT (JSON Web Tokens) for protected routes and password hashing using `bcrypt`.
- **Key API Endpoints:**
  - `POST /api/auth/register` & `POST /api/auth/login` — User registration and authentication.
  - `GET /api/tasks` — Retrieve all tasks for the logged-in user.
  - `POST /api/tasks` — Create and validate a new task entry.
  - `PUT /api/tasks/:id` — Update task status, priority, or details.
  - `DELETE /api/tasks/:id` — Remove a completed or unwanted task.
- **Error Handling:** Centralized middleware to return clean HTTP status codes and descriptive error messages.
