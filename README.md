<<<<<<< HEAD
# Essentials

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.1.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
=======
## Task Management Angular App

---

This is a simple task management application built with the Angular framework. It is my first app using Angular and demonstrates basic functionality such as adding tasks, marking tasks as complete, and storing/fetching data from localStorage for persistence.

## Features
Add Task: Users can add new tasks with a title, summary, and due date.

Mark Task as Complete: Users can mark tasks as completed, which removes them from the active task list.

Data Persistence: All tasks are saved in the browser's localStorage to retain data across sessions.

User-Specific Tasks: Tasks are associated with specific users by userId.

---

## Components

TasksComponent: Displays the list of tasks for a specific user, handles task completion, and shows the add task dialog.

TaskComponent: Shows individual task details and a button to mark it complete.

NewTaskComponent: Provides a form to create a new task which is then added to the list.

---

## Data Management

Tasks are managed using an Angular service (TasksService) which:

Maintains the list of tasks.

Adds new tasks.

Removes completed tasks.

Persists tasks in localStorage between sessions.

---

## Usage
Click the "Add Task" button to open the task creation form.

Fill in the title, summary, and due date of your task.

Click "Create" to add the task to your personal task list.

Click the "Complete" button next to any task to mark it as done and remove it from the list.

---

## Technologies Used
Angular 15+ (Standalone Components)

TypeScript

localStorage for persistence

Angular Forms (ngModel, EventEmitter)
>>>>>>> aa6f984209612b4c5f3cfd190a7709813fbb48bd
