Loops can be used to `repeat`{:class="block3control"} code blocks a set number of times, `repeat until`{:class="block3control"} a condition is met, or run `forever`{:class="block3control"}. 

Inserting a `change`{:class="block3variables"} block into a loop will `change`{:class="block3variables"} your `variable`{:class="block3variables"} each tim the loop runs. 

The code below would accelerate a sprite gradually:  

```blocks3
repeat (10)
change [speed v] by (1)
move (speed) steps
end
```  

The code below would increase a player's score the longer they played the game:  

```blocks3
forever
wait (10) seconds
change [score v] by (1)
end
```  

The code below would keep running the loop adding `1` to the `time`{:class="block3variables"} variable until `time`{:class="block3variables"} `=`{:class="block3operators"} `50`.

```blocks3
repeat until <(time) = (50)>
wait (1) seconds
change [time v] by (1)
end
``` 

You can also use built in Scratch variables, such as `size`{:class="block3looks"}, `costume number`{:class="block3looks"}, `volume`{:class="block3sound"} and `direction`{:class="block3motion"}:

```blocks3
repeat (10)
change (size) by (10)
change (costume [number v]) by (1)
change (volume) by (5)
change (direction) by (-45)
end
```  


