# Copilot Instructions for AI Agents

## Project Overview
This is a Django web application. The main project directory is `dashboard/`, containing the Django settings, URLs, and views. Templates are located in `templates/`.

## Architecture & Key Files
- `dashboard/dashboard/settings.py`: Django settings (database, installed apps, middleware, etc.)
- `dashboard/dashboard/urls.py`: Root URL configuration
- `dashboard/dashboard/views.py`: Core view logic
- `dashboard/templates/`: HTML templates for rendering views
- `dashboard/manage.py`: Django management script (runserver, migrations, etc.)
- `dashboard/db.sqlite3`: SQLite database (local development)

## Developer Workflows
- **Run the development server:**
  ```sh
  python manage.py runserver
  ```
- **Apply migrations:**
  ```sh
  python manage.py migrate
  ```
- **Create a superuser:**
  ```sh
  python manage.py createsuperuser
  ```
- **Templates:** Use Django template language in `templates/`.

## Project Conventions
- All Django code is under the `dashboard/dashboard/` directory.
- Templates are in `dashboard/templates/` and referenced by name in views.
- Database is SQLite by default for local development.
- No custom apps detected yet; all logic is in the main Django app.

## Integration & Patterns
- No external APIs or third-party integrations are present by default.
- Views are defined in `views.py` and mapped in `urls.py`.
- Static files and advanced settings are not yet configured.

## Example: Adding a New View
1. Define the view in `dashboard/dashboard/views.py`.
2. Add a URL pattern in `dashboard/dashboard/urls.py`.
3. Create a template in `dashboard/templates/` if needed.

---

**Update this file as the project grows or if new conventions are adopted.**
