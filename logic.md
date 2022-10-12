J'ai toujours voulu représenter ma théore aussi évidente qu'elle n'en a l'air qu'il existe forcèment une faille dans un système quel que soit le système est vraie mais c'est pas aussi évident que ça
Je vais pas redonner les bases de la logique mais quelques éléement essentiel qu'il faut toujours savoir

## Proposition

Un proposition est une assertion qui pour valeur de vérité V ou F

En informatique on désigne par proposition en général la partie évaluée dans un if ou dans une boucle, par exemple le code suivant

```
While N<10 :
  N=N+1
  print("Hello world!")
```

Il se traduit par: Tant que la valeur de vérité de la proposition « N<lO » est VRAI,
augmenter N de 1 et afficher« bonjour ».

La proposition c'est N<10, vous allez voir c'est pas aussi évident que ça mais on y arrive

`3 < 4` est une proposition et sa valeur de vérité et V, on peut même le tester avec un interpréteur ça va marcher

`(3 < 4) <=> (7+3 = 10)` est V et avec du code ça s'écrit `(3 < 4) == (7+3 == 10)`

## Prédicat

Un prédicat qui dépend d'une variable par contre n'a aucune valeur de vérité que si on lui ajoute des quantificateurs

