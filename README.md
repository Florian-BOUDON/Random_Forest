# Arbre de décision et forêt aléatoire pour la classification 

Ce projet vise à utiliser les algorithmes d'arbre de décision et de forêt aléatoire pour la classification de données médicales sur les cancers du côlon.     
Les méthodes explorées dans ce projet seront  comparées en utilisant la métrique d'accuracy et les matrices de confusion.

## Description du projet
Les données médicales fournies pour ce projet concernent les cancers du côlon et comprennent plusieurs caractéristiques cliniques des patients.     
L'objectif est de créer un modèle de classification qui peut prédire si un patient a un cancer du côlon ou non, en utilisant les caractéristiques disponibles.    
Il s'agit de modèle non-linéaire.

### Contenu du projet

Le projet est structuré comme suit :

- Chargement et exploration des données
- Prétraitement des données : nous effectuerons des opérations de nettoyage et de prétraitement sur les données
- Création de l'arbre de décision 
- Création de la forêt aléatoire
- Comparaison des performances :  l'accuracy et les matrices de confusion.

### Prérequis
Utilisation de l'environnement:

Python 3.x     
pandas        
numpy      
scikit-learn     
seaborn     

### Structure des fichiers

├── colon_cancer_dataset.csv     
├── colon_cancer_classification.ipynb      
└── README.md       

Le dossier "data" contient le fichier CSV du jeu de données médical sur les cancers du côlon.     
Le fichier colon_cancer_classification.ipynb est un cahier Jupyter contenant tout le code du projet,     
y compris le chargement des données, la création des modèles et l'évaluation des performances.      
Le fichier README.md est le présent document, fournissant une description détaillée du projet.

### Conclusion
Ce projet montre comment utiliser l'algorithme de forêt aléatoire pour la classification des cancers du côlon, en le comparant à l'arbre de décision.     
En utilisant l'accuracy et les matrices de confusion, nous évaluerons la qualité des prédictions de chaque modèle.       
La réussite de ce projet nous permettra de choisir le meilleur modèle pour la prédiction des cancers du côlon dans les données médicales fournies.
