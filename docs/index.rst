
pynliner
====================================

.. automodule :: pynliner

Project pages
-------------

- PyPI package page: http://pypi.python.org/pypi/pynliner
- github project page: http://github.com/rennat/pynliner
- this documentation: http://pythonhosted.org/pynliner

installation
------------

::

    $ easy_install pynliner

or

::

    $ pip install pynliner

example 
-------

>>> html = u'<style>h1 { color:#ffcc00; }</style><h1>Hello World!</h1>'
>>> output = pynliner.fromString(html)
u'<h1 style="color: #fc0">Hello World!</h1>'

functions
---------

.. autofunction :: pynliner.fromURL
.. autofunction :: pynliner.fromString

pynliner.Pynliner
-----------------

.. autoclass :: pynliner.Pynliner

methods
~~~~~~~

.. automethod :: pynliner.Pynliner.from_url
.. automethod :: pynliner.Pynliner.from_string
.. automethod :: pynliner.Pynliner.with_cssString
.. automethod :: pynliner.Pynliner.run


changelog
=========

0.5.0
-----

- started keeping track of changes here.
- improve CSS capabilities
- abandon old versions of BeautifulSoup (pre 3.2.1) in favor of full unicode support
