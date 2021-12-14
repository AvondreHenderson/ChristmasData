# JupyterNotebooks

This folder contains all the Jupyter notebooks that were used to perform the Extraction, Transformation, and Loading operations for this project.

* "recipes.ipynb" is the notebook for importing the recipe data file into PostgreSQL.
* "movies.ipynb" is the notebook for pulling Christmas movies from OMDB and putting into PostgreSQL.
* "SalesData_Michael.ipynb" is the notebook pulling all of the Holiday Shopping data and putting into PostgreSQL. 
* "MusicData.ipynb" is the notebook for pulling all of the Christmas Music and putting into PostgreSQL. 

#### The "Resources" Folder contains all of the input data files that were used by the above notebooks.
#### Before running "movies.ipynb" you will need to create a "config.py" file containing an OMDB api key called "omdbapi_key".
