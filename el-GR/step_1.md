Οι βρόχοι μπορούν να χρησιμοποιηθούν ως μπλοκ κώδικα `επανάλαβε`{:class="block3control"} για έναν καθορισμένο αριθμό επαναλήψεων, ή ως `επανάλαβε ώσπου` {:class="block3control"} μια συνθήκη γίνει αληθής ή ως εκτέλεση `για πάντα`{:class= "block3control"}.

Εισάγοντας ένα μπλοκ `άλλαξε`{:class="block3variables"} σε έναν βρόχο θα `αλλάξεις`{:class="block3variables"} τη `μεταβλητή`{:class="block3variables"} κάθε φορά που εκτελείται ο βρόχος.

Ο παρακάτω κώδικας θα επιτάχυνε σταδιακά ένα αντικείμενο:

```blocks3
repeat (10)
change [speed v] by (1)
move (speed) steps
end
```

Ο παρακάτω κώδικας θα αύξανε το σκορ ενός παίκτη όσο περισσότερο έπαιζε το παιχνίδι:

```blocks3
forever
wait (10) seconds
change [score v] by (1)
end
```

Ο παρακάτω κώδικας θα συνεχίσει να εκτελεί τον βρόχο προσθέτοντας `1` στη μεταβλητή`χρόνος`{:class="block3variables"} ώσπου ο `χρόνος`{:class="block3variables"} `=`{:class="block3operators"} `50`.

```blocks3
repeat until <(time) = (50)>
wait (1) seconds
change [time v] by (1)
end
```

Μπορείς επίσης να χρησιμοποιήσεις ενσωματωμένες μεταβλητές του Scratch, όπως `μέγεθος`{:class="block3looks"}, `ενδυμασία νούμερο`{:class="block3looks"}, `ένταση`{:class="block3sound"} και `κατεύθυνση`{:class="block3motion"}:

```blocks3
repeat (10)
change (size) by (10)
change (costume [number v]) by (1)
change (volume) by (5)
change (direction) by (-45)
end
```  


