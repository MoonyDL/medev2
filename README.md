# Deuxième TP de MEDEV

## PDF 1

Le repo a bien été créé.
Pour ignorer les .o :

```
*.o
```

Concernant le fait de bouger un fichier, je ne suis pas sûr de comprendre la question.
L'état final du dépôt peut se suivre directement sur l'interface de github.
Le dépot contient à cette étape : le README (ce fichier), un fichier texte : text.txt ainsi que le .gitignore.

## PDF 2

Ici on voit le concept de versions et de commit. Pour visualiser une  diff, il suffit de faire des changements locaux sans les commit.
Concernant les tag, l'interface gitg permet de tagger efficacement des repos.

## PDF 3

Dans ce pdf, il s'agit de voir le concept de branches, pour cela on créee une nouvelle branche avec un nouveau fichier (qui simule une nouvelle feature par exemple), et l'on continue de modifier la branche principale pour se retrouver avec un conflit.
En faisant :
```
git diff master AvecParellel
```
On observe les différences entre les deux branches.
Par la suite on peut "effacer" le fichier de la branche parallèle une fois revenu sur la branche principale (pour simuler le fait que l'on ne travaille pas sur cette feature). Par la suite, en effectuant un
```
git merge AvecParellel
```
Une fois cela effectué, on peut vérifier dans gitg que le merge a bien eu lieu.
