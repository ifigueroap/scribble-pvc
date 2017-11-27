scribble-pvc
============

Continuous previsualization for Racket's Scribble.

Simple script that uses [watchmedo](https://pypi.python.org/pypi/watchdog) to monitor changes in a single Scribble file. It manages documentation cross-references using the same
default parameters as the DrRacket IDE.

It requires Python's [watchdog](https://pypi.python.org/pypi/watchdog) package.

Usage
------

```bash
scribble-pvc [html|htmls|latex|pdf|latex-section|text|markdown] <file>
```

Installation
------------

* Install [watchmedo](https://pypi.python.org/pypi/watchdog) first
* Mark scribble-pvc script as executable and put it into your path.
