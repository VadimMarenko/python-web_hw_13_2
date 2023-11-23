# Implementation of the Django project

The `/hw_project/.env` file with environment variables is required for the project to work.
Create it with this content and substitute your values.

```dotenv
SECRET_KEY=

DATABASE_NAME=
DATABASE_USER=
DATABASE_PASSWORD=
DATABASE_HOST=
DATABASE_PORT=

EMAIL_HOST=
EMAIL_PORT=
EMAIL_HOST_USER=
EMAIL_HOST_PASSWORD=
```

Launching the application

The postgres service is required to run the application
```
cd hw_project
python3 manage.py migrate
python3 manage.py runserver
```