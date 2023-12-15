# pyauthorizer

[![Actions Status][actions-badge]][actions-link]
[![PyPI version][pypi-version]][pypi-link]
[![PyPI platforms][pypi-platforms]][pypi-link]

<!-- SPHINX-START -->

<!-- prettier-ignore-start -->
[actions-badge]:            https://github.com/msclock/pyauthorizer/workflows/main/badge.svg
[actions-link]:             https://github.com/msclock/pyauthorizer/actions
[pypi-link]:                https://pypi.org/project/pyauthorizer/
[pypi-platforms]:           https://img.shields.io/pypi/pyversions/pyauthorizer
[pypi-version]:             https://img.shields.io/pypi/v/pyauthorizer
<!-- prettier-ignore-end -->

A simple authorizer for python project.

## Install

Package-built has uploaded to pypi and just install with the command:

```bash
pip install pyauthorizer
```

## Usage

To generate and validate a license, use the command:

```bash
pyauthorizer create -f simple -C password=1234567890  -O /tmp/license.json
pyauthorizer validate -f simple -C password=1234567890  -I /tmp/license.json
```

More command options can be listed by using `pyauthorizer --help`.

<!-- SPHINX-END -->
