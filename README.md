# Utilisation d'une Forêt Aléatoire pour la Classification de Cancer du Côlon 

Ce projet vise à utiliser les algorithmes d'arbre de décision et de Forêt Aléatoire pour la classification de données médicales sur les cancers du côlon.     
Les méthodes explorées dans ce projet seront  comparées en utilisant la métrique d'accuracy et les matrices de confusion.

## Description du Projet
Les données médicales fournies pour ce projet concernent les cancers du côlon et comprennent plusieurs caractéristiques cliniques des patients.     
L'objectif est de créer un modèle de classification qui peut prédire si un patient a un cancer du côlon ou non, en utilisant les caractéristiques disponibles.    
Il s'agit de modèle non-linéaire.

### Contenu du Projet

Le projet est structuré comme suit :

- Chargement et Exploration des Données
- Prétraitement des Données : Nous effectuerons des opérations de nettoyage et de prétraitement sur les données
- Création de l'Arbre de Décision 
- Création de la Forêt Aléatoire
- Comparaison des Performances :  l'accuracy et les matrices de confusion.

### Prérequis
Utilisation de l'environnement:

Python 3.x     
pandas        
numpy      
scikit-learn     
seaborn     

### Structure des Fichiers

├── colon_cancer_dataset.csv     
├── colon_cancer_classification.ipynb      
└── README.md       

Le dossier "data" contient le fichier CSV du jeu de données médical sur les cancers du côlon.     
Le fichier colon_cancer_classification.ipynb est un cahier Jupyter contenant tout le code du projet,     
y compris le chargement des données, la création des modèles et l'évaluation des performances.      
Le fichier README.md est le présent document, fournissant une description détaillée du projet.

### Conclusion
Ce projet montre comment utiliser l'algorithme de Forêt Aléatoire pour la classification des cancers du côlon, en le comparant à l'Arbre de Décision.     
En utilisant l'accuracy et les matrices de confusion, nous évaluerons la qualité des prédictions de chaque modèle.       
La réussite de ce projet nous permettra de choisir le meilleur modèle pour la prédiction des cancers du côlon dans les données médicales fournies.
