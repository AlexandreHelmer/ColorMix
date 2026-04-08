Un jeu de mélange de couleurs simple pour les enfants.

# Build

## Android (debug APK)

Depuis la racine du projet :

```bash
# Requiert: cordova + Android SDK
./build_app.sh ColorMix

# Sortie: ColorMix.apk
```

Équivalent (extrait de `build_app.sh`) :

```bash
export ANDROID_HOME=/opt/android-sdk/
cd ColorMix
cordova build android
mv platforms/android/app/build/outputs/apk/debug/app-debug.apk ../ColorMix.apk
```


# TODO, améliorations & idées
* musiques de fond en fonction du thème

* leaderboard ? Demande un stockage local.

* Gérer la mise en pause:
  * avec un bouton dédié
  * quand on perd le focus

* images libres de droit
* localisation ?

# Bugs
* Zoom sur ordi / pas possible
