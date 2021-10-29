---
title: EffectStack
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.effects](../index.html)/[EffectStack](index.html)



# EffectStack



[jvm]\
class [EffectStack](index.html)<[P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<out [P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>?> : [EffectGroup](../-effect-group/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)> 

The class models a group of effects, stored as a stack. It can manage priority of visualization and visibility of each effect inside it.



## Parameters


jvm

| | |
|---|---|
| <P> | The position type |



## Constructors


| | |
|---|---|
| [EffectStack](-effect-stack.html) | [jvm]<br>open fun [EffectStack](-effect-stack.html)()<br>Constructor that creates an empty stack of effects with default name. |
| [EffectStack](-effect-stack.html) | [jvm]<br>open fun [EffectStack](-effect-stack.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Default constructor. |


## Functions


| Name | Summary |
|---|---|
| [add](add.html) | [jvm]<br>open fun [add](add.html)(e: [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [addAll](add-all.html) | [jvm]<br>open fun [addAll](add-all.html)(c: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<out [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [changePriority](change-priority.html) | [jvm]<br>open fun [changePriority](change-priority.html)(effect: [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>, offset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Changes the specified offset priority of the specified offset. |
| [clear](clear.html) | [jvm]<br>open fun [clear](clear.html)() |
| [computeDrawCommands](compute-draw-commands.html) | [jvm]<br>open fun <[T](compute-draw-commands.html)> [computeDrawCommands](compute-draw-commands.html)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-property-type-adapter/index.html), [P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>><br>Computes a queue of commands to Draw something. |
| [contains](contains.html) | [jvm]<br>open fun [contains](contains.html)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [containsAll](contains-all.html) | [jvm]<br>open fun [containsAll](contains-all.html)(c: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [element](element.html) | [jvm]<br>open fun [element](element.html)(): [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)> |
| [equals](equals.html) | [jvm]<br>open fun [equals](equals.html)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-655675525%2FFunctions%2F-134779887)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getTypeAdapter](get-type-adapter.html) | [jvm]<br>@NotNull()<br>open fun [getTypeAdapter](get-type-adapter.html)(): @NotNull()[EffectGroupAdapter](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.html)<br>Returns a com.google.gson.JsonSerializer and com.google.gson.JsonDeserializer combo class to be used as a {@code TypeAdapter} for this {@code EffectStack}. |
| [getVisibilityOf](get-visibility-of.html) | [jvm]<br>open fun [getVisibilityOf](get-visibility-of.html)(effect: [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns the visibility of the specified effect. |
| [hashCode](hash-code.html) | [jvm]<br>open fun [hashCode](hash-code.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isEmpty](is-empty.html) | [jvm]<br>open fun [isEmpty](is-empty.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isVisible](is-visible.html) | [jvm]<br>open fun [isVisible](is-visible.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Gets the visibility of the effect. |
| [iterator](iterator.html) | [jvm]<br>open fun [iterator](iterator.html)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.html#-1606146105%2FFunctions%2F-134779887)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-property-type-adapter/index.html)> |
| [offer](offer.html) | [jvm]<br>open fun [offer](offer.html)(e: [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [parallelStream](../-effect-group/index.html#-708921786%2FFunctions%2F-134779887) | [jvm]<br>open fun [parallelStream](../-effect-group/index.html#-708921786%2FFunctions%2F-134779887)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[E](../../it.unibo.alchemist.boundary.monitors/-leaflet-map-display/index.html#-1246139635%2FFunctions%2F-134779887)> |
| [peek](peek.html) | [jvm]<br>open fun [peek](peek.html)(): [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)><br>Returns the effect with maximum priority, without removing it. |
| [poll](poll.html) | [jvm]<br>open fun [poll](poll.html)(): [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)> |
| [pop](pop.html) | [jvm]<br>open fun [pop](pop.html)(): [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)><br>Removes the effect with maximum priority and returns it. |
| [push](push.html) | [jvm]<br>open fun [push](push.html)(effect: [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>): [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)><br>Puts the effects in the group, giving it the maximum priority. |
| [remove](remove.html) | [jvm]<br>open fun [remove](remove.html)(): [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)><br>open fun [remove](remove.html)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeAll](remove-all.html) | [jvm]<br>open fun [removeAll](remove-all.html)(c: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeIf](../-effect-group/index.html#1420767036%2FFunctions%2F-134779887) | [jvm]<br>open fun [removeIf](../-effect-group/index.html#1420767036%2FFunctions%2F-134779887)(filter: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [retainAll](retain-all.html) | [jvm]<br>open fun [retainAll](retain-all.html)(c: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [search](search.html) | [jvm]<br>open fun [search](search.html)(effect: [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Checks if an effect is present in the group. |
| [setName](../-effect-f-x/set-name.html) | [jvm]<br>abstract fun [setName](../-effect-f-x/set-name.html)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Sets the name of the effect. |
| [setVisibility](../-effect-f-x/set-visibility.html) | [jvm]<br>abstract fun [setVisibility](../-effect-f-x/set-visibility.html)(visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets the visibility of the effect. |
| [setVisibilityOf](set-visibility-of.html) | [jvm]<br>open fun [setVisibilityOf](set-visibility-of.html)(effect: [EffectFX](../-effect-f-x/index.html)<[P](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.html)>, visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets the visibility of the specified effect. |
| [size](size.html) | [jvm]<br>open fun [size](size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.html#-677603448%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-property-type-adapter/index.html)><br>open fun [spliterator](../-effect-group/index.html#485701680%2FFunctions%2F-134779887)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[E](../../it.unibo.alchemist.boundary.monitors/-leaflet-map-display/index.html#-1246139635%2FFunctions%2F-134779887)> |
| [stream](../-effect-group/index.html#-1977615027%2FFunctions%2F-134779887) | [jvm]<br>open fun [stream](../-effect-group/index.html#-1977615027%2FFunctions%2F-134779887)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[E](../../it.unibo.alchemist.boundary.monitors/-leaflet-map-display/index.html#-1246139635%2FFunctions%2F-134779887)> |
| [toArray](to-array.html) | [jvm]<br>@NotNull()<br>open fun [toArray](to-array.html)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>@NotNull()<br>open fun <[T](to-array.html)> [toArray](to-array.html)(a: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-property-type-adapter/index.html)>): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-property-type-adapter/index.html)> |


## Properties


| Name | Summary |
|---|---|
| [name](name.html) | [jvm]<br>private open var [name](name.html): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [visibility](visibility.html) | [jvm]<br>private open var [visibility](visibility.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

