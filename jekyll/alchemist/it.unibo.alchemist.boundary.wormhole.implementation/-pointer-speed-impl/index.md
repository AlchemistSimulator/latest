---
title: PointerSpeedImpl
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.implementation](../index.html)/[PointerSpeedImpl](index.html)



# PointerSpeedImpl



[jvm]\
class [PointerSpeedImpl](index.html) : [PointerSpeed](../../it.unibo.alchemist.boundary.wormhole.interfaces/-pointer-speed/index.html)

Implementation for [PointerSpeed](../../it.unibo.alchemist.boundary.wormhole.interfaces/-pointer-speed/index.html) interface.



## Functions


| Name | Summary |
|---|---|
| [getCurrentPosition](get-current-position.html) | [jvm]<br>open fun [getCurrentPosition](get-current-position.html)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Gets the pointer's current position. |
| [getVariation](get-variation.html) | [jvm]<br>open fun [getVariation](get-variation.html)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Gets the vector [current position - old position]. |
| [setCurrentPosition](set-current-position.html) | [jvm]<br>open fun [setCurrentPosition](set-current-position.html)(point: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>Sets the pointer's current position and, consequently, updates the old one. |


## Properties


| Name | Summary |
|---|---|
| [oldPosition](old-position.html) | [jvm]<br>private open val [oldPosition](old-position.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |

