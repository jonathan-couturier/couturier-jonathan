**Projet de rattrapage du module de Programmation structurée en Java**


#INTRODUCTION :

Ce rapport à pour but de valider mon module de programmation structurée en Java. En effet, suite à des lacunes rencontrées lors des examens passé en premier année nous devons rédiger un rapport afin de valider ce module qui me permettra par la même occasion de valider ma première année du cycle ingénieur.
Ce rapport devra contenir dix mille mots, à plus ou moins dix pourcents près, synthétisant mes connaissances et mes compétences mais aussi mes lacunes. Pour répondre au cahier des charges, ce rapport se composera de deux parties distinctes. 
Dans un premier temps nous verons l'importance de mes connaissances et compétences dans mon cursus scolaire et dans 
l'entreprise dans laqu'elle j'effectue mon apprentissage. Dans cette même partie nous retrouverons la façon dont j'ai acquis ces connaissances et ces compétences. La dernière partie concernera mes échecs et mes lacunes rencontré lors de ma première année dans le module de programmation structurée en Java.



#Le Java dans mon cursus scolaire et en entreprise :

Mon parcours choisi à l'ISEP est les Systèmes embarqués, par conséquence la programmation en Java est importante et autant plus indispensable pour la réussite de mon diplome d'ingénieur. Cependant, à PSA Peugeot Citroen, l'entreprise où j'effectue mon apprentissage, le Java n'occupe pas une grande place dans mon service. C'est pour cela que pour la suite du rapport je ne parlerai pas l'importance que peu avoir la programmation en Java au sein de mon entreprise. Cette partie sera donc focalisé sur le Java vue à travers mon cursus scolaire. 

Le module de programmation structurée en Java suivi en première année à l'ISEP était le premier dans mon cursus scolaire. A vrai dire, la programmation orientée objet dans sa globalité était nouveau. Mais grace aux cours et aux nombreux travaux pratiques j'ai pu acquerir rapidement des bases dans nouveau ce langage. J'ai compris de plus que ce langage portait une grande importance dans le monde de l'informatique. 
Comme expliquer précedemment, avant d'apprendre le Java j'ai du comprendre le principe de la programmation orientée objet. J'ai donc appris ce qu'était un objet et une classe. Un objet est une structure de données qui permet de gérer des données, de les classer, et de les stocker sous une certaine forme. Autrement dit un objet est une chose caractérisée par un ensemble de variables appellées attributs. Une classe c'est le modèle de quelque chose que nous voulons construire, elle représente un ensemble d'objets qui partagent une structure commune. Les classes sont nommées selon la méthode camelCase mais commencent par une majuscule.
Afin de mieux comprendre ces définitions prenons l'exemple du monde automobile :
    la classe Voiture servira à spécifier que tous les objets voiture ont une marque, une puissance, une année ...
    
Exemple : 

Voici ce que cela donnerai si nous devions le coder en Java.
```sh
                  class Voiture {
                    int marque ;     // Marque de la voiture 
                    int puissance ; // Puissance de la voiture en chevaux
                    int annee ;    // Annee de sortie de la voiture
                  }          
```
      
N'oublions pas de plus que la programmation orientée est dirigée par trois fondamentaux qu'il convient de toujours garder à l'esprit : encapsulation, héritage et polymorphisme. Tout comme pour l'objet et la classe je vais donner une définition simple de ces trois fondamentaux. 

**L'encapsulation :** l'encapsulation permet de rassembler les données et les méthodes au sein d'une structure en cachant l'implémentation de l'objet, autrement dit en empêchant l'accès aux données. 

**L'héritage :** le concept d'héritage est un des concepts les plus importants de la programmation orientée objet. L'héritage est un mécanisme permettant de créer une nouvelle classe à partir d'une classe existante en gardant les même propriétés et méthodes.

Exemple : 

Voici ce que cela donnerai si nous devions le coder en Java.
```sh 
                class Animal extends Object {
	                   // Corps de la classe 
                }
``` 

**Le polymorphisme : ** le polymophisme est une technique particulière d'héritage. Elle consiste, lorsqu'on hérite d'une classe, à redéfinir l'une des méthodes pour la spécialiser.


Après avoir compris ces prinpales règles et fondamentaux de la programmation Java, j'ai pu commencer à réaliser des codes, qui était bien évidemment au début de simple code. 

Comme pour tous les nouveaux codeur, que ça soit pour n'importe quel langage de programmation, mon premier code était un "Hello World". Pour cela j'avais utiliser un ``System.out.print("Hello World !");``. Ce qui m'a permis d'afficher le fameux "Hello World" dans la console de l'IDE NetBeans. 

Ensuite, j'ai commencé serieusement la programmation. J'ai effectué des opérations par exemple arithmétique, construit des tableaux à deux et trois dimensions, utilisé les structures "if ... else" et "switch" ou encore les boucles "for", "while" et "do ... while".
Toutes ces manipulations cité ci-dessus ont été effectuées et apprises à travers des différents travaux pratiques.

Evidemment comme pour toutes les matières enseignées, afin de rencontrer le moins de lacunes possible, le travail à la maison est vivement conseillé. Un des avantages du Java est qu'il y a de nombreuses communautés autour de celui-ci. En effet, il est très facile de trouver des cours ou/et exercices sur le net par exemple. Ce qui m'a permis d'approfondir mes connaissances et mes compétences. 

Afin de mettre en pratique ce que nous avions appris, nous devions réaliser un projet de fin d'année. Ce projet consistait à réalliser le jeu Stream. 




A l'heure actuelle, le Java n'a pas grande importance dans les systèmes embarqués. En effet, le C est le langage dominant dans ce domaine. Mais d'ici quelques années ces systèmes seront programmés en Java. Ce changement de langage dans les applications embarqués est du que le Java n'a pas premièrement des problèmes de portabilités. Un programme codé en Java pourra etre éxécuté dans plusieurs applications. Un autre avantage du Java par rapport au langage C est qu'il ne possède pas les convénients de la gestion de mémoire par conséquent ceux des pointeurs qu'on retrouve dans le langage C. Malgrès une forte domination du C dans le monde des applications embarquées actuellement, nous pouvons retrouver des applications coder en Java dans des systèmes complexes tel que nous pouvons retrouver dans l'automobiles. Mais cela n'ai pas encore générique. Les systèmes où nous retrouvons du Java sont généralement dù à une préférence du constructeur et non à des contraires de langage. Mais comme je l'expliquais précédemment, dans un futur proche les systèmes seront en Java pour des raisons technologique. 
De ce fait, étant un futur ingénieur dans les systèmes embarqués le Java prend une grande importance dans mon cursus scolaire.
Je me permet de citer la marque "Samsung" car les applications smartphone de cette marque sont coder en Java. Samsung étant une marque mondialement nous montre que le langage Java est utile et important.






Aujourd’hui, le langage Java combine à la fois la puissance de la programmation objet et la programmation concurrente. Ces caractéristiques en font un candidat de choix pour la programmation de systèmes embarqués et des systèmes temps réel. Ainsi le langage Java apparait couramment pour le développement d’applications mobiles/embarquées.


Avantage du Java par rapport au autre langage : Le langage Java hérite de la puissance de C++, sans ses inconvénients (complexité, pointeurs et références, gestion de la mémoire). Il intègre de puissants concepts : applets, gestion des threads, distribution…, qui en font un langage de développement incontournable, adapté à de très nombreux contextes.



#Analyse des mes échecs et de mes lacunes en première année en Java :



#CONCLUSION :

