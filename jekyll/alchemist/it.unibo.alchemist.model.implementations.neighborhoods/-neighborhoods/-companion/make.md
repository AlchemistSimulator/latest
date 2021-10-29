---
title: make
---
//[alchemist](../../../../index.html)/[it.unibo.alchemist.model.implementations.neighborhoods](../../index.html)/[Neighborhoods](../index.html)/[Companion](index.html)/[make](make.html)



# make



[jvm]\




@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()



@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()



fun <[T](make.html), [P](make.html) : [Position](../../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](make.html)>> [make](make.html)(env: [Environment](../../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](make.html), [P](make.html)>, center: [Node](../../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](make.html)>, neighbors: [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)<[Node](../../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](make.html)>> = emptyList()): [SimpleNeighborhood](../../-simple-neighborhood/index.html)<[T](make.html), [P](make.html)>



Creates a [SimpleNeighborhood](../../-simple-neighborhood/index.html).



#### Return



The newly created [SimpleNeighborhood](../../-simple-neighborhood/index.html).



## Parameters


jvm

| | |
|---|---|
| env | The environment of the neighborhood. |
| center | The center of the neighborhood. |
| neighbors | The neighbors in the neighborhood, defaults to empty. |




