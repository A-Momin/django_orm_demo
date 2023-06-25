### Initialize `core` Django project with `student` app.

-   `$ mkdir django_orm_demo`
-   `$ cd django_orm_demo`
-   `$ cae django-env` → Activate the `django-env` conda environment.
-   `$ django-admin startproject core .`
-   `$ python manage.py startapp student`
    -   Checkout URL: `localhost:8000/`
-   `$ python manage.py createsuperuser --email bbcredcap3@gmail.com --username bbcredcap3@gmail.com --noinput`→ Create admin user.

    ```yaml
    ### Created admin user with following credentials:
    username: bbcredcap3@gmail.com
    password: 1111
    email: bbcredcap3@gmail.com
    ```

    -   Checkout URL: `localhost:8000/admin/`

-   `$ git add .`
-   `$ git commit -m "Initialize `core` Django project with` student` app."`
-   `$ git remote add origin git@github.com:A-Momin/django_orm_demo.git`
-   `$ git push origin master`
