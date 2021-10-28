---
title: ConnectToAccessPoint
---
//[alchemist](../../../index.html)/[it.unibo.alchemist.model.implementations.linkingrules](../index.html)/[ConnectToAccessPoint](index.html)



# ConnectToAccessPoint



[jvm]\
class [ConnectToAccessPoint](index.html)<[T](index.html), [P](index.html) : [Position](../../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](index.html)>>(**radius**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **accessPointId**: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)) : [ConnectWithinDistance](../-connect-within-distance/index.html)<[T](index.html), [P](index.html)>



## Parameters


jvm

| | |
|---|---|
| accessPointId | the id of the access point. |



## Constructors


| | |
|---|---|
| [ConnectToAccessPoint](-connect-to-access-point.html) | [jvm]<br>fun [ConnectToAccessPoint](-connect-to-access-point.html)(radius: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), accessPointId: [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html))<br>the id of the access point. |


## Functions


| Name | Summary |
|---|---|
| [computeNeighborhood](compute-neighborhood.html) | [jvm]<br>open override fun [computeNeighborhood](compute-neighborhood.html)(center: [Node](../../it.unibo.alchemist.model.interfaces/-node/index.html)<[T](index.html)>, environment: [Environment](../../it.unibo.alchemist.model.interfaces/-environment/index.html)<[T](index.html), [P](index.html)>): [Neighborhood](../../it.unibo.alchemist.model.interfaces/-neighborhood/index.html)<[T](index.html)><br>Subclasses may change the way a neighborhood is computed. |
| [getRange](../-connect-via-access-point/index.html#197962739%2FFunctions%2F-134779887) | [jvm]<br>fun [getRange](../-connect-via-access-point/index.html#197962739%2FFunctions%2F-134779887)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html) | [jvm]<br>override fun [isLocallyConsistent](../-abstract-locally-consistent-linking-rule/is-locally-consistent.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Properties


| Name | Summary |
|---|---|
| [accessPointId](access-point-id.html) | [jvm]<br>val [accessPointId](access-point-id.html): [Molecule](../../it.unibo.alchemist.model.interfaces/-molecule/index.html)<br>the id of the access point. |

