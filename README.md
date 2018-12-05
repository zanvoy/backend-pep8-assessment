## Cleanup on aisle 5: PEP8ify
For this assessment, you'll be cleaning up a program that functions properly,
but doesn't conform to the [PEP8](https://www.python.org/dev/peps/pep-0008/)
style guide. 

Your task is to update the program so that it is PEP 8 compliant. 

## Guidelines

- You should *not* remove comments. If a comment is too long, simply break it up into multiple lines.

- While there are several other PEP8 violations, we are only concerned with those reported by [flake8](http://flake8.pycqa.org/en/latest/)

- Do *not* modify anything in the `tests` directory

- The test suite (see below) must pass all tests.

## Running the test suite
There are several ways to run the test suite:

- Use automatic[ _test discovery_ within VSCode](https://code.visualstudio.com/docs/python/unit-testing).  You must enable this feature in your IDE.

- You can use [rerun](https://pypi.org/project/rerun/) run continually run unit tests:

```console
foo@bar:~ $ rerun "python -m unittest discover"
```

If you don't have rerun installed, you can run the test suite by itself:
```console
foo@bar:~ $ python -m unittest discover
```
