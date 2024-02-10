## offline-pyvis - a Python library for visualizing networks without internet connection

Forked from: [pyvis](https://github.com/WestHealth/pyvis). With the aim of being able to run Pyvis without reaching out to external sites.

## Description

offline-pyvis is built around [visjs](http://visjs.org/), a JavaScript visualization library.

## Documentation

Pyvis' full documentation can be found at http://pyvis.readthedocs.io/en/latest/

## Installation

```bash
python setup.py install
```

## Dependencies

[networkx](https://networkx.github.io/)

[jinja2](http://jinja.pocoo.org/)

[ipython](https://ipython.org/ipython-doc/2/install/install.html)

[jsonpickle](https://jsonpickle.github.io/)

### Test Dependencies

[selenium](https://www.selenium.dev/documentation/webdriver/)

[numpy](https://numpy.org/install/)

## Quick Start

The most basic use case of a pyvis instance is to create a Network object and invoke methods:

```python
from offline_pyvis.network import Network

g = Network()
g.add_node(0)
g.add_node(1)
g.add_edge(0, 1)
g.show("basic.html")
```

## TODO

- [ ] Remove options for remote content
