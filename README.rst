A browser based Role Playing Game
=================================

A Role Playing Game skeleton that use django and gevent. To start the server, run::

    $ python run.py

Example chat room from http://bitbucket.org/denis/gevent/src/tip/examples/webchat/chat/views.py

Tested on Opera, Firefox, Chrome.

Screenshot
==========

.. image:: http://batiste.dosimple.ch/django-rpg-screenshot.png


Install
=======

To install on a ubuntu distribution::

    $ sudo apt-get install python python-django python-pip git sqlite3
    $ sudo pip install gevent
    $ git clone git://github.com/batiste/django-rpg.git
    $ cd django-rpg/
    $ python manage.py syncdb
    $ python run.py


Features
========

    * The goal is to be massively multiplayer
    * Room Chat
    * Non player characters example
    * Basic example of spell
    * Map editing

Goals
=====

    * Write down a gameplay
    * Player experience, spells learning, combact mode, quests, crafting
    * Add a second layer on the map for objects
    * Get some graphics designer involved
