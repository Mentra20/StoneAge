# Projet Informatique de Licence 3 Semestre pair : 
## l'Age de pierre | *Groupe : SAH | Pseudo : Mentra20*

Mon projet de Licence 3 portant sur le jeu [L'Age de pierre](https://www.philibertnet.com/fr/jeux-de-societe/8136-age-de-pierre-l--8435407629387.html).  
### [Le syllabus du cours](https://github.com/Mentra20/StoneAge/blob/master/doc/Syllabus.pdf).

#### Concerant le repository github du projet : 
Le projet consistait à recréer le jeu version console avec différentes IA jouant les unes contres les autres (pas de graphique, pas de vrai joueur).  
Le projet est entièrement en java et inclus un Maven Project.  
Dans le repository du projet vous trouverez les itérations que mon groupe et moi même avons choisis de faire ainsi que le code source de notre jeu. Egalement toutes les issues (close) utilisées dans un kanban pour la répartition du travail.   
Dans l'onglet contributor vous trouverez la répartition globale du travail de chacun dans le projet en ajout et suppression de code ainsi que le nombre de commits (Mon pseudo : Mentra20).  
Tout les détails de l'UE sont contenues dans le syllabus.

#### Vous pouvez trouvez les règles du jeu [ici](https://github.com/Mentra20/StoneAge/blob/master/doc/lage-de-pierre-regle.pdf) les cartes batiments [ici](https://github.com/Mentra20/StoneAge/blob/master/doc/batiments.pdf) et cartes civilisations [là](https://github.com/Mentra20/StoneAge/blob/master/doc/Cartecivilisation.pdf) ainsi que leur [effets](ttps://github.com/Mentra20/StoneAge/blob/master/doc/description_carte.pdf) à chacunes.  

#### Le projet fut présenté devant un jury de 4 professeurs d'informatique. [(les diapositives de la présentation)](https://github.com/Mentra20/StoneAge/blob/master/doc/DiaposPresentation.pdf).
 

# projetinfo-2019-stoneage-sah  
projetinfo-2019-stoneage-sah created by GitHub Classroom  
  
Nom/prénom des membres du groupe:  
-Iopama : Goulot Thomas  
-Idrash : Tognetti Yohann  
-Mentra20 : Martin d'escrienne Yann  
-Theoricien : Jerome Maxime  
-AnthonyS06 : Santi Anthony  
  
## Première Itération:        
-1 joueur.      
-1 figurine.    
-1 zone de ressource.  
première version de l'inventaire du joueur.  
phase de jeu, l'IA (pas encore vraiment développée) posera donc sa figurine dans la seule zone disponible, viendra donc la phase où il reçoit sa ressource, puis la fin du tour de jeu.  
la valeur sera constante pour la récolte de ressource.  
pas de dé.  
fin du jeu a la fin du tour, le joueur est gagnant.  
  
## Seconde itération:  
-2 joueurs  
-le joueur commence avec 5 figurines.  
-ajout des zones de ressources manquantes (sauf nourriture)  
-ajout du système de dé  
-ajout du système de récolte "semi complet", avec le lancer de dé.  
-développement d'une première IA simpliste, jouant au moins une figurine dans une zone aléatoire.  
-Le premier tour ne se termine pas tant que l'IA ne pose pas toutes ses figurines (première boucle de jeu).  
-Si possible, ajout de la cabane de reproduction et de ses contraintes (optionnel).  
-Il y a victoire d'un joueur si un joueur a au moins 1 de bois.  
  
## Troisième itération:  
-Ajout d'un second joueur.  
-Ajout du champ ainsi que du système l'accompagnant.  
-Ajout de la cabane de reproduction et de ses contraintes si non fait.  
-ajout de la zone de chasse ainsi que du système complet de nourriture.  
-Finalisation du système de tour, le joueur doit désormais nourrir les figurines avant que le tour termine.  
-Un ou plusieurs joueurs gagnent dès qu'ils ont plus de 1 bois au moins.  
  
## Quatrième itération:  
-Avant le lancement du programme, nous demandons à l'utilisateur combien veut-il de joueur dans sa partie, ce nombre sera compris entre 2 et 4  
-Nous ajouterons la cabane de craft en guise de dernière zone spécial faisant parti du village  
-Pour continuer sur la boucle de jeu, nous améliorerons le système de manque de ressources pour un joueur, par exemple quand le joueur n'a plus assez de nourriture pour nourrir ses figurines au début d'un nouveau tour, il aura le choix entre conserver ses ressources collectables ou de perdre des points de victoire  
-Nous ajouterons alors un système de point de victoire rudimentaire  
-Nous ajouterons un protytpe de bâtiment et de carte qui seront de nouvelles zones spéciales.  
  
## Cinquième itération:  
-Ajouts de (presque) toutes les cartes et bâtiments  
-Ajout d'une nouvelle IA  
-Affinement de la boucle de jeu, on assiste à une partie normale avec des conditions de victoires réalistes  
-Améliorer la maintenabilité du code  
  
## Sixième itération:  
-Ajout des regles en fonction du nombre de joueur  
-Ajout d'un système de statistique disponible pour l'utilisateur  
-Ajouts des IA intéressantes à implémenter pour tester une stratégie avancée  
-Ajout de la carte civilisation manquante  
  
## Juste avant rendu:  
-Affinement du système statistique pour une utilisation plus user-friendy et correction de possibles bugs.  
-Affinement ou ajout d'IA, on propose à l'utilisateur un système avancé et propre.  
-Améliorer la maintenabilité du code.  
-Finalisation des test unitaire.  
