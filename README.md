# PyPI repository

Static PyPI repository for personal Python packages. Built with [dumb-pypi](https://github.com/chriskuehl/dumb-pypi) and hosted with GitHub Pages.

## Web interface

See https://tiagoshibata.github.io/PyPI

## Updating the static pages with new packages

Run on the repository root:

```
dumb-pypi --package-list <(ls packages) \
    --packages-url https://raw.githubusercontent.com/tiagoshibata/PyPI/gh-pages/packages \
    --output-dir .
```
