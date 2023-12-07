# FULL-STACK(MERN) TASK MANAGER APP
![new-to-do](https://github.com/Peteroxy/Mern-stack-to-do-list-local-host-endpoints/assets/99334331/ccba6b9b-def3-45d9-87d9-9d1900d1bc26)


**INTRODUCTION**

Welcome to the Task Manager API Documentation! This API provides a simple and efficient solution for managing a list of tasks. Whether you're building a to-do list application, project management tool, or any other task-oriented system, this API is designed to streamline the process of creating, retrieving, updating, and deleting tasks.
You may visit this link to take a look at the deployed project https://task-manager-with-vercel-end-points-frontend.vercel.app/

**OVERVIEW**

The Task Manager API is built on Node.js and uses MongoDB as its underlying database. It follows RESTful principles, offering a straightforward interface for interacting with tasks. Each task in the system contains essential information, including a title, description, status (pending or completed), and creation date.

**USER STORIES**

It implements all the basic functionalities of a todo list, i.e, CRUD Operations (Create Read Update Delete).

-Create (POST) a Task: Users can create a new task by sending a POST request to the /item endpoint with the task details.

-Get All Tasks: Retrieve a list of all tasks by making a GET request to the /items endpoint.

-Get a Specific Task: Retrieve details of a specific task by making a GET request to the /items/:itemId endpoint.

-Update (PUT) a Task: Users can update a task by sending a PUT request to the /items/:itemId endpoint with the updated task details.

-Delete a Task: Remove a task from the system by making a DELETE request to the /items/:itemId endpoint.

**GETTING STARTED**


