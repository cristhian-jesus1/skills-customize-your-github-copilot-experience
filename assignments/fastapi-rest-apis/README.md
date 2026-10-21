# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build a REST API with FastAPI by creating endpoints, managing a small resource, and validating requests.

## 📝 Tasks

### 🛠️ Create Your First Endpoint

#### Description
Create a FastAPI application with a welcome endpoint and run it locally.

#### Requirements
Completed program should:

- Create a FastAPI application that starts with Uvicorn
- Define a `GET /` endpoint that returns a JSON welcome message
- Confirm the endpoint works by opening its URL or using an API client


### 🛠️ Build a CRUD API

#### Description
Create an API for managing a small in-memory collection, such as books or tasks.

#### Requirements
Completed program should:

- Define endpoints to list all items, retrieve one item by ID, create an item, and update or delete an item
- Return the appropriate HTTP status codes for successful requests and missing items
- Store and return item data as JSON


### 🛠️ Validate Requests and Explore the API

#### Description
Add request validation and use FastAPI's interactive documentation to try the API.

#### Requirements
Completed program should:

- Define a Pydantic model for the data required to create an item
- Reject a request with invalid or missing required data
- Use the interactive API documentation to test each endpoint
