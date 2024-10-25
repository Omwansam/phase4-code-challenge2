#  Flask API for Episodes and Guests
This project implements a Flask API to manage episodes and guest appearances. The API includes functionality to create and retrieve episodes, guests, and appearances, with validations and relationships set up according to the provided ER diagram.

# Features
Manage episodes and guests through a RESTful API.
Create and retrieve appearances with validation for ratings.
Handle cascading deletes for relationships between episodes, guests, and appearances.


## Technologies Used

- Python
- Flask
- SQLAlchemy
- SQLite (or your preferred database)
- Alembic (for migrations)

## Prerequisites

Before running the project, ensure you have the following installed on your machine:

- Python 3.6 or later
- pip (Python package installer)

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Omwansam/phase4-code-challenge2.git
   cd  phase4-code-challange2

2. **Create the virtual environment**:

    ```bash
   pipenv install

3. **Activate the virtual environment**:

    ```bash
   pipenv shell

4. **Install the required packages**:

    ```bash
   pip install -r requirements.txt 

5. **Move the set up directory**:

    ```bash
   cd server   

6. **Set up the database**:

    ```bash
   flask db upgrade

7. **Seed the Database**:

    ```bash
   python3 seed.py

8. **Set up flask environment variable**:

    ```bash
   export FLASK_APP=app.py
   export FLASK_RUN_PORT=5555

9. **Run the application**:

    ```bash
   python3 app.py

This will start the Flask development server. By default, it runs on http://127.0.0.1:5555/