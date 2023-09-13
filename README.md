# Driver of deforestation labeling tool

Driver of deforestation labeling tool is built under `Jupyter Notebook` platform. 

First, please ensure `phyton` and `anaconda` are successfully installed on your computer. When installing `anaconda`, `python3` will be automatically installed as well. You can download the `anaconda` installer [here](https://docs.anaconda.com/anaconda/install/index.html).

You must have [Google Earth Engine](https://earthengine.google.com/) ([sign up](https://accounts.google.com/signin/v2/identifier?service=ah&passive=true&continue=https%3A%2F%2Fuc.appengine.google.com%2F_ah%2Fconflogin%3Fcontinue%3Dhttps%3A%2F%2Fsignup.earthengine.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin)) account as this tool will be hugely relied on dataset stored in GEE.

After fresh installing `anaconda` you have to make `conda` environment and install several important packages below:

```python
conda create --name gis
conda activate gis
conda install -c conda-forge earthengine-api
conda install --channel conda-forge geopandas
conda install -c conda-forge ipyleaflet
conda install -c conda-forge voila
conda install jupyter notebook
```
