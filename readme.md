GitHub is able to 

* Show Jupyter Notebooks with **static content**, e.g. output of matplotlib:

https://github.com/stefaneidelloth/jupyterDemo/blob/master/demo_static.ipynb

* **GeoJson** files:

https://github.com/stefaneidelloth/jupyterDemo/blob/master/geojson/z_geojson_file.geojson

----

**Dynamic content** does not work un GitHub directly, see bokeh outout of following example:

https://github.com/stefaneidelloth/jupyterDemo/blob/master/demo.ipynb

----

**In order to see dynamic/interactive notebooks**, you can pass the url of a notebook<br>
to some online service (note different url syntax):

* **nbviewer**: https://nbviewer.jupyter.org/github/stefaneidelloth/jupyterDemo/blob/master/demo.ipynb?flush_cache=true

* **mybinder**: (First shows noninteractive preview; might take a while until server is ready)
  * Notebook: https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?filepath=demo.ipynb
  * JupyterLab: https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?urlpath=lab?filepath=demo.ipynb

----

NbViewer and Binder do not support everything by default. 

If your JupyterLab notebook requires some dependencies,<br>
you can specify them with<br>
* postBuild : a bash script file that can be used to install jupyterlab extensions
* requirements.txt: install pip packages 
* apt.txt : install linux dependencies with apt-get package manager

Also see:
* https://mybinder.readthedocs.io/en/latest/using/config_files.html
* https://github.com/jupyterlab/jupyterlab-demo

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/master?urlpath=lab)

If you get the below examples working, please let me know.



**mybinder**

https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?urlpath=lab?filepath=geojson/a_geojson_extension.ipynb

https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?urlpath=lab?filepath=geojson/b_geopandas_and_ipympl.ipynb

https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?urlpath=lab?filepath=geojson/c_leaflet.ipynb

https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?urlpath=lab?filepath=geojson/d_kepler_gl.ipynb


**nbviewer** (does not work)

https://nbviewer.jupyter.org/github/stefaneidelloth/jupyterDemo/blob/master/geojson/a_geojson_extension.ipynb

https://nbviewer.jupyter.org/github/stefaneidelloth/jupyterDemo/blob/master/geojson/b_geopandas_and_ipympl.ipynb

https://nbviewer.jupyter.org/github/stefaneidelloth/jupyterDemo/blob/master/geojson/c_leaflet.ipynb

https://nbviewer.jupyter.org/github/stefaneidelloth/jupyterDemo/blob/master/geojson/d_kepler_gl.ipynb


