Les boucles peuvent être utilisées pour `répéter`{:class="block3control"}des blocs de code un nombre défini de fois, `répéter jusqu'à`{:class="block3control"} une condition est remplie, ou exécuter ` indéfiniment`{:class= "bloc3contrôle"}.

L'insertion d'un bloc `mettre ma variable à`{:class="block3variables"} dans une boucle changera ``{:class="block3variables"} ta `variable`{:class="block3variables"} à chaque fois que la boucle s'exécute.

Le code ci-dessous accélérerait un sprite progressivement :

```blocks3
repeat (10)
change [vitesse v] by (1)
move (vitesse) steps
end
```

Le code ci-dessous augmenterait le score d'un joueur au fur et à mesure qu'il a joué au jeu :

```blocks3
forever
wait (10) seconds
change [score v] by (1)
end
```

Le code ci-dessous continuerait à exécuter la boucle en ajoutant `1` à la variable `temps`{:class="block3variables"} jusqu'à ce que `temps`{:class="block3variables"} `=`{:class="block3operators"} `50`.

```blocks3
repeat until <(temps) = (50)>
wait (1) seconds
change [temps v] by (1)
end
```

Tu peux également utiliser des variables Scratch intégrées, telles que `taille`{:class="block3looks"}, `numéro du costume`{:class="block3looks"}, `volume`{:class="block3sound"} et `directions`{:class="block3motion"} :

```blocks3
repeat (10)
change (size) by (10)
change (costume [number v]) by (1)
change (volume) by (5)
change (direction) by (-45)
end
```  


