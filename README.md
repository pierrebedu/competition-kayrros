# competition-kayrros
Competition de l'entreprise kayrros (5 ième). Regression.

Il s'agit de prévoir la production de deux groupes d'usines.
Difficultés liées à la taille du dataset (250 000 samples) et au fait que des anomalies de fonctionnement (incidents dans l'usine) créent des pics de "bruit".

###########################################################################

HOW TO USE THIS?

    download the dataset
    launch the EDA and modeles files in a Jupyter environnement

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
