# AAV évalué

A la fin du cours d'AP1, les étudiants seront capables d'écrire en binome un programme fonctionnel (correct ?) en Python de quelques centaines de lignes, en suivant un cahier des charges (cf. liste des projets de 2018-2019).


# Evaluation en deux temps

* Evaluation formative
* Evaluation certificative

# Evaluation formative

On demande à tous les binômes de programmer en Python en 15 jours un jeu de bataille navale.
Ils doivent rendre au jour J :
* une documentation du jeu vidéo programmé
* un programme en Python
Ils doivent préparer une soutenance :
* ils devront faire une démonstration du jeu vidéo
* ils devront défendre leur production pendant 15 minutes

Warning : on doit demander de pouvoir placer x bateaux


**On observe :**
* est-ce que le jeu fonctionne ?
* est-ce qu'il y a de la documentation ?
* est-ce que le code est lisible ?
* est-ce qu'il y a des tests ?
* qu'elle est la complexité cyclomatique
* l'investissement et la répartition des taches dans le binôme
* est-ce que, d'après eux, les étudiants ont appris quelque chose au cours de la soutenance ?
	("S'il fallait le refaire, qu'est-ce que tu changerais ?")
* est-ce que le rapport est en cohérence avec la démonstration du soft ?


**On n'observe pas :**
* Le temps de travail passé pour produire le rendu

# Evaluation certificative

La même chose, mais :
* les binômes choisissent un sujet dans une liste (qui ne contient plus la bataille navale !)
* les étudiants ont 1 mois pour réaliser le projet

## Proposition de grille critériée

Critère 1 : fonctionnement du jeu

critères :
----------
a) le jeu fonctionne
b) le jeu réponds au cahier des charges (ex. : lorsque l'on joue, on ne voit pas la grille de l'adversaire) 
c) l'interface est ergonomique
d) les éléments de régles du jeu sont valides (ex. : la règle de placements des bateaux ; plouf, en vue, touché/coulé ; conditions de fin de jeu)
e) Quid de la qualité du code (est-ce qu'il y a de la documentation ? est-ce que le code est lisible ? est-ce qu'il y a des tests ? qu'elle est la complexité cyclomatique)
f) Investissement et la répartition des taches dans le binôme
g) est-ce que le rapport est en cohérence avec la démonstration du soft ?

Attention :
* b est trop large, probablement
* pas beaucoup sur le rapport

Niveau de la grille : Excellent/Bien/Passable/Insuffisant

* est-ce que, d'après eux, les étudiants ont appris quelque chose au cours de la soutenance ?
	("S'il fallait le refaire, qu'est-ce que tu changerais ?")


## Exemple de grille critériée en AP2


### Fonctionnalités obligatoires (11 pts)


* Tâche 1 (2 pts) : fonctions lire_grille, affiche_grille et ecrire_grille (sans les cases noircies).
	* 0 points : Rien ne fonctionne ou presque
	* 1 points : Quelques bugs gênants
	* 2 points : Parfait ou bugs mineurs

* Tâche 2 (3 pts) : fonctions sans_conflit, sans_voisines_noircies et connexe.
	* 0 points : Aucune des fonctions n'est correcte
	* 1 points : Une fonction correcte
	* 2 points : Deux fonctions correctes
	* 3 points : Trois fonctions correctes

* Tâche 3 (3 pts) : interface graphique - ergonomie et jouabilité, apparence, présence d'un menu, annulation de coups.
	* 0 points : Ne fonctionne pas ou plante rapidement
	* 1 points : Fonctionnalité minimale permettant de jouer
	* 2 points : Interface satisfaisante, sans plus
	* 3 points : Joli, jouable et stable, présence de menu, fonction annuler

* Tâche 4 (3 pts) : solveur.
	* 0 points : Non implémenté
	* 1 points : Début d'implémentation
	* 2 points : Quelques bugs mineurs
	* 3 points : Solveur fonctionnel sur des grilles de petite taille


### Qualité du projet (7 pts)


* Respect des consignes (1 pt) : travail en binôme, respect des consignes de rendu (format, etc.).
	* 0 points : À améliorer (mauvais format d'archive ou de rapport, travail seul ou à trois)
	* 1 points : Correct (archive ZIP, rapport en PDF ou HTML, travail réellement en binôme)

* Qualité du code (2 pts) : clarté, absence de code redondant, introduction de variables et fonctions auxiliaires, choix des identificateurs, commentaires, tests. On insistera principalement sur la structure et la propreté du code.
	* 0 points : Code redondant, maladroit ou obscur
	* 1 points : Maîtrise correcte du langage (introduction de variables auxiliaires, de fonctions, bon usage des types)
	* 2 points : Style et structure de code satisfaisants, commentaires, tests

* Qualité du rapport (2 pts) : clarté, utilité. On insistera principalement sur le contenu du rapport plus que sur la forme (mise en page, etc.).
	* 0 points : Rapport vide ou très insuffisant
	* 1 points : Rapport informatif, quelques manques
	* 2 points : Rapport complet, lisible et intéressant

* Qualité de la soutenance (2 pts) : on prendra en compte de manière individualisée la qualité des réponses aux questions.
	* 0 points : Compréhension faible.
	* 1 points : Quelques éléments compris.
	* 2 points : Bonne compréhension d'ensemble.
	* 3 points : Très bonne compréhension.

* Améliorations éventuelles (2 pts) : on évaluera la qualité et la pertinence des améliorations proposées (suggérées dans le sujet, ou personnelles).
	* 0 points : Aucune amélioration significative
	* 1 points : Une amélioration significative
	* 2 points : Plusieurs améliorations significatives
