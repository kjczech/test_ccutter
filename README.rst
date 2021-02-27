========
Overview
========

textoperations provides text manipulation functionality

* Free software: Apache Software License 2.0

Installation
============

::

    pip install test-cookiecutter

You can also install the in-development version with::

    pip install https://gitlab.com/kjczech/python-test_cookiecutter/-/archive/master/python-test_cookiecutter-master.zip


Documentation
=============


https://python-test_cookiecutter.readthedocs.io/


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
