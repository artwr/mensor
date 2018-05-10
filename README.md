# Mensor
[![Build Status](https://travis-ci.org/airbnb/mensor.svg?branch=master)](https://travis-ci.org/airbnb/mensor)
[![Documentation Status](https://readthedocs.org/projects/mensor/badge/?version=latest)](http://mensor.readthedocs.io/en/latest/?badge=latest)
![Project Status](https://img.shields.io/pypi/status/mensor.svg)
[![PyPI Version](https://img.shields.io/pypi/v/mensor.svg)](https://pypi.org/project/mensor/)
![Python Versions](https://img.shields.io/pypi/pyversions/mensor.svg)
[![License](https://img.shields.io/github/license/airbnb/mensor.svg)](https://github.com/airbnb/mensor/blob/master/LICENSE)

Mensor is a graph-based computation engine for computing measures and metrics.

- **Documentation:** http://mensor.readthedocs.io
- **Source:** https://github.com/airbnb/mensor
- **Bug reports:** https://github.com/airbnb/mensor/issues

Among other things, Mensor:

- defines a new grammar for extracting measures and metrics that is designed to
  be intuitive and capable (it can do almost(?) anything that makes sense to
  do with metrics and measures).
- makes measure and metric definitions explicit and shareable, and their
  computations transparent and reproducible.
- allows multiple data sources to be stitched together on the fly without users
  having to explicitly write the code / query required to join the data sources.
- is agnostic as to how data is stored or accessed, and new data backends are
  relatively simple to write.
- allows for local ad-hoc definitions of additional data sources for exploration
  by data scientists or other technically minded folk, decoupling it from
  deployment into production services.
