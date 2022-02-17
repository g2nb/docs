# Release Notes
--- 

## GenePattern Notebook Repository

Release updates for the [GenePattern Notebook Repository](https://notebook.genepattern.org/).

### GenePattern Notebook Repository 20.05 (May 28, 2020)
- Updated to genepattern-notebook 20.05, nbtools 20.05 and genepattern-python 20.05.

### GenePattern Notebook Repository 20.03 (March 6, 2020)
- Bug fix in preview image generation.
- Updated to nbtools 20.03 and jupyter-wysiwyg 20.03.

### GenePattern Notebook Repository 20.01 (January 7, 2020)
- Now includes the [Globus](https://www.globus.org/) client. Documentation on how to connect your workspace to Globus is available [here](https://gpnotebook-website-docs.readthedocs.io/en/latest/programmatic/#globus-connect).
- Several R packages including Seurat, scater and dyplr are now included by default.
- Updated to [nbtools](#notebook-tools-manager) 20.01 and [igv-jupyter](https://github.com/igvteam/igv-jupyter) 0.9.8, which include several bug fixes.

### GenePattern Notebook Repository 19.11 (November 22, 2019)
- Workshop notebooks now display in their own table inside the Notebook Library tab.
- Updated to ccal-noir 2.7.1 to fix an incompatibility in that library with the latest version of numpy.
- Bug fix for notebook sharing emails.

### GenePattern Notebook Repository 19.10 (October 28, 2019)
- Pinned public notebook tags now display an optional description.
- Updated to [JupyterHub 1.0](https://github.com/jupyterhub/jupyterhub/blob/master/docs/source/changelog.md#100-2019-05-03).
- Updated to latest version of [nbtools](#notebook-tool-manager) and [jupyter-wysiwyg](#rich-text-editor).

### GenePattern Notebook Repository 19.09.2 (October 4, 2019)
- Updated to [Jupyter 6](https://jupyter-notebook.readthedocs.io/en/stable/changelog.html)

### GenePattern Notebook Repository 19.09 (September 17, 2019)
- Updated to latest version of [nbtools](#notebook-tool-manager), [jupyter-wysiwyg](#rich-text-editor) and [genepattern-notebook](#genepattern-notebook-extension)
- Updated to [Plotly 4.0](https://medium.com/plotly/plotly-py-4-0-is-here-offline-only-express-first-displayable-anywhere-fc444e5659ee) in the Python 3.7 kernel

### GenePattern Notebook Repository 19.08 (August 19, 2019)
- Update the notebook preview images anytime a public notebook is updated
- Graceful failure of GenePattern features added for single-user work and non-Python kernels
- R kernel added to the Docker image
- Support for MySQL added to the public notebooks service

### GenePattern Notebook Repository 19.07 (July 19, 2019)
- New GenePattern theme added.
- Public notebooks now sorted by latest by default
- Added login/register button to preview page.
- Improved organization of Community notebooks.
- Added Workshop Notebooks tab.
- Added optional email notification when a new notebook is published.
- Added terms of use.
- Bug fixes.

### GenePattern Notebook Repository 19.05 (May 7, 2019)
- Improved notebook preview functionality.
- Updated Python 3.7 environment with new Python packages
- Added repository start and stop scripts.
- Notebook Library tab will now remember user selection.
- Improved Dockerized architecture.
- Added support for SwarmSpawner.
- Improved theme support.
- Bug fixes.

### GenePattern Notebook Repository 19.04 (April 5, 2019)
- Added support for user-installed nbextensions.
- Formalized webtour notebook extension.
- Formalized repository notebook extension.
- Added support for newer versions of JupyterHub.
- Bug fixes.

### GenePattern Notebook Repository 19.02 (February 14, 2019)
- Improved notebook preview functionality.
- Added the ability to comment on public notebooks.
- Added ability to share with collaborators from within a notebook.
- New repository introductory tour.
- Loading indicator while generating notebook preview.
- Bug fixes.

### GenePattern Notebook Repository 18.11 (November 13, 2018)
- Added "My Notebooks" to the notebook library.
- Renamed Public Notebooks tab to Notebook Library.
- Added URL to get a copy of the notebook and open it all in a single link click.
- When opening a public notebook, show the user where it was copied to.
- Bug fixes.

### GenePattern Notebook Repository 18.09 (September 14, 2018)
- Notify users when others are editing a shared notebook.
- Added edit sharing button to dialog in public notebooks tab.
- Restructure notebook sharing to shared by/with me.
- Add sharing invite badge to public notebooks tab.
- Added Human Cell Atlas theme.
- Bug fixes.

### GenePattern Notebook Repository 18.07 (July 24, 2018)

-   Added the ability for users to easily share notebooks with others.
-   Improved integration with JupyterHub's Services API.
-   Admins now have an interface for pinning and protecting tags..
-   Improved preview functionality for the public notebooks.
-   Added support for the [NDEx2 API](http://www.ndexbio.org/)

### GenePattern Notebook Repository 18.03 (March 23, 2018)

-   Tagging functionality added to the Public Notebooks tab.
-   Public Notebooks tab UI redesign.
-   Preview functionality added to public notebooks.

### GenePattern Notebook Repository 18.01 (January 19, 2018)

-   Upgraded repository to JupyterHub 0.8, Jupyter 5.3 and ipywidgets 7.
-   Updated repository containers to include R 3.4.3 and rpy2 package.
    See [R Support documentation](http://genepattern-notebook.org/programmatic/#r-support) for more details.
-   Updated spawner and authenticator plugins to latest JupyterHub API.

### GenePattern Notebook Repository 17.12 (December 8, 2017)

-   Improved compute node scaling and performance.
-   Public notebook service port change.

### GenePattern Notebook Repository 17.07 (July 27, 2017)

-   Support for Python environment versioning added.
-   Python 3 kernel updated to Python 3.6.
-   GenePattern Notebook extension updated to v0.6.4.
-   GenePattern Python library updated to v1.3.0.
-   Scientific computing libraries updated.
-   Deprecated Python 2 kernel.

### [GenePattern Notebook Repository 17.05](/notebook-repo-17.05/) (May 15, 2017)

-   Notebook sharing functionality.
-   Infrastructure update (AWS hosting).

------------------------------------------------------------------------

## GenePattern Notebook Extension

Release updates for the [GenePattern Notebook nbextension](https://github.com/genepattern/genepattern-notebook). Install using
`pip install genepattern-notebook` or
`conda install -c genepattern genepattern-notebook`.
        
### GenePattern Notebook 20.05 (May 28, 2020)
- Fixed a bug where checking for password parameters was erroneously case insensitive
- Removed custom values for job memory parameters

### GenePattern Notebook 19.09 (September 17, 2019)
- Added support for HTML in module and parameter descriptions
- Cell templates moved to "+" origin

### GenePattern Notebook 19.08 (August 12, 2019)
- Cell template improvements
- Login message fix
- Graceful failure implemented when operating with a non-Python kernel

### GenePattern Notebook 19.07 (July 16, 2019)
- Build improvements and bug fixes

### GenePattern Notebook 19.05 (May 31, 2019)
- Updated release architecture
- New versioning scheme

### GenePattern Notebook 0.8.6 (April 10, 2019)
- Bug fix release.

### GenePattern Notebook 0.8.5 (February 13, 2019)
- Bug fix release.

### GenePattern Notebook 0.8.4 (January 10, 2019)
- Bug fix release.
- GenePattern Notebook 0.8.3 (December 21, 2018)
- Removed genepattern.broadinstitute.org from the list of servers.
- Added cell templates.
- Support for output files in subdirectories for GPJob widget.

### GenePattern Notebook 0.8.2 (October 31, 2018)
- Default server changed to GenePattern Cloud.
- File kinds can include a wildcard character.
- Compatibility fix for latest version of ipywidgets.
- Combined the gear menus in analysis/job cells.
- Warning message added to orphaned analysis cells
- Jobs that output index.html will display it in an iframe
- Bug fixes.

### GenePattern Notebook 0.8.1 (September 17, 2018)
- Bug fix release.
- GenePattern Notebook 0.8.0 (August 16, 2018)
- Refactored to support nbtools 0.2.0.
- Moved UI Builder and UI Output functionality to nbtools package.
- Support for output files in subdirectories for GPJob widget.

### GenePattern Notebook 0.7.3 (July 9, 2018)
- Added new UI Output widget.
- Added option to not add UI Builder functions to the Notebook Tool Manager.
- Updated to latest GenePattern URLs.
- Better support for multiple widgets in combined cells.
- Bug fixes.

### GenePattern Notebook 0.7.2 (May 30, 2018)

-   Analysis and job widgets will now appear together in the same cell
    by default.
-   UI Builder cells and outputs will now appear together in the same
    cell.
-   Added a new widget GPUIOutput intended to visually display
    programmatic output.
-   An icon has been added to job widgets, indicating their sharing
    status.
-   Bug fixes.

### GenePattern Notebook 0.7.1 (March 21, 2018)

-   UI Builder file upload added.
-   Double-click to edit file parameter functionality added.
-   Added parameter reset to analysis widgets.
-   Bug fixes.

### GenePattern Notebook 0.7.0 (February 16, 2018)

-   GenePattern workflow execution interface added. For more information
    see the Workflow Execution documentation.
-   Support for job result syntax added to GenePattern analyses. This is
    a simple syntax for specifying GenePattern analysis inputs based on
    the output of of upstream jobs. For more information see the Job
    Result Syntax documentation.
-   Added support for renaming, hiding or overriding the output variable
    in the UI Builder.
-   Major refactoring of code structure and file names.
-   Updated Javascript code to ES6 standard.
-   New webpack build process added.
-   Bug fixes.

### GenePattern Notebook 0.6.8 (December 8, 2017)

-   UI Builder now has type-specific support for file, number, password
    and bool parameters.
-   Placeholder job cells added.
-   Job cells can now send a browser notification when a job completes.
-   Added the ability to programmatically set the output variable in the
    UI Builder.
-   Add ability to pass in custom function import path in the UI
    Builder.
-   Bug fixes.

### GenePattern Notebook 0.6.7 (November 8, 2017)

-   Improved UI Builder customization and features.
-   Usability improvements.
-   Bug fixes.

### GenePattern Notebook 0.6.6 (October 13, 2017)

-   UI Builder support for choice parameters and dynamic configuration.
-   Support for ipywidgets 7.
-   Bug fixes.

### GenePattern Notebook 0.6.5 (September 15, 2017)

-   Beta release of the UI Builder.
-   Package restructuring to better fit Python standards.
-   Bug fixes.

### GenePattern Notebook 0.6.4 (July 27, 2017)

-   Added support for parameter groups
-   UI Builder alpha release

### GenePattern Notebook 0.6.3 (June 28, 2017)

-   Bug fix release for low-numbered LSIDs

------------------------------------------------------------------------

## GenePattern Python Library

Release updates for the GenePattern Python Library. Install using
`pip install genepattern-python` or
`conda install -c genepattern genepattern-python`.

### GenePattern Python 20.05 (May 28, 2020)
- CLS file support added to gp.data package

### GenePattern Python 1.4.5 (July 31, 2019)
- Updated release to the latest PIP standards

### GenePattern Python 1.4.2 (September 17, 2018)
- Bug fixes.

### GenePattern Python 1.4.1 (February 16, 2018)

-   CLS file creation function added to gp.data package.
-   JSON serialization added to GPFile object.

### GenePattern Python 1.4.0 (December 8, 2017)

-   Added write\_gct() and write\_odf(), which write pandas dataframes
    to disk in GCT or ODF formats, respectively.
-   ODF() and GCT() now directly create pandas dataframes from the
    loaded data.
-   Added get\_recent\_jobs() function to retrieve a list of recently
    launched jobs.
-   Dropped Python 2 support.

### GenePattern Python 1.3.1 (September 15, 2017)

-   Support for local and remote LSID authorities when generating
    GenePattern modules from Python scripts.

### GenePattern Python 1.3.0 (July 27, 2017)

-   Functionality added for creating GenePattern modules from Python
    (gp.modules)

------------------------------------------------------------------------

## Notebook Tool Manager

Release updates for the Notebook Tool Manager. Install using
`pip install nbtools` or `conda install -c genepattern nbtools`.

### Notebook Tool Manager 20.05 (May 28, 2020)
- Added support for multi-select parameters

### Notebook Tool Manager 20.03 (March 6, 2020)
- Bug fix in handling of file list parameters.

### Notebook Tool Manager 20.01 (January 2, 2020)
- Bug fixes for the R UI Builder.

### Notebook Tool Manager 19.10 (October 28, 2019)
- Bug fix for the build_ui decorator.

### Notebook Tool Manager 19.09.1 (September 26, 2019)
- Critical bug fix for UI Builder

### Notebook Tool Manager 19.09 (September 17, 2019)
- Added better support for defining and importing UI Builder widgets from a Python module
- Implemented support for large file uploads in the UI Builder
Added support for HTML in widget and parameter descriptions

### Notebook Tool Manager 19.07 (July 16, 2019)
- Adding r_build_ui magic (UI Builder support for R cells)
- Condensed display for UI Builder widgets with no parameters
- R support critical fix
- Dropping support for Python 3.5

### Notebook Tool Manager 19.05 (May 31, 2019)
- Updated release architecture
- New versioning scheme
- Added prototype support for R in the UI Builder

### Notebook Tool Manager 0.2.6 (April 12, 2019)
- Bug fix release

### Notebook Tool Manager 0.2.5 (April 9, 2019)
- Allow HTML in UIOutput status
- Hide custom value option in dropdowns by default
- Bug fixes

### Notebook Tool Manager 0.2.4 (February 13, 2019)
- Added ability to send text to UI Builder widgets from markdown cells or upstream output.
- Added custom status indicator and update call for UIOutput widgets.
- Added optional/required parameter annotation
- Fixed bug where some inputs strings would incorrectly be treated as numbers

### Notebook Tool Manager 0.2.3 (October 31, 2018)
- Bug fix release

### Notebook Tool Manager 0.2.2 (December 21, 2018)
- File kinds now support wildcards *
- Compatibility fix for newer versions of Jupyter
- Bug fixes

### Notebook Tool Manager 0.2.1 (September 17, 2018)
- Event hooks added to UI Builder
- Bug fixes

### Notebook Tool Manager 0.2.0 (August 16, 2018)
- Moved UI Builder functionality from the GenePattern Notebook package to nbtools
- Moved UI Output functionality from the GenePattern Notebook package
- Added support for output files in subdirectories
- Added id and events parameters to the UI Builder

### Notebook Tool Manager 0.1.7 (April 3, 2018)
-   Changed nbextension installation to match new Jupyter 5.3+ standard.

### Notebook Tool Manager 0.1.6 (December 8, 2017)

-   Focus is now automatically given to the search/filter box when the
    toolbox is opened.

### Notebook Tool Manager 0.1.5 (October 19, 2017)

-   Button label for for Jupyter &gt;= 5.1.0.

------------------------------------------------------------------------

## Rich Text Editor

Release updates for the Rich Text Editor. Install using
`pip install jupyter-wysiwyg` or
`conda install -c genepattern jupyter-wysiwyg`.

### Rich Text Editor 20.03 (March 6, 2020)
- Fixed bug where buttons wouldn't disappear as expected.

### Rich Text Editor 19.10 (October 28, 2019)
- Bug fix for double-clicking erroneously displaying markdown text
- Bug fix for markdown cells erroneously being changed to code

### Rich Text Editor 19.08 (August 25, 2019)
- Upgraded the rich text widget to TinyMCE 5
- Added "Rich Text" pseudo-cell type

### Rich Text Editor 19.07 (July 31, 2019)
- Updated PIP deploy to the latest standards

### Rich Text Editor 19.05 (May 31, 2019)
- Updated conda packaging
- Updated versioning scheme

### Rich Text Editor 0.1.9 (December 4, 2018)
- Fixed a bug in the install process for Jupyter 5.3.

### Rich Text Editor 0.1.8 (May 3, 2018)

-   Added LICENSE.txt file to PyPI source archive.

### Rich Text Editor 0.1.7 (April 26, 2018)

-   Fixed an issue that could call installation to fail due to a bug in
    setuptools.

### Rich Text Editor 0.1.6 (April 3, 2018)

-   Changed nbextension installation to match new Jupyter 5.3+ standard.
-   Bug fix for behavior when switching between command and edit modes.

### Rich Text Editor 0.1.5 (February 16, 2018)

-   Bootstrap style support added to the editor.
