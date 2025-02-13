# FullStack-project-using-SpringBoot-ReactJS (Backend )
In this project we use Java as Backend, spring Boot , React JS, MYSQL and Postman for Database

Project Overview:
Project aims to develop a dynamic and interactive full-stack website for to display this data for user credentials given on MY SQL or Postman . By combining the power of Spring Boot for the backend and React.js for the frontend, we strive to create a modern and user-friendly web application.

Technology Stack:

List the technologies and frameworks used in the project:

Backend: Spring Boot, Java

Frontend: React.js

Database: MySQL

API Platform: Postman

Additional Tools: Git, npm, Axios, Bootstrap, RESTful APIs

Spring Boot Backend:
Used RESTful API endpoints and Database integration with Spring Data JPA for creating packages. connected postman for @PostMapping for sending data to the database and @GetMapping for retrieving data and @PutMapping for updating data and @deleteMapping for deleting data.


React Frontend:
Begin by explaining the process of setting up a React app using npm:
Installed Node.js and npm if not already installed. Open the terminal and run the command npx create-react-app my-react-app to create a new React app named "my-react-app." Navigated into the project directory using cd my-react-app. Started the development server with npm start.This will create a basic React app with the necessary folder structure and dependencies.

Folder structure of the React APP:
src: Contains the source code of the React application.
index.js: Entry point of the React application.
App.js: Main component where other components are rendered.
components/: Directory for storing reusable components.
assets/: Directory for storing static assets such as images and CSS files.
pages/: Directory for storing individual pages of the application.

Creation of Navbar using Bootstrap and React:
Installed Bootstrap by running npm install bootstrap. Imported Bootstrap CSS in the index.js file: import 'bootstrap/dist/css/bootstrap.min.css';.Created a Navbar component in the components/ directory.Using Bootstrap's Navbar component and React's JSX syntax to define the Navbar structure. Customized the Navbar as needed by adding links, dropdowns, and other elements.

Creation of Homepage using a Bootstrap table:
Created a Homepage component in the pages/ directory and imported Bootstrap CSS in the Homepage component if not already imported.
Used Bootstrap's Table component to create a table layout and populate the table with dummy data or fetch data from an API using Axios and styled the table using Bootstrap classes. 

Use of Axios for making GET requests to fetch information:
Installed Axios by running npm install axios.Imported Axios in the component where data fetching is required: import axios from 'axios';.Used Axios's get() method to fetch data from a specified URL.Handled the Promise returned by Axios to access the fetched data.Updated the component's state with the fetched data, triggering a re-render to display the information.

Routing and Forms:
Installed react-router-dom by running npm install react-router-dom. Define routes in the main component of your application, typically App.js. Used BrowserRouter or HashRouter as the router component to wrap your application.<Route> components for each route, specifying the path and component to render.

Exception Handling:
Used @ControllerAdvice annotation to define a global exception handler class. Used methods within this class annotated with @ExceptionHandler to handle specific exceptions. In each method, define the logic to construct error responses with appropriate HTTP status codes, error messages, and additional details if necessary. Return the error response as JSON or XML, depending on your application's requirements.

User Management:
Ensuring efficient editing and deletion of users in your Spring Boot and React.js project while utilizing Axios for making PUT and DELETE requests to the backend.

Viewing Specific User Information: users can view specific information about themselves or other users in your Spring Boot and React.js project. The backend endpoint retrieves the requested user's data from the database, while the frontend component fetches and displays this information to the user.

Forntend part Link: https://github.com/Prashanthi9/FullStack-project-using-SpringBoot-ReactJS-Frontend

Backend Part Link: https://github.com/Prashanthi9/FullStack-project-using-SpringBoot-ReactJS
