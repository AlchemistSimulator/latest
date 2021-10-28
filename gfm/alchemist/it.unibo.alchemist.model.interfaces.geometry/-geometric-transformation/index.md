//[alchemist](../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry](../index.md)/[GeometricTransformation](index.md)

# GeometricTransformation

[jvm]\
interface [GeometricTransformation](index.md)<[S](index.md) : [Vector](../-vector/index.md)<[S](index.md)>>

Defines a generic transformation of a generic shape. The operations allowed depend on the space the shape belongs to. This interface is meant to be extended.

## Functions

| Name | Summary |
|---|---|
| [origin](origin.md) | [jvm]<br>abstract fun [origin](origin.md)(position: [S](index.md))<br>Performs an absolute translation to the provided position. |

## Inheritors

| Name |
|---|
| [Euclidean2DTransformation](../../it.unibo.alchemist.model.interfaces.geometry.euclidean2d/-euclidean2-d-transformation/index.md) |
