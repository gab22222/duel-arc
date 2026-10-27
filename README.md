# Duel à l'Arc

Duel à l'arc en 3D pour deux téléphones. Les flèches ont un temps de vol et retombent avec la gravité. Chaque joueur a 300 HP : une flèche dans le corps enlève 100 HP, une flèche dans la tête enlève les 300 d'un coup. Le premier qui touche 3 flèches (ou 1 dans la tête) gagne.

Deux cartes :
- **Canyon** : face à face sur deux piliers, on ne peut que se décaler sur le côté pour esquiver.
- **Forêt** : déplacements libres avec un joystick, arbres et rochers pour se cacher ou foncer sur l'adversaire.

Pour jouer : https://gab22222.github.io/duel-arc/

- Un joueur appuie sur **Créer une partie** et donne le code à l'autre, qui le tape puis appuie sur **Rejoindre**.
- Gauche : glisser pour se déplacer (joystick en forêt). Droite : maintenir pour bander l'arc, glisser pour viser, relâcher pour tirer.
- Aucun compte n'est nécessaire. Le multijoueur passe par un relais MQTT public (broker.emqx.io).
