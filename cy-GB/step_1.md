Mae modd defnyddio dolenni i `ailadrodd`{:class="block3control"} blociau cod nifer penodol o weithiau, `ailadrodd tab`{:class="block3control"} fod amod wedi'i fodloni, neu redeg `am byth`{:class="block3control"}.

Bydd mewnosod bloc `newid`{:class="block3variables"} i mewn i ddolen yn `newid`{:class="block3variables"} dy `newidyn`{:class="block3variables"} bob tro mae'r ddolen yn rhedeg.

Byddai'r cod isod yn cyflymu corlun yn raddol:

```blocks3
repeat (10)
change [cyflymder v] by (1)
move (cyflymder) steps
end
```

Byddai'r cod isod yn cynyddu sgôr chwaraewr po hiraf bydd yn chwarae'r gêm:

```blocks3
forever
wait (10) seconds
change [sgôr v] by (1)
end
```

Byddai'r cod isod yn parhau i redeg y ddolen gan ychwanegu `1` at y newidyn `amser`{:class="block3variables"} tan fod yr `amser`{:class="block3variables"} `=`{:class="block3operators"} `50`.

```blocks3
repeat until <(amser) = (50)>
wait (1) seconds
change [amser v] by (1)
end
```

Galli di hefyd ddefnyddio newidynnau Scratch parod, fel `maint`{:class="block3looks"}, `rhif gwisg`{:class="block3looks"}, `lefel sain`{:class="block3sound"} a `cyfeiriad`{:class="block3motion"}:

```blocks3
repeat (10)
change (size) by (10)
change (costume [number v]) by (1)
change (volume) by (5)
change (direction) by (-45)
end
```  


