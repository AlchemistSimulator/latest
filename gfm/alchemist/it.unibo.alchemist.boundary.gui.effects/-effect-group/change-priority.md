//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[EffectGroup](index.md)/[changePriority](change-priority.md)

# changePriority

[jvm]\
abstract fun [changePriority](change-priority.md)(effect: [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.md)>, offset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))

Changes the specified offset priority of the specified offset.

## Parameters

jvm

| | |
|---|---|
| effect | the effect |
| offset | the offset; it can be positive or negative |

#### Throws

| | |
|---|---|
| [java.lang.IllegalArgumentException](https://docs.oracle.com/javase/8/docs/api/java/lang/IllegalArgumentException.html) | if can't find the effect |
