# Overview

<table>
<tbody>
<tr class="odd">
<td>tests</td>
<td><div class="line-block"><a href="https://travis-ci.org/rtibbles/delta-crdt"><img src="https://api.travis-ci.org/rtibbles/delta-crdt.svg?branch=master" alt="Travis-CI Build Status" /></a> <a href="https://ci.appveyor.com/project/rtibbles/delta-crdt"><img src="https://ci.appveyor.com/api/projects/status/github/rtibbles/delta-crdt?branch=master&amp;svg=true" alt="AppVeyor Build Status" /></a> <a href="https://requires.io/github/rtibbles/delta-crdt/requirements/?branch=master"><img src="https://requires.io/github/rtibbles/delta-crdt/requirements.svg?branch=master" alt="Requirements Status" /></a><br />
<a href="https://codecov.io/github/rtibbles/delta-crdt"><img src="https://codecov.io/gh/rtibbles/delta-crdt/branch/master/graphs/badge.svg?branch=master" alt="Coverage Status" /></a></div></td>
</tr>
<tr class="even">
<td>package</td>
<td><div class="line-block"><a href="https://pypi.org/project/delta_crdt"><img src="https://img.shields.io/pypi/v/delta_crdt.svg" alt="PyPI Package latest release" /></a> <a href="https://pypi.org/project/delta_crdt"><img src="https://img.shields.io/pypi/wheel/delta_crdt.svg" alt="PyPI Wheel" /></a> <a href="https://pypi.org/project/delta_crdt"><img src="https://img.shields.io/pypi/pyversions/delta_crdt.svg" alt="Supported versions" /></a> <a href="https://pypi.org/project/delta_crdt"><img src="https://img.shields.io/pypi/implementation/delta_crdt.svg" alt="Supported implementations" /></a><br />
<a href="https://github.com/rtibbles/delta-crdt/compare/v0.0.0...master"><img src="https://img.shields.io/github/commits-since/rtibbles/delta-crdt/v0.0.0.svg" alt="Commits since latest release" /></a></div></td>
</tr>
</tbody>
</table>

A Python implementation of Delta CRDTs

  - Free software: MIT license

## Installation

    pip install delta_crdt

You can also install the in-development version with:

    pip install https://github.com/rtibbles/delta-crdt/archive/master.zip

## Documentation

To use the project:

``` python
import delta_crdt
```

## Development

To run the all tests run:

    tox

Note, to combine the coverage data from all the tox environments run:

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 90%" />
</colgroup>
<tbody>
<tr class="odd">
<td>Windows</td>
<td><pre><code>set PYTEST_ADDOPTS=--cov-append
tox</code></pre></td>
</tr>
<tr class="even">
<td>Other</td>
<td><pre><code>PYTEST_ADDOPTS=--cov-append tox</code></pre></td>
</tr>
</tbody>
</table>
