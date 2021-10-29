---
title: equals
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[EffectGroup](index.html)/[equals](equals.html)



# equals



[jvm]\
abstract fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)



Compares the [EffectGroup](index.html)s. The result is true if and only if the argument is not {@code null} and every [EffectFX](../-effect-f-x/index.html) contained is not {@code null} and [equal](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html#equals-java.lang.Object-) to the corresponding in the comparing {@code EffectGroup} (order is important!) and the group has the same name, visibility and transparency.



## See also


jvm

| | |
|---|---|
| [java.lang.Object](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html#equals-java.lang.Object-) | Object#equals(Object) |




