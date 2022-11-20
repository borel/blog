# Interface , really ?

Bonjour , aprés des années de developpement en Java , je me suis posé la question suivante.
A t'on besoin d'inteface ? Et si oui dans quel cas et la difference avec une classe **Abstract**


# Définition

On va commencer par emprunter une défintion qui fait consensus sur le web :

>  Une **interface** décrit un ensemble de méthodes en fournissant
> uniquement leur signature. Une **interface** introduit un nouveau type
> d'abstraction qui définit à travers ces méthodes un ensemble
> d'interactions autorisées. Une classe peut ensuite implémenter une ou
> plusieurs **interfaces**.

bon ok , quesqu'on comprend : si on a un ensemble de classe qui partage un me me domaine fonctionnelle on peut unifier leurs comportements via une interface .
Mais à quoi ca peut bien servir concretement ..

## Choix d'exemple

J'ai du mal à comprendre les choses de façon thérorique , il me faut souvent des exemples.
Le choix de l'exemple de cet article est donc important. 
Je souhaite trouver un exemple qui puisse etre un besoin réel.
Je vais donc eviter les pizza, animaux ou autre vehicule
