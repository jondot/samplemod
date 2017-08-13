# Foobanzle


## Quick Start


## Developers

Set up a development environment
```
$ pip install -r requirements.txt
```

### Development

* Dependencies: list them in `requirements.txt`

### Release

* Dependencies: list them in `setup.py` under `install_requires`:

```python
install_requires=['peppercorn'],
```

Then:

```
$ make dist && make release
```
