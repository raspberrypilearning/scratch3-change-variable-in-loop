يمكن استخدام المقطع البرمجي `كرر`{: class = "block3control"} لعدد محدد من المرات ، `كرر حتى`{: class = "block3control"} تم استيفاء شرط ، أو تشغيل `كرر باستمرار`{: class = "block3control"}.

إدخال المقطع البرمجي `غير بمقدار`{:class="block3variables"} في المقطع البرمجي `كرر`{:class="block3variables"} الخاص بك سيغير الـ`متغير`{:class="block3variables"} في كل مرة يتنفذ بها المقطع البرمجي كرر.

يعمل المقطع البرمجي أدناه على تسريع الكائن تدريجيًا:

```blocks3
repeat (10)
change [speed v] by (1)
move (speed) steps
end
```

سيزيد المقطع البرمجي أدناه نقاط اللاعب كلما طالت مدة لعب اللعبة:

```blocks3
forever
wait (10) seconds
change [score v] by (1)
end
```

ان المقطع البرمجي أدناه يحافظ على تشغيل حلقة التكرار من خلال اضافة `1` إلى متغير`الوقت`{:class="block3variables"} حتى يصبح`الوقت`{:class="block3variables"} `=`{:class="block3operators"} `50`.

```blocks3
repeat until <(time) = (50)>
wait (1) seconds
change [time v] by (1)
end
```

يمكنك أيضًا استخدام متغيرات موجودة في Scratch ، مثل `الحجم`{:class="block3looks"} ، `رقم المظهر`{:class="block3looks"}، `شدة الصوت`{:class="block3sound"} و `الاتجاه`:class="block3motion"}:

```blocks3
repeat (10)
change (size) by (10)
change (costume [number v]) by (1)
change (volume) by (5)
change (direction) by (-45)
end
```  


