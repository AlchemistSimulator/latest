//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.interactions](../index.md)/[SelectionHelper](index.md)

# SelectionHelper

[jvm]\
class [SelectionHelper](index.md)<[T](index.md), [P](index.md) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.md)<[P](index.md)>>

Manages multi-element selection and click-selection.

## Constructors

| | |
|---|---|
| [SelectionHelper](-selection-helper.md) | [jvm]<br>fun [SelectionHelper](-selection-helper.md)() |

## Types

| Name | Summary |
|---|---|
| [SelectionBox](-selection-box/index.md) | [jvm]<br>class [SelectionBox](-selection-box/index.md)(**anchorPoint**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), **movingPoint**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>Allows basic multi-element box selections. |

## Functions

| Name | Summary |
|---|---|
| [begin](begin.md) | [jvm]<br>fun [begin](begin.md)(point: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [SelectionHelper](index.md)<[T](index.md), [P](index.md)><br>Begins a new selection at the given point. |
| [boxSelection](box-selection.md) | [jvm]<br>fun [boxSelection](box-selection.md)(nodes: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, [P](index.md)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](index.md)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, [P](index.md)><br>Retrieves the elements selected by box selection, thus possibly empty. |
| [clickSelection](click-selection.md) | [jvm]<br>fun [clickSelection](click-selection.md)(nodes: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, [P](index.md)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.md)<[P](index.md)>): [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, [P](index.md)>?<br>Retrieves the element selected by clicking. |
| [close](close.md) | [jvm]<br>fun [close](close.md)()<br>Closes the selection. |
| [update](update.md) | [jvm]<br>fun [update](update.md)(point: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [SelectionHelper](index.md)<[T](index.md), [P](index.md)><br>Updates the selection with a new point. |

## Properties

| Name | Summary |
|---|---|
| [isBoxSelectionInProgress](is-box-selection-in-progress.md) | [jvm]<br>var [isBoxSelectionInProgress](is-box-selection-in-progress.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false<br>Returns whether a box selection is currently occurring. |
| [rectangle](rectangle.md) | [jvm]<br>val [rectangle](rectangle.md): Rectangle<br>The rectangle representing the box. |
