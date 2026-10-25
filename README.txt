RaktSetu - Blood Donor Finder (Flask + SQLite + Bootstrap 5)

Steps to Run (Windows / Mac / Linux):

1. Python 3.9+ must be installed.
2. Open the terminal in this folder.
3. (Optional) python -m venv venv → venv\Scripts\activate (Mac/Linux: source venv/bin/activate)
4. pip install -r requirements.txt
5. python app.py
6. Open in your browser: http://127.0.0.1:5000

The database (raktsetu.db) is automatically created on the first run with sample data.

To reset it, delete the raktsetu.db file and run python app.py again.

Bootstrap loads from a CDN, so an internet connection is required.

Structure:

app.py — Flask routes + SQLite  
templates/ — HTML (Jinja2) pages  
static/style.css — Custom dark theme  
static/app.js — Contact modal, form validation
