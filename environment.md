Pour les séances de programmation Python, vous pouvez utiliser les machines de l'école ou votre machine.

## Machines de l'école

Un environnement a été préparé pour vous sur les machines de l'école. Pour l'utiliser, entrez **systématiquement** les lignes suivantes dans un terminal :
```sh
useensta python3
source activate ~olive/cartography
```

## Machines personnelles

### Installation

Commencez par installer un environnement Anaconda pour votre machine en suivant le lien [suivant](https://www.continuum.io/downloads).

Puis, à partir du terminal placé dans le dossier du cours:
```sh
conda env create -n cartography -f environment.yml
```

Si des erreurs surviennent à l'installation, contactez le professeur.

### Utilisation

Sous Linux/Mac OS:
```sh
source activate cartography
```

Sous Windows:
```sh
activate cartography
```

