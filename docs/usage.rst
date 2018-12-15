=====
Usage
=====

To use Rest Simple Pandas in a project, add it to your `INSTALLED_APPS`:

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
