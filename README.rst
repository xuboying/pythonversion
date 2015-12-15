pythonversion
=============

Check Python Version for script
-------------------------------

Usage
~~~~~

.. code:: python

    #!/usr/bin/env python
    import pythonversion
    pythonversion.PyVersionCheck(min="2.7.5",max="2.7.6")
    print "foo"

test.py The supported Python version for this script is from 2.7.5 to
2.7.6

.. code:: python

    #!/usr/bin/env python
    import pythonversion
    pythonversion.PyVersionCheck(min="2.7.5")
    print "foo"

test.py foo
