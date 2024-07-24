Os loops podem ser usados para `repetir`{:class="block3control"} blocos de código um determinado número de vezes, `repetir até`{:class="block3control" "} uma condição for atendida ou execute `para sempre`{:class="block3control"}.

Inserir um bloco `alterar`{:class="block3variables"} em um loop `alterará`{:class="block3variables"} sua `variável`{: class="block3variables"} cada vez que o loop é executado.

O código abaixo aceleraria um sprite gradualmente:

```blocks3
repeat (10)
change [speed v] by (1)
move (speed) steps
end
```

O código abaixo aumentaria a pontuação de um jogador quanto mais tempo ele jogasse:

```blocks3
forever
wait (10) seconds
change [score v] by (1)
end
```

O código abaixo continuaria executando o loop adicionando `1` à variável `time`{:class="block3variables"} até `time`{:class=" block3variables"} `=`{:class="block3operators"} `50`.

```blocks3
repeat until <(time) = (50)>
wait (1) seconds
change [time v] by (1)
end
```

Você também pode usar variáveis incorporadas no Scratch, como `tamanho`{:class="block3looks"}, `número da fantasia`{:class="block3looks"}, `volume`{:class="block3sound"} e `direção`{:class="block3motion"}:

```blocks3
repeat (10)
change (size) by (10)
change (costume [number v]) by (1)
change (volume) by (5)
change (direction) by (-45)
end
```  


