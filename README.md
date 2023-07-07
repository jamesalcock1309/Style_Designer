# Style_Designer
This repository represents a methodology for identifying different building typologies using ML Clustering algorithms with building footprint shape data.

Creating The Dataset
begin by taking a look at the GH code provided, this gives insight into potential geometric data that can be calculated for each builing footprint using the urbano plugin. Of course there are many more potential types of encoding, so this is user dependent, thorough research and undrestanding in desired outcomes is needed for accurate results. 
From here you can export this data as a csv. 

Python Code
I have uploaded an example of my final dataframe that I used in the code, this is based on residential typologies of Amsterdam. 
From here look at BIRCH_DIANA file to run the initial clustering and pre-prosseccing as well some post processing. Research into which clustering methods work best is also neccessary, I have tried many inclusing OPTICS, Agglomerative, and the ones shown in this code. 
Following this you can analyse the results of tsne andlysis and pca.

My process after this was to export the csv results with the clusters added to them, importing this to GIS and merging this data with the original shp files. The images show some of the typology results.
