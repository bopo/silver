========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/silver/badge/?style=flat
    :target: https://readthedocs.org/projects/silver
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/bopo/silver.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/bopo/silver

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/bopo/silver?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/bopo/silver

.. |requires| image:: https://requires.io/github/bopo/silver/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/bopo/silver/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/bopo/silver/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/bopo/silver

.. |version| image:: https://img.shields.io/pypi/v/silver.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/silver

.. |commits-since| image:: https://img.shields.io/github/commits-since/bopo/silver/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/bopo/silver/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/silver.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/silver

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/silver.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/silver

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/silver.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/silver


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD license

Installation
============

::

    pip install silver

Documentation
=============

https://silver.readthedocs.io/

Development
===========

To run the all tests run::

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
