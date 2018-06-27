# mozilla-version

[![Build Status](https://travis-ci.org/mozilla-releng/mozilla-version.svg?branch=master)](https://travis-ci.org/mozilla-releng/mozilla-version) [![Coverage Status](https://coveralls.io/repos/github/mozilla-releng/mozilla-version/badge.svg?branch=master)](https://coveralls.io/github/mozilla-releng/mozilla-version?branch=master)


Process Firefox versions numbers. Tell whether they are valid or not, whether they are nightlies or regular releases, whether this version precedes that other.

## Get the code

Just install it from pip:

```sh
pip install mozilla-version
```


## Hack on the code
First, you need `python>=3.5.0`.

```sh
virtualenv3 venv3   # create the virtualenv in ./venv3
. venv3/bin/activate    # activate it
git clone https://github.com/mozilla-releng/mozilla-version
cd mozilla-version
pip install mozilla-version
```
