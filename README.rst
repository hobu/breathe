Breathe
=======

This is an extension to reStructuredText and Sphinx to be able to read and
render the Doxygen xml output.

Download
--------

Breathe is available from github and `PyPI, the Python Package Index
<http://pypi.python.org/pypi/breathe>`_

Documentation
-------------

Documentation is available in the ``documentation`` folder and up in full `here
<http://michaeljones.github.com/breathe>`_.

Testing
-------

Breathe doesn't have a set of tests at the moment. The documentation does a good
job of running the different parts of the Breathe functionality but there is
nothing to check that the output is appropriate.

To build the documentation, run ``make`` in the root of the project. 

This will run doxygen over the example code and then run the Breathe
documentation. View the results at::

   documentation/build/html/index.html

Requirements
------------

Development is currently done with:
 
- Python 2.7.4
- Docutils 0.11
- Sphinx 1.2.2
- Doxygen 1.8.4

Doxygen 1.5.1 seems to produce xml with repeated sections which causes Breathe
some confusion. Not sure when this was resolved but it might be best to go for
the latest possible.

Mailing List
------------

There is a mailing list available thanks to `LibreList <http://librelist.com>`_::

    breathe@librelist.com

The archives are available `here <http://librelist.com/browser/breathe/>`_.

Credits
-------

Thank you to:

- `nijel <https://github.com/nijel>`_
- `sebastianschaetz <https://github.com/sebastianschaetz>`_
- `mbolivar <https://github.com/mbolivar>`_
- `queezythegreat <https://github.com/queezythegreat>`_
- `abingham <https://github.com/abingham>`_
- `davidm <https://github.com/davidm>`_
- `hobu <https://github.com/hobu>`_
- `magro11 <https://github.com/magro11>`_
- `scopatz <https://github.com/scopatz>`_
- `vitaut <https://github.com/vitaut>`_
- `vonj <https://github.com/vonj>`_
- `jmnas <https://github.com/jmnas>`_
- `donkopotamus <https://github.com/donkopotamus>`_
- `jo3w4rd <https://github.com/jo3w4rd>`_
- `Anthony Truchet <https://github.com/AnthonyTruchet>`_
- `Daniel Matz <https://github.com/danielmatz>`_
- `Andrew Hundt <https://github.com/ahundt>`_
- `sebastinas <https://github.com/sebastinas>`_

For their contributions; reporting issues and improving the code and
documentation. And thanks to:

- Dimitri van Heesch for `Doxygen <http://www.stack.nl/~dimitri/doxygen/>`_.
- Georg Brandl for `Sphinx <http://sphinx-doc.org>`_.
- David Goodger for `Docutils <http://docutils.sourceforge.net/>`_ and reStructuredText. 

