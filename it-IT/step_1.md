I loop possono essere utilizzati per `ripetere`{:class=“block3control”} blocchi di codice un numero prestabilito di volte, per `ripetere fino a quando`{:class=“block3control”} non viene soddisfatta una condizione, o per eseguire un blocco di codice `per sempre`{:class=“block3control”}.

Inserire un blocco `cambia`{:class="block3variables"} in un loop `modificherà`{:class="block3variables"} la tua `variabile`{:class="block3variables"} ogni volta che il loop viene eseguito.

Il codice seguente farà accelerare gradualmente uno sprite:

```blocks3
repeat (10)
change [speed v] by (1)
move (speed) steps
end
```

Il codice seguente aumenterà il punteggio della persona che gioca man mano che la partita continua:

```blocks3
forever
wait (10) seconds
change [score v] by (1)
end
```

Il codice seguente continuerà a eseguire il loop aggiungendo `1` alla variabile `tempo`{:class="block3variables"} fino a quando `tempo`{:class="block3variables"} `=`{:class="block3operators"} `50`.

```blocks3
repeat until <(time) = (50)>
wait (1) seconds
change [time v] by (1)
end
```

Puoi anche usare le variabili integrate di Scratch, come `dimensione`{:class="block3looks"}, `numero costume`{:class="block3looks"}, `volume`{:class="block3sound"} e `direzione`{:class="block3motion"}:

```blocks3
repeat (10)
change (size) by (10)
change (costume [number v]) by (1)
change (volume) by (5)
change (direction) by (-45)
end
```  


