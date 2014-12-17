# REST framework tutorial

This is [Brent O'Connor's](https://github.com/epicserve) code from the [REST framework tutorial](http://www.django-rest-framework.org/tutorial/1-serialization/).


## Environment Setup

1. Clone and checkout the code

        cd ~
        git clone https://github.com/epicserve/rest-framework-tutorial.git
        cd rest-framework-tutorial

2. Create a python virtualenv

        virtualenv env
        source env/bin/activate

3. Install requirements

        pip install -r requirements.txt

4. Run migrate

        ./manage.py migrate

5. Create a user

        ./manage.py createsuperuser

6. Run the development server

        ./manage.py runserver

