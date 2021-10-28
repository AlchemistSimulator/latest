//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.gui.layouts](../index.md)/[HorizontalFlowLayout](index.md)/[HorizontalFlowLayout](-horizontal-flow-layout.md)

# HorizontalFlowLayout

[jvm]\
open fun [HorizontalFlowLayout](-horizontal-flow-layout.md)(ordered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

Constructs an instance of VerticalLayout with a vertical vgap of 5 pixels, horizontal centering and anchored to the top of the display area.

## Parameters

jvm

| | |
|---|---|
| ordered | true if should be ordered |

[jvm]\
open fun [HorizontalFlowLayout](-horizontal-flow-layout.md)(hgap: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), ordered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

Constructs a VerticalLayout instance with horizontal centering, anchored to the top with the specified vgap.

## Parameters

jvm

| | |
|---|---|
| hgap | An int value indicating the vertical seperation of the components |
| ordered | true if the components must be ordered |

[jvm]\
open fun [HorizontalFlowLayout](-horizontal-flow-layout.md)(hgap: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), align: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), ordered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

Constructs a VerticalLayout instance anchored to the top with the specified hgap and horizontal alignment.

## Parameters

jvm

| | |
|---|---|
| hgap | An int value indicating the vertical seperation of the components |
| align | An int value which is one of RIGHT, LEFT, CENTER, BOTH for the horizontal getAlignment(). |
| ordered | true if the components must be ordered |

[jvm]\
open fun [HorizontalFlowLayout](-horizontal-flow-layout.md)(hgap: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), align: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), anchor: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), ordered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))

Constructs a VerticalLayout instance with the specified vgap, horizontal getAlignment() and anchoring.

## Parameters

jvm

| | |
|---|---|
| hgap | An int value indicating the vertical seperation of the components |
| align | An int value which is one of RIGHT, LEFT, CENTER, BOTH for the horizontal getAlignment(). |
| anchor | An int value which is one of TOP, BOTTOM, CENTER indicating where the components are to appear if the display area exceeds the minimum necessary. |
| ordered | true if the components must be ordered |
