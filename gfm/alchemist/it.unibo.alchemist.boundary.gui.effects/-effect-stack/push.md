//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[EffectStack](index.md)/[push](push.md)

# push

[jvm]\
open fun [push](push.md)(effect: [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>): [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>

Puts the effects in the group, giving it the maximum priority. 

 Acts nearly the same than using [add](add.md) or [offer](offer.md).

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
