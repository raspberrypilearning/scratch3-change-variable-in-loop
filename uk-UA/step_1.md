Цикли можуть використовуватися, щоб `повторювати`{:class="block3control"} блоки коду задану кількість разів, `повторювати допоки`{:class="block3control"} виконується умова, або запустити і повторювати `завжди`{:class="block3control"}.

Вставлення блоку `змінити`{:class="block3variables"} в цикл зможе `змінювати`{:class="block3variables"} твої `змінні`{:class="block3variables"} при кожному виконанні циклу.

Нижченаведений код буде поступово прискорювати спрайт:

```blocks3
repeat (10)
change [speed v] by (1)
move (speed) steps
end
```

Нижченаведений код підвищуватиме результат гравця залежно від того, як довго він буде грати:

```blocks3
forever
wait (10) seconds
change [score v] by (1)
end
```

Нижченаведений код буде продовжувати виконувати цикл, додаючи `1` до змінної `час`{:class="block3variables"} до тих пір, поки `час`{:class="block3variables"} `=`{:class="block3operators"} `50`.

```blocks3
repeat until <(time) = (50)>
wait (1) seconds
change [time v] by (1)
end
```

Ти також можеш використовувати вбудовані змінні Scratch, такі як `розмір`{:class="block3looks"}, `номер образу`{:class="block3looks"}, `гучність`{:class="block3sound"} та `напрям`{:class="block3motion"}:

```blocks3
repeat (10)
change (size) by (10)
change (costume [number v]) by (1)
change (volume) by (5)
change (direction) by (-45)
end
```  


