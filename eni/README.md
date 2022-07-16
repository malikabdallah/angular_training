# angular_training

le developpement angular se fait en se basant sur les outils de nodejs 
notamment npm
nodejs est un moteur d execution qui s execute cote serveur en oposition avec js cote navigateur.
il est utilise dans le dev web pour apporter un ensemble d outils a la machine de developpement.
npm (node package manager) est le gestionnaire de pacquets de node.js et permet d installer de nouveau module 
venant enrichir le runtime de node.js

# installion d angular 
1)installer nodejs
https://nodejs.org/en/
npm -v verifier la version
2)installer le cli 
les equipes ont mis en place un invite de commande pour creer une application from scratch et la manager
npm install -g @angular/cli
ng verfier le cli installer

#creer sa premiere application

ng new firstapp


#fondamentaux d angular

un composant est une classe exporant une vue et definisant la maniere d interagir avec elle via un fichier ts qui 
contient la logique. un composant est decore par @component
un composant peut etre composant de plusieur composant ,une application est donc l assemblage de ces elements .
il doit etre independant , reutilisable

le decorateur @component permet de consider une classe comme un composant ,il contient un ensemble de proprite definisant le 
comportement general d composant
-selector : la balise css identifiant le composant dans le template , chaque fois qu il sera rencontre angular creera une
nouvelle insance du composant
-template | templateUrl : le html decrit comment doit etre rendu le composant
-styleUrls:le css

#binding 