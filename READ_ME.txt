
Comment est constitué le répertoire ?

Le répertoire contient :

- Un Notebook en Python pour le nettoyage des données
- Un fichier 'liste_variables_a_retirer' nécessaire pour le fonctionnement du code de nettoyage
- Un Notebook en Python pour l'analyse des données


Quelles sont les librairies nécessaires pour l'utilisation des Notebooks ?

Pour pouvoir exploiter les codes de nettoyage et d'analyse, il est nécessaire d'avoir installé les librairies suivantes:
- Pandas
- Numpy
- Scipy
- Statsmodel
- Matplotlib
- Seaborn

Il est également nécessaire d'avoir Jupyter Notebook installé pour la lecture des fichiers .pynb


Comment utiliser les Notebooks ?

Afin de pouvoir utiliser correctement les Notebooks, il est nécessaire de respecter les étapes suivantes :

- Télécharger les données disponibles sur le site d'Open Food Facts au format .csv
- S'assurer que le nom du dataset est bien 'data_openfoodfacts'
- Placer les deux Notebooks et le fichier 'liste_variables_a_retirer' dans le même répertoire que le dataset
- Ouvrir et exécuter le Notebook de nettoyage, celui-ci générera un dataset nettoyé en .csv nommé 'cleaned_zscore_dataset'
- Ouvrir et exécuter le notebook d'analyse