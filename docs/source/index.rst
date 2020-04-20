Welcome to zipcreator's documentation!
==============================================

A quick tool for creating a zipfile from a list of files and/or directories.

Installation
^^^^^^^^^^^^
::

    python setup.py install

or::

    pip install zipcreator

Example
^^^^^^^
::

   from zipcreator import list_zip

   files = ['test.txt', 'testdir/test2.txt']
   dest = 'result.zip'

   list_zip.create(files, dest)

:mod:`list_zip` Module
^^^^^^^^^^^^^^^^^^^^^^

.. automodule:: zipcreator.list_zip
    :members:

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Versioning
^^^^^^^^^^

v1.0.0 - Initial Release - 04/20/2020

Authors
^^^^^^^

* **Matt Palazzolo** - `GitHub Profile <https://github.com/mpalazzolo>`_

License
^^^^^^^
https://github.com/mpalazzolo/apple-music-python/LICENSE.txt

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
