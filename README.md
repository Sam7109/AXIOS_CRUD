# AXIOS_CRUD

# Backend-Frontend CRUD Project with Axios

This project demonstrates a basic CRUD (Create, Read, Update, Delete) application with a backend server and frontend client using Axios for HTTP requests.
The backend server is simulated using the dummy backend service provided by [crudcrud.com](https://crudcrud.com/).

***************************************************************************************************************************
## Overview

The project consists of two main parts:

1. Backend Server:
   - Simulated using the dummy backend service provided by [crudcrud.com](https://crudcrud.com/).
   - Implements basic CRUD operations for managing data.
   - Exposes RESTful API endpoints for performing CRUD operations.
   - Uses Axios for handling HTTP requests.

2. Frontend Client:
   - Provides a user interface for interacting with the backend server.
   - Consists of four buttons (`GET`, `POST`, `PUT`, `DELETE`) for triggering CRUD operations.
   - Uses Axios for making HTTP requests to the backend API.
***************************************************************************************************************************
## How to Run

1. Clone the repository:

2 . Create an endpoint on https://crudcrud.com/ 

3 . Now on console tab of window the Operations should be visible ! ! 

***************************************************************************************************************************
The backend server exposes the following RESTful API endpoints:

- `GET /api/data`: Retrieves all data from the backend.
- `POST /api/data`: Creates new data on the backend.
- `PUT /api/data/:id`: Updates existing data on the backend.
- `DELETE /api/data/:id`: Deletes data from the backend.
