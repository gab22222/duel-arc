# Duel à l'Arc

Duel à l'arc en 3D pour deux téléphones. Les flèches ont un temps de vol et retombent avec la gravité. Chaque joueur a 300 HP : une flèche dans le corps enlève 100 HP, une flèche dans la tête enlève les 300 d'un coup. Le premier qui touche 3 flèches (ou 1 dans la tête) gagne.

Deux cartes :
- **Canyon** : face à face sur deux piliers, on ne peut que se décaler sur le côté pour esquiver.
- **Forêt** : déplacements libres avec un joystick, arbres et rochers pour se cacher ou foncer sur l'adversaire. On y choisit son arme :
  - **Arc** (par défaut).
  - **Arbalète** avec lunette x1,5 : ses carreaux tombent et volent comme une flèche tirée à fond, et tuent d'un coup où qu'ils touchent.
  - **Carabine** de chasse en bois avec lunette x3 : les balles ne tombent pas et vont deux fois plus vite qu'une flèche.
  - **Batte** de baseball : corps à corps (portée environ 2 m, devant soi), 100 HP par coup, et on court 3 fois plus vite.

Pour jouer : https://gab22222.github.io/duel-arc/

- Un joueur appuie sur **Créer une partie** et donne le code aux autres, qui le tapent puis appuient sur **Rejoindre**.
- **À 3 (1v1v1)** : si trois joueurs sont dans le salon, la partie démarre quand les trois ont appuyé sur **Prêt**. On joue en forêt, chacun part d'un côté, le dernier debout gagne. Les adversaires sont en rouge et en jaune.
- Gauche : glisser pour se déplacer (joystick en forêt). Droite : maintenir pour bander l'arc, glisser pour viser, relâcher pour tirer.
- Aucun compte n'est nécessaire. Le multijoueur passe par un relais MQTT public (broker.emqx.io).
