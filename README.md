# Notify

## Description
This is a Flask-based web application where users can log in and maintain their notes. It supports user authentication and note management features.

## Features
- User authentication (Sign Up, Login, Logout)
- Create, edit, and delete notes
- Secure and responsive design

## Installation
### Prerequisites
- Python 3.x
- pip
- Virtual Environment (optional but recommended)

### Steps
1. Clone the repository:
   ```sh
   git clone <repository_url>
   cd Flask Web Application
   ```
2. Create and activate a virtual environment:
   ```sh
   python -m venv .venv
   source .venv/bin/activate  # For MacOS/Linux
   .venv\Scripts\activate     # For Windows
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Set the FLASK_APP environment variable:
   ```sh
   export FLASK_APP=main.py  # For MacOS/Linux
   set FLASK_APP=main.py     # For Windows
   ```
5. Run the application:
   ```sh
   flask run
   ```
6. Open a browser and go to `http://127.0.0.1:5000`

## Project Structure
```
Flask Web Application/
│-- website/
│   ├── static/         # CSS, JavaScript, images
│   ├── templates/      # HTML templates
│   ├── models.py       # Database models
│   ├── views.py        # Application routes
│   ├── auth.py         # Authentication routes
│   ├── __init__.py     # App initialization
│-- main.py             # Entry point of the app
│-- requirements.txt    # Dependencies
│-- README.md           # Project documentation
```



