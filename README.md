# Task Manager App (Angular)

This is a simple Task Manager web application built with Angular. It allows users to add tasks with a name and priority, view them in a list, and mark them as completed. It demonstrates component communication, data binding, and Angular directives.

## 🔧 Features

- Add tasks with a **name** and **priority** (High, Medium, Low)
- View task list in a **child component**
- Mark tasks as **Completed**
- Show **"No tasks available"** message when the list is empty
- Dynamic styling based on **task priority** and **status**

## 📚 Angular Concepts Used

- `@Input()` and `@Output()` for parent-child communication
- Two-way binding using `[(ngModel)]`
- Template Reference Variables
- Directives: `*ngIf`, `*ngFor`, `ngSwitch`, `ngClass`, `ngStyle`
- Event Binding: `(click)`

## 🏗️ Component Structure

- `task-manager` (Parent)
  - Handles task creation and manages the task list
- `task-list` (Child)
  - Displays the list of tasks and emits events when a task is completed

## 🚀 Getting Started

1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/task-manager-angular.git
   cd task-manager-angular


#Project Structure

src/
├── app/
│   ├── task-manager/
│   │   ├── task-manager.component.html    # Main component template
│   │   ├── task-manager.component.ts     # Main component logic
│   │   └── task-manager.component.scss   # Main component styles
│   ├── task-list/
│   │   ├── task-list.component.html      # Task list template
│   │   ├── task-list.component.ts        # Task list logic
│   │   └── task-list.component.scss      # Task list styles
│   ├── app.component.html                # Root component template
│   └── app.component.ts                  # Root component logic


License
This project is open source and available under the MIT License.
