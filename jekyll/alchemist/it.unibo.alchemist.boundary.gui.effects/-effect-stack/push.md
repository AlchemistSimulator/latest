---
title: push
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[EffectStack](index.html)/[push](push.html)



# push



[jvm]\
open fun [push](push.html)(effect: [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.html)>): [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.html)>



Puts the effects in the group, giving it the maximum priority. 



 Acts nearly the same than using [add](add.html) or [offer](offer.html).



#### Return



the effect pushed



## Parameters


jvm

| | |
|---|---|
| effect | the effect |



#### Throws


| | |
|---|---|
| [java.lang.UnsupportedOperationException](https://docs.oracle.com/javase/8/docs/api/java/lang/UnsupportedOperationException.html) | if the add operation is not supported by this list |
| [java.lang.ClassCastException](https://docs.oracle.com/javase/8/docs/api/java/lang/ClassCastException.html) | if the class of the specified element prevents it from being added to this list |
| [java.lang.NullPointerException](https://docs.oracle.com/javase/8/docs/api/java/lang/NullPointerException.html) | if the specified element is null and this list does not permit null elements |
| [java.lang.IllegalArgumentException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalArgumentException.html) | if some property of this element prevents it from being added to this list |



