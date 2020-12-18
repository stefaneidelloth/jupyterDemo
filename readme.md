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

* **mybinder**: https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?filepath=demo.ipynb

----

NbViewer and Bokeh do not support everything. If your notebook requires some JupyterLab extension,<br> 
it might not work. Below are **some gis examples that do not work**.<br>
If you get them working, please let me know.




**nbviewer**

https://nbviewer.jupyter.org/github/stefaneidelloth/jupyterDemo/blob/master/geojson/a_geojson_extension.ipynb

https://nbviewer.jupyter.org/github/stefaneidelloth/jupyterDemo/blob/master/geojson/b_geopandas_and_ipympl.ipynb

https://nbviewer.jupyter.org/github/stefaneidelloth/jupyterDemo/blob/master/geojson/c_leaflet.ipynb

https://nbviewer.jupyter.org/github/stefaneidelloth/jupyterDemo/blob/master/geojson/d_kepler_gl.ipynb

**mybinder**

https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?filepath=geojson/a_geojson_extension.ipynb

https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?filepath=geojson/b_geopandas_and_ipympl.ipynb

https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?filepath=geojson/c_leaflet.ipynb

https://mybinder.org/v2/gh/stefaneidelloth/jupyterDemo/master?filepath=geojson/d_kepler_gl.ipynb


