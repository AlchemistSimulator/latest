---
title: Direction2D
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.interactions](../index.html)/[Direction2D](index.html)



# Direction2D



[jvm]\
enum [Direction2D](index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Direction2D](index.html)> 

Cardinal and intercardinal directions indicating a movement.



## Parameters


jvm

| | |
|---|---|
| x | the X-value. Grows positively towards the "right". |
| y | the Y-value. Grows positively upwards. |



## Entries


| | |
|---|---|
| [NORTHWEST](-n-o-r-t-h-w-e-s-t/index.html) | [jvm]<br>[NORTHWEST](-n-o-r-t-h-w-e-s-t/index.html)(-1, 1) |
| [SOUTHWEST](-s-o-u-t-h-w-e-s-t/index.html) | [jvm]<br>[SOUTHWEST](-s-o-u-t-h-w-e-s-t/index.html)(-1, -1) |
| [SOUTHEAST](-s-o-u-t-h-e-a-s-t/index.html) | [jvm]<br>[SOUTHEAST](-s-o-u-t-h-e-a-s-t/index.html)(1, -1) |
| [NORTHEAST](-n-o-r-t-h-e-a-s-t/index.html) | [jvm]<br>[NORTHEAST](-n-o-r-t-h-e-a-s-t/index.html)(1, 1) |
| [WEST](-w-e-s-t/index.html) | [jvm]<br>[WEST](-w-e-s-t/index.html)(-1, 0) |
| [EAST](-e-a-s-t/index.html) | [jvm]<br>[EAST](-e-a-s-t/index.html)(1, 0) |
| [SOUTH](-s-o-u-t-h/index.html) | [jvm]<br>[SOUTH](-s-o-u-t-h/index.html)(0, -1) |
| [NORTH](-n-o-r-t-h/index.html) | [jvm]<br>[NORTH](-n-o-r-t-h/index.html)(0, 1) |
| [NONE](-n-o-n-e/index.html) | [jvm]<br>[NONE](-n-o-n-e/index.html)(0, 0) |


## Functions


| Name | Summary |
|---|---|
| [contains](contains.html) | [jvm]<br>operator fun [contains](contains.html)(other: [Direction2D](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns whether this direction contains [other](contains.html). |
| [minus](minus.html) | [jvm]<br>operator fun [minus](minus.html)(other: [Direction2D](index.html)): [Direction2D](index.html)<br>Subtracts with a direction. |
| [plus](plus.html) | [jvm]<br>operator fun [plus](plus.html)(other: [Direction2D](index.html)): [Direction2D](index.html)<br>Sums with a direction. |
| [times](times.html) | [jvm]<br>operator fun [times](times.html)(scalar: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Multiplies by a scalar. |


## Properties


| Name | Summary |
|---|---|
| [flipped](flipped.html) | [jvm]<br>val [flipped](flipped.html): [Direction2D](index.html)<br>Flips the direction horizontally and vertically. |
| [flippedX](flipped-x.html) | [jvm]<br>val [flippedX](flipped-x.html): [Direction2D](index.html)<br>Flips the direction's X-values. |
| [flippedY](flipped-y.html) | [jvm]<br>val [flippedY](flipped-y.html): [Direction2D](index.html)<br>Flips the direction's Y-values. |
| [name](index.html#1420971322%2FProperties%2F-134779887) | [jvm]<br>val [name](index.html#1420971322%2FProperties%2F-134779887): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ordinal](index.html#433313732%2FProperties%2F-134779887) | [jvm]<br>val [ordinal](index.html#433313732%2FProperties%2F-134779887): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [x](x.html) | [jvm]<br>val [x](x.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the X-value. |
| [y](y.html) | [jvm]<br>val [y](y.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the Y-value. |

