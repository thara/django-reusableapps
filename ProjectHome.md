## Reusable Django apps with setuptools ##

This is yet another approach on enabling Django to load reusable, pluggable, egg-based applications without changing the Django sourcecode. Think of plugins or components, e.g. django-registration, django-voting or django-tagging.

It uses [setuptools](http://peak.telecommunity.com/DevCenter/setuptools) for finding, handling and loading egg-based Python modules with a certain "[entry point](http://peak.telecommunity.com/DevCenter/setuptools#dynamic-discovery-of-services-and-plugins)" (`'django.apps'`).

[Egg-based](http://peak.telecommunity.com/DevCenter/PythonEggs) Python modules (a.k.a. eggs) are compressed packaged Python modules like Django apps. Every Django app can be converted to an egg distribution by using a [special setup.py](http://django-reusableapps.googlecode.com/svn/trunk/docs/setup-example.py) file.

Hope you like it, Jannis.

PS: Please don't miss the [documentation](http://api.rst2a.com/1.0/rst2/html?uri=http%3A//django-reusableapps.googlecode.com/svn/trunk/docs/overview.rst&style=zope) :)