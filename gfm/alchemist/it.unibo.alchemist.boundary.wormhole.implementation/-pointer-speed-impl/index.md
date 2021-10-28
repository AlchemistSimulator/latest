//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.md)/[PointerSpeedImpl](index.md)

# PointerSpeedImpl

[jvm]\
class [PointerSpeedImpl](index.md) : [PointerSpeed](../../it.unibo.alchemist.boundary.wormhole.interfaces/-pointer-speed/index.md)

Implementation for [PointerSpeed](../../it.unibo.alchemist.boundary.wormhole.interfaces/-pointer-speed/index.md) interface.

## Functions

| Name | Summary |
|---|---|
| [getCurrentPosition](get-current-position.md) | [jvm]<br>open fun [getCurrentPosition](get-current-position.md)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Gets the pointer's current position. |
| [getVariation](get-variation.md) | [jvm]<br>open fun [getVariation](get-variation.md)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Gets the vector [current position - old position]. |
| [setCurrentPosition](set-current-position.md) | [jvm]<br>open fun [setCurrentPosition](set-current-position.md)(point: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>Sets the pointer's current position and, consequently, updates the old one. |

## Properties

| Name | Summary |
|---|---|
| [oldPosition](old-position.md) | [jvm]<br>private open val [oldPosition](old-position.md): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
