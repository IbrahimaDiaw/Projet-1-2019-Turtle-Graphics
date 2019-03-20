# Projet-1-2019-Turtle-Graphics
Projet Design Pattern Master 1 Informatique 2019


Ce projet consistait à implémenter les spécifications d’un code en java avec Turtle Gaphics.
Ainsi nous allons détailler chaque méthode avec des captures pour mieux appréhender le projet.
Durant le projet nous avons travaillé sur les classes suivantes : turtleSoupe.java
RulesOf6005.java

                          • La classe RulesOf6005.java
Notre travail consiste à implémenter la méthode mayUseCodeInAssignment() qui est une
fonction booléenne qui ne retourne que vrai ou faux (True of False). la figure 1: rulesof6005 
illustre ces propos.
                     
                         • La classe turtleSoupe.java
Dans cette classe nous avons six méthodes à savoir :

➢ La méthode drawSquare : qui permet de dessiner un carré pour cela le programme a
besoin du nombre de cotés qui est égal à 4 et de la longueur des cotés pour obtenir le
résultat de la figure 2:Carré.

➢ la méthode calculateRegularPolygonAngle : cette méthode permet de calculer l’angle
interne d’un polygone régulier. Par définition un polygone régulier est un polygone qui
a tous ses cotés de même longueurs et ses angles de même mesure. Ainsi l’angle interne
se calcule par la formule ((n-2) *180)) /n avec n le nombre de cotés. Voir le code
source dans la classe La classe turtleSoupe.java.

➢ La méthode calculatePolygonSidesFromAngle : cette méthode calcule le nombre de
cotés à partir de l’angle interne d’un polygone régulier. La fonction math.round retourne
la valeur arrondie à l’entier le plus proche. Voir le code source dans la classe La classe turtleSoupe.java.

➢ La méthode drawRegularPolygon : permet de dessiner un polygone régulier une fois
qu’elle a le nombres de cotés et la longueur des côtés.la figure 3: Polygone regulier.

➢ La méthode calculateHeadingToPoint : elle permet de calculer le cap vers le point
cible à partir de la direction actuelle, de l’emplacement actuel et d’un emplacement
cible.Voir le code source dans la classe La classe turtleSoupe.java.

➢ La méthode List<Double> calculateHeadings : elle permet de calculer les
ajustements nécessaires pour par passer d’un point à l’autre à partir une séquence de
points d’où on applique la généricité pour passer une liste.
Voir le code source dans la classe La classe turtleSoupe.java.
  
 ➢ La méthode drawPersonalArt : elle permet de dessiner un art personnel ou bien un
graphique avec une coloration. la figure 4 :Art Personnel.

➢ La méthode main : qui est la méthode principale, elle est exécutée quand on exécute
la classe.
                
                Outils utilisés
➢JUnit  qui est un framework open source pour le développement et l'exécution de tests unitaires automatisables. Le principal intérêt est de s'assurer que le code répond toujours aux besoins même après d'éventuelles modifications. Plus généralement, ce type de tests est appelé tests unitaires de non-régression.

➢ Git qui est un système de contrôle de version distribué gratuit et à source ouverte , conçu pour gérer tout projet, du plus petit au plus grand, avec rapidité et efficacité.

➢ Eclipse qui est un environnement de développement (IDE) historiquement destiné au langage Java, même si grâce à un système de plugins il peut également être utilisé avec d'autres langages de programmation, dont le C/C++ et le PHP. 
