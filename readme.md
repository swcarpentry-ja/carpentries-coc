### About this site

This site is built using [Read the Docs](https://github.com/rtfd/sphinx_rtd_theme).  See the [Getting Started](https://docs.readthedocs.io/en/latest/getting_started.html) section.

It uses the [Sphinx](https://github.com/rtfd/sphinx_rtd_theme) theme.

#### Required dependencies
```
pip install Sphinx sphinx_rtd_theme recommonmark
```

After installing Read the Docs packages and the Sphinx theme, build the site locally using

`$ make html`

Open the file `/_build/html/index.html` to preview the site locally.

After making changes, run `make html` again to view your changes.  You may need to delete the contents of the `/_build/`  directory before running `make html` to force the changes to refresh.

If new files or folders are added to the project, `index.rst` will need to be updated.

#### Site structure

The root level `index.rst` generates main categories the sidebar navigation.  Each sub-section is a folder in the `topic_folders` directory. Each folder within the `topic_folders` directory has its own `index.rst` file. These then expand into the subcategories in each directory.

Within each folder's `index.rst` file, the section heading is defined by a string of  `=` beneath it. Subheadings can be defined using `###` in each markdown file or by a heading with `-` under it in the `index.rst` file.


#### Additional information
This site is built from the master branch of [this repo](https://github.com/carpentries/handbook/). Changes can be previewed live [here](http://docs-src.carpentries.org/).  Changes to the [actual site](https://docs.carpentries.org/) will take several hours to go live.

If you are making experimental changes to live content please be sure to do so in another branch. Draft content can be added to the [drafts folder](https://github.com/carpentries/usersguides/tree/master/drafts) in the master branch without breaking anything.




