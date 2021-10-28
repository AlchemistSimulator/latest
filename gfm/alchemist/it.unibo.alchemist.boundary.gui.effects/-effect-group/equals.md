//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[EffectGroup](index.md)/[equals](equals.md)

# equals

[jvm]\
abstract fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Compares the [EffectGroup](index.md)s. The result is true if and only if the argument is not {@code null} and every [EffectFX](../-effect-f-x/index.md) contained is not {@code null} and [equal](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html#equals-java.lang.Object-) to the corresponding in the comparing {@code EffectGroup} (order is important!) and the group has the same name, visibility and transparency.

## See also

jvm

| | |
|---|---|
| [java.lang.Object](https://docs.oracle.com/javase/8/docs/api/java/lang/Object.html#equals-java.lang.Object-) | Object#equals(Object) |
