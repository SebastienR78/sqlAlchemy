# Projet SQLALCHEMY

## Méthodes et outils

### Environnement virtuel (venv) et Git

- Créer un environnement virtuel pour isoler les dépendances du projet :
  - [Documentation venv](https://docs.python.org/3/library/venv.html)

    `python -m venv .venv`

    `.venv\Scripts\Activate.ps1`

    `python -m pip install --upgrade pip`

    `pip install sqlalchemy sqlalchemy-utils`

- Créer un fichier `.gitignore` pour GitHub :
  - [Documentation GitHub `.gitignore`](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files)

### Gestion des dépendances (`requirements.txt`)

- Créer un fichier `requirements.txt` pour lister toutes les dépendances du projet :
  - [Documentation `requirements.txt`](https://pip.pypa.io/en/stable/user_guide/#requirements-files)
  - **Dépendances** :
    - [Pandas](https://pandas.pydata.org/docs/)
    - [SQLAlchemy](https://docs.sqlalchemy.org/en/20/)
    - [Streamlit](https://docs.streamlit.io/)
    - [NumPy](https://numpy.org/doc/)
    - [Matplotlib](https://matplotlib.org/stable/contents.html)
    - [Seaborn](https://seaborn.pydata.org/)
    - [Logging](https://docs.python.org/3/library/logging.html) / [Loguru](https://loguru.readthedocs.io/)

### Documentation (`readme.md`)

- Créer un fichier `readme.md` pour documenter le projet, y compris les instructions d'installation, d'exécution et d'utilisation :
  - [Guide de création de README sur GitHub](https://docs.github.com/en/get-started/writing-on-github/basic-writing-and-formatting-syntax)

### Modélisation Merise

- Utiliser la méthode Merise pour concevoir le Modèle Conceptuel de Données (MCD) et le Modèle Logique de Données (MLD) de la base de données.
  - [Introduction à Merise](https://fr.wikipedia.org/wiki/Merise)

### Bibliothèques

- [Pandas](https://pandas.pydata.org/docs/) : pour la manipulation et l'analyse des données.
- [SQLAlchemy](https://docs.sqlalchemy.org/en/20/) : pour l'interaction avec la base de données (ORM).
- [Streamlit](https://docs.streamlit.io/) : pour l'interface utilisateur interactive.
- [NumPy](https://numpy.org/doc/) : pour les calculs numériques.
- [Matplotlib](https://matplotlib.org/stable/contents.html) et/ou [Seaborn](https://seaborn.pydata.org/) : pour la création de graphiques.
- [Pytest](https://docs.pytest.org/en/stable/) : pour les tests.

### Versionnage et monitoring

- [GitHub](https://github.com/) : pour travailler en groupe.
- [Logging](https://docs.python.org/3/library/logging.html) ou [Loguru](https://loguru.readthedocs.io/) : pour la journalisation.

## Étapes

### Collecte et préparation des données

1. Trouver un jeu de données :
   - [Video Game Sales](https://www.kaggle.com/gregorut/videogamesales)
   - [Supermarket Sales](https://www.kaggle.com/aungpyaeap/supermarket-sales)
2. Nettoyer et préparer les données avec `pandas` :
   - [Guide Pandas pour le nettoyage de données](https://pandas.pydata.org/pandas-docs/stable/user_guide/data_cleaning.html)

### Modélisation de la base de données

1. Concevoir le MCD et le MLD en utilisant Merise.
2. Créer la base de données (`sqlite`) et les tables avec `SQLAlchemy` :
   - [SQLAlchemy ORM Documentation](https://docs.sqlalchemy.org/en/20/orm/)

### Développement de l'application Streamlit

1. Créer l'interface utilisateur pour charger, explorer et visualiser les données, ainsi qu'analyser les ventes :
   - [Documentation Streamlit](https://docs.streamlit.io/)
2. Utiliser `pandas` et `SQLAlchemy` pour interagir avec les données.
3. Utiliser `pyplot`/`seaborn` pour créer des graphiques :
   - [Matplotlib Pyplot Guide](https://matplotlib.org/stable/tutorials/introductory/pyplot.html)
   - [Seaborn Guide](https://seaborn.pydata.org/)
