# How to contribute to Hyperbard's `tutorials`

Thanks for being willing to contribute to Hyperbard's `tutorials`! Here are some
resources to get you started:

- Check out [open issues](/issues) in case you are looking for things
  to tackle.

**When contributing code, please be aware that your contribution will
fall under the terms of the [license](https://github.com/hyperbard/tutorials/blob/main/LICENSE).**

## Pull requests

If you propose some changes, a pull request is the easiest way to
integrate them. Please be mindful of the coding conventions (see below)
and [write good commit messages](https://cbea.ms/git-commit/).

## Coding conventions

Above all, consider that this is *open source software*. It is meant
to be used and extended by many people. Be mindful of them by making
your code look nice and appealing to them. We cannot build upon some
module no one understands.

As a way to obtain some consistency in all contributions, your code
in Python scripts should at least be conform with [PEP
8](https://www.python.org/dev/peps/pep-0008/).

```console
$ flake8 script.py
```

PEP8-conforming code formatting in Jupyter Lab can be achieved by
loading the `nb_black` extension installed with the repository's
requirements before executing the Jupyter Notebook code: 
%load_ext lab_black.
