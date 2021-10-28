//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.interfaces](../index.md)/[ViewPort](index.md)

# ViewPort

[jvm]\
interface [ViewPort](index.md)

This interface implements an Adapter pattern between a generic view element and the needs of a [Wormhole2D](../-wormhole2-d/index.md).

## Functions

| Name | Summary |
|---|---|
| [getHeight](get-height.md) | [jvm]<br>abstract fun [getHeight](get-height.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Getter method for the height of the adapted view. |
| [getWidth](get-width.md) | [jvm]<br>abstract fun [getWidth](get-width.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Getter method for the width of the adapted view. |

## Inheritors

| Name |
|---|
| [NodeViewPort](../../it.unibo.alchemist.wormhole.implementation.adapter/-node-view-port/index.md) |
| [ComponentViewPort](../../it.unibo.alchemist.boundary.wormhole.implementation.adapter/-component-view-port/index.md) |
