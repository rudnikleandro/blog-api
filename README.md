# Frontend with Node.js and Express
This is a frontend project built with Node.js and Express, which interacts with a separate API to perform CRUD operations (Create, Read, Update, Delete) on blog posts. The API backend runs on a different server, and this project serves as the user interface, allowing users to view, create, edit, and delete posts through dynamic pages rendered with EJS.

## Features
View posts: The homepage displays all blog posts stored in the API.
Create new post: A dedicated page allows users to create new blog posts.
Edit existing post: Option to edit an existing post using the post ID.
Delete post: Allows users to delete posts through the user interface.
API integration: All CRUD operations are performed via HTTP requests to a backend API.
Technologies Used
Node.js: Runtime environment for building the web application.
Express: Minimalist framework for Node.js, used for managing routes and requests.
Axios: HTTP client library used to communicate with the API.
EJS: Template engine for dynamic HTML page rendering.
Body-Parser: Middleware to process incoming HTTP request data.

## How to Run the Project

### Clone this repository:

```git clone https://github.com/your-username/repository-name.git```

### Install the dependencies:

```npm install```

Ensure the API server is running on port 4000. (This frontend is configured to connect to an API at http://localhost:4000).

### Start the server:

```npm start```

### Open your browser and go to:

```http://localhost:4200```

### File Structure
server.js: Main file to run the Express server.
public/: Directory for static files.
views/: Contains EJS template files for rendering pages.
routes/: Defines the routes and API interaction functionality.
Future Improvements
Add an authentication system to protect post creation and editing.
Implement pagination to handle a large number of posts.
Improve the interface with more visual elements and responsiveness.
