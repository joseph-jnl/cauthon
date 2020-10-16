========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - |
        |
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/cauthon/badge/?style=flat
    :target: https://readthedocs.org/projects/cauthon
    :alt: Documentation Status

.. |version| image:: https://img.shields.io/pypi/v/cauthon.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/cauthon

.. |wheel| image:: https://img.shields.io/pypi/wheel/cauthon.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/cauthon

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/cauthon.svg
    :alt: Supported versions
    :target: https://pypi.org/project/cauthon

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/cauthon.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/cauthon

.. |commits-since| image:: https://img.shields.io/github/commits-since/joseph-jnl/cauthon/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/joseph-jnl/cauthon/compare/v0.0.0...master



.. end-badges

Collection of custom pytorch preprocessing transforms

* Free software: MIT license

Installation
============

::

    pip install cauthon

You can also install the in-development version with::

    pip install https://github.com/joseph-jnl/cauthon/archive/master.zip


Documentation
=============


https://cauthon.readthedocs.io/


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
