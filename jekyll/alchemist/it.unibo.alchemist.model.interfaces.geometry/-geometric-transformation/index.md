---
title: GeometricTransformation
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry](../index.html)/[GeometricTransformation](index.html)



# GeometricTransformation



[jvm]\
interface [GeometricTransformation](index.html)<[S](index.html) : [Vector](../-vector/index.html)<[S](index.html)>>

Defines a generic transformation of a generic shape. The operations allowed depend on the space the shape belongs to. This interface is meant to be extended.



## Functions


| Name | Summary |
|---|---|
| [origin](origin.html) | [jvm]<br>abstract fun [origin](origin.html)(position: [S](index.html))<br>Performs an absolute translation to the provided position. |


## Inheritors


| Name |
|---|
| [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.html) |

