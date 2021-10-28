//[alchemist](../../../index.md)/[it.unibo.alchemist.protelis](../index.md)/[AlchemistExecutionContext](index.md)/[routingDistance](routing-distance.md)

# routingDistance

[jvm]\
open fun [routingDistance](routing-distance.md)(dest: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)>): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)

Computes the distance along a map. Requires a [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md).

#### Return

the distance on a map

## Parameters

jvm

| | |
|---|---|
| dest | the destination, in form of a destination node |

[jvm]\
open fun [routingDistance](routing-distance.md)(dest: [Number](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)

Computes the distance along a map. Requires a [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md).

#### Return

the distance on a map

## Parameters

jvm

| | |
|---|---|
| dest | the destination, in form of [ProtelisNode](../../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.md) ID. Non integer numbers will be cast to integers by [intValue](https://docs.oracle.com/javase/8/docs/api/java/lang/Number.html#intValue--). |

[jvm]\
open fun [routingDistance](routing-distance.md)(dest: [GeoPosition](../../it.unibo.alchemist.model.interfaces/-geo-position/index.md)): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)

Computes the distance along a map. Requires a [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md).

#### Return

the distance on a map

## Parameters

jvm

| | |
|---|---|
| dest | the destination |

[jvm]\
open fun [routingDistance](routing-distance.md)(dest: Tuple): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)

Computes the distance along a map. Requires a [MapEnvironment](../../it.unibo.alchemist.model.interfaces/-map-environment/index.md).

#### Return

the distance on a map

## Parameters

jvm

| | |
|---|---|
| dest | the destination, as a Tuple of two values: [latitude, longitude] |
