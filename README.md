# `tbl` - Readme

Simple table printing for Python CLI tools

## How to install

```
$ python setup.py install
```

## Development

```
$ virtualenv --no-site-packages venv && source venv/bin/activate
$ python setup.py develop
```

And then run the tests with:

```
$ python setup.py test
```

If you need test dependencies for writing new tests, you can install them with:

```
$ pip install .[test]
```
