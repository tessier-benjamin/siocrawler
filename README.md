#project sioCrawler#

préentation du project : le but est de réaliser un jeu de role permettant un jeu peu massivement  multi joueur permettant aux étudiants du bts sio de se divertir pendant les heures de cantine mais surtout d'améliorer leurs compétences en developpement.

Les outils mis en oeuvre :

* git
* Visual Studio
* Mysql
* Apache

Le développement tourne autour de 3 grandes parties 

1. l'inscription en ligne
2. développement du jeu en lui même permettant l'exploration d'un labyrinthe 
3. la sauvegarde des personnages et du contexte du jeu

|      **développement**      | **langages** |          **technique de programmation**       			|
|-----------------------------|:------------:|---------------------------------------------------------:|
| inscription en ligne		  | php, Mysql   |   développement web MVC avec Code Igniter    			|
| sio crawler le jeu          | c#           |   programmation objet, tests unitaires        			|
| sauvegarde du contexte      | c#, Mysql    |   programmation procédural procédures stockées en Mysql  |

#L'inscription en ligne.#
site web permettant à un joueur de s'inscrire en ligne le projet prévoit le principe suivant pour l'inscription en ligne.
![acteurFluxInscription.png](C:\Users\btessier\Desktop\git\imagesTpGit\acteurFluxInscription.png)

#sio crawler le jeu #
le joueur possédera les fonctionnalités suivantes

![useCasePersonnage.png](C:\Users\btessier\Desktop\git\imagesTpGit\useCasePersonnage.png)

les classes développées

![diagrammeClassePersonnage.png](C:\Users\btessier\Desktop\git\imagesTpGit\diagrammeClassePersonnage.png)

#Sauvegarde du contexte#
la sauvegarde du contexte se fera dans la base de données

![mcdSauvegarde.png](C:\Users\btessier\Desktop\git\imagesTpGit\mcdSauvegarde.png)
