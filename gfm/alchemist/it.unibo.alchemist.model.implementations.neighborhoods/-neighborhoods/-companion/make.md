//[alchemist](../../../../index.md)/[it.unibo.alchemist.model.implementations.neighborhoods](../../index.md)/[Neighborhoods](../index.md)/[Companion](index.md)/[make](make.md)

# make

[jvm]\

@[JvmStatic](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-static/index.html)()

@[JvmOverloads](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.jvm/-jvm-overloads/index.html)()

fun <[T](make.md), [P](make.md) : [Position](../../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](make.md)>> [make](make.md)(env: [Environment](../../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](make.md), [P](make.md)>, center: [Node](../../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](make.md)>, neighbors: [Iterable](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-iterable/index.html)<[Node](../../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](make.md)>> = emptyList()): [SimpleNeighborhood](../../-simple-neighborhood/index.md)<[T](make.md), [P](make.md)>

Creates a [SimpleNeighborhood](../../-simple-neighborhood/index.md).

#### Return

The newly created [SimpleNeighborhood](../../-simple-neighborhood/index.md).

## Parameters

jvm

| | |
|---|---|
| env | The environment of the neighborhood. |
| center | The center of the neighborhood. |
| neighbors | The neighbors in the neighborhood, defaults to empty. |
