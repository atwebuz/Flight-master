
### Features
1. Users can create their user account.
2. Users can book both one-way as well as round-trip tickets.
3. Webpages are mobile responsive.
4. Users can cancel their booked tickets.
5. Users can view their previously booked tickets (Both confirmed and cancelled tickets).
6. Tickets are downloadable as pdf document.
7. As-you-type Search

- Install project dependencies by running `py -m pip install -r requirements.txt`.
- Run the commands `py manage.py makemigrations` and `py manage.py migrate` in the project directory to make and apply migrations.
- Create superuser with `py manage.py createsuperuser`. This step is optional.
- Run the command `py manage.py runserver` to run the web server.
- Open web browser and goto `127.0.0.1:8000` url to start using the web application.

```
python manage.py createsuperuser
```
