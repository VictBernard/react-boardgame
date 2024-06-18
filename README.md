# Lancement du projet
Allez dans le dossier **`Serveur`** puis entrez la commande suivante : 
`json-server -p 1998 users.json`

Ensuite, dans le dossier **`Client/my-app`** lancez 
`npm install` 
puis 
`npm start`

# Contexte

Vous pouvez retrouver les détails de ce projet universitaire sur ce lien : https://cours-js.codenestedu.fr/

# Règles du jeu

## Règle de Fill :
- À tour de rôle les joueurs déposent un pion de leur couleur sur une case vide
- Si un joueur clique sur une case déjà remplie, alors il perd la partie (peu importe la couleur présente)

## Règle de Crush :
- À tour de rôle les joueurs déposent un pion de leur couleur sur une case vide
- Si un joueur clique sur une case déjà remplie par son adversaire il gagne la partie
- Si un joueur clique sur une case déjà remplie par sa propre couleur, il perd la partie



