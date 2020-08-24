# Exercice d'évaluation pour le poste Inria / AP-HP

Le notebook Deduplicates_notebook a pour objectif de : 
* Mettre en évidence les problèmes de qualité de données 
* Cleaning des données en se basant soit sur des données de l'australie recupéré du Wikipedia 
comme (noms des states, range des postcodes de chaque state)
* Construction de la fonction detect_duplicates 
* Tester les fonctions utilisées pour la construction de la fonction detect_duplicates (eg utilisant https://docs.pytest.org/en/stable/)
* Creation de deux nouvelles tables (patient_cleaned après la phase du cleaning et une autre table new_patient table après cleaninf et 
le suppression des doublons)

Le notebook EDA_notebook a pour objectif de d'analyse exploratoire de données: 
* Analyse et cleaning de la dataframe pcr 
* Représentation visuelle de nombre de tests soit positifs soit négatifs par state par tranche d'age en utilisant des 
(graphiques, histogrammes, pies, maps)

Le notebook Dedupe_open_source a pour objectif de tester la librairie pandas_dedupe qui consiste a detecter des doubland en utilisant du ML:
Réf: https://pypi.org/project/pandas-dedupe/
 
* Import cleaned patient data 
* Application de la fonction dedupe pour la suppression des doublons et estimation du pourcentage des doublons
