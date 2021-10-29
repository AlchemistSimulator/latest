---
title: SelectionBox
---
//[alchemist](../../../../index.html)/[it.unibo.alchemist.boundary.interactions](../../index.html)/[SelectionHelper](../index.html)/[SelectionBox](index.html)



# SelectionBox



[jvm]\
class [SelectionBox](index.html)(**anchorPoint**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), **movingPoint**: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))

Allows basic multi-element box selections.



## Parameters


jvm

| | |
|---|---|
| anchorPoint | the starting and unchanging [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) of the selection |



## Constructors


| | |
|---|---|
| [SelectionBox](-selection-box.html) | [jvm]<br>fun [SelectionBox](-selection-box.html)(anchorPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) = Point(0, 0), movingPoint: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) = anchorPoint)<br>the starting and unchanging [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) of the selection |


## Functions


| Name | Summary |
|---|---|
| [close](close.html) | [jvm]<br>fun [close](close.html)()<br>Closes this SelectionBox. |
| [toString](to-string.html) | [jvm]<br>open override fun [toString](to-string.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |


## Properties


| Name | Summary |
|---|---|
| [anchorPoint](anchor-point.html) | [jvm]<br>val [anchorPoint](anchor-point.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>the starting and unchanging [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) of the selection |
| [closed](closed.html) | [jvm]<br>var [closed](closed.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false<br>Returns whether the SelectionBox has been closed. |
| [rectangle](rectangle.html) | [jvm]<br>val [rectangle](rectangle.html): Rectangle<br>The rectangle representing the box. |

