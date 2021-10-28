//[alchemist](../../../index.md)/[it.unibo.alchemist.boundary.wormhole.interfaces](../index.md)/[PointerSpeed](index.md)

# PointerSpeed

[jvm]\
interface [PointerSpeed](index.md)

Base type for any pointing device: it provides services to analyze the pointer's movement.

## Functions

| Name | Summary |
|---|---|
| [getCurrentPosition](get-current-position.md) | [jvm]<br>abstract fun [getCurrentPosition](get-current-position.md)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Gets the pointer's current position. |
| [getOldPosition](get-old-position.md) | [jvm]<br>abstract fun [getOldPosition](get-old-position.md)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Gets the pointer's old position. |
| [getVariation](get-variation.md) | [jvm]<br>abstract fun [getVariation](get-variation.md)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Gets the vector [current position - old position]. |
| [setCurrentPosition](set-current-position.md) | [jvm]<br>abstract fun [setCurrentPosition](set-current-position.md)(point: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>Sets the pointer's current position and, consequently, updates the old one. |

## Inheritors

| Name |
|---|
| [PointerSpeedImpl](../../it.unibo.alchemist.boundary.wormhole.implementation/-pointer-speed-impl/index.md) |
