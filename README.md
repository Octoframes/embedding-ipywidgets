# Embedding widget possible?

JupyterLab4 -> There's the option "Save widget state automatically", but that's broken
Jupyter Notebook 7
JupyterVS Code (no, not planned)


# Is there a disconnection indicator after kernel restart?
JupyterLab4  -> yes!
Jupyter Notebook 7 -> ??
JupyterVS Code -> no!


# Is there a disconnection indicator after kernel restart + reopening?

JupyterLab4 -> Error displaying widget: model not found
related 
https://github.com/jupyter-widgets/ipywidgets/issues/3758
https://github.com/jupyter-widgets/ipywidgets/issues/3773
https://github.com/jupyter-widgets/ipywidgets/issues/2628

Jupyter Notebook 7
JupyterVS Code

# Does the platfoorm allow displaying embedded widtgets after restart kernel and closing+reopening notebook? 






Steps to reproduce for JupyterLab Version 4.0.4:

python3.11 -m venv .venv && source .venv/bin/activate
pip install jupyterlab
pip install ipywidget


