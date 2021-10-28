//[alchemist](../../../../index.md)/[it.unibo.alchemist.boundary.interactions](../../index.md)/[SelectionHelper](../index.md)/[SelectionBox](index.md)

# SelectionBox

[jvm]\
class [SelectionBox](index.md)(**anchorPoint**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), **movingPoint**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))

Allows basic multi-element box selections.

## Parameters

jvm

| | |
|---|---|
| anchorPoint | the starting and unchanging [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) of the selection |

## Constructors

| | |
|---|---|
| [SelectionBox](-selection-box.md) | [jvm]<br>fun [SelectionBox](-selection-box.md)(anchorPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) = Point(0, 0), movingPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) = anchorPoint)<br>the starting and unchanging [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) of the selection |

## Functions

| Name | Summary |
|---|---|
| [close](close.md) | [jvm]<br>fun [close](close.md)()<br>Closes this SelectionBox. |
| [toString](to-string.md) | [jvm]<br>open override fun [toString](to-string.md)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

## Properties

| Name | Summary |
|---|---|
| [anchorPoint](anchor-point.md) | [jvm]<br>val [anchorPoint](anchor-point.md): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>the starting and unchanging [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) of the selection |
| [closed](closed.md) | [jvm]<br>var [closed](closed.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false<br>Returns whether the SelectionBox has been closed. |
| [rectangle](rectangle.md) | [jvm]<br>val [rectangle](rectangle.md): Rectangle<br>The rectangle representing the box. |
