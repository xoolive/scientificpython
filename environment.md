Pour les séances de programmation Python, vous pouvez utiliser les machines de l'école ou vos machines personnelles.

## Machines de l'école

Un environnement complet a été préparé pour vous sur les machines de l'école. Avant d'utiliser Python ou Jupyter, entrez **systématiquement** les lignes suivantes dans un terminal :
```sh
useensta python3
source activate ~olive/cartography
```

## Machines personnelles

### Installation

Commencez par installer un environnement Anaconda pour votre machine.  [lien](https://www.continuum.io/downloads).

Puis, à partir du terminal placé dans le dossier du cours:
```sh
conda env create -n cartography -f environment.yml
```

Si des erreurs surviennent à l'installation, contactez le professeur.

### Utilisation

Vous avez maintenant un environnement identique à celui installé sur les machines de l'école. Avant d'utiliser Python ou Jupyter, entrez **systématiquement** les lignes suivantes dans un terminal :

- sous Linux/Mac OS:
```sh
source activate cartography
```

- sous Windows:
```sh
activate cartography
```

