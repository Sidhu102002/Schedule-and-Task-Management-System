# 📅 Tasks App (To-Do List)

Website of a task organizer (to-do list) built with React JS, Tailwind CSS, TypeScript, Redux Toolkit, and more.

![home page](./src/assets/Screenshot%202023-08-19%20at%206.59.23%20PM.png)

## Description

- Used for organizing your tasks with the following data: title, description, date, mark as complete, and mark as important.
- Tasks are organized into categories: today's tasks, important tasks, incomplete tasks, complete tasks, all tasks, and tasks by directory (folder). Directories and tasks can be edited or deleted. Additionally, there is a main directory called "Main" that cannot be edited or deleted.
- The task list can be displayed first by: closest, farthest, complete, or incomplete.
- You can search for tasks in the search field.
- Today's tasks are displayed in the user section and in notifications.
- Task, directory, and dark mode data are saved in localStorage.

## Objective

The project primarily aimed to apply knowledge of TypeScript, Tailwind, Redux Toolkit, and React JS.

## Tools Used

- React JS
- TypeScript
- Tailwind CSS
- Redux Toolkit
- React Router DOM
- HTML
- Figma (prototyping)

## How to Test

You can access the project here: https://tasks-app-aridsm.netlify.app/

Or run it on your machine:

``` 
git clone https://github.com/aridsm/tasks-app.git
cd tasks-app
npm install
npm start
```

## Notes

- Task, directory, and dark mode data are saved in your browser's localStorage. You can click the "delete all data" button to remove them from localStorage.
- For demonstrative purposes, the application comes with a default list of 3 tasks and 1 directory called "Main."
