# Using python in the termial
The standard jupyterlab environment runs on python3.11 currently.
When one wants to start a script from the terminal, the standard jupyterlab datalabs does not include an alias for this python version.
The python installation can be found from a notebook via
```bash

import os, sys
os.path.dirname(sys.executable)
>>>/opt/miniconda/bin
```
then an alias can be defined in the terminal, for example
```bash

alias python3.11='/opt/miniconda/bin'

```
then python can be launched from inside the terminal by calling the alias.
