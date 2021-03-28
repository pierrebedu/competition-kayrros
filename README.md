KAYRROS CHALLENGE (5th). Predict the production of different groups of asset on the basis of geospatial data. Regression techniques.
255 000 samples.

###########################################################################

HOW TO USE THIS?

   - download the dataset
   - launch the EDA and modeles files in a Jupyter environnement

##############################################################################

EDA file :
 - overall shape
 - reshaping by boolean indexing
 - lots of preprocessing
 - first strategy
 
modeles files :
- simple model : linear regression (trees, forests ans SVM give worse results)
- best threshold- function for deleting the pikes
- gridsearch for the best regularization value
- learning curves
- attempt to adress the bias by polynomial expansion (not working)
