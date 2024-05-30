# Task Management Project
A task management application using Laravel (backend) and Vue (frontend) with Tasks CRUD Listing features.

## Endpoints
1. GET `/api/tasks` Retrieve and return all tasks `index()`.
2. POST `/api/tasks` Create a new task `store(StoreTaskRequest $request)`.
3. GET `/api/tasks/{task}` Show the task `show(Task $task)`.
4. PUT `/api/tasks/{task}` Update the task (e.g., mark as completed) `update(UpdateTaskRequest $request, Task $task)`.
5. DELETE `/api/tasks/{task}` Delete the task `destroy(Task $task)`.

## Installation
1. Clone the project `git clone git@github.com:achilezweb/task-management.git`
2. Navigate to the project's root directory using terminal
3. Create `.env` file - `cp .env.example .env`
4. Execute `composer install`
5. Execute `npm install`
6. Set application key - `php artisan key:generate --ansi`
7. Execute migrations and seed data - `php artisan migrate --seed`
8. Start Artisan server - `php artisan serve`

## Screenshot
<img src="https://www.archiemercader.com/downloads/task-list.png" alt="Task Management Project">

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
