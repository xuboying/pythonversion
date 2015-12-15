# pythonversion

## Check Python Version for script

### Usage
``` python
#!/usr/bin/env python
import pythonversion
pythonversion.PyVersionCheck(min="2.7.5",max="2.7.6")
print "foo"
```

>python -V
Python 2.7.10

>test.py

>The supported Python version for this script is from 2.7.5 to 2.7.6

``` python
#!/usr/bin/env python
import pythonversion
pythonversion.PyVersionCheck(min="2.7.5")
print "foo"
```

>python -V
Python 2.7.10

>test.py

>foo