Introduction
============

.. toctree::
   :maxdepth: 2
   :caption: Contents:

* Github: https://github.com/utlco/utl-sphinx-theme

This theme is a variation of **sphinx13** which is currently used by
`Sphinx <https://www.sphinx-doc.org/en/master/index.html>`_ documentation.
But more brown.

This documentation uses utl_sphinx_theme.


How to use
==========

Install the theme from GitHub::

    pip install https://github.com/utlco/utl-sphinx-theme/archive/refs/heads/main.zip

Add the following line to your conf.py::

    html_theme = 'utl_sphinx_theme'

To change the theme options (also in conf.py)::

    html_options = {
        'title': 'MyTitle',
        'logo': '_static/my-logo.svg',
    }

By default it will use the logo image **_static/logo.svg**.

