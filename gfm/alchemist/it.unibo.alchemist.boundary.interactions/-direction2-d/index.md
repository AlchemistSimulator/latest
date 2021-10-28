//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.interactions](../index.md)/[Direction2D](index.md)

# Direction2D

[jvm]\
enum [Direction2D](index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Direction2D](index.md)> 

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
| [NORTHWEST](-n-o-r-t-h-w-e-s-t/index.md) | [jvm]<br>[NORTHWEST](-n-o-r-t-h-w-e-s-t/index.md)(-1, 1) |
| [SOUTHWEST](-s-o-u-t-h-w-e-s-t/index.md) | [jvm]<br>[SOUTHWEST](-s-o-u-t-h-w-e-s-t/index.md)(-1, -1) |
| [SOUTHEAST](-s-o-u-t-h-e-a-s-t/index.md) | [jvm]<br>[SOUTHEAST](-s-o-u-t-h-e-a-s-t/index.md)(1, -1) |
| [NORTHEAST](-n-o-r-t-h-e-a-s-t/index.md) | [jvm]<br>[NORTHEAST](-n-o-r-t-h-e-a-s-t/index.md)(1, 1) |
| [WEST](-w-e-s-t/index.md) | [jvm]<br>[WEST](-w-e-s-t/index.md)(-1, 0) |
| [EAST](-e-a-s-t/index.md) | [jvm]<br>[EAST](-e-a-s-t/index.md)(1, 0) |
| [SOUTH](-s-o-u-t-h/index.md) | [jvm]<br>[SOUTH](-s-o-u-t-h/index.md)(0, -1) |
| [NORTH](-n-o-r-t-h/index.md) | [jvm]<br>[NORTH](-n-o-r-t-h/index.md)(0, 1) |
| [NONE](-n-o-n-e/index.md) | [jvm]<br>[NONE](-n-o-n-e/index.md)(0, 0) |

## Functions

| Name | Summary |
|---|---|
| [contains](contains.md) | [jvm]<br>operator fun [contains](contains.md)(other: [Direction2D](index.md)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Returns whether this direction contains [other](contains.md). |
| [minus](minus.md) | [jvm]<br>operator fun [minus](minus.md)(other: [Direction2D](index.md)): [Direction2D](index.md)<br>Subtracts with a direction. |
| [plus](plus.md) | [jvm]<br>operator fun [plus](plus.md)(other: [Direction2D](index.md)): [Direction2D](index.md)<br>Sums with a direction. |
| [times](times.md) | [jvm]<br>operator fun [times](times.md)(scalar: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Multiplies by a scalar. |

## Properties

| Name | Summary |
|---|---|
| [flipped](flipped.md) | [jvm]<br>val [flipped](flipped.md): [Direction2D](index.md)<br>Flips the direction horizontally and vertically. |
| [flippedX](flipped-x.md) | [jvm]<br>val [flippedX](flipped-x.md): [Direction2D](index.md)<br>Flips the direction's X-values. |
| [flippedY](flipped-y.md) | [jvm]<br>val [flippedY](flipped-y.md): [Direction2D](index.md)<br>Flips the direction's Y-values. |
| [name](index.md#1420971322%2FProperties%2F-267951372) | [jvm]<br>val [name](index.md#1420971322%2FProperties%2F-267951372): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ordinal](index.md#433313732%2FProperties%2F-267951372) | [jvm]<br>val [ordinal](index.md#433313732%2FProperties%2F-267951372): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [x](x.md) | [jvm]<br>val [x](x.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the X-value. |
| [y](y.md) | [jvm]<br>val [y](y.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>the Y-value. |
