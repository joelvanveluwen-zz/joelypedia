# Generate configs

You can generate local configuration files to change how Jupyter works:

```text
jupyter notebook --generate-config
```

E.g. we can make the notebook accessible across a network

First generate a hashed password:

```text
from notebook.auth import passwd
passwd()
```

Take this hashed password and place in the 4th line below

```text
c.NotebookApp.ip = '*'
c.NotebookApp.port = 5555
c.Notebook.open_browser = False
c.NotebookApp.password = u'HASH'
```

