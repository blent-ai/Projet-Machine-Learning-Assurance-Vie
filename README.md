<div align="center">
  <a href="https://blent.ai">
    <img src="https://blent-static-media.s3.eu-west-3.amazonaws.com/images/logo/logo_blent_300x.png" alt="Logo Blent.ai" width="200" />
  </a>

  <h2 align="center">Modélisation des provisionnements en assurance vie</h2>

  <p align="center">
    Projet Machine Learning - <a href="https://blent.ai">Blent.ai</a>
    <br />
    <a href="https://blent.ai/app/projects" target="_blank"><strong>Explorer tous les projets »</strong></a>
</div>

<div align="center"><img src="https://cdn.static-media.blent.ai/images/projects/badge_shield.svg" width="120" alt="Badge du projet" /></div>

## À propos du projet


Une grande entreprise financière propose des services d'assurance vie à ses clients. En raison de contraintes réglementaires, l'entreprise doit être capable de modéliser les risques futurs, et notamment ses engagements futurs envers ses assurés.

En particulier, elle doit être en mesure de prévoir ce qu'elle devra verser aux assurés pour les prochaines années. Un contrat d'assurance vie peut être terminé selon plusieurs conditions.

-   En cas de  **rachat total**, c'est-à-dire que l'assuré récupère l'intégralité des bénéfices du contrat.
-   En cas de  **décès**  de l'assuré.
-   En cas de  **sortie par redressement judiciaire**.
-   En cas de  **renonciation**, lorsque le bénéficiaire ne souhaite pas récupérer le bénéfice du contrat.

Pour l'assureur, un contrat qui se termine représente un risque, car il s'agit d'un montant que l'assureur a pour obligation légale de régler. En effet, si un rachat total intervient l'année suivante, l'assureur doit récupérer ce montant qu'il a investi pour remplir ces obligations : retirer ce montant à ce moment-là n'est peut être pas ce que l'assureur aurait souhaité. Il est donc nécessaire de modéliser ce risque pour prévoir combien de contrats devront être réglés parmi toutes les situations décrits.

Les données utilisés pour ce projet et mis à disposition contiennent des informations anonymisées sur des contrats d'assurance vie de clients français.

> TODO : Compléter cette partie pour apporter plus d'informations sur le contexte du projet.

## Étapes du projet

- [ ] Préparer le jeu de données afin de l'adapter au périmètre de l'étude
- [ ] Construire des variables explicatives cohérentes selon les besoins de l'étude
- [ ] Proposer un modèle prédictif optimisé et stable
- [ ] Interpréter les variables explicatives
- [ ] Publier le code source et les résultats sur GitHub

La description des étapes est disponible sur la page associée au projet.

> TODO : Cocher les cases au fur et à mesure de l'avancement.

## Résultats

| Taille du train |      Erreur d'estimation PM      |
|:---------------:|:-------------------:|
|        1k       | 00.00€ ± 00.00€ |
|       10k       | 00.00€ ± 00.00€ |
|       100k      | 00.00€ ± 00.00€ |

> TODO : Il est possible d'ajouter des graphes pour apporter plus d'indications sur les résultats.

## Structure du projet

Le dépôt Git contient les éléments suivantes.

- `notebooks/` contient les Notebooks Jupyter du projet.
- `LICENSE.txt` : licence du projet.
- `requirements.txt` : liste des dépendances Python nécessaires.
- `README.md` : fichier d'accueil.

## Premiers pas

Les instructions suivantes permettent d'exécuter le projet sur son PC.

### Pré-requis

Le projet nécessite Python 3 d'installé sur le système.

> TODO : Ne pas hésiter à compléter/adapter cette partie en fonction des dépendances logicielles.

### Installation

1. Cloner le projet Git.
	```
	git clone https://github.com/blent-ai/Projet-Machine-Learning-Bank-Churn.git
	```
2. Installer les dépendances du fichier `requirements.txt` dans un environnement virtuel.

	**Linux / MacOS**
	```
	python3 -m venv venv/
	source venv/bin/activate
	pip install -r requirements.txt
	```
	**Windows**
	```
	python3 -m venv venv/
	C:\<chemin_dossir>\venv\Scripts\activate.bat
	pip install -r requirements.txt
	```

> TODO :
> - Remplir le fichier `requirements.txt` pour y ajouter les dépendances (Scikit-Learn, Pandas, etc).

### Démarrage

> TODO : Expliquer en quelques lignes et avec des exemples de ligne de commande comment l'utilisateur peut entraîner ou utiliser lui-même le modèle. 

## Licence

*Ce projet est proposé par <a href="https://blent.ai">Blent.ai</a>. Les données utilisées pour ce projet peuvent être soumises à des droits d'auteur et de propriété intellectuelle. Blent.ai ne peut être responsable des utilisations faites des données utilisées dans le cadre de ce projet.*

> TODO : Ajouter les licences supplémentaires au projet (autres données, outils propriétaires, etc).
