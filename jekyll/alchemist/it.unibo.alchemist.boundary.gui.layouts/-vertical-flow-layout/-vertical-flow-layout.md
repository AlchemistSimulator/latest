---
title: VerticalFlowLayout
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.gui.layouts](../index.html)/[VerticalFlowLayout](index.html)/[VerticalFlowLayout](-vertical-flow-layout.html)



# VerticalFlowLayout



[jvm]\
open fun [VerticalFlowLayout](-vertical-flow-layout.html)(ordered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))



Constructs an instance of VerticalLayout with a vertical vgap of 5 pixels, horizontal centering and anchored to the top of the display area.



## Parameters


jvm

| | |
|---|---|
| ordered | true if the components must be ordered |





[jvm]\
open fun [VerticalFlowLayout](-vertical-flow-layout.html)(vgap: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), ordered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))



Constructs a VerticalLayout instance with horizontal centering, anchored to the top with the specified vgap.



## Parameters


jvm

| | |
|---|---|
| vgap | An int value indicating the vertical seperation of the components |
| ordered | true if the components must be ordered |





[jvm]\
open fun [VerticalFlowLayout](-vertical-flow-layout.html)(vgap: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), alignment: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), ordered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))



Constructs a VerticalLayout instance anchored to the top with the specified vgap and horizontal alignment.



## Parameters


jvm

| | |
|---|---|
| vgap | An int value indicating the vertical seperation of the components |
| alignment | An int value which is one of RIGHT, LEFT, CENTER, BOTH for the horizontal alignment. |
| ordered | true if the components must be ordered |





[jvm]\
open fun [VerticalFlowLayout](-vertical-flow-layout.html)(vgap: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), alignment: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), anchor: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), ordered: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))



Constructs a VerticalLayout instance with the specified vgap, horizontal alignment and anchoring.



## Parameters


jvm

| | |
|---|---|
| vgap | An int value indicating the vertical seperation of the components |
| alignment | An int value which is one of RIGHT, LEFT, CENTER, BOTH for the horizontal alignment. |
| anchor | An int value which is one of TOP, BOTTOM, CENTERindicating where the components are to appear if the display area exceeds the minimum necessary. |
| ordered | true if the components must be ordered |




