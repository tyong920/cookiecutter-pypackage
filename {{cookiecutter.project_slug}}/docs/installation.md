# Installation

## Stable release
ZhengRen does not have a Python package warehouse like PyPI yet.
We do not assume the target you are going to deploy for now.
But install packages from VCS project urls is a commonly accpeted way.
- VCS project urls.
- Local project directories.
- Local or remote source archives.
To install {{ cookiecutter.project_name }}, run this command in your
terminal:

``` console
$ pip install git+https://... {{ cookiecutter.project_slug }}
```

This is the preferred method to install {{ cookiecutter.project_name
}}, as it will always install the most recent stable release.

If you don't have [pip][] installed, this [Python installation guide][]
can guide you through the process.

## From source

The source for {{ cookiecutter.project_name }} can be downloaded from
the [Github repo][].

You can either clone the public repository:

``` console
$ git clone git://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}
```

Or download the [tarball][]:

``` console
$ curl -OJL https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/tarball/master
```

Once you have a copy of the source, you can install it with:

``` console
$ pip install .
```

  [pip]: https://pip.pypa.io
  [Python installation guide]: http://docs.python-guide.org/en/latest/starting/installation/
  [Github repo]: https://github.com/%7B%7B%20cookiecutter.github_username%20%7D%7D/%7B%7B%20cookiecutter.project_slug%20%7D%7D
  [tarball]: https://github.com/%7B%7B%20cookiecutter.github_username%20%7D%7D/%7B%7B%20cookiecutter.project_slug%20%7D%7D/tarball/master
