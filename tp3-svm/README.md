# TP2

Ce répertoire contient mon [rapport](rapport-tp3-svm.pdf) du TP3 de hax907x au format pdf ainsi que tous les éléments nécessaires à sa reproductibilité.

## Auteur

Mathieu Le Séac'h

## Reproductibilité

### Prérequis

Vous devez avoir Python (3.11 ou plus), Poetry et Quarto installés sur votre machine. Si vous ne l'avez pas déjà fait, vous pouvez les installer en suivant ces instructions :

- Python : https://www.python.org/downloads/
- Poetry : https://python-poetry.org/docs/#installation
- Quarto : https://quarto.org/docs/get-started/

Vous pouvez utiliser un gestionnaire de paquet autre que poetry tant que les dépendances sont bien installées dans votre environnement courant.

### Installation des dépendances

Une fois que vous avez cloné le projet, naviguez jusqu'au répertoire du TP et exécutez la commande suivante pour installer les dépendances du projet:

```bash
poetry install
```

Ou avec pip si vous utilisez un autre gestionnaire d'environnement virtuel :

```bash
pip install -r requirements.txt
```

### Génération du rapport

Le projet utilise Quarto pour générer le rapport. Vous pouvez le faire en exécutant la commande suivante :

```sh
poetry run quarto render rapport.qmd
```

Sinon, si vous utilisez un autre gestionnaire d'environnement virtuel, activez-le puis exécutez la commande suivante :

```sh
quarto render rapport.qmd
```
