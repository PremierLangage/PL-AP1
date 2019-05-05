

# AAV

## Interaction avec l'interpréteur

En mode REPL

Décrire et utiliser correctement la boucle d'interaction de l'interpréteur Python

lecture d'une ligne

évaluation

affichage du résultat (sans print)

Décrire l'ensemble des identifiants connus par l'interpréteur en cours de session

Importer un module et explorer son contenu depuis l'interpréteur

En mode "programme / script"

Utiliser les fonctions prédéfinies permettant la saisie (input) et l'affichage (print) dans un programme lancé depuis un terminal

Récupérer les arguments fournis en ligne de commande


## Valeurs, types, expressions

PL: Identifier la nature de chaque élément lexical dans un programme (mot-clé, identificateur, ponctuation, opérateur, etc.), éventuellement à l'aide de l'outil de coloration syntaxique de l'environnement de travail

PL: distinguer les variables des mots-clefs

PL: distinguer les variables en opposition aux littéraux

Décrire la sémantique des principaux opérateurs pour les principaux types (+, -, *, /, //, %, **, and, or, not, ==, <, > <=, >=, !=)

PL: identifier les types possibles des opérandes d'un opérateur

PL: calculer de tête le résultat d'une opération binaire 

PL: Identifier le type et la structure d'une expression (notion d'expression elle-même, priorité des opérateurs, type du résultat)

PL: identifier le type d'une valeur littérale

PL: identifier le type et la valeur d'une expression composée (nombre entier, nombre flottant, chaîne de caractères, booléen)

PL: identifier le type et la valeur courante d'une variable

PL: Connaître les principales conversions possibles entre valeurs de différents types (fonctions int, float, str, etc.), 

PL: classer les convertions:   simple, dangeureuses, impossibles (TODO: un meilleur classement). 


## Variables et affectation

### Notions

Décrire la notion d'espace de noms et leur imbrication (prédéfini, global, local, structuration en pile)

Décrire la notion de tas (allocation de valeurs, garbage collection)

Construire un modèle mental de la mémoire Python 

association entre nom et valeur, (notion de "fil", flèche, etc.)

représentation de type Python Tutor explicite (avec toutes les flèches)

Comprendre les différentes étapes de l'instruction d'affectation

PL?: identification de la valeur gauche (variable éventuellement nouvelle, ou élément d'objet mutable)

calcul de la partie droite (évaluation d'expression), création et/ou localisation d'un objet dans le tas

association ("tirer un fil")

distinction avec l'opérateur d'égalité

Décrire le phénomène d'aliasing (deux références vers le même objet)

(éventuellement) décrire la différence entre l'opérateur == et l'opérateur is

(éventuellement) décrire la manière dont Python gère la création ou la réutilisation des objets

### Savoir-faire

PL: Construire à la main une représentation de la mémoire à l'issue de l'exécution d'un programme contenant des affectations, suivre une suite d'allocation 


PL: Donner la liste des identificateurs accessibles en tout point d'un programme

Choisir un nom approprié pour une variable selon son rôle


## Conditionnelles

Nommer, écrire, reconnaître les deux valeurs booléennes de Python

(éventuellement) connaître la façon dont une valeur non-booléenne est interprétée comme un booléen

Exprimer à l'aide d'une expression booléenne certaines conditions utiles

nullité d'une valeur

appartenance d'une valeur à un intervalle (numérique, lexicographique...)

condition de type "ou exclusif" entre deux valeurs booléennes

divisibilité d'un nombre par un autre

appartenance d'un point à une partie du plan définie par plusieurs inégalités

Construire un programme simple réalisant un traitement conditionnel

syntaxe correcte (if <condition>: ...)

bonne gestion de l'indentation des blocs

bon usage de if, else, elif, etc.

Prédire et expliquer l'ordre dans lequel les lignes d'un programme contenant des blocs conditionnels seront exécutées en fonction des données fournies (préparation à la notion de couverture de code pour les tests)

Simplifier, quand c'est possible, une imbrication de blocs conditionnels en utilisant des opérateurs booléens (and, or, not), et réciproquement éliminer les opérateurs booléens d'une condition en introduisant de nouveaux blocs conditionnels

(éventuellement) Illustrer sur quelques exemples la sémantique paresseuse des opérateurs logiques (exemple : b > 0 and a / b > 1)



## Boucles

### Savoir Faire 

Répéter un nombre de fixé de fois un traitement simple (boucle for _ in range(n)   rem: sans utiliser la variable de boucle )

Répéter un nombre de fixé de fois un traitement simple utilisant le numéro de l'itération courante (boucle for i in range(n))

Répéter un nombre de fixé de fois un traitement simple en utilisant une variable de boucle non triviale

for i in range(inf, sup, pas)

i = 0; while i < limite: i *= 2 blockdinstructions

Utiliser les instructions break et continue pour contrôler l'exécution d'une boucle

### Notions

Distinguer itération bornée (nombre de tours connu à l'avance) d'une itération non bornée (nombre de tours inconnu)

Dans le cas d'une boucle non bornée, 

Argumenter de la terminaison du programme (preuve de terminaison), de manière formelle ou informelle

Compter le nombre d'exécution du corps de la boucle en fonction des valeurs initiales des variables (approche de la notion de complexité)


Énumérer une suite d'objets simples (suite de nombres, chaînes de longueurs croissantes, suite mathématique simple...)

Choisir à bon escient la condition d'arret/ la condition de continuation et la valeur initiale de la variable de boucle éventuelle

Traduire un algorithme de type "répéter jusqu'à..." en algorithme de type "répéter tant que...", puis en un programme Python utilisant une boucle "while"


## Fonctions 

### Notions

fonction

appel

parametre 

valeur de retour

doc

doctest

### Savoir faire 

Décomposer un algorithme en fonctions 

Eviter d'écrire des fonctions trop longue ou trop compliquées 

différencier les fonctions des instructions 

Comprendre l'intérêt d'écrire des fonctions

Identifier quelles fonctions Python ont déjà été utilisées depuis le début du cours (print, input, str, ...) et indentifier leurs paramètres et valeur de retour

Distinguer fonctions et programme principal

Ecrire des fonctions réalisant l'évaluation d'un polynome a une variable

Ecrire des fonctions réalisant l'évaluation d'un polynome a plusieurs variables

Ecrire une documentation d'une fonction  

Ecrire des doctests d'une fonction

Tester ses fonctions grace aux doctests

Savoir décomposer un problème en un ensemble de sous-problèmes

Décrire pas à pas l'éxécution d'un programme contenant des fonctions

Décrire l'états de l'ensemble des variables d'un programme pendant l'exécution de fonctions 





## classe & Objets

     Accessibilité des composants un objet, espace de nom d'un objet 

     identifier champs/variables locales 

    ecrire une méthode d'objet 





## Random & autres paquetages de base 

    utiliser l'instruction import 

    utiliser  l'instruction from import  

    utiliser random pour produire des entiers, des tuples, de listes, des chaines, des floats aléatoires 



## Listes

### Notions

coût des opérations 

slices 

acces par index

acces par itérateur 

allocation (les listes cela prend de la place)

zip + unpacking 

### savoir faire 

Créer une liste vide 

créer une liste contenant une énumération d'entiers 

créer une liste contenant des entier aléatoires 

choisir aléatoiremenet dans une liste 

