//[alchemist](../../index.md)/[it.unibo.alchemist.model](index.md)

# Package it.unibo.alchemist.model

## Types

| Name | Summary |
|---|---|
| [BiochemistryIncarnation](-biochemistry-incarnation/index.md) | [jvm]<br>class [BiochemistryIncarnation](-biochemistry-incarnation/index.md)<[P](-biochemistry-incarnation/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)>?, [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md)<[P](../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)>?> : [Incarnation](../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[Double](https://docs.oracle.com/javase/8/docs/api/java/lang/Double.html), [P](../it.unibo.alchemist.model.implementations.layers/-biomol-gradient-layer/index.md)> <br>position type, must be a [Vector](../it.unibo.alchemist.model.interfaces.geometry/-vector/index.md) |
| [ProtelisIncarnation](-protelis-incarnation/index.md) | [jvm]<br>class [ProtelisIncarnation](-protelis-incarnation/index.md)<[P](-protelis-incarnation/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<[P](-protelis-incarnation/index.md)>?> : [Incarnation](../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html), [P](-protelis-incarnation/index.md)> <br>position type |
| [SAPEREIncarnation](-s-a-p-e-r-e-incarnation/index.md) | [jvm]<br>class [SAPEREIncarnation](-s-a-p-e-r-e-incarnation/index.md)<[P](-s-a-p-e-r-e-incarnation/index.md) : [Position](../it.unibo.alchemist.model.interfaces/-position/index.md)<out [P](../it.unibo.alchemist.model.implementations.reactions/-s-a-p-e-r-e-gradient/index.md)>?> : [Incarnation](../it.unibo.alchemist.model.interfaces/-incarnation/index.md)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[ILsaMolecule](../it.unibo.alchemist.model.interfaces/-i-lsa-molecule/index.md)>, [P](../it.unibo.alchemist.model.implementations.reactions/-s-a-p-e-r-e-gradient/index.md)> , [Serializable](https://docs.oracle.com/javase/8/docs/api/java/io/Serializable.html)<br>position type |

## Functions

| Name | Summary |
|---|---|
| [minus](minus.md) | [jvm]<br>operator fun [Time](../it.unibo.alchemist.model.interfaces/-time/index.md).[minus](minus.md)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Time](../it.unibo.alchemist.model.interfaces/-time/index.md)<br>Minus operator for [Time](../it.unibo.alchemist.model.interfaces/-time/index.md) and [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html). |
| [plus](plus.md) | [jvm]<br>operator fun [Time](../it.unibo.alchemist.model.interfaces/-time/index.md).[plus](plus.md)(other: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Time](../it.unibo.alchemist.model.interfaces/-time/index.md)<br>Plus operator for [Time](../it.unibo.alchemist.model.interfaces/-time/index.md) and [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html). |
| [randomAngle](random-angle.md) | [jvm]<br>fun RandomGenerator.[randomAngle](random-angle.md)(): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>Generates a random value in 0..2π. |
