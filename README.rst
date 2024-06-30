
================
utl_sphinx_theme
================

- Github: https://github.com/utlco/utl-sphinx-theme
- Documentation: https://utlco.github.io/utl-sphinx-theme/


Introduction
============

Very simple
`Sphinx <https://www.sphinx-doc.org/en/master/index.html>`_
theme loosely derived from **sphinx13** which is a nice compact
and minimal theme that Sphinx uses for its own documentation.

There are a few small differences, mainly in colors (more brown)
and header styling (less chrome).
Also adds a couple of theme options (*title*, *logo*).

This is mainly used for UTLCo projects and may change in unexpected ways,
so if you really want to use this then it may be better to fork it.


Installation
============

Install the theme::

    pip install utl-sphinx-theme


How to use
==========

Add the following line to your Sphinx doc *conf.py*::

    html_theme = 'utl_sphinx_theme'

If you use GitHub workflow actions to build your docs you
will also probably need to create a requirements.txt in your docs
folder with this package listed in it.


Theme options
-------------

Inherits all basic theme options and adds the following:

**title**
    The project title. Used in header as well as the HTML title tag.

**logo**
    The path to the project logo. By default this is *_static/logo.svg*.

Example configuration entry (conf.py)::

    html_options = {
        'title': 'MyTitle',
        'logo': '_static/my-logo.svg',
    }

