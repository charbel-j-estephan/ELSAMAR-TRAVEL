# Django Website Project

## Overview
This Django project is designed to create a dynamic and user-friendly website for showcasing products. It includes features for managing product details, images, brochures, and background visuals through a comprehensive admin interface.

## Project Structure
- `manage.py`: Django's command-line utility for administrative tasks.
- `my_project/`: Main project directory.
  - `settings.py`: Django project settings and configurations.
  - `urls.py`: URL routing configuration for the project.
  - `wsgi.py`: WSGI application entry point.
  - `your_app/`: Django app directory.
    - `models.py`: Defines the database models, including the `Product` model.
    - `admin.py`: Registers models with the admin interface for management.
    - `views.py`: Contains view functions for rendering HTML templates and processing requests.
    - `urls.py`: URL routing configuration for the app.
    - `templates/`: HTML templates for rendering dynamic content.
    - `static/`: Static files such as CSS, JavaScript, and images.
    - `migrations/`: Database migration files generated by Django.
- `requirements.txt`: List of Python packages required for the project.

## Setup Instructions
1. Clone the repository:
   ```
   git clone https://github.com/charbel-j-estephan/ELSAMAR-TRAVEL.git
   ```
2. Activate the virtual environment:
   - Windows:
     ```
     venv\Scripts\activate
     ```
   - macOS/Linux:
     ```
     source venv/bin/activate
     ```
3. Apply database migrations:
   ```
   python manage.py migrate
   ```
4. Start the development server:
   ```
   python manage.py runserver
   ```
9. Access the admin interface at `http://127.0.0.1:8000/admin/` and log in with the superuser credentials.
10. Create and manage products, upload images and brochures, and customize background visuals through the admin interface.

## Customization and Extension
- To customize the website's design, modify HTML templates and static files in the app's `templates/` and `static/` directories.
- Extend functionality by adding new views, models, or forms as needed within the Django app.
- Ensure to update the `settings.py` file for production deployment, including database configuration, static files handling, and security settings.

## Contributors
- [Stephan](https://github.com/charbel-j-estephan) - Project Lead & Developer

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the `LICENSE` file for details.
