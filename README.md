# Text-to-Web-app

## Overview
T2W-main is a web application generator built using Django. It automates the creation of frontend code based on input specifications, helping developers quickly generate web applications.

## Features
- Django-based backend for handling requests.
- SQLite database for storing generated data.
- Modular structure with a `generator` app handling core functionalities.
- RESTful API endpoints for interaction.

## Project Structure
```
T2W-main/
├── README.md
├── webapp_generator/
│   ├── db.sqlite3
│   ├── manage.py
│   ├── generator/
│   │   ├── __init__.py
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── models.py
│   │   ├── tests.py
│   │   ├── urls.py
│   │   ├── views.py
```

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/T2W-main.git
   cd T2W-main/webapp_generator
   ```
2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Apply migrations:
   ```sh
   python manage.py migrate
   ```
5. Run the development server:
   ```sh
   python manage.py runserver
   ```

## Usage
- Access the application at `http://127.0.0.1:8000/`
- Use the provided API endpoints to generate web applications dynamically.


