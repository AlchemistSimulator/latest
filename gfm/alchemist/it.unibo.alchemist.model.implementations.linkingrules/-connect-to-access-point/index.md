//[alchemist](../../../index.md)/[it.unibo.alchemist.model.implementations.linkingrules](../index.md)/[ConnectToAccessPoint](index.md)

# ConnectToAccessPoint

[jvm]\
class [ConnectToAccessPoint](index.md)<[T](index.md), [P](index.md) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](index.md)>>(**radius**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **accessPointId**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)) : [ConnectWithinDistance](../-connect-within-distance/index.md)<[T](index.md), [P](index.md)>

## Parameters

jvm

| | |
|---|---|
| accessPointId | the id of the access point. |

## Constructors

| | |
|---|---|
| [ConnectToAccessPoint](-connect-to-access-point.md) | [jvm]<br>fun [ConnectToAccessPoint](-connect-to-access-point.md)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), accessPointId: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md))<br>the id of the access point. |

## Functions

| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.md) | [jvm]<br>open override fun [computeNeighborhood](compute-neighborhood.md)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.md)<[T](index.md)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.md)<[T](index.md), [P](index.md)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.md)<[T](index.md)><br>Subclasses may change the way a neighborhood is computed. |
| [getRange](../-connect-via-access-point/index.md#197962739%2FFunctions%2F-267951372) | [jvm]<br>fun [getRange](../-connect-via-access-point/index.md#197962739%2FFunctions%2F-267951372)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.md) | [jvm]<br>override fun [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

## Properties

| Name | Summary |
|---|---|
| [accessPointId](access-point-id.md) | [jvm]<br>val [accessPointId](access-point-id.md): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.md)<br>the id of the access point. |
