# cthreading

cthreading implements Python 2 Lock, RLock, and Condition in C.  Like
[pthreading](https://github.com/oVirt/pthreading), without the undefined
behavior.

## Usage

```python
import cthreading
cthreading.monkeypatch()
```

## Hacking

Installing development packages:

```
pip install pytest
pip install yappi==0.93
dnf install python-test
```

Building and running the quick tests:

```
make
```

Before submiting patches, run the entire Python regression tests suite:

```
make regrtest
```

Check the `Makefile` for more info.
