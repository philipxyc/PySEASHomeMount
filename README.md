# PySEASHomeMount
Mount UPenn SEAS home directory by Python

Useful to mount the SEAS home dir in library PCs (e.g. public computers in Van Pelt library)

Code is super simple:

```
import os
os.system(r"net use g: \\smb.seas.upenn.edu\xyc /user:xyc")
```
