### About this site

This site is built using [Read the Docs](https://github.com/rtfd/sphinx_rtd_theme).  See the [Getting Started](https://docs.readthedocs.io/en/latest/getting_started.html) section.

It uses the [Sphinx](https://github.com/rtfd/sphinx_rtd_theme) theme.

## Required dependencies
```
pip install Sphinx sphinx_rtd_theme recommonmark
```

After installing Read the Docs packages and the Sphinx theme, build the site locally using

`$ make html`

Open the file `/_build/html/toc.html` to preview the site locally.

After making changes, run `make html` again to view your changes.  You may need to delete the contents of the `/_build/`  directory before running `make html` to force the changes to refresh.

If new files or folders are added to the project, `toc.rst` will need to be updated.




