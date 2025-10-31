Smart File Organizer Pro
-----------------------------------
A dark-mode Flask dashboard that organizes uploaded files into categorized folders.

Run locally:
> python -m venv venv
> venv\Scripts\activate
> pip install -r requirements.txt
> python app.py

Deploy on Render:
- Push this folder to GitHub
- Create new Web Service on Render
- Build Command: pip install -r requirements.txt
- Start Command: gunicorn app:app
