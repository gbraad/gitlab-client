Simple GitLab client
====================

.. WIP ..

Installation
------------

From source:
::

    $ sudo pip install -r requirements.txt --allow-all-external && sudo python setup.py install

From pypi:
::

    $ sudo pip install gitlab-client


Create a ``~/.gitlab.cfg`` file with the following content:

::

    [default]
    host=https://gitlab.com
    token=
    project=gbraad/gitlab-client

Authors
-------

+-----------------------------------------+
| |"Gerard Braad"|                        |
+=========================================+
| `@gbraad <https://twitter.com/gbraad>`_ |
+-----------------------------------------+

.. |"Gerard Braad"| image:: http://gravatar.com/avatar/e466994eea3c2a1672564e45aca844d0.png?s=60
   :target: http://gbraad.nl