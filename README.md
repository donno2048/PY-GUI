# PY-GUI

Create a pygame session for specific functions

## install

From Pypi:

`python -m pip install PY-GUI`

From GitHub:

`python -m pip install git+https://github.com/donno2048/PY-GUI`

## Usage

You can use the demo one by running:

```bat
py -m PY-GUI
```

Or just `PY-GUI`

Or you can run a custom one from within Python, for example:

```py
from PY_GUI import Main
def parse(text: str) -> str:
  return text * 2
Main(parse, name = "Duplicate")
```
