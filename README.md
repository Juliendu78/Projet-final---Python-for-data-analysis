# Projet-final---Python-for-data-analysis

Ce projet a été réalisé par Audrey POISSON et Julien PYTEL sur Google Colaboratory.

Le projet consiste en une analyse de données du Dataset QSAR Biodegradation disponible à l'url https://archive.ics.uci.edu/ml/datasets/QSAR+biodegradation.

Prédire si une molécule est facilement biodégradable ou non est la raison pour laquelle ce dataset a été pensé.
Nous nous sommes ainsi fixé pour objectif de produire à notre échelle le modèle de Machine Learning le plus adapté possible à la résolution de ce problème.
L'interet de notre API est de mettre à disposition d'un client un service de prédiction.
Le client n'a ainsi pas a se soucier de concevoir un modèle. Le client envoie une requete à l'API pour demander la(les) prédiction(s) d'observation(s) (une espèce chimique est elle prete à être biodégradée ou non?).

Concernant l'API, nous avons fait le choix d'utiliser flask-ngrok afin de rendre notre application Flask fonctionnant sur l'hôte local disponible sur Internet.
Le projet s'articule selon les principales étapes énumérées ci-dessous :
- Feature Engineering
- Conception de modèle
- Développement d'une API (Application Programming Interface)
- Requettage de l'API

Ainsi, afin d'évaluer notre projet, nous conseillons de suivre l'ordre de lecture suivant :
- 1 : FeatureEngineering&Model.ipynb
- 2 : API.ipynb
- 3 : QueryExample.ipynb
