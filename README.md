UAVCAN v0 stack in Python
==========================

[![Travis CI](https://travis-ci.org/UAVCAN/pyuavcan.svg?branch=master)](https://travis-ci.org/UAVCAN/pyuavcan)
[![Gitter](https://img.shields.io/badge/gitter-join%20chat-green.svg)](https://gitter.im/UAVCAN/general)

Python implementation of the [UAVCAN v0 protocol stack](http://uavcan.github.io).

UAVCAN is a lightweight protocol designed for reliable communication in aerospace and robotic applications via CAN bus.

## Documentation

* [UAVCAN v0 website](http://uavcan.github.io)
* [UAVCAN forum](https://forum.uavcan.org)
* [Pyuavcan documentation and tutorials](http://uavcan.org/Implementations/Pyuavcan/)

## Installation

Compatible Python versions are 2.7 and 3.3 and newer.
If the library is used with Python 3, which is recommended, it does not require any additional dependencies.
If Python 2.7 is used, additional dependencies are needed - refer to `setup.py` for more info.

```bash
pip install uavcan
```

## Development

### Automatic deployment to PyPI

In order to deploy to PyPI via CI, do this:

1. Update the version number in `version.py`, e.g. `1.0.0`, and commit before proceeding.
2. Create a new tag with the same version number, e.g. `git tag -a 1.0.0 -m "My release 1.0.0"`
3. Push to master.

### Code style

Please follow the [Zubax Python Coding Conventions](https://kb.zubax.com/x/_oAh).
