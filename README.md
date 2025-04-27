# Auto Parts API

This is a FastAPI-based API for managing items and categories in an online auto parts store.

## Run the app

To run the app locally:

1. Install the required dependencies:
pip install -r requirements.txt

2. Run the server using Uvicorn:
uvicorn app.main:app --reload

3. Access the API documentation at `http://127.0.0.1:8000/docs`.

## Database

The application uses SQLite by default, and database tables can be created with the command:

python init_db.py
