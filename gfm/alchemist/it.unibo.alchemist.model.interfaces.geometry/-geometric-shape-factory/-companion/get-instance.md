//[alchemist](../../../../index.md)/[it.unibo.alchemist.model.interfaces.geometry](../../index.md)/[GeometricShapeFactory](../index.md)/[Companion](index.md)/[getInstance](get-instance.md)

# getInstance

[jvm]\
inline fun <[S](get-instance.md) : [Vector](../../-vector/index.md)<[S](get-instance.md)>, [A](get-instance.md) : [GeometricTransformation](../../-geometric-transformation/index.md)<[S](get-instance.md)>, [F](get-instance.md) : [GeometricShapeFactory](../index.md)<[S](get-instance.md), [A](get-instance.md)>> [getInstance](get-instance.md)(): [F](get-instance.md)

Retrieves a factory of [GeometricShape](../../-geometric-shape/index.md) compatible with the given vector type.

#### Return

the factory

## Parameters

jvm

| | |
|---|---|
|  | <F> The interface of the factory requested |

[jvm]\

@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()

fun <[S](get-instance.md) : [Vector](../../-vector/index.md)<[S](get-instance.md)>, [A](get-instance.md) : [GeometricTransformation](../../-geometric-transformation/index.md)<[S](get-instance.md)>, [F](get-instance.md) : [GeometricShapeFactory](../index.md)<[S](get-instance.md), [A](get-instance.md)>> [getInstance](get-instance.md)(type: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[F](get-instance.md)>): [F](get-instance.md)

Retrieves a factory of [GeometricShape](../../-geometric-shape/index.md) compatible with the given space. (This method is meant for compatibility with java).

#### Return

the factory

## Parameters

jvm

| | |
|---|---|
|  | <F> The interface of the factory requested |
| type | The interface of the factory requested |
