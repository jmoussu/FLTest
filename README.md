# Test Technique : Compétences en Algorithmie

Ce test évalue vos compétences en résolution de problèmes algorithmiques. Veuillez compléter les exercices suivants.

## Exercice 1

Michel est un pompier qui a besoin d'une échelle de la bonne taille pour secourir les personnes d'un immeuble en feu. L'échelle doit avoir une barre par étage en fonction de la hauteur de l'immeuble. Votre tâche consiste à écrire une fonction qui construit l'échelle en fonction du nombre d'étages donné.

Exemple :
Pour 2 étages et en exécutant la commande : `node exo1.js 2`
Résultat attendu :
```
|  |
|--|
|  |
|--|
|  |
```


## Exercice 2

Il n'y a pas d'énoncé pour cet exercice. Débrouillez-vous !

Exemples :
```
- node exo2.js 0 Salut => Sortie : Salut
- node exo2.js 1 Salut => Sortie : tulaS
- node exo2.js 101 123456 => Sortie : 654321
- node exo2.js 1000 JIM => Sortie : JIM
- node exo2.js 101110 JIM => Sortie : JIM
- node exo2.js 10100101 JIM => Sortie : MIJ
```
## Exercice 3

*La cigale et la fourmi*

La cigale n'a pas fait de provisions pour l'hiver et risque de mourir. Les fourmis ont beaucoup de provisions et sont prêtes à partager avec la cigale. La vie de la cigale est notée H. Il reste D jours avant l'arrivée de l'hiver. Chaque jour, la cigale perd F points de vie, tandis que les fourmis fournissent P provisions par jour à la cigale (chaque provision ajoute +1 point de vie).

Votre programme `exo3.js` doit renvoyer le nombre de points de vie restants de la cigale ou "Morte" si elle est décédée.

exo3.js H D F P

Exemples :
- `node exo3.js 120 3 20 10` => Sortie : `90`
- `node exo3.js 40 5 20 10` => Sortie : `"Morte"`
