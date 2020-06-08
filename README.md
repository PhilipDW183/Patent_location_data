# Patent_location_data
A repository for code that merges patents/citations/controls with location data.

A file will need to be created of Patents data within this repository that contains PCT_citing&Citing_nosefl.csv, first_and_subsequent.txt files and geoc_inv data.

The exploring geo_coded files.ipynb uses the first_and_subsequent files from https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/QLT9WM to create the files used in merging exact location data.ipynb files.

The geoc_inv data comes from https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/OTTBDX as used in both merging files. 

The EPO_treatment_data.csv is used in the merging exact location data and EPO.ipynb file.

The merging exact location data and EPO.ipynb is used to merge the location data, through the first and subsequent file, to the treatment data. The first half can be ignored by explains the way in which EPO_treatment_data.csv is reached at. The second half deals with the merging.  

Merging exact location data and PCT.ipynb performs a similar function, but stops after merging with the first and subsequent file due to the loss of data.


