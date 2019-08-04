## First steps with the virtual environment

Install python3 and pip.

Install virtualenv with `python3.7 -m pip install virtualenv` (you may need a `--user` after `install`, it depends on your installation).

Create the virtual environment, for example `virtualenv arasVenv`.

In the directory of the virtual environment activate it with `source bin/activate` (when you are done working close the session with `deactivate`).

Clone or download the repo and install the requirements with `pip install -r requirements.txt`.

## Running the notebooks

Start a jupyter notebook  with `jupyter-notebook <name>.ipynb`.

If you do not want the jupyter environment convert the notebook to a .py script with `jupyter-nbconvert <name>.ipynb --to python`.

You can also start an online interactive session with [mybinder](https://mybinder.org/): there you just need to copy the URL of this github repo and you can launch the notebooks, once the container is ready.

[Website](http://www.astrosurf.com/aras/) of the ARAS group.

Please contact the administrators of the ARAS website if you intend to use their spectra for publications.

