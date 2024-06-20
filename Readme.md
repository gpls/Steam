# Steam_project

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>


## Presentation

Steam est une plateforme de distribution de jeux vidéo, de gestion des droits numériques, de communication et de services multi-joueurs développée par Valve Corporation. Elle propose des milliers de jeux de toutes sortes, allant des jeux indépendants aux gros titres. Les utilisateurs peuvent acheter, télécharger, mettre à jour, et interagir avec d'autres joueurs via la plateforme.
Première version: 12 septembre 2023
Steam comptait en février 2015 plus de 125 millions d'utilisateurs et en mars 2017 plus de 14 000 jeux.

## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for src
│                         and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── src                <- Source code for use in this project.
    │
    ├── __init__.py    <- Makes src a Python module
    │
    ├── data           <- Scripts to download or generate data
    │   └── make_dataset.py
    │
    ├── features       <- Scripts to turn raw data into features for modeling
    │   └── build_features.py
    │
    ├── models         <- Scripts to train models and then use trained models to make
    │   │                 predictions
    │   ├── predict_model.py
    │   └── train_model.py
    │
    └── visualization  <- Scripts to create exploratory and results oriented visualizations
        └── visualize.py
```
 




## Dataset

Notre jeu de données nous à été transmis par Jedha Bootcamp et est disponilbe par ce lien: (('s3://full-stack-bigdata-datasets/Big_Data/Project_Steam/steam_game_output.json')


## Goal of the project

Réaliser une analyse globale des jeux disponibles sur la place de marché Steam afin de mieux comprendre l'écosystème du jeu vidéo et les tendances actuelles.



## Project and repository architecture

Ce projet se décline en trois analyses: (Veuillez cliquez sur les liens ci-dessous)

Analyse du macro-environnement:
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/362438496397165/2956102882853578/1619747908713141/latest.html

Analyse des genres:
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/362438496397165/2956102882853589/1619747908713141/latest.html

Analyse de la plateforme:
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/362438496397165/2956102882853600/1619747908713141/latest.html



## Deliverables

Rapport,
PowerPoint,
Code

## Source code
Le code source est disponible dans ce référentiel et écrit en Python3

## Author

Paola L 









