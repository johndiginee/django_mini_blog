# Django Mini Blog

## Project Overview

Django Mini Blog platform where users can read, create, update, and delete post!

Base link at https://seashell-app-rpxfb.ondigitalocean.app/

## Installation Instructions

### Prerequisites

Before setting up the project locally, ensure you have the following prerequisites installed:

- [Python](https://www.python.org/downloads/) (>=3.11.4)
- [Django](https://www.djangoproject.com/download/)
- [Django Rest Framework](https://www.django-rest-framework.org/#installation)
- A Database System (e.g., PostgreSQL, MySQL, SQLite) - [Django Database Installation](https://www.djangoproject.com/download/#database-installation)

### Installation Steps

1. Clone the repository:

        git clone https://github.com/johndiginee/django_mini_blog.git


2. Change into the parent directory:

        cd django_mini_blog


3. Set up a virtual environment:

        python3 -m venv venv


4. Activate your virtual environment:

        source venv/bin/activate


5. Install the Python dependencies:

        pip install -r requirements.txt


6. Create a .env file and set the necessary secret keys below:


7. Apply migrations to create the database schema:

        python3 manage.py makemigrations
        python3 manage.py migrate


8. Start the development server: 
 ```
 python3 manage.py runserver
 ```

The API should now be running locally at [http://localhost:8000/](http://localhost:8000/).