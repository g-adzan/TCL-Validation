# Driver of deforestation mapping tool

Untuk menjalankan tool ini, Anda perlu membuat Python virtual environment dan melakukan instalasi beberapa Python package, direkomendasikan menggunakan `conda`.

Pertama, Anda perlu memastikan bahwa Python dan `anaconda` telah terpasang pada komputer pengguna. Ketika memasang `anaconda`, Python3 otomatis akan terpasang pada komputer pengguna. Instalasi `anaconda` dapat dilihat [di sini](https://docs.anaconda.com/anaconda/install/index.html).

Kedua, Anda harus memiliki akun [Google Earth Engine](https://earthengine.google.com/) ([sign up](https://accounts.google.com/signin/v2/identifier?service=ah&passive=true&continue=https%3A%2F%2Fuc.appengine.google.com%2F_ah%2Fconflogin%3Fcontinue%3Dhttps%3A%2F%2Fsignup.earthengine.google.com%2F&flowName=GlifWebSignIn&flowEntry=ServiceLogin)).

Anda dapat membuat conda environment (lebih detil [di sini](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)) dan memasang beberapa Python package dengan command berikut:

``python
conda create --name gis -c conda-forge python=3.8 earthengine-api geopandas ipyleaflet
conda activate gis
```
