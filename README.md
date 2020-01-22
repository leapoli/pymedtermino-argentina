# pymedtermino-argentina

Modificación de pymedtermino para incorporar el release de SNOMED-CT ArgentinaEdition. Forkeado de:
https://bitbucket.org/jibalamy/pymedtermino/src/default/

Instalación:

```bash
python3 setup.py build --snomedct {RUTA A CARPETA RAIZ SNOMEDCT}
```

Uso:

```python
import pymedtermino
pymedtermino.LANGUAGE = 'es'
from pymedtermino.snomedct import *
SNOMEDCT.search("sumar")
```