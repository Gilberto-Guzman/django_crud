
    Get-ExecutionPolicy
    Set-ExecutionPolicy RemoteSigned


    pip install virtualenv
    python -m venv .venv
    .\.venv\Scripts\Activate
    pip install django

    django-admin startproject Universidad .

    md Aplicaciones
    cd .\Aplicaciones\

    django-admin startapp Academico

    cd ..

    python manage.py migrate
    python manage.py makemigrations

    python manage.py createsuperuser

    user: gilbe
    password: Eq_VdeRwx79e46i

    python manage.py runserver

