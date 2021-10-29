---
title: getInstance
---
//[alchemist](../../../../index.html)/[it.unibo.alchemist.model.interfaces.geometry](../../index.html)/[GeometricShapeFactory](../index.html)/[Companion](index.html)/[getInstance](get-instance.html)



# getInstance



[jvm]\
inline fun <[S](get-instance.html) : [Vector](../../-vector/index.html)<[S](get-instance.html)>, [A](get-instance.html) : [GeometricTransformation](../../-geometric-transformation/index.html)<[S](get-instance.html)>, [F](get-instance.html) : [GeometricShapeFactory](../index.html)<[S](get-instance.html), [A](get-instance.html)>> [getInstance](get-instance.html)(): [F](get-instance.html)



Retrieves a factory of [GeometricShape](../../-geometric-shape/index.html) compatible with the given vector type.



#### Return



the factory



## Parameters


jvm

| | |
|---|---|
|  | <F> The interface of the factory requested |





[jvm]\




@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()



fun <[S](get-instance.html) : [Vector](../../-vector/index.html)<[S](get-instance.html)>, [A](get-instance.html) : [GeometricTransformation](../../-geometric-transformation/index.html)<[S](get-instance.html)>, [F](get-instance.html) : [GeometricShapeFactory](../index.html)<[S](get-instance.html), [A](get-instance.html)>> [getInstance](get-instance.html)(type: [Class](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)<[F](get-instance.html)>): [F](get-instance.html)



Retrieves a factory of [GeometricShape](../../-geometric-shape/index.html) compatible with the given space. (This method is meant for compatibility with java).



#### Return



the factory



## Parameters


jvm

| | |
|---|---|
|  | <F> The interface of the factory requested |
| type | The interface of the factory requested |




