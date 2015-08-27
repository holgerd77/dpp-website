===========
dpp-website
===========

Website for ``django-public-project`` software, see:

* https://github.com/holgerd77/django-public-project


Old version needed translation with ``i18next`` (Javascript), but was given up due to poor Google search visability:

* http://i18next.com

Now static translated files are in ``en`` and ``de`` folders, initial domain visits on ``/`` are forwarded to
english version by ``Nginx`` config.

Development needs Python SimpleHTTPServer, run with ``python -m SimpleHTTPServer 8000`` from root directory.
