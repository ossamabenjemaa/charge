# Charge RX (web app hors ligne)

Estimation du temps de charge et de l'autonomie de la Super73 RX, calée sur la charge mesurée le 20/09/2026 (10 à 100 % en 5 h 25, 882 Wh au mur).

## Mise en ligne sur GitHub Pages

1. Crée un dépôt public sur GitHub, par exemple `charge-rx`.
2. Dépose tous les fichiers de ce dossier à la racine du dépôt (bouton "Add file", puis "Upload files"), en gardant le dossier `icons`.
3. Dans Settings, puis Pages : Source "Deploy from a branch", branche `main`, dossier `/ (root)`. Enregistre.
4. Au bout d'une minute ou deux, l'app est en ligne à l'adresse `https://<ton-pseudo>.github.io/charge-rx/`.

## Installation sur l'iPhone

1. Ouvre l'adresse dans Safari, avec du réseau.
2. Partager, puis "Sur l'écran d'accueil".
3. Ouvre l'app une fois depuis l'icône, toujours avec du réseau : elle se met en cache.
4. Elle fonctionne ensuite hors ligne.

## Mettre à jour

Remplace `index.html` dans le dépôt, puis change `CACHE` dans `sw.js` (v1 en v2, etc.). L'iPhone prendra la nouvelle version à la prochaine ouverture avec du réseau.

## À savoir

- Les données restent sur le téléphone, dans l'app installée. Elles sont distinctes de celles du proto sur claude.ai.
- Le dépôt étant public, le code est visible par tous. Il ne contient aucune donnée personnelle : tes réglages ne quittent pas le téléphone.

## Versions

- La version actuelle (V2) est à la racine : Batterie et Historique.
- La V1 (avec Rouler et Réglages) reste disponible à l'adresse `.../charge/v1/`. Ses données sont séparées de celles de la V2.

