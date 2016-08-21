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
        | |coveralls| |codecov|
        | |landscape| |scrutinizer| |codacy| |codeclimate|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/python-libsudofu/badge/?style=flat
    :target: https://readthedocs.org/projects/python-libsudofu
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/boweeb/python-libsudofu.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/boweeb/python-libsudofu

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/boweeb/python-libsudofu?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/boweeb/python-libsudofu

.. |requires| image:: https://requires.io/github/boweeb/python-libsudofu/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/boweeb/python-libsudofu/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/boweeb/python-libsudofu/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/boweeb/python-libsudofu

.. |codecov| image:: https://codecov.io/github/boweeb/python-libsudofu/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/boweeb/python-libsudofu

.. |landscape| image:: https://landscape.io/github/boweeb/python-libsudofu/master/landscape.svg?style=flat
    :target: https://landscape.io/github/boweeb/python-libsudofu/master
    :alt: Code Quality Status

.. |codacy| image:: https://img.shields.io/codacy/REPLACE_WITH_PROJECT_ID.svg?style=flat
    :target: https://www.codacy.com/app/boweeb/python-libsudofu
    :alt: Codacy Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/boweeb/python-libsudofu/badges/gpa.svg
   :target: https://codeclimate.com/github/boweeb/python-libsudofu
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/libsudofu.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/libsudofu

.. |downloads| image:: https://img.shields.io/pypi/dm/libsudofu.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/libsudofu

.. |wheel| image:: https://img.shields.io/pypi/wheel/libsudofu.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/libsudofu

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/libsudofu.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/libsudofu

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/libsudofu.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/libsudofu

.. |scrutinizer| image:: https://img.shields.io/scrutinizer/g/boweeb/python-libsudofu/master.svg?style=flat
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/boweeb/python-libsudofu/


.. end-badges

Crunch sudoku patterns

* Free software: BSD license

Installation
============

::

    pip install libsudofu

Documentation
=============

https://python-libsudofu.readthedocs.io/

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
