# Basic Django Project

This is a minimal Django setup with a project `config` and app `core`.

## Quickstart

1. Create and activate virtualenv (already created at `.venv`):
   - Linux/macOS:
     - `python3 -m venv .venv`
     - `source .venv/bin/activate`
2. Install dependencies:
   - `pip install -r requirements.txt`
3. Run migrations:
   - `python manage.py migrate`
4. Start the dev server:
   - `python manage.py runserver`
5. Open http://127.0.0.1:8000/ to see "Hello, Django!"

## App structure
- `config/` — project settings and URLs
- `core/` — app with a simple `home` view (`core/views.py`) and URLconf (`core/urls.py`)
