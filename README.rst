======
Syrinx
======

Enabling every bird sing freely.


What is Syrinx?
===============

A SQLite and Flask powered distributed twitter clone.


How do I use it?
================

1. edit the configuration in the __init__.py file or export an SYRINX_SETTINGS
   environment variable pointing to a configuration file.

2. fire up a python shell and run this:

>>> from syrinx import init_db; init_db()

3. now you can run the syrinx.py file with your python interpreter and the
   application will greet you on http://localhost:5000/

Is it tested?
=============

You betcha.  Run the `syrinx_tests.py` file to see the tests pass.
