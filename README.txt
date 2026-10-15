RaktSetu - Blood Donor Finder (Flask + SQLite + Bootstrap 5)

Run karne ke steps (Windows / Mac / Linux):
1. Python 3.9+ install hona chahiye.
2. Is folder me terminal kholein.
3. (optional) python -m venv venv  ->  venv\Scripts\activate   (Mac/Linux: source venv/bin/activate)
4. pip install -r requirements.txt
5. python app.py
6. Browser me kholein: http://127.0.0.1:5000

Database (raktsetu.db) pehli run par apne aap ban jaata hai, sample data ke saath.
Reset karne ke liye raktsetu.db file delete karke dobara python app.py chalayein.
Bootstrap CDN se load hota hai, isliye internet chahiye.

Structure:
app.py            - Flask routes + SQLite
templates/        - HTML (Jinja2) pages
static/style.css  - custom dark theme
static/app.js     - contact modal, form validation
