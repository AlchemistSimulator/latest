---
title: EffectGroup
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[EffectGroup](index.html)



# EffectGroup



[jvm]\
interface [EffectGroup](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>?> : [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html), [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>> , [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)> 

Models a group of effects. Each effect has a different priority of visualization.



## Parameters


jvm

| | |
|---|---|
| <P> | the position type |



## Functions


| Name | Summary |
|---|---|
| [add](index.html#-336804990%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [add](index.html#-336804990%2FFunctions%2F-134779887)(p: [E](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [addAll](index.html#-1037973866%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [addAll](index.html#-1037973866%2FFunctions%2F-134779887)(p: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<out [E](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [changePriority](change-priority.html) | [jvm]<br>abstract fun [changePriority](change-priority.html)(effect: [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>, offset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Changes the specified offset priority of the specified offset. |
| [clear](index.html#-1962405120%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [clear](index.html#-1962405120%2FFunctions%2F-134779887)() |
| [computeDrawCommands](../-effect-f-x/compute-draw-commands.html) | [jvm]<br>abstract fun <[T](../-effect-f-x/compute-draw-commands.html)> [computeDrawCommands](../-effect-f-x/compute-draw-commands.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html), [P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>><br>Computes a queue of commands to Draw something. |
| [contains](index.html#-1733424485%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [contains](index.html#-1733424485%2FFunctions%2F-134779887)(p: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [containsAll](index.html#1886599770%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [containsAll](index.html#1886599770%2FFunctions%2F-134779887)(p: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [element](index.html#586144384%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [element](index.html#586144384%2FFunctions%2F-134779887)(): [E](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html) |
| [equals](equals.html) | [jvm]<br>abstract fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Compares the [EffectGroup](index.html)s. |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getName](../-effect-f-x/get-name.html) | [jvm]<br>abstract fun [getName](../-effect-f-x/get-name.html)(): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html)<br>Gets the name of the effect. |
| [getVisibilityOf](get-visibility-of.html) | [jvm]<br>abstract fun [getVisibilityOf](get-visibility-of.html)(effect: [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns the visibility of the specified effect. |
| [hashCode](hash-code.html) | [jvm]<br>abstract fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isEmpty](index.html#-1792844854%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [isEmpty](index.html#-1792844854%2FFunctions%2F-134779887)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isVisible](../-effect-f-x/is-visible.html) | [jvm]<br>abstract fun [isVisible](../-effect-f-x/is-visible.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Gets the visibility of the effect. |
| [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)><br>abstract fun [iterator](index.html#-359036897%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[E](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html)> |
| [offer](index.html#-1815061187%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [offer](index.html#-1815061187%2FFunctions%2F-134779887)(p: [E](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [parallelStream](index.html#-708921786%2FFunctions%2F-134779887) | [jvm]<br>open fun [parallelStream](index.html#-708921786%2FFunctions%2F-134779887)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[E](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html)> |
| [peek](index.html#-1430561565%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [peek](index.html#-1430561565%2FFunctions%2F-134779887)(): [E](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html) |
| [poll](index.html#-1510576385%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [poll](index.html#-1510576385%2FFunctions%2F-134779887)(): [E](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html) |
| [remove](index.html#1583481242%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [remove](index.html#1583481242%2FFunctions%2F-134779887)(): [E](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html)<br>abstract fun [remove](index.html#754631126%2FFunctions%2F-134779887)(p: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeAll](index.html#-499358763%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [removeAll](index.html#-499358763%2FFunctions%2F-134779887)(p: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeIf](index.html#1420767036%2FFunctions%2F-134779887) | [jvm]<br>open fun [removeIf](index.html#1420767036%2FFunctions%2F-134779887)(filter: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [retainAll](index.html#111949236%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [retainAll](index.html#111949236%2FFunctions%2F-134779887)(p: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [search](search.html) | [jvm]<br>abstract fun [search](search.html)(effect: [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Checks if an effect is present in the group. |
| [setName](../-effect-f-x/set-name.html) | [jvm]<br>abstract fun [setName](../-effect-f-x/set-name.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Sets the name of the effect. |
| [setVisibility](../-effect-f-x/set-visibility.html) | [jvm]<br>abstract fun [setVisibility](../-effect-f-x/set-visibility.html)(visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets the visibility of the effect. |
| [setVisibilityOf](set-visibility-of.html) | [jvm]<br>abstract fun [setVisibilityOf](set-visibility-of.html)(effect: [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>, visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets the visibility of the specified effect. |
| [size](index.html#2132759532%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [size](index.html#2132759532%2FFunctions%2F-134779887)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)><br>open fun [spliterator](index.html#485701680%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[E](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html)> |
| [stream](index.html#-1977615027%2FFunctions%2F-134779887) | [jvm]<br>open fun [stream](index.html#-1977615027%2FFunctions%2F-134779887)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[E](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html)> |
| [toArray](index.html#-2012376625%2FFunctions%2F-134779887) | [jvm]<br>abstract fun [toArray](index.html#-2012376625%2FFunctions%2F-134779887)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<@NotNull()[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>abstract fun <[T](index.html#2015865373%2FFunctions%2F-134779887)> [toArray](index.html#2015865373%2FFunctions%2F-134779887)(p: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)>): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[T](../../it.unibo.alchemist.boundary.monitor/-f-x-step-monitor/index.html)> |


## Inheritors


| Name |
|---|
| [EffectStack](../-effect-stack/index.html) |

