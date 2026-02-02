# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a simple REST API using FastAPI to practice endpoint design, request/response handling, and data validation with Pydantic models.

## 📝 Tasks

### 🛠️	Define the API and Data Models

#### Description
Set up a FastAPI application and define a data model for a resource (e.g., `Task` or `Book`).

#### Requirements
Completed program should:

- Create a FastAPI app instance
- Define a Pydantic model with at least three fields (including an `id`)
- Provide a root endpoint that returns a welcome message


### 🛠️	Implement CRUD Endpoints

#### Description
Add endpoints to create, read, update, and delete items stored in an in-memory list.

#### Requirements
Completed program should:

- Implement `POST` to add a new item
- Implement `GET` to list all items and `GET` by `id`
- Implement `PUT` to update an existing item
- Implement `DELETE` to remove an item by `id`
