
.. include:: ../README.rst



Integration with GitHub actions
===============================

If there isn't one already,
create a *requirements.txt* file in your docs directory
(where your conf.py is)
and add the following dependency line::

    https://github.com/utlco/utl-sphinx-theme/archive/refs/heads/main.zip

This will install from the latest source. Alternatively, just
add the package name byt itself, which will be installed from PyPI::

    utl_sphinx_theme


Example GitHub workflow
-----------------------

.. literalinclude:: ../.github/workflows/push_docs.yml 
   :language: yaml
