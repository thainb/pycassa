.. _installing:

Installing
==========

easy_install
------------
If you have :file:`easy_install` installed, you can simply do:

.. code-block:: bash

  $ easy_install pycassa

This will also install the Thrift python bindings automatically.

Manual Installation
-------------------
Make sure that you have Thrift's python bindings installed:

.. code-block:: bash

  $ easy_install thrift05

You can download a release from 
`github <http://github.com/pycassa/pycassa/downloads>`_
or check out the latest source from github::

  $ git clone git://github.com/pycassa/pycassa.git

You can simply copy the pycassa directory into your project, or
you can install pycassa system-wide:

.. code-block:: bash

  $ cd pycassa/
  $ sudo python setup.py install
