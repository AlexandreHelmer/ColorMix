Un jeu de mélange de couleurs simple pour les enfants.

# Build

## Android (debug APK)

Depuis la racine du projet :

```bash
# Requiert: cordova + Android SDK
./build_app.sh ColorMix

# Sortie: ColorMix.apk
```

(Le script exporte ANDROID_HOME et lance `cordova build android`.)

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
