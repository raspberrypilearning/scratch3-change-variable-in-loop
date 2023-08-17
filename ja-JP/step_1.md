ループは、コードブロックを設定した`回数繰り返す`{:class="block3control"}、条件が満たされる`まで繰り返す`{:class="block3control"}、または `ずっと`{:class="block3control"}繰り返すのに使用できます。

`変数を...にする`{:class="block3variables"}ブロックをループに挿入すると、ループが実行されるたびに`変数`{:class="block3variables"}を`変更`{:class="block3variables"}できます。

以下のコードはスプライトを徐々に加速します。

```blocks3
repeat (10)
change [速度 v] by (1)
move (速度) steps
end
```

以下のコードは、プレイヤーがゲームを長くプレイするほど、プレイヤーのスコアを増加させます。

```blocks3
forever
wait (10) seconds
change [スコア v] by (1)
end
```

以下のコードは、`時間`{:class="block3variables"} `=`{:class="block3operators"} `50`になるまで、`時間`{:class="block3variables"}変数に`1`を追加するループを実行し続けます。

```blocks3
repeat until <(時間) = (50)>
wait (1) seconds
change [時間 v] by (1)
end
```

`大きさ`{:class="block3looks"}、`コスチュームの番号`{:class="block3looks"}、`音量`{:class="block3sound"}、`向き`{:class="block3motion"}など、Scratchに元から用意されている変数を使用することもできます。

```blocks3
repeat (10)
change (size) by (10)
change (costume [number v]) by (1)
change (volume) by (5)
change (direction) by (-45)
end
```  


