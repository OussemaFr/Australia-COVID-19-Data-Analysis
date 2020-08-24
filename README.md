# Exercice d'évaluation pour le poste Inria / AP-HP

Le notebook Deduplicates_notebook a pour objectif de : 
* Mettre en évidence les problèmes de qualité de données 
* Cleaning des données en se basant soit sur des données de l'australie recupéré du Wikipedia 
comme (noms des states, range des postcodes de chaque state)
* Construction de la fonction detect_duplicates 
* Tester les fonctions utilisées pour la construction de la fonction detect_duplicates (eg utilisant https://docs.pytest.org/en/stable/)
* Creation de deux nouvelles tables (patient_cleaned après la phase du cleaning et une autre table new_patient table après cleaning et 
le suppression des doublons)

Le notebook EDA_notebook a pour objectif de d'analyse exploratoire de données: 
* import du dataframe new_patient sans les doublons
* Analyse et cleaning de la dataframe pcr 
* Représentation visuelle de nombre de tests soit positifs soit négatifs par state par tranche d'age en utilisant des 
(graphiques, histogrammes, pies, maps)

Notices:
Pour installer les libraries: Vous pourrez soit les installer directement via jupyter ou via cmd commande pythom -m pip install your_folder_path/requirements.txt

