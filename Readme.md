# Welcome to this repo

<img width="504" height="216" alt="image" src="https://github.com/user-attachments/assets/22d3c48f-c96a-4e34-bddf-56e2406679fd" />

============
Django-polls App
============
Django polls app, is an application to conduct web-based polls. For each
question, visitors can choose between a fixed number of answers with a voting option. It uses sqlite as a database, which you will have to set it up on your own dev environment.

* There is a github workflow included to test your code as you commit them:
Matrix python-version supported: <3.10. 

Quick start
-----------

1. Add "polls" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...,
        "django_polls",
    ]

2. Include the polls URLconf in your project urls.py like this::

    path("polls/", include("django_polls.urls")),

3. Run ``python manage.py migrate`` to create the models.

4. Start the development server and visit the admin to create a poll.

5. Visit the ``/polls/`` URL to participate in the poll.
