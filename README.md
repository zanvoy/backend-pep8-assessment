# Assessment: PEP 8
For this assessment, you'll be cleaning up a program that functions propely,
but doesn't conform to the [PEP 8](https://www.python.org/dev/peps/pep-0008/)
style guide. 

Your task is to update the program so that it is PEP 8 compliant. 

## Guidelines

- You should *not* remove comments. If a comment is two long,  for instance,
  simply break it up into multiple lines.

- While there are several other PEP 8 violations, we are only concerned with
  those reported by [flake8](http://flake8.pycqa.org/en/latest/)

- You should *not* be modifying anything in the `tests` directory

- The test suite (see below) must pass

## Running the test suite
You can use [rerun](https://pypi.org/project/rerun/) run continually run unit
tests:

```console
foo@bar:~ $ rerun "python -m unittest discover"
```

If you don't have rerun installed, you can of course run the test suite by itself:
```console
foo@bar:~ $ python -m unittest discover
```