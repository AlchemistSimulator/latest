//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.effects](../index.md)/[EffectStack](index.md)

# EffectStack

[jvm]\
class [EffectStack](index.md)<[P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<out [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>?> : [EffectGroup](../-effect-group/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)> 

The class models a group of effects, stored as a stack. It can manage priority of visualization and visibility of each effect inside it.

## Parameters

jvm

| | |
|---|---|
| <P> | The position type |

## Constructors

| | |
|---|---|
| [EffectStack](-effect-stack.md) | [jvm]<br>open fun [EffectStack](-effect-stack.md)()<br>Constructor that creates an empty stack of effects with default name. |
| [EffectStack](-effect-stack.md) | [jvm]<br>open fun [EffectStack](-effect-stack.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Default constructor. |

## Functions

| Name | Summary |
|---|---|
| [add](add.md) | [jvm]<br>open fun [add](add.md)(e: [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [addAll](add-all.md) | [jvm]<br>open fun [addAll](add-all.md)(c: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<out [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [changePriority](change-priority.md) | [jvm]<br>open fun [changePriority](change-priority.md)(effect: [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>, offset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>Changes the specified offset priority of the specified offset. |
| [clear](clear.md) | [jvm]<br>open fun [clear](clear.md)() |
| [computeDrawCommands](compute-draw-commands.md) | [jvm]<br>open fun <[T](compute-draw-commands.md)> [computeDrawCommands](compute-draw-commands.md)(environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-serializable-enum-property/index.md), [P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>): [Queue](https://docs.oracle.com/javase/8/docs/api/java/util/Queue.html)<[DrawCommand](../../it.unibo.alchemist.boundary.interfaces/-draw-command/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>><br>Computes a queue of commands to Draw something. |
| [contains](contains.md) | [jvm]<br>open fun [contains](contains.md)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [containsAll](contains-all.md) | [jvm]<br>open fun [containsAll](contains-all.md)(c: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [element](element.md) | [jvm]<br>open fun [element](element.md)(): [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)> |
| [equals](equals.md) | [jvm]<br>open fun [equals](equals.md)(obj: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372) | [jvm]<br>open fun [forEach](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-655675525%2FFunctions%2F-267951372)(action: [Consumer](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>) |
| [getTypeAdapter](get-type-adapter.md) | [jvm]<br>@NotNull()<br>open fun [getTypeAdapter](get-type-adapter.md)(): @NotNull()[EffectGroupAdapter](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)<br>Returns a com.google.gson.JsonSerializer and com.google.gson.JsonDeserializer combo class to be used as a {@code TypeAdapter} for this {@code EffectStack}. |
| [getVisibilityOf](get-visibility-of.md) | [jvm]<br>open fun [getVisibilityOf](get-visibility-of.md)(effect: [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns the visibility of the specified effect. |
| [hashCode](hash-code.md) | [jvm]<br>open fun [hashCode](hash-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isEmpty](is-empty.md) | [jvm]<br>open fun [isEmpty](is-empty.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isVisible](is-visible.md) | [jvm]<br>open fun [isVisible](is-visible.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Gets the visibility of the effect. |
| [iterator](iterator.md) | [jvm]<br>open fun [iterator](iterator.md)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>><br>abstract fun [iterator](../../it.unibo.alchemist.loader.variables/-arbitrary-variable/index.md#-1606146105%2FFunctions%2F-267951372)(): [Iterator](https://docs.oracle.com/javase/8/docs/api/java/util/Iterator.html)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-serializable-enum-property/index.md)> |
| [offer](offer.md) | [jvm]<br>open fun [offer](offer.md)(e: [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [parallelStream](../-effect-group/index.md#-708921786%2FFunctions%2F-267951372) | [jvm]<br>open fun [parallelStream](../-effect-group/index.md#-708921786%2FFunctions%2F-267951372)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[E](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html)> |
| [peek](peek.md) | [jvm]<br>open fun [peek](peek.md)(): [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)><br>Returns the effect with maximum priority, without removing it. |
| [poll](poll.md) | [jvm]<br>open fun [poll](poll.md)(): [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)> |
| [pop](pop.md) | [jvm]<br>open fun [pop](pop.md)(): [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)><br>Removes the effect with maximum priority and returns it. |
| [push](push.md) | [jvm]<br>open fun [push](push.md)(effect: [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>): [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)><br>Puts the effects in the group, giving it the maximum priority. |
| [remove](remove.md) | [jvm]<br>open fun [remove](remove.md)(): [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)><br>open fun [remove](remove.md)(o: [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeAll](remove-all.md) | [jvm]<br>open fun [removeAll](remove-all.md)(c: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [removeIf](../-effect-group/index.md#1420767036%2FFunctions%2F-267951372) | [jvm]<br>open fun [removeIf](../-effect-group/index.md#1420767036%2FFunctions%2F-267951372)(filter: [Predicate](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [retainAll](retain-all.md) | [jvm]<br>open fun [retainAll](retain-all.md)(c: [Collection](https://docs.oracle.com/javase/8/docs/api/java/util/Collection.html)<out [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [search](search.md) | [jvm]<br>open fun [search](search.md)(effect: [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Checks if an effect is present in the group. |
| [setName](../-effect-f-x/set-name.md) | [jvm]<br>abstract fun [setName](../-effect-f-x/set-name.md)(name: [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html))<br>Sets the name of the effect. |
| [setVisibility](../-effect-f-x/set-visibility.md) | [jvm]<br>abstract fun [setVisibility](../-effect-f-x/set-visibility.md)(visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets the visibility of the effect. |
| [setVisibilityOf](set-visibility-of.md) | [jvm]<br>open fun [setVisibilityOf](set-visibility-of.md)(effect: [EffectFX](../-effect-f-x/index.md)<[P](../../it.unibo.alchemist.boundary.gui.effects.json/-effect-group-adapter/index.md)>, visibility: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>Sets the visibility of the specified effect. |
| [size](size.md) | [jvm]<br>open fun [size](size.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372) | [jvm]<br>open fun [spliterator](../../it.unibo.alchemist.expressions.implementations/-list-tree-node/index.md#-677603448%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-serializable-enum-property/index.md)><br>open fun [spliterator](../-effect-group/index.md#485701680%2FFunctions%2F-267951372)(): [Spliterator](https://docs.oracle.com/javase/8/docs/api/java/util/Spliterator.html)<[E](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html)> |
| [stream](../-effect-group/index.md#-1977615027%2FFunctions%2F-267951372) | [jvm]<br>open fun [stream](../-effect-group/index.md#-1977615027%2FFunctions%2F-267951372)(): [Stream](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html)<[E](https://docs.oracle.com/javase/8/docs/api/java/lang/Enum.html)> |
| [toArray](to-array.md) | [jvm]<br>@NotNull()<br>open fun [toArray](to-array.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)><br>@NotNull()<br>open fun <[T](to-array.md)> [toArray](to-array.md)(a: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-serializable-enum-property/index.md)>): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[T](../../it.unibo.alchemist.boundary.gui.view.properties/-serializable-enum-property/index.md)> |

## Properties

| Name | Summary |
|---|---|
| [name](name.md) | [jvm]<br>private open var [name](name.md): [String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html) |
| [visibility](visibility.md) | [jvm]<br>private open var [visibility](visibility.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
