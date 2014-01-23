userena-bootstrap
=================================
Twitter `Bootstrap`_ Templates for Django Userena.

Userena is a Django application that supplies your Django project with full
account management. It's a fully customizable application that takes care of
the signup, activation, messaging and more. It's BSD licensed, which means you
can use it commercially for free!

These templates use Twitter-bootstrap CSS to integrate Userena into a bootstrsap application.

.. _Bootstrap: http://getbootstrap.com/2.3.2/


Requirements
----------------------------

::

    django >= 1.3
    Userena >= 1.02
    django-bootstrap-form >= 2.03

And also

Twitter Bootstrap 2 (you must load the CSS files)


Installation
----------------------------

::

    $ git clone git://github.com/syntaxsugar/userena-bootstrap.git
    $ cd userenabootstrap && pip install .

Add the apps to your settings file BEFORE userena

::

    INSTALLED_APPS = (
        ...
        'bootstrapform',
        'userenabootstrap',
        'userena',
        ...
    )

