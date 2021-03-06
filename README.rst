TorStatus README
================
.. Updated 2011-06-28 11:00:00 GMT-5
.. This file is written in reStructuredText.

Installation
------------
For help installing and running TorStatus, consult doc/INSTALL.rst.

Generating the API
------------------
To generate the TorStatus API, install epydoc (available at
http://epydoc.sourceforge.net/installing.html) and run:

    | $ cd status/
    | $ epydoc . --config config/epydoc_config.py

ReStructured Text
-----------------
TorStatus documentation, like this README, is written in
reStructuredText. To generate HTML-formatted design documentation using
reStructuredText, install docutils (available at
http://docutils.sourceforge.net/) and run commands analogous to
the following:

    | $ cd doc/
    | $ rst2html design.rst design.html

To view the documentation, open design.html using your favorite web
browser. If you'd rather view the plaintext documentation, open
design.rst.

