# Ship Radar 360 — mises à jour du firmware

Ce dépôt héberge uniquement les **binaires chiffrés et signés** du firmware
Ship Radar 360 (ESP32-S3) et leur `manifest.json`, publiés dans les *Releases*. Les
appareils lisent le manifeste de la dernière version :

    https://github.com/Sufenstyle/ship-radar-360-updates/releases/latest/download/manifest.json

Chaque binaire est vérifié par l'appareil avant installation (empreinte
SHA-256 + signature ECDSA), puis déchiffré avec une clé propre au produit :
le fichier publié ne fonctionne sur aucune autre carte. Aucun code source ni
clé n'est publié ici.
