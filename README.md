Tech stack and Framework:

Backend:
Node.js – JavaScript runtime used to run the server.
Express.js – Web framework for building the RESTful API (server.js).
Mongoose – ODM library for MongoDB to define schemas and interact with the database (models.js).
MongoDB – NoSQL database for storing quizzes.

Frontend:
HTML5 – Used in index.html to create the UI structure.
CSS3 – For styling the frontend UI (style.css).
Vanilla JavaScript (ES6) – Used in script.js for handling user interactions, DOM updates, and API calls.

Dependencies:
express – HTTP server framework.
mongoose – MongoDB object modeling.
node-fetch – To make HTTP requests (though not actively used in the final implementation).

Project structure:
server.js – Entry point for the Express server.
models.js – Defines the Mongoose schema and model for quizzes.
index.html, style.css, script.js – Frontend files in the public directory (served statically).
package.json / package-lock.json – Project metadata and dependencies.

Note: The huggingface token has been removed for security purposes, add it in server.js before you run.

