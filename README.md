# Deuxième_relase_Video_game
# Documentation du Jeu

## Structure de la Démo:

Le projet est actuellement composé de :

Menu Principal : Interface d'accueil permettant de lancer la partie ou de quitter le jeu.

2 Niveaux : Deux environnements testant les mécaniques de mouvement et la difficulté .

## Systèmes de Base :

Mouvements et Collisions

Le moteur de jeu intègre un système de physique gérant :

Les déplacements horizontaux et le saut.
Une détection de collision précise avec le décor (sol, murs, plafonds).
La gestion de la friction et de la gravité pour un ressenti fluide.

## Nouveauté : Cross-Platform & Support Mobile
Le jeu intègre désormais le New Input System d'Unity, le rendant jouable sur de multiples plateformes (PC et mobile) :

Support Universel : Jouable au Clavier/Souris, à la Manette(non testée) et sur Écran Tactile.

Interface Mobile : Format paysage forcé. L'interface tactile se masque automatiquement si le jeu est lancé sur PC.

Joystick Dynamique : Un joystick de déplacement flottant qui apparaît exactement là où le joueur pose son pouce.

Boutons d'Action avec contexte : Les boutons tactiles pour faire les action, les capacités spéciales  n'apparaissent sur l'écran qu'une fois la capacité débloquée en jeu.

## Système de Vie:

Le joueur possède une jauge de santé :

Dégâts : Réduction de la vie lors d'un contact avec un ennemi ou un piège.

Mort : Reset du niveau ou retour au dernier checkpoint une fois la vie épuisée.

Ennemie: les ennemie peuvent être tuée.

## Système de Power-ups

Des objets ramassables sont présents dans les niveaux pour modifier les statistiques ou capacités du joueur.

  -Double Saut

  -Wall-climb (Saut mural)

  -Dash

## Ennemis

Le jeu propose deux types d'Intelligence Artificielle :

Ennemi de Patrouille : Se déplace selon un itinéraire fixe (va-et-vient) .
Ennemi de Traque : Reste immobile, mais se met à poursuivre activement le joueur dès que celui-ci entre dans son rayon de détection.

## Liste des Pièges

j'ai fait tout un ensemble de piège :

Piques : Fixes au sol ou au plafond, infligent des dégâts immédiats au contact.
Lanceur de flèches : Mécanisme tirant des projectiles à intervalles réguliers.
Piège de feu : Jet de flammes déclenchée des que le joueur est détectée au contact.
Scie : Obstacle mobile suivant un mouvement horizontal.
Spikeheads : Blocs épineux qui foncent sur le joueur lorsqu'il est détecté à proximité.
