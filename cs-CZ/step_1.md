Cykly mohou být použity pro `opakování`{:class="block3control"} daného bloku kódu `několik` `krát`{:class="block3control"}, `opakování dokud nenastane`{:class="block3control"} podmínka, nebo pro `opakování stále`{:class="block3control"}.

Vložením bloku `změň`{:class="block3variables"} do smyčky se `změní`{:class="block3variables"} vaše `proměnná`{:class="block3variables"} pokaždé, když smyčka proběhne.

Níže uvedený kód by postupně zrychloval sprite:

```blocks3
repeat (10)
change [rychlost v] by (1)
move (rychlost) steps
end
```

Níže uvedený kód by zvýšoval skóre hráče, čím déle hru hraje:

```blocks3
forever
wait (10) seconds
change [skóre v] by (1)
end
```

Níže uvedený kód by se opakoval a přidával `1` do proměnné `čas`{:class="block3variables"} až do `čas`{:class="block3variables"} `=`{:class="block3operators"} `50`.

```blocks3
repeat until <(čas) = (50)>
wait (1) seconds
change [čas v] by (1)
end
```

Můžete také použít zabudované proměnné Scratch, jako je `velikost`{:class="block3looks"}, `kostým číslo`{:class="block3looks"}, `hlasitost`{:class="block3sound"} a `směr`{:class="block3motion"}:

```blocks3
repeat (10)
change (size) by (10)
change (costume [číslo v]) by (1)
change (volume) by (5)
change (direction) by (-45)
end
```  


