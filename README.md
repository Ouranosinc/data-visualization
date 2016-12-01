# data-visualization
Exploration of data visualization technologies

## Setup

We run [Python 3.5.2](https://www.python.org/downloads/release/python-352/).
We use a virtual environment (virtualenv) for this project:

    $ mkdir -p ~/.virtualenv
    $ python3 -m venv ~/.virtualenv/data-visualization

Activate the virtualenv:

    $ source ~/.virtualenv/data-visualization/bin/activate

When you are done working on this project, you may want to `$ deactivate`.

Install the dependencies:

    $ pip install -r requirements.txt

### Basemap

To install `basemap`, follow http://matplotlib.org/basemap/users/installing.html#installation
using

    $ export GEOS_DIR=~/.virtualenv/data-visualization/lib/python3.5/site-packages/

### Jupyter

Enable notebook extension jupyter-js-widgets:

    $ jupyter nbextension enable --py widgetsnbextension

Launch the Jupyter Notebook:

    $ jupyter notebook
