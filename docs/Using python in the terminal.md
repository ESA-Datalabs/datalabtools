# Using python in the termial
In some cases the standard jupyterlab environment may use a different Python interpreter than the system's default.
Sometimes this version does not have an alias assigned and can thus not be launched from the terminal.

The python installation used by Jupyter can be found from a notebook via
```py

import os, sys
# this will display the path to the Python binary used in Jupyter
os.path.dirname(sys.executable)
>>>/opt/miniconda/bin
```
then an alias can be defined in the terminal, for example
```bash

alias python3.11='/opt/miniconda/bin'

```
then calling 'python3.11' inside the terminal will launch that version.
