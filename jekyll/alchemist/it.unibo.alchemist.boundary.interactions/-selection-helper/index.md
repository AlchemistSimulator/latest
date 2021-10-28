---
title: SelectionHelper
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interactions](../index.html)/[SelectionHelper](index.html)



# SelectionHelper



[jvm]\
class [SelectionHelper](index.html)<[T](index.html), [P](index.html) : [Position2D](../../it.unibo.alchemist.model.interfaces/-position2-d/index.html)<[P](index.html)>>

Manages multi-element selection and click-selection.



## Constructors


| | |
|---|---|
| [SelectionHelper](-selection-helper.html) | [jvm]<br>fun [SelectionHelper](-selection-helper.html)() |


## Types


| Name | Summary |
|---|---|
| [SelectionBox](-selection-box/index.html) | [jvm]<br>class [SelectionBox](-selection-box/index.html)(**anchorPoint**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), **movingPoint**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>Allows basic multi-element box selections. |


## Functions


| Name | Summary |
|---|---|
| [begin](begin.html) | [jvm]<br>fun [begin](begin.html)(point: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [SelectionHelper](index.html)<[T](index.html), [P](index.html)><br>Begins a new selection at the given point. |
| [boxSelection](box-selection.html) | [jvm]<br>fun [boxSelection](box-selection.html)(nodes: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, [P](index.html)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](index.html)>): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, [P](index.html)><br>Retrieves the elements selected by box selection, thus possibly empty. |
| [clickSelection](click-selection.html) | [jvm]<br>fun [clickSelection](click-selection.html)(nodes: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, [P](index.html)>, wormhole: [Wormhole2D](../../it.unibo.alchemist.boundary.wormhole.interfaces/-wormhole2-d/index.html)<[P](index.html)>): [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, [P](index.html)>?<br>Retrieves the element selected by clicking. |
| [close](close.html) | [jvm]<br>fun [close](close.html)()<br>Closes the selection. |
| [update](update.html) | [jvm]<br>fun [update](update.html)(point: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [SelectionHelper](index.html)<[T](index.html), [P](index.html)><br>Updates the selection with a new point. |


## Properties


| Name | Summary |
|---|---|
| [isBoxSelectionInProgress](is-box-selection-in-progress.html) | [jvm]<br>var [isBoxSelectionInProgress](is-box-selection-in-progress.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false<br>Returns whether a box selection is currently occurring. |
| [rectangle](rectangle.html) | [jvm]<br>val [rectangle](rectangle.html): Rectangle<br>The rectangle representing the box. |

