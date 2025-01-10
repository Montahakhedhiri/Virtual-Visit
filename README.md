Ce projet utilise Three.js pour afficher un panorama interactif à 360° à l'intérieur d'un cube.

Fonctionnalités
Exploration à 360° : Visualisez un environnement immersif en pivotant autour du panorama.
Contrôles interactifs : Navigation fluide avec la souris.
Textures dynamiques : Génération automatique des faces du cube à partir d'une seule image.

Clonez ou téléchargez ce projet :
bash

Copier le code
git clone https://github.com/votre-repo/panorama-threejs.git
cd panorama-threejs

Lancez un serveur local avec npx serve :

bash
Copier le code
npx serve
Ouvrez l'URL fournie par serve (généralement http://localhost:3000) dans votre navigateur.

Structure des Fichiers
bash
Copier le code
.
├── index.html           # Fichier principal
├── main.css             # Styles de la page
├── textures/            # Dossier des textures
│   └── cube/
│       └── sun_temple_stripe.jpg  # Texture atlas pour le panorama
├── js/
│   └── addons/
│       └── controls/
│           └── OrbitControls.js  # Module pour les contrôles interactifs

Explication du Code : 

index.html : Initialise la scène, la caméra, le cube et les contrôles interactifs.
main.css : Définit les styles pour la présentation visuelle.
Texture Atlas : L'image sun_temple_stripe.jpg est découpée en 6 parties, une pour chaque face du cube.
Technologies Utilisées
Three.js : Moteur 3D pour WebGL.
OrbitControls.js : Fournit des contrôles interactifs pour naviguer dans la scène.
