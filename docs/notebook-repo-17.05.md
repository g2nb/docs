# GenePattern Notebook Repository 17.05
*Released May 25, 2017*
--- 

The [GenePattern Notebook Repository]() has been updated with improved server infrastructure and scaling capabilities. Click on the links below for details on the updates.

- New User Features
- Bug Fixes and Enhancements
- Programmer Support

## New User Features
Users now have the ability to publicly share their notebooks on the GenePattern Notebook Repository, and to run notebooks shared by others.

## Browsing Public Notebooks
- To view the available notebooks, click the "Public Notebooks" tab and browse through the list.
- To obtain a copy and run the shared notebook, click the notebook in the list and then select "Get a Copy" on the confirmation dialog that pops up. This will make a copy of the chosen notebook in your current directory, accessible by clicking on the Files tab.
- To run the notebook, click the "Click here if you would like to open this notebook" link in the resulting dialog, or go back to the "Files" tab and run the notebook as normal from there.

![image](http://genepattern.org/uploaded/content_notebook-tab.jpg)

## Publicly Sharing Notebooks
- To publicly share a notebook, click the checkbox next to that notebook and then click the "Publish" button on the toolbar above.
- This will open a dialog with a short form, prompting you to enter the author's name, the quality and a brief description. Fill out this information and then click the "Publish" button on the dialog.
- Your notebook should now be available to the public and should appear on the "Public Notebooks" tab. The published version of the notebook is checkpoint of the notebook at the time it was published. Any changes you make to the notebook in the future are not copied over to the published version unless you explicitly choose to update the notebook in the public repository.

![image](http://genepattern.org/uploaded/content_share-notebook.jpg)

## Updating or Removing a Public Notebook
- You can update or remove a notebook that you have made public by first clicking the checkbox next to the notebook and then clicking the "Publish" button.
- In the dialog that comes up you will have the option to edit any of the notebook's metadata, such as author name, description, etc.
- To update or remove the notebook, click the "Update" or "Unpublish" buttons, respectively.

## Bug Fixes and Enhancements
- The GenePattern Notebook Repository's memory and compute capacity now scale to handle higher server usage. Infrastructure is now running on Amazon Web Services (AWS).
- Improvements have been made to backing up user notebooks.
- The repository now supports JupyterHub 0.7.2.

## Programmer Support
- Python packages currently supported in the GenePattern Notebook Repository include those in the Anaconda distribution. Of particular note are: 
    - genepattern-python v1.2.3
    - ipywidgets v5.1.5
    - jupyter-wysiwyg v0.1.1
    - matplotlib v1.5.1
    - nbtools v0.1.3
    - numpy v1.10.4
    - pandas v0.18.1
    - scikit-learn v0.17.1
    - scipy v0.17.1
    - seaborn v0.7.0
- If you need a package that isn't currently supported, please [contact us](contact/) with the request.