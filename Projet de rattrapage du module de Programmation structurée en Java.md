**Projet de rattrapage du module de Programmation structurée en Java**


#INTRODUCTION :

Le rapport qui suit a pour objectif de valider le module de programmation structurée en Java. 
En effet, les lacunes et difficultés rencontrées au cours de la première année d’étude n’ont pas permis la validation de ce module, cette dernière étant nécessaire à la validation de la première année d’étude du cycle ingénieur.
Selon la consigne ayant été donnée, ce devoir devra comporter, avec une marge de dix pourcents, environ dix mille mots et se devra d’être une synthèse des connaissances et compétences acquises lors de cette formation. Ce rapport présentera également les difficultés que j’ai rencontrées ainsi que mes lacunes en la matière.

Afin de répondre au cahier des charges imposé, le rapport suivant sera composé de deux chapitres. Le premier exposera l’utilité des connaissances et compétences acquises lors de cette formation, à la fois dans mon cursus scolaire, mais aussi dans le travail que j’effectue en entreprise dans le cadre de ma formation en apprentissage. Il s’agira également d’expliquer le processus d’acquisition de ces connaissances et compétences.
Le second chapitre sera, quant à lui, consacré aux difficultés rencontrées lors de la première année de formation dans le module de programmation structurée en Java et tentera d’analyser  les lacunes dans ce domaine.



#Le Java dans mon cursus scolaire et en entreprise :

 **a- Le Java au sein du cursus scolaire.**

J’ai choisi de suivre le parcours proposé par l’ISEP intitulé « Les Systèmes embarqués ». Cette formation implique une certaine maîtrise du langage Java pour plusieurs raisons. L’objectif de cette partie est de mettre en avant les apports du Java et de la formation à ce langage informatique.

L’étude du Java à travers le module de programmation structurée en première année à l’ISEP à constitué ma première formation à ce langage. La programmation orientée objet dans sa globalité était d’ailleurs quelque chose de tout à fait nouveau pour moi. Etant débutant dans le domaine, j’ai dû acquérir les bases de ce langage. Les cours ont assuré la formation théorique et les divers travaux pratiques qui nous ont été proposés ont contribué de façon importante à l’acquisition des connaissances et des principes de base de ce langage. 
Il s’agissait donc dans un premier temps de comprendre la programmation orientée objet et d’apprendre ce que sont les différents éléments relatifs au Java tels qu’un objet ou une classe par exemple. Un objet est une structure de données qui permet de gérer des données, de les classer, et de les stocker sous une certaine forme. Autrement dit, un objet est une chose caractérisée par un ensemble de variables appelées attributs. Une classe est le modèle de quelque chose que l’on souhaite construire. Elle représente un ensemble d'objets qui partagent une structure commune. Les classes sont nommées selon la méthode camelCase mais commencent par une majuscule. Afin de mieux comprendre ces définitions et travaillant au sein de l’entreprise PSA, je souhaiterais illustrer cela à travers un exemple tiré du domaine de l’automobile. La classe Voiture servira à spécifier que tous les objets voiture ont une marque, une puissance, une année etc.

    
Exemple : 

Si ces données étaient codées en langage Java, voilà la forme que cela prendrait :
```sh
                  class Voiture {
                    int marque ;     // Marque de la voiture 
                    int puissance ; // Puissance de la voiture en chevaux
                    int annee ;    // Annee de sortie de la voiture
                  }          
```
      
Rappelons de plus que la programmation orientée est dirigée par trois fondamentaux qu'il convient de toujours garder à l'esprit : encapsulation, héritage et polymorphisme. Tout comme pour l'objet et la classe, je vais donner une définition simple de ces trois fondamentaux. 

**L'encapsulation :** l'encapsulation permet de rassembler les données et les méthodes au sein d'une structure en cachant l'implémentation de l'objet, autrement dit en empêchant l'accès aux données. 

**L'héritage :** le concept d'héritage est un des concepts les plus importants de la programmation orientée objet. L'héritage est un mécanisme permettant de créer une nouvelle classe à partir d'une classe existante en gardant les même propriétés et méthodes.

Exemple 2: 

Voici ce que cela donnerai si nous devions le coder en Java.
```sh 
                class Animal extends Object {
	                   // Corps de la classe 
                }
``` 

**Le polymorphisme :** il s’agit d’une technique particulière d'héritage. Elle consiste, lorsqu'on hérite d'une classe, à redéfinir l'une des méthodes pour la spécialiser.


Après avoir compris les règles et fondamentaux principaux de la programmation Java, j'ai pu dans un deuxième temps passer à la réalisation des codes. Il s’agissait au départ d’un code simple. 
Comme c’est fréquemment le cas de tout nouveau codeur et ce peu importe le langage de programmation, le premier code réalisé a été un "Hello World". Pour se faire, j'ai utilisé un ``System.out.print("Hello World !");``. Cela m'a permis d'afficher le fameux "Hello World" dans la console de l'IDE NetBeans. 
Suite à cette première expérience, je suis passé à une programmation plus complexe. J'ai effectué différents opérations telle que l’arithmétique, construit des tableaux à deux et trois dimensions, utilisé les structures "if ... else" et "switch" ou encore les boucles "for", "while" et "do ... while". Toutes les manipulations citées ci-dessus ont été effectuées et apprises à travers les différents travaux pratiques en cours.

Evidemment, comme pour toutes les matières enseignées, afin de rencontrer le moins de lacunes possible, le travail à la maison est vivement conseillé. Un des avantages du Java est qu'il y a de nombreuses communautés autour de celui-ci. Cependant, il est très facile de trouver des cours ou/et exercices sur le net. Ce qui m'a permis d'approfondir mes connaissances et mes compétences. 

Afin de mettre en pratique ce que nous avions appris, nous devions réaliser un projet de fin d'année. Ce projet consistait à réaliser le jeu Stream. Ce projet m'a été bénéfique car j'ai pu mettre en pratique ce dont j'avais appris tout au long du module de programmation structurée et par la même occasion à apprendre à créer des interfaces graphique. Pour réaliser ce projet, j'ai dù utiliser par exemple la classe scanner, qui à permis une saisie du pseudomine du joueur. De plus, les conditions telle que la structure if...else, les boucles ou encore les tableaux ont été nécessaire pour la conception du jeu. Bien evidemment l'héritage ou encore l'encapsulation ont été aussi important pour le bon fonctionnement de Stream. Pour l'interface graphique j'ai utlisé essentiellement les packages javax.swing et java.awt présents d'office dans Java. J'ai pu ainsi comprendre le fonctionnement de base des IHM et appris qu'en réalité, une fenêtre n'est qu'une multitude de composants posés les uns sur les autres et que chacun possède un rôle qui lui est propre.

A l'heure actuelle, le Java n'a pas grande "importance" dans les systèmes embarqués. En effet, le C est le langage informatique dominant dans ce domaine. Mais d'ici quelques années ces systèmes seront programmés en Java. Ce changement de langage dans les applications embarqués est du que le Java n'a pas premièrement des problèmes de portabilités. Un programme codé en Java pourra etre éxécuté dans plusieurs applications. Un autre avantage du Java par rapport au langage C est qu'il ne possède pas les convénients de la gestion de mémoire par conséquent ceux des pointeurs qu'on retrouve dans le langage C. Malgrès une forte domination du C dans le monde des applications embarquées actuellement, nous pouvons retrouver des applications coder en Java dans des systèmes complexes tel que nous pouvons retrouver dans l'automobiles. Mais cela n'ai pas encore générique. Les systèmes où nous retrouvons du Java sont généralement dù à une préférence du constructeur et non à des contraires de langage. Mais comme je l'expliquais précédemment, dans un futur proche les systèmes seront en Java pour des raisons technologique. De ce fait, étant un futur ingénieur dans les systèmes embarqués le Java prend une grande importance dans mon cursus scolaire.

Je me permet de citer la marque "Samsung" car les applications smartphone de cette marque sont coder en Java. Samsung étant une marque mondialement nous montre que le langage Java est utile et important.

Durant ce module de programmation structurée suivi en première année j'ai pu découvrir ce qu'était un langage informatique orienté objet. J'ai donc créé des classes et ainsi manipuler des objets. Sans oublier les niveaux d'accès pour les variables d'instances (données membres) et les méthodes : 


	- Public ->  un élément public est accessible de partout et sans aucune restriction. Certaines classes (comme la classe principale main) doivent obligatoirement être déclarées publiques (pour pouvoir exécuter l'application...).
	
	- Protected ->  un élément protected (protégé) est accessible uniquement aux classes d'un package et à ses classes filles.
	
	- Private -> un élément private (privé) est accessible uniquement au sein de la classe dans laquelle il est déclaré. Ces éléments ne peuvent être manipulés qu'à l'aide de méthode spécifiques appelés accesseur et mutateur.
	
J'ai aussi découvert les avantages que pouvait offir le Java par rapport au langage C++ et au langage C. Cependant au cours de ce module j'ai été confronté à des lacunes et rencontré des dificultés lors de la conception de certaines applications. Dans la partie qui va suivre je vais expliquer quels ont été mes dificultés et comment j'ai essayé à les surmonter.

J'ai compris de plus que ce langage portait une grande importance dans le monde de l'informatique.


  **b- Le Java en entreprise.**




#Analyse des mes échecs et de mes lacunes en première année en Java :

Dans cette partie nous allons voir les lacunes et les échecs rencontrer durant cette première année dans le module de programmation structurée en Java. 
Lors des devoirs sur table j'ai rencontré de grande difficulté à (la je dois dire que coder sur feuille est destabilisant)

#CONCLUSION :

