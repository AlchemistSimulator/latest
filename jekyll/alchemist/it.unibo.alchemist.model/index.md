---
title: it.unibo.alchemist.model
---
//[alchemist](../../index.html)/[it.unibo.alchemist.model](index.html)



# Package it.unibo.alchemist.model



## Types


| Name | Summary |
|---|---|
| [BiochemistryIncarnation](-biochemistry-incarnation/index.html) | [jvm]<br>class [BiochemistryIncarnation](-biochemistry-incarnation/index.html)<[P](-biochemistry-incarnation/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>?, [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html)<[P](../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)>?> : [Incarnation](../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.html)> <br>position type, must be a [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.html) |
| [ProtelisIncarnation](-protelis-incarnation/index.html) | [jvm]<br>class [ProtelisIncarnation](-protelis-incarnation/index.html)<[P](-protelis-incarnation/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<[P](../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)>?> : [Incarnation](../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](../it.unibo.alchemist.model.implementations.nodes/-protelis-node/index.html)> <br>position type |
| [SAPEREIncarnation](-s-a-p-e-r-e-incarnation/index.html) | [jvm]<br>class [SAPEREIncarnation](-s-a-p-e-r-e-incarnation/index.html)<[P](-s-a-p-e-r-e-incarnation/index.html) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.html)<out [P](../it.unibo.alchemist.model.implementations.actions/-lsa-ascending-gradient-dist/index.html)>?> : [Incarnation](../it.unibo.alchemist.model.interfaces/-incarnation/index.html)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.html)>, [P](../it.unibo.alchemist.model.implementations.actions/-lsa-ascending-gradient-dist/index.html)> , [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>position type |


## Functions


| Name | Summary |
|---|---|
| [minus](minus.html) | [jvm]<br>operator fun [Time](../it.unibo.alchemist.model.interfaces/-time/index.html).[minus](minus.html)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Time](../it.unibo.alchemist.model.interfaces/-time/index.html)<br>Minus operator for [Time](../it.unibo.alchemist.model.interfaces/-time/index.html) and [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html). |
| [plus](plus.html) | [jvm]<br>operator fun [Time](../it.unibo.alchemist.model.interfaces/-time/index.html).[plus](plus.html)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Time](../it.unibo.alchemist.model.interfaces/-time/index.html)<br>Plus operator for [Time](../it.unibo.alchemist.model.interfaces/-time/index.html) and [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html). |
| [randomAngle](random-angle.html) | [jvm]<br>fun RandomGenerator.[randomAngle](random-angle.html)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Generates a random value in 0..2π. |

