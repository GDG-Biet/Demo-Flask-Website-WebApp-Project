# Demo-Flask-Website-WebApp-Project
# Flask Project Demo

This is a simple Flask-based web application with user authentication functionality, including login and registration features. Below is the project structure and a brief overview of its components.

## File Structure

```
Flask Project Demo/
│
├── .venv/                          # Virtual environment for the project
│
├── instance/                       # Instance folder (currently empty) for SQLite3(u can choose any other database here if u want)
│
├── static/
│   └── style.css                   # CSS file for styling
│
├── templates/                      # HTML templates
│   ├── home.html                   # Home page
│   ├── login.html                  # Login page
│   └── register.html               # Registration page
│
└── app.py                          # Main Flask application
```

## Flask Application: `app.py`

The main Flask application includes routes for:

- **Home** (`/`)
- **Login** (`/login`)
- **Register** (`/register`)

### Key Features:
- User authentication using Flask and SQLAlchemy.
- Database initialization for user management.
- Flash messages for form validation feedback.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/AyushGoel0/Flask-Project-Demo.git
   cd Flask-Project-Demo
   ```

2. Set up a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # For Linux/Mac
   .venv\Scripts\activate     # For Windows
   ```

3. Install dependencies:
   ```bash
   pip install Flask SQLAlchemy
   ```

4. Run the Flask app:
   ```bash
   python app.py
   ```

5. Open your browser and visit `http://127.0.0.1:5000`.

## Technologies Used

- **Flask**: Web framework for Python.
- **SQLAlchemy**: ORM for database management.
- **HTML/CSS**: Frontend templates and styling.
- **SQLite**: Lightweight database for user data storage.

---

## The tech stack for this **Flask Project Demo** includes the following technologies:

### **Frontend**:
1. **HTML** - For structuring the web pages.
2. **CSS** - For styling and layout (basic styles provided in `style.css`).

### **Backend**:
1. **Flask** - Lightweight Python web framework for building web applications.
2. **SQLAlchemy** - Object-Relational Mapping (ORM) tool for database interactions.

### **Database**:
1. **SQLite** - Lightweight and embedded database for managing user authentication data.

### **Server**:
1. **Flask Development Server** - Built-in development server for running and testing the application.

### **Other Tools**:
1. **Python** - The programming language used for backend development.
2. **Virtual Environment** (`venv`) - For managing Python dependencies locally without affecting the global environment.

---

### **Summary of Tech Stack**:
- **Frontend**: HTML, CSS  
- **Backend**: Flask, Python  
- **Database**: SQLite  
- **Tools**: SQLAlchemy, Python Virtual Environment  

This combination of technologies makes the project simple, modular, and easy to deploy or scale as needed.
