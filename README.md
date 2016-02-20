corbelpy
==========================

[![Build Status](https://travis-ci.org/RomRuben/corbel-py.svg?branch=master)](https://travis-ci.org/RomRuben/corbel-py)
[![Coverage Status](https://coveralls.io/repos/github/RomRuben/corbel-py/badge.svg?branch=master)](https://coveralls.io/github/RomRuben/corbel-py?branch=master)


  * **Setting up the development environment before first use**
  
        > python bootstrap.py
        > export PATH=$PWD/bin:$PATH  
            (in Windows: set PATH=%CD%\bin;%PATH%)
        > buildout
       
  * **Running tests**  
    Tests are kept in the `tests` directory and are run using

        > py.test
    
  * **Creating Sphinx documentation**
  
        cd docs/
        make [html|epub|...]

  * **Debugging the code manually**      
    Simply run `bin/python`. This generated interpreter script has the project package included in the path.
    
  * **Publishing the package on Pypi**
  
         > python setup.py register sdist upload
       
  * **Creating an egg or a windows installer for the package**
  
         > cd src/corbelpy
         > python setup.py bdist_egg
          or
         > python setup.py bdist_wininst
