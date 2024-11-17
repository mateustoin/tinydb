Welcome to TinyDB!
==================

Welcome to TinyDB, your tiny, document oriented database optimized for your
happiness :)

>>> from tinydb import TinyDB, Query
>>> db = TinyDB('path/to/db.json')
>>> User = Query()
>>> db.insert({'name': 'John', 'age': 22})
>>> db.search(User.name == 'John')
[{'name': 'John', 'age': 22}]

User's Guide-test
------------

.. toctree::
   :maxdepth: 2

   intro
   getting-started
   usage

Extending TinyDB-test2
----------------

.. toctree::
   :maxdepth: 2

   Extending TinyDB <extend>
   TinyDB Extensions <extensions>

API Reference-test3
-------------

.. toctree::
   :maxdepth: 2

   api

Additional Notes-test4
----------------

.. toctree::
   :maxdepth: 2

   contribute
   changelog
   Upgrade Notes <upgrade>
