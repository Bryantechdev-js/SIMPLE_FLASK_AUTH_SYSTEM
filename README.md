# Simple Login / Registration System in Python Flask

This is a complete beginner-friendly Flask authentication project with:

- User registration
- User login
- Session-based authentication
- Logout
- SQLite database
- Password hashing with Werkzeug
- Bootstrap-styled pages

## Project Structure

```bash
simple_flask_auth_system/
│── app.py
│── requirements.txt
│── README.md
│── users.db              # created automatically after first run
│── templates/
│   │── base.html
│   │── index.html
│   │── login.html
│   │── register.html
│   └── dashboard.html
└── static/
    └── css/
        └── style.css
```

## How to Run

### 1. Extract the zip folder

Unzip the project.

### 2. Open terminal in the project folder

```bash
cd simple_flask_auth_system
```

### 3. Create virtual environment (recommended)

#### Windows
```bash
python -m venv venv
venv\Scripts\activate
```

#### Mac/Linux
```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the app

```bash
python app.py
```

### 6. Open in browser

```bash
http://127.0.0.1:5000
```

## Default Notes

- The SQLite database file (`users.db`) is created automatically.
- Change the `SECRET_KEY` in `app.py` before using in production.
- This project is suitable for learning and small starter systems.

## Suggested Next Upgrades

- Email verification
- Forgot password
- Admin dashboard
- Profile edit page
- Flask-SQLAlchemy integration
- Role-based access control
