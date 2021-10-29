---
title: PointerSpeed
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.boundary.wormhole.interfaces](../index.html)/[PointerSpeed](index.html)



# PointerSpeed



[jvm]\
interface [PointerSpeed](index.html)

Base type for any pointing device: it provides services to analyze the pointer's movement.



## Functions


| Name | Summary |
|---|---|
| [getCurrentPosition](get-current-position.html) | [jvm]<br>abstract fun [getCurrentPosition](get-current-position.html)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Gets the pointer's current position. |
| [getOldPosition](get-old-position.html) | [jvm]<br>abstract fun [getOldPosition](get-old-position.html)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Gets the pointer's old position. |
| [getVariation](get-variation.html) | [jvm]<br>abstract fun [getVariation](get-variation.html)(): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)<br>Gets the vector [current position - old position]. |
| [setCurrentPosition](set-current-position.html) | [jvm]<br>abstract fun [setCurrentPosition](set-current-position.html)(point: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>Sets the pointer's current position and, consequently, updates the old one. |


## Inheritors


| Name |
|---|
| [PointerSpeedImpl](../../it.unibo.alchemist.boundary.wormhole.implementation/-pointer-speed-impl/index.html) |

