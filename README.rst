=============================
Rest Simple Pandas
=============================

.. image:: https://badge.fury.io/py/djangorestframework-simple-pandas.svg
    :target: https://badge.fury.io/py/djangorestframework-simple-pandas

.. image:: https://travis-ci.org/fahmirevo/djangorestframework-simple-pandas.svg?branch=master
    :target: https://travis-ci.org/fahmirevo/djangorestframework-simple-pandas

.. image:: https://codecov.io/gh/fahmirevo/djangorestframework-simple-pandas/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/fahmirevo/djangorestframework-simple-pandas

simple pandas renderer for django rest framework

Documentation
-------------

The full documentation is at https://djangorestframework-simple-pandas.readthedocs.io.

Quickstart
----------

Install Rest Simple Pandas::

    pip install djangorestframework-simple-pandas

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'rest_simple_pandas.apps.RestSimplePandasConfig',
        ...
    )

Add Rest Simple Pandas's URL patterns:

.. code-block:: python

    from rest_simple_pandas import urls as rest_simple_pandas_urls


    urlpatterns = [
        ...
        url(r'^', include(rest_simple_pandas_urls)),
        ...
    ]

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox

Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
