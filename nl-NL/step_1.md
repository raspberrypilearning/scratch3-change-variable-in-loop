Lussen kunnen worden gebruikt om `herhaal`{:class="block3control"} codeblokken een bepaald aantal keren, `herhaal tot`{:class="block3control"} een voorwaarde is voldaan, of `altijd`{:class="block3control"} te blijven uitvoeren.

Het invoegen van een `verander`{:class="block3variables"} blok in een lus zal je `variabele`{:class="block3variables"} `veranderen`{:class="block3variables"} iedere keer dat de lus wordt uitgevoerd.

De onderstaande code zou een sprite steeds meer versnellen:

```blocks3
repeat (10)
change [speed v] by (1)
move (speed) steps
end
```

De onderstaande code verhoogt de score van een speler naarmate hij het spel langer speelt:

```blocks3
forever
wait (10) seconds
change [score v] by (1)
end
```

De onderstaande code zou de lus blijven uitvoeren door `1` te voegen aan de `tijd`{:class="block3variables"} variabele tot `tijd`{:class="block3variables"} `=`{:class="block3operators"} `50`.

```blocks3
repeat until <(time) = (50)>
wait (1) seconds
change [time v] by (1)
end
```

Je kunt ook ingebouwde Scratch-variabelen gebruiken, zoals `grootte`{:class="block3looks"}, `uiterlijk nummer`{:class="block3looks"}, `volume`{:class="block3sound"} en `richting`{:class="block3motion"}:

```blocks3
repeat (10)
change (size) by (10)
change (costume [number v]) by (1)
change (volume) by (5)
change (direction) by (-45)
end
```  


