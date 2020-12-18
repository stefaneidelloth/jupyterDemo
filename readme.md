GitHub is able to 

* Show Jupyter Notebooks with **static content**, e.g. output of matplotlib:

https://github.com/stefaneidelloth/jupyterDemo/blob/master/demo_static.ipynb

Also see

https://docs.github.com/en/free-pro-team@latest/github/managing-files-in-a-repository/working-with-jupyter-notebook-files-on-github

* **GeoJson** files:

https://github.com/stefaneidelloth/jupyterDemo/blob/master/geojson/z_geojson_file.geojson

Also see

https://docs.github.com/en/free-pro-team@latest/github/managing-files-in-a-repository/mapping-geojson-files-on-github

----

**Dynamic content does not work** on GitHub directly, see bokeh outout of following example:

https://github.com/stefaneidelloth/jupyterDemo/blob/master/demo.ipynb

----

**In order to see dynamic/interactive notebooks**, you can pass the url of a notebook<br>
to some online service (note different url syntax):

* **nbviewer**: https://nbviewer.jupyter.org/github/stefaneidelloth/jupyterDemo/blob/master/demo.ipynb?flush_cache=true

* **mybinder**: https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?urlpath=lab/tree/demo.ipynb<br>
  (First shows nbviewer preview; might take a while until actual binder content is ready)
  
----

Binder does not support everything by default. 

If your JupyterLab notebook requires some dependencies,<br>
you can specify them with<br>
* postBuild : a bash script file that can be used to install jupyterlab extensions
* requirements.txt: install pip packages 
* environment.yml: install conda packages
* apt.txt : install linux dependencies with apt-get package manager

This project includes many depenencies => build time is quite long.

Also see:
* https://mybinder.readthedocs.io/en/latest/using/config_files.html
* https://github.com/binder-examples/jupyter-extension
* https://github.com/binder-examples/jupyterlab


If you get the below examples working, please let me know.


**mybinder** (supporting some jupyterlab extensions and pip dependencies)

https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?urlpath=lab/tree/geojson/a_geojson_extension.ipynb

https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?urlpath=lab/tree/geojson/b_geopandas_and_ipympl.ipynb

https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?urlpath=lab/tree/geojson/c_leaflet.ipynb

https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?urlpath=lab/tree/geojson/d_kepler_gl.ipynb


**nbviewer** (only supporting some default dependencies)

https://nbviewer.jupyter.org/github/stefaneidelloth/jupyterDemo/blob/master/geojson/a_geojson_extension.ipynb

https://nbviewer.jupyter.org/github/stefaneidelloth/jupyterDemo/blob/master/geojson/b_geopandas_and_ipympl.ipynb

https://nbviewer.jupyter.org/github/stefaneidelloth/jupyterDemo/blob/master/geojson/c_leaflet.ipynb

https://nbviewer.jupyter.org/github/stefaneidelloth/jupyterDemo/blob/master/geojson/d_kepler_gl.ipynb


