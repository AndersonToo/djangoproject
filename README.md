# Django Tutorial Project (Parts 1–4)

A Django web application built by following the official Django documentation tutorial, covering parts 1 through 4.

## What's Covered

- **Part 1** – Project setup, creating an app, writing the first view
- **Part 2** – Database setup, models, Django admin interface
- **Part 3** – Views and templates (generic views)
- **Part 4** – Forms, generic views, and URL configuration


# Create and activate virtual environment
python -m venv venv
venv\Scripts\activate        # Windows

# Install dependencies
pip install django

# Apply migrations
python manage.py migrate

# Create superuser (for admin)
python manage.py createsuperuser

# Run the dev server
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser.

## Admin Panel

Access the Django admin at `http://127.0.0.1:8000/admin/` using the superuser credentials you created.

## Author

Anderson Too — Kaimosi Friends University
