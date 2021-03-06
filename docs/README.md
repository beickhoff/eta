# Eta Documentation

## Building

### Prerequisites

- Python
- [pip](https://pip.pypa.io/en/stable/installing/)
  - Python 2 >= 2.7.9 or Python 3 >= 3.4 automatically have `pip` installed.

```
$ pip install Sphinx sphinx_rtd_theme
```

### Build

```
$ cd highlight
$ python setup.py install
$ cd ..
$ make clean html
```

## Development

It's faster to have automated rebuilds via Gulp during development.

### Prerequisites

- Node.js
- Gulp

```
npm install --global gulp-cli # May require 'sudo'
npm install
```

### Develop

```
$ gulp reload
```
