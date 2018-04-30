=====
Artists
=====

Artists is a simple Django app to scrape artist data from the week of 4/28 (for now). You can see the top 100 Billboard Artists for that week, a visualization of the # of weeks each artist has been charted, as well as their gigography.
Detailed documentation is probably not in the "docs" directory.

Quick start
-----------

1. Add "artists" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'artists',
    ]

2. Include the artists URLconf in your project urls.py like this::

    path('artists/', include('artists.urls')),

3. Run `python manage.py migrate` to create the polls models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a poll (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/artists/ to participate in the poll.
