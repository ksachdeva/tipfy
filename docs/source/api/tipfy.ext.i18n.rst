tipfy.ext.i18n
==============
.. module:: tipfy.ext.i18n

.. toctree::
   :maxdepth: 5

This module provides internationalization utilities: a translations store,
a middleware to set locale for the current request and functions to translate
or localize strings and dates.

I18nMiddleware
--------------
.. autoclass:: I18nMiddleware

Translation functions
---------------------
.. autofunction:: set_locale
.. autofunction:: gettext
.. autofunction:: ngettext
.. autofunction:: lazy_gettext
.. autofunction:: lazy_ngettext

Date and time functions
-----------------------
.. autofunction:: get_tzinfo
.. autofunction:: format_date
.. autofunction:: format_datetime
.. autofunction:: format_time