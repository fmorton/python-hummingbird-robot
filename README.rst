========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-hummingbird-robot/badge/?style=flat
    :target: https://python-hummingbird-robot.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/fmorton/python-hummingbird-robot/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/fmorton/python-hummingbird-robot/actions

.. |requires| image:: https://requires.io/github/fmorton/python-hummingbird-robot/requirements.svg?branch=main
    :alt: Requirements Status
    :target: https://requires.io/github/fmorton/python-hummingbird-robot/requirements/?branch=main

.. |codecov| image:: https://codecov.io/gh/fmorton/python-hummingbird-robot/branch/main/graphs/badge.svg?branch=main
    :alt: Coverage Status
    :target: https://codecov.io/github/fmorton/python-hummingbird-robot

.. |version| image:: https://img.shields.io/pypi/v/hummingbird-robot.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/hummingbird-robot

.. |wheel| image:: https://img.shields.io/pypi/wheel/hummingbird-robot.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/hummingbird-robot

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/hummingbird-robot.svg
    :alt: Supported versions
    :target: https://pypi.org/project/hummingbird-robot

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/hummingbird-robot.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/hummingbird-robot

.. |commits-since| image:: https://img.shields.io/github/commits-since/fmorton/python-hummingbird-robot/v0.0.9.svg
    :alt: Commits since latest release
    :target: https://github.com/fmorton/python-hummingbird-robot/compare/v0.0.9...main



.. end-badges

A robot using Birdbrain Technologies Hummingbird using the hummingbird_joystick and hummingbird_dual_motor_driver
packages.

* Free software: MIT license

Installation
============

::

    pip install hummingbird-robot

You can also install the in-development version with::

    pip install https://github.com/fmorton/python-hummingbird-robot/archive/main.zip


Documentation
=============


https://python-hummingbird-robot.readthedocs.io/


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
