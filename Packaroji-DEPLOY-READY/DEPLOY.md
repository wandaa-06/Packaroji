# Packaroji deployment

This package is intentionally flat at the repository root.

Render:
- Root Directory: leave EMPTY
- Build Command: pip install -r requirements.txt
- Start Command: gunicorn --bind 0.0.0.0:$PORT app:app
- Environment variables: SECRET_KEY, PACKAROJI_ADMIN_PASSWORD

Do not commit .env or secrets.
