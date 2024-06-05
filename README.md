# customer_clustering

Le premier objectif de ce projet est de segmenter différents types de clients d'un site d'e-commerce, grâce à leurs données personnelles. Le second objectif consiste à simuler la stabilité des segments au cours du temps, afin de déterminer la fréquence nécessaire de mise à jour du modèle de segmentation.

Les données utilisées dans ce projet sont disponibles sur le lien suivant :
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## Description du répertoire

**Fichiers :**
- **_RFM_data.csv_** contient les données nettoyées.
- **_essais.ipynb_** est le notebook Jupyter proposant différentes pistes de modélisation ainsi que le modèle final sélectionné.
- **_exploration.ipynb_** est le notebook Jupyter présentant les étapes de nettoyage, de feature engineering et d'analyse exploratoire.
- **_requirements.txt_** contient la liste des packages utilisés pour la réalisation du projet.
- **_simulation.ipynb_** est le notebook Jupyter définissant le délai de maintenance du modèle final.

## Installation

Le projet a été réalisé sur un environnement Python 3.11.5. Les packages peuvent être installés grâce à la ligne de commande suivante :

`pip install -r requirements.txt`
