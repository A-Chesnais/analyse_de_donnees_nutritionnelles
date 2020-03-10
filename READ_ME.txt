
Comment est constitu� le r�pertoire ?

Le r�pertoire contient :

- Un Notebook en Python pour le nettoyage des donn�es
- Un fichier 'liste_variables_a_retirer' n�cessaire pour le fonctionnement du code de nettoyage
- Un Notebook en Python pour l'analyse des donn�es


Quelles sont les librairies n�cessaires pour l'utilisation des Notebooks ?

Pour pouvoir exploiter les codes de nettoyage et d'analyse, il est n�cessaire d'avoir install� les librairies suivantes:
- Pandas
- Numpy
- Scipy
- Statsmodel
- Matplotlib
- Seaborn

Il est �galement n�cessaire d'avoir Jupyter Notebook install� pour la lecture des fichiers .pynb


Comment utiliser les Notebooks ?

Afin de pouvoir utiliser correctement les Notebooks, il est n�cessaire de respecter les �tapes suivantes :

- T�l�charger les donn�es disponibles sur le site d'Open Food Facts au format .csv
- S'assurer que le nom du dataset est bien 'data_openfoodfacts'
- Placer les deux Notebooks et le fichier 'liste_variables_a_retirer' dans le m�me r�pertoire que le dataset
- Ouvrir et ex�cuter le Notebook de nettoyage, celui-ci g�n�rera un dataset nettoy� en .csv nomm� 'cleaned_zscore_dataset'
- Ouvrir et ex�cuter le notebook d'analyse