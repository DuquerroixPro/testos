## projet sioCrawler ##

présentation du projet : le but est de réaliser un jeu de rôle permettant ... multi joueur permettant aux 
étudiants du bts sio de se divertir pendant les heures de cantine mais aussi d'améliorer leurs compétences en
développement 

les outils mis en oeuvre:

* git
* visual studio
* mysql
* apache

Le développement tourne autour de 3 grands parties

1. L'inscription en ligne
2. développement du jeu en lui même permettant l'exploitation d'un labyrinthe
3. la sauvegarde des personnages et du ... du jeu

|  **développement**  | **langages**|            **technique de programmation**           |
|---------------------|-------------|-----------------------------------------------------|
|inscription en ligne |php,Mysql    |développement web ... avec Code Igniter              |
|sio crawler le jeu   |c#           |programmation objet, tests unitaires                 |
|sauvegarde du ...    |c#, mysql    |programmation procédural procédures stockées en mysql|

**L'inscription en ligne**

site web permettant à un joueur de s'inscrire en ligne le projet prévoit le principe suivant pour l'inscription en ligne

![acteurFluxInscription](https://user-images.githubusercontent.com/63001648/93993255-cfb2b400-fd8e-11ea-95aa-9f7fd88d2b87.PNG)

### **sio crawler le jeu** ###

le joueur possède les fonctions suivantes

![useCasePersonnage](https://user-images.githubusercontent.com/63001648/93993253-cf1a1d80-fd8e-11ea-9a93-e4e0d21ce6e1.PNG)

**les classes développées**

![diagrammeClassePersonnage](https://user-images.githubusercontent.com/63001648/93993251-ce818700-fd8e-11ea-84cf-729f440d9c5d.PNG)

**Sauvegarde du contexte**

La sauvegarde du contexte se fera dans la base de données

![mcdSauvegarde](https://user-images.githubusercontent.com/63001648/93993252-cf1a1d80-fd8e-11ea-85b3-8d0eccf5703c.PNG)


