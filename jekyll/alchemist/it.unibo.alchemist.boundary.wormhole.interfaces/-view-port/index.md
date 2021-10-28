---
title: ViewPort
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.interfaces](../index.html)/[ViewPort](index.html)



# ViewPort



[jvm]\
interface [ViewPort](index.html)

This interface implements an Adapter pattern between a generic view element and the needs of a [Wormhole2D](../-wormhole2-d/index.html).



## Functions


| Name | Summary |
|---|---|
| [getHeight](get-height.html) | [jvm]<br>abstract fun [getHeight](get-height.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Getter method for the height of the adapted view. |
| [getWidth](get-width.html) | [jvm]<br>abstract fun [getWidth](get-width.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Getter method for the width of the adapted view. |


## Inheritors


| Name |
|---|
| [NodeViewPort](../../it.unibo.alchemist.wormhole.implementation.adapter/-node-view-port/index.html) |
| [ComponentViewPort](../../it.unibo.alchemist.boundary.wormhole.implementation.adapter/-component-view-port/index.html) |

