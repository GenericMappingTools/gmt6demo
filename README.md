# GMT6 Demo: Modern mode and subplots

This demo was made to accompany the AGU Fall Meeting 2017 talk
"[The Generic Mapping Tools 6: Classic versus Modern Mode](https://agu.confex.com/agu/fm17/meetingapp.cgi/Paper/233558)"
by [Paul Wessel](http://www.soest.hawaii.edu/wessel/).

The demo runs on a [Jupyter notebook](http://jupyter.org) using `%%bash` cells
and `IPython.display.Image` to insert the generated plots in the notebook.

You can try it online (no install required) at [gmt6demo.gmtpython.xyz](http://gmt6demo.gmtpython.xyz)
or by clicking on this badge
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/GenericMappingTools/gmt6demo/master?filepath=demo.ipynb)

The online demo runs on [mybinder.org](https://mybinder.org/).

To run it locally, you'll need the [Anaconda Python
distribution](https://www.anaconda.com/download/).
After installing it, grab an archive of this repository and unzip it (or clone
it to your machine).
Inside the unzipped repository, run the following in your terminal:

    conda env create
    source activate gmt6demo
    jupyter notebook

This should open you browser to the Jupyter notebook interface. Select
`demo.ipynb` and run the code using `Shift+Enter`.
