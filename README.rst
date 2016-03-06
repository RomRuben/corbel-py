===========
 Corbel-py
===========

.. image:: https://travis-ci.org/RomRuben/corbel-py.svg?branch=master
    :target: https://travis-ci.org/RomRuben/corbel-py

.. image:: https://coveralls.io/repos/github/RomRuben/corbel-py/badge.svg?branch=master
    :target: https://coveralls.io/github/RomRuben/corbel-py?branch=master

.. image:: https://api.codacy.com/project/badge/grade/858f13a0745a4550ac7ea7d948a350f7
    :target: https://www.codacy.com/app/ruben-romcor/corbel-py

.. image:: https://caniusepython3.com/project/l.svg?style=flat
    :target: https://caniusepython3.com/project/l

Project Tools
=============

* Paver_ for running miscellaneous tasks
* Setuptools_ for distribution (Setuptools and Distribute_ have merged_)
* Sphinx_ for documentation
* flake8_ for source code checking
* pytest_ for unit testing
* mock_ for mocking (not required by the template, but included anyway)
* tox_ for testing on multiple Python versions

Using Paver
-----------

Tasks from pavement::

    lint             - Perform PEP8 style check, run PyFlakes, and run McCabe complexity metrics on the code.
    doc_open         - Build the HTML docs and open them in a web browser.
    coverage         - Run tests and show test coverage report.
    doc_watch        - Watch for changes in the Sphinx documentation and rebuild when changed.
    test             - Run the unit tests.
    get_tasks        - Get all paver-defined tasks.
    commit           - Commit only if all the tests pass.
    test_all         - Perform a style check and run all unit tests.



Install Project's development and runtime requirements
------------------------------------------------------

::

    pip install -r requirements-dev.txt

