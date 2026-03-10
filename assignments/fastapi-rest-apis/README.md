# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to design and build a simple REST API using the FastAPI framework. You will practice creating endpoints, handling request data, and returning structured JSON responses.

## 📝 Tasks

### 🛠️ Create Core API Endpoints

#### Description
Set up a FastAPI app and implement core endpoints for a simple resource, such as books, tasks, or products.

#### Requirements
Completed program should:

- Create a FastAPI application with at least one root endpoint (`GET /`) that returns a welcome message.
- Implement `GET` and `POST` endpoints for one resource collection (for example, `GET /items` and `POST /items`).
- Return all responses in JSON format with clear keys and values.

### 🛠️ Validate Data and Improve API Behavior

#### Description
Add request validation and robust API behavior so users receive clear and useful responses.

#### Requirements
Completed program should:

- Use a Pydantic model to validate request body data for the `POST` endpoint.
- Implement an endpoint to fetch a single resource by ID (for example, `GET /items/{item_id}`).
- Return an appropriate error response when a resource is not found.
