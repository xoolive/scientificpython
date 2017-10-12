Pour créer une icône vers l'application d'enregistrement des données :

```sh
adsb kamome
```

## `dump1090`

Un exécutable [`dump1090`](https://github.com/MalcolmRobb/dump1090) construit pour différentes architectures est embarqué dans l'application.

### Dépendance pour Linux

```sh
sudo apt install librtlsdr-dev
```


### Compilation (au cas où...)


- pour MacOS :  
commencer par installer [homebrew](https://brew.sh/) et `rtlsdr`

```sh
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" < /dev/null 2> /dev/null
brew install librtlsdr
```

- puis pour MacOS ou Linux :

```sh
git clone https://github.com/MalcolmRobb/dump1090
cd dump1090
make
mv dump1090 `python -c 'import adsb_py; print adsb_py.__path__[0]'`/tools/darwin
```
