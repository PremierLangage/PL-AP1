# Formation approche programme

27, 28 et 29 mai 2019


## Raisons pour participer

rationnaliser (en particulier évaluation)
qualité (exos, etc.)
pertinence


## Idées d'AAV

- rédaction d'un rapport écrit (y compris aspects techniques)
- lecture d'un énoncé / cahier des charges / passage d'article
- synthétiser une idée en quelques phrases


## Notes diverses

- apprentissage de l'auto-évaluation : en commençant par de l'évaluation des
  pairs ?
- apprentissage par problème : comment gérer
    + l'hétérogénéité (de niveau et de motivation)
    + la triche (?)
    + l'évaluation sommative
- Gestion des tuteurs (M1/M2) : récompensé par 3 ECTS, non payé

## Exercice AAV : cours "labos math-info" de S3 math et S3 info

Participants : PMS, DD, FR, AM

### AAV sur la représentation informatique des objets

(Pré-requis : avoir réussi la L1 math / info de l'UPEM ou équivalente)

À la fin du module, chaque élève sera capable :
- d'*élaborer une représentation informatique*  d'une *classe d'objets
  mathématiques connue*, qui permette de réaliser de manière *effective* une
  liste donnée d'*opérations* sur les objets de cette classe ;
- de démontrer que la représentation informatique proposée d'une classe
  d'objets est *correcte* ;
- de décrire les *caractéristiques* d'une représentation informatique donnée
  d'une classe d'objets ;
- de *discuter* la pertinence du choix d'une représentation parmi plusieurs
  représentations données d'une même classe d'objets et pour un usage donné ;
- programmer en Python les *opérations de base* ou des *algorithmes plus
  élaborés* sur les classes d'objets considérés et dans les représentations
  envisagées (données par l'enseignant ou mises au point par l'élève).


**Définition des termes en italique :**
- Élaborer une représentation informatique (d'une classe d'objets) :
  (construire / choisir / déterminer ?) (à l'aide des types de base et
  types construits de Python)
- Classe d'objets mathématiques connue : vue en L1 : complexes, polynômes,
  matrices, etc.
- Correction d'une représentation : le fait qu'elle est non ambiguë, qu'elle
  préserve les propriétés mathématiques des objets représentés.
- Discuter : (comparer ?) (de manière informelle ?) (avantages et inconvénients
  ?)
- Caractéristiques d'une représentation : en terme d'efficacité (complexité
  algorithmique : temps de calcul, consommation mémoire), de complexité de mise
  en oeuvre, etc.
- Opérations élémentaires sur une classe d'objets : ...  (addition,
  multiplication, etc.)

**Remarques :**
- Termes pas évidents à comprendre pour des non-spécialistes (ex:
  représentation info des données)
- Détailler certains termes en annexe (représentation, "discuter")
- Préciser les mises en situation et modes de travail possibles (individuel,
  binômes, groupes...)
- Le verbe discuter -- intéressant et important mais pas évident à faire ni à
  évaluer, est-ce appris ici, est-ce un pré-requis, est-ce transversal ? OUI,
  mais il faut quand même l'inclure partout où c'est pertinent.
- Préciser les ressources documentaires autorisées (fait partie de la
  responsabilité de l'enseignant, pas de "meilleur" choix). Attention,
  implique de former les étudiants à l'usage des documents (en particulier en
  examen). Peut constituer un AAV à part. A DISCUTER (en particulier en math).


### Autres idées d'AAV

- Revisiter convergences de suites, calculs de sommes, estimation asymptotique.
- Travailler l'esprit d'expérimentation, d'exploration, de bidouille...

## Exercice AAV transversaux : compétence transversale "apprendre à apprendre"

Avoir appris à apprendre, c'est être capable de :
- rechercher l'information :
    + identifier les media favorables à son propre apprentissage ;
    + localiser une information spécifique (définition, énoncé de théorème,
      description d'un concept, etc.) dans les ressources documentaires
      fournies par les enseignants ;
    + interagir avec les pairs, les enseignants... pour résoudre un problème ;
    + rechercher et sélectionner une information manquante en tirant parti des
      ressources documentaires disponibles (bibliothèque, Internet...) ;
- entraînement, auto-évaluation, bilan :
    + choisir son niveau de performance visé et ses objectifs d'apprentissage ;
    + résumer en quelques phrases les apprentissages visés par un (chapitre
      d'un) cours (synthétiser, extraire les points essentiels, établir un
      plan);
    + faire un bilan de la progression de son apprentissage sur l'ensemble du
      programme (de la formation, du cours...) ;
    + reproduire seul·e une tâche d'apprentissage antérieure, plus ou moins
      récente (exercice, démonstration, résumé...) et évaluer la qualité de son
      travail sur cette tâche ;
    + mettre au point ses propres activités d'apprentissage ;
- méthodologie :
    + organiser son temps de travail en fonction de ses objectifs
      d'apprentissage personnels (stratégie, planning) ;

## Exercice évaluation formative des AAV

### Tentative 1

Situation : l'enseignant fournit (explication + exemples) une classe d'objets,
une représentation et une ou plusieurs opérations, éventuellement quelques
rappels mathématiques utiles.

Prestation attendue : programme en Python, constitué de fonctions, qui réalise
les opérations demandées, illustré d'un ou plusieurs tests sur les exemples
fournis.

Modalités : travail sur machine, de préférence seul, avec accès à la
documentation, au cours et à internet, en temps limité à l'intérieur d'une
séance, avec une liste précise de modules externes autorisés.

Observation : ...

Curseurs : quantité de travail demandée, temps disponible, travail à la maison
possible ou non, etc.

Questions : de quella manière faire référence à d'autres AAV ?

### Tentative 2

Situation : l'enseignant fournit une classe d'objets et une ou plusieurs opérations ou questions portant sur ces objets.

Prestation attendue : un dossier consitué de plusieurs éléments,
- étude mathématique a priori, synthétique, concernant les objets concernés
  (définitions et propriétés utiles) et la ou les questions posées -- peut consister en une synthèse de cours ;
- proposition de représentation des objets, incluant une preuve de son
  adéquation ;
- algorithmes de calcul des opérations demandées ou de résolution des questions
  posées ;
- analyse des algorithmes le cas échéant (preuve de termination, correction,
  complexité) ;
- implémentation en Python, incluant documentation, tests et démonstration.

Modalités : précisions concernant le volume du dossier, le travail en groupe...

Observation : ...

## Exercice grille d'évaluation critériée

Critère 1 : Spécification (*doctring*)
- A : présente, complète, correcte, inclut le type des pramètres et du
  résultat, les cas particuliers éventuels, les cas d'erreur éventuels ;
- B : présente, mais maladresse d'expression, ou absence d'un des détails
  précédents ;
- C : présente mais manque de plusieurs critères ;
- F : absente, fausse ou vide de sens.

Critère 2 : Test (*doctests* ou autres)
- A : présence de tests assurant une bonne couverture du code, incluant tous
  les cas particuliers et les erreurs
- B : absence de test pour quelques cas significatifs (<25%)
- C : absence de tests pour trois cas significatifs ou plus (<50%)
- F : absence de tests pour plusieurs cas (>= 50%) ou tests non pertinents

Critère 3 : Lisibilité
- A : identificateurs bien choisis, présence de commentaires là où c'est utile,
  respect des conventions de présentation
- B : au moins un point obscur non documenté ou un identificateur mal choisi
- C : le nom de plusieurs variables de donne aucune indication sur son rôle,
  aucun commentaire
- F : code obscur

Critère 4 : Effectivité (le code produit un résultat correct en temps fini)
- A : résultat correct sur tous les cas testés
- B : erreur mineure sur toutes les instances ou erreur majeure sur quelques
  cas
- C : quelques erreurs gênantes
- F : aucun résultat correct ou presque, ou code non exécutable

Critère 5 : Efficience (le cas échéant)
- A : algorithme clair, de complexité optimale dans l'état des connaissances
  attendu
- B : algorithme correct mais non tout à fait optimal
- C : algorithme nettement plus complexe que l'attendu (en temps et/ou en
  mémoire)
- F : algorithme défaillant ou incapable de résoudre les instances de la taille
  demandée


## Exercice AAV terminaux pour la licence d'informatique

- Un truc sur le développement d'un logiciel répondant à un problème en partant
  d'un cahier des charges pré-établi
    + Écosystème technique, outils
    + Méthodes, pratiques appropriées
    + Spécification, test, validation...
    + Relations entre théorie et pratique, processus de mise en oeuvre

- Un truc sur l'algorithmique, les structures de données, les modèles de calcul
    + Maîtrise de la complexité algorithmique
    + Terminaison, correction
    + Relations entre théorie et pratique, processus de mise en oeuvre
    + Faisabilité, existence d'une solution, optimalité

- Un truc sur les compétences transversales
    + Apprendre à apprendre, extraire de l'information, qualifier le statut
      d'une ressource (primaire, secondaire...), travailler de manière
      autonome, formuler des questions
    + Communiquer (écrire un compte-rendu, présenter oralement, documenter un
      objet technique)
    + Raisonner, argumenter, démontrer, choisir, critiquer
    + Un truc sur les math (discrètes ou autres)
    + Un truc sur la méthodo du travail (seul ou en équipe) : gestion des
      délais, découpage des tâches, retours d'expérience

### Tentative de rédaction

À l'issue de la formation, l'étudiant de licence d'informatique de l'UPEM sera en mesure de :

- Concevoir, développer et valider un logiciel de taille modeste répondant à un
  cahier des charges pré-établi
    + en utilisant et en prenant en compte tous les aspects et contraintes de
      l'environnement technique (logiciel et matériel) ;
        * explorer et manipuler le système de fichiers
        * accéder aux ressources matérielles de la machine (entrées / sorties,
          disques, mémoire), les partager
        * accéder aux ressources du réseau
        * etc.
    + en utilisant à bon escient les outis de développement appropriés ;
        * compilateur,
        * gestionnaire de versions et de tickets,
        * débuggueur, profileur,
        * gestionnaire de test,
        * environnement de développement, etc.
        * make
        * archiveur
    + en observant des pratiques de développement qui favorisent la qualité du
      programme ;
        * nommage des variables
        * conventions syntaxiques
        * style
        * documentation
        * modularité
        * barrières d'abstraction (API)
        * consignes de rendu
        * portabilité
    + en démontrant la conformité aux spécifications ;
        * choix de tests pertinents
        * identification des cas particuliers
        * couverture
        * cas exceptionnels, erreurs
    + en tirant parti des fondements théoriques pertinents
        * algorithmes classiques, complexité
        * méthodes logicielles de haut niveau (analyse syntaxique et
          compilation)
        * avoir un modèle fiable de "la machine"
        * logique, raisonnement

- Décrire, analyser et choisir des algorithmes et des structures de données
  permettant de résoudre un problème (algorithmique)
    + en interrogeant l'existence d'une solution effective et/ou efficace (?) ;
    + en faisant appel aux principaux types d'algorithmes et méthodes de
      résolution connus (approche récursive, programmation dynamique,
      heuristiques...) ;
    + en fournissant une preuve de correction (terminaison, correction
      partielle par invariant ou par récurrence) ;
    + en quantifiant les coûts (en temps, en mémoire) et en analysant les
      caractéristiques (stabilité...) des algorithmes ;
    + en choisissant la solution la plus appropriée et en justifiant ces choix
      ;


## Plan de bataille

- Créer un conseil pédagogique de la licence d'info
    + Responsables de formations + responsables de matières + volontaires
    + Grande statégie (AAV, APProjets, APProblèmes, modalités, MCC, Conception
      de la maquette)
    + Discussion sur la méthode de travail des enseignants, la formation des
      non-titulaires, clarification des tâches (fiche mission)
    + Organisation des services dans la licence
    + Organisation d'assemblées    

- POC L1
    + AAV terminaux de la licence d'info
    + AAV d'AP1 et AP2 (si possible PW) + LMI
    + Dégager des heures payées sur une matière pour des réunions pédago
      régulières
        * Exemple : en AP1, réduire le nombre d'heures de présentiel, organiser
          une réunion hebdomadaire obligatoire d'une heure
    + Préciser les modalités d'évaluation en AP1
        * Mettre en place des expérimentations de grilles critériées sur des
          évaluations choisies
    + Libérer une séance de TP (pour faire du PL)
    + 1 séance de TD (... non terminé)
