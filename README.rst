Joomla 3 - Mobile-ready user-friendly content management
========================================================

`Joomla!`_ is an award-winning Content Management System (CMS) for
building websites as well as a Model-view-controller (MVC) Web
Application Development framework. Features include page caching to
improve performance, RSS feeds, printable versions of pages, news
flashes, blogs, polls, website searching, and language
internationalization.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- Joomla 3 configurations:
   
   - Installed from upstream source code to /var/www/joomla

- SSL support out of the box.
- `Adminer`_ administration frontend for MySQL (listening on port
  12322 - uses SSL).
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring Apache2, PHP, MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL: username **root**
-  Adminer: username **adminer**
-  Joomla: username **admin**


.. _Joomla!: http://www.joomla.org/
.. _TurnKey Core: https://www.turnkeylinux.org/core
.. _Adminer: http://www.adminer.org
