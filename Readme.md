# Escape-Game

## Contexte :



## Outils utilisés :

- Ordinateur sous MAC OS
- Mobile sous IOS
- VSCode
- XCode
- Unity
- Unity Assets Store
- Vuforia


## Technologies utilisées :

- XCode : Objective-C
- Unity : C#
- Vuforia : AR-SDK


## Fonctionnement général de l'escape game :

- L'utilisateur disposera d'une application sur mobile disponible uniquement sur IOS pour l'instant.

- Lorsque l'utilisateur lancera l'application, son appareil photo s'activera sur son écran.

- Grâce à cette application, l'appareil photo scane tous les objets réactifs de la pièce.

- Lorsque un indice est trouvé (Objet réactif), une scène possédant une énigme apparaitra sur l'écran de l'utilisateur.

- Une fois qu'une énigme a été résolue, l'utilisateur peut passer à n'importe quelle énigme. Il n'y a pas d'ordre spécifique à respecter dans la résolution des énigme de l'escape game.


## Fonctionnement des énigmes :

- Enigme de l'Oracle :
  
  On fait apparaître une personne qui va dire au début que certaines réponses sont cachées dans la salle.
  Il posera des questions classiques et des questions plus ou moins dures.

- Enigme sur la Famille :
  
  Trouver la personne dont il s'agit.
  Je suis son frère, mais ce n’est pas mon frère. Qui est-ce ?

- Enigme "Nomade des nations" :
  
  Trouver le nom des habitants du pays donné.

- Enigme des chiffres cachés :
  
  Il faut trouver le résultat de la dernière opération en s'aidant de la logique des précédentes.

- Enigme pièce mystérieuse :
  
  Il faut trouver le pays d'où provient la piece sur la photo, mais en 1 essai seulement.

- Enigme coffre caché + énigme :
  
  Il faut trouver un coffre caché dans une salle et trouver l’énigme cachée également.
  Elle est en mer extraordinaire,
  Sans lendemain et éphémère.
  S’y lancer pourrait être tragique,
  Sur Skyrim, elle est épique.

- Enigme en Morse :
  
  Déchiffrer le code inscrit en Morse.

- Enigme code des couleurs :
  
  rouge = 1 | Priorité = 1
 
  2 = uelb | Priorité = 2
 
  gris = 3 | Priorité = 3
 
  vert = 4 | Priorité = 4
 
  5 = teloiv | Priorité  = 5
 
  orange = 6 | Priorité = 6
 
  jaune = 7 | Priorité = 7
 
  Trouver un nombre de boules de couleurs indéfini et entrer le code.

- Enigme jeu "Super Simon" :
  
  Le jeu "Super Simon" apparaît, et on doit réaliser 15 niveaux du jeu sans erreurs.


## Problèmes rencontrés :

- Compatibilité de certains assets en URP (Universal Rendering Pipeline)
- Téléversement de l'escape game sur Android (A l'aide d'Android studio)
 

## Améliorations potentielles :

- Portage de l'escape game sur android
- Ajout d'un leaderboard qui classera en fonction du temps mis pour terminer l'escape game
- Exploiter les scènes d'énigmes vides (Création de nouvelles énigmes)
