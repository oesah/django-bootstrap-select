Django Bootstrap Select
============

Django Bootstrap Select widgets.

Installation
------------

To get the latest stable release from PyPi

.. code-block:: bash

    pip install django-bootstrap-select

To get the latest commit from GitHub

.. code-block:: bash

    pip install -e git+git://github.com/oesah/django-bootstrap-select.git#egg=django_bootstrap_select

TODO: Describe further installation steps (edit / remove the examples below):

Add ``django_bootstrap_select`` to your ``INSTALLED_APPS``

.. code-block:: python

    INSTALLED_APPS = (
        ...,
        'django_bootstrap_select',
    )

Add the ``django_bootstrap_select`` URLs to your ``urls.py``

.. code-block:: python

    urlpatterns = [
        url(r'^django-bootstrap-select/', include('django_bootstrap_select.urls')),
    ]

Before your tags/filters are available in your templates, load them by using

.. code-block:: html

	{% load django_bootstrap_select_tags %}


Don't forget to migrate your database

.. code-block:: bash

    ./manage.py migrate django_bootstrap_select


Usage
-----

TODO: Describe usage or point to docs. Also describe available settings and
templatetags.


Contribute
----------

If you want to contribute to this project, please perform the following steps

.. code-block:: bash

    # Fork this repository
    # Clone your fork
    mkvirtualenv -p python2.7 django-bootstrap-select
    make develop

    git co -b feature_branch master
    # Implement your feature and tests
    git add . && git commit
    git push -u origin feature_branch
    # Send us a pull request for your feature branch

In order to run the tests, simply execute ``tox``. This will install two new
environments (for Django 1.8 and Django 1.9) and run the tests against both
environments.

Sponsorship
-----------

This project is maintained by `Mathison AG | Mobile & Web Development <https://mathison.ch>`_.

Used by
-------

* `Stella Gastro | The best Restaurants, Bars and Cafés in Switzerland <https://stellagastro.ch>`_.
* `Lancer Express | The Swiss Army Knife for Freelancers <https://my.lancer.express>`_.
