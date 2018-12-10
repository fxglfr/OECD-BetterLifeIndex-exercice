# OECD-BetterLifeIndex-exercice
Mon premier pas dans l’analyse de données par les méthodes d’apprentissage profond (Machine Learning) 

Je me suis inspiré des codes du livre d'Aurélien Geron, Machine learning avec Scikilearn et de son Git :  
https://github.com/ageron/handsoan-ml/blob/master/01_the_machine_learning_landscape.ipynb

Il avait créé tout d'abord un modèle basé sur la régression linéaire simple pour prédire l’indice de satisfaction de Chypre suivant le Produit National Brut par  habitant en 2016.
A cette fin, il avait fusionné les données du PNB par habitant du FMI, Fonds Monétaire Internationale avec ceux de l’indice du mieux vivre de l’OCDE,  Organisation de coopération économique et de développement.
Cet indice a été créé suite au rapport de la commission Stiglitz-Sen-Fitouss afin de mieux appréhender la richesse d’un pays autre que celui de la production économique

En ce qui me concerne, j'ai utilisé uniquement les données de l’OCDE (revenu hors revenu du capital et l’indice de satisfaction).

Le but est un simple exercice de manipulation de données avec python et les dépendances, PANDAS, NUMPY, SCIKITLEARN et MATPLOTLIB.
  
Voici les 5 étapes :

        1- importation et formatage d’un fichier CSV
        2- ordonnancement des données
        3- représentation graphique
        4- modélisation part la méthode de régression linéaire avec Scikitlearn
        5- prédiction de l’indice de satisfaction de Chypre avec le revenu moyen en 2017 

J’espère dans un deuxième temps appliquer un modèle polynomiale et à la fin, aboutir à une étude de modèle logistique.
