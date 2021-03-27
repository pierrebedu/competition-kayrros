//work in progress...//

KAYRROS CHALLENGE (5th). Predict the production of different groups of asset on the basis of geospatial data. Regression techniques.
255 000 samples.

###########################################################################

HOW TO USE THIS?

   - download the dataset
   - launch the EDA and modeles files in a Jupyter environnement

##############################################################################

Deploiement "rapide" d'un modèle en visant l'efficacité et la rationnalité :
- EDA
- beaucoup de preprocessing, nettoyage par boolean indexing
- features engineering ->reduction à 104 samples
- stratégie d'effacage du bruit avec un seuil trouvé par optimisation systématique du RMSE
- modèle simple de regression par SGD
- optimisation du paramètre de régularisation par gridsearch
- courbes d'apprentissage
- tentative infructueuse d'adressage de l'underfitting par expansion polynomiale

NB: pistes non explorées (classement à la compétition satisfaisant)
- essai de techniques à base d'arbres 
- SVM
- NN
