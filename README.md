**BajtaHack hackathon demo project**

.. image:: https://travis-ci.org/psywerx/BajtaHack.svg?branch=master
  :target: https://travis-ci.org/psywerx/BajtaHack
  :alt: Traves CI

.. image:: https://codecov.io/gh/Psywerx/BajtaHack/branch/master/graph/badge.svg
  :target: https://codecov.io/gh/Psywerx/BajtaHack
  :alt: Codecov


This is an example project for Bajtahack heckaton. This app contains a simple
web server for controlling a SRM module.


Installation
------------

For basic usage:

.. code:: sh

    pip instal git+git://github.com/psywerx/BatjaHack.git


Usage
-----

.. code:: python

    export FLASK_APP=web
    flask run

For development
---------------

Install

.. code:: sh

    virtualenv --python=python3 bajtahack_env
    bajtahack_env/bin/activate
    git clone git://github.com/psywerx/BajtaHack.git
    cd BajtaHack
    pip install -e .[dev,test]

Run tests

.. code:: sh

    python setup.py test

