# PresiTracker2027 pour Android

Ce dépôt ne contient que les versions de l'app Android **PresiTracker2027** distribuées hors Google Play.

- Télécharger la dernière version : https://presitracker2027.fr/telecharger/android
- Site : https://presitracker2027.fr

Chaque [release](https://github.com/fcroiseaux/presitracker2027-android/releases) contient l'APK signé et son manifeste `version.json` (numéro de version, empreinte SHA-256, taille). L'app installée lit ce manifeste et se met à jour elle-même.

Empreinte SHA-256 du certificat de signature :

```
7f:1a:27:eb:50:cc:f4:0f:96:46:35:b8:31:e5:37:64:bd:54:54:a0:32:3f:a5:b2:82:6c:c4:74:cd:29:95:b5
```

Vérification : `apksigner verify --print-certs presitracker2027-*.apk`
