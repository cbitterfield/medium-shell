==================
medium-shell
==================


.. image:: https://img.shields.io/pypi/v/python_boilerplate.svg
        :target: https://pypi.python.org/pypi/python_boilerplate

.. image:: https://img.shields.io/travis/fgriberi/python_boilerplate.svg
        :target: https://travis-ci.org/fgriberi/python_boilerplate

.. image:: https://readthedocs.org/projects/python-boilerplate/badge/?version=latest
        :target: https://python-boilerplate.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status

medium-shell contains all the boilerplate you need to create a Python package.

Get Started!
--------
Here’s how to set up *medium-shell* for local environment.

1- Clone the *medium-shell* locally:

.. code-block:: console

    $ git clone git@github.com:cbitterfield/medium-shell.git

2- Install your local copy into a *virtualenv*. Assuming you have *virtualenvwrapper* installed, this is how you set up the package for local development:

.. code-block:: console

    $ sudo make boostrap
    $ mkvirtualenv medium-shell
    $ pip install -r requirements/dev.txt

3- How to enable/disable virtualenv

.. code-block:: console

    $ workon medium-shell
    $ ...
    $ deactivate


Credits
-------

This package was generated using Yeoman_ and Cookiecutter_ projects.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _Yeoman: https://yeoman.io/learning/
