### pypy
---
http://pypy.org/

https://bitbucket.org/pypy/pypy

```
set PYPY_GC_MAX_DELTA=200MB
pypy --jit loop_longevity=300 ../../rpython/bin/rpython -Ojit targetpypystandalone
set PYPY_GC_MAX_DELTA=
PYTHONPATH=../.. ./pypy-c ../tool/build_cffi_imports.py

```

```
```

```
```


