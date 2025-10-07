# Answers of <Robin> <Giannoni> <Robin200207>

## Basics
### Task 1
1 unstaged change: veut dire qu'un fichier a été modifié en amont mais n'a pas encore été ajouté à l'index (staging area) pour le commit futur.

### Task 2

1.Le message proposé en exemple veut dire que le commit est le premier commit dans l'historique du dépôt.

2.Non on ne peut pas faire de commit sans message, un commit doit toujours avoir un message pour décrire les changements qui ont effectués.

3.Un nouveau commit a été ajouté à l'historique du dépôt, représentant les changements effectués dans le fichier modifié.

4.Non, le dépôt distant n'est pas encore à jour avec les modifications locales. Il faut pousser les changements vers le dépôt distant pour le mettre à jour.


### Task 3
Un fichier README a été ajouté, pas d'autres modifications.

### Task 4

Lorsque l'on revient au commit "initial commit", le dépôt revient à l'état du commit initial.


Lorsque l'on revient au dernier commit, le dépôt revient à l'état du dernier commit.

### Task 5
La différence entre le dépôt local et le dépôt distant est que le dépôt local contient un commit supplémentaire qui n'a pas encore été poussé (push) vers le dépôt distant. 

Si l'on supprime le dépot local, le dépôt distant restera inchangé et contiendra toujours les commits précédents, mais le commit supplémentaire présent dans le dépôt local qui n'a pas encore été poussé (push) sera perdu.
### Task 6
Le dépôt original n'a pas été modifié. Le dépôt cloné est une copie du dépôt original à l'état où il a été cloné. Les deux dépôts sont indépendants l'un de l'autre après le clonage.

## Gitgraph

### Task 7

![Gitgraph](img/gitgraph.svg)