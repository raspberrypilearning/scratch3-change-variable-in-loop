Pętli można używać aby powtarzać `powtarzaj`{:class="block3control"} blok kodu określoną liczbę razy, `powtarzaj aż`{:class="block3control"} służy do powtarzania bloku dopóki dany warunek jest spełniony, a `zawsze`{:class="block3control"} służy do powtarzania bloku w nieskończoność.

Wstawienie bloku `zmień`{:class="block3variables"} do pętli spowoduje zmianę za pomocą `zmień`{:class="block3variables"} twojej `zmiennej`{:class="block3variables"} za każdym razem, gdy pętla zostanie uruchomiona.

Poniższy kod będzie stopniowo przyspieszał duszka:

```blocks3
repeat (10)
change [prędkość v] by (1)
move (prędkość) steps
end
```

Poniższy kod zwiększałby wynik gracza, wraz z długością trwania gry:

```blocks3
forever
wait (10) seconds
change [wynik v] by (1)
end
```

Poniższy kod będzie uruchamiał pętlę, dodając `1` do zmiennej `czas`{:class="block3variables"} aż do momentu, gdy `czas`{:class="block3variables"} `=`{:class="block3operators"} `50`.

```blocks3
repeat until <(czas) = (50)>
wait (1) seconds
change [czas v] by (1)
end
```

Możesz także używać zmiennych wbudowanych w Scratch, takich jak `rozmiar`{:class="block3looks"}, `numer kostiumu`{:class="block3looks"}, `objętość`{:class="block3sound"} i `kierunek`{:class="block3motion"}:

```blocks3
repeat (10)
change (size) by (10)
change (costume [number v]) by (1)
change (volume) by (5)
change (direction) by (-45)
end
```  


