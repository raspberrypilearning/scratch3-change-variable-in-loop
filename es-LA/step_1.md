Los bucles o "loops" se pueden usar para `repetir`{:class="block3control"} bloques de código un número determinado de veces, `repetir hasta que`{:class="block3control"} cumpla una condición, o correr `por siempre`{:class="block3control"}.

Inserta un bloque `cambiar`{:class="block3variables"} en un bucle va a `cambiar`{:class="block3variables"} tu `variable`{:class="block3variables"} cada vez que se se ejecute el bucle.

El siguiente código aceleraría un objeto gradualmente:

```blocks3
repeat (10)
change [speed v] by (1)
move (speed) steps
end
```

El siguiente código aumentaría la puntuación de un jugador cuanto más tiempo jugara:

```blocks3
forever
wait (10) seconds
change [score v] by (1)
end
```

El siguiente código seguiría ejecutando el bucle incrementando en `1` a la variable `tiempo`{:class="block3variables"} hasta que el `tiempo`{:class="block3variables"} `=`{:class="block3operators"} `50`.

```blocks3
repeat until <(time) = (50)>
wait (1) seconds
change [time v] by (1)
end
```

También puedes utilizar variables que vienen con Scratch, como `tamaño`{:class="block3looks"}, ` disfraz número`{:class="block3looks"}, `volumen`{:class="block3sound"} y `dirección`{:class="block3motion"}:

```blocks3
repeat (10)
change (size) by (10)
change (costume [number v]) by (1)
change (volume) by (5)
change (direction) by (-45)
end
```  


