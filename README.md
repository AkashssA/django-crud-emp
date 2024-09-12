# CRUD Operation using Django
## Employee List

| ID  | Name         | Salary   | Options          |
|-----|--------------|----------|------------------|
| 1   | John Doe     | $50,000  | [Update](#) [Delete](#) |
| 2   | Jane Smith   | $60,000  | [Update](#) [Delete](#) |
| 3   | Emily Johnson| $70,000  | [Update](#) [Delete](#) |
| ... | ...          | ...      | ...              |

## Create and Activate virtual env

    python -m venv venv
    ./venv/Scripts/activate

## Install Django & other dependencies

    pip install -r requirements.txt

## Create project and app

    django-admin startproject crud .
    django-admin startapp main

## Run the migrations
This is for creating a table inside the database using the `model.py` file

    python manage.py makemigrations
    python manage.py migrate

