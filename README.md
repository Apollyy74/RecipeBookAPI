﻿# RecipeBookAPI
RecipeBookAPI is a simple and efficient API built with Flask that allows users to retrieve and manage meal recipes. It connects to a MySQL database to fetch data for various meal categories like breakfast, lunch, dinner, and more.

## Getting Started

To start using the API, follow these steps:
1. Clone the repository.
2. Set up your MySQL database and configure the connection details.
3. Install the necessary Python packages using `pip install -r requirements.txt`.
4. Run the Flask server using `python app.py`.
5. Access the API via `http://localhost:5000` on your local machine.

## Available Endpoints
- **GET /breakfast**: Fetches all breakfast recipes.
- **GET /lunch**: Fetches all lunch recipes.
- **GET /dinner**: Fetches all dinner recipes.
- **GET /allmeals**: Fetches all available recipes across all categories.

## Technologies Used
- **Flask** for building the API.
- **MySQL** for the database.
- **PyMySQL** for database connectivity.
- **Flask-CORS** for handling cross-origin requests.

