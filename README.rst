======================
Django Bad Word Filter
======================


.. image:: https://img.shields.io/pypi/v/badwordfilter.svg
        :target: https://pypi.python.org/pypi/badwordfilter

.. image:: https://img.shields.io/travis/riiy/badwordfilter.svg
        :target: https://travis-ci.org/riiy/badwordfilter

.. image:: https://readthedocs.org/projects/badwordfilter/badge/?version=latest
        :target: https://badwordfilter.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status




Python Boilerplate contains all the boilerplate you need to create a Python package.


* Free software: MIT license

Installation
------------
::
        pip install badwordfilter

Usage
-----

FILE_PATH must be plain text file, contains bad word, a word a line.

::
        from badwordfilter.badwordfilter import BadWordFilter

        bf=BadWordFilter(custom_censor_file={FILE_PATH}))

        bf.is_bad('fuck')


Credits
-------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
