# Django CRUD API with Django REST Framework

This project is a simple CRUD (Create, Read, Update, Delete) API built using Django and Django REST Framework (DRF). It provides endpoints for managing resources such as users, posts, products, or any other data model.

## Features:

  RESTful API using Django REST Framework
  CRUD operations on a sample model
  Token-based authentication (optional)
  Pagination and filtering support
  Well-structured Django app with serializers, views, and models

## Installation:

  1. Clone the repository:
   
    git clone https://github.com/yourusername/Django-CRUD-API.git
    cd Django-CRUD-API

  2. Set up a virtual environment:

    python -m venv venv  # or python3 -m venv venv
    source venv/bin/activate  # On Windows use: venv\Scripts\activate

  3. Install dependencies:

    pip install -r requirements.txt

  4. Apply migrations:

    python manage.py migrate

## API Endpoints:
  GET /api/users/ - List all users
  POST /api/users/create/ - Create a new user
  GET /api/users/{id}/ - Retrieve a specific user
  PUT /api/users/{id}/ - Update an user
  DELETE /api/users/{id}/ - Delete an user


