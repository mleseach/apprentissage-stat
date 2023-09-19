# TP2

Ce répertoire contient mon [rapport](rapport-tp2-arbres.pdf) du TP2 de hax907x au format pdf ainsi que tout les élements nécessaires à sa reproductibilité.

## Status

TP pas terminé

## Reproductibilité

### Prérequis

Vous devez avoir Python (3.11 ou plus), Poetry et Quarto installés sur votre machine. Si vous ne l'avez pas déjà fait, vous pouvez les installer en suivant ces instructions :

- Python : https://www.python.org/downloads/
- Poetry : https://python-poetry.org/docs/#installation
- Quarto : https://quarto.org/docs/installation.html

Vous pouvez vous passer de Poetry mais il faudra vous assurer d'avoir installé les dépendances de `pyproject.toml` dans votre environnement python.

### Installation des dépendances

Une fois que vous avez cloné le projet, naviguez jusqu'au répertoire du TP et exécutez la commande suivante pour installer les dépendances du projet :

```bash
poetry install
```

### Génération du rapport

Le projet utilise Quarto pour générer le rapport. Vous pouvez le faire en exécutant la commande suivante :

```sh
poetry run quarto render rapport.qmd
``` 
