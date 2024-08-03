### Description Todo Application:

To build a to-do application using React components, you start by defining a set of components that manage different aspects of the app’s functionality. The primary component, often named App, serves as the container for other components and handles the overall state of the tasks. This component typically includes the task list, input field, and controls for adding, editing, and deleting tasks.

The TaskInput component is responsible for rendering an input field where users can enter new tasks. It also includes a button to submit the task, triggering a function passed from the App component to add the task to the list.

The TaskList component manages the display of tasks by iterating through the list of tasks and rendering a TaskItem component for each one. Each TaskItem displays the task’s text and includes options to mark the task as complete or delete it. It also handles user interactions, such as toggling the completion status and invoking deletion functions.

State management is handled within these components using React’s useState hook to maintain and update the list of tasks dynamically. Local storage integration can be used to persist tasks across page reloads. Styling with CSS or SCSS ensures that the application is both functional and visually appealing, providing a responsive design that works well on various devices.


### Features :
Add Task: Allows users to enter and add new tasks to the list.
Edit Task: Enables modification of existing task text.
Delete Task: Provides the option to remove tasks from the list.
Mark as Complete/Incomplete: Lets users toggle tasks between completed and pending.
Responsive Design: Ensures the application adapts to various screen sizes and devices.

### Technologies  

[React js] - to Build the web apps!
node.js - evented I/O for the backend
Express - fast node.js network app framework

### Installations :

install the dependencies and devDependencies and start the server.

npx create-react-app 
cd todoProject
npm start 

    "js-cookie": "2.2.1",
    "jsonwebtoken": "8.5.1",
    "react": "17.0.1",
    "react-dom": "17.0.1",
    "react-icons": "5.2.1",
    "react-loader-spinner": "4.0.0",
    "react-router-dom": "5.2.0"




### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
